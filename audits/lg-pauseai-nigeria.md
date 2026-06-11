---
entity_id: lg-pauseai-nigeria
entity_hash: c9e2e6fc8c57be438378d473f65aab82efb813a4
audit_date: 2026-06-10
pass: 2
status: corrections-pending
claims_total: 15
claims_corroborated: 1
claims_primary_sourced: 10
claims_single_source: 0
claims_uncorroborated: 1
open_corrections: 3
sources_consulted:
  - https://pauseai.info/communities
  - https://pauseai.info/about
  - https://pauseai.info/national-groups
  - https://pauseai.substack.com/p/we-screened-an-ai-safety-documentary
  - https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
  - https://pauseai.info/2025-february
  - https://en.wikipedia.org/wiki/AI_Action_Summit
  - https://manifund.org/projects/pause-ai-kenya-hub
  - product/entities/local-groups/lg-pauseai-utrecht.md
  - product/entities/local-groups/lg-pauseai-nyc.md
  - product/entities/local-groups/lg-pauseai-kenya.md
---

Pass-2 re-audit after the 2026-06-03 researcher fix (commit 9bddf52e). Of pass 1's three
corrections: claim 14 (scalar) is CLEARED by the fix; claim 7's rewrite still carries an
exclusivity error (correction remains); claim 8 was not addressed (correction remains).
One same-family claim in § Place in the movement, not extracted in pass 1, is added as
claim 15 (correction).

## Claim 1: "PauseAI Nigeria is the Nigerian national chapter of [PauseAI]"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Communities directory lists Nigeria among the federation's national chapters, routed via a WhatsApp invite link (https://chat.whatsapp.com/L4o2IiOX1HI2GWQi0J9ZJv).
Comparison: Body's identification of the chapter as PauseAI's Nigerian national chapter matches the federation's own directory. Single first-party (federation) source.
Decision: primary-sourced

## Claim 2: "Khadija Sabiu" is named as the PauseAI Nigeria national-chapter lead

Source: https://pauseai.info/about
Source tier: primary
Source content: About page lists "Khadija Sabiu" as the head of PauseAI Nigeria (single national-leader listing).
Comparison: Body's attribution and single-leader characterisation match the federation's own About page.
Decision: primary-sourced

## Claim 3: List of other named national-chapter leads — Holly Elmore (US), Joseph Miller (UK), Clémence Peyrot (France), Benjamin Schmidt (Germany), Ayoze García González (Spain), Giulia Consonni (Italy), Carl (Sweden), Matěj Jaroš (Czechia), Raluca Spataru (Romania), Seth Momanyi Ouko (Kenya), Svetozar Jankovic (Serbia), Jeremy Eliosoff (Canada), Michael Huang and Peter Horniak (Australia)

Source: https://pauseai.info/about
Source tier: primary
Source content: About page lists each name under the matching chapter — US: Holly Elmore; UK: Joseph Miller; France: Clémence Peyrot; Germany: Benjamin Schmidt; Spain: Ayoze García González; Italy: Giulia Consonni; Sweden: Carl; Czechia: Matěj Jaroš; Romania: Raluca Spataru; Kenya: Seth Momanyi Ouko; Serbia: Svetozar Jankovic; Canada: Jeremy Eliosoff; Australia: Michael Huang and Peter Horniak.
Comparison: Every listed leader matches the About page exactly.
Decision: primary-sourced

## Claim 4: "Clémence Peyrot following [Maxime Fournes]'s elevation to PauseAI Global CEO in late 2025"

Source: https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
Source tier: primary
Source content: PauseAI's own announcement, published December 2, 2025: "After serving as the Director of PauseIA France, Maxime Fournes will be taking on the role of CEO at PauseAI Global." and "Clémence Peyrot will be taking Maxime's place as the Director of PauseIA France."
Comparison: The elevation, the succession, and the "late 2025" date (announcement dated 2025-12-02) all match. Upgrades pass 1's uncorroborated decision — the announcement post was located this pass.
Decision: primary-sourced

## Claim 5: Chapter is "volunteer-led, consistent with the federation's general pattern outside the three paid-staff chapters — PauseAI US, PauseAI UK, and Pause IA"

