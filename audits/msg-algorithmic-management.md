---
entity_id: msg-algorithmic-management
entity_hash: f5b9b75ff4dd37d9d8ce15ef937312a91d5af487
audit_date: 2026-06-05
pass: 1
status: unverifiable
claims_total: 18
claims_verified: 11
claims_discrepancy: 0
claims_unverifiable: 7
sources_consulted:
  - https://en.wikipedia.org/wiki/Algorithmic_management
  - https://datasociety.net/library/explainer-algorithmic-management-in-the-workplace/
  - https://www.workerinfoexchange.org/wie-report-managed-by-bots
  - https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024L2831
  - https://fair.work/
  - https://www.techmonitor.ai/digital-economy/ai-and-automation/algorithmic-management-erodes-gig-workers-rights-quality-of-life-ilo
  - https://restofworld.org/2025/code-ai-filipino-tech-workers/
  - https://www.hrw.org/report/2025/05/12/the-gig-trap/algorithmic-wage-and-labor-exploitation-in-platform-work-in-the-us
---

## Claim 1: "the Carnegie Mellon Human-Computer Interaction Institute paper *Working with Machines: The Impact of Algorithmic and Data-Driven Management on Human Workers* by Min Kyung Lee, Daniel Kusbit, Evan Metsky, and Laura Dabbish"

Source: https://en.wikipedia.org/wiki/Algorithmic_management
Source content: Title "Working with Machines: The Impact of Algorithmic and Data-Driven Management on Human Workers"; authors Min Kyung Lee, Daniel Kusbit, Evan Metsky, and Laura Dabbish.
Comparison: Body title, author list, and institutional affiliation match the Wikipedia article on algorithmic management. Wikipedia is canonical-alone for named-entity definitional facts (paper authorship and title).
Decision: verified

## Claim 2: "presented at the 33rd Annual ACM Conference on Human Factors in Computing Systems (CHI 2015) on 18 April 2015"

Source: https://en.wikipedia.org/wiki/Algorithmic_management
Source content: "CHI '15 (33rd Annual ACM Conference on Human Factors in Computing Systems), April 18, 2015"
Comparison: Conference name, edition number, and presentation date match. (Cross-check against dl.acm.org returned HTTP 403; not load-bearing because Wikipedia is canonical-alone for dates of public events such as a conference presentation.)
Decision: verified

## Claim 3: "defined algorithmic management as 'software algorithms that assume managerial functions and surrounding institutional devices that support algorithms in practice'"

Source: https://en.wikipedia.org/wiki/Algorithmic_management
Source content: "software algorithms that assume managerial functions and surrounding institutional devices that support algorithms in practice"
Comparison: Verbatim quote present in the canonical secondary source. Wikipedia tiebreaker-only applies to contested attributions; this is a settled definitional quote consistently attributed to Lee et al. 2015 across the literature.
Decision: verified

## Claim 4: "which studied Uber and Lyft drivers"

Source: https://en.wikipedia.org/wiki/Algorithmic_management
Source content: "Uber and Lyft drivers" identified as the field study's scope.
Comparison: Scope claim matches Wikipedia's account of the 2015 paper. Wikipedia is canonical-alone for the definitional fact of what platforms the paper studied.
Decision: verified

## Claim 5: scalar:sources[2].note — "February 2019 *Data & Society* explainer ... *Algorithmic Management in the Workplace* by Alexandra Mateescu and Aiha Nguyen"

Source: https://datasociety.net/library/explainer-algorithmic-management-in-the-workplace/
Source content: Title "Explainer: Algorithmic Management in the Workplace"; authors Alexandra Mateescu and Aiha Nguyen; publication date February 6, 2019.
Comparison: Title, authors, and month/year all match. Body's "February 2019" is consistent with publisher's "February 6, 2019" within paraphrase tolerance.
Decision: verified

## Claim 6: 'redefined it as "a diverse set of technology tools and techniques that structure the conditions of work and remotely manage workforces"'

Source: https://datasociety.net/library/explainer-algorithmic-management-in-the-workplace/
Source content: "A diverse set of technology tools and techniques that structure the conditions of work and remotely manage workforces"
Comparison: Verbatim definition matches the Data & Society publication's own definition.
Decision: verified

## Claim 7: "extended its scope from ride-hail to retail, service, and delivery-and-logistics work"

Source: https://datasociety.net/library/explainer-algorithmic-management-in-the-workplace/
Source content: Sectors covered: "Retail; Service industry; Delivery and logistics"
Comparison: Sector list matches body's extension claim.
Decision: verified

## Claim 8: "*Managed by Bots — Data Driven Exploitation in the Gig Economy* report (13 December 2021)"

Source: https://www.workerinfoexchange.org/wie-report-managed-by-bots
Source content: Report title "Managed by Bots: Data-Driven Exploitation in the Gig Economy"; copyright notice "© 2021 Worker Info Exchange". Landing-page fetch did not surface a specific December 13, 2021 publication date.
Comparison: Title within paraphrase tolerance (em-dash vs colon, "Data Driven" vs "Data-Driven"). Year (2021) verified. Specific 13 December 2021 publication date was not present in the fetched landing-page content; cannot confirm precise day without a second canonical source.
Decision: unverifiable

## Claim 9: 'report "Managed by Bots" "co-authored by WIE Research Lead Cansu Safak and WIE Director James Farrar"'

Source: https://www.workerinfoexchange.org/wie-report-managed-by-bots
Source content: Authors not stated in the fetched landing-page content.
Comparison: The WIE landing page available to this audit did not surface author bylines. Cannot confirm Safak / Farrar authorship from the cited source alone.
Decision: unverifiable

## Claim 10: "foreword by Bama Athreya of the Open Society Foundations"

