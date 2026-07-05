---
entity_id: camp-no-tech-for-apartheid-nimbus-workers-2021-ongoing
entity_hash: 959b551bbe68ebd1ac40faad15a9f3081314e3c8
audit_date: 2026-07-05
pass: 1
status: corrections-pending
claims_total: 29
claims_corroborated: 14
claims_primary_sourced: 10
claims_single_source: 1
claims_uncorroborated: 3
open_corrections: 1
sources_consulted:
  - https://www.fightforthefuture.org/news/2021-10-13-40-organizations-join-500-tech-workers-in-demanding-amazon-and-google-end-all-ties-with-israeli-apartheid/
  - https://en.wikipedia.org/wiki/No_Tech_for_Apartheid
  - https://en.wikipedia.org/wiki/Project_Nimbus
  - https://www.democracynow.org/2024/4/17/no_tech_for_apartheid_google_israel
  - https://www.alphabetworkersunion.org/press/updated-awu-cwa-statement-following-termination-of-workers-after-project-nimbus-protest-at-google-cloud-office
  - https://medium.com/@notechforapartheid/statement-from-google-workers-organizing-with-the-no-tech-for-apartheid-campaign-on-googles-17ee10b088f0
  - https://www.aljazeera.com/news/2024/4/23/what-is-project-nimbus-and-why-are-google-workers-protesting-israel-deal
  - https://www.notechforapartheid.com/
  - https://www.commondreams.org/news/2021/10/13/no-tech-apartheid-40-groups-demand-amazon-and-google-ditch-israeli-military
  - https://mediajustice.org/news/no-tech-for-israeli-apartheid-protesters-disrupt-aws-conference-over-military-contract/
  - https://www.mpowerchange.org/campaignupdates/amazon-labor-union-joins-amazon-tech-workers-to-protest-amazons-cloud-contracts-with-israel-at-companys-annual-aws-summit
  - https://laborforpalestine.net/2021/10/12/we-are-google-and-amazon-workers-we-condemn-project-nimbus-the-guardian/
  - https://www.leftvoice.org/workers-at-amazon-and-google-condemn-project-nimbus-contract-with-israeli-military/
  - https://www.engadget.com/more-than-1000-students-pledge-not-to-work-at-google-and-amazon-due-to-project-nimbus-042439081.html
  - https://www.cnbc.com/2018/04/05/google-employees-protest-pentagon-partnership-to-ceo-sundar-pichai.html
  - https://www.armscontrol.org/act/2018-07/news/google-renounces-ai-work-weapons
  - https://time.com/6964364/exclusive-no-tech-for-apartheid-google-workers-protest-project-nimbus-1-2-billion-contract-with-israel/
  - https://www.business-standard.com/world-news/israel-project-nimbus-google-amazon-winking-mechanism-data-leak-125103000892_1.html
---

Connective type (campaign): claims audited are the edges (`lead_orgs`, `participating_orgs`, cross-references) and hard specifics (dates, counts, locations, quoted attributions, outcomes). Interpretive body prose ("outer limit of tech-worker conscience organizing", "most fully realised execution", significance framing) is not a claim and receives no decision. All 12 edge/cross-reference targets resolve to existing entity files. Harness notes: laborforpalestine.net direct fetch fails (expired TLS certificate; letter text reached via search-snippet quotes and the leftvoice.org mirror); theguardian.com, time.com, and newarab.com 403 on direct fetch.

## Claim 1: "start_date: 2021-10" + "Launched in October 2021 through a founding open letter in *The Guardian*" (12 October 2021)

Source: https://en.wikipedia.org/wiki/No_Tech_for_Apartheid + https://www.commondreams.org/news/2021/10/13/no-tech-apartheid-40-groups-demand-amazon-and-google-ditch-israeli-military
Source tier: mainstream
Source content: "Workers at Google and Amazon published an open letter in *The Guardian* on October 12, 2021, condemning Project Nimbus. ... Starting with an anonymous letter written by Google and Amazon workers condemning the deal, the group eventually became a dedicated campaign." (Wikipedia); Common Dreams launch coverage dated 13 October 2021 follows the 12 October letter.
Comparison: Date of a public event; letter date, venue, and title match across Wikipedia, the laborforpalestine.net republication (dated 2021/10/12), and mainstream launch coverage.
Decision: corroborated

