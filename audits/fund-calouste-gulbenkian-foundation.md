---
entity_id: fund-calouste-gulbenkian-foundation
entity_hash: 0875b341c3cd456e1da609a48d46ca9a62e6a072
audit_date: 2026-09-01
pass: 1
status: corrections-pending
claims_total: 24
claims_corroborated: 13
claims_primary_sourced: 4
claims_single_source: 3
claims_uncorroborated: 3
open_corrections: 1
sources_consulted:
  - https://en.wikipedia.org/wiki/Calouste_Gulbenkian_Foundation
  - https://civitates-eu.org/foundation-partners/
  - https://civitates-eu.org/
  - https://civitates-eu.org/tech-and-democracy/
  - https://philea.eu/opinions/beyond-funding-exploring-participatory-practices-in-the-gulbenkian-foundations-management-of-the-active-citizens-fund/
  - https://www.eui.eu/news-hub?id=first-donation-to-the-european-media-and-information-fund
  - https://media-and-learning.eu/type/news/launch-of-new-european-media-and-information-fund/
  - https://philanthropy.org/foundation/calouste-gulbenkian-foundation/
  - https://www.swfinstitute.org/profile/5bc459d2dda4002126c6cecc
  - https://gulbenkian.pt/en/about-us/
  - https://gulbenkian.pt/emifund/
  - https://gulbenkian.pt/uk-branch/about-us/the-foundation/
  - https://gulbenkian.pt/en/grant-making-activities/
  - https://eeagrants.org/news/programme-implementation-agreement-signed-active-citizens-fund-portugal
  - https://blog.google/around-the-globe/google-europe/googles-25-million-contribution-to-media-literacy/
  - https://frittord.no/en/news/civitates-tech-democracy-open-call
  - https://armenianweekly.com/2022/05/09/antonio-feijo-is-the-new-president-of-the-calouste-gulbenkian-foundation/
---

Note on source access this pass: gulbenkian.pt (all paths, including /emifund/ and /cidadaos-ativos/) returns 403 on direct fetch as of 2026-09-01 — the entity's primary sources on that domain were verified via search snippets and third-party mirrors (eui.eu, media-and-learning.eu, philea.eu, eeagrants.org) where possible.

## Claim 1: "established on 18 July 1956 per the will of Armenian-British oil magnate Calouste Sarkis Gulbenkian and headquartered in Lisbon"

Source: https://en.wikipedia.org/wiki/Calouste_Gulbenkian_Foundation ; https://gulbenkian.pt/uk-branch/about-us/the-foundation/ (via search snippet)
Source tier: primary
Source content: Wikipedia: "established on 18 July 1956 according to the last will and testament of Calouste Sarkis Gulbenkian, an Armenian oil magnate... headquartered in Lisbon". UK Branch page snippet: "a charitable foundation set up in 1956 as a private institution of public utility under a special act of the Portuguese Government... its seat in Lisbon".
Comparison: Date, testamentary origin, founder identity, and Lisbon HQ all match; "Armenian-British" is consistent with Gulbenkian's British nationality and Armenian origin. Also appears in frontmatter scalar `focus`.
Decision: corroborated

## Claim 2: "a Portuguese private foundation of public utility"

Source: https://gulbenkian.pt/uk-branch/about-us/the-foundation/ (via search snippet); https://cdn.gulbenkian.pt/wp-content/uploads/2022/12/Statutes-Calouste-Gulbenkian-Foundation.pdf (via search snippet)
Source tier: primary
Source content: "The Foundation is governed as a private institution of public utility under Portuguese law, with statutes approved by decree following the Founder's will."
Decision: corroborated
Comparison: "Private foundation of public utility" matches the foundation's own statement of its legal form ("private institution of public utility"). Also in `focus` scalar.

## Claim 3: "with a UK branch in London"

