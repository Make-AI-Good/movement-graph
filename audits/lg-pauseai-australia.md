---
entity_id: lg-pauseai-australia
entity_hash: afa52d8f4eeafd0043883527fa14328a7066acb7
audit_date: 2026-06-10
pass: 2
status: supported
claims_total: 17
claims_corroborated: 0
claims_primary_sourced: 12
claims_single_source: 2
claims_uncorroborated: 3
open_corrections: 0
sources_consulted:
  - https://pauseai.info/australia
  - https://pauseai.info/about
  - https://luma.com/pauseaiaustralia
  - https://pauseai.info/2024-may
  - https://pauseai.info/2025-february
  - https://en.wikipedia.org/wiki/AI_Action_Summit
  - https://en.wikipedia.org/wiki/AI_Seoul_Summit
---

## Claim 1: "PauseAI Australia is the Australian national chapter of [PauseAI]"

Source: https://pauseai.info/australia
Source tier: primary
Source content: "We are the Australian national chapter of the PauseAI movement."
Comparison: Body framing matches the chapter's own self-description verbatim.
Decision: primary-sourced

## Claim 2: "named on PauseAI Global's About page under two co-listed national leaders — Michael Huang and Peter Horniak — the only chapter in the federation's national-leadership listing to carry two co-equal leaders"

Source: https://pauseai.info/about
Source tier: primary
Source content: Enumeration of national leads (fetched 2026-06-10): "Michael Huang — Australia / Peter Horniak — Australia"; every other listed chapter (US Holly Elmore, UK Joseph Miller, France Clémence Peyrot, Germany Benjamin Schmidt, Spain Ayoze García González, Italy Giulia Consonni, Sweden Carl, Czechia Matěj Jaroš, Romania Raluca Spataru, Nigeria Khadija Sabiu, Kenya Seth Momanyi Ouko, Serbia Svetozar Jankovic, Canada Jeremy Eliosoff) carries a single named lead — "no other chapter includes more than one person."
Comparison: Both the dual-listing and the uniqueness claim match the page's current leadership enumeration.
Decision: primary-sourced

## Claim 3: "PauseAI Australia Ltd is an incorporated not-for-profit" (verbatim quotation from chapter page)

Source: https://pauseai.info/australia
Source tier: primary
Source content: "PauseAI Australia Ltd is an incorporated not-for-profit."
Comparison: Verbatim match.
Decision: primary-sourced

## Claim 4: "Stichting PauseAI (KVK 92951031, the Utrecht-anchored Dutch foundation that is the federation's parent legal vehicle)"

Source: https://pauseai.info/australia
Source tier: primary
Source content: Footer carries "Legal Info Stichting PauseAI (kvk 92951031)".
Comparison: Stichting name and KVK number match the chapter page's footer. "Utrecht-anchored" is an in-corpus cross-entity assertion (lg-pauseai-utrecht) not surfaced on this page; the auditor does not verify cross-entity claims against other corpus entries.
Decision: primary-sourced

## Claim 5: Names of other PauseAI national chapter leaders — Holly Elmore (US), Joseph Miller (UK), Clémence Peyrot (France), Benjamin Schmidt (Germany), Ayoze García González (Spain), Giulia Consonni (Italy), Carl (Sweden), Matěj Jaroš (Czechia), Raluca Spataru (Romania), Khadija Sabiu (Nigeria), Seth Momanyi Ouko (Kenya), Svetozar Jankovic (Serbia), Jeremy Eliosoff (Canada) — body and scalar:sources[1].note

Source: https://pauseai.info/about
Source tier: primary
Source content: "Holly Elmore — US / Joseph Miller — UK / Clémence Peyrot — France / Benjamin Schmidt — Germany / Ayoze García González — Spain / Giulia Consonni — Italy / Carl — Sweden / Matěj Jaroš — Czechia / Raluca Spataru — Romania / Khadija Sabiu — Nigeria / Seth Momanyi Ouko — Kenya / Svetozar Jankovic — Serbia / Jeremy Eliosoff — Canada"
Comparison: All thirteen names match verbatim against the About page's current listing; same names appear in scalar:sources[1].note.
Decision: primary-sourced

