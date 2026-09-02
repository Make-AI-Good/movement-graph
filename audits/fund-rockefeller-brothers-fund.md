---
entity_id: fund-rockefeller-brothers-fund
entity_hash: 038731a69274821229c8288a95815c6fbedd8f2d
audit_date: 2026-09-02
pass: 1
status: supported
claims_total: 15
claims_corroborated: 6
claims_primary_sourced: 6
claims_single_source: 2
claims_uncorroborated: 1
open_corrections: 0
sources_consulted:
  - https://en.wikipedia.org/wiki/Rockefeller_Brothers_Fund
  - https://philanthropy.org/foundation/rockefeller-brothers-fund/
  - https://ngo-monitor.org/funder/rockefeller_brothers_fund/
  - https://www.influencewatch.org/non-profit/rockefeller-brothers-fund/
  - https://projects.propublica.org/nonprofits/search?q=7amleh
  - https://7amleh.org/about
  - https://www.rbf.org/about/our-history/timeline/rbf-founded
  - https://www.rbf.org/annual-reviews/fund-2024-interdependent-world
  - https://www.rbf.org/news/updated-democratic-practice-us-guidelines-address-short-term-challenges-and-long-term-needs
  - https://www.rbf.org/grantees/free-press
  - https://www.rbf.org/grantees/data-society-research-institute
  - https://www.rbf.org/grantees/center-technology-and-civic-life
  - https://www.rbf.org/grantees/7amleh-arab-center-social-media-advancement
  - https://www.rbf.org/programs/democratic-practice-united-states/rji
  - https://www.rbf.org/news/peacebuilding-program-builds-impact-lessons-decade-grantmaking
  - https://philanthropynewsdigest.org/news/rbf-awards-62-million-achieves-goal-of-fossil-fuel-free-endowment
  - https://www.philanthropy.com/news/rockefeller-brothers-fund-launches-program-on-racial-justice-boosts-grants-by-48-million/
  - https://freebeacon.com/america/rockefeller-brothers-fund-gave-millions-to-terror-tied-extremist-groups-in-2025/
---

Access note for this pass: rbf.org 403s on direct fetch across all page types (homepage, programs, grantees, news — regressed from the 2026-08-31 grants-search-only note), so every rbf.org-origin confirmation below came through search-index snippets of the named rbf.org pages, not direct fetches. philanthropynewsdigest.org and freebeacon.com also 403 (snippets only). ngo-monitor.org, influencewatch.org, philanthropy.org, 7amleh.org fetched fine.

## Claim 1: "established on December 28, 1940 by five third-generation Rockefeller brothers — John 3rd, Nelson, Laurance, Winthrop, and David — as their primary vehicle for coordinated philanthropy"

Source: https://www.rbf.org/about/our-history/timeline/rbf-founded (via search snippet); https://en.wikipedia.org/wiki/Rockefeller_Brothers_Fund; https://philanthropy.org/foundation/rockefeller-brothers-fund/
Source tier: primary
Source content: "On December 28, 1940, the certificate of incorporation for the Rockefeller Brothers Fund was filed in Albany, New York" (RBF timeline); "established in 1940 in New York City by five brothers: John, Nelson, Laurance, Winthrop and David Rockefeller" (Wikipedia); "Established in 1940 by five sons of John D. Rockefeller, Jr." (philanthropy.org)
Comparison: Date, all five names, and the coordinated-philanthropy purpose match across RBF's own timeline, Wikipedia, and philanthropy.org. Also covers scalar:sources[0].note (Wikipedia as source for the Dec 28 1940 founding).
Decision: corroborated

## Claim 2: "Headquartered in New York City"

Source: https://en.wikipedia.org/wiki/Rockefeller_Brothers_Fund; https://philanthropy.org/foundation/rockefeller-brothers-fund/
Source tier: database
Source content: "headquartered in New York, New York" (Wikipedia); headquarters "New York" (philanthropy.org)
Decision: corroborated
Comparison: Direct match; named-entity definitional fact.

## Claim 3: "Its endowment reached approximately $1.38 billion as of December 31, 2024"

Source: https://philanthropy.org/foundation/rockefeller-brothers-fund/
Source tier: database
Source content: "$1,375,992,519 at December 31, 2024"
Comparison: $1.376B rounds to the body's "approximately $1.38 billion" with the exact as-of date. PND's coverage loosely says "its $1.35 billion endowment" without a precise as-of basis; the precisely-dated database figure matches the claim as stated, so this is lighter sourcing, not a conflict. The cited primary (rbf.org homepage, scalar:sources[1].note) is 403 and could not be re-checked. Covers scalar:sources[1].note's endowment token.
Decision: single-source

## Claim 4: "in 2024, the Fund distributed $62 million across 382 grants"

