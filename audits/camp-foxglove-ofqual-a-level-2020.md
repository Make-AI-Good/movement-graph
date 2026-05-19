---
entity_id: camp-foxglove-ofqual-a-level-2020
entity_hash: 44fd1e1632289d4f315e2bd6813f5b4ccd472184
audit_date: 2026-05-18
pass: 1
status: discrepancy
claims_total: 18
claims_verified: 15
claims_discrepancy: 1
claims_unverifiable: 2
sources_consulted:
  - https://www.foxglove.org.uk/2020/08/17/we-put-a-stop-to-the-a-level-grading-algorithm/
  - https://www.foxglove.org.uk/news/press-release-u-turn-on-a-level-algorithm
  - https://www.statewatch.org/news/2020/august/uk-legal-action-threatened-over-algorithm-used-to-grade-teenagers-exams/
  - https://en.wikipedia.org/wiki/Ofqual_exam_results_algorithm
  - https://en.wikipedia.org/wiki/2020_UK_GCSE_and_A-Level_grading_controversy
  - https://www.technologyreview.com/2020/08/20/1007502/uk-exam-algorithm-cant-fix-broken-system/
  - https://www.government-transformation.com/innovation/fuck-the-algorithm-protests-put-government-use-of-ai-in-spotlight
  - https://feweek.co.uk/2020/08/14/legal-action-threat-over-a-level-results-fiasco/
  - https://smk.org.uk/awards_nominations/stoppingtheunfaira-levelgradingalgorithm/
  - https://www.foxglove.org.uk/news/home-office-says-it-will-abandon-its-racist-visa-algorithm-nbsp-after-we-sued-them
  - https://www.foxglove.org.uk/2021/12/01/secret-dwp-algorithm/
---

## Claim 1: "Ofqual — the regulator of qualifications, exams and tests in England"

Source: https://en.wikipedia.org/wiki/Ofqual_exam_results_algorithm
Source content: "Ofqual, the regulator of qualifications, exams and tests in England"
Comparison: Body description matches Wikipedia verbatim. Wikipedia is supported here by Ofqual's own statutory remit; functions as tiebreaker for a definitional claim.
Decision: verified

## Claim 2: "with secondary-school exams cancelled in response to COVID-19, [Ofqual] used a standardisation algorithm to award A-level and GCSE grades to students who had not been able to sit their papers"

Source: https://en.wikipedia.org/wiki/Ofqual_exam_results_algorithm
Source content: "Ofqual...developed a standardisation algorithm in 2020 to moderate teacher-predicted grades for A-level and GCSE qualifications after exams were cancelled due to COVID-19."
Comparison: Body and source align on cause (COVID-19), instruments (A-level and GCSE grades), and the standardisation-algorithm mechanism.
Decision: verified

## Claim 3: "The algorithm took teachers' Centre Assessed Grades and adjusted them in light of the school's historical performance, with the aim of preventing grade inflation"

Source: https://en.wikipedia.org/wiki/Ofqual_exam_results_algorithm
Source content: Wikipedia describes the algorithm as moderating CAGs against historical school performance to fit distribution curves; MIT Technology Review article describes the algorithm as disproportionately affecting students based on school history.
Comparison: Body's mechanical description (CAGs adjusted by school historical performance, anti-inflation aim) matches the documented mechanism.
Decision: verified

## Claim 4: "results were released on 13 August 2020"

Source: https://en.wikipedia.org/wiki/Ofqual_exam_results_algorithm
Source content: "A-level grades were announced on 13 August 2020 in England, Wales, and Northern Ireland."
Comparison: Exact date match.
Decision: verified

## Claim 5: "almost 40% of teacher-predicted grades had been revised downwards"

Source: https://www.technologyreview.com/2020/08/20/1007502/uk-exam-algorithm-cant-fix-broken-system/
Source content: "Nearly 40% of A-level students received exam scores downgraded from their teachers' predictions."
Comparison: "Almost 40%" matches "nearly 40%" within paraphrase tolerance. Wikipedia gives a slightly lower 36% figure for the "one grade lower" subset, but the broader downgrade figure widely cited at the time was ~39%; the body's claim is consistent with the MIT TR canonical source.
Decision: verified

