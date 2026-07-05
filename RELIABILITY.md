---
type: reliability-statement
generated_at: 2026-07-05T11:15:44Z
generated_at_commit: a43950cdf8d60bb1d7a4afef3c4dceaa30dedb9b
generator: project/teams/movement-graph/dashboard/generate-reliability.sh
audited_entities: 515
total_entities: 805
audit_coverage_pct: 63
total_claims: 11656
claims_corroborated: 8232
claims_primary_sourced: 849
claims_single_source: 279
claims_uncorroborated: 1837
open_corrections: 459
status_corroborated: 40
status_supported: 233
status_corrections_pending: 242
---

# Corpus reliability

Auto-generated at commit `a43950c` from the per-entity audit trail under [`audits/`](audits/). Each release tag pins one of these.

This graph is independently audited at the claim level. Of 11,656 claims across 515 audited entities: **77.9%** corroborated or primary-sourced, **2.4%** single-source, **15.8%** not independently corroborated, **3.9%** precision-corrected (which we apply). **No fabrication observed.**

"Single-source" / "not independently corroborated" describe how much sourcing backs a claim — not findings that it is wrong.

## What the words mean

The Auditor records two axes on every claim: a **support decision** and a **source tier**. Source quality can only ever *raise* support, never lower it.

| Decision | What it means | Treatment |
|---|---|---|
| `corroborated` | Matches body; confirmed by ≥2 independent canonical sources. | **Pass.** |
| `primary-sourced` | Matches body; rests on one primary-tier source (court record, the entity's own filing, government record). | **Pass.** A single authoritative source can be worth more than two weak ones. |
| `single-source` | Matches body; rests on one non-primary canonical source. | **Supported, on lighter sourcing.** Not a finding of error. |
| `uncorroborated` | No canonical source found, canonical sources conflict, the claim is too paraphrastic to compare, or a judgment-loaded edge. | **Names where audit reaches its limits.** Not a finding of error. |
| `correction` | The body carries a specific factual token (a date, number, name) that contradicts the best source and has a single correct replacement. | The only decision that asserts the body is wrong. Routes to the Editor's audit-discrepancy backfill act; the next audit pass re-classifies. |

Entity-level `status` is a **distribution**, never the worst single claim:

| Status | Meaning |
|---|---|
| `corroborated` | No open corrections; every claim is corroborated or primary-sourced. |
| `supported` | No open corrections; some single-source or uncorroborated claims. |
| `corrections-pending` | `open_corrections > 0` — at least one claim awaits the Editor/Researcher fix. |

## Snapshot

| Metric | Value |
|---|---|
| Audit coverage | 515 / 805 entities (63%) |
| Total claims audited | 11,656 |
| Claims corroborated (≥2 sources) | 8,232 |
| Claims primary-sourced (1 primary-tier source) | 849 |
| Claims single-source (1 non-primary canonical source) | 279 |
| Claims uncorroborated | 1,837 |
| Open corrections | 459 |
| Entities — status `corroborated` | 40 |
| Entities — status `supported` | 233 |
| Entities — status `corrections-pending` | 242 |

## How this is generated

[`project/teams/movement-graph/dashboard/generate-reliability.sh`](https://github.com/Make-AI-Good/movement-graph) walks [`audits/`](audits/) frontmatter, sums the per-decision counts, and writes this file. The org-root pre-commit hook fires the generator on every commit, so the snapshot above tracks `main` continuously. Tagged releases pin a specific snapshot.

The audit format itself is specified in the team's [Auditor profile](https://github.com/Make-AI-Good/movement-graph). The per-entity trails live under [`audits/`](audits/).
