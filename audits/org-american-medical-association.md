---
entity_id: org-american-medical-association
entity_hash: b387bccdade762eeeb9c8949161f52a1d8ac34ee
audit_date: 2026-09-16
pass: 1
status: corrections-pending
claims_total: 23
claims_corroborated: 8
claims_primary_sourced: 7
claims_single_source: 3
claims_uncorroborated: 4
open_corrections: 1
sources_consulted:
  - https://en.wikipedia.org/wiki/American_Medical_Association
  - https://www.ama-assn.org/about/ama-history/ama-history
  - https://www.ama-assn.org/press-center/ama-press-releases/ama-issues-new-principles-ai-development-deployment-use
  - https://www.ama-assn.org/press-center/ama-press-releases/ama-develop-recommendations-augmented-intelligence
  - https://www.ama-assn.org/practice-management/prior-authorization/oversight-needed-payers-use-ai-prior-authorization
  - https://www.ama-assn.org/practice-management/digital-health/2-3-physicians-are-using-health-ai-78-2023
  - https://www.ama-assn.org/press-center/ama-press-releases/ama-launches-center-digital-health-and-ai
  - https://ama-assn.org/councils/council-long-range-planning-development/council-long-range-planning-development-clrpd
  - https://www.ama-assn.org/system/files/ama-ai-principles.pdf
  - https://www.ama-assn.org/system/files/2019-08/ai-2019-board-report.pdf
  - https://www.ama-assn.org/practice-management/digital-health/augmented-intelligence-medicine
  - https://www.ama-assn.org/practice-management/digital-health/ama-ai-specialty-collaborative
  - https://www.ama-assn.org/practice-management/digital-health/more-80-physicians-use-ai-professionally-ama-survey
  - https://www.ethicalpsychology.com/2019/07/making-policy-on-augmented-intelligence.html
  - https://www.healthcareitnews.com/news/ama-creates-new-center-digital-health-and-ai
  - https://www.encyclopedia.com/sports-and-everyday-life/social-organizations/private-organizations/american-medical-association
---

## Claim 1: scalar:sources[0].note — Wikipedia note incl. quoted phrase "largest association of physicians and medical students in the U.S."

Source: https://en.wikipedia.org/wiki/American_Medical_Association
Source tier: tiebreaker
Source content: Infobox "Formation: May 7, 1847"; "Membership was 271,660 in 2022"; "330 North Wabash, Chicago". Lead: "an American professional association and lobbying group of physicians and medical students" — no "largest association" phrase anywhere in the live article.
Comparison: Scalar path sources[0].note. Founding date, membership, and HQ all verified on the live article, but the quoted "largest association of physicians and medical students in the U.S." is no longer present (source drift since last_checked 2026-06-08). Re-anchoring or dropping the quote is a prose-judgment fix, not a single-token replacement.
Decision: uncorroborated

## Claim 2: "founded on May 7, 1847, in Philadelphia by Nathan Smith Davis"

Source: https://www.ama-assn.org/about/ama-history/ama-history
Source tier: primary
Source content: "An 1845 resolution to the New York Medical Association by Dr. Nathan S. Davis, calling for a national medical convention, led to the establishment of the American Medical Association (AMA) in 1847." Wikipedia infobox: "Formation: May 7, 1847"; "founded in Philadelphia by Nathan Smith Davis".
Comparison: Date, place, and founder each confirmed by AMA's own history page plus Wikipedia (and third-party histories).
Decision: corroborated

## Claim 3: founding convention of "more than 250 physicians from forty medical societies and twenty-eight medical colleges"

Source: https://www.encyclopedia.com/sports-and-everyday-life/social-organizations/private-organizations/american-medical-association
Source tier: database
Source content: Search-indexed founding histories: "approximately 250 delegates representing 40 medical societies, 28 colleges, and 22 states plus the District of Columbia."
Comparison: 40 societies and 28 colleges match exactly; delegate count attested as "approximately 250" vs body's "more than 250" — same substance, single non-primary source directly fetchable.
Decision: single-source

## Claim 4: "By 2022 membership stood at approximately 271,000"

Source: https://en.wikipedia.org/wiki/American_Medical_Association
Source tier: tiebreaker
Source content: "Membership was 271,660 in 2022."
Comparison: Named-entity definitional fact — Wikipedia-alone sufficient per source rule; 271,660 rounds to approximately 271,000.
Decision: single-source

