---
entity_id: pub-pauseai-treaty-proposal
entity_hash: d4c1c688b6e47ec8a37429af27e01c68627f20ec
audit_date: 2026-06-03
pass: 1
status: discrepancy
claims_total: 27
claims_verified: 21
claims_discrepancy: 4
claims_unverifiable: 2
sources_consulted:
  - https://pauseai.info/proposal
  - https://pauseai.info/feasibility
  - https://pauseai.info/2023-oct
  - https://en.wikipedia.org/wiki/PauseAI
  - https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
  - https://pauseai.info/2025-february
  - https://www.elysee.fr/en/sommet-pour-l-action-sur-l-ia
  - https://en.wikipedia.org/wiki/AI_Action_Summit
  - https://impact.indiaai.gov.in/
  - https://en.wikipedia.org/wiki/India_AI_Impact_Summit_2026
---

## Claim 1: "currently marked 'Version: April 5th, 2026'"

Source: https://pauseai.info/proposal
Source content: "Version: April 5th, 2026"
Comparison: Exact match.
Decision: verified

## Claim 2: "the proposal opens with the demand to 'implement a temporary pause on the training of the most powerful general AI systems'"

Source: https://pauseai.info/proposal
Source content: "Implement a temporary pause on the training of the most powerful general AI systems, until we know how to build them safely and keep them under democratic control."
Comparison: Body quote matches the opening demand verbatim (truncated at the same clause break).
Decision: verified

## Claim 3: "The body of the proposal is organised in four named sections: *Treaty Measures*, *Effects of a Treaty*, *Other Measures*, and *Long-term Policy*."

Source: https://pauseai.info/proposal
Source content: H2 section structure in order — "Getting to a Treaty", "Treaty Measures", "Effects of a treaty", "Other measures that effectively slow down AI", "Long term policy", "Help us achieve this".
Comparison: The body claims four named sections and enumerates them; the actual page has five substantive sections plus a "Help us achieve this" CTA. The body omits "Getting to a Treaty" from its enumeration, and the count "four" undercounts even the substantive sections (five).
Decision: discrepancy

## Claim 4: AISA "modelled explicitly on the International Atomic Energy Agency"

Source: https://pauseai.info/proposal
Source content: "Inspired by the International Atomic Energy Agency (IAEA), this agency will be responsible for:"
Comparison: The source uses "Inspired by"; the body uses "modelled explicitly on". Paraphrase tolerance: the IAEA reference is explicit and the modelling framing is the proposal's own stated frame for the agency.
Decision: verified

## Claim 5: AISA has four named responsibilities — approving deployments/training runs, granting incremental approval for more powerful AI, specifying oversight requirements, verifying compliance.

Source: https://pauseai.info/proposal
Source content: "Granting approval for major deployments and training runs of AIs that are judged not to pose a threat to humanity"; "Granting approval for the creation of more powerful AI once sufficient progress has been made on the technical problems of AI safety and control"; "Specifying requirements for the oversight of AI training runs"; "Verifying that the decisions of the agency are being honored."
Comparison: The four-responsibility enumeration matches the source 1:1 in content, paraphrase tolerance.
Decision: verified

## Claim 6: "verifying compliance through GPU tracking, energy monitoring, data-centre inspections, semiconductor-facility inspections, and chip-location tracking"

Source: https://pauseai.info/proposal
Source content: "tracking GPUs, incentivizing whistleblowers, energy monitoring, data center inspections, financial intelligence, semiconductor manufacturing facility inspections, AI developer inspections, chip location tracking and chip-based reporting."
Comparison: The body presents a five-item verification-methods list without a hedging "including" / "such as"; the source enumerates nine methods. The body's list is a strict subset and is structurally presented as the complete list. Four methods are omitted (incentivizing whistleblowers, financial intelligence, AI developer inspections, chip-based reporting).
Decision: discrepancy

## Claim 7: scalar:sources[0].note "the four AISA verification methods of GPU tracking, energy monitoring, data-centre inspections, and chip-location tracking"

Source: https://pauseai.info/proposal
Source content: "tracking GPUs, incentivizing whistleblowers, energy monitoring, data center inspections, financial intelligence, semiconductor manufacturing facility inspections, AI developer inspections, chip location tracking and chip-based reporting."
Comparison: The frontmatter scalar makes a numeric claim ("the four AISA verification methods") and enumerates four. The source lists nine. The scalar's count is wrong on its face and the enumeration is a partial subset. Fix path: replace "the four AISA verification methods of [four-item list]" with a non-counting paraphrase or the full nine-item list.
Decision: discrepancy

