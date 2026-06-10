# Changelog

All notable changes to the Movement Graph are documented here. The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and the corpus follows the
release semantics described in the [README](README.md#versioning-and-releases):
**MAJOR** = breaking schema change, **MINOR** = content added, **PATCH** = corrections.

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
