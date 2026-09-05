---
entity_id: msg-ai-moratorium
entity_hash: 60a0df962cfa0c1348a3638dacd41a06e6b4d6b4
audit_date: 2026-09-04
pass: 1
status: corrections-pending
claims_total: 22
claims_corroborated: 7
claims_primary_sourced: 8
claims_single_source: 2
claims_uncorroborated: 3
open_corrections: 2
sources_consulted:
  - https://intelligence.org/2023/04/07/pausing-ai-developments-isnt-enough-we-need-to-shut-it-all-down/
  - https://moratorium.ai/
  - https://www.stopai.info/about
  - https://www.stopai.info/
  - https://www.theregister.com/2025/02/19/ai_activists_seek_ban_agi/
  - https://www.sanders.senate.gov/press-releases/news-sanders-ocasio-cortez-announce-ai-data-center-moratorium-act/
  - https://www.commondreams.org/news/stop-data-centers
  - https://www.kqed.org/news/12066171/openai-critic-arrested-for-sf-protest-ahead-of-activist-groups-criminal-trial
  - https://futureoflife.org/open-letter/pause-giant-ai-experiments/
  - https://en.wikipedia.org/wiki/Stop_AI
  - https://www.transformernews.ai/p/a-brief-guide-to-anti-ai-activist-stop-ai-pauseai-controlai
  - https://fortune.com/2026/04/15/pause-ai-and-stop-ai-meet-the-anti-ai-groups-facing-questions-after-the-attack-on-sam-altman/
  - https://www.foodandwaterwatch.org/2026/06/11/500-groups-from-47-states-call-for-nationwide-ai-data-center-moratorium/
  - https://www.kron4.com/news/technology-ai/sf-jury-convicts-protester-who-blocked-openai-headquarters/
  - https://en.wikipedia.org/wiki/Eliezer_Yudkowsky
  - https://time.com/author/eliezer-yudkowsky/
---

Type-shape note: Message is a connective type — claims audited are edges (`propagated_by_orgs`) and hard specifics (dates, counts, names, quoted attributions, demand contents). Interpretive prose about significance, register-structure, and coalitional dynamics (§ "Why the framing has carried" except its embedded specifics) is out of remit and received no decision. `related_messages` targets (msg-pause-giant-ai-experiments, msg-meaningful-human-control) and body cross-refs (org-stop-ai, org-pauseai, person-geoffrey-hinton) all resolve to existing entity files; relatedness itself is interpretation, not a claim.

## Claim 1: "On March 22, 2023, the FLI letter called for a six-month pause on training AI systems more powerful than GPT-4, with a government-imposed moratorium named as the fallback"

Source: https://futureoflife.org/open-letter/pause-giant-ai-experiments/
Source tier: primary
Source content: Dated 22 March 2023: "we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4." "If such a pause cannot be enacted quickly, governments should step in and institute a moratorium."
Comparison: Date, duration, threshold, and moratorium-fallback all match the letter verbatim. Also covers the same assertions in scalar:origin.
Decision: primary-sourced

## Claim 2: Yudkowsky published "Pausing AI Developments Isn't Enough. We Need to Shut it All Down" in TIME, March 29, 2023 ("seven days later"), stating he refrained from signing because the letter "understates the seriousness of the situation and asks for too little to solve it"

Source: https://intelligence.org/2023/04/07/pausing-ai-developments-isnt-enough-we-need-to-shut-it-all-down/
Source tier: primary
Source content: "Pausing AI Developments Isn't Enough. We Need to Shut it All Down" — published in TIME on March 29, 2023. "I refrained from signing because I think the letter is understating the seriousness of the situation and asks for too little to solve it."
Comparison: Title, venue, date (March 22 + 7 days = March 29 ✓) match. Quote matches except the entity inflects "understating" → "understates" inside quotation marks to fit its sentence — substance identical, not a token error, but a verbatim-quote purist would flag it. Also covers scalar:origin and scalar:sources[0].note.
Decision: primary-sourced

## Claim 3: scalar:origin — the TIME op-ed was "the first widely-distributed public articulation of the moratorium-vs-pause distinction"

Source: no canonical source found
Source tier: none
Source content: No source consulted asserts priority ("first") for this articulation.
Comparison: "Who was first" is a contested-attribution claim class (tiebreaker-only under the source rule). The op-ed's existence, date, and content are verified (Claim 2); its priority as "first widely-distributed" is not established by any fetched source. Not a finding of error — the audit reaches its limit here.
Decision: uncorroborated

