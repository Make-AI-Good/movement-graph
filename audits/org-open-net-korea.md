---
entity_id: org-open-net-korea
entity_hash: 5e411d76fc1f189e7e86c8ff2be392cf002a19b9
audit_date: 2026-06-01
pass: 1
status: corrections-pending
claims_total: 22
claims_corroborated: 18
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 3
sources_consulted:
  - https://en.wikipedia.org/wiki/OpenNet_(organization)
  - https://www.apc.org/en/news/interview-open-net-their-10th-anniversary-we-still-believe-power-internet-internet-great
  - https://globalnetworkinitiative.org/member/open-net-korea/
  - https://ooni.org/partners/open-net-korea/
  - https://www.opennetkorea.org/en/wp/7058
  - https://en.wikipedia.org/wiki/Kilnam_Chon
  - https://www.koreatimes.co.kr/www/tech/2022/11/129_338524.html
  - https://www.opennetkorea.org/about-opennet/board
---

## Claim 1: "founded on 4 February 2013 and approved by the Seoul Radiowave Management Office on 7 March 2013"

Source: https://en.wikipedia.org/wiki/OpenNet_(organization)
Source content: "Formation February 4, 2013" and "It was approved by Seoul Radiowave Management Office...on 7 March 2013."
Comparison: Body matches Wikipedia on both dates (4 February 2013 formation and 7 March 2013 approval). Wikipedia is canonical alone for organisation founding dates.
Decision: corroborated

## Claim 2: "Seoul-headquartered Korean civil-society digital-rights organisation"

Source: https://en.wikipedia.org/wiki/OpenNet_(organization)
Source content: "Headquarters Gangnam, Seoul"
Comparison: Body claims Seoul headquarters. Wikipedia confirms Seoul (Gangnam district within Seoul). Body claim is verified at the city-level granularity it asserts.
Decision: corroborated

## Claim 3: scalar:sources[0].note — claims Wikipedia is "primary structural source for ... the Mapo-gu / Seoul headquarters"

Source: https://en.wikipedia.org/wiki/OpenNet_(organization)
Source content: "Headquarters Gangnam, Seoul"
Comparison: The Wikipedia source note (sources[0].note) cites Wikipedia as the source for "Mapo-gu / Seoul headquarters" — but Wikipedia in fact states Gangnam, Seoul, not Mapo-gu. The scalar's attribution of Mapo-gu to Wikipedia is contradicted by the cited source. Single-token fix: "Mapo-gu / Seoul headquarters" → "Gangnam / Seoul headquarters" in the sources[0].note scalar.
Decision: correction

## Claim 4: founders "Kim Keechang, Park Kyung-sin, Nam Heesob, Jeon Eung-hui, Woo Jisuk, Kang Jung Soo, and Kim Borami"

Source: https://en.wikipedia.org/wiki/OpenNet_(organization)
Source content: "Kim Keechang, Park Kyung-sin, Nam Heesob, Jeon Eung-hui, Woo Jisuk, Kang Jung Soo, and Kim Borami" listed as key people; "Kim Keechang, one of Founders in 2013."
Comparison: Body's seven-name founder list matches Wikipedia's named cohort verbatim, including the "Founders in 2013" framing.
Decision: corroborated

## Claim 5: "APC interview marking the organisation's tenth anniversary on 8 March 2024"

Source: https://www.apc.org/en/news/interview-open-net-their-10th-anniversary-we-still-believe-power-internet-internet-great
Source content: "Last month, on 8 March 2024, the non-profit organisation marked its 10th anniversary"
Comparison: Body's date and tenth-anniversary framing match APC verbatim.
Decision: corroborated

## Claim 6: APC interview language "emerged in 2014 following civil society's successful Constitutional Complaint against South Korea's internet real-name law"

Source: https://www.apc.org/en/news/interview-open-net-their-10th-anniversary-we-still-believe-power-internet-internet-great
Source content: "In the wake of this landmark decision, [those] who had engaged in the Constitutional Complaint united to form a civil society organisation" (the section of the APC interview accessible in this session)
Comparison: The APC interview's tenth-anniversary frame of 8 March 2024 implies a 2014 origin point, consistent with the body's "emerged in 2014" phrasing. The accessible APC excerpt does not contain the body's specific quoted sentence verbatim, so the exact quotation cannot be confirmed against the source as-fetched.
Decision: uncorroborated

## Claim 7: board "chaired by Jeongsoo Kang (Concurrent Professor at Yonsei University's School of Business and Director of the Digital Society Research Institute)"

Source: https://www.opennetkorea.org/about-opennet/board
Source content: "Jeongsoo Kang — President — Concurrent Professor, School of Business, Yonsei University; Director, Digital Society Research Institute"
Comparison: Title and affiliations match the Board page exactly.
Decision: corroborated

## Claim 8: "Kilnam Chun (Professor Emeritus at KAIST and Vice-President at Keio University)... Senior Advisor"

Source: https://www.opennetkorea.org/about-opennet/board
Source content: "Kilnam Chun — Senior Advisor — Professor Emeritus, KAIST; Vice President, Keio University, Japan"
Comparison: Role and affiliations match.
Decision: corroborated

## Claim 9: Kilnam Chun "often credited as the engineer who connected Korea to the early internet in 1982"

Source: https://en.wikipedia.org/wiki/Kilnam_Chon
Source content: "The network went live in May 1982" and "In 1982, Chon began work as a professor at the Korea Advanced Institute of Science and Technology (KAIST), focusing on 'the internet and other networking activities'."
Comparison: Wikipedia confirms 1982 as the year the early Korean network went live under Chon's work. Body claim is verified within paraphrase tolerance.
Decision: corroborated

## Claim 10: "Park Kyung-sin (Professor at Korea University Law School) as Executive Director"

