---
entity_id: event-share-foundation-safe-city-belgrade-protest-2019
entity_hash: 35de7e7427d2aae65f9cf0d23552c98519e1ba3d
audit_date: 2026-08-31
pass: 1
status: corrections-pending
claims_total: 23
claims_corroborated: 5
claims_primary_sourced: 8
claims_single_source: 4
claims_uncorroborated: 4
open_corrections: 2
sources_consulted:
  - https://edri.org/our-work/serbia-unlawful-facial-recognition-video-surveillance-in-belgrade/
  - https://sharefoundation.info/en/huawei-knows-everything-about-cameras-in-belgrade-and-they-are-glad-to-share/
  - https://privacyinternational.org/case-study/3967/thousands-cameras-citizen-response-mass-biometric-surveillance
  - https://www.cbsnews.com/news/china-huawei-face-recognition-cameras-serbia-other-countries-questionable-human-rights-2019-10-16/
  - https://giswatch.org/node/6188
  - https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
  - https://hiljade.kamera.rs/en/timeline/
  - https://en.wikipedia.org/wiki/2018%E2%80%932020_Serbian_protests
  - https://www.statewatch.org/news/2019/december/serbia-unlawful-video-surveillance-with-face-recognition-in-belgrade/
  - https://www.sharefoundation.info/en/thousands-of-cameras/
---

Entity type Event is connective (`mission/MISSION.md § Auditor § Type-shape awareness`): claims audited are edges (cross-references) and hard specifics. Significance-section prose about corpus-firsts, movement arc, and the EU AI Act drafting moment is interpretation over facts and receives no decision.

## Claim 1: edge `campaign:` → camp-share-foundation-safe-city-surveillance-serbia-2019-ongoing

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: "cooperation with the Chinese company Huawei on improving the information and telecommunication system through the 'Safe City' project"
Comparison: Campaign entity exists in corpus; the brief is the Safe City campaign's formal DPIA challenge — edge points to the correct entity.
Decision: primary-sourced

## Claim 2: edge `participating_orgs:` → org-share-foundation

Source: https://edri.org/our-work/serbia-unlawful-facial-recognition-video-surveillance-in-belgrade/
Source tier: primary
Source content: "On 3 December 2019, EDRi member SHARE Foundation, together with two other organisations, published a policy brief"; Statewatch (9 Dec 2019) independently names "SHARE Foundation, Partners for Democratic Change Serbia, and Belgrade Center for Security Policy (BCSP)"
Comparison: Org entity exists in corpus; SHARE is a brief co-publisher per the brief itself, EDRi, and Statewatch.
Decision: corroborated

## Claim 3: `date: 2019-12-03` — "published a joint policy brief" / "published 3 December 2019"

Source: https://edri.org/our-work/serbia-unlawful-facial-recognition-video-surveillance-in-belgrade/
Source tier: mainstream
Source content: "On 3 December 2019, EDRi member SHARE Foundation, together with two other organisations, published a policy brief" (EDRi article dated 4 December 2019)
Comparison: Exact date confirmed only by EDRi; Statewatch (9 Dec 2019) confirms the brief's existence that week but not the day; the brief PDF is undated in body.
Decision: single-source

## Claim 4: `location: Belgrade, Serbia`

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: "The installation of smart video surveillance in Belgrade, with thousands of cameras and face recognition software"; CBS (16 Oct 2019) independently places the deployment and protests in Belgrade
Comparison: Deployment challenged, publishing organisations, and protest context are all Belgrade — location scalar matches.
Decision: corroborated

## Claim 5: three-organisation coalition — SHARE Foundation, Partners for Democratic Change Serbia, Belgrade Centre for Security Policy

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: "Three civil society organisations (CSOs) – SHARE Foundation, Partners for Democratic Change Serbia (Partners Serbia) and Belgrade Centre for Security Policy (BCSP) – published a detailed analysis of the MoI's Data Protection Impact Assessment (DPIA)"
Comparison: Brief PDF, EDRi, and Statewatch all name the same three organisations — matches body and `sources[0].note`.
Decision: corroborated

## Claim 6: "failed to meet four requirements" / "identified four structural deficiencies" (body; also scalar:sources[0].note "the four DPIA deficiencies identified")

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: The brief enumerates FIVE bullets: "There is no comprehensive description of the intended actions on processing personal data…; There is no risk assessment regarding the rights and freedoms of the data subjects; The measures that are to be taken in relation to the existence of risk are not described; The technical, organizational and personnel measures for data protection are only partially described; The legal basis for the mass use of smart video surveillance systems is disputable." EDRi reproduces the same five.
Comparison: Body says four and enumerates four, silently merging/omitting the third bullet (measures to address identified risks). Count token "four" → "five"; the four-item enumeration in body and in scalar:sources[0].note needs the omitted bullet restored — prose judgment beyond a single replacement, Editor should flag to Researcher.
Decision: correction

## Claim 7: brief "called for the immediate suspension of further camera installation" and "a public debate"

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: "the process should be suspended immediately and the authorities should engage in an inclusive public debate"; conclusion: "The MoI should suspend further introduction of smart video surveillance systems."
Comparison: Suspension demand, immediacy, and public-debate call all present verbatim in the primary document.
Decision: primary-sourced

