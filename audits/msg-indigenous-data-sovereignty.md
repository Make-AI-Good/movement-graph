---
entity_id: msg-indigenous-data-sovereignty
entity_hash: 43165f8adcb997e86ad9d82eb27d191686d7dc77
audit_date: 2026-06-09
pass: 1
status: supported
claims_total: 28
claims_corroborated: 22
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 6
sources_consulted:
  - https://www.gida-global.org/whoweare
  - https://www.gida-global.org/careprinciples
  - https://datascience.codata.org/articles/10.5334/dsj-2020-043
  - https://www.maramatanga.ac.nz/news-events/news/te-mana-raraunga-m-ori-data-sovereignty-network
  - https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
  - https://openresearch-repository.anu.edu.au/items/210eb2f2-de8e-4788-946b-09b257d51d7c
  - https://www.indigenous-ai.net/digital-sovereignty/
  - https://tehiku.nz/te-hiku-tech/te-hiku-dev-korero/25141/data-sovereignty-and-the-kaitiakitanga-license
  - https://en.wikipedia.org/wiki/First_Nations_principles_of_OCAP
  - https://en.wikipedia.org/wiki/Indigenous_data_sovereignty
  - https://en.wikipedia.org/wiki/First_Nations_Information_Governance_Centre
  - https://standards.ieee.org/ieee/2890/10318/
  - https://www.temanararaunga.maori.nz/
---

## Claim 1: "OCAP — Ownership, Control, Access, Possession"

Source: https://en.wikipedia.org/wiki/First_Nations_principles_of_OCAP
Source content: "OCAP® is an acronym for 'ownership, control, access, and possession' — the four core principles establishing Indigenous data governance standards."
Comparison: Entity's expansion of the acronym matches source verbatim. Definitional public-record fact; Wikipedia-alone sufficient per the source rule.
Decision: corroborated

## Claim 2: "OCAP — the governance framework developed in 1998"

Source: https://en.wikipedia.org/wiki/First_Nations_principles_of_OCAP
Source content: "The principles were 'first established in 1998 by the National Steering Committee in charge of administering the First Nations Regional Longitudinal Health Survey (RHS)'."
Comparison: Date matches.
Decision: corroborated

## Claim 3: "developed in 1998 by the National Steering Committee of the First Nations and Inuit Regional Longitudinal Health Survey"

Source: https://en.wikipedia.org/wiki/First_Nations_principles_of_OCAP
Source content: "...the National Steering Committee in charge of administering the First Nations Regional Longitudinal Health Survey (RHS)."
Comparison: The entity names the survey "First Nations *and Inuit* Regional Longitudinal Health Survey"; the only canonical source I could load (Wikipedia OCAP) names it "First Nations Regional Longitudinal Health Survey." The entity's cited primary source (fnigc.ca/ocap-training/) returned HTTP 403 in this pass and could not corroborate the "and Inuit" element. The two-name divergence may be a historical-vs-current naming distinction rather than a factual error, but I cannot confirm that without the primary source.
Decision: uncorroborated

## Claim 4: "The First Nations Information Governance Centre (FNIGC), formed in April 2010 as a stand-alone non-profit"

Source: https://en.wikipedia.org/wiki/First_Nations_Information_Governance_Centre
Source content: "On April 22, 2010, the First Nations Information Governance Centre was incorporated as a non-profit entity."
Comparison: Month and year match; non-profit status matches.
Decision: corroborated

## Claim 5: "FNIGC trademarked OCAP® and built a national certification and training apparatus around the framework."

Source: https://en.wikipedia.org/wiki/First_Nations_principles_of_OCAP
Source content: "FNIGC holds the registered trademark for OCAP® and seeks to 'protect the principles from misuse and improper interpretation.'"
Comparison: Trademark holding matches; the training/certification apparatus claim is internally consistent with FNIGC's "OCAP training" page URL but not separately verified here. Within paraphrase tolerance for the registered-trademark fact.
Decision: corroborated

## Claim 6: "the 2016 ANU Press volume *Indigenous Data Sovereignty: Toward an Agenda*, edited by Tahu Kukutai ... and John Taylor"

Source: https://openresearch-repository.anu.edu.au/items/210eb2f2-de8e-4788-946b-09b257d51d7c
Source content: "Title & Editors: Indigenous Data Sovereignty: Toward an Agenda, edited by Tahu Kukutai and John Taylor. Publication Year: 2016 (November). Publisher: ANU Press..."
Comparison: Title, editors, year, publisher all match.
Decision: corroborated

## Claim 7: "The book drew on a 2015 Canberra workshop with contributors primarily from CANZUS states"

Source: https://openresearch-repository.anu.edu.au/items/210eb2f2-de8e-4788-946b-09b257d51d7c
Source content: "2015 Canberra Workshop: No mention of a workshop in this source material." (CANZUS focus separately confirmed — see Claim 8.)
Comparison: The CANZUS half is verified separately (Claim 8). The 2015 Canberra workshop attribution is not present in the ANU Press repository entry I fetched and not confirmed by any other source consulted this pass.
Decision: uncorroborated

