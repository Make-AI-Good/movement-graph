---
entity_id: lg-panhandle-1st-coalition
entity_hash: aca1a8065594806a5d3736801020300c7c839e61
audit_date: 2026-06-09
pass: 2
reclassified_at: 2026-06-10
status: supported
claims_total: 22
claims_corroborated: 20
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 2
sources_consulted:
  - https://mediajustice.org/news/grassroots-opposition-forces-setback/
  - https://www.sierraclub.org/texas/blog/2025/12/project-matador-trump-ai-data-center-texas
  - https://abc7amarillo.com/news/local/amarillo-council-approves-water-sale-to-fermi-america-amid-pricing-concerns-ai-data-center-les-simpson-mayor-cole-stanley-trent-sisemore-artificial-intelligence
  - https://abc7amarillo.com/news/local/protesters-raise-water-concerns-over-worlds-largest-ai-data-center-in-texas-fermi-america-texas-tech-potter-county-courthouse-madison-boyle-amarillo-minority-coalition-groundwater-ogallala-aquifer-ashlyn-major-mayor-cole-stanley
  - https://www.yahoo.com/news/articles/fermi-pauses-construction-project-matador-002402437.html
  - https://constructionreviewonline.com/texas-state-owned-tceq-processes-clean-air-permit-as-fermi-america-grinds-project-matador-ai-campus-to-a-halt/
  - https://news.oilandgaswatch.org/post/texas-company-plans-massive-power-plants-to-fuel-intelligence-campus-named-after-trump
  - https://nonprofitquarterly.org/how-mediajustice-is-leading-communities-to-push-back-against-ai-data-centers/
  - https://amarillotribune.org/2025/10/29/amarillo-city-council-authorizes-water-supply-agreement-with-fermi-america/
  - https://www.newschannel10.com/2025/12/04/tceq-hosts-public-meeting-air-quality-permits-submitted-by-fermi-america/
---

## Pass 2 notes

