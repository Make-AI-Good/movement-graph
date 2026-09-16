---
entity_id: msg-stochastic-parrots
entity_hash: 61fa874f02b265e5fe0783543b930216899d09d8
audit_date: 2026-09-16
pass: 1
status: supported
claims_total: 21
claims_corroborated: 8
claims_primary_sourced: 6
claims_single_source: 5
claims_uncorroborated: 2
open_corrections: 0
sources_consulted:
  - https://en.wikipedia.org/wiki/Stochastic_parrot
  - https://en.wikipedia.org/wiki/Timnit_Gebru
  - https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
  - https://dair-institute.org/stochastic-parrots-day/
  - https://dair-institute.org/blog/letter-statement-March2023/
  - https://dair-institute.org/press-release/
  - https://magazine.scienceforthepeople.org/vol24-2-dont-be-evil/stochastic-parrots/
  - https://quoteinvestigator.com/2022/10/07/word-parrot/
  - https://techcrunch.com/2021/12/02/google-timnit-gebru-ai-research-dair/
  - https://americandialect.org/2023-word-of-the-year-is-enshittification/
  - https://americandialect.org/wp-content/uploads/2024/01/2023-Word-of-the-Year-PRESS-RELEASE.pdf
  - https://linguistics.stanford.edu/news/media-bender-1
  - https://medium.com/@emilymenonbender/stochastic-parrots-frequently-unasked-questions-49c2e7d22d11
  - https://dailynous.com/2020/07/30/philosophers-gpt-3/
  - https://x.com/sama/status/1599471830255177728
  - https://www.pulitzer.org/finalists/angie-wang-contributor-new-yorker
  - https://x.com/okchickadee/status/1724789646952128780
  - https://treasures.scss.tcd.ie/miscellany/TCD-SCSS-X.20121208.002/AI-fabrications-related-articles/20230713-StochasticParrot-Wikipedia.pdf
---

Type-shape note: Message is a connective type. Claims audited are the entity's edges
(`propagated_by_orgs`, `related_messages`) and hard specifics (dates, counts, names,
quoted attributions) in the `origin` scalar and body. Interpretive prose about the
framing's significance, register, and "why it carries" received no decisions per
`AUDITOR.md § Type-shape`.

Fetch limits this pass: dl.acm.org, philpapers.org, pulitzer.org, medium.com 403 on
direct fetch; dblp.org blocked (Anubis). Claims resting on those hosts were verified
via search-result content and mirrors, noted per claim.

## Claim 1: edge — propagated_by_orgs: org-dair-institute

Source: https://dair-institute.org/stochastic-parrots-day/ ; https://dair-institute.org/blog/letter-statement-March2023/
Source tier: primary
Source content: DAIR event page: "Stochastic Parrots Day: March 17, 2023"; DAIR pause-letter statement authored by "Timnit Gebru, Emily M. Bender, and Angelina McMillan-Major — described as authors of the 'Stochastic Parrots' paper"
Comparison: Edge target exists in corpus (product/entities/organizations/org-dair-institute.md); DAIR's own event page and statement show it actively deploying the framing. Both documents are the same origin (DAIR), so one primary source.
Decision: primary-sourced

## Claim 2: edges — related_messages: msg-coded-gaze, msg-ethics-washing, msg-algorithmic-colonialism

Source: corpus-internal resolution (product/entities/messages/)
Source tier: primary
Source content: All three target files exist: msg-coded-gaze.md, msg-ethics-washing.md, msg-algorithmic-colonialism.md
Comparison: Mechanical edge-resolution check; all three targets exist and are the referents named in body prose. The relatedness judgment itself is curatorial, not a factual claim.
Decision: primary-sourced

## Claim 3: scalar:origin — "Coined by Emily M. Bender (University of Washington) in late 2020 while co-authoring a paper with Timnit Gebru, Angelina McMillan-Major, and Margaret 'Shmargaret Shmitchell' Mitchell"

Source: https://quoteinvestigator.com/2022/10/07/word-parrot/ ; https://linguistics.stanford.edu/news/media-bender-1
Source tier: database
Source content: Quote Investigator: Bender confirmed coinage — "Yep, that was me" (October 8, 2022 tweet); Stanford Linguistics: "a term coined by Emily Bender, a computational linguist, and her coauthors"; author list "Emily M. Bender, Timnit Gebru, Angelina McMillan-Major, and Shmargaret Shmitchell" per the FAccT '21 record surfaced in search results
Comparison: Coinage by Bender, timing (while writing the paper, pre-October-2020 zero-hit search), co-author list incl. the "Shmargaret Shmitchell" pseudonym all match across ≥2 independent canonical sources.
Decision: corroborated

