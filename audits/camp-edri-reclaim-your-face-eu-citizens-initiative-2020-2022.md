---
entity_id: camp-edri-reclaim-your-face-eu-citizens-initiative-2020-2022
entity_hash: 882659dfc580bbd2f692618d874876ae37736983
audit_date: 2026-09-05
pass: 3
status: corrections-pending
claims_total: 28
claims_corroborated: 1
claims_primary_sourced: 19
claims_single_source: 2
claims_uncorroborated: 3
open_corrections: 3
sources_consulted:
  - https://reclaimyourface.eu/
  - https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
  - https://reclaimyourface.eu/why_eci/
  - https://reclaimyourface.eu/the-movement/
  - https://edri.org/our-work/reclaim-your-face-biometric-surveillance/
  - https://edri.org/our-work/reclaim-your-face-eci/
  - https://edri.org/our-work/reclaim-your-face-impact-in-2021/
  - https://edri.org/our-work/campaign-reclaim-your-face-calls-for-a-ban-on-biometric-mass-surveillance/
  - https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
  - https://edri.org/our-work/civil-society-statement-eu-protect-peoples-rights-in-the-ai-act-trilogue-negotiations/
  - https://algorithmwatch.org/en/reclaim-your-face-campaign/
  - https://algorithmwatch.org/en/eu-artificial-intelligence-act-for-fundamental-rights/
  - https://www.accessnow.org/press-release/reclaim-your-face/
  - https://bigbrotherwatch.org.uk/press-releases/65-parliamentarians-call-for-immediate-stop-to-live-facial-recognition-surveillance/
  - https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
  - https://www.europarl.europa.eu/factsheets/en/sheet/149/european-citizens-initiative
  - https://artificialintelligenceact.eu/article/5/
  - https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai
---

Connective type (campaign): claim surface is frontmatter edges + hard specifics per MISSION § Auditor § Type-shape awareness. Pass 3 re-audit after entity edits (2026-05-23 Claim-19 fix + strategies edge addition). Pass-2 corrections: 1 of 3 resolved (BBW/EDRi); 2 persist (Claims 18, 21 below); 1 new correction found (Claim 26).

## Claim 1: Frontmatter edges — participating_orgs (org-edri, org-algorithmwatch, org-access-now, org-panoptykon-foundation, org-la-quadrature-du-net, org-bits-of-freedom, org-hermes-center), events, strategies all resolve; the seven orgs are RYF coalition members/partners

Source: https://reclaimyourface.eu/the-movement/ (+ internal corpus cross-check)
Source tier: primary
Source content: Coalition orgs listed: "Access Now, ARTICLE19, Bits of Freedom, CCC, Defesa dos Direitos Digitais (D3), Digitalcourage, Digitale Gesellschaft CH, Digitale Gesellschaft DE, Državljan D, EDRi, Electronic Frontier Finland, epicenter.works, Hermes Center for Transparency and Digital Human Rights, Homo Digitalis, IT-Political Association of Denmark, IuRe, La Quadrature du Net, Liberties, Metamorphosis Foundation, Panoptykon Foundation, Privacy International, SHARE Foundation"; separately "In collaboration with our campaign partners:" including "AlgorithmWatch, AlgorithmWatch/CH".
Comparison: All 13 cross-referenced entity files exist in the corpus and name the correct organisations/events/strategies (verified by file read). Six of the seven participating_orgs appear on the campaign's own coalition roster; AlgorithmWatch appears as "campaign partner" rather than core coalition org — participation supported either way. Strategy edges resolve; strat-counter-narrative-framing back-references this campaign, strat-coalition-lobbying-of-binding-regional-regulation does not (asymmetry is not an error — adopter rosters are Analyst-owned).
Decision: primary-sourced

## Claim 2: EDRi as lead/coordinating organisation (lead_orgs; body "EDRi coordinated the principal pan-European grassroots civil-society mobilisation")

