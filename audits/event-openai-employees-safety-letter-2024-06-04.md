---
entity_id: event-openai-employees-safety-letter-2024-06-04
entity_hash: fc7e38867d594987824609c303ecaf0043f0dc3e
audit_date: 2026-08-31
pass: 1
status: corrections-pending
claims_total: 19
claims_corroborated: 11
claims_primary_sourced: 0
claims_single_source: 3
claims_uncorroborated: 2
open_corrections: 3
sources_consulted:
  - https://righttowarn.ai/
  - https://www.cnbc.com/2024/05/14/openai-co-founder-ilya-sutskever-says-he-will-leave-the-startup.html
  - https://www.usnews.com/news/business/articles/2024-05-14/openai-co-founder-ilya-sutskever-announces-departure-from-chatgpt-maker
  - https://www.cnn.com/2024/05/14/tech/openai-chief-scientist-ilya-sutskever-departs/index.html
  - https://www.cbsnews.com/sanfrancisco/news/openai-exec-jan-leike-resigns-says-safety-has-taken-a-backseat/
  - https://www.cnn.com/2024/05/17/tech/openai-exec-exits-safety-concerns
  - https://fortune.com/2024/05/17/openai-researcher-resigns-safety
  - https://www.cnbc.com/2024/05/17/openai-superalignment-sutskever-leike.html
  - https://www.bloomberg.com/news/articles/2024-05-17/openai-dissolves-key-safety-team-after-chief-scientist-ilya-sutskever-s-exit
  - https://www.techmeme.com/240517/p20
  - https://x.com/sama/status/1791936857594581428
  - https://www.engadget.com/sam-altman-is-embarrassed-that-openai-threatened-to-revoke-equity-if-exiting-employees-wouldnt-sign-an-nda-184000462.html
  - https://www.cnbc.com/2024/05/24/openai-sends-internal-memo-releasing-former-employees-from-non-disparagement-agreements-sam-altman.html
  - https://www.bloomberg.com/news/articles/2024-05-24/openai-releases-former-staffers-from-nondisparagement-clauses
  - https://www.cnbc.com/2024/06/04/openai-open-ai-risks-lack-of-oversight.html
  - https://time.com/6985504/openai-google-deepmind-employees-letter/
  - https://aiwi.org/case-studies/right-to-warn-and-daniel-kokotajlo/
  - https://en.wikipedia.org/wiki/Turing_Award
  - https://en.wikipedia.org/wiki/Timnit_Gebru
---

## Claim 1: "On 4 June 2024, current and former employees of OpenAI and Google DeepMind published 'A Right to Warn about Advanced Artificial Intelligence'" (+ frontmatter `date: 2024-06-04`, `location: online`)

Source: https://righttowarn.ai/
Source tier: primary
Source content: Letter site shows publication date "June 4th, 2024"; signatory list spans former OpenAI, former/current Google DeepMind. Corroborated by CNBC 2024-06-04 ("Current and former OpenAI employees warn of AI's 'serious risks' and lack of oversight") and Time coverage of the same date.
Comparison: Date, online publication, and publisher population all match the letter's own site plus mainstream coverage. Covers frontmatter scalars `date` and `location`.
Decision: corroborated

## Claim 2: Seven named signatories — "Jacob Hilton, Daniel Kokotajlo, Ramana Kumar, Neel Nanda, William Saunders, Carroll Wainwright, and Daniel Ziegler" (+ scalar:sources[0].note signatory list)

Source: https://righttowarn.ai/
Source tier: primary
Source content: Named signatories on the letter: "Jacob Hilton (formerly OpenAI), Daniel Kokotajlo (formerly OpenAI), Ramana Kumar (formerly Google DeepMind), Neel Nanda (currently Google DeepMind, formerly Anthropic), William Saunders (formerly OpenAI), Carroll Wainwright (formerly OpenAI), Daniel Ziegler (formerly OpenAI)". AIWI case study independently lists the same seven.
Comparison: Body list and the `sources[0].note` scalar (path `sources[0].note`) both match the letter exactly.
Decision: corroborated

## Claim 3: "Six more signed anonymously — four current and two former OpenAI employees"

Source: https://righttowarn.ai/
Source tier: primary
Source content: "Six anonymous signatories: four currently at OpenAI, two formerly at OpenAI". AIWI: "six anonymous OpenAI members (four current, two former)".
Comparison: Exact match on count and split.
Decision: corroborated

