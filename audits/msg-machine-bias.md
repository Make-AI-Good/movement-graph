---
entity_id: msg-machine-bias
entity_hash: 8ffe5a0e2c2ddc2941ae102e699cf0a8600b9e17
audit_date: 2026-09-16
pass: 1
status: corrections-pending
claims_total: 19
claims_corroborated: 6
claims_primary_sourced: 9
claims_single_source: 1
claims_uncorroborated: 1
open_corrections: 2
sources_consulted:
  - https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
  - https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm
  - https://www.propublica.org/article/bias-in-criminal-risk-scores-is-mathematically-inevitable-researchers-say
  - https://www.propublica.org/article/wisconsin-court-warning-labels-needed-scores-rating-risk-future-crime
  - https://www.propublica.org/series/machine-bias
  - https://www.propublica.org/awards/pulitzer-prize-finalist-explanatory-reporting
  - https://caselaw.findlaw.com/court/wi-supreme-court/1742124.html
  - https://en.wikipedia.org/wiki/Loomis_v._Wisconsin
  - https://www.eff.org/deeplinks/2020/12/questions-remain-about-pretrial-risk-assessment-algorithms-year-review-2020
  - https://privacyinternational.org/examples/1801/propublica-analysis-finds-bias-compas-criminal-justice-risk-scoring-system
  - https://proceedings.mlr.press/v81/buolamwini18a.html
  - http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf
  - https://www.pulitzer.org/finalists/julia-angwin-jeff-larson-surya-mattu-lauren-kirchner-and-terry-parris-jr-propublica
  - https://equivant-court.com/the-history-of-equivant-a-story-of-growth-and-a-commitment-to-simplify-justice/
---

## Claim 1: Published 23 May 2016 by ProPublica reporters Julia Angwin, Jeff Larson, Surya Mattu, and Lauren Kirchner under the headline "Machine Bias: There's Software Used Across the Country to Predict Future Criminals. And It's Biased Against Blacks." (also scalar:origin)

Source: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
Source tier: primary
Source content: "Machine Bias" / "There's software used across the country to predict future criminals. And it's biased against blacks." — "By Julia Angwin, Jeff Larson, Surya Mattu and Lauren Kirchner, ProPublica, May 23, 2016"
Comparison: Headline, subhead, all four bylines, and date match the article itself — the framing's foundational document.
Decision: primary-sourced

## Claim 2: COMPAS = Correctional Offender Management Profiling for Alternative Sanctions, developed by Northpointe (later Equivant), used by US courts to score defendants at bail, sentencing, and parole (also scalar:origin)

Source: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing + https://equivant-court.com/the-history-of-equivant-a-story-of-growth-and-a-commitment-to-simplify-justice/ (rebrand release: CourtView + Constellation Justice Systems + Northpointe → equivant, 9 Jan 2017, via search)
Source tier: primary
Source content: "Correctional Offender Management Profiling for Alternative Sanctions"; scores inform pretrial release/bail, sentencing recommendations, and parole eligibility across multiple states; "Northpointe, Inc. … Announce Company Rebrand to equivant" (Jan 2017).
Comparison: Acronym expansion, developer, later-Equivant rename, and the bail/sentencing/parole usage all match; rename corroborated by equivant's own history page and the Jan 2017 rebrand press release.
Decision: corroborated

## Claim 3: Team obtained COMPAS scores for more than 7,000 people arrested in Broward County, Florida in 2013 and 2014, matched against two-year follow-up records; Broward chosen as a large COMPAS-using jurisdiction under Florida's strong open-records laws (also scalar:origin, scalar:sources[1].note)

Source: https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm
Source tier: primary
Source content: "Through a public records request, ProPublica obtained two years worth of COMPAS scores from the Broward County Sheriff's Office in Florida"; "more than 7,000 people arrested in Broward County, Florida, in 2013 and 2014"; chosen because "it is a large jurisdiction using the COMPAS tool in pretrial release decisions and Florida has strong open-records laws."
Comparison: Count, county, arrest years, two-year follow-up, and selection rationale all match. Terminology nuance, not a correction: the source says "public records request" (Florida open-records), while the origin scalar and body § Origin say "FOIA requests" — colloquial extension of FOIA to a state records request; mechanism matches.
Decision: primary-sourced

