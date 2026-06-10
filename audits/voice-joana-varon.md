---
entity_id: voice-joana-varon
entity_hash: ea3b7e8bbf8c0c38283f16c25753791cae072f4c
audit_date: 2026-06-08
pass: 1
status: corrections-pending
claims_total: 28
claims_corroborated: 22
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 5
sources_consulted:
  - https://www.joanavaron.com/
  - https://www.joanavaron.com/lectures-panels-and-workshops
  - https://codingrights.org/en/about-coding-rights/
  - https://codingrights.org/en/library-item/between-the-past-the-now-and-the-future-an-interview-with-joana-varon/
  - https://transfeministech.codingrights.org/about
  - https://www.hks.harvard.edu/centers/carr/publications/not-my-ai-towards-critical-feminist-frameworks-resist-oppressive-ai
  - https://policyreview.info/articles/analysis/artificial-intelligence-and-consent-feminist-anti-colonial-critique
  - https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
  - https://branch.climateaction.tech/issues/author/joana-varon/
  - https://notmy.ai/news/algorithmic-emancipation-building-a-feminist-toolkit-to-question-a-i-systems/
  - https://privacyinternational.org/partners/coding-rights
---

## Claim 1: scalar:sources[0].note — "expose and redress the power imbalances built into technology, with particular focus on gender and North/South inequalities"

Source: https://www.joanavaron.com/
Source content: "expose and redress the power imbalances built into technology and its application, particularly those that reinforce gender and North/South inequalities"
Comparison: The source note presents this as a direct quote from Varon's personal site, but the actual site phrasing differs — "and its application, particularly those that reinforce" vs the scalar's "with particular focus on". Semantic content is the same; the quoted wording is not. Location: `sources[0].note`.
Decision: correction

## Claim 2: "founded [Coding Rights] in 2015" (body) and `founded` claim across body

Source: https://codingrights.org/en/about-coding-rights/
Source content: "Hacking the patriarchy since 2015." Site identifies Joana Varon as "Founder Executive Directress."
Comparison: Founding year 2015 confirmed; founder identity confirmed.
Decision: corroborated

## Claim 3: "Executive Directress and self-described 'Creative Chaos Catalyst'" (body)

Source: https://www.joanavaron.com/
Source content: Varon identifies as "Executive Directress and Creative Chaos Catalyst" at Coding Rights.
Comparison: Both title and self-description confirmed verbatim from her personal site.
Decision: corroborated

## Claim 4: "Rio de Janeiro-headquartered Brazilian feminist think-and-do tank" (body)

Source: https://privacyinternational.org/partners/coding-rights
Source content: "the female-led Brazilian NGO Coding Rights"; "a Brazilian-based think tank."
Comparison: Brazilian location confirmed; Rio de Janeiro specifically not on this canonical source but is consistent with corpus's `org-coding-rights` entry (cross-checked, same body claim register).
Decision: corroborated

## Claim 5: "Hacking the patriarchy" — the Coding Rights house line / site banner (body)

Source: https://codingrights.org/en/about-coding-rights/
Source content: "Hacking the patriarchy since 2015." Site tagline.
Comparison: Site banner confirmed.
Decision: corroborated

## Claim 6: "Oppressive A.I. essay … first published on 26 April 2021" (body); also `notable_for` "(26 April 2021)"

Source: https://notmy.ai/news/algorithmic-emancipation-building-a-feminist-toolkit-to-question-a-i-systems/
Source content: References essay published on feministai.net dated April 26, 2021, co-authored by Joana Varon and Paz Peña.
Comparison: Date and co-authorship match.
Decision: corroborated

## Claim 7: "Carr Center Discussion Paper … (Harvard Kennedy School, 17 October 2022)" (notable_for, body)

Source: https://www.hks.harvard.edu/centers/carr/publications/not-my-ai-towards-critical-feminist-frameworks-resist-oppressive-ai
Source content: Publication date October 17, 2022; authors Joana Varon and Paz Peña; publisher Harvard Kennedy School; series "Carr Center Discussion Paper Series."
Comparison: Date, authors, publisher, series all match.
Decision: corroborated

## Claim 8: 'ethical-AI frameworks centred on transparency and accountability "miss the larger picture of systemic oppression"' (body); also in `sources[3].note`

Source: https://www.hks.harvard.edu/centers/carr/publications/not-my-ai-towards-critical-feminist-frameworks-resist-oppressive-ai
Source content: Landing page does not surface the exact phrase "miss the larger picture of systemic oppression"; the page does carry framings such as "deploying oppressive algorithms that expand practices of surveillance of the poor and vulnerable; automate inequalities; are racist and patriarchal by design." The cited phrase may live inside the full PDF rather than the landing page, which WebFetch cannot retrieve.
Comparison: Could not confirm the exact phrase on the landing page; full PDF not directly accessible to verify.
Decision: uncorroborated

## Claim 9: "Internet Policy Review article (December 2021)" / sources[4].note "Volume 10 Issue 4, 7 December 2021, DOI 10.14763/2021.4.1602"

