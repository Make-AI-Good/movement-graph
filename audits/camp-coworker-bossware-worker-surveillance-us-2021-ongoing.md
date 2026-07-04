---
entity_id: camp-coworker-bossware-worker-surveillance-us-2021-ongoing
entity_hash: fdcfc78bc973f0192fbf415020cc627fa1d6e8da
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 26
claims_corroborated: 10
claims_primary_sourced: 12
claims_single_source: 1
claims_uncorroborated: 2
open_corrections: 1
sources_consulted:
  - https://home.coworker.org/worktech/
  - https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
  - https://home.coworker.org/ostp-rfi-comments/
  - https://home.coworker.org/little-tech-goes-global/
  - https://s3.us-east-1.amazonaws.com/s3.coworker.org/images/Little_Tech_Goes_Global_Report.pdf
  - https://www.nlrb.gov/news-outreach/news-story/nlrb-general-counsel-issues-memo-on-unlawful-electronic-surveillance-and
  - https://governingforimpact.org/press-release-gfi-and-cdt-lead-broad-coalition-warning-white-house-of-risks-of-workplace-electronic-surveillance-and-automated-management/
  - https://cdt.org/wp-content/uploads/2023/06/CDT-et-al-Workplace-Surveillance-Comments-to-OSTP-revised.pdf
  - https://www.federalregister.gov/documents/2023/05/03/2023-09353/request-for-information-automated-worker-surveillance-and-management
  - https://bidenwhitehouse.archives.gov/ostp/news-updates/2023/05/01/hearing-from-the-american-people-how-are-automated-tools-being-used-to-surveil-monitor-and-manage-workers/
  - https://restofworld.org/2025/employee-surveillance-software-vc-funding/
  - https://www.eeoc.gov/newsroom/readout-eeoc-and-us-dols-ofccp-hosted-ai-and-algorithmic-fairness-and-hire-initiatives
  - https://www.irishtimes.com/business/work/never-mind-big-tech-little-tech-is-a-danger-for-workers-too-1.4809429
---

