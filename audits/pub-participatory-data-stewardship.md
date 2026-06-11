---
entity_id: pub-participatory-data-stewardship
entity_hash: fd1def25568198c9faf1f1accefd7164e97bef05
audit_date: 2026-06-11
pass: 2
status: supported
claims_total: 24
claims_corroborated: 7
claims_primary_sourced: 8
claims_single_source: 7
claims_uncorroborated: 2
open_corrections: 0
sources_consulted:
  - https://www.reemapatel.org/
  - https://uksa.statisticsauthority.gov.uk/news/involving-people-in-the-use-of-data-for-research-and-official-statistics-heres-how/
  - https://thelivinglib.org/participatory-data-stewardship/
  - https://communityscience.astc.org/resources/participatory-data-stewardship-a-framework-for-involving-people-in-the-use-of-data/
  - https://digitalgood.net/research/participatory-and-inclusive-data-stewardship/
  - https://www.adalovelaceinstitute.org/report/participatory-data-stewardship/ (HTTP 403 — unretrievable this pass)
  - https://www.adalovelaceinstitute.org/wp-content/uploads/2021/09/Participatory-data-stewardship_Final-report.pdf (HTTP 403 — unretrievable this pass)
  - https://www.adalovelaceinstitute.org/wp-content/uploads/2021/11/ADA_Participatory-Data-Stewardship.pdf (HTTP 403 — unretrievable this pass)
  - https://ictlogy.net/works/reports/projects.php?idp=5828 (HTTP 403 — unretrievable this pass)
---

Pass-2 context: the only entity change since pass 1 (2026-06-03) is the Researcher's fix to
`sources[8].note` (commit df1affd7), exactly the pass-1 Claim 24 correction. This pass re-fetched
the live anchor sources, re-corroborated the search-dependent claims, verified the fix, and
re-graded all decisions under the 2026-06-10 sourcing-strength vocabulary (with Source tier lines,
which pass 1 predates). The pass-1 correction is cleared; no new corrections found.

## Claim 1: "report published by the Ada Lovelace Institute" and "in September 2021"

Source: https://communityscience.astc.org/resources/participatory-data-stewardship-a-framework-for-involving-people-in-the-use-of-data/ ; Institute's own PDF URL path (2021/09)
Source tier: primary
Source content: Community Science entry: "Publisher/Organization: Ada Lovelace Institute. Publication Year: 2021. Location: London, England." PDF URL path on the Institute's own domain contains "2021/09/Participatory-data-stewardship_Final-report.pdf".
Comparison: Publisher and month/year match across the Institute's own hosting path and an independent database entry.
Decision: corroborated

## Claim 2: "lead-authored by Reema Patel"

Source: https://uksa.statisticsauthority.gov.uk/news/involving-people-in-the-use-of-data-for-research-and-official-statistics-heres-how/ ; https://www.reemapatel.org/
Source tier: primary
Source content: UKSA page: "lead author of the Institute's report on participatory data stewardship." Patel's site: "She is an author of several Ada Lovelace Institute's reports, including Beyond Face Value, Rethinking Data, The Data Divide and Participatory Data Stewardship among others."
Comparison: Lead authorship confirmed by a government source; authorship independently confirmed by Patel's own disclosure.
Decision: corroborated

## Claim 3: "then the Institute's Associate Director for Engagement"

Source: https://uksa.statisticsauthority.gov.uk/news/involving-people-in-the-use-of-data-for-research-and-official-statistics-heres-how/
Source tier: primary
Source content: "Associate Director (Engagement) at the Ada Lovelace Institute"
Comparison: Phrasing variant ("Associate Director (Engagement)" vs "Associate Director for Engagement"); same role, within paraphrase tolerance. Single government source.
Decision: primary-sourced

## Claim 4: "the colleague who established its work on public engagement and participation"

Source: https://www.reemapatel.org/
Source tier: primary
Source content: "She co-founded the Ada Lovelace Institute where she established its work on public engagement and participation."
Comparison: Body matches the source's phrasing verbatim. Single source, but Patel's own site is primary for a claim about her own role.
Decision: primary-sourced

## Claim 5: "the responsible use, collection and management of data in a participatory and rights-preserving way, informed by values and engaging with questions of fairness"

Source: https://thelivinglib.org/participatory-data-stewardship/
Source tier: database
Source content: "Data stewardship" as "the responsible use, collection and management of data in a participatory and rights-preserving way, informed by values and engaging with questions of fairness."
Comparison: Body's quote matches the source verbatim. One canonical database source (the report PDF itself 403'd this pass).
Decision: single-source