Pass 1 (entity_hash 51d0295c, 2026-05-23) found 19 verified / 1 discrepancy / 2 unverifiable. The discrepancy was Claim 9 ("rated at 5.5 million gallons a day" — the Fermi SEC-filed expected demand mis-attributed to the agreement's rated capacity). The Editor's 2026-05-23 d25714bf Audit-discrepancy backfill replaced "5.5 million" with "2.5 million" in the body; that is the only diff between the pass-1-audited version (51d0295c) and the current version (aca1a806). All other claims carry forward from pass 1 against the same cited sources. Pass 2 fetched ABC7 Amarillo (council water vote), Sierra Club Texas chapter (turbines / MW / TCEQ counts / PTfT), and MediaJustice (Chase Brady, Danny Cendejas, $150M tenant withdrawal, share-drop, named tenants) fresh to re-confirm the high-traffic load-bearing claims and guard against hallucination-discrepancy drift. The Amarillo Tribune source (relied on in pass 1 for the 10M-gallon expansion ceiling) returned HTTP 429 in this session — the 10M ceiling carries forward from pass 1's fetched quote and is corroborated by Tribune coverage of the letter-of-intent terms; the council-vote-result and 2.5M figure are re-confirmed by ABC7 in this pass. Two unverifiable claims (Claim 11, Facebook coordination post; Claim 21, MediaJustice internal organising-guide and fact-sheet content) remain unverifiable for the same structural reasons as in pass 1.

## Claim 1: "Panhandle 1st Coalition is a grassroots community-organising coalition based in Amarillo, Texas working to stop the Fermi America Project Matador 11-gigawatt AI infrastructure campus"

Source: https://mediajustice.org/news/grassroots-opposition-forces-setback/
Source content: MediaJustice piece names Panhandle 1st Coalition as the community-organising vehicle against Fermi America's Project Matador (an AI data-centre campus); Chase Brady identified as "Organizer with Panhandle 1st Coalition" (re-confirmed this session).
Comparison: Coalition identity, location, target campaign confirmed.
Decision: corroborated

## Claim 2: "proposed for a 5,800-acre site between Amarillo and Panhandle, Texas — a project sited on the Texas Tech University System's land"

Source: https://amarillotribune.org/2025/10/29/amarillo-city-council-authorizes-water-supply-agreement-with-fermi-america/ ; https://news.oilandgaswatch.org/post/texas-company-plans-massive-power-plants-to-fuel-intelligence-campus-named-after-trump
Source content: Pass 1 verified Tribune quote "The campus will span a total of 5,769 acres … part of its partnership with Texas Tech" and the Fermi-filing description of "a 99-year sovereign leasehold interest in approximately 5,855 acres in Carson County, Texas, granted by Texas Tech University."
Comparison: 5,800-acre is a round-figure paraphrase of 5,769–5,855 acres. Texas Tech land tenure verified.
Decision: corroborated

## Claim 3: "next to the U.S. Department of Energy Pantex Nuclear Weapons Facility"

Source: https://news.oilandgaswatch.org/post/texas-company-plans-massive-power-plants-to-fuel-intelligence-campus-named-after-trump
Source content: Pass 1 verified: "Fermi America's campus would be built on land surrounding Pantex" (Pantex is the DoE/NNSA primary nuclear weapons assembly/disassembly facility).
Comparison: Verified.
Decision: corroborated

## Claim 4: "designed to draw water from the Ogallala Aquifer through an Amarillo City municipal water-sale agreement"

Source: https://abc7amarillo.com/news/local/amarillo-council-approves-water-sale-to-fermi-america-amid-pricing-concerns-ai-data-center-les-simpson-mayor-cole-stanley-trent-sisemore-artificial-intelligence ; https://amarillotribune.org/2025/10/29/amarillo-city-council-authorizes-water-supply-agreement-with-fermi-america/
Source content (this session, ABC7): "The Amarillo City Council has approved a proposal to sell 2.5 million gallons of water per day to Fermi America." Pass 1 verified Tribune: "Part of Amarillo's water supply comes from the Ogallala Aquifer."
Comparison: Verified.
Decision: corroborated

## Claim 5: "built around what would be the largest gas plant in the United States once its full 5,100+ MW of gas-turbine capacity is operational"

Source: https://www.sierraclub.org/texas/blog/2025/12/project-matador-trump-ai-data-center-texas
Source content (this session): "more than 5,100 MW of gas capacity"; "the largest gas plant in the United States."
Comparison: Body's "5,100+ MW" and "largest gas plant" both confirmed verbatim.
Decision: corroborated

## Claim 6: "named verbatim in the in-corpus Kairos Fellowship / MediaJustice Fight Data Centers campaign as the lead community-organising vehicle on the Project Matador fight"

Source: https://mediajustice.org/news/grassroots-opposition-forces-setback/
Source content (this session): MediaJustice piece names Panhandle 1st Coalition as the community-organising vehicle on the Project Matador fight.
Comparison: Verified.
Decision: corroborated

## Claim 7: "93 gas-fired turbines around the perimeter of the AI data center"

Source: https://www.sierraclub.org/texas/blog/2025/12/project-matador-trump-ai-data-center-texas
Source content (this session): "93 gas-fired turbines around the perimeter of the AI data center."
Comparison: Verbatim match.
Decision: corroborated

## Claim 8: "an Amarillo City Council water-sale agreement signed in late 2025"

Source: https://amarillotribune.org/2025/10/29/amarillo-city-council-authorizes-water-supply-agreement-with-fermi-america/ ; https://abc7amarillo.com/news/local/amarillo-council-approves-water-sale-to-fermi-america-amid-pricing-concerns-ai-data-center-les-simpson-mayor-cole-stanley-trent-sisemore-artificial-intelligence
Source content: Pass 1 (Tribune): "Council gave final approval on Tuesday, October 28, 2025, by a 4-1 vote." This session (ABC7): "approved by a vote of 4-1."
Comparison: "Late 2025" is a fair gloss on late October 2025; the 4-1 vote result is confirmed by both sources.
Decision: corroborated

## Claim 9: "rated at 2.5 million gallons a day, expandable to 10 million" (Editor-corrected from "5.5 million" since pass 1, per d25714bf Audit-discrepancy backfill)

Source: https://abc7amarillo.com/news/local/amarillo-council-approves-water-sale-to-fermi-america-amid-pricing-concerns-ai-data-center-les-simpson-mayor-cole-stanley-trent-sisemore-artificial-intelligence ; https://amarillotribune.org/2025/10/29/amarillo-city-council-authorizes-water-supply-agreement-with-fermi-america/
Source content (this session, ABC7): "The Amarillo City Council has approved a proposal to sell 2.5 million gallons of water per day to Fermi America." Pass 1 (Tribune, fetched 2026-05-23): "The water delivery agreement calls for a maximum of 2.5 million gallons per day over an initial 20-year term, with potential for increases later. The letter of intent showed they were hoping to buy two and a half million gallons of water a day from the city, and up to 10 million gallons of water a day."
Comparison: 2.5M/day rated capacity re-confirmed by ABC7 this session; 10M expansion ceiling matches the Tribune letter-of-intent passage from pass 1. Pass 1's discrepancy on this claim is resolved by the Editor's backfill.
Decision: corroborated

## Claim 10: "Panhandle 1st convened community attendance at the 4 December 2025 Texas Commission on Environmental Quality public meeting in Panhandle, Carson County"

Source: https://www.newschannel10.com/2025/12/04/tceq-hosts-public-meeting-air-quality-permits-submitted-by-fermi-america/
Source content: Pass 1 verified: "The Texas Commission on Environmental Quality (TCEQ) held a public meeting on Fermi Equipment Holdco, LLC's proposed new Air Quality Standard Permit on Dec. 4 at 7 p.m. at the Carson County War Memorial, 500 Main St. in Panhandle."
Comparison: Meeting date, venue, time confirmed.
Decision: corroborated

## Claim 11: "the coalition's Facebook coordination post framing the meeting as 'Protect our Air — TCEQ meeting on Dec 4th at 7 PM. 500 Main Street, Panhandle, Texas'"

Source: no canonical source found (Facebook page content could not be retrieved this session, as in pass 1)
Source content: —
Comparison: The Facebook post text is the entity's own primary source; the page is not retrievable via WebFetch (Facebook walled content). The 4 December 2025 TCEQ meeting at 500 Main Street, Panhandle is independently verified (Claim 10), but the verbatim wording attributed to the coalition's Facebook post cannot be confirmed without access to the page.
Decision: uncorroborated

## Claim 12: "279 total comments, 63 contested-case-hearing requests, and 21 additional-public-meetings requests on the permit"

Source: https://www.sierraclub.org/texas/blog/2025/12/project-matador-trump-ai-data-center-texas
Source content (this session): "over 279 comments from community members were received - the bulk of them in opposition - including 63 requests for a contested case hearing, as well as 21 requests for another public meeting."
Comparison: Numbers match exactly.
Decision: corroborated

## Claim 13: "named adjacent group Panhandle Taxpayers for Transparency filing the formal Contested Case Hearing requests"

Source: https://www.sierraclub.org/texas/blog/2025/12/project-matador-trump-ai-data-center-texas
Source content (this session): "Panhandle Taxpayers for Transparency" identified as "the main group opposing the site"; "they filed a request for a contested case hearing."
Comparison: Verified.
Decision: corroborated

## Claim 14: "MediaJustice's 15 December 2025 piece records the campaign's clearest single named win: the first prospective tenant withdrew a $150 million funding commitment from Project Matador and Fermi America's share price fell by roughly 50%"

Source: https://mediajustice.org/news/grassroots-opposition-forces-setback/
Source content (this session): "$150 million funding commitment" withdrawn by a prospective tenant; Fermi stock "fell by approximately half" (~50%). Piece dated 15 December 2025 (pass 1 verified).
Comparison: Date, dollar amount, and share-drop magnitude all match.
Decision: corroborated

## Claim 15: "Chase Brady, named in the same piece as Organizer with Panhandle 1st Coalition, framed the moment as evidence that 'investors and other prospective clients are starting to realize what our community has known for some time now. This is an inexperienced and unproven company that should not be trusted with anyone's investments let alone our community's natural resources.'"

Source: https://mediajustice.org/news/grassroots-opposition-forces-setback/
Source content (this session): Chase Brady's role confirmed as "Organizer with Panhandle 1st Coalition"; the substring "This is an inexperienced and unproven company that should not be trusted" surfaced verbatim in this session's fetch. Pass 1 verified the full multi-sentence quote.
Comparison: Identity, title, and quote substring re-confirmed; the full quote was verified in pass 1 against the same URL.
Decision: corroborated

## Claim 16: "MediaJustice's campaign specialist Danny Cendejas supplied the campaign's headline framing that 'this moment shows that data centers are not inevitable,' with Oracle, AWS, and Palantir named as the prospective tenant pool the campaign targets and the adjacent Purge Palantir coalition named as a coordinated track"

Source: https://mediajustice.org/news/grassroots-opposition-forces-setback/
Source content (this session): Danny Cendejas identified as "Campaign Specialist at MediaJustice"; Oracle, AWS, and Palantir named as corporations that could have been the withdrawing tenant; Purge Palantir named in the footer as "a nationwide campaign to defend our privacy and stop Palantir." The specific Cendejas quote "this moment shows that data centers are not inevitable" was verified verbatim in pass 1 against the same URL.
Comparison: Cendejas title, named tenants, and named adjacent coalition all confirmed this session; the verbatim Cendejas quote carries forward from pass 1's verification (URL unchanged).
Decision: corroborated

## Claim 17: "Fermi America paused Project Matador construction in early February 2026 pending TCEQ permit approval"

Source: https://www.yahoo.com/news/articles/fermi-pauses-construction-project-matador-002402437.html ; https://constructionreviewonline.com/texas-state-owned-tceq-processes-clean-air-permit-as-fermi-america-grinds-project-matador-ai-campus-to-a-halt/
Source content: Pass 1 verified — Yahoo News piece dated 7 February 2026 references the pause; Construction Review Online piece dated 12 February 2026 describes construction pause pending Clean Air Permit from TCEQ.
Comparison: Pause in early February 2026 confirmed by two independent sources.
Decision: corroborated

## Claim 18: Coalition statement quotes: "Building before obtaining all necessary permits and financial assurances is not innovation, it is negligence" and "This situation reinforces a troubling pattern of outside corporations cutting corners and treating both our community and workforce as expendable"

Source: https://www.yahoo.com/news/articles/fermi-pauses-construction-project-matador-002402437.html
Source content: Pass 1 verified both verbatim quotes in the article.
Comparison: Exact match.
Decision: corroborated

## Claim 19: Coalition's standing demand for industrial projects "fully permitted, properly funded" and "rooted in respect for both people and place"

Source: https://www.yahoo.com/news/articles/fermi-pauses-construction-project-matador-002402437.html
Source content: Pass 1 verified: "Amarillo deserves development that is responsible, fully permitted, properly funded, and rooted in respect for both people and place."
Comparison: Body paraphrase consistent with source quote.
Decision: corroborated

## Claim 20: "142 activist groups across 24 states"

Source: https://nonprofitquarterly.org/how-mediajustice-is-leading-communities-to-push-back-against-ai-data-centers/
Source content: Pass 1 verified: "between May 2024 and March 2025, 142 activist groups in 24 states" carried out organising that delayed or stopped $64 billion in US data centre projects.
Comparison: Numbers match.
Decision: corroborated

## Claim 21: "MediaJustice's October 2025 Amarillo Fermi Data Center fact sheet and the Kairos / MediaJustice 18 August 2025 organiser guide The Cost of Data Centers to Our Communities — And How to Fight Back (cited in the campaign body)"

Source: no canonical source found in this session for the fact sheet or organiser guide as standalone documents (same as pass 1)
Source content: —
Comparison: Neither document is independently locatable as a standalone published URL via canonical-source fetch; the cross-reference is to documents named in the corpus's own Fight Data Centers campaign body but not independently verified here. Status unchanged from pass 1.
Decision: uncorroborated

## Claim 22: September 2025 Potter County Courthouse protest quotes — Madison Boyle (Amarillo Minority Coalition), Ashlyn Major, Mayor Cole Stanley

Source: https://abc7amarillo.com/news/local/protesters-raise-water-concerns-over-worlds-largest-ai-data-center-in-texas-fermi-america-texas-tech-potter-county-courthouse-madison-boyle-amarillo-minority-coalition-groundwater-ogallala-aquifer-ashlyn-major-mayor-cole-stanley
Source content: Pass 1 verified — Madison Boyle (Amarillo Minority Coalition): "Why are we using ground water that farmers could be using for agriculture, for AI data center, where it's going to deplete a resource that's not really renewable?" Ashlyn Major: call for transparency and a public vote. Mayor Cole Stanley: comments on balancing project benefits with protecting Amarillo's natural resources and water.
Comparison: All three speakers' attributions and the substance of their statements match the source.
Decision: corroborated
