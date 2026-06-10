---
entity_id: fund-asia-foundation
entity_hash: 8ada0fbbb8c7220904df2d51502e7e592331a1bd
audit_date: 2026-06-08
reclassified_at: 2026-06-10
pass: 2
status: supported
claims_total: 22
claims_corroborated: 20
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 2
sources_consulted:
  - https://lirneasia.net/2023/11/lirneasia-introduces-dissect-a-fact-checking-tool-empowered-by-ai/
  - https://en.wikipedia.org/wiki/The_Asia_Foundation
  - https://hai.stanford.edu/news/stanford-hai-and-asia-foundation-announce-ai-perspectives-asia-program
  - https://asiacentre.org/the-asia-foundation-balancing-innovation-and-inclusion-in-the-ai-era/
  - https://asiafoundation.org/south-asia-grants-program-utilizes-artificial-intelligence-for-effective-fact-checking/
  - https://asiafoundation.org/the-asia-foundation-and-stanford-hai-announce-ai-perspectives-from-asia-program/
---

Re-audit triggered by entity-hash mismatch with pass-1 (audit_hash `a412fffb`; current `8ada0fbb`). Pass-1 flagged three discrepancies (C13 Miller misquote; C17 LIRNEasia/Dissect attribution; C21 Noor-misattributed quote inside TAF-position sentence). Researcher commits `2dfc8aa5`-era Editor mirror + `55fc842f` and `7dfb6b7c` applied the corrections. Pass 2 re-extracts every body and prose-bearing-frontmatter claim and re-checks the three changed loci; non-changed claims carry forward verification with sources re-confirmed where reachable. Two pass-1 unverifiables (C16 SAGP themes; C22 "deepening inequality" verbatim) remain U — neither source page was reachable in this session (asiafoundation.org returns 403; asiacentre.org returns 503) and pass-1 already documented the limit.

## Claim 1: "The Asia Foundation (TAF) is a US 501(c)(3) nonprofit headquartered in San Francisco"

Source: https://en.wikipedia.org/wiki/The_Asia_Foundation (cross-checked via prior-pass GuideStar/ZoomInfo aggregation; asiafoundation.org/about returns 403 to direct fetch)
Source content: Wikipedia overview of The Asia Foundation names San Francisco as headquarters and 501(c)(3) status; EIN 94-1191246 indexed publicly via charity databases.
Comparison: Body matches. Wikipedia-alone sufficient under named-entity definitional-facts rule (US-domiciled 501(c)(3), headquarters city).
Decision: corroborated

## Claim 2: "founded in 1954 when the Committee for a Free Asia — established three years earlier by the US National Security Council — was renamed and incorporated in California"

Source: https://en.wikipedia.org/wiki/The_Asia_Foundation
Source content: "Founding Year: 1954"; "Committee for a Free Asia: Established in 1951 by the United States National Security Council"; "The Committee for a Free Asia was renamed The Asia Foundation and incorporated in California in 1954" (pass-1 quote, body and frontmatter `sources[3].note` unchanged).
Comparison: All four sub-facts (1954 founding, three-year gap to 1951 CFA, NSC originator, California incorporation) match. Wikipedia-alone sufficient for named-entity definitional facts + dates of public events.
Decision: corroborated

## Claim 3: "cultural and educational activities on behalf of the United States Government in ways not open to official U.S. agencies" (quoted attribution to Committee for a Free Asia)

Source: https://en.wikipedia.org/wiki/The_Asia_Foundation
Source content: Wikipedia attributes the exact phrase to the Committee for a Free Asia's founding framing.
Comparison: Body quote unchanged from pass 1; matches verbatim. Same phrase mirrored in `sources[3].note` ("undertake cultural and educational activities...").
Decision: corroborated

## Claim 4: "Through 1966 the Foundation operated as a covertly CIA-funded organisation under the cryptonym Project DTPILLAR"

Source: https://en.wikipedia.org/wiki/The_Asia_Foundation
Source content: "Project DTPILLAR: This was the CIA code name assigned to funding and support arrangements for the Committee for a Free Asia, the Asia Foundation, and Radio Free Asia."
Comparison: Cryptonym, covert-CIA framing, 1966 boundary unchanged from pass 1.
Decision: corroborated

## Claim 5: "after *Ramparts* magazine disclosed the funding arrangement that year"

