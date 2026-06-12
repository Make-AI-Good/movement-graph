---
entity_id: voice-fran-drescher
entity_hash: 34f50b42fd93c27c8f286070bf7ee2626f2059df
audit_date: 2026-06-12
pass: 2
status: supported
claims_total: 39
claims_corroborated: 10
claims_primary_sourced: 2
claims_single_source: 23
claims_uncorroborated: 4
open_corrections: 0
sources_consulted:
  - https://en.wikipedia.org/wiki/Fran_Drescher
  - https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike
  - https://en.wikipedia.org/wiki/2024%E2%80%932025_SAG-AFTRA_video_game_strike
  - https://en.wikipedia.org/wiki/No_Fakes_Act
  - https://deadline.com/2023/07/fran-drescher-the-complete-sag-aftra-strike-speech-video-hollywood-1235437816/
  - https://deadline.com/2023/07/sag-aftra-fran-drescher-were-being-victimized-by-a-greedy-entity-1235437292/
  - https://deadline.com/2023/07/actors-strike-press-conference-livestream-sag-aftra-1235437177/
  - https://deadline.com/2023/10/no-fakes-act-ai-limits-senate-1235571538/
  - https://deadline.com/2024/09/jane-fonda-shonda-rhimes-pedro-pascal-urge-gavin-newsom-sign-ai-safety-bill-open-letter-1236099942/
  - https://www.cbsnews.com/news/hollywood-actors-strike-today-2023-sag-aftra/
  - https://variety.com/2021/film/news/fran-drescher-president-sag-aftra-joely-fisher-1235054675/
  - https://variety.com/2025/film/news/fran-drescher-sag-aftra-president-step-aside-1236482680/
  - https://www.hollywoodreporter.com/business/business-news/fran-drescher-reelected-sag-aftra-president-1235584524/
  - https://www.hollywoodreporter.com/business/business-news/actors-strike-sag-aftra-leaders-stakes-hollywood-1235536001/
  - https://www.rev.com/transcripts/fran-drescher-delivers-speech-on-sag-aftra-strike-transcript
  - https://abcnews.com/US/sag-aftra-national-board-votes-approve-strike/story?id=101210303
  - https://perkinscoie.com/insights/blog/generative-ai-movies-and-tv-how-2023-sag-aftra-and-wga-contracts-address-generative
  - https://www.equaltimes.org/hollywood-s-stand-against-ai-a?lang=en
---

Pass-2 re-audit. Trigger: entity edited by Editor commit 0b37159d (audit-discrepancy backfill — the
pass-1 `correction` "27th" → "3rd" applied at all three locations). Pass-1's single open correction is
verified fixed (Claim 1). Two pass-1 `uncorroborated` claims resolved with newly fetched sources
(Claims 31, 32); two remain `uncorroborated` honestly (Claims 4, 11). The entity-cited primary
https://www.sagaftra.org/message-sag-aftra-president-and-chief-negotiator returned HTTP 403 again this
pass (also 403: nbcnews.com, today.com; web.archive.org unreachable from this tool; phillytrib.com 429).

## Claim 1: "3rd president of SAG-AFTRA" (body paragraph 1; "Organisational vehicle"; scalar:sources[6].note "SAG-AFTRA's 3rd president")

Source: https://en.wikipedia.org/wiki/Fran_Drescher
Source tier: tiebreaker
Source content: "3rd National President of SAG–AFTRA" — "In office October 15, 2021 – September 12, 2025."
Comparison: Pass-1 correction ("27th" → "3rd" at body paragraph 1, "Organisational vehicle", and the sources[6].note scalar) verified applied in all three locations by Editor commit 0b37159d; the corrected value matches the source. Official-role ordinal is a Wikipedia-alone-sufficient claim type.
Decision: single-source

## Claim 2: Tenure as SAG-AFTRA president 15 October 2021 to 12 September 2025 (body paragraph 1; "Organisational vehicle")

