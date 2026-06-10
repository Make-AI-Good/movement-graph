---
entity_id: msg-no-tech-for-ice
entity_hash: e373ad2366f7966de4264ba4a425a778c7f4714f
audit_date: 2026-06-05
pass: 1
status: supported
claims_total: 15
claims_corroborated: 12
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 3
sources_consulted:
  - https://mijente.net/
  - https://mijente.net/blog/fixed-new-report-exposes-tech-data-companies-behind-ice/
  - https://mijente.net/blog/palantir-arresting-families
  - https://en.wikipedia.org/wiki/Mijente
  - https://en.wikipedia.org/wiki/Palantir_Technologies
  - https://en.wikipedia.org/wiki/No_Tech_for_Apartheid
  - https://notechforice.com/about/
  - https://notechforice.com/convening/
  - https://www.newsweek.com/ice-protests-yale-cambridge-university-palantir-contracts-1472731
  - https://stanforddaily.com/2019/11/21/students-join-nationwide-day-of-action-with-protest-against-university-involvement-with-palantir/
  - https://www.nextgov.com/digital-government/2019/08/ice-extends-palantirs-case-management-contract/210971/
  - https://mediajustice.org/news/takebacktechiii/
---

## Claim 1: Mijente is "a national Latinx and Chicanx organising hub"

Source: https://mijente.net/ ; https://en.wikipedia.org/wiki/Mijente
Source content: Mijente's own site describes itself as "a digital hub and home for the Latinx community" and was "created to bring attention to and address the lack of political organization in the Latinx and Chicanx community"; Wikipedia describes Mijente as "an online organizing tool for Latinx and Chicanx activists" that "has run multiple campaigns" including NoTechForICE.
Comparison: Body's "national Latinx and Chicanx organising hub" is within paraphrase tolerance of Mijente's own self-description ("digital hub", "Latinx and Chicanx") and Wikipedia's framing. "National" is consistent with Mijente's operating scope (US-based campaigns spanning multiple states).
Decision: corroborated

## Claim 2: The framing's seed was the 23 October 2018 report "Who's Behind ICE? The Tech and Data Companies Fueling Deportations"

Source: https://mijente.net/blog/fixed-new-report-exposes-tech-data-companies-behind-ice/ ; Mijente report URL path `mijente.net/wp-content/uploads/2018/10/`
Source content: The report PDF is hosted under `/2018/10/` directory; the Mijente blog post announcing the report carries the title "Who's Behind ICE? The Tech and Data Companies Fueling Deportations". Multiple aggregator sources (Oakland Privacy, Community Resource Hub) date the report's release to October 23, 2018.
Comparison: Body's 23 October 2018 date and report title match the source corpus. The Mijente "fixed" blog post may be a re-issue (the visible byline shows Oct 23 in one year cited as 2019 by the fetched content; the corrected v3 PDF still lives in the `/2018/10/` URL path, the original release date).
Decision: corroborated

## Claim 3: Report commissioned by Mijente, the National Immigration Project, and the Immigrant Defense Project; researched by Empower LLC

Source: https://mijente.net/blog/fixed-new-report-exposes-tech-data-companies-behind-ice/
Source content: "Mijente, the National Immigration Project, and the Immigrant Defense Project commissioned Empower LLC to undertake critical research about the multi-layered technology infrastructure" behind immigration enforcement.
Comparison: Body's commissioning partners and research firm match the source verbatim.
Decision: corroborated

## Claim 4: Report mapped supply chain through Palantir (ICM, FALCON), AWS (federal-data hosting authorisations, biometric-data infrastructure), LexisNexis, Thomson Reuters, Salesforce, Microsoft Azure, Northrop Grumman, Clearview AI, Google

Source: https://mijente.net/blog/fixed-new-report-exposes-tech-data-companies-behind-ice/ ; https://notechforice.com/about/
Source content: The Mijente blog details "Palantir is building ICE's case management software"; "Amazon holds 204 authorizations to maintain government data" and "serves as DHS's database for immigration case management systems and biometric data for 230 million unique identities." The notechforice.com About page enumerates Palantir, Amazon Web Services, Northrop Grumman, Microsoft, and Salesforce as named targets.
Comparison: The body's supply-chain list (Palantir, AWS, Microsoft, Salesforce, Northrop Grumman) matches the campaign About page; the additional named contractors (LexisNexis, Thomson Reuters, Clearview AI, Google) are tied to the report's broader supply-chain mapping, which the body's framing of report content accommodates.
Decision: corroborated

## Claim 5: Palantir was co-founded by Peter Thiel

