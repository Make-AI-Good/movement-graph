---
entity_id: lg-oakland-privacy
entity_hash: ec40c870f912cbf4f18621441c0897c4ad82e8d4
audit_date: 2026-06-10
pass: 2
status: supported
claims_total: 24
claims_corroborated: 4
claims_primary_sourced: 6
claims_single_source: 8
claims_uncorroborated: 6
open_corrections: 0
sources_consulted:
  - https://oaklandprivacy.org/timeline/
  - https://oaklandprivacy.org/oaklands-domain-awareness-center-2013-2014/
  - https://www.eff.org/deeplinks/2017/10/oakland-privacy-and-fight-community-control
  - https://www.eff.org/deeplinks/2019/07/victory-oakland-city-council-votes-ban-government-use-face-surveillance
  - https://www.eff.org/deeplinks/2021/01/oaklands-progressive-fight-protect-residents-government-surveillance
  - https://secure-justice.org/blog/first-in-the-nation-bans-predictive-analytics-biometric-surveillance-technologies
  - https://statescoop.com/oakland-calif-set-to-ban-predictive-policing-biometric-surveillance-tools/
  - https://www.governing.com/next/What-Cities-Can-Learn-from-the-Nations-Only-Privacy-Commission.html
  - https://en.wikipedia.org/wiki/Domain_Awareness_Center
  - https://www.cbsnews.com/sanfrancisco/news/oaklands-facial-recognition-ban-passes-first-administrative-hurdle/
  - https://www.aclu.org/community-control-over-police-surveillance
  - https://www.aclunorcal.org/news/hofer/
  - https://oaklandside.org/2025/11/12/oakland-privacy-advisory-commission-resignation-brian-hofer-sean-everhart/
---

Pass-2 note: the entity changed since pass 1 (hash 126ffc21 → ec40c870): the pass-1 `correction` on Claim 21 (a "feedback loop" quote misattributed to StateScoop) was repaired by re-sourcing the rationale to Secure Justice, and `key_people` gained `person-brian-hofer` (an ID reference, not a prose claim). The correction is CLEARED this pass — see Claim 21. Three pass-1 `uncorroborated` claims also resolve this pass on newly reachable or newly located sources (Claims 13, 14, 17, 22). This audit predates none of the decision-taxonomy update: pass-state labels follow the current five-decision taxonomy (`primary-sourced` / `single-source` did not exist at pass 1), so some claims relabel from pass 1's `corroborated` without any change in underlying evidence.

## Claim 1: "emerged in July 2013 as the Occupy Oakland Privacy Working Group"

Source: https://oaklandprivacy.org/timeline/ (entity-cited); https://www.eff.org/deeplinks/2017/10/oakland-privacy-and-fight-community-control (entity-cited)
Source tier: primary
Source content: Timeline: "July. Current and former Occupy Oakland members become aware of the DAC." and "August 29th. Third meeting. The group is now called the 'Occupy Oakland Privacy Working Group.'" EFF 2017: Oakland Privacy "began as 'the Occupy Oakland Privacy Working Group' in July 2013."
Comparison: The group's own timeline (primary) and EFF (mainstream) both anchor the July 2013 emergence under the OOPWG name.
Decision: corroborated

## Claim 2: DAC "the city had begun building quietly under a Department of Homeland Security port-security grant"

Source: https://oaklandprivacy.org/oaklands-domain-awareness-center-2013-2014/ (entity-cited); https://en.wikipedia.org/wiki/Domain_Awareness_Center
Source tier: none
Source content: The cited DAC page: DHS or port-security grant funding "Not mentioned on this page." Wikipedia DAC article: "Department of Homeland Security funding or port security grants: Not mentioned in the article."
Comparison: The specific DHS-port-security-grant attribution is still not present in the cited source or any consulted canonical source. Unchanged from pass 1.
Decision: uncorroborated

## Claim 3: DAC proposed Phase II would integrate "more than 700 cameras across schools and public housing"

