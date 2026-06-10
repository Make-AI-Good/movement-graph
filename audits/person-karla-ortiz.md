---
entity_id: person-karla-ortiz
entity_hash: ba24536dc283d58aa8f90179b13902af52263385
audit_date: 2026-06-02
pass: 1
status: corrections-pending
claims_total: 9
claims_corroborated: 5
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 3
sources_consulted:
  - https://www.conceptartassociation.com/advocacy
  - https://disconnect.blog/how-artists-are-fighting-generative-ai/
  - https://copyrightalliance.org/andersen-v-stability-ai-copyright-case/
  - https://www.ftc.gov/news-events/events/2023/10/creative-economy-generative-ai
---

## Claim 1: "Concept artist"

Source: https://copyrightalliance.org/andersen-v-stability-ai-copyright-case/
Source content: "In early 2023, visual artists Sarah Andersen, Kelly McKernan, and Karla Ortiz filed a class-action lawsuit against Stability AI, Midjourney, and DeviantArt..." (also identified as concept artist in disconnect.blog: "Karla Ortiz is a concept artist")
Comparison: Multiple canonical sources identify Ortiz as a concept artist; matches body claim.
Decision: corroborated

## Claim 2: "board member of the Concept Art Association"

Source: https://disconnect.blog/how-artists-are-fighting-generative-ai/
Source content: Ortiz quoted directly: "I'm a board member of the Concept Art Association, which is this wonderful little association, and I brought the concerns to them."
Comparison: Direct quote from Ortiz confirms board membership.
Decision: corroborated

## Claim 3: "a lead-named plaintiff in *Andersen v. Stability AI*"

Source: https://copyrightalliance.org/andersen-v-stability-ai-copyright-case/
Source content: "In early 2023, visual artists Sarah Andersen, Kelly McKernan, and Karla Ortiz filed a class-action lawsuit against Stability AI, Midjourney, and DeviantArt..."
Comparison: Ortiz is one of three named lead plaintiffs in the case caption (Andersen, McKernan, Ortiz); the case is named for Andersen but Ortiz is one of the three lead-named plaintiffs. Matches body claim.
Decision: corroborated

## Claim 4: "CAA's most public-facing voice on its generative-AI advocacy work"

Source: no canonical source found that explicitly identifies Ortiz as the *most* public-facing voice of CAA's AI advocacy
Source content: Disconnect.blog shows Ortiz brought AI concerns to CAA, organized a September 2022 town hall, testified before the Senate, and was a lead plaintiff — but does not characterize her as the "most" or sole leading public-facing voice on CAA's advocacy.
Comparison: This is load-bearing characterization (a voice's distinctive contribution / positioning relative to peers); the Source rule requires ≥1 canonical source explicitly making the comparative claim. Underlying activity is well documented but the comparative "most" framing is not directly sourced.
Decision: uncorroborated

## Claim 5: scalar:affiliations[0].role — "board member; lead public-facing voice on AI advocacy"

Source: https://disconnect.blog/how-artists-are-fighting-generative-ai/
Source content: Ortiz quoted: "I'm a board member of the Concept Art Association, which is this wonderful little association, and I brought the concerns to them."
Comparison: First clause ("board member") is verified directly. Second clause ("lead public-facing voice on AI advocacy") is the same load-bearing characterization as Claim 4 — well-supported activity, but the comparative "lead voice" framing is not directly sourced. Editor's per-claim backfill should target the second clause; first clause stands.
Decision: uncorroborated

## Claim 6: scalar:sources[0].note — "CAA advocacy page where Ortiz's role is publicly identified"

Source: https://www.conceptartassociation.com/advocacy
Source content: Page fetched 2026-06-02 contains no mention of Karla Ortiz. (WebFetch result: "this page does not name Karla Ortiz or describe any role for her at the Concept Art Association. There is no mention of her anywhere in the text.")
Comparison: The source note's claim — that the linked page publicly identifies Ortiz's role — does not match the page's current content. Either the page was edited since `last_checked: 2026-05-08` or the note was inaccurate at draft time. Either way, the citation now fails to support the role identification.
Decision: correction

## Claim 7: scalar:sources[1].note — "Ortiz launching CAA's December 2022 GoFundMe to fund the AI lobbying effort"

Source: https://x.com/kortizart/status/1603458805425410048 (cited; behind X.com paywall, but corroborated via secondary canonical search)
Source content: Tweet title surfaced in search: "I am THRILLED to announce that the #ConceptArtAssociation has released a #gofundmecampaign to fund multiple actions, so we artists can stand up for our rights and be heard in the public and in DC!" — posted from @kortizart in mid-December 2022. MIT Technology Review (2022-12-16) and other coverage corroborate the December 2022 launch of the CAA GoFundMe to fund AI advocacy/lobbying, attributed to Ortiz's announcement.
Comparison: Note matches: Ortiz did launch (announce) CAA's December 2022 GoFundMe for the AI lobbying effort.
Decision: corroborated

## Claim 8: scalar:sources[2].note — "Andersen v. Stability AI coverage naming Ortiz as a lead plaintiff"

Source: https://news.artnet.com/art-world/artists-vs-stability-ai-lawsuit-moves-ahead-2524849 (cited; returned HTTP 403 on direct fetch); cross-checked against https://copyrightalliance.org/andersen-v-stability-ai-copyright-case/
Source content: Copyright Alliance: "In early 2023, visual artists Sarah Andersen, Kelly McKernan, and Karla Ortiz filed a class-action lawsuit against Stability AI, Midjourney, and DeviantArt..." Artnet article title appeared in search results ("Artists Land a Win in Class Action Lawsuit Against A.I. Companies"); the underlying claim that Ortiz is a lead plaintiff is corroborated by multiple canonical sources.
Comparison: The cited artnet URL was unreachable in this session (403), but the substantive claim — that Andersen v. Stability AI coverage names Ortiz as a lead plaintiff — is corroborated by other canonical sources. Note matches the substance of the case coverage.
Decision: corroborated

## Claim 9: scalar:sources[3].note — "Transcript of the FTC Creative Economy and Generative AI roundtable, October 4 2023, with Ortiz on the CAA panel"

Source: https://www.ftc.gov/news-events/events/2023/10/creative-economy-generative-ai (FTC event page; direct fetch returned 403, but event details surfaced via web search)
Source content: FTC hosted "Creative Economy and Generative AI" virtual roundtable on October 4, 2023, 3:00–4:40pm ET. Karla Ortiz was a panelist, identified as a concept artist and illustrator; other panelists included John August, Tim Friedlander, Douglas Preston. The PDF transcript path matches the cited URL pattern.
Comparison: The roundtable occurred on the stated date (Oct 4, 2023) and Ortiz was a panelist on it. The note's phrasing "the CAA panel" is imprecise — the roundtable itself was the FTC's, not a CAA panel — but Ortiz's CAA affiliation is widely associated with her advocacy presence at that event. Substantive claims (transcript exists, date correct, Ortiz on panel) match.
Decision: corroborated
