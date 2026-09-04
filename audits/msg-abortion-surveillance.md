---
entity_id: msg-abortion-surveillance
entity_hash: 934d03ff4fe2e9c59a486e751d24194ff3e4b7c9
audit_date: 2026-09-04
pass: 1
status: corrections-pending
claims_total: 21
claims_corroborated: 4
claims_primary_sourced: 6
claims_single_source: 4
claims_uncorroborated: 4
open_corrections: 3
sources_consulted:
  - https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy
  - https://www.vice.com/en/article/location-data-abortion-clinics-safegraph-planned-parenthood
  - https://digitaldefensefund.org/ddf-guides/abortion-privacy
  - https://app.leg.wa.gov/RCW/default.aspx?cite=19.373
  - https://nationalpartnership.org/report/data-privacy-reproductive-freedom/
  - https://en.wikipedia.org/wiki/Dobbs_v._Jackson_Women%27s_Health_Organization
  - https://www.ftc.gov/news-events/news/press-releases/2021/06/ftc-finalizes-order-flo-health-fertility-tracking-app-shared-sensitive-health-data-facebook-google
  - https://www.ftc.gov/news-events/news/press-releases/2021/01/developer-popular-womens-fertility-tracking-app-settles-ftc-allegations-it-misled-consumers-about
  - https://www.guttmacher.org/2022/12/state-policy-trends-2022-devastating-year-us-supreme-courts-decision-overturn-roe-leads
  - https://housedemocrats.wa.gov/blog/2023/04/27/governor-inslee-signs-wa-my-health-my-data-act-into-law/
  - https://iapp.org/resources/article/washington-my-health-my-data-act-overview
  - https://www.aclu.org/news/privacy-technology/impending-threat-of-abortion-criminalization-brings-new-urgency-to-the-fight-for-digital-privacy
  - https://www.wyden.senate.gov/news/press-releases/sens-wyden-hirono-rep-jacobs-reintroduce-the-my-body-my-data-act-to-protect-reproductive-and-sexual-health-data
  - https://sarajacobs.house.gov/news/press-releases/rep-jacobs-sens-hirono-and-wyden-reintroduce-bill-to-protect-reproductive-and-sexual-health-data
  - https://www.cnn.com/2023/09/23/us/nebraska-abortion-pill-jessica-burgess
  - https://www.forbes.com/sites/anafaguy/2023/09/22/nebraska-mom-who-gave-teen-daughter-abortion-pills-sentenced-to-two-years-in-prison/
---

Type-shape note: Message is a connective type — claims audited are edges (`propagated_by_orgs`) and hard specifics (dates, counts, names, attributions). Interpretive prose about significance/arc is out of remit and received no decision. `related_messages` targets (msg-surveillance-capitalism, msg-data-is-a-civil-rights-issue, msg-ban-biometric-mass-surveillance) all resolve to existing entity files; relatedness itself is interpretation, not a claim.

## Claim 1: "the May 2, 2022 Politico leak of the draft Dobbs v. Jackson Women's Health Organization Supreme Court opinion"

Source: https://en.wikipedia.org/wiki/Dobbs_v._Jackson_Women%27s_Health_Organization
Source tier: tiebreaker
Source content: "On May 2, 2022, Politico released a draft of a majority opinion by Justice Samuel Alito circulated among the justices in February 2022."
Comparison: Date of a public event — Wikipedia-alone-sufficient class per the source rule. Date matches exactly. Appears in scalar:origin and body.
Decision: single-source

## Claim 2: "the June 24, 2022 Dobbs decision"

Source: https://en.wikipedia.org/wiki/Dobbs_v._Jackson_Women%27s_Health_Organization
Source tier: tiebreaker
Source content: "The Court issued its decision on June 24, 2022. In a 6–3 judgment, the Court reversed the Fifth Circuit's decision and remanded the case for further review."
Comparison: Date of a public court decision — Wikipedia-alone-sufficient class. Matches.
Decision: single-source

## Claim 3: Edge propagated_by_orgs → org-electronic-frontier-foundation; "EFF published 'Reproductive Privacy Requires Data Privacy'" "within days of the leak" (May 2022)

Source: https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy
Source tier: primary
Source content: Article dated May 10, 2022: "EFF supports data privacy for all, and that includes people seeking reproductive health care." "Even before the Supreme Court draft decision regarding Roe v. Wade leaked, EFF was engaged with reproductive justice advocates on how to better protect data privacy for people seeking care, providing it, and funding it."
Comparison: Edge target file exists; EFF's own publication confirms it propagated the data-privacy-for-reproductive-rights framing. Published May 10, eight days after the May 2 leak — "within days" is loose but not a token error.
Decision: primary-sourced