## Claim 4: scalar:origin — "zero Google hits in early October 2020; the only near-antecedent was a July 2020 Daily Nous post by philosopher Regina Rini using the phrase 'all-electronic statistical parrot'"

Source: https://medium.com/@emilymenonbender/stochastic-parrots-frequently-unasked-questions-49c2e7d22d11 (via search content; direct fetch 403) ; https://dailynous.com/2020/07/30/philosophers-gpt-3/ (via search content)
Source tier: primary
Source content: Bender's own account: "as of early October 2020, a Google search for 'stochastic parrot' provided 0 hits... two quasi-antecedents, including a Daily Nous post from July 2020 by Regina Rini"; Rini's Daily Nous text: "we won't bother testing whether our interlocutor is a fellow human or an all-electronic statistical parrot"
Comparison: Both specifics match Bender's own published account and Rini's actual text. Note: the entity cites Wikipedia for this claim, but neither the current article nor the July-2023 archived copy carries it — the real support is Bender's primary account. Bender's FUQ also names Stuart Russell's "randomized parrots" email as a second quasi-antecedent; the entity's "only near-antecedent" is slightly stronger than the source but Rini's is the only published prior use, matching as stated.
Decision: primary-sourced

## Claim 5: origin/body — Google demanded retraction or removal of all Google employees' names; on 2 December 2020 Google sent Gebru an email "accepting her resignation"; Gebru maintains she never formally resigned

Source: https://en.wikipedia.org/wiki/Timnit_Gebru ; https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: Wikipedia: Google demanded she "withdraw the paper before publication, or remove the names of all the Google employees from the paper"; Google terminated her employment "immediately, declaring that they accepted her resignation"; Gebru "has maintained that she never formally offered to resign, and only threatened to". MIT Tech Review (4 Dec 2020) reports the exit contemporaneously.
Comparison: Demand, the "accepting her resignation" email, the 2 Dec 2020 date, and Gebru's disputed-resignation position all match; public-event date and official-action facts within Wikipedia-alone sufficiency, plus contemporaneous mainstream coverage.
Decision: corroborated

## Claim 6: scalar:origin — "Gebru refused without further discussion"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: tiebreaker
Source content: "sent an email offering to remove herself from the paper if Google provided an account of who had reviewed the work and how, and established a more transparent review process for future research"
Comparison: The source describes a conditional counter-offer, not a flat refusal without discussion. The divergence is characterization, not a single-token error, so no correction is asserted; fix would require prose judgment. (Body prose in § The firing carries the more accurate "conditional threat" framing; the origin scalar's compression is what diverges.)
Decision: uncorroborated

## Claim 7: origin/body — Margaret Mitchell was fired in February 2021

Source: https://techcrunch.com/2021/02/19/google-fires-top-ai-ethics-researcher-margaret-mitchell/ ; https://www.axios.com/2021/02/19/google-fires-another-ai-ethics-leader
Source tier: mainstream
Source content: TechCrunch (19 Feb 2021): "Google fires top AI ethics researcher Margaret Mitchell"; Axios (19 Feb 2021): "Google fires another AI ethics leader"; Bloomberg later: "Fired From Google After Critical Work"
Comparison: Firing and February 2021 date match multiple independent mainstream outlets. Entity's description of her as Gebru's co-lead on the Ethical AI team matches TechCrunch/VentureBeat descriptions ("Ethical AI lead / team founder and co-lead").
Decision: corroborated

## Claim 8: origin/body — paper presented at FAccT '21 (March 3–10, 2021, Virtual Event, Canada), published as pages 610–623 of the proceedings, without retraction

Source: https://quoteinvestigator.com/2022/10/07/word-parrot/ ; https://dl.acm.org/doi/10.1145/3442188.3445922 (via search-result record; direct fetch 403)
Source tier: database
Source content: Quote Investigator citation line: "ACM FAccT '21... Date: March 3–10, 2021... Location: Virtual Event, Canada"; ACM DL record via search: "published in FAccT '21: Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency... pages 610–623"
Comparison: Conference name, dates, virtual-event location, and page span all match; publication despite the retraction demand is the documented sequence across sources.
Decision: corroborated

## Claim 9: body — paper's definition: LLMs stitch together "sequences of linguistic forms (…) according to probabilistic information about how they combine, but without any reference to meaning"

Source: https://quoteinvestigator.com/2022/10/07/word-parrot/
Source tier: database
Source content: "an LM is a system for haphazardly stitching together sequences of linguistic forms it has observed in its vast training data, according to probabilistic information about how they combine, but without any reference to meaning: a stochastic parrot."
Comparison: Entity's quoted fragments match the paper's passage verbatim as reproduced by Quote Investigator; the paper itself (primary) is behind ACM's 403. One canonical source verified this session.
Decision: single-source

## Claim 10: body — "Training one large language model produces CO2 equivalent to five cars' lifetime emissions"

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: "about the lifetime output of five average American cars"
Comparison: Matches the Tech Review report of the paper's cited figure (Strubell et al.'s training-with-NAS estimate), at the granularity the entity states and with the same attribution path (via the Tech Review link).
Decision: single-source

