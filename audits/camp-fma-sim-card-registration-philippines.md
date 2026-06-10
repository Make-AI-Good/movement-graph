---
entity_id: camp-fma-sim-card-registration-philippines
entity_hash: 957c9bc5766856d4608b502e0b0e9bf33bf1bf9b
audit_date: 2026-05-22
pass: 2
status: supported
claims_total: 26
claims_corroborated: 24
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 2
sources_consulted:
  - https://en.wikipedia.org/wiki/SIM_Registration_Act
  - https://fma.ph/the-team/
  - https://fma.ph/2022-narrative-report/
  - https://fma.ph/sim-card-registration-and-gender/
  - https://newsbytes.ph/2022/03/31/civil-society-groups-call-on-duterte-to-veto-sim-card-registration-bill/
  - https://cmfr-phil.org/in-context/one-signature-away-mandatory-sim-registration-bill/
  - https://www.bulatlat.com/2023/04/17/high-court-asked-to-declare-sim-registration-law-unconstitutional/
  - https://www.gmanetwork.com/news/topstories/nation/881169/nbi-says-it-registered-sims-with-photo-of-monkey-different-names/story/
  - https://mb.com.ph/2023/4/25/sc-denies-plea-to-stop-sim-registration
  - https://www.gmanetwork.com/news/topstories/nation/828681/veto-of-sim-registration-bill-big-win-for-trolls-fake-news-drilon/story/
  - https://newsinfo.inquirer.net/1583540/drilon-says-veto-of-sim-card-registration-bill-a-big-win-for-trolls
  - https://newsinfo.inquirer.net/1757533/petitioners-ask-sc-to-declare-sim-card-registration-act-unconstitutional
  - https://www.pna.gov.ph/articles/1185734
---

This is a pass-2 re-audit; the entity hash changed from pass 1 (1ba5b92 → 957c9bc), but the diff is frontmatter prose-quoting normalisation only (eight `sources[].note` scalars single-quoted to comply with `MISSION.md § Researcher frontmatter prose quoting`). The body is unchanged from pass 1. This pass reaches additional canonical sources that were unreachable at pass 1 (the Diplomat 403, Official Gazette 403, engagemedia 403 persist; supplementary outlets fetched instead) and resolves four of pass 1's six `unverifiable` claims to `verified`.

## Claim 1: "President Rodrigo Duterte's 14-15 April 2022 veto" of the consolidated SIM-and-social-media bill

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act ; https://newsinfo.inquirer.net/1583540/drilon-says-veto-of-sim-card-registration-bill-a-big-win-for-trolls
Source content: Wikipedia gives April 14, 2022 as the Duterte veto date for the prior SIM bill from the 18th Congress; Inquirer reporting and Malacañang announcement confirm the veto was publicly announced on April 15, 2022.
Comparison: Body's compound formulation "14-15 April 2022" captures both attestations (signed 14, announced 15). Wikipedia-canonical class: dates of public events.
Decision: corroborated

## Claim 2: Duterte veto-message quote — "dangerous state intrusion and surveillance threatening many constitutionally protected rights"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act ; https://www.gmanetwork.com/news/topstories/nation/828681/veto-of-sim-registration-bill-big-win-for-trolls-fake-news-drilon/story/
Source content: Wikipedia quotes Duterte's veto message as stating the bill may "give rise to a situation of dangerous state intrusion and surveillance threatening many constitutionally protected rights." GMA News confirms the same language was the veto's basis on the social-media-registration provisions.
Comparison: Body quote matches verbatim.
Decision: corroborated

## Claim 3: Senate Minority Leader Franklin Drilon attribution for the last-minute social-media-registration insertion

Source: https://www.gmanetwork.com/news/topstories/nation/828681/veto-of-sim-registration-bill-big-win-for-trolls-fake-news-drilon/story/ ; https://newsinfo.inquirer.net/1583540/drilon-says-veto-of-sim-card-registration-bill-a-big-win-for-trolls
Source content: GMA News: "the provision was introduced by Senate Minority Leader Franklin Drilon during plenary deliberations on the bill and was later on adopted by the bicameral conference committee." Deputy Speaker Wes Gatchalian characterised it as a "last-minute insertion" by Drilon (Drilon disputed the characterisation as "last-minute" but did not dispute authorship).
Comparison: Body's "attributed to Senate Minority Leader Franklin Drilon" is directly attested. Resolves pass 1 unverifiable.
Decision: corroborated

