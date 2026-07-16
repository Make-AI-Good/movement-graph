---
id: strat-collective-licensing-and-opt-out-for-training-data
type: strategy
name: Collective licensing and opt-out infrastructure for training data
status: active
confidence: high
tags: [copyright, data-rights, training-data, chokepoint, collective-licensing, ascap-for-ai, opt-out-registry, provenance, creators-rights, publisher-organizing, supply-chain-control]
created: 2026-07-16
last_updated: 2026-07-16
related_strategies:
  - strat-creator-class-collective-bargaining-on-generative-ai
  - strat-class-action-litigation-against-private-ai
  - strat-distribute-user-side-technical-countermeasures
  - strat-empirical-audit-and-expose
sources: []
---

# Collective licensing and opt-out infrastructure for training data

Rights-holders — authors, artists, musicians, journalists, photographers, publishers, code authors — aggregate their individual data-and-copyright interests into collective structures (rights-collecting societies, opt-out registries, industry-wide licensing consortia, standard-form training-data-use terms) that constrain the AI vendor's training-data supply on collective terms rather than on the vendor's single-actor terms. The infrastructure ranges from opt-out registries (a machine-readable "do-not-train" claim asserted at the domain, feed, or work level) through provenance-and-consent registries (Content Authenticity Initiative, C2PA) to full collective-licensing agencies on the ASCAP / BMI model (a single license from the collective covers the full member repertoire, with revenue distribution back to members). The strategy converts a diffuse individual-rights problem — every creator would need to sue individually to defend their own work — into a collective-bargaining position with the vendor at the training-data supply layer.

An actor chooses this strategy because the training-data supply chain is the AI model's structural chokepoint: a large-scale model cannot be trained without access to a large corpus, and the corpus is composed of individual works whose rights-holders can, in aggregate, refuse or price that access. The strategy runs at the *supply* layer rather than at the deployment layer, which means it constrains the vendor's whole downstream product regardless of which harm the model produces. It also plays the standard music-industry precedent: the ASCAP / BMI collective-licensing regime resolved a comparable individual-rights collective-action problem in the 1910s-1940s by aggregating songwriters' rights into a single license the broadcaster had to negotiate against. The AI industry sits in exactly the pre-ASCAP position — training on individual works without a collective counterparty — and the strategy is to build that counterparty.

It trades scope for aggregation. A collective licensing regime only reaches works whose rights-holders have opted in (or, in a compulsory-licensing regime, whose statute requires the licensing) — the vast public-domain and unclaimed corpus remains available. The strategy is vulnerable to the *sui generis* legal argument that AI training is transformative use or otherwise exempt from copyright, an argument the vendor bar has pushed hard in every jurisdiction; a court ruling either way reshapes what the collective can license and on what terms. And the collective itself is a governance problem: rights-collecting societies have historically distributed revenue unevenly toward established repertoires and against new / marginalised creators, replicating industry hierarchies inside the movement-side infrastructure.

## Ecology

**Distinct from [creator-class collective bargaining on generative AI](strat-creator-class-collective-bargaining-on-generative-ai.md).** That strategy operates at the *labour-contract* layer — creator unions bargaining with employer studios and publishers over generative-AI use in the workplaces where creators are employed. This strategy operates at the *rights-in-work* layer — rights-holders bargaining with AI vendors over the works themselves as training data. The two strategies often live inside the same creator-sector organisations (the Authors Guild pursues both; the Writers Guild has pushed both), but they address different vendor-relationships (employer vs. AI-vendor) and different bargaining objects (employment terms vs. training-data licensing).

**Distinct from [class-action litigation against private-sector AI harms](strat-class-action-litigation-against-private-ai.md).** Class actions are backward-looking litigation for damages on training that has already happened, resolved through the courts on a per-case basis. Collective licensing is forward-looking infrastructure that establishes the licensing regime the next round of training will operate inside. The two strategies complement — a class action can produce a settlement that includes a licensing commitment, and a collective licensing regime is often what a class action settles into — but the strategies work at different times in the vendor's product cycle.

**Distinct from [distributing user-side technical countermeasures](strat-distribute-user-side-technical-countermeasures.md).** User-side countermeasures (Glaze, Nightshade, robots.txt at scale) are *technical* tools individual rights-holders deploy against training; collective licensing is *institutional* infrastructure the aggregate rights-holder deploys against the vendor. The two are complementary: the countermeasures raise the cost of unauthorised training, which strengthens the licensing collective's bargaining position by making the alternative to a license more expensive.

**Fed by [empirical audit and expose](strat-empirical-audit-and-expose.md).** Documented evidence that a vendor trained on a specific corpus (books, articles, code) is the standing evidentiary base for a rights-holder collective's licensing demand; the audit converts a suspicion of unauthorised training into a citable finding the collective can bring to the negotiating table.

**Coordinated with [class-action litigation against private-sector AI harms](strat-class-action-litigation-against-private-ai.md)** at the litigation-and-licensing pipeline. The class action supplies the leverage; the collective licensing regime supplies the settlement architecture the leverage lands in. A well-organised creator-sector coalition runs the litigation arm to establish the vendor's liability and the licensing arm to convert that liability into an ongoing revenue-and-consent regime.
