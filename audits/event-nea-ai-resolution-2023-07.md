---
entity_id: event-nea-ai-resolution-2023-07
entity_hash: 242b1d3ae2cb0d1fa8af439df861a42043cb07d1
audit_date: 2026-08-31
pass: 1
status: supported
claims_total: 22
claims_corroborated: 6
claims_primary_sourced: 5
claims_single_source: 5
claims_uncorroborated: 6
open_corrections: 0
sources_consulted:
  - https://www.edweek.org/teaching-learning/nea-president-sympathizes-with-teachers-who-want-to-quit-heres-her-advice/2023/07
  - https://www.nea.org/resource-library/artificial-intelligence-education/ii-task-force-and-its-work
  - https://www.edweek.org/teaching-learning/nea-approves-ai-guidance-but-its-vital-for-educators-to-tread-carefully/2024/07
  - https://www.nea.org/nea-today/all-news-articles/2023-nea-representative-assembly-freedom-learn-spotlight
  - https://www.nea.org/about-nea/media-center/press-releases/nea-delegates-approve-measure-recommend-policy-actions-use-ai
  - https://www.nea.org/nea-today/all-news-articles/teaching-age-ai
  - https://en.wikipedia.org/wiki/National_Education_Association
  - https://en.wikipedia.org/wiki/ChatGPT
  - https://www.cta.org/event/nea-representative-assembly-2023
  - https://okea.org/for-members/2023-nea-representative-assembly/
  - https://blog.csba.org/nea-ai/
---

Connective type (Event): claim surface is edges + hard specifics per `AUDITOR.md § Type-shape`. The Significance section's movement-arc prose ("anchor point," "democratic ratification surface," "2023 was the year AI labor governance moved…") is interpretation over the audited facts and receives no decisions; its embedded cross-references are covered in Claim 1.

## Claim 1: edges — `participating_orgs: org-national-education-association`; body cross-refs to org-national-education-association, event-african-content-moderators-union-founding-vote-2023-05-01, org-wga, org-sag-aftra, org-concept-art-association

Source: repo entity files; all session sources below
Source tier: primary
Source content: All five referenced entity files exist in `product/entities/` and denote the referenced entities (mechanical resolution). NEA's participation in its own Representative Assembly is confirmed by every source consulted (e.g. NEA: "Approximately 6,000 delegates—representing state and local affiliates, student members, and retired members—will be in Orlando this year").
Comparison: All edges resolve to the correct corpus entities; the sole `participating_orgs` edge is trivially confirmed (the NEA convened the event).
Decision: corroborated

## Claim 2: scalar:date `2023-07` + scalar:location `Orlando, Florida` + body "102nd Representative Assembly, convened in July 2023 at the Orange County Convention Center in Orlando, Florida"

Source: https://www.nea.org/nea-today/all-news-articles/2023-nea-representative-assembly-freedom-learn-spotlight ; https://www.nea.org/about-nea/media-center/press-releases/remarks-prepared-delivery-kim-anderson-executive-director-national-education-association-102nd ; https://www.cta.org/event/nea-representative-assembly-2023 ; https://okea.org/for-members/2023-nea-representative-assembly/
Source tier: primary
Source content: NEA: "Approximately 6,000 delegates…will be in Orlando this year from July 3-6"; NEA press pages are titled "…to the 102nd Representative Assembly"; CTA/OKEA affiliate pages (via search) place the 2023 RA at the Orange County Convention Center, Orlando ("The 2023 NEA Human and Civil Rights Awards Dinner was held on Sunday, July 2, 2023 at the Orange County Convention Center in Orlando, Florida").
Comparison: Date (July 2023), location (Orlando), ordinal (102nd), and venue (OCCC) each confirmed by ≥2 independent sources (NEA primary pages + union-affiliate/database pages).
Decision: corroborated

## Claim 3: "NEA President Becky Pringle responded from the assembly floor by announcing that the NEA would convene a Task Force on Artificial Intelligence in Education" (+ scalar:sources[0].note, same announcement)

