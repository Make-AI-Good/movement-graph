---
entity_id: fund-global-fund-for-women
entity_hash: 20a4c4e2342c420cf2fada62e76a5a0d894ddab6
audit_date: 2026-09-01
pass: 1
status: corrections-pending
claims_total: 28
claims_corroborated: 6
claims_primary_sourced: 9
claims_single_source: 5
claims_uncorroborated: 6
open_corrections: 2
sources_consulted:
  - https://en.wikipedia.org/wiki/Global_Fund_for_Women
  - https://www.globalfundforwomen.org/who-we-are/vision-mission/
  - https://www.globalfundforwomen.org/latest/article/peiyao-chen-new-president-ceo-of-global-fund-for-women/
  - https://www.globalfundforwomen.org/who-we-are/team/
  - https://www.globalfundforwomen.org/who-we-are/
  - https://www.globalfundforwomen.org/about/mission-history/
  - https://www.globalfundforwomen.org/initiatives/
  - https://www.journey.awdf.org/
  - https://www.learningtogive.org/resources/global-fund-women
  - https://www.ted.com/speakers/kavita_ramdas
  - https://en.wikipedia.org/wiki/Anne_Firth_Murray
  - https://www.unwomen.org/en/news/stories/2014/11/ignite-press-release
  - https://www.synergos.org/news-and-insights/2006/global-fund-women-reshaping-philanthropy-along-feminist-lines
  - https://ignite.globalfundforwomen.org/technologyfund
  - https://www.globalfundforwomen.org/initiatives/technologyinitiative/
  - https://en.wikipedia.org/wiki/Mama_Cash
  - https://www.mamacash.org/en/the-community-committee
  - https://numun.fund/grants/
  - https://en.wikipedia.org/wiki/African_Women%27s_Development_Fund
  - https://www.ohchr.org/en/instruments-mechanisms/instruments/convention-rights-child
  - https://inwellecentre.org/
---

## Claim 1: "founded in 1987 in Palo Alto, California by Anne Firth Murray, Frances Kissling, Laura Lederer, and Nita Barrow, now headquartered in San Francisco"

Source: https://www.globalfundforwomen.org/who-we-are/vision-mission/
Source tier: primary
Source content: "Global Fund for Women was founded in 1987 in Palo Alto, California, by four bold women: Anne Firth Murray, Frances Kissling, Laura Lederer, and Nita Barrow." Wikipedia: "It was founded in 1987" and is "headquartered in San Francisco, California."
Comparison: Founding year, place, all four founders, and current HQ match the org's own page plus Wikipedia. Also covers the same claim in the `focus` scalar.
Decision: corroborated

## Claim 2: mission quote — "bold, ambitious, and expansive gender justice movements to create meaningful change that will last beyond our lifetimes"

Source: https://www.globalfundforwomen.org/who-we-are/vision-mission/
Source tier: primary
Source content: "We fund bold, ambitious, and expansive gender justice movements to create meaningful change that will last beyond our lifetimes."
Comparison: Verbatim match on the org's own mission page.
Decision: primary-sourced

## Claim 3: "awarded its first grants in 1988 to eight grantees totalling $31,000"

Source: https://en.wikipedia.org/wiki/Global_Fund_for_Women
Source tier: tiebreaker
Source content: "The Global Fund for Women awarded the organization's first grants in 1988 to eight grantees totaling $31,000."
Comparison: Wikipedia states the claim verbatim, but the dollar amount is a financial specific — tiebreaker-only per the source rule — and no second canonical source was found; GFW's own mission-history page carries no first-grant detail.
Decision: uncorroborated

## Claim 4: "over $100 million to more than 4,000 organisations in more than 170 countries"

Source: https://www.globalfundforwomen.org/who-we-are/
Source tier: primary
Source content: "Over the past 40 years, we have awarded $263 million to 5,800+ organizations in 180 countries." Wikipedia: "the foundation has awarded over $100 million in grants to over 4,000 organizations supporting progressive women's rights in over 170 countries."
Comparison: Wikipedia states the figures verbatim; GFW's own current totals ($263M / 5,800+ / 180) entail every "more than" claim. Figures are dated but literally true. Also covers the `focus` scalar.
Decision: corroborated

## Claim 5: "approximately $15.5 million in annual grants"

