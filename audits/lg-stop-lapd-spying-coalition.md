---
entity_id: lg-stop-lapd-spying-coalition
entity_hash: 109787a57b3d5302f36967c67b9b3a5e739f076a
audit_date: 2026-06-04
pass: 1
status: discrepancy
claims_total: 28
claims_verified: 24
claims_discrepancy: 2
claims_unverifiable: 2
sources_consulted:
  - https://stoplapdspying.org/
  - https://stoplapdspying.org/about/
  - https://stoplapdspying.org/category/data-driven-policing/
  - https://stoplapdspying.org/architecture-of-surveillance/
  - https://stoplapdspying.org/contact/
  - https://automatingbanishment.org/
  - https://en.wikipedia.org/wiki/Geolitica
  - https://en.wikipedia.org/wiki/Predictive_policing
  - https://mediajustice.org/take-back-tech/
  - https://anthro.ucla.edu/people/p.-jeffrey-brantingham
---

## Claim 1: "founded in 2011"

Source: https://stoplapdspying.org/about/
Source content: "The Stop LAPD Spying Coalition is a community organization founded in 2011."
Comparison: Body's 2011 founding year matches source verbatim.
Decision: verified

## Claim 2: "fiscally sponsored by the Los Angeles Community Action Network"

Source: https://stoplapdspying.org/about/
Source content: "We are rooted in the Skid Row neighborhood of downtown Los Angeles, based out of the Los Angeles Community Action Network"; "make the check out to LA CAN (our fiscal sponsor)"
Comparison: Skid Row base and LA CAN fiscal sponsorship both confirmed.
Decision: verified

## Claim 3: scalar:sources[0].note + body — self-description "a community group building power toward abolition of the police state"

Source: https://stoplapdspying.org/
Source content: "a community group building power toward abolition of the police state"
Comparison: Exact verbatim match on the front page.
Decision: verified

## Claim 4: mission quote — "build community power toward abolishing police surveillance"

Source: https://stoplapdspying.org/about/
Source content: "We work to build community power toward abolishing police surveillance."
Comparison: Body's quoted mission language matches source verbatim.
Decision: verified

## Claim 5: body + scalar:sources[1].note — verbatim quote "beyond privacy concerns toward examining policing's deliberate harm toward Black and brown communities"

Source: https://stoplapdspying.org/about/
Source content: "expand narratives concerning surveillance beyond a narrow and privileged focus on privacy, legal rights, and national security policymaking, toward a more community-centered focus on policing's deliberate harm toward Black and brown communities"
Comparison: The body's body-prose quote and frontmatter sources[1].note both assert this is verbatim from /about/. The source's actual phrasing is "toward a more community-centered focus on policing's deliberate harm" — neither "beyond privacy concerns" alone nor "toward examining" appears. The quoted construction collapses the source's longer phrasing (which names privacy, legal rights, and national security policymaking) and substitutes "examining" for the source's "more community-centered focus on". The underlying framing is faithfully represented but the quoted text is not what the source says. Affects body §1 and sources[1].note.
Decision: discrepancy

## Claim 6: "the LAPD's 2019 cancellation of Operation LASER"

Source: https://stoplapdspying.org/category/data-driven-policing/
Source content: "helped frame our successful organizing to dismantle LASER (which LAPD ended in 2019)"
Comparison: Operation LASER discontinuance in 2019 confirmed by the Coalition's own programme archive.
Decision: verified

## Claim 7: "the LAPD's 2020 cancellation of PredPol"

Source: https://stoplapdspying.org/category/data-driven-policing/
Source content: "and PredPol (which LAPD stopped using in 2020)"
Comparison: PredPol discontinuance in 2020 confirmed.
Decision: verified

## Claim 8: "*Before the Bullet Hits the Body: Dismantling Predictive Policing in Los Angeles*" (May 2018)

Source: https://stoplapdspying.org/category/data-driven-policing/
Source content: "Our 2018 report Before the Bullet Hits the Body: Dismantling Predictive Policing in Los Angeles dissects the violence of these programs"
Comparison: Year 2018, title, and subtitle confirmed. The body asserts "May 2018" specifically; the cited source page only carries "2018" with no month. No additional canonical source consulted in this pass establishes the month.
Decision: unverifiable

## Claim 9: SAR criminalises "normal, innocent behaviors" (e.g. taking photographs, asking business hours)

Source: https://stoplapdspying.org/contact/
Source content: "SAR is a criminalization of normal, innocent behaviors" and "criminalization of normal behavior like taking a picture, asking businesses hours of operation, using a video camera, taking notes and other innocent behaviors"
Comparison: Quote and example behaviours confirmed. Photography and business-hours examples both present.
Decision: verified

## Claim 10: "82% of the SARs filed in the period reviewed had been on non-whites"

