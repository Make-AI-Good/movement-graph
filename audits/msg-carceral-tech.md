---
entity_id: msg-carceral-tech
entity_hash: d7119c533036611abe2e79c27982e021adc6c02f
audit_date: 2026-09-05
pass: 1
status: corrections-pending
claims_total: 27
claims_corroborated: 13
claims_primary_sourced: 7
claims_single_source: 0
claims_uncorroborated: 5
open_corrections: 2
sources_consulted:
  - https://logicmag.io/care/community-defense-sarah-t-hamid-on-abolishing-carceral-technologies/
  - https://mediajustice.org/challengingecarceration/
  - https://stoplapdspying.org/data-driven-policing-abolition-requires-a-culture-of-resistance/
  - https://www.dukeupress.edu/captivating-technology
  - https://www.eff.org/about/staff/sarah-hamid
  - https://blogs.ubalt.edu/legaldatadesign/abolitionist-movements-the-carceral-tech-resistance-network/
  - https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
  - https://nfg.org/technologies-for-liberation-toward-abolitionist-futures/
  - https://archive.astraeafoundation.org/fundabolitiontech/
  - https://www.governing.com/security/Santa-Cruz-Calif-Becomes-First-to-Ban-Predictive-Policing.html
  - https://www.buzzfeednews.com/article/carolinehaskins1/los-angeles-police-department-dumping-predpol-predictive
  - https://thelensnola.org/2020/12/18/new-orleans-city-council-approves-ban-on-facial-recognition-predictive-policing-and-other-surveillance-tech/
  - https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
  - https://proceedings.mlr.press/v81/buolamwini18a.html
  - https://en.wikipedia.org/wiki/George_Floyd_protests
  - https://wraphome.org/2021/11/19/los-angeles-ca-automating-banishment-released-today/
  - https://mediajustice.org/resource/no-more-shackles-report/
  - https://www.prisonlegalnews.org/news/publications/no-more-shackles-why-we-must-end-use-electronic-monitors-people-parole-challenging-e-carceration/
---

Note on source availability this pass: www.carceral.tech (entity source 1) is offline — DNS ENOTFOUND on fetch; Wayback is blocked in this harness. read.dukeupress.edu 403s but www.dukeupress.edu fetches fine. astraeafoundation.org/FundAbolitionTech/glossary/ (entity source 6) 404s; the archived hub at archive.astraeafoundation.org/fundabolitiontech/ fetches but carries no glossary text.

## Claim 1: edge `propagated_by_orgs: org-mediajustice` — MediaJustice as primary in-corpus organizational carrier via Challenging E-Carceration / #NoDigitalPrisons

Source: https://mediajustice.org/challengingecarceration/
Source tier: primary
Source content: "The #ChallengingEcarceration project, part of the #NoDigitalPrisons campaign at MediaJustice, was launched in 2018"
Comparison: Edge resolves to existing entity file; MediaJustice's own campaign page confirms the campaign and its e-carceration framing; Prison Legal News and In These Times coverage independently confirm the campaign's existence and reports.
Decision: corroborated

## Claim 2: edges `related_messages` — msg-automating-banishment, msg-machine-bias, msg-no-tech-for-ice, msg-ban-biometric-mass-surveillance

Source: in-corpus entity files; anchor facts per Claims 16–17 and 26
Source tier: primary
Source content: all four target files exist in product/entities/messages/; anchor facts of the two load-bearing edges verified this pass (Automating Banishment = Stop LAPD Spying 2021 report, Claim 26; Machine Bias = ProPublica 2016 COMPAS investigation, Claim 16)
Comparison: Mechanical edge check — each reference resolves to the correct entity; the body's characterization of each relation is interpretive and out of remit beyond the anchor facts.
Decision: corroborated

## Claim 3: *Captivating Technology* — Duke University Press, 2019, anthology edited by Ruha Benjamin, introduced "carceral technoscience"

