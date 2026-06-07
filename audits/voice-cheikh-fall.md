---
entity_id: voice-cheikh-fall
entity_hash: 33750864884a3527b33787424ac90d79573be41b
audit_date: 2026-06-07
pass: 1
status: discrepancy
claims_total: 24
claims_verified: 9
claims_discrepancy: 1
claims_unverifiable: 14
sources_consulted:
  - https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
  - https://ici.radio-canada.ca/nouvelle/1094673/cheikh-fall-reve-afrique-africtivistes
  - https://africtivistes.com/en/speech-by-cheikh-fall-president-of-africtivistes-at-the-opening-of-the-fifafrica-forum-26th-27th-september-2024-dakar-senegal/
  - https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
  - https://africtivistes.com/en/farafina-tech-an-african-database-advancing-electoral-integrity/
  - https://africtivistes.com/en/africtivistes-launches-the-african-election-civic-tech-fund/
  - https://africtivistes.net/en/africtivistes-en/
  - https://www.divancitoyen.com/africtivistes-lance-farafina-elections/
  - http://www.socialnetlink.org/2016/07/consolidation-democratique-en-afrique-par-les-tic-le-web-activiste-senegalais-cheikh-fall-honore
  - https://www.ouestaf.com/cheikh-fall-president-africtivistes-le-senegal-manque-dambition-mais-peut-assurer-la-protection-des-donnees-personnelles-interview/
---

## Claim 1: "co-founder and President since November 2015" of AfricTivistes (also frontmatter `affiliations`-shape claim through `person_entry` link and `notable_for`)

Source: https://africtivistes.com/en/speech-by-cheikh-fall-president-of-africtivistes-at-the-opening-of-the-fifafrica-forum-26th-27th-september-2024-dakar-senegal/ (primary) cross-checked against https://africtivistes.net/en/africtivistes-en/ and https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: AfricTivistes FIFAfrica24 page header — "Speech by Cheikh Fall, President of AfricTivistes, at the opening of the FIFAfrica Forum, 26th-27th September 2024 – Dakar, Senegal." Africtivistes.net About page — "Founded in 2015 in Dakar, AfricTivistes is a pan-African civil society organization." Boell 2021 — "In 2015, _Africtivistes_ was born at a summit in Dakar with 150 participants from different African countries."
Comparison: President role + 2015 Dakar founding both confirmed by two primary sources plus independent secondary. The specific month "November 2015" matches Boell's framing of the 2015 founding (and is consistent with prior person-cheikh-fall audit Claim 1's verbatim Boell quote "Established at a November 2015 Dakar summit").
Decision: verified

## Claim 2: AfricTivistes is "the Dakar-headquartered pan-African civil-society network at the intersection of digital technology and democracy"

Source: https://africtivistes.net/en/africtivistes-en/
Source content: "Founded in 2015 in Dakar, AfricTivistes is a pan-African civil society organization."
Comparison: "Dakar-headquartered" and "pan-African civil-society network" both match within paraphrase tolerance. The "intersection of digital technology and democracy" framing is consistent with AfricTivistes's stated mission and the Boell description "pan-African network."
Decision: verified

## Claim 3: AfricTivistes–Democracy Reporting International joint chatbot-reliability study on the "17 November 2024 Senegalese legislative elections" published "22 April 2025"

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/ (cited; could not extract substantive content in this pass — fetched page returned navigation/footer chrome only, same SPA-render failure observed in prior person-cheikh-fall audit Claim 19)
Source content: No verbatim text on the study, the partner DRI, the 17 November 2024 election context, the publication date, or the testing methodology could be extracted in this pass.
Comparison: The cited AfricTivistes URL did not return article body content in this fetch. Without verbatim source text the study existence, partner identity, election date, and publication date cannot be checked against the cited source. No second canonical source for these specifics was located.
Decision: unverifiable

## Claim 4: Five chatbots tested — "Microsoft Copilot, Google Gemini, OpenAI ChatGPT-4o, OpenAI ChatGPT-4omini, and Anthropic Claude" (`sources[0].note` frontmatter scalar and body)

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/ (cited; same fetch failure as Claim 3)
Source content: No verbatim text on the named chatbots could be extracted in this pass.
Comparison: The cited URL did not return article body content. The named-chatbots claim cannot be checked against the cited source in this pass; no second canonical source was located.
Decision: unverifiable

## Claim 5: Three-criteria evaluation methodology — "accuracy, consistency, and completeness" (`sources[0].note` frontmatter scalar and body)

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/ (same fetch failure)
Source content: No verbatim text on the methodology could be extracted.
Comparison: Cannot be checked against the cited source in this pass.
Decision: unverifiable