Source: https://gulbenkian.pt/uk-branch/ (via search snippet); https://en.wikipedia.org/wiki/Calouste_Gulbenkian_Foundation
Source tier: primary
Source content: "The Foundation maintains a grant giving branch in London. Based in London, the UK Branch contributes to the Foundation's mission... London serves as a grant-giver in the UK and Ireland." Wikipedia: "The foundation maintains a delegation in the United Kingdom."
Comparison: Match — UK branch located in London per the foundation's own UK Branch pages.
Decision: corroborated

## Claim 4: "a science institute (Instituto Gulbenkian de Ciência)"

Source: https://en.wikipedia.org/wiki/Calouste_Gulbenkian_Foundation
Source tier: tiebreaker
Source content: "Located in Oeiras near Lisbon, this research institute was founded in 1961 and focuses on biological and biomedical research."
Comparison: Match — named-entity definitional fact; Wikipedia-alone sufficient per source rule.
Decision: single-source

## Claim 5: "total assets of approximately €3.5 billion"

Source: https://en.wikipedia.org/wiki/Calouste_Gulbenkian_Foundation ; https://philanthropy.org/foundation/calouste-gulbenkian-foundation/
Source tier: none
Source content: Wikipedia: "As of 2017, the foundation held a €3.9 billion endowment with annual revenue of €169.5 million." philanthropy.org: assets "$4.53 billion".
Comparison: The body cites Wikipedia for €3.5 billion, but Wikipedia currently gives €3.9 billion (2017 endowment) and philanthropy.org gives $4.53 billion — sources conflict across years and measures (endowment vs. total assets), and no fetched canonical source carries the €3.5 billion figure as stated. Not a correction: no single correct replacement token identifiable. Also in `focus` scalar.
Decision: uncorroborated

## Claim 6: "annual programme spending of approximately €100 million"

Source: https://philanthropy.org/foundation/calouste-gulbenkian-foundation/
Source tier: database
Source content: "Annual Giving: $123.6 million"
Comparison: $123.6M ≈ €105–115M at recent rates — consistent with "approximately €100 million" as an order-of-magnitude figure, supported by one database-tier source only. Also in `focus` scalar.
Decision: single-source

## Claim 7: "operates under four statutory aims — arts, social welfare, education, and science"

Source: https://en.wikipedia.org/wiki/Calouste_Gulbenkian_Foundation
Source tier: tiebreaker
Source content: "dedicated to the promotion of the arts, philanthropy, science, and education"
Comparison: The four aims match modulo translation variance — Wikipedia renders the statutory "beneficência" as "philanthropy" where the body renders it "social welfare"; both are accepted English renderings. Definitional fact, Wikipedia-alone sufficient. Also in `focus` scalar.
Decision: single-source

## Claim 8: "since 2023 has organised its programme work into seven multi-year portfolios: Access to Care, Access to Culture, Access to Education, Climate and Ocean, Democracy and Civil Society, Armenian Communities, and Partnerships with Africa"

Source: https://gulbenkian.pt/en/grant-making-activities/ (via search snippet); 2023–2027 strategic-cycle references via https://gulbenkian.pt/uk-branch/chronology/our-history/ (search snippet)
Source tier: primary
Source content: "The Gulbenkian Foundation develops multi-year programmes focusing on seven areas of action: Access to Culture, Access to Care, Access to Education, Climate and Ocean, Democracy and Civil Society, Armenian Communities, and Partnerships with Africa." UK Branch history: "the Foundation initiated a new strategic programme cycle for 2023–2027."
Comparison: The seven-programme list matches the foundation's own grant-making page exactly; the "since 2023" dating is separately supported by references to the 2023–2027 strategic cycle. Also in `focus` scalar.
Decision: primary-sourced

## Claim 9: "led by President António M. Feijó, who assumed the presidency in May 2022 as the first president drawn from arts and humanities"