Source: https://stoplapdspying.org/contact/
Source content: "According to the Inspector General's audit, 82% of the SARs filed were of non-whites with the largest number being African Americans."
Comparison: Figure and direction confirmed.
Decision: verified

## Claim 11: "*The People's Audit* (2013)"

Source: https://stoplapdspying.org/category/data-driven-policing/
Source content: "Read more about our work against SAR, including our 2013 report The People's Audit"
Comparison: Title and year confirmed.
Decision: verified

## Claim 12: working method "collective study, community-based research, direct action"

Source: https://stoplapdspying.org/about/
Source content: "Collective study, community-based research, direct action are crucial to our work"
Comparison: Exact verbatim match.
Decision: verified

## Claim 13: Tuesday-night community meetings on Zoom; largely volunteer; community-donation funded

Source: https://stoplapdspying.org/
Source content: "Our weekly Tuesday night community meetings on Zoom are a great way to get to know us." / "Our work is largely funded through community donations. Your support is what makes our work sustainable."
Comparison: Tuesday-night Zoom format and community-donation funding model both confirmed.
Decision: verified

## Claim 14: PredPol co-founded in 2012 by Jeff Brantingham and George Mohler on an earthquake-aftershock prediction model

Source: https://en.wikipedia.org/wiki/Geolitica
Source content: "PredPol began as a project of the Los Angeles Police Department (LAPD) and University of California, Los Angeles professor Jeff Brantingham." Wikipedia further records the 2012 founding date, Mohler as co-founder, and the algorithm as "based on a model used to predict earthquake aftershocks".
Comparison: Founding year, founders' names, and earthquake-aftershock model basis all confirmed.
Decision: verified

## Claim 15: Jeff Brantingham described as "UCLA anthropologist"

Source: https://anthro.ucla.edu/people/p.-jeffrey-brantingham
Source content: P. Jeffrey Brantingham is a "Professor" in the "UCLA Department of Anthropology" with research interests in "Paleoanthropology, simulation modeling, carnivore ecology, hunter-gatherers, stone technology, evolutionary theory."
Comparison: Body cites Wikipedia for this claim, which does not establish the discipline ("University of California, Los Angeles professor" only). Cross-check with the UCLA Department of Anthropology faculty page confirms anthropologist as accurate. Within paraphrase tolerance.
Decision: verified

## Claim 16: George Mohler described as "mathematician"

Source: https://en.wikipedia.org/wiki/Geolitica (cited)
Source content: The cited Wikipedia article identifies Mohler as a PredPol co-founder but does not state his academic discipline or department.
Comparison: The cited source does not establish "mathematician" as Mohler's discipline. The Indiana University faculty URL attempted as cross-check returned 404; no other canonical source consulted this pass establishes the descriptor.
Decision: unverifiable

## Claim 17: 2019 LAPD internal audit found "insufficient data to determine if PredPol software helped reduce crime"

Source: https://en.wikipedia.org/wiki/Geolitica
Source content: "In March 2019, the LAPD's internal audit concluded that there were insufficient data to determine if PredPol software helped reduce crime."
Comparison: Quote and 2019 timing confirmed; source specifies March 2019.
Decision: verified

## Claim 18: independent investigative work documented PredPol "perpetuates racial biases by targeting Latino and Black neighborhoods"

Source: https://en.wikipedia.org/wiki/Geolitica
Source content: "a report was published by Gizmodo and The Markup indicating that PredPol perpetuated racial biases by targeting Latino and Black neighborhoods, while crime predictions for white middle- to upper-class areas were absent."
Comparison: Body cites the verbatim "perpetuates" phrasing; Wikipedia uses past tense "perpetuated" — within paraphrase tolerance. Claim attribution (Gizmodo / The Markup) consistent.
Decision: verified

## Claim 19: structural-mathematics critique "a neighborhood monitored four times as intensively can see over twenty times more false flags"

Source: https://en.wikipedia.org/wiki/Predictive_policing
Source content: "A neighborhood monitored four times as intensively can see over twenty times more false flags."
Comparison: Exact verbatim match.
Decision: verified

## Claim 20: "Santa Cruz, California's June 2020 ban on predictive policing (the first US municipal ban)"

Source: https://en.wikipedia.org/wiki/Predictive_policing
Source content: "the Santa Cruz City Council voted in favor of a complete ban on the use of predictive policing technology" (June 2020); also cited in the article as "the first U.S. city to ban predictive policing".
Comparison: Date, vote, and "first US city" status all present in the cited Wikipedia article.
Decision: verified

## Claim 21: "2020 boycott of predictive-policing work by 1,500+ mathematicians"

Source: https://en.wikipedia.org/wiki/Predictive_policing
Source content: "In 2020, following protests against police brutality, a group of mathematicians published a letter in Notices of the American Mathematical Society urging colleagues to stop work on predictive policing. Over 1,500 other mathematicians joined the proposed boycott."
Comparison: 2020 timing, mathematician constituency, "1,500+" figure all verified.
Decision: verified

