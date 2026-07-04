---
entity_id: camp-eff-reproductive-health-data-surveillance-2022-ongoing
entity_hash: 87051d47405739d85a141e5d5b2c46505b2329ff
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 27
claims_corroborated: 13
claims_primary_sourced: 8
claims_single_source: 0
claims_uncorroborated: 1
open_corrections: 5
sources_consulted:
  - https://www.eff.org/deeplinks/2022/06/effs-statement-dobbs-abortion-ruling
  - https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy
  - https://www.eff.org/deeplinks/2022/05/safegraphs-disingenuous-claims-about-location-data-mask-dangerous-industry
  - https://www.eff.org/deeplinks/2022/07/congress-probes-how-location-data-brokers-threaten-reproductive-privacy
  - https://www.eff.org/deeplinks/2022/06/security-and-privacy-tips-people-seeking-abortion
  - https://ssd.eff.org/playlist/reproductive-healthcare-service-provider-seeker-or-advocate
  - https://www.eff.org/deeplinks/2022/12/reproductive-justice-and-digital-rights-year-review
  - https://www.eff.org/deeplinks/2022/09/california-leads-reproductive-and-trans-health-data-privacy
  - https://www.eff.org/deeplinks/2024/04/two-years-post-roe-better-understanding-digital-threats
  - https://www.eff.org/deeplinks/2024/02/sen-wyden-exposes-data-brokers-selling-location-data-anti-abortion-groups-target
  - https://www.eff.org/deeplinks/2023/12/end-geofence-warrants
  - https://www.eff.org/deeplinks/2023/05/eff-supports-my-body-my-data
  - https://www.eff.org/press/releases/eff-and-repro-uncensored-launch-stopcensoringabortion-campaign
  - https://oversightdemocrats.house.gov/news/press-releases/maloney-krishnamoorthi-and-jacobs-launch-probe-of-reproductive-health-data
  - https://www.ftc.gov/news-events/news/press-releases/2022/08/ftc-sues-kochava-selling-data-tracks-people-reproductive-health-clinics-places-worship-other
  - https://www.ftc.gov/news-events/news/press-releases/2024/01/ftc-order-prohibits-data-broker-x-mode-social-outlogic-selling-sensitive-location-data
  - https://www.govtrack.us/congress/bills/118/hr3420
  - https://en.wikipedia.org/wiki/California_Senate_Bill_107
  - https://natlawreview.com/article/new-california-laws-enhance-reproductive-health-privacy-protections
  - https://thehill.com/policy/technology/4465856-wyden-ftc-abortion-clinic-visitor-location-data/
  - https://therecord.media/broker-sold-planned-parenthood-data-wyden
  - https://www.losangelesblade.com/2022/09/30/newsom-signs-refuge-bill-for-trans-kids-their-families-into-law/
  - https://techcrunch.com/2023/12/16/google-geofence-warrants-law-enforcement-privacy/
  - https://www.theregister.com/2023/12/15/google_location_history_geofence/
  - https://www.vice.com/en/article/location-data-abortion-clinics-safegraph-planned-parenthood/
  - https://www.cnbc.com/2022/05/04/data-broker-safegraph-stops-selling-abortion-provider-information.html
  - https://www.cnn.com/2022/08/29/tech/ftc-kochava-abortion-suit/index.html
---

## Claim 1: edge — `lead_orgs` / `participating_orgs` → org-electronic-frontier-foundation

Source: https://www.eff.org/deeplinks/2022/06/effs-statement-dobbs-abortion-ruling (and every other cited source; edge target exists at product/entities/organizations/org-electronic-frontier-foundation.md, name "Electronic Frontier Foundation")
Source tier: primary
Source content: Entire campaign corpus is published under eff.org; congressional letters "cite EFF's reporting on how the State of Illinois bought data from Safegraph" (July 2022 EFF deeplink)
Comparison: EFF is the author and lead of every campaign artifact cited; edge points to the correct existing entity. Congressional letters independently confirm EFF's role.
Decision: corroborated

## Claim 2: `start_date: 2022-05` — campaign began May 2022, before the Dobbs ruling

