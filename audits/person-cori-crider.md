---
entity_id: person-cori-crider
entity_hash: b6bff31fb105fd5a09fa6d9c52278266cdb8add4
audit_date: 2026-06-01
pass: 1
status: corrections-pending
claims_total: 8
claims_corroborated: 7
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 0
sources_consulted:
  - https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
  - https://www.foxglove.org.uk/who-we-are/people/
  - https://www.openmarketsinstitute.org/staff/cori-crider
  - https://www.openmarketsinstitute.org/our-people
  - https://www.coricrider.com/
---

## Claim 1: "US-qualified lawyer"

Source: https://www.openmarketsinstitute.org/staff/cori-crider
Source content: "a B.A. from the University of Texas and a J.D. from Harvard Law School"
Comparison: OMI staff bio confirms US legal education (Harvard J.D.); her own coricrider.com profile and the wider source set describe her as a lawyer practicing primarily in US-rooted matters (Guantánamo, drone-strike cases). "US-qualified" is supported.
Decision: corroborated

## Claim 2: "co-founder of [Foxglove]"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
Source content: "Foxglove co-founder and director Cori Crider is stepping back from her directorship this September."
Comparison: Foxglove's own announcement names her as co-founder. Her coricrider.com bio independently confirms ("Previously I co-founded Foxglove").
Decision: corroborated

## Claim 3: "a director of the organisation from its 2019 founding"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
Source content: "After five brilliant years, Foxglove co-founder and director Cori Crider is stepping back from her directorship this September."
Comparison: Five-year tenure ending September 2024 places her directorship start at September 2019, consistent with Foxglove's 2019 founding date.
Decision: corroborated

## Claim 4: "until September 2024"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
Source content: Article published 13 September 2024 stating she "is stepping back from her directorship this September."
Comparison: Body's "September 2024" matches the announcement date and Foxglove's stated month of departure.
Decision: corroborated

## Claim 5: "subsequently took up a senior fellowship at the Open Markets Institute's Center for Journalism & Liberty"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/ and https://www.openmarketsinstitute.org/staff/cori-crider
Source content: Foxglove announcement: "Cori's next move is joining our friends at Open Markets Institute and the Future of Tech Institute as a Senior Fellow focused on antimonopoly policy." OMI staff page: "Senior Fellow at Open Markets and the Future of Tech Institute"
Comparison: Both canonical sources locate her Senior Fellow role at Open Markets and the Future of Tech Institute (antimonopoly focus), not at the Center for Journalism & Liberty. CJL is a separate OMI program (renamed Center for Media and Digital Governance in 2026) which she is reported to direct, but her senior fellowship is at Future of Tech Institute. The body's program attribution is wrong. Suggested single-token fix: replace "Center for Journalism & Liberty" with "Future of Tech Institute".
Decision: correction

## Claim 6: scalar:affiliations[0].role "co-founder and former director"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
Source content: "Foxglove co-founder and director Cori Crider is stepping back from her directorship this September."
Comparison: Foxglove's own announcement establishes both the co-founder status and her former-director status (now stepped back). Matches the scalar.
Decision: corroborated

## Claim 7: scalar:affiliations[0].period "2019-2024"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
Source content: "After five brilliant years … stepping back from her directorship this September." (article dated 13 September 2024)
Comparison: Five years ending September 2024 implies a 2019 start. The 2019–2024 period in the affiliation frontmatter is consistent.
Decision: corroborated

## Claim 8: scalar:sources[0].note "Foxglove's September 2024 announcement of Crider stepping back from her directorship after five years"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
Source content: Article published 13 September 2024: "After five brilliant years, Foxglove co-founder and director Cori Crider is stepping back from her directorship this September."
Comparison: The scalar's description (Sept 2024 announcement, stepping back from directorship, after five years) matches the source verbatim.
Decision: corroborated