## Claim 4: "Eliezer Yudkowsky — co-founder and research lead of the Machine Intelligence Research Institute (MIRI)"

Source: https://en.wikipedia.org/wiki/Eliezer_Yudkowsky ; https://time.com/author/eliezer-yudkowsky/
Source tier: mainstream
Source content: Wikipedia: "co-founder of the Machine Intelligence Research Institute" (search snippet). TIME author byline: "Yudkowsky is a decision theorist from the U.S. and leads research at the Machine Intelligence Research Institute" (search snippet).
Comparison: Co-founder is a named-entity definitional fact (Wikipedia-alone-sufficient class); "research lead" matches TIME's own byline for the cited op-ed. Both facets confirmed, via search snippets of the named pages.
Decision: corroborated

## Claim 5: Yudkowsky's demand — moratorium "indefinite and worldwide," all large training runs, "with no exceptions, including for governments or militaries"

Source: https://intelligence.org/2023/04/07/pausing-ai-developments-isnt-enough-we-need-to-shut-it-all-down/
Source tier: primary
Source content: "The moratorium on new large training runs needs to be indefinite and worldwide. There can be no exceptions, including for governments or militaries."
Comparison: Verbatim match; also covers scalar:sources[0].note's "indefinite and worldwide" quotation.
Decision: primary-sourced

## Claim 6: the framing's working slogan — "shut it all down"

Source: https://intelligence.org/2023/04/07/pausing-ai-developments-isnt-enough-we-need-to-shut-it-all-down/
Source tier: primary
Source content: "Shut it all down" appears in the op-ed multiple times, including as a concluding statement.
Comparison: Matches; the phrase is the op-ed's title tail and refrain.
Decision: primary-sourced

## Claim 7: proposed enforcement — "international tracking of GPU sales, and the willingness to destroy non-compliant compute infrastructure"

Source: https://intelligence.org/2023/04/07/pausing-ai-developments-isnt-enough-we-need-to-shut-it-all-down/
Source tier: primary
Source content: "Track all GPUs sold. If intelligence says that a country outside the agreement is building a GPU cluster... be willing to destroy a rogue datacenter by airstrike."
Comparison: Entity's paraphrase (GPU tracking; destroying non-compliant compute) accurately renders the source's enforcement passage. Also covers scalar:sources[0].note's enforcement-mechanism sentence.
Decision: primary-sourced

## Claim 8: solving alignment "could very reasonably take at least half" of the sixty-plus years AI research had existed

Source: https://intelligence.org/2023/04/07/pausing-ai-developments-isnt-enough-we-need-to-shut-it-all-down/
Source tier: primary
Source content: "Solving safety of superhuman intelligence…could very reasonably take at least half that long" (referring to the 60+ years since AI research began).
Comparison: Quoted fragment and referent match.
Decision: primary-sourced

## Claim 9: moratorium.ai is run by the AI Safety and Governance Fund and calls on governments for strict national restrictions on frontier AI training, international monitoring, and global coordination to halt risky training runs

Source: https://moratorium.ai/
Source tier: primary
Source content: Run by the "AI Safety and Governance Fund," a 501(c)(4). "We call on policymakers around the world to establish and enforce national restrictions and then a global AI moratorium that would prevent anyone in the world from risking human extinction"; "Globally coordinating to monitor, track, and restrict access to the computational power (chips/data centers) required for dangerous AI development."
Comparison: Operator and the three demand elements match the campaign's own site. Also covers scalar:sources[1].note's demand description.
Decision: primary-sourced

## Claim 10: moratorium.ai is "backed by MIRI, the Center for AI Policy, and the Center for AI Safety" (body and scalar:sources[1].note)

Source: https://moratorium.ai/
Source tier: primary
Source content: The site lists Center for AI Policy, Center for AI Safety, and MIRI under an "Other policy organizations" section (MIRI referenced as "The Problem" resource).
Comparison: The site names all three organizations, but as a listing of other policy organizations/resources — the fetched page does not establish an endorsement or backing relationship. "Backed by" asserts more than the source shows; too judgment-loaded to confirm or refute. Scalar path for any fix: sources[1].note and the body sentence in § Origin.
Decision: uncorroborated

