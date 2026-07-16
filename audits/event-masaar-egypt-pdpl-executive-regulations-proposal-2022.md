---
entity_id: event-masaar-egypt-pdpl-executive-regulations-proposal-2022
entity_hash: ca9f0538cfd461f0089e2d643a6a55c4e064c0d6
audit_date: 2026-07-16
pass: 1
status: corrections-pending
claims_total: 22
claims_corroborated: 11
claims_primary_sourced: 6
claims_single_source: 3
claims_uncorroborated: 1
open_corrections: 1
sources_consulted:
  - https://masaar.net/en/data-protection-center-masaars-proposal-on-the-executive-regulations-for-the-data-protection-law/feed/
  - https://masaar.net/en/a-suspended-law-two-years-after-the-issuance-of-the-personal-data-protection-law-its-executive-regulations-havent-been-issued/feed/
  - https://masaar.net/en/possible-legislative-alternatives-about-the-executive-regulations-of-the-personal-data-protection-law/feed/
  - https://masaar.net/en/unwritten-rules-impacts-of-the-delayed-executive-regulations-of-data-protection-law-on-sensitive-data/feed/
  - https://www.accessnow.org/egypts-new-data-protection-law-data-protection-or-data-control/
  - https://www.shandpartners.com/insights/briefings/telecoms-media-technology/the-issuance-of-the-executive-regulations-of-the-data-protection-law-and-the-establishment-of-the-data-protection-centre/
  - https://www.legal500.com/developments/thought-leadership/overview-of-the-executive-regulations-of-the-egyptian-personal-data-protection-law/
  - https://www.dlapiperdataprotection.com/index.html?t=law&c=EG
  - https://www.bakermckenzie.com/en/insight/publications/2026/01/egypt-important-data-protection-update
  - https://www.loc.gov/item/global-legal-monitor/2020-10-29/egypt-countrys-first-law-on-protection-of-personal-data-enters-into-force/
  - https://cadeproject.org/updates/title-egypt-activates-data-protection-law-with-implementing-regulations-after-five-year-delay/
  - https://www.recordinglaw.com/world-laws/world-data-privacy-laws/egypt-data-privacy-laws/
  - https://shehatalaw.com/law-update/legal-alert-egyptian-court-judgment-tightens-enforcement-of-privacy-and-data-protection-laws/
  - https://www.kennedyslaw.com/en/thought-leadership/article/2026/egypt-s-personal-data-protection-law-the-compliance-countdown-has-begun/
  - https://www.facebook.com/Masaarnet/
---

## Claim 1: edge participating_orgs → org-masaar ("Masaar — Technology and Law Community published a coordinated package of civil society policy proposals on the executive regulations")

