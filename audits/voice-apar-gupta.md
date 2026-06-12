---
entity_id: voice-apar-gupta
entity_hash: 73a2196d832ef95a6a9781e84c38304db694e65e
audit_date: 2026-06-12
pass: 2
status: supported
claims_total: 14
claims_corroborated: 3
claims_primary_sourced: 2
claims_single_source: 7
claims_uncorroborated: 2
open_corrections: 0
sources_consulted:
  - https://en.wikipedia.org/wiki/Apar_Gupta
  - https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
  - https://www.themediarumble.com/speaker/apar-gupta
  - https://www.ashoka.org/en-us/fellow/apar-gupta
  - https://internetfreedom.in/transitions-our-true-potential/
  - https://internetfreedom.in/iffs-submissions-on-the-meity-report-on-ai-governance-guidelines/
  - https://internetfreedom.in/annual-membership-drive-2024/
  - https://www.youtube.com/@apar1984
---

## Claim 1: "one of the eight 2016 co-founders" of the Internet Freedom Foundation

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source tier: tiebreaker
Source content: "Launched on 15 August 2016 — India's Independence Day"; co-founders listed as "Apar Gupta, Aravind Sulekha, Karthik Balakrishnan, Rachita Taneja, Raman Chima, Rohin Dharmakumar, Kiran Jonnalagadda, Nikhil Pahwa" (eight names).
Comparison: Body asserts Gupta is one of eight 2016 IFF co-founders; the IFF Wikipedia article confirms the 2016 launch and exactly eight named co-founders including Gupta. Named-entity definitional founding fact — Wikipedia-alone sufficient; one publication supports it. IFF's own about page (the would-be primary) returned HTTP 403 this session.
Decision: single-source

## Claim 2: "the founding Executive Director (April 2018 – November 2023)" of IFF (body, notable_for, sources[0].note)

Source: https://en.wikipedia.org/wiki/Apar_Gupta and https://en.wikipedia.org/wiki/Internet_Freedom_Foundation (conflict); https://internetfreedom.in/transitions-our-true-potential/ (primary, via search; direct fetch HTTP 403)
Source tier: tiebreaker
Source content: Apar Gupta Wikipedia: "appointed its first executive director from 2018 till November 2023". IFF Wikipedia: "IFF became a staffed organisation in April, 2018 and Apar Gupta took over as the Executive Director … Gupta served in this capacity until July 2023." IFF's own transition post (search-retrieved content): "From the start, Apar intended for a transition process after a term of six years"; transition priorities include "the search for an Executive Director by April 2024" and "having Apar continue to help out in the role of IFF's 'Founder Director'" — no end month stated.
Comparison: The April 2018 start is confirmed (IFF Wikipedia). The November 2023 end date matches Apar Gupta's Wikipedia article but is contradicted by the IFF Wikipedia article ("July 2023"); IFF's own transition announcement describes the handover without naming an end month, so the primary source does not resolve the conflict. Canonical sources disagree — no winner picked, and no single correct replacement is established, so this is not a correction. Same outcome as pass 1. Fix location if a primary source later settles it: body § Organisational vehicle, the notable_for scalar, and the sources[0].note scalar.
Decision: uncorroborated

## Claim 3: "returned as Founder Director in November 2024" (body, notable_for, sources[0].note)

Source: https://en.wikipedia.org/wiki/Apar_Gupta (cross-checked against https://en.wikipedia.org/wiki/Internet_Freedom_Foundation)
Source tier: tiebreaker
Source content: "He resumed the role of IFF's Founder Director in November, 2024"; IFF article: "Following a transition period, Gupta returned to lead the organization as Founder Director in November 2024."
Comparison: Both Wikipedia articles agree on November 2024, but they are one publication, not independent sources. Official-role date — Wikipedia-alone sufficient.
Decision: single-source

## Claim 4: Gupta authored the LexisNexis *Commentary on the Information Technology Act* (body, notable_for, sources[0].note)

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source tier: tiebreaker
Source content: "Gupta authored the Commentary on the Information Technology Act which is published by LexisNexis"
Comparison: Body and notable_for credit Gupta as author of the LexisNexis Commentary; Wikipedia confirms authorship and publisher. Named-entity definitional fact — Wikipedia-alone sufficient.
Decision: single-source

## Claim 5: "writes regularly on digital and democratic rights in leading newspapers" (multi-year columnist register; body, notable_for, sources[0].note)

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source tier: tiebreaker
Source content: "He writes regularly on digital and democratic rights in leading newspapers"
Comparison: The body explicitly attributes this framing to the Wikipedia biographical article and quotes it verbatim; the quotation is accurate against the attributed source. No second canonical source for the columnist register was fetched this session.
Decision: single-source

## Claim 6: Peer-reviewed publications in Indian Journal of Law and Technology, *Seminar*, and the IIC Quarterly

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source tier: tiebreaker
Source content: "Gupta is published in reviewed journals like the Indian Journal of Law and Technology, Seminar and the India International Center Quarterly"
Comparison: Three named publication venues match the source list exactly (allowing "Center"/"Centre" spelling). Public-record publication fact resting on Wikipedia alone.
Decision: single-source

## Claim 7: Started the *1984* YouTube channel "to take forward the discourse on digital policy" (body, notable_for, sources[5].note)

Source: https://en.wikipedia.org/wiki/Apar_Gupta; https://www.youtube.com/@apar1984 (fetched; page content not retrievable beyond YouTube boilerplate)
Source tier: tiebreaker
Source content: "also started a YouTube channel, 1984 to take forward the discourse on digital policy"
Comparison: The body quotes the purpose framing verbatim and attributes it to Wikipedia; the quotation is accurate. The channel URL fetch returned only YouTube footer boilerplate, so channel existence and naming could not be independently confirmed this session; the purpose quote rests on Wikipedia alone.
Decision: single-source