## Claim 11: Edge propagated_by_orgs → org-stop-ai; Stop AI "demands a permanent global ban on AGI/ASI development and has pursued arrest-seeking direct action at AI company offices" (scalar:origin)

Source: https://www.stopai.info/about ; https://www.theregister.com/2025/02/19/ai_activists_seek_ban_agi/
Source tier: primary
Source content: stopai.info: "We call for a permanent enforceable ban on ASI/AGI." The Register: "We want governments to force AI companies to shut down everything related to the creation of general-purpose AI models, destroy any existing general-purpose AI model, and permanently ban their development"; describes repeated arrests at OpenAI actions.
Comparison: Edge target file exists and is the same organization. The propagation claim (Stop AI carries the moratorium/permanent-ban demand via direct action) is confirmed by the org's own site and mainstream coverage.
Decision: corroborated

## Claim 12: Stop AI is "an Oakland, California-based direct-action organization founded in 2024 by Sam Kirchner and Guido Reichstadter" (body; scalar:origin "(Oakland, 2024)")

Source: https://www.theregister.com/2025/02/19/ai_activists_seek_ban_agi/ ; https://www.kqed.org/news/12066171/openai-critic-arrested-for-sf-protest-ahead-of-activist-groups-criminal-trial ; https://en.wikipedia.org/wiki/Stop_AI ; https://fortune.com/2026/04/15/pause-ai-and-stop-ai-meet-the-anti-ai-groups-facing-questions-after-the-attack-on-sam-altman/
Source tier: mainstream
Source content: The Register names "co-founders Sam Kirchner and Guido Reichstadter." KQED (Dec 2025): founded "last year" [=2024] by Sam Kirchner; members "mostly" from a shared West Oakland house. Wikipedia: "formed in 2024," "Based in Oakland, California." Fortune (snippet): "a group he launched in 2024 with 45-year-old Guido Reichstadter"; SF Standard (snippet): "co-founder of Oakland-based Stop AI."
Comparison: Founding year, both co-founders, and Oakland base each confirmed by ≥2 canonical sources.
Decision: corroborated

## Claim 13: Stop AI was "built around a tactical break from PauseAI. PauseAI's leadership refused to authorise illegal direct actions; Stop AI was founded specifically to pursue the forms of civil disobedience PauseAI would not sanction"

Source: https://www.transformernews.ai/p/a-brief-guide-to-anti-ai-activist-stop-ai-pauseai-controlai ; https://fortune.com/2026/04/15/pause-ai-and-stop-ai-meet-the-anti-ai-groups-facing-questions-after-the-attack-on-sam-altman/
Source tier: mainstream
Source content: Transformer guide, quoting PauseAI's own statement: "PauseAI leadership did not allow the eventual StopAI founders...to do illegal direct actions." Fortune (snippet): "The split stemmed from disagreements over tactics, with Stop AI's founders pushing for civil disobedience that would involve breaking the law—something Pause AI explicitly rejects."
Comparison: The tactical-break account, including PauseAI's refusal to sanction illegal actions, is confirmed by two independent outlets (one quoting PauseAI directly).
Decision: corroborated

## Claim 14: Stop AI's core demand is a "permanent enforceable ban on ASI/AGI," paired with an international ban on autonomous AI weapons and surveillance restrictions; framing of AI as "a grave threat to the democratic project" (body; scalar:sources[2].note)

Source: https://www.stopai.info/about ; https://www.theregister.com/2025/02/19/ai_activists_seek_ban_agi/
Source tier: primary
Source content: stopai.info: "We call for a permanent enforceable ban on ASI/AGI"; "We call for an international ban on autonomous and AI-driven weapons"; "We call for robust regulations on surveillance and intellectual property theft"; "AI will not solve our crisis of morality and it presents a grave threat to the democratic project." The Register confirms the permanent-ban demand independently.
Comparison: Quoted demand and democratic-project framing verbatim on the org's own site; ban demand corroborated by The Register. "Surveillance restrictions" fairly renders "robust regulations on surveillance."
Decision: corroborated

## Claim 15: scalar:sources[2].note — "the five principles (biological-life prioritization, non-violence, democratic values, informed consent, personal AI limitation)"