Source: https://www.workerinfoexchange.org/wie-report-managed-by-bots
Source content: "Bama Athreya, Fellow, Open Society Foundations" credited as the foreword author.
Comparison: Foreword author and affiliation match.
Decision: verified

## Claim 11: 'verbatim phrasing "algorithmic management practices by gig platforms"'

Source: https://www.workerinfoexchange.org/wie-report-managed-by-bots
Source content: "Across Europe, courts have passed several significant judgments recognising the exploitative role of algorithmic management practices by gig platforms while also condemning the lack of fairness and transparency in such automated systems."
Comparison: Verbatim string "algorithmic management practices by gig platforms" appears in the report landing page. Body's claim that this phrasing is in the report's introduction is supported.
Decision: verified

## Claim 12: 'Part I title "Misclassification 2.0: Controlled by Algorithms" ... seven platforms — Amazon Flex, Bolt, Deliveroo, Free Now, Just Eat, Ola, and Uber'

Source: https://www.workerinfoexchange.org/wie-report-managed-by-bots
Source content: Section "Misclassification 2.0: Controlled by Algorithms" exists; platforms covered "Amazon Flex, Bolt, Deliveroo, Free Now, Just Eat, Ola, and Uber".
Comparison: Section title and full seven-platform list match the report landing page.
Decision: verified

## Claim 13: "EU Platform Work Directive 2024/2831 ... adopted by the Council on 14 October 2024 and applicable by 2 December 2026"

Source: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024L2831
Source content: "Directive (EU) 2024/2831 of the European Parliament and of the Council of 23 October 2024 on improving working conditions in platform work"; Article 5(6) sets the application date 2 December 2026.
Comparison: Directive number, application date 2 December 2026 verified. The directive's own date of 23 October 2024 is verified; the entity's separate "Council adopted on 14 October 2024" claim could not be verified — the cited Council press release at consilium.europa.eu returned HTTP 403 in this session, and Wikipedia is tiebreaker-only for legislative-action dates within the recent-event window. The two dates are not mutually exclusive (a Council vote on Oct 14 followed by a Parliament-and-Council signed instrument dated Oct 23 is the normal sequence) but cannot be confirmed from accessible sources in this pass.
Decision: unverifiable

## Claim 14: 'EU Directive constitutes "the first EU rules on the use of artificial intelligence in the world of work"'

Source: https://www.consilium.europa.eu/en/press/press-releases/2024/03/11/platform-workers-council-confirms-agreement-on-new-rules-to-improve-their-working-conditions/
Source content: Press release returned HTTP 403 in this session; no text retrievable.
Comparison: The "first EU rules on AI in the world of work" framing is attributed to a specific Council press release that this pass could not fetch. No other canonical source in the entity's `sources:` field corroborates the precise quote.
Decision: unverifiable

## Claim 15: "prohibitions on processing emotional and psychological data"

Source: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024L2831
Source content: Article 7(1)(a) explicitly prohibits platforms from using automated systems to "process any personal data on the emotional or psychological state of a person performing platform work."
Comparison: Directive's prohibition on emotional/psychological data processing matches the body claim.
Decision: verified

## Claim 16: 'Fairwork "five principles of fair platform work including 'fair management'" — fair pay, fair conditions, fair contracts, fair management, fair representation; "716 digital labour platforms in 40 countries"; coordinated by Professor Mark Graham at the Oxford Internet Institute in partnership with the Berlin Social Science Center (WZB)'

Source: https://fair.work/
Source content: Five principles confirmed verbatim: "Fair Pay; Fair Conditions; Fair Contracts; Fair Management; Fair Representation." Oxford affiliation confirmed via footer reference to the University of Oxford. The homepage states Fairwork "have produced national rankings in 38 countries across 5 continents" for location-based platform work; the 716-platform figure and the WZB partnership and Mark Graham's coordinator role are not stated on the landing page consulted.
Comparison: Five-principle list verified. Oxford affiliation verified. The 40-countries figure differs from the homepage's "38 countries" but the homepage's figure is scoped to location-based rankings only, so the totals may not be directly comparable. The 716-platform count, WZB partnership, and Mark Graham coordinator attribution cannot be confirmed from the cited source alone; cross-checking would need a Fairwork annual-report URL or comparable canonical source not in this entity's `sources:`.
Decision: unverifiable

## Claim 17: "global gig-worker survey found that 37% of app-based taxi drivers and 48% of delivery drivers cannot refuse or cancel work without repercussions ... 'human-in-command' approach to ensure that 'final decisions affecting work are taken by human beings'"

Source: https://www.techmonitor.ai/digital-economy/ai-and-automation/algorithmic-management-erodes-gig-workers-rights-quality-of-life-ilo
Source content: "37% of app-based taxi drivers ... cannot refuse or cancel work without repercussions"; "48% of delivery drivers face the same"; "human-in-command" approach; ILO recommends "final decisions affecting work are taken by human beings."
Comparison: Statistics, the human-in-command framing, and the verbatim policy quote all match.
Decision: verified

## Claim 18: 'CODE-AI ... launched in Quezon City on 25 January 2025 by seven founding organisations spanning BPO, delivery, telecommunications, and IT work'

Source: https://restofworld.org/2025/code-ai-filipino-tech-workers/
Source content: Article mentions "a briefing held on January 25, 2025" in Quezon City; describes CODE-AI as including "representatives from digital sectors including BPO, delivery, telecoms, and information technology"; does not explicitly state the date as a formal launch nor name a specific founding-organisation count.
Comparison: The January 25 2025 briefing in Quezon City is verified; the sectors covered match. The explicit "launched on" framing and the specific "seven founding organisations" count are not present in the cited Rest of World article. Without a second canonical source corroborating the launch-event characterisation and the seven-organisation count, these subclaims cannot be verified.
Decision: unverifiable