Source: https://pauseai.info/national-groups
Source tier: primary
Source content: "At this point, most national groups are _volunteer-run,_ exceptions are the USA, France and the United Kingdom."
Comparison: Pause IA is the French chapter; the source's USA/France/UK exception list matches the body's three paid-staff chapters.
Decision: primary-sourced

## Claim 6: PauseAI Nigeria is "routed via a WhatsApp invite link to a group named 'PauseAI Nigeria' rather than a dedicated chapter site"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Directory's Nigeria entry: "Nigeria[](https://chat.whatsapp.com/L4o2IiOX1HI2GWQi0J9ZJv)" — a WhatsApp invite link as the sole channel.
Comparison: Routing matches the directory. The group's own name ("PauseAI Nigeria") rests on the WhatsApp invite landing page, a closed-channel surface not directly inspected this pass; consistent with the channel context.
Decision: primary-sourced

## Claim 7: "[PauseAI Kenya] is the corpus's other in-corpus example of a single-social-channel federation listing, similarly routed via an X (Twitter) account rather than a dedicated chapter site; the federation directory overall lists multiple chapters without dedicated sites"

Source: https://pauseai.info/communities; product/entities/local-groups/lg-pauseai-utrecht.md
Source tier: primary
Source content: Directory link types per chapter: Italy WhatsApp, Kenya X/Twitter, Netherlands WhatsApp, Nigeria WhatsApp, Poland email, Romania Facebook; the rest dedicated websites. In-corpus lg-pauseai-utrecht (PauseAI Utrecht / Netherlands) has `website_or_contact: https://chat.whatsapp.com/EOGvhoPCiCqDqwuf9JUxtB` (a WhatsApp invite).
Comparison: The 2026-06-03 rewrite fixed the "only two chapters" federation-wide claim (the trailing "multiple chapters without dedicated sites" clause now matches the directory), but "the corpus's OTHER in-corpus example" still asserts Kenya is the only other in-corpus case — contradicted by in-corpus PauseAI Utrecht / Netherlands, whose federation-directory listing (Netherlands) is itself a single social channel (WhatsApp). The Kenya-via-X half is correct. Re-framing requires prose judgment beyond a single replacement.
Decision: correction

## Claim 8: "the in-corpus PauseAI Australia, PauseAI Canada, Pause IA, PauseAI Germany, PauseAI Utrecht / Netherlands, PauseAI London, PauseAI Bay Area, and PauseAI NYC chapters, all of which carry dedicated public-facing sites alongside their federation listing"

Source: https://pauseai.info/communities; product/entities/local-groups/lg-pauseai-utrecht.md; product/entities/local-groups/lg-pauseai-nyc.md
Source tier: primary
Source content: Directory lists Netherlands via a WhatsApp link, not a dedicated site. In-corpus lg-pauseai-utrecht has `website_or_contact: https://chat.whatsapp.com/EOGvhoPCiCqDqwuf9JUxtB` (WhatsApp invite); in-corpus lg-pauseai-nyc has `website_or_contact: nyc@pauseai.info` (email address).
Comparison: Two of the eight listed chapters do not carry dedicated public-facing sites — Utrecht/Netherlands (WhatsApp) and NYC (email). Unchanged from pass 1 (the 2026-06-03 fix did not touch this sentence); the correction remains open. List trimming / re-framing requires prose judgment.
Decision: correction

## Claim 9: Nov 12, 2025 PauseAI Global newsletter, under "New National Chapters" section, states "volunteers are in the process of launching additional chapters in the Philippines and Nigeria"

Source: https://pauseai.substack.com/p/we-screened-an-ai-safety-documentary
Source tier: primary
Source content: Publication date November 12, 2025; "New National Chapters" section present; verbatim: "Volunteers are in the process of launching additional chapters in the Philippines and Nigeria."
Comparison: Newsletter date, section heading, and quoted text all match exactly.
Decision: primary-sourced

## Claim 10: Newsletter reports the launch-phase status "alongside the federation's then-recent chapter formations in Canada, Serbia, Romania, and India"