Source: https://www.dukeupress.edu/captivating-technology
Source tier: primary
Source content: "June 2019, edited by Ruha Benjamin"; "Moving from traditional sites of imprisonment to the arenas of everyday life being reshaped by carceral technoscience"
Comparison: Publisher's own catalog page confirms year, editor, publisher; the term "carceral technoscience" is in the book's subtitle and description. Independently confirmed by the Ethnic and Racial Studies review (tandfonline: "edited by Ruha Benjamin, Durham and London, Duke University Press, 2019").
Decision: corroborated

## Claim 4: technologies deployed "to classify and coerce specific populations" (attributed to the book's contributors/description)

Source: https://www.dukeupress.edu/captivating-technology
Source tier: primary
Source content: "examine how carceral technologies are being deployed to classify and coerce specific populations"
Comparison: Verbatim match in the publisher's description; also mirrored at BiblioVault and De Gruyter catalog entries.
Decision: corroborated

## Claim 5: Benjamin's introduction "calls for an abolitionist movement that... seeks 'an end to carcerality in all its forms'" (quoted phrase attributed to the introduction)

Source: no canonical source found for the quoted phrase
Source tier: none
Source content: exact-phrase web search for "an end to carcerality in all its forms" returns no result connected to Benjamin or *Captivating Technology*; the publisher description and searchable excerpts of the introduction do not carry it
Comparison: The book's abolitionist framing is well attested, but the phrase rendered in quote marks (in both origin scalar and body) cannot be located in any fetchable source; the print introduction is not accessible online, so error cannot be asserted either — too paraphrastic/unlocatable to compare.
Decision: uncorroborated

## Claim 6: CTRN co-founded in 2018 by organizer Sarah T. Hamid

Source: https://www.eff.org/about/staff/sarah-hamid
Source tier: primary
Source content: "In 2018, she co-founded the Carceral Tech Resistance Network, a knowledge-sharing network connecting grassroots efforts against the design, testing, and deployment of violent technologies."
Comparison: Hamid's own official bio (self-attested primary) states co-founding and year exactly as the entity does.
Decision: primary-sourced

## Claim 7: CTRN "grew to 76+ advocacy groups across the West Coast, Midwest, and Southwest"

Source: https://www.eff.org/about/staff/sarah-hamid
Source tier: primary
Source content: at its peak the network brought together "76+ advocacy groups across the Midwest, Southwest, and West Coast"
Comparison: Verbatim match on count and regions (order differs, content identical). Same self-attested bio as Claim 6; no independent second source found. Bio also notes the network is "Now sunsetting" — not yet reflected in the entity, but the entity's growth claim is past-tense and remains accurate.
Decision: primary-sourced

## Claim 8: CTRN "formally constituted in March 2020"

Source: no canonical source found
Source tier: none
Source content: the entity's cited source for CTRN facts (www.carceral.tech) is offline (DNS ENOTFOUND); the UBalt Legal Data & Design Clinic blog post was fetched and probed — "The document does not include verbatim text specifying when CTRN was formally established or launched"; a search-engine synthesis asserted "March 30th, 2020" but no fetchable page carrying the date could be identified
Comparison: The March 2020 date cannot be traced to any canonical source this pass; not contradicted, but unverifiable with the primary source offline.
Decision: uncorroborated

## Claim 9: Hamid quote "technological innovation, and the reformism that animates it, is a carceral tactic" — Logic Magazine issue "Care", 31 August 2020

Source: https://logicmag.io/care/community-defense-sarah-t-hamid-on-abolishing-carceral-technologies/
Source tier: primary
Source content: "Technological innovation, and the reformism that animates it, is a carceral tactic." — published August 31, 2020, Logic(s) Issue 11, "Care"
Comparison: The cited interview itself carries the quote verbatim, and the issue name and date match exactly.
Decision: primary-sourced

## Claim 10: CTRN composition "primarily femme, Black, immigrant, and POC organizers"

Source: https://logicmag.io/care/community-defense-sarah-t-hamid-on-abolishing-carceral-technologies/
Source tier: primary
Source content: "Our group is made up primarily of femme, Black, immigrant, POC organizers."
Comparison: Verbatim match in the cited interview.
Decision: primary-sourced