Source: https://reclaimyourface.eu/ and https://edri.org/our-work/reclaim-your-face-biometric-surveillance/
Source tier: primary
Source content: "ReclaimYourFace is a movement led by civil society organisations across Europe" (RYF home, identifying EDRi as coordinator); EDRi hub describes the coalition expanding "of which more than half are from outside the EDRi network", with EDRi as the convening hub.
Comparison: EDRi's coordinating role matches both campaign-side primary sources (not independent of each other, so not two-source corroboration).
Decision: primary-sourced

## Claim 3: "The campaign was launched in October 2020" (body § The coalition; start_date 2020-10; scalar:outcomes "October 2020: launch of the Reclaim Your Face coalition")

Source: https://edri.org/our-work/reclaim-your-face-impact-in-2021/ vs https://edri.org/our-work/reclaim-your-face-biometric-surveillance/ and https://edri.org/our-work/campaign-reclaim-your-face-calls-for-a-ban-on-biometric-mass-surveillance/
Source tier: primary
Source content: "In October 2020, 12 organisations came together to form the Reclaim Your Face coalition, aiming to ban biometric mass surveillance in Europe" (impact-2021 page); but the EDRi campaign hub now reads "The EDRi network and partners launched the first phase of the Reclaim Your Face campaign ... in November 2020", and EDRi's launch article is dated November 12, 2020.
Comparison: EDRi's own pages split the dating: coalition *formed* October 2020, campaign publicly *launched* November 2020 (the hub sentence pass 2 quoted for October has been dropped from the live hub — source drift). "Launched in October 2020" cannot be settled without a formation-vs-launch judgment call; canonical statements conflict on the verb. start_date 2020-10 and the outcomes scalar's "launch of the coalition" reading are consistent with the formation dating; the body's "campaign was launched" phrasing is the tension. Not a correction — no single correct replacement token.
Decision: uncorroborated

## Claim 4: Twelve founding civil-society organisations (body; scalar:outcomes)

Source: https://edri.org/our-work/reclaim-your-face-impact-in-2021/
Source tier: primary
Source content: "In October 2020, 12 organisations came together to form the Reclaim Your Face coalition"; also EDRi hub: "Having launched the campaign with 12 civil society groups"; launch article: "by 12 human rights groups from across the EDRi network".
Comparison: The 12-count matches three EDRi pages (same publisher, so single-primary rather than independent corroboration).
Decision: primary-sourced

## Claim 5: Founding 12-organisation roster composition (body § The coalition; scalar:outcomes — EDRi; AlgorithmWatch and AlgorithmWatch Switzerland; Access Now; ARTICLE 19; Bits of Freedom; Privacy International; Homo Digitalis; Hermes Center; Panoptykon Foundation; IT-Pol Denmark; Liberties; La Quadrature du Net)

Source: https://edri.org/our-work/campaign-reclaim-your-face-calls-for-a-ban-on-biometric-mass-surveillance/ and https://reclaimyourface.eu/the-movement/
Source tier: primary
Source content: EDRi's 12 November 2020 launch article names "SHARE Foundation, Hermes Center, Bits of Freedom, ARTICLE19, Homo Digitalis and EDRi" among the founding groups; the RYF movement page lists SHARE Foundation among coalition orgs and places AlgorithmWatch / AlgorithmWatch/CH under "campaign partners", not coalition orgs.
Comparison: SHARE Foundation is named by EDRi's own launch article among the founders but is absent from the entity's 12-org roster, which instead counts AlgorithmWatch twice (DE + CH) — and the campaign's own roster page classes AlgorithmWatch as a partner, not a coalition org. Canonical sources disagree on the exact 12-org composition; no source enumerates the entity's exact list. Persists from pass 2.
Decision: uncorroborated

## Claim 6: Coalition grew to over thirty organisations by end of ECI cycle

Source: https://edri.org/our-work/reclaim-your-face-biometric-surveillance/
Source tier: primary
Source content: "Having launched the campaign with 12 civil society groups, the coalition is now made up of over 30 organisations"
Comparison: Matches the body claim.
Decision: primary-sourced

