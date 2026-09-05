---
entity_id: msg-ban-surveillance-schools
entity_hash: 080e550d7ef396796be760d4253e81dc845d997d
audit_date: 2026-09-04
pass: 1
status: corrections-pending
claims_total: 37
claims_corroborated: 11
claims_primary_sourced: 11
claims_single_source: 3
claims_uncorroborated: 6
open_corrections: 6
sources_consulted:
  - https://www.fightforthefuture.org/actions/ban-facial-recognition-in-schools
  - https://www.fightforthefuture.org/news/2020-01-14-students-activists-launch-nationwide-campaign-to/
  - https://tumblr.fightforthefuture.org/post/190805359068/more-than-40-organizations-stand-with-students-and
  - https://theappeal.org/after-a-long-fight-facial-recognition-technology-is-in-one-new-york-school-district/
  - https://www.nyclu.org/press-release/nyclu-sues-new-york-state-education-department-over-approval-facial-recognition
  - https://www.nyclu.org/press-release/nyclu-statement-lockport-school-districts-implementation-facial-recognition
  - https://parents-together.org/facial-recognition-enters-schools-but-does-it-really-make-our-kids-safer/
  - https://www.commondreams.org/newswire/2020/09/16/more-1000-parents-sign-open-letter-calling-ban-facial-recognition-schools
  - https://www.commondreams.org/news/2020/02/13/because-facial-recognition-makes-students-and-faculty-less-safe-40-rights-groups
  - https://www.eff.org/deeplinks/2020/09/students-are-pushing-back-against-proctoring-surveillance-apps
  - https://epic.org/2020/12/epic-files-dc-consumer-protect.html
  - https://www.vice.com/en/article/schools-are-abandoning-invasive-proctoring-software-after-student-backlash/
  - https://www.biometricupdate.com/202001/facial-recognition-gun-detection-system-implemented-in-lockport-schools-despite-controversy
  - https://www.biometricupdate.com/202302/scottish-schools-canteen-facial-recognition-likely-infringed-gdpr-ico
  - https://www.navigatorlaw.co.uk/ico-publish-statement-on-scottish-schools-use-of-facial-recognition-technology/
  - https://www.mishcon.com/news/ico-takes-action-on-facial-recognition-in-schools
  - https://bigbrotherwatch.org.uk/2023/05/new-report-says-government-should-urgently-stop-live-facial-recognition-in-the-uk/
  - https://www.aclu.org/press-releases/new-aclu-report-shines-light-on-shadowy-edtech-surveillance-industry-and-the-dangerous-consequences-of-surveillance-in-schools
  - https://www.ajl.org/library/policy-advocacy
  - https://www.governor.ny.gov/news/governor-cuomo-signs-legislation-suspending-use-and-directing-study-facial-recognition
  - https://www.forbes.com/sites/rachelsandler/2020/12/22/new-york-issues-first-in-nation-moratorium-on-facial-recognition-in-schools/
  - https://www.buzzfeednews.com/article/daveyalba/lockport-schools-facial-recognition-pilot-aegis
  - https://www.govtech.com/computing/aegis-software-turned-on-in-lockport-schools.html
  - https://venturebeat.com/ai/fight-for-the-future-launches-campaign-to-keep-facial-recognition-off-u-s-college-campuses
  - https://www.eff.org/deeplinks/2020/10/bar-applicants-deserve-better-proctored-barpocalypse
---

## Claim 1: edge — `originating_org: org-fight-for-the-future` (+ propagated_by) — FFTF originated and led the campaigns

Source: https://www.fightforthefuture.org/news/2020-01-14-students-activists-launch-nationwide-campaign-to/ and https://www.fightforthefuture.org/actions/ban-facial-recognition-in-schools
Source tier: primary
Source content: FFTF's own release: teamed up with SSDP to "launch a nationwide effort to ban facial recognition from university campuses across the USA"; own campaign page demands rejection by "state education departments, lawmakers, and other school administrators".
Comparison: Edge resolves to product/entities/organizations/org-fight-for-the-future.md; FFTF's own campaign artifacts establish origination of the demand as framed.
Decision: primary-sourced