## Claim 2: "scalar:goals" + body — Project Nimbus is "the $1.2 billion April 2021 contract under which Google Cloud and Amazon Web Services provide cloud-computing, artificial-intelligence, and machine-learning infrastructure to the Israeli government and military"

Source: https://en.wikipedia.org/wiki/Project_Nimbus + https://www.aljazeera.com/news/2024/4/23/what-is-project-nimbus-and-why-are-google-workers-protesting-israel-deal
Source tier: mainstream
Source content: "A $1.2 billion agreement announced in April 2021 by the Israeli Finance Ministry. The contract was awarded to Google Cloud Platform and Amazon Web Services to provide the Israeli government with cloud computing infrastructure, AI, and related services." (Wikipedia); "Project Nimbus is a $1.2 billion agreement signed in 2021 between Google and Amazon to provide cloud computing, artificial intelligence, and technology services to the Israeli government and military." (Al Jazeera)
Comparison: Value, date, vendors, and recipient all match; goals-scalar and body renderings are consistent with both sources.
Decision: corroborated

## Claim 3: edges `lead_orgs: org-alphabet-workers-union, org-tech-workers-coalition` (+ body: AWU and TWC "are the campaign's principal institutional anchors")

Source: https://www.notechforapartheid.com/ + https://en.wikipedia.org/wiki/No_Tech_for_Apartheid + https://www.engadget.com/more-than-1000-students-pledge-not-to-work-at-google-and-amazon-due-to-project-nimbus-042439081.html
Source tier: none
Source content: "a worker-led campaign of Google and Amazon workers organizing against the companies'" [Project Nimbus contract] (campaign homepage — no organizations named as leads); "The campaign originated from MPower Change and Jewish Voice for Peace" (Wikipedia); June 2024 pledge coverage describes the movement as "led by ... No Tech for Apartheid, MPower Change, and Jewish Voice for Peace" (search-surfaced pledge coverage).
Comparison: No canonical source names the Alphabet Workers Union or the Tech Workers Coalition as lead organizations of this campaign; the sources consistently name MPower Change and Jewish Voice for Peace as the convening organizations alongside the workers themselves. AWU is documented as a supporting union (its own statements condemning the firings — Claim 21) and TWC hosts a call-to-action page, but "lead" is not supported and the sources point elsewhere. Whether the corpus should re-point `lead_orgs` (MPower Change / JVP entities) is a prose/graph judgment beyond a single-token replacement, so this is recorded as reaching the audit's limits rather than as a correction.
Decision: uncorroborated

## Claim 4: edge `participating_orgs: org-mediajustice` (+ body: "MediaJustice as founding signatory")

Source: https://www.fightforthefuture.org/news/2021-10-13-40-organizations-join-500-tech-workers-in-demanding-amazon-and-google-end-all-ties-with-israeli-apartheid/ + https://mediajustice.org/news/no-tech-for-israeli-apartheid-protesters-disrupt-aws-conference-over-military-contract/
Source tier: primary
Source content: FFTF founding release names MediaJustice among the coalition organizations; MediaJustice's own site carries campaign press coverage naming "MediaJustice" among the organizations that "have come together to form the #NoTechForApartheid campaign".
Comparison: Founding-coalition membership confirmed by the coalition's launch release and by MediaJustice's own site — two independent sources, one the entity's own.
Decision: corroborated

## Claim 5: edge `participating_orgs: org-mijente` (+ body: "Mijente as the lineage originator" within the coalition)

Source: https://mediajustice.org/news/no-tech-for-israeli-apartheid-protesters-disrupt-aws-conference-over-military-contract/
Source tier: primary
Source content: "Activists with the New York Communities for Change (NYCC), Make the Road NY, MediaJustice, MPower Change, Action Center on Race and the Economy (ACRE), and the Immigrant Defense Project (IDP) have come together to form the #NoTechForApartheid campaign, along with Mijente's #NoTechforICE campaign".
Comparison: The campaign's own press release (mirrored on participant sites) groups Mijente's #NoTechforICE campaign within the #NoTechForApartheid formation — supporting participation, though the phrasing is alliance-shaped rather than listing Mijente as a member org. Mijente does not appear in the October 2021 founding-signatory lists (FFTF, Common Dreams).
Decision: primary-sourced

## Claim 6: letter "signed internally by more than 90 Google and 300 Amazon workers"; "Anonymity, explicitly acknowledged in the letter" (fear of retaliation)

