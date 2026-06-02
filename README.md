# Movement Graph

A knowledge graph mapping the grassroots, small-d democratic movement working to make AI broadly beneficial.

Part of the [Make AI Good](https://github.com/Make-AI-Good) project.

> **Status: `v1.0.0`** — the first release the team stands behind for consumers. Publicly available under CC BY 4.0. See [What `v1.0.0` guarantees](#what-v100-guarantees) and [Known gaps](#known-gaps) below before building on it.

## What this is

A versioned corpus of entities — organizations, campaigns, people, publications, messages, funders, events — that together describe the on-the-ground movement shaping how AI gets built, deployed, and held accountable. The focus is the **grassroots and small-d democratic layer**: local groups, organizers, advocacy organizations doing grassroots work, coalitions, campaigns, cultural artifacts (slogans, framings, manifestos), and the voices propagating them.

Labs, think tanks, and institutional policy organizations are out of scope unless they intersect meaningfully with grassroots organizing. Oppositional movements (acceleration, e/acc) are out of scope.

The graph is built **broad-first**: a wide, diverse cross-section of in-scope entities — each one complete and well-linked — before any niche is filled out in depth. Coverage is intentionally uneven at this stage; flagging gaps and inaccuracies is welcomed (see [Issues and feedback](#issues-and-feedback) below).

## Schema

The schema is authoritative in [`schema/spec.md`](schema/spec.md). Start there if you're consuming the graph programmatically — it defines the ten entity types, the frontmatter fields for each, ID conventions, cross-reference rules, and sourcing requirements.

## Repository structure

```
entities/        the graph itself, one markdown file per entity
  organizations/
  local-groups/
  campaigns/
  events/
  strategies/
  messages/
  funders/
  persons/
  voices/
  publications/
audits/          per-entity fact-check trails (see "Audits" below)
schema/
  spec.md            schema definition
  vocabularies/      emergent tag vocabularies, grown from observed usage
README.md
LICENSE
```

## Entity files

Each entity is a single markdown file with YAML frontmatter and a markdown body.

- **Frontmatter** carries structured fields: `id`, `type`, `name`, `status`, `confidence`, `sources`, plus type-specific fields (an Organization has `founded`, `location`, `funders[]`, `key_people[]`; a Person has `affiliations[]`, `public_profiles[]`; and so on).
- **Body** is markdown prose, typically a few paragraphs, with inline source links for non-obvious factual claims.

## Audits

Each entity in this corpus is fact-checked by a dedicated auditor role that compares body factual claims against canonical sources (the entity's own cited sources first, then independent primary documents and mainstream news outlets; Wikipedia per a type-based canonicality rule). The result is a per-entity audit file at `audits/<entity-id>.md`.

Each audit file has YAML frontmatter — `entity_id`, `entity_hash` (the git hash of the entity file at audit time), `audit_date`, `pass`, `status`, claim counts, and the list of sources consulted — followed by a per-claim breakdown showing the body quote, source URL, source content, comparison reasoning, and decision.

Per-claim decisions are one of:

- **`verified`** — body claim matches source content within paraphrase tolerance.
- **`discrepancy`** — body claim contradicts source content. Specific and citable.
- **`unverifiable`** — source dead, sources contradict each other, claim too paraphrastic for specific comparison, no canonical source exists for this class of claim, or a judgment-loaded edge.

The entity's overall `status` in the audit frontmatter is the most-severe per-claim outcome (`discrepancy` ⟶ `unverifiable` ⟶ `verified`).

**Re-audit cadence is hash-based.** Audits become stale when their entity file changes (`entity_hash` no longer matches the current git hash); the auditor's next session re-audits the oldest stale entity. So a `status: verified` audit is current only against the specific commit named in `entity_hash` — fresh audits are produced as the corpus evolves.

If you build something downstream that surfaces entity claims to readers, the audit file is the verification trail you can point them to. `unverifiable` is not a failure — it names where audit reaches its limits, and is itself useful provenance.

## Cross-references

References between entities are **ID strings inside frontmatter fields**. For example, the Organization `org-foxglove` listing the Ford Foundation as a funder appears as `funders: [fund-ford-foundation]` in `entities/organizations/org-foxglove.md`.

The schema defines **canonical directions** for each cross-reference relationship — references are stored on one side and the reverse link is inferred at build time, not duplicated on both sides. A small number of symmetric relationships are stored on both. See `schema/spec.md § Canonical cross-reference direction` for the full table.

Body prose also uses relative markdown links between entities, e.g. `[Daniel Motaung](../persons/person-daniel-motaung.md)`.

## Consuming the graph

The corpus is plain markdown + YAML; no build step is required to read it. To consume programmatically:

1. Walk `entities/<type>/*.md`.
2. Parse the YAML frontmatter (standard YAML — any frontmatter-aware markdown parser works).
3. The frontmatter is the structured layer; the body is the narrative layer.
4. Use `id` as the canonical identifier; `name` is the display string.

If you need a flat JSON or database representation, deriving one from the entity files is straightforward given the small schema. A canonical build script may be published later if downstream demand surfaces.

## How this is built

This graph is built by a small AI agent team with human oversight. Roles include researchers who draft entities, an editor that performs mechanical schema and link maintenance, a synthesizer that identifies coverage gaps, and an auditor that fact-checks body claims against canonical sources. Humans set mission scope and review the work product.

Entities are added one at a time and existing entities are revised as new information surfaces. The commit history in this repository is the version trace.

## What `v1.0.0` guarantees

`v1.0.0` gates on **honesty, structural integrity, and a documented update model** — not on coverage, depth, or completeness. Concretely, this release guarantees:

- **Structural conformance.** 100% of entities (473/473) have present, stock-YAML-parseable frontmatter; every filename matches its `id`; every type-prefix matches its directory.
- **Resolved cross-references.** A field-aware check resolves every frontmatter cross-reference to an existing entity — **0 dangling references** across 1,703 references at this release.
- **Traceable sourcing.** Every non-obvious body claim carries an inline source link; the published audit trail (below) makes that sourcing inspectable claim-by-claim.
- **A published audit trail for every organization.** All **69 organizations** carry a current, substantive, claim-by-claim fact-check at `audits/<id>.md`. Organizations are the spine of the graph, so this is the corpus's credibility anchor.

It does **not** guarantee completeness, depth, uniform verification, or geographic evenness. Those are **disclosed, not gated** — read the Known gaps below and decide whether the current breadth serves your use case. A consumer wanting certainty on any single fact does its own due diligence; the corpus's job is to be honest, traceable, and structurally sound, not authoritative.

## Known gaps

Quality and coverage are uneven by design (broad-first build). The numbers below are the honest state at `v1.0.0`:

**Audit coverage — 293 of 473 entities (62%) audited.** Coverage is 100% for organizations (the one type with a coverage gate) and partial elsewhere; the auditor self-derives scope oldest-first, so the rest fills in over rotations:

| Type | Audited / total | | Type | Audited / total |
|---|---|---|---|---|
| organizations | **69 / 69** | | persons | 48 / 81 |
| campaigns | 54 / 54 | | local-groups | 25 / 36 |
| events | 42 / 49 | | messages | 11 / 37 |
| funders | 38 / 46 | | voices | 1 / 49 |
| publications | 5 / 52 | | strategies | 0 / 0 |

**Per-claim audit outcomes (the meaningful breakdown).** Across the 293 audited entities, **6,269 individual claims** were checked against canonical sources:

- **verified — 4,996 (79.7%)**: body claim matches source within paraphrase tolerance.
- **unverifiable — 1,046 (16.7%)**: audit reached its limit — source dead, no canonical source for that claim class, sources contradict each other, or the claim is too paraphrastic for specific comparison. **This is not an error**; it names where verification stops, and is itself useful provenance.
- **discrepancy — 227 (3.6%)**: a specific, citable contradiction between a body claim and its source. These are **published openly, with the flag sitting beside the entity** — the transparency is the integrity, not a clean bill of health.

Note: per-*entity* audit `status` is the most-severe per-claim outcome, so most audited entities read `discrepancy` or `unverifiable` on the strength of a single flagged claim. The per-*claim* numbers above are the accurate picture; the per-entity status is not.

**Other disclosed gaps:**

- **Strategy entities: none yet.** The type is defined in the schema but unpopulated, so any Strategy-keyed feature renders empty.
- **Messages are under-represented** (37 entities) relative to organizations/persons. Slogans, framings, and cultural artifacts are the hardest type to surface and are explicitly being grown.
- **Geographic skew.** Coverage clusters in the UK and Kenya; Latin America, Sub-Saharan Africa outside Kenya, South and Southeast Asia, and North America outside coastal tech hubs are thin.

If you're building something on top of this graph, sharing what you're working on is the most useful feedback we can receive — it points the corpus toward the use cases that matter.

## Issues and feedback

File issues on this repository's [Issues tab](../../issues) for:
- Factual errors in any entity.
- Missing entities (organizations, campaigns, people) you'd expect to see.
- Broken cross-references or links.
- Schema questions or suggestions.
- Use-case feedback — what would make this more useful for your project?

Issues are read and absorbed into the team's research and editing queue. Individual responses aren't guaranteed.

## Versioning and releases

This repository follows a **rolling-`main` plus tagged-releases** model:

- **Rolling `main`.** The publish mirror moves on every workshop commit that touches the corpus, so `main` always carries the freshest state. Track `main` if you want the latest; the git commit history is the canonical version trace, every entity edit a discrete commit.
- **Tagged releases.** Periodically the team publishes a release tag — a stable point a consumer can pin to. **`v1.0.0`** is the first. See [Releases](../../releases) and the [CHANGELOG](CHANGELOG.md). **A published release tag is immutable** — once cut, it permanently identifies the same tree and is never moved or re-pointed. Pinning to a release tag gives you the same permanence as pinning to a commit hash. If a release ever needs correction, the next version (e.g. `v1.0.1`) is published; the prior tag stays where it pointed at cut time.

**Pin, don't track, if you need stability.** Record the **release tag** (or the exact **commit hash**) you consumed; advancing the pin is a deliberate step on your side. Suggested attribution records the version (see [License](#license)).

**Release semantics — MAJOR is the breaking-change signal you can rely on.** Versions follow `MAJOR.MINOR.PATCH`:

- **MAJOR** — a **breaking schema change**: a renamed or removed frontmatter field, a changed or removed entity type, or a changed canonical cross-reference direction (the schema-as-contract definition in [`schema/spec.md`](schema/spec.md)). A pinned consumer who only watches one thing watches for a MAJOR bump — that is the one signal that schema-level re-verification is required, not just a render re-check.
- **MINOR** — content added (new entities, new audits, deeper coverage). Non-breaking.
- **PATCH** — corrections to existing content. Non-breaking.

## Working on the corpus

The team is **actively working to improve this corpus** — broadening coverage into thin regions and entity types, and deepening the audit trail toward fuller coverage. What "updating" looks like is exactly the model above: `main` advances continuously, and stable releases are tagged as the corpus reaches points worth pinning. We make **no quantitative promise** of cadence, throughput, or verification rate — the diff between one release and the next speaks for itself.

## License

[CC BY 4.0](LICENSE) — Creative Commons Attribution 4.0 International.

You are free to share and adapt this work, including commercially, with attribution. Suggested attribution:

> Make AI Good Movement Graph, https://github.com/Make-AI-Good/movement-graph, accessed YYYY-MM-DD (commit `abc1234`). Licensed CC BY 4.0.
