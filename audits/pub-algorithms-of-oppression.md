---
entity_id: pub-algorithms-of-oppression
entity_hash: 8515d4a4856d645c167d1d1e1c853b145348224a
audit_date: 2026-06-11
pass: 2
status: corrections-pending
claims_total: 25
claims_corroborated: 4
claims_primary_sourced: 8
claims_single_source: 12
claims_uncorroborated: 0
open_corrections: 1
sources_consulted:
  - https://nyupress.org/9781479837243/algorithms-of-oppression/
  - https://en.wikipedia.org/wiki/Algorithms_of_Oppression
  - https://en.wikipedia.org/wiki/Safiya_Noble
  - https://www.macfound.org/fellows/class-of-2021/safiya-noble
  - https://www.c2i2.ucla.edu/
  - https://newsroom.ucla.edu/releases/researchers-receive-2-9m-to-study-intersection-of-technology-power-and-society
  - https://www.dair-institute.org/team
  - https://www.dair-institute.org/press-release/
  - https://www.codeforsociety.org/fsp/news/the-distributed-ai-research-institute-joins-cs-s
  - https://giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
  - https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
  - https://www.penguinrandomhouse.com/books/670356/unmasking-ai-by-joy-buolamwini/
  - https://en.wikipedia.org/wiki/Weapons_of_Math_Destruction
  - https://en.wikipedia.org/wiki/Joy_Buolamwini
  - https://en.wikipedia.org/wiki/Stochastic_parrot
---

Pass-2 re-audit. Entity changed since pass 1 only in frontmatter `authors: []` →
`[person-safiya-noble]` and two body entity-link wraps (no factual-content change).
All 25 claims re-checked against fresh fetches this session. Support decisions follow
the 2026-06-10 count-based taxonomy: `corroborated` is reserved for ≥2 independent
canonical sources, `primary-sourced` for one primary-tier source, `single-source` for
one non-primary canonical source — so several pass-1 `corroborated` labels (legacy
`verified` relabels) now carry the more precise `primary-sourced` / `single-source`
states. These are sourcing-strength labels, not error findings. Pass 1's two
`uncorroborated` claims both resolved this pass (Claims 21, 22). Pass 1's one
`correction` (Claim 5) remains open — the body text is unchanged.

## Claim 1: "is a 2018 book by the internet-studies scholar Safiya Umoja Noble" (and scalar:authors[0] = person-safiya-noble)

Source: https://nyupress.org/9781479837243/algorithms-of-oppression/ + https://en.wikipedia.org/wiki/Algorithms_of_Oppression
Source tier: primary
Source content: Publisher page: author "Safiya Umoja Noble", publisher NYU Press, publication February 2018. Wikipedia: "Publication date: February 20, 2018."
Comparison: Author identity and 2018 attribution match across publisher (primary) and Wikipedia. The frontmatter authors[] entry added since pass 1 matches the verified author.
Decision: corroborated

## Claim 2: "published by NYU Press in February 2018 (paperback ISBN 9781479837243, hardcover ISBN 9781479849949, ebook ISBN 9781479866762, 248 pages)"

Source: https://nyupress.org/9781479837243/algorithms-of-oppression/
Source tier: primary
Source content: Publisher page lists NYU Press, February 2018, paperback ISBN 9781479837243, hardcover ISBN 9781479849949, eBook ISBN 9781479866762, 248 pages.
Comparison: All metadata exact-match against the publisher's own page (the only authoritative source for the ISBN/page-count set).
Decision: primary-sourced

## Claim 3: "released on 20 February 2018"

Source: https://en.wikipedia.org/wiki/Algorithms_of_Oppression + https://nyupress.org/9781479837243/algorithms-of-oppression/
Source tier: primary
Source content: Wikipedia: "Publication date: February 20, 2018." Publisher page: February 2018.
Comparison: Day-precise date from Wikipedia (named-entity definitional fact, Wikipedia-alone-sufficient type), month corroborated by the publisher's page; the two sources are consistent.
Decision: corroborated

## Claim 4: publisher's quoted summary — "data discrimination is a real social problem" / "private interests" / "biased ... algorithms that privilege whiteness and discriminate against people of color, specifically women of color"

Source: https://nyupress.org/9781479837243/algorithms-of-oppression/
Source tier: primary
Source content: "Data discrimination is a real social problem; Noble argues that the combination of private interests in promoting certain sites, along with the monopoly status of a relatively small number of Internet search engines, leads to a biased set of search algorithms that privilege whiteness and discriminate against people of color, specifically women of color."
Comparison: The three quoted fragments match verbatim. The body's ellipsis ("biased ... algorithms") elides "set of search" from the source quote; semantic content preserved.
Decision: primary-sourced

