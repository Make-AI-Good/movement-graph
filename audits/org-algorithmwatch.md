---
entity_id: org-algorithmwatch
entity_hash: d6a9244537f860a3134e0eb37d4337f176634000
audit_date: 2026-06-10
pass: 2
status: supported
claims_total: 29
claims_corroborated: 5
claims_primary_sourced: 20
claims_single_source: 1
claims_uncorroborated: 3
open_corrections: 0
sources_consulted:
  - https://algorithmwatch.org/de/wer-steht-hinter-algorithmwatch/
  - https://algorithmwatch.org/en/team/
  - https://algorithmwatch.org/en/team/matthias-spielkamp/
  - https://algorithmwatch.org/en/transparency/
  - https://algorithmwatch.org/en/ueber-kontakt/
  - https://de.wikipedia.org/wiki/AlgorithmWatch
  - https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/
  - https://openschufa.de/english/
  - https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
  - https://blog.okfn.org/2018/02/22/we-crack-the-schufa-the-german-credit-scoring/
  - https://algorithmwatch.org/en/instagram-research-shut-down-by-facebook/
  - https://www.theregister.com/2021/08/13/algorithmwatch_shut_down/
  - https://dataskop.net/
  - https://algorithmwatch.org/en/automating-society-2020/
  - https://algorithmwatch.org/en/eu-ai-act/
  - https://algorithmwatch.org/en/eu-artificial-intelligence-act-for-fundamental-rights/
  - https://algorithmwatch.org/en/launch-algorithmwatch-switzerland/
  - https://algorithmwatch.ch/en/about/
  - https://algorithmwatch.ch/en/
  - https://www.lto.de/recht/nachrichten/n/bgh-urteil-vi-zr-156-13-schufa-auskunft-scoreformel
  - https://en.wikipedia.org/wiki/Schufa
---

Pass-2 re-audit (inbox `[work]` item, editor obs 2026-06-10). The pass-1 open correction — body's "123 organisations" vs the cited source's 115 — is verified fixed in both body and `sources[14].note` (researcher commit 8644ee4f); see Claim 24. The only other entity changes since pass 1 are the `strategies:` frontmatter list (entity IDs, not prose claims) and a body link on Spielkamp's name. Decisions below apply the 2026-06-10 vocabulary directly (claims resting on one primary source are `primary-sourced`, not `corroborated`). Pass 2 also extracts four claims pass 1 missed (Claims 26–29). English Wikipedia page for AlgorithmWatch still returns 404; German Wikipedia exists and is used under the tiebreaker rules.

## Claim 1: "AlgorithmWatch was founded as a non-profit gGmbH in 2017 in Berlin (the charitable-status determination was issued on 14 July 2017)"

Source: https://algorithmwatch.org/de/wer-steht-hinter-algorithmwatch/
Source tier: primary
Source content: "AW AlgorithmWatch gGmbH, Boyenstraße 41, 10115 Berlin, gegründet 2017"; charitable determination dated 14 July 2017 ("Aktueller Bescheid nach § 60a Abs. 1 AO").
Comparison: Year, legal form, city, and determination date all match the org's own transparency page. German Wikipedia independently confirms the 2017 gGmbH founding ("Die Gründung der dazugehörigen gGmbH erfolgte dann 2017") but not the 14 July determination date, so the full claim rests on one primary source.
Decision: primary-sourced

## Claim 2: "building on a 2016 public-launch announcement at the re:publica conference"

Source: https://de.wikipedia.org/wiki/AlgorithmWatch
Source tier: tiebreaker
Source content: "AlgorithmWatch wurde 2016 von Matthias Spielkamp, Katharina Anna Zweig, Lorena Jaume-Palasí und Lorenz Matzat in Berlin gegründet, was sie auf der re:publica 2016 verkündeten."
Comparison: The announcement of an initiative at a named public conference is a date-of-public-event claim, for which Wikipedia-alone is sufficient under the source rule. The org's own page (ueber-kontakt) dates the initiative's founding to "Ende 2015", which is consistent with a public announcement at re:publica in May 2016. Pass-1 `uncorroborated` resolves: German Wikipedia (not checked at pass 1) confirms.
Decision: single-source

## Claim 3: "The originating founders included journalist and digital-rights researcher Matthias Spielkamp, data journalist Lorenz Matzat, computer scientist Katharina Anna Zweig, and ethicist Lorena Jaume-Palasí"

