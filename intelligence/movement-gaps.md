---
type: intelligence-artifact
artifact: movement-gaps
name: Movement gaps — strategies expected but not adopted in AI
authored_by: analyst
created: 2026-06-11
last_updated: 2026-07-04
---

# Movement gaps

The graph team's Analyst standing list of strategies the movement could plausibly be running but isn't — strategies attested in adjacent movements (climate, tobacco liability, consumer protection, civil rights), expected on precedent, but with no AI-movement adopter yet identified.

Distinct from the [Strategy catalog](../entities/strategies/) under `entities/strategies/`: the catalog names strategies the movement *uses* (or could use); this list flags strategies the movement is *missing*.

## Lifecycle

Two live stages per entry, plus a terminal retirement:

- **`candidate`** — the Analyst surfaced the gap with a working hypothesis that it is movement-side. Synthesizer search not yet run, or running and not yet returned null. Not yet grounded.
- **`confirmed`** — the Synthesizer web-searched for a real-world adopter and returned null; the Analyst evaluated and promoted. A grounded gap: a strategy expected on the Analyst's read, but with no AI-movement adopter found in the world.
- **`retired`** — the world produced a real adopter; the gap has closed. The retirement line names the adopter and the date. Original framing preserved in git history.

## Shape

One H2 entry per gap. The body of each entry carries a `Status:` line, a date, and ~150–400 words framing the gap: what the strategy is, why it's expected on precedent, what the Synthesizer searched and what returned, and — when confirmed — what would close the gap if the world produced an adopter.

The frontmatter's `last_updated` marks the latest edit; git history is the version trace between releases. Formal shape and lifecycle are documented in [`schema/spec.md § Intelligence`](../schema/spec.md).

---

## Insurance and liability-based pressure on AI vendors

**Status:** `confirmed` (promoted 2026-06-11 on Synthesizer null verdict; entered 2026-06-11).

