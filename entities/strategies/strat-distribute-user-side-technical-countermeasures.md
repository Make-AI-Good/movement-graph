---
id: strat-distribute-user-side-technical-countermeasures
type: strategy
name: Distribute user-side technical countermeasures against AI
status: active
confidence: medium
tags: [glaze, nightshade, adversarial-perturbation, anti-scraping, user-tooling, technical-resistance, defensive-tools, opt-out, arms-race]
created: 2026-06-08
last_updated: 2026-06-08
related_strategies: []
sources: []
---

# Distribute user-side technical countermeasures against AI

Researchers and small developer teams build and release tools that an individual can install or apply to defang a specific AI use against them: image perturbations that poison or confuse generative models trained on the user's art (Glaze, Nightshade), browser extensions that block scrapers, audio watermarks that survive synthesis, anti-deepfake provenance signing, hidden-prompt injection on resumes that hiring tools read. The work is distributed free or near-free, optimised for usability by non-technical users, and treated as an ongoing arms race rather than a one-shot release.

An actor chooses this strategy because regulation and litigation operate on a multi-year cycle while AI systems are deployed against people now, and a working tool delivers the protective effect immediately without waiting for any institution to act. The strategy also moves the cost of opting out off the user — for whom it is currently prohibitive — and back onto the AI system, which must invest in defeating each countermeasure, slowing the rate at which extraction becomes economic. It is one of very few strategies in which a small, well-placed technical team can produce a result the largest advocacy organisation cannot match.

It trades durability for immediate effect. Every countermeasure has a finite lifespan against a well-funded adversary willing to retrain or recompute around it, and the strategy risks entrenching a frame in which protection is the individual's burden rather than a public responsibility. Maintenance cost accumulates quickly — a tool that worked last year against last year's models may not work this year — and a movement that overinvests in this strategy can end up subsidising an arms race the larger industrial party always eventually wins.
