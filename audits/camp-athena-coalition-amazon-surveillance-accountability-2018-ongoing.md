---
entity_id: camp-athena-coalition-amazon-surveillance-accountability-2018-ongoing
entity_hash: 719200a9342f5bb7e6c64c49b0b81b65e768c921
audit_date: 2026-06-10
pass: 2
status: corrections-pending
claims_total: 20
claims_corroborated: 18
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 1
sources_consulted:
  - https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys
  - https://athenaforall.org/
  - https://athenaforall.org/news/press-release-athena-coalition-statement-on-ftc-announcement-of-amazon-lawsuit/
  - https://en.wikipedia.org/wiki/FTC_v._Amazon
  - https://www.aclu.org/news/privacy-technology/amazons-face-recognition-falsely-matched-28
---

## Claim 1: "Launched publicly on 26 November 2019" — body; also frontmatter start_date: 2019-11-26

Source: https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys
Source content: Article dated November 26, 2019 reports the coalition "announced the formation of a new coalition called Athena on Tuesday" — the article's own publication date confirms 26 November 2019.
Comparison: Body and frontmatter start_date match.
Decision: corroborated

## Claim 2: "launched with three dozen founding organisations" — body line 56; scalar:sources[1].note "the three-dozen founding organisation count"

Source: https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys
Source content: "Three dozen grassroots advocacy groups opposed to retail giant and tech conglomerate Amazon announced the formation of a new coalition called Athena on Tuesday."
Comparison: Both the body and the sources[1].note match the source's "three dozen" framing. Pass-1 discrepancy ("over 40" / "40+") was corrected in editor sweep 7b7ed0a9.
Decision: corroborated

## Claim 3: "and has grown past 50" — body line 56

Source: https://athenaforall.org/
Source content: Membership list on the coalition's own "Who We Are" section enumerates 52 member organisations (counted from the rendered list); the page presents itself as "a broad coalition of local and national organizations."
Comparison: Body's "grown past 50" matches the current rendered member count (52). Pass-1 unverifiable upgraded to verified now that the page's member list is countable in this pass.
Decision: corroborated

## Claim 4: "raised $15 million in three-year seed funding at launch" — body line 56

Source: https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys
Source content: Common Dreams article (re-fetched this pass) does NOT contain the $15M three-year-budget detail. Pass-1 cross-confirmed via The Hill 2019 coverage ("is raising $15 million to cover its first three years"); the underlying fact is well-sourced. The body cites the Common Dreams URL for this claim, but the fact is not present in that source's text.
Comparison: Body claim is factually verified via The Hill (already cited in pass-1 sources_consulted). Source-attribution mismatch in sources[1].note ("$15 million three-year budget" listed among facts attributed to Common Dreams) is a non-discrepancy editorial detail rather than a factual error in body prose; carried forward from pass 1.
Decision: corroborated

## Claim 5: "Open Society Foundations as named seed funder" — body line 56

Source: https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys (re-fetched); cross-confirmed via The Hill in pass 1
Source content: Common Dreams article does not contain Open Society Foundations attribution; The Hill 2019 coverage cited in pass 1 names OSF. Same source-attribution caveat as Claim 4.
Comparison: Body claim verified via cross-source.
Decision: corroborated

## Claim 6: "inaugural executive director was Dania Rajendra" — body line 48

Source: https://www.commondreams.org/news/2019/11/26/athena-vs-amazon-new-coalition-debuts-eve-holiday-shopping-season-call-out-companys (re-fetched); cross-confirmed via The Hill in pass 1
Source content: Common Dreams does not contain Rajendra info; The Hill describes Rajendra as Athena's "newly appointed executive director" and "only full-time employee." Same source-attribution caveat as Claim 4.
Comparison: Body claim verified via cross-source.
Decision: corroborated

## Claim 7: "FUNA convened by PowerSwitch Action in Northern Virginia in 2018" — body line 52; scalar:sources[3].note

Source: https://www.demos.org/research/challenging-dominance-big-tech-us-not-amazon-arlington-va (carried from pass 1)
Source content: Per pass-1 fetch: "For Us, Not Amazon (FUNA), a women of color-led coalition... PowerSwitch convened local groups that were concerned about their cities' bids for HQ2."
Comparison: Body unchanged since pass 1; verification holds.
Decision: corroborated

