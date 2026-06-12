---
entity_id: lg-pauseai-romania
entity_hash: 9e017e8e219c5c85261255ec722458e88ab1267a
audit_date: 2026-06-11
pass: 1
status: supported
claims_total: 13
claims_corroborated: 0
claims_primary_sourced: 11
claims_single_source: 0
claims_uncorroborated: 2
open_corrections: 0
sources_consulted:
  - https://pauseai.info/communities
  - https://pauseai.info/about
  - https://pauseai.info/proposal
  - https://pauseai.info/protests
  - https://pauseai.info/2024-may
  - https://pauseai.info/2025-february
  - https://pauseai.cz/
  - https://pauseai.pl/
  - https://www.facebook.com/people/Pause-AI-Romania/61581783381263/
---

## Claim 1: "listed on PauseAI Global's communities directory as 'România' with a Facebook page as its primary public contact point"

Source: https://pauseai.info/communities
Source tier: primary
Source content: "România [Facebook]" — entry rendered with the ă diacritic, contact link facebook.com/people/Pause-AI-Romania/...
Comparison: Directory listing, exact rendering, and Facebook contact format all match; same claim appears in scalar:sources[0].note.
Decision: primary-sourced

## Claim 2: "the international AI-safety movement calling for a coordinated, treaty-backed pause on the training of the most powerful general-purpose AI systems"

Source: https://pauseai.info/proposal
Source tier: primary
Source content: "Implement a temporary pause on the training of the most powerful general AI systems, until we know how to build them safely and keep them under democratic control" — implemented via a binding international treaty establishing an International AI Safety Agency.
Comparison: Body characterization of the parent org's demand matches the proposal page's pause-on-training demand and treaty mechanism.
Decision: primary-sourced

## Claim 3: "named on PauseAI Global's About page under a single national-leader listing for Raluca Spataru"

Source: https://pauseai.info/about
Source tier: primary
Source content: About page names "Romania: Raluca Spataru" among national chapter leads.
Comparison: Exact match; living-person public-role claim resting on a primary document per the Person sourcing threshold; same claim appears in scalar:sources[1].note.
Decision: primary-sourced

## Claim 4: roster of other national-chapter leads (Elmore US, Miller UK, Peyrot FR, Schmidt DE, García González ES, Consonni IT, Carl SE, Jaroš CZ, Sabiu NG, Ouko KE, Jankovic RS, Eliosoff CA, Huang and Horniak AU)

Source: https://pauseai.info/about
Source tier: primary
Source content: "US: Holly Elmore; UK: Joseph Miller; France: Clémence Peyrot; Germany: Benjamin Schmidt; Spain: Ayoze García González; Italy: Giulia Consonni; Sweden: Carl; Czechia: Matěj Jaroš; Nigeria: Khadija Sabiu; Kenya: Seth Momanyi Ouko; Serbia: Svetozar Jankovic; Canada: Jeremy Eliosoff; Australia: Michael Huang, Peter Horniak"
Comparison: All fourteen names and country pairings in the body (and scalar:sources[1].note) match the About page exactly.
Decision: primary-sourced

## Claim 5: "primary public digital presence is its Facebook page … Full page content is authentication-gated and not accessible without a Facebook login"

Source: https://www.facebook.com/people/Pause-AI-Romania/61581783381263/
Source tier: primary
Source content: Unauthenticated fetch returns only the page title "Pause AI Romania | Bucharest" — no substantive page content visible without login.
Comparison: Directory confirms Facebook as the listed contact (Claim 1); direct unauthenticated access reproduces the auth-gating described; same claim appears in scalar:sources[2].note.
Decision: primary-sourced

## Claim 6: "social-media-anchored listing tier — alongside PauseAI Kenya (X / Twitter) and PauseAI Nigeria (WhatsApp) — rather than the dedicated-national-website tier used by the Czechia, Germany, France, Spain, Sweden, Australia, Canada, UK, and US chapters"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Kenya — x.com/Pauseaikenya; Nigeria — chat.whatsapp.com invite; dedicated websites: pauseai.cz, pause-ai.de, pauseia.fr, pauseai.es, pauseai.se, pauseai.info/australia, pauseai.ca, pauseai.uk, pauseai-us.org.
Comparison: All eleven contact-format assignments match the current directory; same claim appears in scalar:sources[0].note.
Decision: primary-sourced

