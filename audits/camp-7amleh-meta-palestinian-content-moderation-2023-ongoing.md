---
entity_id: camp-7amleh-meta-palestinian-content-moderation-2023-ongoing
entity_hash: 485c99417906e2cea6459f77ae77cb3729045537
audit_date: 2026-07-04
pass: 4
status: corrections-pending
claims_total: 30
claims_corroborated: 24
claims_primary_sourced: 1
claims_single_source: 1
claims_uncorroborated: 2
open_corrections: 2
sources_consulted:
  - https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
  - https://www.eff.org/deeplinks/2023/12/digital-rights-groups-urge-meta-stop-silencing-palestine
  - https://stopsilencingpalestine.com
  - https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and
  - https://ifex.org/meta-systemic-censorship-of-palestine-content/
---

Pass 4 note: body delta from pass-3 audited blob `80a5707` to current `485c994` is two hunks — (1) the frontmatter `events:` list gained the edge `event-7amleh-meta-bsr-human-rights-investigation-2022-09`, and (2) the opening paragraph's plain-text mentions of Amnesty International, Article 19, and the Electronic Frontier Foundation were promoted to entity cross-reference links. Campaign is a connective type, so these edges are claim surface: new Claims 25–28 verify them. While verifying the event edge against 7amleh's 27 September 2022 BSR statement (fetched this pass), the statement's signatory list was found to contradict the body's and a `sources[].note` scalar's attribution of Article 19 as a co-signer — new Claims 29–30, both `correction`. Claims 1–24 carry forward from pass 3 with the same comparisons (body text unchanged for all of them); Claims 2 and 22 remain `uncorroborated` on the standing pass-2 reasoning.

## Claim 1: 7amleh is "the Arab Center for the Advancement of Social Media"

Source: https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and
Source tier: mainstream
Source content: HRW report names "7amleh, the Arab Center for the Advancement of Social Media." 7amleh's own Hashtag Palestine 2023 release reads "7amleh - The Arab Center for the Advancement of Social Media, issued its 9th annual report." (Pass-2 evidence; body unchanged. Pass-4 HRW re-fetch also quotes "7amleh, the Arab Center for the Advancement of Social Media" in the Summary section.)
Comparison: Body's formal name matches both cited sources verbatim.
Decision: corroborated

## Claim 2: 7amleh is "Haifa-headquartered"

Source: https://en.wikipedia.org/wiki/7amleh; https://7amleh.org/about; https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and
Source tier: none
Source content: Wikipedia article (pass-2 fetch): "no specific city or headquarters location is explicitly stated in the main text or infobox. The only geographic information provided is coordinates: 32°49′08″N 34°59′47″E." 7amleh's own About page (pass-2 fetch): "no explicit mention of 7amleh's headquarters location or city" — describes mission, programs, and funding sources but does not name a city. HRW "Meta's Broken Promises" (pass-2 fetch): "no specific mention of 7amleh's headquarters or base city" in the report text.
Comparison: The geographic coordinates 32°49′08″N 34°59′47″E correspond to a location in/near the Haifa metropolitan area, which would be consistent with the body's claim, but no canonical source consulted in passes 1 or 2 explicitly named Haifa (or any city) as 7amleh's headquarters. Per the source rule's rigor default for any claim not explicitly listed as Wikipedia-alone-sufficient, and given Wikipedia carries only coordinates rather than a textual city statement, the claim cannot be cleanly verified to a single named city. Body unchanged from pass 2; comparison stands.
Decision: uncorroborated

## Claim 3: Meta Oversight Board issued its expedited decision in the Al-Shifa Hospital case on 19 December 2023

Source: https://www.oversightboard.com/decision/ig-wuc3649n/
Source tier: primary
Source content: "Decision Type: Expedited / Decision Date: December 19, 2023" with the page titled "Al-Shifa Hospital | Oversight Board." (Pass-2 evidence corroborated by pass-3 re-fetch: "The only numerical reference presented is the decision date: 'December 19, 2023.'")
Comparison: Date, expedited type, and case identity all match the source.
Decision: corroborated

## Claim 4: The Al-Shifa Hospital case is "Case IG-WUC3649N"

