---
entity_id: camp-ncc-out-of-control-behavioral-advertising-2020
entity_hash: 239e0dabb52402eeb9f53c3aaa77314eb8c6580d
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 33
claims_corroborated: 13
claims_primary_sourced: 6
claims_single_source: 2
claims_uncorroborated: 8
open_corrections: 4
sources_consulted:
  - https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
  - https://noyb.eu/en/ncc-noyb-gdpr-complaint-grindr-fined-eu-63-mio-over-illegal-data-sharing
  - https://www.datatilsynet.no/en/news/aktuelle-nyheter-2023/record-fine-grindr-confirmed/
  - https://www.datatilsynet.no/en/news/news-2025/the-court-of-appeal-upholds-the-fine-against-grindr/
  - https://digitalpolicyalert.org/event/21083-issued-oslo-district-court-ruling-upholding-datatilsynet-nok-65-million-fine-on-grindr
  - https://www.citizen.org/article/popular-dating-health-apps-violate-privacy/
  - https://www.forbrukerradet.no/side/the-norwegian-consumer-council-awarded-epic-international-privacy-champion-award/
  - https://www.forbrukerradet.no/side/new-study-the-advertising-industry-is-systematically-breaking-the-law/
  - https://www.forbrukerradet.no/out-of-control/
  - https://www.forbrukerradet.no/side/complaints-against-grindr-and-five-third-party-companies/
  - https://techcrunch.com/2020/01/14/dating-and-fertility-apps-among-those-snitching-to-out-of-control-adtech-report-finds/
  - https://techcrunch.com/2021/06/23/international-coalition-joins-the-call-to-ban-surveillance-advertising/
  - https://edri.org/our-work/ncc-report-online-advertising-industry-is-out-of-control/
  - https://edri.org/take-action/events/transatlantic-discussion-time-to-ban-surveillance-based-advertising/
  - https://tacd.org/its-not-just-a-phase-consumers-want-less-surveillance/
  - https://crackedlabs.org/en/outofcontrol
  - https://storage02.forbrukerradet.no/media/2021/06/20210622-final-report-time-to-ban-surveillance-based-advertising.pdf
---