## Claim 7: European Commission accepted the ECI for registration on 7 January 2021

Source: https://edri.org/our-work/reclaim-your-face-biometric-surveillance/ and https://edri.org/our-work/reclaim-your-face-eci/
Source tier: primary
Source content: "On 7 January 2021, the Commission accepted the ECI put forward by the Reclaim Your Face coalition"; "Successfully registered on 7 January 2021, our ECI proudly states..."
Comparison: Exact date match on two campaign-side (non-independent) primary pages.
Decision: primary-sourced

## Claim 8: Signature collection opened 17 February 2021 (body; edge event-edri-reclaim-your-face-eci-launch-2021-02-17)

Source: https://www.accessnow.org/press-release/reclaim-your-face/ and https://reclaimyourface.eu/why_eci/
Source tier: primary
Source content: "PUBLISHED: 17 February 2021 ... Today, February 17, the coalition is rallying community support to #ReclaimYourFace through the launch of a new European Citizens' Initiative"; "Our signature collection started on 17 February 2021."
Comparison: Date matches two independent canonical sources (Access Now and the campaign). The events edge points to the correctly-dated launch event.
Decision: corroborated

## Claim 9: Original deadline 16 February 2022, COVID-19 extension, window closed 1 August 2022

Source: https://reclaimyourface.eu/why_eci/
Source tier: primary
Source content: "It was originally intended to be open for 12 months, until 16 February 2022. However, due to the COVID-19 pandemic, the European Commission decided to extend our collection period until 1 August 2022."
Comparison: All three tokens (original deadline, COVID reason, extended close) match verbatim; the post-mortem confirms the 1 August end ("Today, 1st of August at 23:59, our European Citizens Initiative comes to an end").
Decision: primary-sourced

## Claim 10: Nearly 80,000 verified signatures, short of the one-million threshold and seven-member-state minimum

Source: https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/ and https://reclaimyourface.eu/why_eci/
Source tier: primary
Source content: "we gathered almost 80 thousand signatures without using any targeted social media advertisement"; "We have to gather 1 million signatures ... At least 7 EU countries must achieve the corresponding minimum number of signatures."
Comparison: Tally and both thresholds match. Minor: the source says "almost 80 thousand signatures" without the word "verified"; the body's "verified" qualifier is not contradicted but not explicitly sourced.
Decision: primary-sourced

## Claim 11: ECI basis is Article 11(4) TEU and Article 24 TFEU

Source: https://www.europarl.europa.eu/factsheets/en/sheet/149/european-citizens-initiative (via search snippet; en.wikipedia ECI article body does not render on fetch)
Source tier: primary
Source content: "The legal basis of the citizens' initiative is set out in Article 11, Paragraph 4 of the Treaty on European Union (TEU) and Article 24, paragraph 1 of the Treaty on the Functioning of the European Union (TFEU)."
Comparison: Both Treaty citations match the European Parliament fact sheet (EU institutional record).
Decision: primary-sourced

## Claim 12: EU AI Act proposed by the European Commission on 21 April 2021

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
Source tier: tiebreaker
Source content: "On 21 April 2021, the AI Act was officially proposed by the Commission."
Comparison: Day-precise date matches; Wikipedia-alone sufficient for official-action dates per source rule. The entity-cited digital-strategy.ec.europa.eu page no longer carries the proposal date (source drift — its earliest milestone is now the 1 August 2024 entry into force); the campaign post-mortem confirms month precision ("In April 2021, when the law was proposed").
Decision: single-source

## Claim 13: "the campaign's own framing is that the words 'ban' and 'remote biometric identification' entered the European Commission's 21 April 2021 AI Act proposal as a direct consequence of the Reclaim Your Face mobilisation" (body; scalar:sources[1].note makes the same attribution to the post-mortem)