## Claim 6: Quoted conclusion — chatbots "cannot be considered entirely reliable sources of electoral information" (body and `sources[0].note`)

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/ (same fetch failure)
Source content: No verbatim text containing the quoted phrase could be extracted.
Comparison: Cannot be checked against the cited source in this pass. Quoted statement also falls under MISSION § Auditor's stricter Person rule (Person/Voice quoted-statement claims require a primary or mainstream-news document beyond Wikipedia).
Decision: unverifiable

## Claim 7: The chatbot study was conducted "in Wolof and French" (body "Signature framings" first bullet)

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/ (same fetch failure)
Source content: No verbatim text on the testing languages could be extracted.
Comparison: Cannot be checked against the cited source in this pass.
Decision: unverifiable

## Claim 8: Ouestaf News interview dated "8 April 2024, updated 13 April 2024", and conducted "in the frame of the West African Foundation for the Media (MFWA) and Co-Develop journalism fellowship on Digital Public Infrastructure (DPI)" (`sources[1].note` frontmatter scalar)

Source: https://www.ouestaf.com/cheikh-fall-president-africtivistes-le-senegal-manque-dambition-mais-peut-assurer-la-protection-des-donnees-personnelles-interview/ (cited; returned HTTP 403 Forbidden in this session — site appears to block automated fetches)
Source content: Source returned 403; no content extracted.
Comparison: Cannot be checked against the cited source in this pass. No second canonical source for the publication / update dates or the MFWA / Co-Develop fellowship framing was located.
Decision: unverifiable

## Claim 9: Quoted Ouestaf framings — five quoted lines on digital sovereignty, e-citoyen power, ignorance vs malfeasance, local-vs-foreign expertise, and the Diamniadio Data Center (body "Signature framings" bullets 2–4 and `sources[1].note`)

Source: https://www.ouestaf.com/cheikh-fall-president-africtivistes-le-senegal-manque-dambition-mais-peut-assurer-la-protection-des-donnees-personnelles-interview/ (same 403 failure)
Source content: Source returned 403; the quoted French-language lines could not be retrieved.
Comparison: Cannot be checked against the cited source in this pass. Quoted statements fall under MISSION § Auditor's stricter Person/Voice rule and require a primary or mainstream-news document — Wikipedia alone is insufficient and would not carry these specific quotes in any case.
Decision: unverifiable

## Claim 10: FIFAfrica24 opening-ceremony keynote dates "26–27 September 2024" in Dakar, with Fall delivering as "President of AfricTivistes" (body and `sources[2].note`)

Source: https://africtivistes.com/en/speech-by-cheikh-fall-president-of-africtivistes-at-the-opening-of-the-fifafrica-forum-26th-27th-september-2024-dakar-senegal/
Source content: "Speech by Cheikh Fall, President of AfricTivistes, at the opening of the FIFAfrica Forum, 26th-27th September 2024 – Dakar, Senegal."
Comparison: Title (President), event (FIFAfrica forum opening), dates (26-27 September 2024), and location (Dakar, Senegal) all match verbatim.
Decision: verified

## Claim 11: FIFAfrica24 was the "11th Forum on Internet Freedom in Africa" — edition number

Source: https://africtivistes.com/en/speech-by-cheikh-fall-president-of-africtivistes-at-the-opening-of-the-fifafrica-forum-26th-27th-september-2024-dakar-senegal/ (page header / footer only extracted in this fetch)
Source content: No verbatim text confirming the "11th" edition number could be extracted.
Comparison: The "11th" edition specifier is not in any source fetched in this pass. No second canonical source for the edition number was located.
Decision: unverifiable

## Claim 12: FIFAfrica24 was "the first time the continent's flagship internet-freedom convening was hosted in Senegal"

Source: https://africtivistes.com/en/speech-by-cheikh-fall-president-of-africtivistes-at-the-opening-of-the-fifafrica-forum-26th-27th-september-2024-dakar-senegal/ (page header / footer only)
Source content: No verbatim text confirming the "first time in Senegal" superlative could be extracted.
Comparison: The "first" superlative is not supported by any source fetched in this pass. No second canonical source was located.
Decision: unverifiable

## Claim 13: Farafina platform launched "26 June 2025" (`notable_for`, body, and `sources[3].note`)

Source: https://www.divancitoyen.com/africtivistes-lance-farafina-elections/
Source content: "Le 26 juin 2025, Africtivistes a mis en ligne la plateforme **Farafina**."
Comparison: 26 June 2025 launch date matches verbatim. Divan Citoyen is independent French-language press coverage; the entity's primary source (AfricTivistes own page) did not return article body content in this pass, so the secondary stands alone here.
Decision: verified

## Claim 14: Farafina built across "more than twelve (12) months of data collection, processing and aggregation from 54 African countries"

