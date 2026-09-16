---
entity_id: msg-nhs-data-grab
entity_hash: da71fa911da7ce2cffe273c727aec4470c348570
audit_date: 2026-09-16
pass: 1
status: corrections-pending
claims_total: 20
claims_corroborated: 8
claims_primary_sourced: 4
claims_single_source: 3
claims_uncorroborated: 3
open_corrections: 2
sources_consulted:
  - https://medconfidential.org/whats-the-story/care-data-2013-2016/
  - https://www.theregister.com/2021/05/13/nhs_data_grab
  - https://www.foxglove.org.uk/2021/07/02/what-is-the-nhs-data-grab/
  - https://www.foxglove.org.uk/2021/04/01/success-uk-government-concedes-lawsuit-over-23m-nhs-data-deal-with-controversial-us-tech-corporation-palantir/
  - https://www.foxglove.org.uk/2023/11/30/legal-action-palantir-nhs-federated-data-platform/
  - https://www.nationalhealthexecutive.com/Research-and-Technology/patient-data-transfer-to-google-deepmind-by-trust-deemed-unlawful-by-ico
  - https://www.newstatesman.com/science-tech/2021/06/nhs-data-grab-shows-rise-tech-authoritarianism
  - https://www.gov.uk/government/publications/data-saves-lives-reshaping-health-and-social-care-with-data/data-saves-lives-reshaping-health-and-social-care-with-data
  - https://www.theregister.com/2016/09/27/scrapped_nhs_care_data_cost_taxpayer_8_1m_pounds/
  - https://www.digitalhealth.net/2020/12/palantir-awarded-23m-deal-to-continue-work-on-nhs-covid-19-data-store/
  - https://www.digitalhealth.net/2021/06/ggp-data-for-planning-and-research-implementation-date-moved-to-sept/
  - https://www.digitalhealth.net/2021/07/gpdpr-september-implementation-date-scrapped/
  - https://www.computerweekly.com/news/252505760/Over-a-million-opt-out-of-NHS-data-sharing
  - https://www.cnbc.com/2017/07/03/google-deepmind-nhs-deal-health-data-illegal-ico-says.html
  - https://www.hunton.com/privacy-and-cybersecurity-law-blog/uk-government-ends-nhs-patient-database-scheme
  - https://lowdownnhs.info/topics/accountablility/palantir-the-controversy-the-contracts-and-the-campaign/
  - https://www.gov.uk/government/news/national-data-guardian-appointed-to-safeguard-patients-healthcare-information
  - https://www.theregister.com/software/2021/06/22/uk-health-secretary-matt-hancock-follows-delay-to-gp-data-grab-with-campaign-called-data-saves-lives/508616
---

Connective type (Message): claim surface is edges (`propagated_by_orgs`; `originating_person` / `originating_org` are empty — no claim) and hard specifics in the `origin` scalar, body, and `sources[].note` scalars. `related_messages` is not in the mission's claim-surface list — not audited. Narrative significance prose ("Why it has carried") is interpretation, not claim — skipped per type-shape rule.

## Claim 1: edge — propagated_by_orgs → org-foxglove

Source: https://www.foxglove.org.uk/2021/07/02/what-is-the-nhs-data-grab/ ; https://www.foxglove.org.uk/2023/11/30/legal-action-palantir-nhs-federated-data-platform/
Source tier: primary
Source content: Foxglove's own explainer is titled "What is the NHS Data Grab?" and argues the scheme takes "55 million people's cradle-to-grave health records" "without asking for permission, presenting an informed choice."
Comparison: Foxglove uses the framing verbatim in its own published campaign material across 2021 and 2023; edge points to the correct entity.
Decision: corroborated

## Claim 2: edge — propagated_by_orgs → org-privacy-international

Source: https://lowdownnhs.info/topics/accountablility/palantir-the-controversy-the-contracts-and-the-campaign/
Source tier: mainstream
Source content: The "No Palantir in the NHS campaign" roster "includes Privacy International alongside the Good Law Project, Corporate Watch, and other groups"; PI also endorsed Medact's briefing on Palantir and NHS data systems.
Comparison: PI's participation in the NHS-Palantir patient-data campaign supports the propagation edge; confirmed in one specialist-outlet campaign account only this pass.
Decision: single-source