## Claim 4: "the article named the specific data categories at risk (period-app data, location history, search queries, text messages), the specific legal mechanisms by which that data could reach law enforcement (subpoenas to platforms, data-broker purchases, voluntary disclosure)"

Source: https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy
Source tier: primary
Source content: Full-text reproduction of the article (three targeted fetches, one verbatim paragraph-by-paragraph) shows a short post endorsing California A.B. 2091. It contains no enumeration of period-app data, location history, search queries, or text messages, and no discussion of subpoenas to platforms, data-broker purchases, or voluntary disclosure. Its only surveillance examples: "This sad legacy of data misuse stretches from census data being used for Japanese-American internment during World War II, to license plate data being weaponized against immigrants today."
Comparison: The content attribution to the cited article is not supported by the article as fetched. Not a single-token replacement, so not routed as a correction; the fix requires prose judgment. Fetches used a summarizing model, so a residual miss is possible — flagged rather than asserted as error.
Decision: uncorroborated

## Claim 5: scalar:sources[0].note — EFF article "establishes that reproductive health data generated through commercial applications sits outside HIPAA protections, can be subpoenaed by law enforcement in states that have criminalized abortion"

Source: https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy
Source tier: primary
Source content: The article's only subpoena discussion concerns A.B. 2091: "it prohibits health care providers and service plans from releasing medical information related to people seeking or obtaining an abortion, in response to a subpoena or request based on another state's law." No HIPAA or commercial-application content found in full-text reproduction.
Comparison: Scalar path sources[0].note. Same finding as Claim 4 — the note characterizes the article as containing an argument the fetched text does not carry. The HIPAA-gap argument is real elsewhere in the corpus's sources (e.g. the National Partnership report) but is not in this EFF post.
Decision: uncorroborated

## Claim 6: EFF article endorsed "California's A.B. 2091, extending medical-provider privacy protections to abortion-related records"

Source: https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy
Source tier: primary
Source content: "That's why EFF supports California's A.B. 2091, authored by Asm. Mia Bonta and sponsored by Planned Parenthood Affiliates of California." "We urge California's legislators to pass A.B. 2091 as a crucial step to building such a sanctuary."
Comparison: Endorsement confirmed. The entity's gloss of the bill (shielding medical information about abortion from out-of-state legal process) matches the article's description.
Decision: primary-sourced

## Claim 7: Edge propagated_by_orgs → org-aclu — ACLU propagated the reproductive-surveillance framing

Source: https://www.aclu.org/news/privacy-technology/impending-threat-of-abortion-criminalization-brings-new-urgency-to-the-fight-for-digital-privacy
Source tier: primary
Source content: Via search snippets: ACLU, "Impending Threat of Abortion Criminalization Brings New Urgency to the Fight for Digital Privacy"; ACLU "is working across the nation to introduce state legislation to prevent law enforcement from making overly broad requests to try to identify everyone who visited a particular location (such as an abortion clinic) or searched online for particular keywords"; multiple ACLU state-chapter publications (Indiana, Massachusetts, Arizona) on digital privacy and abortion.
Comparison: Edge target file exists; the org's own publications confirm propagation of the framing.
Decision: primary-sourced

## Claim 8: "The FTC's June 2021 enforcement action against Flo Health" — finalized order; "Flo shared menstrual cycle data, pregnancy status, and fertility information with Facebook, Google, Flurry (Yahoo), and AppsFlyer" despite privacy promises

Source: https://www.ftc.gov/news-events/news/press-releases/2021/06/ftc-finalizes-order-flo-health-fertility-tracking-app-shared-sensitive-health-data-facebook-google
Source tier: primary
Source content: Via search snippets (ftc.gov 403s on direct fetch): FTC finalized the order June 22, 2021; "despite promising to keep users' health data private, Flo shared sensitive health data from millions of users of its Flo Period & Ovulation Tracker app with marketing and analytics firms, including Facebook and Google… Facebook, Google's Fabric service, marketing firm AppsFlyer, and analytics firm Flurry."
Comparison: Recipient list, June 2021 finalization date, and promised-vs-actual sharing all match (complaint first announced January 2021; entity cites the June finalized order, consistent). Flurry was a Yahoo/Verizon Media property, so "Flurry (Yahoo)" is accurate. The body's quoted policy fragment ("may be shared with" only limited parties) was not located verbatim in fetched material; the substance (promise of limited sharing) is confirmed. Corroborated by FTC releases plus natlawreview.com and mobihealthnews.com coverage.
Decision: corroborated

## Claim 9: Flo Health — "the leading menstrual-tracking application with over 100 million users"