## Claim 11: CTRN "built from two recognized needs" — including that carceral technologies rolled out locally "travel" to other contexts

Source: https://logicmag.io/care/community-defense-sarah-t-hamid-on-abolishing-carceral-technologies/
Source tier: primary
Source content: CTRN "was created out of two primary needs"; "These technologies, often rolled out at a local scale, have afterlives—they travel to other contexts."
Comparison: The two-needs structure and the "travel" quote both match the cited interview. The body's illustrative gloss "what is tested against a Skid Row population in Los Angeles appears in a different city under a different program name" is NOT in the interview (targeted probe: "Skid Row — absent"); it is interpretation consistent with the Automating Banishment record (Claim 26) rather than a sourced specific.
Decision: primary-sourced

## Claim 12: MediaJustice Challenging E-Carceration / #NoDigitalPrisons project launched 2018

Source: https://mediajustice.org/challengingecarceration/
Source tier: primary
Source content: "The #ChallengingEcarceration project, part of the #NoDigitalPrisons campaign at MediaJustice, was launched in 2018"; "In March 2018, led by MediaJustice Fellow James Kilgore, the #ChallengingEcarceration project released a set of guidelines"
Comparison: Campaign's own page states 2018 launch; the 2018 parole report (mediajustice.org/resource/no-more-shackles-report/, dated 2018) and Prison Legal News coverage independently confirm the project active from 2018.
Decision: corroborated

## Claim 13: electronic monitoring use doubled over the decade (ending ~2018) while incarceration declined

Source: https://mediajustice.org/challengingecarceration/
Source tier: primary
Source content: "Use of electronic monitoring has doubled in the past decade, and the net is widening"; "The prison rate is dropping but the use of electronic monitoring is growing."
Comparison: The cited campaign page carries the doubling-while-declining finding as the entity states it; the body's "decade ending in 2018" endpoint is the entity's reading of a claim made on the 2018-launched campaign page (source itself says only "the past decade").
Decision: primary-sourced

## Claim 14: "No More Shackles" report series arguing electronic monitoring is incarceration in the community / digital prison architecture, not an alternative

Source: https://mediajustice.org/resource/no-more-shackles-report/
Source tier: primary
Source content: "No More Shackles: Why We Must End the Use of Electronic Monitors for People on Parole (2018)" and "No More Shackles: Ten Arguments Against Pretrial Electronic Monitoring (2019)" — MediaJustice resource pages; Prison Legal News: "No More Shackles: Why We Must End the Use of Electronic Monitors for People On Parole, Challenging E-Carceration"
Comparison: The report series exists under the stated title with the stated abolitionist argument; confirmed by MediaJustice's own pages plus Prison Legal News and In These Times coverage. (The current campaign landing page no longer names the series — the resource subpages do.)
Decision: corroborated

## Claim 15: Challenging E-Carceration directed by James Kilgore as a MediaJustice Fellow

Source: https://mediajustice.org/challengingecarceration/
Source tier: primary
Source content: "In March 2018, led by MediaJustice Fellow James Kilgore, the #ChallengingEcarceration project released a set of guidelines"; search-confirmed Prison Legal News / MediaJustice press: "James Kilgore, MediaJustice Fellow and lead author of the report"
Comparison: Role and title match across MediaJustice's own page and independent coverage.
Decision: corroborated

## Claim 16: COMPAS = "Correctional Offender Management Profiling for Alternative Sanctions"; ProPublica Machine Bias investigation published 2016

Source: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
Source tier: mainstream
Source content: "Correctional Offender Management Profiling for Alternative Sanctions"; publication date "May 23, 2016"
Comparison: Acronym expansion and year match the cited investigation exactly; both widely mirrored.
Decision: corroborated

## Claim 17: body: ProPublica "documented that COMPAS flagged Black defendants as high-risk at nearly twice the rate of White defendants"