## Claim 6: "rejects opaque or manipulative data practices in favour of practices that empower people to help inform, shape and, in some instances, govern their own data"

Source: https://thelivinglib.org/participatory-data-stewardship/
Source tier: database
Source content: "rejects practices of data collection, storage, sharing and use in ways that are opaque or seek to manipulate people, in favour of practices that empower people to help inform, shape and – in some instances – govern their own data."
Comparison: Body compresses the opening clause to "opaque or manipulative data practices" — within paraphrase tolerance; the empowering clause matches verbatim. One canonical source.
Decision: single-source

## Claim 7: "Sherry Arnstein's 1969 'ladder of citizen participation'"

Source: https://thelivinglib.org/participatory-data-stewardship/ ; Arnstein's 1969 publication date is a public-record fact about an academic paper (Wikipedia-alone-sufficient class per profile § Source rule)
Source tier: database
Source content: "drawing extensively from Sherry Arnstein's 'ladder of citizen participation' and its more recent adaptation into a spectrum." Arnstein, S. R. (1969) "A Ladder of Citizen Participation," Journal of the American Institute of Planners 35(4).
Comparison: The framework's anchoring in Arnstein's ladder is confirmed; the 1969 date is the canonical public-record date of the paper.
Decision: corroborated

## Claim 8: "the IAP2 spectrum of public participation"

Source: https://communityscience.astc.org/resources/participatory-data-stewardship-a-framework-for-involving-people-in-the-use-of-data/
Source tier: database
Source content: tiers ordered "according to their impact on decision making (from low to high, as defined by the Spectrum of Public Participation)" — the Spectrum of Public Participation is IAP2's canonical instrument so named. (Living Library's "adaptation into a spectrum" is consistent but does not name IAP2.)
Comparison: The IAP2-specific attribution rests on one canonical source.
Decision: single-source

## Claim 9: "five tiers of escalating public influence — inform, consult, involve, collaborate, and empower"

Source: https://communityscience.astc.org/resources/participatory-data-stewardship-a-framework-for-involving-people-in-the-use-of-data/
Source tier: database
Source content: "Informing > Consulting > Involving > Collaborating > Empowering."
Comparison: Tier set matches; base-verb vs gerund phrasing is within paraphrase tolerance. One canonical source.
Decision: single-source

## Claim 10: "analysis of over 100 case studies"

