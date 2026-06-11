---
entity_id: lg-datalabe
entity_hash: 763956b7fd109845794dcf052b0cfeb2aceb0051
audit_date: 2026-06-11
pass: 1
status: supported
claims_total: 32
claims_corroborated: 9
claims_primary_sourced: 10
claims_single_source: 11
claims_uncorroborated: 2
open_corrections: 0
sources_consulted:
  - https://globalinnovationgathering.org/2023/04/06/data_labe-a-hub-for-data-and-narratives-from-the-favela/
  - https://medium.com/data-labe/data-labe-um-laborat%C3%B3rio-de-estrutura-flex%C3%ADvel-1454a6391886
  - https://rioonwatch.org/?p=56874
  - https://education.okfn.org/datalabe-empowering-young-leaders-from-vulnerable-communities-with-open-data-and-civic-tech/index.html
  - https://www.opensocietyfoundations.org/grants/past?filter_keyword=Associacao+Data+Labe
  - https://latamjournalismreview.org/articles/brazilian-youth-led-data-journalism-lab-produces-vital-environmental-and-safety-information-in-a-rio-de-janeiro-favela/
  - https://latinno.net/en/case/3355/
  - https://tacticaltech.org/news/stories/data-labe-partner/
  - https://wikifavelas.com.br/index.php/Data_Labe
  - https://en.wikipedia.org/wiki/Mar%C3%A9,_Rio_de_Janeiro
  - https://podcasts.apple.com/us/podcast/data-l%C3%A1bia/id1261088705
  - https://soundcloud.com/data_labe
  - https://www.aljazeera.com/opinions/2017/10/16/why-is-there-talk-of-banning-funk-music-in-brazil
  - https://djmag.com/longreads/baile-funk-criminalisation-brazils-funk-scene
  - https://colaboramerica2018.sched.com/speaker/clara_sacco.1ysm8yjh
  - https://datalabe.org/sobre/
---

## Claim 1: Complexo da Maré is "the network of sixteen favelas in the northern zone of Rio de Janeiro housing more than 140,000 residents"

Source: https://en.wikipedia.org/wiki/Mar%C3%A9,_Rio_de_Janeiro
Source tier: tiebreaker
Source content: Maré is "a group of 16 contiguous favelas and housing projects in the northern zone of Rio de Janeiro," "home to an estimated 140,000 individuals."
Comparison: 16 favelas, northern zone, and ~140,000 residents all match. Named-entity definitional / public-record demographic fact, for which Wikipedia-alone is sufficient per the source rule; the entity's cited LatAm Journalism Review source confirms only "a set of favelas in the same northern region" without the counts. Body says "more than 140,000" vs. Wikipedia's "estimated 140,000" — within paraphrase tolerance.
Decision: single-source

## Claim 2: data_labe "born in 2016 within the Observatório de Favelas" (also scalar: frontmatter `founded: 2016`)

Source: https://globalinnovationgathering.org/2023/04/06/data_labe-a-hub-for-data-and-narratives-from-the-favela/
Source tier: primary
Source content: GIG: data_labe "was born in 2016 as a project within the Observatório de Favelas." Open Knowledge blog: "The Observatório de Favelas...has received a grant...to develop a Data Journalism training course." data_labe's own /sobre page (via search; direct fetch returned 403): originated in 2016 within the facilities of the Observatório de Favelas, in partnership with Escola de Dados.
Comparison: 2016 founding within Observatório de Favelas confirmed by the entity's own site plus two independent sources; this also confirms the frontmatter scalar `founded: 2016`. (LATINNO independently lists 2015 — see Claim 31; the entity's frontmatter source note already acknowledges this divergence.)
Decision: corroborated

## Claim 3: "formally constituted as an autonomous non-profit association in 2018"

Source: https://globalinnovationgathering.org/2023/04/06/data_labe-a-hub-for-data-and-narratives-from-the-favela/
Source tier: database
Source content: GIG: "In 2018, it became an autonomous non-profit association." Wikifavelas: "Em 2018, o data_labe se tornou uma associação autônoma e sem fins lucrativos."
Comparison: Two independent sources confirm 2018 autonomous non-profit association status.
Decision: corroborated

## Claim 4: Mission quote — "promote the democratisation of knowledge through data generation, analysis and dissemination, focusing on race, gender and territory"

