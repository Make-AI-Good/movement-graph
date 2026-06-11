---
entity_id: person-sasha-costanza-chock
entity_hash: ed10ef3952eabdfc44d0bd25de128b463c24c361
audit_date: 2026-06-02
pass: 1
status: corrections-pending
claims_total: 8
claims_corroborated: 5
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 2
reclassified_at: 2026-06-10
sources_consulted:
  - https://www.ajl.org/crash-project
  - https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
  - https://cms.mit.edu/faculty-expands-sasha-costanza-chock/
  - https://www.usenix.org/conference/enigma2022/speaker-or-organizer/sasha-costanza-chock-algorithmic-justice-league-0
---

## Claim 1: "Sociologist" (body)

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock; https://cms.mit.edu/faculty-expands-sasha-costanza-chock/
Source content: Wikipedia: "a U.S. communications scholar, author, and activist" with discipline "Media studies." MIT Comparative Media Studies faculty announcement: "Assistant Professor of Civic Media" focused on "media and social change" and "communication and social movements" — "sociologist" does not appear.
Comparison: Body opens with "Sociologist and design scholar". Two canonical sources (one tiebreaker, one primary institutional) consistently identify Costanza-Chock as a communications/civic-media scholar, not a sociologist. Per the source rule, Wikipedia + ≥1 other canonical source supports the discrepancy on this living-person professional-identity claim.
Decision: correction

## Claim 2: "design scholar" (body)

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: Wikipedia emphasizes "design justice" as a major research focus; Costanza-Chock is author of "Design Justice: Community-Led Practices to Build the Worlds We Need" (MIT Press, 2020).
Comparison: "Design scholar" matches the canonical record — Costanza-Chock is the author of a foundational design-justice monograph and is widely identified with design scholarship. Wikipedia is sufficient here under named-entity definitional facts (formal authorship of named work).
Decision: corroborated

## Claim 3: "has led research and design work at the Algorithmic Justice League" (body)

Source: https://www.ajl.org/crash-project
Source content: AJL's CRASH project page lists "Sasha Costanza-Chock – AJL Senior Research Fellow & Co-Lead".
Comparison: AJL's own page identifies Costanza-Chock as "Senior Research Fellow & Co-Lead" of the CRASH project — primary-source confirmation of a leadership/research role at AJL. "Led research and design work" is within paraphrase tolerance of "Senior Research Fellow & Co-Lead" combined with Costanza-Chock's broader identity as a design scholar.
Decision: corroborated

## Claim 4: "including the Community Reporting of Algorithmic System Harms (CRASH) project" (body)

Source: https://www.ajl.org/crash-project
Source content: AJL CRASH project page: "Community Reporting of Algorithmic System Harms (CRASH) Project".
Comparison: The expansion of the acronym matches the AJL primary source exactly. Costanza-Chock's involvement in CRASH is confirmed by the same page (Co-Lead).
Decision: corroborated

## Claim 5: scalar:affiliations[0].role — "research and design lead (CRASH project)"

Source: https://www.ajl.org/crash-project
Source content: "Sasha Costanza-Chock – AJL Senior Research Fellow & Co-Lead".
Comparison: AJL's own CRASH page is the canonical source for this role title. "Co-Lead" supports the "lead" component; "Senior Research Fellow" supports "research"; "(CRASH project)" is the correct project name. The "design" element is not in the CRASH-project title specifically but is consistent with Costanza-Chock's broader scholarly identity (see Claim 2). Within paraphrase tolerance. The Editor fix-location, if a tightening is desired, is `affiliations[0].role`.
Decision: corroborated

## Claim 6: scalar:affiliations[0].period — "2020-"

Source: no canonical source found
Source content: Neither the AJL CRASH page nor Wikipedia specifies when Costanza-Chock began their AJL role; the cited USENIX Enigma 2022 page confirms an AJL affiliation by 2022 but not a 2020 start date.
Comparison: The 2020 start year is plausible (aligns with the publication of "Design Justice" and the public emergence of CRASH) but no canonical source confirms it. Per the decision rules, absence of canonical evidence for a specific date claim → unverifiable. Editor fix-location if a sourceable date later surfaces: `affiliations[0].period`.
Decision: uncorroborated

## Claim 7: scalar:sources[0].note — "USENIX Enigma 2022 speaker page identifying Costanza-Chock with the Algorithmic Justice League"

Source: https://www.usenix.org/conference/enigma2022/speaker-or-organizer/sasha-costanza-chock-algorithmic-justice-league-0
Source content: HTTP 403 on direct fetch this session; page body not retrievable.
Comparison: The URL path encodes "enigma2022" and a speaker slug ending in "algorithmic-justice-league-0", which is structural evidence consistent with the note. But under the discipline rule that "Source content" must quote real source text fetched this session, a 403 leaves the comparison without a verifiable source quote; outcome is unverifiable rather than verified-on-URL-structure-alone.
Decision: uncorroborated

## Claim 8: scalar:sources[1].note — "AJL's CRASH project page — the program Costanza-Chock has led"

Source: https://www.ajl.org/crash-project
Source content: "Sasha Costanza-Chock – AJL Senior Research Fellow & Co-Lead" on the CRASH project page.
Comparison: The note's two factual components — (a) this is AJL's CRASH project page, (b) Costanza-Chock has led the program — are both confirmed by the primary-source page itself.
Decision: corroborated
