---
entity_id: camp-fight-for-the-future-ban-surveillance-schools-us
entity_hash: d00564beaefea1a26342872883d9e5b81feac536
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 30
claims_corroborated: 13
claims_primary_sourced: 7
claims_single_source: 3
claims_uncorroborated: 5
open_corrections: 2
sources_consulted:
  - https://www.fightforthefuture.org/news/2020-01-14-students-activists-launch-nationwide-campaign-to/
  - https://www.fightforthefuture.org/news/2020-07-23-victory-against-facial-recognition-in-new-york/
  - https://www.nysed.gov/news/2023/state-education-department-issues-determination-biometric-identifying-technology-schools
  - https://fightfortheftr.medium.com/letter-from-40-civil-society-organizations-ban-facial-recognition-on-college-campuses-3db826cc994c
  - https://www.fightforthefuture.org/news/2024-09-28-students-across-the-country-call-for-a-back-to-school-ban-on-facial-recognition/
  - https://www.fightforthefuture.org/news/2025-08-19-universities-dismantle-surveillance-protect-free-speech/
  - https://fightfortheftr.medium.com/students-rally-to-ban-facial-recognition-from-campus-a18899efb466
  - https://www.fightforthefuture.org/actions/ban-facial-recognition-in-schools
  - https://www.banfacialrecognition.com/schools/
  - https://buffalonews.com/news/local/education/lockport-schools-activate-facial-recognition-system/article_df9722d4-b608-51ab-95b3-a8984cdacbf6.html
  - https://edscoop.com/lockport-city-facial-recognition-finally-activated-new-york-school-district/
  - https://www.governor.ny.gov/news/governor-cuomo-signs-legislation-suspending-use-and-directing-study-facial-recognition
  - https://www.aclu.org/press-releases/new-york-creates-first-nation-moratorium-facial-recognition-schools
  - https://www.forbes.com/sites/rachelsandler/2020/12/22/new-york-issues-first-in-nation-moratorium-on-facial-recognition-in-schools/
  - https://epic.org/new-york-enacts-law-suspending-use-of-facial-recognition-in-schools/
  - https://ssdp.org/blog/ban-facial-recognition-on-campus-day-of-action/
  - https://georgetownlawtechreview.org/facial-recognition-systems-are-hitting-a-wall-of-opposition-on-college-campuses/GLTR-03-2020/
  - https://www.insidehighered.com/news/2020/02/21/ucla-drops-plan-use-facial-recognition-security-surveillance-other-colleges-may-be
  - https://www.fightforthefuture.org/news/2020-01-27-new-scorecard-shows-which-colleges-are-using/
  - https://www.commondreams.org/news/2019/07/09/we-need-ban-it-entirely-beyond-regulation-new-us-campaign-calls-moratorium-facial
  - https://www.washingtonpost.com/health/ny-lawmakers-vote-to-pause-facial-recognition-in-schools/2020/07/23/b59d240c-cd04-11ea-99b0-8426e26d203b_story.html
---

## Claim 1: `lead_orgs` edge — org-fight-for-the-future (Fight for the Future leads the campaign)

Source: https://www.fightforthefuture.org/news/2020-01-14-students-activists-launch-nationwide-campaign-to/ and https://venturebeat.com/ai/fight-for-the-future-launches-campaign-to-keep-facial-recognition-off-u-s-college-campuses
Source tier: primary
Source content: "Fight for the Future and Students for Sensible Drug Policy" co-launched the campus campaign; VentureBeat headline: "Fight for the Future launches campaign to keep facial recognition off U.S. college campuses." Every campaign milestone document (2020 launch, 2024 delivery, 2025 letter) is a Fight for the Future release.
Comparison: Edge resolves to an existing entity; FFTF's lead role is confirmed by its own releases and mainstream coverage.
Decision: corroborated

## Claim 2: `participating_orgs` edge — org-electronic-frontier-foundation

