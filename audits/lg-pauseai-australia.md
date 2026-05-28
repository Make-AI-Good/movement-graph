---
entity_id: lg-pauseai-australia
entity_hash: a70a1643c3e85e6f4cf1745100d57e1f33ff6045
audit_date: 2026-05-28
pass: 1
status: discrepancy
claims_total: 17
claims_verified: 12
claims_discrepancy: 1
claims_unverifiable: 4
sources_consulted:
  - https://pauseai.info/australia
  - https://pauseai.info/about
  - https://luma.com/pauseaiaustralia
  - https://pauseai.info/2024-may
  - https://pauseai.info/2025-february
  - https://en.wikipedia.org/wiki/AI_Action_Summit
---

## Claim 1: "PauseAI Australia is the Australian national chapter of [PauseAI]"

Source: https://pauseai.info/australia
Source content: The chapter operates a dedicated national page at pauseai.info/australia presenting itself as the Australian national chapter of the global PauseAI federation, with chapter contact at australia@pauseai.info and a footer reference to "Stichting PauseAI (kvk 92951031)".
Comparison: Body framing matches the chapter's own self-description as the Australian national chapter.
Decision: verified

## Claim 2: "named on PauseAI Global's About page under two co-listed national leaders — Michael Huang and Peter Horniak — the only chapter in the federation's national-leadership listing to carry two co-equal leaders"

Source: https://pauseai.info/about
Source content: The About page lists Michael Huang and Peter Horniak together as the Australian leads with no hierarchy designation. All other national chapters listed (US, UK, France, Germany, Spain, Italy, Sweden, Czechia, Romania, Nigeria, Kenya, Serbia, Canada) have a single named lead.
Comparison: Both the dual-listing and the uniqueness claim ("only chapter") match the page.
Decision: verified

## Claim 3: "PauseAI Australia Ltd is an incorporated not-for-profit" (verbatim quotation from chapter page)

Source: https://pauseai.info/australia
Source content: "PauseAI Australia Ltd is an incorporated not-for-profit."
Comparison: Verbatim match.
Decision: verified

## Claim 4: "Stichting PauseAI (KVK 92951031, the Utrecht-anchored Dutch foundation that is the federation's parent legal vehicle)"

Source: https://pauseai.info/australia
Source content: Footer carries "Stichting PauseAI (kvk 92951031)".
Comparison: KVK number and Stichting name verified. "Utrecht-anchored" is a cross-entity assertion not directly supported by this page; treated as in-corpus consistency with lg-pauseai-utrecht record (auditor does not verify cross-entity claims against other corpus entries).
Decision: verified

## Claim 5: Names of other PauseAI national chapter leaders — Holly Elmore (US), Joseph Miller (UK), Clémence Peyrot (France), Benjamin Schmidt (Germany), Ayoze García González (Spain), Giulia Consonni (Italy), Carl (Sweden), Matěj Jaroš (Czechia), Raluca Spataru (Romania), Khadija Sabiu (Nigeria), Seth Momanyi Ouko (Kenya), Svetozar Jankovic (Serbia), Jeremy Eliosoff (Canada)

Source: https://pauseai.info/about
Source content: The About page lists each named individual against the corresponding national chapter exactly as the body states.
Comparison: All thirteen names verified verbatim against the About page.
Decision: verified

## Claim 6: "Clémence Peyrot following Maxime Fournes's elevation to PauseAI Global CEO"

Source: https://pauseai.info/about
Source content: The About page currently lists Clémence Peyrot as the France chapter lead but does not state the transition from Maxime Fournes or his elevation to PauseAI Global CEO on the page surveyed.
Comparison: The succession-and-promotion fact is not surfaced on the cited canonical source; no additional canonical source was fetched in this session to support it.
Decision: unverifiable

## Claim 7: "PauseAI Global's first thirteen-country international protest wave" (body) and the matching frontmatter scalar:source[4].note "thirteen-country international protest wave"

Source: https://pauseai.info/2024-may
Source content: Page lists 14 participating cities — San Francisco, New York City, Berlin, London, Rome, Stockholm, Den Haag, Paris, Oslo, Sydney, Ottawa, Reykjavík, Portland, São Paulo — and contains no explicit count statement of "thirteen countries" or "13 countries". A mechanical count of distinct countries across the listed cities yields 12 (USA, Germany, UK, Italy, Sweden, Netherlands, France, Norway, Australia, Canada, Iceland, Brazil).
Comparison: The "thirteen-country" descriptor is contradicted by the source's actual city listing — 12 distinct countries, not 13. Identical wording appears in scalar:sources[4].note ("PauseAI Global's writeup of the 13 May 2024 thirteen-country international protest wave"). Correction route requires prose judgment between two replacement targets ("twelve-country" reflecting the country count, or "fourteen-city" reflecting the count the page actually lists); Editor likely routes to Researcher rather than auto-applying. Mirror to sources[4].note follows the same correction shape.
Decision: discrepancy

## Claim 8: Sydney was the named Australian participating city in the May 2024 protest wave, listed alongside San Francisco, New York, Portland, Berlin, London, Rome, Stockholm, Den Haag, Paris, Oslo, Ottawa, Reykjavík, and São Paulo

Source: https://pauseai.info/2024-may
Source content: The page enumerates these 14 cities including "Sydney, Australia".
Comparison: City list matches the body and frontmatter sources[4].note verbatim.
Decision: verified