Source: https://www.oversightboard.com/decision/ig-wuc3649n/
Source tier: primary
Source content (pass-3 fetch): "The URL slug is 'ig-wuc3649n,' which appears to be the case identifier used in the system." Platform metadata on the page: "Platform: Instagram." "The case identifier is embedded in the URL (oversightboard.com/decision/ig-wuc3649n/) but is never explicitly quoted or presented as a formal case number within the body of the decision document. The page does not use the '2023-007-FB-MR' format for this particular case."
Comparison: Body's "Case IG-WUC3649N" matches the canonical URL-slug identifier uppercased, and the "IG" platform prefix matches the page's "Platform: Instagram" metadata. The Oversight Board uses the URL slug as the case's canonical permalink identifier; while the page does not present the identifier in a separate "Case Number:" field, the URL-slug identifier is the form by which the Board addresses and links to this specific case. Pass-3 re-fetch resolved both pass-2 discrepancy findings; body unchanged since.
Decision: corroborated

## Claim 5: The decision overturned Meta's automated removal of an Instagram post about the Al-Shifa Hospital strike

Source: https://www.oversightboard.com/decision/ig-wuc3649n/
Source tier: primary
Source content: The Board overturned Meta's removal of "an Instagram video showing the aftermath of a strike on or near Al-Shifa Hospital in Gaza City, depicting injured and lifeless people including children." (Pass-2 evidence corroborated by pass-3 re-fetch confirming "Platform: Instagram.")
Comparison: Body describes "a Palestinian-civilian-casualty Instagram post about the strike on or near Al-Shifa Hospital in Gaza" — semantic match within paraphrase tolerance.
Decision: corroborated

## Claim 6: Both the initial removal and rejection of the user's appeal were taken automatically by classifier without human review

