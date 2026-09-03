---
entity_id: lg-pauseai-serbia
entity_hash: 080160d6180a6f26001cec63da8468d3897edc02
audit_date: 2026-09-03
pass: 1
status: corrections-pending
claims_total: 17
claims_corroborated: 1
claims_primary_sourced: 11
claims_single_source: 0
claims_uncorroborated: 3
open_corrections: 2
sources_consulted:
  - https://pauseai.rs/
  - https://pauseai.rs/o-nama
  - https://pauseai.rs/kontakt/
  - https://pauseai.rs/sitemap.xml
  - https://pauseai.rs/post-sitemap.xml
  - https://pauseai.rs/kada-sud-poruci-da-veliki-ne-mogu-da-rade-sta-zele/
  - https://pauseai.rs/kada-botovi-odlucuju-ko-sme-da-govori/
  - https://pauseai.rs/srce-vestacke-inteligencije-ne-sme-kucati-u-mraku/
  - https://pauseai.rs/kako-zabrana-izvoza-retkih-ruda-iz-kine-utice-na-razvoj-vestacke-inteligencije/
  - https://pauseai.info/about
  - https://pauseai.info/communities
  - https://pauseai.info/protests
  - https://pauseai.info/national-groups
  - https://raw.githubusercontent.com/PauseAI/pauseai-website/main/src/posts/about.md
  - https://raf.edu.rs/en/teaching-staff/dr-svetozar-jankovic/
  - https://pauseai.pl/
  - https://www.linkedin.com/in/sjankovic/
---

## Claim 1: "the Serbian national chapter of PauseAI ... an autonomous part of the global PauseAI network"

Source: https://pauseai.rs/o-nama + https://pauseai.info/communities
Source tier: primary
Source content: o-nama: operates "completely autonomously" while "part of the global PauseAI movement"; communities directory lists "Srbija" with link https://pauseai.rs/
Comparison: Chapter's own site and PauseAI Global's directory independently confirm chapter status and autonomy.
Decision: corroborated

## Claim 2: "Based in Belgrade" (body) + scalar:location ("Belgrade, Serbia")

Source: no canonical source found
Source tier: none
Source content: pauseai.rs homepage, o-nama, and kontakt pages fetched this session state no city/seat; web search for the umbrella NGO "DC LINK" Belgrade returned no results naming it
Comparison: No reachable source states a Belgrade seat for the chapter or for DC LINK; plausible but unsourced. Not a finding of error.
Decision: uncorroborated

## Claim 3: "operates as a project under the Serbian NGO DC LINK on a nonprofit, non-commercial basis" + volunteer-run self-description

Source: https://pauseai.rs/o-nama
Source tier: primary
Source content: "a project and initiative of the NGO DC LINK," functioning on a nonprofit basis; "volunteers gathered around the idea" of protecting society from AI risks
Comparison: Exact match on structure, nonprofit basis, and volunteer self-description (body quote matches o-nama text).
Decision: primary-sourced

## Claim 4: "among the minority of PauseAI national chapters to maintain a dedicated national website ... in their own language"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Chapters with own-domain sites: Canada, Czechia, France, Germany, Serbia, Spain, Sweden, UK; others (Australia, Kenya, Nigeria, Romania, Netherlands, Poland-as-listed) rely on social media or email contact
Comparison: Serbia is one of 8 own-website chapters among a larger directory — "minority" holds; pauseai.rs content is in Serbian.
Decision: primary-sourced

## Claim 5: "No founding date is stated on the website; the earliest published blog post is dated November 17, 2025, establishing the outer bound on the chapter's public launch"

Source: https://pauseai.rs/post-sitemap.xml
Source tier: primary
Source content: Post sitemap lists https://pauseai.rs/kako-zabrana-izvoza-retkih-ruda-iz-kine-utice-na-razvoj-vestacke-inteligencije/ (lastmod 2025-10-18T10:52:08), .../if-anyone-builds-it-everyone-dies-knjiga... (2025-10-18T15:32:49), .../vestacka-inteligencija-i-ljudi-geoffrey-hinton... (2025-10-24T09:58:23) — all predating the November 17, 2025 post (.../kada-sud-poruci... lastmod 2025-11-17T23:01:19)
Comparison: "No founding date stated" confirmed (o-nama). But the site's earliest post dates to October 18, 2025, not November 17, 2025 — three posts predate the claimed earliest. Replacement token: "October 18, 2025". Fix locations: body § Founding and structure, and scalar:sources[3].note (the o-nama note carries the same "earliest blog post on the site dated November 17 2025" sentence). Rank Math lastmod cannot predate publication, so the October posts existed before the 2026-06-09 draft.
Decision: correction

