# Movement Graph

A knowledge graph mapping the grassroots, small-d democratic movement working to make AI broadly beneficial.

Part of the [Make AI Good](https://github.com/Make-AI-Good) project.

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

## Current state

This is an early-stage corpus. Coverage is intentionally broad rather than deep, so any single area will feel incomplete. Some entity types (notably Messages — slogans, framings, cultural artifacts) are under-represented and will fill in over time. The Strategy entity type is defined in the schema but not yet populated.

The audit pass is also in progress — at any given time some entities will have current audit files in `audits/`, some will have stale audits (entity edited since last audit), and some will not yet have been audited at all. The auditor self-derives scope oldest-first, so coverage fills in over rotations.

If you're building something on top of this graph, sharing what you're working on is the most useful feedback we can receive — it points the corpus toward use cases that matter.

## Issues and feedback

File issues on this repository's [Issues tab](../../issues) for:
- Factual errors in any entity.
- Missing entities (organizations, campaigns, people) you'd expect to see.
- Broken cross-references or links.
- Schema questions or suggestions.
- Use-case feedback — what would make this more useful for your project?

Issues are read and absorbed into the team's research and editing queue. Individual responses aren't guaranteed.

## Versioning

The git commit history is the canonical version trace; every entity edit is a discrete commit. Tagged releases may be added later as consumers ask for them.

When citing or building against the graph, recording the **commit hash** of the version you consumed is the most reliable reference.

## License

[CC BY 4.0](LICENSE) — Creative Commons Attribution 4.0 International.

You are free to share and adapt this work, including commercially, with attribution. Suggested attribution:

> Make AI Good Movement Graph, https://github.com/Make-AI-Good/movement-graph, accessed YYYY-MM-DD (commit `abc1234`). Licensed CC BY 4.0.
