---
entity_id: camp-iure-prague-airport-facial-recognition-czechia-2021-2025
entity_hash: 6393c6d378853ecf6d6f217e20bb92436135f0c1
audit_date: 2026-07-05
pass: 1
status: supported
claims_total: 37
claims_corroborated: 14
claims_primary_sourced: 15
claims_single_source: 5
claims_uncorroborated: 3
open_corrections: 0
sources_consulted:
  - https://edri.org/our-work/czech-police-forced-to-turn-off-facial-recognition-cameras-at-the-prague-airport-thanks-to-the-ai-act/
  - https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
  - https://edri.org/our-work/big-brother-at-the-prague-airport-the-state-refuses-to-explain-how-the-biometric-camera-system-works/
  - https://edri.org/our-work/biometric-surveillance-in-the-czech-republic-the-ministry-of-the-interior-is-trying-to-circumvent-the-artificial-intelligence-act/
  - https://edri.org/our-work/czech-police-use-facial-recognition-system-iure-finds-out-details/
  - https://monitor.civicus.org/explore/cso-report-reveals-covert-use-of-biometric-surveillance-by-czech-police/
  - https://digitalnisvobody.cz/blog/2023/07/21/policie-nemluvi-pravdu-kdyz-tvrdi-ze-o-biometrickem-systemu-dopredu-informovala/
---

Type-shape: campaign (connective). Claim surface = edges + hard specifics per
`AUDITOR.md § Type-shape` and `mission/MISSION.md § Auditor § Type-shape awareness`.
Significance/arc prose without hard specifics received no decision. Tier note: EDRi
member-update articles on this campaign are IuRe-authored guest posts (authorship
confirmed in-fetch for the Nov 2021 and Aug 2025 articles) — treated as the entity's
own statements, tier `primary`. Two IuRe-authored EDRi articles are the same author,
so they never jointly corroborate.

## Claim 1: edge `lead_orgs: [org-iure]` + body link to org-iure

Source: product/entities/organizations/org-iure.md + all cited sources
Source tier: primary
Source content: org-iure frontmatter: "name: Iuridicum Remedium (IuRe)"; EDRi: "EDRi member IuRe drew attention to the situation back in 2021"; Biometric Update: "Legal experts from IuRe filed a formal complaint with the DPA in 2021"
Comparison: Edge resolves to the correct entity; every source attributes the campaign to IuRe.
Decision: corroborated

## Claim 2: scalar:start_date — 2021 (campaign began with IuRe's 2021 complaint)

Source: https://edri.org/our-work/czech-police-forced-to-turn-off-facial-recognition-cameras-at-the-prague-airport-thanks-to-the-ai-act/ ; https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
Source tier: primary
Source content: EDRi: "EDRi member IuRe drew attention to the situation back in 2021"; Biometric Update: "Legal experts from IuRe filed a formal complaint with the DPA in 2021"
Comparison: Two independent sources place the campaign's opening filing in 2021.
Decision: corroborated

## Claim 3: scalar:end_date — 2025; "shut down in August 2025 — seven years after its deployment"

Source: same two as Claim 2
Source tier: primary
Source content: EDRi: system operated "from 2018, until it was shut down in August 2025"; Biometric Update: "The system operated since 2018" and was turned off in 2025 (article dated 30 Oct 2025)
Comparison: Shutdown date and the 2018→2025 seven-year span confirmed by both.
Decision: corroborated

## Claim 4: "deployed the biometric camera system at Václav Havel Airport in 2018"

Source: same two as Claim 2
Source tier: primary
Source content: EDRi: operated "from 2018"; Biometric Update: "The system operated since 2018"
Comparison: Deployment year confirmed by two independent sources; airport identity consistent throughout.
Decision: corroborated

## Claim 5: "converted passengers' facial contours into numerical 'bio-indexes' and compared them in real-time against databases of wanted or missing individuals"

Source: https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
Source tier: mainstream
Source content: "real-time biometric analysis of travelers' faces, converting facial contours into numerical 'bio-indexes'" compared "against databases of wanted or missing individuals"
Comparison: Exact match; only Biometric Update carries this mechanism detail.
Decision: single-source

## Claim 6: "approximately 3.6 million annual passengers plus hundreds of thousands of individuals passing through pre-transit areas"

Source: https://edri.org/our-work/big-brother-at-the-prague-airport-the-state-refuses-to-explain-how-the-biometric-camera-system-works/
Source tier: primary
Source content: "about 3.6 million passengers who checked in the last year" plus "hundreds of thousands of other people who moved just through the pre-transit area" (IuRe-authored, 17 Nov 2021)
Comparison: Matches; source's figure is for 2020 (a Covid year), body's "approximately … annual" is a fair rendering.
Decision: primary-sourced