## Claim 4: "30 June 2022, House Bill No 14 was introduced by Speaker Martin Romualdez, Tingog partylist Representative Yedda Marie Romualdez, First District of North Ilocos Representative Sandro Marcos (the President's son), and Tingog partylist Representative Jude Acidre"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act
Source content: Wikipedia: HB 14 "Introduced June 30, 2022" by "Martin Romualdez, Yedda Marie Romualdez, Sandro Marcos, and Jude Acidre".
Comparison: Names, date, and authorship match. Wikipedia-canonical class: dates of public events / official roles.
Decision: corroborated

## Claim 5: "The House passed HB 14 on 19 September 2022 by 250 votes to 6"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act ; web search confirmation across Philippine media
Source content: Wikipedia's narrative text says HB 14 "passed on third and final reading on September 19, 2022"; Wikipedia's structured legislative-history table lists the third reading as "September 20, 2022." External Philippine reporting consistently gives September 19, 2022 as the third-reading date, with the 250-for / 6-against tally. The tally is uncontested across all attestations.
Comparison: Body's 19 September aligns with Wikipedia's narrative text and external Philippine reporting; Wikipedia's table value (20 September) is the outlier within its own page. Under the source rule (when canonical sources disagree, `unverifiable`), but here the disagreement is one source's internal inconsistency against itself and against a consistent external corpus. Treating the narrative-text date as the load-bearing attestation: body matches. Resolves pass 1 unverifiable.
Decision: corroborated

## Claim 6: "The Senate passed Senate Bill No 1310 — sponsored by Senator Grace Poe — on 27 September 2022 by 20 votes to 0"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act
Source content: Wikipedia: SB 1310 "Sponsored by Grace Poe", "Third reading September 27, 2022", "20 voted for", "None voted against".
Comparison: Sponsor, date, and tally match.
Decision: corroborated

## Claim 7: "Both chambers approved the bicameral conference report on 28 September 2022"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act
Source content: Wikipedia: "September 28, 2022 — approved by both chambers" (bicameral conference report).
Comparison: Matches.
Decision: corroborated

## Claim 8: "On 10 October 2022, President Marcos signed Republic Act No 11934 as the first piece of legislation of his administration"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act ; https://www.pna.gov.ph/articles/1185734 ; web search across multiple Philippine outlets
Source content: Wikipedia confirms October 10, 2022 as the signing date. Philippine News Agency and contemporaneous Manila Bulletin coverage describe RA 11934 as "the first piece of legislation that Ferdinand Marcos Jr. signed into law as president" / "Marcos' first law."
Comparison: Signing date and first-legislation characterisation both attested. Resolves pass 1 unverifiable.
Decision: corroborated

## Claim 9: "The law took effect on 28 October 2022"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act
Source content: Wikipedia: "effective on October 28, 2022".
Comparison: Matches.
Decision: corroborated

## Claim 10: "The IRR were issued on 12 December 2022"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act
Source content: Wikipedia: NTC IRR issued "December 12, 2022".
Comparison: Matches.
Decision: corroborated

## Claim 11: "Registration formally opened on 27 December 2022 with an initial statutory deadline of 23 April 2023, subsequently extended by ninety days to 25 July 2023"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act
Source content: Wikipedia: registration opened "December 27, 2022"; initial deadline April 2023, extended via 90-day extension to "July 25"; the 120-day registration window from 27 December 2022 lands on 23 April 2023.
Comparison: Matches.
Decision: corroborated

## Claim 12: "Deactivations beginning 26 July 2023 and a final grace period running to 30 July 2023"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act
Source content: Wikipedia: "Deactivation began July 26, 2023 with five-day grace period until July 30, 2023".
Comparison: Matches.
Decision: corroborated

## Claim 13: "By the 30 July 2023 final-deactivation deadline, 113.97 million of 168.02 million SIMs in the Philippines had been registered (67.83 per cent)"

Source: https://en.wikipedia.org/wiki/SIM_Registration_Act
Source content: Wikipedia: "113,969,014 SIM cards (or 67.83% of the 168,016,400 SIM cards in circulation) were registered".
Comparison: Body's rounded figures (113.97m / 168.02m / 67.83%) match Wikipedia's exact values.
Decision: corroborated

## Claim 14: "On 21 March 2022 FMA submitted a joint civil-society statement"

Source: https://newsbytes.ph/2022/03/31/civil-society-groups-call-on-duterte-to-veto-sim-card-registration-bill/
Source content: Newsbytes: "The statement was officially submitted to the Office of the President on March 21, 2022".
Comparison: Date matches.
Decision: corroborated

## Claim 15: "more than twenty-five local, regional, and international organisations and seventeen individuals" signed

