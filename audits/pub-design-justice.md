---
entity_id: pub-design-justice
entity_hash: 9083e9cc9e4de343fa3c18f06ebb287ff3d063fb
audit_date: 2026-06-08
pass: 1
status: corrections-pending
claims_total: 27
claims_corroborated: 20
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 3
reclassified_at: 2026-06-10
claims_uncorroborated: 4
sources_consulted:
  - https://news.mit.edu/2020/design-justice-book-0304
  - http://designjustice.org/djnhistory
  - https://designjustice.org/read-the-principles
  - https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
  - https://just-tech.ssrc.org/our-network/sasha-costanza-chock/
  - https://www.ajl.org/about
  - https://en.wikipedia.org/wiki/Stochastic_parrot
  - https://en.wikipedia.org/wiki/Joy_Buolamwini
  - https://mitpress.mit.edu/9780262043458/design-justice/ (HTTP 403)
  - https://designjustice.mitpress.mit.edu/ (HTTP 403)
  - https://www.proseawards.com/2021-finalists-and-category-winners/ (HTTP 404)
  - https://codingrights.org/oracle-for-transfeminist-technologies/ (HTTP 404)
---

## Claim 1: "2020 MIT Press monograph by Sasha Costanza-Chock"

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: "Design Justice: Community-Led Practices to Build the Worlds We Need (MIT Press, March 2020)"
Comparison: Author, publisher, and year all match.
Decision: corroborated

## Claim 2: "published in March 2020"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: MIT News launch coverage dated March 3, 2020.
Comparison: March 2020 publication confirmed.
Decision: corroborated

## Claim 3: "named a 2021 PROSE Award finalist in Engineering & Technology"

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: "2021 Engineering & Technology PROSE Award Finalist for their book Design Justice"
Comparison: Finalist status, year (2021), and category (Engineering & Technology) all match.
Decision: corroborated

## Claim 4: "ISBN 9780262043458"