Source: https://algorithmwatch.org/en/ueber-kontakt/
Source tier: primary
Source content: "AlgorithmWatch wurde Ende 2015 gegründet als eine Initiative von Lorena Jaume-Palasí, Lorenz Matzat, Matthias Spielkamp und Katharina Anna Zweig."
Comparison: All four named founders confirmed by the org's own about page; German Wikipedia independently names the same four ("wurde 2016 von Matthias Spielkamp, Katharina Anna Zweig, Lorena Jaume-Palasí und Lorenz Matzat ... gegründet"). Two canonical sources. Pass-1 `uncorroborated` resolves: pass 1 had only checked the shareholder page, which names current shareholders, not originating founders.
Decision: corroborated

## Claim 4: "Spielkamp and Matzat remain the equal-partner shareholders of the gGmbH and Spielkamp serves as Executive Director"

Source: https://algorithmwatch.org/de/wer-steht-hinter-algorithmwatch/
Source tier: primary
Source content: "Gleichberechtigte Gesellschafter: Lorenz Matzat und Matthias Spielkamp." "Geschäftsführung: Matthias Spielkamp." (ueber-kontakt page concurs: "Gesellschafter Lorenz Matzat und Matthias Spielkamp; Geschäftsführer ist Matthias Spielkamp.")
Comparison: Shareholders and Executive Director match. Both confirming pages are the org's own site, so this is one primary source, not two independent ones.
Decision: primary-sourced

## Claim 5: "By 2022 it reported €1.1 million in grant revenue"

Source: https://algorithmwatch.org/en/transparency/
Source tier: primary
Source content: Grants 2022: "1.118.777,59 €".
Comparison: €1,118,778 rounds to €1.1 million; matches.
Decision: primary-sourced

## Claim 6: "and a staff of roughly 25 across the German and Swiss entities" (by 2022)

