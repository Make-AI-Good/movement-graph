---
entity_id: pub-atlas-of-ai
entity_hash: b22d484b731dcebaeb7ae4eecddd1b3fb7161043
audit_date: 2026-06-11
pass: 2
status: corroborated
claims_total: 35
claims_corroborated: 31
claims_primary_sourced: 4
claims_single_source: 0
claims_uncorroborated: 0
open_corrections: 0
sources_consulted:
  - https://en.wikipedia.org/wiki/Atlas_of_AI
  - https://en.wikipedia.org/wiki/Kate_Crawford
  - https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
  - https://katecrawford.net/atlas
  - https://katecrawford.net/
  - https://www.technologyreview.com/2021/04/23/1023549/kate-crawford-atlas-of-ai-review/
  - https://knowingmachines.org/
  - https://knowingmachines.org/about
  - https://www.microsoft.com/en-us/research/people/kate/
  - https://www.microsoft.com/en-us/research/podcast/keeping-an-eye-on-ai-with-dr-kate-crawford/
  - https://anatomyof.ai/
---

Pass 2 (2026-06-11). Entity changed since pass 1 only in frontmatter (`authors: []` → `authors: [person-kate-crawford]`; `last_updated`). Body byte-identical to the pass-1 audited text, so pass-1 claim records carry forward; this pass re-verified the authorship surface (Claim 1) and re-attempted the four pass-1 uncorroborated claims (5, 23, 28, 29) with fresh fetches — all four now resolve primary-sourced.

## Claim 1: "2021 book by the AI-and-power scholar Kate Crawford" (and frontmatter `authors: [person-kate-crawford]`)

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: Yale page names "Kate Crawford" as the author; Wikipedia (Kate_Crawford, fetched this pass): "She published a book Atlas of AI: Power, Politics, and the Planetary Costs of Artificial Intelligence through Yale University Press in 2021."
Comparison: Author and year confirmed across publisher (primary) and Wikipedia. The new frontmatter scalar `authors: [person-kate-crawford]` matches the verified authorship (scalar path: authors).
Decision: corroborated

## Claim 2: "published by Yale University Press in eBook on 6 April 2021 (ISBN 9780300252392)"

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: "eBook: Published Tuesday, 6 Apr 2021 | ISBN: 9780300252392" (re-confirmed this pass).
Comparison: Publisher, format, date, and ISBN match Yale's own listing.
Decision: corroborated

## Claim 3: "paperback on 16 August 2022 (ISBN 9780300264630), 336 pages with 31 black-and-white illustrations"

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: "Paperback: Published Tuesday, 16 Aug 2022 | ISBN: 9780300264630"; "336 pages, 31 b-w illustrations" (pass-1 record).
Comparison: All four mechanical facts match.
Decision: corroborated

## Claim 4: "hardcover edition (ISBN 9780300209570) following on 25 May 2021"

Source: https://en.wikipedia.org/wiki/Atlas_of_AI
Source tier: tiebreaker
Source content: ISBN 9780300209570; "Publication Date: May 25, 2021".
Comparison: ISBN and date match Wikipedia infobox (named-entity definitional fact — Wikipedia-alone sufficient per source rule).
Decision: corroborated

## Claim 5: "translated into twelve languages"

Source: https://katecrawford.net/
Source tier: primary
Source content: "has been translated into twelve languages" (author's own site homepage, fetched this pass; the body's inline-cited /atlas subpage no longer carries the count, but the claim stands on the author site itself).
Comparison: Count matches the author's own site — a single primary-tier source. Resolved from pass-1 uncorroborated.
Decision: primary-sourced

## Claim 6: "won three international prizes"

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: Yale lists "CHOICE Outstanding Academic Titles 2021", "Winner of the 2022 Sally Hacker Prize, sponsored by the Society for the History of Technology (SHOT)", "Winner of the 2022 Best Information Science Book of the Year Award, sponsored by ASIS&T" (re-confirmed this pass); katecrawford.net homepage (this pass): "won three international prizes".
Comparison: Three named prizes match the count; the author site now also states the count directly.
Decision: corroborated

## Claim 7: "2022 Sally Hacker Prize from the Society for the History of Technology"

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: "Winner of the 2022 Sally Hacker Prize, sponsored by the Society for the History of Technology (SHOT)" (re-confirmed this pass).
Comparison: Exact match.
Decision: corroborated

## Claim 8: "2022 ASIS&T Best Information Science Book of the Year"

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: "Winner of the 2022 Best Information Science Book of the Year Award, sponsored by ASIS&T" (re-confirmed this pass).
Comparison: Award name, year, and conferring body match.
Decision: corroborated

