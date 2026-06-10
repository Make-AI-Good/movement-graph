---
entity_id: lg-pauseai-czechia
entity_hash: cfb9eb665ba8937e2c68feb5235d48b6b43e263c
audit_date: 2026-05-28
pass: 1
status: corrections-pending
claims_total: 22
claims_corroborated: 17
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 2
claims_uncorroborated: 3
sources_consulted:
  - https://www.pauseai.cz/
  - https://www.pauseai.cz/kdo-jsme
  - https://www.pauseai.cz/udalosti
  - https://pauseai.info/about
  - https://pauseai.info/2025-february
  - https://luma.com/6t4fmgw0
  - https://ideathon.pauseai.cz/
  - https://en.wikipedia.org/wiki/AI_Action_Summit
---

## Claim 1: "PauseAI Czechia (PauseAI CZ) is the Czech national chapter of [PauseAI]"

Source: https://www.pauseai.cz/ and https://pauseai.info/about
Source content: pauseai.cz: "česká odnož celosvětového hnutí PauseAI" (Czech branch of the global PauseAI movement). pauseai.info/about lists "Matěj Jaroš" as the Czechia national-chapter lead alongside other national-chapter leads.
Comparison: Body claim matches both sources.
Decision: corroborated

## Claim 2: "The chapter is anchored across Prague and Brno"

Source: https://www.pauseai.cz/udalosti and https://ideathon.pauseai.cz/
Source content: Events page lists chapter events at venues in both Brno (Místogalerie - Dům Skleněná louka, Kounicova 23) and Prague (Municipal Library of Prague, Mariánské nám. 98/1). Ideathon microsite title reads "Ideathon AI 2026 – PauseAI | Praha & Brno".
Comparison: Dual Prague-and-Brno anchor confirmed in both venue listings and the Ideathon site title.
Decision: corroborated

## Claim 3: "Matěj Jaroš ... Předseda (Chairman) and the chapter's social-media administrator"

Source: https://www.pauseai.cz/kdo-jsme
Source content: Page lists Matěj Jaroš's role as "Předseda PauseAI CZ" and includes social-media administration in his named responsibilities.
Comparison: Role and second-responsibility line match.
Decision: corroborated

## Claim 4: "Dalibor Krejčí as Vice-chairman and media contact"

Source: https://www.pauseai.cz/kdo-jsme
Source content: "Místopředseda PauseAI CZ" and "Kontaktní osoba pro média" appear under Dalibor Krejčí.
Comparison: Místopředseda = Vice-chairman; media-contact role explicit. Match.
Decision: corroborated

## Claim 5: "Ondřej Lukeš (website and social-media manager) and Jiří Košárek as the chapter's co-founders"

Source: https://www.pauseai.cz/kdo-jsme
Source content: Both Ondřej Lukeš and Jiří Košárek listed as "Spoluzakladatel PauseAI CZ" (co-founder); Lukeš additionally listed as "Správce webu a sociálních sítí PauseAI CZ".
Comparison: Co-founder status and Lukeš's additional role both match.
Decision: corroborated

## Claim 6: "Ondřej Kubů (mathematician and newsletter editor)"

Source: https://www.pauseai.cz/kdo-jsme
Source content: Kubů listed with roles "Matematik" and "Editor newsletteru".
Comparison: Both roles match.
Decision: corroborated

## Claim 7: "Dominika Olivová (filmmaker, media team)"

Source: https://www.pauseai.cz/kdo-jsme
Source content: Olivová listed with roles "Filmařka" and "Členka mediálního týmu".
Comparison: Match.
Decision: corroborated

## Claim 8: External expert panel — "Charles University sociologist Martin Nekola, education-and-technology specialist Bohumil Kartous, data-scientist and economist Martin Vraný, macroeconomics expert Zdeněk Rosenberg, Pardubice University philosophy department head Ondřej Krása, and Human-aligned AI Summer School co-organiser Martin Vlach"