Source: https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
Source tier: primary
Source content: "In April 2021, when the law was proposed, we managed to include in the draft a mention of a ban."
Comparison: The post-mortem claims credit for "a mention of a ban" but the fetched text does not carry the "remote biometric identification" wording-claim the body and sources[1].note attribute to it. Partial/paraphrastic match — the attribution as stated is not confirmable against the live source.
Decision: uncorroborated

## Claim 14: Slogan "Reclaim our public space. Ban biometric mass surveillance!"

Source: https://reclaimyourface.eu/
Source tier: primary
Source content: "Reclaim our public space. Ban biometric mass surveillance!"
Comparison: Verbatim match.
Decision: primary-sourced

## Claim 15: Working definition — "any monitoring, tracking, and otherwise processing of the biometric data of individuals or groups in an indiscriminate or arbitrarily-targeted manner"

Source: https://algorithmwatch.org/en/reclaim-your-face-campaign/
Source tier: primary
Source content: "any monitoring, tracking, and otherwise processing of the biometric data of individuals or groups in an indiscriminate or arbitrarily-targeted manner."
Comparison: Verbatim match on AlgorithmWatch's coalition page.
Decision: primary-sourced

## Claim 16: Deployment contexts (streets, parks, train stations, shops, sports venues) and "treats us all as walking barcodes"

Source: https://reclaimyourface.eu/
Source tier: primary
Source content: "Blanket capture of every person's biometric data in public spaces like streets, parks, train stations, shops or sports venues simply for trying to live our lives is biometric mass surveillance."; "It treats us all as walking barcodes."
Comparison: Both phrases match verbatim.
Decision: primary-sourced

## Claim 17: 30 November 2021 statement "An EU Artificial Intelligence Act for Fundamental Rights" signed by 115 organisations

Source: https://algorithmwatch.org/en/eu-artificial-intelligence-act-for-fundamental-rights/
Source tier: primary
Source content: "115 civil society organisations" signed the collective statement released on November 30, 2021.
Comparison: Date and signatory count match.
Decision: primary-sourced

## Claim 18: "remote biometric identification in publicly accessible spaces" "sat as the first of the seven prohibitions" (body § Travel into the EU AI Act; scalar:outcomes — "including 'remote biometric identification in publicly accessible spaces' as the first item")

Source: https://algorithmwatch.org/en/eu-artificial-intelligence-act-for-fundamental-rights/
Source tier: primary
Source content: Ordered prohibitions list per current fetch (2026-09-05): (1) "social scoring systems"; (2) "remote biometric identification in publicly accessible spaces (by all actors)"; (3) "emotion recognition systems"; (4) "discriminatory biometric categorisation"; (5) "AI physiognomy"; (6) "systems used to predict future criminal activity"; (7) "systems to profile and risk-assess in a migration context".
Comparison: The body and the outcomes scalar both claim remote biometric identification was listed FIRST; the source lists it SECOND (social scoring first). Single correct replacement in each location: "first" → "second" (or drop the ordinal). Fix locations: body § Travel into the EU AI Act and scalar:outcomes. Open since pass 1 (third consecutive pass).
Decision: correction

## Claim 19: The seven-prohibition list contents (social scoring, emotion recognition, discriminatory biometric categorisation, AI physiognomy, predictive-policing systems, migration-context profiling and risk-assessment)

Source: https://algorithmwatch.org/en/eu-artificial-intelligence-act-for-fundamental-rights/
Source tier: primary
Source content: The seven listed prohibitions (quoted in Claim 18) cover exactly these categories.
Comparison: The body's enumeration of the other six prohibitions matches the source list's contents.
Decision: primary-sourced

## Claim 20: 12 July 2023 trilogue-stage statement signed by 150 organisations, co-drafted with AlgorithmWatch, Access Now, Amnesty International, Bits of Freedom, ECNL, European Disability Forum, Fair Trials, Homo Digitalis, ICCL, Panoptykon Foundation, and PICUM