## Claim 8: "a 'sufficiently large coalition' of opposing countries should be able to block the deployment of any AI system above the superhuman threshold"

Source: https://pauseai.info/proposal
Source content: "A sufficiently large coalition of opposing countries can veto any deployment of a safe superhuman AI system."
Comparison: Paraphrase tolerance — the quoted phrase matches and the surrounding sense is preserved.
Decision: verified

## Claim 9: "the model weights and access to such systems should be kept 'under the stewardship of the AISA' until inter-state agreement on deployment has been reached"

Source: https://pauseai.info/proposal
Source content: "Until a deployment is agreed, the weights and access to the AI must be kept strictly under the stewardship of the AISA."
Comparison: The quoted phrase and the until-deployment-is-agreed framing both match.
Decision: verified

## Claim 10: scope — "general-purpose AI systems — language models and agentic systems — and would, on the proposal's own framing, 'usually not affect narrow AI systems, like image recognition'"

Source: https://pauseai.info/proposal
Source content: "usually not affect narrow AI systems, like image recognition systems used for diagnosing cancer."
Comparison: The body's quoted phrase matches the source verbatim (truncated at the same clause boundary).
Decision: verified

## Claim 11: "a ban on training AI systems on copyrighted material"

Source: https://pauseai.info/proposal
Source content: "Ban training of AI systems on copyrighted material"
Comparison: Paraphrase tolerance, exact-content match.
Decision: verified

## Claim 12: "the imposition of criminal-acts liability on AI model creators when their systems are used to commit crimes"

Source: https://pauseai.info/proposal
Source content: "Hold AI model creators liable for criminal acts committed using their AI systems."
Comparison: Paraphrase tolerance, exact-content match.
Decision: verified

## Claim 13: Long-term Policy section names "limiting publication of training algorithms and runtime-efficiency improvements, and considering limits on hardware-capability advances"

Source: https://pauseai.info/proposal
Source content: "Limit publication of training algorithms / runtime improvements"; "Limit capability advancements of computational resources"
Comparison: Both demands present; body's "considering limits" framing is paraphrastic but accurate to the long-term-policy framing of the section.
Decision: verified

## Claim 14: "the proposal cites 64–69% U.S. public support for a pause on frontier AI development"

Source: https://pauseai.info/proposal
Source content: "64%–69%" supporting a pause.
Comparison: Exact numeric match.
Decision: verified

## Claim 15: "PauseAI's May 2023 founding in Utrecht by Joep Meindertsma"

Source: https://en.wikipedia.org/wiki/PauseAI
Source content: "The movement was established in Utrecht in May 2023" by "software entrepreneur Joep Meindertsma".
Comparison: Date, place, and founder all match. Per MISSION.md § Auditor source rules, the founding-date/place/founder triple is a definitional public-record fact for which Wikipedia alone is sufficient; the proposal's own pages corroborate as well.
Decision: verified

## Claim 16: "Maxime Fournes as the CEO under whom the current 2026 revision was published"

Source: https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
Source content: Announcement, dated December 2, 2025, that Maxime Fournes "will be taking on the role of CEO at PauseAI Global", having previously served as Director of PauseAI France.
Comparison: Fournes-as-CEO is supported and the announcement date (Dec 2025) precedes the April 5 2026 revision stamp.
Decision: verified

## Claim 17: scalar:sources[6].note "PauseAI's late-2025 announcement of Maxime Fournes as CEO, succeeding Joep Meindertsma as founder"

Source: https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
Source content: Announcement of Fournes as CEO of PauseAI Global (Dec 2, 2025); the announcement does not name Meindertsma nor describe a succession.
Comparison: Fournes-as-CEO and the late-2025 timing are supported by the source. The "succeeding Joep Meindertsma as founder" portion is not stated in the cited announcement — it is inference from background knowledge that Meindertsma was the founder. Per the source rule, an inference not stated in the source should not be attributed to that source.
Decision: unverifiable

## Claim 18: "PauseAI's first public action was to protest in front of Microsoft's Brussels lobbying office in May 2023"

Source: https://en.wikipedia.org/wiki/PauseAI
Source content: "PauseAI's first public action was to protest in front of Microsoft's Brussels lobbying office in May 2023".
Comparison: Body paraphrases as "small Brussels Microsoft action May 2023"; source confirms occurrence and date.
Decision: verified

## Claim 19: "the October 21 2023 international protest"