## Claim 4: Black defendants who did not reoffend were nearly twice as likely to be falsely labeled high-risk as white defendants (45 percent vs. 23 percent) (also scalar:origin, scalar:sources[0].note)

Source: https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm
Source tier: primary
Source content: "black defendants who did not recidivate over a two-year period were nearly twice as likely to be misclassified as higher risk compared to their white counterparts (45 percent vs. 23 percent)." (Main article table: 44.9% vs. 23.5%.)
Comparison: Figures and "nearly twice as likely" framing match ProPublica's own rounded presentation exactly.
Decision: primary-sourced

## Claim 5: White defendants who did reoffend were nearly twice as likely to be incorrectly labeled low-risk "(48 percent vs. 25 percent)" (body § Origin and scalar:origin; scalar:sources[0].note says "white defendants 48% vs. Black defendants 25%")

Source: https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm
Source tier: primary
Source content: "White defendants who re-offended within the next two years were mistakenly labeled low risk almost twice as often as black re-offenders (48 percent vs. 28 percent)." (Main article table: 47.7% vs. 28.0%.)
Comparison: The white-defendant figure (48%) matches, but the Black-defendant figure is wrong in all three locations — body § Origin, scalar:origin, and scalar:sources[0].note say 25 percent; both ProPublica pieces say 28 percent (28.0%). Single-token fix: 25 → 28 in each location.
Decision: correction

## Claim 6: The algorithm's overall prediction for violent recidivism was wrong 80 percent of the time (also scalar:sources[0].note)

Source: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
Source tier: primary
Source content: "Only 20 percent of the people predicted to commit violent crimes actually went on to do so."
Comparison: 80% error rate is the direct complement of the article's 20% figure for violent-recidivism predictions; matches.
Decision: primary-sourced

## Claim 7: COMPAS score derived from a 137-item questionnaire (body: "137-item questionnaire"; scalar:sources[1].note: "137-question structure")

Source: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
Source tier: primary
Source content: "Northpointe's core product is a set of scores derived from 137 questions that are either answered by defendants or pulled from criminal records."
Comparison: 137 matches. Minor note attribution slip (no fix needed): sources[1].note attributes the 137 figure to the methodology piece, but the sentence lives in the main article; the number itself is correct.
Decision: primary-sourced

## Claim 8: COMPAS generates a 1–10 recidivism risk score

Source: https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm
Source tier: primary
Source content: "COMPAS scores for each defendant ranged from 1 to 10, with ten being the highest risk."
Comparison: Scale matches.
Decision: primary-sourced

## Claim 9: Northpointe responded formally, defending COMPAS as "equally accurate" across racial groups in a calibration sense; "Northpointe published a formal rejoinder" (body § Origin and § Why it has carried)

Source: https://www.propublica.org/article/bias-in-criminal-risk-scores-is-mathematically-inevitable-researchers-say + Dieterich/Mendoza/Brennan, "COMPAS Risk Scales: Demonstrating Accuracy Equity and Predictive Parity" (Northpointe, 2016; title via search)
Source tier: mainstream
Source content: "A test that is correct in equal proportions for all groups cannot be biased, the company said"; Northpointe called the test "racially neutral," citing ~60% accuracy "the same for black and white defendants"; its formal response is titled "Demonstrating Accuracy Equity and Predictive Parity."
Comparison: The substance — a formal Northpointe rejoinder defending equal calibration/predictive accuracy across races — is well supported. But the in-quotes phrase "equally accurate" could not be confirmed as verbatim Northpointe wording in any source fetched this session (ProPublica's Dec 2016 article does not contain the phrase; Northpointe's own vocabulary is "accuracy equity" / "predictive parity"; "equally accurate" appears only in secondary glosses). Too paraphrastic to compare as a quotation.
Decision: uncorroborated

## Claim 10: "Researchers Alexandra Chouldechova and Jon Kleinberg, Sendhil Mullainathan, and Astrid Luca Smola independently proved" the impossibility result (body § The core argument)