Source: https://edri.org/our-work/civil-society-statement-eu-protect-peoples-rights-in-the-ai-act-trilogue-negotiations/
Source tier: primary
Source content: "150 civil society organisations" signed the statement on July 12, 2023; drafted by EDRi, Access Now, AlgorithmWatch, Amnesty International, Bits of Freedom, ECNL, European Disability Forum, Fair Trials, Homo Digitalis, ICCL, Panoptykon Foundation, and PICUM.
Comparison: Date, count, and co-drafter roster all match the body's list.
Decision: primary-sourced

## Claim 21: 12 July 2023 statement "under the trilogue pillar of 'restriction of harmful surveillance by law enforcement and migration authorities including bans on remote biometric identification and predictive policing'" (body § Travel into the EU AI Act)

Source: https://edri.org/our-work/civil-society-statement-eu-protect-peoples-rights-in-the-ai-act-trilogue-negotiations/
Source tier: primary
Source content: Verbatim pillar heading per current fetch (2026-09-05): "Limit harmful and discriminatory surveillance by national security, law enforcement and migration authorities" — with explicit bans on "remote biometric identification, predictive policing systems, individual risk assessments and predictive analytic systems in migration contexts."
Comparison: The body wraps its pillar text in quote marks but the quoted phrase does not appear verbatim in the source: it substitutes "restriction" for "Limit", omits "national security" and "discriminatory", and splices the bans-language into the heading. Fix: replace the quoted string with the source's verbatim heading (or unquote and paraphrase). Fix location: body § Travel into the EU AI Act. Open since pass 1 (third consecutive pass).
Decision: correction

## Claim 22: AI Act endgame — trilogue political agreement 9 December 2023; Parliament adoption 13 March 2024 by 523 for, 46 against, 49 abstaining; Council approval 21 May 2024

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
Source tier: tiebreaker
Source content: "On 9 December 2023, after three days of 'marathon' talks, the EU Council and Parliament concluded an agreement"; passed 13 March 2024 with "523 for, 46 against, and 49 abstaining"; "approved by the EU Council on 21 May 2024".
Comparison: All three dates and the vote tally match; Wikipedia-alone sufficient for official-action dates.
Decision: single-source

## Claim 23: Final act retained partial prohibitions on remote biometric identification, emotion recognition (workplaces and education), AI physiognomy, social scoring, and discriminatory biometric categorisation, alongside law-enforcement carve-outs (body; scalar:outcomes)

