---
entity_id: event-7amleh-meta-bsr-human-rights-investigation-2022-09
entity_hash: f8e8108cd11d4ed24c2d580bb5b249f8ab7e0a1a
audit_date: 2026-07-07
pass: 1
status: corrections-pending
claims_total: 27
claims_corroborated: 7
claims_primary_sourced: 11
claims_single_source: 1
claims_uncorroborated: 4
open_corrections: 4
sources_consulted:
  - https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
  - https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
  - https://www.hrw.org/news/2022/09/27/statement-regarding-bsrs-hra-meta-palestine-israel
  - https://www.accessnow.org/press-release/bsr-findings-meta-palestinian-rights/
  - https://meta.7amleh.org/about
  - https://www.lawfaremedia.org/article/independent-report-metas-human-rights-impact-israel-and-palestine-may-2021-released
  - https://www.bsr.org/en/blog/human-rights-due-diligence-of-meta-impacts-in-israel-and-palestine-may-2021
  - https://www.article19.org/resources/israel-and-palestine-meta-must-uphold-human-rights-obligations/
---

## Claim 1: scalar:date `2022-09-22` + body "On 22 September 2022, Meta published the findings of an independent Human Rights Due Diligence assessment by Business for Social Responsibility (BSR)"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/ ; https://www.bsr.org/en/blog/human-rights-due-diligence-of-meta-impacts-in-israel-and-palestine-may-2021
Source tier: primary
Source content: Meta's announcement is dated September 22, 2022; BSR's own report/blog pages date publication to September 2022; the joint statement of 27 September responds to it as just-published.
Comparison: Publication date and publisher match across Meta's announcement and BSR's report page.
Decision: corroborated

## Claim 2: edges — `campaign: camp-7amleh-meta-palestinian-content-moderation-2023-ongoing`; `participating_orgs: org-7amleh, org-access-now, org-human-rights-watch`; `participating_people: person-marwa-fatafta`; `location: online / international`

Source: https://www.hrw.org/news/2022/09/27/statement-regarding-bsrs-hra-meta-palestine-israel ; https://www.accessnow.org/press-release/bsr-findings-meta-palestinian-rights/
Source tier: primary
Source content: Signatory list (HRW-hosted copy) opens "7amleh- The Arab Center for the Advancement of Social Media / Access Now" and includes "Human Rights Watch" (item 64); Access Now's own release quotes "Marwa Fatafta, MENA Policy and Advocacy Manager at Access Now."
Comparison: All four org/person edges resolve to existing corpus entities and are confirmed participants (7amleh, Access Now, HRW signatories; HRW hosts the statement; Fatafta quoted in the civil-society response). The campaign edge resolves to an existing Campaign entity on the same subject (mechanical resolution). Location "online / international" is consistent with a report publication plus international joint statement.
Decision: corroborated

## Claim 3: edge — `participating_orgs: org-article-19`

Source: https://www.hrw.org/news/2022/09/27/statement-regarding-bsrs-hra-meta-palestine-israel ; https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: Article 19 does not appear in the signatory list of either hosted copy of the 27 September 2022 joint statement (HRW-hosted list reproduced in full, 72 entries; 7amleh-hosted copy checked directly: "Article 19 / ARTICLE 19: Not present in the signatory list"). Article 19 published its own separate response to the BSR report (article19.org, "Israel and Palestine: Meta must uphold human rights responsibilities").
Comparison: The entity grounds Article 19's participation in the joint statement (body, § Civil society response), but Article 19 is not a signatory on either hosted copy. Fix location: frontmatter `participating_orgs`. Default mechanical fix is removal; whether Article 19's separate own-statement response warrants keeping the edge on different grounding is prose judgment — flag to Researcher.
Decision: correction

## Claim 4: body "7amleh and more than 60 civil society organisations — including Human Rights Watch, Access Now, Article 19, Amnesty International, the Electronic Frontier Foundation, Al-Haq, Jewish Voice for Peace"

