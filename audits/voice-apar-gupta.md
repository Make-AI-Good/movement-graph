---
entity_id: voice-apar-gupta
entity_hash: 63073464b7b6cc64d31cb8f2114aded1640f9e9d
audit_date: 2026-06-03
pass: 1
status: corrections-pending
claims_total: 12
claims_corroborated: 9
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 2
sources_consulted:
  - https://en.wikipedia.org/wiki/Apar_Gupta
  - https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
  - https://www.themediarumble.com/speaker/apar-gupta
---

## Claim 1: "one of the eight 2016 co-founders" of the Internet Freedom Foundation

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "The organization was established on August 15, 2016, with eight co-founders." — naming "Founder Apar Gupta, Aravind Sulekha, Karthik Balakrishnan, Rachita Taneja, Raman Chima, Rohin Dharmakumar, Kiran Jonnalagadda, Nikhil Pahwa."
Comparison: Body asserts Gupta is one of eight 2016 IFF co-founders. The IFF Wikipedia article confirms August 15, 2016 founding with exactly eight named co-founders including Apar Gupta. Wikipedia-alone is sufficient for named-entity definitional founding facts.
Decision: corroborated

## Claim 2: "the founding Executive Director (April 2018 – November 2023)" of IFF

Source: https://en.wikipedia.org/wiki/Apar_Gupta (entity-cited) and https://en.wikipedia.org/wiki/Internet_Freedom_Foundation (cross-check)
Source content: Apar Gupta Wikipedia: "co-founder of the Internet Freedom Foundation (IFF) and was appointed its first executive director from 2018 till November 2023". IFF Wikipedia: "IFF became a staffed organisation in April, 2018 and Apar Gupta took over as the Executive Director … Gupta served in this capacity until July 2023."
Comparison: The April 2018 start date is corroborated by the IFF Wikipedia article ("April, 2018"). The November 2023 end date in the entity matches Apar Gupta's Wikipedia article but is directly contradicted by IFF's Wikipedia article, which states "July 2023". Two canonical sources disagree on the end date and Wikipedia cannot tiebreak itself; no other canonical source resolves the contradiction. Per the source rule, the outcome is unverifiable.
Decision: uncorroborated

## Claim 3: "returned as Founder Director in November 2024"

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source content: "He resumed the role of IFF's Founder Director in November, 2024"
Comparison: Body and notable_for assert Gupta returned as Founder Director from November 2024. Wikipedia confirms verbatim. Named-entity definitional fact — Wikipedia-alone sufficient.
Decision: corroborated

## Claim 4: Gupta authored the LexisNexis *Commentary on the Information Technology Act*

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source content: "Gupta authored the Commentary on the Information Technology Act which is published by LexisNexis"
Comparison: Body and notable_for credit Gupta as author of the LexisNexis Commentary. Source confirms authorship and LexisNexis publication. Named-entity / public-record definitional fact.
Decision: corroborated

## Claim 5: "writes regularly on digital and democratic rights in leading newspapers" (multi-year columnist register)

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source content: "He writes regularly on digital and democratic rights in leading newspapers and is quoted as an expert in India"
Comparison: Body quotes this framing directly from Wikipedia; the multi-year columnist register in notable_for matches the same source. Paraphrase tolerance not stretched — entity quotes the source verbatim.
Decision: corroborated

## Claim 6: Peer-reviewed publications in Indian Journal of Law and Technology, *Seminar*, and the IIC Quarterly

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source content: "Gupta is published in reviewed journals like the Indian Journal of Law and Technology, Seminar and the India International Center Quarterly"
Comparison: Three named publication venues match the source list exactly (allowing for "Center"/"Centre" spelling).
Decision: corroborated

## Claim 7: Started the *1984* YouTube channel "to take forward the discourse on digital policy"

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source content: "also started a YouTube channel, 1984 to take forward the discourse on digital policy"
Comparison: Entity's quoted phrasing matches Wikipedia verbatim. The 1984 channel naming and stated purpose are confirmed.
Decision: corroborated

## Claim 8: Delivered the Krishna Raj Memorial Lecture

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source content: "He has delivered the 11th Krishna Raj Memorial Lecture at the 37th Annual Dr. Ramanatham Memorial Meeting (with Jinee Lokaneeta)"
Comparison: Body and notable_for assert Gupta delivered the Krishna Raj Memorial Lecture. Wikipedia confirms (specifically the 11th instance). Public-record / definitional fact about a named lecture.
Decision: corroborated

## Claim 9: Awarded the Ashoka Fellowship in 2019

Source: https://en.wikipedia.org/wiki/Apar_Gupta
Source content: "For his work at IFF he was awarded the Ashoka Fellowship in 2019"
Comparison: Body and notable_for assert "2019 Ashoka Fellowship". Wikipedia confirms the year and the award. Public role/recognition definitional fact — Wikipedia-alone sufficient.
Decision: corroborated

## Claim 10: scalar:notable_for + body — Ashoka Fellowship framing "creating a model for digital rights advocacy in the country that is driven by the public, for the public"

Source: https://www.ashoka.org/en-us/fellow/apar-gupta (entity-cited; fetched, returned HTTP 403); cross-check https://en.wikipedia.org/wiki/Apar_Gupta
Source content: Ashoka URL fetch returned "HTTP 403 Forbidden" — no source content retrievable in this session. The Wikipedia article on Apar Gupta does not contain the phrase "driven by the public, for the public" or any equivalent quoted Ashoka framing.
Comparison: The body asserts the Ashoka Fellowship "recognised Gupta for 'creating a model for digital rights advocacy in the country that is driven by the public, for the public'", and notable_for repeats the quoted fragment. The cited Ashoka URL is unreachable (403); the cross-check Wikipedia source does not carry the formulation. The quoted phrase is a contested, judgment-loaded characterization (load-bearing significance claim) that needs a non-Wikipedia canonical source per the source rule, and that source is currently inaccessible. Editor fix location if confirmed elsewhere: body para "Signature framings → 'Driven by the public, for the public'" and the `notable_for` scalar.
Decision: uncorroborated

## Claim 11: Media Rumble bio frames his post-2015 work as "digital rights issues through strategic litigation and organisation of campaigns and collectives" (appears in body and in sources[4].note)

Source: https://www.themediarumble.com/speaker/apar-gupta
Source content: "From 2015, I have been working extensively on public interest issues which include strategic litigation and organisation of campaigns and collectives."
Comparison: The body and the `sources[4].note` scalar quote the Media Rumble bio with the phrase "digital rights issues through strategic litigation and organisation of campaigns and collectives". The actual page text reads "public interest issues which include strategic litigation and organisation of campaigns and collectives" — the subject is "public interest issues", not "digital rights issues", and the connector is "which include", not "through". The misquoted phrase appears (a) in the body paragraph under "Public output and venues → Festival, lecture, and forum speaker register" and again in (b) the "Signature framings → The lawyer-founder-and-columnist proposition" paragraph, and (c) in the `sources[4].note` frontmatter scalar (the Media Rumble entry). Editor fix locations: all three occurrences.
Decision: correction

## Claim 12: September 2025 Media Rumble session "IT Rules — Learnings from the laws for broadcast and print media"

Source: https://www.themediarumble.com/speaker/apar-gupta
Source content: "Gupta is scheduled to speak on 'IT Rules — Learnings from the laws for broadcast and print media' from 3:00 pm to 3:50 pm on September 22."
Comparison: Session title quoted verbatim matches the Media Rumble page; September 2025 date corroborated (the page lists a September 22 session, consistent with the September 2025 framing in the body).
Decision: corroborated
