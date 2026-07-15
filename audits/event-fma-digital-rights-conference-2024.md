---
entity_id: event-fma-digital-rights-conference-2024
entity_hash: 25a84c23b6ed36ce577c8602ff39f99e6f0cf25b
audit_date: 2026-07-15
pass: 1
status: corrections-pending
claims_total: 24
claims_corroborated: 1
claims_primary_sourced: 14
claims_single_source: 4
claims_uncorroborated: 2
open_corrections: 3
sources_consulted:
  - https://fma.ph/drc2024/
  - https://hronlineph.com/2024/02/29/event-digital-rights-conference-fma/
  - https://hronlineph.com/2024/03/23/event-digital-rights-conference-2024-fma/
  - https://fma.ph/2024-philippine-declaration-on-internet-rights-and-principles/
  - https://fma.ph/fmas-2024-in-publications/
  - https://www.rappler.com/technology/phildec-2-experts-discuss-digital-rights-democracy-ai-use-literacy/
  - https://engagemedia.org/projects/drapac23/
  - https://engagemedia.org/2024/drapac24-taipei/
  - https://fma.ph/fma-releases-digital-rights-report-2023-looks-into-the-future-of-ai/
  - https://en.wikipedia.org/wiki/Internet_in_the_Philippines
  - https://en.wikipedia.org/wiki/Southeast_Asia
---

Entity is connective (Event): claim surface is edges and hard specifics per
`mission/MISSION.md § Auditor § Type-shape awareness`. Significance/arc prose without a
hard specific received no decision. Note on retrieval: rappler.com and
engagemedia.org refuse direct fetch (HTTP 403); their content was retrieved via web-search
extraction of those exact URLs this session, noted per claim. hronlineph.com is tiered
`caution` throughout (civil-society advocacy aggregator, not an editorial-standards news
outlet); it never demotes a claim (quality only raises support) but does not count as
canonical on its own.

## Claim 1: "On 20-21 March 2024" (also frontmatter scalar:date = 2024-03-20)

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: "MARCH 20 to 21, 2024"
Comparison: Entity dates match FMA's own conference page exactly; frontmatter `date:` carries the start date.
Decision: primary-sourced