Source: https://www.hrw.org/news/2022/09/27/statement-regarding-bsrs-hra-meta-palestine-israel ; https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: Full HRW-hosted signatory list (72 entries) includes 7amleh, Access Now, Electronic Frontier Foundation, Al-Haq, Human Rights Watch — but no Amnesty International, no Article 19, no Jewish Voice for Peace. 7amleh-hosted copy confirms: "Amnesty International: Not present... Article 19: Not present... Jewish Voice for Peace: Not present in the signatory list." (The list does include "Union juive française pour la paix" — French Jewish Union for Peace — a distinct organisation, the likely confusion source for JVP.)
Comparison: Three named signatories (Article 19, Amnesty International, Jewish Voice for Peace) contradict both hosted copies of the source; the other four named (HRW, Access Now, EFF, Al-Haq) are confirmed. Fix: remove the three false names from the enumeration in § Civil society response, and the echo in § Significance ("7amleh, HRW, Access Now, Article 19, Amnesty International, EFF") — that Significance echo describes the post-Oct-2023 campaign coalition, which is prose judgment beyond a single replacement; flag to Researcher.
Decision: correction

## Claim 5: scalar:sources[3].note (hrw.org) — "independent corroboration of the signatory coalition including 7amleh, Access Now, Amnesty International, Article 19, EFF"

Source: https://www.hrw.org/news/2022/09/27/statement-regarding-bsrs-hra-meta-palestine-israel
Source tier: primary
Source content: The HRW-hosted signatory list contains 7amleh, Access Now, and Electronic Frontier Foundation, but neither Amnesty International nor Article 19 appears anywhere in the 72-entry list.
Comparison: The note misdescribes its own source's signatory list. Fix location: scalar `sources[3].note` — remove "Amnesty International, Article 19" from the enumeration (single mechanical replacement).
Decision: correction

## Claim 6: body "more than 60 civil society organisations" signed; "Five days later"; statement dated 27 September 2022

Source: https://www.hrw.org/news/2022/09/27/statement-regarding-bsrs-hra-meta-palestine-israel ; https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: Both hosted copies are dated September 27, 2022. Neither states a total in prose; counting the signatory lists yields 72 (HRW-hosted) and ~89 (7amleh-hosted) organisations — both exceed 60.
Comparison: 27 September is five days after 22 September; "more than 60" holds under either host's count (the true figure is higher — 72+ — but "more than 60" is not false).
Decision: corroborated

## Claim 7: body "In September 2021 the Meta Oversight Board formally recommended that Meta commission an independent human-rights impact assessment" + scalar:sources[0].note "Oversight Board recommendation that triggered the assessment"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
Source tier: primary
Source content: Meta's announcement states the Oversight Board recommended the assessment "in September 2021" and frames the due diligence as undertaken in response to that recommendation.
Comparison: Date and trigger match Meta's own announcement (single primary source).
Decision: primary-sourced

## Claim 8: body — BSR's assessment "proceeded through 2021 and 2022 with consultations across civil society, rights-holder, and stakeholder groups in Israel, Palestine, and internationally"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
Source tier: primary
Source content: "BSR conducted a detailed analysis, including engaging with groups and rights holders in Israel, Palestine, and globally, to inform its report."
Comparison: Consultation scope (civil society/rights holders, Israel/Palestine/global) matches Meta's announcement.
Decision: primary-sourced

## Claim 9: body — consultations "including 7amleh"

Source: no canonical source found
Source tier: none
Source content: Meta's announcement names no specific consulted organisations ("engaging with groups and rights holders in Israel, Palestine, and globally"); neither the joint statement nor 7amleh's campaign pages fetched this session state that BSR consulted 7amleh during the assessment.
Comparison: Plausible but unconfirmed in any source fetched this pass; the claim that 7amleh was among BSR's consultees could not be grounded.
Decision: uncorroborated