Source: no canonical source found (primary source https://mitpress.mit.edu/9780262043458/design-justice/ returned HTTP 403 in this session; the open-access PubPub edition https://designjustice.mitpress.mit.edu/ also returned 403)
Source content: not retrieved.
Comparison: The ISBN is embedded in the entity's two MIT Press URLs (which themselves were unreachable in this session); no fetched canonical source independently states the ISBN. The claim is plausible but the comparison cannot be made.
Decision: uncorroborated

## Claim 5: "open-access reading edition on MIT Press's PubPub platform" at designjustice.mitpress.mit.edu

Source: no canonical source found (https://designjustice.mitpress.mit.edu/ returned HTTP 403)
Source content: not retrieved.
Comparison: The URL form is consistent with MIT Press PubPub-hosted open editions, but the page contents (open-access status, table of contents) could not be retrieved this session.
Decision: uncorroborated

## Claim 6: "on Costanza-Chock's own published account, it has been cited more than 3,000 times"

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: "Cited over 3,000 times"
Comparison: The underlying claim ("more than 3,000 times") is supported by Wikipedia. Note: the body links this claim to the SSRC Just Tech profile (https://just-tech.ssrc.org/our-network/sasha-costanza-chock/), which in the fetched content did not state a citation count — see Claim 6b on the source attribution.
Decision: corroborated

## Claim 6b: scalar:sources[8].note — "Social Science Research Council Just Tech profile of Costanza-Chock — primary source for Costanza-Chock's own report that the book has been cited more than 3,000 times"

Source: https://just-tech.ssrc.org/our-network/sasha-costanza-chock/
Source content: The fetched Just Tech profile lists Costanza-Chock as "Director of Research & Sensemaking | OneProject.org / Associate Professor | Northeastern University" and names the publications #MoreThanCode (2018), Who Audits the Auditors? (2022), and Design Justice (2020), but does not state a citation count for Design Justice.
Comparison: The scalar attributes the "more than 3,000 times" claim to Just Tech as a primary source, but Just Tech does not state a citation count for the book in the content fetched this session. The claim itself is supported by Wikipedia (Claim 6), so the underlying fact stands; the discrepancy is in the source-attribution scalar.
Decision: correction

## Claim 7: '"a community of practice, and a framework for analysis"'

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: "Design justice is both a community of practice, and a framework for analysis"
Comparison: Verbatim match.
Decision: corroborated

## Claim 8: "apply Patricia Hill Collins's framework of the 'matrix of domination'"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: "structured by what the black feminist sociologist Patricia Hill Collins calls a 'matrix of domination'"
Comparison: Attribution of "matrix of domination" to Patricia Hill Collins matches.
Decision: corroborated

## Claim 9: matrix of domination "structured by white supremacy, heteropatriarchy, capitalism, ableism, and settler colonialism"

Source: https://news.mit.edu/2020/design-justice-book-0304 (the link the entity body uses for this claim)
Source content: "structured by what the black feminist sociologist Patricia Hill Collins calls a 'matrix of domination' in the form of white supremacy, heteropatriarchy, capitalism, and settler colonialism."
Comparison: The cited MIT News source lists four components (white supremacy, heteropatriarchy, capitalism, settler colonialism) and does NOT include "ableism". The body adds ableism as a fifth component, citing this MIT News article. The underlying book may include ableism in its formulation, but the linked canonical source does not — and the only other entity-cited source that lists ableism (https://mitpress.mit.edu/9780262043458/design-justice/) could not be reached this session (HTTP 403), so independent verification of the five-component list is not possible.
Decision: correction

## Claim 10: opening case is "the airport millimeter-wave scanner's binary-gender classification of nonbinary bodies"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: The article opens with Costanza-Chock's experience at airport security, where binary millimeter-wave scanners flag transgender and nonbinary bodies as "anomalous."
Comparison: Opening case and its content match.
Decision: corroborated

## Claim 11: "design reflects existing power structures"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: "There are biases built into everyday objects, including software interfaces, medical devices, social media, and the built environment, and these biases reflect existing power structures in society."
Comparison: Direct semantic and near-verbatim match.
Decision: corroborated

## Claim 12: "even diverse teams routinely build products for affluent users with constant connectivity"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: "they would by and large still be mostly organizing their time and energy around producing products that would be attractive to a very thin slice of the global population — people who have disposable income, always-on internet connectivity, and broadband."
Comparison: Semantic match (disposable income + always-on connectivity = "affluent users with constant connectivity").
Decision: corroborated

## Claim 13: "workforce-diversity alone … is necessary but not sufficient"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: Article establishes "workforce diversity alone is insufficient; design must center marginalized communities' needs beyond hiring initiatives."
Comparison: "Necessary but not sufficient" matches the source's framing.
Decision: corroborated

## Claim 14: "ten principles drafted, finalised, and released under Creative Commons across five years of Allied Media Conference convenings"

Source: http://designjustice.org/djnhistory and https://designjustice.org/read-the-principles
Source content: djnhistory traces the principles 2014→2018 (5-year span) across Allied Media Conference convenings, with 2018 finalisation released "under a Creative Commons license"; the principles page lists ten principles.
Comparison: All three elements (ten principles, Creative Commons, AMC convenings across roughly 2014–2018) match.
Decision: corroborated

## Claim 15: "2014 Future Design Lab launch at AMC"

Source: http://designjustice.org/djnhistory
Source content: "2014: Future Design Lab Origins — The Future Design Lab emerged as a practice space at the Allied Media Conference"
Comparison: Year and venue match.
Decision: corroborated

## Claim 16: "21 June 2015 'Generating Shared Principles for Design Justice' session at AMC Detroit (thirty designers, artists, technologists, and community organizers)"

Source: http://designjustice.org/djnhistory
Source content: "June 21, 2015 … Thirty people gathered at the Allied Media Conference in Detroit for a session titled 'Generating Shared Principles for Design Justice.' Participants identified as 'designers, artists, technologists, and community organizers.'"
Comparison: Date, title, venue (Detroit AMC), count (thirty), and participant categories all match.
Decision: corroborated

## Claim 17: "2016 Network-establishing AMC gathering"

Source: http://designjustice.org/djnhistory
Source content: "2016: Network Establishment — The Design Justice Network Gathering at the Allied Media Conference brought together 30 design practitioners and community organizers to collaboratively edit and refine the principles"
Comparison: Year and network-establishing AMC gathering match.
Decision: corroborated

## Claim 18: "2018 finalisation at the AMC Design Justice Track"

Source: http://designjustice.org/djnhistory
Source content: "2018: Principles Finalized — The principles were officially shared with the network at the Design Justice Track at the Allied Media Conference and released under a Creative Commons license"
Comparison: Year, venue (AMC Design Justice Track), and finalisation match.
Decision: corroborated

## Claim 19: Principle 3 verbatim — "We prioritize design's impact on the community over the intentions of the designer"

Source: https://designjustice.org/read-the-principles
Source content: "We prioritize design's impact on the community over the intentions of the designer."
Comparison: Verbatim match with the source as the entity body and frontmatter sources[4].note both quote it.
Decision: corroborated

## Claim 20: '"Nothing About Us Without Us" as the disability-rights inheritance Principle 3 carries forward'

Source: https://designjustice.org/read-the-principles (no result); https://mitpress.mit.edu/9780262043458/design-justice/ (HTTP 403); https://en.wikipedia.org/wiki/Sasha_Costanza-Chock (no result for this phrase)
Source content: WebFetch on https://designjustice.org/read-the-principles reports: '"Nothing About Us Without Us" / Disability Rights Reference: Not found in this document.' The MIT Press page (the body's cited source for this phrase) returned HTTP 403; no fetched canonical source confirms the phrase or its tie to Principle 3.
Comparison: The cited primary source (MIT Press) was unreachable; the Design Justice Network's own principles page does not surface the phrase. The book itself does discuss disability-rights inheritance per movement-knowledge, but no fetched canonical source verifies the specific Principle-3-carries-forward attribution.
Decision: uncorroborated

## Claim 21: Allied Media Projects is the Design Justice Network's institutional sponsor

Source: https://designjustice.org/read-the-principles and http://designjustice.org/djnhistory
Source content: principles page: "The Design Justice Network is a sponsored project of Allied Media Projects"; djnhistory: "The Design Justice Network operates as 'a sponsored project of Allied Media Projects'"
Comparison: Two independent DJN pages confirm.
Decision: corroborated

## Claim 22: "Costanza-Chock has been Director of Research and Design" of the AJL CRASH project

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock and https://www.ajl.org/about
Source content: Wikipedia: "Research Director of the Algorithmic Justice League." AJL's own about page does not mention Costanza-Chock at all, naming only Joy Buolamwini as Founder; AJL's about page also does not surface CRASH.
Comparison: The body claim uses the title "Director of Research and Design" of the CRASH project. The closest canonical title in the canonical sources fetched is Wikipedia's "Research Director of the Algorithmic Justice League" — same role-domain but a different role title, and applied to AJL the organization rather than CRASH the project. "Research Director" and "Director of Research and Design" are not semantically equivalent (the latter names "Design" as a domain the former does not). The CRASH-specific project leadership claim is not confirmed in fetched canonical sources.
Decision: correction

## Claim 23: "Oracle for Transfeminist Technologies, co-conceived by Costanza-Chock with Joana Varon in partnership with the Design Justice Network"

Source: no canonical source found (https://codingrights.org/oracle-for-transfeminist-technologies/, https://codingrights.org/en/oracle-for-transfeminist-technologies/, https://oracle.codingrights.org/, and https://www.codingrights.org/oracle/ all returned HTTP 404 or TLS errors this session; the Coding Rights main page https://www.codingrights.org/ did not surface the Oracle project in the fetched content)
Source content: not retrieved.
Comparison: No canonical source could be fetched this session to verify the co-conception attribution (Costanza-Chock with Varon in partnership with DJN). The underlying claim is plausible from movement-knowledge but cannot be cross-checked against a fetched canonical source.
Decision: uncorroborated

## Claim 24: "Gender Shades (2018)"

Source: https://en.wikipedia.org/wiki/Joy_Buolamwini and https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: "Her 2018 paper Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification…"
Comparison: 2018 date verified.
Decision: corroborated

## Claim 25: "Stochastic Parrots (2021)"

Source: https://en.wikipedia.org/wiki/Stochastic_parrot
Source content: The paper "was later presented at the 2021 ACM Conference" with the reference listing the publication as "March 2021."
Comparison: 2021 date verified.
Decision: corroborated

## Claim 26: "Out of the Shadows, into the Streets!" listed as Costanza-Chock's earlier MIT Press monograph (2014)

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: "Out of the Shadows, into the Streets! Transmedia Organizing and the Immigrant Rights Movement (MIT Press, 2014)"
Comparison: Title, publisher, and year all match.
Decision: corroborated