Source: https://en.wikipedia.org/wiki/Fran_Drescher and https://variety.com/2025/film/news/fran-drescher-sag-aftra-president-step-aside-1236482680/
Source tier: mainstream
Source content: Wikipedia: "In office October 15, 2021 – September 12, 2025." Variety: "Ballots were scheduled to be distributed August 13, with returns due by September 12, 2025—marking the conclusion of her four-year tenure."
Comparison: Start and end dates match across both sources.
Decision: corroborated

## Claim 3: 13 July 2023 strike-call press conference date (body multiple references)

Source: https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike and https://www.cbsnews.com/news/hollywood-actors-strike-today-2023-sag-aftra/ and https://deadline.com/2023/07/sag-aftra-fran-drescher-were-being-victimized-by-a-greedy-entity-1235437292/
Source tier: mainstream
Source content: Wikipedia: "On July 13, with no agreement between SAG-AFTRA and the Alliance of Motion Picture and Television Producers (AMPTP), the SAG-AFTRA negotiating committee voted unanimously to recommend a strike." Deadline: "during the press conference … on July 13, 2023."
Comparison: Date matches across three fetched sources.
Decision: corroborated

## Claim 4: Press conference held at "SAG-AFTRA's Los Angeles national headquarters" (body "Public output and venues"; scalar:notable_for; scalar:sources[0].note; scalar:sources[3].note)

Source: https://deadline.com/2023/07/sag-aftra-fran-drescher-were-being-victimized-by-a-greedy-entity-1235437292/ and https://abcnews.com/US/sag-aftra-national-board-votes-approve-strike/story?id=101210303 vs https://deadline.com/2023/07/actors-strike-press-conference-livestream-sag-aftra-1235437177/
Source tier: mainstream
Source content: Deadline event report: "during the press conference held at SAG-AFTRA's national headquarters in Los Angeles on July 13, 2023." ABC News caption: "during a press conference at the labor union's headquarters in Los Angeles, July 13, 2023." But Deadline's same-day livestream announcement: "will talk about the move during a press conference, live from Sherman Oaks."
Comparison: Two contemporaneous event reports support the body's "Los Angeles national headquarters"; Deadline's pre-event announcement places the press conference "live from Sherman Oaks" (SAG-AFTRA Plaza is Mid-Wilshire, not Sherman Oaks — same conflict recorded in the msg-existential-threat-to-creative-professions audit, whose entity body says "Sherman Oaks offices"). Canonical sources conflict on the venue; per the source rule the audit does not pick a winner. Note: the two entities' bodies currently disagree with each other on this venue — resolution requires prose judgment, not a single-token fix, so no correction is routed.
Decision: uncorroborated

## Claim 5: 118-day strike duration (body multiple references)

Source: https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike
Source tier: tiebreaker
Source content: "July 14 – November 9, 2023 (2023-07-14 – 2023-11-09) (3 months and 26 days)"
Comparison: 14 July to 9 November 2023 is 118 days; the source's date range supports the body's figure (date-of-public-event type, Wikipedia-alone sufficient).
Decision: single-source

## Claim 6: Strike start 14 July 2023 (body implicit, multiple references)

Source: https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike and https://www.hollywoodreporter.com/business/business-news/fran-drescher-reelected-sag-aftra-president-1235584524/
Source tier: mainstream
Source content: Wikipedia: "July 14 – November 9, 2023". THR: the strike "had begun July 14".
Comparison: Matches across two sources.
Decision: corroborated

## Claim 7: Strike end 9 November 2023 (scalar:sources[5].note)

Source: https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike
Source tier: tiebreaker
Source content: "July 14 – November 9, 2023"
Comparison: Matches (date-of-public-event type, Wikipedia-alone sufficient).
Decision: single-source

## Claim 8: 98% strike-authorisation vote on 5 June 2023 (scalar:sources[5].note)

Source: https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike
Source tier: tiebreaker
Source content: "On June 5, 2023, SAG-AFTRA approved the strike authorization by a 98% margin, according to the union."
Comparison: Matches.
Decision: single-source

## Claim 9: Contract ratification 5 December 2023 by 78.33% (body "Public output and venues"; scalar:sources[5].note)