Source: https://www.oversightboard.com/decision/ig-wuc3649n/
Source tier: primary
Source content: "Both the initial decision to remove this content as well as the rejection of the user's appeal were taken automatically based on a classifier score, without any human review." (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 7: The Board identified Meta's lowering of its Violent and Graphic Content removal threshold during crisis response as a contributing cause

Source: https://www.oversightboard.com/decision/ig-wuc3649n/
Source tier: primary
Source content: The Board noted Meta "used its automated tools more aggressively to remove content" and that the Violent and Graphic Content classifier threshold was "significantly lowered" following October 7. (Pass-2 evidence; body unchanged.)
Comparison: Body's claim of "lowered Violent and Graphic Content removal threshold during crisis response" matches.
Decision: corroborated

## Claim 8: The Board expressed concern about unintentional bias against Palestinian and Arabic-speaking users

Source: https://www.oversightboard.com/decision/ig-wuc3649n/
Source tier: primary
Source content: "various instances of unintentional bias where Meta policy and practice...does lead to different human-rights impacts on Palestinian and Arabic speaking users." (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 9: HRW released "Meta's Broken Promises: Systemic Censorship of Palestine Content on Instagram and Facebook" on 21 December 2023

Source: https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and
Source tier: mainstream
Source content: Report dated "December 21, 2023" with the title "Meta's Broken Promises: Systemic Censorship of Palestine Content on Instagram and Facebook" (per URL slug and page header). (Pass-2 evidence; body unchanged. Note: the IFEX republication fetched pass 4 dates HRW's accompanying statement 20 December 2023; the report page itself carries 21 December 2023, which is the date the body claims and the URL slug encodes.)
Comparison: Direct match.
Decision: corroborated

## Claim 10: HRW verified 1,050 cases of pro-Palestine content-moderation actions reviewed between October-November 2023

Source: https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and
Source tier: mainstream
Source content: "Between October and November 2023, Human Rights Watch documented over 1,050 takedowns and other suppression of content." (Pass-2 evidence; body unchanged.)
Comparison: Body's "1,050 cases ... reviewed between October and November 2023" matches.
Decision: corroborated

## Claim 11: HRW identified six recurring censorship patterns each appearing at least 100 times

Source: https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and
Source tier: mainstream
Source content: "Human Rights Watch identified six key patterns of undue censorship, each recurring at least 100 times." (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 12: HRW named 7amleh, Access Now, and Amnesty International as civil-society partners

Source: https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and
Source tier: mainstream
Source content (re-fetched pass 4): Acknowledgments: "Human Rights Watch also benefited greatly from expert input from and collaboration with 7amleh, Access Now, and Amnesty International." Methodology: "The research included consultations with several human rights and digital rights organizations including 7amleh, Access Now, and Amnesty International."
Comparison: Direct match, re-confirmed by pass-4 fetch.
Decision: corroborated

## Claim 13: HRW's six headline recommendations to Meta (DOI policy overhaul; transparency on government takedown requests; audit of newsworthiness allowance; disclosure of automation and algorithm error rates; functional appeal mechanisms; human-rights due-diligence on temporary algorithmic changes)

Source: https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and
Source tier: mainstream
Source content: HRW's recommendations include: (1) overhaul the Dangerous Organizations and Individuals policy; (2) improve transparency around government content removal requests; (3) audit newsworthiness allowance application for equitable enforcement; (4) increase transparency on automation and machine learning for Palestine content moderation; (5) provide users adequate notification and functional appeals; (6) conduct human rights due diligence with civil society input on implementation. (Pass-2 evidence; body unchanged.)
Comparison: Body's six recommendations match the source's six within paraphrase tolerance. Body's framing of #6 as "due-diligence on temporary algorithmic changes" is narrower than source's "due diligence ... on implementation of prior commitments" but covers the same recommendation cluster (HRW lists the temporary-algorithmic-change diligence among its recommendations).
Decision: corroborated

## Claim 14: Access Now released "It's not a glitch: how Meta systematically censors Palestinian voices" on 19 February 2024, authored by Marwa Fatafta as MENA Policy and Advocacy Director

Source: https://www.accessnow.org/publication/how-meta-censors-palestinian-voices/; https://www.accessnow.org/profile/marwa-fatafta/
Source tier: primary
Source content: Publication date 19 February 2024; report title matches verbatim; Access Now's staff profile gives Fatafta's title as "MENA Policy and Advocacy Director." (Pass-2 evidence; body unchanged.)
Comparison: All three claims match the cited sources.
Decision: corroborated

## Claim 15: Meta lowered algorithmic detection thresholds from 80% to 40% for Middle East content and to 25% for Palestine during the post-October 2023 crisis-response window

Source: https://www.accessnow.org/publication/how-meta-censors-palestinian-voices/
Source tier: primary
Source content: "[Meta] lowered the threshold for its algorithms to detect and hide comments violating Community Guidelines from 80% to 40% for content from the Middle East and to just 25% for content from Palestine." (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 16: 77% error rate for Arabic-language terrorist-content classifiers from leaked 2020 internal documents

Source: https://www.accessnow.org/publication/how-meta-censors-palestinian-voices/
Source tier: primary
Source content: "Meta's algorithms for detecting terrorist content erroneously deleted non-violent Arabic content 77% of the time" — citing leaked 2020 internal documents. (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 17: 7amleh's 7or observatory documented approximately 1,043 instances of censorship between 7 October 2023 and 9 February 2024

Source: https://www.accessnow.org/publication/how-meta-censors-palestinian-voices/
Source tier: primary
Source content: 7or "has documented around 1,043 instances of censorship between October 7, 2023 and February 9, 2023" — note: source contains an apparent typo "2023" for the closing date that should read 2024 given the report's February 2024 publication. (Pass-2 evidence; body unchanged.)
Comparison: Numerical figure (1,043), start date (7 October 2023), and intended end date (9 February 2024) match. The source's "February 9, 2023" is a date typo; the body uses the corrected reading consistent with the report's own February 2024 publication.
Decision: corroborated

## Claim 18: 9th annual Hashtag Palestine report released 17 January 2024, documenting 4,400 digital-rights violations in 2023 with 69% after 7 October 2023

Source: https://7amleh.org/post/1299
Source tier: primary
Source content: Page is dated 17 January 2024; describes 7amleh's "9th annual report, 'Hashtag Palestine 2023'"; states "documented 4,400 violations" and "69% of these violations were documented after October 7, 2023." (Pass-2 evidence; body unchanged.)
Comparison: Direct match on all four sub-claims.
Decision: corroborated

## Claim 19: 16 September 2024 "Palestinian Digital Rights, Genocide, and Big Tech Accountability" report documented over 5,100 digital-censorship cases across Meta and X between 7 October 2023 and September 2024

Source: https://7amleh.org/post/report-on-palestinian-digital-rights-in-the-context-of-genocide-and-big-tech-accountability-one-year-after-the-war-on-gaza-en
Source tier: primary
Source content: Release date 16 September 2024; "7amleh, through its platform 7or...documented over 5100 cases of digital censorship" on Meta and X between October 7, 2023 and September 2024. (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 20: $7.1 million Israeli Ministry of Foreign Affairs YouTube ad budget in two weeks post-October 2023 targeting France, Germany, and UK audiences

Source: https://7amleh.org/post/report-on-palestinian-digital-rights-in-the-context-of-genocide-and-big-tech-accountability-one-year-after-the-war-on-gaza-en
Source tier: primary
Source content: The Israeli Ministry of Foreign Affairs "promoted advertisements about the ongoing war on Gaza on YouTube" targeting France, Germany, and the UK "with a budget of $7.1 million in two weeks after 7 October 2023." (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 21: 18 December 2024 "Erased and Suppressed: Palestinian Testimonies of Meta's Censorship" compiled 20 first-person testimonies from Palestinian influencers, journalists, and media outlets

Source: https://7amleh.org/post/erased-and-suppressed-palestinian-testimonies-of-meta-s-censorship-en
Source tier: primary
Source content: Release date 18 December 2024; title matches verbatim; "20 documented testimonies detailing Palestinian users' experiences." (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 22: Hashtag Palestine 2024 report "The War on Gaza, Digital Rights Violations, and Weaponization of AI" released 27 January 2025, citing ~75% destruction of Gaza's internet infrastructure and Israeli AI-targeting systems Lavender and Habsora

Source: https://7amleh.org/post/hashtag-palestine-2024-en
Source tier: primary
Source content (pass-2 fetch): The source contains two different release dates. Body text: "29 January 2025, 7amleh - The Arab Center for the Advancement of Social Media released its annual report, 'Hashtag Palestine 2024,'" — explicit textual statement. Publication-date metadata at the top of the article: "2025/01/27." Title, infrastructure-destruction figure ("75% of this infrastructure was partially or completely destroyed"), and named systems "Lavender" and "Habsora" all match.
Comparison: Title, 75% destruction figure, and Lavender/Habsora — verified. The release-date sub-claim (27 January 2025) matches the page's publication-metadata timestamp but does not match the article body's stated release-date sentence ("29 January 2025"). Per the source rule, when a single source effectively contradicts itself on a date and no other canonical source resolves the contradiction (this body claim is sourced only to 7amleh's own page), the outcome is uncorroborated. Body unchanged from pass 2; comparison stands.
Decision: uncorroborated

## Claim 23: 2 September 2025 "Meta's Role in Amplifying Harmful Content During Genocide" report documented 2,000+ pieces of harmful Hebrew content (Oct 2023-May 2025), 2.5 million harmful Hebrew posts in 2024 alone, and characterized Meta's enforcement as "systematic racial discrimination in content governance"

Source: https://7amleh.org/post/meta-s-role-during-genocide-en
Source tier: primary
Source content: Release date 2 September 2025; "over 2,000 pieces of harmful content manually detected on Meta's platforms between October 2023 and May 2025"; "more than 2.5 million harmful Hebrew posts in 2024 alone"; quoted as exposing "systematic racial discrimination in content governance." (Pass-2 evidence; body unchanged.)
Comparison: All four sub-claims match the source.
Decision: corroborated

## Claim 24: 7amleh's Violence Indicator has detected more than 15 million inciting Hebrew-language posts against Palestinians since October 2023

Source: https://7amleh.org/post/erased-and-suppressed-palestinian-testimonies-of-meta-s-censorship-en
Source tier: primary
Source content: "more than 15 million inciting posts in Hebrew against Palestinians were documented across social media platforms since October 2023, as recorded by 7amleh's AI-powered language model, the Violence Indicator." (Pass-2 evidence; body unchanged.)
Comparison: Direct match.
Decision: corroborated

## Claim 25: scalar:events[0] — the campaign carries the edge `event-7amleh-meta-bsr-human-rights-investigation-2022-09` (new in this blob)

Source: product/entities/events/event-7amleh-meta-bsr-human-rights-investigation-2022-09.md (edge-target identity); https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: Edge target exists; its frontmatter reads name "BSR Human Rights Due Diligence of Meta's Impacts in Israel and Palestine — publication and civil society response (September 2022)", type event. 7amleh's 27 September 2022 statement (fetched this pass): a joint statement "responding to Business for Social Responsibility's (BSR) Human Rights Due Diligence Report on Meta's content moderation in the Israel/Palestine context," dated September 27, 2022, in which the signatories "appreciate and value BSR's efforts," note "BSR's findings provide further evidence of the over-enforcement of Arabic content compared to Hebrew content," and call on Meta to "Implement BSR's recommendations."
Comparison: The edge points to the correct entity — the event is exactly the BSR HRDD publication and civil-society response the campaign's Origins section describes, and 7amleh's own statement (the campaign's cited source) documents the campaign's structured engagement with that event. One primary-tier source fetched this pass confirms the connection.
Decision: primary-sourced

## Claim 26: body edge — "Amnesty International" links to `org-amnesty-international` as a coalition partner of the campaign

Source: product/entities/organizations/org-amnesty-international.md (edge-target identity); https://www.hrw.org/report/2023/12/21/metas-broken-promises/systemic-censorship-palestine-content-instagram-and; https://stopsilencingpalestine.com
Source tier: primary
Source content: Edge target exists; frontmatter name "Amnesty International", type organization. HRW report (re-fetched this pass), Acknowledgments: "Human Rights Watch also benefited greatly from expert input from and collaboration with 7amleh, Access Now, and Amnesty International." Coalition campaign site stopsilencingpalestine.com (fetched this pass) lists Amnesty International among coalition members (footer logo listing).
Comparison: Edge points to the correct entity, and Amnesty's participation in the campaign's international civil-society register is confirmed by two independent canonical sources fetched this pass (HRW's named-collaboration acknowledgment on the campaign's anchor report; the coalition's own campaign page).
Decision: corroborated

## Claim 27: body edge — "Article 19" links to `org-article-19` as a coalition partner of the campaign

Source: product/entities/organizations/org-article-19.md (edge-target identity); https://stopsilencingpalestine.com
Source tier: primary
Source content: Edge target exists; frontmatter name "ARTICLE 19", type organization. Coalition campaign site stopsilencingpalestine.com (fetched this pass): "Article 19: Listed in the footer logos section" among coalition members. No second canonical source found this pass: Article 19 is definitively absent from the 27 September 2022 joint-statement signatory list (see Claim 29), is not named in HRW's acknowledgments, and article19.org 403s on direct fetch (known harness limit), so its own statement record could not be checked.
Comparison: The edge itself points to the correct entity. Article 19's membership in the campaign coalition rests on a single canonical source (the coalition's own campaign page), and that confirmation is logo-based rather than quotable text. Supported on lighter sourcing; not a finding of error.
Decision: single-source

## Claim 28: body edge — "Electronic Frontier Foundation" links to `org-electronic-frontier-foundation` as a coalition partner of the campaign

Source: product/entities/organizations/org-electronic-frontier-foundation.md (edge-target identity); https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel; https://www.eff.org/deeplinks/2023/12/digital-rights-groups-urge-meta-stop-silencing-palestine
Source tier: primary
Source content: Edge target exists; frontmatter name "Electronic Frontier Foundation", type organization. 7amleh's 27 September 2022 joint statement (fetched this pass, targeted check): "Electronic Frontier Foundation: Yes, listed" among the 60+ signatory organizations. EFF's own 6 December 2023 post (fetched this pass): "EFF and 17 other digital and human rights organizations are issuing an updated set of demands" to Meta over suppression of Palestinian voices.
Comparison: Edge points to the correct entity; EFF's participation in the campaign's joint-statement register is confirmed by two independent canonical sources fetched this pass (the 2022 joint statement it signed; EFF's own December 2023 coalition demands).
Decision: corroborated

## Claim 29: 7amleh's 27 September 2022 statement on the BSR review was "jointly signed with Human Rights Watch, Article 19, and regional partners"

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content (targeted re-fetch this pass): "(1) Article 19 / ARTICLE 19: Not listed. This organization name does not appear anywhere on the page. ... (3) Human Rights Watch: Yes, listed. ... (4) Electronic Frontier Foundation: Yes, listed." The full signatory list (first fetch this pass, 70+ organizations) includes Human Rights Watch, Access Now, Electronic Frontier Foundation, SMEX, Al-Haq, APC, and others — but not Article 19 and not Amnesty International.
Comparison: The body's "Human Rights Watch" and "regional partners" tokens match the source, but the specific token "Article 19" contradicts the statement's own signatory list — Article 19 does not appear anywhere on the page, confirmed by a targeted re-fetch. Single mechanical fix: remove "Article 19" from the signatory phrase in the Origins section (or replace it with an actual major co-signer such as Access Now or the Electronic Frontier Foundation — a choice requiring prose judgment, so an Editor `[editor-flag]` to the Researcher may be the right route).
Decision: correction

## Claim 30: scalar:sources[10].note (url https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel) — "the joint civil-society response also signed by Human Rights Watch, Article 19, and other regional partners"

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content (targeted re-fetch this pass): "Article 19 / ARTICLE 19: Not listed. This organization name does not appear anywhere on the page." Human Rights Watch and Electronic Frontier Foundation are listed among the signatories.
Comparison: Same contradiction as Claim 29, located in the frontmatter scalar sources[10].note (0-indexed; the entry whose url is the 7amleh 2022 statement). The scalar's "Human Rights Watch" token matches; the "Article 19" token contradicts the statement's own signatory list. Fix location: that sources[].note scalar — remove "Article 19" or replace with an actual co-signer.
Decision: correction
