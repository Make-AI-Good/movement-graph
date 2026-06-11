---
entity_id: person-cheikh-fall
entity_hash: afcaaa88a90f615fb319be0de09f5bab4771490a
audit_date: 2026-06-07
pass: 1
status: supported
claims_total: 24
claims_corroborated: 11
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 13
reclassified_at: 2026-06-10
sources_consulted:
  - https://africtivistes.net/en/africtivistes-en/
  - https://africtivistes.com/en/home/
  - https://africtivistes.com/en/speech-by-cheikh-fall-president-of-africtivistes-at-the-opening-of-the-fifafrica-forum-26th-27th-september-2024-dakar-senegal/
  - https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
  - https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
  - https://ici.radio-canada.ca/nouvelle/1094673/cheikh-fall-reve-afrique-africtivistes
  - https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique)
  - http://www.socialnetlink.org/2016/07/consolidation-democratique-en-afrique-par-les-tic-le-web-activiste-senegalais-cheikh-fall-honore
---

## Claim 1: "co-founder and President since 2015" of AfricTivistes (also scalar:affiliations[0].role/period)

Source: https://africtivistes.com/en/speech-by-cheikh-fall-president-of-africtivistes-at-the-opening-of-the-fifafrica-forum-26th-27th-september-2024-dakar-senegal/ (primary, cross-checked against the boell.de 2021 secondary that places him as a founder at the November 2015 Dakar summit)
Source content: AfricTivistes 2024 page header — "Speech by Cheikh Fall, President of AfricTivistes, at the opening of the FIFAfrica Forum, 26th-27th September 2024 – Dakar, Senegal." Boell 2021: "Africtivistes Network … Established at a November 2015 Dakar summit."
Comparison: President role + 2015 origin both confirmed by primary source plus independent secondary. Frontmatter affiliations[0] (`role: co-founder and President`, `period: 2015-`) carries the same content as the body and verifies identically.
Decision: corroborated

## Claim 2: AfricTivistes is "the Dakar-headquartered pan-African civil-society network at the intersection of digital technology and democracy"

Source: https://africtivistes.com/en/home/ and https://africtivistes.net/en/africtivistes-en/ (primary)
Source content: "a pan-African civil society organization that brings together bloggers, cyber-activists and change agents across 45 African countries"; "Founded in 2015 in Dakar."
Comparison: "Dakar-headquartered" and "pan-African civil-society network" both match within paraphrase tolerance. The "intersection of digital technology and democracy" framing is consistent with the org's stated mission of leveraging digital tools for democratic participation.
Decision: corroborated

## Claim 3: "Born Cheikh Fall on 31 August 1981 in Diourbel, Senegal"

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique)
Source content: "Born August 31, 1981, in Diourbel, Senegal."
Comparison: Date and place of birth match exactly. Per AUDITOR.md § Source rule, Wikipedia alone is sufficient for a person's date and place of birth (named-entity definitional fact). MISSION § Auditor's stricter Person rule scopes to affiliation/tenure/quoted statement, not birth facts.
Decision: corroborated

## Claim 4: Dakar-based

Source: https://ici.radio-canada.ca/nouvelle/1094673/cheikh-fall-reve-afrique-africtivistes
Source content: Radio-Canada records the journalist meeting Fall "dans un café Internet de Dakar"; AfricTivistes' own pages place its President in Dakar.
Comparison: Confirmed by multiple primary/secondary sources.
Decision: corroborated

## Claim 5: Bachelor's degree from Université de Picardie Jules-Verne (2008–2012); master's from Université Paris-Est-Marne-la-Vallée (2012–2014)

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique) only
Source content: "Bachelor's degree from Université de Picardie Jules-Verne (2008-2012). Master's degree from Université Paris-Est-Marne-la-Vallée (2012-2014)."
Comparison: Wikipedia matches the body verbatim, but per MISSION § Auditor, a Person body claim about affiliation or tenure (a university enrollment period is tenure-shaped) requires a primary or mainstream-news document beyond Wikipedia. No second canonical source for these degree dates was located in this pass.
Decision: uncorroborated

## Claim 6: Regional Programme Coordinator for the West Africa office of the Agence universitaire de la Francophonie (AUF) from 2006 to 2016

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique) cross-checked against http://www.socialnetlink.org/2016/07/consolidation-democratique-en-afrique-par-les-tic-le-web-activiste-senegalais-cheikh-fall-honore
Source content: Wikipedia — "Coordonnateur régional de programme for AUF's West Africa office (2006-2016)." Socialnetlink 2016 — "Coordonnateur régional du programme de Formations ouverte et à distance à l'Agence universitaire de la Francophonie."
Comparison: AUF role at the West Africa office during the 2006–2016 window confirmed by both. Title differs slightly (Wikipedia's generic "Coordonnateur régional de programme" vs Socialnetlink's specific "Coordonnateur régional du programme de Formations ouverte et à distance") but the body acknowledges the framing variance in the next sentence (Claim 7), so the AUF tenure claim is supported by two canonical sources.
Decision: corroborated