Source: https://www.edweek.org/teaching-learning/nea-president-sympathizes-with-teachers-who-want-to-quit-heres-her-advice/2023/07 ; https://www.nea.org/about-nea/media-center/press-releases/nea-delegates-approve-measure-recommend-policy-actions-use-ai
Source tier: primary
Source content: EdWeek (July 2023) reports Pringle's plan to convene the task force; NEA press release: "At the 2023 Representative Assembly, NEA President Becky Pringle called for the creation of an AI task force."
Comparison: Announcement at the 2023 RA confirmed by NEA's own press release and contemporaneous EdWeek coverage.
Decision: corroborated

## Claim 4: "the topic of artificial intelligence repeatedly surfaced in delegate discussions across the multi-day gathering"

Source: https://www.edweek.org/teaching-learning/nea-approves-ai-guidance-but-its-vital-for-educators-to-tread-carefully/2024/07
Source tier: mainstream
Source content: "NEA President Becky Pringle convened the task force…after the topic repeatedly came up."
Comparison: Body's "repeatedly surfaced in delegate discussions" is a fair paraphrase of "the topic repeatedly came up" at the 2023 RA; only one source carries it.
Decision: single-source

## Claim 5: Pringle quotes — "The reality is it's here, and it's not going anywhere." and "What do we want to say about that? What do we know about it?"

Source: https://www.edweek.org/teaching-learning/nea-president-sympathizes-with-teachers-who-want-to-quit-heres-her-advice/2023/07
Source tier: mainstream
Source content: Both quotes appear verbatim in the EdWeek article: "The reality is it's here, and it's not going anywhere." / "What do we want to say about that? What do we know about it?"
Comparison: Living-person quoted statements; matched verbatim in one mainstream source (the article the body cites).
Decision: single-source

## Claim 6: "the task force would bring together external technology-sector representatives, international experts, and labor union partners alongside educators"

Source: https://www.edweek.org/teaching-learning/nea-president-sympathizes-with-teachers-who-want-to-quit-heres-her-advice/2023/07
Source tier: mainstream
Source content: Pringle: "bring together groups of people—from external folks, from technology [sectors], from around the world who are ahead of us in the U.S., and other labor unions."
Comparison: Body is a fair paraphrase of Pringle's quoted composition envelope; one source.
Decision: single-source

## Claim 7: "Approximately 6,000 delegates…were present" (2023 RA)

Source: https://www.nea.org/nea-today/all-news-articles/2023-nea-representative-assembly-freedom-learn-spotlight ; https://www.cta.org/event/nea-representative-assembly-2023
Source tier: primary
Source content: NEA: "Approximately 6,000 delegates—representing state and local affiliates, student members, and retired members—will be in Orlando this year"; affiliate/search coverage repeats "approximately 6,000 educators."
Comparison: Delegate count matches across NEA's own coverage and affiliate pages.
Decision: corroborated

## Claim 8: "…representing 2.8 million educators across every US state and territory"

Source: https://en.wikipedia.org/wiki/National_Education_Association ; https://www.nea.org/nea-today/all-news-articles/2023-nea-representative-assembly-freedom-learn-spotlight ; https://www.nea.org/about-nea/media-center/press-releases/nea-delegates-approve-measure-recommend-policy-actions-use-ai
Source tier: tiebreaker
Source content: Wikipedia: "The NEA has 2.8 million members" ("2,839,808 (2024)"); NEA's own 2023 RA article says delegates represent "nearly 3 million members"; NEA press release boilerplate says "more than 3 million" members.
Comparison: The exact 2.8M figure rests on Wikipedia alone (tiebreaker-only class for quantitative claims) while NEA's own surfaces say "nearly/more than 3 million" — divergent roundings, not a token contradiction with a single correct replacement; "every US state and territory" as a delegate-representation specific was not confirmed in any fetched source (Wikipedia does not assert universal state coverage).
Decision: uncorroborated

## Claim 9: NEA is "the largest labor union in the United States"

Source: https://en.wikipedia.org/wiki/National_Education_Association
Source tier: tiebreaker
Source content: "The National Education Association (NEA) is the largest labor union in the United States."
Comparison: Named-entity definitional fact — Wikipedia-alone sufficient per the source rule; one canonical source.
Decision: single-source

## Claim 10: the 2023 RA "produced the first formal AI governance action by the largest labor union in the United States"

