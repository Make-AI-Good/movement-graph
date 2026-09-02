---
entity_id: fund-nathan-cummings-foundation
entity_hash: 0ec081840a3a62b8854f0df359f7d798861e12b5
audit_date: 2026-09-01
pass: 1
status: corrections-pending
claims_total: 40
claims_corroborated: 7
claims_primary_sourced: 20
claims_single_source: 3
claims_uncorroborated: 6
open_corrections: 4
sources_consulted:
  - https://nathancummings.org/
  - https://nathancummings.org/our-legacy/
  - https://nathancummings.org/our-focus/
  - https://nathancummings.org/faq/
  - https://nathancummings.org/focus-area/economic-justice/
  - https://nathancummings.org/focus-area/racial-justice/
  - https://nathancummings.org/shareholder-activism/
  - https://nathancummings.org/nathan-cummings-foundation-reveals-results-from-transition-to-100-mission-aligned-investing/
  - https://nathancummings.org/amy-sorensen-ben-dov-elected-chair-board-trustees-nathan-cummings-foundation/
  - https://projects.propublica.org/nonprofits/organizations/237093201
  - https://www.iccr.org/nathan-cummings-foundation-files-suit-to-prevent-axon-from-excluding-shareholder-proposal-on-political-spending-transparency/
  - https://www.iccr.org/iccr-and-the-nathan-cummings-foundation-joint-statement-following-the-settlement-of-the-axon-lawsuit/
  - https://www.influencewatch.org/non-profit/action-center-on-race-the-economy-institute/
  - https://omidyar.com/update/omidyar-network-purchases-shares-of-anthropic/
  - https://impactalpha.com/with-stakes-in-anthropic-impact-investors-seek-a-seat-at-the-ai-table/
  - https://en.wikipedia.org/wiki/Nathan_Cummings_Foundation
  - https://acrecampaigns.org/about/
---

## Claim 1: "New York-based private family foundation established in 1949 by Nathan Cummings (1896–1985)"

Source: https://nathancummings.org/our-legacy/ + https://en.wikipedia.org/wiki/Nathan_Cummings_Foundation
Source tier: primary
Source content: Legacy page: "Nathan Cummings was born in Saint John, New Brunswick, Canada, in 1896." / "He died in 1985, leaving the majority of his estate to this Foundation." Wikipedia: "established in 1949 by Nathan Cummings (1896–1985)". ProPublica: New York, NY, private foundation.
Comparison: Birth/death years primary-confirmed; founding year 1949 on Wikipedia (Wikipedia-alone sufficient for org founding date) plus NCF materials; NY private-foundation status via IRS record.
Decision: corroborated

## Claim 2: "acquired the C.D. Kenny Company of Baltimore in 1939 — a small wholesale distributor of canned goods, coffee, tea, and spices — and built it into Consolidated Foods, which was subsequently renamed Sara Lee Corporation"

Source: https://nathancummings.org/our-legacy/ + https://en.wikipedia.org/wiki/Nathan_Cummings_Foundation
Source tier: primary
Source content: "In 1939, he purchased the C.D. Kenny Company of Baltimore, a small wholesale distributor of canned foods, coffee, tea, and spices." / "That was the beginning of the international company that was known as the Sara Lee Corporation." Wikipedia: founder of Consolidated Foods, "later renamed Sara Lee Corporation".
Comparison: All tokens match ("canned goods" vs source "canned foods" is trivial paraphrase); Consolidated Foods → Sara Lee arc confirmed by both.
Decision: corroborated

## Claim 3: "Cummings retired from active management in 1968 to pursue philanthropy"

Source: https://nathancummings.org/our-legacy/
Source tier: primary
Source content: "He retired from active management in 1968 to pursue philanthropic interests."
Comparison: Exact match.
Decision: primary-sourced

## Claim 4: "on his death in 1985 he left his estate, then estimated at $500 million, to the Foundation" (also scalar:sources[1].note)