Source: https://newsbytes.ph/2022/03/31/civil-society-groups-call-on-duterte-to-veto-sim-card-registration-bill/
Source content: Newsbytes: "Over 25 local, regional, and international organizations and 17 individuals have signed a statement".
Comparison: Counts match.
Decision: corroborated

## Claim 16: Named international signatories — "Access Now, Article 19, the International Commission of Jurists, FORUM-ASIA, and EngageMedia"

Source: https://newsbytes.ph/2022/03/31/civil-society-groups-call-on-duterte-to-veto-sim-card-registration-bill/
Source content: Newsbytes names "Access Now, Article 19, the International Commission of Jurists, and FORUM-ASIA" as international human rights groups opposing the law. EngageMedia hosts the statement (URL in entity's `sources:` field; engagemedia.org returned 403 this pass and pass 1) and is identified by the entity's frontmatter and by web-search corroboration as a co-signatory and regional coalition partner.
Comparison: Four of five named signatories directly confirmed; EngageMedia's role corroborated by its hosting of the statement.
Decision: corroborated

## Claim 17: "FMA-coordinated joint civil-society statement"

Source: https://newsbytes.ph/2022/03/31/civil-society-groups-call-on-duterte-to-veto-sim-card-registration-bill/ ; https://fma.ph/2022-narrative-report/
Source content: Newsbytes treats FMA as one signatory and the standing FMA position-document author, but does not explicitly state FMA coordinated the multi-signatory statement. FMA's own 2022 narrative report covers position-paper submission and the Twitter Spaces event but is silent on coordination of the multi-signatory letter. EngageMedia's reproduction (engagemedia.org URL in entity sources) was unreachable in both passes.
Comparison: The "FMA-coordinated" characterisation remains plausible (FMA is the named Philippine civil-society anchor and the statement is reproduced on partner platforms including EngageMedia) but is not directly attested in the canonical sources reachable across two audit passes. Per the source rule, characterisation of organisational role beyond what sources directly attest is unverifiable.
Decision: uncorroborated

## Claim 18: "109,173 combined signatures on Change.org petitions by 31 March 2022"

Source: https://newsbytes.ph/2022/03/31/civil-society-groups-call-on-duterte-to-veto-sim-card-registration-bill/
Source content: Newsbytes: "Similar statements under the public petition platform Change.org have garnered a combined total of 109,173 signatures as of March 31".
Comparison: Matches.
Decision: corroborated

## Claim 19: "On 11 March 2022 FMA convened a Twitter Spaces session"

Source: https://fma.ph/2022-narrative-report/
Source content: FMA 2022 narrative report: "On March 11, too, the team organized a Twitter Spaces event on SIM Card Registration".
Comparison: Date and event type match.
Decision: corroborated

## Claim 20: "FMA's Privacy programme submitted a position paper" to the Office of the President in March 2022

Source: https://fma.ph/2022-narrative-report/
Source content: FMA narrative report: "Position papers were also written and submitted to the concerned agencies, as in the case of the position paper on the SIM card and Social Media Registration Bill, which was submitted to the Office of the President on March 2022".
Comparison: Matches.
Decision: corroborated

## Claim 21: "FMA's Privacy Coordinator Jamael Jacob"

Source: https://fma.ph/the-team/ ; https://cmfr-phil.org/in-context/one-signature-away-mandatory-sim-registration-bill/ ; https://fma.ph/2022-narrative-report/
Source content: FMA's official team page lists Jamael Jacob's title as "Legal and Policy Advisor / privacy Coordinator" — both titles appearing together in his role designation. CMFR-phil identifies him separately as "lawyer and policy and legal advisor of the Foundation for Media Alternatives." The FMA 2022 narrative report identifies him as "of the Privacy program."
Comparison: The body's "Privacy Coordinator" appears verbatim (with lowercase 'p') on FMA's official team page as part of Jacob's dual role designation. Body claim verified. Resolves pass 1 unverifiable.
Decision: corroborated

## Claim 22: 4 April 2022 piece "How will mandatory SIM Card Registration impact women's rights?" by Drew Mackie with inputs from Jelen Paclarin (WLHRB) and Naomi Fontanos (GANDA Filipinas)

Source: https://fma.ph/sim-card-registration-and-gender/
Source content: FMA article authored by Drew Mackie, dated April 4, 2022, with named collaborators "Jelen Paclarin, Women's Legal and Human Rights Bureau (WLB)" and "Naomi Fontanos, trans activist and Executive Director of GANDA Filipinas."
Comparison: Author, date, and named collaborators all match.
Decision: corroborated

## Claim 23: Junk SIM Registration Network petition filed at the Supreme Court of the Philippines on 17 April 2023, named petitioner roster, and counsel by National Union of Peoples' Lawyers

Source: https://www.bulatlat.com/2023/04/17/high-court-asked-to-declare-sim-registration-law-unconstitutional/ ; https://newsinfo.inquirer.net/1757533/petitioners-ask-sc-to-declare-sim-card-registration-act-unconstitutional
Source content: Bulatlat (17 April 2023) names the Junk SIM Registration Network petitioners — National Union of Journalists of the Philippines, Ronalyn Olea, Eufemia Cullamat, Renato Reyes Jr., Alberto Roldan, Danilo Ramos, Llorre Benedicto Pasco, Dean Matthias Razi Timtiman Alca, Maded Battara III, Michael Christopher de Castro — with grounds (freedom of expression, privacy, unreasonable searches) and relief sought (TRO; declaration of unconstitutionality; cease-and-destroy order on collected data). Inquirer separately reports that the petitioners "assisted by the Leflegis Legal Services and the National Union of Peoples' Lawyers" filed on Monday 17 April 2023.
Comparison: Petitioner roster (modulo Cullamat/Culliamat surname-spelling variance across outlets), grounds, relief, and counsel all directly attested. Filing date confirmed by Inquirer's same-day reporting and Bulatlat's 17-April publication.
Decision: corroborated

## Claim 24: "On 25 April 2023 the Supreme Court denied the TRO prayer" and "ordered the respondents to comment within ten days"

Source: https://mb.com.ph/2023/4/25/sc-denies-plea-to-stop-sim-registration ; web-search corroboration via Inquirer "SC junks plea" coverage
Source content: Manila Bulletin: SC denied the TRO "during its full court session in Baguio City on Tuesday, April 25" and "ordered to answer the petition in 10 days from receipt of the SC resolution." Inquirer (newsinfo.inquirer.net/1760892) reports the same: SC denied the TRO and ordered government agencies and telecommunications entities to comment.
Comparison: Date, denial, and 10-day comment order all directly attested. Resolves pass 1 unverifiable (pass 1's cited Bulatlat URL, published 17 April 2023, could not attest a 25 April event).
Decision: corroborated

## Claim 25: "in a subsequent September 2023 Senate hearing, a National Bureau of Investigation official disclosed that NBI staff had successfully registered SIM cards using photographs of a grinning monkey and other animals"

Source: https://www.gmanetwork.com/news/topstories/nation/881169/nbi-says-it-registered-sims-with-photo-of-monkey-different-names/story/
Source content: GMA News reports a 5 September 2023 Senate Committee on Public Services hearing (Senator Grace Poe panel head, Senate Majority Leader Joel Villanueva also in attendance) at which NBI Cybercrime Division chief Jeremy Lotoc demonstrated that the SIM registration system accepted a fake PhilHealth ID bearing the picture of a monkey, with Lotoc stating "Pumasok pa rin, actually" — registration still went through.
Comparison: Date (September 2023), venue (Senate hearing), NBI-official source, and monkey/animal-photograph SIM-registration demonstration all attested. Body's "grinning" / "smiling" descriptor matches GMA's characterisation of the photo's expression (other Philippine outlets describe the photo as a "smiling monkey").
Decision: corroborated

## Claim 26: International-comparative evidence — "Mexico had repealed its mandatory-SIM-registration law after three years with no improvement in the prevention, investigation, or prosecution of crime; Canada had rejected comparable proposals; Pakistan's regime had spawned a black market in pre-registered SIMs"

Source: https://cmfr-phil.org/in-context/one-signature-away-mandatory-sim-registration-bill/ ; primary FMA Medium article unreachable this pass
Source content: CMFR-phil references the 2018 FMA briefing paper as "documenting mandatory SIM registration as flawed and ineffective, noting examples like Mexico's repeal and Canada's scrapped proposals due to implementation failures." The primary FMA source (Medium article and 2018 briefing paper) is the load-bearing attestation but was not reachable in this pass.
Comparison: The Mexico-repealed and Canada-rejected elements of the body claim are attested by an independent canonical source (CMFR) as recorded in FMA's own briefing paper. The Pakistan black-market specific is not attested in the sources reached this pass. The compound claim's Pakistan component remains unverifiable from sources reachable this pass; the Mexico and Canada components are verified.
Decision: uncorroborated (split: Mexico/Canada verified, Pakistan component unverified)
