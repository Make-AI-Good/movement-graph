---
entity_id: org-masaar
entity_hash: e2632836e05b2d1a54f01c89f6714f8712d26ca0
audit_date: 2026-06-01
pass: 1
status: corrections-pending
claims_total: 22
claims_corroborated: 9
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 2
claims_uncorroborated: 11
sources_consulted:
  - https://ooni.org/partners/masaar/
  - https://ooni.org/post/2019-egypt-blocks-bbc-and-alhurra
  - https://www.accessnow.org/new-middle-east-and-north-africa-coalition-to-combat-digital-surveillance/
  - https://www.freedomhouse.org/country/egypt/freedom-net/2022
  - https://www.freedomhouse.org/country/egypt/freedom-net/2023
  - https://www.freedomhouse.org/country/egypt/freedom-net/2024
  - https://www.dlapiperdataprotection.com/index.html?t=law&c=EG
  - https://www.thecairoreview.com/essays/regulating-privacy-and-digital-identities-in-the-age-of-ai-the-view-from-egypt/
  - https://en.wikipedia.org/wiki/Internet_censorship_in_Egypt
---

## Claim 1: "Masaar (مَسَار — مجتمع التكنولوجيا والقانون) is an Egyptian digital rights organisation based in Cairo"

Source: https://www.freedomhouse.org/country/egypt/freedom-net/2022
Source content: Freedom House FOTN 2022 cites "Masaar" multiple times as a documentation source on Egyptian internet censorship (e.g. "Internet Censorship in Time of Social Distancing," Masaar, April 11, 2020), identifying it as an Egyptian civil-society source.
Comparison: FOTN treats Masaar as an Egyptian civil-society source on Egyptian-state censorship. Egyptian identity is corroborated; Cairo specifically is the entity's self-reported location.
Decision: corroborated

## Claim 2: "Masaar [announced the launch of its public activities in February 2021], having formed in 2020 (earliest archival publications date to that year)"

Source: https://www.freedomhouse.org/country/egypt/freedom-net/2022
Source content: "Internet Censorship in Time of Social Distancing," Masaar, April 11, 2020.
Comparison: FOTN-cited Masaar publications dating to April 2020 are consistent with "formed in 2020" and "earliest archival publications date to that year." The "February 2021" public-launch date relies on Masaar's own press-release URL; the consulted FOTN report does not contradict.
Decision: corroborated

## Claim 3: scalar:sources[11].note — "Cairo Review of Global Affairs essay by Masaar — primary source for the organisation's public intellectual contribution on privacy, digital identity, and AI governance in Egypt"

Source: https://www.thecairoreview.com/essays/regulating-privacy-and-digital-identities-in-the-age-of-ai-the-view-from-egypt/
Source content: "By Alia El Bolock." No Masaar attribution in the byline, author bio, or article body.
Comparison: The `sources[].note` frontmatter scalar for the Cairo Review URL (the 12th `sources:` entry) explicitly attributes the essay to Masaar ("essay by Masaar"). The actual byline is Alia El Bolock with no stated Masaar affiliation. Scalar-prose discrepancy; fix is in the `sources[].note` text for the Cairo Review URL.
Decision: correction

## Claim 4: "A Cairo Review of Global Affairs essay … placing Masaar's AI-policy voice alongside formal policy proposals in international-facing publications"

Source: https://www.thecairoreview.com/essays/regulating-privacy-and-digital-identities-in-the-age-of-ai-the-view-from-egypt/
Source content: "By Alia El Bolock." No mention of Masaar in byline or bio.
Comparison: The body sentence frames the Cairo Review essay as carrying "Masaar's AI-policy voice," implying institutional voicing. The essay's actual byline is Alia El Bolock with no stated Masaar affiliation. Body claim not supported by the cited source.
Decision: correction

## Claim 5: "Egypt's mass website-blocking wave — which began in May 2017"

