---
entity_id: fund-skoll-foundation
entity_hash: 6a51331cb2fb4e2473aaa6c0fe3c2ddb663f20fb
audit_date: 2026-06-10
pass: 1
status: corrections-pending
claims_total: 34
claims_corroborated: 17
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 5
claims_uncorroborated: 12
sources_consulted:
  - https://en.wikipedia.org/wiki/Skoll_Foundation
  - https://en.wikipedia.org/wiki/Jeff_Skoll
  - https://en.wikipedia.org/wiki/Skoll_Centre_for_Social_Entrepreneurship
  - https://skoll.org/
  - https://skoll.org/about/
  - https://skoll.org/about/financials/
  - https://skoll.org/2024/04/02/skoll-foundation-announces-the-winners-of-2024-skoll-award-for-social-innovation/
  - https://projects.propublica.org/nonprofits/organizations/113659133
  - https://www.insidephilanthropy.com/home/2021-4-26-from-the-who-to-the-what-the-skoll-foundation-clarifies-its-priorities
  - https://meedan.org/about
---

## Claim 1: "established in 1999 by Jeff Skoll"

Source: https://en.wikipedia.org/wiki/Skoll_Foundation and https://skoll.org/about/
Source content: Wikipedia: "It was founded by Jeffrey Skoll in 1999." Skoll about page: "In 1999, Jeff Skoll created the Foundation to build a sustainable world of peace and prosperity for all."
Comparison: Body claim matches both primary and Wikipedia.
Decision: corroborated

## Claim 2: "Jeff Skoll — eBay's first president and first full-time employee"

Source: https://en.wikipedia.org/wiki/Jeff_Skoll
Source content: "In 1996, Skoll met eBay's founder Pierre Omidyar, who hired him as the company's first president and first full-time employee."
Comparison: Body claim matches verbatim — named-entity definitional / public role; Wikipedia sufficient.
Decision: corroborated

## Claim 3: "headquartered in Palo Alto, California"

Source: https://en.wikipedia.org/wiki/Skoll_Foundation and https://projects.propublica.org/nonprofits/organizations/113659133
Source content: Wikipedia: "The Skoll Foundation is an American private foundation based in Palo Alto, California." ProPublica filing address: "San Francisco, CA".
Comparison: The two canonical sources the entity itself cites disagree on the city. Per `AUDITOR.md § Source rule`, when canonical sources disagree the claim is unverifiable; do not pick a winner.
Decision: uncorroborated

## Claim 4: "Skoll, born in Montreal"

Source: https://en.wikipedia.org/wiki/Jeff_Skoll
Source content: "Born in Montreal, Quebec, Canada"
Comparison: Body claim matches — named-entity definitional fact; Wikipedia sufficient.
Decision: corroborated

## Claim 5: "holds a civil engineering degree from McGill University"

Source: https://en.wikipedia.org/wiki/Jeff_Skoll
Source content: "BASc with honours in 1987 from the University of Toronto's electrical engineering program." McGill University is not mentioned in the article.
Comparison: Body says civil engineering / McGill; Wikipedia says electrical engineering / University of Toronto. Both the degree subject and the institution are wrong.
Decision: correction

## Claim 6: "an MBA from Stanford"

Source: https://en.wikipedia.org/wiki/Jeff_Skoll
Source content: "Master of Business Administration degree at Stanford Graduate School of Business, graduating in 1995."
Comparison: Body claim matches.
Decision: corroborated

## Claim 7: "he founded the philanthropic vehicle alongside the Skoll Fund (a paired public charity) shortly after the eBay IPO"

Source: https://skoll.org/about/financials/
Source content: Page reports paired entities — "the Skoll Foundation assets were $1,019 million and the Skoll Fund assets were $1,183 million" — confirming the Skoll Fund exists as a paired entity. eBay's IPO (Sept 1998) preceded the 1999 founding, matching "shortly after."
Comparison: Pairing and timing both verifiable from primary source.
Decision: corroborated

## Claim 8: "Together the two entities hold combined assets of $2.202 billion as of December 31, 2025"

Source: https://skoll.org/about/financials/
Source content: "As of December 31, 2025, the Skoll Foundation assets were $1,019 million and the Skoll Fund assets were $1,183 million. Combined assets totaled $2,202 million."
Comparison: Body matches primary source verbatim on amounts and date.
Decision: corroborated

## Claim 9: "$1.019 billion in the Foundation and $1.183 billion in the Fund"

Source: https://skoll.org/about/financials/
Source content: "Skoll Foundation assets were $1,019 million and the Skoll Fund assets were $1,183 million"
Comparison: Body matches.
Decision: corroborated