## Claim 6: "heaviest downgrades concentrated in pupils at state schools in less affluent areas and the smallest in private schools whose smaller class sizes the algorithm treated more leniently"

Source: https://www.technologyreview.com/2020/08/20/1007502/uk-exam-algorithm-cant-fix-broken-system/
Source content: "[the algorithm] disproportionately hurt students from working-class and disadvantaged communities and inflated the scores of students from private schools."
Comparison: Body's distributional claim (state schools / less affluent areas hit hardest; private schools treated more leniently via small-class-size mechanism) matches the source's characterization. The small-class-size mechanism is documented in the Wikipedia article as well.
Decision: verified

## Claim 7: "Curtis Parfitt-Ford, an 18-year-old A-level student at a comprehensive school in Ealing, west London"

Source: https://smk.org.uk/awards_nominations/stoppingtheunfaira-levelgradingalgorithm/ (age); https://www.statewatch.org/news/2020/august/uk-legal-action-threatened-over-algorithm-used-to-grade-teenagers-exams/ (school)
Source content: SMK: "an 18-year-old student." Statewatch: "A-level student at Elthorne Park High School (comprehensive school in Ealing, London)."
Comparison: Age 18 verified by SMK; comprehensive school in Ealing verified by Statewatch. Ealing is in west London.
Decision: verified

## Claim 8: "sending a pre-action letter to Ofqual on 14 August 2020"

Source: https://www.foxglove.org.uk/2020/08/17/we-put-a-stop-to-the-a-level-grading-algorithm/ (Foxglove); https://www.statewatch.org/news/2020/august/uk-legal-action-threatened-over-algorithm-used-to-grade-teenagers-exams/ (Statewatch)
Source content: Foxglove (the entity that sent the letter): the letter was sent "Friday," referring to the day after Thursday's results — Friday 14 August 2020. Statewatch: "Legal letter sent today on behalf of Ealing A-level student Curtis Parfitt-Ford," dated 12 August 2020 in the Statewatch piece.
Comparison: Foxglove's own account and Statewatch disagree on the letter date (14 Aug vs 12 Aug). Both are canonical sources; primary (Foxglove) vs secondary news (Statewatch). Per the source rule, when canonical sources disagree the outcome is unverifiable rather than picking a winner — even though the Foxglove "Friday after Thursday results" framing is internally consistent with results day on 13 Aug, the documented Statewatch disagreement is what triggers the rule.
Decision: unverifiable

## Claim 9: "The letter argued that the algorithm exceeded Ofqual's statutory powers, breached key principles of data-protection law, and was unfair because it graded the school's historical performance rather than the individual student"

Source: https://smk.org.uk/awards_nominations/stoppingtheunfaira-levelgradingalgorithm/
Source content: "Curtis's case argued that Ofqual's algorithm was unlawful, that Ofqual had acted in contradiction of its statutory powers, it had violated data protection law, and was unfair."
Comparison: All three grounds the body asserts (exceeded statutory powers, data-protection law, unfairness) appear in the SMK account. Statewatch independently corroborates the data-protection-law and fairness grounds, with focus on GDPR Article 22.
Decision: verified

## Claim 10: "Change.org petition that gathered more than 250,000 signatures within days"

Source: https://www.foxglove.org.uk/2020/08/17/we-put-a-stop-to-the-a-level-grading-algorithm/
Source content: "over 250,000 people signed [Curtis's change.org petition]."
Comparison: Signature count matches; "within days" is consistent with the four-day campaign window.
Decision: verified

## Claim 11: "On 16 August 2020, students gathered in Parliament Square and outside the Department for Education in Westminster"

Source: https://www.technologyreview.com/2020/08/20/1007502/uk-exam-algorithm-cant-fix-broken-system/ (date and DfE); https://www.government-transformation.com/innovation/fuck-the-algorithm-protests-put-government-use-of-ai-in-spotlight (DfE/Whitehall)
Source content: MIT TR: "August 16, 2020 - hundreds gathered outside the UK Department of Education building in London." Government Transformation: "outside the DfE in Whitehall."
Comparison: 16 August date and Department for Education location are both verified. The body additionally asserts Parliament Square as a protest site; none of the canonical sources fetched in this pass explicitly confirm Parliament Square (only DfE / Whitehall). Without a second canonical source for Parliament Square specifically, the conjunctive claim cannot be fully verified.
Decision: unverifiable

