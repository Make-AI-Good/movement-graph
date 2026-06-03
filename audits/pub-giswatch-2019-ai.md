---
entity_id: pub-giswatch-2019-ai
entity_hash: fece9d5b2f60b4839abc7b25c6181b26ff9fa394
audit_date: 2026-06-02
pass: 1
status: discrepancy
claims_total: 20
claims_verified: 17
claims_discrepancy: 1
claims_unverifiable: 2
sources_consulted:
  - https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
  - https://www.apc.org/en/pubs/global-information-society-watch-2019-artificial-intelligence-human-rights-social-justice-and
  - https://www.apc.org/en/news/giswatch-launch-internet-governance-forum-artificial-intelligence-and-human-rights-forefront
  - https://www.apc.org/en/news/what-have-we-learned-revisiting-giswatch-edition-artificial-intelligence
  - https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
---

## Claim 1: published "by the Association for Progressive Communications (APC) and ARTICLE 19"

Source: https://www.apc.org/en/pubs/global-information-society-watch-2019-artificial-intelligence-human-rights-social-justice-and
Source content: "APC and ARTICLE 19" named as the publishers on APC's own publication page; the launch news article also reads "The Association for Progressive Communications (APC) and ARTICLE 19 jointly launched the report."
Comparison: body's co-publisher pair matches the canonical APC pages exactly.
Decision: verified

## Claim 2: published "on 28 November 2019" and "launched at the Internet Governance Forum in Berlin the same day"

Source: https://www.apc.org/en/news/giswatch-launch-internet-governance-forum-artificial-intelligence-and-human-rights-forefront
Source content: "The 2019 GISWatch report was launched on Thursday, 28 November 2019 at the Internet Governance Forum in Berlin."
Comparison: date and venue match exactly.
Decision: verified

## Claim 3: "Edited by Valeria Betancourt and Mallory Knodel"

Source: https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source content: GISWatch's own 2019 publication page names "Valeria Betancourt and Mallory Knodel" as the editor pair.
Comparison: editor names and pairing match exactly.
Decision: verified

## Claim 4: "40 country reports, three regional reports, and eight thematic reports"

Source: https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source content: page lists "Thematic reports: 8 / Regional reports: 3 / Country reports: 40". APC publication page confirms "40 country reports", "three regional reports", "eight thematic reports".
Comparison: counts match exactly across both canonical sources.
Decision: verified

## Claim 5: country-report register spans "Benin, Argentina, India, Russia, Ukraine, and 35 other jurisdictions"

Source: https://www.apc.org/en/pubs/global-information-society-watch-2019-artificial-intelligence-human-rights-social-justice-and
Source content: APC publication page explicitly mentions Benin, Argentina, India, Russia, and Ukraine among the country reports. With total country count confirmed at 40 (Claim 4), the residual "35 other jurisdictions" follows arithmetically.
Comparison: named countries verified; the "35 other" framing is arithmetic from the verified total.
Decision: verified

## Claim 6: "regional reports cover Africa, the Caribbean, and Latin America"

Source: https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source content: GISWatch publication page identifies three regional reports covering "Africa, Caribbean, Latin America".
Comparison: regional coverage matches exactly.
Decision: verified

## Claim 7: eight thematic reports address "data governance, food sovereignty, AI in the workplace, autonomous weapons systems ('killer robots')"

Source: https://www.apc.org/en/pubs/global-information-society-watch-2019-artificial-intelligence-human-rights-social-justice-and
Source content: APC publication page names four thematic-report subjects: "data governance, food sovereignty, AI in the workplace, and autonomous weapons (referred to as 'killer robots')".
Comparison: the four named thematic topics match the canonical source's enumeration exactly.
Decision: verified

## Claim 8: "released in 13 language versions"

