---
entity_id: event-openmedia-bill-c27-house-industry-committee-testimony-2023-11
entity_hash: 8d290cc54665f41d9fa138c55dcb10749df72746
audit_date: 2026-08-31
pass: 1
status: supported
claims_total: 32
claims_corroborated: 9
claims_primary_sourced: 17
claims_single_source: 1
claims_uncorroborated: 5
open_corrections: 0
sources_consulted:
  - https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
  - https://www.ourcommons.ca/documentviewer/en/44-1/INDU/meeting-94/evidence
  - https://openparliament.ca/committees/industry/44-1/94/brad-vis-9/
  - https://openparliament.ca/committees/industry/44-1/94/
  - https://openmedia.org/article/item/canada-must-regulate-ai-right-not-first
  - https://iclmg.ca/c-27-indu/
  - https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
  - https://www.parl.ca/legisinfo/en/bill/44-1/c-27
  - https://openmedia.org/article/item/your-voice-delivered-Bill-C27
  - https://openmedia.org/article/item/stakeholders-present-key-artificial-intelligence-amendments-to-bill-c-27
  - https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-86/evidence
  - https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document
---

Connective type (Event): claim surface is edges + hard specifics per `mission/MISSION.md § Auditor § Type-shape awareness`. Narrative significance prose skipped.

## Claim 1: edge `campaign: camp-openmedia-bill-c27-ai-governance-canada-2022-ongoing`

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes + https://openmedia.org/article/item/canada-must-regulate-ai-right-not-first
Source tier: primary
Source content: Minutes list "OpenMedia: Matthew Hatfield" among witnesses on Bill C-27; OpenMedia's own article (8 Nov 2023) presents the testimony as part of its C-27 campaign work.
Comparison: Edge target exists at `product/entities/campaigns/` and is the correct campaign — the hearing is OpenMedia's parliamentary appearance within its Bill C-27 campaign.
Decision: corroborated

## Claim 2: edge `participating_orgs: [org-openmedia]`

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: Witness list includes "OpenMedia: Matthew Hatfield"; also confirmed by openparliament.ca digest and OpenMedia's own testimony article.
Comparison: Edge target exists at `product/entities/organizations/org-openmedia.md`; OpenMedia's participation is on the official record.
Decision: corroborated

## Claim 3: `date: 2023-11-02`

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: "Thursday, November 2, 2023, from 3:31 p.m. to 5:31 p.m."
Comparison: Frontmatter date matches official minutes; also confirmed by ICLMG's own account ("Date of Testimony: November 2, 2023").
Decision: corroborated

## Claim 4: `location: Ottawa — House of Commons Standing Committee on Industry and Technology (INDU)`

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: Official House of Commons INDU minutes for meeting 94; the committee sits in the House of Commons, Ottawa.
Comparison: Frontmatter scalar matches the venue on the official record.
Decision: primary-sourced

## Claim 5: hearing ran 3:31 to 5:31 p.m.

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: "Thursday, November 2, 2023, from 3:31 p.m. to 5:31 p.m."
Comparison: Body times match minutes exactly.
Decision: primary-sourced

## Claim 6: meeting 94 of the 44th Parliament's first session

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: Document is the official minutes at path 44-1/INDU/meeting-94.
Comparison: Body claim matches the parliamentary record's own numbering.
Decision: primary-sourced

## Claim 7: scalar:sources[0].note — minutes as source for date, time, six witness organisations/names, and follow-up meeting scheduled for 7 November 2023

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: Witness list: "Canadian Civil Liberties Association: Daniel Konikoff; International Civil Liberties Monitoring Group: Tim McSorley; OpenMedia: Matthew Hatfield; Privacy and Access Council of Canada: Sharon Polsky; Public Interest Advocacy Centre: John Lawford and Yuka Sai; Toronto Metropolitan University: Sam Andrey"; "the committee would hold the meeting requested by members pursuant to Standing Order 106(4) on Tuesday, November 7, 2023."
Comparison: Every element of the note (scalar path sources[0].note) — date, times, all six organisations and witness names, and the 7 November follow-up — matches the minutes.
Decision: primary-sourced

