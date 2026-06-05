---
id: msg-machine-bias
type: message
name: Machine bias
status: active
confidence: high
tags: [us-based, criminal-justice, algorithmic-accountability, algorithmic-racism, recidivism, risk-assessment, compas, courts, sentencing, pretrial-detention, framing, racial-bias, algorithmic-fairness, due-process, data-journalism, investigative-journalism, florida, broward-county, propublica]
created: 2026-06-04
last_updated: 2026-06-04
origin: |
  Published 23 May 2016 by ProPublica reporters Julia Angwin, Jeff Larson, Surya Mattu, and Lauren Kirchner under the headline "Machine Bias: There's Software Used Across the Country to Predict Future Criminals. And It's Biased Against Blacks." The article exposed racial disparities in COMPAS (Correctional Offender Management Profiling for Alternative Sanctions), a proprietary risk-assessment tool developed by Northpointe (later Equivant) and used by courts across the United States to generate scores predicting defendants' likelihood of future criminality at bail hearings, sentencing, and parole decisions. The team obtained COMPAS scores for more than 7,000 people arrested in Broward County, Florida in 2013 and 2014 through FOIA requests, then matched those scores against two-year follow-up arrest records. Black defendants who did not reoffend were nearly twice as likely to be falsely labeled high-risk as white defendants (45 percent vs. 23 percent); white defendants who did reoffend were nearly twice as likely to be incorrectly labeled low-risk (48 percent vs. 25 percent). The title phrase "machine bias" entered civil-society, legal, and academic discourse immediately as the standard shorthand for racial discrimination encoded in algorithmic decision-making — a framing that directly contested the neutrality claims used to justify the deployment of predictive tools at the core of the criminal justice system.
originating_person:
originating_org:
propagated_by_orgs:
  - org-algorithmic-justice-league
  - org-electronic-frontier-foundation
related_messages:
  - msg-coded-gaze
  - msg-data-is-a-civil-rights-issue
  - msg-automating-banishment
sources:
  - url: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
    last_checked: 2026-06-04
    note: 'Julia Angwin, Jeff Larson, Surya Mattu, Lauren Kirchner, "Machine Bias: There''s Software Used Across the Country to Predict Future Criminals. And It''s Biased Against Blacks," ProPublica, 23 May 2016 — the originating article; primary source for the COMPAS analysis, the Broward County dataset (7,000+ defendants, 2013–2014 arrests), the false-positive rate disparity (Black defendants 45% vs. white defendants 23%), the false-negative rate disparity (white defendants 48% vs. Black defendants 25%), the overall violent-recidivism prediction error rate (80%), and the framing that algorithmic tools embed racial bias'
  - url: https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm
    last_checked: 2026-06-04
    note: 'Jeff Larson et al., "How We Analyzed the COMPAS Recidivism Algorithm," ProPublica, 23 May 2016 — companion methodology piece; primary source for the FOIA data-collection process, Broward County selection rationale (large jurisdiction, Florida open-records laws), the COMPAS instrument''s 137-question structure, and publication of the dataset and code'
  - url: https://www.propublica.org/series/machine-bias
    last_checked: 2026-06-04
    note: 'ProPublica "Machine Bias" series archive — primary source for the series'' scope beyond the initial COMPAS article, including follow-up coverage of Amazon pricing algorithms, Facebook advertising targeting, and other algorithmic discrimination contexts that widened the framing from criminal justice to algorithmic decision-making generally'
  - url: https://www.pulitzer.org/finalists/julia-angwin-jeff-larson-surya-mattu-lauren-kirchner-and-terry-parris-jr-propublica
    last_checked: 2026-06-04
    note: 'Pulitzer Prizes — 2017 Explanatory Reporting finalist citation for Julia Angwin, Jeff Larson, Surya Mattu, Lauren Kirchner, and Terry Parris Jr. of ProPublica; primary source for the Pulitzer finalist designation and the April 2017 project submission date'
  - url: https://www.propublica.org/article/wisconsin-court-warning-labels-needed-scores-rating-risk-future-crime
    last_checked: 2026-06-04
    note: 'ProPublica, "Wisconsin Court: Warning Labels Are Needed for Scores Rating Defendants'' Risk of Future Crime" — primary source for the Wisconsin Supreme Court''s July 2016 ruling in State v. Loomis upholding COMPAS use with a mandated five-part warning, the prohibition on using the score as a determinative sentencing factor, and the Wisconsin ruling''s status as the leading legal precedent'
  - url: https://en.wikipedia.org/wiki/Loomis_v._Wisconsin
    last_checked: 2026-06-04
    note: 'Wikipedia on Loomis v. Wisconsin — secondary source for the case history, Eric Loomis''s due-process challenge (inability to contest the scientific validity of a proprietary algorithm), the Wisconsin Supreme Court ruling, and the U.S. Supreme Court denial of certiorari in June 2017; tiebreaker under corpus sourcing rules'
  - url: https://www.propublica.org/article/bias-in-criminal-risk-scores-is-mathematically-inevitable-researchers-say
    last_checked: 2026-06-04
    note: 'ProPublica, "Bias in Criminal Risk Scores Is Mathematically Inevitable, Researchers Say" — primary source for the impossibility result established independently by Alexandra Chouldechova (2017) and by Kleinberg, Mullainathan, and Raghavan (2016): error-rate equality and calibration equality cannot simultaneously hold across groups with differing base rates, meaning the choice of fairness definition is a normative value judgment'
  - url: https://www.eff.org/deeplinks/2020/12/questions-remain-about-pretrial-risk-assessment-algorithms-year-review-2020
    last_checked: 2026-06-04
    note: 'Electronic Frontier Foundation, "Questions Remain About Pretrial Risk-Assessment Algorithms," December 2020 — primary source for EFF''s sustained civil-society adoption of the machine-bias framing in advocacy against pretrial risk assessment tools, and for the finding that risk assessment tools do not create fair pretrial systems'
  - url: https://privacyinternational.org/examples/1801/propublica-analysis-finds-bias-compas-criminal-justice-risk-scoring-system
    last_checked: 2026-06-04
    note: 'Privacy International, "ProPublica analysis finds bias in COMPAS criminal justice risk scoring system" — primary source for international civil-society uptake of the ProPublica findings as a canonical reference case for algorithmic bias in criminal justice'