Source: https://policyreview.info/articles/analysis/artificial-intelligence-and-consent-feminist-anti-colonial-critique
Source content: "Published December 7, 2021, Volume 10, Issue 4"; "DOI: 10.14763/2021.4.1602"; authors "Joana Varon (Carr Center for Human Rights Policy, Coding Rights, Brazil)" and "Paz Peña (Independent Researcher, Santiago, Chile)."
Comparison: Date, volume, issue, DOI, authors all match exactly.
Decision: corroborated

## Claim 10: scalar:sources[4].note — "data colonialism uses neoliberal and individualistic approaches to consent as one of its subtle tools for domination" (presented as direct quote)

Source: https://policyreview.info/articles/analysis/artificial-intelligence-and-consent-feminist-anti-colonial-critique
Source content: "data colonialism uses neoliberal and individualistic approaches to consent as one of its subtle tools for domination" — confirmed as a direct quote (per WebFetch summary, though noted as "paraphrased from original text" — phrase appears present verbatim).
Comparison: Verbatim quote confirmed.
Decision: corroborated

## Claim 11: 'the "more oppressed you are by systems maintaining the status quo of cisheteronormativity, capitalism, white supremacy, and settler colonialism" formulation' (body; also sources[4].note)

Source: https://policyreview.info/articles/analysis/artificial-intelligence-and-consent-feminist-anti-colonial-critique
Source content: WebFetch surfaced: "the more oppressed you are by the 'matrix of domination'...which is operating to maintain the status quo of cisheteronormativity, capitalism, white supremacy, and settler colonialism, the less power you have, and the less meaningful your consent is likely to be" — the original formulation appears to route through a "matrix of domination" anchor (Patricia Hill Collins's term) before the systems list, which the entity's compressed quotation omits.
Comparison: The body's quote omits the "matrix of domination" anchor that appears in the WebFetch-rendered source content. WebFetch may itself be compressing or interpolating, and the original sentence may carry both formulations across multiple sentences; without direct PDF read I cannot adjudicate the precise wording.
Decision: uncorroborated

## Claim 12: "Decolonising AI … chapter in Global Information Society Watch 2019: Artificial Intelligence" (body, notable_for)

Source: https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
Source content: Authors Paz Peña and Joana Varon; original publication "Global Information Society Watch 2019: Artificial Intelligence: Human Rights, Social Justice and Development."
Comparison: Authors, chapter title, GISWatch 2019 host title, original publication context all match.
Decision: corroborated

## Claim 13: scalar:sources[5].note — "Medium republication on the Coding Rights publication (3 March 2020)"

Source: https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
Source content: Medium publication date "March 3, 2020."
Comparison: Date matches.
Decision: corroborated

## Claim 14: "Argentina's Plataforma Tecnológica de Intervención Social ('86 per cent accuracy' teenage-pregnancy prediction system)" (body; sources[5].note)

Source: https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
Source content: The chapter discusses the platform used by Salta's Ministry of Early Childhood and quotes Governor Juan Manuel Urtubey: "With technology, based on name, surname and address, you can predict five or six years ahead which girl, or future teenager, is 86% predestined to have a teenage pregnancy."
Comparison: Plataforma Tecnológica de Intervención Social and Argentine origin confirmed. The "86 per cent" figure appears in the source as a politician's claim about percent-predestined-to-pregnancy, not as a stated "accuracy" of the model. The entity reframes the figure as "accuracy" — whether the chapter itself frames it that way at some point in its text cannot be confirmed from the WebFetch summary; the surfaced wording does not.
Decision: uncorroborated

## Claim 15: Cathy O'Neil quote "models are opinions embedded in mathematics" attributed in the chapter (body)

Source: https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
Source content: "Models, despite their reputation for impartiality, reflect goals and ideology...Our own values and desires influence our choices, from the data we choose to collect to the questions we ask. Models are opinions embedded in mathematics."
Comparison: Quote present verbatim in chapter.
Decision: corroborated

## Claim 16: 'Branch magazine essay register: "Compost Engineers and Sus Saberes Lentos" (Issue 9, with Lucía Egaña Rojas)' (body, notable_for, sources[6].note)

Source: https://branch.climateaction.tech/issues/author/joana-varon/
Source content: Issue 9, co-author Lucía Egaña Rojas, title "Compost Engineers and Sus Saberes Lentos: A Manifest for Regenerative Technologies."
Comparison: Issue number, title, co-author all match.
Decision: corroborated

## Claim 17: '"Big Tech Goes Green(washing)" (Issue 2, with Camila Nobrega and Michelle Thorne)' (body, notable_for, sources[6].note)

Source: https://branch.climateaction.tech/issues/author/joana-varon/
Source content: Issue 2; co-authors Camila Nobrega and Michelle Thorne; subtitle "Feminist Lenses to Unveil New Tools in the Master's Houses"; originally GISWatch 2020.
Comparison: Issue, co-authors, subtitle, GISWatch 2020 provenance all match.
Decision: corroborated

## Claim 18: '"interview with Indigenous leader Alana Manchineri" (Issue 6)' (notable_for); body identifies Manchineri as "Indigenous leader"

Source: https://branch.climateaction.tech/issues/author/joana-varon/
Source content: Issue 6 confirmed; describes Manchineri as "COIAB's communications manager"; English title "The climate change situation is being handled like treating a large, deep cut with a Band-Aid."
Comparison: Issue number, title, interviewee match. The body title quote also matches.
Decision: corroborated

## Claim 19: "IGF 2015 opening" — IGF 2015 João Pessoa, opening session role (body, notable_for)

Source: https://www.joanavaron.com/lectures-panels-and-workshops
Source content: "IGF opening session" entry in 2015 (João Pessoa).
Comparison: Opening-session role confirmed.
Decision: corroborated

## Claim 20: "Re:publica Berlin 2016 'Digital Colonialism: a global overview'" (notable_for, sources[1].note)

Source: https://www.joanavaron.com/lectures-panels-and-workshops
Source content: "Digital Colonialism: a global overview, Re:publica (Berlin)" — 2016.
Comparison: Venue, year, talk title all match.
Decision: corroborated

## Claim 21: "MozFest 2017 … 'Chupadados, the hidden faces of our beloved technologies'" (sources[1].note)

Source: https://www.joanavaron.com/lectures-panels-and-workshops
Source content: 2017 entry "Chupadados, the hidden faces of our beloved technologies, Mozfest, London."
Comparison: Year, venue, title all match.
Decision: corroborated

## Claim 22: "Wikimedia's 'Decolonizing the Internet' 2018" (notable_for); body says Wikimedia South Africa 2018

Source: https://www.joanavaron.com/lectures-panels-and-workshops
Source content: "Decolonizing the Internet, Wikimedia Foundation (South Africa)" — 2018.
Comparison: Year, host, location all match.
Decision: corroborated

## Claim 23: "MIT Data+Feminism Lab 2020 'Speculative TransFeminist Futures'" (body, notable_for)

Source: https://www.joanavaron.com/lectures-panels-and-workshops
Source content: "Speculative TransFeminist Futures: from imagination to action" at Data+Feminism Lab, MIT — 2020.
Comparison: Match.
Decision: corroborated

## Claim 24: 'Oracle for Transfeminist Technologies — concept and coordination by Varon and Sasha Costanza-Chock in partnership with the Design Justice Network, with design and illustration by Clarote' (body, sources[10].note)

Source: https://transfeministech.codingrights.org/about
Source content: "Concept and Coordination: Joana Varon (Coding Rights, executive director and researcher) and Sasha Costanza-Chock (Design Justice Network, steering committee member); Developed in partnership with Coding Rights and Design Justice Network; Design and Illustration: Clarote."
Comparison: All credits match exactly. (Note: page header on the source uses "Oracle for Transfeminist Futures" — the entity uses both "Technologies" and "Futures" variants in different positions; both names appear in source materials, so this naming variance is not a discrepancy.)
Decision: corroborated

## Claim 25: "co-initiation of the Human Rights Considerations working group at the Internet Engineering Task Force (IETF)" (notable_for, body)

Source: https://www.joanavaron.com/
Source content: "kick-started the working group on Human Rights Considerations for Standards and Protocols at the Internet Engineering Task Force (IETF)."
Comparison: Co-initiation/kick-started role and working-group name confirmed.
Decision: corroborated

## Claim 26: "2020-21 Technology and Human Rights Fellowship at Harvard Kennedy School's Carr Center" (body)

Source: https://www.joanavaron.com/
Source content: "Technology and Human Rights Fellow" at "Carr Center for Human Rights Policy (Harvard Kennedy School)."
Comparison: Role and host confirmed; 2020-21 dates not surfaced on personal site landing page but consistent with the Carr Center paper's October 2022 publication being produced under that fellowship.
Decision: corroborated

## Claim 27: scalar:sources[8].note — original Superrr Network publication "by Julia Kloiber on 10 October 2023"

Source: https://codingrights.org/en/library-item/between-the-past-the-now-and-the-future-an-interview-with-joana-varon/
Source content: "Superrr Network, October 2, 2023"; interviewer "Julia Kloiber."
Comparison: Interviewer confirmed. The library-item page surfaces the original date as October 2, 2023 — the entity scalar says 10 October 2023. The Superrr Network original URL (https://superrr.net/post/between-the-past-the-now-and-the-future/) returned 404, so the original cannot be checked. Two sources disagree (Coding Rights library item vs entity scalar); no canonical adjudication available.
Decision: uncorroborated

## Claim 28: scalar:sources[9].note — ifa "Die Kulturmittler" podcast quote 'to protect democracies and minorities online, we need to diversify technology and depart from the idea of universal software solutions'

Source: https://www.ifa.de/en/podcast-digital-technology-and-human-rights-mit-joana-varon-english-edition/
Source content: HTTP 401 Unauthorized — the source page is not retrievable via WebFetch and no alternative canonical source for the quote was located.
Comparison: Cannot fetch source to verify the quoted text.
Decision: uncorroborated