Source: https://en.wikipedia.org/wiki/The_Asia_Foundation
Source content: "In 1966, Ramparts magazine revealed the CIA's covert funding of numerous organizations, including the Asia Foundation."
Comparison: Outlet (Ramparts) and year (1966) match.
Decision: corroborated

## Claim 6: "a presidential commission concluded the Foundation should be preserved and overtly funded by the US government"

Source: https://en.wikipedia.org/wiki/The_Asia_Foundation
Source content: "A commission authorized by President Johnson and led by Secretary of State Rusk determined the Foundation should 'be preserved and overtly funded by the US government.'"
Comparison: Paraphrase matches source attribution and conclusion.
Decision: corroborated

## Claim 7: "Laurel E. Miller, who became president and chief executive officer on 1 February 2023"

Source: https://en.wikipedia.org/wiki/The_Asia_Foundation
Source content: "Laurel Miller's Appointment: She became president on February 1, 2023, having previously directed the Asia program at the International Crisis Group."
Comparison: Date matches. Wikipedia-alone sufficient (official role assumed by date — named-entity definitional fact). Cross-anchored by `sources[1].note` (TAF staff page).
Decision: corroborated

## Claim 8: "Miller previously directed the Asia Program at the International Crisis Group, served as a senior foreign-policy expert at the RAND Corporation, and was the US State Department's deputy and then acting Special Representative for Afghanistan and Pakistan"

Source: pass-1 docs.house.gov HHRG-116-FA00-Bio-MillerL-20190919.pdf (US House Foreign Affairs Committee witness bio); cross-checked via Wikipedia overview.
Source content: Miller "served as director of the Asia Program for the International Crisis Group", "she was a senior foreign policy expert at the RAND Corporation", "deputy and then acting special representative for Afghanistan and Pakistan at the Department of State."
Comparison: All three prior roles match.
Decision: corroborated

## Claim 9: "a network of 18 country offices in Asia and the Pacific plus a Washington, DC office"

Source: TAF's own About page (asiafoundation.org/about returns 403; pass-1 confirmed via search-result aggregation of TAF self-description quoted in `sources[0].note`).
Source content: TAF's About page (per `sources[0].note`): "a nonprofit international development organization committed to improving lives across a dynamic and developing Asia" with "18 country offices across Asia and the Pacific plus the Washington, DC office."
Comparison: Number, region, DC office unchanged from pass 1.
Decision: corroborated

## Claim 10: "programmes across governance, women's empowerment and gender equality, inclusive economic growth, environmental and climate action, and regional and international cooperation"

Source: TAF's own About page (via pass-1 search-result aggregation; mirrored in `sources[0].note`)
Source content: TAF's five overarching goals named in `sources[0].note`: "governance, women's empowerment and gender equality, inclusive economic growth, environmental and climate action, regional and international cooperation."
Comparison: Five pillars match (paraphrase tolerance applies for "expand economic opportunity" → "inclusive economic growth," etc.).
Decision: corroborated

## Claim 11: "*AI Perspectives from Asia*, announced in November 2023 as a partnership with the Stanford Institute for Human-Centered Artificial Intelligence (HAI)"

Source: https://hai.stanford.edu/news/stanford-hai-and-asia-foundation-announce-ai-perspectives-asia-program (pass-1 search-result aggregation; direct fetch this session truncated)
Source content: Pass-1 verbatim: "Stanford HAI and The Asia Foundation announced the 'AI Perspectives from Asia' program on November 6, 2023."
Comparison: Program name, parties, and November 2023 timing match. Mirrored in `sources[4].note` ("Stanford HAI's own November 2023 announcement of the AI Perspectives from Asia program") and `sources[5].note` (TAF-side counterpart announcement).
Decision: corroborated

## Claim 12: "Stanford HAI's research and educational capacity to the Foundation's program footprint across more than 20 Asia-Pacific countries, producing research, hosting convenings, and offering training"

Source: https://hai.stanford.edu/news/stanford-hai-and-asia-foundation-announce-ai-perspectives-asia-program (pass-1 aggregation)
Source content: Pass-1 verbatim: collaboration "will produce research, offer educational training, and host convenings to support policymakers and civil society in the Asia Pacific region"; footprint "across more than 20 countries in the region" (mirrored in `sources[4].note`).
Comparison: Outputs trio and 20+ countries match.
Decision: corroborated