Source: https://en.wikipedia.org/wiki/Nathan_Cummings_Foundation
Source tier: tiebreaker
Source content: Wikipedia: "The foundation received most of his estate (then estimated at $500 million)." Legacy page (the cited source): "He died in 1985, leaving the majority of his estate to this Foundation" — no dollar figure on the current page. Search record also surfaces a conflicting estimate ("his foundation received the bulk of his estate, estimated at $200 million according to another source").
Comparison: The estate-to-foundation fact is primary-confirmed, but the $500M figure now rests on Wikipedia alone (financial specifics are tiebreaker-only), the cited legacy page no longer carries it, and estimates conflict in the search record. scalar:sources[1].note attributes the figure to the legacy page, which the current page does not support.
Decision: uncorroborated

## Claim 5: "registered with the IRS as The Nathan Cummings Foundation Inc. (EIN 23-7093201), headquartered in New York, NY" (also scalar:focus, scalar:sources[5].note)

Source: https://projects.propublica.org/nonprofits/organizations/237093201
Source tier: primary
Source content: "The Nathan Cummings Foundation Inc; EIN: 23-7093201; Location: New York, NY; Classification: 501(c)(3) Private Independent Foundation."
Comparison: Exact match on registered name, EIN, city, and classification (IRS filing data via ProPublica).
Decision: primary-sourced

## Claim 6: "total assets of approximately $482 million as of FY2024" (also scalar:focus "$482 million (FY2024)", scalar:sources[5].note "$482,551,138" / "$24,448,521" / "Rey Ramsey ($475,000 compensation)")

Source: https://projects.propublica.org/nonprofits/organizations/237093201
Source tier: primary
Source content: "Most Recent Fiscal Year (2024): Total Assets: $482,551,138; Charitable Disbursements: $24,448,521; President & CEO Compensation: Rey Ramsey received $475,000 in salary."
Comparison: FY2024 assets, disbursements, and Ramsey compensation figures in body and sources[5].note all match the IRS record exactly.
Decision: primary-sourced

## Claim 7: "Current President and CEO is Rey Ramsey" (also scalar:focus)

Source: https://projects.propublica.org/nonprofits/organizations/237093201 + https://impactalpha.com/with-stakes-in-anthropic-impact-investors-seek-a-seat-at-the-ai-table/
Source tier: primary
Source content: ProPublica FY2024: "President & CEO Compensation: Rey Ramsey". ImpactAlpha (2026, via search record): "Rey Ramsey of the Nathan Cummings Foundation".
Comparison: IRS FY2024 filing and current ImpactAlpha coverage both name Ramsey as President & CEO. (Wikipedia still lists Sharon Alpert — stale; the two current canonical sources agree.)
Decision: corroborated

## Claim 8: "Board Chair is Jaimie Mayer" (also scalar:focus "Board Chair: Jaimie Mayer")

