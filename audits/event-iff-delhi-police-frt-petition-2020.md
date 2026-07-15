---
entity_id: event-iff-delhi-police-frt-petition-2020
entity_hash: 5cc12648b48a1e43a308904344442eb0bb5f7f0a
audit_date: 2026-07-15
pass: 1
status: supported
claims_total: 31
claims_corroborated: 20
claims_primary_sourced: 7
claims_single_source: 1
claims_uncorroborated: 3
open_corrections: 0
sources_consulted:
  - https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system
  - https://panoptic.in/case-study/delhi-police
  - https://panoptic.in/right-to-information/RTI-00005
  - https://panoptic.in/case-study/right-to-information-updates-from-delhi-police-kolkata-police-and-telangana-state-technology-services
  - https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/
  - https://m.thewire.in/article/economy/delhi-police-is-now-using-facial-recognition-software-to-screen-habitual-protestors
  - https://internetfreedom.in/we-demand-the-delhi-police-stop-its-facial-recognition-system/
  - https://internetfreedom.in/cic-directs-delhi-police-to-respond-to-frt-rti/
  - https://www.medianama.com/2022/08/223-delhi-police-iff-rti-facial-recognition-80-percent-accuracy-2/
  - https://theprint.in/india/dna-fingerprints-facial-recognition-used-to-probe-riots-cases-says-delhi-police-chief/608235/
  - https://www.theweek.in/news/india/2020/03/13/amit-shah-said-facial-recognition-identified-1900-delhi-rioters-how-does-technology-work.html
  - https://www.outlookindia.com/national/delhi-police-s-80-per-cent-match-of-facial-recognition-to-nab-accused-raises-concern-finds-rti-news-217182
  - https://www.commondreams.org/news/2019/12/31/act-mass-surveillance-india-use-facial-recognition-tech-against-protesters-angers
  - https://thewire.in/law/telangana-hc-issues-notice-on-pil-challenging-use-of-facial-recognition-technology
  - https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
  - https://en.wikipedia.org/wiki/Puttaswamy_v._Union_of_India
---

Connective type (event): claim surface is edges + hard specifics per `mission/MISSION.md § Auditor § Type-shape awareness`. Narrative significance prose without a hard specific carries no decision. Note: internetfreedom.in and medianama.com 403 on direct fetch — their content verified via search snippets (workbench-documented harness limit).

## Claim 1: edge — participating_orgs: org-internet-freedom-foundation

Source: https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system + https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/
Source tier: primary
Source content: Panoptic case study attributes the notice to IFF (author "Anushka Jain, Policy Counsel, IFF"); Inc42: "IFF sent notice to the secretary, Ministry of Home Affairs and the commissioner of Delhi Police"
Comparison: Edge resolves to org-internet-freedom-foundation ("Internet Freedom Foundation"); IFF as the acting org confirmed by its own case study and independent press.
Decision: corroborated

## Claim 2: edge — campaign: camp-iff-project-panoptic

Source: https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system
Source tier: primary
Source content: The legal notice is hosted and chronicled as a Project Panoptic case study on panoptic.in, IFF's Project Panoptic site
Comparison: Edge resolves to camp-iff-project-panoptic ("Internet Freedom Foundation Project Panoptic (2020–ongoing)"); the notice is documented within the campaign's own case-study corpus, supporting the membership edge on one primary source.
Decision: primary-sourced

## Claim 3: edge — related_events: event-iff-project-panoptic-launch-2020-11-27

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation (with Lawctopus/idtechwire coverage in search results)
Source tier: tiebreaker
Source content: "The Project debuted on November 27, 2020" (Project Panoptic launch)
Comparison: Edge resolves to the corpus launch-event entity (date: 2020-11-27); launch date is a named-entity/public-event date where Wikipedia-alone suffices per the source rule, and independent legal/tech press coverage (Lawctopus, idtechwire) confirms.
Decision: corroborated