Source: https://www.learningtogive.org/resources/global-fund-women
Source tier: none
Source content: Cited source now states: "the Global Fund for Women awarded $6,958,217.73 in grants in 82 countries" (2015). Search-surfaced recent figures: 2024 Form 990 ~$13.7M in grants; 2025 annual report ~$12M.
Comparison: The cited source no longer carries $15.5M and no canonical source found states it; recent primary figures are lower and year-dependent, so no single correct replacement exists. Also appears in the `focus` scalar and `sources[6].note` (learningtogive note). Likely stale — flagged for the team via this record, but not a single-token correction.
Decision: uncorroborated

## Claim 6: "current President and CEO is PeiYao Chen, who has a ten-year tenure with the organisation and previously served as Senior Vice President of Global Operations"

Source: https://www.globalfundforwomen.org/latest/article/peiyao-chen-new-president-ceo-of-global-fund-for-women/
Source tier: primary
Source content: "PeiYao has a ten-year tenure in leadership roles at Global Fund for Women, including in her most recent role as the Senior Vice President of Global Operations"; team page: "PeiYao Chen became President and CEO of Global Fund for Women in January 2024."
Comparison: Matches; still current per the org's team page fetched this session. Both sources are the org's own (not independent), hence primary-sourced rather than corroborated.
Decision: primary-sourced

## Claim 7: "Board Co-Chairs are Caroline Barlerin and Dayna Ash"

Source: https://www.globalfundforwomen.org/who-we-are/team/
Source tier: primary
Source content: Team page lists "Board Co-Chairs: Caroline Barlerin, Dayna Ash."
Comparison: Matches; current as of this session's fetch. Also covers `sources[3].note`.
Decision: primary-sourced

## Claim 8: "founding president Anne Firth Murray (1986–1996)"

Source: https://en.wikipedia.org/wiki/Anne_Firth_Murray
Source tier: primary
Source content: "She founded the organization in 1987 and continued to act as president until 1996." GFW's own page: "founded in 1987 in Palo Alto"; GFW Wikipedia: "It was founded in 1987 … In September 1996, Murray retired."
Comparison: The body's tenure-start token 1986 contradicts every source — the org's own pages and both Wikipedia articles date the founding and her presidency from 1987. Single correct replacement: 1986 → 1987. Fix in two locations: body ("(1986–1996)") and scalar:sources[1].note (which misattributes "Anne Firth Murray 1986–1996" to Wikipedia — Wikipedia does not say 1986).
Decision: correction

## Claim 9: "Kavita Ramdas (1996–2010)"

Source: https://en.wikipedia.org/wiki/Global_Fund_for_Women
Source tier: tiebreaker
Source content: "succeeded by Kavita N. Ramdas" (1996); "Ramdas ended her 14-year tenure at the Global Fund in September 2010."
Comparison: Wikipedia states the span directly; TED's speaker bio is consistent ("more than 22 years" org history, assets "more than tripled" under her) but gives no tenure years, so no independent direct confirmation fetched.
Decision: single-source

## Claim 10: "who grew assets from $6 million to $21 million" (Ramdas)

