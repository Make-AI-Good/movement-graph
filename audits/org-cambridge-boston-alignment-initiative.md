---
entity_id: org-cambridge-boston-alignment-initiative
entity_hash: c837302ec611c240163f92a5e763637aea08edd6
audit_date: 2026-09-17
pass: 1
status: supported
claims_total: 24
claims_corroborated: 2
claims_primary_sourced: 16
claims_single_source: 0
claims_uncorroborated: 6
open_corrections: 0
sources_consulted:
  - https://www.cbai.ai/
  - https://www.cbai.ai/cambria
  - https://projects.propublica.org/nonprofits/organizations/921463153
  - https://www.lesswrong.com/posts/LShJtvwDf4AMo992L/update-on-harvard-ai-safety-team-and-mit-ai-alignment
  - https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-student-ai-safety-groups/
  - https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-2025-summer-fellowship/
  - https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-haist-office-space/
  - https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-ai-safety-field-building/
  - https://app.grantmaking.ai/orgs/aeaf5f1d-7b11-4d3f-9c7c-cde18a57da14
  - https://www.goodventures.org/our-portfolio/grants/cambridge-boston-alignment-initiative-ai-safety-field-building/
---

## Claim 1: "a Cambridge, Massachusetts 501(c)(3) public charity (EIN 92-1463153)"

Source: https://www.cbai.ai/ and https://projects.propublica.org/nonprofits/organizations/921463153
Source tier: primary
Source content: cbai.ai: "a Cambridge, MA-based 501(c)(3) non-profit"; EIN listed as 92-1463153. ProPublica/IRS: "Cambridge Boston Alignment Initiative Inc", Cambridge, MA, EIN 92-1463153, "Designated as a 501(c)(3)".
Comparison: Own site and IRS filing data independently confirm location, 501(c)(3) status, and EIN. Also confirms frontmatter `location` scalar.
Decision: corroborated

## Claim 2: "Founded in 2022" (body + frontmatter `founded: 2022`)

Source: https://www.cbai.ai/
Source tier: primary
Source content: "a Cambridge, MA-based 501(c)(3) non-profit, founded in 2022, with the original goal of reducing risks from advanced AI systems through research on AI alignment"
Comparison: Own-site founding year matches body and the frontmatter `founded` scalar exactly.
Decision: primary-sourced

## Claim 3: CBAI provides fiscal sponsorship to MIT AI Alignment (MAIA) and the Harvard AI Safety Team (AISST)

Source: https://www.cbai.ai/
Source tier: primary
Source content: Fiscally sponsored student teams listed: "MAIA (MIT AI Alignment)" and "AISST (Harvard AI Safety Team)"
Comparison: Own site names exactly these two fiscally sponsored student groups; the MAIA cross-reference edge points to the correct entity (lg-mit-ai-alignment). Also confirms sources[0].note's two-groups sentence.
Decision: primary-sourced

## Claim 4: "In fall 2022, a founding team ... transformed an informal MIT–Harvard reading group into two distinct student organisations"

Source: https://www.lesswrong.com/posts/LShJtvwDf4AMo992L/update-on-harvard-ai-safety-team-and-mit-ai-alignment
Source tier: primary
Source content: Post (2 Dec 2022) says the groups expanded from "one group of about 15 Harvard and MIT students who read AI alignment papers together once a week" over the prior ~3 months.
Comparison: The reading-group-to-two-organisations transformation in fall 2022 matches the founders' own contemporaneous account.
Decision: primary-sourced

## Claim 5: The founding team "included Trevor Levin and Sam Marks" and was "simultaneously establishing CBAI as the 501(c)(3) umbrella"

Source: https://www.lesswrong.com/posts/LShJtvwDf4AMo992L/update-on-harvard-ai-safety-team-and-mit-ai-alignment and https://projects.propublica.org/nonprofits/organizations/921463153
Source tier: primary
Source content: LW post authors include Sam Marks and tlevin; it credits Levin with retreats and Marks with the intro fellowship, and mentions CBAI only as bootcamp partner. 990 lists Levin (Secretary) and Marks (Board Member) as officers.
Comparison: No fetched canonical source states who founded CBAI itself. Officer roles and group-organiser roles support the inference but "founding team ... establishing CBAI" is a composite not directly attested (a charityjournal.org snippet names Jeyapragasan/Levin as founders but is not canonical-tier).
Decision: uncorroborated