## Claim 10: "in 2025 awarded $128 million, a 30% spending increase announced at the 2025 Skoll World Forum"

Source: https://skoll.org/about/financials/ (and attempted https://www.devex.com/news/special-edition-6-things-we-learned-at-the-skoll-world-forum-2025-109811)
Source content: Skoll financials confirms "In 2025, the Skoll Foundation and the Skoll Fund awarded a total of $128 million in grants." Financials page makes no mention of a 30% increase or 2025 Skoll World Forum announcement. The cited Devex 2025 Forum recap returned HTTP 403 in this audit pass.
Comparison: The $128M figure is verified; the "30% spending increase" + "announced at the 2025 Skoll World Forum" sub-claim cannot be confirmed from accessible canonical sources this pass. Splitting would let the verified half stand; the joint sentence as written is partially unverifiable.
Decision: uncorroborated

## Claim 11: "Skoll has invested more than $1.3 billion across more than 425 organisations in five continents"

Source: https://skoll.org/about/
Source content: "Over $1.3 billion invested worldwide" (as of December 31, 2024); "476 social entrepreneurs and other social innovators"; reach across "five continents".
Comparison: $1.3B and "five continents" match. "More than 425" is consistent with the current count of 476 (the body phrases it as a minimum).
Decision: corroborated

## Claim 12: "the Foundation reported FY2024 total assets of $846,865,174 and charitable disbursements of $70,996,475, with Donald Gips as CEO"

Source: https://projects.propublica.org/nonprofits/organizations/113659133
Source content: "Total Assets: $846,865,174"; "Charitable Disbursements: $70,996,475"; "Donald Gips (Director And Ceo)".
Comparison: All three values match verbatim.
Decision: corroborated

## Claim 13: "A 2021 strategic shift reoriented Skoll's grantmaking from a 'who' framing — backing any strong social entrepreneur — toward a 'what' framing"

Source: https://www.insidephilanthropy.com/home/2021-4-26-from-the-who-to-the-what-the-skoll-foundation-clarifies-its-priorities
Source content: "Shivani Garg Patel characterized the move as 'almost like a shift from the who to the what.'"
Comparison: Body claim matches the cited source's framing.
Decision: corroborated

## Claim 14: "anchored in six issue clusters"