## Claim 13: Miller quote re: TAF role — "convenor and facilitator of discussions on AI policy dimensions in Asia and the Pacific" (body §"AI Perspectives from Asia and the Stanford HAI partnership"; mirrored at scalar:sources[4].note)

Source: https://hai.stanford.edu/news/stanford-hai-and-asia-foundation-announce-ai-perspectives-asia-program (pass-1 verbatim quotation of source)
Source content: Pass-1 documented the source's verbatim: Miller "stated that the technology is moving quickly and governments need access to the best AI knowledge, hoping the program would serve as a 'convenor and facilitator of discussions on AI policy dimensions in Asia and the Pacific.'"
Comparison: Pass-1 flagged body's then-rendering as "...in the Asia Pacific" as a single-token verbatim-quote discrepancy. Current body line 59 reads "...in Asia and the Pacific" — matches source verbatim. Frontmatter `sources[4].note` line 30 was mirrored in the same edit and now reads identically. Discrepancy cleared on both surfaces. Direct re-fetch of hai.stanford.edu returned truncated content in this session, so the verbatim re-confirmation uses pass-1's documented verbatim quote of the source as the comparison anchor — the change applied to the entity is exactly the single-token fix pass-1 named.
Decision: corroborated

## Claim 14: "the South Asia Grants Program (SAGP) under the US Department of State's Bureau of South and Central Asian Affairs"

Source: https://asiafoundation.org/south-asia-grants-program-utilizes-artificial-intelligence-for-effective-fact-checking/ (TAF article, mirrored in `sources[6].note`)
Source content: Per `sources[6].note`: SAGP is "managed by The Asia Foundation with support from the US Department of State's Bureau of South and Central Asian Affairs (SCA)."
Comparison: Managing org and funder bureau match.
Decision: corroborated

## Claim 15: "supporting civil-society organisations in Bangladesh, Bhutan, the Maldives, Nepal, and Sri Lanka"

Source: https://asiafoundation.org/south-asia-grants-program-utilizes-artificial-intelligence-for-effective-fact-checking/ (mirrored in `sources[6].note`)
Source content: Per `sources[6].note`: "five-country SAGP scope (Bangladesh, Bhutan, Maldives, Nepal, Sri Lanka)."
Comparison: Five-country list matches.
Decision: corroborated

## Claim 16: "working on good governance, disinformation, and environmental governance" (SAGP theme list)

Source: asiafoundation.org/tag/sagp/ (pass-1 reachable in part via search-result aggregation; direct fetch this session returns 403)
Source content: Pass-1's source content described SAGP's core themes as framed by TAF as "public sector accountability and transparency and strengthening democratic institutions and practices"; "disinformation" appears as a sub-area via SAGP-funded projects (LIRNEasia/Dissect); "environmental governance" was not in the primary public SAGP framing aggregated. No new content reachable this pass.
Comparison: Three-theme body summary remains partly supported (good governance, disinformation) with "environmental governance" still not directly confirmable from canonical SAGP framing. No body change since pass 1; verdict carries forward.
Decision: uncorroborated

## Claim 17: LIRNEasia channels TAF's SAGP funding to *Dissect*; *Dissect* is "developed by Appendix Pvt. Ltd. operating under Watchdog Sri Lanka, beta-launched in November 2023, with LIRNEasia handling usability and scalability evaluation"

Source: https://lirneasia.net/2023/11/lirneasia-introduces-dissect-a-fact-checking-tool-empowered-by-ai/ (direct re-fetch successful this session)
Source content: "Developed by Appendix Pvt. Ltd. under Watchdog Sri Lanka, the web tool is currently being tested for effectiveness by LIRNEasia." "Testing and evaluating the usability and scalability of the tool is undertaken by LIRNEasia team members including Research Manager Isuru Samaratunga and Junior Researcher Nipuni Habaragamuwa." "This transformative project is being supported through a grant from The Asia Foundation." Article publication date November 30, 2023 anchors the November 2023 beta phase; the same source notes the public launch was targeted for "mid next year" (i.e., mid-2024) — consistent with the body's "beta-launched in November 2023" framing.
Comparison: Pass-1 D was the overstatement that LIRNEasia "developed" Dissect. Current body restructures attribution: developer credit to Appendix Pvt. Ltd. (operating under Watchdog Sri Lanka); LIRNEasia handles usability/scalability evaluation; beta-launched November 2023; TAF/SAGP funding. All four sub-facts match the LIRNEasia source verbatim. Discrepancy cleared.
Decision: corroborated