## Claim 12: "chanting and carrying placards reading 'fuck the algorithm'"

Source: https://www.technologyreview.com/2020/08/20/1007502/uk-exam-algorithm-cant-fix-broken-system/; https://www.government-transformation.com/innovation/fuck-the-algorithm-protests-put-government-use-of-ai-in-spotlight
Source content: MIT TR describes the slogan as the protest's "rallying cry"; the Government Transformation article's headline names the "Fuck the algorithm" protests directly.
Comparison: Slogan content matches across multiple canonical sources.
Decision: verified

## Claim 13: "On the morning of 17 August 2020...Education Secretary Gavin Williamson announced a U-turn: the standardisation algorithm would be withdrawn and 2020 A-level grades would be awarded on the basis of teachers' Centre Assessed Grades"

Source: https://en.wikipedia.org/wiki/2020_UK_GCSE_and_A-Level_grading_controversy
Source content: "On August 17, 2020, Ofqual and Secretary of State for Education Gavin Williamson agreed that grades would be reissued using unmoderated teacher predictions."
Comparison: Date, person, and substance of the U-turn (CAGs replace algorithmic grades) match.
Decision: verified

## Claim 14: "the Scottish government having already reversed an analogous SQA algorithm the previous week"

Source: https://en.wikipedia.org/wiki/2020_UK_GCSE_and_A-Level_grading_controversy
Source content: "On August 10, 2020, First Minister Nicola Sturgeon apologized... On August 11, the Scottish Government agreed to upgrade results."
Comparison: Scottish reversal occurred 10-11 August 2020; English U-turn was 17 August 2020 — six to seven days apart, squarely "the previous week."
Decision: verified

## Claim 15: "Eight days later, on 25 August 2020, Sally Collier resigned as Ofqual's Chief Regulator"

Source: https://en.wikipedia.org/wiki/Ofqual_exam_results_algorithm
Source content: "[Sally Collier] resigned from the post of chief regulator of Ofqual" on 25 August 2020.
Comparison: Date, person, role, and event all match. "Eight days later" — 17 August to 25 August — is arithmetically correct.
Decision: verified

## Claim 16: "from results day to government U-turn took four days"

Source: composite of Claims 4 and 13 above (results day 13 Aug 2020; U-turn 17 Aug 2020)
Source content: see Claims 4 and 13.
Comparison: 13 Aug to 17 Aug is four days. Arithmetic check on independently verified facts.
Decision: verified

## Claim 17: "Foxglove and partners would later use [the same pairing of strategic litigation, named claimant, crowdfunding, petitioning, and street protest] against the Home Office's visa-streaming algorithm"

Source: https://www.foxglove.org.uk/news/home-office-says-it-will-abandon-its-racist-visa-algorithm-nbsp-after-we-sued-them
Source content: Foxglove's own press release on the visa-streaming victory is dated 4 August 2020 and states the Home Office conceded on 3 August 2020, agreeing to discontinue the algorithm from 7 August 2020 — before the case reached court. The campaign was conducted jointly with the Joint Council for the Welfare of Immigrants (JCWI).
Comparison: Body asserts Foxglove "would later use" these tactics against the visa-streaming algorithm. The temporal direction is reversed: the visa-streaming campaign was concluded by 4 August 2020, more than a week before the Ofqual results were released on 13 August 2020. The tactical-pairing claim itself is well-supported by the source — what fails is the temporal ordering ("would later use"). Visa-streaming was an earlier instance of the same playbook, not a subsequent one.
Decision: discrepancy

## Claim 18: "and the DWP's General Matching Service"

Source: https://www.foxglove.org.uk/2021/12/01/secret-dwp-algorithm/
Source content: Foxglove's December 2021 announcement of a legal challenge to a DWP algorithm targeting disabled benefits claimants, conducted in support of the Greater Manchester Coalition of Disabled People.
Comparison: The DWP campaign begins December 2021 — clearly "later" than the August 2020 Ofqual campaign, so the temporal framing holds. Foxglove's involvement and the tactical shape (named coalition claimant, crowdfunded legal action, transparency demand) are verified.
Decision: verified
