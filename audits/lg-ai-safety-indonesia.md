---
entity_id: lg-ai-safety-indonesia
entity_hash: a2e3410f714ca175773e2aa90017ff0f706988c3
audit_date: 2026-09-03
pass: 1
status: supported
claims_total: 18
claims_corroborated: 2
claims_primary_sourced: 12
claims_single_source: 1
claims_uncorroborated: 3
open_corrections: 0
sources_consulted:
  - https://aisafety.id/
  - https://aisafety.id/training/
  - https://luma.com/j808d2ks
  - https://aisafetyindonesia.substack.com/p/ai-red-teaming
  - https://luma.com/user/aisafety
  - https://mansurarief.github.io/
  - https://en.wikipedia.org/wiki/Indonesia
---

## Claim 1: "Jakarta-based community organization whose mission is to build 'a grassroot community of AI Safety guardians' ensuring 'our values and spirit of gotong royong are reflected in the AI technologies we use'"

Source: https://aisafety.id/
Source tier: primary
Source content: "building a grassroot community of AI Safety guardians to ensure our values and spirit of gotong royong are reflected in the AI technologies"; location listed as Jakarta, Indonesia; contact aisafetyindonesia@gmail.com
Comparison: Mission quote and Jakarta base match the organization's own site verbatim (also covers scalar sources[0].note). Frontmatter `location: Jakarta, Indonesia` matches.
Decision: primary-sourced

## Claim 2: "Founded in 2025" (and scalar `founded: 2025`)