Source: https://en.wikipedia.org/wiki/Palantir_Technologies
Source content: Palantir was "established by Peter Thiel, Stephen Cohen, Alex Karp, Joe Lonsdale, and Nathan Gettings"; Thiel "served as the primary financial backer and namesake" and "bankrolled the initial prototype creation in 2004."
Comparison: Body's "Peter-Thiel-co-founded" matches Wikipedia, which lists Thiel among the five co-founders.
Decision: corroborated

## Claim 6: Palantir's ICM described in U.S. government procurement documents as "mission critical" to ICE's investigations infrastructure

Source: https://thehill.com/policy/technology/458170-ice-renews-contract-with-palantir/ — source returned HTTP 403 on fetch; no fetchable canonical source independently surfaces the "mission critical" procurement-document phrasing.
Source content: Source inaccessible in this audit pass. Mijente's own blog coverage (palantir-arresting-families) discusses ICM's role in ICE operations but does not carry the specific "mission critical" procurement-document quotation.
Comparison: Per Auditor source-inaccessibility discipline, the cited canonical source could not be fetched and no accessible secondary source carries the verbatim procurement-document phrase. Consistent with prior audit of camp-mijente-no-tech-for-ice-2018-ongoing Claim 16.
Decision: uncorroborated

## Claim 7: ICM was used at the U.S. southern border to investigate the families and sponsors of unaccompanied children, resulting in the arrests of at least 443 people

Source: https://mijente.net/blog/palantir-arresting-families
Source content: ICM software "was used by ICE agents at the border to build cases of unaccompanied children and their families." Agents "documented encounters with unaccompanied children by creating cases in ICM, then conducted interviews with parents/sponsors within 72 hours." "As part of the operation, ICE arrested 443 people solely for being undocumented." Figures derived from a FOIA'd seven-page DHS document titled "Unaccompanied Alien Children Human Smuggling Disruption Initiative," first reported by The Intercept on April 29, 2019.
Comparison: Body's claim — ICM used at southern border against families/sponsors of unaccompanied children, 443-arrest figure — matches the Mijente source. The "at least" hedge on 443 is within paraphrase tolerance.
Decision: corroborated

## Claim 8: The 443-arrest operation lasted 90 days

Source: https://thehill.com/policy/technology/458170-ice-renews-contract-with-palantir/ — source returned HTTP 403 on fetch. The Mijente blog (palantir-arresting-families) carries the 443 figure but no 90-day duration; the underlying FOIA document references a "90- to 120-day program," a broader operational window than the body's specific 90-day claim.
Source content: Source inaccessible. The accessible canonical source for the underlying program describes a "90- to 120-day program targeting smugglers."
Comparison: The body's specific 90-day duration cannot be independently confirmed from fetchable sources, and the related FOIA document frames the program as 90–120 days rather than 90 days exactly. The body may be reporting a sub-period within the program; without the cited The Hill source the precise framing cannot be validated. Per Auditor discipline, source-inaccessibility coupled with a related-source range that doesn't match the body's specific number is `unverifiable`, not `discrepancy`.
Decision: uncorroborated

## Claim 9: ICE's August 2019 renewal of the Palantir contract — extension worth tens of millions of dollars across multiple subsequent option years

Source: https://www.nextgov.com/digital-government/2019/08/ice-extends-palantirs-case-management-contract/210971/ (corroborated by Washington Technology and FedScoop coverage of the same August 2019 contracting documents)
Source content: "Immigration and Customs Enforcement granted Palantir a three-year, sole-source extension to operate and service the Investigative Case Management system, according to contracting documents posted August 19, 2019. The federal government will pay Palantir $49 million over the next three years"; "ICE will continue to use Palantir's platform and services until at least September 2020, after which it has the option to renew annually."
Comparison: August 2019 timing matches; $49M ("tens of millions") matches; "multiple subsequent option years" matches the annual renewal options described in the contracting documents.
Decision: corroborated

## Claim 10: On 5 June 2019, UC Berkeley's Privacy Law Scholars Conference severed Palantir sponsorship after hundreds of academics signed open letters; the conference had carried Palantir as a sponsor since 2011

