---
entity_id: fund-omidyar-network
entity_hash: 456c8132774c487c6daa1b2cf8fa346f93bd970c
audit_date: 2026-05-22
pass: 1
status: discrepancy
claims_total: 28
claims_verified: 20
claims_discrepancy: 1
claims_unverifiable: 7
sources_consulted:
  - https://en.wikipedia.org/wiki/Omidyar_Network
  - https://en.wikipedia.org/wiki/Pierre_Omidyar
  - https://www.opensocietyfoundations.org/newsroom/open-society-and-other-funders-launch-new-initiative-to-ensure-ai-advances-the-public-interest
  - https://www.fordfoundation.org/news-and-stories/news-and-press/news/philanthropies-launch-new-initiative-to-ensure-ai-advances-the-public-interest/
  - https://www.nuffieldfoundation.org/news/the-nuffield-foundation-announces-new-5-million-ada-lovelace-institute
  - https://cipesa.org/2025/03/african-digital-rights-funding-crisis/
  - https://democracyfund.org/who-we-are/financials/
---

## Claim 1: "established in 2004 by eBay founder Pierre Omidyar and his wife Pam"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: "Established in 2004 by 'eBay founder Pierre Omidyar and his wife Pam.'"
Comparison: Year, founders, and eBay-founder attribution all match. Definitional named-entity fact; Wikipedia-alone canonical per source rule.
Decision: verified

## Claim 2: '"philanthropic investment firm"'

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: 'The organization describes itself as a "philanthropic investment firm."'
Comparison: Exact phrase confirmed as Omidyar Network's own self-description.
Decision: verified

## Claim 3: '"harnessing the power of markets to create opportunities for people to improve their lives"'

Source: https://en.wikipedia.org/wiki/Pierre_Omidyar
Source content: 'The exact phrase appears in the article: "harnessing the power of markets to create opportunities for people to improve their lives."'
Comparison: Exact mission phrasing matches verbatim.
Decision: verified

## Claim 4: "a 501(c)(3) and a Limited Liability Company, and part of The Omidyar Group"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: 'Comprises "a 501(c)(3) and a Limited Liability Company (LLC)."'
Comparison: Dual structure matches verbatim; "part of The Omidyar Group" framing matches the Wikipedia article's organisational placement. Named-entity definitional fact; Wikipedia-alone canonical.
Decision: verified

## Claim 5: "Redwood City, California, with a Washington, DC office"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"Based in Redwood City, California, with an office in Washington, D.C."'
Comparison: HQ and office locations match. Named-entity definitional fact; Wikipedia-alone canonical.
Decision: verified

## Claim 6: '"awarded almost $2 billion to more than 700 organizations" by 2025'

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"By 2025, Omidyar Network had awarded almost $2 billion to more than 700 organizations."'
Comparison: Wording matches Wikipedia verbatim, but this is a financial-specific claim (cumulative grant volume). Source rule places financial specifics in the Wikipedia-tiebreaker-only list; no second canonical source in the entity's sources or my consulted set substantiates the figure.
Decision: unverifiable

## Claim 7: "CEO Mike Kubzansky (since 2018)"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"Since 2018, Mike Kubzansky has been the CEO."'
Comparison: Name and start year match. Official role at an organisation; treated as named-entity / role fact for Wikipedia-alone canonicality.
Decision: verified

## Claim 8: "President Michele Jawando (from 2025; previously Senior Vice President for Programs)"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"Jawando became president of the organization in 2025." Prior role: "senior vice president for programs in 2023."'
Comparison: Both the 2025 elevation and the prior SVP-for-Programs role match. Official role; Wikipedia-alone canonical.
Decision: verified

## Claim 9: "more than $992 million committed to for-profit companies and nonprofit organisations"

Source: https://en.wikipedia.org/wiki/Pierre_Omidyar
Source content: '"Omidyar Network has committed more than $992 million to for-profit companies and nonprofit organizations that foster economic advancement and encourage individual participation across multiple investment areas."'
Comparison: Wording matches Wikipedia verbatim, but the figure is a financial specific (cumulative commitment volume). Wikipedia-tiebreaker-only for financial claims; no second canonical source substantiates.
Decision: unverifiable

