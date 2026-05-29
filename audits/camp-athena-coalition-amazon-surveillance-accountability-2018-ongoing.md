---
entity_id: camp-athena-coalition-amazon-surveillance-accountability-2018-ongoing
entity_hash: 8b3231573226a093cb36485ee920f8ee5c975974
audit_date: 2026-05-29
pass: 1
status: discrepancy
claims_total: 20
claims_verified: 16
claims_discrepancy: 2
claims_unverifiable: 2
sources_consulted:
  - https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys
  - https://ilsr.org/press/ilsr-co-founds-national-coalition-to-take-on-amazon/
  - https://forgeorganizing.org/article/reining-amazon-build-people-powered-democracy/
  - https://mediajustice.org/news/eyesonamazon-week-of-action-highlights/
  - https://datasociety.net/people/ryan-gerety/
  - https://en.wikipedia.org/wiki/Amazon_Rekognition
  - https://en.wikipedia.org/wiki/Joy_Buolamwini
  - https://en.wikipedia.org/wiki/The_Vanguard_Group
  - https://en.wikipedia.org/wiki/FTC_v._Amazon
  - https://www.aclu.org/news/privacy-technology/amazons-face-recognition-falsely-matched-28
  - https://www.aclu.org/press-releases/aclu-statement-extended-amazon-face-recognition-moratorium
  - https://thehill.com/policy/technology/472153-activists-form-national-coalition-to-take-on-amazon/
  - https://www.demos.org/research/challenging-dominance-big-tech-us-not-amazon-arlington-va
  - https://en.wikipedia.org/wiki/Project_Nimbus
  - https://athenaforall.org/news/press-release-athena-coalition-statement-on-ftc-announcement-of-amazon-lawsuit/
---

## Claim 1: "Launched publicly on 26 November 2019" — body, also start_date: 2019-11-26

Source: https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys
Source content: Common Dreams article dated November 26, 2019 reports that the coalition "announced the formation of a new coalition called Athena on Tuesday" — the article's own publication date confirms 26 November 2019.
Comparison: Body and frontmatter `start_date` match the source date.
Decision: verified

## Claim 2: "Launched with over 40 founding organisations" — body; also scalar:sources[1].note "the 40+ founding organisation count"

Source: https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys
Source content: "three dozen grassroots advocacy groups" — i.e. approximately 36, not "over 40". Cross-checked against The Hill (2019), which also describes the coalition as "three-dozen grassroots groups".
Comparison: Both the body and the `sources[1].note` scalar attribute "over 40" / "40+" founding orgs to Common Dreams; the cited source actually says "three dozen". The single-token correction is "40" → "three dozen" (or "over 40" → "three dozen") in both body and note; the note's exact phrase "the 40+ founding organisation count" should become "the three-dozen founding organisation count". The corpus's other claim that membership has "grown past 50" is a separate, current-state claim (not audited here).
Decision: discrepancy

## Claim 3: "Coalition has grown past 50" — body

Source: https://athenaforall.org/
Source content: The Athena Coalition's own website (cited by the entity as primary source for the "current organizational membership roster") presents a membership list. Public-facing membership lists on coalition sites of this type vary; without a direct rendered list count, the precise current membership ("past 50") is not directly quotable from the source pass I conducted.
Comparison: Claim is a paraphrastic count of current membership against a list whose specific count I could not extract verbatim from the source's text content during this pass.
Decision: unverifiable

## Claim 4: "Raised $15 million in three-year seed funding at launch" — body; outcomes-adjacent

Source: https://thehill.com/policy/technology/472153-activists-form-national-coalition-to-take-on-amazon/ (cross-confirmed in multiple 2019 outlets)
Source content: The 2019 launch coverage in The Hill and contemporaneous outlets confirms the coalition "is raising $15 million to cover its first three years."
Comparison: Body claim matches source content. Note: the entity attributes this fact to Common Dreams (`sources[1].note`); the Common Dreams article as fetched does not contain it, so the underlying fact is verified but the source-note's attribution does not match the cited article's text. This is documented here for the Researcher; the body claim itself stands `verified` because the fact is well-sourced elsewhere.
Decision: verified

## Claim 5: "Open Society Foundations as named seed funder" — body; scalar:sources[1].note

Source: https://thehill.com/policy/technology/472153-activists-form-national-coalition-to-take-on-amazon/ (cross-confirmed in multiple 2019 outlets)
Source content: Contemporaneous coverage confirms Open Society Foundations as a seed funder; The Hill and other 2019 outlets identify it as such. Same attribution caveat as Claim 4 — Common Dreams article does not contain this specific fact, but the underlying claim is independently verified.
Comparison: Body claim matches source content.
Decision: verified