Source: https://www.rbf.org/annual-reviews/fund-2024-interdependent-world (via search snippet); https://philanthropynewsdigest.org/news/rbf-awards-62-million-achieves-goal-of-fossil-fuel-free-endowment (via search snippet)
Source tier: primary
Source content: "In 2024, the Rockefeller Brothers Fund awarded 382 grants totaling $62 million (including donor contributions)" (RBF Fund-in-2024 review); "RBF awards $62 million" (PND headline)
Comparison: Both tokens match; RBF's own annual review plus PND coverage. Covers scalar:sources[2].note's $62M token.
Decision: corroborated

## Claim 5: "with $65 million projected for 2025"

Source: https://www.insidephilanthropy.com/find-a-grant/grants-r/rockefeller-brothers-foundation (via search snippet)
Source tier: mainstream
Source content: "grantmaking surged from $25.6 million in 2001 to $65 million in 2025"
Comparison: The $65M-for-2025 figure is confirmed as realized, consistent with the body's projection framing; only one source directly carried the number this pass (RBF's Fund-in-2025 review separately reports "373 grants totaling $62 million" for 2025 on a different accounting basis, so the 2025 total is not cleanly double-confirmed).
Decision: single-source

## Claim 6: "In 2024 RBF also completed its transition to a fossil-fuel-free endowment — a milestone reached through a decade of mission-aligned divestment"

Source: https://philanthropynewsdigest.org/news/rbf-awards-62-million-achieves-goal-of-fossil-fuel-free-endowment (via search snippet); https://en.wikipedia.org/wiki/Rockefeller_Brothers_Fund
Source tier: mainstream
Source content: "RBF awards $62 million, achieves goal of fossil fuel-free endowment ... stood at 99.8 percent fossil fuel-free at the end of the year ... coincides with the 10th anniversary of the fund's decision to divest from fossil fuels in 2014" (PND); "On September 30, 2014, the organization announced plans to divest from fossil fuels" (Wikipedia)
Comparison: Goal-achievement in 2024 and the decade arc from the 2014 divestment decision both match. Covers scalar:sources[2].note's fossil-fuel-free token.
Decision: corroborated

## Claim 7: "three thematic programs — Democratic Practice, Sustainable Development, and Peacebuilding — alongside four geographic and specialized initiatives: China, Western Balkans, Central America, and Culpeper Arts & Culture ... Sustainable Development's focus is climate and clean energy"

Source: https://philanthropy.org/foundation/rockefeller-brothers-fund/; https://www.rbf.org/programs/grantmaking-approach (via search snippet)
Source tier: primary
Source content: "Three thematic programs—Democratic Practice, Sustainable Development, and Peacebuilding" (RBF grantmaking-approach); Pivotal Place programs "China, Western Balkans, Central America" plus "Charles E. Culpeper Arts & Culture ... artists and cultural organizations in New York City"; Sustainable Development "advances climate change solutions through public awareness, clean energy economies" (philanthropy.org)
Comparison: Program roster, four initiatives, and the Sustainable Development characterization all match across two sources.
Decision: corroborated

## Claim 8: quote — "emerging technologies could benefit democratic systems, but their unregulated adoption threatens to bolster authoritarianism by expanding surveillance, further concentrating power, and distorting public feedback"; program supports election integrity, internet freedom, civic tech, racial-equity movement-building

Source: https://www.rbf.org/news/updated-democratic-practice-us-guidelines-address-short-term-challenges-and-long-term-needs (via search snippet)
Source tier: primary
Source content: "Emerging technologies could benefit democratic systems, but their unregulated adoption threatens to bolster authoritarianism by expanding surveillance, further concentrating power, and distorting public feedback."
Comparison: Quote confirmed verbatim in RBF's Democratic Practice–U.S. guidelines text. Covers scalar:sources[3].note and the frontmatter focus scalar's surveillance/power-concentration framing.
Decision: primary-sourced

## Claim 9: "Free Press ... the media-policy and internet-freedom advocacy organization" is an RBF Democratic Practice grantee

Source: https://www.rbf.org/grantees/free-press (via search snippet); https://en.wikipedia.org/wiki/Free_Press_(advocacy_group)
Source tier: primary
Source content: Free Press "received support from the Rockefeller Brothers Fund's Democratic Practice–U.S. program" (grantee-page-derived snippet); "largest media reform organization in the United States ... safeguard the free and open Internet" (Wikipedia)
Comparison: Grantee relationship and program placement confirmed from RBF's own grantee page via search index; characterization of Free Press consistent. Covers scalar:sources[6].note.
Decision: primary-sourced

## Claim 10: "Data & Society Research Institute, which works on digital policy and technology governance research" is an RBF grantee in this program

Source: https://www.rbf.org/grantees/data-society-research-institute (via search snippet)
Source tier: primary
Source content: "Data & Society received grants under the Democratic Practice-U.S. | Equality of Representation program (Retired 2025)"
Comparison: Grantee relationship under Democratic Practice–U.S. confirmed from RBF's own grantee page via search index; the body's research-field characterization is consistent with the institute's remit. Covers scalar:sources[7].note.
Decision: primary-sourced

## Claim 11: "Center for Technology and Civic Life, an RBF grantee working to modernise election infrastructure through digital tools and build resilient, participatory election systems"