Source: https://fightfortheftr.medium.com/letter-from-40-civil-society-organizations-ban-facial-recognition-on-college-campuses-3db826cc994c and https://www.fightforthefuture.org/news/2025-08-19-universities-dismantle-surveillance-protect-free-speech/
Source tier: primary
Source content: EFF confirmed as signatory of the 13 February 2020 open letter; "Electronic Frontier Foundation (EFF)" listed among the August 2025 letter's 41 signatories.
Comparison: Edge resolves; EFF's participation is evidenced in two campaign documents, both published by the lead org (not independent of each other).
Decision: primary-sourced

## Claim 3: `participating_orgs` edge — org-encode-justice

Source: https://www.fightforthefuture.org/news/2024-09-28-students-across-the-country-call-for-a-back-to-school-ban-on-facial-recognition/
Source tier: primary
Source content: "Encode Justice California hosted a virtual 'learn-athon' educating students on the dangers of facial recognition."
Comparison: Edge resolves; Encode Justice's participation (California actions, September 2024) confirmed by the campaign's own release. Body's "co-ordinated the California actions" is a fair rendering of hosting the named California action.
Decision: primary-sourced

## Claim 4: `strategies` edge — strat-local-rapid-response-against-single-deployment

Source: product/entities/strategies/strat-local-rapid-response-against-single-deployment.md (corpus-internal) and https://www.fightforthefuture.org/actions/ban-facial-recognition-in-schools
Source tier: primary
Source content: The strategy entity's `effects` list records this campaign's arc as an effect: "New York State enacted the Biometric Identifying Technology in Schools Act in July 2020 (signed December 2020)... after Fight for the Future, NYCLU and EPIC coalition pressure; the NYSED Commissioner issued a permanent prohibition... on 27 September 2023," sourced to the same FFTF action page this entity cites.
Comparison: Edge resolves to an existing entity and is reverse-consistent — the strategy's own effect record names this campaign's outcome.
Decision: corroborated

## Claim 5: `start_date: 2020-01` (campaign launched January 2020)

Source: https://www.fightforthefuture.org/news/2020-01-14-students-activists-launch-nationwide-campaign-to/ and https://venturebeat.com/ai/fight-for-the-future-launches-campaign-to-keep-facial-recognition-off-u-s-college-campuses
Source tier: primary
Source content: Launch announcement dated January 14, 2020: "Fight for the Future and Students for Sensible Drug Policy" launch nationwide campus campaign; independently covered by VentureBeat.
Comparison: The January 2020 start matches the documented 14 January 2020 launch.
Decision: corroborated

## Claim 6: `end_date: ongoing` / `status: active` (campaign remains active)

Source: https://www.fightforthefuture.org/actions/ban-facial-recognition-in-schools
Source tier: primary
Source content: Live action page fetched this session: "We can build on the momentum coming out of this decision and push other states to take the same steps to protect our kids" — presented as an active, ongoing campaign; most recent milestone document August 2025.
Comparison: Ongoing status supported by the live action page and August 2025 activity.
Decision: primary-sourced

## Claim 7: scalar:outcomes — "January 2020: Fight for the Future and Students for Sensible Drug Policy co-launched the campus track"

Source: https://www.fightforthefuture.org/news/2020-01-14-students-activists-launch-nationwide-campaign-to/ and https://venturebeat.com/ai/fight-for-the-future-launches-campaign-to-keep-facial-recognition-off-u-s-college-campuses
Source tier: primary
Source content: "Co-launching Organizations: Fight for the Future and Students for Sensible Drug Policy"; launch date January 14, 2020.
Comparison: Co-launch, partners, and date match. Scalar path: `outcomes`.
Decision: corroborated

## Claim 8: scalar:outcomes — "January 2020: ... coordinated a national day of action targeting 40+ universities"

Source: https://ssdp.org/blog/ban-facial-recognition-on-campus-day-of-action/ and https://fightfortheftr.medium.com/students-and-activists-announce-national-day-of-action-to-ban-facial-recognition-from-college-61b539f1982d
Source tier: primary
Source content: "A national campus day of action took place on March 2nd, organized... Fight for the Future, the New York Civil Liberties Union (NYCLU), and Students for Sensible Drug Policy." The 14 January 2020 launch release identifies "40 major university administrations including Stanford, Harvard, and Northwestern" for contact but does not announce a day of action ("National Day of Action: Not mentioned in this content").
Comparison: The day of action occurred on 2 March 2020, not January 2020; the "40+ universities" figure belongs to the January launch's contact list. The milestone conflates the launch and the later day of action — fixing it requires re-dating/splitting the milestone (prose judgment, not a single-token replacement). Scalar path: `outcomes`; body § "The January–February 2020 campaign launch" carries the same day-of-action sentence undated (proportionate, not contradicted).
Decision: uncorroborated