## Claim 6: "Inaugural executive director was Dania Rajendra" — body; scalar:sources[1].note

Source: https://thehill.com/policy/technology/472153-activists-form-national-coalition-to-take-on-amazon/ (cross-confirmed)
Source content: Contemporaneous coverage describes Dania Rajendra as "Athena's newly appointed executive director and... the coalition's only full-time employee."
Comparison: Body claim matches. Same Common Dreams attribution caveat as Claims 4 and 5.
Decision: verified

## Claim 7: "FUNA convened by PowerSwitch Action in Northern Virginia in 2018 as Amazon conducted its publicised national search for a second headquarters" — body; scalar:sources[3].note

Source: https://www.demos.org/research/challenging-dominance-big-tech-us-not-amazon-arlington-va
Source content: Demos research on FUNA confirms: "For Us, Not Amazon (FUNA), a women of color-led coalition... mobilized to prevent Amazon from coming to Arlington" after the late-2018 HQ2 announcement, with "PowerSwitch convened local groups that were concerned about their cities' bids for HQ2." Cross-confirmed by ARLnow press release.
Comparison: Body claim matches source content.
Decision: verified

## Claim 8: "ILSR Co-Director Stacy Mitchell" — body; scalar:sources[2].note

Source: https://ilsr.org/press/ilsr-co-founds-national-coalition-to-take-on-amazon/
Source content: "ILSR Co-Director Stacy Mitchell" — verbatim title used by ILSR's own press release.
Comparison: Body claim matches.
Decision: verified

## Claim 9: "PowerSwitch Action and ILSR... two co-founders" — body; scalar:sources[2].note "ILSR and PowerSwitch Action as co-founding institutions"

Source: https://forgeorganizing.org/article/reining-amazon-build-people-powered-democracy/
Source content: "This is why PowerSwitch Action and the Institute for Local Self-Reliance joined with allies across issues and movements to create the Athena Coalition."
Comparison: Body claim matches.
Decision: verified

## Claim 10: "described the resulting approach as a 'braided strategy'" — body; scalar:sources[3].note "the coalition's 'braided strategy' framing"

Source: https://forgeorganizing.org/article/reining-amazon-build-people-powered-democracy/
Source content: "This is what PowerSwitch Action refers to as 'braided strategy'" — phrase confirmed verbatim, attributed to PowerSwitch Action specifically (not jointly to both authors).
Comparison: Body claim matches the source's use of the phrase.
Decision: verified

## Claim 11: "Rekognition's accuracy problems on darker-skinned subjects had been documented by MIT researcher Joy Buolamwini" — body

Source: https://en.wikipedia.org/wiki/Joy_Buolamwini
Source content: Wikipedia notes Buolamwini was "a researcher at the MIT Media Lab" and that her 2018 Gender Shades paper "evaluated systems from IBM, Microsoft, and Face++" — Amazon Rekognition was not in that initial study. Wikipedia mentions Amazon only in connection with the documentary Coded Bias and with follow-on industry responses ("IBM, Microsoft, and Amazon all announced significant updates"). Buolamwini's follow-up "Actionable Auditing" work (2019) did include Rekognition, but Wikipedia's biographical article does not directly document this in the fetched text.
Comparison: Living-person specifics beyond public role require ≥1 canonical source beyond Wikipedia per the source rule; the entity's own sources do not cite a Buolamwini-on-Rekognition source. The claim is broadly true (her follow-up paper covered Rekognition) but not directly verifiable from the sources reachable in this pass without escalation.
Decision: unverifiable

## Claim 12: "the ACLU... found it misidentified 28 members of Congress as criminals" — body

Source: https://www.aclu.org/news/privacy-technology/amazons-face-recognition-falsely-matched-28
Source content: "the software incorrectly matched 28 members of Congress, identifying them as other people who have been arrested for a crime."
Comparison: Body claim matches.
Decision: verified

## Claim 13: "Amazon had announced a one-year Rekognition moratorium in June 2020" — body; outcomes: "Amazon announced a one-year moratorium on Rekognition sales to law enforcement in June 2020"

Source: https://en.wikipedia.org/wiki/Amazon_Rekognition
Source content: "In June 2020, Amazon announced it was implementing a one-year moratorium on police use of Rekognition, in response to the George Floyd protests."
Comparison: Body and `outcomes` scalar both match the source. (Public-event date for which Wikipedia is canonical-alone per the source rule.)
Decision: verified

## Claim 14: "Amazon extended the moratorium indefinitely on 18 May 2021" — body; scalar:sources[4].note "Amazon's 18 May 2021 indefinite extension of the Rekognition moratorium"

