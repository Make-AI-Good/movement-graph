---
entity_id: voice-beatriz-busaniche
entity_hash: 863006e024f86313fcb3a302830e55884fe55ce0
audit_date: 2026-06-10
pass: 2
status: corrections-pending
claims_total: 23
claims_corroborated: 20
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 2
sources_consulted:
  - https://2020.allthingsopen.org/speakers/beatriz-busaniche/
  - https://blog.okfn.org/2023/04/20/beatriz-busaniche-hate-speech-is-sustained-by-stereotypes-which-are-often-driven-by-ai/
  - https://aplusalliance.org/e-d-i-a-a-democratising-toolkit-to-audit-biases-and-stereotypes-in-language-models/
  - https://aclanthology.org/2023.c3nlp-1.10/
  - https://www.vialibre.org.ar/en/we-participated-in-the-iachr-hearing-artificial-intelligence-and-human-rights/
  - https://www.vialibre.org.ar/en/a-year-of-growth-and-major-challenges/
  - https://www.vialibre.org.ar/en/13964-2/
  - https://www.vialibre.org.ar/en/home/
  - https://www.vialibre.org.ar/en/about-us/
  - https://www.vialibre.org.ar/edia-sesgos-de-genero/
  - https://ia.vialibre.org.ar/en/home/
  - https://ia.vialibre.org.ar/en/2024/06/05/a-tool-to-overcome-technical-barriers-for-bias-assessment-in-human-language-technologies/
  - https://www.vialibre.org.ar/en/international-recognition-one-of-our-papers-among-the-highlights-of-iclr-2026/
  - https://github.com/fvialibre/edia
  - https://arxiv.org/abs/2505.24712
  - https://aclanthology.org/2025.emnlp-main.1275/
  - https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/
  - https://srfp.odia.legal/
  - https://www.tedic.org/en/ai_iachr2025/
  - https://es.wikipedia.org/wiki/Wikimedia_Argentina
  - https://es.wikipedia.org/wiki/Sistema_de_Boleta_%C3%9Anica_Electr%C3%B3nica
  - https://dl.acm.org/doi/10.1145/3653322
---

Pass-2 re-audit (entity unchanged since pass 1; queued via `[work]` inbox item, Fable 5 A/B
batch 2). Pass 1 left 9 claims unverifiable; this pass fetched secondary canonical sources
and resolved 7 of them (6 to verified, 1 to discrepancy). Note: pass 1's frontmatter counts
(14 V / 8 U) did not match its own per-claim decisions (13 V / 9 U); corrected by this
overwrite.

## Claim 1: "president of [Fundación Vía Libre]"

Source: https://2020.allthingsopen.org/speakers/beatriz-busaniche/
Source content: "President at Fundación Vía Libre - Argentina"
Comparison: Body matches source; OKFN interview (2023) independently confirms the role.
Decision: corroborated

## Claim 2: "Córdoba-headquartered Argentine civil-society organisation" (Fundación Vía Libre)

Source: https://www.vialibre.org.ar/en/about-us/
Source content: "Fundación Vía Libre is a non-profit civil organization established in Córdoba, Argentina, in 2000."
Comparison: Body matches the organisation's own about page (fetched this session).
Decision: corroborated

## Claim 3: self-description "an activist for Free Software, free culture and human rights in environments mediated by ICTs"

Source: https://2020.allthingsopen.org/speakers/beatriz-busaniche/
Source content: "She is an activist for Free Software, free culture and human rights in environments mediated by ICTs."
Comparison: Verbatim quote match.
Decision: corroborated

## Claim 4: "co-founded Wikimedia Argentina in 2007"

Source: https://blog.okfn.org/2023/04/20/beatriz-busaniche-hate-speech-is-sustained-by-stereotypes-which-are-often-driven-by-ai/; https://es.wikipedia.org/wiki/Wikimedia_Argentina
Source content: OKFN: "co-founder of the Argentine chapter of Wikimedia". es.wikipedia: "la Asamblea fundacional de Wikimedia Argentina tuvo lugar el 1 de septiembre de 2007 con 28 miembros fundadores."
Comparison: Co-founder role from OKFN (primary interview); the 2007 founding date is a named-entity definitional fact for which Wikipedia-alone is sufficient per the source rule. Both halves match.
Decision: corroborated

## Claim 5: "long-standing member of the Creative Commons Argentina team"

Source: https://blog.okfn.org/2023/04/20/beatriz-busaniche-hate-speech-is-sustained-by-stereotypes-which-are-often-driven-by-ai/
Source content: "a member of the Creative Commons Argentina team"
Comparison: Body matches source; "long-standing" within paraphrase tolerance given her two-decade public record.
Decision: corroborated

