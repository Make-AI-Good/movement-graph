---
entity_id: camp-coding-rights-anti-frt-brazil
entity_hash: 32fbc7318e1a6aa9bda428cdd30a725325f289dc
audit_date: 2026-07-16
pass: 4
status: corrections-pending
claims_total: 27
claims_corroborated: 1
claims_primary_sourced: 18
claims_single_source: 7
claims_uncorroborated: 0
open_corrections: 1
sources_consulted:
  - https://codingrights.org/en/project-item/legislators-from-all-regions-of-brazil-present-bills-to-ban-facial-recognition-in-public-spaces/
  - https://tiremeurostodasuamira.org.br/en/open-letter/
  - https://globalvoices.org/2022/06/20/brazilian-facial-recognition-ruling-can-set-an-important-precedent-for-country-wide-use/
  - https://www.biometricupdate.com/202407/as-brazil-debates-ai-bill-calls-for-facial-recognition-bans-emerge
  - https://www.biometricupdate.com/202107/brazils-bahia-state-contracts-131m-facial-recognition-system-to-tackle-criminality
---

Pass-4 context: re-audit triggered by stale `entity_hash` after the Researcher's Claim 25 + 27 audit fixes (commit 21d4a834) and the Analyst's `strategies` edge addition. Both pass-3 corrections verified CLEARED this pass (Claims 25 and 27 below). One NEW correction found (Claim 2). Type-shape: campaign (connective) — claims are edges and hard specifics; interpretive body prose about significance/arc is not audited. The Medium retrospective source rendered as a JS nav-shell on fetch this session (no article content); claims 7–12 rest on the pass-2 verified record with the body text unchanged since.

## Claim 1: "On 21 June 2022 [Coding Rights], MediaLab-UFRJ / Rede Lavits, the Brazilian Institute of Consumer Defence (IDEC), and the Centre for Studies on Security and Citizenship (CESeC) published a joint communiqué"

Source: https://codingrights.org/en/project-item/legislators-from-all-regions-of-brazil-present-bills-to-ban-facial-recognition-in-public-spaces/
Source tier: primary
Source content: Re-fetched this pass: page dated "06.21.2022" (updated 02.07.2023); leads named as "Coding Rights, MediaLab-UFRJ/Rede Lavits, the Brazilian Consumer Defense Institute (IDEC), and the Center for Studies on Security and Citizenship (CESeC)".
Comparison: Date and four-organisation lead composition match. Single primary source (the campaign's own page).
Decision: primary-sourced

## Claim 2: "more than 50 state and municipal legislators across thirteen Brazilian states and the Federal District had presented bills banning or restricting facial-recognition technology (FRT)". Also scalar:goals ("over 50 state and municipal legislators across thirteen states and the Federal District by the time of the June 2022 communiqué"); scalar:outcomes ("naming over 50 state and municipal parliamentarians across thirteen states and the Federal District"); scalar:sources[0].note ("the over-50-parliamentarians figure across thirteen states and the Federal District").

Source: https://codingrights.org/en/project-item/legislators-from-all-regions-of-brazil-present-bills-to-ban-facial-recognition-in-public-spaces/
Source tier: primary
Source content: Re-fetched this pass: "more than 50 state and local legislators from 13 states" and "12 states and the Federal District had bills presented".
Comparison: The over-50 legislator count matches. The jurisdiction count does not: the source's precise phrasing is "12 states and the Federal District" — 13 jurisdictions total — and the entity's own enumerated list (Claim 3) has exactly 13 entries with Distrito Federal as one of them. The body's "thirteen Brazilian states and the Federal District" asserts 14 jurisdictions, double-counting the DF. (The source's looser "from 13 states" headline counts DF among the 13.) The body's own §first-bills line — "parliamentarians in twelve further jurisdictions" after Rio de Janeiro — independently confirms the 13-jurisdiction total. Single correct token replacement: "thirteen" → "twelve" at four locations: body opening paragraph, scalar:goals, scalar:outcomes, scalar:sources[0].note. Prior passes glossed this as matching; the source's precise phrase re-fetched this pass contradicts it.
Decision: correction