## Claim 4: "On 28 December 2019 the Internet Freedom Foundation (IFF) sent a legal notice" (scalar:date = 2019-12-28; scalar:name includes "28 December 2019")

Source: https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system + https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/
Source tier: primary
Source content: Panoptic case study dates the legal notice December 28, 2019; Inc42 coverage published December 30, 2019 reports the notice
Comparison: Date matches IFF's own record and contemporaneous independent press.
Decision: corroborated

## Claim 5: scalar:location = "New Delhi, India"; scalar:event_type = "legal notice"

Source: https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system + https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/
Source tier: primary
Source content: Legal notice addressed to "Secretary, Ministry of Home Affairs and Commissioner of Police, Delhi" concerning Delhi Police's AFRS deployment in Delhi
Comparison: Both scalars consistent with the sources — the instrument is a legal notice and the subject deployment and addressees are in New Delhi.
Decision: corroborated

## Claim 6: "sent a legal notice to the Secretary, Ministry of Home Affairs and the Commissioner of Police, Delhi"

Source: https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system + https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/
Source tier: primary
Source content: Panoptic: addressed to "Secretary, Ministry of Home Affairs and Commissioner of Police, Delhi"; Inc42: "secretary, Ministry of Home Affairs and the commissioner of Delhi Police"
Comparison: Addressees match both sources exactly.
Decision: corroborated

## Claim 7: "demanding the complete halt and recall of Delhi Police's Automated Facial Recognition System (AFRS)"

Source: https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system + https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/
Source tier: primary
Source content: Panoptic: demanded "complete halt and recall of the AFRS"; Inc42: demanded they "halt the use of the facial recognition system"
Comparison: Demand matches the primary record verbatim; independent press confirms the halt demand.
Decision: corroborated

## Claim 8: "a system IFF called 'an illegal act of mass surveillance'"

Source: https://internetfreedom.in/we-demand-the-delhi-police-stop-its-facial-recognition-system/ (via search snippet; direct fetch 403) + https://www.commondreams.org/news/2019/12/31/act-mass-surveillance-india-use-facial-recognition-tech-against-protesters-angers
Source tier: primary
Source content: Search-snippet of IFF's post: IFF called this "an illegal act of mass surveillance"; Common Dreams headline: "'An Act of Mass Surveillance': India Use of Facial Recognition Tech Against Protesters"
Comparison: Quoted phrase confirmed in IFF's own announcement and echoed in contemporaneous independent coverage.
Decision: corroborated

## Claim 9: "The notice, authored by IFF Policy Counsel Anushka Jain"

Source: https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system
Source tier: primary
Source content: Notice author identified as "Anushka Jain, Policy Counsel, IFF"
Comparison: Author name and title match IFF's own case-study record; one primary source.
Decision: primary-sourced

## Claim 10: "with input from researchers Vidushi Marda and Srinivas Kodali"

Source: https://internetfreedom.in/we-demand-the-delhi-police-stop-its-facial-recognition-system/ (via search snippet; direct fetch 403)
Source tier: primary
Source content: "received inputs from researchers such as Vidushi Marda and Srinivas Kodali in helping to provide inputs for the notice"
Comparison: Both researcher names and their input role match IFF's own post; one primary source.
Decision: primary-sourced

## Claim 11: "was the first formal legal petition directed specifically at Delhi Police's expanding FRT use"

Source: no canonical source found
Source tier: none
Source content: No fetched source states a "first formal legal petition" claim for the Delhi Police AFRS specifically; IFF's own record references prior work including "a national facial recognition system notice to the NCRB" (panoptic.in case study)
Comparison: Contested "first" class per the source rule; no source asserts this superlative, and its truth depends on judgment about what counts as a "formal legal petition." Not a token error — no single correct replacement.
Decision: uncorroborated

