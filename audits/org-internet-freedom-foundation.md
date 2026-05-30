---
entity_id: org-internet-freedom-foundation
entity_hash: fd2711a8cf31ce379911e83091d69551edeaa18d
audit_date: 2026-05-30
pass: 1
status: unverifiable
claims_total: 24
claims_verified: 14
claims_discrepancy: 0
claims_unverifiable: 10
sources_consulted:
  - https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
  - https://en.wikipedia.org/wiki/Apar_Gupta
  - https://www.hrw.org/report/2023/06/14/no-internet-means-no-work-no-pay-no-food/internet-shutdowns-deny-access-basic
  - https://globalfreedomofexpression.columbia.edu/cases/bhasin-v-union-of-india/
  - https://internetfreedom.in/about/
  - https://internetfreedom.in/transparency-and-finances/
  - https://www.lawctopus.com/internet-freedom-foundation-iff-launches-project-panoptic/
---

## Claim 1: "launched on 15 August 2016, India's Independence Day"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "formally launched on August 15, 2016" (India's Independence Day).
Comparison: Body's founding date and Independence Day framing match the Wikipedia article. Wikipedia-alone is sufficient for named-entity founding-date facts per source rule.
Decision: verified

## Claim 2: scalar:location "New Delhi, India" (and body: "Delhi-based digital-rights organisation")

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: Wikipedia article identifies IFF as a Delhi-based organisation. Frontmatter location field claims "New Delhi, India".
Comparison: Body and frontmatter location match the canonical Wikipedia description.
Decision: verified

## Claim 3: scalar:website "https://internetfreedom.in/"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: Wikipedia article references internetfreedom.in as the org's official website.
Comparison: URL matches the canonical organisation website per Wikipedia.
Decision: verified

## Claim 4: mission quote — "to advance liberty, equality, fraternity and social justice in the digital age"

Source: https://internetfreedom.in/about/ (cited primary) — HTTP 403 in this audit session
Source content: no canonical source content retrievable this session
Comparison: The verbatim quote is attributed to IFF's own /about/ page (primary source), which returned HTTP 403 on three separate fetches. Wikipedia's IFF article does not corroborate the exact wording. Per source rule (primary source unavailable; verbatim quote requires the primary), claim is judgment-loaded.
Decision: unverifiable

## Claim 5: eight named co-founders — Apar Gupta, Aravind Sulekha, Karthik Balakrishnan, Rachita Taneja, Raman Chima, Rohin Dharmakumar, Kiran Jonnalagadda, Nikhil Pahwa

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "eight co-founders: Apar Gupta, Aravind Sulekha, Karthik Balakrishnan, Rachita Taneja, Raman Chima, Rohin Dharmakumar, Kiran Jonnalagadda, and Nikhil Pahwa."
Comparison: All eight names and the count match exactly. Named-entity founders are a public-record-style fact for which Wikipedia-alone is sufficient.
Decision: verified

## Claim 6: SaveTheInternet.in net-neutrality predecessor — "more than 1.2 million signatures" (2014-2016)

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: campaign "gathered over 1.2 million signatures from Indian citizens" opposing discriminatory pricing.
Comparison: 1.2-million-signature figure matches Wikipedia exactly.
Decision: verified

## Claim 7: "the Telecom Regulatory Authority of India to issue regulations prohibiting discriminatory pricing"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "The TRAI subsequently issued regulations prohibiting zero-rating practices."
Comparison: TRAI action against discriminatory pricing matches; "zero-rating" and "discriminatory pricing" are coextensive in this context.
Decision: verified

## Claim 8: "became a staffed body in April 2018, at which point Apar Gupta ... took over as Executive Director"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "Gupta became Executive Director in April 2018"
Comparison: April 2018 staffing transition and Gupta-as-ED appointment match.
Decision: verified

## Claim 9: "Gupta served as Executive Director from April 2018 to July 2023"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation and https://en.wikipedia.org/wiki/Apar_Gupta
Source content: IFF Wikipedia article: Gupta "served in this capacity until July 2023." Apar Gupta Wikipedia article: Gupta "was appointed its first executive director from 2018 till November 2023."
Comparison: Two cited Wikipedia sources disagree on the end date of Gupta's first ED tenure (July 2023 vs. November 2023). Per source rule, Wikipedia cannot resolve a contradiction alone, and the claim is a "Living-person specifics beyond public role" / tenure-end-date fact that Wikipedia is tiebreaker-only for. No third canonical source was reachable this session.
Decision: unverifiable

