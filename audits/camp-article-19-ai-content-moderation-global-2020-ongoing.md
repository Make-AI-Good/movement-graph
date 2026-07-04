---
entity_id: camp-article-19-ai-content-moderation-global-2020-ongoing
entity_hash: dca5a48b424a48bf904afe6a7d2314a8e877db11
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 30
claims_corroborated: 4
claims_primary_sourced: 15
claims_single_source: 1
claims_uncorroborated: 8
open_corrections: 2
sources_consulted:
  - https://privacyinternational.org/press-release/1753/ai-tools-threaten-right-privacy-and-freedom-expression-report
  - https://www.unesco.org/en/articles/social-media-4-peace
  - https://www.eff.org/deeplinks/2024/03/disinformation-and-elections-eff-and-article-19-submit-key-recommendations-eu
  - https://dig.watch/updates/article-19-launches-the-social-media-4-peace-handbook
  - https://stories.article19.org/impact-report-2024/
  - https://fsi.stanford.edu/content/social-media-councils-concept-reality-conference-report
  - https://cmpf.eui.eu/the-social-media-councils-bringing-content-moderation-back-to-the-public-forum/
  - https://www.ohchr.org/sites/default/files/Documents/Issues/Expression/disinformation/2-Civil-society-organisations/ARTICLE19.pdf
  - https://www.article19.org/resources/eu-protect-freedom-of-expression-in-digital-services-act/
  - https://www.article19.org/resources/regulating-social-media-content-why-ai-alone-cannot-solve-the-problem/
  - https://www.article19.org/resources/social-media-councils-moderation/
  - https://www.article19.org/about-us/
  - https://digital-strategy.ec.europa.eu/en/policies/digital-services-act
  - https://artificialintelligenceact.eu/annex/3/
  - https://www.businesspost.ie/business/plans-for-worlds-first-social-media-council-in-ireland-d04bb1e9
---

Method note: article19.org returns HTTP 403 to direct fetch (bot-blocking; same class as amnestyusa.org per workbench). Claims resting on article19.org pages were compared via search-engine-surfaced content from those same pages plus independent coverage; where neither reached the specific assertion, the decision is `uncorroborated` (cannot compare), not a finding of error. Connective-type discipline applied: campaign entity — claim surface is org edges + hard specifics; interpretive positioning prose (corpus-comparison framing, Significance-register characterizations of other orgs) received no decisions.

## Claim 1: edge lead_orgs → org-article-19 (campaign led by ARTICLE 19)

Source: https://privacyinternational.org/press-release/1753/... ; https://www.unesco.org/en/articles/social-media-4-peace ; https://www.eff.org/deeplinks/2024/03/...
Source tier: primary
Source content: "UNESCO partnered with ARTICLE 19 to conduct research on content moderation practices"; EFF: "EFF and ARTICLE 19 submitted recommendations to the EU Commission"; PI: joint A19/PI report.
Comparison: Every tracked campaign activity (2018 reports, 2020 DSA submission, 2021 SMC, SM4P, 2024 submissions) is ARTICLE 19's work per multiple independent primary sources. Edge target exists in corpus.
Decision: corroborated

## Claim 2: edge participating_orgs → org-privacy-international

Source: https://privacyinternational.org/press-release/1753/ai-tools-threaten-right-privacy-and-freedom-expression-report
Source tier: primary
Source content: Report "Privacy and Freedom of Expression in the Age of Artificial Intelligence" by "ARTICLE 19 and Privacy International", 25 April 2018.
Comparison: PI's participation (joint 2018 report) confirmed by PI's own press release. Edge target exists in corpus.
Decision: primary-sourced

## Claim 3: edge participating_orgs → org-electronic-frontier-foundation

Source: https://www.eff.org/deeplinks/2024/03/disinformation-and-elections-eff-and-article-19-submit-key-recommendations-eu
Source tier: primary
Source content: "EFF and ARTICLE 19 submitted recommendations to the EU Commission regarding disinformation and election integrity measures" (March 21, 2024).
Comparison: EFF's participation confirmed by EFF's own site. Edge target exists in corpus.
Decision: primary-sourced

## Claim 4: scalar:start_date = 2020; body "first sustained regulatory engagement opened in September 2020"

Source: https://www.article19.org/resources/eu-protect-freedom-of-expression-in-digital-services-act/ (via search; direct fetch 403)
Source tier: primary
Source content: "In September 2020, ARTICLE 19 responded to the EU consultation on the future Digital Services Act ('DSA')..."
Comparison: Campaign-start anchor (Sept 2020 DSA consultation response) matches A19's own page. start_date 2020 consistent.
Decision: primary-sourced