## Claim 12: "eventually produced the Project Panoptic tracker (November 2020) and the S.Q. Masood Telangana High Court public-interest litigation (January 2022)" (also Significance: "the January 2022 Telangana High Court PIL brought by S.Q. Masood with IFF legal-counsel support")

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation + https://thewire.in/law/telangana-hc-issues-notice-on-pil-challenging-use-of-facial-recognition-technology
Source tier: mainstream
Source content: "The Project debuted on November 27, 2020"; The Wire/IFF: "The Telangana high court on January 3 [2022] issued notice to the state government on the PIL" by S.Q. Masood; "The Internet Freedom Foundation (IFF) provided legal support in the drafting of the petition"
Comparison: Both hard dates and the Masood/IFF-support specifics match multiple independent sources. ("Trajectory produced" framing is interpretive; the specifics are what is audited.)
Decision: corroborated

## Claim 13: "was sourced from M/s Innefu Labs Private Limited in March 2018"

Source: https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/ + https://panoptic.in/case-study/the-delhi-police-must-stop-its-facial-recognition-system
Source tier: primary
Source content: Inc42: AFRS "sourced from 'M/s Innefu Labs Private Limited'"; Delhi Police "obtained the system in March 2018" ostensibly "to identify missing children"; Panoptic names vendor "M/s Innefu Labs Private Limited"
Comparison: Vendor name and March 2018 acquisition match both sources.
Decision: corroborated

## Claim 14: "under the direction of the Delhi High Court in Sadhan Haldar v The State NCT of Delhi (WP(Crl) 1560/2017) — a 2017 petition seeking help to locate and reunite missing children ... authorised ... specifically for the purpose of tracking missing children"

Source: https://panoptic.in/case-study/delhi-police + search-snippet corroboration (internetfreedom.in, theweek.in)
Source tier: primary
Source content: "Sadhan Haldar v NCT of Delhi," purpose "tracking and re-uniting missing children"; search results confirm the docket "Sadhan Haldar v The State NCT of Delhi [WP(Crl) 1560/2017]" filed 2017 "for locating and reuniting missing children"
Comparison: Case name, docket number, year, and authorized purpose all match IFF's primary record and independent coverage.
Decision: corroborated

## Claim 15: "In a Right to Information response IFF obtained in February 2020, Delhi Police confirmed that the technology is being used to match similar faces for police investigation"

Source: https://panoptic.in/case-study/delhi-police
Source tier: primary
Source content: Delhi Police stated the technology was being used to "match similar faces for police investigation" — diverging from the court-authorized purpose of locating missing children (RTI response received February 2020)
Comparison: The quoted RTI-response language and February 2020 timing match the primary record (a government RTI reply as published by IFF); no independent second source fetched with the verbatim.
Decision: primary-sourced

## Claim 16: "reported deployment of the AFRS at Prime Minister Modi's rally at Ramlila Maidan, screening attendees against facial data collected from protest videos"

Source: https://m.thewire.in/article/economy/delhi-police-is-now-using-facial-recognition-software-to-screen-habitual-protestors + https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/
Source tier: mainstream
Source content: The Wire (Dec 29, 2019): Modi's Ramlila Maidan event (Dec 22, 2019) was "the first political event where the Automated Facial Recognition System was used to screen the crowd"; "all the footage collected by Delhi Police during protest demonstrations is now being fed to the AFRS, which extracts 'identifiable faces' of the protesters to its dataset." Inc42: "each attendee was recorded on the camera fitted on the metal detector gate. The live footage would then match attendees to the facial datasheet in five seconds."
Comparison: Ramlila Maidan deployment, attendee screening, and protest-footage-derived dataset all match two independent contemporaneous outlets.
Decision: corroborated

## Claim 17: "The system was also deployed during the protests against the Citizenship Amendment Act that ran through late 2019 and into early 2020"

Source: https://m.thewire.in/article/economy/delhi-police-is-now-using-facial-recognition-software-to-screen-habitual-protestors + https://www.commondreams.org/news/2019/12/31/act-mass-surveillance-india-use-facial-recognition-tech-against-protesters-angers
Source tier: mainstream
Source content: The Wire: the dataset "specifically included those protesting against the Citizenship (Amendment) Act (CAA) and National Register of Citizens (NRC)"; Common Dreams: FRT use against protesters, December 2019
Comparison: CAA-protest deployment window and use match two independent outlets.
Decision: corroborated