## Claim 7: "biometric data was retained for 30 days before deletion" / Foreign Police 30-day retention

Source: https://edri.org/our-work/big-brother-at-the-prague-airport-the-state-refuses-to-explain-how-the-biometric-camera-system-works/
Source tier: primary
Source content: "they only store it for thirty days"
Comparison: Matches (also frontmatter sources[2].note names the 30-day retention).
Decision: primary-sourced

## Claim 8: Václav Mach data-subject request; 30-day retention made access structurally impossible

Source: https://edri.org/our-work/big-brother-at-the-prague-airport-the-state-refuses-to-explain-how-the-biometric-camera-system-works/
Source tier: primary
Source content: Mach requested his biometric data; "the Foreign Police responded they no longer retained his records because data storage lasted only 30 days, preventing him from accessing information about himself"
Comparison: Name, request, and impossibility mechanism all match the IuRe-authored account.
Decision: primary-sourced

## Claim 9: Foreign Police refused to disclose purposes, legal justification, access, and measurements

Source: https://edri.org/our-work/big-brother-at-the-prague-airport-the-state-refuses-to-explain-how-the-biometric-camera-system-works/
Source tier: primary
Source content: "The authorities withheld details about biometric camera operations, providing only 'general phrases' while keeping secret what they could"
Comparison: Body's opacity claims match the IuRe-authored account (also frontmatter sources[2].note).
Decision: primary-sourced

## Claim 10: core legal argument — Czech law required biometric processing to rest on explicit permission from a special statute

Source: https://edri.org/our-work/big-brother-at-the-prague-airport-the-state-refuses-to-explain-how-the-biometric-camera-system-works/ ; https://edri.org/our-work/czech-police-forced-to-turn-off-facial-recognition-cameras-at-the-prague-airport-thanks-to-the-ai-act/
Source tier: primary
Source content: EDRi 2025: IuRe argued "that biometric data processing required explicit legal permission"; EDRi 2021 makes the same statutory argument
Comparison: Matches, but both confirming articles are IuRe-authored (same author, not independent).
Decision: primary-sourced

## Claim 11: Czech Republic implemented the Law Enforcement Directive's mandatory DPIA requirement after the airport system launched

Source: https://edri.org/our-work/big-brother-at-the-prague-airport-the-state-refuses-to-explain-how-the-biometric-camera-system-works/
Source tier: primary
Source content: "The Czech Republic implemented the EU's Data Protection Directive on law enforcement (requiring personal data protection impact assessments) only *after* the biometric system launched … the article argues the EU directive's implementation period had already expired"
Comparison: Matches, including the implementation-timeline-violation framing.
Decision: primary-sourced

## Claim 12: formal complaint filed to the Czech DPA in 2021

Source: same two as Claim 2
Source tier: primary
Source content: EDRi: "IuRe drew attention to the situation back in 2021" and filed a complaint with the DPA; Biometric Update: "filed a formal complaint with the DPA in 2021"
Comparison: Filing and year confirmed by two independent sources.
Decision: corroborated

## Claim 13: complaint "argued that the biometric data processing … violated both GDPR's proportionality and necessity principles and the Czech Personal Data Processing Act's requirement of explicit legal authority"

Source: https://edri.org/our-work/czech-police-forced-to-turn-off-facial-recognition-cameras-at-the-prague-airport-thanks-to-the-ai-act/
Source tier: primary
Source content: Fetched content confirms only the general argument that "biometric data processing required explicit legal permission" — the specific GDPR proportionality/necessity + Czech Personal Data Processing Act framing was not found in fetched source content
Comparison: Partial confirmation only; the specific legal-grounds enumeration could not be confirmed as stated. Not a contradiction — no correction token.
Decision: uncorroborated

## Claim 14: "the investigation ran for nearly four years"

Source: https://edri.org/our-work/czech-police-forced-to-turn-off-facial-recognition-cameras-at-the-prague-airport-thanks-to-the-ai-act/ ; https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
Source tier: primary
Source content: EDRi: the inspection "took almost four years"; Biometric Update: complaint 2021, findings obtained mid-2025 "following a multi-year investigation"
Comparison: EDRi states it directly; Biometric Update's 2021→mid-2025 timeline independently supports the same duration.
Decision: corroborated