Source: https://pauseai.info/2023-oct
Source content: PauseAI's own page for the October 21, 2023 international-protest day, including the framing "For our entire proposal, see here".
Comparison: Date and event-type match the entity's own cited primary source.
Decision: verified

## Claim 20: "the November 2023 AI Safety Summit at Bletchley Park" and "Bletchley Park November 2023" protest

Source: https://en.wikipedia.org/wiki/PauseAI
Source content: "In November of the same year, they protested outside the inaugural AI Safety Summit at Bletchley Park"
Comparison: Date, location, and event match. Public-event date is Wikipedia-alone-sufficient per the source rule.
Decision: verified

## Claim 21: "the thirteen-country May 13 2024 mobilisation ahead of Seoul"

Source: https://en.wikipedia.org/wiki/PauseAI
Source content: "On 13 May 2024, protests were held across thirteen countries before the AI Seoul Summit"
Comparison: Date, country count, and Seoul-summit anchoring all match.
Decision: verified

## Claim 22: "the February 2025 Paris mobilisation" and "Paris AI Action Summit" Feb 2025

Source: https://www.elysee.fr/en/sommet-pour-l-action-sur-l-ia ; https://pauseai.info/2025-february ; https://en.wikipedia.org/wiki/AI_Action_Summit
Source content: Summit was held at the Grand Palais, Paris, 10–11 February 2025; PauseAI organized protests Feb 8–11, 2025, across multiple cities.
Comparison: Month, year, and protest-mobilisation framing all match across multiple canonical sources.
Decision: verified

## Claim 23: "the February 2026 India AI Impact Summit" / "New Delhi summit"

Source: https://impact.indiaai.gov.in/ ; https://en.wikipedia.org/wiki/India_AI_Impact_Summit_2026
Source content: Summit held at Bharat Mandapam, New Delhi; main event 19–20 February 2026 within a 16–21 February window.
Comparison: Location, month, and year all match. Public-event date is Wikipedia-alone-sufficient per the source rule, and the government site corroborates.
Decision: verified

## Claim 24: "the November 2024 Anthropic-and-others international wave"

Source: no canonical source found
Source content: Wikipedia article on PauseAI does not mention an Anthropic protest wave in November 2024; PauseAI's summit page does not provide a primary source for this specific event.
Comparison: No canonical source consulted in this audit substantiates a November 2024 Anthropic-targeted protest wave. The claim may be true but is unsourced in the entity's `sources:` and not found in independent canonical sources.
Decision: unverifiable

## Claim 25: "the 2025 Google DeepMind London protest"

Source: no canonical source found
Source content: Wikipedia article on PauseAI does not mention a 2025 Google DeepMind London protest; the entity's own cited sources do not provide a primary reference.
Comparison: As Claim 24 — claim may be true but is unsourced and not found in independent canonical sources during this audit. Per the source rule for "recent events" Wikipedia is tiebreaker-only and at least one other canonical source is required.
Decision: unverifiable

## Claim 26: "what the spokespeople carry into press appearances on outlets including NBC, Bloomberg, KQED, the New York Times, and Fortune ([Wikipedia])"

Source: https://en.wikipedia.org/wiki/PauseAI
Source content: Wikipedia article body and references cite Wired, Politico, The Guardian, The New York Times, euronews, VentureBeat, TIME, ABC7 San Francisco, and The Verge; NBC, Bloomberg, KQED, and Fortune do not appear in the article body or references on the date consulted.
Comparison: The body explicitly attributes the five-outlet list to Wikipedia via an inline citation. The cited source supports only one of the five outlets (NYT, and only in references rather than article text). Bloomberg, NBC, KQED, and Fortune are not present in the cited source.
Decision: discrepancy

## Claim 27: scalar:sources[5].note "the New York Times, Bloomberg, NBC, and KQED coverage of the protest track the proposal anchored"

Source: https://en.wikipedia.org/wiki/PauseAI
Source content: Article body and references list Wired, Politico, The Guardian, NYT, euronews, VentureBeat, TIME, ABC7 SF, The Verge; Bloomberg, NBC, and KQED are not present.
Comparison: The frontmatter source-note attributes coverage from a four-outlet list to the Wikipedia article. Wikipedia carries NYT only (and only in references). The other three outlets (Bloomberg, NBC, KQED) are not attested in the cited source. Same factual issue as Claim 26, located in a different scalar (sources[5].note) — fix to the body alone would leave this frontmatter assertion stale.
Decision: discrepancy