Source: https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy ; https://www.eff.org/deeplinks/2022/05/safegraphs-disingenuous-claims-about-location-data-mask-dangerous-industry
Source tier: primary
Source content: Reproductive-privacy analysis published May 10, 2022; SafeGraph piece published May 6, 2022 — both pre-date the June 24, 2022 Dobbs decision
Comparison: Two EFF pieces from early May 2022 confirm campaign activity began that month, pre-decision. Both are the entity's own output (one origin), so single-primary rather than two-independent.
Decision: primary-sourced

## Claim 3: scalar:goals — hard specifics (Dobbs June 2022 trigger; corporate demands; sanctuary laws modelled on A.B. 2091/1242; "My Body, My Data" Act contents; geofence/keyword warrant restriction)

Source: https://www.eff.org/deeplinks/2022/06/effs-statement-dobbs-abortion-ruling ; https://www.govtrack.us/congress/bills/118/hr3420 ; https://www.eff.org/deeplinks/2022/09/california-leads-reproductive-and-trans-health-data-privacy
Source tier: primary
Source content: Dobbs statement lists company demands (anonymous access, "stop behavioral tracking," deletion policies, encryption, data request notices); MBMD Act "aims to minimize the amount of sexual health data that is collected... to prevent this information from being disclosed or misused"; A.B. 2091/1242 are the named California models
Comparison: Each hard specific in the goals scalar matches its source; the three-layer demand framing is interpretation over verified facts and not separately judged.
Decision: corroborated

## Claim 4: Dobbs issued June 24, 2022; EFF published its campaign statement the same day

Source: https://www.eff.org/deeplinks/2022/06/effs-statement-dobbs-abortion-ruling
Source tier: primary
Source content: Statement publication date "June 24, 2022" — the day the Court issued Dobbs v. Jackson Women's Health Organization (public-record decision date)
Comparison: Decision date is a Wikipedia-alone-class public-record fact and matches; EFF page confirms same-day statement.
Decision: corroborated

## Claim 5: quote — "seeking, offering, or facilitating abortion access must now assume that any data they provide online or offline could be sought by law enforcement"

Source: https://www.eff.org/deeplinks/2022/06/effs-statement-dobbs-abortion-ruling
Source tier: primary
Source content: "But those seeking, offering, or facilitating abortion access must now assume that any data they provide online or offline could be sought by law enforcement."
Comparison: Body quote matches the source verbatim (body elides the leading "But those").
Decision: primary-sourced

## Claim 6: scalar:sources[0].note — Dobbs statement carries the three-track response (individuals, companies, policymakers) and names location, search history, social media, text messages, app behavioral data

Source: https://www.eff.org/deeplinks/2022/06/effs-statement-dobbs-abortion-ruling
Source tier: primary
Source content: Statement addresses individuals, companies, and policymakers; names "location services/location tracking, search engine queries, social media posts, text messages, app data, behavioral tracking data"
Comparison: Note's description of the source's content matches the source.
Decision: primary-sourced

## Claim 7: body — "In a [May 2022 analysis](…/2022/05/reproductive-privacy-requires-data-privacy)… EFF documented that data broker SafeGraph had already been selling location information showing visits to Planned Parenthood facilities, including the origin and destination addresses"

Source: https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy (linked); https://www.eff.org/deeplinks/2022/05/safegraphs-disingenuous-claims-about-location-data-mask-dangerous-industry (actual)
Source tier: primary
Source content: Linked article names no data broker at all ("no specific surveillance technology companies or data brokers by name"). EFF's May 6, 2022 SafeGraph piece states SafeGraph "was selling location information 'related to visits to clinics that provide abortions including Planned Parenthood facilities.' This included where people came from and where they went afterwards."
Comparison: The factual substance is true and EFF-documented in May 2022, but the body's hyperlink attributes it to an article that contains no SafeGraph mention. Single correct replacement: link https://www.eff.org/deeplinks/2022/05/safegraphs-disingenuous-claims-about-location-data-mask-dangerous-industry instead.
Decision: correction

## Claim 8: scalar:sources[1].note — the May 2022 reproductive-privacy article "names license plate readers, geofencing technology ('83,000 cameras'), and electronic health records as specific surveillance mechanisms"