## Claim 8: Delivered the Krishna Raj Memorial Lecture (body, notable_for)

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source tier: tiebreaker
Source content: "He has delivered the 11th Krishna Raj Memorial Lecture at the 37th Annual Dr. Ramanatham Memorial Meeting"
Comparison: Body and notable_for assert delivery of the Krishna Raj Memorial Lecture; Wikipedia confirms (the 11th instance). Public-event occurrence — Wikipedia-alone sufficient.
Decision: single-source

## Claim 9: Awarded the Ashoka Fellowship in 2019 (body, notable_for, sources[1].note)

Source: https://www.ashoka.org/en-us/fellow/apar-gupta (entity-cited; content retrieved via search — direct fetch HTTP 403) and https://en.wikipedia.org/wiki/Apar_Gupta
Source tier: primary
Source content: Ashoka fellow page (search-retrieved): "In 2019, Apar Gupta was elected as an Ashoka Fellow". Wikipedia: "awarded the Ashoka Fellowship in 2019".
Comparison: The 2019 election year is confirmed by Ashoka's own fellow page (primary) and by Wikipedia. Two sources, one primary.
Decision: corroborated

## Claim 10: scalar:notable_for + body — Ashoka framing "creating a model for digital rights advocacy in the country that is driven by the public, for the public" (also sources[1].note)

Source: https://www.ashoka.org/en-us/fellow/apar-gupta (entity-cited; content retrieved via search — direct fetch HTTP 403) and https://en.wikipedia.org/wiki/Apar_Gupta
Source tier: primary
Source content: Ashoka fellow page (search-retrieved): elected "for 'creating a model for digital rights advocacy in the country that is driven by the public, for the public'". Wikipedia (fetched directly) now carries the same formulation verbatim: "creating a model for digital rights advocacy in the country that is driven by the public, for the public".
Comparison: Pass 1 found the Ashoka URL unreachable and the phrase absent from Wikipedia; this pass retrieves the phrase verbatim from Ashoka's own page via search and finds Wikipedia now carries it too. Quoted framing of a living person needs a non-Wikipedia source — Ashoka's own page is that source, with Wikipedia as tiebreaker support. Pass-1 uncorroborated resolved.
Decision: corroborated

## Claim 11: Media Rumble bio frames his post-2015 work as "public interest issues which include strategic litigation and organisation of campaigns and collectives" (body x2, sources[3].note)

Source: https://www.themediarumble.com/speaker/apar-gupta
Source tier: primary
Source content: "From 2015, I have been working extensively on public interest issues which include strategic litigation and organisation of campaigns and collectives."
Comparison: Pass 1 recorded a correction — the entity then misquoted this as "digital rights issues through strategic litigation…". All three occurrences (two body paragraphs and the sources[3].note scalar) now quote the page accurately. The speaker page is the primary document for its own bio text. Pass-1 correction RESOLVED.
Decision: primary-sourced

## Claim 12: September 2025 Media Rumble session "IT Rules — Learnings from the laws for broadcast and print media" (body, sources[3].note)

Source: https://www.themediarumble.com/speaker/apar-gupta
Source tier: primary
Source content: Scheduled for "IT Rules: Learnings from the laws for broadcast and print media" on September 22, from 3:00 pm to 3:50 pm.
Comparison: Session title matches; the page lists a September 22 session consistent with the September 2025 framing in the body (the page itself shows no year in the retrievable content — same reading as pass 1). The festival's own speaker page is the primary document for its programme.
Decision: primary-sourced

## Claim 13: scalar:sources[2].note — IFF author archive carries "his named-byline IFF submissions on the NITI Aayog National Strategy for Artificial Intelligence ('#AIforAll') and the 2025 Ministry of Electronics and Information Technology AI Governance Guidelines under the IndiaAI Mission"

Source: https://internetfreedom.in/author/apar/ (entity-cited; HTTP 403 this session); https://internetfreedom.in/iffs-submissions-on-the-meity-report-on-ai-governance-guidelines/ (via search)
Source tier: primary
Source content: Search-retrieved: IFF's post "IFF's Submissions on the MeitY Report on AI Governance Guidelines" exists, with the submission described as made "on behalf of Apar Gupta, Gayatri Malhotra & Naman Kumar … on January 15, 2025". No named-byline Apar Gupta post on the NITI Aayog National Strategy / #AIforAll was found in canonical search results, and the cited author archive is unreachable (403).
Comparison: The MeitY half of the composite claim is confirmed with Gupta's named byline on IFF's own post; the NITI Aayog #AIforAll half could not be confirmed because the cited archive is inaccessible and search surfaced no named-byline submission. Partial confirmation of a composite claim — not an error finding. Fix location if it persists: the sources[2].note scalar.
Decision: uncorroborated

## Claim 14: IFF's "community-funded, membership-organisation posture" (body §§ Signature framings, Organisational vehicle)

Source: https://internetfreedom.in/annual-membership-drive-2024/ and https://internetfreedom.in/become-an-iff-member-today/ (via search) and https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source tier: primary
Source content: IFF's own pages (search-retrieved): "Fight for your civil liberties in a digital society. Become an IFF member today!" — membership from Rs. 100/month, members-only forum channel. IFF Wikipedia: "IFF runs on a small budget primarily through a domestic, community-funded model. Nearly all income comes from small, repeat donations by Indian citizens."
Comparison: The community-funded model is confirmed by Wikipedia and IFF's own membership-drive pages confirm the membership-organisation posture. Two sources, one primary.
Decision: corroborated