## Claim 18: "Delhi Police commissioner SN Shrivastava subsequently stating that 137 of 231 riot-related arrests were made with facial-recognition assistance following the February 2020 northeast Delhi communal violence"

Source: https://theprint.in/india/dna-fingerprints-facial-recognition-used-to-probe-riots-cases-says-delhi-police-chief/608235/ (via search snippet) + panoptic.in case-study record
Source tier: mainstream
Source content: "Delhi police commissioner SN Shrivastava stated that 231 people were arrested on the basis of CCTV or video footage and that 137 of those people were identified through the use of facial recognition technology" in connection with the northeast Delhi communal violence of February 2020
Comparison: Name, numbers (137 of 231), and February 2020 northeast Delhi context match. Nuance: the 231 were arrests based on CCTV/video footage in riots cases; body's "riot-related arrests" is a fair paraphrase, not a token error.
Decision: corroborated

## Claim 19: "Minister of Home Affairs Amit Shah separately stated over 1,900 faces had been identified through the system in connection with those events"

Source: https://panoptic.in/case-study/delhi-police + https://www.theweek.in/news/india/2020/03/13/amit-shah-said-facial-recognition-identified-1900-delhi-rioters-how-does-technology-work.html
Source tier: primary
Source content: Panoptic: "over 1,900 faces have been identified through facial recognition software for inciting violence in the national capital during the Delhi riots"; The Week (Mar 13, 2020): "Amit Shah said 'facial recognition' identified 1,900 Delhi rioters"
Comparison: Attribution and figure match primary record and independent press.
Decision: corroborated

## Claim 20: "the system operated at an accuracy rate of 2 per cent in 2018 and less than 1 per cent in 2019"

Source: https://internetfreedom.in/we-demand-the-delhi-police-stop-its-facial-recognition-system/ (via search snippet; direct fetch 403) + The Wire/Pulitzer Center coverage (search results)
Source tier: primary
Source content: "in 2018, Delhi Police reported that the facial recognition system on trial was operating at an accuracy rate of 2 per cent. In 2019, when the accuracy rate fell to less than 1 per cent..."; independent coverage: "In 2018, the Delhi Police informed the high court that its facial recognition software had an accuracy rate of just 2%. By 2019, this figure had dropped below 1%"
Comparison: Both figures and years match IFF's notice announcement and independent press coverage.
Decision: corroborated

## Claim 21: "a figure the Ministry of Women and Child Development had independently noted as insufficient to distinguish between boys and girls"

Source: https://internetfreedom.in/we-demand-the-delhi-police-stop-its-facial-recognition-system/ (via search snippet; direct fetch 403) + The Wire/Pulitzer Center coverage (search results)
Source tier: primary
Source content: "the Ministry of Women and Child Development reported that the system couldn't even accurately distinguish between boys and girls"
Comparison: MWCD attribution and the boys/girls specific match IFF's record and independent coverage.
Decision: corroborated

## Claim 22: "the proportionality test the Indian Supreme Court's landmark judgment in Justice K.S. Puttaswamy v. Union of India (2017) applies ... requires that any state intrusion on privacy have a lawful purpose, be limited to what is necessary for that purpose, and be subject to procedural safeguards"

Source: https://en.wikipedia.org/wiki/Puttaswamy_v._Union_of_India + https://translaw.clpr.org.in/case-law/justice-k-s-puttaswamy-anr-vs-union-of-india-ors-privacy/ (search results) + https://www.commondreams.org/news/2019/12/31/act-mass-surveillance-india-use-facial-recognition-tech-against-protesters-angers
Source tier: primary
Source content: "The invasion of privacy must meet three conditions: legality, the existence of a legitimate state aim, and proportionality"; the nine-judge bench held privacy protected under Article 21 (2017). IFF's notice argued FRT use is in "breach of the principle of proportionality"
Comparison: Case name, year, and the proportionality standard match public record (court-decision class where Wikipedia-alone suffices; multiple legal sources confirm); the notice's invocation of proportionality is confirmed in contemporaneous coverage. Body's "procedural safeguards" phrasing matches the judgment's articulated framework (Kaul J.'s formulation adds procedural safeguards) — a fair paraphrase.
Decision: corroborated