## Claim 8: Commissioner for Personal Data Protection independently confirmed — DPIA "was not conducted in line with the requirements of the Personal Data Protection Law" and lacked the "risk assessment regarding the rights and freedoms of data subjects"

Source: https://www.statewatch.org/news/2019/december/serbia-unlawful-video-surveillance-with-face-recognition-in-belgrade/
Source tier: primary
Source content: Brief PDF: "The Commissioner on Personal Data Protection in Serbia published his opinion on the DPIA, confirming the findings… the DPIA was not conducted in line with the requirements of the Personal Data Protection Law; … it does not include a risk assessment regarding the rights and freedoms of data subjects". Statewatch independently: "Serbia's Commissioner on Personal Data Protection independently confirmed these concerns".
Comparison: Both quoted fragments in body match the Commissioner's opinion as reported by the primary brief and independently by Statewatch.
Decision: corroborated

## Claim 9: DPIA "delivered to the Commissioner in September 2019"

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: "in September the MoI drafted and delivered the DPIA to the Commissioner for an opinion… the DPIA was completed in September 2019"
Comparison: Matches; EDRi states the same.
Decision: primary-sourced

## Claim 10: DPIA delivered "two months after Serbia's GDPR-based Personal Data Protection Law entered into force in August 2019"

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: "the new Personal Data Protection Law entered into force at the end of August and the DPIA was completed in September 2019"; giswatch: "The application of the law starts on 21 August 2019"
Comparison: End of August 2019 → September 2019 is one month, not two. The interval token "two months" contradicts both cited sources; correct replacement is "the month after" / "one month".
Decision: correction

## Claim 11: Personal Data Protection Law "entered into force in August 2019"

Source: https://giswatch.org/node/6188
Source tier: primary
Source content: giswatch: "The application of the law starts on 21 August 2019, after a nine-month adaptation period"; brief PDF: "the new Personal Data Protection Law entered into force at the end of August"
Comparison: August 2019 entry into force confirmed by two publications.
Decision: corroborated

## Claim 12: SHARE Foundation investigation published March 29, 2019 (body; also scalar:sources[1].note "published March 29, 2019")

Source: https://sharefoundation.info/en/huawei-knows-everything-about-cameras-in-belgrade-and-they-are-glad-to-share/
Source tier: primary
Source content: Article publication date March 29, 2019, on SHARE Foundation's own site
Comparison: Date matches the article's own publication stamp.
Decision: primary-sourced

## Claim 13: Phase 1 specifications — 100 cameras, 60+ locations, facial recognition, behaviour analysis, licence plate recognition, 4K video, one-year retention (body; also scalar:sources[1].note)

Source: https://sharefoundation.info/en/huawei-knows-everything-about-cameras-in-belgrade-and-they-are-glad-to-share/
Source tier: primary
Source content: "100 high-definition video cameras were installed in more than 60 key locations"; "video retrieval, video compression, automatic license plate recognition, behavior analysis, facial recognition, and video quality diagnosis"; "4k video solutions, H.265 HD encoding"; "retention period of received data is limited to one year"
Comparison: Every listed specification present in the cited investigation, including 4K and one-year retention.
Decision: primary-sourced

## Claim 14: Huawei removed the case study from its website after SHARE's publication

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: Brief: "Huawei removed the content on cooperation with the MoI from the official website shortly after the SHARE Foundation released a report"; SHARE article editor's note: "case study about cameras for video surveillance in Belgrade was removed from the official website of Huawei"
Comparison: Removal confirmed in the primary document and the investigation's editor's note (same organisational family — counted as one source family).
Decision: primary-sourced

## Claim 15: FOI "requests to the Ministry for camera location data were refused as confidential, the Ministry claiming to hold no location analysis" (body; cf. scalar:sources[1].note "classifying procurement documents as confidential")

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: "The MoI answered that all documents for the public procurement of video equipment are confidential, while the information on locations and crime rate analysis is not contained in any document that the Ministry possesses"
Comparison: Source: PROCUREMENT documents were confidential; location/crime-analysis data was claimed nonexistent (not "refused as confidential"). Body attaches "confidential" to the location-data request — a conflation. scalar:sources[1].note states it correctly. Fix requires re-drafting the clause, not a single token — judgment-loaded, so no correction asserted; flagged here for Researcher review via the Editor pipe if picked up.
Decision: uncorroborated

## Claim 16: Minister of Interior and Police Director "publicly announced in early 2019" installation of 1,000 cameras at 800 locations

Source: https://www.sharefoundation.info/wp-content/uploads/Serbia-Video-Surveillance-Policy-brief-final.pdf
Source tier: primary
Source content: "At the beginning of 2019, the Minister of Interior and the Director of Police announced the placement of 1,000 cameras on 800 locations in Belgrade"; campaign timeline (hiljade.kamera.rs) has the same beginning-of-2019 entry
Comparison: Officials, counts, and "early 2019" timing all match the primary document verbatim.
Decision: primary-sourced