## Claim 3: origin/body — care.data history: 2013 inception, GP-record extraction plan, medConfidential primary opposition, poster/pizza-leaflet communication, FOI-revealed data losses vs 25-year safety claim

Source: https://medconfidential.org/whats-the-story/care-data-2013-2016/
Source tier: primary
Source content: "from its inception in 2013 to its cancellation in 2016"; "a poster in a GP surgery would be sufficient to tell patients"; "The leaflets were often delivered folded into pizza leaflets"; NHS England's director claimed "There have been no data losses in over 25 years," yet "Freedom of Information requests revealed major data losses in each year for which information was held."
Comparison: Body and origin match the framing-originator org's own campaign-history document (the entity's cited source) on all these specifics.
Decision: primary-sourced

## Claim 4: care.data "formally cancelled on 6 July 2016" (origin scalar + body)

Source: https://www.hunton.com/privacy-and-cybersecurity-law-blog/uk-government-ends-nhs-patient-database-scheme ; https://www.digitalhealth.net/2016/07/care-data-dumped-after-caldicott-review/ ; https://medconfidential.org/whats-the-story/care-data-2013-2016/
Source tier: mainstream
Source content: "On July 6, 2016, the UK government decided to close its controversial care.data scheme" (Hunton); "care.data was finally cancelled in July 2016" (medConfidential); Digital Health: "Care.data dumped after Caldicott review" (July 2016).
Comparison: Exact date confirmed by multiple canonical sources. Note: the `sources[].note` for the medConfidential URL attributes the 6 July date to that page, which carries only "July 2016" — the date is right but rests on other sources.
Decision: corroborated

## Claim 5: care.data cost "approximately £8.1 million" (origin scalar + body)

