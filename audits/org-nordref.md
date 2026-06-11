---
entity_id: org-nordref
entity_hash: 6b065ac909fc39e17c940b027e09d8bad970b11a
audit_date: 2026-06-10
pass: 1
status: corrections-pending
claims_total: 23
claims_corroborated: 6
claims_primary_sourced: 10
claims_single_source: 0
claims_uncorroborated: 6
open_corrections: 1
sources_consulted:
  - https://www.nordref.org/about
  - https://www.nordref.org/who-we-are
  - https://www.nordref.org/projects-3
  - https://www.nordref.org/what-we-do
  - https://www.nordref.org/our-report
  - https://www.nordref.org/post/recruiting-digital-youth-ambassadors-in-denmark-finland-iceland-and-sweden
  - https://www.nordref.org/digital-youth-ambassadors
  - https://www.nordref.org/game-changer
  - https://nordicnavigator.org/
  - https://en.wikipedia.org/wiki/Nordic_Digital_Rights_and_Equality_Foundation
  - https://en.wikipedia.org/wiki/Thordis_Elva
  - https://en.wikipedia.org/wiki/Emma_Holten
  - https://www.thordiselva.com/
  - https://www.norden.org/en/news/women-have-poorer-legal-protection-men-online-hate
  - https://nikk.no/en/our-work/our-projects/our-earlier-projects/online-hate-and-violence/
---

## Claim 1: "co-founded in 2020 by six Nordic activists and researchers: Thordis Elva (Iceland, chairperson), Emma Holten (Denmark), María Rún Bjarnadóttir (Iceland), Moa Bladini (Sweden), Milla Mølgaard (Denmark), and Ida Östensson (Sweden)" (+ frontmatter `founded: 2020`)

Source: https://www.nordref.org/about
Source tier: primary
Source content: "Founding Year: 2020 … Founders/Co-founders: Thordis Elva, Emma Holten, María Rún Bjarnadóttir, Moa Bladini, Milla Mølgaard, and Ida Östensson"
Comparison: Founding year and all six co-founder names match the org's own About page exactly; covers frontmatter scalar `founded` as well.
Decision: primary-sourced

## Claim 2: "Registered in Stockholm and active across Sweden, Denmark, Finland, and Iceland" (+ frontmatter `location`; + body "operates in four of the five" Nordic countries)

Source: https://www.nordref.org/about ; https://en.wikipedia.org/wiki/Nordic_Digital_Rights_and_Equality_Foundation
Source tier: primary
Source content: About page: "Registered address: Box 2119, 116 74 Stockholm, Sweden". Wikipedia: operates across "Sweden, Denmark, Finland and Iceland"; "administrative base is in Sweden".
Comparison: Stockholm registration confirmed primary; the four-country scope (i.e. four of five Nordics, excluding Norway) confirmed by both; geographic scope is a named-entity definitional fact where Wikipedia counts as canonical. Frontmatter `location` scalar matches.
Decision: corroborated

## Claim 3: "a region of 26 million people, nearly all of whom are online" (+ scalar sources[3].note "26 million people, ~97% online")

Source: https://www.nordref.org/what-we-do
Source tier: primary
Source content: "26 million netizens" across the Nordic countries.
Comparison: The page's "26 million netizens" supports the 26-million figure and the nearly-all-online framing. The scalar note's specific "~97%" figure was not located on the page this pass — no contradiction found, but the percentage token is unconfirmed.
Decision: primary-sourced

## Claim 4: "produces empirical research, builds civil society capacity, and engages European regulatory processes" / org scope of research, consultation, tool development, best practices (scalar sources[4].note)

Source: https://www.nordref.org/what-we-do
Source tier: primary
Source content: "consultation about digital rights / abuse" including legislation; "developing and sharing knowledge about digital rights and responsibilities"; "developing and implementing tools and solutions"; "outlining best practices"; manifesto: online abuse "silences certain voices, threatens freedom of expression and thereby undermines democracy itself".
Comparison: Activity scope and the abuse-undermines-democracy premise (scalar sources[4].note) match the org's own theory-of-change page.
Decision: primary-sourced

## Claim 5: "Thordis Elva serves as Chairperson"

Source: https://www.nordref.org/who-we-are
Source tier: primary
Source content: "Chairperson & Founder: Thordis Elva (Iceland) — Writer, speaker and activist"
Comparison: Direct match on the org's team page.
Decision: primary-sourced

## Claim 6: "Thordis Elva's founding role grew directly from her years chairing Iceland's only women's shelter, where she observed technology-facilitated violence being used to trap victims — threats of non-consensual image sharing preventing women from safely leaving abusive relationships"