## Claim 5: MacArthur Foundation citation — "search engines are not sources of neutral and objective information" and "how economic incentives and social values shape algorithmic results, showing how bias embedded in search algorithms can promote disinformation and lead to real-world harms"

Source: https://www.macfound.org/fellows/class-of-2021/safiya-noble
Source tier: primary
Source content: Foundation page (re-fetched this pass): "Noble demonstrates that search engines are not sources of neutral and objective information. Rather, economic incentives (primarily advertising revenue) and the social values assigned to ideas, objects, or people shape search engine results." And: "She details how bias embedded within search algorithms promotes disinformation, reduces the political and social agency of marginalized people, and can lead to real-world violence."
Comparison: First quoted fragment matches verbatim. The second fragment, inside body quotation marks, ends "lead to real-world harms" — the Foundation's text says "lead to real-world violence." "Harms" softens the source's "violence" while sitting inside quotation marks that promise exact wording; the intervening paraphrase also rewords "embedded within search algorithms promotes disinformation" inside quote marks. OPEN SINCE PASS 1 (2026-06-02) — the body text is unchanged this pass. Editor's mechanical fix: restore "real-world violence" and "embedded within search algorithms" verbatim within the quote, or drop the quotation marks and make it an attributed paraphrase.
Decision: correction

## Claim 6: three named search-result case studies — Google searches for "black girls" returning pornographic results; searches for "Jew" surfacing antisemitic content; searches for "black on white crimes" surfacing white-supremacist sources

Source: https://en.wikipedia.org/wiki/Algorithms_of_Oppression
Source tier: tiebreaker
Source content: Wikipedia lists the case studies: "black girls" (returned pornography), "Jew" (returned anti-Semitic pages), "black on white crimes" (returned conservative sources with racist information).
Comparison: The three search terms and outcomes match. Body's "white-supremacist sources" is a sharper rendering of Wikipedia's "conservative sources with racist information" but within paraphrase tolerance for the named-case-study fact. Book-contents claim resting on Wikipedia alone — supported, lighter sourcing.
Decision: single-source

## Claim 7: Library of Congress "illegal aliens" subject heading case

Source: https://en.wikipedia.org/wiki/Algorithms_of_Oppression
Source tier: tiebreaker
Source content: Wikipedia describes "A two-year effort to change terminology from 'illegal aliens' to 'noncitizen' or 'unauthorised immigrants'."
Comparison: Subject heading "illegal aliens" and cataloging context match; rests on Wikipedia alone this pass.
Decision: single-source

## Claim 8: the term "algorithmic oppression" names "the class of data-failure that disproportionately affects people of colour, women, and other marginalised groups"

Source: https://en.wikipedia.org/wiki/Algorithms_of_Oppression
Source tier: tiebreaker
Source content: Wikipedia: Noble coins the term to describe "data failures specific to people of color, women, and other marginalized groups."
Comparison: Term attribution and definition scope match; rests on Wikipedia alone this pass.
Decision: single-source

## Claim 9: "worked for more than a decade in multicultural marketing, advertising, and public relations before entering academia"

Source: https://en.wikipedia.org/wiki/Safiya_Noble
Source tier: tiebreaker
Source content: "After she graduated, Noble worked for more than a decade in multicultural marketing, advertising, and public relations."
Comparison: Pre-academic career claim matches near-verbatim. Employment-history specifics about a living person rest on Wikipedia alone — supported, lighter sourcing than the person-claim bar (primary or mainstream-news) prefers.
Decision: single-source

## Claim 10: "earned her PhD in library and information science from the University of Illinois Urbana-Champaign in 2012 with the named dissertation 'Searching for black girls: old traditions in new media'"

Source: https://en.wikipedia.org/wiki/Safiya_Noble
Source tier: tiebreaker
Source content: "PhD — Year: 2012; Institution: University of Illinois Urbana-Champaign; Field: Library and Information Science; Dissertation: Searching for Black Girls: Old Traditions in New Media."
Comparison: Year, institution, field, and dissertation title match; rests on Wikipedia alone this pass.
Decision: single-source

## Claim 11: "David O. Sears Presidential Endowed Chair of Social Sciences and Professor of Gender Studies, African American Studies, and Information Studies at UCLA"

Source: https://en.wikipedia.org/wiki/Safiya_Noble
Source tier: tiebreaker
Source content: "David O. Sears presidential endowed chair of social sciences; Professor of gender studies, African American studies, and information studies."
Comparison: Title and three department appointments match. Official roles/titles are a Wikipedia-alone-sufficient claim type; one source.
Decision: single-source