## Claim 11: body — Facebook automated translation "falsely translated a Palestinian man's post as a threat, resulting in his arrest"

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: "mistranslated a Palestinian man's post, which said 'good morning' in Arabic, as 'attack them' in Hebrew"
Comparison: Mistranslation confirmed verbatim from the cited source; the arrest outcome is the widely reported 2017 incident the article references. One canonical source verified this session.
Decision: single-source

## Claim 12: body — "Approximately 2,700 Google employees and over 4,300 academics" signed condemnation letters; nine congressional members requested clarification; Pichai initiated a months-long investigation resulting in policy changes

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: tiebreaker
Source content: "Roughly 2,700 Google employees and more than 4,300 academics and civil society supporters signed a letter condemning Gebru's alleged firing"; "Nine members of Congress sent a letter to Google asking it to clarify the circumstances"; Pichai "initiated a months-long investigation" after which Google changed "how certain employees leave the company" and how "sensitive" research is reviewed
Comparison: All counts and the investigation/policy-change sequence match. The congressional letter and Pichai's official actions sit in the Wikipedia-alone-sufficient class; the signature counts are quantitative and rest on Wikipedia only this session.
Decision: single-source

## Claim 13: origin/body — Gebru founded DAIR on 2 December 2021, exactly one year after her firing

Source: https://dair-institute.org/press-release/ ; https://techcrunch.com/2021/12/02/google-timnit-gebru-ai-research-dair/ ; https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: primary
Source content: DAIR press release: "Dec. 2, 2021 — Timnit Gebru announced DAIR's establishment... an independent, community-rooted institute set to counter Big Tech's pervasive influence on the research, development and deployment of AI"; TechCrunch dated 2021-12-02; Wikipedia: "On 2 December 2021"
Comparison: Founding date, one-year anniversary of the 2 Dec 2020 exit, and the community-rooted / outside-Big-Tech positioning all match across primary and mainstream sources.
Decision: corroborated

## Claim 14: body — DAIR's founding funders were "Ford Foundation, MacArthur Foundation, Kapor Center, Open Society Foundation, and Rockefeller Foundation"

