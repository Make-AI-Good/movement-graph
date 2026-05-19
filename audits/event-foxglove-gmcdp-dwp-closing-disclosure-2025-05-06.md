---
entity_id: event-foxglove-gmcdp-dwp-closing-disclosure-2025-05-06
entity_hash: 610a25901f61977435696186bd662213e34c1ff3
audit_date: 2026-05-18
pass: 1
status: discrepancy
claims_total: 16
claims_verified: 14
claims_discrepancy: 1
claims_unverifiable: 1
sources_consulted:
  - https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
  - https://www.foxglove.org.uk/2024/02/12/dwp-boss-bias-algorithm-disabled-people/
  - https://www.foxglove.org.uk/2021/12/01/secret-dwp-algorithm/
  - https://www.foxglove.org.uk/2022/02/14/algorithm-dwp-challenge/
  - https://gmcdp.com/gmcdp-foxglove-legal-challenge-department-work-and-pensions-dwp-fraud-algorithm
---

## Claim 1: "On Tuesday 6 May 2025, Foxglove published the closing-disclosure post"

Source: https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
Source content: Post publication date stated as "06.05.2025". The URL slug confirms 2025/05/06. 2025-05-06 was a Tuesday on the Gregorian calendar.
Comparison: Body claim matches source date; weekday is correctly derivable.
Decision: verified

## Claim 2: Foxglove "ran [the case] with the Greater Manchester Coalition of Disabled People"

Source: https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
Source content: "In 2021, Foxglove began an investigation with the Greater Manchester Coalition of Disabled People into the Department for Work and Pensions' (DWP) secret benefit fraud investigations algorithm."
Comparison: Joint case described identically in semantic content.
Decision: verified

## Claim 3: The challenge was "into the Department for Work and Pensions's secret benefit-fraud algorithm"

Source: https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
Source content: "the Department for Work and Pensions' (DWP) secret benefit fraud investigations algorithm."
Comparison: Phrasing differs in possessive form ("DWP's" vs "DWP'"), semantic content matches.
Decision: verified

## Claim 4: The post "identified [the system] by its DWP-side name as the General Matching Service"

Source: https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
Source content: Full body text of the post was retrieved verbatim; the phrase "General Matching Service" does not appear anywhere in the post. The post refers to the system only as "the algorithm" or "the DWP algorithm". A targeted second fetch confirmed: "General Matching Service: Not present in page text."
Comparison: Body asserts the closing post identified the system by this DWP-side name. The cited source does not contain that name. The body's `sources:` note for this URL repeats the same claim ("primary source for the operational explanation of the General Matching Service") and is also unsupported. The body separately cites a WhatDoTheyKnow FOI archive thread URL whose slug contains "general_matching_service" as independent corroboration; that page was not fetchable in this session (403). Regardless of whether the name is real and DWP-attributable elsewhere, the specific claim that the closing post identifies the system as the General Matching Service is contradicted by the post.
Decision: discrepancy

## Claim 5: Post headline "We forced the DWP to explain its benefits fraud algorithm: here's what we found"

Source: https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
Source content: Headline confirmed as "We forced the DWP to explain its benefits fraud algorithm: here's what we found"
Comparison: Exact match.
Decision: verified

## Claim 6: "The case had opened on 1 December 2021, when Foxglove and GMCDP launched the legal challenge"

Source: https://www.foxglove.org.uk/2021/12/01/secret-dwp-algorithm/
Source content: Foxglove launch post dated 1 December 2021, describing legal letter sent: "The coalition has sent a legal letter, supported by Foxglove, demanding the government explain how the algorithm works and what, if anything, it has done to eliminate bias."
Comparison: The case-opening date 1 December 2021 is corroborated by the launch post's publication date and the pre-action legal letter described in it; "launched the legal challenge" is paraphrase-tolerant for "sent a pre-action legal letter inside the judicial-review track."
Decision: verified

## Claim 7: "Foxglove escalated to a Letter Before Action in February 2022"

Source: https://www.foxglove.org.uk/2022/02/14/algorithm-dwp-challenge/
Source content: Post dated 14 February 2022; "We've supported the GMCDP to send a formal pre-action letter to the DWP telling them to come clean about exactly how their algorithm works ... Unless the DWP responds promptly with the full details, the GMCDP and Foxglove will seek a judicial review. They have 28 days to respond."
Comparison: "Letter Before Action" is the standard UK pre-action procedural term for the kind of formal pre-action letter described; month matches.
Decision: verified

## Claim 8: Couling admission "on 10 January 2024 in oral evidence to the Work and Pensions Select Committee"

