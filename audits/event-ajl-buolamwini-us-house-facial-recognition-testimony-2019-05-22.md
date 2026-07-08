---
entity_id: event-ajl-buolamwini-us-house-facial-recognition-testimony-2019-05-22
entity_hash: 1c0801182f52ef26b6918a3036f0128888b5a5fe
audit_date: 2026-07-07
pass: 1
status: corrections-pending
claims_total: 29
claims_corroborated: 14
claims_primary_sourced: 3
claims_single_source: 3
claims_uncorroborated: 5
open_corrections: 4
sources_consulted:
  - https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
  - https://www.theregister.com/2019/05/22/congress_facial_recognition
  - https://medium.com/@Joy.Buolamwini/face-the-final-frontier-of-privacy-full-spoken-congressional-testimony-may-22-2019-ff8607df045b
  - https://www.ajl.org/about
  - https://proceedings.mlr.press/v81/buolamwini18a.html
  - https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology
  - https://www.npr.org/2019/05/14/723193785/san-francisco-considers-ban-on-governments-use-of-facial-recognition-technology
  - https://www.congress.gov/bill/116th-congress/senate-bill/847
  - https://www.govtrack.us/congress/bills/116/s847
  - https://oversight.house.gov/hearing/law-enforcements-use-facial-recognition-technology/
---

Type-shape note: Event is a connective type — claims audited are the edges (`campaign`, `participating_orgs`, `participating_people`) and hard specifics (date, location, witnesses, figures, quoted attributions, downstream legislative facts). Significance prose without a hard specific ("marked the entry of", "one of the first times the US Congress heard directly from an algorithmic-auditing researcher" [hedged], "seeded regulatory response", "a wave of legislative activity") received no decision.

## Claim 1: hearing occurred 22 May 2019, Washington, D.C., before the House Committee on Oversight and Reform, as congressional testimony (frontmatter `date`, `location`, `event_type` + body)

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: GPO official transcript: "House Committee on Oversight and Reform, chaired by Rep. Elijah E. Cummings (D-MD)", May 22, 2019; The Register: "The House Committee on Oversight and Reform held the hearing on Wednesday, May 22, 2019."
Comparison: Date, venue, committee, and event type all match the official transcript and contemporaneous coverage. Scalar paths `date`, `location`, `event_type` all confirmed.
Decision: corroborated

## Claim 2: hearing titled "Facial Recognition Technology (Part 1): Its Impact on Our Civil Rights and Liberties," convened under Committee Chair Rep. Elijah Cummings

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript title: "Facial Recognition Technology: Part I Its Impact on Our Civil Rights and Liberties"; "chaired by Rep. Elijah E. Cummings (D-MD)". Register: "chaired by Elijah Cummings".
Comparison: Title and chair match (transcript renders "Part I" where body renders "(Part 1)" — same title, formatting variance only).
Decision: corroborated

## Claim 3: edge `campaign: camp-fight-for-the-future-ban-frt-us-cities-2019-ongoing` (scalar:campaign)

Source: no canonical source found
Source tier: none
Source content: Campaign entity (in-corpus) reciprocates — its `events:` lists this event and its `lead_orgs:` includes org-algorithmic-justice-league — but its `start_date: 2019-07-09` postdates the 22 May 2019 testimony by seven weeks.
Comparison: scalar:campaign — no external source ties this testimony to the Fight for the Future campaign, which launched 2019-07-09, after the event; whether a pre-launch event belongs under the campaign is a corpus-modeling judgment, not a factual token with a single correct replacement. The edge target exists and reciprocates.
Decision: uncorroborated

## Claim 4: edges `participating_orgs: [org-algorithmic-justice-league, org-aclu]`, `participating_people: [person-joy-buolamwini]`

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript witness list: "Joy Buolamwini, Founder, Algorithmic Justice League"; "Neema Singh Guliani, Senior Legislative Counsel, American Civil Liberties Union". Register names both.
Comparison: Both organizations were represented by testifying witnesses and Buolamwini testified in person; edges point to the correct entities.
Decision: corroborated

