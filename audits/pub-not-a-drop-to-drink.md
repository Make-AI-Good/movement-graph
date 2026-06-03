---
entity_id: pub-not-a-drop-to-drink
entity_hash: 6c616f2f910320582ad8ea3b2d5dc154e808be93
audit_date: 2026-06-02
pass: 1
status: discrepancy
claims_total: 15
claims_verified: 9
claims_discrepancy: 2
claims_unverifiable: 4
sources_consulted:
  - https://www.globalactionplan.org.uk/insights/publications/not-a-drop-to-drinkhow-britains-data-centre-surge-threatens-water-security
  - https://www.globalactionplan.org.uk/insights/news/report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas
  - https://www.globalactionplan.org.uk/about-us/our-team/oliver-hayes
  - https://caad.info/analysis/reports/the-ai-threats-to-climate-change/
  - https://www.foxglove.org.uk/2026/01/22/uk-government-admits-serious-error-data-centre/
---

## Claim 1: scalar:name — "Not a drop to drink: How Britain's AI data centre surge threatens water security"

Source: https://www.globalactionplan.org.uk/insights/publications/not-a-drop-to-drinkhow-britains-data-centre-surge-threatens-water-security
Source content: GAP's own publication landing page titles the report "Not a drop to drink: How Britain's data centre surge threatens water security" (no "AI" qualifier). The URL slug itself — `not-a-drop-to-drinkhow-britains-data-centre-surge-threatens-water-security` — corroborates: it omits any `ai-` segment between "britains" and "data-centre". The announcement page (`...report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas`) is consistent with the no-"AI" title (it refers to "data centre developments", not "AI data centre developments").
Comparison: the entity's `name` frontmatter scalar inserts "AI" into the title between "Britain's" and "data centre"; the report's actual title (as the publisher renders it) does not contain "AI". The body's opening italic-quotation of the title ("*Not a drop to drink: How Britain's AI data centre surge threatens water security*") inherits the same discrepancy. Fix location: `name:` scalar plus the italicised title in the first paragraph of the body.
Decision: discrepancy

## Claim 2: scalar:publisher — "Global Action Plan" (publisher frontmatter and body)

Source: https://www.globalactionplan.org.uk/insights/publications/not-a-drop-to-drinkhow-britains-data-centre-surge-threatens-water-security
Source content: The report is hosted on GAP's own site under `insights/publications/`; GAP is named as publisher throughout the landing page and the announcement page.
Comparison: matches.
Decision: verified

## Claim 3: scalar:date — "2026-04" (April 2026 publication)

Source: https://www.globalactionplan.org.uk/insights/news/report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas
Source content: GAP's announcement page presents the report as released in April 2026; the PDF URL itself (`not_a_drop_to_drink_-_april_2026.pdf`) names April 2026.
Comparison: matches.
Decision: verified

## Claim 4: body — Oliver Hayes is "GAP's Head of Big Tech and Campaigns"

Source: https://www.globalactionplan.org.uk/about-us/our-team/oliver-hayes
Source content: GAP's own team page for Hayes uses the title "Head of Big Tech & Campaigns" as the primary heading on the profile.
Comparison: matches (the entity's "and" vs. the page's ampersand is paraphrase tolerance). Note: the CAAD page refers to him as "Head of Policy & Campaigns at Global Action Plan", but the entity cites GAP's own team page as the basis and that page is canonical for his current GAP title.
Decision: verified

## Claim 5: body — Nicole Sugerman is "Campaign Manager at ... Kairos"

Source: https://caad.info/analysis/reports/the-ai-threats-to-climate-change/
Source content: CAAD identifies Sugerman as "Campaign Manager at Kairos Fellowship."
Comparison: the entity's own cited source (CAAD) matches "Campaign Manager". However, GAP's announcement page for *this very report* describes her as "Senior Campaigner at Kairos" — a different title, in a canonical primary source published the same month as the report. Two canonical sources disagree on her current title; per the Source rule, the outcome is `unverifiable` rather than picking a winner. (If "Senior Campaigner" is current and "Campaign Manager" is prior, the body should reflect the current title; the audit cannot make that call from the materials available.)
Decision: unverifiable

## Claim 6: body — "84% of proposed water-intensive UK data-centre developments are planned for areas that are already water-stressed or are projected to be water-stressed by 2040"

Source: https://www.globalactionplan.org.uk/insights/news/report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas
Source content: "84% of water-intensive data centre developments proposed for areas that are already water stressed or are projected to be water stressed by 2040."
Comparison: matches; entity phrasing is faithful paraphrase.
Decision: verified

## Claim 7: body — methodology "derived from cross-referencing publicly known proposed data-centre developments with the Environment Agency's 2021 classification of water-stressed areas"

Source: https://www.globalactionplan.org.uk/insights/news/report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas
Source content: GAP's announcement attributes the 84% figure to "Environment Agency 2021 classification of water stressed areas."
Comparison: matches.
Decision: verified