## Claim 9: 13 February 2020 open letter — 40+ civil society organisations to school/university administrators; signatories incl. EFF, ACLU, NYCLU, EPIC, Color of Change, Demand Progress, Muslim Justice League, National Center for Transgender Equality, National Immigration Law Center, United We Dream

Source: https://fightfortheftr.medium.com/letter-from-40-civil-society-organizations-ban-facial-recognition-on-college-campuses-3db826cc994c and https://georgetownlawtechreview.org/facial-recognition-systems-are-hitting-a-wall-of-opposition-on-college-campuses/GLTR-03-2020/
Source tier: primary
Source content: Letter dated February 13, 2020, "40+ organizations signed," addressed to "school administrators — at public and private grade schools, colleges, and universities"; all ten named organisations confirmed as signatories. Georgetown Law Tech Review: "Over forty civil liberties organizations, including the ACLU and Color of Change, signed on to an open letter condemning facial recognition on campus."
Comparison: Date, count, addressees, and every named signatory match (outcomes scalar + body § launch).
Decision: corroborated

## Claim 10: "Harvard, Columbia, the University of Michigan, Oberlin College, and UCLA subsequently issued non-use pledges/commitments"

Source: https://fightfortheftr.medium.com/students-rally-to-ban-facial-recognition-from-campus-a18899efb466 and https://georgetownlawtechreview.org/facial-recognition-systems-are-hitting-a-wall-of-opposition-on-college-campuses/GLTR-03-2020/ and https://www.insidehighered.com/news/2020/02/21/ucla-drops-plan-use-facial-recognition-security-surveillance-other-colleges-may-be
Source tier: primary
Source content: FFTF (3 March 2020): Oberlin "does not currently use nor is it currently considering the use of facial recognition systems," "joining over 60 other campuses like Harvard, MIT, and UCLA." Georgetown-era coverage: "More than 60 colleges—including... Columbia University, the University of Michigan... have said they won't use the technology." Inside Higher Ed: UCLA "the potential benefits are limited and are vastly outweighed by the concerns of the campus community" (February 2020).
Comparison: All five named schools are confirmed non-users across two independent source families (campaign scorecard/posts + press coverage).
Decision: corroborated

## Claim 11: July 2020 — New York State legislature passed the Biometric Identifying Technology in Schools Act, the first state moratorium on biometric surveillance technology in US schools

Source: https://www.washingtonpost.com/health/ny-lawmakers-vote-to-pause-facial-recognition-in-schools/2020/07/23/b59d240c-cd04-11ea-99b0-8426e26d203b_story.html and https://www.aclu.org/press-releases/new-york-creates-first-nation-moratorium-facial-recognition-schools and https://www.fightforthefuture.org/news/2020-07-23-victory-against-facial-recognition-in-new-york/
Source tier: mainstream
Source content: Washington Post (23 July 2020): "NY lawmakers vote to pause facial recognition in schools." ACLU/NYCLU: "New York Creates First-in-the-Nation Moratorium on Facial Recognition in Schools" (bill A6787-D/S5140-B). FFTF release confirms passage.
Comparison: July 2020 passage and first-in-nation status both corroborated. Note: fetched sources describe the bill as a moratorium/suspension (A6787-D/S5140-B, later Technology Law § 106-b); none uses the formal title "Biometric Identifying Technology in Schools Act" verbatim, though NYSED's 2023 determination is titled "on Biometric Identifying Technology in Schools" — the name is a reasonable rendering, not a contradiction.
Decision: corroborated

## Claim 12: scalar:outcomes — the July 2020 act followed "sustained coalition pressure from Fight for the Future, NYCLU, and EPIC"

