---
entity_id: person-mary-wareham
entity_hash: 824a33c6c8b0f50dc9184f4a1f4b5d475a9f7e3c
audit_date: 2026-06-02
pass: 1
status: discrepancy
claims_total: 9
claims_verified: 4
claims_discrepancy: 5
claims_unverifiable: 0
sources_consulted:
  - https://www.stopkillerrobots.org/news/passing-the-baton/
  - https://www.hrw.org/topic/arms/killer-robots
  - https://en.wikipedia.org/wiki/Campaign_to_Stop_Killer_Robots
  - https://www.hrw.org/about/people/mary-wareham
  - https://www.stopkillerrobots.org/about-us/
---

## Claim 1: "Advocacy director of Human Rights Watch's Arms Division" (body, present-tense)

Source: https://www.hrw.org/about/people/mary-wareham
Source content: "Former Deputy Director, Crisis, Conflict and Arms Division"
Comparison: HRW's own bio page lists Wareham as "Former Deputy Director, Crisis, Conflict and Arms Division" — both the title ("Deputy Director" vs "advocacy director") and the present-tense status ("Former") contradict the body's claim that she currently holds an HRW advocacy-director role. The HRW killer-robots topic page also calls her "Deputy Director". The "advocacy director" title is supported by the SKR March-2021 source the entity cites, but is no longer current per HRW's own bio.
Decision: discrepancy

## Claim 2: "Founding global coordinator of Stop Killer Robots"

Source: https://www.stopkillerrobots.org/news/passing-the-baton/
Source content: "the advocacy director of the Arms Division of Human Rights Watch" coordinated the Campaign "from its inception until March 2021"
Comparison: SKR's own announcement confirms she coordinated the campaign from inception. "Founding global coordinator" is the corresponding role descriptor.
Decision: verified

## Claim 3: "serving as the coalition's coordinator from its 2013 launch"

Source: https://www.stopkillerrobots.org/about-us/
Source content: "publicly launched in 2013" — also Wikipedia's article on the Campaign: "The Campaign to Stop Killer Robots launched in London in April 2013."
Comparison: The 2013 launch is corroborated by both SKR's own about-us page and the Wikipedia article on the Campaign. SKR's passing-the-baton article corroborates that Wareham coordinated from inception.
Decision: verified

## Claim 4: "until March 2021"

Source: https://www.stopkillerrobots.org/news/passing-the-baton/
Source content: Wareham coordinated the Campaign "from its inception until March 2021"
Comparison: SKR's own announcement is the canonical record of her step-down date.
Decision: verified

## Claim 5: "continuing in her HRW advocacy-director role" (body)

Source: https://www.hrw.org/about/people/mary-wareham
Source content: "Former Deputy Director, Crisis, Conflict and Arms Division"
Comparison: HRW's bio lists Wareham as "Former" — she is no longer in an active HRW role at the time of audit, so the body's present-tense "continuing in her HRW advocacy-director role" is no longer accurate. (Also, the title was "Deputy Director", not "advocacy director", per HRW's own bio.)
Decision: discrepancy

## Claim 6: scalar:affiliations[0] — "org: org-stop-killer-robots, role: founding global coordinator, period: 2013-2021"

Source: https://www.stopkillerrobots.org/news/passing-the-baton/
Source content: Wareham coordinated the Campaign "from its inception until March 2021"; SKR launched 2013 per its about-us page.
Comparison: Both the role and the period are corroborated by SKR's own sources.
Decision: verified

## Claim 7: scalar:affiliations[1] — "org: org-human-rights-watch, role: advocacy director, Arms Division, period: 2010s-"

Source: https://www.hrw.org/about/people/mary-wareham
Source content: "Former Deputy Director, Crisis, Conflict and Arms Division"
Comparison: HRW's own bio gives the title as "Deputy Director" (not "advocacy director") and the division as "Crisis, Conflict and Arms Division" (not "Arms Division"). The open-ended period "2010s-" implies an ongoing role, but the bio explicitly marks her as "Former". Three sub-claims (title, division name, ongoing-status) all contradict HRW's own bio.
Decision: discrepancy

## Claim 8: scalar:sources[1].note — "HRW Killer Robots topic page documenting Wareham's continuing role as advocacy director of HRW's Arms Division"

Source: https://www.hrw.org/topic/arms/killer-robots
Source content: "Delivered by Mary Wareham, Deputy Director"
Comparison: The HRW killer-robots topic page identifies Wareham as "Deputy Director", not "advocacy director", and HRW's bio marks her as "Former". The note's claims about both the title and the continuing nature of the role contradict what the cited page actually says.
Decision: discrepancy

## Claim 9: scalar:sources[2].note — "Wikipedia overview of the Stop Killer Robots campaign and Wareham's founding-coordinator role"

Source: https://en.wikipedia.org/wiki/Campaign_to_Stop_Killer_Robots
Source content: The article does not mention Mary Wareham by name.
Comparison: The note asserts the Wikipedia article documents Wareham's founding-coordinator role, but the article contains no mention of her. The article does confirm the Campaign's existence and 2013 launch, but the note's specific claim about Wareham coverage is unsupported by the cited page.
Decision: discrepancy