## Claim 12: "directs the UCLA Center on Race & Digital Justice"

Source: https://en.wikipedia.org/wiki/Safiya_Noble
Source tier: tiebreaker
Source content: "Director of the UCLA Center on Race & Digital Justice."
Comparison: Direction role and Center name match. Official-role type, Wikipedia-alone-sufficient; one source.
Decision: single-source

## Claim 13: "co-directs the Minderoo Initiative on Tech & Power at the UCLA Center for Critical Internet Inquiry"

Source: https://en.wikipedia.org/wiki/Safiya_Noble + https://newsroom.ucla.edu/releases/researchers-receive-2-9m-to-study-intersection-of-technology-power-and-society
Source tier: primary
Source content: Wikipedia: "Co-director of the Minderoo Initiative on Tech & Power at the UCLA Center for Critical Internet Inquiry (C2i2)." UCLA Newsroom: co-directors Safiya Umoja Noble and Sarah T. Roberts.
Comparison: Co-direction role and institutional location match across two independent canonical sources.
Decision: corroborated

## Claim 14: C2i2 self-description "a community of scholars at UCLA and beyond whose work engages the past, present and future of the Internet"

Source: https://www.c2i2.ucla.edu/
Source tier: primary
Source content: "UCLA Center for Critical Internet Inquiry is a community of scholars at UCLA and beyond whose work engages the past, present and future of the Internet."
Comparison: Exact-match self-description on the Center's own homepage.
Decision: primary-sourced

## Claim 15: Center "co-founded with Sarah T. Roberts"

Source: https://newsroom.ucla.edu/releases/researchers-receive-2-9m-to-study-intersection-of-technology-power-and-society + https://www.macfound.org/fellows/class-of-2021/safiya-noble
Source tier: primary
Source content: UCLA Newsroom: "The initiative will be led by the center's co-directors and co-founders, Safiya Umoja Noble and Sarah T. Roberts." MacArthur: Noble "is also co-founder of the newly established University of California at Los Angeles Center for Critical Internet Inquiry."
Comparison: The Newsroom sentence names both as "the center's co-directors and co-founders"; MacArthur independently names Noble C2i2 co-founder. Two independent canonical sources.
Decision: corroborated

## Claim 16: "USD 2.9 million Minderoo Foundation grant in August 2020 that funds the Minderoo Initiative on Technology and Power under Noble and Roberts as co-directors"

Source: https://newsroom.ucla.edu/releases/researchers-receive-2-9m-to-study-intersection-of-technology-power-and-society
Source tier: primary
Source content: Release dated August 13, 2020: $2.9 million from the Minderoo Foundation to the UCLA Center for Critical Internet Inquiry to establish the Minderoo Initiative on Technology and Power; co-directors Safiya Umoja Noble and Sarah T. Roberts.
Comparison: Amount, month, recipient, program name, and co-director names all match the university's own release.
Decision: primary-sourced

## Claim 17: "named a 2021 MacArthur Fellow with the citation 'Highlighting the ways digital technologies and internet architectures magnify racism, sexism, and harmful stereotypes'"

Source: https://www.macfound.org/fellows/class-of-2021/safiya-noble
Source tier: primary
Source content: Foundation page carries the citation "Highlighting the ways digital technologies and internet architectures magnify racism, sexism, and harmful stereotypes."
Comparison: Year (2021) and citation text match verbatim against the Foundation's own fellow page.
Decision: primary-sourced

## Claim 18: co-edited "The Intersectional Internet: Race, Sex, Class, and Culture Online (with Brendesha M. Tynes, 2016)"

Source: https://en.wikipedia.org/wiki/Safiya_Noble
Source tier: tiebreaker
Source content: Wikipedia lists "The Intersectional Internet: Race, Sex, Class, and Culture Online (with Brendesha M. Tynes, 2016)."
Comparison: Title, year, and co-editor name match; rests on Wikipedia alone this pass.
Decision: single-source

## Claim 19: co-edited "Emotions, Technology, and Design (with Sharon Y. Tettegah, 2016)"

Source: https://en.wikipedia.org/wiki/Safiya_Noble
Source tier: tiebreaker
Source content: Wikipedia lists "Emotions, Technology & Design (with Sharon Y. Tettegah, 2016)."
Comparison: Year and co-editor match; Wikipedia renders the title with an ampersand ("Technology & Design") where the body has "Technology, and Design" — stylistic variance within paraphrase tolerance, not a token contradiction. Rests on Wikipedia alone this pass.
Decision: single-source

## Claim 20: cross-corpus dates — "Weapons of Math Destruction (2016)", "Gender Shades (2018)", "Stochastic Parrots (2021)"