## Claim 5: "the largest professional physician organization in the country"

Source: https://www.ama-assn.org/about/ama-history/ama-history
Source tier: primary
Source content: AMA's own site refers to the AMA as "the largest physician organization"; third-party descriptions (SIU School of Medicine, Health Exec) carry "the largest professional association of physicians (MDs and DOs) and medical students in the United States."
Comparison: Self-description plus independent institutional descriptions agree.
Decision: corroborated

## Claim 6: House of Delegates "convenes twice a year with elected representatives from more than 190 state and specialty medical societies; it functions as the AMA's legislative body"

Source: https://www.ama-assn.org/press-center/ama-press-releases/ama-announces-board-trustees-2024-2025
Source tier: primary
Source content: "physicians and medical students representing more than 190 state and specialty medical societies convened during the Annual Meeting of the House of Delegates, the AMA's policy-making body"; Wikipedia: "policy discussion groups that meet twice a year for an annual meeting and an Interim meeting."
Comparison: 190+ societies, twice-yearly meetings, and policy-making role all attested by AMA primary plus Wikipedia.
Decision: corroborated

## Claim 7: House of Delegates "modelled after the U.S. House of Representatives"

Source: no canonical source found
Source tier: none
Source content: AMA and affiliate descriptions say the HOD "functions like a Congress" and is the AMA's "principal policy-making body" / a "democratic forum"; none of the fetched or search-indexed canonical sources state it was modelled after the U.S. House of Representatives.
Comparison: The specific modelling claim is unattested; adjacent language ("like a Congress") exists but is not the same assertion.
Decision: uncorroborated

## Claim 8: "Chicago headquarters at 330 North Wabash and a Washington D.C. policy office"

Source: https://en.wikipedia.org/wiki/American_Medical_Association
Source tier: primary
Source content: Wikipedia: "330 North Wabash, Chicago, Illinois, United States". AMA's own advocacy guide and directory listings place the AMA Washington office at 25 Massachusetts Ave NW (with a reported 2026 move to 200 Massachusetts Ave NW).
Comparison: Both facts confirmed across AMA primary material and independent listings.
Decision: corroborated

## Claim 9: "John Whyte, MD, MPH serves as CEO and Executive Vice President"

Source: https://www.ama-assn.org/press-center/ama-press-releases/ama-launches-center-digital-health-and-ai
Source tier: primary
Source content: "AMA CEO & Executive Vice President John Whyte, MD, MPH announced the launch"; Wikipedia: "CEO: John Whyte".
Comparison: Title and credentials confirmed by AMA primary and Wikipedia.
Decision: corroborated

## Claim 10: AI is designed to "enhance human intelligence rather than replace it" (quoted as AMA formulation)

Source: https://www.ama-assn.org/practice-management/digital-health/augmented-intelligence-medicine
Source tier: primary
Source content: "The AMA House of Delegates uses the term augmented intelligence (AI) as a conceptualization of artificial intelligence that focuses on AI's assistive role, emphasizing that its design enhances human intelligence rather than replaces it."
Comparison: The body's quotation marks assert verbatim AMA wording, but AMA's verbatim is "enhances human intelligence rather than replaces it" — the body renders it in altered inflection ("enhance … replace it"). Single correct replacement: quote AMA's actual wording (or unquote). Paraphrase-as-quote class.
Decision: correction

## Claim 11: CLRPD produced "A Primer on Artificial and Augmented Intelligence" and "Generative AI in Medicine and Health Care" with the stated coverage

Source: https://ama-assn.org/councils/council-long-range-planning-development/council-long-range-planning-development-clrpd
Source tier: primary
Source content: Primer "provides a history, definitions and components, and the status of AI in health care"; the generative-AI report covers "terminologies and components, definitions, prominent models, promises, challenges, and pitfalls."
Comparison: Both titles and their described coverage match the cited CLRPD projects page. Scalar sources[9].note verified by the same fetch.
Decision: primary-sourced

## Claim 12: June 2018 Annual Meeting: House of Delegates adopted H-480.940 with requirements (user-centred design, transparency, reproducibility, bias/vulnerable populations, privacy/security)