## Claim 15: FOI strategy — IuRe obtained the inspection results through the FOI route in summer/mid-2025

Source: https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
Source tier: mainstream
Source content: "In mid-2025, the DPA's findings (obtained via a Freedom of Information request) validated concerns that the system breached national and European data protection regulations."
Comparison: FOI route confirmed only by Biometric Update; EDRi confirms the summer-2025 results but not the FOI mechanism. Body's dual-function framing (procedural pressure + public reporting) is interpretation, no decision.
Decision: single-source

## Claim 16: DPA "confirmed violations of national and European personal data protection legislation" (mid-2025)

Source: same two as Claim 14
Source tier: primary
Source content: EDRi: "confirmed the suspicion of a violation of personal data protection legislation" (results in summer 2025); Biometric Update: "breached national and European data protection regulations"
Comparison: Finding and timing confirmed by two independent sources (also scalar:outcomes).
Decision: corroborated

## Claim 17: EU AI Act biometric provisions entered force February 2025, requiring judicial approval for each specific deployment

Source: same two as Claim 14
Source tier: primary
Source content: EDRi: the regulation "explicitly requires judicial approval for each use of such a system" effective February 2025; Biometric Update: "the EU AI Act implemented in February 2025, which mandates judicial approval for biometric surveillance"
Comparison: Date and requirement confirmed by both; also a public-record fact of EU law.
Decision: corroborated

## Claim 18: police "continued operating it for six months — from February through August 2025 — in documented illegality, despite repeated public warnings"

Source: same two as Claim 14
Source tier: primary
Source content: EDRi: "From February 2025 until August 2025, 'the police's use of this system was illegal,' despite repeated warnings"; Biometric Update: system "became illegal under the EU AI Act implemented in February 2025 … approval the airport system never received", shutdown 2025
Comparison: Six-month window and warnings confirmed (also scalar:outcomes "six months despite repeated warnings").
Decision: corroborated

## Claim 19: post-shutdown call on Interior Minister Vít Rakušan to initiate a comprehensive legislative review

Source: https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
Source tier: mainstream
Source content: "IuRe called on Interior Minister Vít Rakušan 'to initiate a legislative review, arguing that Czech law fails to meet EU standards for biometric data safeguards.'"
Comparison: Biometric Update names Rakušan; the IuRe-authored EDRi article addresses "the new Czech Minister of the Interior" without naming one (post-Oct-2025-election framing) — divergent but not contradictory; only one source carries the name. Appears in body and scalar:outcomes and scalar:sources[0-1].note.
Decision: single-source

## Claim 20: IuRe disclosed the IS DPO in July 2023

Source: https://monitor.civicus.org/explore/cso-report-reveals-covert-use-of-biometric-surveillance-by-czech-police/ ; https://digitalnisvobody.cz/blog/2023/07/21/policie-nemluvi-pravdu-kdyz-tvrdi-ze-o-biometrickem-systemu-dopredu-informovala/
Source tier: database
Source content: CIVICUS: "On July 12, 2023, the NGO Iuridicum Remedium released findings"; IuRe's own post (21 Jul 2023) references the July revelations
Comparison: Date confirmed by an independent monitor and the entity's own contemporaneous post.
Decision: corroborated

## Claim 21: IS DPO covertly launched August 2022

Source: https://edri.org/our-work/czech-police-use-facial-recognition-system-iure-finds-out-details/ ; https://monitor.civicus.org/explore/cso-report-reveals-covert-use-of-biometric-surveillance-by-czech-police/
Source tier: primary
Source content: CIVICUS: "in operation since 22nd August 2022"; IuRe post: "provoz byl spuštěn až v srpnu 2022" (operation was launched only in August 2022); EDRi Sept 2023: launch August 2022
Comparison: Launch month confirmed by multiple independent sources.
Decision: corroborated

## Claim 22: reference database of ~19.67 million photographs from national ID cards and travel documents (scalar:outcomes: "approximately 20 million")

Source: https://edri.org/our-work/czech-police-use-facial-recognition-system-iure-finds-out-details/ ; https://monitor.civicus.org/explore/cso-report-reveals-covert-use-of-biometric-surveillance-by-czech-police/ ; https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
Source tier: primary
Source content: EDRi: "more than 19.6 million photographs"; CIVICUS: "19 666 787 fotografií"; Biometric Update: "roughly 20 million photographs from national ID and passport records"
Comparison: 19.67M exact figure and the ~20M outcomes rounding both confirmed by independent sources.
Decision: corroborated

## Claim 23: 73 personnel across three police departments authorised for access