## Claim 6: "teaching texts — used in her courses at the Universidad de Buenos Aires, Universidad Torcuato Di Tella, and FLACSO"

Source: https://2020.allthingsopen.org/speakers/beatriz-busaniche/
Source content: "a professor at the University of Buenos Aires and at Flacso Argentina" — the source confirms two of the three academic posts but says nothing about which texts she teaches from.
Comparison: The academic posts are substantially confirmed (UBA, FLACSO; Di Tella only via Wikipedia, which is tiebreaker-only for living-person employment specifics). The specific claim that *Monopolios Artificiales sobre Bienes Intangibles* and *Propiedad Intelectual y Derechos Humanos* are the teaching texts used in those courses is an interpretive overlay no consulted source establishes.
Decision: uncorroborated

## Claim 7: "Boleta Única Electrónica (BUE) electronic voting machines introduced in Buenos Aires City elections from 2015 onward"

Source: https://es.wikipedia.org/wiki/Sistema_de_Boleta_%C3%9Anica_Electr%C3%B3nica; https://www.vialibre.org.ar/en/about-us/
Source content: es.wikipedia (via search-result content): "El sistema salteño fue luego utilizado en las elecciones del 2014 en Ecuador y en 2015 en las elecciones a Jefe de Gobierno de ciudad autónoma de Buenos Aires." Vía Libre about-us confirms the campaign context: monitoring of "the adoption of electoral technologies, including electronic voting machines" since 2003, hashtag "#NoAlVotoElectrónico (#NoEVoting)".
Comparison: BUE use in the 2015 Buenos Aires City elections is a date-of-public-event fact for which Wikipedia-alone is sufficient per the source rule; the named system, jurisdiction, and 2015 date all match. (Resolves pass-1 unverifiable.)
Decision: corroborated

## Claim 8: "Ekoparty's lifetime-achievement recognition of Vía Libre's electronic-voting security audit work"