## Claim 8: body — "a single hyperscale data centre requires daily water equivalent to the needs of around 10,000 people"

Source: https://www.globalactionplan.org.uk/insights/publications/not-a-drop-to-drinkhow-britains-data-centre-surge-threatens-water-security
Source content: GAP's landing page: a hyperscale campus requires "enough water each day to meet the needs of around 10,000 people."
Comparison: matches.
Decision: verified

## Claim 9: body — "training a single cutting-edge AI model can evaporate hundreds of thousands of litres of clean water"

Source: https://www.globalactionplan.org.uk/insights/news/report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas
Source content: GAP's announcement: "training a single cutting-edge AI model can evaporate hundreds of thousands of litres of clean water."
Comparison: matches.
Decision: verified

## Claim 10: body — "global AI-related water withdrawals could reach 4.2–6.6 billion cubic metres a year by 2027, exceeding annual UK household consumption"

Source: https://www.globalactionplan.org.uk/insights/news/report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas (announcement) and the PDF (could not fetch — exceeds tool size limit)
Source content: GAP's announcement says "Global AI water demand predicted to exceed UK household water use by next year" — a qualitatively related claim but without the specific 4.2–6.6-billion-cubic-metres range or the 2027 horizon. The specific range is presumably from the report body / PDF, which exceeded the fetch tool's content-size limit and could not be read in this pass.
Comparison: cannot confirm the specific 4.2–6.6 bn m³ figure or the 2027 year from the canonical sources actually fetched.
Decision: unverifiable

## Claim 11: body — "Slough alone hosts 32 operational data centres in a 'seriously water-stressed' area"

Source: https://www.globalactionplan.org.uk/insights/news/report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas
Source content: "at least 32 data centres currently running" in Slough, an area the Environment Agency describes as "seriously water stressed."
Comparison: matches; "32 operational" ≈ "at least 32 ... currently running" within paraphrase tolerance.
Decision: verified

## Claim 12: body — "under high-growth scenarios data centres could account for around 30% of new water demand in the Thames Water region, equivalent to 270 million litres a day"

Source: https://www.globalactionplan.org.uk/insights/news/report-reveals-majority-of-new-data-centres-planned-for-water-stressed-areas
Source content: under high-growth scenarios, data centres would drive "almost 30% of all new water demand in the region – around 270 million litres per day."
Comparison: matches.
Decision: verified

## Claim 13: body — "three of the past five years having experienced excessive dry periods"

Source: (not located in fetched sources; would be inside the report PDF, which exceeded the tool's content-size limit)
Source content: no canonical-source quote available in this pass.
Comparison: the announcement page does not carry this claim; the GAP landing page summary does not either; the PDF could not be fetched whole; without the PDF text, no specific comparison is possible.
Decision: unverifiable

## Claim 14: body — "Foxglove's October 2025 estimate that ten UK hyperscale data centres would generate roughly 2.7 million tonnes of CO2 a year"

Source: https://www.foxglove.org.uk/2026/01/22/uk-government-admits-serious-error-data-centre/ (no mention of these figures); a date-derived URL guess (`.../2025/10/29/ten-data-centres-2-7-million-tonnes-co2/`) returned 404; the Foxglove insights index could not be parsed.
Source content: the cited Foxglove Jan 2026 post mentions hyperscale data centres' "high level of carbon emissions" but carries no 2.7 Mt or ten-data-centres specifics; the entity itself does not cite a Foxglove October 2025 source URL.
Comparison: the specific figure ("2.7 million tonnes") attributed to a "Foxglove October 2025 estimate" could not be verified against any fetched canonical source, and the entity's `sources:` list does not include a Foxglove October-2025 URL that would let a reader cross-check the figure.
Decision: unverifiable

## Claim 15: body — "the January 2026 Government Legal Department concession on the Woodlands Park data centre had already established that ministerial approvals could be quashed for failing to require Environmental Impact Assessment screening"

Source: https://www.foxglove.org.uk/2026/01/22/uk-government-admits-serious-error-data-centre/
Source content: Post dated 22.01.2026 — government lawyers formally accepted the Secretary of State's decision should be quashed, on the basis (per the post's summary) that they had not implemented measures ensuring the developer and future operator would honour climate-impact-mitigation commitments. The post emphasises the climate-impact-commitments enforcement failure rather than EIA-screening specifically.
Comparison: the core facts — January 2026, GLD concession, Woodlands Park, ministerial approval quashable — match. The mechanism the entity names ("failing to require Environmental Impact Assessment screening") is more specific than the mechanism actually summarised in the Foxglove post (failure to enforce climate-impact-mitigation commitments). The two mechanisms are related but not identical. The fetched source does not substantiate the EIA-screening framing as the basis of the concession.
Decision: discrepancy
