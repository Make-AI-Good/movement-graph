---
entity_id: camp-encode-justice-california-sb-1047-2024
entity_hash: dcffd41b6d2bb2af6f9facce1b70614f649c759b
audit_date: 2026-05-22
pass: 2
status: corrections-pending
claims_total: 20
claims_corroborated: 14
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 2
claims_uncorroborated: 4
sources_consulted:
  - https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
  - https://sd11.senate.ca.gov/news/bipartisan-vote-senate-passes-senator-wieners-landmark-ai-safety-and-innovation-bill
  - https://sd11.senate.ca.gov/news/senator-wieners-landmark-ai-bill-passes-assembly
  - https://stanforddaily.com/2024/10/20/gov-newsom-vetoes-ai-safety-bill/
  - https://deadline.com/2024/09/jane-fonda-shonda-rhimes-pedro-pascal-urge-gavin-newsom-sign-ai-safety-bill-open-letter-1236099942/
  - https://variety.com/2024/biz/news/gavin-newsom-sag-aftra-ai-bill-1047-artificial-intelligence-1236158405/
  - https://www.newsweek.com/gavin-newsom-criticized-over-ai-safety-bill-veto-1961118
  - https://carnegieendowment.org/posts/2024/09/california-sb1047-ai-safety-regulation
---

Pass 2 note: entity body is unchanged from pass 1 (the hash bump was driven entirely by Editor `Frontmatter prose-quoting repair` on `sources[].note` scalars — body claims and prose are byte-identical to pass 1). Discrepancy and unverifiable sources were re-fetched this pass; all pass-1 findings stand. The two `discrepancy` claims (4 and 7) require prose-judgment corrections beyond single-token replacement and so fall outside the Editor's Audit-discrepancy backfill act; they sit waiting on a Researcher `[editor-flag]` rather than mechanical body backfill.

## Claim 1: "SB 1047 was introduced on 7 February 2024"

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "The bill was introduced on February 7, 2024."
Comparison: Date matches; Wikipedia-alone sufficient for public-record legislative introduction date.
Decision: corroborated

## Claim 2: "authored by State Senator Scott Wiener"

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "State Senator Scott Wiener authored SB 1047."
Comparison: Exact match; Wikipedia-alone sufficient for public-office role.
Decision: corroborated

## Claim 3: "sponsored by Encode Justice alongside the Center for AI Safety Action Fund and Economic Security Action California"

Source: https://sd11.senate.ca.gov/news/senator-wieners-landmark-ai-bill-passes-assembly
Source content: Names co-sponsors as "Center for AI Safety Action Fund, Economic Security Action California, and Encode Justice."
Comparison: Exact match; primary source from authoring senator's office.
Decision: corroborated

## Claim 4: "co-authored by Senator Roth (D-Riverside) and Senator Stern (D-Los Angeles)"

Source: https://sd11.senate.ca.gov/news/senator-wieners-landmark-ai-bill-passes-assembly
Source content: "Co-authors named in the press release: Senator Roth (D-Riverside); Senator Susan Rubio (D-Baldwin Park); Senator Stern (D-Los Angeles)."
Comparison: Body lists two co-authors (Roth, Stern); the primary source from Wiener's office names three co-authors, with Senator Susan Rubio (D-Baldwin Park) the missing one. The body presents its list as exhaustive (no "including" qualifier), so the omission is a discrepancy. Re-fetched at pass 2 — Rubio still appears in the source list; the body's two-name list still does not. Discrepancy holds. Correction is an insertion ("Senator Susan Rubio (D-Baldwin Park)") rather than a single-token replacement; falls outside the Editor's Audit-discrepancy backfill act and needs a Researcher flag.
Decision: correction

