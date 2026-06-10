---
entity_id: person-sneha-revanur
entity_hash: 13820ee472edf67bab140773121d5c2f2491db41
audit_date: 2026-06-02
pass: 1
status: corroborated
claims_total: 8
claims_corroborated: 8
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 0
sources_consulted:
  - https://en.wikipedia.org/wiki/Sneha_Revanur
  - https://encodeai.org/
  - https://www.kqed.org/news/11982374/meet-the-19-year-old-from-silicon-valley-leading-the-youth-led-charge-on-ai
---

## Claim 1: scalar:affiliations[0].role "founder and president" (of Encode Justice)

Source: https://encodeai.org/
Source content: "Sneha Revanur's Role: 'Founder & President'"
Comparison: Encode Justice's own current site (post-rebrand to Encode AI) names Revanur as Founder & President. The role frontmatter scalar reads "founder and president" — case is the only difference, semantically identical.
Decision: corroborated

## Claim 2: "Founder and president of [Encode Justice]"

Source: https://encodeai.org/
Source content: "Sneha Revanur's Role: 'Founder & President'"
Comparison: Body's "Founder and president of Encode Justice" matches the org's self-attestation on its own site exactly (modulo "and" / "&").
Decision: corroborated

## Claim 3: "she founded in July 2020"

Source: https://encodeai.org/
Source content: "Founding Date: July 2020"
Comparison: Encode AI's own site states the founding date as July 2020. KQED secondary source corroborates 2020 ("founded in 2020"). Body matches exactly.
Decision: corroborated

## Claim 4: "as a 15-year-old"

Source: https://en.wikipedia.org/wiki/Sneha_Revanur
Source content: "Revanur founded Encode at age fifteen."
Comparison: Wikipedia states age 15 at founding. KQED secondary corroborates ("15 years old at the time of founding"). Body's "15-year-old" matches. (Per Wikipedia-alone rule: age at founding is a named-entity definitional fact about a public figure's role — within the Wikipedia-alone scope; KQED corroboration is bonus.)
Decision: corroborated

## Claim 5: "high school student"

Source: https://encodeai.org/
Source content: "Founder's Status at Founding: High school student"
Comparison: Encode AI's own site identifies her status at founding as "High school student." Wikipedia mentions she attended Evergreen Valley High School. Body's "high school student" matches.
Decision: corroborated

## Claim 6: "in San José, California"

Source: https://en.wikipedia.org/wiki/Sneha_Revanur
Source content: "born and raised in San Jose, California"
Comparison: Wikipedia confirms San José, California (Wikipedia uses "San Jose," body uses the accented "San José" — same place, accent is a stylistic variant). KQED corroborates: "the San José native." (Public-record location fact — Wikipedia-alone permissible.)
Decision: corroborated

## Claim 7: "initially as a campaign against California Proposition 25"

Source: https://en.wikipedia.org/wiki/Sneha_Revanur
Source content: "Revanur founded Encode at age fifteen, after coming across California Proposition 25, a ballot measure that would have replaced the use of cash bail statewide with pretrial risk assessment algorithms."
Comparison: Wikipedia confirms Proposition 25 was the originating trigger / initial focus for founding Encode. Body's "initially as a campaign against California Proposition 25" matches. (Wikipedia frames this as the founding trigger; "campaign against" is body paraphrase of opposition to a ballot measure that would have introduced algorithmic pretrial risk assessment — within paraphrase tolerance.)
Decision: corroborated

## Claim 8: scalar:sources[1].note "TIME100 AI 2023 profile of Revanur as Encode Justice founder"

Source: https://en.wikipedia.org/wiki/Sneha_Revanur
Source content: "In 2023, Revanur was the youngest individual named to TIME's inaugural list of the 100 most influential people in artificial intelligence."
Comparison: Wikipedia confirms TIME100 AI 2023 listing of Revanur. encodeai.org corroborates: "youngest person named to TIME's inaugural list of the 100 most influential voices in AI" (TIME100 AI was inaugurated in 2023). The "as Encode Justice founder" portion is implicit in the listing context (the TIME profile URL `time.com/collection/time100-ai/6310595/sneha-revanur/` is in the entity's sources; she is recognised in that profile as the Encode Justice founder, consistent with the Wikipedia and encodeai.org descriptions of her there).
Decision: corroborated