## Claim 4: "the explicit endorsement of Turing Award winners Geoffrey Hinton and Yoshua Bengio and computer scientist Stuart Russell"

Source: https://righttowarn.ai/
Source tier: primary
Source content: Endorsed by "Yoshua Bengio, Geoffrey Hinton, Stuart Russell". AIWI: "endorsed by notable AI experts Yoshua Bengio, Geoffrey Hinton, and Stuart Russell".
Comparison: Match on all three endorsers.
Decision: corroborated

## Claim 5: "The letter named three AI risk categories... further entrenchment of existing inequalities; manipulation and misinformation; and loss of control of autonomous AI systems, with the potential for human extinction"

Source: https://righttowarn.ai/
Source tier: primary
Source content: "Further entrenchment of existing inequalities, to manipulation and misinformation, to the loss of control of autonomous AI systems potentially resulting in human extinction".
Comparison: Body's three categories are a faithful close paraphrase of the letter's own text; VentureBeat headline independently reflects the extinction framing.
Decision: corroborated

## Claim 6: The four principles as enumerated in the body (no nondisparagement enforcement on safety matters; anonymous reporting channels; culture of open criticism; whistleblower protection for public disclosure after internal channels fail)

Source: https://righttowarn.ai/
Source tier: primary
Source content: Letter's four asks: (1) not enforce agreements prohibiting risk-related criticism nor retaliate; (2) facilitate verifiably anonymous processes to report risk concerns to boards, regulators, independent organizations; (3) support a culture of open criticism while protecting IP; (4) not retaliate against public sharing of risk-related confidential information after other processes have failed.
Comparison: Body's four numbered principles match the letter's four principles in order and substance.
Decision: corroborated

## Claim 7: Edges — `participating_people` [person-daniel-kokotajlo, person-geoffrey-hinton, person-neel-nanda]; `related_events` [event-timnit-gebru-firing-google-2020-12-02]

Source: https://righttowarn.ai/
Source tier: primary
Source content: Kokotajlo and Nanda appear as named signatories; Hinton as endorser (per Claim 2/4 source content).
Comparison: All edge-target files exist in the corpus and each points at the correct person/event given their documented roles in the letter; the Gebru-event edge is the body's declared structural precedent (interpretive linkage — the edge-correctness check is that the target is the right entity, which it is).
Decision: corroborated

## Claim 8: "On 15 May 2024, Ilya Sutskever — OpenAI's co-founder and chief scientist, and one of the two heads of its Superalignment team — announced he was leaving"

Source: https://www.cnbc.com/2024/05/14/openai-co-founder-ilya-sutskever-says-he-will-leave-the-startup.html
Source tier: mainstream
Source content: CNBC, CNN, AP (via usnews.com), and Axios all dated 2024-05-14: Sutskever "announced his decision on the social media site X on Tuesday, May 14, 2024"; AP: "Jan Leike, who had been co-leader with Sutskever of OpenAI's Superalignment team". His own X post (x.com/ilyasut) is dated 14 May 2024.
Comparison: Role facts (co-founder, chief scientist, Superalignment co-head) match. The announcement date token is wrong: sources uniformly say 14 May 2024, body says 15 May 2024. Single correct replacement: "15 May 2024" → "14 May 2024". Note the adjacent "Two days later" phrase then needs prose adjustment (see Claim 10) — flag to Researcher if beyond single-token replacement.
Decision: correction

## Claim 9: Jan Leike "published a thread on X that stated: 'Over the past years, safety culture and processes have taken a backseat to shiny products'" and "wrote that he had 'reached a breaking point'" (+ scalar:sources[3].note)

Source: https://www.cbsnews.com/sanfrancisco/news/openai-exec-jan-leike-resigns-says-safety-has-taken-a-backseat/
Source tier: mainstream
Source content: "Jan Leike posted on X on May 17, 2024, stating 'safety culture and processes have taken a backseat to shiny products'... Leike wrote that he had been 'disagreeing with OpenAI leadership about the company's core priorities for quite some time, until we finally reached a breaking point.'" Entity-cited Fortune (2024-05-17) carries the same thread.
Comparison: Both quotes and the 17 May thread date match across CBS, CNN, Fast Company, and Fortune. The `sources[3].note` scalar (Fortune as source for the resignation and quote) is consistent.
Decision: corroborated