Source: no canonical source found
Source tier: none
Source content: TED speaker bio: "Since Ramdas took the reins, the fund's assets have more than tripled." Wikipedia (the body's cited source for this): no asset figures present.
Comparison: The body attributes the $6M/$21M figures to Wikipedia, which does not carry them; the strongest fetched source says only "more than tripled" — directionally consistent but not confirming the specific tokens.
Decision: uncorroborated

## Claim 11: "Latanya Mapp Frett (2019–2023)"

Source: https://en.wikipedia.org/wiki/Global_Fund_for_Women
Source tier: primary
Source content: Wikipedia: "appointed president and CEO of the Global Fund for Women in June 2019, a role she held through the end of 2023." GFW's PeiYao Chen announcement (primary) corroborates the end point: Chen became CEO January 1, 2024, having served "as Interim CEO during Mapp Frett's sabbatical in 2022."
Comparison: Wikipedia carries the full span directly; the org's own announcement confirms the 2023/2024 transition but not the 2019 start, so one direct source overall.
Decision: single-source

## Claim 12: "provided the USD 5,000 proposal-development grant that allowed the African Women's Development Fund founders to develop their founding proposal in 1994"

Source: https://www.journey.awdf.org/
Source tier: primary
Source content: "A USD 5,000 grant to write a proposal offered by the Global Fund for Women." The timeline places this in the 1994 Dakar (Beijing-preparatory) period.
Comparison: Amount and purpose match verbatim on AWDF's own timeline; the 1994 date is by timeline placement rather than an explicit dated line. Also covers `sources[7].note`.
Decision: primary-sourced

## Claim 13: "conceived by Anne Firth Murray while she worked at the Hewlett Foundation"

Source: https://www.synergos.org/news-and-insights/2006/global-fund-women-reshaping-philanthropy-along-feminist-lines
Source tier: mainstream
Source content: Via search snippet: Murray "was then director of environment and international population programs at the William and Flora Hewlett Foundation when she founded the organization." Murray's Wikipedia: she "led philanthropic efforts on population and environmental issues for the William and Flora Hewlett Foundation from 1978 to 1987."
Comparison: Synergos states it directly; the Wikipedia timeline (Hewlett until 1987, GFW founded 1987) is consistent. One direct non-primary source.
Decision: single-source

## Claim 14: "receives approximately 2,700 proposals annually and selects roughly 400 for funding" via an advisory council

Source: https://www.learningtogive.org/resources/global-fund-women
Source tier: database
Source content: "receives roughly 2,700 grant proposals each year"; "The staff of the Global Fund for Women work with an advisory council to select about 400 of the proposal ideas for funding."
Comparison: Matches the cited source's current text, including the advisory-council mechanism.
Decision: single-source

## Claim 15: "typical grants of $5,000 to $50,000 and first-time grants typically in the $5,000–$13,000 range"

Source: https://www.learningtogive.org/resources/global-fund-women
Source tier: none
Source content: Cited source now states: "The grants are usually between $500 and $20,000 and are intended to be spent within one year." Inside Philanthropy (search snippet): "Grants generally range from $10,000 to $50,000."
Comparison: The cited source's current text contradicts the body's ranges, and available canonical sources disagree with each other — no winner picked. Also appears in the `focus` scalar and `sources[6].note`.
Decision: uncorroborated

## Claim 16: "funds its annual grantmaking through individual, foundation, and corporate contributions" rather than an endowment

Source: https://www.learningtogive.org/resources/global-fund-women
Source tier: database
Source content: "the Global Fund for Women relies on the contributions of individuals, foundations, and corporations to meet its annual budget."
Comparison: Matches directly.
Decision: single-source

## Claim 17: Technology Initiative is "one of its nine named strategic initiatives"

Source: https://www.globalfundforwomen.org/initiatives/
Source tier: primary
Source content: The initiatives index lists exactly nine named initiatives (Adolescent Girls Fund, Collective Impact Partnership, AmplifyChange, Ending Gender-Based Violence in the Garment Industry, FLOW, A Framework of Hope, Seeds of Change, Roots Lab, Technology Initiative).
Comparison: Count and membership match. Note: the cited detail page /initiatives/technologyinitiative/ now 404s on direct fetch though still live in search indexes.
Decision: primary-sourced

## Claim 18: Technology Initiative aims — ending the gender technology gap, empowering women to create technology solutions, access and control of technology, framed as a human rights issue

Source: https://www.globalfundforwomen.org/initiatives/technologyinitiative/
Source tier: primary
Source content: Via search snippets of GFW's own content: the initiative "aims to help end the gender technology gap and empower women and girls to create innovative solutions to advance equality"; "Access to technology, control of it, and the ability to create and shape it, is a fundamental issue of women's human rights."
Comparison: The goals and human-rights framing match GFW's own initiative copy (reachable only via snippets; page 404s on direct fetch).
Decision: primary-sourced

## Claim 19: "technology-facilitated gender-based violence (TFGBV) dimension … is a named component of the mandate"

Source: no canonical source found
Source tier: none
Source content: The initiative detail page 404s; retrieved snippets of GFW initiative copy mention the gender technology gap, STEM access, and human-rights framing but not TFGBV by name.
Comparison: Could not confirm TFGBV is a named component of the Technology Initiative's mandate from reachable source text; not contradicted either.
Decision: uncorroborated

## Claim 20: IGNITE pairs a stories campaign "organised around five categories (Visionaries, Creatives, Leaders, Geeks, Changemakers)" with a dedicated Technology Fund donation mechanism

Source: https://ignite.globalfundforwomen.org/technologyfund
Source tier: primary
Source content: IGNITE gallery pages for Visionaries, Creatives, Leaders, Geeks, and Changemakers all surface in search with GFW's own descriptions; an "About the Technology Fund" page exists on the same site; UN Women's 2014 launch release: IGNITE is "an online campaign and multimedia project which explores the roles of science and technology in advancing women's human rights."
Comparison: All five categories and the Technology Fund mechanism confirmed from GFW's own campaign pages (via snippets — the ignite subdomain refuses connections on direct fetch, 2026-09-01) plus UN Women's independent release.
Decision: corroborated

## Claim 21: "200 million more men than women globally have internet access" and women are "21% less likely to own a mobile phone than men"

Source: https://ignite.globalfundforwomen.org/technologyfund
Source tier: primary
Source content: Via search snippets of GFW IGNITE content: "Worldwide, 200 million more men than women have access to the Internet, and women are 21% less likely to own a mobile phone."
Comparison: The body presents these as the statistics the IGNITE Technology Fund page documents, and GFW's own campaign copy carries them verbatim; the entity's framing (attribution to the campaign, not assertion of current truth) matches. Also covers `sources[5].note`.
Decision: primary-sourced

## Claim 22: grantee "Feminist Approach to Technology (India, training young women aged 12–18 in technology confidence and computer skills)"

Source: https://ignite.globalfundforwomen.org/gallery/voices-india-feminist-approach-technology
Source tier: primary
Source content: GFW copy via snippet: "grantee partner Feminist Approach to Technology in India is creating a movement of tech savvy young women and girls by training and engaging young women aged 12-18 … confidence and skills-building courses alongside computer classes and trainings."
Comparison: Grantee status, country, age range, and program description all match GFW's own content.
Decision: primary-sourced

## Claim 23: grantee "Inwelle Study and Resource Centre (Nigeria, ICT skills for teenage girls for economic empowerment)"

Source: https://inwellecentre.org/
Source tier: primary
Source content: GFW copy via snippet: "Inwelle is teaching teenage girls computer and ICT skills to help them earn money to support their families and pay for secondary school fees"; Inwelle's own site locates the Centre in Enugu, Nigeria, teaching ICT to marginalized girls.
Comparison: GFW's own grantee copy plus Inwelle's own site confirm country, beneficiaries, and economic-empowerment purpose.
Decision: corroborated

## Claim 24: "Mama Cash (founded 1983, Amsterdam, participatory-grantmaking structure through an external Community Committee)"

Source: https://www.mamacash.org/en/the-community-committee
Source tier: primary
Source content: Mama Cash's own pages: founded in Amsterdam in 1983; "The Community Committee (COM COM) is Mama Cash's participatory grantmaking decision-making body run for and by activists"; Wikipedia confirms the 1983 Amsterdam founding.
Comparison: Founding year, city, and the external participatory Community Committee all match Mama Cash's own pages plus Wikipedia.
Decision: corroborated

## Claim 25: "Numun Fund (launched grantmaking 2022, Global South–based, feminist-tech-specific, $1.6M first cohort)"

Source: https://numun.fund/grants/
Source tier: primary
Source content: Numun's own grants/report pages via snippets: "In July 2022, Numun Fund launched its first grantmaking cycle … supporting 43 groups, mobilizing $1.6 million USD"; described as "the first dedicated fund for feminist tech."
Comparison: Launch year, amount, and feminist-tech specificity match the fund's own pages.
Decision: primary-sourced

## Claim 26: "African Women's Development Fund (founded 2000, Accra, pan-African scope …)"

Source: https://en.wikipedia.org/wiki/African_Women%27s_Development_Fund
Source tier: database
Source content: "The AWDF was founded in 2000 … its headquarters are located in Accra, Ghana"; a "feminist non-governmental organization that operates throughout Africa" (Wikipedia, corroborated by InfluenceWatch/Devex profiles in the same search).
Comparison: Founding year, HQ city, and pan-African scope match multiple canonical profiles.
Decision: corroborated

## Claim 27: AWDF "$111M cumulative over 25 years"

Source: no canonical source found
Source tier: none
Source content: Exact-phrase search for the figure returns nothing; surfaced profiles carry older, much lower figures (e.g. "over $26.2 million to 1,200 women's organisations in 42 African countries").
Comparison: The $111M cumulative figure could not be confirmed from any reachable canonical source this session, and findable figures are stale and inconsistent; not clearly contradicted (the low figures are dated), so no correction asserted. AWDF's own entity audit is the right place to settle it.
Decision: uncorroborated

## Claim 28: "founded in 1987, three years before the Convention on the Rights of the Child was adopted"

Source: https://www.ohchr.org/en/instruments-mechanisms/instruments/convention-rights-child
Source tier: primary
Source content: "adopted and opened for signature, ratification and accession by General Assembly resolution 44/25 of 20 November 1989. … It entered into force 2 September 1990."
Comparison: The CRC was adopted in 1989 — two years after 1987, not three (three fits entry into force, 1990, but the body says "adopted"). Single correct replacement in body prose: "three years" → "two years".
Decision: correction