## Claim 7: Socialnetlink described his AUF position as "Coordinator for distance-learning programmes at the Francophone Universities Agency"

Source: http://www.socialnetlink.org/2016/07/consolidation-democratique-en-afrique-par-les-tic-le-web-activiste-senegalais-cheikh-fall-honore
Source content: "Coordonnateur régional du programme de Formations ouverte et à distance à l'Agence universitaire de la Francophonie" — Regional Coordinator of the open and distance-learning programme at AUF.
Comparison: Body's English rendering "Coordinator for distance-learning programmes at the Francophone Universities Agency" is a faithful paraphrase ("Formations ouverte et à distance" → "distance-learning programmes"; "Agence universitaire de la Francophonie" → "Francophone Universities Agency").
Decision: corroborated

## Claim 8: Director of Digital at Groupe Futurs Médias from 2016 to 2017

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique) only
Source content: "Director of digital media at Groupe Futurs Médias (2016-2017)."
Comparison: Wikipedia matches but no second canonical source for this Person-tenure claim was located. Per MISSION § Auditor, Wikipedia alone is insufficient for a Person tenure claim.
Decision: uncorroborated

## Claim 9: 2010 launch of "Citoyen au Sénégal" participatory platform

Source: https://ici.radio-canada.ca/nouvelle/1094673/cheikh-fall-reve-afrique-africtivistes
Source content: "Fall created 'Citoyen au Sénégal,' a web platform, in 2010."
Comparison: Date and platform name match exactly. Radio-Canada is a mainstream secondary source with editorial standards.
Decision: corroborated

## Claim 10: "Senegal's first citizen-journalism web platform"

Source: no canonical source found for this superlative
Source content: Radio-Canada records the platform's 2010 launch but does not claim it was Senegal's first.
Comparison: The "first" superlative is not supported by the entity's cited sources, and no other canonical source confirming this superlative was located in this pass.
Decision: uncorroborated

## Claim 11: #Sunu2012 election-monitoring platform; "Wolof for 'Our 2012'"; February–March 2012 Senegalese presidential election

Source: https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: "'Sunu' translates to 'Our' in Wolof. The platform launched ahead of the 2012 presidential elections." Public-record fact: 2012 Senegalese presidential election ran 26 February (round 1) and 25 March (round 2).
Comparison: "Sunu" = "Our" in Wolof confirmed. "Sunu 2012" as a compound = "Our 2012" is a paraphrase within tolerance. The February–March 2012 election dates are public-record fact (Wikipedia-sufficient per § Source rule for public-event dates).
Decision: corroborated

## Claim 12: "launched from June 2011"

Source: no canonical source found for the specific "June 2011" launch month
Source content: Radio-Canada says "the following year [after 2010], he established another platform dedicated to monitoring the 2012 electoral campaign" — pinning the launch to 2011 but not to June specifically. Boell records the platform "ahead of the 2012 presidential elections" without a launch month.
Comparison: Year (2011) is supported; the "June" specifier is not in any cited source located in this pass.
Decision: uncorroborated

## Claim 13: "equipping hundreds of young Senegalese with mobile phones at polling stations and publishing preliminary results by 9 p.m. on election day"

Source: https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: "Fall's team equipped 'hundreds of young Senegalese with mobile phones' stationed at polling locations to record results. Data was compiled at Dakar headquarters, enabling the group to release preliminary election forecasts by 9 PM on election day."
Comparison: Verbatim match on both the scale ("hundreds") and the 9 p.m. preliminary-results detail.
Decision: corroborated

## Claim 14: "AfricTivistes records as having directly informed President Wade's concession call"

Source: https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: "information that reportedly influenced the outgoing president's concession call."
Comparison: Boell uses "reportedly influenced"; body strengthens to "directly informed" and attributes the framing to AfricTivistes records rather than the journalist. The strengthening from "reportedly" to "directly" and the meta-attribution to AfricTivistes' own records are not supported by the cited Boell article, and no AfricTivistes self-record of this specific framing was fetched in this pass.
Decision: uncorroborated

## Claim 15: "After Sunu2012, Fall was invited across the continent to share the model"

Source: https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: "Following Sunu 2012's success, Fall was invited to multiple African nations where he shared the model."
Comparison: Direct match.
Decision: corroborated

## Claim 16: "the cycle catalysed analogous citizen-monitoring initiatives in Benin (#Vote229), Burkina Faso (#Lwili), and Ghana (#GhanaVote)"