Source: https://www.insidephilanthropy.com/home/2021-4-26-from-the-who-to-the-what-the-skoll-foundation-clarifies-its-priorities (and https://skoll.org/ )
Source content: Inside Philanthropy article (April 2021) names five priorities: "strengthening health systems and preventing pandemics; mobilizing climate action; reimagining inclusive and sustainable economies; keeping democracy safe by promoting effective governance; and advancing racial justice." Current skoll.org/ home page lists only three focus areas (community health workers, deforestation/Indigenous land rights, smallholder agriculture/girls' education); the dedicated /our-strategic-priorities/ URL 302-redirects to the home page.
Comparison: The "six" count is not supported by the 2021 source (which gives five) nor by current Skoll.org communications (which name three focus areas). Information Integrity may have been added later, but the precise pillar count and its alignment with the 2021 shift cannot be confirmed from accessible canonical sources.
Decision: uncorroborated

## Claim 15: "the Foundation's flagship annual grant of $2 million in unrestricted funding per organisation, typically awarded to a cohort of three to five"

Source: https://skoll.org/2024/04/02/skoll-foundation-announces-the-winners-of-2024-skoll-award-for-social-innovation/
Source content: "Each Awardee organization receives $2 million in unrestricted funding and flexible support to scale their work and increase their impact." The 2024 cohort contained four recipients, within 3–5.
Comparison: Body matches the verbatim award size and cohort range.
Decision: corroborated

## Claim 16: "In 2024 the award went to Meedan"

Source: https://skoll.org/2024/04/02/skoll-foundation-announces-the-winners-of-2024-skoll-award-for-social-innovation/
Source content: 2024 award recipients were "IllumiNative (U.S.), Food for Education (Kenya), Meedan (U.S.), and SaveLIFE Foundation (India)."
Comparison: Meedan confirmed as a 2024 recipient.
Decision: corroborated

## Claim 17: "Meedan, a US-based organisation whose Check platform and SynDy framework power AI-assisted fact-checking and misinformation-detection tools"

Source: https://skoll.org/2024/04/02/skoll-foundation-announces-the-winners-of-2024-skoll-award-for-social-innovation/ and https://meedan.org/about
Source content: 2024 Skoll announcement: describes Meedan as preventing "the spread of misinformation with technology that helps news organizations collaborate and quickly verify information," with no mention of "Check" or "SynDy". Meedan.org: "Check" appears in the navigation under "Our tools" section; "SynDy framework" does not appear.
Comparison: Check is supported by Meedan.org but not by the cited Skoll announcement. SynDy framework cannot be confirmed from any source consulted.
Decision: uncorroborated

## Claim 18: "deployed in sixty-five countries"

Source: https://skoll.org/2024/04/02/skoll-foundation-announces-the-winners-of-2024-skoll-award-for-social-innovation/ and https://meedan.org/about
Source content: The cited 2024 Skoll announcement does not mention a country count. Meedan.org currently states partners operate across "57 countries."
Comparison: 65 does not appear in the cited source. The closest current Meedan-self-reported number is 57. The body's "sixty-five" is unsupported and contradicted by the organisation's own current number.
Decision: correction

## Claim 19: "more than fifty newsrooms and fact-checking organisations"

Source: https://skoll.org/2024/04/02/skoll-foundation-announces-the-winners-of-2024-skoll-award-for-social-innovation/
Source content: "Over 50 newsrooms and fact-checking organizations have used Meedan's tools"
Comparison: Body matches.
Decision: corroborated

## Claim 20: "eighteen election and public health coalitions worldwide"

Source: https://skoll.org/2024/04/02/skoll-foundation-announces-the-winners-of-2024-skoll-award-for-social-innovation/
Source content: "Meedan has supported 18 election and public health coalitions worldwide"
Comparison: Body matches.
Decision: corroborated

## Claim 21: "Meedan applied its tools during the 2024 election cycle in Mexico, India, and the United States"

Source: https://skoll.org/2024/04/02/skoll-foundation-announces-the-winners-of-2024-skoll-award-for-social-innovation/
Source content: "is partnering with organizations covering everything from disaster response to the 2024 elections in Mexico, India, and the United States"
Comparison: Body matches.
Decision: corroborated

## Claim 22: "The 2026 cohort included Indus Action, which builds open-source civic-technology solutions to connect Indian citizens to government benefits, aiming to reach 800 million potential beneficiaries through technology-mediated social-protection access by 2030"

Source: no canonical source consulted in this pass
Source content: n/a — body cites no inline URL for this claim and no 2026 award announcement was reachable in this pass.
Comparison: Claim cannot be verified from sources consulted.
Decision: uncorroborated

## Claim 23: "Digital Action, another Skoll grantee... presented at the 2023 Skoll World Forum on protecting seventy-plus elections during the 2024 global election cycle from Big Tech risks"

Source: cited inline https://skoll.org/grantee/digital-action/ (not fetched this pass)
Source content: not retrieved in this audit pass.
Comparison: Cannot verify.
Decision: uncorroborated

## Claim 24: "annual Skoll World Forum, held at Oxford's Saïd Business School since 2004"

Source: https://en.wikipedia.org/wiki/Skoll_Foundation
Source content: "The annual Skoll World Forum assembles social entrepreneurship leaders at the Said Business School. The foundation held its first forum in 2004."
Comparison: Named-entity / public-event date — Wikipedia sufficient.
Decision: corroborated

## Claim 25: "Skoll Centre for Social Entrepreneurship (established by a $7.5 million founding gift from Jeff Skoll in 2003)"

Source: https://en.wikipedia.org/wiki/Skoll_Centre_for_Social_Entrepreneurship
Source content: "In November 2003, the Skoll Foundation, a social entrepreneurship foundation founded by Jeff Skoll, donated $7.5 million to the Saïd Business School for the creation of The Skoll Centre for Social Entrepreneurship."
Comparison: Body matches verbatim on year and amount; gift attributed to "Jeff Skoll" / "the Skoll Foundation founded by Jeff Skoll" is a paraphrase equivalent.
Decision: corroborated

## Claim 26: "gathers roughly 1,200–1,500 practitioners, policymakers, and funders from approximately eighty countries each April"

Source: no canonical source consulted in this pass
Source content: n/a — no Forum attendance figures appear in the cited sources fetched; the cited Devex 2025 recap returned HTTP 403.
Comparison: Cannot verify.
Decision: uncorroborated

## Claim 27: "the 2024 Forum hosted a dedicated session on AI for Good and Countering Disinformation, with speakers including technologist Kate Kallot, ML entrepreneur Jim Fruchterman of Tech Matters, and Digital Green CEO Rikin Gandhi covering AI applications in healthcare, agriculture, and democratic resilience"

Source: cited https://sponsored.foreignpolicy.com/skoll-world-forum/ai-countering-disinformation-skoll-world-forum-2024/
Source content: Cited source returned HTTP 403 in this audit pass; no alternative canonical source confirms speaker line-up.
Comparison: Cannot verify from sources consulted.
Decision: uncorroborated

## Claim 28: "The 2025 Forum included open-source AI collaboration on the programme; multiple speakers cited the statistic that only one percent of global philanthropic funding is currently dedicated to AI for good... and Pelonomi Moiloa's Lelapa AI — building African-language small language models — was showcased"

Source: cited https://www.devex.com/news/special-edition-6-things-we-learned-at-the-skoll-world-forum-2025-109811
Source content: Cited source returned HTTP 403 in this audit pass; no alternative canonical source confirms.
Comparison: Cannot verify from sources consulted.
Decision: uncorroborated

## Claim 29: "The Skoll Centre for Social Entrepreneurship has also published skeptical analysis of AI-for-good marketing"

Source: cited inline http://skollcentreblog.org/2019/04/11/getting-to-the-root-of-the-problem-the-myth-of-ai-for-good/ (not fetched this pass)
Source content: not retrieved.
Comparison: Cannot verify.
Decision: uncorroborated

## Claim 30: "Skoll is not a member of the January 2024 Public Interest AI initiative (the ten-foundation, $200 million-plus collaborative that includes Ford, MacArthur, Democracy Fund, Mozilla Foundation, Kapor Foundation, Omidyar Network, Open Society Foundations, and others)"

Source: cited inline https://www.fordfoundation.org/news-and-stories/news-and-press/news/philanthropies-launch-new-initiative-to-ensure-ai-advances-the-public-interest/ (not fetched this pass)
Source content: not retrieved.
Comparison: Cannot verify the membership-set negative.
Decision: uncorroborated

## Claim 31: "is not among the founding members of the October 2025 Humanity AI coalition ($500 million over five years)"

Source: no canonical source cited or consulted
Source content: not retrieved.
Comparison: Cannot verify.
Decision: uncorroborated

## Claim 32: scalar:sources[1].note — "ProPublica Nonprofit Explorer for Skoll Foundation (EIN 11-3659133) — Palo Alto address; FY2024 revenue $47.9M, total assets $846,865,174, charitable disbursements $70,996,475; Donald Gips listed as CEO"

Source: https://projects.propublica.org/nonprofits/organizations/113659133
Source content: ProPublica lists address as "San Francisco, CA" — not Palo Alto. EIN "11-3659133", revenue $47,915,522, total assets $846,865,174, charitable disbursements $70,996,475, and Donald Gips as Director and CEO all match the source.
Comparison: The source note describes the ProPublica filing's address as Palo Alto, but the actual ProPublica page lists San Francisco. All other source-note paraphrases match. Fix location: `sources[1].note` in frontmatter.
Decision: correction

## Claim 33: scalar:sources[2].note — "Skoll Foundation Wikipedia entry — Jeff Skoll as founder; eBay first president; civil engineering degree McGill University, MBA Stanford; combined assets ~$2.2B unaudited Dec 31 2025; cumulative giving more than $1.3B across 425+ organisations"

Source: https://en.wikipedia.org/wiki/Skoll_Foundation
Source content: The Skoll Foundation Wikipedia article confirms Jeff Skoll as founder and as "first president of eBay." It does not contain any reference to Jeff Skoll's degree, McGill University, or Stanford MBA — those details live on the separate `Jeff_Skoll` article and there read "BASc with honours in 1987 from the University of Toronto's electrical engineering program" (not McGill, not civil engineering). The Skoll Foundation Wikipedia article's reported total assets figure is "$1.127 billion as of 2018," not "~$2.2B unaudited Dec 31 2025"; the $2.2B figure is a primary-source (skoll.org/about/financials/) fact, not a Wikipedia fact.
Comparison: The source note attributes several claims to the Skoll Foundation Wikipedia article that the article does not contain (degree / school) and one that is wrong-school-and-wrong-subject regardless of attribution (civil engineering McGill vs. electrical engineering U of Toronto). Same root issue as Claim 5 but lives in the frontmatter scalar; fix location: `sources[2].note`.
Decision: correction

## Claim 34: scalar:sources[8].note — "Inside Philanthropy April 2021 — Skoll strategic shift from funding any social entrepreneur to six issue-area pillars"

Source: https://www.insidephilanthropy.com/home/2021-4-26-from-the-who-to-the-what-the-skoll-foundation-clarifies-its-priorities
Source content: Article names five issue-area priorities — "strengthening health systems and preventing pandemics; mobilizing climate action; reimagining inclusive and sustainable economies; keeping democracy safe by promoting effective governance; and advancing racial justice." Information Integrity is not present in this article.
Comparison: Source note describes "six issue-area pillars" but the cited article names five. Fix location: `sources[8].note`.
Decision: correction