Source: https://www.ama-assn.org/system/files/2019-08/ai-2019-board-report.pdf
Source tier: primary
Source content: "[p]romote development of thoughtfully designed, high-quality, clinically validated health care AI that is designed and evaluated in keeping with best practices in user-centered design… is transparent; conforms to leading standards for reproducibility; identifies and takes steps to address bias and avoids introducing or exacerbating health care disparities including when testing or deploying new AI tools on vulnerable populations; and safeguards patients' and other individuals' privacy interests…" AMA Journal of Ethics (Feb 2019): "In June 2018, the AMA adopted a new policy, H-480.940."
Comparison: Adoption date and every enumerated requirement match AMA primary documents. (Note: cited policysearch.ama-assn.org URL renders an empty JS shell on fetch; verified via AMA board-report PDF instead.) Covers scalar sources[2].note.
Decision: corroborated

## Claim 13: "The policy explicitly enumerates values of ethical relevance — professionalism, transparency, justice, safety, and privacy — as co-equal concerns"

Source: https://www.ethicalpsychology.com/2019/07/making-policy-on-augmented-intelligence.html
Source tier: primary
Source content: AMA Journal of Ethics (mirrored): "Values of ethical relevance considered in this policy include professionalism, transparency, justice, safety, and privacy."
Comparison: The five values are verbatim-attested — but in the AMA Journal of Ethics commentary about the policy, not enumerated in the policy text itself (the extracted policy language carries no "professionalism" or "justice"). "The policy explicitly enumerates" misplaces the enumeration; the fix is a re-wording judgment, not a token swap.
Decision: uncorroborated

## Claim 14: 2019 policy H-480.939 supports AI advancing the quadruple aim (patient experience, population health, cost reduction, physician satisfaction)

Source: https://www.ama-assn.org/system/files/ama-ai-principles.pdf
Source tier: primary
Source content: "the development of the AMA's foundational AI policy in 2018 and subsequent policy on coverage and payment for AI in 2019"; 2019 AI Board report / policy text: AI systems should "enhance the patient experience of care and outcomes, improve population health, reduce overall costs for the health care system while increasing value, and support the professional satisfaction of physicians and the health care team."
Comparison: 2019 adoption and all four quadruple-aim components confirmed in AMA primary documents. Covers scalar sources[3].note.
Decision: corroborated

## Claim 15: "At its November 2023 Board of Trustees meeting, the AMA adopted a set of seven advocacy principles" (oversight, transparency, disclosure, generative AI, privacy/security, bias mitigation, liability)

Source: https://www.ama-assn.org/system/files/ama-ai-principles.pdf
Source tier: primary
Source content: "in November 2023, the AMA Board of Trustees approved a set of advocacy principles developed by the Council on Legislation (COL)"; Nov 28, 2023 press release lists the seven principle areas matching the body's list.
Comparison: Adopting body (Board of Trustees), November 2023 timing, and all seven principle topics match AMA's own documents. Covers scalar sources[4].note (press release date Nov 28, 2023 confirmed).
Decision: primary-sourced

## Claim 16: June 2023: HoD directive + Cigna case — "more than 300,000 claims were denied" with physicians "spending an average of 1.2 seconds per claim"

Source: https://www.ama-assn.org/practice-management/prior-authorization/oversight-needed-payers-use-ai-prior-authorization
Source tier: primary
Source content: "Over a period of two months in 2022, Cigna doctors denied more than 300,000 claims" with physicians "spending an average of 1.2 seconds on each case"; directives to advocate for criteria "derived from national medical specialty society guidelines," reviews by professionals "not incentivized to deny care," and "human examination of patient records prior to a care denial."
Comparison: Cigna figures and each HoD advocacy directive match the cited AMA page (dated June 14, 2023; June 13, 2023 companion release confirmed with its risk language). Covers scalars sources[5].note and sources[6].note.
Decision: primary-sourced

## Claim 17: "1 in 3 physicians had witnessed prior authorization causing serious adverse events"

Source: https://www.ama-assn.org/practice-management/prior-authorization/oversight-needed-payers-use-ai-prior-authorization
Source tier: primary
Source content: AMA coverage heading: "1 in 3 doctors has seen prior auth lead to serious adverse event" (AMA prior-authorization physician survey).
Comparison: Matches the AMA's own survey figure as carried on the cited page.
Decision: primary-sourced