Connective-type entity (campaign): claims are edges and hard specifics per
`AUDITOR.md § Type-shape`; interpretive prose (the "Significance in the corpus"
section's framing, "structural gap," "dual dynamic") receives no decision. The
two cited report PDFs were fetched and full-text-extracted locally (~170k chars
for the 2021 report; stream-level extraction, no hex-encoded text remaining) —
quotes below marked "(report text)" come from that extraction; ligatures and
diacritics were stripped by extraction, restored here where obvious.

## Claim 1: scalar:start_date "2021-11-17" + body "launched … on November 17, 2021 with the public release of the Bossware and Employment Tech Database"

Source: https://home.coworker.org/worktech/
Source tier: primary
Source content: "Launch Date: November 17, 2021"
Comparison: Coworker's own database page states the launch date; matches frontmatter start_date and body. Also asserted in scalar:sources[0].note.
Decision: primary-sourced

## Claim 2: edges lead_orgs/participating_orgs → org-coworker; body link to ../organizations/org-coworker.md

Source: https://home.coworker.org/worktech/
Source tier: primary
Source content: The database and campaign live on home.coworker.org — "Coworker.org is a laboratory for workers to experiment with power-building s..." (report text, Coworker self-description)
Comparison: The campaign is Coworker.org's own; edge target `product/entities/organizations/org-coworker.md` exists and resolves to Coworker.org. Edge correct.
Decision: primary-sourced

## Claim 3: "a catalogue of over 550 labor-focused technology products … AI, location tracking, and biometric tools … every phase of employment" (body, goals, outcomes)

Source: https://home.coworker.org/worktech/ ; https://www.irishtimes.com/business/work/never-mind-big-tech-little-tech-is-a-danger-for-workers-too-1.4809429
Source tier: primary
Source content: "Over 550 labor-focused technology products … AI, location tracking, and biometrics to manage employees and collect their data … touch every part of the labor process, from hiring to productivity monitoring and more" (worktech); "compiled a database of more than 550 such products" (Irish Times)
Comparison: Count, technology classes, and lifecycle scope all match across Coworker's page and mainstream coverage. Body's incidental "organized by category, type, and founding date" was not specifically confirmed but is consistent with the report's methodology text ("we sought to capture information on workers and industries targeted; policies on privacy and data usage, storage, and retention; investor information").
Decision: corroborated

## Claim 4: "Workers can submit their own experiences with bossware to expand the database's evidential base" (body)

Source: https://home.coworker.org/worktech/
Source tier: primary
Source content: "Click here to share your story with our team" — the page invites workers who interact with catalogued technologies to submit their experiences.
Comparison: The participatory submission mechanism exists as described.
Decision: primary-sourced

## Claim 5: 2021 report title and author — "Little Tech Is Coming for Workers: A Framework for Reclaiming and Building Worker Power," authored by Wilneida Negrón, PhD (body, scalar:sources[1].note)

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
Source tier: primary
Source content: "LITTLE Tech Is Coming for Workers — A Framework for Reclaiming and Building Worker Power — By Wilneida Negrón, PhD" (report text, cover)
Comparison: Title and byline match the report cover exactly.
Decision: primary-sourced

## Claim 6: Negrón's title — "Coworker's Director of Policy and Research" (body)

Source: https://www.eeoc.gov/newsroom/readout-eeoc-and-us-dols-ofccp-hosted-ai-and-algorithmic-fairness-and-hire-initiatives ; https://restofworld.org/2025/employee-surveillance-software-vc-funding/
Source tier: primary
Source content: "Wilneida Negrón, Director of Policy and Research, Coworker.org" (EEOC readout); Rest of World renders the same role as "director of research and policy at Coworker.org"
Comparison: Government record matches the body's wording exactly; Rest of World flips the word order but names the same role — no substantive conflict.
Decision: corroborated

## Claim 7: "over 30 percent of the database's products emerged between 2020 and 2021" (body, outcomes, scalar:sources[1].note)

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf ; https://www.irishtimes.com/business/work/never-mind-big-tech-little-tech-is-a-danger-for-workers-too-1.4809429
Source tier: primary
Source content: "Thirty-one percent of the products listed emerged between 2020 and 2021; the rest were developed between 2018 and 2020." (report text); "about 30 per cent emerging between 2020 and 2021" (Irish Times)
Comparison: 31% supports "over 30 percent" as stated; mainstream coverage agrees on the figure and window.
Decision: corroborated

## Claim 8: "The report documented … Amazon's automated termination algorithm that generates warnings and firing decisions based on productivity tracking without human review" (body; scalar:sources[1].note claims the PDF is "primary source for … Amazon's automated-termination system")

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
Source tier: none
Source content: Amazon appears in the extracted report text only as: a Big Five company ("we still need to address the challenges posed by Big Tech companies (notably Facebook, Amazon, Google, Microsoft, and Apple)"); a customer of workplace tech and of Percept yx; a company "looking to use workers' productivity data to eventually automate their entire systems"; and a licensee of a union-tracking investigations tool. No passage on an automated termination algorithm, warnings, or firing without human review was found; "termination"/"ADAPT" do not appear in the ~170k-char extraction.
Comparison: The claim attributes a specific documented system to the cited report; near-full text extraction could not locate it (extraction is best-effort, so absence is not asserted definitively). Amazon's auto-termination system is documented elsewhere (e.g. 2019 The Verge/MIT Technology Review coverage), but no canonical source confirms that *this report* documents it. Affects body prose and scalar:sources[1].note.
Decision: uncorroborated

## Claim 9: "emotion-detection tools deployed in AI-powered hiring assessments" documented in the 2021 report (body, scalar:sources[1].note)

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
Source tier: primary
Source content: "Some of these products claim to track emotions such as anger, contempt, disgust, engagement, joy, sadness, surprise and valence … by analyzing a video clip"; "Human, which analyzes video-based job applications and scores candidates' emotional reactions" (report text; HireVue, Affectiva, Pymetrics also named)
Comparison: The report documents emotion detection in hiring assessments at length, as the body states.
Decision: primary-sourced

## Claim 10: "risk-modeling platforms sold to employers to flag workers as potential security or performance risks" documented in the 2021 report (body)

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
Source tier: primary
Source content: "The Verensics assessment focuses specifically on risk: risk of theft, risk of violence, risk of fraud"; "Oracle Retail XBRi Loss Prevention Cloud Service constantly monitors cashiers and provides managers with a daily, ranked list of high-risk workers"; Appriss Insights "risk and criminal justice intelligence company" case study (report text)
Comparison: Multiple such platforms are documented; matches the body.
Decision: primary-sourced

## Claim 11: "October 2022 memo from NLRB General Counsel Jennifer Abruzzo" (body, outcomes, scalar:sources[2].note)

Source: https://www.nlrb.gov/news-outreach/news-story/nlrb-general-counsel-issues-memo-on-unlawful-electronic-surveillance-and
Source tier: primary
Source content: NLRB news release dated October 31, 2022; General Counsel Jennifer Abruzzo announced the memo on electronic surveillance and automated management practices.
Comparison: Date (October 2022) and name/title match; also covered by multiple law-firm and legal-press analyses (Proskauer, Littler, Nov 2022).
Decision: corroborated

## Claim 12: presumptive-violation standard — practices that "would tend to interfere with or prevent a reasonable employee from engaging in Section 7-protected activity" presumptively violate the NLRA (body, outcomes)

Source: https://www.nlrb.gov/news-outreach/news-story/nlrb-general-counsel-issues-memo-on-unlawful-electronic-surveillance-and
Source tier: primary
Source content: "an employer has presumptively violated the Act where an employer's surveillance and management practices, viewed as a whole, would tend to interfere with or prevent a reasonable employee from engaging in activity protected by the Act."
Comparison: Body paraphrases the framework accurately, including the "viewed as a whole" and reasonable-employee elements; independently described in legal-press coverage.
Decision: corroborated

## Claim 13: memo proposed requiring employers to disclose monitoring technologies, business reasons, and data use (body, scalar:sources[2].note)

Source: https://www.nlrb.gov/news-outreach/news-story/nlrb-general-counsel-issues-memo-on-unlawful-electronic-surveillance-and
Source tier: primary
Source content: "require the employer to disclose to employees the technologies it uses to monitor and manage them, its reasons for doing so, and how it is using the information it obtains."
Comparison: Matches the body's three disclosure elements; independently described in legal-press coverage.
Decision: corroborated

## Claim 14: the memo was "the first significant federal regulatory guidance directly confronting bossware as a labor-rights harm" (body, outcomes)

Source: no canonical source found
Source tier: none
Source content: NLRB release and legal-press coverage describe the memo's novelty ("a new framework," "urging the Board to apply settled labor-law principles in a new framework") but none asserts it was the *first* federal regulatory guidance confronting bossware.
Comparison: "First" is a contested-attribution-class superlative (hedged by "significant"); no source found making the priority claim. Not a finding of error — names where the audit reaches its limits.
Decision: uncorroborated

## Claim 15: OSTP RFI published in the Federal Register May 3, 2023 (body, scalar:sources[4].note)

Source: https://www.federalregister.gov/documents/2023/05/03/2023-09353/request-for-information-automated-worker-surveillance-and-management
Source tier: primary
Source content: Federal Register document 2023-09353, "Request for Information; Automated Worker Surveillance and Management," published under the path /documents/2023/05/03/ (direct fetch bot-blocked; document identity and date confirmed via the Federal Register URL and search-indexed content, comment deadline June 15, 2023).
Comparison: Publication venue and date match the government record.
Decision: primary-sourced

## Claim 16: RFI "timed to International Workers' Day (May 1, 2023)" (body, scalar:sources[4].note)

Source: https://bidenwhitehouse.archives.gov/ostp/news-updates/2023/05/01/hearing-from-the-american-people-how-are-automated-tools-being-used-to-surveil-monitor-and-manage-workers/
Source tier: primary
Source content: OSTP blog post dated May 01, 2023: "Today, on International Workers' Day, the White House Office of Science and Technology Policy (OSTP) is announcing that it will be releasing a public request for information (RFI)…"
Comparison: OSTP's own announcement makes the International Workers' Day timing explicit.
Decision: primary-sourced

## Claim 17: "Coworker submitted independent comments on June 18, 2023" (body, outcomes, scalar:sources[3].note)

Source: https://home.coworker.org/ostp-rfi-comments/
Source tier: primary
Source content: Coworker's response page gives the submission date as June 18, 2023.
Comparison: Date matches Coworker's own page.
Decision: primary-sourced

## Claim 18: Coworker's three asks — convene vendors on transparency; fund research on impacts on federally protected groups; encourage algorithmic impact assessments as industry standard (body, scalar:sources[3].note)

Source: https://home.coworker.org/ostp-rfi-comments/
Source tier: primary
Source content: "Engage vendors in order to increase greater transparency over data collection and processing"; "Support more research into how these tools impact federally protected groups, especially in terms of the risk modeling/scoring and predictive analytics and also the training of AI systems that are being integrated into workforce management tools"; "OSTP should encourage the use of algorithmic impact assessments as an industry standard for these products."
Comparison: All three asks match, including the federally-protected-groups and risk-modeling/AI-training elements the body renders.
Decision: primary-sourced

## Claim 19: CDT- and GFI-led coalition of 14 organisations including ACLU, Communications Workers of America, Jobs With Justice, The Leadership Conference on Civil and Human Rights, and NELP (body, outcomes, scalar:sources[5].note; edge → org-aclu)

Source: https://governingforimpact.org/press-release-gfi-and-cdt-lead-broad-coalition-warning-white-house-of-risks-of-workplace-electronic-surveillance-and-automated-management/
Source tier: primary
Source content: "14 organizations" joined the coalition; the release names the American Civil Liberties Union, Communication Workers of America, Jobs With Justice, The Leadership Conference on Civil and Human Rights, and National Employment Law Project.
Comparison: Count and all five named members confirmed by GFI's release and CDT's parallel insight post. Body-link edge to org-aclu resolves (entity file exists).
Decision: corroborated

## Claim 20: coalition "submit[ted] joint comments on June 29, 2023" (body; scalar:sources[5].note dates the GFI press release June 29, 2023)

Source: https://cdt.org/wp-content/uploads/2023/06/CDT-et-al-Workplace-Surveillance-Comments-to-OSTP-revised.pdf
Source tier: primary
Source content: The coalition comment letter itself is headed "June 29, 2023 — To: White House, Office of Science and Technology Policy."
Comparison: Submission date matches the letter (primary document). The GFI press-release page as fetched displays no explicit publication date, so scalar:sources[5].note's "(June 29, 2023)" is supported by the letter date rather than the release page — consistent, not contradicted.
Decision: primary-sourced

## Claim 21: coalition recommendations targeted DOL, EEOC, FTC, NIOSH, and OSHA (body, outcomes, scalar:sources[5].note)

Source: https://governingforimpact.org/press-release-gfi-and-cdt-lead-broad-coalition-warning-white-house-of-risks-of-workplace-electronic-surveillance-and-automated-management/
Source tier: primary
Source content: "The comments include specific recommendations for how federal agencies–including the Department of Labor, Equal Employment Opportunity Commission (EEOC), Federal Trade Commission (FTC), National Institute for Occupational Safety and Health (NIOSH), and Occupational Safety and Health Administration (OSHA)–can use regulation and public education to prevent and mitigate these risks."
Comparison: All five agencies match; independently stated in CDT's insight post.
Decision: corroborated

## Claim 22: "In 2025, Coworker extended the 'Little Tech' frame internationally with the 'Little Tech Goes Global' report" (body, outcomes, scalar:sources[6].note)

Source: https://home.coworker.org/little-tech-goes-global/ ; https://restofworld.org/2025/employee-surveillance-software-vc-funding/
Source tier: primary
Source content: Landing page: report published June 3, 2025, "maps the global rise of algorithmic management across six countries"; Rest of World covered the report in 2025.
Comparison: Year and framing extension confirmed by Coworker's page and mainstream coverage.
Decision: corroborated

## Claim 23: the 2025 report was "(authored by Fabricio Barilli)" (body)

Source: https://home.coworker.org/little-tech-goes-global/ ; https://s3.us-east-1.amazonaws.com/s3.coworker.org/images/Little_Tech_Goes_Global_Report.pdf ; https://restofworld.org/2025/employee-surveillance-software-vc-funding/
Source tier: primary
Source content: Landing page credits "Wilneida Negrón, Coworker.org" as the published author, with Fabricio Barilli listed among Contributors; the report text names him as one of six country collaborators — "This regional analysis was conducted in collaboration with six public interest technologists, lawyers, and researchers based in those countries: Mariel Garcia-Montes (Mexico), Celso Bessa (Colombia), Fabricio Barili (Brazil) …"; Rest of World identifies Negrón and Ayden Férdeline as co-authors.
Comparison: The body attributes report authorship to Barilli; the best sources converge on Wilneida Negrón as the report's author, with Barilli the Brazil-country collaborator/contributor. Single-token replacement: "authored by Wilneida Negrón". (A stray search-indexed PDF title reading "Authored By Fabricio Barilli" exists, but the fetched report text and Coworker's own landing page both contradict it.)
Decision: correction