Source: https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source content: GISWatch's publication page lists fourteen language editions as switcher links — "English, Arabic, Bos/Cro/Ser/Mne, Bulgarian, Catalan, French, Hindi, Hungarian, Japanese, Portuguese Brazil, Romanian, Russian, Spanish, Tagalog". No explicit count phrase ("13 languages", "14 languages") appears on the page.
Comparison: the body's specific count of 13 does not match the 14 distinct language-switcher entries the canonical publisher page exposes. The frontmatter source-note at `sources[0].note` carries the identical "13 language versions" wording and inherits the same discrepancy. This is the single-token form the Editor's Audit-discrepancy backfill act can apply ("13" → "14") in both body and the named frontmatter scalar.
Decision: discrepancy

## Claim 9: language editions include "English, Spanish, French, Arabic, Russian, Brazilian Portuguese, and Japanese"

Source: https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source content: the language-switcher list on GISWatch's page includes English, Spanish, French, Arabic, Russian, Portuguese (Brazil), and Japanese.
Comparison: each named language appears in the canonical source's enumeration.
Decision: verified

## Claim 10: "Creative Commons Attribution 4.0 licence"

Source: https://www.apc.org/en/pubs/global-information-society-watch-2019-artificial-intelligence-human-rights-social-justice-and
Source content: APC's publication page reads "Creative Commons Attribution 4.0 International (CC BY 4.0)".
Comparison: licence matches exactly.
Decision: verified

## Claim 11: "print ISBN 978-92-95113-12-1"

Source: https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source content: ISBN-10 "9295113128" surfaced on the GISWatch publication page via the Amazon listing link; the ISBN-13 with check-digit "978-92-95113-12-1" is the mechanical conversion of that ISBN-10. The frontmatter source-note at `sources[7].note` independently records "ISBN-10 9295113128 / ISBN-13 978-9295113121".
Comparison: ISBN-13 matches the canonical ISBN-10 by conversion; both registers (ISBN-10 and ISBN-13) are mutually consistent.
Decision: verified

## Claim 12: editors' preface "provides a perspective from the global South on the application of AI to our everyday lives"

Source: https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source content: the preface (extracted from the page) reads "provides a perspective from the global South on the application of AI to our everyday lives."
Comparison: quoted phrase appears verbatim in canonical preface.
Decision: verified

## Claim 13: preface "how algorithmic decision making impact on marginalised people and the poor"

Source: https://www.giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source content: preface text on the canonical page reads "How does algorithmic decision making impact on marginalised people and the poor?".
Comparison: body's quote is the declarative form of the canonical question phrasing; the load-bearing content (algorithmic decision making, marginalised people, the poor) matches exactly.
Decision: verified

## Claim 14: APC retrospective quotes — "conversations on AI have been driven largely by Western and Global North predictions" and "the very real effects of AI are also more diverse"

Source: https://www.apc.org/en/news/what-have-we-learned-revisiting-giswatch-edition-artificial-intelligence
Source content: the APC retrospective notes that "conversations on AI have been driven largely by Western and Global North predictions" while "the very real effects of AI are also more diverse" across different jurisdictions.
Comparison: both quotes match the canonical retrospective verbatim.
Decision: verified

## Claim 15: "Joana Varon of Coding Rights and Paz Peña co-authored the *Decolonising AI: A transfeminist approach to data and social justice* thematic chapter"

Source: https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
Source content: Medium republication credits "Paz Peña and Joana Varon" as the authors and states "This report was originally published as part of a larger compilation: 'Global Information Society Watch 2019: Artificial intelligence: Human rights, social justice and development'".
Comparison: author pairing, chapter title, and GISWatch 2019 origin all match.
Decision: verified

## Claim 16: scalar:sources[5].note "the '86 per cent accuracy' teenage-pregnancy prediction system deployed in Salta province" (also body Claim 17)