## Claim 6: "CBAI's 501(c)(3) status was recognised by the IRS effective November 2023"

Source: https://projects.propublica.org/nonprofits/organizations/921463153
Source tier: primary
Source content: "Designated as a 501(c)(3)" with tax exemption issued in November 2023
Comparison: IRS record matches the month and year exactly. Also confirms sources[2].note.
Decision: primary-sourced

## Claim 7: "Kuhan Jeyapragasan, who co-organised MAIA's early retreats, serves as President"

Source: https://www.lesswrong.com/posts/LShJtvwDf4AMo992L/update-on-harvard-ai-safety-team-and-mit-ai-alignment and https://projects.propublica.org/nonprofits/organizations/921463153
Source tier: primary
Source content: LW post: "Ran two retreats (organized by Trevor Levin and Kuhan Jeyapragasan)". 990: "Kuhan Jeyapragasan — President".
Comparison: Retreat co-organiser role and President office each confirmed by one primary source. The post describes the retreats in the joint HAIST/MAIA community context rather than as MAIA-only; minor framing, not a factual conflict.
Decision: primary-sourced

## Claim 8: "Levin as Secretary; and Marks as a board member"

Source: https://projects.propublica.org/nonprofits/organizations/921463153
Source tier: primary
Source content: "Trevor Levin — Secretary ... Sam Marks — Board Member" (also "Carson Ezell — Treasurer (Since June 2024)", confirming sources[2].note's "Treasurer as of June 2024")
Comparison: Officer roster matches the IRS filing exactly, including the sources[2].note scalar's Ezell treasurer transition.
Decision: primary-sourced

## Claim 9: "The January 2023 MLAB-inspired ML bootcamp — one of the first concrete CBAI outputs"

Source: https://www.lesswrong.com/posts/LShJtvwDf4AMo992L/update-on-harvard-ai-safety-team-and-mit-ai-alignment
Source tier: primary
Source content: "organizing an MLAB-inspired ML bootcamp in January 2023 in partnership with the Cambridge Boston Alignment Initiative"
Comparison: Date, MLAB inspiration, and CBAI partnership match the founders' contemporaneous post ("one of the first concrete outputs" is proportionate given CBAI founded 2022). Also confirms sources[3].note.
Decision: primary-sourced

## Claim 10: CAMBRIA is "the Cambridge Bootcamp for Research in Interpretability and Alignment ... a three-week in-person ML upskilling programme built on the ARENA curriculum" covering "transformers, deep reinforcement learning, and mechanistic interpretability"

Source: https://www.cbai.ai/cambria
Source tier: primary
Source content: "Cambridge Bootcamp for Research in Interpretability and Alignment"; "a 3-week ML upskilling bootcamp for AI safety, focusing on interpretability and RL"; based on the "ARENA curriculum"
Comparison: Full name, 3-week length, and ARENA basis match verbatim; live page states the focus as interpretability and RL (the transformers/deep-RL/mech-interp trio is the ARENA curriculum's content, quoted from this page at draft time).
Decision: primary-sourced

## Claim 11: "CAMBRIA is open beyond MIT and Harvard: any applicant with Python proficiency, multivariable calculus, and linear algebra can apply"

Source: https://www.cbai.ai/cambria
Source tier: primary
Source content: "Familiarity with Python and comfort with multivariable calculus (e.g., chain rule) and linear algebra"; no institutional restriction appears on the page.
Comparison: Prerequisites match verbatim; open-application status consistent with the page (no MIT/Harvard-only limit).
Decision: primary-sourced

## Claim 12: "CBAI provides housing, meals, 24/7 office access, and travel support" (CAMBRIA)

Source: https://www.cbai.ai/cambria
Source tier: primary
Source content: Housing and meals provided; "24/7 office access in Harvard Square"; travel support
Comparison: All four provisions confirmed on the live program page.
Decision: primary-sourced

## Claim 13: "In 2026, three cohorts run across two cities: two at Harvard Square (May–June, August) and one in Manhattan, hosted by Collider (July)" (body + sources[1].note; also "partnering with New York-based venues like Collider")

Source: https://www.cbai.ai/cambria
Source tier: primary
Source content: Live page now details only "August 10-28 cohort in Cambridge, MA"; search index additionally carries a January 5-23, 2026 Cambridge cohort. No currently fetchable source mentions a Manhattan/Collider cohort or the May–June cohort.
Comparison: The cohort listing has rotated since the 2026-06-12 fetch recorded in sources[1].note; only the August Harvard Square cohort remains attested. The three-cohort structure and the Collider/Manhattan venue are no longer confirmable and web.archive.org is unavailable. Partial confirmation, no contradicting token with a single replacement.
Decision: uncorroborated

## Claim 14: "CBAI runs a summer fellowship focused on the intersection of AI and biosecurity risks" (AIxBiosecurity Summer Fellowship)

Source: https://www.cbai.ai/
Source tier: primary
Source content: Programs listed include "AIxBiosecurity Fellowship" (program page live at cbai.ai/aixbiosecurity-fellowship-program, "CBAI AIxBiosecurity Research Fellowship Program")
Comparison: Program exists and matches the AI-biosecurity intersection focus; live naming has dropped "Summer" from the June-2026 form recorded in sources[0].note (naming drift, not error).
Decision: primary-sourced

## Claim 15: "Summer Research Fellowship. A direct research-placement fellowship ... over the summer period"

Source: https://www.cbai.ai/ and https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-2025-summer-fellowship/
Source tier: primary
Source content: cbai.ai hosts a "Summer Research Fellowship" page (fellowship "runs from June 8 to August 10, 2026, bringing together up to 30 fellows"); OP grant record: "$350,000 to Cambridge Boston Alignment Initiative to support its Summer Research Fellowship. Fellows will work closely with established AI safety researchers".
Comparison: Program existence and research-placement character confirmed by the entity's own site and the funder's grant record.
Decision: corroborated

## Claim 16: "CBAI's FY2024 Form 990 shows revenue of $1,968,408, nearly all from contributions, and total assets of $1,361,474" (body + sources[2].note figures incl. 99.2% and expenses $1,106,851)

Source: https://projects.propublica.org/nonprofits/organizations/921463153
Source tier: primary
Source content: FY2024: "Total Revenue: $1,968,408; Contributions: $1,952,438 (99.2% of revenue); Total Expenses: $1,106,851; Total Assets: $1,361,474"
Comparison: Every figure matches the IRS filing data exactly, including the sources[2].note scalar's 99.2% and expenses figures.
Decision: primary-sourced

## Claim 17: "The FY2023 figure was $1,497,763 — growth of approximately 30% in one year"

Source: https://projects.propublica.org/nonprofits/organizations/921463153
Source tier: primary
Source content: FY2023 "Total Revenue: $1,497,763"
Comparison: FY2023 figure exact; 1,968,408 / 1,497,763 = 1.314, so "approximately 30%" is a fair rounding.
Decision: primary-sourced

## Claim 18: Staff roster: "a Director of Programs (Emre Yavuz), Director of Operations (Maite Abadia-Manthei), three Research Managers (Alex Semendinger, Claudio Mayrink Verdun, Dmitrii Troitskii), and an Operations Associate"

Source: https://www.cbai.ai/
Source tier: primary
Source content: Live team page: "Emre Yavuz, Director of Programs; Maite Abadia-Manthei, Director of Operations; Alex Semendinger, Upskilling Programs Manager; Claudio Mayrink Verdun, Research Manager; Dmitrii Troitskii, Research Manager; Logan Smith, Senior Research Manager; Alex Mark, Research Manager; Misha Salahshoor, Operations Associate; Penina Crocker, Fellowship Operations Associate"
Comparison: Yavuz and Abadia-Manthei titles confirmed; but the specific "three Research Managers (Semendinger, Verdun, Troitskii)" configuration has drifted — Semendinger is now Upskilling Programs Manager and the research-manager bench is Verdun/Troitskii/Mark plus a Senior RM. Roster as stated matches the June-2026 snapshot, not any currently fetchable source; wholesale drift, no single-token replacement.
Decision: uncorroborated

## Claim 19: "Coefficient Giving (formerly Open Philanthropy) is CBAI's primary documented institutional funder" (+ funders edge fund-coefficient-giving; rename context in sources[4]/[5].notes)

Source: https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-student-ai-safety-groups/ and https://en.wikipedia.org/wiki/Coefficient_Giving
Source tier: primary
Source content: OP/Coefficient grant database records multiple CBAI grants ($1,170,000 student groups; $350,000 summer fellowship; $151,678 HAIST office space; $42,807 cybersecurity bootcamp — via search snippets of the records); Wikipedia: "in November 2025, Open Philanthropy was renamed Coefficient Giving"; 990 shows 99.2% contribution-funded revenue.
Comparison: Multiple grants from the funder's own database plus the rename (funder's own pages + Wikipedia as tiebreaker) support the primary-funder characterisation; the funders edge points at the correct entity.
Decision: corroborated

## Claim 20: Grants "spanning 2023 to 2025"

Source: https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-2025-summer-fellowship/
Source tier: primary
Source content: Summer Fellowship grant record "dated September 2, 2025"; no fetchable record carries an award date for the earliest grants (post-rebrand, several grant URLs 301 to the generic coefficientgiving.org/funds/ page and coefficientgiving.org 403s).
Comparison: The 2025 endpoint is confirmed; the 2023 endpoint of the span is not attested in any currently fetchable canonical source (FY2023 revenue of $1.5M is consistent with 2023 grants but does not date them).
Decision: uncorroborated

## Claim 21: "$1,170,000 for AISST and MAIA operating costs" (body + sources[4].note)

Source: https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-student-ai-safety-groups/
Source tier: primary
Source content: "Open Philanthropy recommended a grant of $1,170,000 to the Cambridge Boston Alignment Initiative to support operating costs for Harvard's AI Safety Student Team (AISST) and MIT AI programs" (via search snippet of the grant record)
Comparison: Amount and purpose match the funder's own grant record. Scalar fix location if ever needed: sources[4].note.
Decision: primary-sourced

## Claim 22: "$550,000 for Harvard AI safety education and outreach"

Source: no canonical source found
Source tier: none
Source content: Targeted searches for the amount and purpose surface no matching grant record; the OP grants found are $1,170,000 / $350,000 / $151,678 ("lease office space for HAIST, a project that facilitates AI safety education and outreach activities for Harvard students") / $42,807. Post-rebrand, coefficientgiving.org 403s and several legacy grant URLs redirect to a generic funds page.
Comparison: The $550,000 figure is unattested in any currently fetchable canonical source. The nearest thematic match (HAIST office space, "education and outreach" wording) carries a different amount, so no single-replacement correction can be asserted.
Decision: uncorroborated

## Claim 23: "$387,741 for AI safety field-building" (body + sources[5].note)

Source: https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-ai-safety-field-building/
Source tier: none
Source content: "REDIRECT ... Location: https://coefficientgiving.org/funds/ Status: 301 Moved Permanently" — the cited grant record no longer resolves (generic funds page; coefficientgiving.org 403 on all paths); the amount appears in no search snippet, and the goodventures.org mirror slug renders only the generic giving-approach page.
Comparison: The record the claim rests on has been redirected away post-rebrand (same class as the BlueDot £3,867,018 case); amount now unverifiable. Scalar fix location if ever needed: sources[5].note.
Decision: uncorroborated

## Claim 24: "$350,000 for the 2025 Summer Research Fellowship"

Source: https://www.openphilanthropy.org/grants/cambridge-boston-alignment-initiative-2025-summer-fellowship/
Source tier: primary
Source content: "Open Philanthropy recommended a grant of $350,000 to Cambridge Boston Alignment Initiative to support its Summer Research Fellowship" (grant record dated September 2, 2025, via search snippet)
Comparison: Amount, year, and purpose match the funder's own grant record.
Decision: primary-sourced
