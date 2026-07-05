---
entity_id: camp-openmedia-bill-c27-ai-governance-canada-2022-ongoing
entity_hash: 0617874b09bc5e4ca89ab01f566732f67d075343
audit_date: 2026-07-05
pass: 1
status: corrections-pending
claims_total: 27
claims_corroborated: 8
claims_primary_sourced: 14
claims_single_source: 2
claims_uncorroborated: 1
open_corrections: 2
sources_consulted:
  - https://openmedia.org/press/item/new-privacy-legislation-repeats-past-mistakes
  - https://openmedia.org/article/item/your-voice-delivered-Bill-C27
  - https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
  - https://www.parl.ca/legisinfo/en/bill/44-1/c-27
  - https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document
  - https://montrealethics.ai/the-death-of-canadas-artificial-intelligence-and-data-act-what-happened-and-whats-next-for-ai-regulation-in-canada/
  - https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
  - https://sencanada.ca/en/content/sen/committee/451/trcm/28ev-57613-e
  - https://gowlingwlg.com/en/insights-resources/articles/2024/bill-c27-timeline-of-developments
  - https://openmedia.org/look-back-our-stop-meter-campaign
---

Connective type (campaign): claim surface is edges (`lead_orgs`, `events`) and hard specifics (dates, counts, named signatories, outcomes). Interpretive body prose about significance/arc received no decision. Note: `https://www.dataguidance.com/news/canada-bill-c-27-dies-after-parliament-prorogued` (cited in entity) did not render on fetch (JS shell); the prorogation claim was verified against LEGISinfo and independent coverage instead.

## Claim 1: edge — `lead_orgs: org-openmedia`

Source: https://openmedia.org/press/item/new-privacy-legislation-repeats-past-mistakes ; https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: "Matt Hatfield, OpenMedia Campaigns Director" (launch release); INDU minutes list witness "OpenMedia, represented by Matthew Hatfield (Executive Director)"
Comparison: Entity `org-openmedia` exists in corpus; every campaign artifact (launch release, INDU submission, coalition letter, testimony) is OpenMedia's — correct entity, correct lead.
Decision: corroborated

## Claim 2: edge — `events: event-openmedia-bill-c27-house-industry-committee-testimony-2023-11`

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: "Thursday, November 2, 2023, 3:31 p.m. to 5:31 p.m. ... Bill C-27 ... OpenMedia, represented by Matthew Hatfield"
Comparison: Edge target exists in corpus and records the same INDU meeting-94 testimony (2 November 2023) the campaign body describes — correct entity.
Decision: primary-sourced

## Claim 3: `start_date: 2022-06-16` / "campaign ran from the bill's introduction on 16 June 2022"

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27 ; https://openmedia.org/press/item/new-privacy-legislation-repeats-past-mistakes
Source tier: primary
Source content: LEGISinfo: "First Reading: Thursday, June 16, 2022"; OpenMedia release dated June 16, 2022
Comparison: Bill introduced 16 June 2022 and OpenMedia's launch release published the same day — start date matches two independent primary sources.
Decision: corroborated

## Claim 4: `end_date: 2025-01` / campaign ended at prorogation

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27 ; https://gowlingwlg.com/en/insights-resources/articles/2025/2025-begins-with-prime-minister-trudeau-resignation
Source tier: primary
Source content: LEGISinfo: "44th Parliament, 1st session ran from November 22, 2021 to January 6, 2025"; Gowling: prorogation announced January 6, 2025
Comparison: Session ended 6 January 2025; end_date 2025-01 matches.
Decision: corroborated

## Claim 5: "the first large-scale Canadian grassroots mobilisation on federal AI governance"

Source: no canonical source found
Source tier: none
Source content: (none — no fetched source asserts or refutes priority/firstness)
Comparison: A contested "first" superlative; no canonical source makes the priority claim, and per the source rule "who was first" cannot rest on Wikipedia alone. Not a finding of error — the scale figures themselves are verified in Claims 10–11.
Decision: uncorroborated