## Claim 24: six Global South countries — Mexico, Colombia, Brazil, Nigeria, Kenya, and India (body, outcomes, scalar:sources[6].note)

Source: https://s3.us-east-1.amazonaws.com/s3.coworker.org/images/Little_Tech_Goes_Global_Report.pdf ; https://home.coworker.org/little-tech-goes-global/
Source tier: primary
Source content: "We then examined trends in six countries — Mexico, Colombia, Brazil, Nigeria, Kenya, and India — where startup investments were increasing." (report text)
Comparison: Country list matches exactly; confirmed by landing page and Rest of World.
Decision: corroborated

## Claim 25: "The report identified 150+ startups and regional vendors in those markets" (body)

Source: https://restofworld.org/2025/employee-surveillance-software-vc-funding/
Source tier: mainstream
Source content: "Audits of more than 150 startups and regional companies" were conducted.
Comparison: Rest of World confirms the 150+ figure as the report's audit scope. The figure was not located in the report's own extracted text (the only "150" there is Nigeria-specific: "over 150 distinct brands available in the Nigerian market" for CCTV), so support rests on one mainstream source.
Decision: single-source

## Claim 26: vendors "frequently retaining worker data indefinitely and in some cases extending surveillance into workers' homes and family lives" (body, scalar:sources[6].note)

Source: https://home.coworker.org/little-tech-goes-global/
Source tier: primary
Source content: "many vendors offer copy-paste privacy notices while quietly retaining worker data indefinitely"; "In countries like Mexico and Colombia, some companies even conduct home visits and collect data on workers' families."
Comparison: Both elements match Coworker's own report page.
Decision: primary-sourced