Source: https://www.freedomhouse.org/country/egypt/freedom-net/2022
Source content: "In November 2020, IFEX reported that at least 600 websites had been blocked by the authorities since May 2017, including 394 virtual private network (VPN) and proxy providers and 116 news sites."
Comparison: Freedom House FOTN 2022 dates the start of mass blocking to May 2017, matching the body.
Decision: corroborated

## Claim 6: "Masaar and the Arabic Network for Human Rights Information (ANHRI) [jointly launched the 'Stop the Block' campaign]"

Source: entity-cited https://masaar.net/en/anhri-masaar-launch-stop-the-block-campaign/ (HTTP 403 — not fetchable this session); cross-checked https://www.freedomhouse.org/country/egypt/freedom-net/2022 (does not name the campaign).
Source content: FOTN cites Masaar reporting on censorship but does not name "Stop the Block" or co-launch with ANHRI in the consulted excerpt.
Comparison: The campaign-naming and ANHRI co-launch detail rest on Masaar's own page (currently unfetchable). No independent canonical source consulted corroborates the specific campaign name or co-launcher.
Decision: uncorroborated

## Claim 7: "by the time of Masaar's first major public campaign had reached at least 628 blocked URLs, including 116 press and media websites, 349 VPN and proxy services, and 15 human rights websites"

Source: https://www.freedomhouse.org/country/egypt/freedom-net/2022
Source content: "In November 2020, IFEX reported that at least 600 websites had been blocked by the authorities since May 2017, including 394 virtual private network (VPN) and proxy providers and 116 news sites."
Comparison: The 116 press/media-sites count matches FOTN exactly. The 628 total and 349 VPN/proxy counts differ from FOTN's 600 / 394 (FOTN cites a November 2020 IFEX snapshot; the body's count is a campaign-launch-date snapshot per Masaar's own page — different cutoffs). The 15 human-rights-websites breakdown is not in the consulted source. Not a contradiction, but the specific numbers (628/349/15) rest on Masaar's own page (unfetchable).
Decision: uncorroborated

## Claim 8: "Masaar contributes to the Egyptian website-testing list and collaborated on the reporting that Egyptian authorities used deep-packet inspection targeting TLS SNI fields to block BBC and Alhurra in September 2019"

Source: https://ooni.org/post/2019-egypt-blocks-bbc-and-alhurra; https://ooni.org/partners/masaar/
Source content: OONI post: "As of 22nd September 2019 (coinciding with Egypt's protests last weekend), OONI measurements started showing signs of interference when testing bbc.com in Egypt … this indicates that some form of Deep Packet Inspection (DPI) technology that is aware of TLS and which is most likely fingerprinting the SNI field of the TLS handshake." OONI partner page lists "Egypt blocks BBC and Alhurra: Expanding media censorship amid political unrest" as a Masaar partnership project.
Comparison: OONI independently confirms (a) September 2019 timing, (b) DPI of TLS SNI fields, (c) BBC and Alhurra targeting. Masaar's collaborative role on the BBC/Alhurra reporting is confirmed via OONI's own partners page.
Decision: corroborated

## Claim 9: "[2022 Court of Cassation ruling limiting website-blocking authority to the NTRA under the Cybercrime Law — finding that the Ministry of Interior could not independently order blocks]"

Source: entity-cited https://masaar.net/en/court-of-cassation-rules-against-expansive-use-of-website-blocking/ (HTTP 403 — not fetchable)
Source content: Cannot retrieve.
Comparison: Specific ruling details (year, court, NTRA scope, Ministry of Interior limitation, Cybercrime Law basis) rest on Masaar's own analysis page (entity-cited source #7), currently unfetchable. No independent canonical secondary source consulted covers this specific ruling.
Decision: uncorroborated

## Claim 10: "Egypt enacted a Personal Data Protection Law in 2020"

Source: https://www.dlapiperdataprotection.com/index.html?t=law&c=EG
Source content: "Personal Data Protection Law No.151 of 2020."
Comparison: DLA Piper Data Protection law database (canonical secondary source on national data-protection statutes) confirms Egypt's PDPL is Law No. 151 of 2020.
Decision: corroborated