Source: https://en.wikipedia.org/wiki/Weapons_of_Math_Destruction + https://en.wikipedia.org/wiki/Joy_Buolamwini + https://en.wikipedia.org/wiki/Stochastic_parrot
Source tier: tiebreaker
Source content: "Weapons of Math Destruction is a 2016 American book ... written by Cathy O'Neil." "Her 2018 paper Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification ..." Stochastic Parrots: "formal publication occurring in March 2021."
Comparison: Three publication years each match a canonical source (named-entity definitional dates, Wikipedia-alone-sufficient type); each year rests on one source.
Decision: single-source

## Claim 21: cross-corpus dates — "Design Justice (2020)", "Unmasking AI (2023)"

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock + https://www.penguinrandomhouse.com/books/670356/unmasking-ai-by-joy-buolamwini/ + https://en.wikipedia.org/wiki/Joy_Buolamwini
Source tier: primary
Source content: Costanza-Chock Wikipedia: "Design Justice: Community-Led Practices to Build the Worlds We Need ... published in March 2020 by MIT Press." Penguin Random House: Unmasking AI original release October 31, 2023. Buolamwini Wikipedia: "In 2023, she published her first book, Unmasking AI."
Comparison: Both years now confirmed (pass-1 fetch failures resolved via alternate pages). Unmasking AI 2023 is corroborated (publisher primary + Wikipedia); Design Justice 2020 rests on one Wikipedia source — the compound claim takes the weaker member's state.
Decision: single-source

## Claim 22: "named alongside Ciira wa Maina as a founding advisor in DAIR's December 2021 fiscal-sponsorship announcement"

Source: https://www.codeforsociety.org/fsp/news/the-distributed-ai-research-institute-joins-cs-s
Source tier: primary
Source content: Code for Science & Society announcement dated December 2, 2021, announcing DAIR as a fiscally sponsored project under CS&S's Sponsored Projects Program: DAIR Founder and Executive Director Dr. Timnit Gebru is "advised by Prof. Safiya Noble and Dr. Ciira wa Maina." (DAIR's own December 2, 2021 press release, also fetched, names no advisors — the advisor naming sits in the fiscal sponsor's announcement, exactly as the body states.)
Comparison: The body's specific framing — Noble named alongside Ciira wa Maina as advisor in the December 2021 fiscal-sponsorship announcement — is confirmed by that announcement itself, retrieved this pass for the first time (pass 1 could not reach it). RESOLVED from pass-1 uncorroborated.
Decision: primary-sourced

## Claim 23: Noble "now sits as a board member" at DAIR

Source: https://www.dair-institute.org/team
Source tier: primary
Source content: DAIR's team page lists "Safiya Noble — Board Member" and "Ciira wa Maina — Board Member" under the "Board Members" section.
Comparison: Current board membership confirmed by DAIR's own published team listing.
Decision: primary-sourced

## Claim 24: Joana Varon and Paz Peña authored the GISWatch 2019 chapter "Decolonising AI: A transfeminist approach to data and social justice"

Source: https://giswatch.org/2019-artificial-intelligence-human-rights-social-justice-and-development
Source tier: primary
Source content: GISWatch 2019 carries the chapter "Decolonising AI: A transfeminist approach to data and social justice" by Paz Peña and Joana Varon.
Comparison: Chapter title, authors, and parent volume year/theme match the publication's own site.
Decision: primary-sourced

## Claim 25: reviewer formulations — Emily Drabinski on "hidden infrastructures ... hard-coded with white supremacy and misogyny" and Hans Rollman on search engines that "replicate the power structures of the western countries where they are built"

Source: https://en.wikipedia.org/wiki/Algorithms_of_Oppression + https://nyupress.org/9781479837243/algorithms-of-oppression/
Source tier: mainstream
Source content: Wikipedia (Drabinski, LARB): "What emerges from these pages is the sense that Google's algorithms of oppression comprise just one of the hidden infrastructures that govern our daily lives, and that the others are likely just as hard-coded with white supremacy and misogyny as the one that Noble explores." NYU Press page (PopMatters/Rollman): search engines are "not simply imperfect machines, but systems designed by humans in ways that replicate the power structures of the western countries where they are built, complete with all the sexism and racism that are built into those structures."
Comparison: Both quoted fragments match verbatim, including "the western countries" (this pass's NYU Press fetch shows the definite article is in the source, clearing pass 1's paraphrase note). Each reviewer's quote rests on one source (Drabinski via Wikipedia only; Rollman via the publisher's blurb), so the compound claim carries the lighter-sourcing label.
Decision: single-source