## Claim 6: "Clémence Peyrot following Maxime Fournes's elevation to PauseAI Global CEO"

Source: https://pauseai.info/about
Source tier: primary
Source content: The About page lists "Clémence Peyrot" as France chapter lead and identifies Maxime Fournes as "CEO PauseAI Global" on the executive team roster.
Comparison: Both component facts (Peyrot leads France; Fournes is PauseAI Global CEO) are confirmed on the page — an improvement over pass 1, where the CEO role was not surfaced. The succession sequence itself ("following ... elevation", i.e. that Fournes previously held the France lead and Peyrot succeeded him on his promotion) is not stated on the fetched source; it is an inference over the current-state listing, and living-person employment-history specifics require direct sourcing.
Decision: uncorroborated

## Claim 7: "PauseAI Global's first fourteen-city international protest wave" (body) and matching scalar:sources[4].note "fourteen-city international protest wave"

Source: https://pauseai.info/2024-may
Source tier: primary
Source content: Page lists participating cities: "San Francisco, New York City, Berlin, London, Rome, Stockholm, Den Haag, Paris, Oslo, Sydney, Ottawa, Reykjavík, Portland, Sao Paulo" — 14 cities by mechanical count; the page states no explicit count itself.
Comparison: Pass 1 recorded a correction here ("thirteen-country" contradicted the source). The Researcher's fix (commit 778a670f) replaced it with "fourteen-city" in both body and scalar:sources[4].note; the mechanical city count on the source is 14. The correction is cleared.
Decision: primary-sourced

## Claim 8: Sydney was the named Australian participating city in the May 2024 protest wave, listed alongside San Francisco, New York, Portland, Berlin, London, Rome, Stockholm, Den Haag, Paris, Oslo, Ottawa, Reykjavík, and São Paulo

Source: https://pauseai.info/2024-may
Source tier: primary
Source content: The page enumerates the 14 cities including Sydney as the sole Australian city.
Comparison: City list matches the body and scalar:sources[4].note.
Decision: primary-sourced

## Claim 9: "ahead of the AI Seoul Summit"

Source: https://pauseai.info/2024-may and https://en.wikipedia.org/wiki/AI_Seoul_Summit
Source tier: tiebreaker
Source content: The protest page references "the next AI Safety Summit (the 22nd of May)" without naming Seoul; Wikipedia: "The AI Seoul Summit 2024 was an event in May 2024 co-hosted by the South Korean and British governments," dated 21–22 May 2024.
Comparison: The load-bearing identification (that the 22 May 2024 summit is the AI Seoul Summit) rests on Wikipedia, which is canonical-alone for dates and names of public events per the Source rule; the chapter-side timing rests on the primary protest page. The identification rests on one non-primary canonical source.
Decision: single-source

## Claim 10: "7-11 February 2025 — Melbourne, Paris AI Action Summit international protest wave ... eighteen-city protest wave"

Source: https://pauseai.info/2025-february
Source tier: primary
Source content: Page states dates "February 7–11" and enumerates "Paris, New York, Victoria, London, Berlin, Brussels, Zürich, Prague, Milan, Stockholm, Copenhagen, Oslo, Kristiansand, Trondheim, Kinshasa, Brazzaville, N'Djaména, Melbourne" — 18 cities, Melbourne included.
Comparison: Dates and eighteen-city count verified by enumeration; Melbourne is the named Australian city. Matches body and scalar:sources[5].note.
Decision: primary-sourced

## Claim 11: "Paris AI Action Summit co-chaired by President Emmanuel Macron and Prime Minister Narendra Modi" (body) and equivalent attribution in scalar:sources[5].note