## Claim 5: April 2018 joint A19/PI report — title, date, authorship, quoted content (body §Intellectual foundations + scalar:sources[2].note)

Source: https://privacyinternational.org/press-release/1753/ai-tools-threaten-right-privacy-and-freedom-expression-report
Source tier: primary
Source content: "AI practices of collecting and sharing data to profile and predict behaviour threaten the rights to privacy and free expression." / "Reliance by companies and governments on intelligent systems to moderate, filter, and remove what we post online increases the risk of over-broad censorship..." / "Ensure protection of international human rights standards."
Comparison: Title, joint authorship, April 2018 date (25th), both body quotes, and the HR-standards-baseline recommendation in scalar:sources[2].note all match verbatim or near-verbatim.
Decision: primary-sourced

## Claim 6: July 2018 report "Regulating social media content: Why AI alone cannot solve the problem" — title, date, "inherent inability to understand context", "can only solve part of the problem"

Source: https://www.article19.org/resources/regulating-social-media-content-why-ai-alone-cannot-solve-the-problem/ (via search; direct fetch 403)
Source tier: primary
Source content: Report published July 11, 2018; AI has "an inherent inability to understand context" and "can only solve part of the problem".
Comparison: Title, July 2018 date, and both quoted phrases match.
Decision: primary-sourced

## Claim 7: scalar:sources[1].note attributes the quote AI-only moderation "increases the risk of over-broad censorship" to the July 2018 report

Source: https://privacyinternational.org/press-release/1753/ai-tools-threaten-right-privacy-and-freedom-expression-report
Source tier: primary
Source content: The "increases the risk of over-broad censorship" phrase appears in the April 2018 joint report's framing per PI's press release; the July 2018 report's text is unreachable (403) to confirm it also carries this phrase.
Comparison: scalar:sources[1].note — the quote is confirmed for the April 2018 joint report, not confirmable for the July 2018 report it is attributed to here. Possibly present in both; cannot compare.
Decision: uncorroborated

## Claim 8: Sept 2020 DSA submission called for "a gold standard for the protection of fundamental rights online with radical transparency and accountability at the heart" (body + scalar:sources[0].note)

Source: https://www.article19.org/resources/eu-protect-freedom-of-expression-in-digital-services-act/ (via search; direct fetch 403)
Source tier: primary
Source content: "ARTICLE 19 called on the European Commission to set a gold standard for the protection of fundamental rights online with radical transparency and accountability at the heart of the DSA."
Comparison: Quote matches verbatim.
Decision: primary-sourced

## Claim 9: Sept 2020 submission's liability position — maintain conditional immunity, actual not constructive knowledge, avoid over-removal incentives (body §DSA)

Source: https://www.article19.org/resources/eu-protect-freedom-of-expression-in-digital-services-act/ (via search; direct fetch 403)
Source tier: primary
Source content: "Maintaining the current standard of knowledge required to benefit from immunity from liability as 'actual' rather than 'constructive knowledge', and that actual knowledge of illegality can only be obtained by an order of a court."
Comparison: Body's constructive-knowledge-liability / over-removal-incentive passage matches the submission's documented position.
Decision: primary-sourced

## Claim 10: Sept 2020 submission demanded mandatory disclosure of false-positive/false-negative rates and appeal rights explicitly covering automated decisions (body + scalar:sources[0].note)

Source: no canonical source found (submission full text unreachable — article19.org 403)
Source tier: none
Source content: Search-surfaced summaries of the submission name the liability, general-monitoring, and notice-and-action demands but do not mention error-rate disclosure or automated-decision appeal demands.
Comparison: scalar:sources[0].note and body assert these two demands; the reachable record neither confirms nor contradicts. Cannot compare.
Decision: uncorroborated

## Claim 11: DSA enacted October 2022; applying to very large online platforms from August 2023 (scalar:outcomes + body)

Source: https://digital-strategy.ec.europa.eu/en/policies/digital-services-act ; https://freedomhouse.org/article/eu-digital-services-act-win-transparency
Source tier: primary
Source content: "The Digital Services Act was published in the Official Journal of the European Union on 27 October 2022... On 25 August 2023 the DSA began applying to entities designated as Very Large Online Platforms."
Comparison: Both dates match (EC official pages + independent coverage).
Decision: corroborated