Source: https://www.foxglove.org.uk/2024/02/12/dwp-boss-bias-algorithm-disabled-people/ (Foxglove's account of the admission); attempted https://committees.parliament.uk/oralevidence/14052/pdf (entity-cited parliamentary record, returned 403)
Source content: Foxglove post confirms "Works and Pensions select committee evidence session" and "January 2024" but does not state the exact date "10 January 2024". The parliamentary record URL the entity cites was not retrievable in this session.
Comparison: The committee, year, and month are corroborated by Foxglove's own subsequent account. The specific day (10 January) is not in the secondary source I could fetch, and the primary parliamentary record was unreachable. Outcome falls to the unverifiable category for the specific date.
Decision: unverifiable

## Claim 9: Neil Couling is "DWP Change and Resilience Director General"

Source: https://www.foxglove.org.uk/2024/02/12/dwp-boss-bias-algorithm-disabled-people/
Source content: Couling's title given as "Change and Resilience Director General" at the DWP.
Comparison: Exact match.
Decision: verified

## Claim 10: Couling addressed Peter Grant MP

Source: https://www.foxglove.org.uk/2024/02/12/dwp-boss-bias-algorithm-disabled-people/
Source content: "Peter Grant MP, during a Works and Pensions select committee evidence session" — Couling answering questions from Peter Grant MP.
Comparison: Exact match.
Decision: verified

## Claim 11: Couling said "the systems do have biases in"

Source: https://www.foxglove.org.uk/2024/02/12/dwp-boss-bias-algorithm-disabled-people/
Source content: "The systems do have biases in."
Comparison: Exact match.
Decision: verified

## Claim 12: Couling said "you have to bias to catch fraudsters"

Source: https://www.foxglove.org.uk/2024/02/12/dwp-boss-bias-algorithm-disabled-people/
Source content: "the issue is whether they are biases that are not allowed in the law, because you have to bias to catch fraudsters."
Comparison: Exact match for the body's quoted fragment. (The Foxglove 2025-05-06 closing post renders the same admission as "you have to have bias to catch fraudsters" — a one-word variant — but the body's quote follows the 2024-02-12 Foxglove rendering of the parliamentary admission, which is the closer contemporary source.)
Decision: verified

## Claim 13: "By early 2025, three years and five months into the disclosure-pressure cycle"

Source: derived from prior verified dates (1 December 2021 case opening → 6 May 2025 closing post)
Source content: 2021-12-01 to 2025-05-06 is 3 years, 5 months, 5 days.
Comparison: "three years and five months" matches the elapsed interval.
Decision: verified

## Claim 14: System "calculates and assigns a 'risk score' to each person claiming a benefit" / case "referred to human case agents for further review" / caseworkers "do not see the risk score" / "randomised mix of high and low risk score cases" / "the risk score is not used to inform or influence any other fraud and error activity or potential investigation"

Source: https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
Source content: "The algorithm works calculates and assigns a 'risk score' to each person claiming a benefit." / "each 'case' is referred to human case agents for further review." / "The case workers do not see the risk score and, in the DWP's words: 'the risk score is not used to inform or influence any other fraud and error activity or potential investigation.'" / "Caseworkers receive a randomised mix of high and low risk score cases."
Comparison: All five operational quotations in the body match the post's text within paraphrase tolerance, and the DWP-attributed quote is reproduced verbatim.
Decision: verified

## Claim 15: Closing position quotes — "to the best of our knowledge, the DWP algorithm is not making decisions that result in disabled people being unfairly targeted for benefit fraud investigations" and "should have published all of this information prior to the introduction of the algorithm for us all to consider and scrutinise"

Source: https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
Source content: "to the best of our knowledge, the DWP algorithm is not making decisions that result in disabled people being unfairly targeted for benefit fraud investigations." / "the DWP should have published all of this information prior to the introduction of the algorithm for us all to consider and scrutinise."
Comparison: Body quotes match the post; body drops "the DWP" from the second quote (omission, not contradiction — the antecedent is clear from the preceding sentence).
Decision: verified

## Claim 16: Foxglove committed to "proactively monitor the government's use of algorithms and machine-learning tools to figure out which of these systems we are best placed to challenge, while maintaining a close relationship with the GMCDP"

Source: https://www.foxglove.org.uk/2025/05/06/dwp-explain-benefits-fraud-algorithm/
Source content: "At Foxglove, we plan to proactively monitor the government's use of algorithms and machine-learning tools to figure out which of these systems we are best placed to challenge, while maintaining a close relationship with the GMCDP, to support them however we can in future."
Comparison: Body quote matches the post verbatim (truncated, not altered).
Decision: verified