Source: https://www.stopai.info/about
Source tier: primary
Source content: The Principles of Unity verbatim: "1. Prioritize biological life, balancing human needs with the broader ecosystem. 2. Adhere to non-violence, democratic values, and informed consent. 3. Pursue a permanent global ban on the further development of frontier AI technology. 4. Create meaningful citizen's oversight of AI technology. 5. Commit to limiting personal exposure and usage of AI technology."
Comparison: The note's parenthetical presents five items as the five principles, but they map onto only principles 1, 2 (split into three items), and 5 — omitting the permanent-global-ban principle (3) and citizen-oversight principle (4). The enumeration contradicts the source's actual list. Fix location: scalar:sources[2].note. The replacement is the actual five-principle list (above); rewriting the parenthetical requires prose judgment beyond a single token, so the Editor will likely flag to the Researcher.
Decision: correction

## Claim 16: Stop AI "explicitly models itself on climate civil-disobedience groups, especially Just Stop Oil, citing political scientist Erica Chenoweth's research that 3.5% population engagement can achieve political change"

Source: https://www.theregister.com/2025/02/19/ai_activists_seek_ban_agi/
Source tier: mainstream
Source content: "We're trying to take the strategy of groups like Just Stop Oil and apply it to protesting AI." Kirchner references Erica Chenoweth's research showing 3.5 percent population engagement can achieve political demands.
Comparison: Both the Just Stop Oil model and the Chenoweth 3.5% citation match; single mainstream source. Also covers scalar:sources[3].note's NVDA-model sentence.
Decision: single-source

## Claim 17: "in June 2024, members rallied and blocked OpenAI's entrance, resulting in three arrests" (body; scalar:sources[3].note "the June 2024 and February 2025 OpenAI protest actions")

Source: https://www.theregister.com/2025/02/19/ai_activists_seek_ban_agi/ ; https://fortune.com/2026/04/15/pause-ai-and-stop-ai-meet-the-anti-ai-groups-facing-questions-after-the-attack-on-sam-altman/
Source tier: mainstream
Source content: The Register: co-founders Sam Kirchner and Guido Reichstadter "were arrested for civil disobedience by blocking OpenAI's entrance" in October 2024; "in February, three Stop AI protestors, including Reichstadter, were arrested after they blocked the doors of OpenAI's offices." Fortune (snippet): "Three members of the group, including Kirchner and his co-founder Guido Reichstadter, were arrested outside of OpenAI's headquarters in February when they refused to leave company property after chaining its doors shut."
Comparison: The entity's own cited source (The Register) places the 2024 entrance-blocking arrests in October 2024, not June 2024; no canonical source consulted records any June 2024 Stop AI action. The date token has a single correct replacement: October 2024. The "three arrests" count attaches to the February 2025 action in both sources, not the 2024 one (the Register names two co-founders arrested in October 2024); untangling the sentence's arrest-count facet requires prose judgment — Editor should flag to Researcher rather than swap the date alone. Fix locations: body § "Grassroots civil-disobedience expression" and scalar:sources[3].note.
Decision: correction

## Claim 18: "on February 22, 2025, a more elaborate blockade saw co-founders chain the front doors of OpenAI's 3rd Street headquarters shut, leading to trespassing, unlawful assembly, and obstructing-business-operations charges"

Source: https://www.kqed.org/news/12066171/openai-critic-arrested-for-sf-protest-ahead-of-activist-groups-criminal-trial ; https://www.kron4.com/news/technology-ai/sf-jury-convicts-protester-who-blocked-openai-headquarters/
Source tier: mainstream
Source content: KQED: on February 22, 2025, Stop AI members "chained the front doors shut at OpenAI's San Francisco headquarters on 3rd Street near Chase Center"; charges were trespassing and offenses related to preventing business operations. KRON4/CBS conviction coverage (snippets): Wynd Kaufmyn convicted of "trespassing with intent to interfere with a business, unlawful assembly, and refusal to disburse at a riot."
Comparison: Date, chained doors, 3rd Street location, and the three charge categories (trespass, unlawful assembly, business obstruction) all confirmed across two independent outlets.
Decision: corroborated

## Claim 19: defendants "framed their trials as a public platform for the moratorium demand, pursuing a necessity defense"; scalar:sources[6].note — Reichstadter arrested for violating a court order; "criminal trial rescheduled to January 2026"

