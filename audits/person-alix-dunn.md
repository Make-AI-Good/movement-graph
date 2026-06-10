---
entity_id: person-alix-dunn
entity_hash: a0c0b5ed45a311d222749d66e5771fd501ec53e0
audit_date: 2026-06-01
pass: 1
status: supported
claims_total: 12
claims_corroborated: 9
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 3
sources_consulted:
  - https://www.foxglove.org.uk/2024/09/09/alix-non-executive-director/
  - https://www.foxglove.org.uk/who-we-are/people/alix-dunn/
  - https://www.alixdunn.com/about
---

## Claim 1: "Non-Executive Director of [Foxglove](../organizations/org-foxglove.md) since [September 2024]"

Source: https://www.foxglove.org.uk/2024/09/09/alix-non-executive-director/
Source content: Page dated 09.09.2024 announces Dunn's appointment as Non-Executive Director; corroborated by the Foxglove people page which lists her current title as "Non-Executive Director".
Comparison: Title and approximate start date (September 2024) both match cited Foxglove sources.
Decision: corroborated

## Claim 2: "having previously sat on Foxglove's Advisory Council from the organisation's inception"

Source: https://www.foxglove.org.uk/2024/09/09/alix-non-executive-director/
Source content: "Alix has been a member of Foxglove's Advisory Council from day one."
Comparison: "from the organisation's inception" is a paraphrase of "from day one"; semantic content matches.
Decision: corroborated

## Claim 3: "Founder of [The Maybe](https://www.alixdunn.com/about) (formerly Computer Says Maybe)"

Source: https://www.alixdunn.com/about ; https://www.foxglove.org.uk/who-we-are/people/alix-dunn/
Source content: Personal site describes her as "founder and director of The Maybe" with no mention of Computer Says Maybe. Foxglove people page describes her as "the founder and CEO of Computer Says Maybe, a public-interest firm focused on technology and society" with no mention of The Maybe.
Comparison: Neither cited source confirms the "formerly Computer Says Maybe" rebrand link — one source names The Maybe only, the other names Computer Says Maybe only, and neither bridges them. The relationship between the two names cannot be resolved from the cited sources.
Decision: uncorroborated

## Claim 4: "[The Maybe is] a consultancy and media studio on technology and society"

Source: https://www.alixdunn.com/about ; https://www.foxglove.org.uk/who-we-are/people/alix-dunn/
Source content: Personal site: The Maybe is "a consultancy, collective, and media agency" focused on "cutting edge, multi-disciplinary collaborations". Foxglove people page: Computer Says Maybe is "a public-interest firm focused on technology and society".
Comparison: The body's description blends The Maybe's structural shape ("consultancy, ... media agency") with Computer Says Maybe's stated topical focus ("technology and society"). Because the rebrand link in Claim 3 is unverifiable, the merged description cannot be attributed to a single sourced entity.
Decision: uncorroborated

## Claim 5: "host of the *Computer Says Maybe* podcast"

Source: https://www.foxglove.org.uk/who-we-are/people/alix-dunn/
Source content: Foxglove people page states Dunn "hosts the Computer Says Maybe podcast."
Comparison: Direct match.
Decision: corroborated

## Claim 6: "co-founder of The Engine Room"

Source: https://www.alixdunn.com/about ; https://www.foxglove.org.uk/who-we-are/people/alix-dunn/
Source content: Personal site: "Alix co-founded The Engine Room". Foxglove people page: she "co-founded and directed The Engine Room".
Comparison: Both cited sources confirm co-founder role.
Decision: corroborated

## Claim 7: "[The Engine Room is] a global non-profit supporting activist organisations to incorporate technology into their work"

Source: https://www.foxglove.org.uk/who-we-are/people/alix-dunn/ ; https://www.alixdunn.com/about
Source content: Foxglove people page describes The Engine Room as "a global non-profit supporting activist organizations." Personal site describes it as "a pioneering organisation that helped activist groups around the world use technology strategically."
Comparison: Two canonical sources confirm: global scope, non-profit status, and supporting activist organisations on technology use. Semantic content matches within paraphrase tolerance.
Decision: corroborated

## Claim 8: "Currently a trustee of the [Ada Lovelace Institute](../organizations/org-ada-lovelace-institute.md)"

Source: https://www.foxglove.org.uk/who-we-are/people/alix-dunn/
Source content: Foxglove people page states Dunn "is a trustee of the Ada Lovelace Institute for AI & Society."
Comparison: Trustee role at Ada Lovelace Institute directly confirmed by a canonical source. (Personal site mentions advising the Ada Lovelace Institute but does not name a trustee role; the Foxglove page is the authoritative source here.)
Decision: corroborated

## Claim 9: "senior advisor to AI Now and the AI Collaborative"

Source: https://www.alixdunn.com/about
Source content: Personal site references "advising organisations like AI Now Institute" and "the AI Collaborative" but does not assign a specific title such as "senior advisor". Neither Foxglove source mentions AI Now or the AI Collaborative.
Comparison: Cited sources confirm an advisory relationship in general terms but do not confirm the specific "senior advisor" title named in the body. Per the source rule, title-specificity beyond what sources state cannot be verified from cited sources alone.
Decision: uncorroborated

## Claim 10: scalar:sources[0].note — "Foxglove's September 2024 announcement of Dunn's appointment as Non-Executive Director, noting she had been on the Advisory Council since the organisation's inception"

Source: https://www.foxglove.org.uk/2024/09/09/alix-non-executive-director/
Source content: Page dated 09.09.2024 announcing the Non-Executive Director appointment; includes "Alix has been a member of Foxglove's Advisory Council from day one."
Comparison: Note describes the announcement page accurately, including the Advisory Council inception claim. Frontmatter scalar `sources[0].note`.
Decision: corroborated

## Claim 11: scalar:sources[1].note — "Foxglove's own people page for Dunn — current title, prior roles, and ongoing affiliations"

Source: https://www.foxglove.org.uk/who-we-are/people/alix-dunn/
Source content: People page carries current title (Non-Executive Director), prior roles (Engine Room co-founder), and ongoing affiliations (Computer Says Maybe, Ada Lovelace Institute trustee, RealML advisory).
Comparison: Note is a faithful descriptive summary of the people page. Frontmatter scalar `sources[1].note`.
Decision: corroborated

## Claim 12: scalar:sources[2].note — "Dunn's personal site — self-described role as founder of The Maybe and current advisory affiliations"

Source: https://www.alixdunn.com/about
Source content: Personal site self-describes Dunn as "founder and director of The Maybe" and lists advisory relationships with "AI Now Institute" and "the AI Collaborative" among others.
Comparison: Note accurately describes the personal site's content — founder of The Maybe is self-stated; advisory affiliations are listed. Frontmatter scalar `sources[2].note`.
Decision: corroborated