## Claim 9: "2021 CHOICE Outstanding Academic Titles recognition"

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: "CHOICE Outstanding Academic Titles 2021" (re-confirmed this pass); Wikipedia: "2021 Choice Outstanding Academic Titles booklist".
Comparison: Confirmed by publisher and Wikipedia.
Decision: corroborated

## Claim 10: "named one of the best books on technology of 2021 by the Financial Times"

Source: https://katecrawford.net/atlas
Source tier: primary
Source content: "*Atlas of AI* was named one of the best books on technology in 2021 by the Financial Times" (re-confirmed this pass).
Comparison: Verbatim match.
Decision: corroborated

## Claim 11: "one of the New Scientist year-end booklist picks"

Source: https://en.wikipedia.org/wiki/Atlas_of_AI
Source tier: tiebreaker
Source content: "included on the year end booklists of...New Scientist" (pass-1 record).
Comparison: Confirmed (public-record booklist inclusion).
Decision: corroborated

## Claim 12: Karen Hao endorsement — "It's a masterpiece, and I haven't been able to stop thinking about it"

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: Karen Hao, *MIT Tech Review*: "It's a masterpiece, and I haven't been able to stop thinking about it." (pass-1 record).
Comparison: Verbatim match.
Decision: corroborated

## Claim 13: Virginia Dignum endorsement — "Meticulously researched and superbly written"

Source: https://yalebooks.yale.edu/book/9780300264630/atlas-of-ai/
Source tier: primary
Source content: Virginia Dignum, *Nature*: "Exposes the dark side of AI's success. . . . Meticulously researched and superbly written." (pass-1 record).
Comparison: The body's quoted fragment is verbatim in Dignum's blurb; outlet attribution matches.
Decision: corroborated

## Claim 14: "endorsements from Ruha Benjamin, Simone Browne, Wendy Hui Kyong Chun, Peter Galison, Geoffrey Bowker, Alondra Nelson, and Lucy Suchman"

Source: https://katecrawford.net/atlas
Source tier: primary
Source content: "Ruha Benjamin, Simone Browne, Wendy Hui Kyong Chun, Peter Galison, Geoffrey C. Bowker, Alondra Nelson, and Lucy Suchman all provided testimonials." (pass-1 record).
Comparison: All seven names match (middle initial "C." in Bowker unstated in body; name match unambiguous).
Decision: corroborated

## Claim 15: Chapter content — lithium mining / Amazon warehouses and Mechanical Turk / ImageNet and Amazon hiring classifier / affective computing / Project Maven / AlphaGo as brute force / tech-billionaire spaceflight critique

Source: https://en.wikipedia.org/wiki/Atlas_of_AI
Source tier: tiebreaker
Source content: Wikipedia overview confirms Big Tech resource extraction and labor exploitation; "Amazon warehouses and the Amazon Mechanical Turk"; ImageNet and "a failed Amazon project to classify job applicants"; affective computing with Ekman's FACS; "Project Maven" military image recognition; AlphaGo as "a natural product of massive brute-force calculation"; tech billionaires' "fantasies of developing private spaceflight" (pass-1 record).
Comparison: Each named chapter component matches Wikipedia's overview within paraphrase tolerance.
Decision: corroborated

## Claim 16: Karen Hao's MIT Technology Review feature, dated 23 April 2021, titled "Stop talking about AI ethics. It's time to talk about power."

Source: https://www.technologyreview.com/2021/04/23/1023549/kate-crawford-atlas-of-ai-review/
Source tier: mainstream
Source content: "Date: April 23, 2021"; "Full Title: 'Stop talking about AI ethics. It's time to talk about power.'"; "Author: Karen Hao" (pass-1 record).
Comparison: Date, title, author, outlet all match.
Decision: corroborated

## Claim 17: Hao's review "traces the case-study chain from Silicon Valley to the Clayton Valley lithium-mining operations in Nevada"

Source: https://www.technologyreview.com/2021/04/23/1023549/kate-crawford-atlas-of-ai-review/
Source tier: mainstream
Source content: "There she investigates the destructive environmental practices required to obtain the lithium that powers the world's computers." Wikipedia confirms Thacker Pass in Nevada's Clayton Valley as the named field site (pass-1 record).
Comparison: Cross-checked Hao + Wikipedia confirm Nevada / Clayton Valley lithium as a named case in the review and book.
Decision: corroborated

## Claim 18: Hao "treats the Amazon fulfilment centres as the labour-mechanisation case"