---

# "Machine bias"

"Machine bias" is the headline phrase from a [ProPublica investigation published 23 May 2016](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) exposing racial disparities in COMPAS, a proprietary algorithmic risk-assessment tool used by U.S. criminal courts to predict defendants' likelihood of future criminality. Within months of publication, the phrase entered civil-society, legal, and academic discourse as the dominant shorthand for racial discrimination encoded in algorithmic decision-making — a framing that directly contested the neutrality claims used to justify the deployment of predictive scoring tools at bail hearings, sentencing, and parole decisions. The argument at the framing's center: that a tool's technical accuracy is distinct from its racial fairness, and that the choice between competing definitions of fairness is a normative judgment about whose harms matter most, not a technical optimization.

## Origin

The ProPublica team — Julia Angwin, Jeff Larson, Surya Mattu, and Lauren Kirchner — filed FOIA requests in Broward County, Florida, a large jurisdiction using COMPAS in pretrial decisions whose open-records laws made the underlying data accessible. They [obtained COMPAS scores for more than 7,000 people arrested in 2013 and 2014](https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm) and matched those scores against two-year follow-up arrest records. COMPAS — Correctional Offender Management Profiling for Alternative Sanctions, developed by Northpointe (later Equivant) — generates a 1–10 recidivism risk score from a 137-item questionnaire covering criminal history, social environment, and self-reported attitudes; judges use the score as a supplementary input at bail, sentencing, and parole hearings.

The findings reported on 23 May 2016: Black defendants who did not reoffend were nearly twice as likely to be falsely labeled high-risk as white defendants (45 percent vs. 23 percent); white defendants who did reoffend were nearly twice as likely to be incorrectly labeled low-risk (48 percent vs. 25 percent). The algorithm's [overall prediction for violent recidivism was wrong 80 percent of the time](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing). Northpointe responded formally, defending COMPAS as "equally accurate" across racial groups in a calibration sense — its scores had equal predictive validity within each group. That defense was technically correct, and the dispute between the two claims named a structural tension the article had surfaced but not resolved.

## The core argument

The framing's lasting contribution was to show that the gap between technical accuracy and racial fairness was not an oversight but an inherent property of the system — and that the choice between competing fairness definitions could not be avoided. [Researchers Alexandra Chouldechova and Jon Kleinberg, Sendhil Mullainathan, and Astrid Luca Smola independently proved](https://www.propublica.org/article/bias-in-criminal-risk-scores-is-mathematically-inevitable-researchers-say), within months of publication, that error-rate equality (the civil rights standard ProPublica applied) and calibration equality (Northpointe's defense) cannot simultaneously hold across groups with differing base rates except in degenerate cases. This impossibility result formalized what the article had surfaced empirically: deploying any risk-assessment tool in a context with racially unequal base rates requires a normative choice about whose error rate to equalize. In the criminal justice context, base rates are themselves a product of racially discriminatory policing and prosecution history — so a model that faithfully captures historical patterns faithfully encodes their racial disparities into predictions that courts then treat as objective.