Source: https://www.ftc.gov/news-events/news/press-releases/2021/01/developer-popular-womens-fertility-tracking-app-settles-ftc-allegations-it-misled-consumers-about
Source tier: primary
Source content: Via search snippets: FTC describes Flo as "a fertility-tracking app used by more than 100 million consumers."
Comparison: The 100-million figure matches the FTC's own release. "Leading" is characterization consistent with FTC's "popular."
Decision: primary-sourced

## Claim 10: SafeGraph "sold aggregated location data of visitors to abortion clinics, including Planned Parenthood," "for less than $200"

Source: https://www.vice.com/en/article/location-data-abortion-clinics-safegraph-planned-parenthood
Source tier: mainstream
Source content: "In total, the data cost just over $160." "SafeGraph classifies 'Planned Parenthood' as a 'brand' that can be tracked, and the data Motherboard purchased includes more than 600 Planned Parenthood locations in the United States."
Comparison: "$160 for a week of data on 600+ Planned Parenthood locations" supports both "including Planned Parenthood" and "less than $200." Single mainstream source (the investigation itself).
Decision: single-source

## Claim 11: "A Motherboard / Vice investigation, published after the Dobbs decision, documented that the location-data broker SafeGraph sold aggregated location data…"

Source: https://www.vice.com/en/article/location-data-abortion-clinics-safegraph-planned-parenthood
Source tier: mainstream
Source content: Article dateline: "May 3, 2022, 12:46pm."
Comparison: Body section "The structural vulnerability" states the investigation was published after the Dobbs decision (June 24, 2022). The article was published May 3, 2022 — the day after the draft-opinion leak, seven weeks before the decision. Single correct replacement: "published after the Dobbs draft leak" (or "the day after the draft-opinion leak").
Decision: correction

## Claim 12: scalar:origin — "After the June 24, 2022 Dobbs decision, a Motherboard / Vice investigation documented that the location-data broker SafeGraph sold aggregated location data of visitors to abortion clinics…"

Source: https://www.vice.com/en/article/location-data-abortion-clinics-safegraph-planned-parenthood
Source tier: mainstream
Source content: Article dateline: "May 3, 2022, 12:46pm."
Comparison: Scalar path: origin. Same error as Claim 11 in the frontmatter origin scalar — the investigation predates the decision by seven weeks. Replacement: "After the May 2, 2022 draft-opinion leak" (sequencing token).
Decision: correction

## Claim 13: "SafeGraph's data included the home census-tract origin of visitors to specific clinic locations"

Source: https://www.vice.com/en/article/location-data-abortion-clinics-safegraph-planned-parenthood
Source tier: mainstream
Source content: "SafeGraph calculates where it believes visitors to a location live to the census block level."
Comparison: Body says "census-tract"; the source says census block level (a finer unit than a tract). Single correct replacement: "census-tract" → "census block". The accompanying de-anonymization-risk framing is consistent with the article.
Decision: correction

## Claim 14: Digital Defense Fund distributed guidance "under the title 'Keep Your Abortion Private & Secure'" for abortion seekers and providers

Source: https://digitaldefensefund.org/ddf-guides/abortion-privacy
Source tier: primary
Source content: Guide title confirmed on the live page: "Keep Your Abortion Private & Secure"; audience: people seeking abortions protecting their digital privacy; recommendations include disabling mobile ad ID, turning off location sharing, Signal, VPNs.
Comparison: Title, publisher, audience, and practical-guidance character all match the DDF's own page.
Decision: primary-sourced

## Claim 15: "The guide's six-category framework — device security, search privacy, location data, communications, payments, and healthcare records" (body; also scalar:sources[2].note "six practical risk categories (device security, search privacy, location data, communications, payments, and healthcare records)")

Source: https://digitaldefensefund.org/ddf-guides/abortion-privacy
Source tier: primary
Source content: The live guide organizes around concern scenarios ("These are possible concerns you might have") whose categories as fetched are: ad tracking, big-tech data collection, communications privacy, device security, ISP tracking, and in-person privacy.
Comparison: The specific six-category list the entity attributes to the guide does not match the live page (only device security and communications overlap). The guide has six concern scenarios, so the count matches, but the named categories don't; the page may have been restructured since the entity was drafted (2026-06-10). Wayback is unreachable from this harness, so the historical version can't be checked. No single-token replacement — flagged, not asserted as error.
Decision: uncorroborated

## Claim 16: "fourteen states would criminalize abortion within months" of the Dobbs decision

Source: https://www.guttmacher.org/2022/12/state-policy-trends-2022-devastating-year-us-supreme-courts-decision-overturn-roe-leads
Source tier: database
Source content: Via search snippets: "As of December 12, 2022, abortion was unavailable in 14 states" — roughly six months after the June 24, 2022 decision.
Comparison: Count and timeframe both supported by Guttmacher's December 2022 policy roundup.
Decision: single-source