Source: https://masaar.net/en/data-protection-center-masaars-proposal-on-the-executive-regulations-for-the-data-protection-law/ (and the three companion masaar.net URLs cited in frontmatter)
Source tier: primary
Source content: All four cited papers are live masaar.net publications — "Data Protection Center: Masaar's Proposal on the Executive Regulations for the Data Protection Law", "A Suspended Law: Two years after the issuance of the Personal Data Protection Law, its executive regulations haven't been issued", "Possible Legislative Alternatives.. About the Executive Regulations of the Personal Data Protection Law", "Unwritten Rules: Impacts of the Delayed Executive Regulations of Data Protection Law on Sensitive Data" (article pages 403 on direct fetch; titles/content confirmed via search index and each page's /feed/ endpoint, which fetches fine).
Comparison: Edge points to the correct entity — Masaar authored and published all four cited papers; `product/entities/organizations/org-masaar.md` exists. The edge itself is correct; the "in 2022" packaging is Claim 2.
Decision: corroborated

## Claim 2: "In 2022, [Masaar] published a coordinated package of civil society policy proposals" + frontmatter `date: 2022` + `name: '…(2022)'` + "coordinated set of policy papers in 2022" + "The 2022 Masaar proposal package"

Source: https://masaar.net/en/possible-legislative-alternatives-about-the-executive-regulations-of-the-personal-data-protection-law/feed/ (and the other three /feed/ endpoints)
Source tier: primary
Source content: Per-article WordPress feed metadata on masaar.net itself: "Possible Legislative Alternatives" — "Thu, 09 Sep 2021 08:20:55 +0000"; "A Suspended Law" — "Wed, 10 Aug 2022 10:30:58 +0000"; "Unwritten Rules" — "Mon, 20 Feb 2023 11:06:03 +0000"; "Data Protection Center: Masaar's Proposal" — "Mon, 18 Mar 2024 13:19:18 +0000". Search-index publish metadata independently gives the same dates ("The proposal was published on March 18, 2024"; "The article was published on February 20, 2023"; "published in August 2022" for A Suspended Law).
Comparison: The four papers were published September 2021, August 2022, February 2023, and March 2024 — only "A Suspended Law" is a 2022 publication. The entity's core date token (frontmatter `date: 2022`, the "(2022)" in `name:`, and the three body statements dating the package to 2022) contradicts the best sources; the correct value is the span 2021–2024. Each paper's content is internally consistent with its feed date (the Sept 2021 alternatives paper ~1 year after entry into force; "A Suspended Law" marking two years; the March 2024 proposal noting no regulations had yet been issued). Caveat: comment-feed lastBuildDate can track post modification rather than first publication, but all four match the search-index publish dates exactly, so modification-drift is unlikely. Fix locations: frontmatter `date:`, frontmatter `name:`, and the "2022 package" framing in the opening paragraph, the "Masaar's proposal package" section opener, and the Significance section — the framing pervades the body, so this correction requires prose judgment beyond a single replacement (Editor → Researcher flag path).
Decision: correction

## Claim 3: scalar:location — "Cairo, Egypt"

Source: https://www.facebook.com/Masaarnet/ (search-index listing; page itself not fetched)
Source tier: primary
Source content: "Masaar - مَسَار | Cairo | Facebook" — the organisation's own public profile self-locates in Cairo. Masaar's Egyptian identity is corroborated broadly (its own About page: "enhancing and promoting digital rights and related freedoms in Egypt").
Comparison: The event is a publication series with no physical venue; the location scalar reflects the publishing organisation's base. Cairo is Masaar's self-reported location (same finding as the org-masaar audit, Claim 1); Egypt is corroborated everywhere. One authoritative self-statement supports the Cairo token.
Decision: primary-sourced

## Claim 4: "Egypt enacted Law No. 151 of 2020 on the protection of personal data in July 2020 … The law entered into force in October 2020"

Source: https://www.loc.gov/item/global-legal-monitor/2020-10-29/egypt-countrys-first-law-on-protection-of-personal-data-enters-into-force/
Source tier: primary
Source content: LOC Global Legal Monitor item (2020-10-29): "Egypt: Country's First Law on Protection of Personal Data Enters into Force". Recording Law: "the law was ratified on July 13, 2020, by Egyptian president Abdel Fattah al-Sisi, and enforcement began 90 days after its publication in Egypt's Official Gazette on July 15, 2020."
Comparison: July 2020 enactment and October 2020 entry into force match multiple independent canonical sources (LOC government record, law-firm analyses, Recording Law).
Decision: corroborated

## Claim 5: "drawing heavily on the European General Data Protection Regulation (GDPR)"

Source: https://masaar.net/en/data-protection-center-masaars-proposal-on-the-executive-regulations-for-the-data-protection-law/
Source tier: primary
Source content: "The Egyptian Personal Data Protection Law was greatly influenced by the European General Data Protection Regulation (GDPR)" (search-index content of Masaar's proposal paper); law-firm jurisdiction guides (DLA Piper, ICLG) make the same GDPR-derivation point.
Comparison: GDPR influence on Law 151/2020 is a standard characterization across Masaar's own analysis and multiple law-firm sources.
Decision: corroborated

## Claim 6: "executive regulations that the law required to be issued within six months of coming into force — by the second quarter of 2021. Those regulations were not issued by that deadline, nor in the two years that followed"

Source: https://masaar.net/en/a-suspended-law-two-years-after-the-issuance-of-the-personal-data-protection-law-its-executive-regulations-havent-been-issued/
Source tier: primary
Source content: Masaar's article (per search index) states the delay "violated the law's article determining a deadline for issuing the executive regulations in the second quarter of 2021"; PwC/Signzy-class summaries: "The Law's Executive Regulation was planned to be issued within 6 months of the Law's issuance (approximately by April 2021)"; regulations were in fact issued only in November 2025.
Comparison: Six-months deadline landing in Q2 2021 (April 2021, six months from the October 2020 entry into force) matches Masaar's account and independent law-firm summaries; non-issuance through 2022 and beyond is corroborated by the November 2025 issuance record.
Decision: corroborated

## Claim 7: "The Personal Data Protection Center — the law's planned regulatory body, with power to enforce the law, issue licenses, and receive complaints — could not be formed without the executive regulations" / "the suspended formation of the Data Protection Center"

Source: https://www.shandpartners.com/insights/briefings/telecoms-media-technology/the-issuance-of-the-executive-regulations-of-the-data-protection-law-and-the-establishment-of-the-data-protection-centre/
Source tier: mainstream
Source content: Shand & Partners pairs "the issuance of the executive regulations" with "the establishment of the Data Protection Centre" (2025); CADE: the law "sat largely dormant for five years, because the executive regulations needed to operationalize key provisions were never issued"; Masaar's "A Suspended Law" names the suspended formation of the Center.
Comparison: The Center's formation waiting on the executive regulations is corroborated by the 2025 record (Center established/website launched only after Decree 816/2025) and Masaar's contemporaneous account. The Center's mandate (enforce, license, receive complaints) matches DLA Piper and Access Now descriptions.
Decision: corroborated

## Claim 8: "Entities collecting and processing personal data could not obtain the legally required licenses"

Source: https://www.legal500.com/developments/thought-leadership/overview-of-the-executive-regulations-of-the-egyptian-personal-data-protection-law/
Source tier: mainstream
Source content: "One of the most significant regulatory shifts introduced by the Executive Regulations No. 816 of 2025 is the establishment of a comprehensive, graduated licensing and permitting regime governing all personal data processing activities" (legal500/law-firm coverage); Kennedys: a one-year grace period to "secure mandatory licences" runs to 31 October 2026.
Comparison: The licensing regime only became operable with the 2025 regulations, corroborating that licenses were unobtainable during the 2020–2025 gap; consistent with Masaar's "A Suspended Law".
Decision: corroborated

## Claim 9: "Sensitive-data protections … remained unenforceable because their procedural implementation was entirely delegated to the missing regulations" (and the "Unwritten Rules" summary paragraph)

Source: https://masaar.net/en/unwritten-rules-impacts-of-the-delayed-executive-regulations-of-data-protection-law-on-sensitive-data/
Source tier: primary
Source content: Paper title: "Unwritten Rules: Impacts of the Delayed Executive Regulations of Data Protection Law on Sensitive Data"; search index describes it as addressing "the impacts of delayed executive regulations concerning data protection law and sensitive data".
Comparison: The claim matches the paper's stated subject, but rests on that single Masaar paper (article body not fetchable; 403). No independent source specifically confirms the "entirely delegated to the regulations" mechanism, though Kennedys lists "special categories of data" among matters operationalized only by the 2025 regulations.
Decision: single-source

## Claim 10: "Multiple members of the Egyptian Parliament filed formal queries to the Prime Minister and the Minister of Communications and Information Technology (CIT) demanding the regulations' issuance"

Source: https://masaar.net/en/a-suspended-law-two-years-after-the-issuance-of-the-personal-data-protection-law-its-executive-regulations-havent-been-issued/
Source tier: primary
Source content: Masaar's article (per search index) documents parliamentary pressure over the delay, including a Senate member's demand to the Minister of CIT.
Comparison: Rests on Masaar's article alone; no independent parliamentary-record or press source located for the plural "multiple members … to the Prime Minister" specifics.
Decision: single-source

## Claim 11: "In August 2022, Senator Hassanin Tawfik filed a formal demand to the Minister of CIT, characterising the multi-year delay as a violation of the law's own statutory deadline and as a jeopardising of Egyptian citizens' data protection rights"

Source: https://masaar.net/en/a-suspended-law-two-years-after-the-issuance-of-the-personal-data-protection-law-its-executive-regulations-havent-been-issued/
Source tier: primary
Source content: "Senator Hassanin Tawfik, a member of the Education and Communication Committee in the Senate, demanded that the Minister of CIT expedite the issuance of the delayed executive regulations for the Personal Data Protection Law, emphasizing that the extended delay suspends the law and jeopardizes the protection of citizens' data" (search-index content of the article, published 2022-08-10 per its feed).
Comparison: Name, addressee, and characterization match the source. The "August 2022" dating of the demand is inferred from the article's 2022-08-10 publication date (the source content does not itself date the demand). An Arabic-language search for independent Egyptian-press coverage of the Tawfik demand returned nothing; rests on Masaar's article alone.
Decision: single-source

## Claim 12: "The PDPL established the Center as a public economic authority under the Ministry of Communications"

Source: https://www.dlapiperdataprotection.com/index.html?t=law&c=EG
Source tier: mainstream
Source content: "The Personal Data Protection Centre (the 'Centre') is a public economic authority that has a legal personality and is under the authority of the Minister of Communications and Information Technology." Access Now: the Center is "established under the Minister of ICT."
Comparison: Exact match on both tokens (public economic authority; under the Ministry of Communications/ICT) across two independent canonical sources.
Decision: corroborated

## Claim 13: "The Center's board must include representatives from the Ministry of Defence, the Ministry of Interior, and the Intelligence Services alongside seven other members, and follows the Minister rather than operating at arm's length from executive power"

Source: https://www.accessnow.org/egypts-new-data-protection-law-data-protection-or-data-control/
Source tier: mainstream
Source content: "the board must include representatives from the Ministry of Defence, the Ministry of Interior, and the Intelligence Services, among seven other members." … "Yet the agency will have a board appointed by the Minister…" "That does not represent independent oversight of this regulatory function, especially since the board has decision-making authority."
Comparison: Near-verbatim match with Access Now (fetched); law-translation summaries (Andersen/ACC, via search index) independently list board representatives from the ministries of Defence, Interior, and the General Intelligence Service, with the board chaired by the Competent Minister.
Decision: corroborated

## Claim 14: "Masaar's proposal argues that the executive regulations should include explicit guarantees of the Center's independence — drawing on the European Data Protection Board model — and protective provisions for employees and whistleblowers facing political interference"

Source: https://masaar.net/en/data-protection-center-masaars-proposal-on-the-executive-regulations-for-the-data-protection-law/
Source tier: primary
Source content: "the paper seeks to take into account the most important rules concerning the European Data Protection Board that can be compatible with Egyptian law" … "a special provision in the Data Protection Law or its executive regulations should ensure the protection of violation reporters (whistleblowers). This would enable the Center's staff and others to report any attempted interference or political pressure without fear of retribution" (search-index content of the proposal paper).
Comparison: All three elements (independence guarantees, EDPB model, employee/whistleblower protection against political interference) match the paper's own content. Claim about the paper's content, supported by the paper itself — one authoritative source.
Decision: primary-sourced

## Claim 15: "The proposal recommends that any changes to the Center's operation or enabling legislation require the Center's own approval, preventing unilateral executive interference in its governance"

Source: https://masaar.net/en/data-protection-center-masaars-proposal-on-the-executive-regulations-for-the-data-protection-law/
Source tier: primary
Source content: "there should be a rule requiring parliament and executive authority to get the Center's approval of any changes or legislation concerning its operation" (search-index content of the proposal paper).
Comparison: Matches the paper's recommendation as stated by the paper itself.
Decision: primary-sourced

## Claim 16: "The executive regulations were ultimately issued in November 2025, five years after the law entered into force, as Executive Decree No. 816 of 2025 by the Ministry of Communications"

Source: https://www.shandpartners.com/insights/briefings/telecoms-media-technology/the-issuance-of-the-executive-regulations-of-the-data-protection-law-and-the-establishment-of-the-data-protection-centre/
Source tier: mainstream
Source content: The Executive Regulations were issued pursuant to "Minister of Communications and Information Technology Decree No. 816 of 2025" and "entered into force on the day following their publication in the Official Gazette on November 2, 2025" (fetched). Baker McKenzie: issued "by virtue of Minister of Telecommunications Decree No. 816 of 2025". CADE: "after five-year delay".
Comparison: Decree number (816 of 2025), November 2025 timing, issuing ministry (Communications/ICT), and the five-year gap from October 2020 all match. Note: one search-engine paraphrase attributed the decree to the Prime Minister, but the underlying legal500 page (fetched) names no issuing authority — no verified source conflict.
Decision: corroborated

## Claim 17: "The long-delayed regulations transformed the PDPL … by introducing licensing requirements, breach notification procedures, data-subject rights mechanisms, and cross-border transfer rules"

Source: https://www.kennedyslaw.com/en/thought-leadership/article/2026/egypt-s-personal-data-protection-law-the-compliance-countdown-has-begun/
Source tier: mainstream
Source content: "The Regulations detail operational rules for consent, licensing, record-keeping, breach notification, cross-border data transfers, special categories of data, children's data, and direct electronic marketing" (law-firm coverage via search index); legal500 (fetched) describes the graduated licensing regime as the most significant regulatory shift.
Comparison: All four enumerated mechanisms appear in independent law-firm summaries of Decree 816/2025.
Decision: corroborated

## Claim 18: "its analysis of the 2025 Orange Egypt telecom compensation ruling, the first significant judicial application of the PDPL against a corporate actor"

Source: https://shehatalaw.com/law-update/legal-alert-egyptian-court-judgment-tightens-enforcement-of-privacy-and-data-protection-laws/
Source tier: mainstream
Source content: "In February 2025, the Alexandria Economic Court ruled that Orange Egypt Telecom would pay EGP 10 million in compensation to a woman whose personal data had been violated" … "this ruling is significant as it represents the first prominent judicial application concerning the accountability of telecommunications companies for violating user privacy" (search-index content); Masaar's own analysis exists: "First Judicial Application of the Personal Data Protection Law: A Reading of a Compensation Ruling Against Orange" (masaar.net).
Comparison: The ruling (2025, Orange Egypt, compensation), Masaar's analysis of it, and the "first judicial application" framing all corroborated across Masaar's own publication and independent law-firm coverage.
Decision: corroborated

## Claim 19: scalar:sources[0].note — "Masaar's core proposal on the formation and independence of the Personal Data Protection Center — primary source for the governance recommendations, the analysis of the Center's structural dependence under the Ministry of Communications, the security-sector board representation, and the GDPR-comparative independence framework"

Source: https://masaar.net/en/data-protection-center-masaars-proposal-on-the-executive-regulations-for-the-data-protection-law/
Source tier: primary
Source content: "Masaar presented a practical proposal for the formation of the Personal Data Protection Center" … "rules ensuring the Center's complete legal independence from executive authority" … EDPB-comparative framework (search-index content of the paper).
Comparison: Formation, independence recommendations, and the EDPB/GDPR-comparative framework are confirmed as the paper's content; the structural-dependence and security-sector-board analysis matches the documented critique of the law (Access Now, Claim 13) though those specific paragraphs of the paper were not directly observed. Scalar path: `sources[0].note`.
Decision: primary-sourced

## Claim 20: scalar:sources[1].note — "Masaar's 'A Suspended Law' article … primary source for parliamentary demands, Senator Hassanin Tawfik's August 2022 demand to the Minister of CIT, suspended formation of the Personal Data Protection Center, and the violation of the law's own deadline"

Source: https://masaar.net/en/a-suspended-law-two-years-after-the-issuance-of-the-personal-data-protection-law-its-executive-regulations-havent-been-issued/
Source tier: primary
Source content: Article (published 2022-08-10 per feed) documents the Tawfik demand to the Minister of CIT, the suspension of the law's implementation, and the violated Q2-2021 deadline (search-index content quoted at Claims 6 and 11).
Comparison: Note accurately describes the cited article's contents. Scalar path: `sources[1].note`.
Decision: primary-sourced

## Claim 21: scalar:sources[2].note — "Masaar's 'Possible Legislative Alternatives' policy paper — primary source for legislative-design analysis of the executive regulations, scope-of-protection alternatives, user-rights mechanisms, and proposed regulatory body governance frameworks"

Source: https://masaar.net/en/possible-legislative-alternatives-about-the-executive-regulations-of-the-personal-data-protection-law/
Source tier: primary
Source content: Search-index content confirms the paper "focuses on the repercussions and effects of the delay in issuing the executive regulations" and that the law delegated rules to the regulations "crossing eighteen different places"; published 2021-09-09 per its feed.
Comparison: The paper exists and is legislative-design analysis of the executive regulations, but the note's specific enumeration (scope-of-protection alternatives, user-rights mechanisms, governance frameworks) could not be observed in the retrievable record — article body 403s and snippets cover only the delay analysis and delegation problem. Too thin to compare the enumerated specifics. Scalar path: `sources[2].note`.
Decision: uncorroborated

## Claim 22: scalar:sources[3].note — "Masaar's 'Unwritten Rules' policy paper — primary source for the analysis of how the regulatory delay left sensitive-data categories without enforceable protections and the cascading impact on data subjects in the absence of implementing rules"

Source: https://masaar.net/en/unwritten-rules-impacts-of-the-delayed-executive-regulations-of-data-protection-law-on-sensitive-data/
Source tier: primary
Source content: Paper title: "Unwritten Rules: Impacts of the Delayed Executive Regulations of Data Protection Law on Sensitive Data" (published 2023-02-20 per feed); search index: it addresses "the impacts of delayed executive regulations concerning data protection law and sensitive data".
Comparison: The note's description matches the paper's stated subject (delay's impact on sensitive-data protection) as declared by the paper's own title and indexed description. Scalar path: `sources[3].note`.
Decision: primary-sourced