Source: https://www.eff.org/deeplinks/2022/05/reproductive-privacy-requires-data-privacy
Source tier: primary
Source content: Article mentions "license plate data being weaponized against immigrants" and "census data being used for Japanese-American internment during World War II"; it contains no geofencing/"83,000 cameras" figure and no electronic-health-records mention. The "83,000 cameras" figure belongs to a May 2025 EFF article ("She Got an Abortion. So A Texas Cop Used 83,000 Cameras to Track Her Down") that appears only in the page's Related Updates sidebar.
Comparison: scalar path sources[1].note (url …/2022/05/reproductive-privacy-requires-data-privacy). The note asserts source content the source does not contain; fix is to drop the geofencing-"83,000 cameras" and electronic-health-records items (license-plate reference survives only in its immigrant-data-misuse form). The note's other items — Planned Parenthood Affiliates of California as A.B. 2091 sponsor, the census/internment parallel, pre-decision timing — all verify.
Decision: correction

## Claim 9: five brokers (Babel Street, Digital Envoy, Gravy Analytics, SafeGraph, Placer.ai) under congressional inquiry July 2022, led by Rep. Maloney (Oversight chair) and Rep. Krishnamoorthi (Consumer Policy Subcommittee chair); EFF cited as research source in the letters

Source: https://oversightdemocrats.house.gov/news/press-releases/maloney-krishnamoorthi-and-jacobs-launch-probe-of-reproductive-health-data ; https://www.eff.org/deeplinks/2022/07/congress-probes-how-location-data-brokers-threaten-reproductive-privacy
Source tier: primary
Source content: Committee press release, July 8, 2022: Maloney (Chairwoman, Oversight and Reform), Krishnamoorthi (Chairman, Subcommittee on Economic and Consumer Policy), and Jacobs "sent letters to five data broker companies... SafeGraph, Digital Envoy, Placer.ai, Gravy Analytics, Babel Street." EFF: "The letters begin by quoting EFF's Eva Galperin... They also cite EFF's reporting"
Comparison: All five broker names, both committee leads and their roles, the July 2022 date, and EFF's cited-research role match the government record and EFF's account. (Letters also went to five health-app companies; entity's five-broker claim is about brokers and is correct.)
Decision: corroborated

## Claim 10: Rep. Sara Jacobs authored the "My Body, My Data" Act

Source: https://www.govtrack.us/congress/bills/118/hr3420 ; https://www.eff.org/deeplinks/2022/07/congress-probes-how-location-data-brokers-threaten-reproductive-privacy ; https://oversightdemocrats.house.gov/news/press-releases/maloney-krishnamoorthi-and-jacobs-launch-probe-of-reproductive-health-data
Source tier: primary
Source content: H.R. 3420 (118th Congress) "My Body, My Data Act of 2023," sponsor "Rep. Jacobs, Sara [D-CA-51]"
Comparison: Sponsorship matches across the congressional record, the committee release, and EFF's account.
Decision: corroborated

## Claim 11: body — digital security guide for abortion seekers "published on June 24, 2022"

Source: https://www.eff.org/deeplinks/2022/06/security-and-privacy-tips-people-seeking-abortion
Source tier: primary
Source content: Page publication date: "June 23, 2022"; no last-updated date shown (confirmed by two independent fetches)
Comparison: Body's date token contradicts the source page's own dateline by one day. Single correct replacement: June 23, 2022.
Decision: correction

## Claim 12: a dedicated Surveillance Self-Defense playlist exists for reproductive-healthcare seekers, providers, and advocates

Source: https://ssd.eff.org/playlist/reproductive-healthcare-service-provider-seeker-or-advocate
Source tier: primary
Source content: Playlist addresses "a clinician, clinic escort, activist, ally, patient in need of healthcare, or some combination of any of the above"
Comparison: Playlist exists at the cited URL and names the claimed audiences.
Decision: primary-sourced

## Claim 13: body — "The playlist structure — differentiating by role rather than by topic —" tailored "to three distinct threat models"

Source: https://ssd.eff.org/playlist/reproductive-healthcare-service-provider-seeker-or-advocate
Source tier: primary
Source content: Page acknowledges "there are many different threat models within the abortion access movement" but its modules are topic-organized (Your Security Plan, Keeping Your Data Safe, Communicating With Others, …), not role-differentiated
Comparison: The current page does not exhibit role-differentiated structure; the 2022-era page may have differed but the Wayback Machine is unreachable from this harness. Cannot confirm or refute the structural claim as of the audit date.
Decision: uncorroborated

## Claim 14: the "Stop Censoring Abortion" series documents platform suppression of abortion content, including removals/suspensions and algorithmic suppression

Source: https://www.eff.org/press/releases/eff-and-repro-uncensored-launch-stopcensoringabortion-campaign ; https://www.eff.org/pages/stop-censoring-abortion
Source tier: primary
Source content: EFF and Repro Uncensored's #StopCensoringAbortion campaign produced "a multi-part blog series" documenting that abortion speech "is being removed, restricted, and silenced by platforms at an alarming rate," including "suppression, shadow-banning, and outright removal of posts and accounts"
Comparison: The series exists and documents what the body describes (account-level and algorithmic suppression).
Decision: primary-sourced

## Claim 15: body + scalar:sources[5].note — the "Stop Censoring Abortion" series is attributed/linked to the 2022 year-in-review article

Source: https://www.eff.org/deeplinks/2022/12/reproductive-justice-and-digital-rights-year-review ; https://www.eff.org/deeplinks/2025/02/stop-censoring-abortion-fight-reproductive-rights-digital-age
Source tier: primary
Source content: The 2022 year-in-review contains no mention of a "Stop Censoring Abortion" series (fetch: "No mention found in this article"). The campaign launched in February 2025 with the Repro Uncensored coalition.
Comparison: Body hyperlinks the series name to the 2022 year-in-review, and scalar sources[5].note claims that article is "primary source for... the 'Stop Censoring Abortion' blog series on platform suppression" — both attribute the series to a source that does not contain it (the series post-dates it by ~2 years). Single correct replacement for the body link: https://www.eff.org/pages/stop-censoring-abortion (or the 2025 deeplink); the note's series item should be dropped. Fix locations: body § Stop Censoring Abortion link; scalar sources[5].note.
Decision: correction

## Claim 16: scalar:sources[5].note — other items: three-audience guide structure; A.B. 2091/1242 as "a crucial step forward" toward digital sanctuary; BIPOC/lower-income/immigrant/LGBTQ+ disproportionality framing

Source: https://www.eff.org/deeplinks/2022/12/reproductive-justice-and-digital-rights-year-review
Source tier: primary
Source content: "assembled data privacy guides for anyone potentially affected: patients seeking reproductive healthcare, clinics and health professionals, and those involved in the abortion access advocacy movements"; bills described as "marking a crucial step forward in making California a digital sanctuary state"; threat "especially dangerous for BIPOC, lower-income, immigrant, LGBTQ+ people, and other traditionally marginalized communities"
Comparison: All three remaining note items match the source (note paraphrases "crucial step forward" accurately).
Decision: primary-sourced

## Claim 17: A.B. 2091 (Asm. Mia Bonta) — prohibits providers disclosing abortion-related medical records to out-of-state law enforcement; blocks California subpoenas in out-of-state cases

Source: https://www.eff.org/deeplinks/2022/09/california-leads-reproductive-and-trans-health-data-privacy ; https://natlawreview.com/article/new-california-laws-enhance-reproductive-health-privacy-protections
Source tier: primary
Source content: "A.B. 2091: authored by Asm. Mia Bonta"; "AB 2091 prohibits health care providers from releasing, in response to out-of-state subpoenas, requests, or to law enforcement, medical information related to an individual seeking or obtaining an abortion" and bars subpoena issuance based on out-of-state orders
Comparison: Author and both operative provisions match across EFF and independent legal-analysis coverage of the statute (a public-record fact).
Decision: corroborated

## Claim 18: A.B. 1242 (Asm. Rebecca Bauer-Kahan) — restricts digital surveillance in investigations of California-lawful abortions; prohibits tech companies complying with out-of-state demands

Source: https://www.eff.org/deeplinks/2022/09/california-leads-reproductive-and-trans-health-data-privacy ; https://natlawreview.com/article/new-california-laws-enhance-reproductive-health-privacy-protections
Source tier: primary
Source content: "A.B. 1242: authored by Asm. Rebecca Bauer-Kahan"; "AB 1242 prohibits law enforcement and California corporations from sharing information related to a lawful abortion with out-of-state entities," e.g. blocking out-of-state warrants for cell tower location data served on California tech companies
Comparison: Author and both operative provisions match EFF and independent legal analysis.
Decision: corroborated

## Claim 19: S.B. 107 (Sen. Scott Wiener) — extends parallel protections to parents of transgender youth receiving gender-affirming care in California

Source: https://en.wikipedia.org/wiki/California_Senate_Bill_107 ; https://www.eff.org/deeplinks/2022/09/california-leads-reproductive-and-trans-health-data-privacy
Source tier: primary
Source content: SB 107 "protects access to gender-affirming medical care for minors and prevents the enforcement of out-of-state laws regarding such care... introduced by state senator Scott Wiener"; EFF: "prevents medical providers from releasing information about parents allowing children to receive gender-affirming care"
Comparison: Author and content match (named-statute definitional fact; Wikipedia-alone class, plus EFF's own description).
Decision: corroborated

## Claim 20: body — "three data sanctuary laws signed by Governor Newsom on September 27, 2022"; scalar:outcomes — "both signed by Governor Newsom on September 27, 2022, alongside S.B. 107"

Source: https://natlawreview.com/article/new-california-laws-enhance-reproductive-health-privacy-protections ; https://en.wikipedia.org/wiki/California_Senate_Bill_107 ; https://www.losangelesblade.com/2022/09/30/newsom-signs-refuge-bill-for-trans-kids-their-families-into-law/
Source tier: mainstream
Source content: "On September 27, 2022, California Governor Gavin Newsom signed into law a pair of bills [A.B. 1242 and A.B. 2091]"; "Governor Gavin Newsom signed SB 107 on September 29, 2022"
Comparison: A.B. 2091 and A.B. 1242 were signed September 27, 2022 (matches), but S.B. 107 was signed September 29, 2022 — the body's "three... signed... on September 27, 2022" and the outcomes scalar's "alongside" co-dating are wrong for S.B. 107. Single correct replacement: S.B. 107 signed September 29, 2022 (two days later). Fix locations: body § State legislation first sentence; scalar:outcomes first sentence.
Decision: correction

## Claim 21: EFF characterised all three bills as "strong protections" and called on other states to enact similar legislation

Source: https://www.eff.org/deeplinks/2022/09/california-leads-reproductive-and-trans-health-data-privacy
Source tier: primary
Source content: "strong protections of reproductive and transgender health data privacy"; "Other pro-choice and pro-trans states should enact similar laws."
Comparison: Both the quoted characterization and the call to other states match EFF's own page (the claim is about EFF's stance; EFF's page is the primary document).
Decision: primary-sourced

## Claim 22: the FTC sued Kochava in 2022, naming the ability to identify devices visiting abortion clinics and trace them to residences

Source: https://www.ftc.gov/news-events/news/press-releases/2022/08/ftc-sues-kochava-selling-data-tracks-people-reproductive-health-clinics-places-worship-other ; https://www.cnn.com/2022/08/29/tech/ftc-kochava-abortion-suit/index.html
Source tier: primary
Source content: FTC (Aug 29, 2022): "it is possible to identify a mobile device that visited a women's reproductive health clinic and trace that mobile device to a single family residence"; suit alleges unfair sale of sensitive geolocation data
Comparison: Year, agency action, and the specific clinic-to-residence tracing allegation match the government record and mainstream coverage. (ftc.gov 403s on direct fetch; content confirmed via search-indexed text plus CNN/Washington Post coverage.)
Decision: corroborated

## Claim 23: in January 2024 the FTC issued an order barring X-Mode (later renamed Outlogic) from selling sensitive location data near healthcare facilities

Source: https://www.ftc.gov/news-events/news/press-releases/2024/01/ftc-order-prohibits-data-broker-x-mode-social-outlogic-selling-sensitive-location-data ; https://www.eff.org/deeplinks/2024/02/sen-wyden-exposes-data-brokers-selling-location-data-anti-abortion-groups-target
Source tier: primary
Source content: "FTC Order Prohibits Data Broker X-Mode Social and Outlogic from Selling Sensitive Location Data" (Jan 2024); FTC "charged X-Mode Social and its successor Outlogic with selling precise location data that could be used to track people's visits to sensitive locations such as medical and reproductive health clinics"; EFF: "We also commend the FTC's recent bar on a data broker selling sensitive location data"
Comparison: Date, parties (X-Mode → successor Outlogic), and scope (sensitive locations including reproductive health clinics) match. Order announced January 2024, finalized April 2024 — "issued an order" in January is consistent with the record.
Decision: corroborated

## Claim 24: in February 2024, Sen. Wyden's investigation publicly exposed data brokers selling location data to anti-abortion groups that used it to target clinic visitors

Source: https://www.eff.org/deeplinks/2024/02/sen-wyden-exposes-data-brokers-selling-location-data-anti-abortion-groups-target ; https://thehill.com/policy/technology/4465856-wyden-ftc-abortion-clinic-visitor-location-data/ ; https://therecord.media/broker-sold-planned-parenthood-data-wyden
Source tier: mainstream
Source content: Wyden's February 2024 letter revealed Near Intelligence "tracked individuals' visits to nearly 600 Planned Parenthood locations" for The Veritas Society (Wisconsin Right to Life), which delivered ~14.3 million targeted anti-abortion ads; EFF covered it February 27, 2024
Comparison: Month, actor (Wyden), mechanism (broker location data sold/used to target clinic visitors with anti-abortion ads) all match multiple independent outlets plus EFF.
Decision: corroborated

## Claim 25: in late 2023 Google committed to changing location data storage to prevent geofence warrant abuses — a reform EFF had been pressing since 2022 / advocated directly to the company

Source: https://www.eff.org/deeplinks/2023/12/end-geofence-warrants ; https://techcrunch.com/2023/12/16/google-geofence-warrants-law-enforcement-privacy/ ; https://www.theregister.com/2023/12/15/google_location_history_geofence/
Source tier: primary
Source content: EFF (Dec 13, 2023): Google's changes (on-device storage, 3-month default deletion, encrypted backups) "would appear to make it much more difficult—if not impossible—for Google to provide mass location data in response to a geofence warrant, a change we've been asking Google to implement for years"
Comparison: "Late 2023" matches December 2023; the geofence-abuse purpose matches; "asking Google to implement for years" (as of Dec 2023) supports "pressing since 2022" and direct advocacy to the company. Independent mainstream coverage corroborates the change and its intent.
Decision: corroborated

## Claim 26: the "My Body, My Data" Act was reintroduced in the 118th Congress, retained EFF endorsement, and had not passed the Senate as of mid-2026

Source: https://www.govtrack.us/congress/bills/118/hr3420 ; https://www.eff.org/deeplinks/2023/05/eff-supports-my-body-my-data
Source tier: database
Source content: H.R. 3420 (118th Congress), "My Body, My Data Act of 2023," introduced May 17, 2023 by Rep. Sara Jacobs, companion S. 1656 (Wyden/Hirono); GovTrack: "it did not receive a vote." EFF (May 2023): "EFF supports Rep. Sara Jacobs' 'My Body, My Data' Act"
Comparison: 118th-Congress reintroduction and EFF endorsement confirmed; the bill received no vote in either chamber, consistent with "had not passed the Senate as of mid-2026." No source shows any Senate passage.
Decision: corroborated

## Claim 27: scalar:sources[7].note — April 2024 retrospective documents digital-evidence prosecutions, the Near Intelligence case, Google's late-2023 change, and collaboration with Digital Defense Fund

Source: https://www.eff.org/deeplinks/2024/04/two-years-post-roe-better-understanding-digital-threats
Source tier: primary
Source content: Published April 18, 2024; documents the Nebraska Facebook-Messenger prosecution and a Google-search-history indictment; "a long investigation into Near Intelligence, a data broker company that sold geolocation data to The Veritas Society"; Google's late-2023 storage promise; "there is Digital Defense Fund, a digital security organization for the abortion access movement, who we are grateful and proud to boost"
Comparison: All four note items appear in the source; "collaboration... as digital security partner" mildly paraphrases "grateful and proud to boost" but names the same relationship the source states.
Decision: primary-sourced