Source: https://artificialintelligenceact.eu/article/5/
Source tier: primary
Source content: Article 5 prohibits "'real-time' remote biometric identification systems in publicly accessible spaces for the purposes of law enforcement" unless strictly necessary for enumerated exceptions (targeted victim search, imminent threat, serious-crime suspects); emotion recognition "in the areas of workplace and education institutions"; social scoring; "biometric categorisation systems that categorise individually natural persons based on their biometric data to deduce or infer their race, political opinions, trade union membership, religious or philosophical beliefs, sex life or sexual orientation"; predictive policing based solely on profiling.
Comparison: The body's "partial prohibition ... alongside law-enforcement, migration, and national-security carve-outs" characterisation matches the Act's prohibition-with-exceptions structure ("AI physiognomy" is the campaign's vocabulary for the 5(g)-class trait-inference ban).
Decision: primary-sourced

## Claim 24: #BanBS international call — 16 June 2021, launched with over 175 organisations across 55 countries (subsequently cited as 178), co-led by Access Now, EDRi, Amnesty International, Human Rights Watch, Internet Freedom Foundation (India), IDEC (Brazil); verbatim demands "stop their own biometric surveillance practices and adopt laws which prohibit others from doing it, too" and "the use of facial recognition and remote biometric technologies in publicly accessible spaces enables mass surveillance and discriminatory targeted surveillance" (body; scalar:outcomes; scalar:sources[5].note)

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source tier: primary
Source content: Published June 16, 2021; "launched in early June 2021 with over 175 organisations"; headline references 178 organisations across 55 countries; led by Access Now with EDRi, Amnesty International, Human Rights Watch, Internet Freedom Foundation (India), Instituto Brasileiro de Defesa do Consumidor (Brazil); both demand quotes appear verbatim.
Comparison: All counts, dates, co-leads, and both verbatim quotes match. (The body's regional-signatory enumeration — India, Brazil, US, Sub-Saharan Africa, East/Southeast Asia — is proportionate to the 55-country figure and the named co-leads, not separately itemised by the source.)
Decision: primary-sourced

## Claim 25: BBW 6 October 2023 joint statement — 65 parliamentarians (38 MPs, 27 Peers) and 31 rights and race-equality organisations, including Access Now, Human Rights Watch, Foxglove, JCWI, Liberty, Privacy International, Open Rights Group, Amnesty International, and Article 19 "alongside 22 other" organisations; demand quote in scalar:sources[9].note

Source: https://bigbrotherwatch.org.uk/press-releases/65-parliamentarians-call-for-immediate-stop-to-live-facial-recognition-surveillance/
Source tier: primary
Source content: Dated October 6, 2023; "65 parliamentarians total—38 MPs and 27 Peers; 31 rights and race equality organisations"; full 31-org list includes all nine organisations the body names; "We call on UK police and private companies to immediately stop using live facial recognition for public surveillance."; EDRi does not appear on the signatory list.
Comparison: All counts and the demand quote match; the nine named signatories all appear; 31 − 9 = 22 ("alongside 22 other" is now arithmetically right). The pass-2 correction (EDRi wrongly listed as signatory) is RESOLVED — EDRi has been removed from the body and sources note.
Decision: primary-sourced

## Claim 26: "The Access Now October 2020 press release announcing the launch corroborates the twelve-organisation founding partner roster" (body § The coalition; scalar:sources[4].note — "Access Now's October 2020 press release announcing the Reclaim Your Face coalition launch — secondary source corroborating the October 2020 coalition formation, the twelve-organisation founding partner roster")

Source: https://www.accessnow.org/press-release/reclaim-your-face/
Source tier: primary
Source content: "PUBLISHED: 17 February 2021 ... Today, February 17, the coalition is rallying community support to #ReclaimYourFace through the launch of a new European Citizens' Initiative." The release names only Access Now and EDRi; it does not enumerate a founding roster and does not announce the October 2020 coalition formation.
Comparison: The cited press release is dated 17 February 2021 (not October 2020), announces the ECI signature launch (not the coalition launch), and carries no twelve-organisation roster. Date token: "October 2020" → "17 February 2021"; but the sentence's corroboration claim (roster, coalition formation) also fails against the source, so the fix needs prose judgment beyond a single token replacement — Editor should flag to Researcher. Fix locations: body § The coalition and scalar:sources[4].note. New this pass (pass 2 used this source only for the 17 Feb 2021 date, where it is correct).
Decision: correction

## Claim 27: Coalition "contributed to strengthening our 62-organisation call for artificial intelligence red lines" (scalar:sources[2].note — "the campaign's role in strengthening a 62-organisation call for AI red lines")

Source: https://edri.org/our-work/reclaim-your-face-biometric-surveillance/
Source tier: primary
Source content: "Whilst this coalition is just beginning, it has already contributed to strengthening our 62-organisation call for artificial intelligence red lines."
Comparison: Matches the sources-note claim.
Decision: primary-sourced

## Claim 28: Campaign remains active/ongoing as an EDRi-coordinated vehicle into the AI Act implementation phase (end_date: ongoing; status: active; body and scalar:outcomes)

Source: https://reclaimyourface.eu/ and https://algorithmwatch.org/en/reclaim-your-face-campaign/
Source tier: primary
Source content: RYF home is live and current, noting EDRi's recognition as an AI policy leader (May 2024); AlgorithmWatch: "The campaign continues to advocate for EU legislation explicitly prohibiting biometric mass surveillance systems."
Comparison: The campaign site remains live and both sources describe continuing advocacy post-ECI; the most recent datable evidence is May 2024, which is consistent with (though does not day-precisely attest) activity "into the 2024–2026 implementation phase".
Decision: primary-sourced