Source: https://oaklandprivacy.org/oaklands-domain-awareness-center-2013-2014/ (entity-cited)
Source tier: none
Source content: The cited page: camera count, schools, or public housing "Not mentioned on this page." Wikipedia describes only the actual integration: "the Oakland DAC integrated 130 cameras from the Port of Oakland and four city cameras."
Comparison: The 700+ / schools / public-housing scope details remain absent from the cited source and from Wikipedia. The frontmatter source-note (sources[1].note) attributes these details to the cited page, which does not carry them in its body text. Unchanged from pass 1.
Decision: uncorroborated

## Claim 4: DAC proposed Phase II would include "facial recognition software"

Source: https://oaklandprivacy.org/oaklands-domain-awareness-center-2013-2014/ (entity-cited); https://en.wikipedia.org/wiki/Domain_Awareness_Center
Source tier: none
Source content: Cited DAC page: facial recognition "Not mentioned on this page." Wikipedia: "Facial recognition: Not mentioned in the article."
Comparison: No fetched canonical source confirms a facial-recognition component in the DAC's proposed Phase II. Unchanged from pass 1.
Decision: uncorroborated

## Claim 5: DAC proposed Phase II would include "automated licence plate readers"

Source: https://en.wikipedia.org/wiki/Domain_Awareness_Center
Source tier: tiebreaker
Source content: "By including gunshot detection and license plate readers the DAC would allow police to faster investigate suspects."
Comparison: Wikipedia confirms license plate readers as a DAC component — a public-record fact about a named program, where Wikipedia-alone is sufficient per the source rule. Nuance: Wikipedia describes the DAC plan generally, not the Phase II expansion specifically. One non-primary canonical source.
Decision: single-source

## Claim 6: DAC proposed Phase II would include "roughly 300 terabytes of storage for the resulting data"

Source: https://oaklandprivacy.org/oaklands-domain-awareness-center-2013-2014/ (entity-cited)
Source tier: none
Source content: Cited page: data storage capacity "Not mentioned on this page." Wikipedia: "Data storage capacity (terabytes): Not mentioned in the article."
Comparison: The 300 TB figure remains absent from the cited source and all consulted canonical sources. Unchanged from pass 1.
Decision: uncorroborated

## Claim 7: "Working in coalition with Lighthouse Mosque, ONYX Organizing Committee / Anti-Police Terror Project, and Justice for Alan Blueford"

Source: https://www.eff.org/deeplinks/2017/10/oakland-privacy-and-fight-community-control (entity-cited)
Source tier: mainstream
Source content: "The organization worked with Lighthouse Mosque, ONYX/Anti-Police Terror Project, Justice for Alan Blueford, and the Dan Siegel for Mayor Campaign to halt the DAC's expansion beyond the Port of Oakland."
Comparison: The three coalition partners named in the body match the source; the body's omission of the Dan Siegel campaign is partial enumeration, not error. Rests on EFF alone.
Decision: single-source

## Claim 8: "the 4 March 2014 city council vote restricting the DAC to the Port of Oakland only"

Source: https://oaklandprivacy.org/timeline/ (entity-cited)
Source tier: primary
Source content: "March 4th. After unanimous public opposition, the Council voted 5-4, Mayor Quan breaking the tie, in favor of a Port-restricted DAC."
Comparison: Date and outcome match the group's own timeline — a primary document by the entity.
Decision: primary-sourced

## Claim 9: "The group renamed itself Oakland Privacy in 2016"

Source: https://oaklandprivacy.org/timeline/ (entity-cited)
Source tier: primary
Source content: "July. Members vote to change the name of OPWG to simply 'Oakland Privacy' and to adopt a somewhat revised logo." (Under 2016.)
Comparison: 2016 rename matches (specifically July 2016), per the entity's own timeline.
Decision: primary-sourced

## Claim 10: "Surveillance Equipment Ordinance (later renamed the Surveillance and Community Safety Ordinance), passed by Oakland City Council in 2018"

Source: https://oaklandprivacy.org/timeline/ (entity-cited); https://www.eff.org/deeplinks/2021/01/oaklands-progressive-fight-protect-residents-government-surveillance (entity-cited)
Source tier: primary
Source content: Timeline: "May 15 – City of Oakland unanimously adopts surveillance transparency ordinance. It becomes law upon the 2nd reading." (Under 2018.) EFF 2021 refers to "the city's already groundbreaking Surveillance and Community Safety Ordinance."
Comparison: 2018 council passage matches the timeline; the later "Surveillance and Community Safety Ordinance" name is confirmed by EFF's 2021 usage. Two independent sources.
Decision: corroborated