## Claim 6: "The chapter's national director is Svetozar Janković ... named as Serbia's national director on PauseAI Global's About page alongside 14 other national-chapter leads" + scalar:key_people + scalar:sources[1].note (About-page leads list)

Source: https://pauseai.info/about (leads list unrenderable); https://www.linkedin.com/in/sjankovic/
Source tier: caution
Source content: pauseai.info/about's "National Leaders" section renders only placeholder asterisks on fetch (JS-loaded; /national-groups likewise shows "Loading national groups..."); LinkedIn search-index title: "Svetozar Jankovic, doc. dr - ... | Docent @RAF | National director PauseAI Serbia"
Comparison: The cited About page's leaders list (and the 14-other-leads roster in sources[1].note) cannot be rendered by fetch, so the quoted content is unconfirmable this session; the only reachable support is the subject's own LinkedIn headline (caution tier, self-stated). Person-affiliation claims require primary or mainstream sourcing; the chapter's own site names no individuals. Not a finding of error — the audit reaches its limits here.
Decision: uncorroborated

## Claim 7: Janković "holds a doctorate in Technical Sciences (Faculty of Mechanical Engineering, University of Belgrade, 2005) and serves as Docent ... at the School of Computing (RAF) ... elected to that rank in 2023. He previously headed the School of Computers at the Vinča Nuclear Institute ... from 2006 to 2019" + scalar:sources[4].note

Source: https://raf.edu.rs/en/teaching-staff/dr-svetozar-jankovic/
Source tier: primary
Source content: Rank: Docent, elected 2023 at the Faculty of Computing, Belgrade; PhD Technical Sciences, Faculty of Mechanical Engineering, University of Belgrade, 2005; "Head of the Computer School 'Vinca'" at the Vinca Nuclear Institute, 2006 to 2019
Comparison: All four tokens (PhD field/faculty/year, Docent rank, 2023 election, Vinča headship 2006–2019) match the employer's official staff page.
Decision: primary-sourced

## Claim 8: the four demands (pause on most-powerful systems; Serbian AI laws and oversight institutions; AI content labeling and accountability; Serbia's representation in global AI negotiations) + scalar:sources[2].note demands list

Source: https://pauseai.rs/
Source tier: primary
Source content: Four requests: (1) pause development of the most powerful systems until safety is assured; (2) clear laws and institutions established in Serbia; (3) labeling of AI-generated content and accountability from those using it; (4) Serbia's voice in global AI negotiations
Comparison: All four demands match the homepage in substance and order.
Decision: primary-sourced

## Claim 9: "Three posts were published between November 2025 and March 2026"

Source: https://pauseai.rs/post-sitemap.xml
Source tier: primary
Source content: Sitemap shows exactly three posts with lastmod in that window: 2025-11-17, 2026-01-26, 2026-03-07
Comparison: Literally accurate for the stated window; the surrounding framing (blog output began November 2025) is the error recorded in Claim 5 — the blog also carried three October 2025 posts, and a July 2026 post postdates the draft (not an error at draft time).
Decision: primary-sourced

## Claim 10: "November 17, 2025 — a report on a German court ruling on AI regulation"

Source: https://pauseai.rs/kada-sud-poruci-da-veliki-ne-mogu-da-rade-sta-zele/ + post-sitemap
Source tier: primary
Source content: Post reports a Munich regional court ruling that OpenAI violated German copyright law by training on nine German songs without authorization (GEMA case; Grönemeyer, Fischer); sitemap lastmod 2025-11-17
Comparison: Date and German-court subject confirmed. Minor imprecision: the ruling is a copyright ruling applied to AI training rather than "AI regulation" — paraphrase-level, no single-token fix.
Decision: primary-sourced

## Claim 11: "January 26, 2026 — 'Kada botovi odlučuju ko sme da govori' ... coordinated bot attacks on independent Serbian media and the risks of automated moderation systems being weaponized against independent journalism"

Source: https://pauseai.rs/kada-botovi-odlucuju-ko-sme-da-govori/ + post-sitemap
Source tier: primary
Source content: Post describes "waves of fake followers, coordinated reports, then suspensions" hitting independent Serbian media, and automated platform penalties triggered by bot networks "without real investigation"; sitemap lastmod 2026-01-26
Comparison: Title, date, and topic all match.
Decision: primary-sourced

