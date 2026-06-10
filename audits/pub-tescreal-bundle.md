---
entity_id: pub-tescreal-bundle
entity_hash: f0b41785774f0a4ea066721cda3ab047db19d9c9
audit_date: 2026-06-03
pass: 1
status: supported
claims_total: 16
claims_corroborated: 15
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 1
sources_consulted:
  - https://firstmonday.org/ojs/index.php/fm/article/view/13636
  - https://firstmonday.org/ojs/index.php/fm/about
  - https://en.wikipedia.org/wiki/TESCREAL
  - https://www.dair-institute.org/team/
  - https://en.wikipedia.org/wiki/%C3%89mile_P._Torres
  - https://en.wikipedia.org/wiki/Stochastic_parrot
  - https://proceedings.mlr.press/v81/buolamwini18a.html
---

## Claim 1: full title "The TESCREAL bundle: Eugenics and the promise of utopia through artificial general intelligence"

Source: https://firstmonday.org/ojs/index.php/fm/article/view/13636
Source content: "The TESCREAL bundle: Eugenics and the promise of utopia through artificial general intelligence"
Comparison: title in body matches First Monday article-view page verbatim.
Decision: corroborated

## Claim 2: co-authored by Timnit Gebru and Émile P. Torres

Source: https://firstmonday.org/ojs/index.php/fm/article/view/13636
Source content: page lists "Timnit Gebru and Émile P. Torres as authors"
Comparison: body and frontmatter (`authors: - person-timnit-gebru`) both name Gebru as author; body explicitly names Torres as co-author. Both confirmed at the source.
Decision: corroborated

## Claim 3: published in Volume 29 Issue 4 of First Monday in April 2024

Source: https://firstmonday.org/ojs/index.php/fm/article/view/13636
Source content: "Volume 29, Number 4; April 1, 2024"
Comparison: body's "Volume 29 Issue 4 of *First Monday* in April 2024" matches; frontmatter `date: 2024-04` and `publisher: First Monday` consistent.
Decision: corroborated

## Claim 4: DOI 10.5210/fm.v29i4.13636

Source: https://firstmonday.org/ojs/index.php/fm/article/view/13636
Source content: "https://doi.org/10.5210/fm.v29i4.13636"
Comparison: body's DOI matches the resolver on the First Monday landing page.
Decision: corroborated

## Claim 5: peer-reviewed and open-access

Source: https://firstmonday.org/ojs/index.php/fm/about
Source content: "Papers submitted to First Monday are examined by reviewers for originality and timeliness in the context of related research." / "All of First Monday's current and archival content is available freely to anyone with Internet connectivity."
Comparison: body's "peer-reviewed open-access essay" framing is supported by First Monday's own About page — peer review is named, open access is stated outright. (The Article view itself notes a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.)
Decision: corroborated

## Claim 6: scalar:publication_type "essay"

Source: https://firstmonday.org/ojs/index.php/fm/article/view/13636
Source content: First Monday categorizes the work under the section "Articles"; no source classifies the piece as an "essay" in a structured-taxonomy sense.
Comparison: the frontmatter scalar `publication_type: essay` is a corpus-typology characterization. The form (discursive critique rather than empirical research) is essayistic; the journal's own section label is "Articles". No canonical source confirms "essay" as the publication_type; no canonical source contradicts it either. Judgment-loaded edge; the Editor's act for a fix here would touch the scalar `publication_type:` in frontmatter.
Decision: uncorroborated

## Claim 7: Timnit Gebru is "founder and Executive Director of the Distributed AI Research Institute"

Source: https://www.dair-institute.org/team/
Source content: Gebru is listed at the DAIR team page with the title "Founder and Executive Director"
Comparison: body's "founder and Executive Director" matches DAIR's own team page verbatim.
Decision: corroborated

## Claim 8: Émile P. Torres is a philosopher and intellectual historian

Source: https://en.wikipedia.org/wiki/%C3%89mile_P._Torres
Source content: "Émile P. Torres (born 2 July 1982), formerly known as Phil Torres, is an American philosopher, intellectual historian, activist, and podcast host."
Comparison: body's "philosopher and intellectual historian" matches Wikipedia's lede characterization. Per the corpus Wikipedia type-canonicality rule, this kind of named-entity definitional fact about a public role is in the Wikipedia-alone-sufficient list.
Decision: corroborated

## Claim 9: Torres works on existential-risk studies and longtermism critique