Source: https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike
Source tier: tiebreaker
Source content: "The deal was approved with 78.33% support" — ratification December 5, 2023.
Comparison: Matches.
Decision: single-source

## Claim 10: Ratification turnout 38.15% (scalar:sources[5].note)

Source: https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike
Source tier: tiebreaker
Source content: "The deal was approved with 78.33% support, with a 38.15% turnout."
Comparison: Matches.
Decision: single-source

## Claim 11: Verbatim "artificial intelligence poses an existential threat to creative professions, and all actors and performers deserve contract language that protects them from having their identity and talent exploited without consent and pay" attributed to the 13 July 2023 joint Drescher / Crabtree-Ireland membership message (body multiple references; scalar:sources[1].note)

Source: https://www.sagaftra.org/message-sag-aftra-president-and-chief-negotiator (entity-cited primary — HTTP 403 this pass)
Source tier: none
Source content: Direct fetch returned HTTP 403 Forbidden (as in pass 1). A web search ties the verbatim sentence to exactly this URL — the result titled "A Message from the SAG-AFTRA President and Chief Negotiator | SAG-AFTRA" — and CBS (fetched) carries the adjacent but different Crabtree-Ireland formulation: "Actors now face an existential threat to their livelihoods from the use of AI and generative technology."
Comparison: The framing and the page's existence/title are well-supported, but no canonical source fetched this session carries the full verbatim sentence; the primary remains unreachable to this tool (nbcnews.com and today.com, which syndicate the quote, also returned 403; web.archive.org unreachable). Honest sourcing-strength label, not an error finding.
Decision: uncorroborated

## Claim 12: Duncan Crabtree-Ireland's title "National Executive Director and Chief Negotiator" (body multiple references; scalar:sources[5].note)

Source: https://www.cbsnews.com/news/hollywood-actors-strike-today-2023-sag-aftra/ and https://deadline.com/2023/07/actors-strike-press-conference-livestream-sag-aftra-1235437177/ and https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike
Source tier: mainstream
Source content: CBS: "the union's national executive director". Deadline: "National Executive Director and chief negotiator Duncan Crabtree-Ireland". Wikipedia: "chief negotiator Duncan Crabtree-Ireland".
Comparison: Both titles confirmed across sources.
Decision: corroborated

## Claim 13: 2 September 2021 election announcement (scalar:sources[12].note)

Source: https://variety.com/2021/film/news/fran-drescher-president-sag-aftra-joely-fisher-1235054675/
Source tier: mainstream
Source content: Results announced "Sep 2, 2021" (Thursday evening).
Comparison: Matches.
Decision: single-source

## Claim 14: 16,958-to-15,371 win over Matthew Modine on the Unite for Strength slate (scalar:sources[12].note)

Source: https://variety.com/2021/film/news/fran-drescher-president-sag-aftra-joely-fisher-1235054675/
Source tier: mainstream
Source content: "Drescher received 16,958 votes to Modine's 15,371" — Drescher represented the "Unite for Strength slate, which has controlled the union since 2009".
Comparison: All three sub-claims match.
Decision: single-source

## Claim 15: 8 September 2023 re-election announcement (scalar:sources[13].note)

Source: https://www.hollywoodreporter.com/business/business-news/fran-drescher-reelected-sag-aftra-president-1235584524/
Source tier: mainstream
Source content: Announcement date September 8, 2023; "an election cycle that took place amid a historic strike."
Comparison: Date matches; the scalar's "registered mid-strike" framing also matches.
Decision: single-source

## Claim 16: 23,080-to-5,276 second-term margin against Maya Gilbert-Dunbar (scalar:sources[13].note)

Source: https://www.hollywoodreporter.com/business/business-news/fran-drescher-reelected-sag-aftra-president-1235584524/
Source tier: mainstream
Source content: "Drescher received 23,080 votes, over competitor Maya Gilbert-Dunbar's 5,276 votes."
Comparison: Matches.
Decision: single-source

## Claim 17: NO FAKES Act discussion-draft introduction October 2023 (body "The NO FAKES Act federal-policy register"; scalar:sources[9].note)