Source: https://algorithmwatch.org/en/transparency/
Source tier: none
Source content: "Employees (full-time/part-time) and interns: 20" as of February 2024.
Comparison: The cited transparency page gives 20 employees as of Feb 2024, not 25 across both entities by 2022; no canonical source consulted gives a combined-entity 2022 headcount of ~25. Not contradicted (the Swiss entity's staff could close the gap), but not confirmable. Unchanged from pass 1.
Decision: uncorroborated

## Claim 7: Senior leadership composition — Spielkamp Executive Director; Müller Executive Board Member and ED of AlgorithmWatch CH; Hübner Deputy Director; Vieth-Ditlmann Head of Policy; Marsh Head of Tech Research; Kayser-Bril Head of Journalism; Galla Head of Communications & Campaigns

Source: https://algorithmwatch.org/en/team/
Source tier: primary
Source content: "Executive Director, Co-Founder & Shareholder ... Matthias Spielkamp"; "Executive Board Member | Executive Director AlgorithmWatch CH: Dr. Angela Müller"; "Deputy Director: Kristina Hübner"; "Head of Policy: Kilian Vieth-Ditlmann"; "Head of Tech Research: Dr. Oliver Marsh"; "Head of Journalism: Dr. Nicolas Kayser-Bril"; "Head of Communications & Campaigns: Nina Galla".
Comparison: All seven named roles match the org's own team page.
Decision: primary-sourced

## Claim 8: Function-area structure — Policy, Tech Research, Journalism, Communications & Campaigns, Operations

Source: https://algorithmwatch.org/en/team/
Source tier: primary
Source content: Team page carries the five corresponding department heads — Head of Policy, Head of Tech Research, Head of Journalism, Head of Communications & Campaigns, Head of Operations (Kathleen Georgi).
Comparison: The five function areas correspond one-to-one to the five named department-head roles on the org's own page.
Decision: primary-sourced

## Claim 9: Spielkamp "serves on the governing board of the German section of Reporters Without Borders and of Stiftung Warentest, holds an Expert Committee role at Germany's UNESCO Commission, sat on the Global Partnership on AI from 2020 to 2022, and was appointed to the German Digital Services Coordinator advisory council for the 2024–2026 term"

Source: https://algorithmwatch.org/en/team/matthias-spielkamp/
Source tier: primary
Source content: "governing boards of the German section of Reporters Without Borders" and Stiftung Warentest; "Expert Committee on Communication/Information of Germany's UNESCO Commission"; Global Partnership on AI "2020-2022"; DSC advisory council "from 2024-2026, elected by the German Bundestag".
Comparison: All five roles and date ranges match the org's own staff page.
Decision: primary-sourced

## Claim 10: "OpenSCHUFA (February–November 2018)"

Source: https://blog.okfn.org/2018/02/22/we-crack-the-schufa-the-german-credit-scoring/
Source tier: primary
Source content: "Last week the Open Knowledge Foundation Germany (OKFDE) and AlgorithmWatch launched the project OpenSCHUFA" (post dated 22 February 2018 — launch ~mid-February 2018). AlgorithmWatch's OpenSCHUFA page: "final evaluation in November 2018".
Comparison: February start now confirmed by the co-running organisation's own blog (a source not consulted at pass 1); November endpoint confirmed by AlgorithmWatch's own pages. Pass-1 `uncorroborated` resolves. Note: scalar:sources[6].note says "May 2018 launch via Startnext crowdfunding" — the cited page ties May 2018 to the data-donation platform going live ("Once the data donation platform is ready in May 2018 ... you'll be able to upload your credit record"), while the project/crowdfunding launch was February; "launch" is ambiguous between the two events, so no correction is asserted for the scalar.
Decision: primary-sourced

## Claim 11: OpenSCHUFA "Run jointly with the Open Knowledge Foundation Germany"

Source: https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/
Source tier: primary
Source content: "Open Knowledge Foundation Germany okfn.de" co-initiated the project. OKF's own blog: "the Open Knowledge Foundation Germany (OKFDE) and AlgorithmWatch launched the project OpenSCHUFA."
Comparison: Confirmed by both partner organisations' own pages — two independent canonical sources.
Decision: corroborated

## Claim 12: OpenSCHUFA "generated more than 4,000 donated SCHUFA records"

Source: https://openschufa.de/english/
Source tier: primary
Source content: "more than 4,000 people to provide us with their SCHUFA information".
Comparison: Match against the campaign's own site.
Decision: primary-sourced

## Claim 13: OpenSCHUFA "prompted more than 30,000 subject-access requests to SCHUFA"

Source: https://openschufa.de/english/
Source tier: primary
Source content: "more than 100,000 subject data requests to credit scoring companies", of them "30,000 to SCHUFA".
Comparison: Match against the campaign's own site.
Decision: primary-sourced

## Claim 14: OpenSCHUFA findings "published in November 2018... in partnership with data journalists at Bayerischer Rundfunk and Spiegel Online"

Source: https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
Source tier: primary
Source content: Results published November 28–29, 2018; "Spiegel Online and Bayerischer Rundfunk conducted the analysis of approximately 2,000 donated credit reports."
Comparison: Date and both media partners match.
Decision: primary-sourced

## Claim 15: "underlying scoring algorithm itself remained legally protected as a trade secret"

Source: https://www.lto.de/recht/nachrichten/n/bgh-urteil-vi-zr-156-13-schufa-auskunft-scoreformel
Source tier: mainstream
Source content: BGH ruling VI ZR 156/13 (28 January 2014): SCHUFA's score formula remains protected as a trade secret and need not be disclosed — "Der Gesetzgeber habe diese Norm mit der Intention erlassen, Geschäftsgeheimnisse zu schützen." openschufa.de confirms the algorithm remained opaque after the campaign ("unable to come up with the kind of evidence that will stand up in court").
Comparison: The legal trade-secret protection is confirmed by specialist legal-news reporting of the BGH ruling, and the campaign's own site confirms the algorithm remained opaque — two independent canonical sources. Pass 1 passed this on paraphrase tolerance from openschufa.de alone; pass 2 grounds the "legally protected" token directly.
Decision: corroborated

## Claim 16: Instagram newsfeed monitoring "(March 2020–July 2021)"; launched 3 March 2020; shut down 13 July 2021

Source: https://algorithmwatch.org/en/instagram-research-shut-down-by-facebook/
Source tier: primary
Source content: "Project Launch Date: March 3, 2020"; "Shutdown Date: July 13, 2021". The Register independently: "On 13 July, we took the decision to terminate the project and delete any collected data."
Comparison: Exact match. Shutdown date is independently corroborated by The Register; the launch date rests on the org's own page, so the composite claim is primary-sourced.
Decision: primary-sourced

## Claim 17: Instagram project "1,500 volunteers" and "Section 3.2.3 of its Terms of Service" alleged breach

Source: https://algorithmwatch.org/en/instagram-research-shut-down-by-facebook/
Source tier: primary
Source content: "Approximately 1,500" volunteers; Section 3.2.3 — "may not access or collect data from [Facebook's products] using automated means".
Comparison: Both tokens match the org's own account. The Register gives "over 1,400 volunteers" (consistent, not exact) and does not name the ToS section, so the composite rests on the primary source.
Decision: primary-sourced

## Claim 18: Instagram quote — "an organisation the size of AlgorithmWatch cannot risk going to court against a company valued at one trillion dollars"

Source: https://algorithmwatch.org/en/instagram-research-shut-down-by-facebook/
Source tier: primary
Source content: "an organization the size of AlgorithmWatch cannot risk going to court against a company valued at one trillion dollars" — quoted identically by The Register.
Comparison: Exact match in the org's own statement and in independent mainstream reporting (US/UK spelling difference is paraphrase tolerance).
Decision: corroborated

## Claim 19: "In May 2021 — shortly after Facebook had shut down NYU's Ad Observatory project on similar grounds — Facebook approached AlgorithmWatch"

Source: https://algorithmwatch.org/en/instagram-research-shut-down-by-facebook/
Source tier: primary
Source content: Facebook's approach: "Early May 2021". The Register: AlgorithmWatch went public after Facebook shut down the NYU project "earlier that month" (i.e. August 2021, after AlgorithmWatch's own July termination).
Comparison: The "May 2021" approach is now confirmed by the org's own page (an improvement over pass 1). But the framing "shortly after Facebook had shut down NYU's Ad Observatory" still conflicts with the sources: the NYU account shutdown occurred in early August 2021, *after* the May 2021 approach. The clause may intend Facebook's earlier (October 2020) cease-and-desist letter to NYU, but no source consulted confirms that chronology, and "shortly after" has no single-token replacement — so this stays a judgment-loaded conflict, not a correction.
Decision: uncorroborated