## Claim 7: "Romania does not appear in PauseAI Global's documented protest history for any of the major federation protest cycles through early 2025"

Source: https://pauseai.info/protests
Source tier: primary
Source content: No mention of Romania or any Romanian city on the protest index, the 2024-may page, or the 2025-february page.
Comparison: Negative claim confirmed against the federation's own protest record across all three pages.
Decision: primary-sourced

## Claim 8: "the May 2024 International Day of Action (thirteen countries)"

Source: https://pauseai.info/2024-may
Source tier: primary
Source content: Page lists protests in San Francisco, New York City, Portland, Berlin, London, Rome, Stockholm, Den Haag, Paris, Oslo, Sydney, Ottawa, Reykjavík, São Paulo — 14 cities across approximately 12 countries; no explicit country count stated on the page.
Comparison: The "thirteen countries" token cannot be confirmed — the primary record states no count and my derived count (~12) is from a summarized extraction that may be incomplete; too ambiguous to assert a correction. The token originates from event-pauseai-international-day-of-action-2024-05-13.
Decision: uncorroborated

## Claim 9: "the February 2025 Paris AI Action Summit wave (eighteen cities)"

Source: https://pauseai.info/2025-february
Source tier: primary
Source content: Enumerated distinct cities: Paris, New York, Victoria, London, Berlin, Brussels, Zürich, Prague, Milan, Stockholm, Copenhagen, Oslo, Kristiansand, Trondheim, Kinshasa, Brazzaville, N'Djaména, Melbourne — "Total count: 18 distinct cities."
Comparison: Exact count of the primary record's city list matches the body's "eighteen cities."
Decision: primary-sourced

## Claim 10: "Serbia is also listed on the PauseAI communities directory with a dedicated website and Svetozar Jankovic as chapter lead, but is not yet in-corpus at draft time"

Source: https://pauseai.info/communities
Source tier: primary
Source content: "Serbia — Dedicated website — pauseai.rs"; About page: "Serbia: Svetozar Jankovic". Corpus git history: lg-pauseai-serbia.md first committed 2026-06-09, after this entity's 2026-06-03 draft date.
Comparison: Directory and About page confirm the listing and lead; the draft-time-qualified "not yet in-corpus" held at draft time (Serbia entity landed six days later, so the qualifier keeps the claim accurate).
Decision: primary-sourced

## Claim 11: "the corpus's first Southeastern European PauseAI entry and the corpus's first local group of any kind anchored in the Southeastern European region"

Source: corpus scan (product/entities/ tags and git creation dates)
Source tier: primary
Source content: Only local-groups carrying the southeastern-europe tag are lg-pauseai-romania (created 2026-06-03) and lg-pauseai-serbia (created 2026-06-09); no other SE-European local group (Bulgaria, Greece, Croatia, Bosnia, Albania) exists in product/entities/local-groups/.
Comparison: Corpus-internal precedence claim confirmed mechanically against the corpus's own record — Romania predates the only other SE-European entry.
Decision: primary-sourced

## Claim 12: "PauseAI Czechia, anchored across Prague and Brno with an executed February 2025 protest, a recurring meetup programme, and the Ideathon AI student-engagement programme"

Source: https://pauseai.cz/ ; https://pauseai.info/2025-february
Source tier: primary
Source content: pauseai.cz navigation lists "Ideathon" (ideathon.pauseai.cz); 2025-february page lists Prague among protest cities. Current pauseai.cz homepage shows no evidence of Brno anchoring or a recurring meetup programme.
Comparison: Two of four components confirmed (Prague February 2025 protest, Ideathon); Brno anchoring and recurring meetups not found in the sources fetched this session — partial confirmation of a composite claim. Not a finding of error; the Czechia entity carries its own sourcing.
Decision: uncorroborated

## Claim 13: "Poland (PauseAI Polska, launch-phase with a dedicated Polish-language website)"

Source: https://pauseai.pl/
Source tier: primary
Source content: Live Polish-language site: "Zatrzymajmy niekontrolowany rozwój sztucznej inteligencji" — presents itself as the Polish chapter of the international PauseAI movement.
Comparison: The factual component (dedicated Polish-language website exists and is live) confirmed directly; "launch-phase" is characterization, not audited. Note: the global communities directory currently lists Poland with an email contact rather than the website — not a contradiction (the site exists), but worth knowing.
Decision: primary-sourced