Source: no canonical source found
Source tier: none
Source content: aisafety.id states no founding date; Luma profile (https://luma.com/user/aisafety) shows "Joined April 2025" — consistent circumstantial evidence only
Comparison: No source explicitly states a founding year. All observed activity (Luma join April 2025, Substack launch May 2025, Batch 02 May 2025) is consistent with 2025 but the "Batch 02" note leaves open that batch 01 predated 2025. Not a contradiction; support is circumstantial. Scalar path: `founded`.
Decision: uncorroborated

## Claim 3: "runs two programs — an AI Safety Professional Training Program … and a student-focused Outreach Program"

Source: https://aisafety.id/
Source tier: primary
Source content: "Professional Training Program - certification for professionals implementing AI safety; Outreach Program - workshops and mentorship for high school and undergraduate students"
Comparison: Both programs named on the homepage exactly as the body describes.
Decision: primary-sourced

## Claim 4: Training program "developed in partnership with the Stanford Center for AI Safety"

Source: https://aisafety.id/training/ ; https://mansurarief.github.io/
Source tier: primary
Source content: aisafety.id/training: certification program "developed in collaboration with Stanford Center for AI Safety". Arief (then Stanford CAIS Executive Director) on his own site: "a part of the AI Safety Indonesia community, which is a group of researchers, practitioners, and policymakers dedicated to bulding AI safety capacity in Indonesia" [sic]
Comparison: Two independent primary sources — the organization's own program page and the personal site of the Stanford Center for AI Safety's then-Executive Director confirming his involvement in the community — support the collaboration.
Decision: corroborated

## Claim 5: "official certification from Stanford Center for AI Safety awarded on completing each course"

Source: https://aisafety.id/training/
Source tier: primary
Source content: "official certification from the Stanford Center for AI Safety upon completing each course"
Comparison: Verbatim match on the organization's own training page. No Stanford-side page confirming the certification arrangement was found; support rests on the single primary source.
Decision: primary-sourced

## Claim 6: Three-course sequence — Fundamentals (6-day intensive or 6-week distributed, fully remote); Principles in 4D (3-day in-person, four lifecycle stages design/development/deployment/decommissioning); Professional (6-day intensive at Stanford campus with site visits)

Source: https://aisafety.id/training/
Source tier: primary
Source content: "AI Safety Fundamentals … 6 days (intensive) or 6 weeks (distributed)" (fully remote, synchronous); "AI Safety Principles in 4D (Design, Development, Deployment, & Decommissioning) … 3 days, in-person"; "AI Safety Professional … 4 lectures + 2 labs + 3 site visits + 1 capstone + 1 exam (6 days, at Stanford)"
Comparison: Course names, durations, formats, lifecycle stages, and Stanford site visits all match the training page.
Decision: primary-sourced

## Claim 7: The 4D course is an in-person intensive "in Jakarta"

Source: https://aisafety.id/training/
Source tier: primary
Source content: "6 lectures + 3 labs + 1 capstone/exam (3 days, in-person, Indonesia)"
Comparison: Current page says "in-person, Indonesia," not Jakarta. The 2026-06-08 sources note (scalar `sources[1].note`) recorded "in-person Jakarta," but the Jakarta specific is not on the page now and no other source names the city. Consistent (org is Jakarta-based) but not confirmed; not a contradiction.
Decision: uncorroborated

## Claim 8: "opened applications April 7–25, 2025 with the program starting May 5–9, 2025"

Source: https://aisafety.id/training/
Source tier: primary
Source content: "Registration: April 7-25, 2025; Program Start: May 5-9, 2025"
Comparison: Exact date match on the training page.
Decision: primary-sourced

## Claim 9: The May 2025 cohort was "Batch 02 … indicating Batch 01 had already run"

Source: https://aisafety.id/training/
Source tier: primary
Source content: Current page presents the April/May 2025 dates as "Upcoming Cohort Timeline" with no batch numbering visible
Comparison: The "Batch 02" label appears in the 2026-06-08 sources note (scalar `sources[1].note`: "Batch 02 applications closed April 25 2025") but is not on the current page and no other source carries it; web.archive.org is unreachable from this harness so the prior page state cannot be checked. The Batch-01 inference inherits the uncertainty. Not a contradiction.
Decision: uncorroborated

## Claim 10: "Yan Pratama Akhra serves as Program Manager" (and edge `key_people: person-yan-pratama-akhra`)

Source: https://aisafety.id/training/
Source tier: primary
Source content: "Yan Pratama Akhra" listed as "AI Safety Professional Training Program Manager"
Comparison: Name and role match; the `key_people` edge resolves to the existing person entity.
Decision: primary-sourced

## Claim 11: Program "explicitly aimed at professionals and organizations working with AI systems, rather than students"

Source: https://aisafety.id/training/
Source tier: primary
Source content: Designed for "Business Executives," "Risk Management Professionals," "Data Scientists, AI Engineers, and Tech Program Managers" and others with professional experience and AI implementation/governance responsibilities
Comparison: Target-audience description matches the professional orientation stated in the body.
Decision: primary-sourced

## Claim 12: Outreach Program targets "high school and undergraduate students through workshops, competitions, and mentorship"; "annual AI safety competitions and a symposium are planned"

Source: https://aisafety.id/ ; https://aisafetyindonesia.substack.com/p/ai-red-teaming
Source tier: primary
Source content: Homepage: "Outreach Program - workshops and mentorship for high school and undergraduate students"; Substack: "annual AI safety competitions and symposium"
Comparison: Student focus, workshops, mentorship, and planned competitions/symposium all match the organization's own materials (two pages, one organization — one independent source).
Decision: primary-sourced

## Claim 13: "A May 3, 2025 webinar commemorating National Education Day brought together speakers from the Stanford Center for AI Safety, Satu Data Indonesia at Bappenas, MindSTEM Indonesia, and the University of Pittsburgh" (and scalar `sources[2].note` speaker list)

Source: https://luma.com/j808d2ks
Source tier: primary
Source content: "Digitalization and AI Safety in Indonesia - AI Safety Indonesia Webinar," Saturday, May 3, 2025, 08:00-10:00 WIB via Zoom, "in commemoration of National Education Day (Hardiknas) 2025"; speakers: Mansur Maturidi Arief ("Executive Director, Center for AI Safety, Stanford University"), Dini Maghfirra ("Executive Director, Satu Data Indonesia, Bappenas"), Muhammad Rizki Oktavian ("Initiator MindSTEM Indonesia, Research Scholar, Purdue University"), Bayu Aryo Yudanta ("PhD Student, Rehabilitation Science, University of Pittsburgh"); e-certificate for "3 JP" (learning hours)
Comparison: Date, format, occasion, all four speakers, their affiliations, and the 3-credit-hour certificate match the event page. Scalar path: `sources[2].note`.
Decision: primary-sourced

## Claim 14: Mansur Maturidi Arief was Executive Director of the Stanford Center for AI Safety (the "speakers from the Stanford Center for AI Safety" edge of Claim 13)

Source: https://luma.com/j808d2ks ; https://mansurarief.github.io/
Source tier: primary
Source content: Luma (contemporaneous): "Executive Director, Center for AI Safety, Stanford University"; his own site (2026): he "served as Executive Director of the Stanford Center for AI Safety" (now Assistant Professor at KFUPM)
Comparison: Two independent sources confirm he held the role at the time of the May 2025 webinar; his own site confirms it is now a past role, which does not affect the entity's time-scoped claim.
Decision: corroborated

## Claim 15: Described as "a consortium bringing together government agencies, private companies, and academic institutions"; partnerships with Satu Data Indonesia, Stanford Center for AI Safety, AI Safety Asia, AI Safety Korea, and AI Safety India; "three training batches scheduled" (scalar `sources[3].note`)

Source: https://aisafetyindonesia.substack.com/p/ai-red-teaming
Source tier: primary
Source content: "a consortium bringing together government agencies, private companies and academic institutions"; collaborates with "Satu Data Indonesia, Stanford Center for AI Safety, AI Safety Asia, AI Safety Korea, and AI Safety India"; "Three batches of AI safety training courses currently scheduled and annual AI safety competitions and symposium"
Comparison: Consortium quote, all five named partners, and the three-batches item match the organization's own Substack article. Scalar path: `sources[3].note`.
Decision: primary-sourced

## Claim 16: "maintains a newsletter at aisafetyindonesia.substack.com covering topics such as culturally-aware AI red teaming for the Indonesian market" (article dated May 4, 2025)

Source: https://aisafetyindonesia.substack.com/p/ai-red-teaming
Source tier: primary
Source content: Article published May 04, 2025, advocating "localized red teaming approaches" for Indonesia's multilingual (700+ languages), archipelagic, culturally complex market
Comparison: Newsletter exists at the stated address; the red-teaming article matches the described topic and date.
Decision: primary-sourced

## Claim 17: "hosts events through Luma (seven events hosted as of mid-2025)"

Source: https://luma.com/user/aisafety
Source tier: primary
Source content: Profile shows "7Hosted" and "Joined April 2025"
Comparison: The profile's current hosted-event count (2026-09-03) is exactly seven, matching the body figure; the count today equals the claimed mid-2025 figure, so the snapshot timing is consistent though not independently datable.
Decision: primary-sourced

## Claim 18: Background country facts — Indonesia is the world's fourth-most-populous country (~280 million), the world's largest Muslim-majority nation, the largest economy in Southeast Asia, spanning ~17,000 islands with hundreds of languages

Source: https://en.wikipedia.org/wiki/Indonesia
Source tier: tiebreaker
Source content: "Home to over 280 million people" (2025 est. 288,315,089); "ranks fourth in the world by population"; "has the largest Muslim population of any country" (87.2% Muslim — also a majority); "Indonesia has the largest economy in Southeast Asia"; island counts "ranging from 13,466 named islands to more than 17,500"
Comparison: All background specifics match; "17,000 islands" falls within the published counting range. These are named-entity definitional / public-record facts for which Wikipedia alone is sufficient per the source rule; one canonical non-primary source supports.
Decision: single-source