Source: https://thelivinglib.org/participatory-data-stewardship/
Source tier: database
Source content: "Over 100 case studies of different methods of participatory data stewardship" were analyzed; the framework is "based on an analysis of over 100 case studies."
Comparison: Match. One canonical source (report PDF 403'd this pass).
Decision: single-source

## Claim 11: "data cooperatives in Barcelona and Liverpool, mental-health data banks, citizen data-impact assessments and audits, co-design initiatives, and the algorithmic registers operated by Helsinki and Amsterdam"

Source: https://uksa.statisticsauthority.gov.uk/news/involving-people-in-the-use-of-data-for-research-and-official-statistics-heres-how/
Source tier: primary
Source content: "data cooperatives in Barcelona and Liverpool, Data Banks on mental health, citizen data impact assessments and audits" plus "algorithmic registers in Helsinki and Amsterdam"
Comparison: Every named-place exemplar and category in the body's list is confirmed by the government source except "co-design initiatives," a generic participatory-mechanism category consistent with (and not contradicted by) the report's scope. Single primary source covering the load-bearing content.
Decision: primary-sourced

## Claim 12: "Public Participation & Research programme" (Ada Lovelace Institute)

Source: WebSearch this session — the Institute's own "Public Participation & Research" page (https://adalovelaceinstitute.org/about/how-to-work-with-us/publics) surfaced as a live page
Source tier: primary
Source content: Search-surfaced Institute page titled "Public Participation & Research | Ada Lovelace Institute"; search summary: "Public Participation & Research is central to the Ada Lovelace Institute's work because it ensures that the voices of people affected by data and AI contribute to building and shaping evidence, research, policy and practices."
Comparison: The named programme exists on the Institute's own site. Evidence is the Institute's own surface (direct fetch 403'd).
Decision: primary-sourced

## Claim 13: "the Citizens' Biometrics Council, the NHS fair-data-sharing juries, Public Voices in AI" (Institute initiatives)

Source: WebSearch this session — https://www.adalovelaceinstitute.org/report/citizens-biometrics-council/ ; https://participedia.net/case/6086 ; https://www.adalovelaceinstitute.org/news/citizen-juries-on-fair-data-sharing-nhs/
Source tier: primary
Source content: "The Ada Lovelace Institute conceived of and designed the Citizens' Biometrics Council" (50 members of the public, 60 hours of workshops, 30 recommendations); "The Ada Lovelace Institute supports Wellcome Trust to undertake citizen juries on fair data sharing in the NHS" (juries in Taunton, Leeds and London, September 2019); Public Voices in AI confirmed as an Institute project in search results alongside the Council.
Comparison: All three named initiatives are confirmed Ada Lovelace Institute projects; the Citizens' Biometrics Council is additionally confirmed by an independent database (Participedia).
Decision: corroborated

## Claim 14: "the UK Statistics Authority's Centre for Applied Data Ethics drew on it to shape engagement guidance for researchers and statisticians working with public data"

Source: https://uksa.statisticsauthority.gov.uk/news/involving-people-in-the-use-of-data-for-research-and-official-statistics-heres-how/
Source tier: primary
Source content: The Authority released "draft ethics guidance on considering public views and engagement in research and statistics projects," drawing on Patel's participatory data stewardship framework.
Comparison: Match. Single source, but it is the adopting body's own government page — the authoritative record of its own adoption.
Decision: primary-sourced

## Claim 15: "The Institute's 2024–25 Participatory and inclusive data stewardship landscape review, produced jointly with the ESRC Digital Good Network and the Liverpool City Region Civic Data Cooperative, explicitly builds on this 2021 report"

Source: https://digitalgood.net/research/participatory-and-inclusive-data-stewardship/ ; WebSearch this session (Institute's own project page and report PDF surfaced; December 2024 publication, Roshni Modhvadia and Octavia Field Reid as authors, Patel foreword)
Source tier: primary
Source content: Digital Good page: the research "builds upon a lead authored report on Participatory Data Stewardship (2022), published by the Ada Lovelace Institute"; Emily Rempel identified as "Public Participation Manager at the Liverpool City Region Civic Data Co-operative (CDC)." Search: "Participatory and inclusive data stewardship: A landscape review" published December 2024 as a partnership of the Ada Lovelace Institute, the Digital Good Network, and the Liverpool Civic Data Cooperative.
Comparison: Review existence, partnership composition, December 2024 publication, and derivation from the prior PDS report all confirmed. The Digital Good page's "(2022)" year for the prior report is a year-attribution error on that page — the report's September 2021 publication is confirmed elsewhere in this audit; the body's "2021" is correct.
Decision: corroborated

## Claim 16: scalar:sources[0].note — "Institute's own landing page for the report — primary source for the report's framing, central proposition, and September 2021 release"

Source: https://www.adalovelaceinstitute.org/report/participatory-data-stewardship/ returned HTTP 403 to WebFetch this pass; substantive content corroborated by the Institute's PDF URL path (2021/09) and the Community Science entry (2021, Ada Lovelace Institute, London)
Source tier: primary
Source content: PDF URL path encodes September 2021 on the Institute's own domain; Community Science: "Publisher/Organization: Ada Lovelace Institute. Publication Year: 2021."
Comparison: The note's substantive claims (Institute's landing page for the report; September 2021 release) are consistent with the URL's domain/path and independently corroborated for publisher and year.
Decision: corroborated

## Claim 17: scalar:sources[1].note — "Final report PDF as hosted on the Institute's own site (September 2021 version)"

Source: https://www.adalovelaceinstitute.org/wp-content/uploads/2021/09/Participatory-data-stewardship_Final-report.pdf (HTTP 403 to WebFetch this pass; the URL path itself is the evidence)
Source tier: primary
Source content: URL path on the Institute's own domain explicitly contains "2021/09" and "Final-report".
Comparison: The note's claims (hosted on the Institute's site; September 2021 version) match the URL's structural evidence. Single primary evidence item.
Decision: primary-sourced

## Claim 18: scalar:sources[2].note — "November 2021 reissue of the report PDF hosted on the Institute's site"

Source: https://www.adalovelaceinstitute.org/wp-content/uploads/2021/11/ADA_Participatory-Data-Stewardship.pdf returned HTTP 403 to WebFetch this pass (also 403 in pass 1)
Source tier: none
Source content: Not retrievable. URL path encodes 2021/11 on the Institute's domain; no source consulted in this or the prior pass characterizes the November PDF as a "reissue" rather than a duplicate upload or alternate-filename copy.
Comparison: URL location and date are consistent with the note, but the "reissue" characterization is not verifiable from any retrievable source.
Decision: uncorroborated

