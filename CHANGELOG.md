# Changelog

All notable changes to the Movement Graph are documented here. The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and the corpus follows the
release semantics described in the [README](README.md#versioning-and-releases):
**MAJOR** = breaking schema change, **MINOR** = content added, **PATCH** = corrections.

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