Source: https://edri.org/our-work/czech-police-use-facial-recognition-system-iure-finds-out-details/ ; https://monitor.civicus.org/explore/cso-report-reveals-covert-use-of-biometric-surveillance-by-czech-police/
Source tier: primary
Source content: EDRi: "73 people from three different police departments"; CIVICUS: "Personnel authorized for system access numbered 73 individuals total"
Comparison: Count and department split confirmed by two independent sources.
Decision: corroborated

## Claim 24: police operated IS DPO ~a year without disclosing to parliamentary oversight; IuRe stated the transparency claim "is not true"

Source: https://edri.org/our-work/czech-police-use-facial-recognition-system-iure-finds-out-details/ ; https://monitor.civicus.org/explore/cso-report-reveals-covert-use-of-biometric-surveillance-by-czech-police/ ; https://digitalnisvobody.cz/blog/2023/07/21/policie-nemluvi-pravdu-kdyz-tvrdi-ze-o-biometrickem-systemu-dopredu-informovala/
Source tier: primary
Source content: EDRi: "according to the minutes of the meeting between the committee and the police, this is not true"; CIVICUS: "a meeting with police representatives occurred on the 6th of October 2021, a year before the programme's initiation, there was no mention of the actual use of IS DPO"; IuRe post: "O samotném využití IS DPO nepadlo ani slovo"
Comparison: Non-disclosure, ~one-year covert window, and the direct "is not true" quote all confirmed.
Decision: corroborated

## Claim 25: police cited § 66a of Act No. 273/2008; IuRe countered it authorises photograph acquisition, not biometric identification

Source: https://digitalnisvobody.cz/blog/2023/07/21/policie-nemluvi-pravdu-kdyz-tvrdi-ze-o-biometrickem-systemu-dopredu-informovala/ ; https://edri.org/our-work/czech-police-use-facial-recognition-system-iure-finds-out-details/
Source tier: primary
Source content: IuRe post: police claim the system is "provozován na základě ustanovení § 66a zákona č. 273/2008 Sb." and the provision contains "ani slovo o jejich využívání za účelem biometrické identifikace" (not a word about use for biometric identification); EDRi confirms the same argument citing "a 2019 amendment of the Police Act" without the section number
Comparison: The § 66a token is confirmed on the entity's own platform; the acquisition-vs-identification counter-argument matches both sources. Both are IuRe-voiced, so not independent corroboration.
Decision: primary-sourced

## Claim 26: critical sections of documentation provided to IuRe were redacted

Source: https://monitor.civicus.org/explore/cso-report-reveals-covert-use-of-biometric-surveillance-by-czech-police/
Source tier: database
Source content: "critical sections of the documents were redacted, thereby concealing vital information"
Comparison: Matches; confirmed in fetched content only by CIVICUS (frontmatter attributes it to the EDRi Sept 2023 article too, but the fetch did not surface it there).
Decision: single-source

## Claim 27: IS DPO's "basic parameters and rules of operation" regulated only by classified internal police instructions, not publicly accessible legislation

Source: https://edri.org/our-work/czech-police-use-facial-recognition-system-iure-finds-out-details/
Source tier: primary
Source content: "The basic parameters and rules of operation of such an information system and rules of its use are missing in the law and are regulated only by the secret instructions by the Chief of Police"
Comparison: Matches; body's "classified internal police instructions" renders the source's "secret instructions by the Chief of Police".
Decision: primary-sourced

## Claim 28: DPIA for IS DPO completed only after IuRe's investigation, likely prompted by the disclosure

Source: https://edri.org/our-work/czech-police-use-facial-recognition-system-iure-finds-out-details/
Source tier: primary
Source content: DPIA "completed one year after launch, presumably on the basis of the IuRe's findings and media pressure"
Comparison: Matches, including the hedged causal framing ("likely prompted").
Decision: primary-sourced

## Claim 29: September 2024 — Czech government approved the Ministry of the Interior proposal to legalise automated facial recognition at international airports

Source: https://edri.org/our-work/biometric-surveillance-in-the-czech-republic-the-ministry-of-the-interior-is-trying-to-circumvent-the-artificial-intelligence-act/
Source tier: primary
Source content: "In September, the Czech government adopted a proposal by the Ministry of the Interior to legalise automated facial recognition at international airports" (article dated 9 Oct 2024, so September = 2024)
Comparison: Matches. Web search surfaced only the Reclaim Your Face mirror of the same article — no independent second source found in-session.
Decision: primary-sourced