Source: https://pauseai.substack.com/p/we-screened-an-ai-safety-documentary
Source tier: primary
Source content: "Volunteers in Canada, Serbia, Romania, and India have recently formed their own groups, taking us to a total of 15 worldwide."
Comparison: The four named countries match exactly.
Decision: primary-sourced

## Claim 11: "PauseAI Kenya, whose [Manifund project page] documents a February 2025 chapter start, a 122-square-metre Nairobi office anchor, and stated translation / workshop / advocacy programmes"

Source: https://manifund.org/projects/pause-ai-kenya-hub (not reachable this session)
Source tier: none
Source content: Manifund returned HTTP 429 (rate-limited) again this pass, as in pass 1; the page could not be inspected.
Comparison: The chapter-start month, office-size figure, and programme list could not be compared against the cited Manifund page. No other canonical source for the square-metre figure was located.
Decision: uncorroborated

## Claim 12: PauseAI Global writeup covers "the 7-11 February 2025 international protest wave around the Paris AI Action Summit co-chaired by Emmanuel Macron and Narendra Modi"

Source: https://pauseai.info/2025-february; https://en.wikipedia.org/wiki/AI_Action_Summit
Source tier: primary
Source content: PauseAI writeup covers Feb 7–11 2025 protests around the Paris AI Action Summit (Feb 10–11). Wikipedia: "The summit was co-chaired by French President Emmanuel Macron and Indian Prime Minister Narendra Modi."
Comparison: Protest-wave dates match the PauseAI writeup; the co-chair fact matches Wikipedia (Wikipedia-alone sufficient for official roles at dated public events). Two independent canonical sources cover the composite claim.
Decision: corroborated

## Claim 13: February 2025 writeup names eighteen participating cities — "Paris, New York, Victoria, London, Berlin, Brussels, Zürich, Prague, Milan, Stockholm, Copenhagen, Oslo, Kristiansand, Trondheim, Kinshasa, Brazzaville, N'Djaména, and Melbourne" — and no Nigerian city is among them

Source: https://pauseai.info/2025-february
Source tier: primary
Source content: Writeup names exactly those eighteen cities; no Nigerian city appears.
Comparison: City list and the absence of Nigerian cities match the source exactly.
Decision: primary-sourced

## Claim 14: scalar:sources[0].note — "placing Nigeria among several federation chapters listed via a single social-channel link rather than a dedicated site; among in-corpus PauseAI chapters, PauseAI Kenya also appears in the directory via a single social channel (an X account) rather than a dedicated site"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Directory routes Italy, Netherlands, and Nigeria via WhatsApp, Romania via Facebook, Kenya via X/Twitter, Poland via email — several chapters via single social channels; Kenya's is an X account.
Comparison: Pass 1's correction on this scalar is CLEARED by the 2026-06-03 rewrite — "several federation chapters" matches the directory, and "PauseAI Kenya also appears" is non-exclusive and true. Scalar path: sources[0].note.
Decision: primary-sourced

## Claim 15: § Place in the movement — the chapter is "the corpus's first PauseAI chapter whose only federation-listed public channel is a closed-group messaging app, structurally distinct from PauseAI Kenya's X-account anchor and from the federation's other in-corpus chapters' dedicated-website anchors"

Source: https://pauseai.info/communities; product/entities/local-groups/lg-pauseai-utrecht.md; product/entities/local-groups/lg-pauseai-nyc.md
Source tier: primary
Source content: In-corpus lg-pauseai-utrecht's `website_or_contact` is a WhatsApp invite (a closed-group messaging app) and the directory's Netherlands listing is a WhatsApp link; in-corpus lg-pauseai-nyc's anchor is an email address.
Comparison: Same error family as claims 7–8, in a passage not extracted in pass 1: "first ... whose only federation-listed public channel is a closed-group messaging app" and "the federation's other in-corpus chapters' dedicated-website anchors" are both contradicted by the in-corpus Utrecht/Netherlands chapter (WhatsApp) and, for the dedicated-website generalisation, by NYC (email). Re-framing requires prose judgment.
Decision: correction