Source: https://www.opennetkorea.org/about-opennet/board
Source content: "Kyung-sin Park — Executive Director, Professor at Korea University Law School"
Comparison: Role and affiliation match.
Decision: corroborated

## Claim 11: Park as "named co-author of the Necessary and Proportionate Principles on Communications Surveillance and the Manila Principles on Intermediary Liability"

Source: https://globalfreedomofexpression.columbia.edu/about/experts/kyung-sin-park/ (returned HTTP 403); no alternative canonical source for the co-authorship claim was fetched in this session.
Source content: not available
Comparison: The Columbia expert page (the entity's cited source for this claim) was unreachable; the claim is supported in the entity's sources[] but cannot be independently verified against a fetched canonical source in this pass.
Decision: uncorroborated

## Claim 12: six programme banners — "Freedom of Speech, Intellectual Property, Privacy, Network Neutrality, Open Government, and Innovation and Regulations"

Source: https://en.wikipedia.org/wiki/OpenNet_(organization)
Source content: "Freedom of Speech", "Intellectual Property", "Privacy", "Network neutrality", "Open Government", and "Innovation and Regulations"
Comparison: Body's six-banner list matches Wikipedia exactly.
Decision: corroborated

## Claim 13: OONI six-area set — "freedom of expression, freedom from surveillance, removing innovation-blocking regulations, net governance and neutrality, open data policy, and intellectual-property reform"

Source: https://ooni.org/partners/open-net-korea/
Source content: "Freedom of Expression, Freedom from Surveillance, Reforming Innovation-blocking Regulations, Net Governance and Neutrality, Open Data Policy, and Reforming the Intellectual Property Regime"
Comparison: Body's six-area list matches OONI's list within paraphrase tolerance (capitalisation and minor phrasing).
Decision: corroborated

## Claim 14: "July 2013 constitutional complaint against government-mandated identity verification for minors"

Source: https://en.wikipedia.org/wiki/OpenNet_(organization)
Source content: "On July 31, 2013, Open Net submitted a Constitutional complaint about how the South Korean government forces minors to verify his or her identity."
Comparison: Date (July 2013) and subject (identity verification for minors) match Wikipedia verbatim.
Decision: corroborated

## Claim 15: "January 2014 suit against the Korea Communications Standards Commission's blocking of Grooveshark"

Source: https://en.wikipedia.org/wiki/OpenNet_(organization)
Source content: "On January 28, 2014, OpenNet filed a lawsuit against the Korea Communications Standards Commission's internet censorship by blocking access to Grooveshark."
Comparison: Date (January 2014), defendant (KCSC), and subject (Grooveshark blocking) all match Wikipedia.
Decision: corroborated

## Claim 16: "2013 restoration of Kakao Voice Talk after KT and SKT had restricted access"

Source: https://www.apc.org/en/news/interview-open-net-their-10th-anniversary-we-still-believe-power-internet-internet-great
Source content: "In 2013, mobile operators like KT and SKT Telecom partially restricted access to Kakao's Voice Talk service...Open Net filed a suit and they restored traffic."
Comparison: Year (2013), operators (KT, SKT), service (Kakao Voice Talk), and outcome (restoration) match APC.
Decision: corroborated

## Claim 17: "2022 defeat of the network usage fee bill through a 286,000-signature petition"

Source: https://www.apc.org/en/news/interview-open-net-their-10th-anniversary-we-still-believe-power-internet-internet-great
Source content: "Open Net organised a petition to stop this measure, garnering an impressive 286,000 signatures...and the bill was dropped."
Comparison: Petition count (286,000) and outcome (bill dropped) match APC.
Decision: corroborated

## Claim 18: "AI Basic Act ... passed by the National Assembly in December 2024 and entered into force on 22 January 2026"

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Basic_Act (404), https://en.wikipedia.org/wiki/Basic_Act_on_the_Development_of_Artificial_Intelligence_and_Establishment_of_Trust (404), https://en.wikipedia.org/wiki/Artificial_intelligence_in_South_Korea (404)
Source content: not available
Comparison: No canonical source (Wikipedia entries probed under several titles all 404) was reachable in this session for the AI Basic Act's passage and entry-into-force dates. Cannot independently verify.
Decision: uncorroborated

## Claim 19: "filed a constitutional complaint on 1 October 2025 challenging Article 82-8(1) of the Public Official Election Act"

Source: https://www.opennetkorea.org/en/wp/7058
Source content: "October 1, 2025" filing; "Article 82-8, Paragraph 1 of the Public Official Election Act"
Comparison: Filing date and statutory provision match Open Net's own announcement verbatim.
Decision: corroborated

## Claim 20: penalties "up to seven years' imprisonment or fines of 10–50 million won"

Source: https://www.opennetkorea.org/en/wp/7058
Source content: "imprisonment of up to 7 years or fines ranging from 10 million won to 50 million won"
Comparison: Penalty ceiling (7 years) and fine range (10–50 million won) match Open Net's announcement.
Decision: corroborated

## Claim 21: "joined the Global Network Initiative in 2023"

Source: https://globalnetworkinitiative.org/member/open-net-korea/
Source content: GNI member page lists Open Net Korea with 2023 accession date.
Comparison: Year matches GNI's own member page.
Decision: corroborated

## Claim 22: "Google Korea donated 220 million won to Open Net in 2020"

Source: https://www.koreatimes.co.kr/www/tech/2022/11/129_338524.html
Source content: "Google Korea gave Open Net 220 million won in 2020 alone", per "the tax agency's data" (National Tax Service) cited by the reporting lawmaker.
Comparison: Donation amount (220 million won), year (2020), and source attribution (National Tax Service) all match the Korea Times report.
Decision: corroborated