## Claim 20: DataSkop "five-organisation consortium with Europa-Universität Viadrina, Fachhochschule Potsdam, Universität Paderborn, and Mediale Pfade, funded by the Federal Ministry of Education and Research (BMBF) under the 'Mensch-Technik-Interaktion für digitale Souveränität' programme"

Source: https://dataskop.net/
Source tier: primary
Source content: "AlgorithmWatch, der Europa-Universität Viadrina, der Fachhochschule Potsdam, der Universität Paderborn und dem Verein Mediale Pfade"; funded by "das Bundesministerium für Bildung und Forschung (BMBF) im Rahmen des Programms Mensch-Technik-Interaktion für digitale Souveränität".
Comparison: All consortium members, funder, and programme name match the project's own site.
Decision: primary-sourced

## Claim 21: DataSkop "TikTok (data collection January–April 2023), the latter yielding insufficient data for reliable conclusions"

Source: https://dataskop.net/
Source tier: primary
Source content: Data collection "vom 26. Januar bis zum 21. April 2023"; "Unsere Untersuchung zu TikTok führte zu keinen belastbaren Erkenntnissen" — due to insufficient data donations.
Comparison: Date range and the no-reliable-findings outcome match.
Decision: primary-sourced

## Claim 22: Automating Society Report 2020 — "28 October 2020, in partnership with the Bertelsmann Stiftung" mapping "sixteen European countries"

Source: https://algorithmwatch.org/en/automating-society-2020/
Source tier: primary
Source content: Published October 28, 2020; "The new report by AlgorithmWatch and Bertelsmann Stiftung ... covers the current use of and policy debates around ADM systems in 16 European countries and at EU level."
Comparison: Date, partner, and country count match.
Decision: primary-sourced

## Claim 23: EU AI Act consultation response "August 2021"; positions on biometric mass-surveillance ban, impact-based regulation, fundamental-rights impact assessments, worker information rights, public-interest data-access frameworks

Source: https://algorithmwatch.org/en/eu-ai-act/
Source tier: primary
Source content: Response dated August 4, 2021; "Comprehensively ban all uses of biometric recognition systems in public space that can lead to mass surveillance"; "the *impact* such system has on individuals and society should be the decisive factor"; mandatory impact assessments "for every system deployed by public or private actors"; workers should "obtain information about the purpose of systems covered under this Act"; "legally binding data access frameworks ... supporting and enabling public interest research".
Comparison: Date and all five policy positions match the org's own position page.
Decision: primary-sourced

## Claim 24: November 2021 joint civil-society statement "An EU Artificial Intelligence Act for Fundamental Rights", co-drafted, "signed by 115 organisations including European Digital Rights (EDRi) and Access Now"

