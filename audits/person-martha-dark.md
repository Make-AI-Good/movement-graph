---
entity_id: person-martha-dark
entity_hash: 017d691ed25b106bc5f8d55a37d380b34a000379
audit_date: 2026-06-10
pass: 2
status: corroborated
claims_total: 6
claims_corroborated: 1
claims_primary_sourced: 5
claims_single_source: 0
claims_uncorroborated: 0
open_corrections: 0
sources_consulted:
  - https://www.foxglove.org.uk/who-we-are/people/
  - https://www.foxglove.org.uk/who-we-are/people/martha-dark/
  - https://www.foxglove.org.uk/about/
  - https://find-and-update.company-information.service.gov.uk/company/12052097
---

## Claim 1: "Co-founder and co-executive director of Foxglove" (also affiliations[0]: role `co-founder and co-executive director`, period `2019-`)

Source: https://www.foxglove.org.uk/who-we-are/people/martha-dark/
Source tier: primary
Source content: "Martha Dark is the Co-Executive Director of Foxglove, where she jointly leads the organisation's work alongside Rosa Curling." … "Martha co-founded Foxglove in 2019 with Rosa Curling and Cori Crider and has served as a director since its inception." The staff index at /who-we-are/people/ also lists her as "Co-Executive Director".
Comparison: Both roles (co-founder, co-executive director) and the affiliation period since 2019 match the body and the `affiliations[0]` frontmatter. The bio and index are the same publisher (Foxglove's own site), so one independent primary source.
Decision: primary-sourced

## Claim 2: "the London-based strategic-litigation non-profit she founded in 2019"

Source: https://find-and-update.company-information.service.gov.uk/company/12052097 and https://www.foxglove.org.uk/about/
Source tier: primary
Source content: Companies House — "Incorporated on 14 June 2019"; registered office "International House, 36-38 Cornhill, London, England, EC3V 3NG"; "Private company limited by guarantee without share capital Community Interest Company (CIC)"; status "Active". Foxglove about page — "an independent non-profit organisation that fights to make tech fair for everyone"; "Foxglove fights for a fairer tech future using litigation, campaigning and communication"; they "take tech abuses to court". Dark's bio — "Martha co-founded Foxglove in 2019".
Comparison: London base, 2019 founding, non-profit structure, and litigation-as-method each match; founding year and London location are confirmed by two independent canonical sources (government record + the organization's own site). "She founded" is consistent with co-founder status per Claim 1.
Decision: corroborated

## Claim 3: "previously head of operations at Reprieve"

Source: https://www.foxglove.org.uk/who-we-are/people/martha-dark/
Source tier: primary
Source content: The bio lists her prior senior roles, including "Head of Operations at Reprieve".
Comparison: Title and organization match the body claim. No second canonical source found this session (search returned only conference bios and advocacy-outlet interviews, none canonical per the mission source list); the entity's own professional bio is a primary-tier source, satisfying the stricter person-entity rule.
Decision: primary-sourced

## Claim 4: "chief operating officer of the Open Rights Group"

Source: https://www.foxglove.org.uk/who-we-are/people/martha-dark/
Source tier: primary
Source content: The bio lists her prior senior roles, including "Chief Operating Officer at Open Rights Group".
Comparison: Title and organization match the body claim. Same sourcing situation as Claim 3 — primary-tier professional bio, no second canonical source found.
Decision: primary-sourced

## Claim 5: scalar:sources[0].note — "Foxglove's own staff page identifying Dark as co-executive director"

Source: https://www.foxglove.org.uk/who-we-are/people/
Source tier: primary
Source content: The staff page lists "Martha Dark: Co-Executive Director" under Directors.
Comparison: The cited page does identify Dark as Co-Executive Director, exactly as the `sources[0].note` scalar states.
Decision: primary-sourced

## Claim 6: scalar:sources[1].note — "Companies House (via Endole) record for Foxglove Legal Community Interest Company, founded 2019"

Source: https://find-and-update.company-information.service.gov.uk/company/12052097
Source tier: primary
Source content: "FOXGLOVE LEGAL COMMUNITY INTEREST COMPANY" — "Incorporated on 14 June 2019".
Comparison: The official Companies House record (checked directly rather than via the Endole mirror cited in `sources[1]`) confirms the company name and 2019 founding stated in the note scalar.
Decision: primary-sourced