## Claim 12: DSA Article 15 transparency reporting covers automated content moderation — accuracy indicators, error rate, safeguards (scalar:outcomes + body)

Source: https://digital-strategy.ec.europa.eu/en/policies/dsa-brings-transparency ; DSA Art 15(1)(e) text
Source tier: primary
Source content: Reports must include "any use made of automated means for the purpose of content moderation, including... indicators of the accuracy and the possible rate of error of the automated means... and any safeguards applied."
Comparison: Matches. Note (no decision impact): Art 15 applies to all intermediary services, not only VLOPs — the entity's "for very large online platforms" framing is under-inclusive but true of VLOPs; VLOPs additionally report six-monthly under Art 42.
Decision: corroborated

## Claim 13: DSA Article 17 requires platforms to provide reasons for content moderation decisions, including automated ones (scalar:outcomes + body)

Source: https://digital-strategy.ec.europa.eu/en/policies/dsa-brings-transparency ; DSA Art 17 text
Source tier: primary
Source content: Article 17 requires "a clear and specific statement of reasons" each time platforms remove or restrict content, submitted to the Commission's DSA Transparency Database.
Comparison: Matches ("statement of reasons" for restriction decisions; automated decisions covered).
Decision: corroborated

## Claim 14: scalar:outcomes — "The EU AI Act (2024) requires meaningful human oversight and post-market monitoring for high-risk AI systems in categories that include content moderation at the scale of very large platforms"

Source: https://artificialintelligenceact.eu/annex/3/ (Annex III text) vs. secondary commentary
Source tier: none
Source content: Annex III's enumerated high-risk categories (biometrics, critical infrastructure, education, employment, essential services, law enforcement, migration, justice/democratic processes) do not name content moderation; secondary commentary is split on whether platform moderation systems can be classified high-risk.
Comparison: scalar:outcomes. The Act's human-oversight and post-market-monitoring duties for high-risk systems are real, but "categories that include content moderation at the scale of very large platforms" is not supported by the Act's own text and is contested in commentary. Canonical source vs. claim conflict on a judgment-loaded classification — not a single-token fix.
Decision: uncorroborated

## Claim 15: SMC proposal published October 2021 — multi-stakeholder, voluntary-compliance national bodies reviewing AI moderation decisions against international HR standards, issuing guidance, giving users recourse (body + scalar:sources[3].note)

Source: https://www.article19.org/resources/social-media-councils-moderation/ + https://www.article19.org/wp-content/uploads/2021/10/A19-SMC.pdf (via search; direct fetch 403)
Source tier: primary
Source content: "Social Media Councils: One piece in the puzzle of content moderation" (PDF path 2021/10); model is a "multi-stakeholder, voluntary-compliance mechanism... review individual content moderation decisions... on the basis of international standards on freedom of expression... provide general guidance."
Comparison: Publication date (October 2021) and all named model features match. Note: the SMC concept dates to A19's 2018–2019 consultation phase; October 2021 is the mature publication, which the body presents acceptably.
Decision: primary-sourced

## Claim 16: scalar:outcomes — SMC model "entered active piloting across multiple jurisdictions, with Stanford's Internet Observatory, CIGI, and the EU's Centre for Media Pluralism and Media Freedom all documenting pilot implementations"

Source: https://fsi.stanford.edu/content/social-media-councils-concept-reality-conference-report ; https://cmpf.eui.eu/the-social-media-councils-bringing-content-moderation-back-to-the-public-forum/ ; https://www.businesspost.ie/business/plans-for-worlds-first-social-media-council-in-ireland-d04bb1e9
Source tier: primary
Source content: Stanford report: convened by "Stanford's Global Digital Policy Incubator (GDPi), ARTICLE 19, and David Kaye... February 1-2, 2019"; "does not discuss any pilot implementations... presents a conceptual proposal." CMPF piece: July 3, 2019, by Pierre François Docquir, "Head of Media Freedom at ARTICLE 19"; "conceptual analysis, not documentation of actual implementations." Business Post: "plans to run a pilot project in Ireland" — one jurisdiction, plan-stage.
Comparison: scalar:outcomes. Contradicted on all three legs: the Stanford engagement was the Global Digital Policy Incubator (not the Internet Observatory), in 2019 (not "by 2023"), and conceptual (no pilots); the CMPF piece is 2019 conceptual analysis authored by A19's own staff; the only located pilot is Ireland, at plan/first-steps stage, a single jurisdiction. No canonical source documents "active piloting across multiple jurisdictions." Requires prose-judgment rewrite, not single-token swap — Editor should flag to Researcher.
Decision: correction