## Claim 10: "Two days later, on 17 May 2024, Jan Leike, the other head of the Superalignment team, resigned"

Source: https://www.usnews.com/news/business/articles/2024-05-14/openai-co-founder-ilya-sutskever-announces-departure-from-chatgpt-maker
Source tier: mainstream
Source content: AP (2024-05-14): "Jan Leike... also said on X on Tuesday that he has left the startup" (Tuesday = 14 May). CBS/CNN (2024-05-17) frame the 17 May posts as his resignation statement: "OpenAI leader Jan Leike resigns" / "Exec quits over concerns".
Comparison: Canonical sources disagree on the resignation-announcement date: AP places his "I resigned" statement on 14 May (same day as Sutskever), while 17 May coverage treats the detailed thread as the resignation moment. The body's "resigned [on 17 May], two days later" cannot be resolved to a single correct token from these sources; the 17 May date is solid only for the thread (Claim 9). Per the two-sources-disagree rule, no winner is picked.
Decision: uncorroborated

## Claim 11: "OpenAI confirmed that it had dissolved the Superalignment team, integrating its members across other research groups"

Source: https://www.cnbc.com/2024/05/17/openai-superalignment-sutskever-leike.html
Source tier: mainstream
Source content: CNBC (2024-05-17) "OpenAI dissolves Superalignment AI safety team"; Bloomberg (2024-05-17) "OpenAI Dissolves Key Safety Team After Chief Scientist Ilya Sutskever's Exit"; coverage: "Rather than maintaining the team as a separate entity, OpenAI chose to integrate its members into the company's overall research efforts."
Comparison: Dissolution and member-integration both match two independent mainstream sources.
Decision: corroborated

## Claim 12: "reporting in major outlets revealed that OpenAI had been requiring departing employees to sign unusually broad nondisparagement agreements — agreements whose language threatened to claw back vested equity"

Source: https://www.techmeme.com/240517/p20
Source tier: mainstream
Source content: Vox (Kelsey Piper, 2024-05-17): "OpenAI has an unusual, extremely restrictive off-boarding agreement with a lifelong nondisparagement commitment; those who don't sign it lose all vested equity." CNBC (2024-05-24): OpenAI had made "former employees choose between signing a non-disparagement agreement that would never expire, or keeping their vested equity in the company."
Comparison: The NDA structure and vested-equity threat match Vox's originating report and CNBC's follow-up.
Decision: corroborated

## Claim 13: "on 24 May 2024, Sam Altman sent an internal memo stating that the nondisparagement clauses would be removed from standard departure paperwork, that former employees would be released from existing obligations, and acknowledging that the equity-clawback language had been a mistake"

Source: https://www.cnbc.com/2024/05/24/openai-sends-internal-memo-releasing-former-employees-from-non-disparagement-agreements-sam-altman.html
Source tier: mainstream
Source content: CNBC (published Friday 2024-05-24): "OpenAI on Thursday sent an internal memo releasing former employees from non-disparagement agreements... The internal memo, which was viewed by CNBC, was sent to former employees and shared with current ones... 'OpenAI has not canceled, and will not cancel, any Vested Units.'" Bloomberg dated the release 2024-05-24 as "the day after it was sent." The mistake-acknowledgment was Altman's separate 18 May X post: "This is on me and one of the few times I've been genuinely embarrassed running OpenAI" (x.com/sama, Engadget).
Comparison: Three token errors in the body: (1) the memo was sent by OpenAI, not by Sam Altman ("Sam Altman sent an internal memo" → "OpenAI sent an internal memo"); (2) it was sent Thursday 23 May 2024, reported 24 May ("on 24 May 2024" → "on 23 May 2024"); (3) the equity-clawback mistake-acknowledgment was Altman's 18 May X statement, not part of the memo. The memo-content claims (clauses removed from standard paperwork, former employees released) are accurate. Note: the `sources[2].note` scalar gets this right ("OpenAI's internal memo... and Sam Altman's acknowledgment") — the drift is body-only. Rewiring the acknowledgment into a separate sentence requires prose judgment → Editor should `[editor-flag]` to Researcher rather than single-token-replace.
Decision: correction