Source: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
Source tier: mainstream
Source content: "The formula was particularly likely to falsely flag black defendants as future criminals, wrongly labeling them this way at almost twice the rate as white defendants."
Comparison: The "nearly twice" figure in the source is specifically the FALSE-flag (false-positive) rate among defendants who did not reoffend (45% vs 23%), not the overall high-risk flag rate; the body drops "falsely," changing the statistic's meaning. Single-token fix in body §Algorithmic risk assessment: "flagged Black defendants as high-risk" → "falsely flagged Black defendants as high-risk" (or "wrongly labeled").
Decision: correction

## Claim 18: Algorithmic Justice League audit work established systematically higher error rates on darker-skinned women in commercial face recognition

Source: https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
Source tier: primary
Source content: Gender Shades (Buolamwini & Gebru, PMLR v81, 2018) — "darker-skinned females were the most misclassified group with error rates of up to 34.7%," versus a maximum 0.8% error rate for lighter-skinned males; all three tested classifiers had highest error rates for darker-skinned females
Comparison: Peer-reviewed paper (proceedings.mlr.press — primary tier) plus MIT News coverage confirm the claim as stated.
Decision: corroborated

## Claim 19: George Floyd uprisings May–June 2020 pushed abolition discourse into mainstream debate

Source: https://en.wikipedia.org/wiki/George_Floyd_protests
Source tier: tiebreaker
Source content: protests "began in Minneapolis in the United States on May 26, 2020," following Floyd's death May 25, 2020, growing into nationwide protests
Comparison: Date of public event — Wikipedia-alone-sufficient class per the source rule; the May–June 2020 timing matches. The "pushed abolition discourse into mainstream" characterization is interpretive framing, audited only for the date anchor; the mainstreaming of "defund the police" is additionally reflected in the city-action record (Claim 20).
Decision: corroborated

## Claim 20: several U.S. cities cancelled or paused predictive policing and face recognition contracts in 2020–2021

Source: https://www.governing.com/security/Santa-Cruz-Calif-Becomes-First-to-Ban-Predictive-Policing.html
Source tier: mainstream
Source content: Santa Cruz "became the first city in the U.S. to approve a ban" on predictive policing (unanimous council vote, June 23, 2020); BuzzFeed News: LAPD memo dated April 15 [2020] — the department "would stop using the software [PredPol], effective immediately"; The Lens: New Orleans council "places an outright ban on... facial recognition software and predictive policing" (Dec 2020); Minneapolis (Feb 2021) and Portland (Sept 2020) face recognition bans
Comparison: Multiple independent mainstream sources confirm the pattern and window exactly as stated.
Decision: corroborated

## Claim 21: Astraea Lesbian Foundation for Justice + Research Action Design (RAD) produced *Technologies for Liberation: Toward Abolitionist Futures* as a funder-facing report

Source: https://nfg.org/technologies-for-liberation-toward-abolitionist-futures/
Source tier: mainstream
Source content: the report "was produced by the Astraea Lesbian Foundation For Justice in collaboration with Research Action Design (RAD)"; created "as a resource for funders to understand what is at stake and what opportunities exist to support critical organizing"
Comparison: Title, producers, and funder-facing purpose confirmed by Neighborhood Funders Group, Community Resource Hub, Allied Media Projects, and RAD's own project page.
Decision: corroborated

## Claim 22: scalar:sources[5].note — the report defines carceral technologies as "tools designed to capture, confine, control, punish, and exploit people"

Source: no canonical source found for the quoted phrase
Source tier: none
Source content: the cited glossary URL (astraeafoundation.org/FundAbolitionTech/glossary/) returns 404; the archived report hub (archive.astraeafoundation.org/fundabolitiontech/) fetches but carries no glossary text; exact-phrase search does not surface the definition; closest fetchable paraphrase (nfg.org): technology used "to control, police, surveil, and limit the flow of money and power to QT2SBIPOC communities"
Comparison: The quoted definition cannot be verified with the glossary page gone and Wayback blocked; not contradicted — the fix location if later corrected is scalar:sources[5].note.
Decision: uncorroborated