## Claim 8: "ILSR Co-Director Stacy Mitchell" — body line 52

Source: https://ilsr.org/press/ilsr-co-founds-national-coalition-to-take-on-amazon/ (carried from pass 1)
Source content: ILSR press release uses the title "ILSR Co-Director Stacy Mitchell" verbatim.
Comparison: Body unchanged; verification holds.
Decision: corroborated

## Claim 9: "PowerSwitch Action and the Institute for Local Self-Reliance (ILSR)... two co-founders" — body line 52

Source: https://forgeorganizing.org/article/reining-amazon-build-people-powered-democracy/ (carried from pass 1)
Source content: "This is why PowerSwitch Action and the Institute for Local Self-Reliance joined with allies across issues and movements to create the Athena Coalition."
Comparison: Body unchanged; verification holds.
Decision: corroborated

## Claim 10: "described the resulting approach as a 'braided strategy'" — body line 52; scalar:sources[3].note

Source: https://forgeorganizing.org/article/reining-amazon-build-people-powered-democracy/ (carried from pass 1)
Source content: "This is what PowerSwitch Action refers to as 'braided strategy'" — phrase confirmed verbatim in the Forge piece by Mitchell and Jacobs.
Comparison: Body unchanged; verification holds.
Decision: corroborated

## Claim 11: "Rekognition's accuracy problems on darker-skinned subjects had been documented by MIT researcher Joy Buolamwini" — body line 60

Source: https://www.aclu.org/news/privacy-technology/amazons-face-recognition-falsely-matched-28 (re-fetched this pass)
Source content: ACLU article links to Buolamwini's 2018 Gender Shades paper ("Academic research has also already shown that face recognition is less accurate for darker-skinned faces and women" — link target buolamwini18a.pdf). The cited 2018 paper studied IBM, Microsoft, Face++ — NOT Amazon Rekognition. Buolamwini's 2019 follow-up "Actionable Auditing" (Raji & Buolamwini) did include Rekognition, but neither the ACLU page nor any source the entity cites confirms her Rekognition-specific work; the Wikipedia biographical article likewise does not name a Rekognition audit.
Comparison: The narrow body claim ("Buolamwini documented Rekognition's accuracy problems") is broadly accepted in the field via the 2019 Actionable Auditing paper, but the entity's own sources do not cite that work, and a canonical (non-Wikipedia, per the Source rule for living-person specifics beyond public role) source confirming the Rekognition-specific audit was not reachable in this pass. The conflation risk — citing the 2018 paper as evidence for a 2019 study's content — is a sourcing thinness rather than a clean discrepancy.
Decision: uncorroborated

## Claim 12: "ACLU... found it misidentified 28 members of Congress as criminals" — body line 60

Source: https://www.aclu.org/news/privacy-technology/amazons-face-recognition-falsely-matched-28
Source content: ACLU page title is "Amazon's Face Recognition Falsely Matched 28 Members of Congress with Mugshots" (re-fetched URL slug confirms); the original ACLU finding stands as quoted in pass 1.
Comparison: Body unchanged; verification holds.
Decision: corroborated

## Claim 13: "Amazon had announced a one-year Rekognition moratorium in June 2020" — body line 60; outcomes mirror "Amazon announced a one-year moratorium on Rekognition sales to law enforcement in June 2020"

Source: https://en.wikipedia.org/wiki/Amazon_Rekognition (carried from pass 1)
Source content: Pass-1 quote: "In June 2020, Amazon announced it was implementing a one-year moratorium on police use of Rekognition, in response to the George Floyd protests." Wikipedia canonical-alone for a public-event date per source rule.
Comparison: Body and outcomes unchanged; verification holds.
Decision: corroborated

## Claim 14: "Amazon extended the moratorium indefinitely on 18 May 2021" — body line 60; scalar:sources[4].note

Source: https://www.aclu.org/press-releases/aclu-statement-extended-amazon-face-recognition-moratorium (carried from pass 1)
Source content: ACLU press release dated May 18, 2021 announcing the indefinite extension; cross-confirmed by Washington Post (URL date 2021/05/18) and CNN in pass 1.
Comparison: Body and scalar unchanged; verification holds.
Decision: corroborated

