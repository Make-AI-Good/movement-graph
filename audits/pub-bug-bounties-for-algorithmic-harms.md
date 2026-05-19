---
entity_id: pub-bug-bounties-for-algorithmic-harms
entity_hash: d564aeeba6aa6509b9ab0de7f7d3c0b2343299aa
audit_date: 2026-05-18
pass: 1
status: unverifiable
claims_total: 13
claims_verified: 10
claims_discrepancy: 0
claims_unverifiable: 3
sources_consulted:
  - https://www.ajl.org/bugs
  - https://aihub.org/2022/02/09/bug-bounties-for-algorithmic-harms-a-report-from-the-algorithmic-justice-league/
  - https://mediawell.ssrc.org/news-items/bug-bounties-for-algorithmic-harms-algorithmic-justice-league/
  - https://www.ajl.org/crash-project
  - https://www.macfound.org/press/grantee-publications/bug-bounties-to-expose-and-prevent-algorithmic-harms
  - https://www.biometricupdate.com/202103/use-bug-bounty-to-tackle-biometric-algorithm-bias-algorithmic-justice-league-researcher-argues
  - https://en.wikipedia.org/wiki/Algorithmic_Justice_League
---

## Claim 1: full title and subtitle — "Bug Bounties For Algorithmic Harms? Lessons from Cybersecurity Vulnerability Disclosure for Algorithmic Harms Discovery, Disclosure, and Redress"

Source: https://aihub.org/2022/02/09/bug-bounties-for-algorithmic-harms-a-report-from-the-algorithmic-justice-league/
Source content: "Kenway, Josh, Camille François, Sasha Costanza-Chock, Inioluwa Deborah Raji, and Joy Buolamwini. *Bug Bounties For Algorithmic Harms? Lessons from Cybersecurity Vulnerability Disclosure for Algorithmic Harms Discovery, Disclosure, and Redress.* Washington, DC: Algorithmic Justice League. January 2022."
Comparison: Body subtitle matches the formal citation reproduced in AIhub coverage exactly; also matches the title on the AJL landing page.
Decision: verified

## Claim 2: published by the Algorithmic Justice League

Source: https://www.ajl.org/bugs
Source content: "Publisher: Algorithmic Justice League (AJL)" (also reproduced in the AIhub citation as "Washington, DC: Algorithmic Justice League").
Comparison: Body and frontmatter `publisher: org-algorithmic-justice-league` match the canonical source.
Decision: verified

## Claim 3: published 27 January 2022

Source: https://mediawell.ssrc.org/news-items/bug-bounties-for-algorithmic-harms-algorithmic-justice-league/
Source content: "By Josh Kenway, Camille François, Sasha Costanza-Chock, Inioluwa Deborah Raji, and Joy Buolamwini on January 27, 2022"
Comparison: Body date "27 January 2022" matches MediaWell's "January 27, 2022" exactly. Frontmatter `date: 2022-01-27` matches.
Decision: verified

## Claim 4: authored by Josh Kenway, Camille François, Sasha Costanza-Chock, Inioluwa Deborah Raji, and Joy Buolamwini

Source: https://aihub.org/2022/02/09/bug-bounties-for-algorithmic-harms-a-report-from-the-algorithmic-justice-league/
Source content: "Kenway, Josh, Camille François, Sasha Costanza-Chock, Inioluwa Deborah Raji, and Joy Buolamwini."
Comparison: Body list (five names, same order, same spellings) matches the formal citation exactly.
Decision: verified

## Claim 5: foundational publication of AJL's Community Reporting of Algorithmic System Harms (CRASH) project

