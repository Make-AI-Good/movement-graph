---
entity_id: lg-pauseai-poland
entity_hash: c7925b811cf81d35838ee8eba2a42ab78007659a
audit_date: 2026-06-11
pass: 1
status: supported
claims_total: 19
claims_corroborated: 0
claims_primary_sourced: 14
claims_single_source: 0
claims_uncorroborated: 5
open_corrections: 0
sources_consulted:
  - https://pauseai.pl/
  - https://pauseai.pl/dolacz
  - https://pauseai.pl/dzialanie/
  - https://pauseai.info/communities
  - https://pauseai.info/protests
  - https://pauseai.info/join
  - https://pauseai.info/proposal
  - https://pauseai.info/2024-may
  - https://pauseai.info/2025-february
  - https://pauseai.substack.com/p/paris-ai-summit-petition-and-protests
  - https://ideathon.pauseai.cz/
  - https://www.pauseai.cz/
  - https://time.com/6977680/ai-protests-international/
---

## Claim 1: PauseAI Polska "is listed on PauseAI Global's communities directory as the Polish national chapter"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Directory lists "Polska" among 16 national chapters (alongside Australia, Canada, Czechia, France, Deutschland, Italia, Kenya, Nederland, Nigeria, România, Srbija, España, Sverige, United Kingdom, United States).
Comparison: Polska listing present as a national chapter. PauseAI's own directory is the primary source for its own chapter roster.
Decision: primary-sourced

## Claim 2: PauseAI is "the international AI-safety movement calling for a coordinated, treaty-backed pause on the training of the most powerful general-purpose AI systems"

Source: https://pauseai.info/proposal
Source tier: primary
Source content: "Implement a temporary pause on the training of the most powerful general AI systems, until we know how to build them safely and keep them under democratic control" — with the page stating "we need a global pause" via international agreement and an international AI Safety Agency.
Comparison: Pause-on-most-powerful-general-AI and treaty/global-coordination framing both match the parent org's own proposal page.
Decision: primary-sourced

## Claim 3: "The chapter operates a dedicated Polish-language website at pauseai.pl"

Source: https://pauseai.pl/
Source tier: primary
Source content: Site is live, branded "PauseAI Polska", content entirely in Polish ("Zatrzymajmy niekontrolowany rozwój sztucznej inteligencji").
Comparison: Website live and Polish-language as claimed.
Decision: primary-sourced

## Claim 4: Listed "with contact email patryk@pauseai.info"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Polska entry carries "mailto:patryk@pauseai.info".
Comparison: Contact email matches exactly; the @pauseai.info domain claim is directly visible in the address.
Decision: primary-sourced

## Claim 5: "The chapter routes new members through the global pauseai.info/join form"

Source: https://pauseai.pl/dolacz
Source tier: primary
Source content: "Przejdź na stronę globalnego Pause AI, wypełnij formularz i dołącz do polskiej grupy" with the call-to-action button linking to pauseai.info/join#after-signing-up.
Comparison: The chapter's own join page routes to the global join form as claimed.
Decision: primary-sourced

## Claim 6: "...and into PauseAI International's Discord server" (body; also scalar:sources[0].note "routes new members to the global pauseai.info/join form and into PauseAI International's Discord")

Source: https://pauseai.pl/dolacz ; https://pauseai.info/join
Source tier: none
Source content: pauseai.pl/dolacz: "Discord is not mentioned anywhere on this page"; pauseai.info/join onboarding directs to "Member Community Welcome Meetings, or a local social event" — Discord appears only as a footer social link, not an onboarding route.
Comparison: The Discord-routing element of the claim is not confirmed on the chapter's join page or the global join page as currently published. Scalar fix location if the Researcher acts: sources[0].note and body § Structure and contact. Not a single-token correction — the pages may have changed since last_checked 2026-06-03.
Decision: uncorroborated

## Claim 7: Website "publishes translated PauseAI International content on AI risk, advocacy pathways (writing to politicians, signing petitions, attending protests), and signatories lists including superintelligence-statement.org and aistatement.com"

Source: https://pauseai.pl/ ; https://pauseai.pl/dzialanie/
Source tier: primary
Source content: Homepage covers AI risk and references "Superintelligence Statement (superintelligence-statement.org): ponad 110 000 sygnatariuszy" and "AI Risk Statement (aistatement.com): podpisane przez setki ekspertów"; the action page lists "Napisz do swoich polityków", "Protestuj: Dołącz do jednego z protestów", "Podpisuj petycje: Naszą, Statement on Superintelligence, International AI Treaty".
Comparison: All named elements — AI-risk content, the three advocacy pathways, both signatories lists — confirmed on the chapter's own pages.
Decision: primary-sourced

## Claim 8: scalar:sources[0].note "no founding date stated" on pauseai.pl

Source: https://pauseai.pl/
Source tier: primary
Source content: "No founding date is stated."
Comparison: Negative claim confirmed against the homepage as currently published.
Decision: primary-sourced

## Claim 9: "Poland does not appear in PauseAI Global's documented protest history" for the major federation protest cycles (also scalar:sources[2].note "Poland does not appear in any of the documented protest cycles")

Source: https://pauseai.info/protests ; https://pauseai.info/2024-may ; https://pauseai.info/2025-february
Source tier: primary
Source content: "Poland and Polish cities do not appear anywhere on this page" (protests history); no Polish city in the May 2024 city list or the February 2025 18-city list.
Comparison: Absence confirmed across the protest history page and both named protest-wave pages.
Decision: primary-sourced