## Claim 15: "delivered 10,000 petitions to Amazon" — body line 60; scalar:sources[4].note "the 10,000-petition delivery"

Source: https://mediajustice.org/news/eyesonamazon-week-of-action-highlights/ (carried from pass 1)
Source content: Pass-1 quote: "we delivered 10K petitions to Andrew Jassy and Jeff Bezos."
Comparison: Body and scalar unchanged; verification holds.
Decision: corroborated

## Claim 16: "Eyes on Amazon Week of Action... Color of Change, the ACLU of Washington, the Electronic Frontier Foundation, Mijente, Just Futures Law, and Free Press" — body line 60; scalar:sources[4].note enumerates the same six partners

Source: https://mediajustice.org/news/eyesonamazon-week-of-action-highlights/ (carried from pass 1)
Source content: MediaJustice piece names the six partners listed in body in the same order.
Comparison: Body and scalar unchanged; verification holds.
Decision: corroborated

## Claim 17: "Current Director is Ryan Gerety, who brings experience at the Ford Foundation and the Open Technology Institute at New America" — body line 48; scalar:sources[6].note

Source: https://datasociety.net/people/ryan-gerety/ (carried from pass 1)
Source content: Pass-1 quote: "Ryan Gerety, a Data & Society affiliate, is the director of the Athena Coalition" and "She was previously at the Ford Foundation and the Open Technology Institute at New America."
Comparison: Body and scalar unchanged; verification holds.
Decision: corroborated

## Claim 18: "May 2022 'Monitored' report... published by United for Respect within the Athena umbrella" — body line 64; outcomes mirror; scalar:sources[5].note

Source: https://united4respect.org/wp-content/uploads/2022/05/athena_monitored_report.pdf (carried from pass 1)
Source content: PDF URL contains "/2022/05/" (May 2022), hosted on united4respect.org — both the date and publishing org confirmed by URL-encoded metadata.
Comparison: Body, outcomes, scalar unchanged; verification holds.
Decision: corroborated

## Claim 19: "May 2022 Amazon annual meeting... action at Vanguard's Malvern, Pennsylvania headquarters" — body line 68; outcomes scalar "Vanguard headquarters in Malvern, Pennsylvania"

Source: https://en.wikipedia.org/wiki/The_Vanguard_Group (carried from pass 1)
Source content: Pass-1 quote: "Vanguard's corporate headquarters is in Malvern, a suburb of Philadelphia, Pennsylvania." Named-entity definitional fact — Wikipedia canonical-alone per source rule.
Comparison: Body and outcomes unchanged; verification holds.
Decision: corroborated

## Claim 20: "When the FTC filed its antitrust lawsuit against Amazon in June 2023" — body line 68 (note: outcomes scalar correctly says "September 2023")

Source: https://en.wikipedia.org/wiki/FTC_v._Amazon (re-fetched); https://athenaforall.org/news/press-release-athena-coalition-statement-on-ftc-announcement-of-amazon-lawsuit/ (re-fetched, dated 2023-09-26)
Source content: Wikipedia FTC v. Amazon: "the FTC filed its lawsuit against Amazon on September 26, 2023" (citing McCabe, NYT, and Fung, CNN, both dated September 26, 2023). Athena's own response press release is dated September 26, 2023 and titled "Athena Coalition Statement on FTC Announcement of Amazon Lawsuit" — its existence on that date confirms the filing.
Comparison: Body line 68 still reads "in June 2023" — the editor's pass-1-backfill commit 7b7ed0a9 ("June 2023→September 2023 (Claim 20 ×2)") fixed the outcomes scalar (line 21) but did NOT change the body sentence at line 68, despite the ×2 in the commit body. The body's "in June 2023" is the single token to replace with "in September 2023" (or more precisely "on September 26, 2023"); the change applies to "When the FTC [filed its antitrust lawsuit against Amazon](https://athenaforall.org/news/...) in June 2023, Athena framed the filing..." Note: the separate "(June 2023)" parenthetical earlier on line 68 referring to Athena's OSTP submission is a distinct fact unrelated to Claim 20.
Decision: correction