## Claim 2: "at The Loft, Areté, Ateneo de Manila University in Quezon City" (also frontmatter scalar:location = "Quezon City, Philippines")

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: "The Loft, Areté, Ateneo de Manila University"; page's venue map link reads "Quezon City, 1108 Metro Manila"
Comparison: Venue and city both match the FMA page (city via the page's own maps link).
Decision: primary-sourced

## Claim 3: Edge — "the Foundation for Media Alternatives convened the Digital Rights Conference 2024" (frontmatter participating_orgs: org-foundation-for-media-alternatives)

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: Page is FMA's own conference page; organizer "Foundation for Media Alternatives (FMA)"
Comparison: Edge points to the correct corpus entity (file exists at product/entities/organizations/org-foundation-for-media-alternatives.md); organizer confirmed by FMA's own page.
Decision: primary-sourced

## Claim 4: Theme — "30 Years of Philippine Internet: Honoring the Past, Safeguarding the Future"

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: "30 Years of Philippine Internet: _Honoring the Past, Safeguarding the Future_"
Comparison: Verbatim match on the primary source. The hronlineph pre-event repost renders it "…Safeguarding the Present"; hronlineph is caution-tier, so no canonical conflict — FMA's own page governs.
Decision: primary-sourced

## Claim 5: "Co-presented by Internews Philippines, with the support of USAID, the Ateneo School of Government, and the Ateneo School of Science and Engineering"

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: Co-presenter "Internews-Philippines"; supporters "USAID Philippines, Ateneo School of Government (ASOG), School of Science and Engineering (SOSE)"
Comparison: Co-presenter and all three named supporters confirmed on FMA's page.
Decision: primary-sourced

## Claim 6: "with Internet Society–Philippines Chapter, Teravibe, Philippine Network Foundation, PH Cert, and Security Bank as partners"

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: Partners: "Philippine Network Foundation, Internet Society – Philippine chapter, Teravibe, Security Bank, LIGHTS Institute, PH-CERT, Mozilla Philippines, NADPOP, PhNOG"
Comparison: All five entities named in the body are on the FMA partner roster. The page lists four further partners the body omits — incompleteness, not error (out of remit).
Decision: primary-sourced

## Claim 7: Track name — "Freedom of Expression and Censorship" (body § Programme and Tracks, bullet 5; also scalar:sources[0].note, which lists the same six tracks)

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: The six tracks verbatim: "Artificial Intelligence", "Disinformation", "Privacy and Data Protection", "Cybersecurity", "Freedom of Information and Censorship", "Access and Digital Divide"
Comparison: FMA's own page names the fifth track "Freedom of Information and Censorship", not "Freedom of Expression and Censorship". Single-token replacement (Expression → Information) in two locations: body § Programme and Tracks bullet 5 and scalar path sources[0].note. Verified by two independent verbatim-quote fetches of the page. The other five track names match (body adds "the" in "Access and the Digital Divide" — cosmetic, not a token error).
Decision: correction

## Claim 8: "structured across fifteen breakout sessions organized under six thematic tracks, with plenary sessions running alongside"

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: "15 sessions total (Sessions 1-7 on Day 1; Sessions 8-15 on Day 2)" plus 3 plenary sessions; six named tracks
Comparison: Session count, track count, and plenaries-alongside structure all match the FMA programme.
Decision: primary-sourced

## Claim 9: Named participants — "Senator Risa Hontiveros delivered the opening keynote message"; "Dr. Rodolfo Villarica, an original Philippine Internet pioneer"; "Liza Garcia as FMA Executive Director and Peter Mackenzie as Internews Philippines Country Director" (also frontmatter participating_people: person-liza-garcia)

Source: https://fma.ph/drc2024/
Source tier: primary
Source content: Keynote "Hon. Risa Hontiveros — Senator, Republic of the Philippines"; "Dr. Rodolfo Villarica (PH Internet Pioneer)"; "Ms. Liza Garcia — Executive Director, Foundation for Media Alternatives"; "Peter Mackenzie (Country Director, Internews)"
Comparison: All four names and titles confirmed verbatim on the FMA programme page; person-liza-garcia edge points to an existing corpus entity.
Decision: primary-sourced

## Claim 10: "the venue for the launch of the 2024 Philippine Declaration on Internet Rights and Principles (PhilDec 2.0), a consultative update of the original 2015 declaration" / "The March 2024 launch was a consultative draft, with FMA explicitly welcoming public remarks and suggestions"

Source: https://fma.ph/2024-philippine-declaration-on-internet-rights-and-principles/ (and https://www.rappler.com/technology/phildec-2-experts-discuss-digital-rights-democracy-ai-use-literacy/, retrieved via search extraction)
Source tier: primary
Source content: "first launched during the Digital Rights Conference in March 2024"; "In the spirit of openness and collaboration, FMA is welcoming any remarks, comments, and suggestions to the initial draft of the 2024 Declaration"; update of "the first Philippine Declaration on Internet Rights and Principles published in 2015". Rappler independently covers PhilDec 2.0 as presented at the conference.
Comparison: Launch venue, draft/consultative status, and 2015-original relation all match FMA's own declaration page; Rappler is an independent mainstream confirmation.
Decision: corroborated

## Claim 11: "the launch of the 2024 Philippine Declaration on Internet Rights and Principles (PhilDec 2.0) by Al Alegre on the final day"

Source: https://www.rappler.com/technology/phildec-2-experts-discuss-digital-rights-democracy-ai-use-literacy/ (retrieved via search extraction; direct fetch 403)
Source tier: mainstream
Source content: "Alan Alegre, former executive director of the Foundation for Media Alternatives (FMA), along with other ICT, media and human rights experts, stressed the need for an updated declaration" — Rappler places the presentation at the conference on March 21, 2024 (the final day). The hronlineph post-event page (caution tier) also states "he launched the Philippine Declaration on Internet Rights and Principles 2.0".
Comparison: Alegre as launcher and final-day timing supported by one canonical mainstream source (Rappler), with caution-tier support from hronlineph.
Decision: single-source

## Claim 12: "a reassessment of the 2015 original in response to four developments ... the emergence of AI and the digital economy; the pervasiveness of major tech platforms; worsening disinformation; and climate realities" (also scalar:sources[3].note, same four areas)

Source: https://fma.ph/2024-philippine-declaration-on-internet-rights-and-principles/
Source tier: primary
Source content: Declaration addresses "ground-breaking developments that impact Philippine democracy and digital rights" including artificial intelligence emergence, digital economy, tech platform pervasiveness, worsening disinformation, and climate realities
Comparison: The body's four-area grouping matches the FMA page's enumeration (AI and digital economy grouped as one development, as in the entity's source note).
Decision: primary-sourced

## Claim 13: "nine years after FMA published the original 2015 Philippine Declaration" / "marking the thirtieth year of the Philippine Internet"

Source: https://fma.ph/fmas-2024-in-publications/
Source tier: primary
Source content: The 2024 declaration revisits the 2015 declaration, "assessing the Philippine Internet anew" after nine years; conference theme is "30 Years of Philippine Internet"
Comparison: Nine-year gap and thirtieth-anniversary framing both confirmed on FMA's own pages.
Decision: primary-sourced

## Claim 14: Quote — "the past few years have been challenging with how hate and prejudice ran rampant online"

Source: https://fma.ph/2024-philippine-declaration-on-internet-rights-and-principles/
Source tier: primary
Source content: "challenging with how hate and prejudice ran rampant online, rendering the Internet a perilous place for many"
Comparison: Quote appears verbatim on FMA's declaration page as the entity attributes.
Decision: primary-sourced

## Claim 15: "Alegre addressed AI's perils across economic (job displacement), political (weaponisation of AI ...), social (algorithmic bias, discrimination, and privacy erosion), and environmental spheres, and argued ... AI adoption governed by 'stricter development and deployment guidelines'"

Source: https://www.rappler.com/technology/phildec-2-experts-discuss-digital-rights-democracy-ai-use-literacy/ (retrieved via search extraction; direct fetch 403)
Source tier: mainstream
Source content: "Alegre addressed AI's potential perils across economic, political, social, and environmental spheres, including job displacement, algorithmic bias, discrimination, privacy erosion, and the weaponization of AI"; "Alegre advocated for adoption of AI with 'stricter development and deployment guidelines' and a 'human-centered approach'"
Comparison: The substance of the claim — four spheres, the named perils, and the direct quote — is fully supported by Rappler. One canonical mainstream source; the body's own inline citation for this passage is wrong (see Claim 16).
Decision: single-source

## Claim 16: scalar:sources[2].note — the hronlineph post-event page is "primary source for ... Alegre's address of AI perils across economic (job displacement), political (weaponisation of AI), social (algorithmic bias and discrimination, privacy erosion), and environmental spheres, his advocacy for adoption of AI with 'stricter development and deployment guidelines'" (the body's § Philippine Declaration inline link makes the same attribution)

Source: https://hronlineph.com/2024/03/23/event-digital-rights-conference-2024-fma/
Source tier: caution
Source content: Targeted verbatim search of the page found no such content. The page's Alegre passage reads: "With unwavering resolve, he launched the Philippine Declaration on Internet Rights and Principles 2.0, a beacon of hope in the fight for digital freedom and equality." No sentence on the page mentions perils, job displacement, weaponization, algorithmic bias, spheres, or "stricter development and deployment guidelines".
Comparison: The cited page does not contain the content attributed to it; the content exists and is carried by the Rappler PhilDec 2.0 article (see Claim 15). Fix locations: scalar path sources[2].note and the body's inline link on "addressed AI's perils" in § Philippine Declaration on Internet Rights and Principles 2.0 — both should cite https://www.rappler.com/technology/phildec-2-experts-discuss-digital-rights-democracy-ai-use-literacy/. Attribution replacement is mechanical; trimming the note's "primary source for" wording may need Researcher prose judgment.
Decision: correction

## Claim 17: scalar:sources[1].note — the hronlineph pre-event page is a source for "the open-submission format for breakout sessions under the six named tracks"

Source: https://hronlineph.com/2024/02/29/event-digital-rights-conference-fma/
Source tier: caution
Source content: Two targeted fetches: "the page does not contain a list of breakout session tracks or themes"; "does not specify breakout tracks or detailed session formats". The page does confirm the partner roster and the target audience ("digital rights advocates, media practitioners, tech hobbyists, and rights defenders") that the note also claims.
Comparison: The note's tracks/open-submission-format component attributes content the page does not carry; the roster and audience components are accurate. Fix location: scalar path sources[1].note — remove or re-source the tracks/format component (prose-judgment trim; Researcher via Editor flag).
Decision: correction

## Claim 18: "the Philippines established its first internet connection in 1994"

Source: https://en.wikipedia.org/wiki/Internet_in_the_Philippines
Source tier: tiebreaker
Source content: "Internet in the Philippines first became available on March 29, 1994, 10:18 a.m., with the Philippine Network Foundation (PHNet) connecting the country and its people to Sprint in the United States via a 64 kbit/s link."
Comparison: Public-record definitional date; Wikipedia-alone is sufficient for this claim class per the source rule.
Decision: single-source

## Claim 19: Edge — related_events: event-engagemedia-drapac23-chiang-mai-2023-05; "DRAPAC's 35-country Asia-Pacific convening"

Source: https://engagemedia.org/projects/drapac23/ (retrieved via search extraction; direct fetch 403)
Source tier: primary
Source content: "a total of 544 participants from 35 countries converged in Chiang Mai" (May 22–26, 2023)
Comparison: Edge points to an existing corpus entity; the 35-country hard specific matches EngageMedia's own DRAPAC23 page.
Decision: primary-sourced

## Claim 20: "the same year's DRAPAC 2024 Taipei edition"

Source: https://engagemedia.org/2024/drapac24-taipei/ (retrieved via search extraction; direct fetch 403)
Source tier: primary
Source content: "Announcing DRAPAC24 in Taipei, August 2024" — EngageMedia hosted DRAPAC24 in Taipei, Taiwan, August 18–19, 2024
Comparison: A DRAPAC 2024 Taipei edition exists as the body states, confirmed on EngageMedia's own site.
Decision: primary-sourced

## Claim 21: "the EngageMedia-convened assembly FMA attended as part of its three-year DRAPAC participation"

Source: no canonical source found
Source tier: none
Source content: EngageMedia's DRAPAC24 pages (via search extraction) confirm the event but do not name FMA among attendees; no fetched source this session confirms FMA's attendance or a three-year participation span.
Comparison: The claim is attributed in-body to "the FMA entry has noted" (corpus-internal); no external canonical source was found to confirm FMA's DRAPAC24 attendance. Names the audit's limit, not an error.
Decision: uncorroborated

## Claim 22: Edge — "the mandatory SIM registration regime FMA had opposed across three legislative cycles" (body link to camp-fma-sim-card-registration-philippines)

Source: no canonical source found
Source tier: none
Source content: No single canonical source states a "three legislative cycles" count; the underlying milestones (2017–2018 position papers, the April 2022 Duterte veto, the October 2022 19th-Congress re-passage as RA 11934) are individually documented in the linked campaign entity's cited sources.
Comparison: Edge points to an existing corpus entity and the opposition itself is well-documented; the specific cycle-count is a synthesis across sources rather than a directly comparable claim — judgment-loaded, so no decision beyond uncorroborated. Not an error finding.
Decision: uncorroborated

## Claim 23: "the most populous country in Southeast Asia after Indonesia"

Source: https://en.wikipedia.org/wiki/Southeast_Asia
Source tier: tiebreaker
Source content: Population figures: Indonesia "284,438,782"; Philippines "114,123,600"; Vietnam "101,343,800"
Comparison: The Philippines is second to Indonesia in Southeast Asian population; named-entity definitional fact, Wikipedia-alone sufficient.
Decision: single-source

## Claim 24: "the issues its annual Digital Rights Report series had been tracking" / "the Philippine 'AI divide' identified in FMA's research (high individual AI adoption against low firm-level adoption concentrated in urban centres)"

Source: https://fma.ph/fma-releases-digital-rights-report-2023-looks-into-the-future-of-ai/ (retrieved via search extraction), corroborating https://fma.ph/fmas-2024-in-publications/
Source tier: primary
Source content: FMA released Digital Rights Report 2023 ("Internet Rights on the Edge") May 27, 2024; FMA's own coverage of the AI divide: "84 percent of the Filipino workforce was found to have been adopting AI tools ... the highest in the world" against a PIDS finding that "only 14.9% of firms use AI tools, with adoption concentrated in large companies in urban centers"; FMA's round-up series titles the theme "AI divide".
Comparison: The report series and the high-individual/low-firm urban-concentrated AI-divide framing are FMA's own published research, matching the body's characterization.
Decision: primary-sourced