## Claim 23: "Delhi Police's initial response ... assert that the AFRS incorporated industry-standard checks and balances and to deny that the system engaged in racial or religious profiling, stating that the database it matched against targeted terror suspects and individuals with criminal records"

Source: https://inc42.com/buzz/iff-sends-legal-notice-to-govt-for-surveillance-using-facial-recognition/ + https://m.thewire.in/article/economy/delhi-police-is-now-using-facial-recognition-software-to-screen-habitual-protestors
Source tier: mainstream
Source content: Inc42: officials maintain "the best industry-standard checks and balances system"; "racial/religious profiling is not a relevant parameter here"; datasets built from "terror suspects," those with "criminal records," and "law and order suspects." The Wire: spokesperson denied "racial or religious profiling is never a relevant parameter"
Comparison: All three response elements match two independent outlets.
Decision: corroborated

## Claim 24: "On 24 January 2020 Anushka Jain filed a Right to Information request with Delhi Police (reference DEPOL/R/E/20/00519) covering eleven areas ... The February 2020 response" (also scalar:sources[4].note "February 24 2020 response date")

Source: https://panoptic.in/right-to-information/RTI-00005
Source tier: primary
Source content: "Date Filed: January 24, 2020; RTI Number: DEPOL/R/E/20/00519; Filed By: Anushka Jain, Policy Counsel at Internet Freedom Foundation; Response Received: February 24, 2020" — with eleven enumerated question areas (legal authorization, legal opinions, privacy assessments, SOPs, purposes, protest/rally monitoring, expenditure, Innefu tender documentation, authorized personnel, specifications, databases)
Comparison: Filing date, reference number, filer, eleven areas, and the February 24, 2020 response date (per scalar:sources[4].note) all match IFF's own RTI record; one primary source.
Decision: primary-sourced

## Claim 25: "On 23 October 2020 IFF filed a second batch of RTIs with Delhi Police (DEPOL/R/E/20/07128), Kolkata Police (initially filed 30 July 2020), and Telangana State Technology Services"

Source: https://panoptic.in/case-study/right-to-information-updates-from-delhi-police-kolkata-police-and-telangana-state-technology-services
Source tier: primary
Source content: "Delhi Police — Filed: October 23, 2020; Reference No.: DEPOL/R/E/20/07128"; "Kolkata Police — Filed: July 30, 2020"; "Telangana State Technology Services — Filed: October 23, 2020"
Comparison: All three filings, dates, and the Delhi reference number match IFF's own record; one primary source.
Decision: primary-sourced

## Claim 26: "Delhi Police's reply on 25 November 2020 refused to provide any information about the FRT system under Section 8(1)(d) of the RTI Act, invoking the commercial-confidence and trade-secrets exemption on behalf of the vendor Innefu Labs Private Limited"

Source: https://panoptic.in/case-study/right-to-information-updates-from-delhi-police-kolkata-police-and-telangana-state-technology-services
Source tier: primary
Source content: "Reply Date: November 25, 2020 ... Grounds for Refusal: Section 8(1)(d) RTI Act ... 'information including commercial confidence, trade secrets or intellectual property, the disclosure of which would harm the competitive position of a third party.' Vendor: Innefu Labs Pvt. Ltd."
Comparison: Reply date, statutory ground, exemption content, and vendor all match IFF's own record; one primary source.
Decision: primary-sourced

## Claim 27: "The trade-secrets refusal drew criticism from technology lawyers who noted that Section 8(1)(d) was being applied to protect a private vendor's commercial interests rather than any legitimate national-security ground"