## Claim 18: physician AI use "38% … in 2023; by 2024 the figure had risen to 66%; by 2026 it exceeded 80%"

Source: https://www.ama-assn.org/practice-management/digital-health/more-80-physicians-use-ai-professionally-ama-survey
Source tier: primary
Source content: Cited survey page (Feb 26, 2025): 38% in 2023, 66% in 2024, "More than half of physicians—57%—said reducing administrative burdens…"; AMA 2026 survey: "more than four in five physicians (81 percent) use AI in their practices" (Jan 15–Feb 2, 2026 fielding).
Comparison: All three year-figures confirmed by AMA primary pages, with mainstream coverage (Fierce Healthcare, ASCO Post) agreeing on the 2026 doubling.
Decision: corroborated

## Claim 19: scalar:sources[7].note — attributes 38%/66%/">80% in 2026" + "top concern is data privacy" to the cited survey-summary page

Source: https://www.ama-assn.org/practice-management/digital-health/2-3-physicians-are-using-health-ai-78-2023
Source tier: primary
Source content: The cited page carries 38% (2023), 66% (2024), and the 57% administrative-burden figure; it does not carry any 2026 figure, and it does not name a single top concern ("47%—ranked increased oversight as the number one regulatory action…"; data privacy listed among several concerns).
Comparison: Scalar path sources[7].note. The 2026 figure and the "top concern is data privacy" ranking are attributed to a page that carries neither (the 81% figure lives on AMA's 2026 survey pages). Fix requires re-anchoring the note — prose judgment, not a token swap.
Decision: uncorroborated

## Claim 20: "The top opportunity physicians cite for AI is reduction of administrative burden"; concerns centre on data privacy, reliability, incorrect-but-confident recommendations

Source: https://www.ama-assn.org/practice-management/digital-health/2-3-physicians-are-using-health-ai-78-2023
Source tier: primary
Source content: "More than half of physicians—57%—said reducing administrative burdens through automation was the biggest area of opportunity for AI"; AMA 2026 survey coverage lists concerns that AI tools "put privacy at risk, integrate poorly with EHR systems, offer incorrect conclusions or recommendations and introduce new liability concerns."
Comparison: Top-opportunity claim matches exactly; the plural concerns list matches AMA's own concern enumeration in substance.
Decision: primary-sourced

## Claim 21: "On October 20, 2025, the AMA launched the Center for Digital Health and AI … announced by CEO John Whyte, MD, MPH" with four focus areas

Source: https://www.ama-assn.org/press-center/ama-press-releases/ama-launches-center-digital-health-and-ai
Source tier: primary
Source content: Press release dated October 20, 2025; announced by "AMA CEO & Executive Vice President John Whyte, MD, MPH"; four focus areas: policy and regulatory leadership, clinical workflow integration, education & training, collaboration/partnerships across tech, research, government, healthcare.
Comparison: Date, announcer, and all four focus areas match the cited release. Covers scalar sources[8].note.
Decision: primary-sourced

## Claim 22: Center launched "after two years of studying how physicians interact with AI systems"

Source: https://www.healthcareitnews.com/news/ama-creates-new-center-digital-health-and-ai
Source tier: mainstream
Source content: "After two years spent studying how doctors use artificial intelligence and developing guidance around AI to better serve its physician members, the American Medical Association on Monday announced a new Center for Digital Health and AI."
Comparison: The two-years framing is carried by specialist trade coverage, not the AMA release itself (release fetch contains no "two years" language).
Decision: single-source

## Claim 23: "AI Specialty Collaborative — bringing together 21 medical specialty societies"

Source: https://www.ama-assn.org/practice-management/digital-health/ama-ai-specialty-collaborative
Source tier: primary
Source content: "The AMA's AI Specialty Collaborative brings together 21 medical specialty societies to help ensure that physicians have a central role in shaping how AI is developed and integrated into healthcare" (convened 2024).
Comparison: The 21-societies fact matches AMA's own collaborative page. The body's "The Center carries forward the AI Specialty Collaborative" linkage is not stated in the launch release or the collaborative page — interpretive framing over the two attested facts, not graded separately.
Decision: primary-sourced