Source: https://www.fightforthefuture.org/news/2020-07-23-victory-against-facial-recognition-in-new-york/ and https://epic.org/epic-coalition-urge-new-york-lawmakers-to-pass-biometric-recognition-bans/ (403 on direct fetch; surfaced via search snippet)
Source tier: primary
Source content: The entity's cited FFTF release features Fight for the Future prominently and references NYCLU's "Stop Student Surveillance 2019," but "EPIC is not mentioned." EPIC's own site carries "EPIC, Coalition Urge New York Lawmakers to Pass Biometric Recognition Bans" (date not confirmable this session — epic.org returns 403 on direct fetch) and EPIC signed the February 2020 administrators letter (which addressed schools, not Albany).
Comparison: FFTF and NYCLU pressure is well documented; EPIC's role in the Albany legislative push specifically is not confirmed by any source fetched this session, and the entity's own cited source (sources[3], the July 2020 release) does not name EPIC — the sources[3].note's "coalition of Fight for the Future, NYCLU, and EPIC credited" overstates that source's content. Not a correction: EPIC's involvement is plausibly real (its own site asserts NY advocacy) and there is no single-token replacement.
Decision: uncorroborated

## Claim 13: December 2020 — Governor Cuomo signed the moratorium into law

Source: https://www.governor.ny.gov/news/governor-cuomo-signs-legislation-suspending-use-and-directing-study-facial-recognition and https://www.forbes.com/sites/rachelsandler/2020/12/22/new-york-issues-first-in-nation-moratorium-on-facial-recognition-in-schools/
Source tier: primary
Source content: Governor's office release: "Governor Cuomo Signs Legislation Suspending Use and Directing Study of Facial Recognition Technology in Schools"; Forbes dated 22 December 2020.
Comparison: December 2020 signing confirmed by the governor's office (government record) and mainstream coverage.
Decision: corroborated

## Claim 14: The act established a two-year prohibition on school purchase/use of biometric technology and mandated a state study