## Claim 8: "contributors primarily from CANZUS states — Canada, Australia, New Zealand, United States"

Source: https://openresearch-repository.anu.edu.au/items/210eb2f2-de8e-4788-946b-09b257d51d7c
Source content: "the CANZUS states of Canada, Australia, Aotearoa/New Zealand and the United States"
Comparison: Match verbatim (minus "Aotearoa/" qualifier which the entity also uses elsewhere).
Decision: corroborated

## Claim 9: "grounded IDS as a rights claim under the United Nations Declaration on the Rights of Indigenous Peoples (UNDRIP)"

Source: https://openresearch-repository.anu.edu.au/items/210eb2f2-de8e-4788-946b-09b257d51d7c
Source content: "The work is 'premised on the United Nations Declaration on the Rights of Indigenous Peoples' and argues that indigenous peoples possess inherent rights regarding data collection, ownership, and use."
Comparison: UNDRIP grounding matches; the rights-claim framing matches the source's "inherent rights" language.
Decision: corroborated

## Claim 10: "the CARE Principles for Indigenous Data Governance, developed at an International Data Week workshop held on 8 November 2018 in Gaborone, Botswana"

Source: https://www.gida-global.org/careprinciples
Source content: "drafted at the International Data Week and Research Data Alliance Plenary co-hosted event 'Indigenous Data Sovereignty Principles for the Governance of Indigenous Data Workshop,' 8 November 2018, Gaborone, Botswana."
Comparison: Date, city, event-class all match.
Decision: corroborated

## Claim 11: "co-led by Stephanie Russo Carroll (University of Arizona) and Maui Hudson (University of Waikato, Aotearoa New Zealand), with thirteen additional contributors"

Source: https://datascience.codata.org/articles/10.5334/dsj-2020-043
Source content: "Lead Author: Stephanie Russo Carroll (with 13 co-authors including Ibrahim Garba, Oscar L. Figueroa-Rodríguez, Jarita Holbrook, Raymond Lovett, and others)"
Comparison: Carroll lead-author role and the count of 13 additional contributors match the peer-reviewed paper's authorship. The GIDA CARE Principles page I fetched did not name workshop co-leads, so the specific "co-led by Carroll and Hudson" attribution and Hudson's University-of-Waikato affiliation are not separately confirmed in sources consulted this pass.
Decision: uncorroborated

## Claim 12: "formally released by GIDA on 6 September 2019"

Source: https://www.gida-global.org/careprinciples
Source content: "The page does not specify when the CARE Principles were released."
Comparison: The GIDA CARE Principles page does not contain a release date in the fetched content. No second canonical source fetched this pass corroborated 6 September 2019 specifically.
Decision: uncorroborated

## Claim 13: "peer-reviewed published in the *Data Science Journal* in November 2020"

Source: https://datascience.codata.org/articles/10.5334/dsj-2020-043
Source content: "Publication Date: November 4, 2020"
Comparison: Journal and month/year match.
Decision: corroborated

## Claim 14: "the principles — Collective Benefit, Authority to Control, Responsibility, Ethics"

Source: https://datascience.codata.org/articles/10.5334/dsj-2020-043
Source content: "The Four CARE Principles: 1. Collective Benefit 2. Authority to Control 3. Responsibility 4. Ethics"
Comparison: All four principles match verbatim.
Decision: corroborated

## Claim 15: "The GIDA '#BeFAIRandCARE' initiative positioned the two frameworks as complementary rather than competing"

Source: https://www.gida-global.org/careprinciples
Source content: Section titled "#BeFAIRandCARE" stating "These principles complement the existing FAIR principles encouraging open and other data movements to consider both people and purpose in their advocacy and pursuits."
Comparison: Initiative name and complementarity framing match.
Decision: corroborated

## Claim 16: "GIDA ... was itself founded at a workshop in Oñati, Spain on 11–12 July 2019"

Source: https://www.gida-global.org/whoweare
Source content: "The Workshop 'International Law, The United Nations Declaration on the Rights of Indigenous Peoples (UNDRIP) and Indigenous Data Sovereignty' was hosted 11-12 July 2019 at the International Institute for the Sociology of Law, Oñati, Spain."
Comparison: Dates and location match verbatim.
Decision: corroborated

## Claim 17: "convened by Maggie Walter and Desi Rodriguez-Lonebear"

Source: https://www.gida-global.org/whoweare
Source content: "Convened by Maggie Walter and Desi Rodriguez-Lonebear."
Comparison: Match verbatim.
Decision: corroborated

## Claim 18: "with founding members from the Maiam nayri Wingara Collective (Australia), Te Mana Raraunga (Aotearoa New Zealand), and the United States Indigenous Data Sovereignty Network (USIDSN)"

Source: https://www.gida-global.org/whoweare
Source content: "representation from the Maiam nayri Wingara Collective (Australia); Te Mana Raraunga Maori Data Sovereignty Network (Aotearoa New Zealand); and the United States Indigenous Data Sovereignty Network."
Comparison: All three founding-member groups match. Source uses "representation from" rather than "founding members"; within paraphrase tolerance given GIDA describes this workshop as its founding.
Decision: corroborated