Source: https://www.pauseai.cz/kdo-jsme
Source content: All six experts present on the page with credentials matching the body listing.
Comparison: Match across all six expert listings and their attributed credentials.
Decision: corroborated

## Claim 9: PauseAI Global about-page chapter-lead list — US Holly Elmore, UK Joseph Miller, France Clémence Peyrot, Germany Benjamin Schmidt, Spain Ayoze García González, Italy Giulia Consonni, Sweden Carl, Romania Raluca Spataru, Nigeria Khadija Sabiu, Kenya Seth Momanyi Ouko, Serbia Svetozar Jankovic, Canada Jeremy Eliosoff, Australia Michael Huang and Peter Horniak

Source: https://pauseai.info/about
Source content: Each named lead appears on the about page in the indicated chapter, including the dual Australia naming.
Comparison: Match across the full list.
Decision: corroborated

## Claim 10: "Maxime Fournes's elevation to PauseAI Global CEO in late 2025"

Source: https://pauseai.info/about
Source content: Executive Team section lists "Maxime Fournes CEO PauseAI Global".
Comparison: CEO role confirmed; the precise late-2025 timing is not contradicted by the source, and the load-bearing fact (Fournes is now Global CEO, Peyrot now leads France) is corroborated.
Decision: corroborated

## Claim 11: scalar:sources[0].note — "names the chapter as 'součástí globálního hnutí PauseAI' (part of the global PauseAI movement)"

Source: https://www.pauseai.cz/
Source content: The page actually says "PauseAI CZ je česká odnož celosvětového hnutí PauseAI" — not "součástí globálního hnutí PauseAI". The quoted Czech wording is wrong (different lexicon: odnož vs. součást; celosvětového vs. globálního). The underlying claim (chapter identifies as part of the global PauseAI movement) is true, but the quoted source text differs from what the page contains.
Comparison: The note's quoted Czech text is not present on the page; the page uses different wording for the same idea. The fix lives in sources[0].note's first sub-clause — Editor act should replace the quoted phrase with the page's actual wording or de-quote and paraphrase.
Decision: correction

## Claim 12: scalar:sources[0].note (mission quote) and body §1 mission quote — "vytvoření globální dohody, která pozastaví vývoj umělé obecné inteligence (AGI), dokud nebude možné zajistit její bezpečnost"

Source: https://www.pauseai.cz/
Source content: The page says "Naším cílem je vytvoření globální dohody, která pozastaví vývoj **obecné umělé inteligence (AGI)**, jež by svými schopnostmi překonala lidský intelekt." The phrase "dokud nebude možné zajistit její bezpečnost" does not appear; the page separately says "Tato pauza nám poskytne čas zajistit bezpečnost" in an adjacent sentence.
Comparison: Two errors in the quoted Czech: (a) word order "umělé obecné inteligence" should be "obecné umělé inteligence"; (b) the trailing clause "dokud nebude možné zajistit její bezpečnost" is not on the page — it appears to fuse the mission sentence with the page's separate sentence about a pause providing time to ensure safety. Same quote appears in body paragraph "Czech-language chapter website with petition and email-builder tools" — fix needed in both the body bullet and sources[0].note.
Decision: correction

## Claim 13: Past collaborators list — "Efektivní Altruismus (Effective Altruism Czech Republic), SCIO, Smíchovská střední průmyslová škola a gymnázium, Students for Impact, České Priority, and KISK"

Source: https://www.pauseai.cz/
Source content: Page displays partner logos/links for Efektivní Altruismus, Scio, Smíchovská střední průmyslová škola a gymnázium, Students for Impact, České Priority, and KISK.
Comparison: All six match; SCIO vs Scio is a casing variant within paraphrase tolerance.
Decision: corroborated

## Claim 14: "the 7-11 February 2025 international protest wave around the Paris AI Action Summit"

Source: https://pauseai.info/2025-february
Source content: Protest wave dated "February 7–11" centred on the Paris AI Action Summit.
Comparison: Dates and event match.
Decision: corroborated

## Claim 15: "Paris AI Action Summit co-chaired by Emmanuel Macron and Narendra Modi"

