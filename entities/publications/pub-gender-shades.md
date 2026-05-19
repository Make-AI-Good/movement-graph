---
id: pub-gender-shades
type: publication
name: "Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification"
status: active
confidence: high
tags: [paper, peer-reviewed, conference-paper, fairness-accountability-transparency, faccT-2018, commercial-vendor-audit, algorithmic-bias, facial-recognition, gender-classification, pilot-parliaments-benchmark, mit-media-lab, microsoft-research, ajl, gender-shades, coded-gaze, foundational-artefact, algorithmic-accountability]
created: 2026-05-13
last_updated: 2026-05-13
authors:
  - person-joy-buolamwini
  - person-timnit-gebru
publisher: Proceedings of Machine Learning Research (PMLR)
date: 2018-02-23
url: https://proceedings.mlr.press/v81/buolamwini18a.html
publication_type: other
sources:
  - url: https://proceedings.mlr.press/v81/buolamwini18a.html
    last_checked: 2026-05-13
    note: PMLR landing page for the paper — primary source for the formal citation (Proceedings of the 1st Conference on Fairness, Accountability and Transparency, PMLR vol. 81, pp. 77–91, 2018) and abstract
  - url: https://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf
    last_checked: 2026-05-13
    note: full-text PDF of the paper hosted by PMLR — primary text
  - url: https://gs.ajl.org/
    last_checked: 2026-05-13
    note: Algorithmic Justice League's Gender Shades project site — primary source for the project's framing, methodology, and continuing AJL anchoring
  - url: https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
    last_checked: 2026-05-13
    note: MIT News announcement (12 February 2018) — primary source for author affiliations at the time (MIT Media Lab Civic Media group, Microsoft Research), the Fitzpatrick-scale skin-typing methodology, the 1,200+ image dataset, and the "would that have been permitted if those failure rates were in a different subgroup?" Buolamwini quote
  - url: https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology
    last_checked: 2026-05-13
    note: WGBH/GBH News coverage (21 March 2018) — primary source for the per-vendor error-rate breakdown on dark-skinned women (IBM 35%, Face++ 34.5%, Microsoft 20.8%) and Buolamwini's "lighter male faces were the easiest to guess the gender on" framing
  - url: https://www.aies-conference.com/2019/wp-content/uploads/2019/01/AIES-19_paper_223.pdf
    last_checked: 2026-05-13
    note: '"Actionable Auditing: Investigating the Impact of Publicly Naming Biased Performance Results of Commercial AI Products" by Inioluwa Deborah Raji and Joy Buolamwini, AIES 2019 — the published follow-up audit measuring the post-Gender-Shades API updates from IBM, Microsoft, and Face++'
  - url: https://onezero.medium.com/how-a-2018-research-paper-led-to-amazon-and-ibm-curbing-their-facial-recognition-programs-db9d6cb8a420
    last_checked: 2026-05-13
    note: OneZero (Dave Gershgorn) article on the throughline from Gender Shades to the June 2020 IBM exit from facial recognition and the Microsoft and Amazon police-use moratoria after the murder of George Floyd
  - url: http://gendershades.org/docs/ibm.pdf
    last_checked: 2026-05-13
    note: IBM's official written response to Gender Shades — primary source for the same-day vendor response and IBM's subsequent commitment to retrain its system
---

# Gender Shades

*Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification* is a peer-reviewed paper by [Joy Buolamwini](../persons/person-joy-buolamwini.md) and [Timnit Gebru](../persons/person-timnit-gebru.md) [presented at the inaugural Conference on Fairness, Accountability and Transparency (FAT\*) in New York on 23 February 2018](https://proceedings.mlr.press/v81/buolamwini18a.html) and [published in *Proceedings of Machine Learning Research* volume 81, pages 77–91](https://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf). The work was completed while [Buolamwini was a graduate student in the MIT Media Lab's Civic Media group and Gebru was at Microsoft Research](https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212).

The paper audited three commercial gender-classification APIs — IBM Watson Visual Recognition, Microsoft Cognitive Services, and Face++ (Megvii) — against the [Pilot Parliaments Benchmark, a 1,270-image dataset Buolamwini assembled from the official portraits of parliamentarians in Rwanda, Senegal, South Africa, Iceland, Finland, and Sweden, balanced on gender and on the six-point Fitzpatrick skin-type scale](https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212). Its headline finding is the [43-fold gap between the maximum 0.8% error rate on lighter-skinned male faces and the up-to-34.7% error rate on darker-skinned female faces](https://proceedings.mlr.press/v81/buolamwini18a.html); broken out per vendor, [IBM misclassified the gender of 35% of darker-skinned women, Face++ 34.5%, and Microsoft 20.8%](https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology), with error rates [for the darkest-skinned women under the Fitzpatrick VI category reaching 46.5% and 46.8%](https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212). Buolamwini's signature framing of the result — ["to fail on one in three, in a commercial system, on something that's been reduced to a binary classification task, you have to ask, would that have been permitted if those failure rates were in a different subgroup?"](https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212) — has been carried into subsequent advocacy and policy writing on algorithmic auditing as the canonical statement of why intersectional benchmarks matter.

The paper triggered immediate vendor responses: [IBM replied the same day pre-release results were shared (22 December 2017) and committed to retraining its system](http://gendershades.org/docs/ibm.pdf), with Microsoft and Face++ following in the months that followed. The 2019 [follow-up audit *Actionable Auditing: Investigating the Impact of Publicly Naming Biased Performance Results of Commercial AI Products*, by Inioluwa Deborah Raji and Joy Buolamwini, presented at AIES 2019](https://www.aies-conference.com/2019/wp-content/uploads/2019/01/AIES-19_paper_223.pdf), measured the resulting API revisions and documented overall Pilot Parliaments Benchmark error reductions of 5.7% for Microsoft, 7.7% for IBM, and 8.3% for Face++. A longer arc runs from the paper through the post-Floyd June 2020 corporate retreat from facial recognition — [IBM's exit from the facial-recognition business and Amazon and Microsoft's police-use moratoria](https://onezero.medium.com/how-a-2018-research-paper-led-to-amazon-and-ibm-curbing-their-facial-recognition-programs-db9d6cb8a420), each of which the firms and subsequent commentary explicitly traced back to the Gender Shades audit and the public-evidence ground it laid.

Within the corpus, *Gender Shades* is the seed empirical artefact of the algorithmic-accountability field on which the three existing [Algorithmic Justice League](../organizations/org-algorithmic-justice-league.md)-anchored Publications — [*Unmasking AI*](pub-unmasking-ai.md), [*Comply To Fly?*](pub-comply-to-fly.md), and [*Bug Bounties For Algorithmic Harms?*](pub-bug-bounties-for-algorithmic-harms.md) — explicitly build. It fills the peer-reviewed audit-paper publication sub-type that the three AJL self-published reports do not occupy, and it is the founding output of the [public voice](../voices/voice-joy-buolamwini.md) that *Unmasking AI* and the "coded gaze" / "evocative audit" framings later extend. The paper is also the work AJL has continued to organise around — its [project page on AJL's site](https://gs.ajl.org/) hosts the original paper, the 5th-anniversary GS5-API-Results dataset, and the framing under which AJL recruits new participatory-audit cohorts — making *Gender Shades* not only the cluster's earliest and most-cited research output but its continuing organising anchor.