Source: https://www.divancitoyen.com/africtivistes-lance-farafina-elections/
Source content: "Farafina est le fruit de plus de douze (12) mois de collectes, de traitement et d'agrégation de données de 54 pays africains."
Comparison: "Plus de douze (12) mois" matches "more than twelve months" verbatim; "54 pays africains" matches "54 African countries" verbatim.
Decision: verified

## Claim 15: Farafina is "the continent's first online one-stop civic-tech platform on African elections and electoral processes"

Source: https://www.divancitoyen.com/africtivistes-lance-farafina-elections/ (article title: "Africtivistes lance Farafina, 'premier guichet unique sur les élections en Afrique'")
Source content: Article title — "Africtivistes lance Farafina, 'premier guichet unique sur les élections en Afrique'" (Africtivistes launches Farafina, "first one-stop window on elections in Africa")
Comparison: Divan Citoyen's title carries the "premier guichet unique" framing in scare quotes — the press citing AfricTivistes's own framing. The body's "continent's first online one-stop civic-tech platform on African elections" matches "premier guichet unique sur les élections en Afrique" within paraphrase tolerance ("one-stop window/civic-tech platform" carries the same meaning; "Africa" / "the continent" carries the same scope). The primary AfricTivistes page that is the source of the framing could not be body-extracted in this pass (same SPA fetch failure), but Divan Citoyen's title quotes the framing.
Decision: verified

## Claim 16: Mandinka-language naming — "*Farafina* meaning 'Africa'" (`sources[3].note`)

Source: https://africtivistes.com/en/farafina-tech-an-african-database-advancing-electoral-integrity/ (cited; same SPA fetch failure as Claim 3) and https://www.divancitoyen.com/africtivistes-lance-farafina-elections/ (Divan Citoyen does not record the Mandinka etymology in the fetched content)
Source content: No verbatim text on the Mandinka-language naming or the "Africa" gloss could be extracted from either source in this pass.
Comparison: Neither source fetched in this pass confirms the Mandinka-language etymology. The frontmatter scalar `sources[3].note` makes this claim; it cannot be verified against the cited source in this pass.
Decision: unverifiable

## Claim 17: African Election Civic Tech Fund — "funding twelve civic-tech projects for electoral engagement" (`notable_for`, body, `sources[5].note`)

Source: https://africtivistes.com/en/africtivistes-launches-the-african-election-civic-tech-fund/ (cited; page returned navigation/footer chrome only in this pass — same SPA fetch failure)
Source content: No verbatim text on the number "twelve" or the projects funded could be extracted.
Comparison: The "twelve civic-tech projects" specific count cannot be checked against the cited source in this pass. No second canonical source for the count was located.
Decision: unverifiable

## Claim 18: "2010 launch of *Citoyen au Sénégal* — Senegal's first citizen-journalism web platform" (body; the "first" superlative is the load-bearing specifier)

Source: https://ici.radio-canada.ca/nouvelle/1094673/cheikh-fall-reve-afrique-africtivistes
Source content: "En 2010, il crée une plateforme web, Citoyen au Sénégal, et l'année suivante, une autre consacrée à la surveillance de la campagne électorale de 2012."
Comparison: 2010 launch + platform name match exactly. The "first citizen-journalism web platform" superlative is not in the Radio-Canada source — the source records the platform's 2010 launch but does not call it Senegal's first. No second canonical source for the superlative was located. Per the prior person-cheikh-fall audit Claim 10 (`unverifiable`) the same gap was found; this remains unresolved.
Decision: unverifiable

## Claim 19: 2012 #Sunu2012 ("Wolof for 'Our 2012'") citizen-election-monitoring platform

Source: https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share cross-checked against https://ici.radio-canada.ca/nouvelle/1094673/cheikh-fall-reve-afrique-africtivistes
Source content: Boell — "Sunu 2012 (Our 2012)." Radio-Canada — "En 2010, il crée une plateforme web, Citoyen au Sénégal, et l'année suivante [2011], une autre consacrée à la surveillance de la campagne électorale de 2012."
Comparison: Boell confirms the Wolof gloss and "Our 2012" rendering verbatim. Radio-Canada confirms the second platform was dedicated to monitoring the 2012 electoral campaign.
Decision: verified

## Claim 20: #Sunu2012 "launched from June 2011" (body, "Public output and venues" second bullet)

Source: https://ici.radio-canada.ca/nouvelle/1094673/cheikh-fall-reve-afrique-africtivistes and https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: Radio-Canada pins the launch to 2011 ("l'année suivante") without naming a launch month. Boell does not surface a launch month in the fetched content.
Comparison: Year (2011) is supported; the "June" specifier is not in any source fetched in this pass. Prior person-cheikh-fall audit Claim 12 marked the same specifier `unverifiable`; this remains unresolved.
Decision: unverifiable

