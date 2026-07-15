---
id: strat-community-red-teaming-of-deployed-ai
type: strategy
name: Community red-teaming of deployed AI systems
status: active
confidence: high
tags: [red-teaming, adversarial-testing, def-con, ai-village, generative-red-team, bug-bounty, hackathon, participatory-audit, jailbreak, evaluation]
created: 2026-07-15
last_updated: 2026-07-15
related_strategies:
  - strat-empirical-audit-and-expose
  - strat-civil-society-inside-technical-standards-bodies
  - strat-distribute-user-side-technical-countermeasures
  - strat-survivor-led-testimony-as-evidence
effects: []
sources: []
---

# Community red-teaming of deployed AI systems

Organise structured adversarial testing of production AI systems — frontier chatbots, image generators, deployed hiring or benefits systems, content-moderation classifiers — by a distributed community of participants working from a shared harm-taxonomy or evaluation rubric, in a public event or ongoing programme. The vehicle is a coordinated hackathon (the DEF CON AI Village Generative Red Team, university red-team courses, bug-bounty-style vendor programmes with civil-society partners) or a standing red-team collective producing structured incident reports over months. Findings are aggregated into a public artefact — a report, a database entry, a filed regulatory comment — that names the failure modes the community elicited and the conditions under which they fired.

An actor chooses this strategy because the vendor's internal safety evaluations are chronically thinner and more monocultural than an open-community effort can produce, and the *specific* harm patterns that surface only under adversarial user shapes drawn from the affected populations are rarely visible from inside the lab. It also creates a movement-side technical bench: hundreds of participants building a working intuition for the failure modes of the deployed system, most of whom then carry that intuition back into journalism, litigation, policy advocacy, and further evaluation work. Compared to a formal published audit, the community register lowers the barrier to participation, produces more evaluations per calendar quarter, and reaches deployment cases and languages the formal literature does not.

It trades methodological rigour for coverage. Community red-teams produce large volumes of incident evidence but rarely with the statistical control the peer-reviewed audit standard requires, and the vendor can (and does) point at the methodological gap when a finding is inconvenient. The strategy is also structurally dependent on the vendor's cooperation — an access-restricted or actively-jailbreak-hostile deployment can defeat the participant's ability to elicit findings at all — and vendor-hosted programmes can filter which findings become public and which the vendor absorbs without disclosure. The strategy has been most productive on general-purpose consumer-facing systems where access is broad; deployed public-sector systems (police, benefits, hiring) rarely admit the strategy at all without an inside-the-institution partner.

This strategy differs from [strat-empirical-audit-and-expose](strat-empirical-audit-and-expose.md) by *register* — audit-and-expose fires a small number of methodologically-hardened findings, community red-teaming fires many looser findings and gains coverage — and from [strat-distribute-user-side-technical-countermeasures](strat-distribute-user-side-technical-countermeasures.md) by *use of the finding* — countermeasures build a tool users deploy against the system, red-teaming documents what the system does. The two strategies feed each other: a red-team finding often becomes the seed of a formal audit, and a distributed audit often begins as a hackathon report.