Source: https://globalinnovationgathering.org/2023/04/06/data_labe-a-hub-for-data-and-narratives-from-the-favela/
Source tier: database
Source content: "Its mission is to promote the democratisation of knowledge through data generation, analysis and dissemination, focusing on race, gender and territory."
Comparison: Exact verbatim match to the cited source. No second canonical source for this English formulation consulted this pass (the entity's own site is in Portuguese and 403'd to direct fetch).
Decision: single-source

## Claim 5: Gilberto Vieira is a co-founder of data_labe

Source: https://latamjournalismreview.org/articles/brazilian-youth-led-data-journalism-lab-produces-vital-environmental-and-safety-information-in-a-rio-de-janeiro-favela/
Source tier: mainstream
Source content: LatAm Journalism Review: "co-founder of Data_labe." GIG: "one of the co-founders of data_labe."
Comparison: Two independent sources name Vieira as co-founder.
Decision: corroborated

## Claim 6: "The lab was co-founded by Gilberto Vieira and Clara Sacco" — the Clara Sacco element (also scalar: sources[1].note "founding managers Clara Sacco and Gilberto Vieira")

Source: https://medium.com/data-labe/data-labe-um-laborat%C3%B3rio-de-estrutura-flex%C3%ADvel-1454a6391886
Source tier: primary
Source content: "Clara e Gilberto são gestores do data_labe" (Clara and Gilberto are managers of data_labe) — data_labe's own November 2017 account of its founding phase. A ColaborAmerica 2018 speaker bio independently describes Clara Sacco as co-founder and coordinator of data_labe.
Comparison: The entity's own primary account presents Sacco and Vieira as the lab's two managers from the founding period; the frontmatter scalar `sources[1].note` says "founding managers," which matches the source exactly. The body's "co-founded by" is a slight escalation of "gestores" but is supported by the founding-period framing and the independent bio. Within paraphrase tolerance.
Decision: primary-sourced

## Claim 7: Vieira quote — "the official data does not take into account the nuances of the periphery, which only we know"

Source: https://latamjournalismreview.org/articles/brazilian-youth-led-data-journalism-lab-produces-vital-environmental-and-safety-information-in-a-rio-de-janeiro-favela/
Source tier: mainstream
Source content: "We act because the official data does not take into account the nuances of the periphery, which only we know"
Comparison: Verbatim match (body quotes the relevant fragment). Knight Center's LatAm Journalism Review is a specialist outlet with editorial standards — satisfies the living-person quoted-statement requirement, but no second source carries the quote.
Decision: single-source

## Claim 8: data_labe emerged "in partnership with the Escola de Dados Brasil (Data School), which provided the data-journalism training and mentorship scaffolding for the first cohort"