## Claim 2: edge — `propagated_by_orgs: org-aclu`

Source: https://www.aclu.org/press-releases/new-aclu-report-shines-light-on-shadowy-edtech-surveillance-industry-and-the-dangerous-consequences-of-surveillance-in-schools + https://tumblr.fightforthefuture.org/post/190805359068/
Source tier: primary
Source content: ACLU authored "Digital Dystopia" (Oct 3, 2023); FFTF letter page: "The signers span the political spectrum and include the ACLU, …".
Comparison: Edge resolves; ACLU both signed the 2020 university-ban letter and authored the consolidation report. Two independent confirmations.
Decision: corroborated

## Claim 3: edge — `propagated_by_orgs: org-electronic-frontier-foundation`

Source: https://www.eff.org/deeplinks/2020/09/students-are-pushing-back-against-proctoring-surveillance-apps + https://tumblr.fightforthefuture.org/post/190805359068/
Source tier: primary
Source content: EFF's own proctoring-pushback documentation; FFTF letter page signatory list includes "Electronic Frontier Foundation".
Comparison: Edge resolves; EFF's own advocacy piece plus letter signature confirm propagation.
Decision: corroborated

## Claim 4: edge — `propagated_by_orgs: org-big-brother-watch`

Source: https://bigbrotherwatch.org.uk/2023/05/new-report-says-government-should-urgently-stop-live-facial-recognition-in-the-uk/
Source tier: primary
Source content: "The report also uncovers how several schools have rolled out facial recognition-powered cashless canteens, with some even charging children for a swipecard if they do not consent to biometric scans."
Comparison: Edge resolves; BBW's own report page documents its school-canteen campaigning.
Decision: primary-sourced

## Claim 5: edge — `propagated_by_orgs: org-algorithmic-justice-league`

Source: https://www.ajl.org/library/policy-advocacy
Source tier: primary
Source content: "A 6787/S 5140 to ban the use of biometric surveillance technology in schools and require a commission to study the effects of this sort of technology on children."
Comparison: Edge resolves; AJL's own policy-advocacy page lists advocacy for the NY school-biometric-surveillance ban bill — direct propagation of the demand.
Decision: primary-sourced

## Claim 6: edges — `related_messages` (msg-ban-biometric-mass-surveillance, msg-banthescan, msg-coded-gaze, msg-protect-not-surveil)

Source: product/entities/messages/ (repository cross-check)
Source tier: primary
Source content: All four entity files exist and match the named framings.
Comparison: Each edge resolves to the intended entity; relatedness rationale in body is interpretation, not audited.
Decision: corroborated

## Claim 7: "the first known US public school district to deploy facial recognition" (body §Lockport; origin has "focal controversy")

Source: https://www.buzzfeednews.com/article/daveyalba/lockport-schools-facial-recognition-pilot-aegis vs https://theappeal.org/after-a-long-fight-facial-recognition-technology-is-in-one-new-york-school-district/
Source tier: mainstream
Source content: BuzzFeed headline: "Lockport Public Schools Will Be The First In The Country To Use Facial Recognition"; but The Appeal (fetched): "the technology was turned on, making the Lockport school district the first in the state to use facial recognition software" and "Wired reported last year that at least eight other school districts in the country have deployed the technology."
Comparison: Canonical sources disagree on the "first in the US" framing — the cited Appeal article itself says first *in the state* and relays Wired's count of eight other deploying districts. Contested-"first" class; no winner picked.
Decision: uncorroborated

## Claim 8: Aegis facial recognition system by SN Technologies, activated in Lockport schools January 2020