## Claim 11: ACLU of Northern California "frames this as the structural inversion that the DAC fight made possible: 'having the public conversation at the beginning, about whether this is appropriate or not for the community'"

Source: https://www.aclunorcal.org/blog/how-fight-stop-oaklands-domain-awareness-center-laid-groundwork-oakland-privacy-commission (entity-cited, HTTP 404); https://www.aclunorcal.org/news/hofer/ (successor); https://www.eff.org/deeplinks/2017/10/oakland-privacy-and-fight-community-control
Source tier: mainstream
Source content: The entity-cited ACLU URL still returns HTTP 404 (aclunc.org redirects back to the same dead path). The successor ACLU page (a Brian Hofer guest post) carries the inversion framing — "meaningful informed discussion at the beginning of the process, not after the fact like with the DAC" — but the exact quoted phrase "does not appear in the article." The exact quote DOES appear in EFF 2017, spoken by Brian Hofer: "We're now flipping that on its head. We're having the public conversation at the beginning, about whether this is appropriate or not for the community, and if so how should it be regulated?"
Comparison: The quote is real and the framing is real, but the body attributes the quote to the ACLU account, and the verifiable carrier of the exact quote is EFF (speaker: Hofer). The original cited ACLU page is dead, so it cannot be confirmed to lack (or carry) the quote — the attribution cannot be settled either way. Not a correction: no single token is demonstrably wrong against an accessible best source.
Decision: uncorroborated

## Claim 12: "The Privacy Advisory Commission itself, created by city ordinance in 2016"

Source: https://oaklandprivacy.org/timeline/ (entity-cited)
Source tier: primary
Source content: Under 2016: "Jan. Legislation actually creating the Oakland Privacy Advisory Commission is finally passed into law."
Comparison: 2016 creation by ordinance matches (specifically January 2016).
Decision: primary-sourced

## Claim 13: "Oakland Privacy members have served on the commission since its first meeting in July 2016"

