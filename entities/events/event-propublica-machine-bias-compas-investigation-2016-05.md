---
id: event-propublica-machine-bias-compas-investigation-2016-05
type: event
name: ProPublica Machine Bias — COMPAS investigation (23 May 2016)
status: historical
confidence: high
tags: [us, florida, broward-county, algorithmic-accountability, criminal-justice, racial-bias, compas, recidivism-scoring, investigative-journalism, machine-bias, data-journalism, data-release, movement-infrastructure]
created: 2026-09-16
last_updated: 2026-09-16
date: 2016-05-23
location: online
event_type: investigative-journalism-publication
participating_orgs:
  - org-propublica
participating_people: []
related_events: []
sources:
  - url: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
    last_checked: 2026-09-16
    note: 'Original ProPublica Machine Bias COMPAS investigation — "There''s Software Used Across the Country to Predict Future Criminals. And It''s Biased Against Blacks." Published 23 May 2016 by Julia Angwin, Jeff Larson, Surya Mattu, and Lauren Kirchner; primary source for the investigation scope, methodology, central racial-disparity findings, and Broward County dataset context.'
  - url: https://github.com/propublica/compas-analysis
    last_checked: 2026-09-16
    note: 'ProPublica public GitHub repository — full COMPAS dataset and analysis code released alongside the investigation for independent verification; primary source for the open-data element of the publication event.'
  - url: https://www.propublica.org/article/making-algorithms-accountable
    last_checked: 2026-09-16
    note: 'ProPublica follow-up analysis on algorithmic accountability policy outcomes — Wisconsin Supreme Court ruling (State v. Loomis) requiring COMPAS scores not be determinative in sentencing and presentence reports include accuracy-limitation warnings; confirms the investigation as catalyst for the court challenge and for EU regulatory attention.'
  - url: https://www.propublica.org/series/machine-bias
    last_checked: 2026-09-16
    note: 'Machine Bias series landing page — contextualizes the COMPAS piece within the broader series investigating "algorithmic injustice and the formulas that influence our lives"; confirms series launched 2015 and the COMPAS investigation as its foundational entry.'
---

# ProPublica Machine Bias — COMPAS investigation (23 May 2016)

On [23 May 2016](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing), [ProPublica](../organizations/org-propublica.md) published "There's Software Used Across the Country to Predict Future Criminals. And It's Biased Against Blacks." — a [Machine Bias](https://www.propublica.org/series/machine-bias) investigation by Julia Angwin, Jeff Larson, Surya Mattu, and Lauren Kirchner into COMPAS (Correctional Offender Management Profiling for Alternative Sanctions), a recidivism risk-scoring algorithm used in US criminal courts for pre-trial detention, sentencing, and parole decisions. Working from [more than 7,000 individual COMPAS risk scores](https://github.com/propublica/compas-analysis) obtained from Northpointe for defendants arraigned in Broward County, Florida in 2013–14, the team tracked actual criminal records over two years and found that Black defendants were [nearly twice as likely as white defendants](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) to be falsely flagged as future criminals — assigned a high recidivism score but not subsequently rearrested — while white defendants were more likely to be wrongly assigned low risk before reoffending with violent crimes. ProPublica simultaneously [released its full dataset and analysis code on GitHub](https://github.com/propublica/compas-analysis), making this the first major AI-bias investigation to treat published data as integral to the accountability act itself.

The Wisconsin Supreme Court, in [*State v. Loomis* (2016)](https://www.propublica.org/article/making-algorithms-accountable), subsequently ruled that COMPAS scores cannot be determinative in sentencing and that presentence investigation reports must include accuracy-limitation warnings about algorithmic instruments. Northpointe's public contestation of ProPublica's methodology seeded a sustained academic sub-field on algorithmic fairness — the full peer-reviewed debate ran on ProPublica's publicly released Broward County dataset.