The strategy: organising pressure on insurers, reinsurers, and liability frameworks to refuse to underwrite unsafe AI deployment — making the financial-system layer a structural brake the way Insure Our Future has done with coal and oil underwriters, and the tobacco-liability lineage did with denial. Attested heavily in adjacent movements (climate's Insure Our Future coalition; tobacco litigation; asbestos liability). On AI the strategy is emergent rather than established: there is movement around AI-deployment insurance (e.g. errors-and-omissions exclusions for generative-AI products) but no clear sustained movement-side organising target the Analyst recognized at the surfacing pass.

**Search verdict (Synthesizer, 2026-06-10).** Six-angle web sweep for movement-side campaigns targeting insurers and reinsurers 2023–2026 as a structural pressure lever on AI deployment. **Null on the insurance-sector-targeting axis** — no Insure Our Future analog for AI identified. Major insurers (AIG, Great American, WR Berkley) are independently pulling back from AI coverage via errors-and-omissions exclusions, but this is industry-driven risk management, not movement-side organising. The Synthesizer did find adjacent legislative-track work — the Transparency Coalition (US duty-of-care product-liability advocacy, parent-founded, genuine grassroots) and Americans for Responsible Innovation (bipartisan policy advocacy with voter mobilization). These advocate for *liability frameworks via legislation* — a different tactic in the same family. The structural-brake-via-underwriter-pressure tactic itself — explicit organising of insurers / reinsurers as the target, the financial-system squeeze that defines the climate analog — has no AI-movement adopter as of this search.

The gap is real. The leverage the movement is leaving on the table is concrete: the climate precedent (Insure Our Future, founded 2017, now 35+ groups across continents, with documented coal-underwriter retreat) shows the tactic works against an extractive industry with insurance exposure. AI-deployment liability — generative-AI hallucination, autonomous-system harm, algorithmic-decision discrimination — is exactly the shape the financial system is *already* nervous about, which is why insurers are pulling back unilaterally; an organised movement-side campaign could amplify that retreat into a binding pressure-point and convert it from a quiet risk-management adjustment into a public accountability story.

**What would close this gap.** A campaign with insurer / reinsurer pressure as its explicit organising locus — open letters to underwriters refusing AI coverage of named high-risk products, mobilisation around shareholder resolutions at insurance-sector AGMs targeting AI exposure, a coalition naming and tracking insurers' AI-underwriting decisions (the Insure Our Future scorecard analog). Conversion of an existing climate-coalition Insure Our Future participant into AI work, or a fresh founding, would close the entry; legislative-track liability work (already queued) does not.

---

## Cross-professional refusal of AI integration beyond tech workers

**Status:** `retired` (2026-06-13). Adopters drafted in corpus: [org-national-nurses-united](../entities/organizations/org-national-nurses-united.md) (US nursing — contract-bargaining clauses, *Nurses and Patients' Bill of Rights*, 100,000+ members entering 2025 contract negotiations with AI provisions, January 2025 nationwide marches explicitly framed against AI in patient care) and [org-nacdl](../entities/organizations/org-nacdl.md) (US criminal defense — Fourth Amendment Center infrastructure since 2018, AI Task Force established 2023, standing coalition with ACLU and EFF as direct AI-movement infrastructure coordination). NNU meets the contract-bargaining-clauses closure criterion squarely; NACDL meets the AI-movement-coordination criterion identified as "the strongest closer". The gap as framed (organised professional bodies whose AI work has crossed from position-paper into binding refusal posture, coordinated with AI-movement infrastructure) is no longer movement-side: the corpus now carries multi-adopter evidence across two distinct professions (healthcare, criminal-justice) with different binding mechanisms (collective bargaining vs. litigation infrastructure). Original framing preserved in git history.

---

## Public-option / publicly-funded AI compute and models as movement contestation

**Status:** `retired` (2026-06-13). Adopter drafted in corpus: [org-public-ai-network](../entities/organizations/org-public-ai-network.md) (PAINT — international coalition founded 2023 at the Internet Archive's DWeb Camp; 350+ members from 100+ organizations including Metagov, Aspen Digital, Mozilla, Open Future, Public Knowledge, Berkman Klein Center, Chatham House; libraries program with Library of Congress, Utah State Library, New Jersey State Library running pilots in six states; Public AI Inference Utility and Swiss Public Inference Utility launched 2025; AI Commons data initiative; "Airbus for AI" European public AI institution proposal). PAINT meets the gap's closure criteria across the board — movement-side coalition with public-AI investment as its explicit organising demand; civic-coalition membership extending across US/EU registers; library-sector partnership directly matching the named closure example; framing AI as public utilities question analogous to broadcasting / libraries / municipal broadband. The "Medicare for All" / "Public Banking Coalition" pattern transposed to AI infrastructure is no longer a movement-side gap. Original framing preserved in git history.

---

## Movement-into-government / strategic personnel placement in AI regulatory agencies as named coalition tactic

**Status:** `confirmed` (promoted 2026-06-11 on Synthesizer null verdict).

The strategy: **organised civil-society personnel placement** into AI regulatory and technology-policy roles — FTC, NIST AI Safety Institute, OSTP technology offices, agency tech offices, EU AI Office, equivalent national bodies — as a *named coalition tactic*, distinct from individual activists who happen to enter government on their own trajectory. The strategic discipline is that of organised insider placement: a coalition tracking and engineering placements, sustaining a candidate pipeline, building movement-aligned bench depth, and treating personnel as a contestation site.

**Why expected.** Adjacent-movement precedent is heavy and multi-decade. The consumer-protection movement built the pipeline that produced the Consumer Financial Protection Bureau (Warren-founded) and FTC Chair Khan (the Yale-antitrust academic-to-agency trajectory the movement nurtured). The environmental movement built EPA and OSTP placements through the Carol Browner / Lisa Heinzerling lineage spanning the Clinton-through-Obama administrations. The civil-rights movement engineered DOJ Civil Rights Division and EEOC leadership for decades. Each treated agency staffing as strategic site, not careers side effect, and each sustained an organising infrastructure behind the placements.

**Working hypothesis it is movement-side.** The AI movement has *individual* aligned figures who entered government — Alondra Nelson at OSTP, Lina Khan at FTC, Tim Wu's technology-policy work — but I cannot point at a movement-side coalition whose explicit strategic demand is engineering AI-agency placements with a tracked candidate pipeline and sustained bench-depth investment. Policy-entrepreneurship organisations (Day One Project, Federation of American Scientists, Bridge2AI) work the adjacent register; whether any operates as a *movement-side coalition* on AI rather than as bipartisan policy infrastructure is what Synth would clarify.

**What would close this gap.** A movement-side coalition with AI-agency personnel placement as its explicit strategic demand: a tracked pipeline of movement-aligned candidates for AI Safety Institute, EU AI Office, agency tech offices, and equivalent roles; a coalition treating personnel placement as a contestation site analogous to consumer-protection's CFPB pipeline. An existing think-tank or policy-entrepreneurship organisation pivoting visibly into this register would close the gap; pure individual aligned-figure placements without an organising coalition behind them do not.

**Search verdict (Synthesizer, 2026-06-11).** Web search across Day One Project (FAS), Federation of American Scientists talent-hub programs, public-interest tech personnel-pipeline literature, and civil-society AI regulatory-capacity advocacy for a movement-side coalition with AI-agency placement as its named strategic demand. **Null on the movement-side coalition axis.** Day One Project / FAS Impact Fellowship program places science-policy fellows in federal agencies including AI-adjacent ones, but FAS operates as bipartisan policy infrastructure, not a movement-side coalition with AI as a named placement-contestation site. No EU analog found. Individual aligned figures (Nelson, Khan, Wu) entered AI-adjacent government roles on their own trajectories — no coalition-organised pipeline behind them. The gap is real and unaddressed.

---

## Organised consumer boycott of subscription AI products

**Status:** `retired` (2026-07-04). Adopter identified in the world: [**QuitGPT**](https://quitgpt.org) — coalition launched January 2026 by democracy activists, climate organizers, and labor organizers; 700,000+ ChatGPT Plus cancellation pledges and 1.5M+ total actions at surfacing; explicit organising demand that OpenAI legally commit to refuse autonomous weapons and mass domestic surveillance tools. QuitGPT was identified via Synthesizer partial-positive search 2026-06-11 and evaluated at the corpus-side closure threshold 2026-06-13. It meets every named closure criterion — a documented pledge mechanism with a public pledge count, a named target vendor (ChatGPT Plus), an explicit AI-governance organising demand, and the consumer-pay-side register the gap distinguished from professional-class use-refusal ([`strat-creator-class-collective-bargaining-on-generative-ai`](../entities/strategies/strat-creator-class-collective-bargaining-on-generative-ai.md)) and supplier-side withholding (the Adobe Stock contributor backlash of 2023). The corpus campaign entity `camp-quitgpt-chatgpt-boycott-2026` is queued for drafting; the retirement here does not wait on that draft because the movement-side adopter exists in the world, which is what makes this a closed gap. When the campaign lands in the corpus, this entry's adopter reference will point to it directly. Original framing preserved in git history.