## Claim 17: protesters "covered surveillance camera lenses with duct tape marked 'censored'" at anti-government rallies, October 2019 (body; also scalar:sources[3].note)

Source: https://www.cbsnews.com/news/china-huawei-face-recognition-cameras-serbia-other-countries-questionable-human-rights-2019-10-16/
Source tier: mainstream
Source content: "During a recent anti-government rally in Belgrade, protesters climbed a pole and covered a camera lens with duct tape that had the word 'censored' written on it" (article dated October 16, 2019)
Comparison: Incident, wording on tape, protest context, and October 2019 timing match; body pluralises ("lenses… at rallies") where CBS documents one incident at one rally — a mild amplification, not a token error.
Decision: single-source

## Claim 18: former Commissioner quote — system "could be used to trail political opponents, 'monitor regime critics at any moment, which is completely against the law'" (body; also scalar:sources[3].note)

Source: https://www.cbsnews.com/news/china-huawei-face-recognition-cameras-serbia-other-countries-questionable-human-rights-2019-10-16/
Source tier: mainstream
Source content: "Rodoljub Sabic, Serbia's former commissioner for personal data protection, stated: 'The system can be used to trail political opponents, monitor regime critics at any moment, which is completely against the law.'"
Comparison: Quote matches verbatim and is correctly attributed to the former commissioner. Living-person quoted statement — mainstream news source satisfies the stricter Person-claim bar; one source only.
Decision: single-source

## Claim 19: "One in 5 Million" anti-government protests "filling Belgrade's streets since late 2018"

Source: https://en.wikipedia.org/wiki/2018%E2%80%932020_Serbian_protests
Source tier: tiebreaker
Source content: "In late 2018, a series of largely peaceful protests…began to take place in the Serbian capital of Belgrade, soon spreading to cities across the country" (began 30 November 2018; ongoing through October 2019)
Comparison: Date-of-public-event claim — Wikipedia-alone-sufficient class; name, late-2018 start, and continuity into October 2019 all match.
Decision: single-source

## Claim 20: "In November 2019, SHARE Foundation launched the #hiljadekamera ('Thousands of Cameras') civic initiative" (body; also scalar:sources[2].note "the November 2019 launch")

Source: no canonical source found
Source tier: none
Source content: Cited source (Privacy International) gives no launch date and attributes the platform to "a community of individuals and organisations", not SHARE alone: "Serbian citizens have launched the website hiljade.kamera.rs". The campaign's own timeline (hiljade.kamera.rs) has no initiative-launch entry; its November 2019 entry reads "DPIA became publicly available; civil society called for installation halt". Unfetched web-search results (BIRD project page) indicate the crowdmapping site launched mid-May 2020.
Comparison: Neither the November 2019 date nor sole-SHARE attribution is supported by the cited source or the campaign's own site; available signals point to a later site launch. No single correct replacement determinable from canonical sources — not asserted as error, but the claim and scalar:sources[2].note need Researcher review.
Decision: uncorroborated

## Claim 21: scalar:sources[2].note — Privacy International case study as "primary source for… the campaign's framing of the December 2019 policy brief as the first formal legal challenge"

Source: https://privacyinternational.org/case-study/3967/thousands-cameras-citizen-response-mass-biometric-surveillance
Source tier: none
Source content: "The case study contains no mention of a December 2019 policy brief or any specific legal challenge to the Safe City deployment's compliance with Serbia's Personal Data Protection Law." (Its June 2020 publication date in the note is accurate: "25th June 2020".)
Comparison: scalar:sources[2].note attributes brief-framing content to a source that does not contain it — a sourcing-attribution error in frontmatter prose; fix requires prose judgment (outside the Editor's single-replacement backfill).
Decision: uncorroborated

## Claim 22: scalar:sources[4].note — giswatch report as "secondary source corroborating the December 3, 2019 policy brief timeline, the three-organisation coalition, the DPIA deficiency findings"

Source: https://giswatch.org/node/6188
Source tier: none
Source content: Fetched twice with targeted prompts; the report "does not mention: a joint policy brief…; Partners for Democratic Change Serbia; the Commissioner['s]… assessment of the Ministry's DPIA; or events from December 2019". It does confirm the August 2019 law date and quotes a BCSP researcher.
Comparison: scalar:sources[4].note over-claims what the source corroborates — only the Personal Data Protection Law timing (claim 11) is actually supported. Sourcing-attribution error in frontmatter prose; fix requires prose judgment.
Decision: uncorroborated

## Claim 23: body edge → org-edri — "SHARE Foundation's membership in EDRi"

Source: https://edri.org/our-work/serbia-unlawful-facial-recognition-video-surveillance-in-belgrade/
Source tier: primary
Source content: "On 3 December 2019, EDRi member SHARE Foundation, together with two other organisations, published a policy brief" (EDRi's own site naming its member)
Comparison: org-edri entity exists in corpus; membership stated by EDRi itself. The surrounding amplifier/AI-Act-timing prose is interpretation, not claim.
Decision: primary-sourced