Source: https://en.wikipedia.org/wiki/AI_Action_Summit
Source content: "The summit was co-chaired by French President Emmanuel Macron and Indian Prime Minister Narendra Modi."
Comparison: Match. Public-event official-role claim — Wikipedia is sufficient under the source rule's first list.
Decision: corroborated

## Claim 16: Eighteen-city protest-wave list — "Paris, New York, Victoria, London, Berlin, Brussels, Zürich, Prague, Milan, Stockholm, Copenhagen, Oslo, Kristiansand, Trondheim, Kinshasa, Brazzaville, N'Djaména, and Melbourne"

Source: https://pauseai.info/2025-february
Source content: The same eighteen cities are listed.
Comparison: Match.
Decision: corroborated

## Claim 17: "Prague action ... at Václavské náměstí (Wenceslas Square) ... naming Matěj Jaroš as the protest's organiser"

Source: https://luma.com/6t4fmgw0
Source content: Event title "PauseAI protest Pařížský summit - Praha"; address "Václavské nám., 110 00 Praha-Praha 1, Czechia"; "Hosted by Matěj Jaroš".
Comparison: Venue and organiser both match. The body's "Luma event page titled 'PauseAI protest Pařížský summit — Praha'" uses an em-dash where the page uses a hyphen — paraphrase tolerance.
Decision: corroborated

## Claim 18: "a May 2026 AI Circle Meeting at VEGALITE in Brno co-organised with the Effective Altruism Society"

Source: https://www.pauseai.cz/udalosti
Source content: Page currently lists an AI Circle Meeting on 1 June 2026 at "Místogalerie - Dům Skleněná louka, Kounicova 23, Brno", co-organised with the Effective Altruism Society ("setkání kruhu AI organizovaného PauseAI CZ a spolkem Efektivního altruismu"). The page does not show any May 2026 AI Circle Meeting at VEGALITE.
Comparison: The events page has rotated past May 2026 and replaced the listing with a June 1 event at a different venue; the historical May VEGALITE entry cannot be confirmed or contradicted from the current page, and no canonical archive of the page's May 2026 state is available.
Decision: uncorroborated

## Claim 19: "a May 2026 Prague meetup at the Municipal Library of Prague on Mariánské náměstí"

Source: https://www.pauseai.cz/udalosti
Source content: A meetup is now listed for 4 June 2026 at "Municipal Library of Prague, Mariánské nám. 98/1, 110 00 Praha 1". No May 2026 entry remains.
Comparison: Same rotation issue — the venue is plausibly the same recurring location but the May date cannot be verified from the current page.
Decision: uncorroborated

## Claim 20: "a May 2026 expert meeting at Na Boršově in Prague 1"

Source: https://www.pauseai.cz/udalosti
Source content: No entry for an expert meeting at Na Boršově appears on the current page.
Comparison: Cannot be verified or contradicted from the current page; same rotation pattern as the other May 2026 entries.
Decision: uncorroborated

## Claim 21: "a June 2026 panel discussion"

Source: https://www.pauseai.cz/udalosti
Source content: A "Panel Discussion" is listed in June 2026 (June 18-19 window).
Comparison: Match.
Decision: corroborated

## Claim 22: "April 2026 ideathons held in both Prague and Brno on the ethical and societal challenges posed by artificial intelligence, with mentorship and seventeen workshop topics"

Source: https://www.pauseai.cz/udalosti and https://ideathon.pauseai.cz/
Source content: Events page references the April 2026 Ideathons in Prague and Brno, "17 různorodých témat od dopadů na demokracii až po 'AI alignment'" (17 varied topics from impacts on democracy to AI alignment) and "etické a společenské výzvy" (ethical and societal challenges). Ideathon microsite title: "Ideathon AI 2026 – PauseAI | Praha & Brno".
Comparison: Dual-city programme, ethical-and-societal framing, and 17-topic count all match. Workshop-count phrasing ("seventeen workshop topics" vs "17 různorodých témat") within paraphrase tolerance.
Decision: corroborated