## Claim 17: body §Governance — "Stanford's Internet Observatory, the Centre for International Governance Innovation (CIGI), and the EU's Centre for Media Pluralism and Media Freedom all documented active pilot implementations by 2023"

Source: same as Claim 16
Source tier: primary
Source content: See Claim 16. Additionally CIGI's SMC articles (cigionline.org, 2019, also Docquir-authored) are conceptual advocacy for the model, not pilot documentation.
Comparison: Same contradiction as Claim 16 in the body's own words: wrong Stanford unit ("Internet Observatory" → Global Digital Policy Incubator), wrong period (2019 engagements, not "by 2023"), wrong characterization ("documented active pilot implementations" → conceptual analyses of the proposal; two of the three authored or co-convened by ARTICLE 19 itself, so they are also not independent uptake evidence). The following sentence's "traction" framing inherits the defect. Prose-judgment fix.
Decision: correction

## Claim 18: Social Media 4 Peace — January 2021 to December 2023, EU-funded UNESCO partnership, pilots in Bosnia and Herzegovina, Colombia, Indonesia, Kenya; ARTICLE 19 primary research partner (body + scalar:sources[9].note)

Source: https://www.unesco.org/en/articles/social-media-4-peace
Source tier: primary
Source content: "January 2021 - December 2023", "supported by the European Union", pilots in "Bosnia and Herzegovina, Colombia, Indonesia, and Kenya"; "UNESCO partnered with ARTICLE 19 to conduct research on content moderation practices."
Comparison: Timeline, funder, four countries, and A19's research role all match UNESCO's project page. "Primary research partner" is a fair rendering of UNESCO's description.
Decision: primary-sourced

## Claim 19: Three national coalitions on Freedom of Expression and Content Moderation established — Bosnia and Herzegovina, Indonesia, Kenya (body + scalar:outcomes)

Source: https://www.unesco.org/en/articles/social-media-4-peace
Source tier: primary
Source content: "UNESCO and ARTICLE 19 jointly supported multistakeholder coalitions focused on 'Freedom of Expression and Content Moderation' in three nations: Bosnia and Herzegovina, Indonesia, and Kenya."
Comparison: Countries and coalition naming match exactly.
Decision: primary-sourced

## Claim 20: "Bridging the Gap" report June 2022 — platforms fail to account for local context in the three research countries (body + scalar:sources[4].note)

Source: https://www.unesco.org/en/articles/social-media-4-peace
Source tier: primary
Source content: Research reports on online content moderation launched June 18, 2022 across three pilot countries, aiming at "bridg[ing] the gap between tech giants and local communities," with "concrete recommendations" including establishing local coalitions.
Comparison: Publication date (June 2022), gap-framing, three-country scope, and coalition recommendation match; the finer findings language in the entity is consistent with UNESCO's summary though the full report text (article19.org, 403) was not directly comparable.
Decision: primary-sourced

## Claim 21: body §Ground-level — ARTICLE 19 cited Facebook's role in Rohingya genocide incitement in Myanmar as the paradigmatic case in the research design

Source: no canonical source found (report full text unreachable — article19.org 403)
Source tier: none
Source content: Neither UNESCO's project page nor reachable coverage mentions the Myanmar/Rohingya framing of the SM4P research design.
Comparison: Specific attribution (what A19 cited, and its role in the research design) cannot be compared against reachable sources.
Decision: uncorroborated

## Claim 22: SM4P handbook published August 2023; "measures addressing problematic content must align with international norms and human rights" (body + scalar:sources[6].note)

Source: https://dig.watch/updates/article-19-launches-the-social-media-4-peace-handbook
Source tier: mainstream
Source content: "ARTICLE 19 released the handbook on August 24, 2023, as part of the UNESCO Social Media for Peace initiative." Quote confirmed: "Measures addressing problematic content must align with international norms and human rights."
Comparison: Date, publisher, UNESCO partnership, and quote all match; rests on the single dig.watch item (specialist outlet, in-beat).
Decision: single-source

## Claim 23: February 2021 submission to UN Special Rapporteur on disinformation — demands full transparency of AI moderation procedures, disclosure of government engagement on content decisions, avoidance of government-pressure over-removal (body + scalar:sources[5].note)