## Claim 10: "returned to lead the organisation as Founder Director in November 2024"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: Gupta "returned to lead the organization as Founder Director in November 2024."
Comparison: November 2024 Founder Director return matches.
Decision: verified

## Claim 11: "registered as an Indian non-profit trust under Sections 80G and 12A of the Income Tax Act 1961"

Source: https://internetfreedom.in/transparency-and-finances/ (cited primary) — HTTP 403 this session
Source content: no canonical source content retrievable this session
Comparison: Specific statutory-section claim attributed to IFF's own transparency page; primary source unreachable this session. IFF Wikipedia article does not corroborate the specific section numbers. Public-record statutory claim with the only cited source unavailable.
Decision: unverifiable

## Claim 12: "by-laws adopted on 17 August 2022"

Source: https://internetfreedom.in/transparency-and-finances/ (cited primary) — HTTP 403 this session
Source content: no canonical source content retrievable this session
Comparison: Specific date claim attributed solely to IFF's own transparency page; unreachable this session. Not corroborated elsewhere.
Decision: unverifiable

## Claim 13: "Board of Trustees comprising Rachita Taneja, Aravind Ravi-Sulekha, Karthik Balakrishnan, and Apar Gupta"

Source: https://internetfreedom.in/transparency-and-finances/ (cited primary) — HTTP 403 this session
Source content: no canonical source content retrievable this session
Comparison: Trustee composition attributed solely to IFF's own transparency page; unreachable this session. Wikipedia does not list the Board of Trustees.
Decision: unverifiable

## Claim 14: "Project Panoptic ... launched on 27 November 2020"

Source: https://www.lawctopus.com/internet-freedom-foundation-iff-launches-project-panoptic/ (cited) — HTTP 403 this session
Source content: no canonical source content retrievable this session
Comparison: Specific launch date attributed to Lawctopus reporting; source unreachable this session. The IFF Wikipedia article confirms Project Panoptic exists but does not give a specific launch date ("No specific launch date is provided").
Decision: unverifiable

## Claim 15: "built jointly with volunteers from DataKind Bangalore and the Indian open-source software company Frappe"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "built by IFF along with volunteers from Datakind and Frappe."
Comparison: Wikipedia confirms DataKind and Frappe involvement but does not specify the "Bangalore" chapter. The chapter-specific claim is not corroborated in this session and the primary source (Lawctopus) was unreachable. The Frappe and DataKind partnership is verified; the Bangalore-chapter specifier is not.
Decision: unverifiable

## Claim 16: "As of November 2021 Panoptic documented seventy-eight FRT projects ... with a combined budgeted spend of approximately 9.6 billion Indian rupees"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "As of November 2021, Project Panoptic tracked 78 facial recognition technology (FRT) projects across India, with the tracked projects collectively budgeted at approximately 9.6 billion Indian rupees."
Comparison: Both figures match exactly.
Decision: verified

## Claim 17: "has since expanded past 120 government FRT tenders"

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "By 2024, the tracker had expanded to document over 120 government FRT tenders."
Comparison: Expansion past 120 tenders matches.
Decision: verified

## Claim 18: "Project Panoptic's Hyderabad-leg #BanTheScan campaign was conducted in partnership with Amnesty International and Article 19."

Source: no canonical source confirming this specific partnership found in this session
Source content: Wikipedia's IFF article extract does not mention #BanTheScan or the partner pair (Amnesty International + Article 19). Primary IFF source pages were 403 this session.
Comparison: Claim about a specific partner pair on a specific campaign is not corroborated by any reachable canonical source this session.
Decision: unverifiable

## Claim 19: "Supreme Court's judgment of 10 January 2020" in Anuradha Bhasin v. Union of India