## Claim 12: "March 7, 2026 — 'Srce veštačke inteligencije ne sme kucati u mraku' — calling for public oversight of a Serbian-language LLM reportedly under development for Expo 2027, raising concerns about political deadline pressure, data bias, and social-engineering risk"

Source: https://pauseai.rs/srce-vestacke-inteligencije-ne-sme-kucati-u-mraku/ + post-sitemap
Source tier: primary
Source content: Post discusses the announced national language model for Expo 2027 (Marko Čadež announcement); names political-deadline pressure, data bias ("automated propaganda tool" risk), social engineering; demands "urgent transparency and democratic oversight"; sitemap lastmod 2026-03-07
Comparison: Title, date, subject, all three named concern categories, and the public-oversight call match.
Decision: primary-sourced

## Claim 13: "The chapter is the corpus's first entry in the Balkans and is among..." / "PauseAI Serbia is the corpus's first entry in the Balkans and the first from Serbia"

Source: corpus record (product/entities/, created: frontmatter)
Source tier: primary
Source content: org-share-foundation (SHARE Foundation, Serbia; tagged serbia/balkans) created: 2026-06-03; camp-share-foundation-safe-city-surveillance-serbia-2019-ongoing created: 2026-06-03 — both predate lg-pauseai-serbia (created: 2026-06-09)
Comparison: The corpus's own record contradicts both "first entry in the Balkans" and "first from Serbia": the SHARE Foundation cluster (Serbian org + campaign) entered six days earlier. Appears twice in body (intro ¶ and § Place in the movement). No single-token replacement — the sentence needs removal or reframing (e.g. "first PauseAI chapter in the Balkans" would be defensible), so this correction requires prose judgment: Editor should route to Researcher per the Audit-discrepancy backfill act.
Decision: correction

## Claim 14: peer-cluster descriptors — Czechia "dedicated Czech-language website", Polska "Polish-language website", Romania "formation-phase, Facebook-anchored"

Source: https://pauseai.info/communities + https://pauseai.pl/
Source tier: primary
Source content: Communities directory: Czechia — pauseai.cz; Romania — social-media contact only; pauseai.pl is live with Polish-language content (directory currently lists Poland as mailto:patryk@pauseai.info — drift from the site link, but the site itself is up)
Comparison: Website/anchoring characterizations confirmed. Czechia's "active protest programme, Ideathon" descriptor is a peer-entity claim verified under lg-pauseai-czechia's own audit, not re-verified here.
Decision: primary-sourced

## Claim 15: "No PauseAI Serbia-specific protest events appear in PauseAI Global's documented protest history"

Source: https://pauseai.info/protests
Source tier: primary
Source content: Protest locations listed: UK, US, Netherlands, France, Germany, Sweden, Belgium, Australia, Italy cities; "No, there is no protest listed for Serbia or Belgrade on this page"
Comparison: Confirmed — no Serbia/Belgrade entry on the protest-history page.
Decision: primary-sourced

## Claim 16: scalar:sources[0].note — Serbia maintains a full national website "alongside Czechia, Germany, France, Spain, Sweden, Australia, Canada, UK, and US"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Current own-website list: Canada, Czechia, France, Germany, Serbia, Spain, Sweden, UK; Australia now listed with social-media contact only; US not surfaced in the own-website list on this fetch
Comparison: Source drift since last_checked 2026-06-09 — the directory's own-website roster no longer matches the note's list (Australia moved to social-media contact; Poland moved from site to mailto). The note's original accuracy cannot be confirmed (web.archive.org blocked); the live page conflicts with it. Not a body error; the entity's load-bearing "minority" claim survives (Claim 4).
Decision: uncorroborated

## Claim 17: scalar:sources[2].note contact details — "contact: kontakt@pauseai.rs; also lists Facebook (facebook.com/PauseAISerbia) and Discord (discord.gg/gUsKShKM)"

Source: https://pauseai.rs/ + https://pauseai.rs/kontakt/
Source tier: primary
Source content: Homepage social links: facebook.com/PauseAISerbia, discord.gg/gUsKShKM (plus a LinkedIn company page added since); kontakt page: "kontakt@pauseai.rs"
Comparison: Email, Facebook, and Discord all match the live site.
Decision: primary-sourced