Source: https://education.okfn.org/datalabe-empowering-young-leaders-from-vulnerable-communities-with-open-data-and-civic-tech/index.html
Source tier: primary
Source content: "five young fellows learning the basic principles of data journalism with Escola de Dados Brasil"; LATINNO independently describes data_labe as bridging community residents with "Favela Observatory and Data School."
Comparison: Open Knowledge (Escola de Dados' parent network) confirms the training role; LATINNO independently confirms the Data School partnership.
Decision: corroborated

## Claim 9: "by late 2017 it was operating autonomously, before formally incorporating as an independent association in 2018" — the late-2017 autonomy element

Source: no canonical source found
Source tier: none
Source content: The Medium article (November 2017, titled "data_labe — um laboratório de estrutura flexível") discusses the lab's structure and funding but the fetched content does not state that the lab was operating autonomously from Observatório de Favelas by late 2017.
Comparison: The 2018 incorporation is corroborated (Claim 3), but the specific "operating autonomously by late 2017" framing is paraphrastic and not directly anchored by any source consulted this pass.
Decision: uncorroborated

## Claim 10: "The team comprises young residents from Maré and other popular territories"

Source: https://globalinnovationgathering.org/2023/04/06/data_labe-a-hub-for-data-and-narratives-from-the-favela/
Source tier: database
Source content: GIG: "Its team comprises young people from low-income regions who produce new narratives through data." LATINNO: the lab consists of "young residents of the Maré favela."
Comparison: Two independent sources confirm the team composition.
Decision: corroborated

## Claim 11: "data_labe has been a member of the Global Innovation Gathering since 2017"

Source: https://globalinnovationgathering.org/2023/04/06/data_labe-a-hub-for-data-and-narratives-from-the-favela/
Source tier: primary
Source content: "Data_labe has been part of GIG since 2017 when they participated in the re:publica conference in Berlin."
Comparison: GIG's own page is the authoritative record of its own membership — primary for this claim.
Decision: primary-sourced

## Claim 12: "The initial five-fellow cohort (2016) was supported by Open Society Foundations and worked with Escola de Dados Brasil and Coding Rights to produce data-visualisation projects on topics including transgender killings, neighbourhood perception, education access, maternal health, and public-transportation privacy"

Source: https://education.okfn.org/datalabe-empowering-young-leaders-from-vulnerable-communities-with-open-data-and-civic-tech/index.html
Source tier: primary
Source content: "five young fellows learning the basic principles of data journalism with Escola de Dados Brasil"; OSF grant "to develop a Data Journalism training course and mentorship project"; Coding Rights collaboration (Fernanda Távora); fellows' topics: killings of transgender people in Brazil (Eloi Leones), perception of Baixada Fluminense (Fábio Silva), ENEM participation and school performance (Paloma Calado), maternal deaths in the public health system (Vitória Lourenço), public-transportation data and privacy (Fernanda Távora).
Comparison: All five topics match within paraphrase tolerance (ENEM participation/school performance → "education access"; maternal deaths → "maternal health"; Baixada Fluminense perception → "neighbourhood perception"). Note: the source also says the grant specified four young leaders while profiling five fellows; the body's "five-fellow cohort" matches the five fellows the source names and profiles. OSF support independently confirmed by the Medium primary source (January 2016–January 2017 support).
Decision: primary-sourced

## Claim 13: "Ford Foundation joined as a funder from September 2017"

Source: https://medium.com/data-labe/data-labe-um-laborat%C3%B3rio-de-estrutura-flex%C3%ADvel-1454a6391886
Source tier: primary
Source content: "Só em setembro de 2017 recebemos apoio da Fundação Ford" (Only in September 2017 did we receive Ford Foundation support)
Comparison: Date and funder match the entity's own primary account.
Decision: primary-sourced

## Claim 14: "Open Society Foundations went on to commit three further grants totalling $672,000 between 2019 and 2023, including a $350,000 three-year general-support grant in 2023" (also scalar: sources[4].note grant details)

Source: https://www.opensocietyfoundations.org/grants/past?filter_keyword=Associacao+Data+Labe
Source tier: primary
Source content: Three grants to Associacao Data Labe: $15,000 in 2019 ("to support a meeting with focus on data revealing practices of corruption and environmental racism in favelas in Brazil," 6-month term), $307,000 in 2020 ("to provide general support," 2-year term), $350,000 in 2023 ("to provide general support," 3-year term).
Comparison: $15,000 + $307,000 + $350,000 = $672,000 across 2019–2023; the 2023 grant is $350,000 over three years. The funder's own grants database is the authoritative primary record. The frontmatter scalar `sources[4].note` matches the database in every particular.
Decision: primary-sourced

## Claim 15: "data_labe operates along three axes: journalism and content production; training and education; and citizen-generated data monitoring"

Source: https://wikifavelas.com.br/index.php/Data_Labe
Source tier: database
Source content: Wikifavelas: "jornalismo; formação; monitoramento e geração cidadã de dados" (journalism; training; monitoring and citizen-generated data). GIG names journalism, education, and citizen data generation/monitoring as the work areas.
Comparison: The three axes match across two independent sources.
Decision: corroborated

## Claim 16: "The journalism axis produces the Data_stories platform — data-driven reporting on health, violence, education, culture, and environment from a favela-resident perspective"

Source: no canonical source found
Source tier: none
Source content: Web searches for a data_labe product named "Data_stories" return only unrelated entities (the Data Stories visualization podcast, DataStories International software). data_labe's own site sections found via search are "Conteúdos," "Mapas," "Dados Ausentes," and its Medium publication; none is named "Data_stories." The site itself returned HTTP 403 to direct fetch.
Comparison: The data-driven-reporting activity is real (Medium publication, site content sections), but no canonical source names a platform called "Data_stories." Possible confabulated product name, but with the entity's own site unreachable this pass no source contradicts it with a single correct replacement — so this is an unverifiable naming, not a correction.
Decision: uncorroborated

## Claim 17: "the Data_lábia podcast series on data literacy"

Source: https://podcasts.apple.com/us/podcast/data-l%C3%A1bia/id1261088705
Source tier: primary
Source content: "data_lábia" podcast listed on Apple Podcasts, hosted on data_labe's own SoundCloud account (soundcloud.com/data_labe); listing descriptions present it as a data_labe podcast exploring data literacy through conversations about favelas and their residents.
Comparison: The podcast exists as data_labe's own published artifact and the data-literacy theme matches the listing description.
Decision: primary-sourced

## Claim 18: The "Mapa da Comunicação Comunitária (Community Communication Map), a collaborative platform mapping community media outlets across the Rio metropolitan region"

Source: https://medium.com/data-labe/data-labe-um-laborat%C3%B3rio-de-estrutura-flex%C3%ADvel-1454a6391886
Source tier: primary
Source content: "uma plataforma colaborativa que reúne veículos de toda a Região Metropolitana" (a collaborative platform that brings together [community media] vehicles from the entire Metropolitan Region)
Comparison: Name, collaborative-platform nature, and Rio-metropolitan-region scope match the entity's own primary account.
Decision: primary-sourced

## Claim 19: "Códigos Ancestrais — workshops introducing Black women to data science and coding"

Source: https://globalinnovationgathering.org/2023/04/06/data_labe-a-hub-for-data-and-narratives-from-the-favela/
Source tier: database
Source content: "Códigos Ancestrais: a series of workshops introducing black women to data science and coding"
Comparison: Near-verbatim match to the cited source; no second canonical source consulted carries this programme.
Decision: single-source

## Claim 20: Vieira frames citizen-generated data as "how people can produce data by themselves and be engaged in the production of data without being a formal research institute"

Source: https://rioonwatch.org/?p=56874
Source tier: mainstream
Source content: "Coordinator Gilberto Vieira defines CGD as: 'how people can produce data by themselves and be engaged in the production of data without being a formal research institute.'"
Comparison: Verbatim match. RioOnWatch (Catalytic Communities) is a specialist outlet with editorial standards on the favela beat; single source for the quote.
Decision: single-source

## Claim 21: "In September 2023, data_labe hosted the 1º Seminário de Geração Cidadã de Dados (First Citizen Data Generation Seminar), drawing researchers from Rio de Janeiro, São Paulo, and Pará"

Source: https://wikifavelas.com.br/index.php/Data_Labe
Source tier: database
Source content: September 2023; "pesquisadores das periferias do Rio de Janeiro, São Paulo e Pará" (researchers from the peripheries of Rio de Janeiro, São Paulo, and Pará)
Comparison: Date, event name, and the three states match. Single source (Dicionário de Favelas Marielle Franco, an academically curated favela encyclopedia).
Decision: single-source

## Claim 22: CocôZap is "a WhatsApp-based channel through which Maré residents submit sanitation complaints (sewage leaks, floods, garbage failures) with photographs and geolocation data, which data_labe aggregates into mapped public reports"

Source: https://rioonwatch.org/?p=56874
Source tier: mainstream
Source content: RioOnWatch: residents report sanitation violations (raw sewage leaks, uncollected garbage, lack of clean water) via WhatsApp with photos; the team uploads reports to a database including date, description, category, frequency, and location; data are mapped into reports. Wikifavelas: "um número de WhatsApp que recebe fotos, vídeos e narrativas sobre lixo e esgoto."
Comparison: Mechanics match across two independent sources.
Decision: corroborated

## Claim 23: CocôZap "created in 2016 and formally launched in 2017 after winning the DataShift Community Seed Funding Challenge run by CIVICUS's DataShift initiative"

Source: https://rioonwatch.org/?p=56874
Source tier: mainstream
Source content: RioOnWatch: "CocôZap was planned in 2016 and launched in 2017 after winning the DataShift Community Seed Funding Challenge," "sponsored by the international NGO CIVICUS." The Medium primary source independently mentions the DataShift prize money.
Comparison: 2016 origination ("planned" vs. body's "created" — within paraphrase tolerance), 2017 launch, the DataShift challenge win, and CIVICUS sponsorship all match; the prize is independently confirmed by the entity's own Medium account.
Decision: corroborated

## Claim 24: CocôZap "is co-operated with Redes da Maré and Casa Fluminense with academic partnerships at PUCPR and UFRJ's engineering department"

Source: https://rioonwatch.org/?p=56874
Source tier: mainstream
Source content: Partners listed: Redes da Maré, Casa Fluminense, Pontifical Catholic University of Paraná (PUCPR), Federal University of Rio de Janeiro (UFRJ) Engineering Department.
Comparison: All four partners match. Single source.
Decision: single-source

## Claim 25: "65+ residents contributed data across Nova Holanda, Rubens Vaz, and Parque União favelas"

Source: https://rioonwatch.org/?p=56874
Source tier: mainstream
Source content: "Over 65 residents have contributed data, primarily from Nova Holanda, Rubens Vaz, and Parque União favelas."
Comparison: Count and the three named favelas match. Single source.
Decision: single-source

## Claim 26: "local youth were hired as mobilisers"

Source: https://rioonwatch.org/?p=56874
Source tier: mainstream
Source content: "data_labe hired local youth as 'mobilizers' to recruit collaborators and collect data," naming Maykon Sardinha and Gabrielle of Nova Holanda.
Comparison: Matches. Single source.
Decision: single-source

## Claim 27: "Co-funding came from the Heinrich Böll Foundation and Fundo Socioambiental Caixa"

Source: https://rioonwatch.org/?p=56874
Source tier: mainstream
Source content: "Additional funding came from Fundo Socioambiental Caixa and the Heinrich Böll Foundation."
Comparison: Both funders match. Single source.
Decision: single-source

## Claim 28: "Crimideia is a campaign data_labe runs against the criminalisation of funk music and culture in Brazil"

Source: https://globalinnovationgathering.org/2023/04/06/data_labe-a-hub-for-data-and-narratives-from-the-favela/
Source tier: database
Source content: "Crimideia: a campaign that denounces the criminalisation of funk music and culture in Brazil"
Comparison: Near-verbatim match to the cited source; no second canonical source consulted carries this programme.
Decision: single-source

## Claim 29: "Funk carioca — born in Rio's favelas and disproportionately associated with Black and peripheral Brazilian communities — has faced sustained policing and legal suppression, including show shutdowns and municipal bans"

Source: https://djmag.com/longreads/baile-funk-criminalisation-brazils-funk-scene
Source tier: mainstream
Source content: Multiple canonical sources document the criminalisation of funk: 1990s Rio bills to investigate funk performers and ban events; the 1999 ALERJ parliamentary inquiry into funk; the 2000 law forcing metal detectors, military-police guards, and written government permission for bailes; the 2008 refocus on criminalising bailes; Al Jazeera (2017) on proposals to ban funk; sources attribute the suppression to funk's favela origins and its association with Black and peripheral communities.
Comparison: The suppression, show shutdowns/restrictions, and racialised framing are confirmed by ≥2 canonical sources (DJ Mag longread, Al Jazeera, RioOnWatch series, peer-reviewed Sound Studies scholarship). One imprecision noted: the landmark restrictive laws were Rio *state*-level (ALERJ), not municipal; "municipal bans" is loose but enforcement shutdowns occurred locally and the characterisation is background framing rather than a specific token.
Decision: corroborated

## Claim 30: "Criptofunk is an annual festival connecting technology and funk... It has served as the venue for data_labe's collaboration with Tactical Tech to adapt and localise digital-rights materials"

Source: https://tacticaltech.org/news/stories/data-labe-partner/
Source tier: primary
Source content: "they adapted and localised existing resources which were shown at their annual event Criptofunk," described as "a festival connecting technology and funk."
Comparison: Tactical Tech's own partner story is primary for its own collaboration; festival name, annual cadence, tech-funk framing, and the materials-displayed-at-Criptofunk claims all match.
Decision: primary-sourced

## Claim 31: scalar:sources[6].note — LATINNO lists a 2015 founding year, while data_labe's own sources cite 2016

Source: https://latinno.net/en/case/3355/
Source tier: database
Source content: LATINNO lists data_labe as "2015 – ongoing," characterising it as participatory projects addressing "potentialities and complexities of living in popular territories through data and maps."
Comparison: The frontmatter note accurately reports both the LATINNO 2015 listing and the characterisation; the note's acknowledgment that data_labe's own sources cite 2016 matches Claim 2's evidence. The scalar is an accurate description of its source.
Decision: primary-sourced

## Claim 32: scalar:sources[1].note — "revenue-generating partnerships with Amnesty International and Escola de Jornalismo da Énois"

Source: https://medium.com/data-labe/data-labe-um-laborat%C3%B3rio-de-estrutura-flex%C3%ADvel-1454a6391886
Source tier: primary
Source content: The article mentions establishing revenue-generating partnerships with Amnesty International and Escola de Jornalismo da Énois during the second half of 2017.
Comparison: The scalar matches the entity's own primary account. (This claim appears only in the frontmatter note, not the body.)
Decision: primary-sourced