Source: https://www.technologyreview.com/2021/04/23/1023549/kate-crawford-atlas-of-ai-review/
Source tier: mainstream
Source content: "The Amazon fulfillment centers where human bodies have been mechanized in the company's relentless pursuit of growth and profit." (pass-1 record).
Comparison: Direct match.
Decision: corroborated

## Claim 19: Hao "reads Samuel Morton's 19th-century skull collection as the historical pre-figuration of contemporary algorithmic classification"

Source: https://www.technologyreview.com/2021/04/23/1023549/kate-crawford-atlas-of-ai-review/
Source tier: mainstream
Source content: Morton named as "a 19th-century American craniologist, who believed it was possible to 'objectively' divide [human skulls] by their physical measurements into the five 'races' of the world"; "Crawford draws parallels between Morton's classification work and modern AI systems that classify the world into fixed categories" (pass-1 record).
Comparison: Person, century, and the classification-pre-figuration framing all confirmed.
Decision: corroborated

## Claim 20: The "often-cited Crawford line that AI 'is neither artificial nor intelligent — we're just looking at forms of statistical analysis at scale'"

Source: https://www.technologyreview.com/2021/04/23/1023549/kate-crawford-atlas-of-ai-review/
Source tier: mainstream
Source content: "It's the *opposite* of artificial. It comes from the most material parts of the Earth's crust and from human bodies laboring... Neither is it intelligent." And separately: "we're just looking at forms of statistical analysis at scale that have as many problems as the data that it's given." (pass-1 record).
Comparison: The body's quoted line is a paraphrastic stitch of two separate source passages; body's "often-cited Crawford line" framing does not present it as a single verbatim Hao quotation. Semantic content matches within paraphrase tolerance.
Decision: corroborated

## Claim 21: Closing call to "contend with the environmental footprint of the systems and the very real forms of labor exploitation"

Source: https://www.technologyreview.com/2021/04/23/1023549/kate-crawford-atlas-of-ai-review/
Source tier: mainstream
Source content: "We have to contend with the environmental footprint of the systems. We have to contend with the very real forms of labor exploitation." (pass-1 record).
Comparison: The body's quoted run is a compression of two consecutive source sentences; semantic content matches within paraphrase tolerance.
Decision: corroborated

## Claim 22: "Crawford holds a PhD from the University of Sydney"

Source: https://en.wikipedia.org/wiki/Kate_Crawford
Source tier: tiebreaker
Source content: "Crawford holds 'a PhD from the University of Sydney.'" (pass-1 record).
Comparison: Direct match (named-entity definitional fact — Wikipedia-alone sufficient).
Decision: corroborated

## Claim 23: "Senior Principal Researcher at Microsoft Research New York in the Social Media Collective"

Source: https://www.microsoft.com/en-us/research/people/kate/
Source tier: primary
Source content: Microsoft Research's own people page (fetched this pass): she is a "Senior Principal Researcher at Microsoft Research New York." Wikipedia says "principal researcher at Microsoft Research (Social Media Collective)" without the "Senior" qualifier.
Comparison: The employer's own page — primary tier for an employment title — confirms the "Senior Principal Researcher" qualifier Wikipedia lacked; Wikipedia supplies the Social Media Collective placement. Resolved from pass-1 uncorroborated.
Decision: primary-sourced

## Claim 24: "Research Professor at the University of Southern California"

Source: https://en.wikipedia.org/wiki/Kate_Crawford
Source tier: tiebreaker
Source content: "Research Professor at USC Annenberg School for Communication and Journalism" (pass-1 record).
Comparison: Confirmed (USC + Research Professor title — official role).
Decision: corroborated

## Claim 25: "inaugural Visiting Chair of AI and Justice at the École Normale Supérieure in Paris (2019)"

Source: https://en.wikipedia.org/wiki/Kate_Crawford
Source tier: tiebreaker
Source content: "In 2019, Crawford 'was the inaugural holder of the AI & Justice visiting chair at École Normale Supérieure in Paris, in partnership with the Fondation Abeona.'" (pass-1 record).
Comparison: Year, inaugural status, chair name, and institution match.
Decision: corroborated

## Claim 26: "co-founder and former director of research of the AI Now Institute at NYU"

Source: https://en.wikipedia.org/wiki/Kate_Crawford
Source tier: tiebreaker
Source content: "Co-founder and former director of research at the AI Now Institute at NYU" (pass-1 record); katecrawford.net homepage (this pass): "co-founded multiple research institutes, including FATE ... and the AI Now Institute (NYU)".
Comparison: Verbatim match, now also confirmed by the subject's own site.
Decision: corroborated

## Claim 27: "former visiting professor at the MIT Center for Civic Media"