## Claim 8: scalar:sources[1].note — openparliament digest confirming Hatfield's children's-protections-for-all position, the undefined-"sensitive information" concern, and Polsky's "reprehensible" characterisation

Source: https://openparliament.ca/committees/industry/44-1/94/brad-vis-9/
Source tier: primary
Source content: Hatfield: "I do think we need to ask ourselves whether many of the protections enjoyed by children shouldn't be enjoyed by everyone in Canada." Polsky: "Of course it's ethically wrong. It's reprehensible. It doesn't give parents, guardians or the kids any say." "Both witnesses flagged that Bill C-27 lacks a definition for 'sensitive information' despite applying it to children's data."
Comparison: All three elements of the note (scalar path sources[1].note) confirmed; openparliament mirrors the official committee evidence, so the underlying record is the parliamentary transcript.
Decision: primary-sourced

## Claim 9: scalar:sources[2].note — 8 Nov 2023 article as source for AIDA critique framing including "rating AIDA 'between a three and an undeciphered symbol'"

Source: https://openmedia.org/article/item/canada-must-regulate-ai-right-not-first
Source tier: none
Source content: Targeted probe of the cited article: "No, this phrase ['undeciphered symbol'] does not appear anywhere in the article. … the author does not provide a numerical rating or scaled assessment of AIDA." Official meeting-94 evidence transcript: "No witness provided a numeric scale rating of AIDA in this transcript." Web search for the phrase returns nothing.
Comparison: The note (scalar path sources[2].note) is accurate on the article's date (8 Nov 2023), "frankly undercooked", the "AI dumping ground" argument, and the three-part call — but the clause attributing the "between a three and an undeciphered symbol" rating to this article is not supported by the article, the official transcript, or search. Not a single-token replacement, so not a correction; the rating clause cannot be sourced.
Decision: uncorroborated

## Claim 10: scalar:sources[3].note — ICLMG account as source for McSorley's testimony on national security exemptions and AIDA's human-rights failure

Source: https://iclmg.ca/c-27-indu/
Source tier: primary
Source content: "Bill C-27 contains several national security exemptions that are unacceptable and dangerous for our rights"; the page states the proposed AI regulations "fail to address the human rights concerns around the technology overall"; testimony dated November 2, 2023.
Comparison: Note (scalar path sources[3].note) matches ICLMG's own account on all elements.
Decision: primary-sourced

## Claim 11: scalar:sources[4].note — 25 Sept 2023 press release as source for the 45-organisation letter, five demands, and Sai/Konikoff/McSorley as signatories who also testified

Source: https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
Source tier: primary
Source content: "45 leading civil society organisations, experts and academics"; demands quoted: "Recognizing privacy as a fundamental human right"; "Removing AI regulation from ISED's sole jurisdiction"; "Addressing poorly defined language in AIDA that create loopholes"; enhanced stakeholder consultation; "Expanding AI regulation to apply to both the public and private sector". Named: Tim McSorley (ICLMG), Daniel Konikoff (CCLA), Yuka Sai (PIAC).
Comparison: Note (scalar path sources[4].note) matches the release: date, 45 signatories, all five demands, and the three named individuals, each of whom appears in the meeting-94 witness list.
Decision: primary-sourced

## Claim 12: scalar:sources[5].note — LEGISinfo as source for bill structure, second reading 24 April 2023, INDU referral, death on prorogation 6 January 2025

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27
Source tier: primary
Source content: "An Act to enact the Consumer Privacy Protection Act, the Personal Information and Data Protection Tribunal Act and the Artificial Intelligence and Data Act"; second reading "Monday, April 24, 2023"; referred to Standing Committee on Industry and Technology; "the 44th Parliament, 1st session concluded on Monday, January 6, 2025" with the bill still in committee.
Comparison: Note (scalar path sources[5].note) matches the LEGISinfo record on all four elements.
Decision: primary-sourced