## Claim 21: "AfricTivistes records as having directly informed President Wade's concession call" (body and `notable_for`)

Source: https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: Boell (per the fetch) records "Wade called his opponent after receiving preliminary election results" — the framing is that the preliminary results "reportedly influenced" the concession (per the verbatim quote in prior person-cheikh-fall audit Claim 14).
Comparison: The body's "directly informed" strengthens the source's "reportedly influenced," and the body attributes the framing to AfricTivistes records rather than the journalist's reporting. Neither the strengthening nor the meta-attribution is supported by the cited Boell article. No AfricTivistes self-record carrying the specific "directly informed" framing was fetched.
Decision: unverifiable

## Claim 22: Heinrich Böll Stiftung records the AfricTivistes founding network as "200 cyber-activists from 35 different countries on the continent" (`notable_for` frontmatter scalar — "200 cyber-activists from 35 different countries on the continent" — and body "Public output and venues" third bullet — "the '200 cyber-activists from 35 different countries' framing of the founding network")

Source: https://www.boell.de/en/2021/09/22/senegal-if-i-dont-know-i-ask-if-i-know-i-share
Source content: Boell — "a pan-African network with more than 200 members from 40 countries on the African continent" (appears in the author/contributor biography at the end of the interview, describing the network's current size). Two targeted fetches in this session searching specifically for any reference to "35 countries" or to the founding-network size returned no match — the only network-size specification in the fetched article is "200 members from 40 countries."
Comparison: The body and frontmatter attribute the specific framing "200 cyber-activists from 35 different countries on the continent" to the Heinrich Böll source as a record of Fall's canonical framing of the founding network. The cited source as fetched in this pass carries "200 members from 40 countries on the African continent" — a different country count (40 vs body's 35) and a different noun ("members" vs body's "cyber-activists") — and presents this as a third-party biographical description of the network's current scope, not as Fall's framing of the founding network. The body/frontmatter quote cannot be sourced to the cited article as fetched, and the country-count specifier (35) directly contradicts the source's specifier (40). The Editor's Audit-discrepancy backfill act applies to both locations: body in the "Public output and venues" third-bullet sentence and frontmatter `notable_for` scalar.
Decision: discrepancy

## Claim 23: 2016 Diakonia Prize — awarded by Diakonia (Swedish humanitarian) for "democratic consolidation in Africa through information and communication technologies" at AFRICAPACITES 2016 in Burkina Faso (body "Signature framings" last bullet, "Public output and venues" last bullet, `notable_for`, and `sources[7].note`)

Source: http://www.socialnetlink.org/2016/07/consolidation-democratique-en-afrique-par-les-tic-le-web-activiste-senegalais-cheikh-fall-honore
Source content: "Diakonia, une organisation humanitaire suédoise, a remis, la semaine dernière, un diplôme pour la consolidation démocratique en Afrique par les TIC à Cheikh Fall" — and AFRICAPACITES 2016 in Burkina Faso confirmed as the venue.
Comparison: Socialnetlink confirms (a) Diakonia as Swedish humanitarian, (b) the citation "consolidation démocratique en Afrique par les TIC" — body's "democratic consolidation in Africa through information and communication technologies" is the faithful unabbreviated English rendering (TIC → ICT → "information and communication technologies"), (c) AFRICAPACITES 2016 venue, and (d) Burkina Faso location. Article publication date 5 July 2016 ("la semaine dernière" — the previous week) is consistent with a late-June 2016 award.
Decision: verified

## Claim 24: Awards and recognitions sourced to French Wikipedia only — "2013 Reporters Without Borders Net-citoyen Prize nomination, the 2014 Deutsche Welle 'Best Online of Activism' nomination, the 2014 membership of UNESCO's 'Youth Civic Engagement' expert group, and the 2019 Intelligences Magazine ranking among the fifty most influential young people in Senegal" — plus "data-journalism training programmes deployed in Senegal, Guinea, Niger, and Burkina Faso" (body "Public output and venues" fifth bullet, `sources[10].note`)

Source: https://fr.wikipedia.org/wiki/Cheikh_Fall_(expert_num%C3%A9rique) only (per the body's own link structure; not refetched in this pass — prior person-cheikh-fall audit Claims 20–22 and 24 already established Wikipedia carries the claims verbatim).
Source content: Per the prior person audit's fetched content, Wikipedia matches each claim verbatim.
Comparison: Per MISSION § Auditor's stricter rule, a Person/Voice body claim about affiliation, tenure, recognition, or training-programme participation requires a sourceable primary or mainstream-news document — Wikipedia alone is insufficient. No second canonical source for any of these specific recognitions or for the four-country training-programme list was located in this pass. Same outcome as the parallel person-cheikh-fall audit Claims 20–22 and 24.
Decision: unverifiable
