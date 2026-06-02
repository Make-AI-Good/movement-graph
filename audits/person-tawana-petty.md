---
entity_id: person-tawana-petty
entity_hash: 5899c8705b32b7a70e3e0b157c35301b956b4bc1
audit_date: 2026-06-02
pass: 1
status: discrepancy
claims_total: 7
claims_verified: 5
claims_discrepancy: 2
claims_unverifiable: 0
sources_consulted:
  - https://en.wikipedia.org/wiki/Tawana_Petty
  - https://www.ajl.org/about
  - https://tawanapetty.org/
  - https://www.democracynow.org/2023/6/1/ai_bengio_petty_tegmark
---

## Claim 1: "has served as Director of Policy and Advocacy at the [Algorithmic Justice League]"

Source: https://en.wikipedia.org/wiki/Tawana_Petty
Source content: "Director of Policy and Advocacy for the Algorithmic Justice League"
Comparison: Title matches verbatim. Cross-confirmed by Democracy Now! 2023-06-01 article header ("director of policy and advocacy at the Algorithmic Justice League") and by tawanapetty.org's own bio ("Director of Policy and Advocacy for the Algorithmic Justice League"), satisfying the ≥1-non-Wikipedia canonical source rule for living-person employment-history specifics.
Decision: verified

## Claim 2: "Data-justice organizer"

Source: https://en.wikipedia.org/wiki/Tawana_Petty
Source content: "author, poet, social justice organizer, mother and youth advocate who works to counter systemic racism"; further identified as a "data-justice expert" with prior roles as "Data Justice Director for the Detroit Community Technology Project" and "National Organizing Director for Data for Black Lives".
Comparison: Wikipedia describes her both as a "social justice organizer" and as a "data-justice expert," and names data-justice organizing roles (Data Justice Director at DCTP; National Organizing Director at Data for Black Lives). "Data-justice organizer" sits within paraphrase tolerance of this combined characterization.
Decision: verified

## Claim 3: "representing AJL in U.S. and international AI-governance processes"

Source: https://en.wikipedia.org/wiki/Tawana_Petty
Source content: "represented AJL in national and international processes shaping AI governance"
Comparison: Near-verbatim match. "National" → "U.S." is a defensible paraphrase given Petty's U.S. base and the AJL's U.S. headquartering; "AI-governance processes" matches "processes shaping AI governance."
Decision: verified

## Claim 4: scalar:affiliations[0].role "director of policy and advocacy"

Source: https://en.wikipedia.org/wiki/Tawana_Petty
Source content: "Director of Policy and Advocacy for the Algorithmic Justice League"
Comparison: Role title matches. Same triangulation as Claim 1 (Wikipedia + tawanapetty.org + Democracy Now! 2023).
Decision: verified

## Claim 5: scalar:affiliations[0].period "2021-"

Source: https://tawanapetty.org/
Source content: "has previously served as co-lead of Our Data Bodies, as Data Justice Director for the Detroit Community Technology Project, National Organizing Director at Data for Black Lives and Director of Policy and Advocacy for the Algorithmic Justice League"
Comparison: The scalar's open dash form ("2021-") asserts ongoing affiliation. Petty's own site lists the AJL role under positions she "has previously served," i.e. as a past affiliation, not ongoing — her current role is "founding Executive Director of Petty Propolis, Inc." A separate, secondary issue is that the start year 2021 is not confirmed by any canonical source consulted (Wikipedia gives no joining date; tawanapetty.org lists the role without dates; Democracy Now! 2023 simply confirms she was in the role at that point). The discrepancy on ongoing-vs-past is the load-bearing one. Editor's audit-D backfill cannot resolve this with a single-token replacement (no canonical end-date is recoverable from sources consulted); flag to Researcher.
Decision: discrepancy

## Claim 6: scalar:sources[0].note "Wikipedia overview noting Petty as a data-justice organizer with leadership roles at AJL"

Source: https://en.wikipedia.org/wiki/Tawana_Petty
Source content: Wikipedia identifies her as a "social justice organizer" and "data-justice expert," and names her as "Director of Policy and Advocacy for the Algorithmic Justice League."
Comparison: The note prose accurately describes what the Wikipedia page contains: a data-justice-aligned characterization plus a leadership role at AJL ("Director of Policy and Advocacy"). Within paraphrase tolerance.
Decision: verified

## Claim 7: scalar:sources[1].note "AJL's own about page where Petty's program leadership has been publicly listed"

Source: https://www.ajl.org/about
Source content: The current AJL "about" page contains no mention of Tawana Petty by name, title, or role. (The site navigation shows /about as the only About page; /team and /about-us both 404.)
Comparison: The note claims AJL's about page publicly lists Petty's program leadership. The page as currently served does not list her. The note may have been accurate at last_checked: 2026-05-08 (the Researcher recorded it that way) — AJL likely removed her listing after her departure from the role (per tawanapetty.org listing AJL among past positions). Either way, the current source content contradicts the note. The fix requires prose judgment (drop the source, replace with a working primary source for the AJL affiliation, or rephrase the note as past-listed); flag to Researcher.
Decision: discrepancy