## Claim 13: six civil society organisations and academics testified at INDU meeting 94 as part of the study of Bill C-27, the Digital Charter Implementation Act, 2022

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes + https://www.parl.ca/legisinfo/en/bill/44-1/c-27
Source tier: primary
Source content: Minutes list six witness organisations; LEGISinfo short title: "Digital Charter Implementation Act, 2022".
Comparison: Body matches the official record on the witness count, the study, and the bill's short title.
Decision: corroborated

## Claim 14: Bill C-27 bundled the CPPA, the Personal Information and Data Protection Tribunal Act, and AIDA; AIDA takes a risk-based approach requiring operators of "high-impact" systems to identify, assess, and mitigate risks of harm and bias

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27 + https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document
Source tier: primary
Source content: LEGISinfo names the three acts. Companion document: "AIDA would require that appropriate measures be put in place to identify, assess, and mitigate risks of harm or biased output prior to a high-impact system being made available for use."
Comparison: Body matches both primary sources; the identify/assess/mitigate and "high-impact" language is near-verbatim from the companion document.
Decision: corroborated

## Claim 15: AIDA vested primary AI oversight in the Minister of ISED and proposed an AI and Data Commissioner operating under that department

Source: https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document
Source tier: primary
Source content: "The Minister of Innovation, Science, and Industry would be responsible for administration and enforcement"; "AIDA would create a new statutory role for an AI and Data Commissioner, who would support the Minister"; "Codifying the role of the Commissioner would separate the functions from other activities within ISED".
Comparison: Body matches the companion document; the coalition letter's demand to remove AI regulation "from ISED's sole jurisdiction" independently corroborates the department placement.
Decision: corroborated

## Claim 16: civil society had argued the ISED conflict of interest "from the bill's introduction in June 2022"

Source: https://gowlingwlg.com/en/insights-resources/articles/2023/committee-study-of-bill-c-27 (via search)
Source tier: mainstream
Source content: Search-snippet: Minister Champagne announced "significant amendments to the bill that was originally introduced in June 2022."
Comparison: The June 2022 introduction date is confirmed by one canonical source; the "from the bill's introduction" span of the civil-society argument is consistent with the record but rests on this single confirmation of the date token.
Decision: single-source

## Claim 17: the bill passed second reading on 24 April 2023 and INDU began formal witness hearings in September 2023

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27 + https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-86/evidence
Source tier: primary
Source content: LEGISinfo: second reading "Monday, April 24, 2023"; hearings "began in September 2023". Meeting-86 evidence: "Pursuant to the order of reference of Monday, April 24, 2023, the committee is commencing consideration" (26 September 2023).
Comparison: Both dates match two primary parliamentary records.
Decision: corroborated

## Claim 18: Minister Champagne appeared as the first witness on 26 September 2023

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-86/evidence
Source tier: primary
Source content: Meeting 86, "Tuesday, September 26, 2023"; "the Hon. François-Philippe Champagne, Minister of Innovation, Science and Industry, appeared"; the chair announced the committee "is commencing consideration" of C-27 at this meeting.
Comparison: Body matches: the study's opening meeting was 26 September 2023 with Champagne as the witness; a Gowling WLG bulletin ("Committee study of Bill C-27 to start on September 26") corroborates.
Decision: corroborated

## Claim 19: on 25 September 2023 a coalition of 45 organisations, experts, and academics released an open letter with five demands; signatories included OpenMedia, ICLMG (McSorley), CCLA (Konikoff), PIAC (Sai), BCCLA, and Professor Emeritus Andrew Clement

Source: https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
Source tier: primary
Source content: "45 leading civil society organisations, experts and academics"; five demands as quoted at Claim 11; named signatories include "Aislin Jackson, Policy Staff Counsel, British Columbia Civil Liberties Association" and "Andrew Clement, Professor Emeritus, University of Toronto".
Comparison: Body's date, count, all five demands, and each named signatory match the release; the body's paraphrase of the five demands preserves their substance.
Decision: primary-sourced