Source: https://deadline.com/2023/10/no-fakes-act-ai-limits-senate-1235571538/ and https://en.wikipedia.org/wiki/No_Fakes_Act
Source tier: mainstream
Source content: Deadline: introduction date October 12, 2023. Wikipedia: "The bill was first introduced in 2023 as a discussion draft."
Comparison: Body's "October 2023" matches.
Decision: corroborated

## Claim 18: NO FAKES Act formal Senate introduction July 2024 (body "The NO FAKES Act federal-policy register")

Source: https://en.wikipedia.org/wiki/No_Fakes_Act
Source tier: tiebreaker
Source content: "In July 2024, policymakers formally introduced NO FAKES Act in the Senate."
Comparison: Matches (date-of-public-event type, Wikipedia-alone sufficient).
Decision: single-source

## Claim 19: SAG-AFTRA standing public endorsement of the NO FAKES Act under Drescher (body; scalar:sources[8].note; scalar:sources[9].note)

Source: https://en.wikipedia.org/wiki/No_Fakes_Act and https://deadline.com/2023/10/no-fakes-act-ai-limits-senate-1235571538/
Source tier: mainstream
Source content: Wikipedia: "The NO FAKES Act has received broad support from stakeholders in the technology and entertainment industries, including SAG-AFTRA". Deadline: "Union President Fran Drescher stated: 'A performer's voice and their appearance are all part of their unique essence, and it's not ok when those are used without their permission. Consent is key.'" Deadline also records RIAA endorsement; the Motion Picture Association "expressed willingness to collaborate on the bill" — a softer posture than the scalar's "lead labour endorser … alongside the RIAA and the Motion Picture Association" grouping, but the body's own endorsement claim is direct.
Comparison: Endorsement under Drescher confirmed by both sources, with a named Drescher statement. Wikipedia additionally confirms the bill-to-strike linkage claimed in sources[8].note: "Actors' concerns over studios' use of their digital likeness were one of the primary drivers of the … SAG-AFTRA strike in 2023."
Decision: corroborated

## Claim 20: 25 September 2024 Artists 4 Safe AI open letter; "125+ Hollywood signatory list" (scalar:notable_for; body multiple references)

Source: https://deadline.com/2024/09/jane-fonda-shonda-rhimes-pedro-pascal-urge-gavin-newsom-sign-ai-safety-bill-open-letter-1236099942/
Source tier: mainstream
Source content: Article dated September 25, 2024; "125 Hollywood professionals" signed; "The letter was organized by 'Artists 4 Safe AI'".
Comparison: Date, organizer attribution, and signatory count match (body's "125+" is consistent with the source's 125).
Decision: single-source

## Claim 21: Named co-signatories — Jane Fonda, Mark Ruffalo, Shonda Rhimes, J.J. Abrams, Pedro Pascal, Mark Hamill, Sean Astin, Ava DuVernay, Mahershala Ali, Joseph Gordon-Levitt, Don Cheadle, Jessica Chastain, Janelle Monáe (scalar:sources[7].note; body)

Source: https://deadline.com/2024/09/jane-fonda-shonda-rhimes-pedro-pascal-urge-gavin-newsom-sign-ai-safety-bill-open-letter-1236099942/
Source tier: mainstream
Source content: "The article lists Jane Fonda, Mark Ruffalo, Shonda Rhimes, J.J. Abrams, Pedro Pascal, Mark Hamill, Sean Astin, Ava DuVernay, Mahershala Ali, Joseph Gordon-Levitt, Don Cheadle, Jessica Chastain, and Janelle Monáe" among the signatories, with Drescher also named.
Comparison: All thirteen names plus Drescher's own signature confirmed.
Decision: single-source

## Claim 22: The letter urged Governor Gavin Newsom to sign California SB 1047 (body multiple references)

Source: https://deadline.com/2024/09/jane-fonda-shonda-rhimes-pedro-pascal-urge-gavin-newsom-sign-ai-safety-bill-open-letter-1236099942/
Source tier: mainstream
Source content: "The open letter urges Governor Gavin Newsom to sign SB 1047, legislation requiring AI developers in California to implement security safeguards before training their models."
Comparison: Matches.
Decision: single-source