## Claim 30: the proposal as government-modified reduced retention of unrecognised visitor data from 90 to 30 days

Source: https://edri.org/our-work/biometric-surveillance-in-the-czech-republic-the-ministry-of-the-interior-is-trying-to-circumvent-the-artificial-intelligence-act/
Source tier: primary
Source content: retention "reduced from 90 to 30 days"
Comparison: Exact match.
Decision: primary-sourced

## Claim 31: AI Act requires authorisation for a specific person; proposal allowed "predefined categories of persons"; "virtually anyone can be included in the database"

Source: https://edri.org/our-work/biometric-surveillance-in-the-czech-republic-the-ministry-of-the-interior-is-trying-to-circumvent-the-artificial-intelligence-act/
Source tier: primary
Source content: "the use of a facial recognition system on a specific person must be authorised by a court or other independent authority"; proposal allows "predefined categories of persons"; "With such a vague definition, virtually anyone can be included in the database"
Comparison: All three tokens, including the direct quote, match verbatim.
Decision: primary-sourced

## Claim 32: IuRe launched "Czech Republic is not China" — an interactive online quiz, Czech-language only

Source: https://edri.org/our-work/biometric-surveillance-in-the-czech-republic-the-ministry-of-the-interior-is-trying-to-circumvent-the-artificial-intelligence-act/
Source tier: primary
Source content: "a website called 'The Czech Republic is not China' (noted as Czech-language only), presenting the issue through an interactive quiz format"
Comparison: Campaign name, quiz format, and language restriction all match the entity's own account.
Decision: primary-sourced

## Claim 33: explanatory memorandum indicated potential expansion beyond airports to other public spaces

Source: https://edri.org/our-work/biometric-surveillance-in-the-czech-republic-the-ministry-of-the-interior-is-trying-to-circumvent-the-artificial-intelligence-act/
Source tier: primary
Source content: "the explanatory memorandum shows that the ministry is certainly not opposed to extending the systems to other public spaces"
Comparison: Matches.
Decision: primary-sourced

## Claim 34: civil-society pressure had, by October 2024, limited the legislative text to airports

Source: https://edri.org/our-work/biometric-surveillance-in-the-czech-republic-the-ministry-of-the-interior-is-trying-to-circumvent-the-artificial-intelligence-act/
Source tier: primary
Source content: "It was only after comments from civil society that the law was limited to the use of airport systems"
Comparison: Matches; "by October 2024" is the article's publication date.
Decision: primary-sourced

## Claim 35: scalar:outcomes — the September 2024 proposal "remained unresolved at campaign close"

Source: no canonical source found
Source tier: none
Source content: No fetched source states the proposal's status as of the August 2025 campaign close; the October 2025 Biometric Update article does not mention its resolution. (A post-close expats.cz headline suggests later legislative movement, outside this claim's window and not fetched.)
Comparison: An absence-based status claim no fetched source affirms or contradicts.
Decision: uncorroborated

## Claim 36: IS DPO continued operating as a second active biometric tool at campaign close (scalar:outcomes + body)

Source: https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
Source tier: mainstream
Source content: "This separate police tool compares images of unidentified individuals against a reference database of roughly 20 million photographs" (present tense, Oct 2025)
Comparison: Continued operation as of Oct 2025 supported by Biometric Update alone in fetched content.
Decision: single-source

## Claim 37: "IuRe's warnings that the IS DPO could be repurposed for surveillance of demonstrators or journalists, against police claims that it served only the identification of deceased persons"

Source: https://www.biometricupdate.com/202510/czechia-turns-off-prague-airport-facial-recognition-system-amid-legal-violations
Source tier: mainstream
Source content: "While police claim it aids in identifying deceased persons, critics warn it could be repurposed to track demonstrators or other civilians, raising serious privacy concerns."
Comparison: Deceased-persons police claim and demonstrator-surveillance warning confirmed, but the source says "demonstrators or other civilians" (not "journalists") and attributes the warning to "critics" (not IuRe specifically). Partial/paraphrastic — no single-token contradiction, so not a correction.
Decision: uncorroborated

## Edge check: body cross-references

camp-tasz-hungary-biometric-surveillance-protests-2025 and
camp-edri-reclaim-your-face-eu-citizens-initiative-2020-2022 both exist in
`product/entities/campaigns/` and their names match the body's usage (TASZ-led
Hungarian coalition 2025; EDRi-coordinated Reclaim Your Face ECI 2020–2022).
Counted within Claim 1's edge surface; no separate decision needed — both resolve.