## Claim 20: Hatfield testified that privacy reform was "long overdue" and worthy of passage with amendments, while AIDA was "frankly undercooked" and should be removed from C-27 for full public consultation

Source: https://openparliament.ca/committees/industry/44-1/94/ + https://openmedia.org/article/item/canada-must-regulate-ai-right-not-first
Source tier: primary
Source content: Transcript: "One part is long-overdue privacy reform, and your task is closing its remaining loopholes." Article: "One part is frankly undercooked AI regulation you should take out of C-27 altogether"; "I urge you to separate AIDA from C-27, and send it back for a full public consultation".
Comparison: Both quoted tokens and the removal-for-consultation position match the transcript and OpenMedia's published testimony.
Decision: corroborated

## Claim 21: Hatfield rated AIDA "between a three and an undeciphered symbol," noting the committee did not yet have every piece of the puzzle

Source: no canonical source found
Source tier: none
Source content: Cited article probe: "No, this phrase does not appear anywhere in the article… the author does not provide a numerical rating"; "'every piece of the puzzle' or similar" also absent. Official evidence transcript: "No witness provided a numeric scale rating of AIDA in this transcript." Web search for the phrase returns no results.
Comparison: The quoted rating and the puzzle remark could not be found in the source the entity cites for them, the official transcript, or search; possible confabulated quote, but absence cannot be proven from summarised fetches and there is no single-token replacement.
Decision: uncorroborated

## Claim 22: Hatfield argued protections extended to children's data should apply to all Canadians

Source: https://openparliament.ca/committees/industry/44-1/94/brad-vis-9/
Source tier: primary
Source content: "I do think we need to ask ourselves whether many of the protections enjoyed by children shouldn't be enjoyed by everyone in Canada."
Comparison: Body paraphrase matches the transcript quote.
Decision: primary-sourced

## Claim 23: OpenMedia also submitted a detailed written brief to INDU

Source: https://openmedia.org/article/item/your-voice-delivered-Bill-C27
Source tier: primary
Source content: "OpenMedia delivered a detailed submission to Parliament's INDU committee, which will be undertaking a study of Bill C-27." (4 May 2023, Bryan Short)
Comparison: Body claim matches OpenMedia's own record of the submission; the entity links the submission PDF on openmedia.org.
Decision: primary-sourced

## Claim 24: McSorley focused on national security exemptions described as "unacceptable and dangerous for our rights" and the position that AIDA's regulations fail to adequately address human rights concerns

Source: https://iclmg.ca/c-27-indu/
Source tier: primary
Source content: "Bill C-27 contains several national security exemptions that are unacceptable and dangerous for our rights"; the AI regulations "fail to address the human rights concerns around the technology overall".
Comparison: Body matches ICLMG's own published account of the testimony.
Decision: primary-sourced

## Claim 25: Konikoff raised concerns about children's data protections and the committee's findings on children's biometric and location data commercialisation

Source: no canonical source found for this characterisation
Source tier: none
Source content: Official evidence transcript: Konikoff said "Biometric data is perhaps the most vulnerable data we have, and its abuse can be particularly devastating to members of equity-seeking groups" and urged that C-27 "unequivocally define biometric information as sensitive information"; per the transcript probe he "did not specifically address location data or children".
Comparison: The transcript supports Konikoff on biometric data as undefined sensitive information, not on children's data protections or children's biometric/location commercialisation; the body's characterisation does not match the found record and has no single-token fix.
Decision: uncorroborated

## Claim 26: Polsky characterised current practices around children's data as "reprehensible" and highlighted the failure to define "sensitive information" despite designating children's data as sensitive