Source: no canonical source found for the "technology lawyers" attribution
Source tier: none
Source content: The panoptic.in RTI-updates page carries IFF's own criticism ("raises concerns about data access for commercial purposes without citizen consent") but attributes no criticism to technology lawyers
Comparison: The specific attribution to "technology lawyers" was not found in any fetched source; the criticism substance exists but in IFF's own voice. Too vague an attribution to confirm or to correct with a single token.
Decision: uncorroborated

## Claim 28: "at a Second Appeal hearing on 29 June 2022 the Central Information Commission directed Delhi Police to revise their responses in compliance with the RTI Act"

Source: https://internetfreedom.in/cic-directs-delhi-police-to-respond-to-frt-rti/ (via search snippet; direct fetch 403) + https://www.medianama.com/2022/08/223-delhi-police-iff-rti-facial-recognition-80-percent-accuracy-2/ (via search snippet; direct fetch 403)
Source tier: primary
Source content: "These appeals were heard on June 29, 2022, and the Delhi Police were directed to revise their response to the RTI applications in compliance with the RTI Act"; MediaNama: "After being directed by the Central Information Commission to respond afresh to RTI requests..."
Comparison: Hearing date and direction match IFF's report and independent tech-press coverage.
Decision: corroborated

## Claim 29: "Subsequent RTI responses following the CIC direction eventually disclosed that Delhi Police treats a face-similarity score above 80 per cent as a positive identification result for arrest purposes"

Source: https://www.medianama.com/2022/08/223-delhi-police-iff-rti-facial-recognition-80-percent-accuracy-2/ (via search snippet; direct fetch 403) + https://www.outlookindia.com/national/delhi-police-s-80-per-cent-match-of-facial-recognition-to-nab-accused-raises-concern-finds-rti-news-217182
Source tier: mainstream
Source content: "Delhi Police conducts 'empirical investigation' on individuals if the facial recognition technology (FRT) match has an accuracy of over 80 percent"; "the Delhi Police revealed that it treats all results above 80% similarity as positive results"; Outlook: "Delhi police's 80 per cent match of facial recognition to nab accused raises concern, finds RTI"
Comparison: The 80% threshold and its treatment as positive identification in enforcement match multiple independent outlets. Body's "for arrest purposes" tracks the sources' investigation/nab-accused framing.
Decision: corroborated

## Claim 30: "a threshold Anushka Jain framed as treating 80 per cent probability as certainty and leaving a 20 per cent margin of wrongful-arrest error operative in enforcement decisions" (also scalar:sources[7].note "IFF Associate Counsel Anushka Jain")

Source: https://www.medianama.com/2022/08/223-delhi-police-iff-rti-facial-recognition-80-percent-accuracy-2/ (via search snippet; direct fetch 403)
Source tier: mainstream
Source content: "The 80% match is a similarity match ... treating 80% similar as positive identification means there is a 20% margin of error. Anushka Jain, IFF associate counsel, said that people with the slightest facial similarity can be targeted due to this"
Comparison: The 20%-margin framing, Jain's attribution, and her Associate Counsel title (per scalar:sources[7].note) match the MediaNama piece; single non-primary canonical source. Body's "wrongful-arrest error" is a fair rendering of the targeting/false-positive concern.
Decision: single-source

## Claim 31: Significance — "IFF's first documented strategic-litigation act in the surveillance-accountability space"

Source: no canonical source found
Source tier: none
Source content: IFF's own case study references prior work including "a national facial recognition system notice to the NCRB" (panoptic.in), which predates the Delhi Police notice; IFF separately describes the January 2022 Masood PIL as "India's first legal challenge to the deployment of Facial Recognition Technology"
Comparison: Contested "first" class; no source asserts this superlative, and IFF's own record of an earlier NCRB legal notice puts it in tension. Whether a legal notice to NCRB counts as a "strategic-litigation act" is a judgment call, not a token error with a single replacement. (The adjacent "corpus's first event anchored on..." phrasing is corpus-internal framing, not an external claim.)
Decision: uncorroborated