Source: https://www.timesofisrael.com/anonymous-google-amazon-workers-decry-deal-with-israel/ + https://www.middleeasteye.net/news/amazon-google-employees-call-for-termination-of-israel-military-contracts (search-verified) + https://laborforpalestine.net/2021/10/12/we-are-google-and-amazon-workers-we-condemn-project-nimbus-the-guardian/
Source tier: mainstream
Source content: "More than 90 workers at Google and more than 300 at Amazon signed the letter internally. The workers are anonymous because they fear retaliation." (consistent across Times of Israel, Middle East Eye, Al Jazeera, and the letter republication, per search-snippet quotes)
Comparison: Signatory split and anonymity rationale match multiple independent mainstream accounts and the letter text itself. Note: the entity's sources[0].note also says "more than 500 signatories" — the 500 figure is the coalition's aggregate framing (FFTF release headline: "500 tech workers"), not a number in the letter; the body itself carries only the 90/300 split, which is correct.
Decision: corroborated

## Claim 7: letter quote — the contract would "make the systematic discrimination and displacement carried out by the Israeli military and government even crueler and deadlier for Palestinians"

Source: https://laborforpalestine.net/2021/10/12/we-are-google-and-amazon-workers-we-condemn-project-nimbus-the-guardian/ (letter text, search-snippet verified; direct fetch blocked by expired TLS certificate)
Source tier: primary
Source content: "The technology our companies have contracted to build will make the systematic discrimination and displacement carried out by the Israeli military and government even crueler and deadlier for Palestinians."
Comparison: Body quote matches the letter text verbatim for the quoted span.
Decision: primary-sourced

## Claim 8: letter demand quoted as — "called on Google and Amazon to refuse the contract and 'all contracts that will harm our users'"

Source: https://www.leftvoice.org/workers-at-amazon-and-google-condemn-project-nimbus-contract-with-israeli-military/ + https://laborforpalestine.net/2021/10/12/we-are-google-and-amazon-workers-we-condemn-project-nimbus-the-guardian/ (letter text, search-snippet verified)
Source tier: primary
Source content: "We condemn Amazon and Google's decision to sign the Project Nimbus contract with the Israeli military and government, and ask them to reject this contract and future contracts that will harm our users."
Comparison: The body places "all contracts that will harm our users" inside quotation marks, but the letter reads "future contracts that will harm our users" — a one-token misquote ("all" → "future") of a direct quotation. Single correct replacement: the quoted string should read "future contracts that will harm our users" (or be unquoted as paraphrase). The same slip appears unquoted in scalar:sources[0].note ("refuse the contract and all contracts that harm users") — fix both the body quotation and, for consistency, the note paraphrase.
Decision: correction

## Claim 9: letter "placed the Nimbus campaign in the lineage of prior Google tech-worker actions against the Department of Defense (Project Maven), ICE, and state and local police departments"

Source: https://laborforpalestine.net/2021/10/12/we-are-google-and-amazon-workers-we-condemn-project-nimbus-the-guardian/ (letter text, search-snippet verified)
Source tier: primary
Source content: "Google and Amazon have aggressively pursued contracts with the US Department of Defense, Immigration and Customs Enforcement (ICE), and state and local police departments" — described in the letter as "part of a disturbing pattern of militarization, lack of transparency and avoidance of oversight."
Comparison: The letter does reference DoD, ICE, and state/local police contracts; the body's gloss that this places the campaign in that lineage matches the letter's framing.
Decision: primary-sourced

## Claim 10: "One day later, on 13 October 2021, a coalition of more than forty civil-society organisations ... launched the No Tech for Apartheid campaign publicly"

Source: https://www.fightforthefuture.org/news/2021-10-13-40-organizations-join-500-tech-workers-in-demanding-amazon-and-google-end-all-ties-with-israeli-apartheid/ + https://www.commondreams.org/news/2021/10/13/no-tech-apartheid-40-groups-demand-amazon-and-google-ditch-israeli-military
Source tier: primary
Source content: "Over 40 grassroots organizations joined the campaign" and "the No Tech For Apartheid campaign will amplify the efforts of people of conscience across the world to disrupt profiteering from apartheid" (FFTF release, 13 October 2021); Common Dreams same-day coverage: "40+ groups".
Comparison: Date, organization count, and campaign naming all match the coalition's own launch release and independent same-day coverage.
Decision: corroborated

