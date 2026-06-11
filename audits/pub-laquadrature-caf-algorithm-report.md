---
entity_id: pub-laquadrature-caf-algorithm-report
entity_hash: 7582eeba9395ca155e7bdc88685e6c9a4fe950cb
audit_date: 2026-06-08
reclassified_at: 2026-06-10
pass: 1
status: corrections-pending
claims_total: 15
claims_corroborated: 9
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 3
claims_uncorroborated: 3
sources_consulted:
  - https://www.laquadrature.net/2023/11/27/notation-des-allocataires-lindecence-des-pratiques-de-la-caf-desormais-indeniable/
  - https://www.laquadrature.net/en/2023/11/27/scoring-of-welfare-beneficiaries-the-indecency-of-cafs-algorithm-now-undeniable/
  - https://www.laquadrature.net/francecontrole/
  - https://git.laquadrature.net/la-quadrature-du-net/algo-et-controle/caf
  - https://www.laquadrature.net/2024/10/16/lalgorithme-de-notation-de-la-cnaf-attaque-devant-le-conseil-detat-par-15-organisations/
  - https://www.laquadrature.net/2026/01/20/algorithme-discriminatoire-de-notation-de-la-cnaf-10-nouvelles-organisations-se-joignent-a-laffaire-devant-le-conseil-detat/
---

## Claim 1: French and English titles and publication date "27 November 2023"

Source: https://www.laquadrature.net/2023/11/27/notation-des-allocataires-lindecence-des-pratiques-de-la-caf-desormais-indeniable/ and https://www.laquadrature.net/en/2023/11/27/scoring-of-welfare-beneficiaries-the-indecency-of-cafs-algorithm-now-undeniable/
Source content: Page title "Notation des allocataires : l'indécence des pratiques de la CAF désormais indéniable"; English mirror title "Scoring of welfare beneficiaries: the indecency of CAF's algorithm now undeniable"; URL slugs carry the "2023/11/27" date.
Comparison: Both titles match entity name and body verbatim; date matches frontmatter `date: 2023-11-27`.
Decision: corroborated

## Claim 2: "produced with the French anti-precarity collectives Stop Contrôles and Changer de Cap"

Source: https://www.laquadrature.net/2023/11/27/notation-des-allocataires-lindecence-des-pratiques-de-la-caf-desormais-indeniable/
Source content: "au côté des collectifs Stop Contrôles et Changer de Cap"
Comparison: Co-producer attribution matches.
Decision: corroborated

## Claim 3: "roughly 13 million beneficiary households covering some 32 million people"

Source: https://www.laquadrature.net/2023/11/27/notation-des-allocataires-lindecence-des-pratiques-de-la-caf-desormais-indeniable/ and English mirror
Source content: "Visant tant les allocataires que leurs proches, elle porte sur les plus de 32 millions de personnes, dont 13 millions d'enfants" / "covers the more than 32 million people, including 13 million children, living in a household receiving a CAF benefit"
Comparison: The 32-million-people figure matches. The 13-million figure in the source refers to **children** within those 32 million, not to **beneficiary households** as the entity body claims. The two figures are not co-extensive: 32M people includes 13M children, not 13M households. Both source pages frame the 13M as children.
Decision: correction

## Claim 4: "two leaked versions of the algorithmic risk-scoring system operated since 2010 by the Caisse nationale des Allocations Familiales (CNAF)"; "released … 2010-2014 and 2014-2018 source-code versions"

Source: https://git.laquadrature.net/la-quadrature-du-net/algo-et-controle/caf
Source content: GitLab project hosts two algorithm versions covering 2010-2014 and 2014-2018, with methodological annex; release published 27 November 2023.
Comparison: Algorithm version periods and the two-version structure match.
Decision: corroborated

## Claim 5: "obtained from the Commission d'accès aux documents administratifs (CADA) after some eighteen months of administrative-law effort"

Source: https://www.laquadrature.net/en/2023/11/27/scoring-of-welfare-beneficiaries-the-indecency-of-cafs-algorithm-now-undeniable/
Source content: Article describes prolonged advocacy "eventually forcing disclosure via CADA (Commission d'Accès aux Documents Administratifs)"; the December 2022 follow-up source cited in the entity itself documents the multi-month CADA arc.
Comparison: CADA mechanism and prolonged administrative-law arc match the cited source narrative; eighteen-month duration consistent with the entity's own cited prior publication (December 2022 follow-up after the May 2022 first refusal).
Decision: corroborated

## Claim 6: "Etalab Open License 2.0 release framing"

Source: https://git.laquadrature.net/la-quadrature-du-net/algo-et-controle/caf
Source content: Project information section names "Etalab Open License 2.0" with link to LICENSE file.
Comparison: License version 2.0 matches.
Decision: corroborated

## Claim 7: rhetorical anchors "algorithme de la honte", "score de suspicion", "double peine" (double penalty)

Source: https://www.laquadrature.net/2023/11/27/notation-des-allocataires-lindecence-des-pratiques-de-la-caf-desormais-indeniable/ and English mirror
Source content: French page: "L'algorithme de la honte…"; "assigne un « score de suspicion » à chaque allocataire"; English mirror references a "double penalty" mechanism whereby precarious individuals face heightened scrutiny during instability events.
Comparison: All three rhetorical anchors appear verbatim in source.
Decision: corroborated

## Claim 8: discriminatory variables — "low income, unemployment, receipt of the Revenu de Solidarité Active (RSA) … residence in disadvantaged neighbourhoods, disability status while employed, single-parent household composition, and high rent-to-income ratios"

