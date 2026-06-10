---
entity_id: camp-africtivistes-ai-elections-disinformation-west-africa-2023-ongoing
entity_hash: 476d573fc767352d71a813fc97e27bb58ae630cf
audit_date: 2026-06-10
pass: 2
status: discrepancy
claims_total: 47
claims_verified: 35
claims_discrepancy: 4
claims_unverifiable: 8
sources_consulted:
  - https://africtivistes.net/en/strengthening-senegalese-democracy-through-digital-innovation-and-the-quality-of-information/
  - https://cipesa.org/2024/02/senegal-elections-cipesa-and-africtivistes-engage-key-stakeholders-on-content-moderation/
  - https://africtivistes.com/en/ahead-africa-launch-focuses-on-citizen-engagement-for-electoral-transparency-and-integrity/
  - https://africtivistes.com/en/africtivistes-gives-a-new-boost-to-citizen-participation-in-electoral-processes-in-africa
  - https://africtivistes.com/en/africtivistes-and-amld-join-forces-to-counter-electoral-disinformation-in-senegal/
  - https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
  - https://africtivistes.com/en/africtivistes-launches-the-african-election-civic-tech-fund/
  - https://africtivistes.com/en/farafina-tech-an-african-database-advancing-electoral-integrity/
  - https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/
  - https://www.idea.int/news/combatting-election-related-foreign-information-manipulation-and-interference-senegal
  - https://soobu.tech/about/
  - https://africtivistes.com/en/africtivistes-honours-sud-fm-radio-at-information-and-democracy-seminar/
  - https://ahead.africa/en/
---

Pass-2 note: the pass-1 discrepancy (AHEAD acronym expansion) was corrected by the Editor (commit 0babc0fb) and now verifies. Three pass-1 unverifiables resolve to verified this pass (three-year duration; Soobu Wolof etymology; the Media & Democracy Prize, confirmed via a supplementary AfricTivistes primary source). New findings this pass: the Nairobi soft-launch date and the outcomes scalar's project-country count are discrepancies; pass 1's verification of the Feb 27 date and the "three AI-focused projects" attribution did not hold up against closer source reads.

## Claim 1: "the October 24–25, 2023 Seminar on Information and Democracy in Dakar"

Source: https://africtivistes.net/en/strengthening-senegalese-democracy-through-digital-innovation-and-the-quality-of-information/
Source content: "24-25 October 2023 in Dakar, Senegal"
Comparison: Dates and location match exactly.
Decision: verified

## Claim 2: "convened by AfricTivistes in partnership with Article 19, the Forum on Information and Democracy, Reporters Without Borders (RSF), Internet Without Borders, Amnesty International, Y'en a Marre, Raddho, and Jonction"