Source: https://algorithmwatch.org/en/eu-artificial-intelligence-act-for-fundamental-rights/
Source tier: primary
Source content: Statement dated November 30, 2021; "115 organizations" signed; "drafted by European Digital Rights (EDRi), Access Now, Panoptykon Foundation, epicenter.works, AlgorithmWatch, ..."; EDRi and Access Now both among signatories.
Comparison: The pass-1 correction (body said 123; source says 115) is verified FIXED — body and scalar:sources[14].note both now read 115, matching the source. The "co-drafted" token is also confirmed (AlgorithmWatch named among drafters). Correction cleared.
Decision: primary-sourced

## Claim 25: AlgorithmWatch Switzerland — "launched on 20 November 2020 in Zurich as a legally independent Swiss organisation under founding managing director Dr. Anna Mätzener (Angela Müller subsequently took on the Executive Director role), with seed funding from the Engagement Migros development fund"

Source: https://algorithmwatch.org/en/launch-algorithmwatch-switzerland/
Source tier: primary
Source content: Launch November 20, 2020 as "a Swiss organization with its own team"; "Managing director of AlgorithmWatch Switzerland is Dr. Anna Mätzener"; "supported by the Engagement Migros development fund". algorithmwatch.ch: "AlgorithmWatch is a non-governmental, non-profit organization based in Zurich and Berlin." Team page: Müller is "Executive Director AlgorithmWatch CH".
Comparison: Launch date, founding director, seed funder, Zurich seat, and Müller's subsequent ED role all confirmed — but every confirming page belongs to the AlgorithmWatch organisation family, so this is one primary source, not independent corroboration.
Decision: primary-sourced

## Claim 26: "Its flagship product is the Atlas of Automation, a public database of algorithmic systems in use in Switzerland, and it is supported by the Mercator Foundation Switzerland, the Christoph Merian Foundation, the Ernst Göhner Foundation"

Source: https://algorithmwatch.ch/en/about/
Source tier: primary
Source content: Atlas of Automation is "a directory of examples of algorithmic systems that are used in Switzerland, whether by government agencies or the private sector"; supporters listed include Mercator Foundation Switzerland, Christoph Merian Foundation, Ernst Göhner Foundation.
Comparison: Atlas description and the three named foundations match the Swiss entity's own about page. (New claim — not extracted at pass 1.)
Decision: primary-sourced

## Claim 27: "and the Hasler Foundation (for the RAISD democracy-and-AI project)"

Source: https://algorithmwatch.ch/en/about/
Source tier: primary
Source content: Supporters list includes "Hasler Foundation" (alongside ClimaNow and Democracy Foundation Basel); the page does not attach the Hasler support to a project named RAISD.
Comparison: Hasler Foundation as supporter is confirmed; the parenthetical attribution to a "RAISD democracy-and-AI project" is not found on the current page and no other canonical source consulted confirms it. Partial confirmation. (New claim — not extracted at pass 1.)
Decision: uncorroborated

## Claim 28: SCHUFA — "whose scores effectively gate rental tenancies, mobile-phone contracts, and consumer credit for some seventy million adults"

Source: https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/
Source tier: primary
Source content: "SCHUFA holds data on round about 70 million people in Germany. That's nearly everyone in the country aged 18 or older"; "landlords will refuse to rent you an apartment, banks will reject your credit card application and network providers will say 'no' to a new Internet contract." English Wikipedia (Schufa): "over 1.2 billion records on 69 million natural persons".
Comparison: The ~70-million figure and the rental/phone/credit gating both match the entity's cited source, with Wikipedia's 69-million figure consistent as a tiebreaker alongside it. (New claim — not extracted at pass 1.)
Decision: corroborated

## Claim 29: Instagram findings — "the recommendation algorithm preferred posts showing particular body presentations and dampened the reach of textual political content"

Source: https://algorithmwatch.org/en/instagram-research-shut-down-by-facebook/
Source tier: primary
Source content: "Instagram likely encouraged content creators to post pictures that fit specific representations of their body"; "politicians were likely to reach a larger audience if they abstained from using text in their publications." (Facebook "denied both claims".)
Comparison: Both findings match the org's own account of its published research; the body's hedged framing ("preferred", "dampened") is within paraphrase tolerance of the source's "likely" findings. (New claim — not extracted at pass 1.)
Decision: primary-sourced