## Claim 11: "In February 2025, Masaar [analysed a landmark Alexandria Economic Court ruling] ordering Orange Egypt Telecom to pay EGP 10 million in compensation to a woman whose SIM card was replaced without consent, enabling WhatsApp account takeover and subsequent extortion"

Source: entity-cited https://masaar.net/en/first-judicial-application-of-the-personal-data-protection-law-a-reading-of-a-compensation-ruling-against-orange/ (HTTP 403 — not fetchable)
Source content: Cannot retrieve.
Comparison: Specific ruling details (February 2025 date, Alexandria Economic Court, Orange Egypt Telecom, EGP 10 million, SIM-swap, WhatsApp extortion) rest on Masaar's own analysis page (entity-cited source #8), currently unfetchable. No independent canonical source consulted.
Decision: uncorroborated

## Claim 12: "['Regulating Artificial Intelligence in Egypt: Proposed Standards and Principles'] proposes 24+ governance principles including prohibition of mass surveillance, prohibition of lethal autonomous weapons, mandatory non-discrimination requirements, human oversight, and human-rights impact assessments"

Source: entity-cited https://masaar.net/en/regulating-artificial-intelligence-in-egypt-proposed-standards-and-principles/ (HTTP 403 — not fetchable)
Source content: Cannot retrieve.
Comparison: The "24+ principles" count and specific principle enumeration rest on Masaar's own paper (entity-cited source #9), currently unfetchable. No independent canonical secondary source consulted enumerates Masaar's principles list.
Decision: uncorroborated

## Claim 13: "Masaar is a founding member of … the **Arab Alliance for Digital Rights (AADR)** … co-founded by Masaar alongside [JOSA] (Jordan), INSM (Iraq), [7amleh] (Palestine/Israel), and [SMEX] (Lebanon)"

Source: entity-cited https://aadr.network/en/the-launch-of-the-arab-alliance-for-digital-rights/ (socket-close error this session); cross-checked https://www.accessnow.org/new-middle-east-and-north-africa-coalition-to-combat-digital-surveillance/.
Source content: Access Now MENA Coalition page confirms all five organisations (Masaar, JOSA, INSM, 7amleh, SMEX) with the same country attributions are members of the MENA Coalition to Combat Digital Surveillance — a sibling coalition, not AADR.
Comparison: Five-org identity and country attributions are independently confirmed via the sibling-coalition page. The AADR-specific co-founder claim rests on the entity's own cited AADR page (currently unfetchable). MENA Coalition is not AADR; cannot be used to verify AADR-specific membership.
Decision: uncorroborated

## Claim 14: "The **MENA Coalition to Combat Digital Surveillance**, [launched at RightsCon in June 2021], brought Masaar together with [Access Now], [ARTICLE19], CPJ, Front Line Defenders, HRW, RSF"

Source: https://www.accessnow.org/new-middle-east-and-north-africa-coalition-to-combat-digital-surveillance/
Source content: "The coalition was officially launched on June 7, 2021, during a public session at RightsCon … founding member organizations: Access Now, ARTICLE19, Committee to Protect Journalists (CPJ), Front Line Defenders, Gulf Centre for Human Rights (GCHR), Human Rights Watch (HRW), Iraqi Network for Social Media (INSM), Jordan Open Source Association (JOSA), Masaar – Technology and Law Community, Red Line for Gulf, Reporters Without Borders (RSF), SMEX."
Comparison: Access Now's launch announcement independently confirms June 2021 RightsCon launch and the full founding-member list. Body claim verified in full.
Decision: corroborated

## Claim 15: "Freedom House cites Masaar as a primary source in its Egypt Freedom on the Net reports for 2022, 2023, and 2024"

Source: https://www.freedomhouse.org/country/egypt/freedom-net/2022, /2023, /2024
Source content: FOTN 2022: "Internet Censorship in Time of Social Distancing," Masaar, April 11, 2020; "The Egyptian authorities block Telegram," Masaar, October 22, 2020. FOTN 2023: same Telegram citation plus "How The Supreme Council For Media Will Subject Netflix And Disney To Egyptian Laws," Masaar, September 18, 2022. FOTN 2024: same Telegram + Netflix/Disney citations.
Comparison: All three FOTN years explicitly cite Masaar publications. The body's "primary source" framing is somewhat strong (Freedom House also cites many other Egyptian sources) but the underlying claim — cited in 2022/2023/2024 FOTN — is verified.
Decision: corroborated