Source: https://www.kqed.org/news/12066171/openai-critic-arrested-for-sf-protest-ahead-of-activist-groups-criminal-trial
Source tier: mainstream
Source content: Reichstadter: "We have a right of necessity to take nonviolent direct action to stop an imminent threat to our lives"; the group described the trial as "the first time in human history where a jury of normal people are asked about the extinction threat that AI poses"; Reichstadter arrested for "allegedly violating a judge's order that barred him from the premises"; trial "pushed back to Jan. 29" (2026). Article dated December 5, 2025.
Comparison: Necessity defense, platform framing, court-order arrest, and January 2026 reschedule all match the cited KQED piece (which the note correctly dates December 2025 and labels secondary).
Decision: single-source

## Claim 20: Sanders and Ocasio-Cortez introduced the Artificial Intelligence Data Center Moratorium Act (March 2026; release March 25, 2026) — a federal moratorium on new AI data center construction with three lifting conditions; AI expansion framed as controlled by "billionaire Big Tech oligarchs"

Source: https://www.sanders.senate.gov/press-releases/news-sanders-ocasio-cortez-announce-ai-data-center-moratorium-act/
Source tier: primary
Source content: Press release dated March 25, 2026: "Artificial Intelligence (AI) Data Center Moratorium Act of 2026," introduced by Sen. Bernie Sanders (I-Vt.) and Rep. Alexandria Ocasio-Cortez (D-N.Y.) — "an immediate federal moratorium on AI data centers." Conditions: "AI is safe and effective — preventing executives in the AI industry from releasing harmful products"; economic gains benefit workers, not just wealthy tech owners; "AI does not increase electricity or utility prices, harm communities or destroy the environment." Quote: "We cannot sit back and allow a handful of billionaire Big Tech oligarchs to make decisions that will reshape our economy, our democracy and the future of humanity."
Comparison: Sponsors, date, bill name, the three conditions (entity's renderings track the release's wording), and the oligarchs quote all match the government primary source. Also covers scalar:origin and scalar:sources[4].note.
Decision: primary-sourced

## Claim 21: the Stop Data Centers Coalition — convened by Food & Water Watch, "500+ organizations from 47 states," including Greenpeace USA, Friends of the Earth, Our Revolution, and the Center for Constitutional Rights — sent a letter to Congress June 11, 2026 demanding a national moratorium on new data center approvals; Food & Water Watch organizing director Emily Wurth quoted ("the large and surging national movement")

Source: https://www.commondreams.org/news/stop-data-centers ; https://www.foodandwaterwatch.org/2026/06/11/500-groups-from-47-states-call-for-nationwide-ai-data-center-moratorium/
Source tier: primary
Source content: Common Dreams (June 11, 2026): "Over 500 organizations representing millions of people across the United States" from 47 states; signatories include Greenpeace USA, Friends of the Earth, Our Revolution, Center for Constitutional Rights; letter sent Thursday, June 11, 2026, demanding "a national moratorium on the approval and construction of new data centers"; Emily Wurth, Food & Water Watch organizing director: "The large and surging national movement to rein in runaway data center build-out was born at the grassroots level." Food & Water Watch's own release title: "500+ Groups from 47 States Call for Nationwide AI Data Center Moratorium."
Comparison: Convener, counts, named members, letter date/demand, and Wurth's title and quoted fragment all match the convener's own release plus one mainstream outlet. (A FedScoop search snippet renders the tally "more than 520 organizations from 48 states" — likely a later or differently-scoped count; the entity's figures match the convener's own release verbatim.) Body's "beginning with residents in communities already affected" is paraphrase outside the quotation marks and tracks the grassroots-origin sense of the quote. Also covers scalar:origin and scalar:sources[5].note.
Decision: corroborated

## Claim 22: "Stop AI members cite Geoffrey Hinton's extinction-risk warnings"

Source: no canonical source found
Source tier: none
Source content: stopai.info homepage fetch: "no — the page does not cite or quote Geoffrey Hinton or other AI researchers regarding extinction risk from AI." No fetched or snippet source shows Stop AI members invoking Hinton by name.
Comparison: The cross-reference to person-geoffrey-hinton resolves, and Stop AI's extinction-risk framing is well documented, but the specific claim that its members cite Hinton's warnings found no support in the org's own pages or coverage consulted. Not established as wrong — the audit reaches its limit.
Decision: uncorroborated