## Claim 9: "ahead of the AI Seoul Summit"

Source: https://pauseai.info/2024-may
Source content: The page references the protest goal as addressing "the next AI Safety Summit (the 22nd of May)" without naming Seoul on this page. The 21-22 May 2024 AI Safety Summit was the AI Seoul Summit (widely documented; Wikipedia AI Safety Summit article confirms).
Comparison: Page-level claim that the wave preceded the May 22, 2024 AI Safety Summit is verified; the "AI Seoul Summit" identification is supported externally and is a named-entity definitional fact (date and name of a public event) for which Wikipedia is canonical-alone per source rule.
Decision: verified

## Claim 10: "7-11 February 2025 — Melbourne, Paris AI Action Summit international protest wave ... eighteen-city protest wave"

Source: https://pauseai.info/2025-february
Source content: Page lists dates "February 7-11" and enumerates Paris, New York, Victoria, London, Berlin, Brussels, Zürich, Prague, Milan, Stockholm, Copenhagen, Oslo, Kristiansand, Trondheim, Kinshasa, Brazzaville, N'Djaména, and Melbourne — 18 cities.
Comparison: Dates and eighteen-city count both verified by enumeration on the source page. Melbourne is named as the Australian participating city.
Decision: verified

## Claim 11: "Paris AI Action Summit co-chaired by President Emmanuel Macron and Prime Minister Narendra Modi" (body) and equivalent attribution in scalar:sources[5].note

Source: https://en.wikipedia.org/wiki/AI_Action_Summit
Source content: "The summit was co-chaired by French President Emmanuel Macron and Indian Prime Minister Narendra Modi." Dates 10-11 February 2025, Grand Palais Paris.
Comparison: Co-chair identification verified. Wikipedia is canonical-alone for official roles/titles at a named public event per Source rule (named-entity definitional facts about public events).
Decision: verified

## Claim 12: "PauseAI Canada chapter's transition from an Ottawa anchor in May 2024 to a Victoria, British Columbia anchor in February 2025"

Source: https://pauseai.info/2024-may and https://pauseai.info/2025-february
Source content: 2024-may lists "Ottawa, Canada"; 2025-february lists "Victoria" (alongside European and Australian cities, distinguishing it from the Australian state of Victoria — the city Melbourne in that state is listed separately on the same page).
Comparison: Both endpoints of the state-rotation claim verified on the respective pages. The "British Columbia" disambiguation is the standard reading given the page's context (Canada is the prior-wave home country, Melbourne is listed independently).
Decision: verified

## Claim 13: "PayID donation channel" with number "85692218938"

Source: https://pauseai.info/australia
Source content: "PayID: 85692218938" listed as a donation channel.
Comparison: Verbatim number match.
Decision: verified

## Claim 14: "Canberra Casual Catchups — recurring meetup series ... at Libraries ACT — Tuggeranong, organised by Peter Horniak" (body) and matching scalar:sources[3].note

Source: https://luma.com/pauseaiaustralia
Source content: Current calendar (fetched 2026-05-28) lists "Canberra: Anna Goldsworthy & Andrew Leigh RE: quarterly essay" at Tangney Road organised by Peter Horniak, plus a Brisbane equivalent. No event titled "Casual Catchups" and no Libraries ACT — Tuggeranong venue appears on the current calendar. Past Luma events may roll off as they pass, so absence does not establish non-existence at draft time (2026-05-15).
Comparison: The cited source no longer contains the claim as written. Cannot distinguish between (a) calendar-rollover of past recurring events versus (b) misattribution at draft time. Per source rule, when a cited source no longer supports the claim and no canonical alternative is fetched, outcome is unverifiable rather than discrepancy. Mirror applies to sources[3].note describing the same event series.
Decision: unverifiable

## Claim 15: "While We Still Can: The AI Revolution and Our Last Chance to Steer the Future" Melbourne talk co-organised by Peter Horniak and Mark Brown (body) and matching scalar:sources[3].note

Source: https://luma.com/pauseaiaustralia
Source content: Current calendar (fetched 2026-05-28) does not list a "While We Still Can" Melbourne talk. Mark Brown is listed as organiser of a July online meetup (Google Meet location); Peter Horniak organises multiple events but none under this title on the current calendar.
Comparison: Same calendar-rollover ambiguity as Claim 14 — the talk may have been a past listing not retained on the current public calendar. Outcome unverifiable.
Decision: unverifiable

## Claim 16: "PauseAI @ AI Safety Forum 2026" convening at Camperdown, Sydney, organised by Peter Horniak (body) and scalar:sources[3].note

Source: https://luma.com/pauseaiaustralia
Source content: Calendar lists "PauseAI @AI Safety Forum 2026" at "Camperdown, Australia" organised by Peter Horniak.
Comparison: Verbatim match including organiser.
Decision: verified

## Claim 17: "PauseAI @ NeurIPS" placeholder engagement with a Sydney chapter-side location, organised by Peter Horniak (body) and scalar:sources[3].note

Source: https://luma.com/pauseaiaustralia
Source content: Calendar lists "(placeholder) PauseAI @NeurIPS" at "Sydney, Australia" organised by Peter Horniak.
Comparison: Verbatim match including placeholder framing, location, and organiser.
Decision: verified