Source: no canonical source found
Source tier: none
Source content: No fetched source asserts the 2023 RA action was the NEA's (or any largest-US-union's) *first* formal AI governance action; sources establish it as the origin of the NEA's AI task force and 2024 policy statement, not a first-ever superlative.
Comparison: Contested "first" claim (tiebreaker-only class, needs ≥1 canonical source beyond Wikipedia); none found either way.
Decision: uncorroborated

## Claim 11: "generative AI — launched into mainstream awareness by ChatGPT's November 2022 release"

Source: https://en.wikipedia.org/wiki/ChatGPT
Source tier: tiebreaker
Source content: "Originally released on November 30, 2022, the product uses large language models…"
Comparison: Date of a public event — Wikipedia-alone sufficient; November 2022 matches.
Decision: single-source

## Claim 12: "fewer than 20 US states had issued any AI guidance to schools at all"

Source: https://www.nea.org/about-nea/media-center/press-releases/nea-delegates-approve-measure-recommend-policy-actions-use-ai
Source tier: primary
Source content: "As of this release, fewer than 20 states have issued guidance about the use of AI in education."
Comparison: Matches the body's cited source. Note the release is dated July 2024 while the body frames the fact in the 2023-RA context — if fewer than 20 had issued guidance by mid-2024, the same held in 2023, so the claim is entailed.
Decision: primary-sourced

## Claim 13: "Following the July 2023 assembly, President Pringle formally appointed the Task Force on AI in Education in fall 2023"