Source: https://www.propublica.org/article/bias-in-criminal-risk-scores-is-mathematically-inevitable-researchers-say
Source tier: mainstream
Source content: The article credits Alexandra Chouldechova (Carnegie Mellon) and the Cornell/Harvard group of Jon Kleinberg, Manish Raghavan, and Sendhil Mullainathan (plus Stanford and Srebro/Hardt/Price groups). No person named "Astrid Luca Smola" appears in the article or in the authorship of "Inherent Trade-Offs in the Fair Determination of Risk Scores" (Kleinberg, Mullainathan, Raghavan).
Comparison: "Astrid Luca Smola" is a confabulated name — the third author of the Kleinberg–Mullainathan paper is Manish Raghavan, as the entity's own sources[6].note correctly states. Single-token fix in body § The core argument: "Astrid Luca Smola" → "Manish Raghavan".
Decision: correction

## Claim 11: The impossibility result — error-rate equality and calibration equality cannot simultaneously hold across groups with differing base rates — emerged within months of publication, by Chouldechova (2017) and Kleinberg, Mullainathan, and Raghavan (2016) (also scalar:sources[6].note)

Source: https://www.propublica.org/article/bias-in-criminal-risk-scores-is-mathematically-inevitable-researchers-say + https://journals.sagepub.com/doi/abs/10.1089/big.2016.0047 (Chouldechova, Big Data 2017, record via search)
Source tier: mainstream
Source content: "a risk score could either be equally predictive or equally wrong for all races — but not both" (ProPublica, 30 Dec 2016, seven months after publication); Chouldechova, "Fair Prediction with Disparate Impact" (Big Data, 2017); Kleinberg/Mullainathan/Raghavan preprint 2016.
Comparison: Result content, independence of the proofs, the within-months timing (May → Sept/Oct arXiv, Dec 2016 ProPublica coverage), and the note's year attributions all match.
Decision: corroborated

## Claim 12: Eric Loomis challenged his six-year sentence on due-process grounds (proprietary algorithm he could not contest); the Wisconsin Supreme Court upheld COMPAS use in July 2016, barred use of the score as a determinative factor, and mandated a five-part warning in presentence reports (also scalar:sources[4].note)

Source: https://caselaw.findlaw.com/court/wi-supreme-court/1742124.html + https://www.propublica.org/article/wisconsin-court-warning-labels-needed-scores-rating-risk-future-crime
Source tier: primary
Source content: Opinion dated July 13, 2016; ¶100 enumerates five cautions the written advisement must list (proprietary nature; group-not-individual data; studies raising minority-classification questions; no Wisconsin cross-validation / re-norming need; developed for corrections, not sentencing); "risk scores may not be used as the determinative factor" (¶98). ProPublica: Loomis received six years imprisonment; his argument targeted "an opaque algorithm that generated a score he couldn't directly challenge."
Comparison: July 2016 date, six-year sentence, due-process argument, non-determinative rule, and exactly five enumerated cautions all match the opinion text (primary court record) and ProPublica coverage.
Decision: corroborated

## Claim 13: The U.S. Supreme Court declined to hear the appeal in June 2017 (also scalar:sources[5].note)

Source: https://en.wikipedia.org/wiki/Loomis_v._Wisconsin
Source tier: tiebreaker
Source content: "June 26, 2017" is when the Supreme Court denied the writ of certiorari.
Comparison: Cert-denial date matches; a court-action date is in the Wikipedia-alone-sufficient class, so one source passes, but no second canonical source was fetched this session.
Decision: single-source

## Claim 14: The project was a 2017 Pulitzer Prize finalist for Explanatory Reporting, credited to Angwin, Larson, Mattu, Kirchner, and Terry Parris Jr. (also scalar:sources[3].note)

Source: https://www.propublica.org/awards/pulitzer-prize-finalist-explanatory-reporting + https://www.pulitzer.org/finalists/julia-angwin-jeff-larson-surya-mattu-lauren-kirchner-and-terry-parris-jr-propublica (403 on direct fetch; naming via search-index title)
Source tier: primary
Source content: "Pulitzer Prize Finalist, Explanatory Reporting — 2017 … April 10, 2017 … 'Machine Bias' — 'the hidden power of computer-driven algorithms, from the advertisements we see to decisions made in the criminal justice system'"; Pulitzer page title: "Julia Angwin, Jeff Larson, Surya Mattu, Lauren Kirchner and Terry Parris Jr. of ProPublica | The Pulitzer Prizes".
Comparison: Category, year, and all five names match across the Pulitzer register and ProPublica's award page; sources[3].note's "April 2017" corresponds to the April 10, 2017 finalist announcement.
Decision: corroborated