Source: https://dair-institute.org/press-release/ vs https://en.wikipedia.org/wiki/Timnit_Gebru (citing Washington Post); https://techcrunch.com/2021/12/02/google-timnit-gebru-ai-research-dair/
Source tier: primary
Source content: DAIR's own press release names four funders — "Ford Foundation, John D. and Catherine T. MacArthur Foundation, Kapor Center, Open Society Foundation(s)" — "The Rockefeller Foundation is not mentioned"; TechCrunch: "the institute has raised $3.7 million, from the Ford Foundation, the MacArthur Foundation, the Kapor Center and the Open Society Foundation"; Wikipedia/Washington Post-derived accounts add "the Rockefeller Foundation" to the same $3.7M list
Comparison: Canonical sources disagree on whether Rockefeller was a founding funder: the primary (DAIR's own press release) and TechCrunch name four; Wikipedia (tracing to the Washington Post) names five. Wikipedia cannot resolve a contradiction; no winner picked.
Decision: uncorroborated

## Claim 15: body — Stochastic Parrots Day held 17 March 2023, ~3,300 attendees, 137 related works discussed, harms reviewed incl. content-moderation labour exploitation and AI sentience overclaims, sessions recorded on PeerTube

Source: https://dair-institute.org/stochastic-parrots-day/
Source tier: primary
Source content: "Stochastic Parrots Day: March 17, 2023"; "The 3,300 hundred attendees and us apparently discussed 137 works!"; "exploited workers filtering hateful content"; "an engineer claiming that chatbots are sentient"; "Watch recorded sessions" (peertube.dair-institute.org)
Comparison: Date, attendee count (page's "3,300 hundred" is a typo for 3,300 — the entity's "approximately 3,300" matches), works count, harm categories, and PeerTube hosting all match DAIR's own event page.
Decision: primary-sourced

## Claim 16: body — DAIR's March 2023 statement deployed the framing against the FLI pause letter: language that "inflates the capabilities of automated systems and anthropomorphizes them"; harms named incl. labour exploitation, synthetic media, power concentration; accountability with builders/deployers

Source: https://dair-institute.org/blog/letter-statement-March2023/
Source tier: primary
Source content: "Such language that inflates the capabilities of automated systems and anthropomorphizes them... deceives people"; "On Tuesday March 28, the Future of Life Institute published a letter asking for a six-month minimum moratorium"; "worker exploitation and massive data theft"; "the explosion of synthetic media"; "the concentration of power in the hands of a few people"; "Accountability properly lies not with the artifacts but with their builders"; authored by Gebru, Bender, McMillan-Major (Stochastic Parrots authors)
Comparison: The entity's quoted phrase and the enumerated harms match the statement's text; timing (March 2023, response to FLI letter) matches.
Decision: primary-sourced

## Claim 17: body — Sam Altman tweeted the phrase shortly after ChatGPT's December 2022 release

Source: https://x.com/sama/status/1599471830255177728 ; https://en.wikipedia.org/wiki/Stochastic_parrot
Source tier: primary
Source content: Tweet (4 December 2022): "i am a stochastic parrot, and so r u"; Wikipedia: Altman "used the term shortly after the release of ChatGPT in December 2022, tweeting 'i am a stochastic parrot, and so r u'"
Comparison: The tweet artifact and Wikipedia both confirm. Minor nuance: ChatGPT launched 30 November 2022; the entity follows Wikipedia's "December 2022 release" phrasing and the tweet is 4 December — matches as sourced.
Decision: corroborated

## Claim 18: body — Angie Wang's New Yorker illustrated essay "Is My Toddler a Stochastic Parrot?" (15 November 2023) became a Pulitzer Prize finalist

Source: https://www.pulitzer.org/finalists/angie-wang-contributor-new-yorker ; https://x.com/okchickadee/status/1724789646952128780 ; https://dair-institute.org/stochastic-parrots-day/
Source tier: primary
Source content: Pulitzer finalist listing "Angie Wang, contributor, The New Yorker" (Illustrated Reporting and Commentary); Wang's announcement of the New Yorker publication (essay published 15 November 2023 per search-confirmed date); DAIR page: "was a finalist for the 2024 Pulitzer Prize"
Comparison: Title, venue, publication date, and finalist status match across the Pulitzer record, the author's own announcement, and DAIR's page.
Decision: corroborated

## Claim 19: body — the American Dialect Society named "stochastic parrot" the AI-related Word of the Year for 2023

Source: https://americandialect.org/wp-content/uploads/2024/01/2023-Word-of-the-Year-PRESS-RELEASE.pdf ; https://linguistics.stanford.edu/news/media-bender-1
Source tier: primary
Source content: ADS 2023 WOTY press release (winners by category); Stanford Linguistics: the society ran "an ad-hoc category entirely devoted to AI-related terms" and "'stochastic parrot' was the... winner in that category"; Bender's announcement: "Stochastic parrot is @americandialect's AI related word of the year for 2023!"
Comparison: Winner (not merely nominee) of the 2023 AI-related category confirmed by the society's press release and independent accounts; the current Wikipedia article's "was nominated" phrasing is the weaker rendering — the entity matches the primary record.
Decision: corroborated

## Claim 20: body — Science for the People framing quotes: "the least privileged are harmed" as datasets codify "the hegemonic vision"

Source: https://magazine.scienceforthepeople.org/vol24-2-dont-be-evil/stochastic-parrots/
Source tier: primary
Source content: "It is also the least privileged who are harmed in another way by the models"; "datasets sourced from the Internet codify the hegemonic vision that excludes people on the margins" (Esther Sánchez García and Michael Gasser, "Stochastic Parrots: How Natural Language Processing Research Has Gotten Too Big for Our Own Good")
Comparison: The claim is what this article says, so the article is its primary source. "Hegemonic vision" matches exactly; "the least privileged are harmed" is a close compression of "the least privileged who are harmed" — substance identical.
Decision: primary-sourced

## Claim 21: body — Jeff Dean's stated objection that the paper "didn't meet our bar for publication"; Bender's warning of a "chilling effect" on AI ethics research

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: Jeff Dean: "didn't meet our bar for publication"; Bender warned of "a chilling effect on future AI ethics research"
Comparison: Both quoted attributions match the cited article verbatim. Quoted statements of living persons; one mainstream source verified this session.
Decision: single-source