Source: https://openparliament.ca/committees/industry/44-1/94/brad-vis-9/
Source tier: primary
Source content: "Of course it's ethically wrong. It's reprehensible. It doesn't give parents, guardians or the kids any say." "Both witnesses flagged that Bill C-27 lacks a definition for 'sensitive information' despite applying it to children's data."
Comparison: Both the "reprehensible" token and the definitional-gap point match the transcript record.
Decision: primary-sourced

## Claim 27: Polsky described children's information as "gathered surreptitiously and shared with the data broker industry"

Source: no canonical source found
Source tier: none
Source content: Evidence-transcript probe: "the transcript does not contain a specific verbatim quote from Polsky about children's information being gathered surreptitiously and shared with data brokers"; her recorded data-broker remark is "the monetization of our personal information by a global data broker industry already worth more than $300 billion U.S."
Comparison: The specific quoted phrase could not be located in the official transcript or the openparliament digest; thematically adjacent remarks exist but the verbatim attribution is unsupported.
Decision: uncorroborated

## Claim 28: Lawford and Sai participated as co-signatories of the September 2023 coalition letter who translated its five demands into testimony

Source: https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation + https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: Release names "Yuka Sai, Staff Lawyer, Public Interest Advocacy Centre" among signatories; "John Lawford from the Public Interest Advocacy Centre is not mentioned as an individual signatory." Minutes confirm both testified for PIAC.
Comparison: Both testified (confirmed), and Sai is a named signatory, but Lawford's co-signatory status is not confirmable from the release (the full 45-name list is not published on the page); the joint "co-signatories" claim as written cannot be confirmed.
Decision: uncorroborated

## Claim 29: Sam Andrey (Toronto Metropolitan University) testified

Source: https://www.ourcommons.ca/DocumentViewer/en/44-1/INDU/meeting-94/minutes
Source tier: primary
Source content: Witness list includes "Toronto Metropolitan University: Sam Andrey".
Comparison: Attendance and affiliation match the minutes; the "academic context" characterisation is interpretive and not audited.
Decision: primary-sourced

## Claim 30: the three structural asks matched the formal amendment package OpenMedia and stakeholders delivered to parliamentarians in March 2024

Source: https://openmedia.org/article/item/stakeholders-present-key-artificial-intelligence-amendments-to-bill-c-27
Source tier: primary
Source content: Published "March 4th, 2024"; "A package of AIDA High-Priority Amendments to Members of Parliament"; includes "a mechanism of iterative consultation and review" and "an independent AI & Data Commissioner, detached from industry influence and direct Ministerial control."
Comparison: The hard specific — a March 2024 amendment-package delivery — is confirmed; the package's commissioner-independence and iterative-review planks align with two of the three testimony asks (the fetched summary does not mention AIDA separation, so "matched" is partial but the dated delivery is sound).
Decision: primary-sourced

## Claim 31: the campaign's mobilisation comprised nearly 40,000 member inputs and 10,000+ contacts to government on AI

Source: https://openmedia.org/article/item/your-voice-delivered-Bill-C27 + https://openmedia.org/press/item/advocates-demand-proper-consideration-for-ai-regulation
Source tier: primary
Source content: "Nearly 40,000 action takers from the OpenMedia community provided input for the submission"; "in the past two years, more than 10,000 signatures and letters were sent to government officials" regarding AI and facial recognition.
Comparison: Both counts match OpenMedia's own published figures.
Decision: primary-sourced

## Claim 32: Bill C-27 never reached a vote; Parliament was prorogued on 6 January 2025, killing all pending legislation including C-27

Source: https://www.parl.ca/legisinfo/en/bill/44-1/c-27
Source tier: primary
Source content: "the 44th Parliament, 1st session concluded on Monday, January 6, 2025, with Bill C-27 remaining stalled in committee review" — final status "At consideration in committee", i.e. never reached report stage or third reading.
Comparison: Date and the bill's death-in-committee match LEGISinfo; the body's attribution to Trudeau's resignation is a widely documented public-record event consistent with the date.
Decision: primary-sourced