## Claim 16: "OONI — the Open Observatory of Network Interference — Masaar contributes to the Egyptian website-testing list"

Source: https://ooni.org/partners/masaar/
Source content: OONI partner page lists Masaar as a partner; describes the collaboration as merging "law and technology" to measure digital freedoms within Egyptian legal contexts; lists collaborative project "Egypt blocks BBC and Alhurra: Expanding media censorship amid political unrest" and "The State of Internet Censorship in Egypt."
Comparison: OONI's own partner page independently confirms the partnership and collaboration scope; "Egyptian website-testing list" contribution is consistent with the test-list framing of OONI collaboration.
Decision: corroborated

## Claim 17: "[Masaar] describes itself as a community (مجتمع) rather than a registered NGO — a deliberate structural framing"

Source: frontmatter `name: 'Masaar — Technology and Law Community'`; https://www.freedomhouse.org/country/egypt/freedom-net/2022 (treats Masaar as a community / civil-society source without naming registered-NGO status)
Source content: Entity name itself contains "Community" (English of مجتمع). FOTN citations treat Masaar as an institutional voice with no NGO-registration framing.
Comparison: The "community" self-description is consistent with the entity's own name and the FOTN citation pattern. Direct self-description from Masaar's About page is the canonical primary source (currently unfetchable), but the name itself substantiates the claim.
Decision: corroborated

## Claim 18: "Egypt's 2017 NGO law"

Source: https://en.wikipedia.org/wiki/Internet_censorship_in_Egypt (does not cover); no other canonical source for Egypt's 2017 NGO law consulted this session.
Source content: Wikipedia article on Egyptian internet censorship does not reference the 2017 NGO law (Law No. 70 of 2017). No alternate canonical source fetched this session corroborates.
Comparison: Egypt's 2017 NGO law is a named-statute, public-record fact (Wikipedia-canonical in principle) but not corroborated by sources consulted in this audit pass.
Decision: uncorroborated

## Claim 19: "Masaar's programme structure covers seven named areas. **Free Internet** … **Privacy** … **Tech and Equality** … **Human Rights and Business** … **Decentralisation** and **Internet Governance** … **Strategic Litigation**"

Source: entity-cited https://masaar.net/en/about-us/ (HTTP 403 — not fetchable)
Source content: Cannot retrieve. The named-programme-area list comes from Masaar's own About page.
Comparison: The exact set of seven named thematic areas is not independently re-enumerated in any source fetched this session. No contradiction observed; OONI partnership, FOTN citations and Access Now MENA coalition page corroborate work in censorship documentation, privacy, and platform accountability, but not the specific seven-area programme structure.
Decision: uncorroborated

## Claim 20: "[Masaar] archives its research output publicly on GitHub" (https://github.com/masaarnet/Publications)

Source: not fetched this session.
Source content: N/A.
Comparison: Standard public-repo claim; the GitHub link was not fetched in this audit pass.
Decision: uncorroborated

## Claim 21: "Masaar is a founding member of two Arab-region civil-society coalitions"

Source: https://www.accessnow.org/new-middle-east-and-north-africa-coalition-to-combat-digital-surveillance/
Source content: Confirms Masaar as MENA Coalition founding member; the second coalition (AADR) rests on the entity's own AADR page (unfetchable; see Claim 13).
Comparison: One of two coalitions verified; the other (AADR) is currently unverifiable. The aggregate "two" claim cannot be fully verified without the AADR source.
Decision: uncorroborated

## Claim 22: "As of 2026, its Facebook page carried over 119,000 followers"

Source: not fetched this session.
Source content: N/A.
Comparison: Third-party-platform follower-count claim; no independent canonical source consulted.
Decision: uncorroborated