## Claim 10: body "During May 6–21, 2021, 7amleh documented a fifteen-fold increase in violent speech targeting Palestinians compared with the same period in 2020" + scalar:sources[2].note (fifteen-fold component)

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: "7amleh's racism and hate speech index between 6th to the 21st May 2021 showed a 15-fold increase in violent speech compared to the same time period of the previous year."
Comparison: Date range, multiplier, and comparison period (previous year = 2020) all match 7amleh's own statement.
Decision: primary-sourced

## Claim 11: body "Meta found on appeal that it had mistakenly taken down almost half of the Arabic-language content its systems had removed" + scalar:sources[5].note (appeal component)

Source: https://meta.7amleh.org/about
Source tier: primary
Source content: "Meta found that it mistakenly took down almost half of the Arabic language content in cases in which users appealed the action."
Comparison: Matches the cited campaign page verbatim in substance (appeal-cases scope preserved in the body's phrasing).
Decision: primary-sourced

## Claim 12: body "almost 1,500 digital rights violations across 2021 and 2022, over 80% of which had occurred on Meta's platforms" (also echoed in § Significance) + scalar:sources[5].note (violations component)

Source: https://meta.7amleh.org/about
Source tier: primary
Source content: "7amleh has documented almost 1500 violations from 2021 to 2022 alone. Over 80% of these violations occurred on Meta's platforms."
Comparison: Count, period, and Meta share match the cited campaign page.
Decision: primary-sourced

## Claim 13: body "found over-enforcement of Arabic content compared with Hebrew ... while under-enforcing community-standards violations in Hebrew" + scalar:sources[1].note (over-enforcement component)

Source: https://www.bsr.org/en/blog/human-rights-due-diligence-of-meta-impacts-in-israel-and-palestine-may-2021 ; https://www.accessnow.org/press-release/bsr-findings-meta-palestinian-rights/ ; https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
Source tier: primary
Source content: "BSR's findings provide further evidence of the over-enforcement of Arabic content compared to Hebrew content, and under-enforcement of content moderation policies on Hebrew language content."
Comparison: The asymmetric-enforcement finding matches across BSR's own pages, Access Now's release, and Meta's announcement.
Decision: corroborated

## Claim 14: body "adverse human-rights implications for Palestinians across four rights: freedom of expression, freedom of assembly, political participation, and non-discrimination" + scalar:sources[1].note (four-rights component)

Source: https://www.bsr.org/en/reports/meta-human-rights-israel-palestine ; https://www.accessnow.org/press-release/bsr-findings-meta-palestinian-rights/
Source tier: primary
Source content: "The report cites adverse human rights implications to Palestinians' right to freedom of expression, freedom of assembly, freedom to political participation, and non-discrimination." Access Now's release headline: Meta's actions "adversely impacted" Palestinians' rights.
Comparison: The four enumerated rights match the report's framing as carried by BSR's page and Access Now's coverage.
Decision: corroborated

## Claim 15: body — "The report's 21 recommendations spanned Meta's content-moderation policies, their enforcement, and transparency — including reevaluation of the Dangerous Organizations and Individuals (DOI) policy, investment in more precise Hebrew and Arabic language classifiers, enhanced transparency on government content-removal requests"

Source: https://www.bsr.org/en/blog/human-rights-due-diligence-of-meta-impacts-in-israel-and-palestine-may-2021 ; https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/ ; https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: "BSR made 21 specific recommendations ... covering areas related to Meta's policies, how those policies are enforced, and efforts to provide transparency to users." The joint statement: BSR said Meta should "reevaluate certain content moderation policies ... increase transparency ... invest in more precise Hebrew and Arabic language content moderation resources." Meta committed to "a comprehensive review" of incitement and Dangerous Organizations policies and to disclosing "the number of formal reports received from government entities to remove content."
Comparison: Count (21), the three spans, DOI reevaluation, Hebrew/Arabic precision investment, and government-request transparency all confirmed across BSR, Meta, and the joint statement.
Decision: corroborated

## Claim 16: body — 21 recommendations including "ongoing human-rights impact assessments"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
Source tier: none
Source content: Meta's announcement says "we'll keep people updated on our progress in our annual Human Rights report" and "Human rights assessments like these are an important way we can continue to improve" — Meta's own remarks, not a statement that ongoing HRIAs were among BSR's 21 recommendations.
Comparison: No fetched source confirms ongoing human-rights impact assessments as one of the recommendation areas; the full report PDF is unfetchable (bsr.org 403). Could not ground this specific element.
Decision: uncorroborated

## Claim 17: body "BSR also identified areas of good practice, including Meta's establishment of a dedicated Special Operations Center with regional experts and native Arabic and Hebrew speakers"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
Source tier: primary
Source content: "BSR identified the establishment of a dedicated Special Operations Center to respond to activity across Meta's apps in real time as a good practice. This center was staffed with expert teams, including regional experts and native speakers of Arabic and Hebrew."
Comparison: Good-practice finding, SOC, and staffing specifics match Meta's announcement.
Decision: primary-sourced

## Claim 18: body "Meta committed to fully implementing 10 of BSR's 21 recommendations, partially implementing 4, and assessing the feasibility of 6 others" + scalar:sources[0].note (10-of-21 component)

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/ ; https://www.accessnow.org/press-release/bsr-findings-meta-palestinian-rights/ ; https://www.lawfaremedia.org/article/independent-report-metas-human-rights-impact-israel-and-palestine-may-2021-released
Source tier: primary
Source content: Meta's announcement: full implementation 10, partial 4, assessing feasibility 6, no further action 1. Lawfare: Meta "will implement 10, partly implement four, and is currently 'assessing the feasibility of another six.'"
Comparison: The 10/4/6 split matches across Meta's announcement, Access Now, and Lawfare.
Decision: corroborated

## Claim 19: body "The one recommendation Meta declined was to fund public research exploring the relationship between counter-terrorism obligations and social media platforms"

Source: https://www.lawfaremedia.org/article/independent-report-metas-human-rights-impact-israel-and-palestine-may-2021-released
Source tier: mainstream
Source content: Meta declined the recommendation to "fund public research into 'the optimal relationship between legally required counterterrorism obligations and the policies and practices of social media platforms,'" stating it would "rely on its counsel to understand its legal obligations."
Comparison: The declined recommendation's subject matches. Meta's own announcement confirms one recommendation gets "no further action" but does not identify it — Lawfare is the only fetched source naming it.
Decision: single-source

## Claim 20: body — accepted commitments included "developing a Hebrew hostile speech machine-learning classifier, reviewing incitement and dangerous organisation policies ... expanding transparency in government content-removal reporting"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
Source tier: primary
Source content: "we have launched a Hebrew 'hostile speech' classifier to help us proactively detect more violating Hebrew content"; Meta will conduct "a comprehensive review" of incitement and dangerous organizations policies; Meta committed to disclosing "the number of formal reports received from government entities to remove content."
Comparison: These three commitment elements match Meta's announcement.
Decision: primary-sourced

## Claim 21: body — "hiring additional content reviewers with diverse dialect capabilities" listed "among the accepted commitments"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/ ; https://www.accessnow.org/press-release/bsr-findings-meta-palestinian-rights/
Source tier: primary
Source content: On Arabic dialects, Meta is "exploring a range of options" including "reviewing hiring more content reviewers with diverse dialect and language capabilities"; per Access Now's summary of the dialect-routing recommendation, "Meta is assessing the feasibility of this recommendation."
Comparison: The source places reviewer-hiring in the exploring/assessing-feasibility bucket, not among the accepted commitments; the body asserts the opposite status. Fix location: body § Meta's response — remove "hiring additional content reviewers with diverse dialect capabilities" from the accepted-commitments enumeration (or relabel as under feasibility assessment; the latter is prose judgment).
Decision: correction

## Claim 22: body "The statement commended the BSR review as a step in the right direction while pressing Meta to implement all 21 recommendations in full, with a transparent implementation timeline aligned with the UN Guiding Principles"

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: The signatories commend the report as "a step in the right direction," "look forward to Meta's unequivocal commitment to implementing the recommendations," and demand "a detailed timeline for exactly how they will commit to, and implement these recommendations in full transparency," with reference to the UN Guiding Principles on Business and Human Rights.
Comparison: Commendation, full-implementation press, timeline, and UNGP alignment all present in the statement.
Decision: primary-sourced

## Claim 23: body — quote "even if the bias started out as unintentional, after knowing about the issues for years and not taking appropriate action, the unintentional became intentional"

Source: https://www.hrw.org/news/2022/09/27/statement-regarding-bsrs-hra-meta-palestine-israel
Source tier: primary
Source content: "Therefore, even if the bias started out as unintentional, after knowing about the issues for years and not taking appropriate action, the unintentional became intentional."
Comparison: Verbatim match to the statement text.
Decision: primary-sourced

## Claim 24: body "Meta had historically complied with approximately 90% of Israeli government takedown requests" (attributed to the signatories) + scalar:sources[2].note (90% component)

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: "the company has historically complied around 90% of the time" (regarding Israeli government takedown requests).
Comparison: The figure and its attribution to the joint statement match.
Decision: primary-sourced

## Claim 25: body — Marwa Fatafta of Access Now quote "Meta's censorship of Palestinian content is fundamentally biased. Now we have the receipts to prove it." + her "MENA Policy and Advocacy" role + scalar:sources[4].note

Source: https://www.accessnow.org/press-release/bsr-findings-meta-palestinian-rights/
Source tier: primary
Source content: "We've long known that Meta's censorship of Palestinian content is fundamentally biased. Now we have the receipts to prove it," said Marwa Fatafta, MENA Policy and Advocacy Manager at Access Now. The release also rejects the "unintentional" framing and calls on Meta "to provide a detailed timeline for exactly how and when it will implement BSR's recommendations in full transparency."
Comparison: The quoted span is a contiguous verbatim substring of the original (the entity omits the opening clause "We've long known that" — attribution remains accurate); role and the sources-note components (rejection of "unintentional," timeline call) all confirmed.
Decision: primary-sourced

## Claim 26: body — "The joint statement's five collective demands ... full implementation of all 21 recommendations with a detailed timeline; complete transparency on Israeli government content-removal requests and responses; creation of a Hebrew-language hate speech lexicon; establishment of a co-design process with civil society; and adherence to the UN Guiding Principles in all implementation work" + scalar:sources[2].note ("7amleh's five structured demands")

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source tier: primary
Source content: The statement's asks: "provide complete transparency on voluntary content removal requests from the Israeli government," including its Cyber Unit; disclose where and how automated decision-making is used; share details about "terrorism"/"extremism" content policies; create "a Hebrew hate speech lexicon"; commit to "a co-design process with civil society"; provide "a detailed timeline for exactly how they will commit to, and implement these recommendations in full transparency."
Comparison: Individual elements (transparency on Israeli requests, Hebrew lexicon, co-design, timeline) are each in the statement, but the statement does not structure its asks as five demands, includes asks the entity omits (automated decision-making disclosure; terrorism/extremism policy details), and does not present UNGP adherence as a standalone demand. The "five collective demands" framing (body and scalar `sources[2].note`) is too paraphrastic to compare against the source's structure. Not an error finding; re-grouping is prose judgment.
Decision: uncorroborated

## Claim 27: body — "the first independent, third-party audit of Meta's content-moderation systems focused specifically on the asymmetric treatment of Arabic and Palestinian-language content"

Source: no canonical source found
Source tier: none
Source content: Meta's announcement, BSR's pages, the joint statement, Access Now, and Lawfare describe the exercise as an independent human rights due diligence of the May 2021 escalation; none of the fetched sources states it was the first such audit.
Comparison: "First" is a contested-attribution-class superlative; no fetched source asserts it. Not necessarily false, but ungrounded.
Decision: uncorroborated