Source: https://www.biometricupdate.com/202001/facial-recognition-gun-detection-system-implemented-in-lockport-schools-despite-controversy + https://theappeal.org/... + BuzzFeed/GovTech via search snippets
Source tier: mainstream
Source content: Biometric Update: "A facial recognition system was implemented on January 2, 2020 in the Lockport school district in New York state"; The Appeal (Feb 7, 2020) dates activation to January 2020; BuzzFeed/GovTech coverage names the Aegis system from Canada-based SN Technologies.
Comparison: System name, vendor, and January 2020 activation all match across multiple outlets. Note: the vendor name does not appear in the cited Appeal article (see Claim 33).
Decision: corroborated

## Claim 9: "went live across 300 cameras" (body §Lockport; origin "running across 300 cameras")

Source: https://www.biometricupdate.com/202001/facial-recognition-gun-detection-system-implemented-in-lockport-schools-despite-controversy
Source tier: mainstream
Source content: "Aegis consists in 300 cameras, servers and software which cost the district $1.4 million."
Comparison: The 300-camera figure matches one canonical specialist outlet; the cited Appeal article does not carry a camera count (see Claim 33).
Decision: single-source

## Claim 10: "in eight Lockport schools" / origin "eight schools"

Source: https://www.biometricupdate.com/202001/... vs GovTech via search snippets
Source tier: mainstream
Source content: Biometric Update: "The system has been installed in the district office and ten school buildings, at a total cost of $3.8 million." GovTech-derived coverage describes the district's eight schools.
Comparison: Canonical sources disagree on the building/school count (eight schools vs. ten school buildings plus district office); the cited Appeal article carries no count. No winner picked.
Decision: uncorroborated

## Claim 11: "In 2015, a security consultant approaching the district offered a free threat assessment and recommended the purchase of a camera system with facial recognition capability"

Source: https://theappeal.org/after-a-long-fight-facial-recognition-technology-is-in-one-new-york-school-district/
Source tier: mainstream
Source content: "In 2015, a security consultant approached the Lockport City School District in western New York, offering to do a free threat assessment." The consultant recommended a camera system equipped with facial recognition technology costing $1.4 million.
Comparison: Matches the cited source directly.
Decision: single-source

## Claim 12: "Following the February 2018 Marjory Stoneman Douglas High School shooting … Lockport moved to install Aegis"

Source: no canonical source pinned this session
Source tier: none
Source content: The Appeal (fetched): no mention of Parkland/Marjory Stoneman Douglas. Biometric Update (fetched): no mention. Search synthesis asserted an "in the wake of the 2018 shooting" link but no specific canonical page carrying it could be pinned.
Comparison: The Parkland-causation framing is not in either fetched Lockport source; the district's procurement began from the 2015 consultant visit and Smart Schools Bond Act funds, which predate Parkland. Causal claim without a pinned canonical carrier.
Decision: uncorroborated

## Claim 13: NYCLU "sued the New York State Education Department over its approval of the system"