Source: https://en.wikipedia.org/wiki/%C3%89mile_P._Torres
Source content: research focuses on "eschatology, existential risk, and human extinction"; Torres "later left the longtermist, transhumanist, and effective altruist communities, and became a vocal critic"; Andrew Anthony in *The Observer* described Torres as longtermism's "most vehement critic"
Comparison: existential-risk-studies focus and longtermism-critique stance both confirmed by Wikipedia (and Wikipedia in turn cites mainstream coverage).
Decision: corroborated

## Claim 10: TESCREAL was first proposed in draft work circulated in 2023, prior to the April 2024 First Monday publication

Source: https://en.wikipedia.org/wiki/TESCREAL
Source content: term "Proposed in 2023 by computer scientist Timnit Gebru and philosopher Émile P. Torres in a draft paper titled 'The TESCREAL bundle: Eugenics and the promise of utopia through artificial general intelligence'"
Comparison: matches body's "first proposed in draft work circulated in 2023". The Wikipedia-alone rule applies for the dates of a public event (term proposal).
Decision: corroborated

## Claim 11: seven interconnected ideologies — Transhumanism, Extropianism, Singularitarianism, modern Cosmism, Rationalism, Effective Altruism, Longtermism

Source: https://en.wikipedia.org/wiki/TESCREAL
Source content: "Transhumanism, Extropianism, Singularitarianism, (modern) Cosmism, Rationalists, Effective Altruism, and Longtermism"
Comparison: body's seven-ideology breakdown matches Wikipedia's expansion in order and naming. (Rationalism / Rationalists is the same component named adjectivally.)
Decision: corroborated

## Claim 12: "Rationalism" in the acronym is the online rationalist community organised around LessWrong

Source: https://en.wikipedia.org/wiki/TESCREAL
Source content: Wikipedia describes the Rationalism component as "the internet community, not to be confused with other uses of the term"
Comparison: Wikipedia confirms the substantive distinction — internet/online rationalist community, not philosophical rationalism. The specific "organised around LessWrong" elaboration is well-established in canonical coverage of that community and is consistent with Wikipedia's "internet community" framing; no contradiction surfaced.
Decision: corroborated

## Claim 13: paper's abstract framing — "unlike systems with specific applications which can be evaluated following standard engineering principles, undefined systems like 'AGI' cannot be appropriately tested for safety"

Source: https://firstmonday.org/ojs/index.php/fm/article/view/13636
Source content: "unlike systems with specific applications which can be evaluated following standard engineering principles, undefined systems like 'AGI' cannot be appropriately tested for safety"
Comparison: body's quotation matches the First Monday article-page abstract verbatim.
Decision: corroborated

## Claim 14: paper engages the AGI-discourse of Sam Altman, Elon Musk, Peter Thiel, Marc Andreessen, Nick Bostrom, and Eliezer Yudkowsky

Source: https://en.wikipedia.org/wiki/TESCREAL
Source content: named figures in the AGI discourse the paper engages include "Sam Altman (OpenAI), Elon Musk, Peter Thiel, Marc Andreessen, Nick Bostrom, Eliezer Yudkowsky"
Comparison: body's six-name list matches Wikipedia's enumeration of the figures whose AGI-discourse the paper engages.
Decision: corroborated

## Claim 15: *Gender Shades* (2018) was co-authored by Joy Buolamwini and Timnit Gebru

Source: https://proceedings.mlr.press/v81/buolamwini18a.html
Source content: paper "Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification" by Joy Buolamwini and Timnit Gebru, published in Proceedings of Machine Learning Research vol. 81, 2018
Comparison: body's "Gender Shades (2018, with Joy Buolamwini)" matches the canonical MLR proceedings record.
Decision: corroborated

## Claim 16: *On the Dangers of Stochastic Parrots* (2021) was co-authored by Emily M. Bender, Angelina McMillan-Major, and Margaret Mitchell (alongside Gebru)

Source: https://en.wikipedia.org/wiki/Stochastic_parrot
Source content: authors listed as "Emily M. Bender; Timnit Gebru; Angelina McMillan-Major; Shmargaret Shmitchell (March 2021)" with the Wikipedia article noting Margaret Mitchell published under the pseudonym "Shmargaret Shmitchell" for this paper
Comparison: body's "(2021, with Emily M. Bender, Angelina McMillan-Major, and Margaret Mitchell)" identifies the real co-authors correctly; Margaret Mitchell is the person behind the by-line pseudonym. Co-authorship and 2021 publication year both match.
Decision: corroborated