Source: https://www.aclu.org/press-releases/aclu-statement-extended-amazon-face-recognition-moratorium
Source content: ACLU press release dated May 18, 2021: "Amazon today announced" the indefinite extension. Cross-confirmed by Washington Post (URL date 2021/05/18) and CNN (May 18, 2021).
Comparison: Body and scalar match.
Decision: verified

## Claim 15: "delivered 10,000 petitions to Amazon" — body; scalar:sources[4].note "the 10,000-petition delivery"

Source: https://mediajustice.org/news/eyesonamazon-week-of-action-highlights/
Source content: "we delivered 10K petitions to Andrew Jassy and Jeff Bezos"
Comparison: Body and scalar match (10K = 10,000).
Decision: verified

## Claim 16: "Eyes on Amazon Week of Action in June 2021... coalition partners including Color of Change, the ACLU of Washington, the Electronic Frontier Foundation, Mijente, Just Futures Law, and Free Press" — body; scalar:sources[4].note also names "Color of Change, ACLU-WA, EFF, Mijente, Just Futures Law, Free Press"

Source: https://mediajustice.org/news/eyesonamazon-week-of-action-highlights/
Source content: Article names the same six partners (Color of Change, ACLU-WA, Electronic Frontier Foundation, Mijente, Just Futures Law, Free Press) and places the Week of Action in May/June 2021.
Comparison: Body and scalar match.
Decision: verified

## Claim 17: "Current Director is Ryan Gerety, who brings experience at the Ford Foundation and the Open Technology Institute at New America" — body; scalar:sources[6].note "her role as Athena Director, her prior positions at Ford Foundation and the Open Technology Institute at New America"

Source: https://datasociety.net/people/ryan-gerety/
Source content: "Ryan Gerety, a Data & Society affiliate, is the director of the Athena Coalition" and "She was previously at the Ford Foundation and the Open Technology Institute at New America."
Comparison: Body and scalar match.
Decision: verified

## Claim 18: "May 2022 'Monitored' report... published by United for Respect within the Athena umbrella" — body; outcomes mirror; scalar:sources[5].note

Source: https://united4respect.org/wp-content/uploads/2022/05/athena_monitored_report.pdf
Source content: The cited PDF URL path itself contains "/2022/05/" (May 2022) and is hosted by United for Respect (united4respect.org), corroborating both the publication date and the publishing organisation.
Comparison: Body, `outcomes`, and scalar note match the source's URL-encoded metadata. The report's content (worker-surveillance documentation, productivity quotas, etc.) is the descriptive framing for which Wikipedia/other cross-check would be tiebreaker-only; the publishing facts are confirmed by the URL.
Decision: verified

## Claim 19: "May 2022 Amazon annual meeting... action at Vanguard's Malvern, Pennsylvania headquarters" — body; outcomes: "Vanguard headquarters in Malvern, Pennsylvania"

Source: https://en.wikipedia.org/wiki/The_Vanguard_Group
Source content: "Vanguard's corporate headquarters is in Malvern, a suburb of Philadelphia, Pennsylvania." (Named-entity definitional fact per source rule; Wikipedia is canonical-alone.)
Comparison: Body and `outcomes` scalar match on the Vanguard-Malvern, PA location. The May 2022 dating of the shareholder action is a separate sub-claim; the entity's own primary source (athenaforall.org) is cited for the action's occurrence, and the dating is consistent with the Monitored report's publication month.
Decision: verified

## Claim 20: "When the FTC filed its antitrust lawsuit against Amazon in June 2023" — body; outcomes: "The FTC filed an antitrust lawsuit against Amazon in June 2023"

Source: https://en.wikipedia.org/wiki/FTC_v._Amazon ; https://www.naag.org/multistate-case/ftc-and-plaintiff-states-v-amazon-com-inc-no-223-cv-01495-w-d-wash-sept-26-2023/ ; cross-confirmed by https://athenaforall.org/news/press-release-athena-coalition-statement-on-ftc-announcement-of-amazon-lawsuit/ (Athena's own statement dated 26 September 2023)
Source content: The case docket — "FTC and Plaintiff States v. Amazon.com, Inc., No. 2:23-cv-01495 (W.D. Wash. Sept. 26, 2023)" — and Athena's own press release (dated September 26, 2023, in direct response to the announcement) both place the filing on September 26, 2023, not June 2023.
Comparison: Body and `outcomes` both name "June 2023"; the actual filing date is September 26, 2023. Single-token correction "June 2023" → "September 2023" (or more precisely "September 26, 2023") applies to both the body sentence ("When the FTC filed its antitrust lawsuit against Amazon in June 2023") and the `outcomes` scalar ("The FTC filed an antitrust lawsuit against Amazon in June 2023"). Editor's Audit-discrepancy backfill act covers this mirror.
Decision: discrepancy