The framing is distinct from adjacent algorithmic-bias framings. It is not about technical accuracy alone (the model may be accurate), not about data quality alone (the data may reflect real patterns), and not about design intent (no deliberate bias is required). The argument is that structural racial disparities in the criminal justice system are the input to COMPAS, so a faithful model encodes those disparities and reproduces them as algorithmic outputs that carry the authority of scientific prediction. "Machine bias" names that feedback loop: the machine mirrors the historical bias it was trained on.

## Propagation

The article drew rapid academic response. Within months of publication, the impossibility proofs by Chouldechova and by Kleinberg, Mullainathan, and Raghavan had emerged directly from the COMPAS debate, spawning a body of work on algorithmic fairness that continues to grow. The phrase "machine bias" appears as a term of art in titles and abstracts across computer science, law, sociology, and public policy. The publication of the dataset and analytical code set a new template for open, replicable data journalism on algorithmic systems — subsequent audits, including the [Algorithmic Justice League](../organizations/org-algorithmic-justice-league.md)'s *Gender Shades* study, drew on the approach.

In the courts, the Wisconsin case of State v. Loomis became the first significant legal test of algorithmic sentencing. Eric Loomis challenged his six-year sentence on due-process grounds, arguing that COMPAS's proprietary status denied him the ability to contest the scientific validity of the score. [The Wisconsin Supreme Court upheld COMPAS use at sentencing in July 2016](https://www.propublica.org/article/wisconsin-court-warning-labels-needed-scores-rating-risk-future-crime) but ruled that courts could not use the score as a determinative sentencing factor, and mandated that presentencing reports carrying COMPAS scores include a five-part warning about the algorithm's limited utility. The [U.S. Supreme Court declined to hear the appeal in June 2017](https://en.wikipedia.org/wiki/Loomis_v._Wisconsin), leaving the Wisconsin ruling as the leading legal precedent on algorithmic sentencing.

In civil-society advocacy, the [Electronic Frontier Foundation](../organizations/org-electronic-frontier-foundation.md) adopted the machine-bias framing in sustained work against pretrial risk assessment tools, [finding that such tools do not create fair pretrial systems](https://www.eff.org/deeplinks/2020/12/questions-remain-about-pretrial-risk-assessment-algorithms-year-review-2020). [Privacy International](https://privacyinternational.org/examples/1801/propublica-analysis-finds-bias-compas-criminal-justice-risk-scoring-system) catalogued the ProPublica findings as a canonical international reference case for algorithmic bias in criminal justice. The ProPublica "Machine Bias" [series expanded beyond COMPAS](https://www.propublica.org/series/machine-bias) to cover Amazon's pricing algorithm, Facebook's advertising targeting, and other domains — extending the framing from criminal justice to algorithmic decision-making across commercial platforms. The project was a [2017 Pulitzer Prize finalist for Explanatory Reporting](https://www.pulitzer.org/finalists/julia-angwin-jeff-larson-surya-mattu-lauren-kirchner-and-terry-parris-jr-propublica).

## Why it has carried

Three features explain the framing's persistence. First, the phrase works across every level of the discourse. "Machine bias" fits a newspaper headline, a congressional hearing testimony, a placard, a law review article title, and an algorithm-auditing methodology description without requiring translation between registers. Adjacent framings — the [coded gaze](msg-coded-gaze.md), [data is a civil rights issue](msg-data-is-a-civil-rights-issue.md) — name the same underlying phenomenon but in domain-specific registers (optical/surveillance; civil rights law); "machine bias" is register-neutral and extensible, as the ProPublica series' expansion beyond criminal justice demonstrated.

Second, the open methodology made the findings durable. Publishing the dataset and code meant independent verification was possible, which removed the standard industry defense of proprietary opacity. It also enabled the impossibility proofs to emerge from the same data — researchers could engage with the argument concretely rather than abstractly. The open approach did not prevent challenge (Northpointe published a formal rejoinder; academic papers disputed aspects of the analysis) but it ensured the challenge was substantive.

Third, the impossibility result amplified rather than neutralized the framing. Proving that the choice of fairness definition could not be avoided — that deploying any risk-assessment tool required a normative judgment about whose harms matter more — relocated the question from the domain of technical expertise to the domain of democratic accountability. The framing's political argument (that algorithmic tools used to decide people's freedom encode value choices that deserve democratic scrutiny) was strengthened, not weakened, by the mathematical proof that the choice was genuine. The impossibility result became itself a movement resource: it gave advocates a formal basis for arguing that "better algorithms" alone cannot resolve the civil rights stakes, and that algorithmic sentencing tools require democratic governance, not merely technical refinement.