## Claim 17: "The Nebraska prosecution of Jessica Burgess in 2022 — in which the state obtained Facebook Messenger communications between a mother and her 17-year-old daughter about obtaining abortion medication and used them as the evidentiary basis for felony charges"

Source: https://www.cnn.com/2023/09/23/us/nebraska-abortion-pill-jessica-burgess
Source tier: mainstream
Source content: Via search snippets (CNN, Forbes, NBC): "Police secured a search warrant to gain access to Facebook messages between the two, where prosecutors say the women discussed terminating the pregnancy"; "In one of the Facebook messages, Jessica Burgess instructed her daughter on how to take the pills to end the pregnancy, according to court records"; daughter Celeste was 17; Jessica pleaded guilty to two felonies.
Comparison: All tokens match — Nebraska, 2022 charges, Facebook Messenger messages between mother and 17-year-old daughter about abortion pills, obtained via legal process directed at the platform (search warrant to Meta), felony charges. Confirmed across ≥2 mainstream outlets.
Decision: corroborated

## Claim 18: Washington My Health My Data Act "signed by Governor Jay Inslee on April 27, 2023"; "first state-level privacy law explicitly covering consumer health-application data outside the HIPAA framework"; requires "affirmative consent before sharing that data with third parties and prohibits the use of geofencing around healthcare facilities" (also scalar:sources[5].note)

Source: https://app.leg.wa.gov/RCW/default.aspx?cite=19.373
Source tier: primary
Source content: RCW 19.373.030 "Collection or sharing of consumer health data" requires authorization; RCW 19.373.080 "Geofence restrictions." Washington House Democrats (April 27, 2023): "Governor Inslee Signs WA My Health, My Data Act into Law." IAPP: "the first privacy-focused law in the country to protect personal health data that falls outside the ambit of" HIPAA; "unlawful for any person to implement a geofence… [around] any entity that provides in-person health care services."
Comparison: Signing date, signer, first-in-nation status, consent requirement, and geofence prohibition all confirmed against the statute text plus government and specialist sources.
Decision: corroborated

## Claim 19: "the 'My Body, My Data Act' introduced by Representative Sara Jacobs and Senators Wyden and Hirono… without passage as of mid-2026"

Source: https://www.wyden.senate.gov/news/press-releases/sens-wyden-hirono-rep-jacobs-reintroduce-the-my-body-my-data-act-to-protect-reproductive-and-sexual-health-data
Source tier: primary
Source content: Sponsors' own press releases: introduced June 21, 2022 by Rep. Jacobs with Sens. Hirono and Wyden; reintroduced May 2023 and again June 11, 2025 ("Rep. Jacobs, Sens. Hirono and Wyden Reintroduce Bill to Protect Reproductive and Sexual Health Data").
Comparison: Sponsor names match. The June 2025 reintroduction confirms non-passage through mid-2026.
Decision: corroborated

## Claim 20: "The National Partnership for Women & Families' October 2024 report" — "Data Privacy & Reproductive Freedom: How Digital Surveillance Increases the Risk of Pregnancy Criminalization Post-Dobbs"

Source: https://nationalpartnership.org/report/data-privacy-reproductive-freedom/
Source tier: primary
Source content: Report page confirms title "Data Privacy & Reproductive Freedom: How Digital Surveillance Increases the Risk of Pregnancy Criminalization Post-Dobbs," publication October 2024, author organization National Partnership for Women & Families (author Ashley Emery).
Comparison: Title, date, and organization match exactly (in body and scalar:sources[3].note).
Decision: primary-sourced

## Claim 21: The NPWF report "documented the full range of data types at issue: location history…, search queries…, period-app data…, payment records (purchases associated with abortion medication), digital communications…, and insurance and billing records" (also scalar:sources[3].note listing "payment records")

Source: https://nationalpartnership.org/report/data-privacy-reproductive-freedom/
Source tier: primary
Source content: Fetched report content confirms location data, web browsing/search data, menstruation/ovulation/pregnancy-tracking app data, and communications ("phone records and other communications," "social media posts and text messages"), plus the HIPAA-gap framing ("fall[s] outside the scope of HIPAA"). A pointed second fetch found no mention of payment/purchase records or insurance/billing records.
Comparison: Four of the six attributed data types confirmed; payment records and insurance/billing records not found in the fetched report content (the full PDF may contain them, but the fetched landing content does not). Enumeration attribution partially unsupported; no single-token replacement.
Decision: uncorroborated