## Claim 11: named coalition organisations — "Jewish Voice for Peace, MPower Change, the Adalah Justice Project, Fight for the Future, the BDS Movement, the Center for Constitutional Rights, Data for Black Lives, and MediaJustice"

Source: https://www.fightforthefuture.org/news/2021-10-13-40-organizations-join-500-tech-workers-in-demanding-amazon-and-google-end-all-ties-with-israeli-apartheid/ + https://www.commondreams.org/news/2021/10/13/no-tech-apartheid-40-groups-demand-amazon-and-google-ditch-israeli-military
Source tier: primary
Source content: FFTF release names Jewish Voice for Peace, MPower Change, Adalah Justice Project, Fight for the Future, BDS Movement, and MediaJustice; Common Dreams launch coverage additionally names "Center for Constitutional Rights (CCR)" and "Data for Black Lives" among the coalition.
Comparison: All eight named organisations confirmed as coalition members across the two launch documents. Note for scalar:sources[1].note: it attributes the full list including Center for Constitutional Rights and Data for Black Lives to the FFTF release, but that release does not name those two (confirmed by two targeted reads); they are attested in Common Dreams' same-day launch coverage. The world-facing claim is correct; the note's source attribution is imprecise.
Decision: corroborated

## Claim 12: "The campaign's name directly echoed Mijente's 2018 No Tech for ICE campaign" / drew on its structural template

Source: https://en.wikipedia.org/wiki/No_Tech_for_Apartheid + https://mediajustice.org/news/no-tech-for-israeli-apartheid-protesters-disrupt-aws-conference-over-military-contract/
Source tier: primary
Source content: Workers "created an external campaign to put pressure on their employers, following the model of Mijente's 'No Tech for ICE' campaign" (Wikipedia); the campaign's own press release ties the formation to "Mijente's #NoTechforICE campaign which focused on AWS contracts powering ICE's surveillance, terrorizing, and deportation of migrants in the United States".
Comparison: The lineage/template claim is stated by both the campaign's own materials and Wikipedia; edge target camp-mijente-no-tech-for-ice-2018-ongoing resolves.
Decision: corroborated

## Claim 13: "scalar:status active / end_date ongoing" + sources[2].note homepage self-description — "a worker-led campaign of Google and Amazon workers organising against the companies' Project Nimbus cloud-computing contract with the Israeli government and military"; campaign continues operating

Source: https://www.notechforapartheid.com/
Source tier: primary
Source content: The homepage describes the campaign as "a worker-led campaign of Google and Amazon workers organizing against the companies'" $1B "Project Nimbus cloud computing contract with the Israeli government and military"; live social-media presence, press contact, and worker call-to-action link present.
Comparison: Self-description matches the note's quotation (trivial variance: homepage currently says "$1B"); operational status confirmed by the live page.
Decision: primary-sourced

## Claim 14: "In March 2024, Google Cloud engineer Eddie Hatfield was fired after interrupting Google Israel managing director Barak Regev at the Mind the Tech conference in New York with the line 'I refuse to build technology that powers genocide'"

Source: https://www.aljazeera.com/news/2024/4/23/what-is-project-nimbus-and-why-are-google-workers-protesting-israel-deal + https://en.wikipedia.org/wiki/No_Tech_for_Apartheid
Source tier: mainstream
Source content: "On March 4, 2024, at the Mind the Tech conference in New York, Google Cloud software engineer Eddie Hatfield interrupted Google Israel's managing director Barak Regev, declaring: 'I am a Google Cloud software engineer, and I refuse to build technology that powers genocide, apartheid, or surveillance!' He was fired days later." (Al Jazeera); Wikipedia records a Google Cloud engineer fired in March 2024 after shouting at a company event.
Comparison: Date, names, conference, city, and firing all match. The body's quotation is a verbatim prefix of the fuller line ("...genocide, apartheid, or surveillance!") — truncated but not altered.
Decision: corroborated

## Claim 15: "On 16 April 2024, workers ... staged simultaneous sit-ins at Google's New York and Sunnyvale headquarters — including a ten-hour occupation of Google Cloud CEO Thomas Kurian's office — alongside outdoor protests at the Seattle and San Francisco offices. Nine workers were arrested for trespass"

