# Changelog

All notable changes to the Movement Graph are documented here. The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and the corpus follows the
release semantics described in the [README](README.md#versioning-and-releases):
**MAJOR** = breaking schema change, **MINOR** = content added, **PATCH** = corrections.

## [2.0.0] — 2026-06-13

The first **directed-coverage** release. Where `v1.0.0` built broadly — a little
of everything — `v2.0.0` aims: the team pointed its work at the most valuable
gaps in the graph, driven by two engines (requests from people who use the graph,
filed as public GitHub issues, and the team's own read of what the mission says
is missing). This is the pattern every future release follows, not a one-off.

The headline is **connections**. A graph's value is what you can navigate, and
the edge count **doubled** (826 → 1,652 unique-pair edges) while the corpus grew
70% — so density rose, not just size. Whole-corpus orphan share **halved**
(11.6% → 5.7%).

### Added

- **Theory of Coverage (draft `v0.1`)** in the [README](README.md) — the
  measuring stick. It states what the graph claims to represent, the dimensions
  we judge ourselves on (geography, entity types, cultural artifacts,
  insider/outsider engagement), how representative we believe we are, and where
  we fall short and why. Provisional and sharpened each release; honest-and-useful
  over exhaustive-and-false.
- **Strategy entities — a whole entity type, populated for the first time.**
  25 named strategies (the approaches the movement uses, or could use, to pursue
  making AI good), cross-linked to their adopters: `organization.strategies`
  0% → 61%, `campaign.strategies` 0% → 55%. Strategy *depth* (evaluation of what
  works, effects taxonomy) is a later release; this is breadth.

### Changed — directed coverage fills

- **Connections backfilled across the aimed areas.** Publication authorship
  `authors[]` 38% → 55%; organization funder edges 54% → 59% (funder orphans
  45.7% → 32.4%); local-group connection floor `key_people` 8% → 77%,
  `parent_org` 39% → 45% (local-group orphans 55.6% → 21.4%).
- **Regional breadth.** New anchors in under-covered regions — Indigenous data
  sovereignty (Aotearoa, Australia, US), Southeast Asia (Indonesia), MENA (Egypt,
  Palestine). MENA 21 → 38, Oceania 16 → 25. Coverage is still uneven and the ToC
  says so plainly.
- **Cultural artifacts kept pace.** Messages — the mission's named under-tended
  type — grew with the corpus (37 → 62) rather than being diluted.

### Disclosed — verification state

The published fact-check trail is unchanged in rigor, but its **coverage fell**
this release: **61.6%** of entities carry an audit trail, down from 69% at
`v1.1.0`. The corpus grew while routine auditing was **deliberately paused** to
focus effort on the directed-coverage build; the audit habit resumes after this
release and climbs back toward 100% over time. Per-claim reliability across the
495 audited entities holds: of 11,035 claims, **78.3% corroborated or
primary-sourced, 15.8% uncorroborated, 3.7% with a precision-correction pending**
(corrections-pending state is published openly, not hidden — see
[`RELIABILITY.md`](RELIABILITY.md)). No fabrication observed.

### Why this isn't a MAJOR bump

The entity schema in [`schema/spec.md`](schema/spec.md) is **unchanged**. Strategy
was already a defined entity type; populating it adds content, it does not change
the data's shape. MINOR is the correct bump (content added).

### Corpus state at this release

- **803 entities** across all ten types — Strategy populated for the first time
  (organizations 131, persons 168, campaigns 84, events 74, voices 69, funders 68,
  publications 66, messages 62, local-groups 56, strategies 25).
- **1,652 unique-pair edges; average degree 4.11** (v1.0.0: 826 / 3.49). Orphan
  share 5.7% (v1.0.0: 11.6%).
- **Audit coverage 61.6%** (495/803); per-claim breakdown above.
- **Provenance floor held:** no `confidence: low` Person entries.

[2.0.0]: https://github.com/Make-AI-Good/movement-graph/releases/tag/v2.0.0

## [1.1.0] — 2026-06-10

The audit reporting layer is re-keyed for consumer reading. The audit work itself
is unchanged — same canonical-source rules, same Auditor independence, same
discrepancies surfaced — but the *vocabulary* the audits publish in changes, and
a corpus-wide reliability statement is now generated from the audit trail.

### Why

`v1.0.0`'s audit vocabulary (`verified` / `discrepancy` / `unverifiable`) was an
internal-QA register published as the consumer reliability verdict. Consumer
reads were collapsing the entity status to its single most-severe claim — an
entity carrying 26 corroborated claims and 1 unverifiable one rendered the same
shade of red as an entity that was actually wrong. The claim-level reality
across the v1.0.0 corpus was sound (~80% corroborated, ~17% unverifiable, ~4%
correction — see [`RELIABILITY.md`](RELIABILITY.md) for the current numbers).
The reporting layer was misreading itself.

This release fixes the words; verification rigor stands.

### Added

- **[`RELIABILITY.md`](RELIABILITY.md)** — a corpus-wide reliability statement, generated from `audits/` frontmatter on every commit (wired to the team's pre-commit hook alongside the dashboard). Each release tag pins one of these snapshots. Lives at the published repo root.
- **Per-claim source tier** recorded on every audit-file claim, on a six-tier taxonomy (primary / mainstream / database / tiebreaker / caution / none) — saved information even where the tier doesn't change the decision.
- **`primary-sourced`** as a new pass decision: a single primary-tier source (court record, the entity's own filing, a government record) passes a claim. Quality of source can raise support; it can never lower it.

### Changed — breaking for programmatic audit-file consumers

Audit-file frontmatter and per-claim Decision values are renamed across the board. A consumer reading `audits/<id>.md` programmatically needs to update its field map. Entity-file (`entities/<type>/<id>.md`) schema is **unchanged** — `schema/spec.md` defines the entity layer, which this release does not touch.

**Per-claim Decision rename:**

| Old | New | Notes |
|---|---|---|
| `verified` | `corroborated` | The relabel pass defaulted every prior `verified` claim to `corroborated`; the split into `corroborated` (≥2 sources) vs `primary-sourced` (1 primary-tier source) vs `single-source` (1 non-primary canonical source) rides organic re-audit as the corpus evolves. |
| `discrepancy` | `correction` | The repair-trigger; routes through the team's Editor pipe. |
| `unverifiable` | `uncorroborated` | "Names where audit reaches its limits" — not a finding of error. |

**Entity `status:` rename and re-semantic:**

| Old | New | Notes |
|---|---|---|
| `verified` | `corroborated` | Every claim is corroborated or primary-sourced. |
| `unverifiable` (most-severe rollup) | `supported` | No open corrections; some single-source or uncorroborated claims. |
| `discrepancy` (most-severe rollup) | `corrections-pending` | `open_corrections > 0`. |

The most-severe rollup is **retired** — `status:` now reads as a positive-or-neutral distribution label, never an alarm word. The full distribution lives in the frontmatter count fields.

**Frontmatter field rename:**

| Old | New |
|---|---|
| `claims_verified` | `claims_corroborated` |
| `claims_discrepancy` | `open_corrections` |
| `claims_unverifiable` | `claims_uncorroborated` |
| — | `claims_primary_sourced` (new; counts primary-tier single-source passes) |
| — | `claims_single_source` (new; counts non-primary single-source claims) |

A pinned consumer reading `audits/` programmatically: update the field map per the above and you're current. A consumer reading the audit files as prose (or following links from `RELIABILITY.md`) sees the new vocabulary directly.

### Why this isn't a MAJOR bump

The README defines MAJOR as a breaking change to the **entity** schema in [`schema/spec.md`](schema/spec.md) — renamed entity frontmatter fields, changed entity types, changed canonical cross-reference direction. That schema is unchanged here. The audit-file format lives in the team's Auditor profile, not in `schema/spec.md`; renaming its vocabulary doesn't trip the MAJOR criterion.

We've called the rename out prominently in this entry so a consumer reading audit files programmatically can adapt without surprise.

### Corpus state at this release

Snapshot from [`RELIABILITY.md`](RELIABILITY.md) — refresh that file for the current `main`:

- **469 audits across 676 entities (69% coverage).** Audit coverage is the per-entity verification trail — `audits/<entity-id>.md`.
- **10,198 claims** audited at the claim level. **79.8% corroborated or primary-sourced, 0.1% single-source, 16.5% uncorroborated, 3.7% precision-corrected.** No fabrication observed.
- The 0.1% `single-source` figure reflects the relabel-pass default (every prior `verified` claim mapped to `corroborated`); the corroborated / primary-sourced / single-source split will sharpen as re-audits land.

[1.1.0]: https://github.com/Make-AI-Good/movement-graph/releases/tag/v1.1.0

## [1.0.0] — 2026-06-02

The first release the team stands behind for consumers. `v1.0.0` gates on **honesty,
structural integrity, and a documented update model** — not on coverage or depth, which
are disclosed rather than gated (see the README's *Known gaps*).

### Added
- **Release model.** Rolling-`main`-plus-tagged-releases versioning, documented in the README, with `MAJOR` carrying the one signal a pinned consumer needs (a breaking schema change).
- **This CHANGELOG**, seeded at `v1.0.0`.
- **Disclosure layer in the README**: what `v1.0.0` guarantees, the per-claim audit breakdown, and the known coverage/quality gaps.

### Corpus state at this release
- **473 entities** across nine populated types (organizations, campaigns, events, funders, local-groups, messages, persons, publications, voices); Strategy is defined in the schema but unpopulated.
- **Structural integrity:** 473/473 entities pass all mechanical checks (frontmatter parses, filename matches `id`, type-prefix matches directory); **0 dangling cross-references** across 1,703 references (field-aware check).
- **Audit coverage:** 293/473 entities (62%) carry a published fact-check trail, including **100% of organizations (69/69)** — the credibility anchor. Across audited entities, 6,269 claims were checked: 4,996 verified (79.7%), 1,046 unverifiable (16.7%), 227 discrepancy (3.6%). Discrepancies and unverifiables are published openly.
- **Provenance floor:** no `confidence: low` Person entries (0/81).

[1.0.0]: https://github.com/Make-AI-Good/movement-graph/releases/tag/v1.0.0