## Claim 6: Bill C-27 bundled CPPA (replacing PIPEDA), AIDA, and the Personal Information and Data Protection Tribunal Act

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27 ; https://openmedia.org/article/item/your-voice-delivered-Bill-C27
Source tier: primary
Source content: "An Act to enact the Consumer Privacy Protection Act, the Personal Information and Data Protection Tribunal Act and the Artificial Intelligence and Data Act"; OpenMedia: "update Canada's private sector privacy laws, establish a new tribunal, and create artificial intelligence regulations"
Comparison: Three-act structure matches the bill's full title; private-sector privacy-law replacement matches.
Decision: corroborated

## Claim 7: AIDA adopted a risk-based approach requiring operators of "high-impact" systems to identify, assess, and mitigate risks of harm and bias

Source: https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document
Source tier: primary
Source content: "appropriate measures be put in place to identify, assess, and mitigate risks of harm or biased output prior to a high-impact system being made available for use"
Comparison: Body phrasing matches the companion document nearly verbatim.
Decision: primary-sourced

## Claim 8: AIDA vested primary oversight in the ISED Minister and proposed an AI and Data Commissioner under that department

Source: https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document ; https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
Source tier: primary
Source content: "The Minister of Innovation, Science, and Industry holds primary authority for administering and enforcing AIDA"; Commissioner "supports the Minister"; coalition letter demands removal of "AI regulation from ISED's exclusive jurisdiction"
Comparison: Both the government's own companion document and the coalition letter confirm ISED-centred oversight and the Commissioner's placement.
Decision: corroborated

## Claim 9: Matt Hatfield (Campaigns Director) called the bill "a tremendous disappointment" and said "The government has had nearly two years to learn from the mistakes of their 2020 bill — yet today's privacy bill repeats most of the same mistakes" (16 June 2022)

Source: https://openmedia.org/press/item/new-privacy-legislation-repeats-past-mistakes
Source tier: primary
Source content: "Frankly, Bill C-27 is a tremendous disappointment"; "The government has had nearly two years to learn from the mistakes of their 2020 bill — yet today's privacy bill repeats most of the same mistakes"; "Matt Hatfield, OpenMedia Campaigns Director"
Comparison: Quotes, attribution, title, and date match the release. Body drops "Frankly," and appends "with only minor improvements at the edges" — the latter phrase is in the release's continuation as characterised; substance matches.
Decision: primary-sourced

## Claim 10: 29,500+ petition signatures and 17,800+ messages to ministers accumulated by launch

Source: https://openmedia.org/press/item/new-privacy-legislation-repeats-past-mistakes
Source tier: primary
Source content: "29,500+ signatures collected since November 2021 on privacy petitions; 17,800+ messages sent to Ministers requesting privacy protections"
Comparison: Both figures match exactly.
Decision: primary-sourced

## Claim 11: nearly 40,000 community members contributed input to the INDU submission by May 2023; article of 4 May 2023 by Bryan Short

Source: https://openmedia.org/article/item/your-voice-delivered-Bill-C27
Source tier: primary
Source content: "May 4th, 2023 | By Bryan Short ... Nearly 40,000 action takers from the OpenMedia community provided input"
Comparison: Figure, date, and author all match (also asserted in `sources[1].note`).
Decision: primary-sourced

## Claim 12: OpenMedia supplied a detailed written submission (PDF) to the INDU committee

Source: https://openmedia.org/article/item/your-voice-delivered-Bill-C27
Source tier: primary
Source content: "OpenMedia delivered a detailed submission to Parliament's INDU committee studying Bill C-27 ... The full submission was made available as a PDF document"
Comparison: Submission existence and PDF form confirmed; the cited PDF URL is OpenMedia's own asset.
Decision: primary-sourced

## Claim 13: coalition of 45 civil-society organisations, experts, and academics released an open letter (25 September 2023) demanding proper parliamentary treatment / AIDA separation