## Claim 23: Video game strike start 26 July 2024 (body "The 2024–25 video game strike"; scalar:sources[10].note)

Source: https://en.wikipedia.org/wiki/2024%E2%80%932025_SAG-AFTRA_video_game_strike
Source tier: tiebreaker
Source content: "July 26, 2024" (infobox and opening paragraph).
Comparison: Matches (date-of-public-event type, Wikipedia-alone sufficient).
Decision: single-source

## Claim 24: Video game strike ratification 9 July 2025 by 95.04% (body; scalar:sources[10].note)

Source: https://en.wikipedia.org/wiki/2024%E2%80%932025_SAG-AFTRA_video_game_strike
Source tier: tiebreaker
Source content: "The agreement was overwhelmingly ratified on July 9, 2025" with "95.04% of the votes in favor".
Comparison: Matches.
Decision: single-source

## Claim 25: Struck companies — Activision, Electronic Arts, Epic Games, Insomniac Games, Take-Two Interactive, Disney Character Voices, Warner Bros. Games (body)

Source: https://en.wikipedia.org/wiki/2024%E2%80%932025_SAG-AFTRA_video_game_strike
Source tier: tiebreaker
Source content: Infobox parties: "Activision Productions, Blindlight, Disney Character Voices, Electronic Arts Productions, Epic Games, Formosa Interactive, Insomniac Games, Llama Productions, Take-Two Interactive, VoiceWorks Productions, Warner Bros. Games".
Comparison: All seven companies the body names appear in the source's party list (the body's list is a subset, framed as such). Treated as a definitional/public-record fact of the named public event.
Decision: single-source

## Claim 26: Video game strike duration "11-month-1-week-6-day stoppage" on AI digital-replica protections in voice-acting and motion-capture work (body)

Source: https://en.wikipedia.org/wiki/2024%E2%80%932025_SAG-AFTRA_video_game_strike
Source tier: tiebreaker
Source content: "July 26, 2024 – July 9, 2025 (11 months, 1 week and 6 days)"; "negotiations which failed to result in a protection agreement from the use of artificial intelligence (AI) for all performers covered by the Interactive Media Agreement."
Comparison: Duration figure matches verbatim; AI-protections core issue confirmed.
Decision: single-source

## Claim 27: "the longest interactive-media work stoppage in U.S. labor history on the public record" (body)

Source: https://en.wikipedia.org/wiki/2024%E2%80%932025_SAG-AFTRA_video_game_strike
Source tier: none
Source content: "The Wikipedia article does not explicitly state whether this was the longest interactive-media or video-game work stoppage."
Comparison: The superlative could not be confirmed against any source fetched this session. Honest sourcing-strength label, not an error finding.
Decision: uncorroborated

## Claim 28: Sean Astin succeeded Drescher as SAG-AFTRA president on 12 September 2025 (body; scalar:sources[6].note)

Source: https://en.wikipedia.org/wiki/Fran_Drescher
Source tier: tiebreaker
Source content: "Succeeded by Sean Astin"; "In office October 15, 2021 – September 12, 2025."
Comparison: Matches (official-office succession, Wikipedia-alone sufficient). The Deadline SB 1047 article (fetched) independently confirms Astin as a 2024 letter signatory but not the succession.
Decision: single-source

## Claim 29: 2023 strike was the union's first against the AMPTP since 1980 (body "Public output and venues")

Source: https://en.wikipedia.org/wiki/2023_SAG-AFTRA_strike and https://variety.com/2025/film/news/fran-drescher-sag-aftra-president-step-aside-1236482680/
Source tier: mainstream
Source content: Wikipedia: "It marked the first time that actors initiated a labor dispute in the U.S. since the 1980 actors strike." Variety: "taking the union on strike against the major film and TV companies for the first time in four decades."
Comparison: Matches within paraphrase tolerance across two sources.
Decision: corroborated