Source: https://en.wikipedia.org/wiki/Kate_Crawford
Source tier: tiebreaker
Source content: "Former visiting professor at MIT Center for Civic Media" (pass-1 record).
Comparison: Verbatim match.
Decision: corroborated

## Claim 28: "co-founder of FATE (Fairness, Accountability, Transparency and Ethics in AI)"

Source: https://katecrawford.net/
Source tier: primary
Source content: Author's own site homepage (fetched this pass): "co-founded multiple research institutes, including FATE (Fairness, Accountability, Transparency and Ethics in AI, based at MSR)". Crawford on Microsoft Research's own podcast page (fetched this pass): "that was the reason we formed the FATE group here in New York."
Comparison: The subject's own site states the co-founding directly and her statement on the employer's site is consistent. Both sources trace to Crawford herself, so they are not independent — one primary source class, not two-source corroboration. Resolved from pass-1 uncorroborated.
Decision: primary-sourced

## Claim 29: Anatomy of an AI System with Vladan Joler, 2018, "subsequently acquired by MoMA and held in the permanent collections of the V&A, the Ars Electronica Center, and the Design Museum London"

Source: https://katecrawford.net/
Source tier: primary
Source content: Author's own site homepage (fetched this pass): the work "is in the permanent collections of the Museum of Modern Art (MoMA) in New York, the Victoria and Albert Museum (V&A) in London, the Ars Electronica Center, and the Design Museum in London". Wikipedia (this pass): "It is in the permanent collection of the Museum of Modern Art in New York and the Victoria and Albert Museum in London." anatomyof.ai itself (this pass) states only the 2018 temporary V&A exhibition, not permanent holdings.
Comparison: The full four-institution holdings list matches the creator's own site (primary, single source); Wikipedia independently corroborates the MoMA and V&A subset; Joler authorship and 2018 date confirmed by Wikipedia in pass 1. Resolved from pass-1 uncorroborated.
Decision: primary-sourced

## Claim 30: "Training Humans with Trevor Paglen (2019)"

Source: https://en.wikipedia.org/wiki/Kate_Crawford
Source tier: tiebreaker
Source content: "Training Humans: Collaboration with Trevor Paglen, exhibited at Prada Foundation Milan in 2019" (pass-1 record).
Comparison: Collaborator and year match.
Decision: corroborated

## Claim 31: "Calculating Empires: A Genealogy of Technology and Power since 1500 exhibition with Vladan Joler that won the Silver Lion at the 2025 Venice Architecture Biennale"

Source: https://en.wikipedia.org/wiki/Kate_Crawford
Source tier: tiebreaker
Source content: "Calculating Empires: Co-created with Vladan Joler; 'received the Silver Lion at the Venice Biennale of Architecture 2025'" (pass-1 record).
Comparison: Collaborator, award, venue, and year all match.
Decision: corroborated

## Claim 32: Knowing Machines Project — "a research project tracing the histories, practices, and politics of how machine learning systems are trained to interpret the world"

Source: https://knowingmachines.org/
Source tier: primary
Source content: "Knowing Machines is a research project tracing the histories, practices, and politics of how machine learning systems are trained to interpret the world." (pass-1 record).
Comparison: Verbatim match.
Decision: corroborated

## Claim 33: Knowing Machines is "Sloan-Foundation-funded"

Source: https://knowingmachines.org/
Source tier: primary
Source content: "Knowing Machines is sponsored by the Alfred P. Sloan Foundation." (pass-1 record).
Comparison: Funder confirmed.
Decision: corroborated

## Claim 34: "Crawford directs" Knowing Machines

Source: https://knowingmachines.org/about
Source tier: primary
Source content: "Kate Crawford (Lead-PI)"; "she currently leads the Knowing Machines Project" (pass-1 record).
Comparison: "Directs" matches "leads / Lead-PI" within paraphrase tolerance.
Decision: corroborated

## Claim 35: Knowing Machines outputs include "Calculating Empires exhibition, Models all the Way Down visual investigation, Synthetic Media collection, Bird in hand collection, Knowing Legal Machines collection, the Generative AI Legal Explainer, the 9 ways to see a Dataset essays, A Critical Field Guide for Working with Machine Learning Datasets, and the Critical Dataset Studies reading list"

Source: https://knowingmachines.org/
Source tier: primary
Source content: Listed outputs include "Calculating Empires, Models all the Way Down, Synthetic Media, Understanding the Work of Dataset Creators, Bird in hand, Generative AI Legal Explainer, Knowing Legal Machines, 9 ways to see a Dataset, A Critical Field Guide for Working with Machine Learning Datasets, Critical Dataset Studies" (pass-1 record).
Comparison: Every named output in the body appears in the project's own output list.
Decision: corroborated