Source: https://www.vialibre.org.ar/en/a-year-of-growth-and-major-challenges/
Source content: "the first lifetime achievement award presented by Ekoparty as part of its event celebrating 25 years of the most important security conference in the region" — the source does not say which body of work the award recognised.
Comparison: The award is confirmed; its attribution specifically to electronic-voting security audit work (rather than Vía Libre's security work generally) is an interpretive overlay the source does not establish.
Decision: uncorroborated

## Claim 9: "hate speech is sustained by stereotypes, which are often driven by AI"

Source: https://blog.okfn.org/2023/04/20/beatriz-busaniche-hate-speech-is-sustained-by-stereotypes-which-are-often-driven-by-ai/
Source content: Article title quotes her verbatim: "Hate speech is sustained by stereotypes, which are often driven by AI" (OKFN interview, 20 April 2023).
Comparison: Verbatim quote match, correctly attributed and dated.
Decision: corroborated

## Claim 10: "EDIA — **E**stereotipos y **D**iscriminación en **I**nteligencias **A**rtificiales"

Source: https://www.vialibre.org.ar/edia-sesgos-de-genero/; https://github.com/fvialibre/edia
Source content: Vía Libre's own page: "La herramienta EDIA (Estereotipos y Discriminación en Inteligencia Artificial) fue desarrollada por el equipo de Etica en IA". GitHub repo (fvialibre/edia) English title: "EDIA: Stereotypes and Discrimination in Artificial Intelligence".
Comparison: The body expands the acronym with plural "Inteligencias Artificiales"; the developer's own canonical expansion is singular "Inteligencia Artificial" (both the Spanish page and the English repo title agree). Fix location: body section "## \"Hate speech is sustained by stereotypes...\"", second paragraph, bolded acronym expansion — single replacement "Inteligencias Artificiales" → "Inteligencia Artificial". (Resolves pass-1 unverifiable to a citable discrepancy.)
Decision: correction

## Claim 11: "Co-developed alongside Laura Alonso Alemany and Luciana Benotti of the Universidad Nacional de Córdoba's FAMAF faculty"

Source: https://ia.vialibre.org.ar/en/2024/06/05/a-tool-to-overcome-technical-barriers-for-bias-assessment-in-human-language-technologies/; https://aplusalliance.org/e-d-i-a-a-democratising-toolkit-to-audit-biases-and-stereotypes-in-language-models/
Source content: Vía Libre's own IA site lists the EDIA authors as "Laura Alonso Alemany, Luciana Benotti, Lucía González, Hernán Maina, Sección de Computación, FAMAF, Universidad Nacional de Córdoba, Fundación Via Libre Argentina". A+ Alliance lists "Laura Alonso Alemany, Luciana Benotti, Beatriz Busaniche (Fundación Vía Libre, Argentina)" as the team.
Comparison: Team composition and the FAMAF / Universidad Nacional de Córdoba affiliation both confirmed by the project's own publication page. (Resolves pass-1 unverifiable.)
Decision: corroborated

## Claim 12: EDIA "supporting English and Spanish base models out of the box"

Source: https://github.com/fvialibre/edia
Source content: "The tool has models in Spanish and English to work with and explore biases in different languages"; the repo setup downloads English and Spanish embeddings and vocabulary files by default.
Comparison: Vía Libre's own repository (primary source) confirms Spanish and English models ship with the tool; "out of the box" is within paraphrase tolerance of default-provided models. (Resolves pass-1 unverifiable.)
Decision: corroborated

## Claim 13: "selected in 2024 as one of five Mozilla Data Futures Lab Infrastructure Fund awardees"

Source: https://aplusalliance.org/e-d-i-a-a-democratising-toolkit-to-audit-biases-and-stereotypes-in-language-models/
Source content: "E.D.I.A. has recently been selected as one of five funded projects in Mozilla's Data Futures Lab 2024 Infrastructure Fund Award."
Comparison: Count ("one of five"), year (2024), and award name all match.
Decision: corroborated

## Claim 14: "in 2025 won the Mozilla Festival audience-vote impact award in Barcelona"

Source: https://www.vialibre.org.ar/en/a-year-of-growth-and-major-challenges/
Source content: "We crowned that achievement with the public vote for the most impactful project at the Mozilla Festival in Barcelona." (2025 year-in-review)
Comparison: "Audience-vote" paraphrases "public vote"; "impact award" paraphrases "most impactful project"; Barcelona and 2025 match the source and its year-in-review framing.
Decision: corroborated

## Claim 15: "2023 ACL workshop paper *Bias assessment for experts in discrimination, not in computer science*"

Source: https://aclanthology.org/2023.c3nlp-1.10/
Source content: Title "Bias assessment for experts in discrimination, not in computer science", First Workshop on Cross-Cultural Considerations in NLP (C3NLP), May 2023; authors include Laura Alonso Alemany, Luciana Benotti, and Beatriz Busaniche. Abstract: "In this paper we present EDIA, a tool that facilitates that experts in discrimination explore social biases in word embeddings and masked language models."
Comparison: Title, year, venue, and Busaniche co-authorship all match; the abstract also ties the paper to EDIA as the body claims.
Decision: corroborated

## Claim 16: "2024 Communications of the ACM article *Exploring Stereotypes and Biases in Language Technologies in Latin America*"

Source: https://dl.acm.org/doi/10.1145/3653322
Source content: "Exploring Stereotypes and Biases in Language Technologies in Latin America", Communications of the ACM, Vol. 67 No. 8 (August 2024), pp. 54–56; authors Hernán Maina, Laura Alonso Alemany, Guido Ivetta, Mariela Rajngewerc, Beatriz Busaniche, Luciana Benotti.
Comparison: Title, venue, year, and EDIA-team co-authorship confirmed against the ACM Digital Library record (the entity-cited cacm.acm.org author page returned HTTP 403 this session; the publisher's DOI record is the stronger primary record). Strengthens pass 1, which had verified this claim without a fetch.
Decision: corroborated

## Claim 17: HESEIA = "a community-based dataset for evaluating social biases in large language models, co-designed in real school settings in Latin America"

Source: https://www.vialibre.org.ar/en/home/
Source content: "HESEIA: A community-based dataset for evaluating social biases in large language models, co-designed in real school settings in Latin America"
Comparison: Verbatim quote match against the Vía Libre home page, fetched this session.
Decision: corroborated

## Claim 18: "June 2024 launch ... extension course *Tools to Explore Biases and Stereotypes of Artificial Intelligence in the Classroom* ... more than 500 registrants ... 34.1% from outside the provincial capital ... 55.6% with no prior AI-tool experience" (+ sources[9].note: FAMAF and Córdoba Ministry of Education partnership; instructors Benotti and Echeveste)

Source: https://www.vialibre.org.ar/en/13964-2/
Source content: "With more than 500 registrants, on Saturday, June 1, the extension course 'Tools to Explore Biases and Stereotypes of Artificial Intelligence in the Classroom' was launched"; "34.1% of the registered teachers are from outside the provincial capital"; "55.6% acknowledge that they have never used tools with artificial intelligence"; partners "the Faculty of Mathematics, Astronomy, Physics, and Computing (FAMAF), the Vía Libre Foundation, and the Ministry of Education of the Province of Córdoba"; led by "Luciana Benotti and Emilia Echeveste".
Comparison: All quantitative, temporal, and identification claims — body and the scalar at sources[9].note — match the source verbatim or near-verbatim.
Decision: corroborated

## Claim 19: "HESEIA / EDIA combination was accepted at EMNLP 2025"

Source: https://aclanthology.org/2025.emnlp-main.1275/; https://www.vialibre.org.ar/en/a-year-of-growth-and-major-challenges/
Source content: ACL Anthology carries "HESEIA: A community-based dataset for evaluating social biases in large language models, co-designed in real school settings in Latin America" as EMNLP 2025 main-conference paper 1275 (Busaniche and Benotti among authors per the arXiv record at arxiv.org/abs/2505.24712). Vía Libre year-in-review: "Our work and academic output was selected by a very demanding jury for presentation at EMNLP2025".
Comparison: The HESEIA paper's EMNLP 2025 acceptance is now confirmed by the conference's own anthology record, closing the attribution gap pass 1 noted.
Decision: corroborated

## Claim 20: "a related paper recognised at ICLR 2026"

Source: https://www.vialibre.org.ar/en/international-recognition-one-of-our-papers-among-the-highlights-of-iclr-2026/
Source content: Sofía Martinelli presented research developed with Luciana Benotti and Guido Ivetta at ICLR 2026; the paper was "selected for an oral presentation at the workshop, a distinction awarded to only 8 papers out of the 206 accepted submissions" and received "the Outstanding Paper recognition, granted to the most notable works presented in the oral session."
Comparison: Vía Libre's own announcement confirms a paper recognised at ICLR 2026 by HESEIA-team authors (Benotti, Ivetta) on bias evaluation in reasoning models — "related paper" holds within paraphrase tolerance. (Resolves pass-1 unverifiable.)
Decision: corroborated

## Claim 21: "the wider regional civil-society submission co-signed by seventeen Latin American organisations" (IACHR hearing)

Source: https://www.tedic.org/en/ai_iachr2025/; https://www.vialibre.org.ar/en/we-participated-in-the-iachr-hearing-artificial-intelligence-and-human-rights/
Source content: TEDIC: "Derechos Digitales de América Latina led the drafting of the region's civil society contributions, a collaborative effort involving 17 organizations." The Vía Libre page separately lists twelve organisations under "Civil Society Organisations that participated in the session."
Comparison: The seventeen figure attaches to the regional written contribution (TEDIC, a participating organisation's primary account), which is consistent with twelve organisations participating in the hearing session itself — the two counts describe different things and do not conflict. Body matches. (Resolves pass-1 unverifiable.)
Decision: corroborated

## Claim 22: "multi-year challenge to the City of Buenos Aires's Fugitive Facial Recognition System (SRFP) — in which ODIA's *amparo* lawsuit (joined by Vía Libre as *amicus curiae*) had produced the September 2022 first-instance unconstitutionality ruling and the April 2023 Court of Appeals confirmation"

Source: https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/; https://srfp.odia.legal/
Source content: CELS: "In 2020, ODIA initiated an amparo action in which it challenged the constitutionality and legality of the regulations"; "in September 2022 she ruled that the implementation of the SRFP by the Buenos Aires government was unconstitutional"; confirmed by "the Court of Appeals on April 28" (2023). ODIA's own case site lists Fundación Vía Libre among the amici curiae filings.
Comparison: Named system (SRFP), ODIA's amparo, Vía Libre's amicus role, the September 2022 first-instance ruling, and the April 2023 appellate confirmation are each confirmed by a primary or canonical source. (Resolves pass-1 unverifiable.)
Decision: corroborated

## Claim 23: "On 7 March 2025 she appeared at the Inter-American Commission on Human Rights' regional hearing ... on behalf of a four-organisation Argentine civil-society coalition — CELS, Democracia en Red, Fundación Vía Libre, and ODIA — raising concerns about the Argentine state's adoption of predictive-algorithm surveillance technologies"

Source: https://www.vialibre.org.ar/en/we-participated-in-the-iachr-hearing-artificial-intelligence-and-human-rights/
Source content: "On 7 March, we participated virtually in the regional thematic hearing" (2025); Busaniche spoke for the consortium of Centro de Estudios Legales y Sociales (CELS), Democracia en Red, Fundación Vía Libre, and Observatorio de Derecho Informático Argentino (ODIA); the presentation expressed alarm about "the use of surveillance technologies based on predictive algorithms by state actors" and the lack of "adequate legislation to regulate the incorporation of AI in these tasks".
Comparison: Date, speaker role, the four named coalition organisations, and the predictive-algorithm surveillance concern all match. (New claim this pass — pass 1 carried no explicit entry for the hearing's core facts.)
Decision: corroborated