## Claim 5: Buolamwini is "founder and president" of the Algorithmic Justice League

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript: "Joy Buolamwini, Founder, Algorithmic Justice League". AJL about page: "Founder of the Algorithmic Justice League". Search results attribute "Artist-in-Chief and President" only to non-canonical bios (DataCamp podcast, theorg.com).
Comparison: "Founder" is primary-confirmed; "president" found only in non-canonical sources this session (living-person title beyond public role requires primary/mainstream). Partial confirmation, not a contradiction.
Decision: uncorroborated

## Claim 6: "the first congressional hearing dedicated to the civil-rights and civil-liberties implications of facial recognition technology" (repeated as "the first congressional panel to convene witnesses specifically on the civil-rights dimension" and "the first US congressional hearing dedicated to the civil-rights impact")

Source: https://oversight.house.gov/hearing/law-enforcements-use-facial-recognition-technology/
Source tier: none
Source content: House Oversight held "Law Enforcement's Use of Facial Recognition Technology" on March 22, 2017, which per the committee page examined FBI FRT use including that "FRT has accuracy deficiencies, misidentifying female and African American individuals at a higher rate."
Comparison: Contested "first" claim — no canonical source found asserting the first-dedicated-hearing framing, and a 2017 House Oversight FRT hearing covering bias and civil-liberties concerns exists; whether "dedicated to" distinguishes the 2019 hearing is judgment-loaded. Not a correction (no single correct replacement; the 2019 hearing was the first of its titled "Part I" series).
Decision: uncorroborated

## Claim 7: Gender Shades findings were presented at the hearing / entered testimony before the committee

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript records Buolamwini's error-rate and dataset-composition findings ("no more than 1 percent for lighter-skinned men" versus "over 30 percent for darker-skinned women"); Register: Buolamwini "presented research showing commercial models 'struggled most when it came to recognizing women with darker skin'".
Comparison: The research findings were presented in her testimony per both the transcript and contemporaneous coverage.
Decision: corroborated

## Claim 8: "the first time Gender Shades-derived findings appeared in the congressional record"

Source: no canonical source found
Source tier: none
Source content: No fetched source asserts this priority claim; only the entity's own Wikipedia source note frames the testimony as "the translation of Gender Shades research into formal legislative record" (Wikipedia is tiebreaker-only for contested firsts).
Comparison: Contested "first" attribution with no non-Wikipedia canonical support found; plausible but unasserted by any consulted source.
Decision: uncorroborated

## Claim 9: Gender Shades published roughly a year earlier by Buolamwini and Timnit Gebru, auditing commercial facial-analysis products from IBM, Microsoft, and Megvii, documenting accuracy disparities by skin type and gender