Source: https://www.ohchr.org/sites/default/files/Documents/Issues/Expression/disinformation/2-Civil-society-organisations/ARTICLE19.pdf
Source tier: primary
Source content: Submission (posted February 12, 2021; A19 PDF dated 2021/02) "calls for disclosure of automated moderation systems and their decision-making criteria... requires platforms reveal when governments request content removal or influence moderation decisions... preventing governmental pressure from causing excessive censorship."
Comparison: Date and all three named demands confirmed against the submission document itself (OHCHR-hosted copy).
Decision: primary-sourced

## Claim 24: March 2024 joint EFF/ARTICLE 19 submission to the EU Commission on platform guidelines for disinformation and elections — transparency and human-rights compliance over liability expansion (body + scalar:sources[7].note)

Source: https://www.eff.org/deeplinks/2024/03/disinformation-and-elections-eff-and-article-19-submit-key-recommendations-eu
Source tier: primary
Source content: March 21, 2024 submission to the EU Commission on disinformation/election-integrity guidelines; compliance evaluations should "focus primarily on ensuring respect for fundamental rights"; DSA risk assessments should maintain human-rights protections.
Comparison: Date, parties, addressee, topic, and position all match EFF's own account.
Decision: primary-sourced

## Claim 25: the quoted phrase — guidelines must "prioritise best practices over policing speech" (body + scalar:sources[7].note)

Source: https://www.eff.org/deeplinks/2024/03/disinformation-and-elections-eff-and-article-19-submit-key-recommendations-eu
Source tier: primary
Source content: EFF's page renders the position as "guidelines prioritize best practices, instead of policing speech."
Comparison: Substance identical; the entity's quotation-marked wording ("over policing speech") differs from the fetched rendering (", instead of policing speech"), and fetch summarization prevents establishing the verbatim source text. Too paraphrastic to compare as an exact quote; no error asserted.
Decision: uncorroborated

## Claim 26: Impact Report 2024 — all 193 UN Member States adopted a human-rights-based approach to AI in 2024; nearly 5,000 defenders equipped; over 175 million people's information rights advanced (body + scalar:outcomes + scalar:sources[8].note)

Source: https://stories.article19.org/impact-report-2024/
Source tier: primary
Source content: "All 193 UN Member States adopted our position on a human rights-based approach to AI." / "Nearly 5,000 journalists, activists, and human rights defenders are better equipped..." / "Our advocacy advanced the right to know for over 175 million people."
Comparison: All three figures match verbatim. Entity correctly attributes the claim to the Impact Report rather than asserting it independently.
Decision: primary-sourced

## Claim 27: body §UN — the pathway was sustained engagement with the UN Secretary-General's AI Advisory Body and the parallel UNESCO AI ethics civil-society network

Source: no canonical source found
Source tier: none
Source content: The Impact Report page (as fetched) and reachable coverage do not name the SG's AI Advisory Body or a UNESCO AI-ethics network as the mechanism.
Comparison: Specific causal-pathway attribution not comparable against reachable sources.
Decision: uncorroborated

## Claim 28: body §Significance — ARTICLE 19's partner network of nearly a hundred civil-society organisations across sixty-plus countries

Source: https://www.article19.org/about-us/ (via search; direct fetch 403)
Source tier: primary
Source content: ARTICLE 19 works "with 100 organizations in more than 60 countries."
Comparison: "Nearly a hundred... sixty-plus countries" matches A19's own self-description.
Decision: primary-sourced

## Claim 29: body §DSA — ARTICLE 19 subsequently identified remaining DSA gaps, including the absence of mandatory human review requirements

Source: https://www.article19.org/resources/does-the-digital-services-act-protect-freedom-of-expression/ (existence confirmed via search; content unreachable — 403)
Source tier: none
Source content: The cited A19 assessment page exists; its content (whether it names mandatory human review as the gap) could not be retrieved.
Comparison: Existence of the follow-up assessment confirmed; the specific gap attribution cannot be compared.
Decision: uncorroborated

## Claim 30: scalar:end_date = ongoing (campaign active through present)

Source: https://stories.article19.org/impact-report-2024/ ; https://www.eff.org/deeplinks/2024/03/...
Source tier: primary
Source content: Campaign-track activity documented through the 2024 reporting period (March 2024 submission; 2024 Impact Report AI results).
Comparison: Sustained activity through 2024 confirmed with no evidence of conclusion; no reachable source affirms continuation into 2025–2026, so "ongoing" rests on absence-of-termination rather than positive confirmation. No error asserted.
Decision: uncorroborated