Source: https://globalfreedomofexpression.columbia.edu/cases/bhasin-v-union-of-india/ (cited; 403 this session); cross-checked via WebSearch hits at Lawctopus, India Law Journal, Drishti Judiciary
Source content: "On 10th January 2020, a landmark decision by the Supreme Court of India declared access to the Internet a fundamental right under the Indian Constitution."
Comparison: 10 January 2020 judgment date is well-established across multiple secondary sources.
Decision: verified

## Claim 20: court held indefinite internet suspension illegal; necessity-and-proportionality tests required; access to internet integral to Article 19(1)(a)

Source: WebSearch hits at globalfreedomofexpression.columbia.edu / lawctopus / multiple legal-academic summaries
Source content: "The Supreme Court of India ruled that an indefinite suspension of internet services would be illegal under Indian law and that orders for internet shutdown must satisfy the tests of necessity and proportionality. ... freedom of speech and expression ... over the medium of internet enjoys constitutional protection under Article 19(1)(a) and Article 19(1)(g)."
Comparison: All three holdings (indefinite suspension illegal; necessity/proportionality test; Article 19(1)(a) constitutional protection of internet speech) match the body claim.
Decision: verified

## Claim 21: "5 August 2019 communications blackout ... alongside the abrogation of Article 370"

Source: cross-checked via WebSearch (Bhasin case summaries)
Source content: The shutdown was "imposed in the Jammu and Kashmir region in India on August 4, 2019" per one summary, while the Article 370 abrogation is widely dated 5 August 2019 (Bhasin "had been unable to publish her newspaper since August 6, 2019").
Comparison: The 5 August 2019 framing aligns with the Article 370 abrogation date; restrictions on communications began the night of 4-5 August 2019. The body's pairing of the blackout with Article 370 abrogation is consistent with the standard chronology.
Decision: verified

## Claim 22: "Foundation for Media Professionals' Supreme Court petition that led to the partial restoration of 4G mobile data in Jammu and Kashmir after a 550-day mobile-broadband blackout" (May 2020 IFF support)

Source: https://www.hrw.org/report/2023/06/14/no-internet-means-no-work-no-pay-no-food/internet-shutdowns-deny-access-basic
Source content: Mobile 4G internet access was "effectively down for over 500 days, until February 2021."
Comparison: The "over 500 days, until February 2021" HRW figure is consistent with the body's "550-day" claim (Aug 2019 to Feb 2021 ≈ 18 months). The IFF role in supporting the FMP Supreme Court petition is not corroborated in the reachable HRW report extract this session and the IFF primary page was 403; the causal "led to partial restoration" element is not directly verified.
Decision: unverifiable

## Claim 23: 2023 joint IFF+HRW report "No Internet Means No Work, No Pay, No Food" — 84 of 187 global shutdowns in 2022; 127 shutdowns across 18 Indian states between January 2020 and December 2022

Source: https://www.hrw.org/report/2023/06/14/no-internet-means-no-work-no-pay-no-food/internet-shutdowns-deny-access-basic
Source content: "Co-Authors: Human Rights Watch and Internet Freedom Foundation"; "In 2022, India accounted for '84 shutdowns out of 187 globally'"; "127 shutdowns in the three years between the Supreme Court's January 2020 landmark judgment and the end of 2022, affecting 18 of India's 28 states"; publication date 14 June 2023.
Comparison: Title, co-authors, publication month (June 2023), and both quantitative figures (84/187; 127 across 18 states) match.
Decision: verified

## Claim 24: AI-policy interventions — 2019 DoT "Indian AI Stack" submission; NITI Aayog #AIforAll critique; MeitY 2025 AI Governance Guidelines; Prix Ars Electronica 2022 Honorary Mention; Global Privacy Assembly 2025 Privacy and Human Rights Award

Source: https://en.wikipedia.org/wiki/Internet_Freedom_Foundation
Source content: "IFF filed comments on: the DoT's 'Indian AI Stack' concept (2019), NITI Aayog's draft #AIforAll framework, and MeitY's 2025 AI Governance Guidelines." Awards: "Prix Ars Electronica 2022 (Honorary Mention); Global Privacy Assembly (GPA) Privacy and Human Rights Award 2025."
Comparison: Three policy interventions and both awards all corroborated by Wikipedia; the DoT, NITI Aayog, and MeitY submissions are public-record-style policy facts within Wikipedia-alone sufficiency.
Decision: verified