Source: https://en.wikipedia.org/wiki/Thordis_Elva ; https://www.nordref.org/what-we-do
Source tier: tiebreaker
Source content: Wikipedia: "Chair of the Board of the Women's Shelter of Iceland" (2010). what-we-do: "20% of contacts to Iceland's sole women's shelter seek help due to online abuse".
Comparison: The shelter chairing is confirmed (though Wikipedia dates it to 2010, vs the body's "her years chairing"), and the org's manifesto carries a related shelter statistic — but the causal claim (founding role grew directly from what she observed there, specifically NCII threats trapping victims) is a causal/motivational claim found in no consulted source. Causal claims are tiebreaker-only territory for Wikipedia and need direct sourcing.
Decision: uncorroborated

## Claim 7: "An Icelandic author, playwright, and speaker whose memoir South of Forgiveness (2017), co-written with her assault perpetrator … generated over ten million TED views … a sought-after interlocutor … at the United Nations, Council of Europe, and EU institutions"

Source: https://en.wikipedia.org/wiki/Thordis_Elva ; https://www.thordiselva.com/
Source tier: primary
Source content: Wikipedia: "Icelandic author, speaker, playwright and activist"; South of Forgiveness published 2017, co-authored with Tom Stranger, "who perpetrated the sexual assault"; "the accompanying TED talk having been viewed over 10 million times"; "keynotes at events hosted by the UN, the Nordic Council of Ministers, the Council of Europe, the European Union". Her own site: "a TED talk that has been viewed over 10 million times"; "keynotes … at events hosted by the UN, the Nordic Council of Ministers, the Council of Europe, the European Union and the Nordic Council".
Comparison: Every factual token (professions, memoir year and co-authorship, TED view count, UN/CoE/EU venues) confirmed by two independent sources (Wikipedia + Elva's own site, primary for her own biography).
Decision: corroborated

## Claim 8: scalar sources[5].note — "Woman of the Year 2015 (Federation of Icelandic Women's Societies); #MeToo Iceland Person of the Year 2017"

Source: https://en.wikipedia.org/wiki/Thordis_Elva
Source tier: tiebreaker
Source content: "She was voted Woman of the Year 2015 by the Federation of Icelandic Women's Societies"; "accepting the Person of the Year Award 2017 on behalf of the movement" (#MeToo Iceland).
Comparison: The scalar note accurately reflects Wikipedia (scalar path: sources[5].note). However, living-person recognitions are not in the Wikipedia-alone-sufficient class and no second canonical source was consulted for these two awards this pass — sourcing-strength label, not an error finding.
Decision: uncorroborated

## Claim 9: "Co-founder Emma Holten is a Danish digital-rights activist known for her advocacy against non-consensual image sharing"

Source: https://www.nordref.org/who-we-are ; https://en.wikipedia.org/wiki/Emma_Holten
Source tier: primary
Source content: who-we-are: "Online human rights activist" (Denmark), founder of CONSENT project. Wikipedia: "Holten became famous in Denmark in 2014 when she took a stand against revenge porn. In 2011 Holten had naked pictures stolen from her and distributed over the internet without her consent."
Comparison: Org page (primary) plus Wikipedia (tiebreaker, permitted as second source) together confirm the role and the NCII-advocacy she is known for. Wikipedia says "Danish-Swedish"; "Danish" is consistent with the org's own listing (Denmark).
Decision: corroborated

## Claim 10: "Moa Bladini is a Swedish legal scholar specialising in online harassment law"

Source: https://www.nordref.org/who-we-are ; https://www.norden.org/en/news/women-have-poorer-legal-protection-men-online-hate
Source tier: primary
Source content: who-we-are: "Lawyer, lecturer and researcher" specializing in criminal law and hate speech regulation. norden.org/GU: Associate Professor in Criminal Law at University of Gothenburg; research on online hate speech legislation and gendered online abuse; co-author of "Rethinking Online Anti-Gender Hate Speech" (Routledge).
Comparison: "Swedish legal scholar" confirmed primary; the online-harassment-law specialism confirmed by independent mainstream/academic sources (norden.org, Routledge title, NIKK project where she was Swedish PI).
Decision: corroborated

## Claim 11: "NordREF's flagship EU policy project operationalises three EU frameworks — the Digital Services Act, the AI Act, and the Violence Against Women Directive — into practical advocacy toolkits and civil society training"

Source: https://www.nordref.org/projects-3
Source tier: primary
Source content: "turning EU legislation—such as the Digital Services Act, the AI Act, and the Violence Against Women Directive—into concrete advocacy"; project "aims to strengthen civil society's ability combating technology-facilitated gender-based violence by leveraging EU legislation".
Comparison: All three named instruments and the toolkit/training purpose confirmed verbatim on the org's projects page.
Decision: primary-sourced

## Claim 12: "training Nordic and European organisations … to use the Act's high-risk-system provisions as accountability levers against platforms algorithmically amplifying harmful content"

Source: https://www.nordref.org/projects-3
Source tier: none
Source content: The projects page names the AI Act among the legislation being turned "into concrete advocacy" but says nothing about high-risk-system provisions or that specific accountability mechanism.
Comparison: The specific mechanism (high-risk-system provisions as levers against algorithmic amplification) appears in no consulted source; it reads as an inference from the project's general framing.
Decision: uncorroborated

## Claim 13: "Game Changer (2023–2026). An international collaboration across Denmark, Sweden, Finland, and Iceland … combines research, gaming mechanics, and youth ambassador networks … specifically addresses boys at elevated risk of perpetrating digital violence"

Source: https://www.nordref.org/projects-3
Source tier: primary
Source content: "The Game Changer — September 2023 – 2026 — Denmark, Sweden, Finland, Iceland — Combining research, gaming and youth work to counter online abuse … emphasis on boys and young men as potential perpetrators. Funded by Erasmus+."
Comparison: Dates, countries, method mix, and the boys-as-potential-perpetrators focus all match the org's projects page ("youth ambassador networks" matches the Digital Youth Ambassadors strand of the project).
Decision: primary-sourced

## Claim 14: "#HateFYP … tracks whether major social media platforms systematically amplify anti-LGBTI hate content to new and uninitiated users … replicates a methodology drawn from published research showing that brand-new social media accounts were served anti-feminist content within minutes of registration, with hate-driven narratives dominating their feeds within hours"

Source: https://www.nordref.org/projects-3
Source tier: primary
Source content: "The project intends to track whether online platforms are pushing hate-driven indoctrination to users. A 2024 study by Dublin City University found that brand new YouTube and TikTok accounts, registered as belonging to teenage boys, were exposed to anti-feminist content within 23 minutes. Within hours, over 75% of their feeds were filled with hate-driven narratives. … Project partners aim to replicate this experiment — this time focusing on anti-LGBTI content."
Comparison: The tracking aim, the anti-LGBTI focus, and the replicated methodology (anti-feminist content within minutes — 23 minutes; feeds dominated within hours — over 75%) match the projects page nearly verbatim.
Decision: primary-sourced

## Claim 15: "Results are intended to support Digital Services Act enforcement proceedings and regulatory complaints in Nordic jurisdictions"

Source: no canonical source found
Source tier: none
Source content: The #HateFYP section on the projects page (quoted in full this pass) contains no mention of DSA enforcement proceedings or regulatory complaints; a dedicated /hatefyp page returned 404.
Comparison: The stated intended use of #HateFYP results appears in no consulted source.
Decision: uncorroborated

## Claim 16: "The Profiling Nordic Perpetrators study (2022–2023) … documenting age, gender, motive, and relationship-to-victim patterns across Sweden, Denmark, and Iceland"

Source: https://www.nordref.org/projects-3 ; https://nikk.no/en/our-work/our-projects/our-earlier-projects/online-hate-and-violence/
Source tier: primary
Source content: projects page: "2022-2023 — Sweden, Denmark, Iceland — Research collaboration with women's shelters, police, and courts … perpetrator profiles are established with regard to age, gender, motive and relationship to the victim. Funded by the Nordic Equality Fund (NIKK)." NIKK (independent database source) lists the project "Profiling Nordic Perpetrators of Gendered Online Abuse" among its funded projects.
Comparison: Dates, the three countries, and the exact four profiling dimensions confirmed verbatim on the primary source, with the project's existence independently confirmed by the funder's database.
Decision: corroborated

## Claim 17: "produced the first cross-Nordic evidence base on online abuse perpetrators"

Source: https://www.nordref.org/projects-3
Source tier: none
Source content: Neither the projects page nor the research page claims the study was the "first" cross-Nordic evidence base.
Comparison: The "first" superlative is a contested-attribution-class claim found in no consulted source.
Decision: uncorroborated

## Claim 18: "NordREF has also published analysis on generative AI misuse for producing non-consensual intimate imagery"

Source: https://www.nordref.org/our-report
Source tier: primary
Source content: "Sexually explicit material can be - and is increasingly - made by Generative AI technology, as is now the case with twenty girls aged 12-17 in Spain in a high-profile case."
Comparison: The org's own research page carries published analysis of generative-AI-produced sexual material as an emerging harm vector — matches the body claim.
Decision: primary-sourced

## Claim 19: "Nordic Navigator and Digital Youth Embassy. Longer-arc youth infrastructure programmes building digital citizenship skills and civil society capacity among young people across the Nordic countries"

Source: https://nordicnavigator.org/ ; https://www.nordref.org/digital-youth-ambassadors ; https://www.nordref.org/game-changer
Source tier: primary
Source content: Nordic Navigator is "a comprehensive resource for safety and wellbeing in gaming and digital spaces … built on proven materials from Denmark, Sweden, Finland, and Iceland," developed by NordREF; "From 2025-2026, the Game Changer project will establish Digital Youth Embassies"; Digital Youth Ambassadors recruited "in Denmark, Finland, Iceland and Sweden."
Comparison: Both programmes exist and match the youth-infrastructure characterization. Nuance: the Digital Youth Embassies are a 2025–2026 component of the Game Changer project rather than a freestanding programme — within paraphrase tolerance, not a token error.
Decision: primary-sourced

## Claim 20: scalar sources[2].note — "NordREF projects page — primary source for full project portfolio: Turning EU Laws Into Action …, Game Changer (2023–2026), #HateFYP …, Nordic Navigator, Profiling Nordic Perpetrators (2022–2023), and Digital Youth Embassy"

Source: https://www.nordref.org/projects-3
Source tier: primary
Source content: The projects page lists five projects: The Nordic Talk (2022), Profiling Nordic Perpetrators (2022-2023), The Game Changer (Sept 2023–2026), Turning EU Laws Into Action, and #HateFYP. Two targeted fetches this pass confirm "Nordic Navigator" and "Digital Youth Embassy" are "not mentioned on this page."
Comparison: Scalar path sources[2].note asserts the cited page lists Nordic Navigator and Digital Youth Embassy in its project portfolio; the page lists neither (they are sourced at nordicnavigator.org, /digital-youth-ambassadors, and /game-changer instead). The fix is to drop those two names from this note (or re-cite them to the pages that carry them); the body claims themselves are supported elsewhere (Claim 19).
Decision: correction

## Claim 21: "The advisory board includes Johanna Vehkoo (Finland) …; Christian Mogensen (Denmark) …; Anni Carlsson (Sweden) …; Linda Luhtala (Finland) …; Eygló Árnadóttir (Iceland) …; and Kristina Wicksell (Sweden) …"

Source: https://www.nordref.org/who-we-are
Source tier: primary
Source content: Board members listed: "Johanna Vehkoo (Finland) — Award-winning journalist specializing in misinformation online; Christian Mogensen (Denmark) — Senior advisor on Technological Diplomacy; expert on destructive online behavior; Anni Carlsson (Sweden) — Doctor of Laws, Lecturer researching freedom of expression on social media; Linda Luhtala (Finland) — Project Manager at Finnish Institute focusing on technology, gender equality, and development; Eygló Árnadóttir (Iceland) — Gender studies expert and former educational director of sexual violence counseling center; Kristina Wicksell (Sweden) — Communicator and change-maker on equality and digital rights."
Comparison: All six names, countries, and roles match the org's team page (also covers scalar sources[1].note). Paraphrase deltas within tolerance: body's "online radicalisation" vs page's "destructive online behavior" (Mogensen); body's "equality and human rights" vs page's "equality and digital rights" (Wicksell) — characterization nuances, not single-token contradictions.
Decision: primary-sourced

## Claim 22: "NordREF is funded in part by the Nordic Gender Equality Fund and the Erasmus+ programme" (+ scalar sources[4 (wikipedia)].note funding)

Source: https://www.nordref.org/projects-3 ; https://en.wikipedia.org/wiki/Nordic_Digital_Rights_and_Equality_Foundation
Source tier: primary
Source content: projects page: Profiling Nordic Perpetrators "Funded by the Nordic Equality Fund (NIKK)"; Game Changer "Funded by Erasmus+". Wikipedia: support from "the Nordic Gender Equality Fund, the Erasmus program and elsewhere."
Comparison: Both funders confirmed by the org's own project pages with Wikipedia as the permitted second source for this financial claim.
Decision: corroborated

## Claim 23: "Academic partnerships include Gothenburg University and Samtökin '78, Iceland's primary LGBTI civil society organisation"

Source: https://en.wikipedia.org/wiki/Nordic_Digital_Rights_and_Equality_Foundation
Source tier: tiebreaker
Source content: Wikipedia: documented collaborations include "Gothenburg University" and "Samtökin '78 (an equality-focused organization)"; the org works through "partnerships with civil society organizations, academic institutions, and public authorities."
Comparison: The partnership pair rests on Wikipedia, which is tiebreaker-only for organizational-positioning claims. The Gothenburg half has independent indirect support (co-founder Moa Bladini is at Gothenburg and was Swedish PI of the NIKK-funded study), but the Samtökin '78 partnership was found in no second canonical source this pass. Sourcing-strength label, not an error finding.
Decision: uncorroborated