Source: https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
Source tier: primary
Source content: "Release Date: September 25, 2023 ... 45 civil society organizations, experts, and academics"
Comparison: Count and date match (also asserted in `sources[2].note` and the outcomes scalar's "45-organisation coalition open letter").
Decision: primary-sourced

## Claim 14: named signatories — Tim McSorley (ICLMG), Daniel Konikoff (CCLA), Yuka Sai (PIAC), Aislin Jackson (BCCLA), Prof. Emeritus Andrew Clement (University of Toronto)

Source: https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
Source tier: primary
Source content: "Tim McSorley, National Coordinator, International Civil Liberties Monitoring Group; Daniel Konikoff ... Canadian Civil Liberties Association; Yuka Sai, Staff Lawyer, Public Interest Advocacy Centre; Aislin Jackson, Policy Staff Counsel, British Columbia Civil Liberties Association; Andrew Clement, Professor Emeritus, University of Toronto"
Comparison: All five names, organisations, and Clement's Professor-Emeritus title match.
Decision: primary-sourced

## Claim 15: the letter's five recommendations as listed in the body (and in `goals`)

Source: https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
Source tier: primary
Source content: "(1) Recognize privacy as a fundamental human right (2) Remove AI regulation from ISED's exclusive jurisdiction due to conflicting mandates (3) Address poorly defined language creating loopholes (4) Expand stakeholder consultation beyond industry insiders (5) Apply AI regulation to both public and private sectors, including government security agencies"
Comparison: Body's five recommendations map one-to-one to the release's list; the `goals` scalar's five asks restate the same set plus the launch release's data-broker objection (Claim 10's source confirms that objection).
Decision: primary-sourced

## Claim 16: "the INDU committee scheduled to begin its clause-by-clause study of the bill on 26 September 2023"

Source: https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation ; https://gowlingwlg.com/en/insights-resources/articles/2024/bill-c27-timeline-of-developments
Source tier: primary
Source content: OpenMedia release: "Committee Study Date: September 26, 2023 (House of Commons Industry and Technology Committee)"; Gowling timeline: INDU "began its clause-by-clause consideration of C-27 on April 8, 2024"
Comparison: 26 September 2023 was the start of INDU's *study* (witness hearings), not clause-by-clause consideration, which began 8 April 2024 — the body's own later sentence ("conducted witness hearings through late 2023 and into 2024 before a clause-by-clause review began") states this correctly. Single-token fix in body § "September 2023 coalition open letter and committee testimony": "clause-by-clause study" → "study".
Decision: correction

## Claim 17: OpenMedia testified before the INDU committee on 2 November 2023

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: "Thursday, November 2, 2023, 3:31 p.m. to 5:31 p.m. ... OpenMedia, represented by Matthew Hatfield (Executive Director)"
Comparison: Date and appearance confirmed by the committee's official minutes.
Decision: primary-sourced

## Claim 18: 10,000+ contacts to government on AI and facial recognition over two years

Source: https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
Source tier: primary
Source content: "10,000+ signatures/letters on AI and facial recognition (past two years)"
Comparison: Figure and two-year window match.
Decision: primary-sourced

## Claim 19: Bill C-27 passed second reading 24 April 2023 and was referred to INDU

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27
Source tier: primary
Source content: "Second Reading Passage: Monday, April 24, 2023; Committee Referral: Standing Committee on Industry and Technology, with referral occurring on April 24, 2023"
Comparison: Both date and committee match the parliamentary record.
Decision: primary-sourced

## Claim 20: INDU conducted witness hearings through late 2023 and into 2024 before a clause-by-clause review began; the bill never reached a floor vote

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27 ; https://gowlingwlg.com/en/insights-resources/articles/2024/bill-c27-timeline-of-developments
Source tier: primary
Source content: LEGISinfo: bill remained "at consideration in committee in the House of Commons" (never reached report stage or third reading); Gowling: clause-by-clause began April 8, 2024, paused May 29, 2024
Comparison: Sequence (hearings → 2024 clause-by-clause) and no-floor-vote both confirmed.
Decision: corroborated

## Claim 21: Parliament prorogued 6 January 2025 following Trudeau's resignation announcement, killing all Order Paper legislation including C-27 (body + `outcomes` scalar + `sources[6].note`)

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27 ; https://gowlingwlg.com/en/insights-resources/articles/2025/2025-begins-with-prime-minister-trudeau-resignation
Source tier: primary
Source content: "On Monday, January 6, 2025, Prime Minister Justin Trudeau announced that he would step down ... Governor General Mary Simon granted his request to prorogue Parliament"; "unfinished business 'dies' on the Order Paper"; LEGISinfo session end January 6, 2025
Comparison: Date, resignation link, and Order-Paper death confirmed by the parliamentary record plus independent coverage (Fasken, IAPP, CBC concur in search results). The cited DataGuidance page did not render on fetch; verification rests on these substitutes.
Decision: corroborated

## Claim 22: broader coalition — Canadian Labour Congress, Writers Guild of Canada, Directors Guild of Canada, Amnesty International, Assembly of First Nations — documented structural failings (vague scope, exclusionary consultation, insufficient protections for vulnerable groups)

Source: https://montrealethics.ai/the-death-of-canadas-artificial-intelligence-and-data-act-what-happened-and-whats-next-for-ai-regulation-in-canada/
Source tier: database
Source content: critical briefs from "Canadian Labour Congress ... Writers Guild of Canada and Directors Guild of Canada – joint submission ... Amnesty International ... Assembly of First Nations"; flaws: requirements "vaguely described and insufficient," development "behind closed doors with a selective group of industry representatives," failure to protect vulnerable groups
Comparison: All five organisations and all three structural criticisms match the cited analysis; not independently confirmed by a second canonical source this session (the underlying committee briefs exist on the INDU record but were not fetched).
Decision: single-source

## Claim 23: the successor Parliament did not reintroduce AIDA in its original form (body + `outcomes` scalar)

Source: https://montrealethics.ai/the-death-of-canadas-artificial-intelligence-and-data-act-what-happened-and-whats-next-for-ai-regulation-in-canada/
Source tier: database
Source content: "AIDA was not reintroduced. The bill died in parliamentary committee in 2024 and was not revived following Parliament's prorogation."
Comparison: Negative claim confirmed by the cited analysis; consistent with the 2026 Senate AI study proceeding without an AIDA successor bill (Claim 24's source), but only one source states it directly.
Decision: single-source

## Claim 24: OpenMedia's subsequent AI-governance work included 2026 campaigns on AI and democracy before the Senate Standing Committee on Transport and Communications

Source: https://sencanada.ca/en/content/sen/committee/451/trcm/28ev-57613-e
Source tier: primary
Source content: "Standing Senate Committee on Transport and Communications ... Wednesday, April 15, 2026 ... Matthew Hatfield, Executive Director of OpenMedia ... focus on AI's impact on democracy"
Comparison: Committee name, 2026 timing, OpenMedia's appearance, and AI-and-democracy topic all confirmed by the Senate's own transcript record.
Decision: primary-sourced

## Claim 25: prior OpenMedia digital-rights campaigns "had won concrete CRTC reversals"

Source: https://openmedia.org/look-back-our-stop-meter-campaign
Source tier: primary
Source content: "The CRTC released a revised decision in November, reversing their earlier ruling" (usage-based billing, Stop the Meter campaign)
Comparison: At least one concrete CRTC reversal (2011 usage-based-billing revision) is documented in OpenMedia's own campaign record; self-account of its own win, no independent confirmation fetched this session.
Decision: primary-sourced

## Claim 26: scalar `sources[5].note` (parl.ca) — "referral to INDU committee (September 2023 onward)"

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27
Source tier: primary
Source content: "Committee Referral: Standing Committee on Industry and Technology, with referral occurring on April 24, 2023"
Comparison: The note dates the INDU referral to "September 2023 onward," but the source it describes records the referral on 24 April 2023 (26 September 2023 is when the committee *began its study*). Fix location: frontmatter scalar `sources[].note` for the parl.ca URL — replace "(September 2023 onward)" with "(24 April 2023)".
Decision: correction

## Claim 27: `outcomes` scalar — OpenMedia's five substantive asks "were not addressed in C-27 as tabled"

Source: https://openmedia.org/press/item/new-privacy-legislation-repeats-past-mistakes ; https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document
Source tier: primary
Source content: launch release: bill includes "neither data broker restrictions nor acknowledgment of privacy as a fundamental human right"; companion document: AIDA within C-27 (not separated), Minister of ISED "holds primary authority"; coalition letter demands public-sector extension "including government security agencies"
Comparison: The "as tabled" qualifier holds: the introduced bill lacked fundamental-right framing and data-broker limits (launch release), kept AIDA bundled under ISED authority (bill title + companion doc), and the letter's public-sector demand presupposes its absence. Composite negative claim supported across independent primary sources.
Decision: corroborated