## Claim 14: "it arrived ten days after Sam Altman had been forced by public pressure to retract the nondisparagement agreements" / "The letter followed ten days later" / "OpenAI's pre-emptive NDA reversal ten days before publication" (three occurrences)

Source: https://www.cnbc.com/2024/05/24/openai-sends-internal-memo-releasing-former-employees-from-non-disparagement-agreements-sam-altman.html
Source tier: mainstream
Source content: Memo sent Thursday 23 May 2024 (CNBC "on Thursday", published Friday 24 May; Bloomberg: released "the day after it was sent"); letter published 4 June 2024 (righttowarn.ai).
Comparison: 23 May → 4 June is twelve days (eleven even if anchored on the 24 May report date); no reading yields ten. Single correct replacement given the best-source memo date: "ten days" → "twelve days" at all three body locations (Background intro ¶1, end of Background section, final Significance ¶). Consistent with the Claim 13 date correction.
Decision: correction

## Claim 15: "OpenAI's spokesperson responded that the company was proud of its 'track record providing the most capable and safest AI systems' and emphasised the importance of rigorous debate" (+ scalar:sources[1].note quote)

Source: https://time.com/6985504/openai-google-deepmind-employees-letter/
Source tier: mainstream
Source content: Search-confirmed spokesperson statement (given to the New York Times): "proud of our track record providing the most capable and safest AI systems and believe in our scientific approach to addressing risk... We agree that rigorous debate is crucial given the significance of this technology."
Comparison: The quoted fragment and the rigorous-debate framing match; body's truncation is faithful. Confirmed via one canonical source's text in-session (the entity-cited CNBC 2024-06-04 article is 403 on direct fetch and its full text was not independently retrievable), so one-source support. Covers the `sources[1].note` scalar.
Decision: single-source

## Claim 16: "It was the first time current employees of OpenAI had publicly and collectively raised concerns about the company's safety culture in a structured advocacy document"

Source: no canonical source found
Source tier: none
Source content: Coverage consulted (Time, Bloomberg, AIWI, CNBC titles/snippets) describes the letter and notes all current-OpenAI signatories were anonymous, but none asserts it was the *first* such collective public action by current employees.
Comparison: A contested-"first" claim requires ≥2 canonical sources per the source rule; none found affirming firstness. Not a finding of error — the audit reached its limit on this superlative.
Decision: uncorroborated

## Claim 17: "Hinton and Bengio — two of the three 2018 Turing Award winners"

Source: https://en.wikipedia.org/wiki/Turing_Award
Source tier: tiebreaker
Source content: "The 2018 award was shared by three recipients: Yoshua Bengio, Geoffrey Hinton, Yann LeCun... 'for conceptual and engineering breakthroughs that have made deep neural networks a critical component of computing.'"
Comparison: Matches — Hinton and Bengio are two of the three 2018 winners. Named-entity/public-record fact, Wikipedia-alone sufficient per the type-based canonicality rule; one source.
Decision: single-source

## Claim 18: "the forced departure of Timnit Gebru from Google's Ethical AI team in December 2020... its downstream institution was DAIR"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: tiebreaker
Source content: "Gebru's employment at Google ended in December 2020. She co-led 'a team on the ethics of artificial intelligence'... On December 2, 2021, Gebru launched the Distributed Artificial Intelligence Research Institute (DAIR)."
Comparison: The date (December 2020), team, and DAIR-founding linkage match. Date-of-public-event and definitional facts, Wikipedia-alone sufficient; the contested fired-vs-resigned framing is the linked event entity's own audit surface, not this edge's.
Decision: single-source

## Claim 19: scalar:sources[2].note — "OpenAI's internal memo releasing former employees from nondisparagement obligations and Sam Altman's acknowledgment that the equity-clawback threat had been a mistake"

Source: https://x.com/sama/status/1791936857594581428
Source tier: primary
Source content: Altman (X, 18 May 2024): "we have never clawed back anyone's vested equity, nor will we do that... this is on me and one of the few times I've been genuinely embarrassed running OpenAI"; CNBC (24 May): OpenAI sent the internal memo releasing former employees.
Comparison: The scalar correctly attributes the memo to OpenAI and the mistake-acknowledgment to Altman as distinct facts — both confirmed (Altman's own post is primary for his statement; CNBC/Engadget corroborate).
Decision: corroborated