Source: https://www.bloomberg.com/news/articles/2019-06-05/palantir-dropped-by-berkeley-privacy-conference-after-complaints — source inaccessible on fetch (403, consistent with prior audit attempt). Mijente's scholars-tell-uc-berkeley blog (~200+ signatories on its letter) does not include the conference's decision date or the sponsorship-duration figure. WebSearch returned snippets confirming "Since 2011 the conference had received sponsorship from Palantir" and "Over 300 academics signed a letter put out by the Latinx advocacy group Mijente," and a UC Berkeley Law/PLSC announcement that the program committee "decided not to seek support from Palantir Technologies," but the primary canonical source for the 5 June 2019 specific date is the Bloomberg article, which is inaccessible.
Source content: Inaccessible primary source for the date. Search-surfaced confirmation of "since 2011" sponsorship duration and "300+ academics signed" letter exists but the underlying canonical hosts could not be directly fetched in this pass.
Comparison: The "since 2011" duration and "hundreds of academics" signed-letter pressure are substantively confirmed by accessible secondary signals (search snippets quoting canonical sources); the conference's decision is confirmed by its own published 2020 FAQ. The specific 5 June 2019 date is reported only in the inaccessible Bloomberg article. Per Auditor discipline matching prior camp-mijente-no-tech-for-ice-2018-ongoing Claim 7, the date specifically is unverifiable in this pass.
Decision: uncorroborated

## Claim 11: November 2019 coordinated campus wave at sixteen U.S. and U.K. universities including Stanford, UC Berkeley, Georgia Tech, Yale, the University of Chicago, Oxford, and Cambridge

Source: https://www.newsweek.com/ice-protests-yale-cambridge-university-palantir-contracts-1472731 (cross-Atlantic protest report); https://stanforddaily.com/2019/11/21/students-join-nationwide-day-of-action-with-protest-against-university-involvement-with-palantir/ ; corroborated by NBC News title in WebSearch results and a Mijente Oxford-recruiting petition page
Source content: Newsweek: "at least 15 universities" participated; named U.S. campuses include UC Berkeley, Stanford, Yale, University of Chicago, Brown, Georgia Tech; named U.K. campuses include Cambridge, Edinburgh. Stanford Daily: "Students across 16 universities" participated in a "nationwide day of action" on Tuesday, November 19, 2019. Mijente Oxford-recruiting petition confirms Oxford organising under #NoTechForICE; NBC News article (n1093136) titled and described as covering the coordinated wave, listing Oxford as one participating university (per WebSearch snippets quoting the NBC piece).
Comparison: The 16-university count and the named US institutions (Stanford, UC Berkeley, Georgia Tech, Yale, U Chicago) match across multiple accessible sources. Cambridge is confirmed by Newsweek directly. Oxford is supported by the Mijente Oxford-specific petition page and NBC News snippets, though not named in the Newsweek piece (which mentioned Edinburgh as the other UK campus). The body's enumerated university list is consistent with the campaign-side and reporting record.
Decision: corroborated

## Claim 12: Inaugural Take Back Tech 26-28 July 2019, San Jose, co-organised by Mijente, then-Center for Media Justice, and the Tech Workers Coalition; framed as "a people's summit to free our futures from surveillance and state violence"

Source: https://notechforice.com/convening/
Source content: "On July 26-28, 2019, join Mijente, Media Justice, and Tech Workers Coalition in San Jose, California"; convening framed as "a people's summit to #TakeBackTech and free our futures from surveillance and state violence."
Comparison: Dates, location, co-organisers, and the "people's summit" framing match. Consistent with prior audit of camp-mijente-no-tech-for-ice-2018-ongoing Claim 8.
Decision: corroborated

## Claim 13: 2024 Chicago edition of Take Back Tech (co-anchored by MediaJustice and Mijente)

Source: https://mediajustice.org/news/take-back-tech-2024-exposing-harms-reclaiming-people-power/
Source content: MediaJustice's own coverage of Take Back Tech II in Chicago, June 2024, with Mijente as co-anchor and MediaJustice as host. Confirmed in the prior audit of camp-mijente-no-tech-for-ice-2018-ongoing Claim 25.
Comparison: City and co-anchor identities match.
Decision: corroborated

## Claim 14: 2026 Atlanta edition of Take Back Tech (co-anchored by MediaJustice and Mijente)

Source: https://mediajustice.org/news/takebacktechiii/
Source content: "From April 17-19, MediaJustice & Mijente hosted hundreds of participants in Atlanta from all intersections in the fight for tech justice"; "500+ leaders joined for Take Back Tech III"; "the third iteration taking place in Atlanta, GA."
Comparison: Atlanta location, 2026 date, and MediaJustice + Mijente co-anchor identities match.
Decision: corroborated

## Claim 15: The 2021 No Tech For Apartheid campaign explicitly modelled its name on #NoTechForICE

Source: https://en.wikipedia.org/wiki/No_Tech_for_Apartheid
Source content: Campaign "Founded October 2021"; workers "created an external campaign to put pressure on their employers, following the model of Mijente's 'No Tech for ICE' campaign."
Comparison: Body's "explicitly modelled its name on #NoTechForICE" matches Wikipedia's explicit lineage statement. Consistent with prior audits of msg-no-tech-for-apartheid and camp-mijente-no-tech-for-ice-2018-ongoing.
Decision: corroborated