Source: https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share (the body's cited source for this claim)
Source content: "Young activists in Guinea, Mali, Côte d'Ivoire, and other countries replicated the platform under open-source licensing."
Comparison: Boell names Guinea, Mali, and Côte d'Ivoire as the replicator countries, with "and other countries" as a catch-all. The body's specific named countries — Benin (#Vote229), Burkina Faso (#Lwili), Ghana (#GhanaVote) — are not in the cited source. The cited source does not contradict the named countries (they could be part of the catch-all), but it does not support them either. No second canonical source confirming the three named hashtag campaigns was located in this pass.
Decision: uncorroborated

## Claim 17: "after four years of online exchange the West-African cyber-activist cohort convened in Dakar in November 2015 and on 26 November 2015 established AfricTivistes as the standing institutional vehicle with Fall as President and journalist Aïsha Dabo as co-founder and Coordinator"

Source: https://africtivistes.net/en/africtivistes-en/, https://africtivistes.com/en/home/, https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: AfricTivistes — "Founded in 2015 in Dakar"; Boell — "Established at a November 2015 Dakar summit with 150 participants." Neither fetched source names the specific 26 November date; neither names Aïsha Dabo as "co-founder and Coordinator."
Comparison: November 2015 Dakar founding with Fall as President is supported. The exact "26 November 2015" date and Aïsha Dabo's specific co-founder/Coordinator role are not supported by the sources fetched in this pass.
Decision: uncorroborated

## Claim 18: Principal public-facing voice through the 2024 FIFAfrica forum opening (26-27 September 2024, Dakar)

Source: https://africtivistes.com/en/speech-by-cheikh-fall-president-of-africtivistes-at-the-opening-of-the-fifafrica-forum-26th-27th-september-2024-dakar-senegal/
Source content: "Speech by Cheikh Fall, President of AfricTivistes, at the opening of the FIFAfrica Forum, 26th-27th September 2024 – Dakar, Senegal."
Comparison: Title (President), event (FIFAfrica forum opening), dates (26-27 September 2024), and location (Dakar) all match verbatim. The "principal public-facing voice" interpretive framing is consistent with him delivering the opening speech.
Decision: corroborated

## Claim 19: 2024 AfricTivistes–Democracy Reporting International chatbot-reliability study on the 17 November 2024 Senegalese legislative elections; quoted conclusion that chatbots "cannot be considered entirely reliable sources of electoral information"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/ (cited; could not extract substantive content in this pass — fetched page returned header/footer layout only)
Source content: No verbatim text on the joint study, the five chatbots tested, the 17 November 2024 election context, or the quoted conclusion could be extracted in this pass.
Comparison: The cited AfricTivistes URL did not return substantive content in this fetch. Without verbatim source text the joint-study claim and the quoted conclusion cannot be checked against the cited source. Quoted statement also falls under MISSION § Auditor's stricter Person rule.
Decision: uncorroborated

## Claim 20: "data-journalism training programmes deployed in Senegal, Guinea, Niger, and Burkina Faso"

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique) only
Source content: "Provided data-journalism and digital media training across West Africa, specifically in Senegal, Guinea, Niger, and Burkina Faso."
Comparison: Wikipedia matches the country list exactly. Per MISSION § Auditor, this Person professional-activity claim needs a second canonical source; none was located in this pass.
Decision: uncorroborated

## Claim 21: 2014 member of UNESCO's "Youth Civic Engagement" expert group

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique) only
Source content: "Selected as a member of the expert group for 'Youth Civic Engagement' discussions in 2014."
Comparison: Wikipedia matches. Per MISSION § Auditor, this Person affiliation claim needs a second canonical source; none was located in this pass.
Decision: uncorroborated

## Claim 22: 2013 Reporters Without Borders Net-citoyen Prize nomination; 2014 Deutsche Welle "Best Online of Activism" nomination

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique) only
Source content: "Reporters Without Borders Net-citoyen nomination (2013); Deutsche Welle nomination for 'Best Online Of Activism' (2014)."
Comparison: Wikipedia matches both. Per MISSION § Auditor, these Person recognition claims (affiliation-shaped — the body asserts Fall's relationship to these awarding institutions) need a second canonical source; none was located in this pass.
Decision: uncorroborated

## Claim 23: 2016 Diakonia Prize — awarded by Swedish humanitarian Diakonia at AFRICAPACITES 2016 in Burkina Faso, "for democratic consolidation in Africa through information and communication technologies"

Source: http://www.socialnetlink.org/2016/07/consolidation-democratique-en-afrique-par-les-tic-le-web-activiste-senegalais-cheikh-fall-honore cross-checked against https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique)
Source content: Socialnetlink — "Diakonia, a Swedish humanitarian organization, presented Cheikh Fall with 'un diplôme pour la consolidation démocratique en Afrique par les TIC' (a diploma for democratic consolidation in Africa through ICT) at AFRICAPACITES 2016, held in Burkina Faso." Wikipedia — "Diakonia Prize (2016) 'for significant contribution to democratic consolidation in Africa through ICT'."
Comparison: Both sources confirm the prize, year, venue (AFRICAPACITES 2016 / Burkina Faso), the Swedish-humanitarian framing of Diakonia, and the citation language ("democratic consolidation in Africa through ICT" — body's "information and communication technologies" is the unabbreviated form of TIC). Two canonical sources agree.
Decision: corroborated

## Claim 24: 2019 Intelligences Magazine ranking among the fifty most influential young people in Senegal

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique) only
Source content: "Ranked among fifty most influential young people in Senegal by Intelligences Magazine (2019)."
Comparison: Wikipedia matches. Per MISSION § Auditor, this Person recognition claim needs a second canonical source; none was located in this pass.
Decision: uncorroborated