Source: https://en.wikipedia.org/wiki/AI_Action_Summit
Source tier: tiebreaker
Source content: "The summit was co-chaired by French President Emmanuel Macron and Indian Prime Minister Narendra Modi." Dates 10–11 February 2025, Grand Palais, Paris.
Comparison: Co-chair identification matches. The pauseai.info/2025-february page does not name the co-chairs, so the claim rests on Wikipedia alone — sufficient for official roles at a named public event per the Source rule, but a single non-primary canonical source.
Decision: single-source

## Claim 12: "PauseAI Canada chapter's transition from an Ottawa anchor in May 2024 to a Victoria, British Columbia anchor in February 2025"

Source: https://pauseai.info/2024-may and https://pauseai.info/2025-february
Source tier: primary
Source content: 2024-may lists "Ottawa"; 2025-february lists "Victoria" as a separate entry from Melbourne on the same protest-locations list.
Comparison: Both endpoints of the rotation claim appear on the federation's own protest pages. The "British Columbia" disambiguation is the standard contextual reading (Canada is the prior-wave country; Melbourne, the city in Australia's state of Victoria, is listed independently on the same page).
Decision: primary-sourced

## Claim 13: "PayID donation channel" with number "85692218938"

Source: https://pauseai.info/australia
Source tier: primary
Source content: "Donate to support our work via PayID 85692218938"
Comparison: Verbatim number match.
Decision: primary-sourced

## Claim 14: "Canberra Casual Catchups — recurring meetup series ... at Libraries ACT — Tuggeranong, organised by Peter Horniak" (body) and matching scalar:sources[3].note

Source: https://luma.com/pauseaiaustralia
Source tier: none
Source content: Current calendar (fetched 2026-06-10) lists: "Brisbane: Anna Goldsworthy & John Birmingham RE: quarterly essay" (West End), "PauseAI Australia - July online meetup" (Google Meet), "PauseAI @AI Safety Forum 2026" (Camperdown), "(placeholder) PauseAI @NeurIPS" (Sydney) — all organised by Peter Horniak. "The calendar does not display ... 'Canberra: Casual Catchups' at Libraries ACT — Tuggeranong."
Comparison: The cited source no longer contains the claim as written (same finding as pass 1, two fetches apart). Cannot distinguish calendar-rollover of past recurring events from misattribution at draft time (2026-05-15); no canonical alternative source covers the series. Mirror applies to scalar:sources[3].note.
Decision: uncorroborated

## Claim 15: "While We Still Can: The AI Revolution and Our Last Chance to Steer the Future" Melbourne talk co-organised by Peter Horniak and Mark Brown (body) and matching scalar:sources[3].note

Source: https://luma.com/pauseaiaustralia
Source tier: none
Source content: Current calendar (fetched 2026-06-10) does not list a "While We Still Can" Melbourne talk and shows no events organised by Mark Brown; all visible events are organised by Peter Horniak.
Comparison: Same calendar-rollover ambiguity as Claim 14 — the talk may have been a past listing not retained on the current public calendar (pass 1 additionally observed a Mark Brown online meetup that has since rolled off). No canonical source currently supports the claim; not a finding of error.
Decision: uncorroborated

## Claim 16: "PauseAI @ AI Safety Forum 2026" convening at Camperdown, Sydney, organised by Peter Horniak (body) and scalar:sources[3].note

Source: https://luma.com/pauseaiaustralia
Source tier: primary
Source content: Calendar lists "PauseAI @AI Safety Forum 2026" at "Camperdown, Australia", organiser Peter Horniak.
Comparison: Match including organiser.
Decision: primary-sourced

## Claim 17: "PauseAI @ NeurIPS" placeholder engagement with a Sydney chapter-side location, organised by Peter Horniak (body) and scalar:sources[3].note

Source: https://luma.com/pauseaiaustralia
Source tier: primary
Source content: Calendar lists "(placeholder) PauseAI @NeurIPS" at "Sydney, Australia", organiser Peter Horniak.
Comparison: Match including placeholder framing, location, and organiser.
Decision: primary-sourced