Source: https://gulbenkian.pt/en/news/antonio-feijo-is-the-new-president-of-the-gulbenkian-foundation/ (via search snippet); https://armenianweekly.com/2022/05/09/antonio-feijo-is-the-new-president-of-the-calouste-gulbenkian-foundation/
Source tier: primary
Source content: "António Feijó assumed the mandate of President of the Calouste Gulbenkian Foundation on 3 May 2022... he is the first President with a Humanities background... was the Director of the University's School of Arts and Humanities."
Comparison: Assumed office 3 May 2022 matches "May 2022"; "first president drawn from arts and humanities" matches "first President with a Humanities background" (he directed Lisbon University's School of Arts and Humanities).
Decision: corroborated

## Claim 10: "EMIF... co-managed by the Calouste Gulbenkian Foundation and the European University Institute (Florence)"

Source: https://www.eui.eu/news-hub?id=first-donation-to-the-european-media-and-information-fund
Source tier: primary
Source content: "managed by the Calouste Gulbenkian Foundation in partnership with the European University Institute (EUI)"
Comparison: Match — CGF manages in partnership with EUI; multiple independent confirmations (EUI, Google blog, media-and-learning.eu).
Decision: corroborated

## Claim 11: "established with an initial €25 million, five-year contribution from Google"

Source: https://www.eui.eu/news-hub?id=first-donation-to-the-european-media-and-information-fund ; https://blog.google/around-the-globe/google-europe/googles-25-million-contribution-to-media-literacy/
Source tier: primary
Source content: EUI: "Google committed €25 million over a five-year period to support the initiative." Google was "the first donor to the fund with a contribution of 25 million euros... spread over 5 years."
Comparison: Match — amount, duration, and Google as initial contributor all confirmed by two independent sources.
Decision: corroborated

## Claim 12: "EMIF's stated mission is to support fact-checking and media literacy initiatives in Europe and address online disinformation across the European information ecosystem"

Source: https://www.eui.eu/news-hub?id=first-donation-to-the-european-media-and-information-fund ; https://media-and-learning.eu/type/news/launch-of-new-european-media-and-information-fund/
Source tier: primary
Source content: "funding will support media literacy and fact-checking initiatives, as well as research projects on online disinformation"; "support collaborative efforts to debunk disinformation, amplify independent fact-checking."
Comparison: Match — mission framing confirmed by EUI and launch coverage.
Decision: corroborated

## Claim 13: "four priority areas: fact-checking initiatives, multidisciplinary investigations on disinformation, research studies and sandboxes, and media literacy programming"

Source: https://media-and-learning.eu/type/news/launch-of-new-european-media-and-information-fund/ ; https://www.eui.eu/news-hub?id=emif-awards-5.7m-for-projects-fighting-disinformation-in-2022 (via search snippet)
Source tier: mainstream
Source content: Launch article: "Projects supported by the Fund will focus on four areas: Media Literacy, Online Disinformation, Fact-checking, Academic research into media, disinformation and information literacy." 2022 announcement: calls for fact-checking, "Multidisciplinary Investigations on Disinformation in Europe", "Supporting Research into Media, Disinformation and Information Literacy Across Europe", "Media and Information Literacy for Citizens Empowerment".
Comparison: The four-area structure and three of the four labels map onto EMIF's actual call structure, but the "research studies and sandboxes" wording — specifically the "sandboxes" token — could not be confirmed anywhere; the cited primary (gulbenkian.pt/emifund/) 403s on direct fetch. As stated, partially confirmed only.
Decision: uncorroborated

## Claim 14: "the fund explicitly funds work examining the effects of digital media and AI technologies on human cognition, civic behavior, social interactions, and democratic participation"

Source: no canonical source found (cited primary https://gulbenkian.pt/emifund/ 403s on direct fetch)
Source tier: none
Source content: Neither the EUI announcement, the media-and-learning.eu launch article, nor three targeted searches surfaced this language; the launch article "does not discuss effects of digital media or AI technologies on human cognition, civic behavior, social interactions, or democratic participation."
Comparison: This near-verbatim quote from the EMIF site could not be verified because the site refuses direct fetch and no mirror carries the language. Not contradicted — simply unverifiable this pass. The body's AI-democracy throughline framing rests on it, so re-check when gulbenkian.pt becomes fetchable.
Decision: uncorroborated

## Claim 15: "In its 2022 grant round EMIF awarded €5.7 million to projects fighting disinformation, with civil society organisations and academic research groups as the primary recipient categories"

Source: https://www.eui.eu/news-hub?id=emif-awards-5.7m-for-projects-fighting-disinformation-in-2022 (via search snippet); https://gulbenkian.pt/emifund/news/emif-awards-e5-7m-for-projects-fighting-disinformation-in-2022/ (title via search)
Source tier: primary
Source content: "In its first year of activity, EMIF distributed €5,751,721 in grants supporting 33 projects aimed at countering disinformation across the continent... EMIF supported 33 projects in 21 European countries."
Comparison: €5,751,721 matches "€5.7 million"; recipients (researchers, fact-checkers, not-for-profits) match the stated recipient categories.
Decision: corroborated

## Claim 16: "The coordination architecture connects EMIF to the European Digital Media Observatory (EDMO)"

Source: https://www.eui.eu/news-hub?id=first-donation-to-the-european-media-and-information-fund
Source tier: primary
Source content: "The European Digital Media Observatory at EUI's School of Transnational Governance will act as independent advisor in the formulation of calls for proposals, as well as in the evaluation and selection of projects."
Comparison: The structural EMIF–EDMO link is confirmed (EDMO as independent advisor in EMIF's grant process); the body's "coordination architecture" phrasing is a fair rendering of that role.
Decision: primary-sourced

## Claim 17: "The Active Citizens Fund (2018–2024)... disbursing €11.5 million... and reaching over 65,000 individuals"

Source: https://philea.eu/opinions/beyond-funding-exploring-participatory-practices-in-the-gulbenkian-foundations-management-of-the-active-citizens-fund/ ; https://gulbenkian.pt/cidadaos-ativos/en/about-the-programme/ (via search snippet)
Source tier: primary
Source content: "In the period from 2018 to 2024, a total of €11.5 million has been allocated, funding 182 projects that have reached over 65,000 individuals."
Comparison: Period, total allocation, and individuals reached all match across the ACF's own page and Philea. Also in `focus` scalar.
Decision: corroborated

## Claim 18: "disbursing €11.5 million across 182 civil society organisations" — the "182 civil society organisations" token

Source: https://gulbenkian.pt/cidadaos-ativos/en/about-the-programme/ (via search snippet); https://philea.eu/opinions/beyond-funding-exploring-participatory-practices-in-the-gulbenkian-foundations-management-of-the-active-citizens-fund/
Source tier: primary
Source content: "funding 182 projects that have reached over 65,000 individuals" (both sources; Philea: "Projects funded: 182").
Comparison: The sources count 182 *projects*, not 182 civil society organisations — one organisation can run multiple projects, so the units are not interchangeable. The entity's own frontmatter source note for the ACF page correctly records "182 projects funded"; the body and the `focus` scalar both render it "182 civil society organisations". Single correct replacement: "182 civil society organisations" → "182 projects" in the body (§ Active Citizens Fund) and in frontmatter scalar `focus` ("disbursed €11.5 million to 182 civil society organisations" → "to 182 projects").
Decision: correction

## Claim 19: "co-financed through the European Economic Area Financial Mechanisms (the EEA and Norway Grants programme channelling funds from Iceland, Liechtenstein, and Norway...), with the Gulbenkian Foundation serving as the national fund manager for Portugal"

Source: https://eeagrants.org/news/programme-implementation-agreement-signed-active-citizens-fund-portugal (via search snippet); https://philea.eu/opinions/beyond-funding-exploring-participatory-practices-in-the-gulbenkian-foundations-management-of-the-active-citizens-fund/
Source tier: primary
Source content: "The EEA Grants are financial resources provided by Iceland, Liechtenstein, and Norway... In Portugal, the ACF is managed by the Calouste Gulbenkian Foundation (CGF) in partnership with the Bissaya Barreto Foundation."
Comparison: Funding mechanism, donor states, and CGF's fund-operator role all match. Sources add that CGF manages in partnership with the Bissaya Barreto Foundation — an omission in the body, not an error.
Decision: corroborated

## Claim 20: "Its four focus areas are: democracy, active citizenship, good governance, and transparency; human rights, equality, and anti-discrimination; social justice and inclusion of vulnerable groups; and NGO capacity-building"

Source: https://philea.eu/opinions/beyond-funding-exploring-participatory-practices-in-the-gulbenkian-foundations-management-of-the-active-citizens-fund/ ; https://gulbenkian.pt/cidadaos-ativos/en/about-the-programme/ (via search snippet)
Source tier: primary
Source content: "The programme addresses four domains: democracy and governance, human rights and anti-discrimination efforts, social justice for vulnerable populations, and organizational capacity-building for NGOs."
Comparison: The four areas match across both sources with minor label compression.
Decision: corroborated

## Claim 21: "The programme's participatory design philosophy... was documented by Philea (the European philanthropy network) as a case study in participatory grant management"

Source: https://philea.eu/opinions/beyond-funding-exploring-participatory-practices-in-the-gulbenkian-foundations-management-of-the-active-citizens-fund/
Source tier: primary
Source content: "the foundation established a Consultative Group comprising 26 citizens (program beneficiaries) selected through competitive application... 'a more courageous, participatory and diverse Foundation, which includes beneficiaries in the design of its initiatives.'"
Comparison: The Philea piece exists and documents exactly this — participatory practices in the Gulbenkian Foundation's ACF management. The piece itself is the primary document for the claim that Philea documented it.
Decision: primary-sourced

## Claim 22: "The Gulbenkian Foundation is a foundation partner of Civitates"

Source: https://civitates-eu.org/foundation-partners/
Source tier: primary
Source content: The Civitates foundation-partners page lists "Calouste Gulbenkian Foundation" among its partners.
Comparison: Match — confirmed directly on Civitates' own partner roster. Also confirmed by the frontmatter source note.
Decision: primary-sourced

## Claim 23: "Civitates, the Brussels-based pooled European civil-society philanthropy vehicle that operates three sub-funds: Civic Power..., Tech and Democracy..., and Media...; pools contributions from approximately 30 European foundations"

Source: https://civitates-eu.org/ ; https://civitates-eu.org/foundation-partners/
Source tier: primary
Source content: "we decided to continue supporting the same three portfolios (or Sub-Funds)" — Civic Power, Tech & Democracy, and Media; address "Philanthropy House, Rue Royale 94, 1000 Brussels"; partner page lists approximately 33 foundation partners.
Comparison: Brussels base, the three named sub-funds, and pooled structure all match; ~33 listed partners is consistent with "approximately 30". Also in `focus` scalar.
Decision: corroborated

## Claim 24: "Civitates' Tech and Democracy sub-fund (supporting civil society enforcement of the Digital Services Act and EU AI and platform regulations)"

Source: https://civitates-eu.org/tech-and-democracy/ ; https://frittord.no/en/news/civitates-tech-democracy-open-call (via search snippet)
Source tier: primary
Source content: Sub-fund page: early funder of grantees "influencing the Digital Services Act (DSA)" and "tech regulation enforcement at national level". Open call: "support for civil society working to improve enforcement of EU tech regulations at the national level, including key EU regulations such as the Digital Services Act, GDPR, AI Act and the European Media Freedom Act."
Comparison: DSA enforcement, AI Act, and platform-regulation enforcement support all explicitly confirmed. Also in `focus` scalar.
Decision: corroborated