Source: https://proceedings.mlr.press/v81/buolamwini18a.html
Source tier: primary
Source content: PMLR: "Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification" by Joy Buolamwini and Timnit Gebru, PMLR 81:77-91, 2018. WGBH (2018-03-21): "The study examined facial recognition systems from IBM, Microsoft, and Face++ (China-based)."
Comparison: Authors, 2018 publication, three companies (Face++ is Megvii's product), and disparity findings all match. "Roughly a year" before May 2019 is loose (published Feb 2018, ~15 months) but within the body's own hedge.
Decision: corroborated

## Claim 10: "The study's findings had already prompted IBM to update its product"

Source: https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology
Source tier: mainstream
Source content: WGBH: IBM "recreated her study and asked her to audit their system"; IBM's accuracy improved "from approximately 65% to around 96% (self-reported)".
Comparison: Supported by one mainstream source. Note: the body cites ajl.org/about for this claim, but that page (fetched) carries nothing about IBM updating its product — the supporting source is elsewhere.
Decision: single-source

## Claim 11: "Six witnesses appeared: Buolamwini …, Clare Garvie …, Cedric Alexander …, Michael Punke (Amazon's Vice President of Global Public Policy), Neema Guliani …, and Andrew Ferguson"

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Official transcript witness list has five witnesses: Buolamwini, Ferguson, Garvie, Guliani, Alexander — "No one from Amazon testified." Register references Punke "for a separate statement rather than as a hearing witness" (his claim that Amazon "has not received a single report of misuse by law enforcement").
Comparison: The official transcript records five witnesses; Michael Punke did not appear — the Register quoted his Rekognition defense as a separate statement. Correct replacement: five witnesses, dropping Punke from the list (his statement may be cited separately). Two tokens change ("Six"→"Five", remove Punke), so likely a Researcher prose-judgment fix rather than a single Editor replacement.
Decision: correction

## Claim 12: witness identities/affiliations — Clare Garvie (Georgetown Law Center on Privacy and Technology), Cedric Alexander (former president, National Organization of Black Law Enforcement Executives), Neema Guliani (ACLU, Senior Legislative Counsel), Andrew Ferguson (law professor, University of the District of Columbia)

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript: "Clare Garvie, Senior Associate, Center on Privacy & Technology, Georgetown University Law Center; Neema Singh Guliani, Senior Legislative Counsel, American Civil Liberties Union; Dr. Cedric Alexander, Former President, National Organization of Black Law Enforcement Executives; Andrew G. Ferguson, Professor of Law, University of the District of Columbia."
Comparison: All four names, roles, and affiliations match the transcript; Register corroborates the names.
Decision: corroborated

## Claim 13: written testimony submitted under the title "Face: The Final Frontier of Privacy"

Source: https://medium.com/@Joy.Buolamwini/face-the-final-frontier-of-privacy-full-spoken-congressional-testimony-may-22-2019-ff8607df045b
Source tier: primary
Source content: Her own post: "Face: The Final Frontier of Privacy — Full Spoken Congressional Testimony May 22, 2019".
Comparison: Title matches her own published testimony (the cited docs.house.gov PDF would confirm the written version's exact title but returned HTTP 403 on direct fetch). One primary source.
Decision: primary-sourced

## Claim 14: as a graduate student she was unable to get facial-detection software to register her face until she put on a white mask

Source: https://medium.com/@Joy.Buolamwini/face-the-final-frontier-of-privacy-full-spoken-congressional-testimony-may-22-2019-ff8607df045b
Source tier: primary
Source content: Medium: "Personally, I've had to resort to literally wearing a white mask to have my face detected by some of this technology." Transcript: "I have had to resort to literally wearing a white mask to have my face detected."
Comparison: Confirmed in both her own testimony post and the official transcript.
Decision: corroborated

## Claim 15: IBM's facial-analysis system was incorrect 34.7% of the time for darker-skinned women, versus under 1% for lighter-skinned men

Source: https://proceedings.mlr.press/v81/buolamwini18a.html
Source tier: primary
Source content: PMLR abstract: "darker-skinned females are the most misclassified group (with error rates of up to 34.7%)" while "the maximum error rate for lighter-skinned males is 0.8%". Register: "IBM's system was incorrect for 34.7 per cent of the time when it came to identifying black women." Transcript: "no more than 1 percent for lighter-skinned men" versus "over 30 percent for darker-skinned women".
Comparison: Figures match across the paper, the Register's attribution to IBM, and the testimony transcript.
Decision: corroborated

## Claim 16: "a gap she attributed to training datasets that were 75% male and 80% lighter-skinned"

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript: the 75%/80% figure describes a "NIST benchmark dataset: '75 percent male and 80 percent lighter skin'". Medium: "One prominent NIST dataset was 75% male and 80% lighter skinned."
Comparison: Both primary sources attach the 75%/80% composition to a NIST benchmark (evaluation) dataset, not to training datasets — the body's own adjacent quote ("the gold standard benchmark dataset is biased") says the same. Single replacement: "training datasets" → "a prominent NIST benchmark dataset".
Decision: correction

## Claim 17: quote — she named "the gold standard benchmark dataset is biased and can lead to a false understanding of progress"

Source: https://www.theregister.com/2019/05/22/congress_facial_recognition
Source tier: mainstream
Source content: Register: "The gold standard benchmark dataset is biased and can lead to a false understanding of progress."
Comparison: Quote matches verbatim in one specialist outlet with editorial standards (topic in beat); not independently confirmed in the transcript fetch this session.
Decision: single-source

## Claim 18: Amazon's Rekognition failed to correctly identify Oprah Winfrey's face, labelling her as male

Source: https://medium.com/@Joy.Buolamwini/face-the-final-frontier-of-privacy-full-spoken-congressional-testimony-may-22-2019-ff8607df045b
Source tier: primary
Source content: Medium: Rekognition "even failed on the face of Oprah Winfrey, labeling her male." Transcript: Amazon facial recognition "failed on the face of Oprah Winfrey, labeling her male."
Comparison: Confirmed in both her testimony post and the official transcript.
Decision: corroborated

## Claim 19: a Brown University student was misidentified as a terrorism suspect and subsequently received death threats

Source: https://medium.com/@Joy.Buolamwini/face-the-final-frontier-of-privacy-full-spoken-congressional-testimony-may-22-2019-ff8607df045b
Source tier: primary
Source content: Medium: "a Brown university senior preparing for finals was misidentified as a terrorist suspect in the Sri Lanka Easter bombings … She received death threats and her family was put at risk." Transcript: Brown University senior "misidentified as a terror suspect in the Sri Lanka Easter bombings".
Comparison: Misidentification and death threats both confirmed by her testimony; transcript corroborates the misidentification.
Decision: corroborated

## Claim 20: three-part policy ask — (1) moratorium on law-enforcement use of facial recognition/facial-analysis, (2) mandatory disclosure by federal agencies and federally funded organisations of face-based technology use, (3) stricter consent requirements for biometric data collection by commercial platforms

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript: "(a) moratorium on police facial recognition use; (b) mandatory disclosure by all Federal agencies using face-based technologies; (c) affirmative consent requirements for facial data collection". Medium confirms the same three, including "organizations using federal funding must disclose".
Comparison: All three asks match across the official transcript and her own testimony post.
Decision: corroborated

## Claim 21: the moratorium was asked for "pending adoption of regulations developed in partnership with affected communities"

Source: no canonical source found
Source tier: none
Source content: Neither the transcript fetch nor the Medium post fetch returned this qualifier; the cited written-testimony PDF (docs.house.gov) returned HTTP 403 on direct fetch this session.
Comparison: The qualifier is attributed to the written testimony, which could not be fetched; not contradicted, but not confirmable this session.
Decision: uncorroborated

## Claim 22: the ACLU's Guliani made aligned recommendations, framing the moratorium as necessary given "the capacity for abuse, lack of oversight, and technical immaturity"

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript: "At a minimum, Congress should pass a moratorium on the police use of facial recognition as the capacity for abuse, lack of oversight, and technical immaturity poses too great a risk."
Comparison: Quote and aligned moratorium recommendation confirmed by the official transcript.
Decision: primary-sourced

## Claim 23: "San Francisco's city-wide ban on government use of the technology passed two weeks later, in June 2019"

Source: https://www.npr.org/2019/05/14/723193785/san-francisco-considers-ban-on-governments-use-of-facial-recognition-technology
Source tier: mainstream
Source content: NPR (via search snippet; dated 2019-05-14): "On May 14, 2019, San Francisco banned the use of facial recognition software by the police and other agencies. The city's Board of Supervisors voted 8-1 on the measure."
Comparison: The Board of Supervisors passed the ban on 14 May 2019 — eight days BEFORE the 22 May hearing, not "two weeks later, in June 2019". Both tokens wrong (direction and month). Correct replacement: "had passed the week before, on 14 May 2019" — note this also breaks the sentence's "directly preceded" framing, so the fix needs Researcher prose judgment.
Decision: correction

## Claim 24: "the US Senate and House introduced the Commercial Facial Recognition Privacy Act and related legislation in the same congressional session"

Source: https://www.congress.gov/bill/116th-congress/senate-bill/847
Source tier: primary
Source content: Congress.gov/GovTrack (via search snippets): "S.847, the Commercial Facial Recognition Privacy Act of 2019, was introduced on March 14, 2019, by Senators Roy Blunt (R-Mo.) and Brian Schatz (D-Hawaii)" in the 116th Congress.
Comparison: The Act (a Senate bill) was introduced in the same congressional session (116th) — literally true as hedged. Note: introduction (March 2019) predates the hearing, so it sits awkwardly under the sentence's "the hearing directly preceded" framing; that framing is interpretation, not a token error.
Decision: corroborated

## Claim 25: scalar:sources[0].note — written testimony "Face the Final Frontier of Privacy," May 22 2019, primary source for the three-part recommendations and AJL representation

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Transcript confirms the three recommendations and "Joy Buolamwini, Founder, Algorithmic Justice League"; Medium post title: "Face: The Final Frontier of Privacy".
Comparison: scalar:sources[0].note — the note's factual content (title, date, three recommendations, AJL representation) matches the transcript and her own testimony post; the PDF itself 403s on direct fetch but its described content is corroborated.
Decision: corroborated

## Claim 26: scalar:sources[1].note — Medium post includes white-mask narrative, Oprah misidentification, Brown student death threats, moratorium and disclosure calls

Source: https://medium.com/@Joy.Buolamwini/face-the-final-frontier-of-privacy-full-spoken-congressional-testimony-may-22-2019-ff8607df045b
Source tier: primary
Source content: Fetched post confirms every listed element (white mask, Oprah/Rekognition, Brown senior with death threats, moratorium/disclosure recommendations).
Comparison: scalar:sources[1].note — accurate description of the fetched source; transcript corroborates the same content.
Decision: corroborated

## Claim 27: scalar:sources[2].note — GPO official transcript of the full hearing confirms committee, chair, all witnesses, and proceedings

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Fetched transcript carries hearing title, committee, Chair Cummings, and the witness list.
Comparison: scalar:sources[2].note — accurate description of the transcript's contents.
Decision: primary-sourced

## Claim 28: scalar:sources[3].note — "The Register contemporaneous coverage … lists all six witnesses and summarises key testimony"

Source: https://www.govinfo.gov/content/pkg/CHRG-116hhrg36663/html/CHRG-116hhrg36663.htm
Source tier: primary
Source content: Official transcript lists five witnesses, none from Amazon; the Register fetch shows Punke "referenced for a separate statement rather than as a hearing witness."
Comparison: scalar:sources[3].note — the note asserts six witnesses; the primary record has five (the Register's sixth name, Punke, was quoted separately, not a witness). Correct replacement in the scalar: "lists the witnesses" or "five witnesses". Fix location: frontmatter sources[3].note (the theregister.com entry).
Decision: correction

## Claim 29: scalar:sources[4].note — Wikipedia entry for Buolamwini places the 2019 House testimony in her career arc

Source: https://en.wikipedia.org/wiki/Joy_Buolamwini
Source tier: tiebreaker
Source content: Search snippet of the Wikipedia entry: "in 2019, she testified before the United States House Committee on Oversight and Reform about the risks of facial recognition technology."
Comparison: scalar:sources[4].note — Wikipedia does cover the 2019 testimony as described; the note itself frames Wikipedia as secondary cross-check, consistent with its tiebreaker role.
Decision: single-source