Source: https://nathancummings.org/amy-sorensen-ben-dov-elected-chair-board-trustees-nathan-cummings-foundation/
Source tier: primary
Source content: NCF announcement (via search record): "Amy Sorensen Ben Dov Elected Chair of the Board of Trustees of Nathan Cummings Foundation"; National Law Review press release: "Jaimie Mayer, Former NCF Board Chair, Launches Middle Child Philanthropy" (May 2026), after a seven-year tenure as chair.
Comparison: The present-tense claim contradicts NCF's own announcement: Mayer's chairship ended in 2026 and Amy Sorensen Ben Dov is now Board Chair. Single correct replacement — name Ben Dov as chair (or date-bound Mayer's tenure). Fix location: body ¶1 and scalar:focus.
Decision: correction

## Claim 9: NCF self-describes as "a multigenerational family foundation, rooted in the Jewish tradition of social justice", mission "more just, vibrant, sustainable, and democratic society", advancing REEJ in the US and Israel-Palestine (also scalar:sources[0].note)

Source: https://nathancummings.org/
Source tier: primary
Source content: "A multigenerational family foundation, rooted in the Jewish tradition of social justice"; "Working to help create a more just, vibrant, sustainable, and democratic society."; "NCF seeks to advance Racial, Environmental & Economic Justice (REEJ) in the U.S. and Israel-Palestine."
Comparison: All three quoted self-descriptions match the home page verbatim.
Decision: primary-sourced

## Claim 10: REEJ framed as interconnected; root-cause analysis names capitalism, white supremacy, antisemitism, and patriarchy; additional focus areas on combating antisemitism and place-based work in Israel-Palestine and the US South

Source: https://nathancummings.org/our-focus/
Source tier: primary
Source content: "focused on the long-term and interconnected goal of advancing racial, economic, and environmental justice (REEJ)"; "upheld by systems rooted in capitalism, white supremacy, anti-Semitism, and patriarchy"; focus areas listed include "Combating Antisemitism" and place-based Israel-Palestine and U.S. South work.
Comparison: Interconnection framing, all four named root causes, and the focus areas match.
Decision: primary-sourced

## Claim 11: "changemaking, not just grantmaking" — grants, PRIs, endowment strategy, shareholder engagement, and institutional voice deployed collectively

Source: https://nathancummings.org/our-focus/ + https://nathancummings.org/
Source tier: primary
Source content: "We are committed to changemaking, not just grantmaking."; totality-of-assets approach spans "grant funding, program-related investments, and our endowment" plus voice via "proxy voting, strategic communications, and cross-sector partnerships".
Comparison: Phrase verbatim; the multi-instrument description matches the totality-of-assets framing.
Decision: primary-sourced

## Claim 12: "Venture grants (up to $100,000, one year)… Enterprise grants ($250,000 and above, multi-year, by invitation only)" (also scalar:focus, scalar:sources[4].note)

Source: https://nathancummings.org/faq/
Source tier: primary
Source content: "up to $100k for one year" (Venture); "$250k+ annually for more than two years" multi-year, unrestricted, invitation-only (Enterprise).
Comparison: Venture and Enterprise tier amounts, durations, and invitation-only status match the FAQ.
Decision: primary-sourced

## Claim 13: "Advancement grants (up to $250,000, up to two years)" (also scalar:focus "Advancement grants up to $250,000 over two years", scalar:sources[4].note)

Source: https://nathancummings.org/faq/
Source tier: primary
Source content: "Up to $250k annually for up to two years"
Comparison: The FAQ's ceiling is $250k *annually* for up to two years (i.e., up to $500k total); body and both scalars state "up to $250,000 over two years", understating the tier. Single correct replacement: "up to $250,000 annually for up to two years". Fix locations: body § REEJ mandate, scalar:focus, scalar:sources[4].note.
Decision: correction

## Claim 14: "PRIs — typically $250,000 to $750,000 in low-interest loans repaid within 3–7 years"

Source: https://nathancummings.org/faq/
Source tier: primary
Source content: "most PRIs will range from $250,000 to $750,000, typically to be repaid within three to seven years."
Comparison: Range and repayment period match; "low-interest" matches the FAQ's low-cost-financing framing of PRIs.
Decision: primary-sourced

## Claim 15: "FY2026 grantmaking budget is approximately $15 million, with a PRI budget of approximately $4 million" (also scalar:focus "$15–17 million" grants / "$3–4 million" PRIs, scalar:sources[4].note)

Source: https://nathancummings.org/faq/
Source tier: primary
Source content: "NCF's grant-making budget is $15 million for FY 2026."; "Our budget for funding program-related investments (PRIs) in 2026 is approximately $4 million."
Comparison: Body figures match the FAQ exactly. The scalar:focus ranges ($15–17M, $3–4M) are hedged approximations whose confirmed endpoints ($15M, $4M) match; the upper/lower bounds are not separately sourced but do not contradict.
Decision: primary-sourced

## Claim 16: "board designated commitment of 5% of endowment ($22 million) for PRIs"

Source: https://nathancummings.org/faq/
Source tier: primary
Source content: "We have dedicated $22 million, five percent of the endowment, to be deployed for PRIs in the coming years."
Comparison: Exact match on both the percentage and the dollar figure.
Decision: primary-sourced

## Claim 17: "A US South place-based initiative receives 40% of the Foundation's assets"

Source: https://nathancummings.org/focus-area/economic-justice/ + https://nathancummings.org/our-focus/
Source tier: primary
Source content: "NCF will continue to fund nationally, but has focused 40% of our assets on work in or focused on the U.S. South."; "NCF has committed to bringing 40% of our assets — both financial and non-financial — to advance REEJ solutions across the U.S. South".
Comparison: The 40%-of-assets US South commitment matches on both pages.
Decision: primary-sourced

## Claim 18: first economic-justice sub-strategy prioritises worker power and fair compensation, affordable housing, and employee ownership / alternative ownership models

Source: https://nathancummings.org/focus-area/economic-justice/
Source tier: primary
Source content: "Increases workers' power and their ability to negotiate for fair pay and good benefits"; "Addresses the high cost of housing for renters and/or homeowners"; "Expands the uptake of employee ownership and other forms of alternative ownership structures".
Comparison: All three components of the fostering-economic-security sub-strategy match.
Decision: primary-sourced

## Claim 19: "Documented grantees in this cluster include the Coalition of Immokalee Workers, the National Domestic Workers Alliance, ROC United, the Workers Defense Project, the National Day Laborer Organizing Network, and Jobs with Justice"

Source: https://www.insidephilanthropy.com/find-a-grant/grants-c/nathan-cummings-foundation (403; via search record)
Source tier: mainstream
Source content: Search record: "The Coalition of Immokalee Workers is listed as a past grantee of the Nathan Cummings Foundation's Economic Justice program"; "The NDWA is listed among grantees supported by Nathan Cummings in the labor and workers' rights space." The remaining four organizations were not confirmed as NCF grantees in any canonical source reached this session.
Comparison: Two of six named grantees confirmed via Inside Philanthropy coverage (site 403s; snippets only); ROC United, Workers Defense Project, NDLON, and Jobs with Justice unconfirmed. Partial confirmation of a six-part list — not an error finding.
Decision: uncorroborated

## Claim 20: second sub-strategy "increasing access to capital — targets historically excluded entrepreneurs, particularly BIPOC and women founders, seeking to expand the capital controlled by people of colour"

Source: https://nathancummings.org/focus-area/economic-justice/
Source tier: primary
Source content: "Increases capital controlled and allocated by women and people of color"; "Expands Black, Indigenous, and other people of color's ability to secure competitively priced private and public capital".
Comparison: Matches the access-to-capital sub-strategy as stated.
Decision: primary-sourced

## Claim 21: third sub-strategy combats monopoly power via antitrust enforcement, targeting concentration in energy, agriculture, healthcare, and retail

Source: https://nathancummings.org/focus-area/economic-justice/
Source tier: primary
Source content: "Increases competition in key industries (i.e., energy, agriculture, healthcare, and retail)" with regulatory enforcement and antitrust named as the primary approach.
Comparison: The four named sectors and the antitrust-enforcement framing match.
Decision: primary-sourced

## Claim 22: NCF "challenges the consumer welfare standard that has narrowed US antitrust doctrine since the 1970s" (also scalar:sources[2].note "challenging the consumer welfare standard")

Source: no canonical source found
Source tier: none
Source content: The cited economic-justice page contains no mention of the consumer welfare standard (page fetched; extraction confirms absence). A targeted search for "Nathan Cummings Foundation consumer welfare standard" returned no NCF source connecting the foundation to that position.
Comparison: The claim attributes a specific doctrinal position to NCF that its cited page does not carry and no canonical source reached this session supports. Not a contradiction — the anti-monopoly work is confirmed (Claim 21) — but this specific framing is unsupported. scalar:sources[2].note carries the same unsupported attribution.
Decision: uncorroborated

## Claim 23: "The technology-specific dimension of the economic justice focus is named explicitly in the US South sub-strategy: NCF funds data transparency and technological interventions in the American South that undermine societal biases and structural inequities" (also scalar:sources[2].note)

Source: https://nathancummings.org/focus-area/racial-justice/
Source tier: primary
Source content: Racial-justice page: "In 2026, we are particularly interested in in data transparency and technological interventions in the U.S. South that undermine societal biases and structural inequities." — under the "Combats Racism + Oppression" strategy of the racial justice focus area. Economic-justice page (the cited source): "No references to 'data transparency,' 'technological interventions,' or similar concepts appear in this content."
Comparison: The quoted language is real and primary-confirmed, but it belongs to the *racial justice* focus area's "Combats Racism + Oppression" strategy, not the economic justice focus's US South sub-strategy as the body and scalar:sources[2].note assert, and the body's citation links the wrong page. Single correct replacement: attribute the framing (a stated 2026 interest) to the racial-justice focus area and re-point the citation to /focus-area/racial-justice/. Fix locations: body § Economic justice, scalar:sources[2].note.
Decision: correction

## Claim 24: "ACRE — the Action Center on Race and the Economy — which works on algorithmic accountability and the intersection of racial capitalism and financial and technology systems"

Source: https://acrecampaigns.org/about/ + ACRE published reports (via search record)
Source tier: primary
Source content: About page: ACRE "directly take[s] on the financial institutions and anti-democratic actors that are responsible for pillaging communities of color and poor families". Search record: ACRE report "Driven Out By AI: How Uber Deactivations Force Drivers into Chatbot Hell and Financial Crisis"; a 2019 ACRE report on Facebook, Twitter, and Google platform algorithms.
Comparison: The finance × racial-justice characterization matches ACRE's own about page; the algorithmic-accountability strand is evidenced by ACRE's own published reports (titles surfaced via search; not fetched in full).
Decision: primary-sourced

## Claim 25: ACRE "received $200,000 from NCF in 2019"

Source: https://www.influencewatch.org/non-profit/action-center-on-race-the-economy-institute/
Source tier: caution
Source content: "the Nathan Cummings Foundation provided $200,000 in 2019 to the Action Center on Race and the Economy Institute."
Comparison: The figure appears only on InfluenceWatch (a Capital Research Center project — partisan watchdog covering subjects of its advocacy; caution tier, not canonical per mission source rules). No canonical source (NCF grant records, 990 grant schedule, Candid) reached this session confirms the amount/year. Not an error finding — sourcing strength only.
Decision: uncorroborated

## Claim 26: "filed more than 200 shareholder resolutions over fifteen years on issues ranging from climate to executive compensation, working both independently and with institutional partners" (also scalar:sources[3].note)

Source: https://nathancummings.org/shareholder-activism/
Source tier: primary
Source content: "Over the last fifteen years, NCF has filed more than 200 shareholder resolutions on issues ranging from climate change to executive compensation."; "NCF works both independently and with other investors to file shareholder resolutions".
Comparison: Count, period, issue range, and independent-plus-collaborative mode all match verbatim.
Decision: primary-sourced

## Claim 27: "In February 2026, NCF filed suit against Axon Enterprise, Inc. … seeking to prevent Axon from excluding NCF's shareholder proposal requesting disclosure of the company's political spending" (also scalar:sources[6].note "February 17, 2026")

Source: https://www.iccr.org/nathan-cummings-foundation-files-suit-to-prevent-axon-from-excluding-shareholder-proposal-on-political-spending-transparency/
Source tier: primary
Source content: "Nathan Cummings Foundation (NCF) announced earlier this week that it has filed a lawsuit against Axon Enterprise, Inc. (AXON) in the U.S. District Court for the District of Columbia."; "The proposal calls for AXON to publish a report detailing how it determines when and where corporate funds are used to support or oppose political candidates or influence elections."
Comparison: February 2026 filing, defendant, and proposal subject match (ICCR announcement of its member NCF's suit). The scalar's specific "February 17, 2026" date was not confirmed on the page but is not contradicted.
Decision: primary-sourced

## Claim 28: "the SEC's November 2025 decision to stop reviewing no-action requests … making litigation newly necessary"

Source: https://www.iccr.org/nathan-cummings-foundation-files-suit-to-prevent-axon-from-excluding-shareholder-proposal-on-political-spending-transparency/
Source tier: primary
Source content: "In November 2025, the Securities and Exchange Commission (SEC) announced that it would no longer review company requests to exclude shareholder proposals."
Comparison: The November 2025 SEC change and its role in making litigation the remaining avenue match.
Decision: primary-sourced

## Claim 29: "Axon had invoked the SEC 'ordinary business' and 'micromanagement' exclusion rationales to block the proposal" (also scalar:sources[6].note)

Source: https://www.iccr.org/nathan-cummings-foundation-files-suit-to-prevent-axon-from-excluding-shareholder-proposal-on-political-spending-transparency/
Source tier: primary
Source content: "AXON recently notified the Securities and Exchange Commission (SEC) of its intent to exclude the proposal, asserting that it constitutes 'micromanagement.'"
Comparison: The source confirms "micromanagement" only; "ordinary business" is not named on the page (micromanagement is a prong of the ordinary-business exclusion under SEC Rule 14a-8(i)(7), so the pairing may be accurate, but as stated it is only partially confirmed). Not a contradiction.
Decision: uncorroborated

## Claim 30: "The litigation was settled with Axon agreeing to broad and detailed annual disclosure and transparency on its direct political spending" (also scalar:sources[7].note)

Source: https://www.iccr.org/iccr-and-the-nathan-cummings-foundation-joint-statement-following-the-settlement-of-the-axon-lawsuit/
Source tier: primary
Source content: Joint NCF/ICCR statement (March 11, 2026): Axon committed to "broad and detailed annual disclosure and transparency on its direct political spending."
Comparison: Settlement outcome matches the joint statement verbatim (NCF is a co-author of the statement — party-primary).
Decision: primary-sourced

## Claim 31: "Axon Enterprise, Inc. — the policing-technology firm that manufactures Tasers and AI-enabled body cameras"

Source: https://en.wikipedia.org/wiki/Axon_Enterprise + business press (Benzinga, via search record)
Source tier: tiebreaker
Source content: "Axon is a public-safety technology company best known for TASER conducted energy devices and for the body-worn camera … products"; "Axon Enterprise: From TASER To AI-Powered Public Safety Platform" — product suite spans TASER 7/10, Axon Body 4 cameras, AI-powered report writing (Draft One).
Comparison: Tasers, body cameras, and the AI layer are confirmed by Wikipedia plus business-press coverage — definitional facts about a named company, consistently reported.
Decision: corroborated

## Claim 32: "In 2024, the Foundation joined the Ford Foundation and Omidyar Network in purchasing … shares of Anthropic … from assets sold in the FTX bankruptcy proceedings"

Source: https://omidyar.com/update/omidyar-network-purchases-shares-of-anthropic/ + https://impactalpha.com/with-stakes-in-anthropic-impact-investors-seek-a-seat-at-the-ai-table/ (403; via search record)
Source tier: primary
Source content: Omidyar (April 1, 2024): purchasers were "Omidyar Network, Ford Foundation, and Nathan Cummings Foundation"; shares "were made available for sale as part of FTX's bankruptcy proceedings". ImpactAlpha: "Ford Foundation, Omidyar Network and Nathan Cummings Foundation invested … acquired at auction from FTX Trading."
Comparison: The three co-purchasers, the 2024 date, and the FTX-bankruptcy provenance match across a party-primary announcement and specialist press.
Decision: corroborated

## Claim 33: "purchasing approximately 250,000 shares of Anthropic at approximately $1 million" (also scalar:sources[8].note "~$1 million, approximately 250,000 shares from FTX bankruptcy proceedings")

Source: https://impactalpha.com/with-stakes-in-anthropic-impact-investors-seek-a-seat-at-the-ai-table/ (403; via search record) + https://omidyar.com/update/omidyar-network-purchases-shares-of-anthropic/
Source tier: primary
Source content: ImpactAlpha (the cited source): "Ford Foundation, Omidyar Network and Nathan Cummings Foundation invested a combined $7.5 million for just under 250,000 shares of Anthropic" — Ford $5M, Omidyar $1.5M, NCF $1M. Omidyar's own announcement: "just under 50,000 shares of Anthropic stock" (April 1, 2024).
Comparison: Per its own cited source, the ~250,000 shares correspond to the trio's combined $7.5 million purchase, not to NCF's ~$1 million portion — the body/scalar pairing of "250,000 shares" with "$1 million" misstates the source under either share count. Single correct replacement: NCF contributed ~$1 million to the combined $7.5 million purchase. (Residual conflict: ImpactAlpha says just under 250,000 combined shares, Omidyar's April 2024 primary announcement says just under 50,000 — possibly different tranches/cumulative counts; the exact count should not be asserted without resolving this.) Fix locations: body § Technology-accountability thread, scalar:sources[8].note.
Decision: correction

## Claim 34: co-investment amounts — "the Ford Foundation ($5 million) and Omidyar Network ($1.5 million)" (scalar:sources[8].note)

Source: https://impactalpha.com/with-stakes-in-anthropic-impact-investors-seek-a-seat-at-the-ai-table/ (403; via search record)
Source tier: mainstream
Source content: "The Ford Foundation committed $5 million, Omidyar Network $1.5 million and the Nathan Cummings Foundation $1 million".
Comparison: The per-foundation amounts match ImpactAlpha; Omidyar's own announcement does not break out individual amounts, so this rests on one specialist outlet.
Decision: single-source

## Claim 35: "the three foundations together sought a seat at the AI table as investors committed to transparency, accountability, and safety"

Source: https://impactalpha.com/with-stakes-in-anthropic-impact-investors-seek-a-seat-at-the-ai-table/ (403; via search record) + https://omidyar.com/update/omidyar-network-purchases-shares-of-anthropic/
Source tier: primary
Source content: ImpactAlpha: "The trio saw an opportunity to influence conversations around governance, safety, transparency and the broader public interest implications of AI"; ensuring foundations had "a seat at the table". Omidyar: "investing in generative AI that protects and promotes the public interest", mission-aligned investors positioned to "protect and reinforce the safety and other mission-driven priorities of Anthropic's work".
Comparison: The seat-at-the-table framing and the transparency/safety/public-interest rationale match both sources.
Decision: corroborated

## Claim 36: the foundations were "prepared to exit if Anthropic failed to live up to its stated values"

Source: no canonical source found
Source tier: none
Source content: Neither the Omidyar announcement (fetched) nor the ImpactAlpha coverage reached via search records an exit/divestment commitment; ImpactAlpha's 2026 coverage instead reports NCF "stands by the company" after Anthropic's Pentagon standoff.
Comparison: The prepared-to-exit framing could not be confirmed in the sources reached this session (the cited ImpactAlpha article 403s and its full text may carry it). Not a contradiction — sourcing strength only.
Decision: uncorroborated

## Claim 37: "Rey Ramsey described NCF's rationale as believing that 'standing by values is important'" (also scalar:sources[8].note)

Source: https://impactalpha.com/with-stakes-in-anthropic-impact-investors-seek-a-seat-at-the-ai-table/ (403; via search record)
Source tier: mainstream
Source content: "Rey Ramsey … told ImpactAlpha: 'We understand that all AI companies will continue to navigate complexities that present them with choices, but we believe standing by values is important.'"
Comparison: The quoted phrase matches Ramsey's statement to ImpactAlpha verbatim, in the navigating-complexities context the body describes. Living-person quote resting on one specialist outlet with editorial standards.
Decision: single-source

## Claim 38: "The Foundation made the decision approximately in 2018 to transition its endowment to 100% mission-aligned investing — documented in its 2021 'Values Proposition' report" (also scalar:sources[9].note)

Source: https://nathancummings.org/nathan-cummings-foundation-reveals-results-from-transition-to-100-mission-aligned-investing/ + https://www.alliancemagazine.org/blog/nathan-cummings-foundation-commits-100-endowment-mission-aligned-investing/ (via search record)
Source tier: primary
Source content: NCF release (May 13, 2021): the foundation "made the decision three years ago" (= 2018); report titled "Values Proposition: How and Why We Transformed Our Investment Model to Align Our Capital with Our Mission". Search record: "This decision was made in 2018", the largest foundation to commit its entire portfolio.
Comparison: 2018 decision year, 2021 report, and report name all match across NCF's own release and sector press.
Decision: corroborated

## Claim 39: "By 2024, 94.5% of assets were described as mission-aligned"

Source: https://www.insidephilanthropy.com/find-a-grant/grants-c/nathan-cummings-foundation (403; via search record)
Source tier: mainstream
Source content: Search record: "In 2024, the Nathan Cummings Foundation reported $463 million in endowment assets, with 94.5% described as mission-aligned".
Comparison: The 94.5%-in-2024 figure matches sector-press reporting reached via search snippets (the cited Inside Philanthropy page 403s). One non-primary canonical source.
Decision: single-source

## Claim 40: findings — "mission-alignment does not require sacrificing financial returns … likely enhances them by mitigating systemic risk … diverse investment professionals face marketplace disadvantages due to shorter track records … few [impact investors] apply racial, economic, or environmental justice criteria in selecting fund managers" (also scalar:sources[9].note)

Source: https://nathancummings.org/nathan-cummings-foundation-reveals-results-from-transition-to-100-mission-aligned-investing/
Source tier: primary
Source content: "Aligning investments with mission does not require sacrificing financial returns. In fact, it likely enhances financial returns, while helping to mitigate risk."; "Diverse investment professionals face significant disadvantages in the marketplace, often because they don't have as lengthy a track record as white peers."; "Even among impact investors, too few OCIOs factor racial, economic, or environmental justice into their investing approach."
Comparison: All three findings match the foundation's own report announcement verbatim.
Decision: primary-sourced