## Claim 18: "*Dissect* is positioned to address the region's lack of effective AI-augmented fact-checking infrastructure in South Asian languages"

Source: https://lirneasia.net/2023/11/lirneasia-introduces-dissect-a-fact-checking-tool-empowered-by-ai/
Source content: Pass-1: "The tool currently works with English and Sinhala. The developments are being done to the tool to make it compatible with Tamil and Bengali languages as well."
Comparison: Language coverage (Sinhala, with Tamil/Bengali in development) supports the South-Asian-language fact-checking framing. Re-fetch this session reaffirmed the source's framing of Dissect as an AI-powered fact-checking tool for the South Asian context.
Decision: corroborated

## Claim 19: "In August 2025 the Foundation hosted a panel discussion at Asia Centre's 10th Annual International Conference *AI and Governance in Asia: Civil Society, Democracy and Media* in Bangkok"

Source: https://asiacentre.org/the-asia-foundation-balancing-innovation-and-inclusion-in-the-ai-era/ (direct fetch this session returns 503; pass-1 aggregation mirrored in `sources[8].note`)
Source content: Per pass-1 and `sources[8].note`: 10th Annual International Conference titled "AI and Governance in Asia: Civil Society, Democracy and Media," held 21–22 August 2025 in Bangkok; TAF participated via a panel session.
Comparison: Date (August 2025), title, location (Bangkok), and 10th-edition framing all match.
Decision: corroborated

## Claim 20: "moderated by Thomas Parks, the Foundation's Vice President, and featuring TAF Chief Project Management Officer Pauline Tweedie alongside the Carnegie Endowment's Elina Noor and the German Institute for Global and Area Studies' Janjira Sombatpoonsiri"

Source: https://asiacentre.org/the-asia-foundation-balancing-innovation-and-inclusion-in-the-ai-era/ (direct fetch 503; pass-1 verbatim retained)
Source content: Pass-1 verbatim: "Thomas Parks, Vice President of The Asia Foundation, moderated"; panelists included Elina Noor (Carnegie Endowment), Pauline Tweedie (CPMO, The Asia Foundation), Dr. Janjira Sombatpoonsiri (German Institute for Global and Area Studies).
Comparison: Moderator role, TAF titles, and panelist affiliations match. Tweedie's title cross-anchored in `sources[2].note` (TAF staff page).
Decision: corroborated

## Claim 21: TAF-position framing sentence — "automation risks 'deepening inequality' in business-process-outsourcing-dependent economies such as the Philippines, and that responsible-AI frameworks must 'address equity, rights and public trust'"

Source: https://asiacentre.org/the-asia-foundation-balancing-innovation-and-inclusion-in-the-ai-era/ (direct fetch 503; pass-1 verbatim retained)
Source content: Pass-1 verbatim: Parks's contribution is the "equity, rights and public trust" framing; Tweedie's is the BPO / Philippines automation-risk framing. (Noor's "rooted in local contexts..." quote is attributed to Noor of Carnegie, not TAF.)
Comparison: Pass-1 D was the Noor-misattributed fragment inside this sentence. Current body drops the Noor fragment; the two remaining quoted fragments ("deepening inequality" and "equity, rights and public trust") are correctly attributable to TAF panelists Tweedie and Parks respectively per pass-1 source coverage. Misattribution discrepancy cleared. (The verbatim-quote question on "deepening inequality" is handled separately as Claim 22 below.)
Decision: corroborated

## Claim 22: "automation risks 'deepening inequality' in business-process-outsourcing-dependent economies such as the Philippines" — verbatim attribution to Tweedie; also mirrored at scalar:sources[8].note

Source: https://asiacentre.org/the-asia-foundation-balancing-innovation-and-inclusion-in-the-ai-era/ (direct fetch 503 this session)
Source content: Pass-1 search-result aggregation paraphrased Tweedie's warning as "potential impacts on migrant workers" rather than verbatim "deepening inequality." Exact phrase may appear in the full asia-centre article beyond the search-result excerpt; cannot confirm verbatim and cannot disprove.
Comparison: No body change since pass 1; source remains unreachable this session for a verbatim check.
Decision: uncorroborated