Source: https://www.democracynow.org/2024/4/17/no_tech_for_apartheid_google_israel + https://en.wikipedia.org/wiki/No_Tech_for_Apartheid
Source tier: mainstream
Source content: "Sit-ins occurred at Google's New York office (10th floor commons) and Google Cloud CEO's office in Sunnyvale, California. Outdoor protests took place in New York, Sunnyvale, San Francisco, and Seattle. ... Workers occupied Thomas Kurian's office for over 10 hours before being forcibly removed by police. ... At least nine Google employees were arrested." (Democracy Now!); "Nine employees were charged with trespassing" at "New York and Sunnyvale headquarters" (Wikipedia).
Comparison: Date (AWU statement names April 16, 2024), locations, occupation length, and arrest count all match across sources.
Decision: corroborated

## Claim 16: Khatami quote — Google executives had "chosen to arrest workers for speaking out against the use of our technology to power the first AI-powered genocide" (framed to Democracy Now!; Khatami a Google software engineer)

Source: https://www.democracynow.org/2024/4/17/no_tech_for_apartheid_google_israel
Source tier: primary
Source content: "Google execs basically chose to arrest workers for speaking out against the use of our technology to power the first AI-powered genocide." — Mohammad Khatami, identified as a "Google software engineer, arrested in New York".
Comparison: The transcript is the primary record of the utterance; body quote and speaker identification match verbatim.
Decision: primary-sourced

## Claim 17: Khatami — "a Google software engineer who had joined in August 2022"