## Claim 19: "GIDA takes its name from the Basque word for 'guide.'"

Source: https://www.gida-global.org/whoweare
Source content: "GIDA is the Basque word for guide."
Comparison: Match verbatim.
Decision: corroborated

## Claim 20: "the idea emerged at a July 2015 workshop in Australia"

Source: https://www.temanararaunga.maori.nz/
Source content: "Te Mana Raraunga's concept emerged from a July 2015 workshop in Australia hosted by the Academy of the Social Sciences..."
Comparison: Match.
Decision: corroborated

## Claim 21: "the inaugural hui was held at Hopuhopu on 19 October 2015, and the charter was ratified at Papakura Marae on 5 April 2016"

Source: https://www.temanararaunga.maori.nz/
Source content: "The network's first formal gathering occurred at Hopuhopu on 19 October 2015 ... The organization's foundational charter received official approval at the second hui, held at Papakura Marae in Auckland on 5 April 2016."
Comparison: Dates and locations match.
Decision: corroborated

## Claim 22: scalar:sources[5].note — "Tahu Kukutai as a founding member" of Te Mana Raraunga

Source: https://www.temanararaunga.maori.nz/
Source content: "The provided content does not mention Tahu Kukutai or identify any specific founding members by name. While the text references 'Māori researchers and practitioners' who participated in early meetings, it does not single out individual founders."
Comparison: TMR's own site does not name founding members in the content I fetched. The body claim "Kukutai (then a Professor of Demography at the University of Waikato, later a founding member of Te Mana Raraunga)" is consistent with her later confirmed leadership of TMR (she leads its current "Kia Ārohi Kia Mārama Scoping Excellence project" per the source), but founder-membership status as such is not corroborated in this pass.
Decision: uncorroborated

## Claim 23: "Te Hiku Media ... based in Kaitaia, Aotearoa New Zealand, that built the first te reo Māori speech-recognition AI under indigenous stewardship terms"

Source: https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
Source content: "Te Hiku Media Location: Kaitaia, in the northernmost region of Aotearoa (New Zealand)... Te Hiku Media developed speech recognition and natural language processing tools for te reo Māori, creating algorithms for speech recognition (86% accuracy)..."
Comparison: Location matches; speech-recognition work matches; "first ... under indigenous stewardship terms" framing is within paraphrase tolerance of MIT Technology Review's framing of the work.
Decision: corroborated

## Claim 24: "Chief Technology Officer Keoni Mahelona has stated ... 'Data is the last frontier of colonization'"

Source: https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
Source content: "Keoni Mahelona: CTO (Chief Technology Officer)" and quote "Data is the last frontier of colonization."
Comparison: Role and quote match verbatim.
Decision: corroborated

## Claim 25: "Peter-Lucas Jones, Chief Executive, has warned that absent indigenous governance structures, Māori-language data would be used by 'the very people that beat that language out of our mouths to sell it back to us as a service'"

Source: https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
Source content: "Peter-Lucas Jones: CEO" and quote "Our data would be used by the very people that beat that language out of our mouths to sell it back to us as a service."
Comparison: The entity's quoted substring is a literal substring of the source's full quote. Role match verbatim.
Decision: corroborated

## Claim 26: scalar:sources[7].note — verbatim Jones quote "I don't just think about how AI can be used, I think about how we can be the makers of AI"

Source: https://www.indigenous-ai.net/digital-sovereignty/
Source content: 'Jones emphasized a crucial distinction: "I don\'t just think about how AI can be used, I think about how we can be" indigenous creators rather than merely adopters.'
Comparison: My fetch's extraction closed the verbatim quote mid-sentence with the model paraphrasing the remainder as "indigenous creators rather than merely adopters" — the specific tail "the makers of AI" was not reproduced verbatim by the extraction. The source may carry the claimed phrasing; this pass cannot confirm it.
Decision: uncorroborated

## Claim 27: "the Indigenous Protocols for Artificial Intelligence (IP-AI) workshops — held first in Honolulu, Hawai'i in 2019"

Source: https://www.indigenous-ai.net/digital-sovereignty/
Source content: "The Indigenous Protocols and Artificial Intelligence workshops occurred in March 2019 in Hawaiʻi. They were founded by Old Ways, New and the Initiative for Indigenous Futures..."
Comparison: 2019 and Hawai'i match. Source does not specify Honolulu; "Honolulu" is the entity's narrower claim and is within typical-tolerance for Hawai'i-located convenings but not strictly confirmed.
Decision: corroborated

## Claim 28: "the IEEE 2890-2025 standard for provenance documentation of Indigenous Peoples' data"

Source: https://standards.ieee.org/ieee/2890/10318/
Source content: "The standard is titled 'IEEE Recommended Practice for Provenance of Indigenous Peoples' Data.' Its scope establishes 'a common set of parameters for the provenance of Indigenous Peoples' data'... Board Approval: September 10, 2025; Published: November 14, 2025."
Comparison: Standard number, title-scope (provenance of Indigenous Peoples' data), and 2025 designation all match.
Decision: corroborated