## Claim 30: "Wrong side of history" rebuke of the AMPTP (body multiple references; scalar:notable_for; scalar:sources[0].note)

Source: https://deadline.com/2023/07/fran-drescher-the-complete-sag-aftra-strike-speech-video-hollywood-1235437816/ and https://www.rev.com/transcripts/fran-drescher-delivers-speech-on-sag-aftra-strike-transcript
Source tier: mainstream
Source content: Deadline: "They stand on the wrong side of history." Rev transcript: "They stand on the wrong side of history at this very moment."
Comparison: Matches across two sources (Rev carries a longer rendering of the same line; the body quotes only the "wrong side of history" core).
Decision: corroborated

## Claim 31: "we are all going to be in jeopardy of being replaced by machines and big business, who care more about Wall Street than you and your family" (scalar:notable_for; scalar:sources[0].note; body "Signature framings")

Source: https://deadline.com/2023/07/fran-drescher-the-complete-sag-aftra-strike-speech-video-hollywood-1235437816/ and https://www.rev.com/transcripts/fran-drescher-delivers-speech-on-sag-aftra-strike-transcript
Source tier: mainstream
Source content: Deadline: "We are all going to be in jeopardy of being replaced by machines and big business." Rev transcript: "We are all going to be in jeopardy of being replaced by machines and big business who cares more about Wall Street than you and your family."
Comparison: Pass-1 left the trailing "who care more about Wall Street than you and your family" fragment unresolved; the Rev transcript now confirms the full sentence including the tail. Minor transcript variant ("who cares" in Rev vs the body's "who care") is transcription-level divergence between sources, not a single-token correction — the entity-cited Deadline extract carries only the first portion and no authoritative transcript adjudicates the verb form.
Decision: corroborated

## Claim 32: "What's happening to us is happening across all forms of work" as a press-conference framing (body "Signature framings"; "Why this is a Voice entry")

Source: https://www.cbsnews.com/news/hollywood-actors-strike-today-2023-sag-aftra/
Source tier: mainstream
Source content: "'What's happening to us is happening across all forms of work,' SAG-AFTRA President Fran Drescher said in a fiery speech that drew applause from the room."
Comparison: Pass-1 could not confirm this quote; CBS (fetched this pass) carries it verbatim with direct attribution to Drescher at the strike announcement. Note: the body's inline citation for this quote points at the Deadline complete-speech article, which did not surface the line in either pass; the Rev transcript carries a variant ("What is happening to us is happening across all fields of labor…") — supported as stated by CBS, but resting on that one source, and the body's citation choice is imprecise (re-pointing it is prose judgment, not a single-token fix; no correction routed).
Decision: single-source

## Claim 33: "The digital age is cannibalizing us" in the same-day Hollywood Reporter interview (scalar:notable_for; scalar:sources[4].note; body multiple references)

Source: https://www.hollywoodreporter.com/business/business-news/actors-strike-sag-aftra-leaders-stakes-hollywood-1235536001/
Source tier: mainstream
Source content: "'The digital age is cannibalizing us. It's taking over in a way that doesn't have the kind of thought or advanced thinking — nothing, it's just out of control.' — Fran Drescher", interview dated July 13, 2023, with AI and streaming both named as pressures.
Comparison: Verbatim match, same-day date and AI/streaming pairing per the scalar all confirmed.
Decision: single-source

## Claim 34: "we're being victimized by a very greedy entity" framing at the podium (scalar:sources[11].note; body)

Source: https://deadline.com/2023/07/sag-aftra-fran-drescher-were-being-victimized-by-a-greedy-entity-1235437292/ and https://www.rev.com/transcripts/fran-drescher-delivers-speech-on-sag-aftra-strike-transcript
Source tier: mainstream
Source content: Deadline: "'We are being victimized by a very greedy entity,' Drescher stated during the press conference". Rev transcript: "We are being victimized by a very greedy entity."
Comparison: Confirmed by two sources; both render "We are" where the body (following the entity-cited Deadline headline's own contraction) renders "we're" — a quotation-rendering variant of the same spoken line, not a factual-token contradiction. Deadline also confirms the scalar's claim that the populist register was paired with the union's substantive AI bargaining brief (Crabtree-Ireland's background-scan criticism in the same report).
Decision: corroborated

## Claim 35: Speech framed the strike as on behalf of "everybody in the industry" (scalar:sources[0].note)

Source: https://deadline.com/2023/07/fran-drescher-the-complete-sag-aftra-strike-speech-video-hollywood-1235437816/ and https://www.rev.com/transcripts/fran-drescher-delivers-speech-on-sag-aftra-strike-transcript
Source tier: none
Source content: Neither the Deadline extract nor the Rev transcript surfaced the phrase "everybody in the industry" this session (Deadline fetch: "Not present in the provided text"; Rev fetch: "No exact match found in transcript").
Comparison: The quoted token in sources[0].note could not be located in either fetched transcript of the speech. Both fetches returned extracts rather than guaranteed-complete text, so absence is not proof of error — too thin to confirm, not demonstrated wrong. Honest sourcing-strength label.
Decision: uncorroborated

## Claim 36: TV/Theatrical/Streaming contract's five-category AI taxonomy — employment-based digital replicas, independently created digital replicas, background-actor digital replicas, synthetic performers, digital alterations (scalar:sources[13].note; body links)

Source: https://perkinscoie.com/insights/blog/generative-ai-movies-and-tv-how-2023-sag-aftra-and-wga-contracts-address-generative
Source tier: mainstream
Source content: The analysis names exactly five categories: "Employment-Based Digital Replicas", "Independently Created Digital Replicas", "Background Actor Digital Replicas", "Synthetic Performers" ("Digitally created performer that does not resemble a real actor and is not voiced by a real person"), "Digital Alterations".
Comparison: All five categories match the scalar's list.
Decision: single-source

## Claim 37: August 2025 decision not to seek a third term (scalar:sources[14].note; body implicit)

Source: https://variety.com/2025/film/news/fran-drescher-sag-aftra-president-step-aside-1236482680/
Source tier: mainstream
Source content: "The announcement became official on Friday, August 8, 2025, when SAG-AFTRA released its candidate roster for the upcoming election" — with returns due September 12, 2025, "marking the conclusion of her four-year tenure."
Comparison: The scalar's "August 2025 decision not to seek a third SAG-AFTRA presidential term" and tenure-end date both match.
Decision: single-source

## Claim 38: The framing's same-day entry into the CBS News headline cycle with the named pairing of Drescher and Crabtree-Ireland (scalar:sources[2].note; body "Public output and venues")

Source: https://www.cbsnews.com/news/hollywood-actors-strike-today-2023-sag-aftra/
Source tier: primary
Source content: CBS headline: "Hollywood goes on strike as actors join writers on picket lines, citing 'existential threat' to profession"; the article names "SAG-AFTRA President" Fran Drescher and Duncan Crabtree-Ireland, "the union's national executive director", and quotes Crabtree-Ireland: "Actors now face an existential threat to their livelihoods from the use of AI and generative technology."
Comparison: The claim is about the CBS artefact itself, and the fetched artefact confirms it: existential-threat framing in the same-day headline, both leaders named. (CBS attributes its existential-threat quote to Crabtree-Ireland's livelihoods formulation, not the joint-letter sentence — consistent with the scalar, which claims framing-entry and pairing, not the verbatim letter phrase.)
Decision: primary-sourced

## Claim 39: The sectoral-template framing's carry-through into the Equal Times cross-union reception (body "Signature framings")

Source: https://www.equaltimes.org/hollywood-s-stand-against-ai-a?lang=en
Source tier: primary
Source content: "As artificial intelligence continues to transform entire industries, the agreement reached in Hollywood serves as a valuable template for other sectors." The article records the strikes having "inspired workers in other sectors affected by automation and artificial intelligence."
Comparison: The claim is about the Equal Times artefact's content, and the fetched artefact confirms it treats the Hollywood agreement as a cross-sector template. (Equal Times does not itself carry the "existential threat" phrase — irrelevant to this claim, noted for completeness.)
Decision: primary-sourced