Source: https://www.ajl.org/crash-project
Source content: The CRASH project page identifies the project as "Community Reporting of Algorithmic System Harms" and "brings together key stakeholders for discovery, scoping, and iterative prototyping of tools to enable broader participation in the creation of more accountable, equitable, and less harmful AI systems"; the AJL landing page for the report (https://www.ajl.org/bugs) presents this report as the project's launch publication.
Comparison: The CRASH project name expansion matches. The "foundational publication" framing is the AJL-side characterization of the report as the project's launch artefact; not a contested claim.
Decision: verified

## Claim 6: CRASH was originally launched as the Algorithmic Vulnerability Bounty Project

Source: https://www.ajl.org/crash-project
Source content: "FORMERLY Algorithmic Vulnerability Bounty Project"
Comparison: AJL's own CRASH project page explicitly names this as the project's prior name. Matches body.
Decision: verified

## Claim 7: CRASH/Algorithmic Vulnerability Bounty Project launched in July 2020

Source: no canonical source found
Source content: The AJL CRASH project page confirms the renaming from Algorithmic Vulnerability Bounty Project but does not give a launch date; the AJL "about" page and the Wikipedia entry for Algorithmic Justice League I consulted do not state a July 2020 launch date; the Wayback Machine fetch was unavailable in this session.
Comparison: The specific July 2020 launch date for the predecessor project could not be confirmed from any source fetched this pass.
Decision: unverifiable

## Claim 8: Twitter's 2021 algorithmic-bias bounty pilot

Source: https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: Per the Wikipedia entry for the Algorithmic Justice League, results from Twitter's photo-cropping algorithmic-bias bounty challenge — "Twitter's photo-cropping algorithm prefers young, beautiful, and light-skinned faces" — were published on August 10, 2021.
Comparison: Body's "Twitter's 2021 algorithmic-bias bounty pilot" matches the 2021 timing of the Twitter challenge. The pilot is a definitional public event consistent with the Wikipedia-alone canonicality rule for dates of public events.
Decision: verified

## Claim 9: five summary takeaways as listed in the body

Source: https://aihub.org/2022/02/09/bug-bounties-for-algorithmic-harms-a-report-from-the-algorithmic-justice-league/
Source content: AIhub reproduces five takeaways: "Prepare organizations to include socio-technical concerns…"; "Recognize bug bounties as one tool among many; supplement with additional mechanisms…"; "Foster community practice by sharing educational materials and resources across disciplines"; "Intentionally recruit diverse researchers and advocates with fair compensation structures"; "Protect third-party research and 'guarantee some form of public disclosure'".
Comparison: Body's paraphrase of the five takeaways (operators preparing for socio-technical concerns rather than bolt-ons; lifecycle accompaniment with other accountability mechanisms; nurturing a community of practice not excluding non-computer-scientists; intentional diverse-community development with fair compensation; protected participatory adversarial research with guaranteed public disclosure) maps each AIhub bullet within paraphrase tolerance.
Decision: verified

## Claim 10: AJL is a grantee under the MacArthur Foundation's Technology in the Public Interest programme

Source: https://www.macfound.org/press/grantee-publications/bug-bounties-to-expose-and-prevent-algorithmic-harms
Source content: MacArthur identifies AJL as a grantee in the context of its Technology in the Public Interest programme via this report's grantee-publications listing.
Comparison: Body claim matches MacArthur's own framing on its grantee-publications page.
Decision: verified

## Claim 11: report's published acknowledgements credit the Alfred P. Sloan Foundation, the Rockefeller Foundation, and the Mozilla Foundation as supporting funders

Source: no canonical source found
Source content: The AJL landing page fetch does not surface an acknowledgements section; the PDF asset fetch returns binary that cannot be parsed for text in this session; the MacArthur grantee page covers MacArthur's own funding only.
Comparison: The specific funder list could not be cross-checked against a source readable in this pass.
Decision: unverifiable

## Claim 12: third AJL-anchored Publication in the corpus after Unmasking AI and Comply To Fly?

Source: corpus state — `product/entities/publications/pub-unmasking-ai.md` (created 2026-05-08), `product/entities/publications/pub-comply-to-fly.md` (created 2026-05-08), `product/entities/publications/pub-bug-bounties-for-algorithmic-harms.md` (created 2026-05-09)
Source content: Frontmatter `created:` dates and grep over the publications subdirectory for `org-algorithmic-justice-league` references confirm the three named entities are the AJL-anchored Publications, with pub-bug-bounties created last of the three.
Comparison: Body's positional claim matches corpus state.
Decision: verified

## Claim 13: report sits earliest in time of the three AJL Publications

Source: corpus state — `date: 2022-01-27` (bug-bounties), `date: 2023-10-31` (unmasking-ai), `date: 2025-07-29` (comply-to-fly)
Source content: Frontmatter `date:` fields on the three publication entities.
Comparison: 2022-01-27 is earliest of the three. Matches body.
Decision: verified