Source: https://www.theregister.com/2016/09/27/scrapped_nhs_care_data_cost_taxpayer_8_1m_pounds/
Source tier: mainstream
Source content: "NHS England spent nearly £8m on its controversial care.data programme," with an FOI-based itemization totalling "£7.7m"; "NHS England clarified that the £7.7m figure is incomplete, as costs incurred before April 2013 and additional expenses from NHS Digital are not included."
Comparison: The best source gives £7.7m/"nearly £8m" and states the total is incomplete; no fetched source carries £8.1m in text (only The Register's URL slug). Figures vary by accounting scope, so no single correct replacement exists.
Decision: uncorroborated

## Claim 6: care.data "around 1.5 million opt-outs" before cancellation (origin scalar + body)

Source: no canonical source found
Source tier: none
Source content: Search of care.data opt-out reporting surfaced "about 700,000 patients chose the type 2 opt-out" (The Conversation, via search); the cited medConfidential page as fetched carries no opt-out count.
Comparison: The 1.5M figure is attributed by the `sources[].note` to the medConfidential page, which does not carry it; canonical counts found this pass differ by objection type and none states ~1.5 million.
Decision: uncorroborated

## Claim 7: GPDPR announced May 2021 the morning after the Queen's Speech; opt-out deadline 23 June 2021; 55 million patients; scope includes mental health, sexual health, ethnicity and sexual-orientation data; framing spread via The Register, New Statesman, openDemocracy

Source: https://www.theregister.com/2021/05/13/nhs_data_grab ; https://www.newstatesman.com/science-tech/2021/06/nhs-data-grab-shows-rise-tech-authoritarianism
Source tier: mainstream
Source content: "NHS Digital planned to transfer GP records from all 55 million English citizens to a central repository for 'research' purposes, with an opt-out deadline of June 23, 2021"; collection "covered diagnoses, medications, test results... mental health data, sexual health records, and demographic details on ethnicity and sexual orientation"; NHS Digital "deliberately delayed the announcement until after the Queen's Speech"; New Statesman (2 June 2021): "After 23 June the NHS will scrape the data of 55 million people held by GP surgeries in England."
Comparison: All hard specifics match across two independent canonical sources; the New Statesman piece itself evidences the uptake claim.
Decision: corroborated

## Claim 8: attribution — "medConfidential's coordinator Phil Booth publicly characterised [GPDPR] as 'the biggest data grab in NHS history'" (origin scalar; body: "medConfidential's coordinator Phil Booth characterised it publicly as 'the biggest data grab in NHS history'"; scalar:sources[1].note attributes the phrase to Booth)

Source: https://www.theregister.com/2021/05/13/nhs_data_grab
Source tier: mainstream
Source content: "Dr Neil Bhatia, a Hampshire GP and information governance lead, is credited with the phrase... (He initially called it the 'biggest data grab' in the NHS history.)" Booth's quotes in the same article are "even bigger than care.data," "It's more data, more breadth, more depth, it's the whole record... it's the whole f&*king deal," and "the single most valuable data asset on the planet."
Comparison: The entity's own cited source credits the phrase to Dr Neil Bhatia, not Phil Booth; no source found attributing it to Booth (search results say "campaigners"/"dubbed" generically). Fix locations: origin scalar, body § Origin second paragraph, and scalar:sources[1].note (the theregister.com entry). Correct replacement: attribute "biggest data grab" to Dr Neil Bhatia (Hampshire GP); Booth's characterisations are "even bigger than care.data" etc. Surrounding clause "medConfidential's coordinator" also needs rework — prose judgment beyond a single token, so Editor may route to Researcher.
Decision: correction

## Claim 9: Booth quotes — "even bigger than care.data"; "It's more data, more breadth, more depth — it's the whole fucking deal"; "the single most valuable data asset on the planet"; "They learned last time that it's the publicity that kills them"

Source: https://www.theregister.com/2021/05/13/nhs_data_grab
Source tier: mainstream
Source content: "It's more data, more breadth, more depth, it's the whole record, not just prospectively... it's the whole f&*king deal"; "the single most valuable data asset on the planet"; Booth said NHS Digital delayed the announcement "because they learned last time that it's the publicity that kills them."
Comparison: All quoted fragments are genuine Booth quotes in the cited article; the body's em-dash elision drops "it's the whole record, not just prospectively" from the middle of the quote (compression, tokens accurate). Living-person quotes resting on one mainstream source.
Decision: single-source

## Claim 10: postponement — 1 July 2021 start postponed first to 1 September, then indefinitely

Source: https://www.digitalhealth.net/2021/06/ggp-data-for-planning-and-research-implementation-date-moved-to-sept/ ; https://www.digitalhealth.net/2021/07/gpdpr-september-implementation-date-scrapped/ ; https://www.theregister.com/2021/06/08/uk_gov_delays_gp_data_grab/
Source tier: mainstream
Source content: On 8 June 2021 Jo Churchill told MPs the extraction date "would be pushed back from 1 July to 1 September"; her 19 July letter to GPs: "we are not setting a specific start date for the collection of data."
Comparison: Exact sequence (1 July → 1 September → indefinite) confirmed by multiple canonical sources.
Decision: corroborated

## Claim 11: "more than one million people filed opt-outs" during the 2021 campaign

Source: https://www.computerweekly.com/news/252505760/Over-a-million-opt-out-of-NHS-data-sharing ; https://www.understandingpatientdata.org.uk/news/nhs-data-opt-outs-missing-pieces-puzzle
Source tier: mainstream
Source content: "Over a million opt out of NHS data-sharing" (Computer Weekly); national data opt-outs rose by "1,275,153 compared to 1 June 2021" in the month to 1 July 2021.
Comparison: Matches; the opt-out surge exceeded one million in June 2021.
Decision: corroborated

## Claim 12: "NHS England contracted Palantir to build and operate the NHS Covid-19 Datastore in March 2020 for £23 million" (body, § The core argument)

Source: https://www.digitalhealth.net/2020/12/palantir-awarded-23m-deal-to-continue-work-on-nhs-covid-19-data-store/ ; https://www.opendemocracy.net/en/controversial-tech-firm-palantir-23m-nhs-data-deal/
Source tier: mainstream
Source content: "Palantir Technologies UK was initially paid £1 for the data integration work it was doing on the NHS Covid-19 datastore" (March 2020); "In December 2020, Palantir was awarded a £23 million two-year contract to continue its work on the NHS Covid-19 Data Store... The contract commenced on 12 December."
Comparison: The £23m attaches to the December 2020 two-year extension, not the March 2020 engagement (which was for £1). The entity's own `sources[].note` for the Foxglove concession URL correctly calls it "the December 2020 two-year Palantir Covid Datastore extension" — the body sentence contradicts it. Fix location: body § The core argument, third paragraph. Correct replacement: March 2020 contract for £1; £23 million December 2020 extension.
Decision: correction

## Claim 13: openDemocracy and Foxglove initiated legal proceedings February 2021; government conceded (April 2021) not to extend Palantir's NHS role beyond pandemic use without public consultation and a new data-protection impact assessment; trust-deficit/vaccine-hesitancy framing

Source: https://www.foxglove.org.uk/2021/04/01/success-uk-government-concedes-lawsuit-over-23m-nhs-data-deal-with-controversial-us-tech-corporation-palantir/ ; https://www.business-humanrights.org/en/latest-news/opendemocracy-sues-uk-govt-over-23m-nhs-data-deal-with-palantir/
Source tier: primary
Source content: "Foxglove supported openDemocracy to launch legal action over the government's failure" to consult; lawsuit "initiated in February 2021, leading to the government's concession in April 2021"; government agreed to "prevent Palantir from using the NHS datastore for non-Covid purposes without public consultation" and to "a new analysis of whether that would be in compliance with data protection law"; lack of public confidence "appears to be fuelling vaccine hesitancy" in marginalised communities.
Comparison: All specifics match Foxglove's own release plus independent coverage. Body's quoted phrase "risked exacerbating the trust deficit in these communities when the government needs it most" is thematically present but not verbatim-confirmed in the fetched rendering.
Decision: corroborated

## Claim 14: November 2023 FDP challenge — letter before claim (30 Nov 2023) by Foxglove, Just Treatment, Doctors' Association UK, National Pensioners Convention against the £330m Palantir contract; no-legal-basis-without-Parliament argument; contradictory opt-out statements; Home Office/DWP access concerns; HSJ finding 8 of 36 pilot sites reported benefit

Source: https://www.foxglove.org.uk/2023/11/30/legal-action-palantir-nhs-federated-data-platform/
Source tier: primary
Source content: "Foxglove, alongside Just Treatment, Doctors' Association UK, and the National Pensioners Convention" sent a "letter before claim" asserting "the government has no legal basis to go ahead unless they come back to parliament"; an NHS official told the BBC "You cannot opt out but you can ask questions"; "of 36 FDP pilot sites, just eight reported tangible benefits"; concerns cite DWP-NHS data-sharing discussions and the 2018 scrapped plan to "use the NHS records of immigrants to find and deport them."
Comparison: Every hard specific matches the litigant coalition's own release (URL dated 30 Nov 2023). One later account gives the contract as "up to £360m over five years" — a ceiling-value framing, not a contradiction of the £330m award figure.
Decision: primary-sourced

## Claim 15: DeepMind/Royal Free — ~1.6 million patient records transferred for the Streams acute-kidney app; ICO ruled the transfer unlawful July 2017 under the Data Protection Act 1998; data subjects not adequately informed; no fine imposed

Source: https://www.nationalhealthexecutive.com/Research-and-Technology/patient-data-transfer-to-google-deepmind-by-trust-deemed-unlawful-by-ico ; https://www.cnbc.com/2017/07/03/google-deepmind-nhs-deal-health-data-illegal-ico-says.html ; https://www.digitalhealth.net/2017/07/royal-free-and-deepmind-did-not-comply-with-dpa-ico/
Source tier: mainstream
Source content: ICO ruling of July 3, 2017 on "approximately 1.6 million patient records"; "Patients would not have reasonably expected their information to have been used in this way, and the Trust could and should have been far more transparent"; Streams "was designed to test an alert and detection system for acute kidney failure"; "the ICO... has asked the Trust to sign a formal undertaking" — resolved through an undertaking rather than a fine.
Decision: corroborated
Comparison: All specifics confirmed across the cited source and independent coverage.

## Claim 16: "the data had been transferred under an agreement signed 30 September 2015" (body; scalar:sources[5].note attributes this to the nationalhealthexecutive.com page)

Source: https://techcrunch.com/2017/08/31/documents-detail-deepminds-plan-to-apply-ai-to-nhs-data-in-2015/ (via search)
Source tier: mainstream
Source content: "The information sharing agreement (ISA) between Google UK Limited and Royal Free was signed on 29 September 2015, though one source also references September 30, 2015 for the agreement date." The cited nationalhealthexecutive.com page as fetched carries no agreement date.
Comparison: Canonical sources split between 29 and 30 September 2015, and the `sources[].note` attributes the date to a page that does not carry it. When canonical sources disagree, no winner is picked.
Decision: uncorroborated

## Claim 17: Matt Hancock launched a campaign called "Data Saves Lives" in June 2021, immediately after the GPDPR delay

Source: https://www.theregister.com/software/2021/06/22/uk-health-secretary-matt-hancock-follows-delay-to-gp-data-grab-with-campaign-called-data-saves-lives/508616
Source tier: mainstream
Source content: Article title (22 June 2021): "UK health secretary Matt Hancock follows delay to GP data grab with campaign called 'Data saves lives'".
Comparison: Matches on actor, label, timing, and sequence relative to the delay; one canonical source found this pass.
Decision: single-source

## Claim 18: the 2022 "Data Saves Lives" strategy (June 2022) acknowledged the 2021 mistake and proposed trust-rebuilding measures (transparency statement, information-governance frameworks, engagement commitment)

Source: https://www.gov.uk/government/publications/data-saves-lives-reshaping-health-and-social-care-with-data/data-saves-lives-reshaping-health-and-social-care-with-data
Source tier: primary
Source content: "In the summer of 2021, we made a mistake and did not do enough to explain the improvements needed to the way we collect general practice data... Not only did we insufficiently explain, we also did not listen and engage well enough"; commitments include "co-designing a transparency statement" and "publishing information governance frameworks"; updated 15 June 2022 by the Department of Health & Social Care.
Comparison: Matches the government record. Body's "produced jointly by the Department of Health and Social Care and NHS England" — the gov.uk page lists DHSC as publisher; joint NHS England authorship not confirmed by the fetched page (minor framing, no contradiction).
Decision: primary-sourced

## Claim 19: Parliament restricted the Care Act 2014 to limit data use to healthcare provision or health promotion; Dame Fiona Caldicott appointed (first) National Data Guardian in November 2014

Source: https://www.gov.uk/government/news/national-data-guardian-appointed-to-safeguard-patients-healthcare-information ; https://medconfidential.org/whats-the-story/care-data-2013-2016/
Source tier: primary
Source content: Jeremy Hunt "appointed Dame Fiona Caldicott as the first National Data Guardian (NDG) for Health and Care in November 2014"; "The Government added a 'restriction' to the Care Act 2014 that required NHS patients' data be used for the 'provision of' care or 'the promotion of health'."
Comparison: Both public-record facts confirmed by a government record plus the medConfidential account.
Decision: corroborated

## Claim 20: Foxglove's July 2021 explainer — pseudonymised-not-anonymised distinction and re-identification risk; IGARD opacity critique; openSafely as analysis-in-place alternative; under-resourced ICO; "taking personal information from 55 million people without asking permission"

Source: https://www.foxglove.org.uk/2021/07/02/what-is-the-nhs-data-grab/
Source tier: primary
Source content: "This data is not anonymous. It is pseudonymous. This is a really important distinction"; "It is pretty easy to identify people from pseudonymised data"; IGARD's "records of their meetings aren't easily understood by the average person"; openSAFELY "takes research queries to the data itself – instead of grabbing the entire GP record"; the ICO is "understaffed, underfunded, and unable to enforce against major breaches"; "55 million people's cradle-to-grave health records" taken "without asking for permission."
Comparison: Every element of the body's account of the explainer matches the explainer itself (the entity's cited source).
Decision: primary-sourced
