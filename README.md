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

Each audit file has YAML frontmatter — `entity_id`, `entity_hash` (the git hash of the entity file at audit time), `audit_date`, `pass`, `status`, claim counts, and the list of sources consulted — followed by a per-claim breakdown showing the body quote, source URL, source tier, source content, comparison reasoning, and decision.

A rolled-up corpus-wide reliability statement is published at [`RELIABILITY.md`](RELIABILITY.md), refreshed on every commit.

Per-claim **decisions** sit alongside a recorded **source tier** (primary / mainstream / database / tiebreaker / caution / none). The governing invariant: source quality can only ever raise support, never lower it. The decision is one of:

- **`corroborated`** — body claim matches; confirmed by ≥2 independent canonical sources. A pass.
- **`primary-sourced`** — body claim matches and rests on one primary-tier source (a court record, the entity's own filing, a government record). A pass — one authoritative source can be worth more than two weak ones.
- **`single-source`** — body claim matches and rests on one non-primary canonical source. Supported on lighter sourcing — **not** a finding of error.
- **`uncorroborated`** — no canonical source found, canonical sources conflict, the claim is too paraphrastic to compare, or a judgment-loaded edge. Names where the audit reaches its limits — **not** a finding of error.
- **`correction`** — the body carries a specific factual token (a date, number, name) that contradicts the best source and has a single correct replacement. The only decision that asserts the body is wrong; routes to the team's repair pipe.

The entity's overall `status` in the audit frontmatter is **a distribution, never the most-severe single claim** — collapsing the rollup to its worst claim hides the claim-level reality. Status is one of `corroborated` (every claim passes), `supported` (passes plus some single-source / uncorroborated), or `corrections-pending` (one or more `correction` claims open).

**Re-audit cadence is hash-based.** Audits become stale when their entity file changes (`entity_hash` no longer matches the current git hash); the auditor's next session re-audits the oldest stale entity. A `status: corroborated` audit is current only against the specific commit named in `entity_hash` — fresh audits are produced as the corpus evolves.

If you build something downstream that surfaces entity claims to readers, the audit file is the verification trail you can point them to. `single-source` and `uncorroborated` are **not** failures — they name how much sourcing backs a claim, which is itself useful provenance.

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

## Theory of Coverage

**Status: `v0.1`. Provisional. Re-examined every release.** This section answers one question: *of the movement this graph claims to map, how representative is the corpus?* The frame is what the team stands behind today, in the open — specific enough to measure (§3), honest enough about what it cannot yet see (§5). Numbers below are anchored to current `main`, refreshed each release; the [`v1.0.0` guarantees](#what-v100-guarantees) above are anchored to that release tag.

The movement is early and, on strong evidence, will be orders of magnitude larger within a few years. So the Theory of Coverage carries two jobs at once: **backward / measurable** — of the movement *as it exists today*, how much have we captured? — and **forward / aim** — what are we setting ourselves to capture *as it emerges*?

### 1 · What we claim to represent

The **grassroots and small-d democratic layer** of the make-AI-good movement — people outside AI engaged in shaping how AI is built, deployed, and held accountable. Local groups, advocacy organizations doing grassroots work, coalitions, campaigns, cultural artifacts, the voices propagating them. What counts as "in" today is provisional and re-examinable; an actor ruled out today may enter tomorrow.

### 2 · Dimensions we measure on

A dimension belongs in this list only if it traces to a commitment the mission already makes. Four dimensions clear that test today:

- **Geography** — the mission claims a global movement.
- **Entity types** — the schema's defined types; representativeness means spanning them, not over-indexing organizations.
- **Cultural artifacts** (Messages) — explicitly in-scope, explicitly central, historically under-tended.
- **Insider/outsider engagement** — the mission's working principle, and the axis the hard scope calls turn on.

**Language** and **time / currency** — proxies for reach and freshness — are held for ratification; they do not yet trace cleanly to a mission commitment.

### 3 · How representative we believe we are — the numbers

A deterministic rollup, refreshed each release by `process/coverage-script.sh`. **These are measurements, not judgments** — the judgment layer is §4. Counts from the current corpus run:

**Entity types — 803 entities across ten types:**

| type | count | | type | count |
|---|---:|---|---|---:|
| persons | 168 | | funders | 68 |
| organizations | 131 | | publications | 66 |
| campaigns | 84 | | messages | 62 |
| events | 74 | | local-groups | 56 |
| voices | 69 | | strategies | 25 |

**Geography — each entity assigned to one macro-region by tag set; entities with no geographic tag fall to `no-signal` (often persons whose geography lives via affiliation):**

| region | count | | region | count |
|---|---:|---|---|---:|
| Americas-North | 208 | | Americas-Latin | 64 |
| Europe | 186 | | MENA | 38 |
| Africa | 89 | | Oceania | 25 |
| Asia | 88 | | Global-aggregate | 23 |
| no-signal | 82 | | | |

**Cultural artifacts.** Messages, the mission's named under-tended type, are **62 entities — 7.7% of the corpus**.

**Insider/outsider engagement.** A coarse tag-based proxy for the mission's working principle (*are people outside AI being engaged in work to make AI better?*): **196 of 803 entities (24.4%) carry an outsider-audience tag.** The substring list driving the count is judgment; the count given the list is deterministic. See `process/coverage-script.sh`.

### 4 · Where we fall short, and why

The judgment layer. Each verdict is tagged **correctable** (build-order or sourcing), **under-tended** (genuinely hard), or **deliberate** (out of scope or awaiting a decision).

**Geographic skew — deliberate-plus-build-order.** Europe and Americas-North together hold **49% of the corpus (394 / 803)**. Latin America sits at 8%; MENA at 4.7%; Oceania at 3.1%. Sub-Saharan African coverage concentrates heavily on Kenya; South and Southeast Asia are thin; North America outside coastal tech hubs is thin. The skew is partly **build-order** — breadth-first work from English-language sources reaches Europe and North America first — and partly **deliberate**, because the team has not yet stood up the language and regional-sourcing tooling that would correct it at scale. Surfacing thin regions is a Synthesizer heuristic; concrete correction work flows through the Researcher inbox.

**Strategy coverage — correctable / build-order.** The Strategy layer was seeded late (first entries 2026-06-06) and is **thin but actively being filled** — 25 named strategies in the corpus today, after a directed breadth pass; depth (evaluation of what works against what aims, ecology among strategies, adopter cross-linking) follows. Named here as a gap we are *closing on purpose*, not a deliberate omission. Naming a strategy takes no evidence — the test is whether the form holds — so breadth can move ahead of the slower evaluative layer.

**Messages thinness — under-tended.** Messages — the mission's explicitly central, historically under-tended type — sit at **7.7% of the corpus (62 / 803)**, below where their mission weight would warrant. The shortfall is *under-tended*, not deliberate: cultural artifacts (slogans, framings, memes) are the hardest entity type to surface from public material, and the corpus has not yet stood up a steady channel for them. Named here as the gap nearest to the mission's center.

**Audit coverage — correctable / build-order, currently regressing.** Audit coverage — the share of entities carrying a current, claim-by-claim audit at `audits/<id>.md` — sits at **61.6%**. It *fell* during the V2 build: auditing was paused while the directed entity work ran, so the percentage compressed mechanically as the denominator grew without new audits landing. Resumes post-V2. Per-claim discrepancy state continues to publish honestly in the audits that do exist (see [Audits](#audits)); the gap here is verification-state evenness across the corpus, not honesty about it.

### 5 · Blind-spot register — what our frame may not let us see

The §2 dimensions measure *inside* an envelope we drew. The register below names hypotheses about movement-growth *outside* that envelope, paired with the signal we would watch for. This is the part we most expect to grow.

- **Channels we don't monitor** — offline organizing, TikTok, closed platforms. *Signal:* in-corpus entities referencing actions or spaces we hold no entity for.
- **Framings that don't use AI vocabulary** — human-centered work that is functionally about AI but won't pattern-match our filter. *Signal:* the hardest to design — candidly flagged as one we cannot reliably catch yet.
- **AI-safety-world currents crossing into popular-movement territory.** *Signal:* in-corpus AI-safety entities spawning mass-participation actions or coalitions.
- **Temporally-excluded actors entering.** Scope is temporal — an actor ruled out today (a funder strong on one axis only, an org whose AI program does not yet engage outsiders) may later develop the missing axis. *Signal:* periodic re-examination of dated scope-outs.

### 6 · Revision plan

Re-examined every release — **the frame and the register, not only the numbers.** A mechanism and owner for keeping the register honest over time is open and named: v0.1 does not pretend one into existence.

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