## Claim 23: the Astraea/RAD report maps the ecosystem connecting CTRN, MediaJustice, Stop LAPD Spying for funders

Source: https://archive.astraeafoundation.org/fundabolitiontech/
Source tier: mainstream
Source content: "MediaJustice and Stop LAPD Spying Coalition appear as partner organization logos/links in the footer section" of the archived report hub; CTRN not found on any fetchable report page
Comparison: Partial confirmation only — two of the three named organizations appear as partners on the archived hub; CTRN's inclusion is plausible (Hamid milieu) but unverifiable with the full report/glossary offline.
Decision: uncorroborated

## Claim 24: scalar:sources[0].note — carceral.tech home page carried CTRN's working scope list (CCTV, face printing, DNA and biometric databases, acoustic gunshot detection, drones, electronic monitoring, AI and risk profiling algorithms)

Source: no canonical source found (cited page offline)
Source tier: none
Source content: www.carceral.tech fails DNS resolution; a web search reproduced the exact list — "CCTV, face printing, DNA and biometric databases, acoustic gunshot detection, drones, electronic monitoring, AI and risk profiling algorithms" — but as search-engine synthesis of ambiguous provenance, not a quotable page
Comparison: The list very likely comes from the (indexed but dead) carceral.tech site, and nothing contradicts it, but no attributable canonical source is fetchable; with the site offline and Wayback blocked this cannot be pinned. Fix location if later revised: scalar:sources[0].note.
Decision: uncorroborated

## Claim 25: scalar:sources[4].note — the Stop LAPD Spying "Data-Driven Policing" page as "primary source for... the knowledge-sharing rationale that surveillance technologies piloted locally 'travel' to other contexts requiring coordinated community resistance"

Source: https://stoplapdspying.org/data-driven-policing-abolition-requires-a-culture-of-resistance/
Source tier: primary
Source content: two targeted probes of the fetched page — "'travel' — No", "'pilot' — No"; the only spread-related passage is "Many of these technologies and methods were developed for the US's imperial wars abroad" (military-to-police, not local-piloting-travels)
Comparison: Misattribution — the 'travel' rationale is not on the cited page; it lives verbatim in the Logic Magazine interview ("they travel to other contexts", Claim 11). Fix location: scalar:sources[4].note — remove or reattribute the travel clause to the logicmag.io interview (prose-judgment fix; the note's other attributions are sound per Claim 27).
Decision: correction

## Claim 26: *Automating Banishment* — Stop LAPD Spying Coalition 2021 report naming data-driven policing as land dispossession

Source: https://wraphome.org/2021/11/19/los-angeles-ca-automating-banishment-released-today/
Source tier: primary
Source content: "AUTOMATING BANISHMENT: The Surveillance and Policing of Looted Land" released November 19, 2021 (WRAP); Stop LAPD Spying's own report hub (stoplapdspying.org/automating-banishment-the-surveillance-and-policing-of-looted-land/): the report shows "how police terror and surveillance work in tandem with real estate development to banish Black and brown people and secure white wealth," examining "Skid Row and South Central... Operation LASER, PredPol"
Comparison: Year, publisher, and land-dispossession framing match; confirmed by the coalition's own pages plus WRAP and Black Agenda Report coverage.
Decision: corroborated

## Claim 27: Stop LAPD Spying premise that data-driven policing cannot be fixed through audits/oversight and must be dismantled

Source: https://stoplapdspying.org/data-driven-policing-abolition-requires-a-culture-of-resistance/
Source tier: primary
Source content: "Decades of transparency legislation, civilian oversight, and self-auditing have done nothing to reduce the power and violence of the carceral state."; oversight proposals described as "dead-ends"
Comparison: The cited page carries the dismantle-not-reform premise as the entity and sources note state it (this half of sources[4].note is sound; only the travel clause misattributes, Claim 25).
Decision: primary-sourced