Source: https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
Source content: the chapter quotes Salta governor Juan Manuel Urtubey: "With technology, based on name, surname and address, you can predict five or six years ahead which girl, or future teenager, is 86% predestined to have a teenage pregnancy."
Comparison: the 86% figure and Salta deployment are confirmed by the canonical source, but the body's quoted framing "'86 per cent accuracy'" does not appear in the cited chapter — the source frames the 86% as a politician's promotional "predestined" prediction claim, not as a measured "accuracy" of the system. The quoted phrase as written in the body is not present in the cited canonical source. Same wording mirrors in `sources[5].note` (frontmatter scalar). Re-quoting the figure without the "accuracy" frame, or removing the quotation marks to render the phrasing as paraphrase, is the prose-judgment fix; this is beyond a single-token mechanical replacement.
Decision: unverifiable

## Claim 17: Cathy O'Neil "models are opinions embedded in mathematics"

Source: https://medium.com/codingrights/decolonising-ai-a-transfeminist-approach-to-data-and-social-justice-a5e52ac72a96
Source content: chapter reads "Models are opinions embedded in mathematics."
Comparison: quote matches verbatim.
Decision: verified

## Claim 18: IGF Berlin launch panel surfaced "Rachel Adams of the Human Sciences Research Council in South Africa, Alex Comninos on the AI-and-sustainable-human-development thematic, Daniel Mwesigwa of CIPESA Uganda on AI-enabled surveillance tools, and Varon herself on the transfeminist-decolonial thematic"; "APC senior advisor Anriette Esterhuysen framing the wider editorial question of where AI policy intervention points 'need to come from' — 'nationally driven' or via 'global standards'"

Source: https://www.apc.org/en/news/giswatch-launch-internet-governance-forum-artificial-intelligence-and-human-rights-forefront
Source content: "Rachel Adams, Human Sciences Research Council, South Africa"; "Alex Comninos (author of thematic report on AI for sustainable human development)"; "Daniel Mwesigwa, CIPESA (wrote report on modern surveillance tools in Uganda)"; "Joana Varon, Coding Rights, Brazil (author of chapter on decolonising AI through transfeminist approach)". Anriette Esterhuysen: "When you were looking at policy interventions, and the required policy and regulatory interventions, where do you think they need to come from? Do they need to be nationally driven? Is there a need for global standards?"
Comparison: every named panellist and affiliation matches the canonical launch article; the Esterhuysen quote-fragments ("need to come from", "nationally driven", "global standards") all appear verbatim in the canonical source.
Decision: verified

## Claim 19: four exemplar country-report contributions — "Digital Empowerment Foundation in India on caste, gender, and religious bias in AI deployments in education; Cooperativa Sulá Batsú in Costa Rica on citizen-organisation participation in healthcare AI decision-making; Bytes for All Bangladesh on automation's impact on garment-worker labour; and Nodo TAU in Argentina on union responses to AI in working conditions"

Source: https://www.apc.org/en/news/what-have-we-learned-revisiting-giswatch-edition-artificial-intelligence
Source content: the APC retrospective explicitly summarises each — "India (Digital Empowerment Foundation): Highlighted how AI in education perpetuates bias based on caste, gender, and religion"; "Costa Rica (Cooperativa Sulá Batsú): … healthcare AI integration … requires meaningful citizen participation"; "Bangladesh (Bytes for All Bangladesh): Addressed automation's threat to garment workers"; "Argentina (Nodo TAU): Examined labor unions' role in addressing AI's impact".
Comparison: all four exemplar attributions match the canonical retrospective in topic, country, and organisation.
Decision: verified

## Claim 20: "GISWatch annual is APC's flagship Global-South-civil-society-network publication produced continuously from 2007"

Source: no canonical source found
Source content: none of the five sources fetched in this pass explicitly attests the 2007 start year of the GISWatch annual cycle; the entity's own cited sources (APC and GISWatch) describe the 2019 edition but do not quote a launch year for the overall cycle.
Comparison: cannot confirm "from 2007" against a fetched canonical source in this pass. The 2007 origin year may be verifiable on the GISWatch landing page or APC's GISWatch hub, but neither was traversed for this specific claim in this pass.
Decision: unverifiable