## Claim 19: scalar:sources[3].note — "UK Statistics Authority's Centre for Applied Data Ethics blog — primary external source for the report's lead authorship by Reema Patel (then Associate Director, Engagement, at the Ada Lovelace Institute) and for the framework's adoption by a UK public body to shape research-and-statistics engagement guidance"

Source: https://uksa.statisticsauthority.gov.uk/news/involving-people-in-the-use-of-data-for-research-and-official-statistics-heres-how/
Source tier: primary
Source content: Page identifies Patel as "lead author of the Institute's report on participatory data stewardship" and "Associate Director (Engagement) at the Ada Lovelace Institute"; the Authority released "draft ethics guidance on considering public views and engagement in research and statistics projects" drawing on the framework.
Comparison: Every element of the scalar's claim is supported by the page itself (the page is the source the scalar describes).
Decision: primary-sourced

## Claim 20: scalar:sources[4].note — "The Living Library entry on the report — primary external source for the framework's anchoring in Sherry Arnstein's 'ladder of citizen participation' and for the 'over 100 case studies' methodology"

Source: https://thelivinglib.org/participatory-data-stewardship/
Source tier: database
Source content: "based on an analysis of over 100 case studies" and "drawing extensively from Sherry Arnstein's 'ladder of citizen participation' and its more recent adaptation into a spectrum."
Comparison: Both elements of the scalar's claim are present on the page it describes.
Decision: single-source

## Claim 21: scalar:sources[5].note — "Community Science Initiative entry — primary external source for the framework's five named tiers (inform, consult, involve, collaborate, empower) along an IAP2-style spectrum of public influence"

Source: https://communityscience.astc.org/resources/participatory-data-stewardship-a-framework-for-involving-people-in-the-use-of-data/
Source tier: database
Source content: "Informing > Consulting > Involving > Collaborating > Empowering" ordered "as defined by the Spectrum of Public Participation."
Comparison: Five tiers and the IAP2-style spectrum framing are present on the page the scalar describes.
Decision: single-source

## Claim 22: scalar:sources[6].note — "ICTlogy bibliography entry — formal citation as Patel, R. (2021) 'Participatory data stewardship: A framework for involving people in the use of data', Ada Lovelace Institute, London"

Source: https://ictlogy.net/works/reports/projects.php?idp=5828 returned HTTP 403 to WebFetch this pass (also 403 in pass 1)
Source tier: none
Source content: Not retrievable. The citation elements (Patel, 2021, full title, Ada Lovelace Institute, London) are independently consistent with the Community Science entry, but the scalar's claim is about what the ICTlogy page records, and that page was not retrievable.
Comparison: Substantive citation content is consistent across other sources; the page-specific claim cannot be compared directly.
Decision: uncorroborated

## Claim 23: scalar:sources[7].note — "ESRC Digital Good Network research page — records that the 2024–25 'Participatory and inclusive data stewardship' landscape review (co-produced with the Ada Lovelace Institute and the Liverpool City Region Civic Data Cooperative) explicitly builds on the 2021 report"

Source: https://digitalgood.net/research/participatory-and-inclusive-data-stewardship/ ; WebSearch this session (December 2024 publication of the landscape review)
Source tier: primary
Source content: Page: "We published a landscape review on participatory and inclusive data stewardship"; the research "builds upon a lead authored report on Participatory Data Stewardship (2022), published by the Ada Lovelace Institute"; Emily Rempel of the Liverpool City Region Civic Data Co-operative on the research team. Search: review published December 2024.
Comparison: The scalar's substantive content — review title, partnership composition, derivation from the prior report — matches the page it describes. The scalar's "2021" names the prior report's canonical year (the page's own "(2022)" is a year-attribution error, per Claim 15); within paraphrase tolerance for an attributional note.
Decision: corroborated

## Claim 24: scalar:sources[8].note — "Reema Patel's personal site — primary disclosure that she co-founded the Ada Lovelace Institute and established its work on public engagement and participation; lists Participatory Data Stewardship among her authored Ada Lovelace reports"

Source: https://www.reemapatel.org/
Source tier: primary
Source content: "She co-founded the Ada Lovelace Institute where she established its work on public engagement and participation." "She is an author of several Ada Lovelace Institute's reports, including Beyond Face Value, Rethinking Data, The Data Divide and Participatory Data Stewardship among others."
Comparison: The scalar (as corrected in commit df1affd7 per pass-1 Claim 24) now states both disclosures separately — co-founded the Institute; established its public-engagement work — matching the source. The report listing matches verbatim. Pass-1 correction cleared.
Decision: primary-sourced