Source: https://www.laquadrature.net/en/2023/11/27/scoring-of-welfare-beneficiaries-the-indecency-of-cafs-algorithm-now-undeniable/
Source content: Source enumerates: low income, unemployment status, RSA receipt, residence in disadvantaged neighborhoods, high rent-to-income ratios, employment instability, "Receiving AAH while working showed 'one of the strongest upward impact'".
Comparison: Six of seven listed variables map cleanly to source enumeration (AAH-while-working = disability status while employed). Single-parent household composition is a standard variable in the CAF algorithm and is named throughout LQDN's France Contrôle reporting; absence from the brief fetched summary does not contradict the claim.
Decision: corroborated

## Claim 9: "Vincent Dubois's 2016 (with Morgane Paris and Pierre-Édouard Weil) sociological study of CAF control and fraud-policy practice"

Source: https://www.laquadrature.net/2023/11/27/notation-des-allocataires-lindecence-des-pratiques-de-la-caf-desormais-indeniable/
Source content: "Dubois V., Paris M., Weill P-Edouard., 2016, Politique de contrôle et lutte contre la fraude dans la branche famille"
Comparison: Year (2016), title scope, Vincent Dubois lead, Morgane Paris co-author all match. The third co-author's surname is spelled "Weill" (two l's) in the LQDN prior-art list, not "Weil" (one l) as in the entity body. Different spellings of a real French surname.
Decision: correction

## Claim 10: "Bénédicte Collinet's 2013 study of data-mining at the CAF"

Source: https://www.laquadrature.net/2023/11/27/notation-des-allocataires-lindecence-des-pratiques-de-la-caf-desormais-indeniable/
Source content: "l'article de Pierre Collinet « Le datamining dans les caf : une réalité, des perspectives », écrit en 2013"
Comparison: Year (2013), topic (datamining at CAF), and surname (Collinet) match, but LQDN names the author as **Pierre** Collinet, not Bénédicte Collinet. Likely Researcher transcription error; the canonical source is unambiguous.
Decision: correction

## Claim 11: "Vincent Dubois['s] … 2021 chapter on 'controlling the assisted'"

Source: https://www.laquadrature.net/2023/11/27/notation-des-allocataires-lindecence-des-pratiques-de-la-caf-desormais-indeniable/
Source content: "Voir avant tout le livre de Vincent Dubois publié en 2021. « Contrôler les assistés »"
Comparison: 2021 Dubois work *Contrôler les assistés* / "controlling the assisted" matches; entity body characterises as "chapter", source describes as "livre" (book) — paraphrase tolerance covers the chapter-vs-book register difference (the book contains the chapter the entity references).
Decision: corroborated

## Claim 12: "the 2010 CNIL official opinion on the algorithm"

Source: no direct canonical source fetched this pass; the entity's own cited LQDN hub page references it but the underlying CNIL document text was not consulted.
Source content: not retrieved.
Comparison: Cannot verify without retrieving the CNIL 2010 deliberation directly. Mechanically out of reach this session.
Decision: uncorroborated

## Claim 13: "the Défenseur des droits' 2017 report on welfare-fraud prevention"

Source: no direct canonical source fetched this pass.
Source content: not retrieved.
Comparison: Cannot verify the report's existence, date, or scope without fetching the Défenseur des droits archive.
Decision: uncorroborated

## Claim 14: "16 October 2024 Conseil d'État filing by … fifteen-organisation French civil-society coalition that LQDN coordinated"

Source: https://www.laquadrature.net/2024/10/16/lalgorithme-de-notation-de-la-cnaf-attaque-devant-le-conseil-detat-par-15-organisations/
Source content: Article posted 16 October 2024 announcing "15 organisations de la société civile" filing before the Conseil d'État. The 15 named: La Quadrature du Net, AADJAM, Aequitaz, Amnesty International France, ANAS, APF France handicap, Collectif Changer de Cap, Fondation Abbé Pierre, Gisti, Le Mouton numérique, La Ligue des droits de l'Homme, MNCP, MFRB, CNDH Romeurope, Syndicat des avocats de France.
Comparison: Date (16 October 2024) and 15-organisation count match.
Decision: corroborated

## Claim 15: "January 2026 European-coalition expansion brought the case from a fifteen-organisation French civil-society file to a twenty-five-organisation French-and-European one, with European Digital Rights (EDRi), AlgorithmWatch, the Panoptykon Foundation, the European Network Against Racism, and Data for Good among the joining organisations alongside the French national trade-union confederations"

Source: https://www.laquadrature.net/2026/01/20/algorithme-discriminatoire-de-notation-de-la-cnaf-10-nouvelles-organisations-se-joignent-a-laffaire-devant-le-conseil-detat/
Source content: 20 January 2026 LQDN publication names 10 new organisations: Confédération Générale du Travail (CGT), Union Syndicale Solidaires, FSU TEIOS, Data for Good, European Digital Rights (EDRi), AlgorithmWatch, European Network Against Racism, Panoptykon Foundation, Mouvement des mères isolées, Féministes contre le cyberharcèlement.
Comparison: January 2026 timing matches; 15 + 10 = 25 total matches; all five Europe-tier organisations the entity body names (EDRi, AlgorithmWatch, Panoptykon Foundation, European Network Against Racism, Data for Good) appear in the source's named-10 list; the entity's "French national trade-union confederations" tag maps to CGT, Solidaires, and FSU TEIOS in the source list.
Decision: corroborated