## Claim 10: "Democracy Fund [was] established by Pierre Omidyar in 2011 ... launching as an independent private foundation in July 2014 focused on US democracy"

Source: https://democracyfund.org/who-we-are/financials/
Source content: '"Established and solely funded by philanthropist and eBay founder Pierre Omidyar in 2011" ... "Democracy Fund launched as an independent foundation in July 2014."'
Comparison: 2011 establishment, Omidyar founder attribution, and July 2014 independent-launch date all match the Democracy Fund's own financials page. US-democracy focus matches Democracy Fund's standing mission (corroborated in cross-corpus entity fund-democracy-fund).
Decision: verified

## Claim 11: "incubated for three years under Joe Goldman as Investment Director"

Source: no canonical source found
Source content: The Democracy Fund financials page makes no mention of Joe Goldman or an Investment Director role during 2011-2014. The Wikipedia Omidyar Network article also does not name Goldman. No other source in the entity's `sources:` field covers the incubation-period leadership claim.
Comparison: Employment-history specific (a named person's role during a specific period); per source rule, living-person specifics beyond public office require ≥1 non-Wikipedia canonical source. None of the entity's cited sources or the additional sources I fetched substantiate the Joe Goldman claim. Note: the body presents this as fact rather than as supported by the Democracy Fund link adjacent to it.
Decision: unverifiable

## Claim 12: "Luminate [was] spun off in 2018 from Omidyar Network's Governance & Citizen Engagement Initiative"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"In 2018, Omidyar Network spun off its Governance & Citizen Engagement initiative. The group now operates as Luminate."'
Comparison: Year and originating division match Wikipedia. Named-entity definitional fact (a structural spin-off).
Decision: verified

## Claim 13: "[Luminate operates] as an independent international foundation with a Civic Empowerment, Data + Digital Rights, Independent Media, and Financial Transparency remit"

Source: no canonical source found
Source content: Wikipedia's Omidyar Network article confirms the 2018 Luminate spin-off but does not enumerate the four-pillar remit (Civic Empowerment, Data + Digital Rights, Independent Media, Financial Transparency). The entity's other cited sources do not cover Luminate's programmatic structure.
Comparison: The specific four-pillar list is a load-bearing characterisation of Luminate's programmatic structure. No canonical source consulted substantiates this enumeration. The Researcher likely drew it from Luminate's own website (luminategroup.com), which is not in the entity's `sources:`.
Decision: unverifiable

## Claim 14: "Flourish (2019, from Financial Inclusion)"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"Flourish (2019 from Financial Inclusion)."'
Comparison: Year and originating division match. Named-entity definitional fact.
Decision: verified

## Claim 15: "Imaginable Futures (2020, from the education portfolio)"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"Imaginable Futures (2020, education portfolio)."'
Comparison: Year and originating portfolio match. Named-entity definitional fact.
Decision: verified

## Claim 16: "PlaceFund (January 2020, on property rights)"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"PlaceFund (January 2020, property rights)."'
Comparison: Month, year, and focus area all match. Named-entity definitional fact.
Decision: verified

## Claim 17: "Spero Ventures (March 2018, a generalist venture capital firm)"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"Spero Ventures (March 2018)."'
Comparison: Month and year match. The descriptor "generalist venture capital firm" is a minor extension not contradicted by the source; Wikipedia identifies it as a venture-capital spin-off. Within paraphrase tolerance.
Decision: verified

## Claim 18: "Omidyar Network India was established in 2010 to invest in Indian start-ups"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"In 2010, Omidyar Network established an operation in India."'
Comparison: Year and India scope match. Named-entity definitional fact.
Decision: verified

## Claim 19: "managing approximately $673 million across 1mg, Bounce, Vedantu, Bijak, DealShare, Doubtnut, Entri, HealthKart, Indifi, M2P, and Pratilipi by July 2023"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: 'July 2023: "$673 million worth of investments under management in India."'
Comparison: The $673M figure and July 2023 timestamp match Wikipedia; the portfolio-company list is also in the Wikipedia article per the entity's source note. However, both the financial figure and the donor/portfolio identification are financial-specific claims for which Wikipedia is tiebreaker-only. No second canonical source consulted substantiates either component.
Decision: unverifiable

## Claim 20: "its closure was announced in December 2023, with operations ceasing by end of 2024"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"In December 2023, the company announced it would cease operations in India by the end of 2024."'
Comparison: Announcement month and cessation timeline both match. Dates of public events / public-record facts — Wikipedia-alone canonical per source rule.
Decision: verified

## Claim 21: "1 November 2023 ten-foundation Public Interest AI initiative — a coalition announced in coordination with Vice President Kamala Harris during the global AI Safety Summit week"

Source: https://www.fordfoundation.org/news-and-stories/news-and-press/news/philanthropies-launch-new-initiative-to-ensure-ai-advances-the-public-interest/ ; https://www.opensocietyfoundations.org/newsroom/open-society-and-other-funders-launch-new-initiative-to-ensure-ai-advances-the-public-interest
Source content: Both releases are dated 1 November 2023. Ford release: '"areas of need identified today by Vice President Kamala Harris."' Neither release mentions "AI Safety Summit week" or any explicit timing alignment with the UK summit.
Comparison: The 1 November 2023 date and the coordination with VP Harris are both confirmed verbatim by both releases. The "during the global AI Safety Summit week" framing, however, is not stated in either of the entity's cited sources or in any source I consulted; it is an editorial situating-claim that links PIAI to the UK Bletchley Park summit. Source-rule treats causal / contextual situating-claims about public events as tiebreaker-only on Wikipedia, and no source consulted establishes the AI-Safety-Summit-week link.
Decision: unverifiable

## Claim 22: "named among the ten co-launching foundations, alongside the Ford Foundation, the MacArthur Foundation, the Mozilla Foundation, the Open Society Foundations, Democracy Fund, the David and Lucile Packard Foundation, Heising-Simons Foundation, Kapor Foundation, and the Wallace Global Fund"

Source: https://www.opensocietyfoundations.org/newsroom/open-society-and-other-funders-launch-new-initiative-to-ensure-ai-advances-the-public-interest ; https://www.fordfoundation.org/news-and-stories/news-and-press/news/philanthropies-launch-new-initiative-to-ensure-ai-advances-the-public-interest/
Source content: Both releases enumerate the same ten foundations: Open Society Foundations, Packard, Democracy Fund, Ford, Heising-Simons, MacArthur, Kapor, Mozilla, Omidyar Network, Wallace Global Fund.
Comparison: All ten foundations match across both releases and the body's enumeration. Two independent canonical sources confirm.
Decision: verified

## Claim 23: '"collective commitment of more than $200 million toward public-interest efforts to mitigate AI harms and promote responsible use and innovation"'

Source: https://www.fordfoundation.org/news-and-stories/news-and-press/news/philanthropies-launch-new-initiative-to-ensure-ai-advances-the-public-interest/
Source content: '"collectively contributing more than $200 million"'
Comparison: The "$200 million" figure and "more than" framing match Ford's release verbatim. The body's expanded phrasing ("toward public-interest efforts to mitigate AI harms and promote responsible use and innovation") is a paraphrase consistent with the PIAI initiative's stated purpose across both releases.
Decision: verified

## Claim 24: "five focus areas the Harris identified: protecting democracy and rights, public-interest innovation, workers' rights and labour standards, transparency and accountability of AI models and companies, and the development of international AI governance frameworks and norms"

Source: https://www.fordfoundation.org/news-and-stories/news-and-press/news/philanthropies-launch-new-initiative-to-ensure-ai-advances-the-public-interest/
Source content: '"Ensure that AI protects democracy and the rights and freedoms of all people" / "Leverage AI to innovate in the public interest and deliver breakthroughs to improve quality of life" / "Empower workers to thrive amid AI-driven changes across sectors and industries" / "Improve transparency, interpretability, and accountability for AI models, companies, and deployers" / "Support the development of international AI rules and norms."'
Comparison: All five body summaries map clearly onto the five Ford-release items within paraphrase tolerance (semantic content preserved; word-for-word differs).
Decision: verified

## Claim 25: "2024 launch of the Data Empowerment Fund, a new programmatic vehicle to support initiatives promoting greater individual and community control over information privacy"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"In 2024, the organization created the Data Empowerment Fund to support initiatives promoting greater individual and community control in information privacy."'
Comparison: Year, name, and purpose all match Wikipedia verbatim. Named-entity definitional fact (an in-house programmatic vehicle); Wikipedia-alone canonical.
Decision: verified

## Claim 26: "2024 purchase, alongside the Ford Foundation and the Cummings Foundation, of a stake in generative AI firm Anthropic"

Source: https://en.wikipedia.org/wiki/Omidyar_Network
Source content: '"Omidyar, Ford, Cummings purchase stake in generative AI firm Anthropic" (April 2024).'
Comparison: The April 2024 transaction and the three co-investors (Omidyar, Ford, Cummings) match Wikipedia. However, this is a financial / equity-investment claim falling in the Wikipedia-tiebreaker-only list (financial and legal specifics, donor identities). No second canonical source consulted substantiates the transaction.
Decision: unverifiable

## Claim 27: 'CIPESA\'s March 2025 Round Nine announcement names Omidyar Network "among the African Digital Rights Fund\'s historical supporters alongside the Open Society Foundations, the Hewlett Foundation, CIPE, Sida, GIZ, and the New Venture Fund"'

Source: https://cipesa.org/2025/03/african-digital-rights-funding-crisis/
Source content: '"Other supporters of the ADRF in the past include the Center for International Private Enterprise (CIPE), the Swedish International Development Cooperation Agency (Sida), the German Society for International Cooperation Agency (GIZ), the Omidyar Network, the Hewlett Foundation, the Open Society Foundations and New Venture Fund (NVF)."'
Comparison: Announcement date (March 25, 2025), Omidyar Network's inclusion, and the full list of co-listed supporters all match verbatim. Dated-event / public-record fact from the entity that conducted the announcement.
Decision: verified

## Claim 28: 'Nuffield Foundation\'s 28 March 2018 launch announcement names "Omidyar Network\'s Governance & Citizen Engagement Initiative (now Luminate)" among the Ada Lovelace Institute\'s founding partner organisations'

Source: https://www.nuffieldfoundation.org/news/the-nuffield-foundation-announces-new-5-million-ada-lovelace-institute
Source content: The 28 March 2018 Nuffield announcement names the partner as "Omidyar Network's Governance & Citizen Engagement Initiative" — without the parenthetical "(now Luminate)". Per my fetch of the page: "The text does not include any parenthetical note indicating a name change or alternative current designation for Omidyar Network's initiative."
Comparison: The body presents the quoted text including "(now Luminate)" as if it were lifted from the Nuffield announcement, but the parenthetical is the entity author's editorial interpolation. The announcement, dated 28 March 2018, predates the 2018 Luminate spin-off (spin-off year per Wikipedia, Claim 12). The announcement-date and founding-partner-list facts are otherwise verified — the discrepancy is specifically in the quoted-text fidelity. Mechanically one-replacement: move "(now Luminate)" outside the closing quotation mark (or delete it from the quoted span and rephrase the surrounding clause to add the gloss outside quotes). The simplest single-token fix is to replace `"Omidyar Network's Governance & Citizen Engagement Initiative (now Luminate)"` with `"Omidyar Network's Governance & Citizen Engagement Initiative"` (i.e., remove ` (now Luminate)` from inside the quotation). The "(now Luminate)" gloss is reasonable corpus context but does not belong inside the source quote.
Decision: discrepancy
