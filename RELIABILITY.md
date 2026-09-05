---
type: reliability-statement
generated_at: 2026-09-05T02:34:36Z
generated_at_commit: faad1e2e59837865cc6541370620aa4dcc3aa88c
generator: project/teams/movement-graph/dashboard/generate-reliability.sh
audited_entities: 576
total_entities: 906
audit_coverage_pct: 63
total_claims: 13320
claims_corroborated: 8631
claims_primary_sourced: 1557
claims_single_source: 452
claims_uncorroborated: 2103
open_corrections: 577
status_corroborated: 41
status_supported: 245
status_corrections_pending: 290
---

# Corpus reliability

Auto-generated at commit `faad1e2` from the per-entity audit trail under [`audits/`](audits/). Each release tag pins one of these.

This graph is independently audited at the claim level. Of 13,320 claims across 576 audited entities: **76.5%** corroborated or primary-sourced, **3.4%** single-source, **15.8%** not independently corroborated, **4.3%** precision-corrected (which we apply). **No fabrication observed.**

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
| Audit coverage | 576 / 906 entities (63%) |
| Total claims audited | 13,320 |
| Claims corroborated (≥2 sources) | 8,631 |
| Claims primary-sourced (1 primary-tier source) | 1,557 |
| Claims single-source (1 non-primary canonical source) | 452 |
| Claims uncorroborated | 2,103 |
| Open corrections | 577 |
| Entities — status `corroborated` | 41 |
| Entities — status `supported` | 245 |
| Entities — status `corrections-pending` | 290 |

## How this is generated

[`project/teams/movement-graph/dashboard/generate-reliability.sh`](https://github.com/Make-AI-Good/movement-graph) walks [`audits/`](audits/) frontmatter, sums the per-decision counts, and writes this file. The org-root pre-commit hook fires the generator on every commit, so the snapshot above tracks `main` continuously. Tagged releases pin a specific snapshot.

The audit format itself is specified in the team's [Auditor profile](https://github.com/Make-AI-Good/movement-graph). The per-entity trails live under [`audits/`](audits/).