Source: https://www.nyclu.org/press-release/nyclu-sues-new-york-state-education-department-over-approval-facial-recognition
Source tier: primary
Source content: NYCLU (June 22, 2020) "sued the New York State Education Department for approving a facial recognition technology system in Lockport City Schools, claiming it violated student data protection laws."
Comparison: Matches the cited primary source (the NYCLU's own release).
Decision: primary-sourced

## Claim 14: "The NYCLU's Stefanie Coyle stated that 'Subjecting 5-year-olds to this technology will not make anyone safer, and we can't allow invasive surveillance to become the norm in our public spaces.'"

Source: https://parents-together.org/facial-recognition-enters-schools-but-does-it-really-make-our-kids-safer/ (only carrier found)
Source tier: caution
Source content: ParentsTogether: "'Subjecting 5-year-olds to this technology will not make anyone safer, and we can't allow invasive surveillance to become the norm in our public spaces,' reasons Stefanie Coyle of the New York Civil Liberties Union."
Comparison: The quote exists with this attribution only on an advocacy-nonprofit blog; the cited NYCLU lawsuit release does not contain it (its Coyle quote is "NYSED's approval of this technology demonstrated a dangerous lack of oversight…"), nor does the NYCLU implementation statement (fetched). No canonical carrier found.
Decision: uncorroborated

## Claim 15: "New York legislators passed a bill banning facial recognition in schools in July 2020; Governor Andrew Cuomo signed it into law in December 2020 — the first US state prohibition" (also origin)

Source: https://www.governor.ny.gov/news/governor-cuomo-signs-legislation-suspending-use-and-directing-study-facial-recognition + https://www.forbes.com/sites/rachelsandler/2020/12/22/new-york-issues-first-in-nation-moratorium-on-facial-recognition-in-schools/ (via search snippets)
Source tier: primary
Source content: Governor's office: "Governor Cuomo Signs Legislation Suspending Use and Directing Study of Facial Recognition Technology in Schools" (signed Dec 22, 2020); Forbes: "New York Issues First-In-Nation Moratorium On Facial Recognition In Schools"; coverage: legislature passed the bill in July 2020; moratorium "until at least July 1, 2022 or until a study is conducted."
Comparison: Dates and first-in-nation status corroborate. Nuance: the December 2020 law was a suspension/moratorium pending study (made permanent in 2023), which contemporaneous outlets also headlined as a "ban"; the body's unqualified "prohibition" tracks that usage but elides the temporary form.
Decision: corroborated

## Claim 16: FFTF campaign-page content — "biased, and more likely to misidentify students of color"; targeting for tardiness/bathroom visits; watch lists and false arrests; "unethical experiment"; NY ban as model; demand aimed at administrators and state education departments

Source: https://www.fightforthefuture.org/actions/ban-facial-recognition-in-schools
Source tier: primary
Source content: "It's biased, and more likely to misidentify students of color."; "school administrators are already bragging about using this technology to target students for being late"; "track how many times students go to the bathroom"; "Minority students are more likely to end up on watch lists or to get falsely arrested because of an error in the system"; "quietly spending millions conducting unethical experiments with facial recognition software"; "New York State decided to ban facial recognition in schools" urging other states to "take the same steps to protect our kids."
Comparison: All quoted/paraphrased campaign-page claims verified verbatim against the live page.
Decision: primary-sourced

## Claim 17: "In January 2020, the organisation partnered with Students for Sensible Drug Policy to launch a college campus campaign — mobilising student government resolutions at George Washington University and DePaul University"

Source: https://www.fightforthefuture.org/news/2020-01-14-students-activists-launch-nationwide-campaign-to/
Source tier: primary
Source content: Campaign announced January 14, 2020; SSDP "teamed up" with FFTF; "At campuses around the country, including George Washington in DC and DePaul in Chicago, student groups are organizing to introduce student government resolutions to ban facial recognition."
Comparison: Launch month, SSDP partnership, and both named campuses match FFTF's own release. ("Mobilising" resolutions matches "organizing to introduce"; the release does not claim passage, nor does the body.) Note: these specifics are not in the cited Feb 13 Common Dreams piece, which names other campuses.
Decision: primary-sourced

## Claim 18: 40+-rights-group coalition letter calling on universities to ban facial recognition (February 2020)

Source: https://www.commondreams.org/news/2020/02/13/because-facial-recognition-makes-students-and-faculty-less-safe-40-rights-groups + https://tumblr.fightforthefuture.org/post/190805359068/
Source tier: mainstream
Source content: Common Dreams (Feb 13, 2020): more than 40 rights organizations signed the letter, including the ACLU, National Immigration Law Center, and National Center for Transgender Equality; FFTF's own post: "more than 40 organizations" signed.
Comparison: Count and demand match across the news piece and FFTF's own record. Origin's phrasing folds the letter into the January launch; the letter's release was February 13, 2020 (campaign launch was January 14) — sequencing conflation, not a token error; the body §Lockport handles it correctly.
Decision: corroborated

## Claim 19: September 2020 K-12 campaign — over 1,000 parents signed an open letter; grounds: psychological effects, data-breach risk, discriminatory targeting of "students of color, girls, and gender nonconforming" students

Source: https://www.commondreams.org/newswire/2020/09/16/more-1000-parents-sign-open-letter-calling-ban-facial-recognition-schools
Source tier: primary
Source content: More than 1,000 parents from all 50 states signed (release dated September 16, 2020); concerns named: unknown psychological dangers from constant surveillance; physical danger if data is compromised; discrimination against "students of color, girls, and gender nonconforming kids"; organized by Fight for the Future.
Comparison: Count, date, organizer, and all three grounds match (FFTF's own release carried on the newswire).
Decision: primary-sourced

## Claim 20: "Proctorio, Respondus Monitor, HonorLock, ExamSoft, and ProctorU were deployed across hundreds of universities, monitoring students via webcam, tracking gaze patterns, analysing keystroke behaviour" (also origin's platform list)

Source: https://www.eff.org/deeplinks/2020/09/students-are-pushing-back-against-proctoring-surveillance-apps + https://www.eff.org/deeplinks/2020/10/bar-applicants-deserve-better-proctored-barpocalypse and VentureBeat via search snippets
Source tier: primary
Source content: EFF (Sept 25, 2020) names Honorlock, Proctorio, ProctorU, Respondus (and Proctortrack) with webcam/gaze monitoring; EFF/VentureBeat coverage documents ExamSoft's pandemic-era remote bar-exam deployment and facial recognition failures for darker-skinned examinees.
Comparison: All five named platforms' pandemic-scale deployment and the monitoring modalities are documented across EFF's two pieces plus mainstream coverage.
Decision: corroborated

## Claim 21: "Proctorio alone was proctoring more than five times its pre-pandemic volume by the end of 2020" (cited to VICE)

Source: https://www.vice.com/en/article/schools-are-abandoning-invasive-proctoring-software-after-student-backlash/
Source tier: mainstream
Source content: Proctorio "proctored more than 20 million exams in 2020 (triple the number in 2019, the company told Motherboard)".
Comparison: The cited source says *triple* its 2019 volume for full-year 2020, not "more than five times"; targeted refetch confirmed no five-times figure anywhere in the article (a separate "four to five times" figure in other coverage refers to company value, not volume). Single correct replacement: "more than three times" (or "triple"). Body token contradicts its cited source.
Decision: correction

## Claim 22: EFF September 2020 documentation — darker-skin recognition failures, gaze-tracking flagging neurodivergent students, personal-device file access, petitions at dozens of institutions

Source: https://www.eff.org/deeplinks/2020/09/students-are-pushing-back-against-proctoring-surveillance-apps
Source tier: primary
Source content: "students with black or brown skin have been asked to shine more light on their faces, as the software had difficulty recognizing them"; Proctorio "tracks a student's gaze, and flags students who look away from the screen as 'suspicious'" which "negatively impacts people who have ADHD-like symptoms"; UMass Lowell petitioners on Respondus's Ring-0 software ("creates massive security vulnerabilities"); petitions at UT Dallas (6,300+), FIU (7,200+), CSU Fullerton (4,500+), and others.
Comparison: All documented-failure claims and the piece's date (September 25, 2020) match; body's paraphrases are faithful to the petition accounts EFF quotes.
Decision: primary-sourced

## Claim 23: "EPIC asked the DC Attorney General to investigate the privacy practices and 'unfair and deceptive' business claims of Proctorio, Respondus, Examity, ProctorU, and HonorLock" (also origin's "complaint to the DC Attorney General against five major proctoring platforms")

Source: https://epic.org/2020/12/epic-files-dc-consumer-protect.html (+ EPIC complaint PDF, via search)
Source tier: primary
Source content: On December 9, 2020, EPIC filed a complaint with the Office of the Attorney General for the District of Columbia alleging that "Respondus, ProctorU, Proctorio, Examity, and Honorlock have engaged in unfair and deceptive trade practices" under the DC CPPA.
Comparison: Company set, venue, and "unfair and deceptive" characterization all match EPIC's own filing record. The body hyperlinks this claim to the EFF September 2020 piece, which predates the complaint by 2.5 months and does not mention EPIC — fact verified, citation misattributed (see Claim 35).
Decision: primary-sourced

## Claim 24: "At the University of Massachusetts Lowell, 1,200 students signed a petition objecting to Respondus, leading the university to announce professors could not mandate its use" (origin: "institutional reversals at … University of Massachusetts Lowell")

Source: https://www.eff.org/deeplinks/2020/09/students-are-pushing-back-against-proctoring-surveillance-apps (petition existence only)
Source tier: mainstream
Source content: EFF confirms UMass Lowell petitioners objected to Respondus's Ring-0 software; the change.org petition shows over 1,000 signatures. The cited VICE article, on targeted refetch: "There is no reference to UMass Lowell, a 1,200-student petition, or any university policy restricting professor mandates regarding Respondus in this text."
Comparison: The petition is real, but the specific 1,200 figure and the claimed institutional outcome (professors could not mandate use) were found in no canonical source, and the cited VICE source carries neither.
Decision: uncorroborated

## Claim 25: "The University of Southern California announced it would drop Respondus Monitor entirely"

Source: https://www.vice.com/en/article/schools-are-abandoning-invasive-proctoring-software-after-student-backlash/
Source tier: mainstream
Source content: "In January, the University of Southern California announced that it would no longer use Respondus Monitor."
Comparison: Matches the cited source directly.
Decision: single-source

## Claim 26: North Ayrshire Council introduced facial recognition for cashless meal payments across nine schools in 2021; ICO letter January 2023 found likely UK GDPR infringement (lawful basis); Council ceased processing after concerns raised (body + origin)

Source: https://www.biometricupdate.com/202302/scottish-schools-canteen-facial-recognition-likely-infringed-gdpr-ico + dataguidance.com and mishcon.com via search snippets (ico.org.uk 403 on direct fetch)
Source tier: mainstream
Source content: ICO "issued a letter to North Ayrshire Council" (announced 31 January 2023) "following their use of Facial Recognition Technology across nine of its schools to manage 'cashless catering'"; "NAC had stopped processing shortly after data protection concerns were raised with the ICO in October 2021"; deployment "likely to have infringed data protection law under several Articles of the UK GDPR including Articles 5(1)(a), 6, 9, 12, 13, and 35."
Comparison: School count, 2021 introduction, January 2023 letter, likely-infringement finding, and cessation all corroborate across multiple independent legal/specialist accounts of the ICO letter.
Decision: corroborated

## Claim 27: Consent findings — consent statement not specific / not presented as a choice distinct from cashless payment; failure to obtain consent from pupils aged 12+ despite Scottish law's presumption of capacity

Source: https://www.navigatorlaw.co.uk/ico-publish-statement-on-scottish-schools-use-of-facial-recognition-technology/ + https://www.mishcon.com/news/ico-takes-action-on-facial-recognition-in-schools (via search snippets)
Source tier: mainstream
Source content: "In Scotland pupils aged 12 or over are presumed to be of sufficient age and maturity to give the necessary consent"; the Council "relied on parental consent for pupils aged 12-14, instead of obtaining consent directly from the pupils themselves," parental consent permissible "only … where it has been determined that the child lacks competence … on a case by case basis"; "Insufficient information was provided to children and parents for them to be able to consent," the system "not present[ed] as being a choice."
Comparison: All three consent findings match independent legal analyses of the ICO letter; body's "option distinct from the cashless payment system" is a fair paraphrase of the not-presented-as-a-choice finding.
Decision: corroborated

## Claim 28: Big Brother Watch "documented similar deployments at other UK schools and reported that some institutions were charging children for a swipecard if they declined biometric scanning"

Source: https://bigbrotherwatch.org.uk/2023/05/new-report-says-government-should-urgently-stop-live-facial-recognition-in-the-uk/
Source tier: primary
Source content: "The report also uncovers how several schools have rolled out facial recognition-powered cashless canteens, with some even charging children for a swipecard if they do not consent to biometric scans."
Comparison: Matches BBW's own report announcement verbatim.
Decision: primary-sourced

## Claim 29: ACLU report "Digital Dystopia: The Danger in Buying What the EdTech Surveillance Industry is Selling", October 2023; "$3.1 billion US school surveillance market" (body + origin)

Source: https://www.aclu.org/press-releases/new-aclu-report-shines-light-on-shadowy-edtech-surveillance-industry-and-the-dangerous-consequences-of-surveillance-in-schools + The Hill/74million via search snippets
Source tier: primary
Source content: Report title confirmed, released October 3, 2023; "K-12 schools spent an estimated $3.1 billion on security products and services in 2021, up from $2.7 billion in 2017."
Comparison: Title, date, and figure match; the release frames $3.1B as 2021 spend on security products/services, which the body renders as market size — consistent with the release's own "industry" framing.
Decision: corroborated

## Claim 30: "surveillance cameras were present in 8 of 10 of the deadliest school shootings in the United States without preventing them" (body + origin's "8 of 10 deadliest school shootings")

Source: https://www.aclu.org/press-releases/new-aclu-report-shines-light-on-shadowy-edtech-surveillance-industry... + coverage via search snippets
Source tier: primary
Source content: "Surveillance cameras were present in 8 of the 10 deadliest schools that experienced mass shootings, yet failed to prevent those incidents."
Comparison: Matches the release and independent coverage of the report.
Decision: corroborated

## Claim 31: "6 in 10 students report they do not feel comfortable expressing their true thoughts and feelings online when their activity is monitored" (body; origin's "6 in 10 students feel chilled")

Source: no canonical source found (cited ACLU press release affirmatively lacks it)
Source tier: none
Source content: Targeted refetch of the cited ACLU release: "No such statistics or sentences exist in the provided content." The release's survey figures are different: "Almost all (87 percent) of students ages 14-18 claimed that their school used surveillance technology…, with 24 percent concerned with how school surveillance limits the resources they feel they can access online, and 17 percent had concerns about school surveillance limiting what they say online."
Comparison: The 6-in-10 figure appears in neither the cited release nor any reachable coverage (The Hill, The 74, POCIT checked; full report PDF exceeds the fetch size cap, so the figure may exist inside the report but could not be verified). No replacement token can be asserted.
Decision: uncorroborated

## Claim 32: Disproportionate-harm populations — "students of color, LGBTQ students, students with disabilities, low-income students, and students in immigrant families" (body; origin's near-identical list)

Source: https://www.aclu.org/press-releases/new-aclu-report-shines-light-on-shadowy-edtech-surveillance-industry...
Source tier: primary
Source content: "Students who are members of the LGBTQ community, students of color, students with disabilities, low-income students, and students who are undocumented or have undocumented family members are especially vulnerable to the many harmful consequences of surveillance in schools."
Comparison: Population list matches the release ("immigrant families" fairly renders "undocumented or have undocumented family members").
Decision: primary-sourced

## Claim 33: scalar:sources[1].note (theappeal.org) — "primary source for … the Aegis system by SN Technologies, 300 cameras in eight schools, January 2020 activation, and the NYCLU opposition"

Source: https://theappeal.org/after-a-long-fight-facial-recognition-technology-is-in-one-new-york-school-district/
Source tier: mainstream
Source content: Targeted refetch: "Number of cameras: No specific number mentioned"; "'Aegis': Not mentioned"; "'SN Technologies': Not mentioned"; no eight-schools count (the article's "eight" refers to *other* districts, via Wired). January 2020 activation and NYCLU criticism ARE present.
Comparison: The note asserts source content the article does not contain — Aegis, SN Technologies, 300 cameras, and eight schools all absent (they verify via Biometric Update/BuzzFeed/GovTech instead). Fix requires re-sourcing prose in the note (and the body links for those tokens) — prose judgment beyond a single replacement; Editor should flag to Researcher.
Decision: correction

## Claim 34: scalar:sources[2].note (nyclu.org) — "primary source for the NYCLU legal challenge and Stefanie Coyle's statement: 'Subjecting 5-year-olds to this technology…'"

Source: https://www.nyclu.org/press-release/nyclu-sues-new-york-state-education-department-over-approval-facial-recognition
Source tier: primary
Source content: The release's only Coyle quote: "NYSED's approval of this technology demonstrated a dangerous lack of oversight and an alarming misunderstanding of the way it analyzes student data." The fetch notes the "Subjecting 5-year-olds" quote "does not appear in this document."
Comparison: Legal-challenge half of the note is accurate; the Coyle-quote attribution is contradicted — the quote is not in the cited release (only carrier found is a non-canonical advocacy blog, Claim 14). Fix requires re-sourcing or removing the quote attribution — prose judgment; Editor should flag to Researcher.
Decision: correction

## Claim 35: scalar:sources[5].note (eff.org) — "primary source for … EPIC's DC Attorney General complaint against Proctorio, Respondus, Examity, ProctorU, and Honorlock"

Source: https://www.eff.org/deeplinks/2020/09/students-are-pushing-back-against-proctoring-surveillance-apps
Source tier: primary
Source content: Fetch: "This article does not mention EPIC, any complaint to regulators, or allegations of unfair/deceptive practices."
Comparison: The EFF piece (September 25, 2020) predates EPIC's complaint (December 9, 2020) and cannot contain it; the complaint verifies at epic.org (Claim 23). The note (and the body hyperlink on the EPIC sentence) misattribute; fix is re-sourcing to EPIC's own filing record — prose judgment; Editor should flag to Researcher.
Decision: correction

## Claim 36: scalar:sources[7].note (aclu.org) — "primary source for … the 6-in-10 students chilling-effects finding"

Source: https://www.aclu.org/press-releases/new-aclu-report-shines-light-on-shadowy-edtech-surveillance-industry...
Source tier: primary
Source content: Targeted refetch found no 6-in-10 / ~60% expression statistic; the release's chilling figures are 87%/24%/17% (quoted at Claim 31).
Comparison: The note's other three attributions ($3.1B, 8-of-10 shootings, populations) verify against the release; the 6-in-10 attribution is contradicted — the release does not carry it. Fix requires re-sourcing or revising the finding — prose judgment; Editor should flag to Researcher.
Decision: correction

## Claim 37: scalar:sources[8].note (vice.com) — "primary source for institutional reversals including … UMass Lowell restricting mandatory proctoring requirements after a 1,200-student petition; and for Proctorio's five-times increase in proctored exam volume"

Source: https://www.vice.com/en/article/schools-are-abandoning-invasive-proctoring-software-after-student-backlash/
Source tier: mainstream
Source content: Targeted refetch: "There is no reference to UMass Lowell, a 1,200-student petition, or any university policy restricting professor mandates"; volume figure is "more than 20 million exams in 2020 (triple the number in 2019)".
Comparison: The USC attribution in the note is accurate; the UMass Lowell reversal, 1,200 figure, and five-times figure are all absent from the article (and the five-times token contradicts its "triple" — Claim 21). Fix requires note revision — prose judgment; Editor should flag to Researcher.
Decision: correction