## Claim 22: PredPol rebranded as Geolitica; acquired by SoundThinking in August 2023; operations ceasing by end of 2023

Source: https://en.wikipedia.org/wiki/Geolitica
Source content: "In an August 2023 earnings call, the CEO of SoundThinking announced that the company had begun the process of absorbing parts of Geolitica…According to SoundThinking, Geolitica would cease operations at the end of 2023."
Comparison: Wikipedia article's title "Geolitica" establishes the rebrand; acquisition timing and end-of-2023 wind-down confirmed.
Decision: verified

## Claim 23: Operation LASER was "Palantir-backed"

Source: https://automatingbanishment.org/ (and content under /section/)
Source content: The report explicitly names Palantir alongside Operation LASER within its analytical scope; the Coalition's own scoping of the report names Palantir as backing the LASER place-and-person targeting framework.
Comparison: The Coalition's own report substantiates the Palantir backing of Operation LASER.
Decision: verified

## Claim 24: scalar:sources[4].note + body — *Automating Banishment* Part 5 is titled "Operation LASER's Racial Terror"

Source: https://automatingbanishment.org/
Source content: The report's Part 5 page is titled "Racial Terror and White Wealth in South Central"; "Operation LASER's Racial Terror" appears as a named subsection within that Part 5, not as the Part's title.
Comparison: Body asserts (and frontmatter sources[4].note redoubles the assertion) that Part 5 itself is titled "Operation LASER's Racial Terror." Source establishes Part 5's actual title as "Racial Terror and White Wealth in South Central," with "Operation LASER's Racial Terror" being a subsection inside that Part. The named subsection exists; the conflation of subsection title with Part title is the discrepancy. Affects body §"Automating Banishment — surveillance and land" and frontmatter sources[4].note.
Decision: discrepancy

## Claim 25: *Automating Banishment* (November 2021) produced by Stop LAPD Spying Coalition's Land and Policing Workgroup; "envisioned, researched, drafted, and edited by dozens of people"

Source: https://automatingbanishment.org/
Source content: Title and subtitle confirmed verbatim; report attributed to "Stop LAPD Spying Coalition's Land and Policing Workgroup"; "envisioned, researched, drafted, and edited by dozens of people"; cover art carries November 2021 release.
Comparison: All three sub-claims (authorship, workgroup, date) confirmed.
Decision: verified

## Claim 26: Architecture of Surveillance (AOS) launched 22 October 2024; 52-article database mapping LAPD's surveillance infrastructure

Source: https://stoplapdspying.org/architecture-of-surveillance/
Source content: "The platform contains a database of 52 articles (pages) about LAPD's surveillance architecture"; page is dated October 22, 2024.
Comparison: Article-count figure verified; the October 22, 2024 date matches the body's "launched 22 October 2024" within paraphrase tolerance (page-dated launch announcement framing common for project landing pages).
Decision: verified

## Claim 27: May 2023 family-policing report "DCF(S) STANDS FOR DIVIDING AND CONQUERING FAMILIES"; May 2022 Echo Park Lake surveillance-camera lawsuit; August 2021 fusion-centers and federal-schools report

Source: https://stoplapdspying.org/architecture-of-surveillance/
Source content: "DCF(S) STANDS FOR DIVIDING AND CONQUERING FAMILIES" posted May 14, 2023; "Lawsuit Challenging LAPD's Refusal to Identify Echo Park Cameras" dated May 5, 2022; "PT 69: Abolish Fusion Centers and Kick the Feds Out of Schools" dated August 8, 2021.
Comparison: All three adjacent publications confirmed with month-precise dates matching the body's month-level granularity.
Decision: verified

## Claim 28: Take Back Tech 2024 in Chicago — 450 participants, 136 US cities, 4 countries; Coalition led workshop on COVID-19 public-health data expanding the surveillance state; partners include Mijente, Carceral Tech Resistance Network, Accountable Tech, Advancement Project, Just Futures Law, Athena Coalition

Source: https://mediajustice.org/take-back-tech/
Source content: "Take Back Tech 2024 is our second convening for organizers, advocates, academics, and workers"; "How Public Health data and crises like the COVID-19 pandemic expand the surveillance state" by the Stop LAPD Spying Coalition; "Mijente and MediaJustice hosted 40 workshops with 70+ presenters, 4 plenary panels, and close to 450 participants. We had folks participating from across 136 cities in the U.S. and 4 other countries"; partners listed include Carceral Tech Resistance Network, Accountable Tech, Advancement Project (with Puente Human Rights Movement), Just Futures Law, Athena Coalition (with Missouri Workers Center).
Comparison: All numeric and partner-list claims confirmed; Coalition workshop title verbatim match. The body's reduced partner list correctly captures the named entities (Puente Human Rights Movement and Missouri Workers Center omitted but the named six are accurately listed).
Decision: verified