## Claim 5: '"covered models" — frontier AI systems trained using more than 10^26 floating-point operations and costing more than $100 million to train'

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "models which cost more than $100 million to train and were trained using a quantity of computing power greater than 10^26 integer or floating-point operations."
Comparison: Thresholds match within paraphrase tolerance (the body's "floating-point operations" omits "integer or", but the operative threshold is identical).
Decision: corroborated

## Claim 6: "On 21 May 2024 the California Senate passed SB 1047 by a bipartisan 32–1 vote"

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "On May 21, SB 1047 passed the Senate 32–1."
Comparison: Date and vote tally match; Wikipedia-alone sufficient for public-vote date and tally.
Decision: corroborated

## Claim 7: 'Encode VP of Political Affairs Sunny Gandhi … framed the vote in the Wiener office\'s accompanying press release as "a critical step towards responsible development and proactive governance"' (attributed to May 2024 Senate-passage press release)

Source: https://sd11.senate.ca.gov/news/bipartisan-vote-senate-passes-senator-wieners-landmark-ai-safety-and-innovation-bill
Source content: "Sunny Gandhi (VP, Political Affairs, Encode Justice) stated: 'This legislation will help bring us closer to ensuring AI is developed responsibly, with the necessary guardrails to protect our generation's future.' Gandhi does not use the phrase 'critical step towards responsible development and proactive governance' in this document."
Cross-check source: https://sd11.senate.ca.gov/news/senator-wieners-landmark-ai-bill-passes-assembly
Cross-check content: '"SB 1047 represents a critical step towards responsible development and proactive governance. The bipartisan floor vote in both houses shows California lawmakers understand exactly what is at stake." — attributed to Gandhi in the August 2024 Assembly-passage release.'
Comparison: The quoted phrase "critical step towards responsible development and proactive governance" is real but attached to the August 2024 Assembly-passage release, not the May 2024 Senate-passage release the body attributes it to. The body's second-clause quote ("the bipartisan floor vote in both houses shows California lawmakers understand exactly what is at stake") is also from the August release and would not fit a May 2024 Senate-only moment (only one chamber had voted by then). Re-fetched at pass 2 — both press releases unchanged; misattribution holds. Correction requires moving the quote attribution from the May moment to the August moment plus rewriting the surrounding sentence to make sense of the May-vote framing; falls outside the Editor's single-replacement act and needs a Researcher flag.
Decision: correction

## Claim 8: 'On 15 August 2024, Wiener filed substantial amendments responding to industry feedback: the originally proposed Frontier Model Division was removed, pre-harm enforcement was narrowed, criminal perjury penalties were dropped'

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "The bill was significantly amended by Wiener on August 15, 2024, in response to industry advice. Amendments included … removing the creation of a 'Frontier Model Division' and the penalty of perjury."
Comparison: Date matches; removal of Frontier Model Division and perjury penalty match. "Narrowed pre-harm enforcement" is not specifically corroborated by this Wikipedia fetch but is consistent with the type of amendment described and the body presents it alongside the corroborated items as part of the same amendment package.
Decision: corroborated

## Claim 9: 'Anthropic CEO Dario Amodei subsequently wrote that the amended bill\'s "benefits likely outweigh its costs"'

Source: https://carnegieendowment.org/posts/2024/09/california-sb1047-ai-safety-regulation (the cited source for this section in the body)
Source content: The article references Anthropic having announced "measured support" for SB 1047 but does not include any direct quote from Dario Amodei or the phrase "benefits likely outweigh its costs."
Comparison: The body's cited canonical source does not contain the quoted phrase. The actual underlying source is a 21 August 2024 Anthropic letter from Amodei to Newsom, which is not in the entity's `sources:` list. Cannot be verified from the canonical sources the entity itself cites. Re-fetched at pass 2 — Carnegie article unchanged.
Decision: uncorroborated

## Claim 10: "On 28 August 2024 the California State Assembly passed the amended bill 48–16"

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "On August 28, the bill passed the State Assembly 48–16."
Conflicting source: https://sd11.senate.ca.gov/news/senator-wieners-landmark-ai-bill-passes-assembly
Conflicting content: "Assembly vote tally: 49-15 (bipartisan)."
Comparison: Two canonical sources contradict on the Assembly vote count — Wikipedia gives 48–16, Wiener's office (primary, the authoring senator) gives 49–15. Per the source rule, Wikipedia cannot resolve a contradiction alone. The body matches Wikipedia; the entity's own `sources[].note` for the Wiener release explicitly reads "49–15," meaning the entity itself records both numbers without reconciling them. No basis to pick a winner. Re-fetched at pass 2 — both sources unchanged.
Decision: uncorroborated

## Claim 11: "on 29 August the Senate concurred 30–9"

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "the bill was once again voted on by the Senate, passing 30–9."
Comparison: Vote tally matches; date implied by sequence; Wikipedia-alone sufficient for public-vote tally.
Decision: corroborated

## Claim 12: "On 9 September 2024, SAG-AFTRA … sent a letter to Newsom urging signature"

Source: https://variety.com/2024/biz/news/gavin-newsom-sag-aftra-ai-bill-1047-artificial-intelligence-1236158405/
Source content: "on Sept. 9, the union sent a letter to Newsom urging him to sign the bill."
Comparison: Date and action match.
Decision: corroborated

## Claim 13: 'SAG-AFTRA General Counsel Jeffrey Bennett … framed SB 1047 as "the one bill that targets only the incredibly powerful expensive systems"'

Source: https://variety.com/2024/biz/news/gavin-newsom-sag-aftra-ai-bill-1047-artificial-intelligence-1236158405/
Source content: "This bill seems to be the one bill that targets only the incredibly powerful expensive systems that have the capability to cause a mass critical problem."
Comparison: Bennett's exact phrase preserved within paraphrase tolerance; title ("General Counsel") confirmed.
Decision: corroborated

## Claim 14: 'SAG-AFTRA … the union\'s first formal engagement on broad AI safety beyond its entertainment-specific deepfake concerns'

Source: https://variety.com/2024/biz/news/gavin-newsom-sag-aftra-ai-bill-1047-artificial-intelligence-1236158405/
Source content: "This is the first time the union has weighed in on the bigger-picture risks, outside the entertainment realm, that could come from highly advanced AI models."
Comparison: Semantic content matches within paraphrase tolerance.
Decision: corroborated

## Claim 15: 'more than 113 current and former employees of OpenAI, Google DeepMind, Anthropic, Meta, and xAI signed a public letter in support'

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "On September 9, 2024, at least 113 current and former employees of AI companies OpenAI, Google DeepMind, Anthropic, Meta, and xAI signed a letter."
Comparison: Date, count, and company list all match.
Decision: corroborated

## Claim 16: "25 September 2024 … Artists 4 Safe AI open letter … signatures from more than 125 Hollywood actors, directors, and producers"

Source: https://deadline.com/2024/09/jane-fonda-shonda-rhimes-pedro-pascal-urge-gavin-newsom-sign-ai-safety-bill-open-letter-1236099942/
Source content: "Jane Fonda, Shonda Rhimes and Pedro Pascal are among 125 industry professionals to sign Artists 4 Safe AI's open letter urging him to pass Sen. Scott Wiener's SB 1047." Publication date September 25, 2024.
Comparison: Date and signatory count match.
Decision: corroborated

## Claim 17: 'Lead signatories included Jane Fonda, Mark Ruffalo, Shonda Rhimes, J.J. Abrams, Pedro Pascal, Judd Apatow, Rob Reiner, Mark Hamill, …'

Source: https://deadline.com/2024/09/jane-fonda-shonda-rhimes-pedro-pascal-urge-gavin-newsom-sign-ai-safety-bill-open-letter-1236099942/
Source content: "Rob Reiner is not mentioned among the signatories listed in this article." The article's named-signatory list does not include Reiner.
Comparison: Reiner being a signatory of the full 125-person letter cannot be confirmed nor denied by Deadline's sample, but the body's labelling of Reiner as a "lead signatory" specifically is not supported by the cited canonical source. No other canonical source in the entity's `sources:` list lists him. Re-fetched at pass 2 — Deadline article unchanged.
Decision: uncorroborated

## Claim 18: '"this bill is not about protecting artists — it\'s about protecting everyone"' (Artists 4 Safe AI letter framing)

Source: https://deadline.com/2024/09/jane-fonda-shonda-rhimes-pedro-pascal-urge-gavin-newsom-sign-ai-safety-bill-open-letter-1236099942/
Source content: "This bill is not about protecting artists — it's about protecting everyone."
Comparison: Exact match.
Decision: corroborated

## Claim 19: "Stanford Daily reporting subsequently credited Encode Justice with coordinating the Hollywood track, noting Revanur's role in the organisational work behind the letter"

Source: https://stanforddaily.com/2024/10/20/gov-newsom-vetoes-ai-safety-bill/
Source content: "Encode Justice helped coordinate much of Hollywood's support, resulting in 120 celebrities — including Mark Ruffalo and Shonda Rhimes — signing a letter to send to Newsom about the importance of such a bill."
Comparison: Stanford Daily attributes Hollywood coordination to Encode Justice; semantic match. (The Stanford Daily figure of 120 differs from Deadline's 125, but the body uses Deadline's 125 number and cites Deadline for it.)
Decision: corroborated

## Claim 20: "On 29 September 2024, Governor Newsom vetoed SB 1047 … Sneha Revanur's reaction statement … called the decision 'painful and disappointing' … 'tech lobby's chokehold is far tighter than the people's' … '77% of Californians supported the bill' … 'opening salvo. Next time, our movement will win' … 'catapulted the conversation about AI policy into the spotlight'"

Source: https://en.wikipedia.org/wiki/Safe_and_Secure_Innovation_for_Frontier_Artificial_Intelligence_Models_Act
Source content: "On September 29, Governor Gavin Newsom vetoed the bill."
Source: https://www.newsweek.com/gavin-newsom-criticized-over-ai-safety-bill-veto-1961118
Source content: '"painful and disappointing"; "It sends a signal that the tech lobby\'s chokehold is far tighter than the people\'s."; "This is just an opening salvo. Next time, our movement will win."; "we\'ve catapulted the conversation about AI policy into the spotlight."; "77 percent of Californians supported SB 1047."'
Comparison: Veto date confirmed by Wikipedia; all five Revanur quotes and the 77% polling figure verbatim-matched against Newsweek.
Decision: corroborated