## Claim 10: "the May 2024 International Day of Action ... (thirteen countries)"

Source: https://pauseai.info/2024-may ; https://time.com/6977680/ai-protests-international/ (via web search aggregation)
Source tier: primary
Source content: PauseAI's own event page enumerates 14 cities — San Francisco, New York City, Portland, Berlin, London, Rome, Stockholm, Den Haag, Paris, Oslo, Reykjavík, Ottawa, Sydney, São Paulo — i.e. 12 countries; search-aggregated TIME coverage says "protests were held across thirteen countries before the AI Seoul Summit"; an EA Forum retrospective mentions nine.
Comparison: Canonical sources conflict on the country count (12 enumerated on the primary event page vs 13 in mainstream coverage vs 9 in a participant retrospective). The body's "thirteen countries" matches TIME but not the primary enumeration; the audit does not pick a winner.
Decision: uncorroborated

## Claim 11: "the February 2025 Paris AI Action Summit wave (eighteen cities)"

Source: https://pauseai.info/2025-february
Source tier: primary
Source content: Event page enumerates exactly 18 cities (Paris, New York, Victoria, London, Berlin, Brussels, Zürich, Prague, Milan, Stockholm, Copenhagen, Oslo, Kristiansand, Trondheim, Kinshasa, Brazzaville, N'Djaména, Melbourne).
Comparison: Exact match to the primary event page's maintained list. PauseAI's pre-event substack announcement said "We have 19 cities confirmed already" including Yaoundé, which is absent from the event page's list — a pre-event confirmation count in flux, not a contradiction of the maintained record. (The protests history page's "15+ cities" is consistent with 18.)
Decision: primary-sourced

## Claim 12: PauseAI Czechia "anchors across Prague and Brno"

Source: https://ideathon.pauseai.cz/ ; https://www.pauseai.cz/
Source tier: primary
Source content: Ideathon AI 2026 is scheduled "Prague on April 17-19, 2026 and Brno on April 24-26, 2026"; pauseai.cz lists a Prague event ("18. 6. 2026 ... Areál Jinonice, Praha 5").
Comparison: Chapter activity documented in both cities on its own sites.
Decision: primary-sourced

## Claim 13: PauseAI Czechia "carries an executed February 2025 protest"

Source: https://pauseai.info/2025-february
Source tier: primary
Source content: "Prague, Czechia" appears in the February 2025 protest city list with an active registration link.
Comparison: Prague's participation in the February 2025 wave is confirmed on the federation's event page.
Decision: primary-sourced

## Claim 14: PauseAI Czechia carries "a recurring meetup programme"

Source: https://www.pauseai.cz/
Source tier: none
Source content: "No recurring meetup programme is mentioned on this webpage" — only a single upcoming Prague event is listed.
Comparison: Not confirmed on the Czech chapter's own site as currently published; no other canonical source consulted this pass documents a recurring meetup programme. Not an error finding — sourcing for this comparison-context claim is thin in this entity.
Decision: uncorroborated

## Claim 15: PauseAI Czechia runs "the Ideathon AI student-engagement programme"

Source: https://ideathon.pauseai.cz/
Source tier: primary
Source content: "Ideathon AI 2026 – PauseAI | Praha & Brno" — an "interdisciplinary event for students organized by PauseAI CZ focused on the impacts and risks of artificial intelligence"; registration free.
Comparison: Programme exists, is student-facing, and is run by PauseAI CZ.
Decision: primary-sourced

## Claim 16: "Sweden, Romania, Serbia, and Italy listed on the global communities page"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Directory lists "Sverige" (Sweden), "România" (Romania), "Srbija" (Serbia), and "Italia" (Italy) among the national chapters.
Comparison: All four named chapters present on the directory. (The "not yet in-corpus at draft time" half is corpus-internal and time-anchored, out of audit remit.)
Decision: primary-sourced

## Claim 17: scalar:sources[1].note — the communities directory "routes supporters to pauseai.pl as the chapter's dedicated national site"

Source: https://pauseai.info/communities
Source tier: none
Source content: "The directory does not link to pauseai.pl" — the Polska entry carries only the mailto contact.
Comparison: The pauseai.pl-link element of the note is not present on the directory as currently published; the page may have changed since last_checked 2026-06-03, and the draft-time state cannot be confirmed this pass. Fix location if the Researcher acts: sources[1].note.
Decision: uncorroborated

## Claim 18: scalar:sources[1].note — national-chapter listing format "used by Czechia, Germany, France, Italy, Sweden, Romania, Serbia, Australia, Canada, the UK, Nigeria, Kenya, the Netherlands, and the US"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Directory's 16 national chapters include all 14 named: Czechia, Deutschland, France, Italia, Sverige, România, Srbija, Australia, Canada, United Kingdom, Nigeria, Kenya, Nederland, United States (plus España and Polska).
Comparison: Every named chapter appears in the directory's national-chapter listing format.
Decision: primary-sourced

## Claim 19: scalar:sources[2].note — the protests page "covers protest events from 2023 through early 2025 across eighteen or more cities"

Source: https://pauseai.info/protests
Source tier: none
Source content: "The protests documented span from May 19-22, 2023 through February 28, 2026."
Comparison: The page as currently published extends through February 2026, not "through early 2025"; whether the note matched the page at last_checked 2026-06-03 cannot be confirmed this pass. The Poland-absence element of the same note is separately confirmed (Claim 9). Fix location if the Researcher acts: sources[2].note date-range phrase.
Decision: uncorroborated