Source: https://oaklandprivacy.org/timeline/ (entity-cited)
Source tier: primary
Source content: Under 2016: "July. The first meeting of the Oakland Privacy Advisory Commission happens. Brian Hofer is elected as chair."
Comparison: The timeline now directly confirms the July 2016 first meeting, with Hofer (an Oakland Privacy member, listed in the entity's key_people) elected chair at it. Resolves pass 1's uncorroborated (the cited Oaklandside source was 429-blocked then and remains so; the entity's own timeline carries the fact).
Decision: primary-sourced

## Claim 14: "longtime chair Brian Hofer, who served on the commission from its inception until his resignation in November 2025"

Source: https://oaklandprivacy.org/timeline/ (entity-cited); https://oaklandside.org/2025/11/12/oakland-privacy-advisory-commission-resignation-brian-hofer-sean-everhart/ (entity-cited; direct fetch returns HTTP 429 — content retrieved this session via web-search excerpt of the same article)
Source tier: primary
Source content: Timeline (July 2016): "Brian Hofer is elected as chair." Oaklandside (12 Nov 2025): "Brian Hofer, former chair of the commission and District 1 commissioner, and Sean Everhart, commissioner for District 7, tendered their resignations from the civilian-run oversight board last week"; "Hofer, first appointed when the Privacy Advisory Commission was established in 2016, had been serving in a holdover capacity since his term expired in March." Resignation dated "Tuesday, Nov. 4, 2025."
Comparison: Inception-to-resignation tenure and the November 2025 resignation both check: chair from the first meeting (timeline, primary) and resignation in November 2025 with 2016 first appointment (Oaklandside, mainstream). Resolves pass 1's uncorroborated.
Decision: corroborated

## Claim 15: "The July 2019 facial recognition amendment made Oakland the third U.S. city to ban government use of face surveillance, after San Francisco and Somerville, Massachusetts"

Source: https://www.eff.org/deeplinks/2019/07/victory-oakland-city-council-votes-ban-government-use-face-surveillance (entity-cited)
Source tier: mainstream
Source content: "Earlier this week, Oakland's City Council voted unanimously to ban local government use of face surveillance" (published July 2019); "will make Oakland the third U.S. city to take this critical step"; the article identifies San Francisco, CA and Somerville, MA as the two preceding cities.
Comparison: July 2019 date, third-city framing, and the SF/Somerville precedence all match. Rests on EFF alone.
Decision: single-source

## Claim 16: "adopted by unanimous council vote in July 2019"

Source: https://www.eff.org/deeplinks/2019/07/victory-oakland-city-council-votes-ban-government-use-face-surveillance (entity-cited)
Source tier: mainstream
Source content: "Oakland's City Council voted unanimously to ban local government use of face surveillance."
Comparison: Unanimous council vote in July 2019 matches. (CBS SF's May 2019 piece reports the *commission's* unanimous approval, an earlier step — it does not independently confirm the council vote.)
Decision: single-source

## Claim 17: "The Privacy Advisory Commission's recommendation cited demographic disparities in the technology's error rates as among its grounds"

Source: https://www.cbsnews.com/sanfrancisco/news/oaklands-facial-recognition-ban-passes-first-administrative-hurdle/
Source tier: mainstream
Source content: "The city's Privacy Commission unanimously approved the ban which now has to pass through the Public Safety Committee and the Oakland City Council before being adopted." "'We know that it has a really high error rate, especially for women and people of color,' according to Brian Hofer, chair of the Oakland Privacy Commission." (3 May 2019.)
Comparison: The commission's recommendation and the demographic error-rate grounds are connected directly by its chair's stated rationale in mainstream coverage of the recommendation. Resolves pass 1's uncorroborated (the entity-cited EFF piece mentions the MIT error-rate research but does not attribute it to the commission).
Decision: single-source

## Claim 18: "The 15 December 2020 amendment package added first-in-the-nation prohibitions on predictive policing analytics, voice recognition, gait recognition, and distance-based biometric identification"

Source: https://oaklandprivacy.org/timeline/ (entity-cited); https://secure-justice.org/blog/first-in-the-nation-bans-predictive-analytics-biometric-surveillance-technologies (entity-cited); https://www.eff.org/deeplinks/2021/01/oaklands-progressive-fight-protect-residents-government-surveillance (entity-cited)
Source tier: primary
Source content: Timeline: "Dec 15th. Oakland City Council passes amendments to SERO forbidding use of predictive policing and biometrics." Secure Justice: "On December 15, 2020, the Oakland City Council unanimously adopted a number of recommended amendments to its existing surveillance technology ordinance"; bans "became effective on January 12, 2021." EFF 2021: bans "predictive policing technology," "voice recognition technology" (first city), and identification "based on physiological, biological, or behavioral characteristics ascertained from a distance" including gait.
Comparison: The 15 December 2020 adoption and all four enumerated prohibitions match across three independent sources. (StateScoop's "final vote on January 12, 2021" refers to the second reading/effective date — consistent with adoption on Dec 15.)
Decision: corroborated

## Claim 19: "making Oakland at that point the largest U.S. city to ban predictive policing and the first to ban government use of voice recognition"

Source: https://www.eff.org/deeplinks/2021/01/oaklands-progressive-fight-protect-residents-government-surveillance (entity-cited)
Source tier: mainstream
Source content: "Oakland became the largest municipality to prohibit predictive policing, following Santa Cruz (2020) and New Orleans (2020)"; Oakland is "the first city to ban government use of voice recognition technology."
Comparison: Both the largest-city and first-voice-recognition framings match EFF. Secure Justice's adjacent "first municipality in the country" framing concerns the prohibition model generally, not these two specific superlatives, so the claim rests on EFF alone.
Decision: single-source

## Claim 20: Governing magazine "called the first standing civilian privacy oversight body of its kind in the U.S."

Source: https://www.governing.com/next/What-Cities-Can-Learn-from-the-Nations-Only-Privacy-Commission.html (entity-cited)
Source tier: mainstream
Source content: Title: "What Cities Can Learn from the Nation's Only Privacy Commission." Body: "No other city has a standing group with such a broad charter"; the commission "remains the only body with such a wide scope."
Comparison: The body's "first standing civilian privacy oversight body of its kind" is a constructed paraphrase of Governing's "only" framing — within paraphrase tolerance per the pass-1 adjudication ("only of its kind" entails "first of its kind"; "standing" and the civilian character track the source). Rests on Governing alone.
Decision: single-source

## Claim 21: "[Secure Justice's account of the legislative record] articulates the Privacy Advisory Commission's core rationale: that algorithms trained on historically skewed policing data direct officers back to communities they have already over-policed, compounding the bias in a self-reinforcing loop the city could not adequately mitigate"

Source: https://secure-justice.org/blog/first-in-the-nation-bans-predictive-analytics-biometric-surveillance-technologies (entity-cited)
Source tier: primary
Source content: "It was partly due to the structural racism present in American law enforcement that the PAC recommended that Oakland ban the use of predictive analytics due to the 'feedback loop' phenomenon"; "based on past data which was likely collected in a disproportionate manner...a computer algorithm directs police back to the very same community being over-policed"; "Predictive analytics thereby serve to cement or even accelerate existing biases."
Comparison: The rewritten body claim is an attribution to the Secure Justice post, and the post (authored by Brian Hofer) explicitly attributes the feedback-loop rationale to the PAC and articulates it in the terms the body summarizes. The cited document is itself the dispositive source for what it articulates. Pass 1's `correction` (the same rationale was then misattributed to StateScoop, which never carried it) was repaired by the 2026-05-26 re-sourcing — CLEARED; no re-discrepancy.
Decision: primary-sourced

## Claim 22: ACLU's Community Control Over Police Surveillance (CCOPS) template "has been adopted by more than twenty U.S. jurisdictions since 2016"

Source: https://www.aclu.org/community-control-over-police-surveillance
Source tier: primary
Source content: "CCOPS laws have been adopted in 26 jurisdictions from coast to coast, where they serve to protect and empower nearly 18 million people." "the Community Control Over Police Surveillance (CCOPS) campaign was launched on September 21, 2016."
Comparison: 26 jurisdictions satisfies "more than twenty," and the September 2016 launch satisfies "since 2016." The ACLU's own program page is the primary document for its program's adoption count. Resolves pass 1's uncorroborated.
Decision: primary-sourced

## Claim 23: scalar:sources[8].note (StateScoop) — "covers Brian Hofer's concern about Forensic Logic data-sharing as the trigger for the ban and the commission's preventive-regulation rationale"

Source: https://statescoop.com/oakland-calif-set-to-ban-predictive-policing-biometric-surveillance-tools/ (entity-cited)
Source tier: mainstream
Source content: "Hofer had initial concerns about the data-sharing between Oakland Police and Forensic Logic, but as he looked more closely at the company's user manual, curtailing the predictive policing capability also offered by Forensic Logic became a greater concern." The commission realized it "hadn't yet regulated the technologies"; "We want to lay it out, as a flat-out ban, so that if some future technology comes forward that's not [made by] Forensic Logic, we don't have to go through this whole use-policy process."
Comparison: Scalar path sources[8].note. The rewritten note (the pass-1 correction's frontmatter half) accurately describes the article's content: the Forensic Logic data-sharing concern as the entry point and the commission's get-ahead-of-it regulation rationale. The note's description matches the article it annotates.
Decision: single-source

## Claim 24: scalar:sources[0].note (timeline) — "records ... the 2017 Surveillance Equipment Ordinance, the 2017 Oakland-ICE separation ..."

Source: https://oaklandprivacy.org/timeline/ (entity-cited)
Source tier: primary
Source content: Timeline 2017: "Jan 5th – After months of working on the language, OPAC passes SERO unanimously for consideration by the City Council after a public hearing"; "July 18th. Oakland City Council nixes memorandum of understanding between Oakland and ICE." Timeline 2018: "May 15 – City of Oakland unanimously adopts surveillance transparency ordinance."
Comparison: Scalar path sources[0].note. The "2017 Oakland-ICE separation" is confirmed (July 2017 council vote). The note's "2017 Surveillance Equipment Ordinance" is ambiguous against the timeline: the commission passed SERO in January 2017 and the committee in May 2017, but full council adoption was May 2018 (which the body itself correctly dates to 2018). Whether "the 2017 ordinance" denotes the 2017 commission passage or misdates the 2018 adoption cannot be settled from the phrasing — a judgment-loaded edge, not a single-token contradiction.
Decision: uncorroborated