## Claim 15: EFF adopted the framing in sustained work against pretrial risk assessment tools, finding such tools do not create fair pretrial systems (edge: propagated_by_orgs → org-electronic-frontier-foundation; also scalar:sources[7].note)

Source: https://www.eff.org/deeplinks/2020/12/questions-remain-about-pretrial-risk-assessment-algorithms-year-review-2020
Source tier: primary
Source content: "Questions Remain About Pretrial Risk-Assessment Algorithms: Year in Review 2020"; "EFF believed this proposition—no matter its outcome—does not create a fair pretrial system"; the piece cites COMPAS racial-misclassification research.
Comparison: EFF's own publication carries the cited finding and sustained pretrial-risk-assessment advocacy grounded in algorithmic racial-bias evidence. Edge target `org-electronic-frontier-foundation.md` exists. (The piece does not use the literal phrase "machine bias"; the framing-adoption gloss is proportionate.)
Decision: primary-sourced

## Claim 16: Privacy International catalogued the ProPublica findings as a canonical reference case for algorithmic bias in criminal justice (also scalar:sources[8].note)

Source: https://privacyinternational.org/examples/1801/propublica-analysis-finds-bias-compas-criminal-justice-risk-scoring-system
Source tier: primary
Source content: "ProPublica analysis finds bias in COMPAS criminal justice risk scoring system" — an entry in PI's examples database of algorithmic harms, tagged AI / Criminal justice / Discrimination / Prediction: "it incorrectly labelled black defendants as likely to commit further crimes at twice the rate as white defendants."
Comparison: PI's own examples entry matches the claim of international civil-society cataloguing.
Decision: primary-sourced

## Claim 17: The "Machine Bias" series expanded beyond COMPAS to Amazon's pricing algorithm, Facebook's advertising targeting, and other domains (also scalar:sources[2].note)

Source: https://www.propublica.org/series/machine-bias + https://www.npr.org/2016/10/19/498582157/propublica-reveals-discriminatory-pricing-by-computer-algorithms (via search)
Source tier: primary
Source content: Series ("Investigating algorithmic injustice and the formulas that influence our lives") includes "Facebook Lets Advertisers Exclude Users by Race" (Oct 2016), insurance-pricing and DNA-algorithm coverage; "Amazon Says It Puts Customers First. But Its Pricing Algorithm Doesn't" (20 Sept 2016) with a ProPublica datastore dataset; NPR covered the series' pricing reporting.
Comparison: Both named expansion domains are real series entries; series scope beyond criminal justice confirmed.
Decision: corroborated

## Claim 18: Subsequent audits, including AJL's Gender Shades study, drew on the approach (edge: propagated_by_orgs → org-algorithmic-justice-league)

Source: http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf
Source tier: primary
Source content: Gender Shades (Buolamwini & Gebru, PMLR 81, 2018) cites the ProPublica investigation as audit precedent: "demographic labels … have been used for performing algorithmic audits (Friedler et al., 2016; Angwin et al., 2016)".
Comparison: The peer-reviewed paper itself situates Angwin et al. 2016 as prior art for algorithmic audits, supporting the drew-on-the-approach claim and the AJL propagation edge. Edge target `org-algorithmic-justice-league.md` exists.
Decision: primary-sourced

## Claim 19: Cross-reference edges resolve (propagated_by_orgs, related_messages, body links)

Source: repository file check (product/entities/)
Source tier: primary
Source content: All five referenced entity files exist: org-algorithmic-justice-league, org-electronic-frontier-foundation, msg-coded-gaze, msg-data-is-a-civil-rights-issue, msg-automating-banishment.
Comparison: Mechanical worktree check; every edge target resolves and matches the entity the body names (coded gaze and data-is-a-civil-rights-issue are the adjacent framings body § Why it has carried describes).
Decision: corroborated