Source: https://time.com/6964364/exclusive-no-tech-for-apartheid-google-workers-protest-project-nimbus-1-2-billion-contract-with-israel/ (search-snippet verified; direct fetch 403)
Source tier: mainstream
Source content: Search-surfaced reporting on Khatami states "he started working at Google in August 2022" — "the same year that he started at Google" as he began organizing (Time exclusive / Khatami's New Arab op-ed, both 403 on direct fetch).
Comparison: The August 2022 start date is attested in one mainstream profile reachable only via search snippets this session; the Democracy Now! transcript (the entity's cited source for this passage) does not carry it.
Decision: single-source

## Claim 18: "Khatami's account of being 'called a supporter of terrorism' in internal channels"

Source: https://www.democracynow.org/2024/4/17/no_tech_for_apartheid_google_israel
Source tier: primary
Source content: Khatami reported being "called a supporter of terrorism" by co-workers, HR, and company personnel for speaking out against Project Nimbus.
Comparison: Matches; the body correctly attributes it as Khatami's own account.
Decision: primary-sourced

## Claim 19: Schubiner — campaign organiser; quote "technology workers actually have a lot of power to shift this paradigm"

Source: https://www.democracynow.org/2024/4/17/no_tech_for_apartheid_google_israel
Source tier: primary
Source content: Gabriel Schubiner (former Google Research engineer, No Tech for Apartheid organizer): "Technology workers actually have a lot of power to shift this paradigm and to remove technology from this deep complicity with Israeli occupation."
Comparison: Speaker role and quote match; body truncates the quote without altering the quoted span.
Decision: primary-sourced

## Claim 20: "Google fired more than fifty workers — 28 initially, then over twenty more by 22 April, including, per the campaign, non-participating bystanders" (also scalar:outcomes "over 50 workers fired")

Source: https://www.npr.org/2024/04/19/1245757317/google-worker-fired-israel-project-nimbus-cloud-protestor + https://www.forbes.com/sites/roberthart/2024/04/23/google-fires-more-workers-over-israeli-cloud-contract-protest-after-ceo-says-leave-politics-at-home/ (search-verified) + https://medium.com/@notechforapartheid/statement-from-google-workers-organizing-with-the-no-tech-for-apartheid-campaign-on-googles-17ee10b088f0
Source tier: mainstream
Source content: "Google fires 28 workers over Project Nimbus contract" (NPR headline, April 2024; same figure in Washington Post, Time, TechCrunch); "Google fired at least 20 more workers in connection with protests ... the latest round of firings brings the total number of people fired in connection with the incident to more than 50" (Forbes, 23 April, quoting a No Tech for Apartheid spokesperson); campaign statement: Google fired "over 20 additional workers ... That brings the total to over 50 workers that Google has indiscriminately retaliated against", including "non-participating bystanders during last week's protests".
Comparison: 28 initial firings corroborated by multiple mainstream outlets; the 20+ second round (evening of 22 April, reported 23 April) and the 50+ total corroborated by Forbes and the campaign's statement; bystander inclusion attributed to the campaign in the body, matching the statement (and consistent with AWU's "most of whom were not directly engaged in protest"). Nuance: the campaign's own statement counts "30 workers" already fired before the second round (i.e. 28 plus subsequent), so the body's 28-then-20+ breakdown follows mainstream reporting rather than the cited statement's arithmetic — no factual conflict, cumulative counts differ by intermediate firings.
Decision: corroborated

## Claim 21: AWU "condemned the firings, stating it was 'disappointed that Google has not seriously engaged with the concerns of thousands of their employees' and called the terminations retaliation against free speech" (+ sources[4].note: nine arrests, ~two dozen terminated, reinstatement call)

Source: https://www.alphabetworkersunion.org/press/updated-awu-cwa-statement-following-termination-of-workers-after-project-nimbus-protest-at-google-cloud-office
Source tier: primary
Source content: "We are disappointed that Google has not seriously engaged with the concerns of thousands of their employees and instead has engaged in a pattern of retaliation and discrimination against those who speak out."; "nine Google workers arrested"; "Roughly two dozen workers" terminated, "most of whom were not directly engaged in protest"; "We call for all terminated workers to be returned to work."
Comparison: Quote verbatim; arrest count, termination count ("approximately two dozen" in the note vs "roughly two dozen" in the statement), retaliation framing, and reinstatement call all match.
Decision: primary-sourced

## Claim 22: campaign's 23 April 2024 statement — "an aggressive and desperate act of retaliation"; demand to "drop Project Nimbus and stop powering Israel's genocide of Palestinians in Gaza now"

Source: https://medium.com/@notechforapartheid/statement-from-google-workers-organizing-with-the-no-tech-for-apartheid-campaign-on-googles-17ee10b088f0
Source tier: primary
Source content: "This evening, in an aggressive and desperate act of retaliation, Google fired over 20 additional workers"; the workers call on Google to "Drop Project Nimbus and stop powering Israel's genocide of Palestinians in Gaza now." Statement dated April 23, 2024.
Comparison: Date and both quoted spans match verbatim. Note for scalar:sources[5].note: its parenthetical gloss "(28 initially, then over twenty more by 22 April)" is the note author's reconstruction from mainstream reporting — the statement itself says "Google already fired 30 workers" before the second round; see Claim 20.
Decision: primary-sourced

## Claim 23: "By June 2024, more than 1,100 STEM students at 120+ universities had signed a pledge committing to refuse employment with Google or Amazon until Project Nimbus ends" (also scalar:outcomes)

Source: https://en.wikipedia.org/wiki/No_Tech_for_Apartheid + https://www.engadget.com/more-than-1000-students-pledge-not-to-work-at-google-and-amazon-due-to-project-nimbus-042439081.html
Source tier: mainstream
Source content: "More than 1,100 self-identified STEM students and young workers from more than 120 universities" signed a pledge refusing jobs or internships at Google or Amazon until Project Nimbus ends (Wikipedia); "More than 1,100 people who identified themselves as STEM students and young workers took the pledge to refuse jobs from the companies ... 'we pledge not to take jobs or internships at either company'" (Engadget, June 2024).
Comparison: Counts, date, and pledge content match across Wikipedia and Engadget. Note the sources describe signatories as "STEM students and young workers", slightly broader than the body's "STEM students" — the counts are the same.
Decision: corroborated

## Claim 24: "the campaign coordinated public actions at AWS Summit ... alongside the Amazon Labor Union" (also scalar:outcomes "sustained AWS-Summit ... co-actions with the Amazon Labor Union")

Source: https://www.mpowerchange.org/campaignupdates/amazon-labor-union-joins-amazon-tech-workers-to-protest-amazons-cloud-contracts-with-israel-at-companys-annual-aws-summit
Source tier: primary
Source content: "Amazon Labor Union Joins Amazon Tech Workers To Protest Amazon's Cloud Contracts with Israel at Company's Annual AWS Summit" — "Amazon tech workers were joined by dozens of supporters" including "Amazon warehouse workers including co-founders of the Amazon Labor Union"; "Part of a campaign called #NoTechforApartheid". (New York, 2023 AWS Summit; a further AWS Summit disruption in 2024 is documented on the campaign's channels.)
Comparison: ALU participation in campaign actions at AWS Summit confirmed by the campaign's own release.
Decision: primary-sourced

## Claim 25: co-actions at "shareholder-meeting events alongside the Amazon Labor Union" (also scalar:outcomes "shareholder-meeting co-actions with the Amazon Labor Union")

Source: no canonical source found
Source tier: none
Source content: Targeted searches for Amazon shareholder-meeting actions by No Tech for Apartheid with the Amazon Labor Union returned AWS Summit and Google-office actions only; no canonical source documenting a joint NTFA–ALU shareholder-meeting action was found this session.
Comparison: The AWS Summit half of the sentence is supported (Claim 24); the shareholder-meeting half could not be sourced. Names where the audit reaches its limits — not a finding of error.
Decision: uncorroborated

## Claim 26: "scalar:outcomes" — "As of mid-2026 the campaign has not achieved its primary demand: Project Nimbus remains in force and Google and Amazon have not renounced the contract"

Source: https://en.wikipedia.org/wiki/Project_Nimbus + https://www.business-standard.com/world-news/israel-project-nimbus-google-amazon-winking-mechanism-data-leak-125103000892_1.html (search-verified)
Source tier: mainstream
Source content: The contract "remains active as of 2026, with no indication of termination"; October 2025 reporting (Business Standard on the leaked "winking mechanism"; Democracy Now! headlines) and April 2026 EFF commentary treat the contract as ongoing.
Comparison: Continued force of the contract into 2026 confirmed; no source reports cancellation or renunciation.
Decision: corroborated

## Claim 27: "scalar:outcomes" — "the Lavender and 'Where's Daddy' automated-targeting disclosures — confirming Israeli military targeting systems ran on the Nimbus cloud" (also scalar:sources[8].note: the systems "were operating on the Nimbus cloud")

Source: https://en.wikipedia.org/wiki/Project_Nimbus
Source tier: none
Source content: The Wikipedia article "mentions these systems in connection with former Google employees' concerns but does not confirm they operate on Project Nimbus infrastructure. Former employees cited an article from +972 Magazine noting that programs called 'Lavender' and 'Where's Daddy' classify Palestinians, but the Wikipedia piece does not specify which cloud platform hosts these tools."
Comparison: The entity's own cited source for this claim (Wikipedia's Project Nimbus article) does not state that Lavender or "Where's Daddy" ran on the Nimbus cloud, and no canonical source found this session establishes it — the 2024 +972 disclosures documented the targeting systems' existence and use, not their hosting platform. The body's "confirming ... ran on the Nimbus cloud" overstates what the disclosures established; both scalar:outcomes and scalar:sources[8].note carry the overclaim. Recorded as uncorroborated rather than correction because the fix (reframing what the disclosures showed) requires prose judgment, not a single-token replacement.
Decision: uncorroborated

## Claim 28: "The 2018 Project Maven petition — in which over 3,100 Google workers successfully pressured the company not to renew a DoD AI-drone-imagery contract"

Source: https://www.cnbc.com/2018/04/05/google-employees-protest-pentagon-partnership-to-ceo-sundar-pichai.html + https://www.armscontrol.org/act/2018-07/news/google-renounces-ai-work-weapons (search-verified)
Source tier: mainstream
Source content: "The letter was circulated on an internal communication server among Google employees and collected 3,100 signatures ... 'We believe that Google should not be in the business of war'"; "By June of 2018, Google announced it would let the contract expire ... the contract wasn't canceled, but it wasn't renewed either." Project Maven "involves Google developing artificial intelligence surveillance to help the military analyze video footage captured by U.S. government drones".
Comparison: Signature count, contract subject (drone-imagery AI for DoD), and non-renewal outcome all match; edge target event-google-project-maven-petition-2018-04 resolves.
Decision: corroborated

## Claim 29: "scalar:sources[8].note" — "the contractual provision reportedly forbidding the two companies from halting services to any Israeli government entity including the military"

Source: https://en.wikipedia.org/wiki/Project_Nimbus + https://www.business-standard.com/world-news/israel-project-nimbus-google-amazon-winking-mechanism-data-leak-125103000892_1.html (search-verified)
Source tier: mainstream
Source content: "The terms Israel set for the project contractually forbid Amazon and Google from halting services due to boycott pressure" and the companies "are contractually forbidden from denying service to any particular entities of the Israeli government, including its military" (Wikipedia); October 2025 leak coverage: "The contract bars the companies from denying service to any Israeli government entity, including the military."
Comparison: The note's hedged "reportedly" claim matches both sources; Wikipedia is supported by independent mainstream coverage of the leaked contract terms.
Decision: corroborated