Connective type (campaign): claim surface is edges + hard specifics per
`mission/MISSION.md § Auditor § Type-shape awareness`. Body prose about
significance/methodology-as-model ("most consequential", "most fully-developed
implementation", § Place in the make-AI-good movement framing) is interpretation,
not claim — skipped. Note for the Editor: both NCC report PDFs (Out of Control
2020, Time to Ban 2021) are image-compressed and unparseable via fetch; claims
resting solely on PDF content are marked at the audit's limit, not as errors.

## Claim 1: edge lead_orgs → org-norwegian-consumer-council

Source: https://www.datatilsynet.no/en/news/aktuelle-nyheter-2023/record-fine-grindr-confirmed/
Source tier: primary
Source content: "In 2020, the Norwegian Consumer Council lodged a complaint against the app with the Data Protection Authority." NCC's own press page: "The online advertising industry is behind comprehensive illegal collection and indiscriminate use of personal data, research from the Norwegian Consumer Council shows."
Comparison: Edge target exists in corpus; NCC is the campaign lead per DPA, noyb, and NCC's own pages. Match.
Decision: corroborated

## Claim 2: edge events → event-ncc-out-of-control-report-launch-2020-01

Source: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: Complaints filed January 14, 2020, by "The Norwegian Consumer Council (Forbrukerrådet) ... in cooperation with noyb"; NCC press release dated January 14, 2020.
Comparison: Edge target exists in corpus; the January 2020 report-launch event is the campaign's opening event, date confirmed by two primary sources. Match.
Decision: corroborated

## Claim 3: edges strategies → strat-empirical-audit-and-expose, strat-coalition-lobbying-of-binding-regional-regulation, strat-open-letter-collective-signatory-action

Source: https://techcrunch.com/2021/06/23/international-coalition-joins-the-call-to-ban-surveillance-advertising/
Source tier: mainstream
Source content: Coalition urged legislators to "consider a ban of surveillance-based advertising as part of the Digital Services Act in the EU" and the US to "enact a long overdue federal privacy law"; technical audit + same-day complaints per noyb and NCC pages (Claims 4, 11).
Comparison: All three edge targets exist in corpus; each connection is consistent with campaign facts corroborated in Claims 4, 11, 25, 28 (technical audit-and-expose; DSA-directed coalition lobbying; collective open letter). Match.
Decision: corroborated

## Claim 4: start_date 2020-01-14 — report published and three GDPR complaints filed simultaneously

Source: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: "Date Filed: January 14, 2020"; Public Citizen action page also dated January 14, 2020; TechCrunch coverage published 2020-01-14.
Comparison: Frontmatter start_date and body "On 14 January 2020" match ≥2 canonical sources. Match.
Decision: corroborated

## Claim 5: report developed with cybersecurity firm Mnemonic and researcher Zach Edwards

Source: https://www.forbrukerradet.no/side/new-study-the-advertising-industry-is-systematically-breaking-the-law/
Source tier: primary
Source content: "Confirmed as conducted by Mnemonic (security company), with additional Grindr auditing by researcher Zach Edwards of Victory Medium." Cracked Labs: "Led by the Norwegian Consumer Council, and together with mnemonic, Zach Edwards and NOYB, Cracked Labs contributed to an investigation."
Comparison: Both named collaborators confirmed by NCC's own release plus a participant org's page and TechCrunch (Mnemonic). Match.
Decision: corroborated

## Claim 6: "186-page" report

Source: https://crackedlabs.org/en/outofcontrol
Source tier: primary
Source content: "Report], January 2020 (PDF, 186 pages)"
Comparison: Page count confirmed by an investigation-participant org's own documentation of the report artifact; the primary PDF itself is unparseable via fetch. Match.
Decision: primary-sourced

## Claim 7: the ten apps tested — Grindr, Tinder, OkCupid, Happn, Clue, MyDays, Perfect365, Qibla Finder, My Talking Tom 2, Wave Keyboard

Source: https://techcrunch.com/2020/01/14/dating-and-fertility-apps-among-those-snitching-to-out-of-control-adtech-report-finds/
Source tier: mainstream
Source content: "Dating apps (Grindr, Happn, OkCupid, Tinder), fertility trackers (Clue, MyDays), makeup app (Perfect365), religious app (Muslim: Qibla Finder), children's game (My Talking Tom 2), and keyboard app (Wave Keyboard)."
Comparison: All ten names match exactly. Only one canonical source enumerated the full list in-session (the report PDF, the entity's cited primary, is unparseable). Match on lighter sourcing.
Decision: single-source

## Claim 8: apps transmitted user data to at least 135 third parties involved in advertising/behavioral profiling

Source: https://techcrunch.com/2020/01/14/dating-and-fertility-apps-among-those-snitching-to-out-of-control-adtech-report-finds/
Source tier: mainstream
Source content: TechCrunch: "at least 135 companies related to advertising" identified. EDRi: apps "transmitted information to at least 135 different intermediaries engaged in advertising or behavioral profiling."
Comparison: Figure and framing match two independent canonical secondary sources. Match.
Decision: corroborated

## Claim 9: report quote "the system in its current form is based on the comprehensive and systemic illegal collection and use of personal data"

Source: https://edri.org/our-work/ncc-report-online-advertising-industry-is-out-of-control/
Source tier: mainstream
Source content: "EDRi directly quotes the report's core finding: 'the system in its current form is based on the comprehensive and systemic illegal collection and use of personal data.'"
Comparison: Verbatim match via EDRi's quotation of the report; NCC's own release carries near-identical framing ("comprehensive illegal collection and indiscriminate use of personal data") but not the exact sentence; the primary PDF is unparseable. One verbatim canonical carrier.
Decision: single-source

## Claim 10: report received media coverage in more than 70 countries, including the United States and Japan

Source: https://www.forbrukerradet.no/side/the-norwegian-consumer-council-awarded-epic-international-privacy-champion-award/
Source tier: none
Source content: "The page does not specify media coverage in any particular number of countries." (fetch of the body's cited source for this claim)
Comparison: The body cites the NCC award page for this figure, but that page does not carry it; the figure surfaced in-session only on non-canonical mirrors (a company blog). Likely originates in the Time to Ban PDF (unparseable). Audit limit, not an error finding.
Decision: uncorroborated

## Claim 11: three GDPR complaints filed at Datatilsynet with NOYB against Grindr, Twitter's MoPub, AT&T's AppNexus (now Xandr), OpenX, AdColony, Smaato

Source: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: "Six respondents are named: 1. Grindr 2. Twitter's MoPub 3. AT&T's AppNexus 4. OpenX 5. AdColony 6. Smaato"; NCC's own release: "complaints against Grindr and five third-party companies: Twitter's MoPub, AT&T's AppNexus, OpenX, AdColony, and Smaato."
Comparison: Respondent list, co-filer, venue, and same-day filing all match two primary sources. Match.
Decision: corroborated

## Claim 12: core legal argument — Grindr's accept-the-whole-privacy-policy consent mechanism was not valid GDPR consent

Source: https://noyb.eu/en/ncc-noyb-gdpr-complaint-grindr-fined-eu-63-mio-over-illegal-data-sharing
Source tier: primary
Source content: "users had to agree to the entire privacy policy and not to a specific processing operation"; Datatilsynet: "consent was neither voluntary, specific nor informed."
Comparison: Substance of the consent-invalidity argument matches DPA and co-complainant statements. Match.
Decision: corroborated

## Claim 13: attribution of the consent standard to "GDPR Article 7"

Source: no canonical source found
Source tier: none
Source content: noyb page describes the legal basis only as "breaches of the General Data Protection Regulation (GDPR)" without article numbers; Datatilsynet pages fetched name no article.
Comparison: The four-part standard (freely given, specific, informed, unambiguous) is GDPR Art 4(11)'s definition, with conditions in Art 7; no source fetched this session names Article 7 for this case. Legal-citation attribution is a judgment-loaded edge — not asserting error, cannot confirm.
Decision: uncorroborated

## Claim 14: nine US groups (ACLU of California, Campaign for a Commercial-Free Childhood, Center for Digital Democracy, Consumer Action, Consumer Federation of America, Consumer Reports, EPIC, Public Citizen, US PIRG) urged the FTC, Congress, and the AGs of California, Texas, and Oregon in January 2020

Source: https://www.citizen.org/article/popular-dating-health-apps-violate-privacy/
Source tier: primary
Source content: Lists exactly: "Public Citizen, American Civil Liberties Union of California, Campaign for a Commercial-Free Childhood, Center for Digital Democracy, Consumer Action, Consumer Federation of America, Consumer Reports, Electronic Privacy Information Center (EPIC), U.S. PIRG"; urged "Federal Trade Commission (FTC), Congressional lawmakers, State Attorneys General of California, Texas, and Oregon"; dated January 14, 2020.
Comparison: All nine names, all targets, and the date match the co-signer's own page (primary for its own action). Single authoritative source.
Decision: primary-sourced

## Claim 15: the joint request called for a federal privacy law including "a new data protection agency, a private right of action, and strong enforcement mechanisms"

Source: https://www.citizen.org/article/popular-dating-health-apps-violate-privacy/
Source tier: none
Source content: "Congress should use the findings of this report as a roadmap for a new law that ensures that such flagrant violations of privacy found in the EU are not acceptable in the U.S." — "The page does not specify what components or enforcement mechanisms such a law should include."
Comparison: The cited source carries the general call but not the three specific components; the underlying letter (EPIC-hosted) is 403 on direct fetch per standing harness limits. Audit limit, not an error finding.
Decision: uncorroborated

## Claim 16: January 2021 — Datatilsynet advance notification of a NOK 100 million fine

Source: https://noyb.eu/en/ncc-noyb-gdpr-complaint-grindr-fined-eu-63-mio-over-illegal-data-sharing
Source tier: primary
Source content: "On January 26, 2021, authorities 'announced its intention to impose a fine of 100 Mio NOK (about 10 Mio EUR)' in a draft decision." Datatilsynet's own "Intention to issue €10 million fine to Grindr LLC" page and EDPB news (2021) confirm the NOK 100,000,000 notification.
Comparison: Amount and January 2021 date match DPA, EDPB, and co-complainant sources. Match.
Decision: corroborated

## Claim 17: final fine NOK 65 million (approximately EUR 6.3 million), December 2021

Source: https://www.datatilsynet.no/en/news/news-2025/the-court-of-appeal-upholds-the-fine-against-grindr/
Source tier: primary
Source content: "In December 2021, the Data Protection Authority issued an administrative fine of NOK 65 million"; noyb: "a fine of 65 Mio NOK (€ 6.34 Mio or $ 7.17 Mio) on Grindr" on December 15, 2021.
Comparison: Amount, EUR approximation, and December 2021 date match two primary sources. Match.
Decision: corroborated

## Claim 18: "the largest GDPR fine produced by a civil-society complaint in Norway at that time" (outcomes scalar; body: Nordic-region superlative framing)

Source: https://www.datatilsynet.no/en/news/aktuelle-nyheter-2023/record-fine-grindr-confirmed/
Source tier: primary
Source content: The NOK 65 million fine is "the highest that the Data Protection Authority has ever imposed."
Comparison: Scalar path `outcomes`. The DPA's broader superlative (highest it has ever imposed) entails the entity's narrower civil-society-complaint framing. Supported a fortiori by one primary source.
Decision: primary-sourced

## Claim 19: "the Norwegian Privacy Appeals Board upheld the fine in 2022" (body § Enforcement outcomes; also outcomes scalar "2022: the Norwegian Privacy Appeals Board upheld the NOK 65 million Grindr fine")

Source: https://www.datatilsynet.no/en/news/news-2025/the-court-of-appeal-upholds-the-fine-against-grindr/
Source tier: primary
Source content: "In September 2023, the Privacy Appeals Board upheld the conclusions"; the 2023 Datatilsynet page the entity cites likewise reports the Board's confirmation as 2023 news ("The Privacy Appeals Board upheld the fine in 2023 ... 'consent was neither voluntary, specific nor informed'").
Comparison: Body token "2022" contradicts the DPA's own record in two pages, including the entity's own cited source. Single correct replacement: "September 2023". Fix locations: body § Enforcement outcomes and scalar path `outcomes` ("2022:" milestone line → "September 2023:").
Decision: correction

## Claim 20: "the Oslo District Court upheld it in March 2024" (body § Enforcement outcomes; also outcomes scalar "March 2024: the Oslo District Court upheld the fine")

Source: https://digitalpolicyalert.org/event/21083-issued-oslo-district-court-ruling-upholding-datatilsynet-nok-65-million-fine-on-grindr
Source tier: primary
Source content: "On 1 July 2024, the Norwegian Data Protection Authority (Datatilsynet) announced that the Oslo District Court upheld the fine against Grindr for 65 million NOK"; Datatilsynet 2025 page: "in 2024, the Oslo District Court upheld the fine."
Comparison: Body token "March 2024" contradicts the DPA's announcement date of 1 July 2024 (independently: "On Monday, 1 July 2024, Grindr lost its appeal in the Oslo District Court"). Single correct replacement: "July 2024". Fix locations: body § Enforcement outcomes and scalar path `outcomes`.
Decision: correction

## Claim 21: Borgarting Court of Appeal dismissed Grindr's appeal after an August 2025 hearing, confirming the fine ("August–late 2025" in outcomes scalar)

Source: https://www.datatilsynet.no/en/news/news-2025/the-court-of-appeal-upholds-the-fine-against-grindr/
Source tier: primary
Source content: "the case was heard in Borgarting Court of Appeal on 12-14 August 2025"; "Borgarting Court of Appeal has handed down a verdict in the Grindr case on Tuesday 21 October"; "The fine of NOK 65 million was maintained."
Comparison: Hearing (12–14 August 2025) and late-2025 dismissal (21 October 2025) match the body's "after an August 2025 hearing" and the scalar's "August–late 2025". Note for Editor: the body links this fact to the 2023 Datatilsynet URL, which does not carry the court content — the 2025 page above does.
Decision: primary-sourced

## Claim 22: enforcement proceedings against the five adtech companies "remained ongoing as of 2026"

Source: no canonical source found
Source tier: none
Source content: NCC's complaints follow-up page "contains no information about whether cases remain active, have been closed, or decisions have been rendered" (fetch); no Datatilsynet outcome page for the five adtech respondents surfaced in search.
Comparison: No source in-session states the current status of the MoPub/AppNexus/OpenX/AdColony/Smaato proceedings either way. Audit limit, not an error finding.
Decision: uncorroborated

## Claim 23: "Time to Ban Surveillance-Based Advertising: The case against commercial surveillance online" published 22 June 2021

Source: https://storage02.forbrukerradet.no/media/2021/06/20210622-final-report-time-to-ban-surveillance-based-advertising.pdf
Source tier: primary
Source content: NCC's own publication artifact at URL path `2021/06/20210622-final-report-time-to-ban-surveillance-based-advertising.pdf`; title/subtitle confirmed by the NR vitenarkiv academic record "Time to ban surveillance-based advertising. The case against commercial surveillance online"; TACD: "Following the publication of a report in June 2021".
Comparison: Title, subtitle, and June 2021 publication corroborated; the specific day-token (22 June) rests on the NCC's own dated artifact (PDF content unparseable via fetch). Match.
Decision: primary-sourced

## Claim 24: report framed consumers as "vulnerable to manipulation, discrimination and fraud"

Source: https://storage02.forbrukerradet.no/media/2021/06/20210622-final-report-time-to-ban-surveillance-based-advertising.pdf
Source tier: primary
Source content: PDF is image-compressed and unparseable via fetch — no directly quotable text obtained this session. An exact-phrase web search for the quoted words returns this PDF as the top result, indirect evidence only.
Comparison: The quote is attributed to the primary PDF, which cannot be read in-session; no canonical secondary carrier of the exact phrase was found. Audit limit, not an error finding.
Decision: uncorroborated

## Claim 25: 23 June 2021 — open letter sent to EU and US policymakers

Source: https://techcrunch.com/2021/06/23/international-coalition-joins-the-call-to-ban-surveillance-advertising/
Source tier: mainstream
Source content: "Date: June 23, 2021" — coalition letter urging legislators on both sides of the Atlantic; TACD and Eticas pages document the same letter ("on June 23, 2021 sent an open letter to EU and US policymakers").
Comparison: Date and addressees match multiple canonical sources. Note for Editor: the body cites the EDRi event page for this sentence, but that page documents an 11 June 2021 discussion event and does not carry the letter (see Claim 33). The fact itself is sound.
Decision: corroborated

## Claim 26: BEUC and EDRi among the co-signatories

Source: https://techcrunch.com/2021/06/23/international-coalition-joins-the-call-to-ban-surveillance-advertising/
Source tier: mainstream
Source content: "BEUC and EDRi Named: Yes, both organizations are explicitly listed among the signatories."
Comparison: Both organisations confirmed as signatories by TechCrunch and coalition-side pages. Match.
Decision: corroborated

## Claim 27: letter "co-signed by more than 60 organisations"

Source: https://techcrunch.com/2021/06/23/international-coalition-joins-the-call-to-ban-surveillance-advertising/
Source tier: mainstream
Source content: TechCrunch: "The coalition comprised '55 organizations and more than 20 experts'"; TACD: "together with 55 organizations and more than 20 experts"; other coalition-side accounts say "more than 60 organizations from Europe and the US".
Comparison: Canonical sources conflict on the organisation count (55 organisations + 20 experts vs. 60+ organisations; signatory lists may also have grown after launch). Do not pick a winner.
Decision: uncorroborated

## Claim 28: letter urged an EU ban via the Digital Services Act and a US federal privacy law

Source: https://techcrunch.com/2021/06/23/international-coalition-joins-the-call-to-ban-surveillance-advertising/
Source tier: mainstream
Source content: Urged legislators to "consider a ban of surveillance-based advertising as part of the Digital Services Act in the EU" and the US to "enact a long overdue federal privacy law."
Comparison: Both policy asks match TechCrunch and coalition-side pages (TACD: "urges policymakers to consider a ban ... as a part of the Digital Services Act. In the US, it urges legislators to enact comprehensive privacy legislation"). Match.
Decision: corroborated

## Claim 29: EPIC awarded the NCC its International Privacy Champion Award, citing work that "played a major role in driving surveillance advertising reform globally"

Source: https://www.forbrukerradet.no/side/the-norwegian-consumer-council-awarded-epic-international-privacy-champion-award/
Source tier: primary
Source content: "The Norwegian Consumer Council received the 2021 EPIC International Privacy Champion Award"; work "'has played a major role in driving surveillance advertising reform globally'"; both "Out of Control" and "Time to Ban Surveillance-Based Advertising" named.
Comparison: Award, cited works, and quote match the NCC's own page (epic.org 403s per standing harness limits). Single authoritative source.
Decision: primary-sourced

## Claim 30: Grindr's pipeline exposed GPS location, IP addresses, advertising identifiers, age, gender, and sexual orientation

Source: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: "Every time you open an app like Grindr advertisement networks get your GPS location, device identifiers and even the fact that you use a gay dating app"; Datatilsynet notification: data shared "included GPS location, user profile data, and the fact that the user in question is on Grindr."
Comparison: GPS, device/advertising identifiers, and sexual-orientation exposure confirmed; "age" and "gender" appear in sources only as "user profile data" — the full six-item enumeration is attributed to the report PDF, which is unparseable. Partial confirmation of a specific enumeration. Audit limit, not an error finding.
Decision: uncorroborated

## Claim 31: scalar:sources[2].note — "confirmation of the fine by the Privacy Appeals Board in 2022" attributed to the noyb fine page

Source: https://noyb.eu/en/ncc-noyb-gdpr-complaint-grindr-fined-eu-63-mio-over-illegal-data-sharing
Source tier: primary
Source content: "The page states 'The case can now be appealed to the Norwegian Privacy Appeals Board (Personvernnemda) within three weeks' but provides no information about any actual appeal decision"; the Board's actual decision came September 2023 (Datatilsynet).
Comparison: Scalar path `sources[2].note` (noyb fine-page entry). The note asserts content the cited page does not carry (the page predates the Board's decision) and repeats the wrong year "2022" (correct: September 2023). Fix requires rewriting the note's final clause, not a single-token swap — prose judgment; Editor should flag to Researcher per the backfill act.
Decision: correction

## Claim 32: scalar:sources[3].note — the Datatilsynet record-fine page as "primary source for ... the Privacy Appeals Board upholding it in 2022, the Oslo District Court upholding it in March 2024, and the Borgarting Court of Appeal dismissing Grindr's further appeal after an August 2025 hearing"

Source: https://www.datatilsynet.no/en/news/aktuelle-nyheter-2023/record-fine-grindr-confirmed/
Source tier: primary
Source content: "The Privacy Appeals Board upheld the fine in 2023 ... This page does not contain information about court decisions at the district or appellate court level."
Comparison: Scalar path `sources[3].note`. The cited 2023 page dates the Board's confirmation to 2023 (not 2022) and carries none of the district-court or appeal-court content the note attributes to it; the court content lives at the Datatilsynet 2025 page (Claim 21) with corrected dates (July 2024 district court). Fix requires rewriting the note and likely re-pointing the citation — prose judgment; Editor should flag to Researcher.
Decision: correction

## Claim 33: scalar:sources[5].note — the EDRi event page as "primary source for the 23 June 2021 open letter ... co-signed by 60+ organisations including BEUC and EDRi" and Myrstad's title

Source: https://edri.org/take-action/events/transatlantic-discussion-time-to-ban-surveillance-based-advertising/
Source tier: primary
Source content: "The page only contains event details for a transatlantic discussion scheduled for 11 June 2021 ... he is 'Director of Digital Policy at the Norwegian Consumer Council (NCC)'."
Comparison: Scalar path `sources[5].note`. Myrstad's title is confirmed by the page; the open-letter date, 60+ count, and DSA-ban framing attributed to this page are not on it as fetched (cannot rule out page change since 2026-06-08). The letter facts themselves are supported elsewhere (Claims 25–28), and the 60+ count is source-conflicted (Claim 27). Not asserting a specific-token error against this note; the attribution cannot be confirmed.
Decision: uncorroborated