Source: https://africtivistes.net/en/strengthening-senegalese-democracy-through-digital-innovation-and-the-quality-of-information/
Source content: "Forum on Information and Democracy, Raddho, Article 19, Jonction, Reporters Without Borders (RSF)"; targeted re-read also surfaced "Emmanuel Diokh, President of Internet Without borders", "El Hadj Abdoulaye Seck of Amnesty International", "Abdou Khafor Kandji of Y EN A MARRE"
Comparison: All eight named partners now explicitly confirmed in the cited source (pass 1 had confirmed seven of eight, with Y'en a Marre unsurfaced).
Decision: verified

## Claim 3: "addressed ... misinformation prevention, the regulation of fake news, and the protection of human rights and freedom of expression online"

Source: https://africtivistes.net/en/strengthening-senegalese-democracy-through-digital-innovation-and-the-quality-of-information/
Source content: "the fight against misinformation" ... "the regulation of fake news systems" ... "the protection of human rights online" ... "freedom of expression and access to information"
Comparison: All themes match within paraphrase tolerance.
Decision: verified

## Claim 4: "The AfricTivistes Media & Democracy Prize was awarded at the event"

Source: https://africtivistes.com/en/africtivistes-honours-sud-fm-radio-at-information-and-democracy-seminar/
Source content: The seminar "culminated in the presentation of the AfricTivistes Media & Democracy Prize to Sud FM" — awarded at the October 24–25, 2023 Seminar on Information and Democracy in Dakar, with PressAfrik in second place.
Comparison: Pass 1 marked this unverifiable (the entity's cited source contains no prize mention). A dedicated AfricTivistes primary source located this session confirms the prize was awarded at this event. Body claim verified.
Decision: verified

## Claim 5: scalar:sources[0].note "the award of the AfricTivistes Media & Democracy Prize"

Source: https://africtivistes.net/en/strengthening-senegalese-democracy-through-digital-innovation-and-the-quality-of-information/
Source content: "No mention of any prize, award, 'Prix,' or ceremony appears in this content" (targeted verbatim search of the cited page; consistent across pass-1 and two pass-2 fetches)
Comparison: The sources[0].note asserts its URL is "primary source for ... the award of the AfricTivistes Media & Democracy Prize"; the cited page contains no prize mention. The fact itself is true (see Claim 4) but is documented at https://africtivistes.com/en/africtivistes-honours-sud-fm-radio-at-information-and-democracy-seminar/, not at the cited URL. Fix location: sources[0].note — drop the prize element or add the honours-Sud-FM URL as a source.
Decision: discrepancy

## Claim 6: "AHEAD Africa (Action for a Holistic Electoral Approach towards Democracy)"

Source: https://africtivistes.com/en/africtivistes-gives-a-new-boost-to-citizen-participation-in-electoral-processes-in-africa
Source content: "the Action for a Holistic Electoral Approach towards Democracy (AHEAD Africa) project"
Comparison: Pass-1 discrepancy (body then read "Advancing Democracy through Electoral Advocacy and Citizen Engagement") corrected by Editor backfill; body now matches the source's expansion exactly.
Decision: verified

## Claim 7: "a three-year consortium project co-funded by the European Union"

Source: https://africtivistes.com/en/africtivistes-gives-a-new-boost-to-citizen-participation-in-electoral-processes-in-africa
Source content: "This three-year project (2024-2027)"; formal-launch article: "pan-African project co-funded by the European Union"
Comparison: Pass 1 marked the duration unverifiable; a closer read of the soft-launch article confirms "three-year project (2024-2027)". EU co-funding confirmed in the formal-launch article. Both elements verified.
Decision: verified

## Claim 8: "AfricTivistes leads the initiative alongside Democracy Reporting International (DRI), the European Partnership for Democracy (EPD), the African Election Observation Network (AfEONET), the Electoral Support Network for Southern Africa (ESN-SA), the East and Horn of Africa Election Observer Network (E-HORN), and the West African Election Observer Network (WAEON)"

Source: https://africtivistes.com/en/ahead-africa-launch-focuses-on-citizen-engagement-for-electoral-transparency-and-integrity/
Source content: "AfricTivistes, Democracy Reporting International (DRI), the European Partnership for Democracy (EPD), the African Election Observation Network (AfEONET), Electoral support network for Southern Africa (ESN-SA), the East and Horn of Africa Electoral Observers Network (E-HORN), and the West African Electoral Observers Network (WAEON)"
Comparison: Full consortium list matches; minor naming variants are paraphrase-tolerable.
Decision: verified

## Claim 9: "softly launched on February 27, 2024 in Nairobi"

Source: https://africtivistes.com/en/africtivistes-gives-a-new-boost-to-citizen-participation-in-electoral-processes-in-africa
Source content: Article dateline "27 février 2024"; body text: "the Action for a Holistic Electoral Approach towards Democracy (AHEAD Africa) project was launched last Wednesday in Nairobi, Kenya" — "February 27, 2024 appears at the top of the article as the publication dateline, not as a reference to when the project launched"
Comparison: The body takes the article's publication date as the event date. February 27, 2024 was a Tuesday; the source places the launch "last Wednesday" — i.e. February 21, 2024. Pass 1's verification of this date did not hold up against the dateline/event distinction. Nairobi location and February 2024 month are correct; the specific day is contradicted by the cited source. Fix location: body § AHEAD Africa (and see Claim 10 for the matching scalar). The outcomes scalar's looser "launch of the AHEAD Africa programme in February 2024 (Nairobi soft launch)" is unaffected.
Decision: discrepancy

## Claim 10: scalar:sources[3].note "the February 27, 2024 AHEAD Africa soft launch in Nairobi"

Source: https://africtivistes.com/en/africtivistes-gives-a-new-boost-to-citizen-participation-in-electoral-processes-in-africa
Source content: "the ... project was launched last Wednesday in Nairobi, Kenya" (article dated 27 février 2024)
Comparison: Same dateline-vs-event-date error as Claim 9, surfaced at the scalar. Fix location: sources[3].note.
Decision: discrepancy

## Claim 11: "formally launched on July 20, 2024 in Accra, Ghana"

Source: https://africtivistes.com/en/ahead-africa-launch-focuses-on-citizen-engagement-for-electoral-transparency-and-integrity/
Source content: "Saturday, July 20, 2024, in Accra, Ghana"
Comparison: Date and location match.
Decision: verified

## Claim 12: "The programme's operational innovation laboratory encompasses five components: Soobu (Tech4Elections) ...; Farafina, an online elections information hub; the AfEONET network supporting electoral situation rooms; a Massive Open Online Course on African electoral processes; and a grant mechanism for civic-tech projects"

Source: https://africtivistes.com/en/africtivistes-gives-a-new-boost-to-citizen-participation-in-electoral-processes-in-africa
Source content: Soft-launch article lists "Online one-stop shop", "Mobile School", "Mapping of citizen observation initiatives", "Africa ElectionLab Centre", "Grant and technical support mechanism for citizens' electoral observation initiatives"; formal-launch article lists "an online one-stop shop, a mobile learning programme, a mapping of citizen observation initiatives, a grant mechanism, and a hackathon". Neither names Soobu, Tech4Elections, Farafina, AfEONET situation rooms, or a MOOC.
Comparison: Both cited sources confirm a five-component innovation laboratory, and Soobu (mapping) and Farafina (elections one-stop platform) are independently real AHEAD-linked tools (soobu.tech; Farafina launch article). But the entity's specific component-to-name mapping — especially "the AfEONET network supporting electoral situation rooms" and the MOOC as lab components — does not appear in the cited sources, whose own lists differ from each other (the formal-launch list includes "a hackathon"). Not contradicted, not confirmable at this specificity.
Decision: unverifiable

## Claim 13: "Soobu (Tech4Elections), a digital-mapping tool cataloguing citizen observation and civic-tech initiatives across the continent since 2010 (the name derives from the Wolof word for 'commitment, mobilisation')"

Source: https://soobu.tech/about/
Source content: "The word 'sóobu', from the Wolof language spoken in West Africa, means 'commitment, mobilisation'." The platform, formally "Sóobu AfricTivistes, Tech4Elections", catalogs "citizen election initiatives throughout the electoral cycle" identified "since 2010", deployed by AfricTivistes within the AHEAD Africa project.
Comparison: Pass 1 marked the Wolof etymology unverifiable; the initiative's own site (primary document) confirms the etymology, the Tech4Elections name, the mapping function, and the since-2010 scope.
Decision: verified

## Claim 14: scalar:sources[2].note "the five-component innovation laboratory (Soobu/Tech4Elections civic-tech mapping tool, Farafina elections platform, AfEONET situation rooms, MOOC on electoral processes, and civic-tech grant mechanism)"

Source: https://africtivistes.com/en/ahead-africa-launch-focuses-on-citizen-engagement-for-electoral-transparency-and-integrity/
Source content: "an online one-stop shop, a mobile learning programme, a mapping of citizen observation initiatives, a grant mechanism, and a hackathon" — "does not reference the specific tools named (Soobu/Tech4Elections, Farafina, MOOC, etc.)"
Comparison: The note asserts the cited formal-launch article documents the five components under the entity's tool names; the article describes the components generically and its list differs (includes a hackathon, no AfEONET situation rooms). Same basis as Claim 12; the named mapping is the researcher's synthesis, not the cited page's content. Fix location: sources[2].note (if the Editor acts; as a note-overstatement without a contradicted underlying fact, unverifiable is the honest outcome).
Decision: unverifiable

## Claim 15: "its explicit objective of 'combating misinformation and fake news'"

Source: https://africtivistes.com/en/ahead-africa-launch-focuses-on-citizen-engagement-for-electoral-transparency-and-integrity/
Source content: "combating misinformation and fake news"
Comparison: Exact phrase appears in the cited source.
Decision: verified

## Claim 16: "Senegal's government postponed the presidential election scheduled for February 25 — an unprecedented constitutional move that triggered protests and two mobile internet shutdowns"

Source: https://cipesa.org/2024/02/senegal-elections-cipesa-and-africtivistes-engage-key-stakeholders-on-content-moderation/
Source content: Government blocked mobile internet on "February 5, 2024: as parliament debated the extension of President Macky Sall's tenure" and "February 13, 2024: amidst civil society-led protests"; election postponement and escalating political tensions confirmed.
Comparison: Postponement, protests, and two mobile internet shutdowns all confirmed.
Decision: verified

## Claim 17: "co-organising with CIPESA a February 8, 2024 workshop on platform accountability and content moderation in Dakar, bringing together 25 journalists, influencers, human-rights defenders, and civil-society representatives"

Source: https://cipesa.org/2024/02/senegal-elections-cipesa-and-africtivistes-engage-key-stakeholders-on-content-moderation/
Source content: "February 8, 2024, in Dakar, Senegal"; "25 participants" comprising "journalists, social media influencers, human rights defenders and staff of civil society organisations"
Comparison: Date, location, count, and participant categories match.
Decision: verified

## Claim 18: "Case studies from Nigeria and Uganda illustrated how platform content moderation disproportionately affected African-language and political content"

Source: https://cipesa.org/2024/02/senegal-elections-cipesa-and-africtivistes-engage-key-stakeholders-on-content-moderation/
Source content: Nigeria 2021: "President Buhari banned Twitter after the platform deleted his tweet"; Uganda 2021: "Facebook and Twitter suspended pro-government accounts for 'Coordinated Inauthentic Behaviour'" and Museveni blocked social media.
Comparison: Nigeria and Uganda case studies confirmed as workshop content on platform-accountability challenges; the body's gloss is within paraphrase tolerance.
Decision: verified

## Claim 19: "Recommendations addressed platform transparency, multilingual terms of use, and user recourse mechanisms"

Source: https://cipesa.org/2024/02/senegal-elections-cipesa-and-africtivistes-engage-key-stakeholders-on-content-moderation/
Source content: Platforms should "ensure their terms of use are available in multiple languages", "increase transparency in their content moderation processes", and "promote awareness and understanding among African users of recourse mechanisms"
Comparison: All three recommendation areas match.
Decision: verified

## Claim 20: "In October 2024, AfricTivistes co-organised with the Alliance for Migration, Leadership, and Development (AMLD) a two-day Dakar workshop on Disinformation in Pre-, During, and Post-Electoral Periods"

Source: https://africtivistes.com/en/africtivistes-and-amld-join-forces-to-counter-electoral-disinformation-in-senegal/
Source content: "30 and 31 October 2024 in Dakar, Senegal"; "Alliance for Migration, Leadership, and Development (AMLD)"
Comparison: Dates (two days, Oct 30–31, 2024), location, partner full name and acronym all match.
Decision: verified

## Claim 21: "gathering 100 participants — predominantly women and young people from political circles, civil society, and the media"

Source: https://africtivistes.com/en/africtivistes-and-amld-join-forces-to-counter-electoral-disinformation-in-senegal/
Source content: "100 participants ... mainly women and young people from political circles, civil society, and the media"
Comparison: Count and categories match.
Decision: verified

## Claim 22: "structured training on 'the role of artificial intelligence and emotional intelligence in politics'"

Source: https://africtivistes.com/en/africtivistes-and-amld-join-forces-to-counter-electoral-disinformation-in-senegal/
Source content: "the role of artificial intelligence and emotional intelligence in politics" (listed as covered topic)
Comparison: Quoted phrase appears in the cited source as a workshop topic.
Decision: verified

## Claim 23: "The workshop covered ... the legal frameworks governing electoral information in Senegal, and the categorical distinctions between the forms of disinformation that circulate during election periods"

Source: https://africtivistes.com/en/africtivistes-and-amld-join-forces-to-counter-electoral-disinformation-in-senegal/
Source content: "the legal and legislative framework governing fake news" ("Article 255 of the Penal Code penalise[s] the dissemination of fake news"); "the distinction between disinformation, rumours, and fake news"
Comparison: Legal-framework and categorical-distinction content both confirmed.
Decision: verified

## Claim 24: "The workshop covered AI's potential to amplify disinformation at scale"

Source: https://africtivistes.com/en/africtivistes-and-amld-join-forces-to-counter-electoral-disinformation-in-senegal/
Source content: "The article does not address AI amplifying disinformation as a distinct topic" — the AI content surfaced is the topic listing "the role of artificial intelligence and emotional intelligence in politics"
Comparison: The amplification-at-scale specific is an elaboration beyond what the cited source states; not contradicted (an AI module existed) but not confirmable at this specificity.
Decision: unverifiable

## Claim 25: "In April 2025, AfricTivistes and DRI published a joint study assessing the reliability of five major AI chatbots — Copilot, Gemini, ChatGPT-4o, ChatGPT-4omini, and Claude"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
Source content: Publication date "22 avril 2025"; chatbots tested: "Copilot, Gemini, ChatGPT-4o, ChatGPT-4omini, and Claude"
Comparison: Month and full chatbot list match.
Decision: verified

## Claim 26: "testing them on the Senegalese legislative elections of November 17, 2024"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
Source content: "Senegalese legislative elections on 17 November 2024"
Comparison: Date and election type match.
Decision: verified

## Claim 27: "Researchers posed questions in both Wolof and French, evaluating accuracy, consistency, and completeness against official sources"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
Source content: Languages "Wolof and French"; "Accuracy: Verification of the correspondence of information with official and reliable sources. Consistency: Evaluation of the uniformity of responses and the absence of contradictions. Completeness: Ability to provide detailed and relevant answers."
Comparison: Languages and all three evaluation criteria match.
Decision: verified

## Claim 28: "The study found that no chatbot could be considered a reliable source of electoral information: none could integrate real-time political developments"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
Source content: "The tested chatbots cannot be considered entirely reliable sources of electoral information"; "A common point among all these tools is their inability to integrate real-time updates of the Senegalese political context"
Comparison: Both elements match within paraphrase tolerance.
Decision: verified

## Claim 29: "several generated 'incorrect information with a high degree of confidence'"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
Source content: "some chatbots generate erroneous responses with a high degree of confidence, which can mislead users" (verbatim search for "incorrect information with a high degree of confidence": NOT FOUND)
Comparison: Semantic content matches exactly; the body's quoted form differs from the cited page's English rendering ("incorrect information" vs "erroneous responses") — likely translation variance, as the article is published from a French original. Within paraphrase tolerance on semantic content per the decision rules, but the quotation marks overstate verbatimness; flagged for awareness, not actionable as a contradiction.
Decision: verified

## Claim 30: "posing, in the study's assessment, 'a serious risk of disinformation, especially during electoral periods'"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
Source content: Verbatim search for "a serious risk of disinformation, especially during electoral periods": NOT FOUND. Nearest content: "The risk of misinformation induced by the use of chatbots during election periods" highlighted as a challenge.
Comparison: The quoted string does not appear in the cited source. It may appear in the underlying study document itself, which could not be located this session (searches of DRI/AfricTivistes surfaced no study text carrying it). Quoted attribution unconfirmable.
Decision: unverifiable

## Claim 31: "ChatGPT-4o and Claude performed best within the tested group; ChatGPT-4omini produced the highest error rates"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
Source content: "ChatGPT-4o and Claude" showed "relatively accurate responses, although limited to general information"; ChatGPT-4omini showed "the weakest performance, with a higher error rate"
Comparison: Performance rankings match.
Decision: verified

## Claim 32: "should 'systematically verify information obtained through these tools by cross-referencing it with recognised official and journalistic sources'"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
Source content: "Systematically verify the information obtained through these tools by cross-referencing it with recognised official and journalistic sources."
Comparison: Quote matches the cited source.
Decision: verified

## Claim 33: "June 26, 2025 launch of Farafina.tech in Dakar — described as 'the continent's first online one-stop platform dedicated to elections and electoral processes' ... (the name means 'Africa' in Mandinka)"

Source: https://africtivistes.com/en/farafina-tech-an-african-database-advancing-electoral-integrity/
Source content: "Farafina.tech was launched on June 26, 2025, in Dakar"; "the continent's first online one-stop platform dedicated to elections and electoral processes"; "Farafina means 'Africa' in the Mandinka language"
Comparison: Date, location, description quote, and etymology all match.
Decision: verified

## Claim 34: "The platform catalogues demographic data, aggregates electoral-system information, and monitors the legal frameworks governing elections across African countries"

Source: https://africtivistes.com/en/farafina-tech-an-african-database-advancing-electoral-integrity/
Source content: "The platform organizes demographic information, aggregates details on electoral systems, and tracks legal electoral frameworks throughout African nations."
Comparison: All three functions match.
Decision: verified

## Claim 35: "the EUR 175,000 African Election Civic Tech Fund, launched June 13, 2025, co-funded through the EU AHEAD Africa project in partnership with the Digital Democracy Initiative"

Source: https://africtivistes.com/en/africtivistes-launches-the-african-election-civic-tech-fund/
Source content: "13 juin 2025"; "€175,000 Innovation Fund for Citizen Participation in Electoral Processes in Africa"; "This initiative is part of the EU co-funded AHEAD Africa project"; "The Election Civic Tech Fund is powered by The Digital Democracy Initiative"
Comparison: Amount, date, EU/AHEAD co-funding, and DDI partnership all match.
Decision: verified

## Claim 36: "The fund supports civic-technology initiatives across 14 African countries: Somalia, Ethiopia, Sudan, South Sudan, Senegal, Benin, Burkina Faso, Guinea, Chad, Cameroon, Mauritania, Niger, Mali, and Togo"

Source: https://africtivistes.com/en/africtivistes-launches-the-african-election-civic-tech-fund/
Source content: "Somalia, Ethiopia, Sudan, South Sudan, Senegal, Benin, Burkina Faso, Guinea, Chad, Cameroon, Mauritania, Niger, Mali, and Togo"
Comparison: Country count and full list match exactly.
Decision: verified

## Claim 37: "Individual grants range from EUR 10,000 to EUR 25,000, with priority given to women-led organisations and youth groups (ages 18–35)"

Source: https://africtivistes.com/en/africtivistes-launches-the-african-election-civic-tech-fund/
Source content: "Grants ranging from €10,000 to €25,000"; "organized groups of young people (aged 18–35), including associations and registered start-ups. Priority will be given to initiatives led by women"
Comparison: Grant range, age band, and priority groups match.
Decision: verified

## Claim 38: "On December 18, 2025, AfricTivistes announced the selection of 12 projects"

Source: https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/
Source content: Announcement date December 18, 2025; 12 projects selected, listed by name and implementing organization.
Comparison: Date and project count match.
Decision: verified

## Claim 39: "including three with an explicit AI focus: MyAIFactChecker Cameroon (Brain Builders Youth Development Initiative — AI-based fact-checking), Vigilant Civic Voice (Association des blogueurs du Bénin — political misinformation monitoring), and Electoral Fact-Checking Initiative South Sudan (Excellence Foundation for South Sudan)"

Source: https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/
Source content: "The article does not provide individual descriptions for any of these three projects. It only lists them by name and implementing organization ... The article does not specify how many projects use artificial intelligence, nor does it describe any of the three projects you mentioned as AI-based. The only AI reference appears in one project title: 'MyAIFactChecker Cameroon.'"
Comparison: The three project names and implementing organizations match the source. But the "explicit AI focus" attribution and the per-project descriptions ("AI-based fact-checking", "political misinformation monitoring") are not in the cited source — only MyAIFactChecker's title signals AI. Not contradicted (the projects may have AI components per other materials), not confirmable from the cited source. Pass 1's verified on this claim did not hold up at this specificity.
Decision: unverifiable

## Claim 40: "Projected aggregate impact across the 12 projects: 15+ digital platforms, 300+ fact-checking items, 1,500+ trained individuals, and 500,000+ citizens mobilised for electoral transparency"

Source: https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/
Source content: "more than 15 digital platforms and tools"; "the production of more than 300 fact-checking items"; "the training of over 1,500 young people, journalists, citizen observers and community leaders"; "the direct mobilisation of more than 500,000 citizens"
Comparison: All four impact figures match.
Decision: verified

## Claim 41: "On October 2, 2025, AfricTivistes presented in Dakar the first national analytical report on Foreign Information Manipulation and Interference in Senegal, produced with International IDEA (applying its global FIMI methodology) and supported by Global Affairs Canada"

Source: https://www.idea.int/news/combatting-election-related-foreign-information-manipulation-and-interference-senegal
Source content: "October 2, 2025, in Dakar"; AfricTivistes produced the report using International IDEA's methodology; "Supported by Global Affairs Canada, this was the first in a series of four national consultations held under the project"; "the first national study launched within its multi-country framework"
Comparison: Date, location, producers, methodology, supporter, and first-report status all match.
Decision: verified

## Claim 42: "The multi-stakeholder event convened policymakers, diplomats, journalists, researchers, the Canadian Embassy, the European External Action Service, Ministries of Communication from Senegal and Côte d'Ivoire, and Code for Africa"

Source: https://www.idea.int/news/combatting-election-related-foreign-information-manipulation-and-interference-senegal
Source content: "policymakers, diplomats, journalists, and researchers" plus representatives of the European External Action Service, Canadian Embassy, Ministries of Communication of Senegal and Côte d'Ivoire, Code for Africa, and International IDEA
Comparison: Full attendee list matches.
Decision: verified

## Claim 43: "The Senegal report is the first in a planned series of four national consultations; subsequent editions target Côte d'Ivoire, North Macedonia, and Moldova"

Source: https://www.idea.int/news/combatting-election-related-foreign-information-manipulation-and-interference-senegal
Source content: "the first in a series of four national consultations"; "In the months ahead, similar consultations will be held in Côte d'Ivoire, North Macedonia, and Moldova"
Comparison: Series count and subsequent countries match.
Decision: verified

## Claim 44: scalar:outcomes "the December 18, 2025 selection of 12 civic-tech projects (including three AI-based fact-checking tools) across 12 countries" — the "three AI-based fact-checking tools" element

Source: https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/
Source content: "The article does not specify how many projects use artificial intelligence, nor does it describe any of the three projects you mentioned as AI-based. The only AI reference appears in one project title: 'MyAIFactChecker Cameroon.'"
Comparison: Same evidence as Claim 39, surfaced at the outcomes scalar. "Three AI-based fact-checking tools" is not supported by the cited source; only one project title signals AI. Fix location if acted on: scalar:outcomes.
Decision: unverifiable

## Claim 45: scalar:sources[8].note "primary source for the AI-focused grantees (MyAIFactChecker Cameroon ...; Vigilant Civic Voice ...; Electoral Fact-Checking Initiative South Sudan ...)"

Source: https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/
Source content: The article "only lists them by name and implementing organization" without describing any as AI-focused.
Comparison: The note's "AI-focused grantees" characterization is the researcher's gloss, not the cited page's content; names and orgs themselves are confirmed (Claim 39). Fix location: sources[8].note.
Decision: unverifiable

## Claim 46: scalar:outcomes "the December 18, 2025 selection of 12 civic-tech projects ... across 12 countries"

Source: https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/
Source content: "these initiatives—led by young people aged 18 to 35—embody excellence in electoral civic innovation across the 14 countries covered by the fund: Somalia, Ethiopia, Sudan, South Sudan, Senegal, Benin, Burkina Faso, Guinea, Chad, Cameroon, Mauritania, Niger, Mali and Togo."
Comparison: The outcomes scalar says the 12 projects span "12 countries"; the cited source says the initiatives span "the 14 countries covered by the fund". Specific and citable contradiction. Fix location: scalar:outcomes — "across 12 countries" → "across the 14 countries covered by the fund".
Decision: discrepancy

## Claim 47: scalar:outcomes "As of mid-2026 the campaign had not produced binding platform-policy or regulatory changes directly attributable to its advocacy"

Source: no canonical source found
Source content: No source consulted addresses the presence or absence of binding policy/regulatory changes attributable to this campaign.
Comparison: A negative causal-attribution claim; no canonical source exists for this class of claim, and proving the absence is judgment-loaded by construction.
Decision: unverifiable