## Claim 3: Thirteen named jurisdictions — "Bahia, Ceará, Espírito Santo, Distrito Federal, Minas Gerais, Pará, Paraná, Pernambuco, Rio de Janeiro, Rio Grande do Sul, Santa Catarina, Sergipe, and São Paulo"

Source: https://codingrights.org/en/project-item/legislators-from-all-regions-of-brazil-present-bills-to-ban-facial-recognition-in-public-spaces/
Source tier: primary
Source content: Communiqué lists the same thirteen jurisdictions (verified verbatim at pass 2; body unchanged).
Comparison: Jurisdiction list matches exactly — 13 entries, Distrito Federal among them (this list is the evidence base for Claim 2's correction). Carrying forward.
Decision: primary-sourced

## Claim 4: "8 December 2021, when State Representative Dani Monteiro (PSOL, Rio de Janeiro) filed the first state-level proposal and Rio City Council Member Reimont (PT) filed the first municipal-level proposal"

Source: https://codingrights.org/en/project-item/legislators-from-all-regions-of-brazil-present-bills-to-ban-facial-recognition-in-public-spaces/
Source tier: primary
Source content: Re-fetched this pass: "State Representative Dani Monteiro — PSOL RJ" and "Councilman Reimont — PT" filed the first bills on December 8, 2021.
Comparison: Date, names, parties, and chambers all match.
Decision: primary-sourced

## Claim 5: Three Brazilian misidentification cases — "in Rio de Janeiro, a Black woman was wrongly arrested on the second day of FRT operational testing; in Piauí, a Black man was wrongly imprisoned for three days on the basis of an FRT match; and in Salvador a 25-year-old Black Brazilian with special needs was approached by police after being mistaken for a wanted person"

Source: https://codingrights.org/en/project-item/legislators-from-all-regions-of-brazil-present-bills-to-ban-facial-recognition-in-public-spaces/
Source tier: primary
Source content: Re-fetched this pass: Rio de Janeiro — "a woman was arrested when she was mistaken for someone already incarcerated"; Piauí — "a man was transferred to the Federal District and wrongly imprisoned for three days"; Salvador — "a 25-year-old with special needs was approached by police officers after being mistaken for a man". Full case details (race attributions, second-day-of-testing circumstance) verified at pass 2 against the same page; body unchanged since.
Comparison: All three cases match on location, duration, and circumstance; the racial attributions and testing-day detail rest on the pass-2 verified record of the same source.
Decision: primary-sourced

## Claim 6: Named legislators across multiple Brazilian jurisdictions (Benedita da Silva, Hilton Coelho, Andreia de Jesus, Érica Malunguinho, Isa Penna, Leci Brandão, Chico Alencar, Lindbergh Farias, Monica Benício, Paulo Pinheiro, Tarcísio Motta, Renata Souza, Carol Dartora)

Source: https://codingrights.org/en/project-item/legislators-from-all-regions-of-brazil-present-bills-to-ban-facial-recognition-in-public-spaces/
Source tier: primary
Source content: Re-fetched this pass: all thirteen names confirmed present on the communiqué page, including Renata Souza and Carol Dartora.
Comparison: Every named legislator in the body appears on the source page.
Decision: primary-sourced

## Claim 7: "Joana Varon ... co-created protestos.org with Artigo 19 in 2014"

Source: https://medium.com/codingrights/reconhecimento-facial-10-anos-de-resist%C3%AAncias-e-parcerias-criativas-para-trazer-o-tema-para-o-b1b8b6a89aa2
Source tier: primary
Source content: "lançou, em parceria com a Artigo 19, o guia ilustrado protestos.org" — 2014 launch in partnership with Artigo 19 (pass-2 verified record; Medium rendered as JS nav-shell on fetch this session; body unchanged since pass 2).
Comparison: Year, partner, and product name match per the pass-2 record. Carrying forward.
Decision: primary-sourced

## Claim 8: "in 2019 Varon participated in a Chamber of Deputies public hearing on facial recognition"

Source: https://medium.com/codingrights/reconhecimento-facial-10-anos-de-resist%C3%AAncias-e-parcerias-criativas-para-trazer-o-tema-para-o-b1b8b6a89aa2
Source tier: primary
Source content: 2019 hearing of the Câmara dos Deputados on facial recognition (pass-2 verified record; body unchanged).
Comparison: Year, institution, and topic match per the pass-2 record. Carrying forward.
Decision: primary-sourced

## Claim 9: "in 2020 Mariah Rafaela Silva and Varon co-authored Reconhecimento Facial no Setor Público"

Source: https://medium.com/codingrights/reconhecimento-facial-10-anos-de-resist%C3%AAncias-e-parcerias-criativas-para-trazer-o-tema-para-o-b1b8b6a89aa2
Source tier: primary
Source content: "a Mariah e a Joana lançaram a pesquisa Reconhecimento Facial no Setor Público" (pass-2 verified record; body unchanged).
Comparison: Year, co-authors, and title match per the pass-2 record. Carrying forward.
Decision: primary-sourced

## Claim 10: "in 2021 Coding Rights launched the Que Inteligência? project mapping AI implementations in Latin American public-sector deployments"

Source: https://medium.com/codingrights/reconhecimento-facial-10-anos-de-resist%C3%AAncias-e-parcerias-criativas-para-trazer-o-tema-para-o-b1b8b6a89aa2
Source tier: primary
Source content: "lançamos um projeto com a pesquisadora Paz Peña chamado Que Inteligência?" mapping AI in Latin American public sectors (pass-2 verified record; body unchanged).
Comparison: Year and project framing match per the pass-2 record. Carrying forward.
Decision: primary-sourced

## Claim 11: "in August 2023 Coding Rights co-organised a Rio de Janeiro state-level seminar with Dani Monteiro"

Source: https://medium.com/codingrights/reconhecimento-facial-10-anos-de-resist%C3%AAncias-e-parcerias-criativas-para-trazer-o-tema-para-o-b1b8b6a89aa2
Source tier: primary
Source content: August 2023 seminar with state deputy Dani Monteiro on FRT in Rio de Janeiro (pass-2 verified record; body unchanged).
Comparison: Month, year, co-organiser, and topic match per the pass-2 record. Carrying forward.
Decision: primary-sourced

## Claim 12: "produced the Quem Paga a Conta? ('who is footing the bill?') investigative series with The Intercept Brasil"

Source: https://medium.com/codingrights/reconhecimento-facial-10-anos-de-resist%C3%AAncias-e-parcerias-criativas-para-trazer-o-tema-para-o-b1b8b6a89aa2
Source tier: primary
Source content: Series with The Intercept Brasil and CESeC investigating Smart Sampa and facial-recognition funding transparency (pass-2 verified record; body unchanged).
Comparison: Series title, partner outlet, and theme match per the pass-2 record. Carrying forward.
Decision: primary-sourced

## Claim 13: "In 2021 the São Paulo State Court ruled against ViaQuatro, the private operator of Line 4 of the São Paulo Metro, for its unauthorised use of FRT"

Source: https://globalvoices.org/2022/06/20/brazilian-facial-recognition-ruling-can-set-an-important-precedent-for-country-wide-use/ and https://en.wikipedia.org/wiki/Line_4_(S%C3%A3o_Paulo_Metro)
Source tier: mainstream
Source content: Re-fetched this pass: "in 2021, ViaQuatro, the private company that administers one of São Paulo's privatized metro lines, was condemned by the São Paulo State Court for using facial recognition without authorization." Wikipedia (pass-2, unchanged) confirms ViaQuatro as the Line 4 concessionaire.
Comparison: Year, court, defendant, and operator role match Global Voices; the Line-4 designation is a named-entity definitional fact for which Wikipedia counts as a second canonical source. Two canonical sources.
Decision: corroborated

## Claim 14: Court quote — "passengers' images were being captured without their consent for commercial purposes that benefit the company and other third-party firms involved"

Source: https://globalvoices.org/2022/06/20/brazilian-facial-recognition-ruling-can-set-an-important-precedent-for-country-wide-use/
Source tier: mainstream
Source content: Re-fetched this pass: judge's finding quoted verbatim — "passengers' images were being captured without their consent for commercial purposes that benefit the company and other third-party firms involved."
Comparison: Quoted phrase matches verbatim. One non-primary canonical source (quoted statement — Wikipedia tiebreaker-only class, no second source recorded).
Decision: single-source

## Claim 15: "56.1% of Brazil's population self-identifies as Black"

Source: https://globalvoices.org/2022/06/20/brazilian-facial-recognition-ruling-can-set-an-important-precedent-for-country-wide-use/
Source tier: mainstream
Source content: Re-fetched this pass: "56.1 percent of the population self-declares themselves Black."
Comparison: Figure and framing match. One non-primary canonical source.
Decision: single-source

## Claim 16: "Brazil's third-largest-in-the-world incarcerated population"

Source: https://tiremeurostodasuamira.org.br/en/open-letter/
Source tier: primary
Source content: Re-fetched this pass: "In Brazil, a country with the third largest incarcerated population" (in the world).
Comparison: Ranking matches; the body attributes the point to the open letter, which is the campaign coalition's own foundational document.
Decision: primary-sourced

## Claim 17: "Bahia [has been deploying] FRT-capable cameras since 2018" (scalar:sources[3].note)

Source: https://tiremeurostodasuamira.org.br/en/open-letter/
Source tier: primary
Source content: Re-fetched this pass: "In the state of Bahia, since 2018, facial recognition cameras have been installed."
Comparison: State, year, and deployment characterisation match. Scalar location: sources[3].note.
Decision: primary-sourced

## Claim 18: "Rio de Janeiro Bill 5240/2021 reference" (scalar:sources[3].note)

Source: https://tiremeurostodasuamira.org.br/en/open-letter/
Source tier: primary
Source content: Re-fetched this pass: Bill 5240/2021 appears in the letter's legislative mapping section under Rio de Janeiro pro-ban initiatives.
Comparison: Bill number and jurisdiction match. Scalar location: sources[3].note.
Decision: primary-sourced

## Claim 19: "the EDRi-coordinated Reclaim Your Face European Citizens' Initiative and Access Now's biometric-surveillance-ban campaigning are named as kindred international initiatives" (in the #TireMeuRostoDaSuaMira letter)

Source: https://tiremeurostodasuamira.org.br/en/open-letter/
Source tier: primary
Source content: Re-fetched this pass: letter links reclaimyourface.eu as a kindred campaign and references Access Now's communications on biometric surveillance bans.
Comparison: Both kindred initiatives are acknowledged in the letter as the body claims.
Decision: primary-sourced

## Claim 20: "In July 2024 the Coalizão Direitos na Rede ... published an open letter calling for a ban on FRT in public security"

Source: https://www.biometricupdate.com/202407/as-brazil-debates-ai-bill-calls-for-facial-recognition-bans-emerge
Source tier: mainstream
Source content: Re-fetched this pass: letter published July 8, 2024, demanding "a ban on facial recognition use for public security and criminal justice over its impact on freedom of expression and assembly."
Comparison: Month, year, organising coalition, and demand match (the body's "incompatible with freedom of expression and freedom of assembly" framing matches the source's grounds). One specialist-press canonical source.
Decision: single-source

## Claim 21: "the over-50-academic-and-civil-society-organisation Brazilian digital-rights coalition that includes Coding Rights"

Source: https://www.biometricupdate.com/202407/as-brazil-debates-ai-bill-calls-for-facial-recognition-bans-emerge
Source tier: mainstream
Source content: Re-fetched this pass: "CDR represents a network of more than 50 academic and civil society organizations involved in digital rights."
Comparison: Coalition size and composition match. One canonical source.
Decision: single-source

## Claim 22: PL 2338/2023 — "modelled on the EU AI Act and incorporating rights guarantees, prohibited AI uses, algorithmic impact assessments, and civil liability for operators"

Source: https://www.biometricupdate.com/202407/as-brazil-debates-ai-bill-calls-for-facial-recognition-bans-emerge
Source tier: mainstream
Source content: Re-fetched this pass: "Drawing inspiration from the EU AI Act, the rulebook categorizes AI systems according to different levels of risk"; the bill "includes basic rights guarantees for individuals affected by AI, defines unacceptable uses of the technology and introduces ... algorithmic impact assessments" plus "civil liability for operators, suppliers and distributors of AI systems."
Comparison: All four feature categories and the EU-AI-Act modelling match. One canonical source.
Decision: single-source

## Claim 23: "a man wrongly detained at a stadium in Sergipe in April 2024" and the lobbying accusation ("private-sector lobbying of attempting to prevent the vote on the bill by introducing late-stage amendments and scheduling additional hearings")

Source: https://www.biometricupdate.com/202407/as-brazil-debates-ai-bill-calls-for-facial-recognition-bans-emerge
Source tier: mainstream
Source content: Re-fetched this pass: "a man [detained] by the police at a [stadium] in Sergipe in April after a facial recognition misidentification"; the letter accuses "technology companies and the private sector of lobbying to prevent the vote on the bill by introducing last-minute amendments and organizing international trips and private events for the senators involved."
Comparison: Month, year, place, circumstance, and the lobbying accusation all match. One canonical source.
Decision: single-source

## Claim 24: "the #TireMeuRostoDaSuaMira open letter [in 2023] ... a civil-society demand for a total ban on FRT in Brazilian public security, encompassing all government spheres and private-sector contracts with public agencies"

Source: https://tiremeurostodasuamira.org.br/en/open-letter/
Source tier: primary
Source content: Re-fetched this pass: the letter's position that "this constant, massive, indiscriminate surveillance is – in itself – a violation of people's rights and freedoms" regardless of proposed safeguards; the total-ban demand spanning government spheres and private contracts verified at pass 3 against the same page.
Comparison: Year, substantive demand, and scope match the letter.
Decision: primary-sourced

## Claim 25: Corrected signatory claim — "signed by a broad coalition of civil-society organisations including [Coding Rights], [Access Now], and the Instituto Aaron Swartz" (body §2023 escalation); scalar:goals and scalar:outcomes now say "the civil-society demand for a total ban" (no count); scalar:sources[3].note now says "the civil-society signatory coalition (including Coding Rights and Access Now)".

Source: https://tiremeurostodasuamira.org.br/en/open-letter/
Source tier: primary
Source content: Re-fetched this pass: signatory list includes "Coding Rights" (codingrights.org), "Access Now" (accessnow.org), and "Instituto Aaron Swartz" (institutoasw.org). "No explicit total count is provided on the page." EFF "appears only in a footnote regarding a separate legal action ... a representation filed to São Paulo's Court of Accounts, not as a signatory organization."
Comparison: BOTH pass-3 corrections verified CLEARED. (1) The unsupported "66 organisations" count is removed from all three scalar locations and the body; the current "broad coalition" phrasing matches a source that states no total. (2) "Electronic Frontier Foundation" is removed from the body's named-signatory list; the source confirms EFF is not a signatory, while all three remaining named signatories are confirmed in the list.
Decision: primary-sourced

## Claim 26: "Bahia, with a R$665 million expansion to over 70 municipalities" (scalar:outcomes)

Source: https://www.biometricupdate.com/202107/brazils-bahia-state-contracts-131m-facial-recognition-system-to-tackle-criminality
Source tier: mainstream
Source content: Re-fetched this pass: "the Governor authorized the sum of Real 665 million (US$131 million) for the biometric system"; "deployed in the State capital Salvador and in 77 other cities" — 78 municipalities total.
Comparison: Amount and "over 70 municipalities" both supported. Scalar location: outcomes. One canonical source.
Decision: single-source

## Claim 27: strategies edge — strat-municipal-affirmative-ban-on-a-class-of-ai-use

Source: https://codingrights.org/en/project-item/legislators-from-all-regions-of-brazil-present-bills-to-ban-facial-recognition-in-public-spaces/
Source tier: primary
Source content: Re-fetched this pass: the communiqué documents the campaign's repertoire as state- and municipal-level bills to ban FRT in publicly accessible spaces across 13 jurisdictions — the sub-national affirmative-ban legislative pipeline.
Comparison: Edge added since pass 3 (Analyst commit). The target entity exists at product/entities/strategies/strat-municipal-affirmative-ban-on-a-class-of-ai-use.md and itself names this campaign and the #TireMeuRostoDaSuaMira letter as an instance of the strategy's open-letter escalation stage. The campaign's documented repertoire — municipal and state affirmative-ban bills on a class of AI use (FRT in public spaces) — matches the strategy's definition, so the edge points to the correct entity. The lead_orgs/participating_orgs edge (org-coding-rights) also resolves and matches the communiqué's lead-organisation list (Claim 1).
Decision: primary-sourced