Source: https://www.governor.ny.gov/news/governor-cuomo-signs-legislation-suspending-use-and-directing-study-facial-recognition and https://epic.org/new-york-enacts-law-suspending-use-of-facial-recognition-in-schools/ (search snippet)
Source tier: primary
Source content: "The moratorium placed restrictions on schools purchasing and using biometric identifying technology until at least July 1, 2022 or until the report was completed and the State Education Commissioner authorized its use, whichever occurred later"; the law "required the commissioner of education to evaluate the privacy implications of biometric identifying technology."
Comparison: Prohibition-plus-mandated-study confirmed; "two-year" matches the July 2020 passage → July 1, 2022 floor (with the whichever-is-later proviso the body's § moratorium prose in fact reflects: "before any authorisation to proceed").
Decision: corroborated

## Claim 15: 27 September 2023 — NYSED Commissioner Betty A. Rosa issued a determination permanently prohibiting all NY schools from purchasing or using facial recognition; schools may consider other biometric technologies subject to local assessment and input

Source: https://www.nysed.gov/news/2023/state-education-department-issues-determination-biometric-identifying-technology-schools
Source tier: primary
Source content: "Date: September 27, 2023. Issued by: Commissioner Betty A. Rosa. Schools in New York State are banned from purchasing or utilizing facial recognition technology... Schools may decide locally whether to use biometric identifying technology other than facial recognition, provided they evaluate the technology's privacy implications, civil rights impact, effectiveness, and solicit parental input."
Comparison: Date, issuer, scope of prohibition, and the other-biometrics carve-out all match (outcomes scalar + body § 2023). Also independently covered by K-12 Dive and StateScoop (search-surfaced).
Decision: corroborated

## Claim 16: The quoted study finding — "serious concerns do not outweigh claimed benefits" (outcomes scalar, sources[4].note, body § 2023)

Source: https://www.nysed.gov/news/2023/state-education-department-issues-determination-biometric-identifying-technology-schools
Source tier: primary
Source content: "Rosa concluded that 'serious concerns surrounding the use of facial recognition technology do not outweigh its claimed benefits.'"
Comparison: The entity renders the finding inside quotation marks as "serious concerns do not outweigh claimed benefits," dropping "surrounding the use of facial recognition technology" and "its" from the quoted string. Meaning is preserved but the quotation is not verbatim; single correct replacement is the source wording "serious concerns surrounding the use of facial recognition technology do not outweigh its claimed benefits" (or unquoted paraphrase). Fix locations: scalar `outcomes`, scalar `sources[4].note`, and body § "The 2023 permanent prohibition".
Decision: correction

## Claim 17: Lockport City School District "in late 2019 activated a facial recognition system" (body § Background)

Source: https://buffalonews.com/news/local/education/lockport-schools-activate-facial-recognition-system/article_df9722d4-b608-51ab-95b3-a8984cdacbf6.html and https://edscoop.com/lockport-city-facial-recognition-finally-activated-new-york-school-district/ and https://www.aclu.org/press-releases/new-york-creates-first-nation-moratorium-facial-recognition-schools
Source tier: mainstream
Source content: "The AEGIS system became operational on January 2, 2020, in conjunction with the return of students and staff from recess." ACLU: the Lockport face surveillance system "was first put into use in January 2020."
Comparison: Activation was January 2020 (2 January 2020), not late 2019 — late 2019 was NYSED's approval to proceed, not activation. Specific date token with a single correct replacement: "in late 2019" → "in January 2020". Fix location: body § "Background: the Lockport flashpoint and the schools track's origin".
Decision: correction

## Claim 18: The Lockport system was supplied by SN Technologies (AEGIS platform), scanning faces against a watch list, and was among the first K-12 school facial recognition activations in the US

Source: https://buffalonews.com/news/local/education/lockport-schools-activate-facial-recognition-system/article_df9722d4-b608-51ab-95b3-a8984cdacbf6.html and https://www.govtech.com/computing/aegis-software-turned-on-in-lockport-schools.html
Source tier: mainstream
Source content: "The system relies on the Aegis software suite created by Canadian-based SN Technologies... works by using a database of flagged individuals and sending an alert to district personnel when a flagged person is detected... Lockport became the first public school district in New York state and one of the first school districts in the country to start using facial recognition technology."
Comparison: Vendor, platform, watch-list mechanism, and among-first status all match.
Decision: corroborated

## Claim 19: "The New York Civil Liberties Union began pressing Albany for a state prohibition following the Lockport activation" (body § Background)

Source: https://www.fightforthefuture.org/news/2020-07-23-victory-against-facial-recognition-in-new-york/ and https://www.aclu.org/press-releases/new-york-creates-first-nation-moratorium-facial-recognition-schools
Source tier: mainstream
Source content: The FFTF release links NYCLU's publication "Stop Student Surveillance 2019"; ACLU/NYCLU materials and search-surfaced coverage document NYCLU opposition to Lockport (including a lawsuit "to revoke Lockport's ability to use the software before the moratorium was passed") beginning while the system was still pre-activation, with activation itself in January 2020.
Comparison: NYCLU's Albany advocacy is documented from 2019, i.e. before the January 2020 activation, so the sequencing "began pressing... following the activation" is not supported as stated; no single-token replacement (the sentence's trigger framing needs prose judgment — pressure followed Lockport's *deployment plans*, not its activation).
Decision: uncorroborated

## Claim 20: "The Lockport system... was by this point [September 2023] already decommissioned"

Source: https://epic.org/new-york-enacts-law-suspending-use-of-facial-recognition-in-schools/ (403 on direct fetch; surfaced via search snippet)
Source tier: database
Source content: "The school turned the technology off at the end of 2020."
Comparison: The system was shut off at the end of 2020 (as the December 2020 moratorium required), so it was indeed decommissioned well before the 2023 determination. Rests on one non-primary source surfaced by snippet.
Decision: single-source

## Claim 21: Fight for the Future launched banfacialrecognition.com in July 2019, calling for a moratorium/ban on government use of facial recognition

Source: https://www.commondreams.org/news/2019/07/09/we-need-ban-it-entirely-beyond-regulation-new-us-campaign-calls-moratorium-facial and https://www.commondreams.org/newswire/2019/07/09/fight-future-launches-major-new-campaign-calling-federal-ban-facial-recognition
Source tier: mainstream
Source content: "Fight for the Future's Ban Facial Recognition campaign launched in July 2019 and calls on local, state, and federal lawmakers to prevent government and law enforcement use of facial recognition... becoming the first national organization to call for a complete Federal ban on government use of facial recognition surveillance" (both dated 9 July 2019).
Comparison: July 2019 launch and moratorium/ban demand match (body § Background).
Decision: corroborated

## Claim 22: The parent campaign "drew more than 40 organizational endorsements" (body § Background)

Source: https://www.commondreams.org/news/2019/07/09/we-need-ban-it-entirely-beyond-regulation-new-us-campaign-calls-moratorium-facial and https://www.securityinfowatch.com/industry-news/article/53028009/battle-lines-drawn-over-facial-recognition-technology-as-lawmakers-revive-proposed-ban
Source tier: mainstream
Source content: Launch-era coverage describes ~30 groups initially; later coverage of the coalition describes "Indivisible, American Federation of Teachers, the American Civil Liberties Union, Public Citizen, MoveOn... and over 100 others."
Comparison: The 40+ figure is exceeded by the coalition's later documented size (100+), so the claim holds a fortiori, but no single fetched source states the 40+ count directly for the parent campaign; rests on the coalition-size description in one search-surfaced article. (The prior-pass audit of the parent campaign entity corroborated 40+ logos on banfacialrecognition.com.)
Decision: single-source

## Claim 23: 14 January 2020 — campus microsite (campus.banfacialrecognition.com) launched with student toolkit; George Washington University and DePaul University student groups among the first to file resolutions

Source: https://www.fightforthefuture.org/news/2020-01-14-students-activists-launch-nationwide-campaign-to/
Source tier: primary
Source content: "Microsite Launched: banfacialrecognition.com/campus with toolkit for student groups... George Washington University (DC) and DePaul University (Chicago) are cited as campuses 'organizing to introduce student government resolutions.'"
Comparison: Microsite-with-toolkit and the GWU/DePaul first-movers match, with two paraphrase-level notes: the release gives the URL as banfacialrecognition.com/campus (the entity writes campus.banfacialrecognition.com — likely equivalent forms, not verified), and the release says the groups were "organizing to introduce" resolutions where the body says "among the first to file." Neither is a contradiction with a single-token fix.
Decision: primary-sourced

## Claim 24: The campus microsite included a scorecard tracking which universities had committed to non-use, which were considering, and which had deployed

Source: https://www.fightforthefuture.org/news/2020-01-27-new-scorecard-shows-which-colleges-are-using/ and https://fightfortheftr.medium.com/students-rally-to-ban-facial-recognition-from-campus-a18899efb466
Source tier: primary
Source content: "New Scorecard Shows Which Colleges are Using Facial Recognition, and Which Say They Won't" (27 January 2020); "The scorecard marks answers by 'WON'T USE,' 'MIGHT USE,' and 'ARE USING.'"
Comparison: Scorecard existence and its three-way tracking match (body § launch + sources[7].note). Also reflected in Common Dreams newswire coverage.
Decision: corroborated

## Claim 25: September 2024 — Fight for the Future, Defending Rights & Dissent, and EPIC hand-delivered nearly 12,000 petition signatures to the US Department of Education; coordinated actions in California, Georgia, New York, and Washington DC

Source: https://www.fightforthefuture.org/news/2024-09-28-students-across-the-country-call-for-a-back-to-school-ban-on-facial-recognition/
Source tier: primary
Source content: "Fight for the Future, Defending Rights & Dissent, and Electronic Privacy Information Center (EPIC) hand-delivered nearly 12,000 petition signatures to the U.S. Department of Education" (Friday, September 27, 2024); actions in "California, Georgia, New York, and Washington D.C."
Comparison: Delivering organisations, signature count, recipient, and the four action locations all match (outcomes scalar + body § 2024). No independent second source fetched.
Decision: primary-sourced

## Claim 26: The campaign framed the Department of Education demand as an application of the Biden administration's 2023 Executive Order on AI, which included language on AI in education

Source: https://www.fightforthefuture.org/news/2024-09-28-students-across-the-country-call-for-a-back-to-school-ban-on-facial-recognition/
Source tier: primary
Source content: "Organizers called on the U.S. Department of Education to issue guidance advising schools to reject facial recognition technology, fulfilling responsibilities under the White House's Executive Order on AI development and use."
Comparison: The EO framing is directly stated in the campaign's release; the EO's education provisions are public record (the October 2023 EO directs education-sector AI resources).
Decision: primary-sourced

## Claim 27: August 2025 — Fight for the Future led a 41-organisation open letter to US university administrators (signatories incl. Amnesty International USA, EFF, CAIR, Center for Constitutional Rights, Freedom of the Press Foundation) with six demands, incl. dismantling ID swipe tracking, social media/online activity monitoring, license plate readers, motion sensors, WiFi location tracking, biometric exam proctoring, and refusing law-enforcement data sharing

Source: https://www.fightforthefuture.org/news/2025-08-19-universities-dismantle-surveillance-protect-free-speech/
Source tier: primary
Source content: "41 organizations listed," addressed "Dear university administrators and trustees"; named signatories include Amnesty International USA, EFF, Center for Constitutional Rights, Freedom of the Press Foundation, CAIR; six demand categories including "Refuse law enforcement data cooperation" and "This includes tools and practices such as ID swipe tracking, social media monitoring, facial recognition tools, license plate readers, motion and heat sensors, WiFi vendors that collect people's location data, and biometric online exam proctoring programs."
Comparison: Signatory count, all five named signatories, the six-demand structure, the technology list, and the law-enforcement data-sharing refusal all match (goals + outcomes scalars, body § 2025).
Decision: primary-sourced

## Claim 28: The 2025 escalation was triggered by the Trump administration's "documented use of campus surveillance systems to identify and target political protesters and international students" (goals scalar + body § 2025)

Source: https://www.fightforthefuture.org/news/2025-08-19-universities-dismantle-surveillance-protect-free-speech/
Source tier: primary
Source content: The letter states the Trump administration has "launched an aggressive campaign against US academic institutions, revoking international students' visas and threatening universities with funding cuts unless they agree to suppress speech on campus," and that "surveillance tools and the data they amass will be used to supercharge... attacks on campus communities."
Comparison: The letter documents the administration's campaign against universities and frames campus surveillance as the infrastructure that *will* supercharge those attacks — prospective framing in the fetched content, whereas the entity asserts *documented use* of campus surveillance systems for targeting as an established fact. The causal/contested framing needs a second canonical source not obtained this session. Scalar path: `goals`; also body § "The August 2025 campus surveillance escalation".
Decision: uncorroborated

## Claim 29: "No federal legislation had passed as of the research date" / no federal guidance had issued (outcomes scalar + body § 2024)

Source: https://www.fightforthefuture.org/news/2024-09-28-students-across-the-country-call-for-a-back-to-school-ban-on-facial-recognition/
Source tier: primary
Source content: The September 2024 release calls on the Department of Education "to issue guidance advising schools to reject facial recognition technology" — i.e., no such guidance existed as of September 2024 — and the campaign continued pressing through 2025.
Comparison: Negative-existence claim; consistent with the campaign's own continuing demands and with no fetched source indicating federal school-facial-recognition legislation or guidance since. Rests on inference from one source family.
Decision: single-source

## Claim 30: "New York remained the only US state with a permanent prohibition on facial recognition in schools" (outcomes scalar; body § Significance renders it as "first US state")

Source: https://www.nysed.gov/news/2023/state-education-department-issues-determination-biometric-identifying-technology-schools and https://www.cpomagazine.com/data-privacy/state-of-new-york-makes-moratorium-on-facial-recognition-technology-in-schools-permanent/
Source tier: mainstream
Source content: 2023 coverage establishes New York as the first state to make a school facial-recognition moratorium permanent ("State of New York Makes Moratorium on Facial Recognition Technology in Schools Permanent"); one search-surfaced summary noted "states such as California and Virginia also put some form of state-wide ban into place" (differing scopes, not school-specific permanence).
Comparison: "First" (2023) is supported; "only... as of the research date [mid-2026]" is a negative-existence claim no fetched source attests, and adjacent state bans of different scope make the uniqueness framing unconfirmable without a dedicated survey.
Decision: uncorroborated