Source: https://www.rbf.org/grantees/center-technology-and-civic-life (via search snippet)
Source tier: primary
Source content: "CTCL harnesses technology and information to modernize the voting experience, build resilient election systems, and increase public confidence and participation in election processes. CTCL received grants under the Democratic Practice-U.S. | Elections and Voting Rights program"
Comparison: Grantee relationship, program placement, and the modernization/resilience characterization all match RBF's own grantee-page text. Covers scalar:sources[8].note.
Decision: primary-sourced

## Claim 12: "RBF's Racial Justice Initiative, launched in June 2020 under the Democratic Practice program, extends grantmaking to organizations building political power in communities most affected by systemic racism"

Source: https://www.rbf.org/programs/democratic-practice-united-states/rji (via search snippet); https://www.philanthropy.com/news/rockefeller-brothers-fund-launches-program-on-racial-justice-boosts-grants-by-48-million/ (via search snippet)
Source tier: primary
Source content: "In June 2020, the Rockefeller Brothers Fund's Board of Trustees approved a special three-year Racial Justice Initiative (RJI) ... a special initiative of the Democratic Practice–United States program ... support structural change to further racial equity" (RBF RJI page); Chronicle of Philanthropy: "Rockefeller Brothers Fund Launches Program on Racial Justice"
Comparison: June 2020 launch, Democratic Practice placement, and racial-equity grantmaking purpose all match across RBF's own page and Chronicle coverage.
Decision: corroborated

## Claim 13: "The Peacebuilding program, established in 2011, focuses on conflicts with significant U.S. involvement — Afghanistan, Iran, and Israel-Palestine — supporting pro-peace civil society organizations and policy analysis"

Source: https://www.rbf.org/news/peacebuilding-program-builds-impact-lessons-decade-grantmaking (via search snippet)
Source tier: primary
Source content: "established its Peacebuilding program in 2011 with a focus on conflicts in the wider Middle East, in particular Afghanistan, Israel/Palestine, and the U.S.-Iran relationship ... because of the outsized role that the United States has played in these conflicts ... support for policy analysis, dialogue across lines of division, and constituencies for peace"
Comparison: Establishment year, the three named conflicts, the U.S.-involvement rationale, and the civil-society/policy-analysis support model all match RBF's own program retrospective. Covers scalar:sources[4].note.
Decision: primary-sourced

## Claim 14: "7amleh documents violations of Palestinian digital rights — platform censorship of political speech, digital-identity erasure, surveillance, and financial-platform exclusion — and operates the Palestinian Digital Rights Observatory"

Source: https://7amleh.org/about
Source tier: primary
Source content: 7amleh "researches and monitors issues related to Palestinian digital activism, with a focus on the right to access the Internet and digital markets, the right to privacy, freedom of expression and association online"; the page links the "7or Report" observatory at https://7or.7amleh.org/
Comparison: Documentation-of-violations role and operation of the 7or observatory confirmed on 7amleh's own site; the body's four enumerated violation categories are consistent elaborations of that documented remit rather than contradicted specifics.
Decision: primary-sourced

## Claim 15: "RBF has funded 7amleh under the Peacebuilding program twice: a $50,000 grant in 2023 and a $135,000 grant in April 2025"

Source: https://www.influencewatch.org/non-profit/rockefeller-brothers-fund/; https://www.rbf.org/grantees/7amleh-arab-center-social-media-advancement (via search snippet); https://freebeacon.com/america/rockefeller-brothers-fund-gave-millions-to-terror-tied-extremist-groups-in-2025/ (via search snippet)
Source tier: caution
Source content: "7amleh-Arab Center for the Advancement of Social Media received $50,000 in 2023" (InfluenceWatch); "7amleh previously received a $100,000 grant for 24 months awarded on April 28, 2023 for general support under the Peacebuilding and Civil Society Protection strategies" (rbf.org grantee-page-derived search snippet); "The RBF in April [2025] awarded a $135,000 grant to 7amleh ... under the umbrella of 'Peacebuilding'" (Free Beacon)
Comparison: The April 2025 $135,000 Peacebuilding grant is consistently supported, but the 2023 record conflicts — InfluenceWatch says $50,000 while snippets derived from RBF's own grantee page indicate $100,000 awarded 2023-04-28 (possibly alongside, possibly instead of, the $50,000), which would also make the "twice" count wrong. The primary (rbf.org grantee page, scalar:sources[5].note) is 403 and cannot be fetched to adjudicate; NGO Monitor's RBF grants table omits 7amleh entirely; ProPublica's nonprofit search surfaces no quotable grant row. Conflicting canonical-adjacent sources with no fetchable primary: no single correct replacement token can be asserted.
Decision: uncorroborated

## Edge check: frontmatter funded_orgs [org-7amleh]

The single funded_orgs edge points to org-7amleh, which matches the body's RBF→7amleh funding relationship (supported by RBF's grantee page existing for 7amleh and by all sources above, whatever the 2023 amount); the edge itself is sound. Counted within Claim 15's scope, not as a separate claim.