Source: https://www.nea.org/resource-library/artificial-intelligence-education/ii-task-force-and-its-work
Source tier: primary
Source content: "NEA President Becky Pringle appointed members of the Task Force on Artificial Intelligence in Education in fall 2023."
Comparison: Exact match on the cited NEA page (NEA's own resource library; corroborating NEA RA-guidance text is not independent of it).
Decision: primary-sourced

## Claim 14: "chaired by Secretary-Treasurer Noel Candelaria"

Source: https://www.edweek.org/teaching-learning/nea-approves-ai-guidance-but-its-vital-for-educators-to-tread-carefully/2024/07 ; https://www.nea.org/sites/default/files/2024-07/updated-ra-guidance-ppt-as-of-7-2-24b.pdf
Source tier: primary
Source content: EdWeek: task force "chaired by Noel Candelaria, 'a special education teacher…from El Paso, Texas, and secretary-treasurer of the NEA'"; NEA RA guidance (via search): "A task force of NEA members, led by NEA Secretary-Treasurer Noel Candelaria."
Comparison: Chair identity and title confirmed by NEA's own RA material and mainstream coverage — two independent sources.
Decision: corroborated

## Claim 15: "virtual sessions from November 2023 through April 2024 and convened in person in Chicago on March 1, 2024, with two virtual subgroups addressing AI uses in education and professional support, and ethics, equity, bias, and intellectual property"

Source: https://www.nea.org/resource-library/artificial-intelligence-education/ii-task-force-and-its-work
Source tier: primary
Source content: "The Task Force convened for online meetings between November 2023 and April 2024" and "met in person on March 1, 2024, in Chicago." "…two virtual subgroup meetings—one focused on AI uses in education and professional support for educators and one focused on ethics, equity, bias, and intellectual property."
Comparison: Session window, Chicago date, and both subgroup remits match the cited NEA page exactly.
Decision: primary-sourced

## Claim 16: "The group consulted subject-matter experts and engaged educators at national conferences across its seven-month run"

Source: https://www.nea.org/resource-library/artificial-intelligence-education/ii-task-force-and-its-work
Source tier: primary
Source content: "The Task Force also met with experts, reviewed research and other resources, and analyzed existing NEA policy"; members "facilitated three sessions" at the Leadership Summit, "led one session" at the Higher Education Conference, and "two sessions at the NEA ESP Conference."
Comparison: Expert consultation and national-conference engagement confirmed on the cited NEA page; "seven-month run" is a fair gloss of fall 2023–spring 2024.
Decision: primary-sourced

## Claim 17: "The Task Force Report was published on June 26, 2024"

Source: https://blog.csba.org/nea-ai/ ; https://www.nea.org/sites/default/files/2024-06/report_of_the_nea_task_force_on_artificial_intelligence_in_education_ra_2024.pdf
Source tier: none
Source content: CSBA blog (via search): the NEA task force report "was published in late June, 2024"; the NEA report PDF sits under a `/2024-06/` path; an open hearing on the policy statement was held June 24, 2024. No source states June 26 specifically.
Comparison: "Late June 2024" partially confirms but the specific June 26 date token was not found in any fetched source; no contradicting date either.
Decision: uncorroborated

## Claim 18: "on July 4, 2024, …delegates to the 103rd NEA Representative Assembly in Philadelphia voted by voice to approve" the AI policy statement

Source: https://www.edweek.org/teaching-learning/nea-approves-ai-guidance-but-its-vital-for-educators-to-tread-carefully/2024/07 ; https://www.nea.org/about-nea/media-center/press-releases/nea-delegates-approve-measure-recommend-policy-actions-use-ai
Source tier: primary
Source content: EdWeek: "The roughly 6,000 delegates voted by voice to approve a policy statement on July 4, the first day of business at the union's annual representative assembly"; NEA (via press release/search): delegates "gathered at the Philadelphia Convention Center" for the NEA's "103rd Representative Assembly."
Comparison: Date (July 4, 2024), voice vote, ordinal (103rd), and Philadelphia all confirmed across NEA primary and mainstream sources.
Decision: corroborated

## Claim 19: "approximately 7,000 delegates" (2024 RA)

Source: https://www.nea.org/about-nea/media-center/press-releases/nea-delegates-approve-measure-recommend-policy-actions-use-ai ; https://www.edweek.org/teaching-learning/nea-approves-ai-guidance-but-its-vital-for-educators-to-tread-carefully/2024/07
Source tier: primary
Source content: NEA press release: "Nearly 7,000 educator delegates gathered at the Philadelphia Convention Center"; EdWeek: "The roughly 6,000 delegates voted by voice."
Comparison: Two canonical sources disagree (NEA ~7,000 vs EdWeek ~6,000); the body matches the primary source but the rule is not to pick a winner when canonical sources conflict.
Decision: uncorroborated

## Claim 20: "the NEA's first-ever policy statement on artificial intelligence in education"

Source: https://www.nea.org/nea-today/all-news-articles/teaching-age-ai
Source tier: primary
Source content: "NEA members approved the first-ever policy statement on the use of artificial intelligence (AI) in education over the summer."
Comparison: "First-ever" confirmed by NEA's own coverage (one primary source; EdWeek does not state firstness).
Decision: primary-sourced

## Claim 21: scalar:sources[1].note — the NEA task-force page is "primary source for…the chair (Noel Candelaria, Secretary-Treasurer)"

Source: https://www.nea.org/resource-library/artificial-intelligence-education/ii-task-force-and-its-work
Source tier: primary
Source content: This session's fetch of the page returned "The page does not identify who chaired the Task Force"; all other elements the note attributes to the page (fall 2023 appointment, Nov 2023–Apr 2024 sessions, March 1 2024 Chicago meeting, two subgroups) were confirmed on it.
Comparison: The note's claim that this page sources the chair was not confirmed — the chair may be named on a sibling page of the web report not fetched here, so this is recorded as unconfirmed rather than an error; the chair fact itself is corroborated (Claim 14). Fix location if acted on: `sources[1].note`.
Decision: uncorroborated

## Claim 22: scalar:sources[2].note — EdWeek 2024 carries "Pringle's stated rationale that delegates were bringing forward AI issues and she wanted members 'to really dig into this'"

Source: https://www.edweek.org/teaching-learning/nea-approves-ai-guidance-but-its-vital-for-educators-to-tread-carefully/2024/07
Source tier: mainstream
Source content: Two targeted fetches of the article did not surface the phrase "to really dig into this"; the article's stated rationale is that Pringle "convened the task force…after the topic repeatedly came up," and it confirms "The need for a policy statement from the NEA arose last year during the 2023 representative assembly" (the note's other element).
Comparison: The note's quote attribution was not confirmed in the fetched article text (extraction may be incomplete on a partially gated page), so it is recorded as unconfirmed rather than an error. Fix location if acted on: `sources[2].note`.
Decision: uncorroborated
