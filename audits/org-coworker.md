---
entity_id: org-coworker
entity_hash: 61b8ee752af4b210fee89817c5c1c9dad0e98023
audit_date: 2026-09-17
pass: 1
status: corrections-pending
claims_total: 31
claims_corroborated: 9
claims_primary_sourced: 14
claims_single_source: 3
claims_uncorroborated: 3
open_corrections: 2
sources_consulted:
  - https://home.coworker.org/about-us/
  - https://home.coworker.org/victories/
  - https://home.coworker.org/worktech/
  - https://home.coworker.org/welcoming-coworkers-new-executive-director/
  - https://home.coworker.org/meeting-the-moment/
  - https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
  - https://home.coworker.org/resources/grounds-for-change-how-baristas-won-visible-tattoos-at-starbucks/
  - https://fellows.echoinggreen.org/fellow/jessica-kutch/
  - https://www.coworker.org/petitions/uber-and-lyft-give-drivers-a-voice
  - https://en.wikipedia.org/wiki/Coworker_(company)
  - https://www.influencewatch.org/non-profit/coworker-org/
  - https://lwp.georgetown.edu/practitionerfellows/michelle-miller-and-coworker-org-selected-for-echoing-green-fellowship/
  - https://coworkerfund.org/about/
  - https://www.fastcompany.com/90737935/tech-employees-organizing-their-workplaces-drew-on-this-mutual-aid-tool
  - https://money.cnn.com/2014/09/10/news/companies/starbucks-tattoos/index.html
  - https://www.fordfoundation.org/work/our-grants/awarded-grants/grants-database/new-venture-fund-134071/
  - https://culturalworkersorganize.org/platform-organizing-digital-tools-for-worker-communication/
  - https://just-tech.ssrc.org/our-network/michelle-miller/
  - https://sici.hks.harvard.edu/person/michelle-miller/
  - https://restofworld.org/2025/employee-surveillance-software-vc-funding/
  - https://blogs.law.ox.ac.uk/business-law-blog/blog/2022/01/worker-data-subject-resources-data-protection-day
  - https://laborcenter.berkeley.edu/how-common-is-employers-use-of-workplace-management-technologies-a-review-of-prevalence-studies/
  - https://www.workerinfoexchange.org/post/historic-digital-rights-win-for-wie-and-the-adcu-over-uber-and-ola-at-amsterdam-court-of-appeal
  - https://techcrunch.com/2023/04/05/uber-ola-gdpr-worker-data-access-rights-appeal/
  - https://www.wga.org/contracts/know-your-rights/artificial-intelligence
  - https://www.sagaftra.org/contracts-industry-resources/contracts/2023-tvtheatrical-contracts/artificial-intelligence-resources
---

## Claim 1: "US-based nonprofit platform founded in 2013 by Jess Kutch and Michelle Miller"

Source: https://en.wikipedia.org/wiki/Coworker_(company) + https://www.influencewatch.org/non-profit/coworker-org/ + https://lwp.georgetown.edu/practitionerfellows/michelle-miller-and-coworker-org-selected-for-echoing-green-fellowship/
Source tier: database
Source content: "Coworker.org was created in 2013 by cofounders Michelle Miller and Jess Kutch, and both had previously worked at Service Employees International Union (SEIU)."
Comparison: Founding year, founders, and US nonprofit status match across Wikipedia, InfluenceWatch, and Georgetown Kalmanovitz (via search snippets). Named-entity definitional facts.
Decision: corroborated

## Claim 2: scalar:sources[0].note — mission statement "laboratory for workers to experiment with power-building strategies and win meaningful changes in the 21st century economy"

Source: https://home.coworker.org/about-us/
Source tier: primary
Source content: "Coworker.org is a laboratory for workers to experiment with power-building strategies and win meaningful changes in the 21st century economy."
Comparison: Verbatim match on the about page; the Little Tech report PDF interior carries the same sentence ("21st-century economy"). Note also correctly attributes gig project, nonprofit status, and NVF sponsorship to this page.
Decision: primary-sourced

## Claim 3: "the organization launched under fiscal sponsorship of the New Venture Fund" (+ scalar:sources[0].note NVF sponsorship)

Source: https://home.coworker.org/about-us/ + https://www.fordfoundation.org/work/our-grants/awarded-grants/grants-database/new-venture-fund-134071/
Source tier: primary
Source content: "Coworker.org is a nonprofit organization fiscally sponsored by the New Venture Fund, with contributions being tax-deductible." Ford's grant to Coworker.org is routed through New Venture Fund.
Comparison: Sponsorship confirmed by own site and independently by Ford's grant record naming NVF as grantee for Coworker.org core support. The "launched under" (at-founding) timing is not explicit on either source but is uncontradicted.
Decision: corroborated

## Claim 4: "Jess Kutch came to Coworker.org from Change.org, where she served as organizing director... five years directing online campaigns" at SEIU (+ scalar:sources[8].note)

Source: https://fellows.echoinggreen.org/fellow/jessica-kutch/
Source tier: database
Source content: "organizing director at Change.org, where she led a team of organizers in providing strategic support to campaigns"; spent five years "directing online campaigns for the Service Employees International Union" and pioneered "digital strategies for worksite organizing."
Comparison: Both prior roles match the cited Echoing Green fellow profile; single directory-bio source for the career specifics.
Decision: single-source

## Claim 5: "Michelle Miller brought experience from SEIU's creative media work on service-worker campaigns"

Source: https://just-tech.ssrc.org/our-network/michelle-miller/ + https://sici.hks.harvard.edu/person/michelle-miller/
Source tier: database
Source content: "Before co-founding Coworker.org, Michelle spent a decade at the Service Employees International Union (SEIU) where she used creative media and the arts to advance union campaigns." (search snippets of bio pages; ashoka.org 403 on direct fetch)
Comparison: SEIU creative-media background matches across two institutional bio pages; "service-worker campaigns" is a fair gloss of SEIU union campaigns.
Decision: corroborated

## Claim 6: "built Coworker on a theory that digital tools could serve as a 'front doorstep' to the labor movement — enabling workers to dip into collective action"

Source: https://culturalworkersorganize.org/platform-organizing-digital-tools-for-worker-communication/
Source tier: database
Source content: "Coworker.org has positioned itself as a 'front doorstep' to the labour movement, helping workers 'dip their toe into collective action'" (search snippet)
Comparison: The quoted framing is attested in one academic project's write-up of Coworker's positioning; not found on Coworker's own pages this session.
Decision: single-source

## Claim 7: "The Service Employees International Union provided $200,000 in seed funding in 2013"

Source: https://www.influencewatch.org/non-profit/coworker-org/
Source tier: database
Source content: "In 2013, the SEIU labor union reported providing Coworker with $200,000." (search snippet)
Comparison: Amount and year match; one source (which itself cites SEIU's reporting), no second canonical source found this session.
Decision: single-source

## Claim 8: "In 2014, both co-founders received Echoing Green Fellowships" (+ scalar:sources[8].note "confirms 2014 Echoing Green fellowship year for co-founders Miller and Kutch")

Source: https://fellows.echoinggreen.org/fellow/jessica-kutch/ + https://lwp.georgetown.edu/practitionerfellows/michelle-miller-and-coworker-org-selected-for-echoing-green-fellowship/
Source tier: primary
Source content: Kutch profile: "2014 Global Fellow", co-founded with Michelle Miller. Georgetown: "Michelle and her co-founder Jess Kutch were selected by Echoing Green as 2014 Global Fellows to continue growing Coworker.org."
Comparison: Echoing Green's own fellows directory is primary for its fellowship years; Georgetown independently names both as 2014 Global Fellows.
Decision: corroborated

## Claim 9: "launched the Coworker Solidarity Fund — a sister 501(c)(4) mutual aid organization providing direct financial support to workers facing retaliation for organizing, with particular focus on tech-sector workers"

Source: https://coworkerfund.org/about/ + https://www.fastcompany.com/90737935/tech-employees-organizing-their-workplaces-drew-on-this-mutual-aid-tool
Source tier: primary
Source content: "Coworker Solidarity Fund (CSF) was formed and incorporated as a nonprofit, nonpartisan 501(c)(4)"; "the first-ever crowdfunded mutual aid 501(c)(4) non-profit designed specifically to help employees and independent contractors who face retaliation for workplace organizing"; pilot fund "designed to support workers in the tech industry and its supply chain."
Comparison: 501(c)(4) status, mutual aid model, retaliation support, and tech-sector focus all match; "sister" framing used by CSF/coverage. CSF's about page stresses the two orgs are legally autonomous, consistent with "sister organization."
Decision: corroborated

## Claim 10: "Both co-founders stepped down as co-executive directors at the end of March 2023, announcing a strategic evolution from petition platform toward 'a whole suite of options'" (+ scalar:sources[9].note)

Source: https://home.coworker.org/meeting-the-moment/
Source tier: primary
Source content: Jess Kutch and Michelle Miller, "Co-Founders and Executive Directors," stepped down "at the end of March" 2023 (post dated March 14, 2023); org shifted from petition platform to "a whole suite of options that support workers along their organizing journey," with mutual aid learned from "their sister organization, the Coworker Solidarity Fund."
Comparison: Date, roles, quote, and mutual-aid/leadership-evolution framing all match the announcement.
Decision: primary-sourced

## Claim 11: "Nur, who joined Coworker in 2019 as a Campaign Strategist after a decade of grassroots organizing with SEIU's Fight For $15 and the National Domestic Workers Alliance, was named Executive Director effective May 1, 2024" (+ scalar:sources[7].note incl. Director of Content & Campaign Strategy, Durham For All)

Source: https://home.coworker.org/welcoming-coworkers-new-executive-director/
Source tier: primary
Source content: "Nur joined Team Coworker five years ago as a campaign strategist through the Kairos Fellowship"; "soon promoted to Senior Campaign Strategist then as the Director of Content & Campaign Strategy"; "Nur came to Coworker with almost a decade of grassroots organizing, leadership development and campaign experience," as "North Carolina Lead Organizer for the National Domestic Workers Alliance - We Dream in Black," "board member and organizer for North Carolina's Durham For All," and "union organizer with SEIU's Fight For $15 campaign in the southeast"; effective May 1, 2024.
Comparison: All specifics match the announcement page, including the promotion path in sources[7].note. Minor drift: body's "after a decade" vs source's "almost a decade" — rounding, not asserted as error.
Decision: primary-sourced

## Claim 12: "began when an Atlanta barista's 2014 petition...; Starbucks reversed the policy in October 2014" (+ scalar:sources[4].note "October 2014")

Source: https://money.cnn.com/2014/09/10/news/companies/starbucks-tattoos/index.html + https://home.coworker.org/resources/grounds-for-change-how-baristas-won-visible-tattoos-at-starbucks/
Source tier: mainstream
Source content: "Atlanta Starbucks worker Kristie Williams posted the petition"; Starbucks changed its dress code "to allow employees to show non-offensive visible tattoos... effective on Monday, October 20, 2014" (CNN/NBC snippets); Coworker's own account confirms Williams and the October 20, 2014 change.
Comparison: Atlanta origin, 2014 petition, and October 2014 reversal all corroborated. Note for the Editor: the victories page itself carries no dates (sources[4].note attributes the "October 2014" date to that page; the date is attested elsewhere, so no body error).
Decision: corroborated

## Claim 13: "drew support from workers across 17 countries"

Source: no canonical source found
Source tier: none
Source content: Coverage says "thousands of people from all over the world took action together" (Coworker's Grounds for Change account); signature counts reported at ~21,000–25,000; no source enumerates supporter countries.
Comparison: The specific "17 countries" figure appears in no fetched source or search snippet, including Coworker's own retrospective of the campaign. Not contradicted, but unattested.
Decision: uncorroborated

## Claim 14: "Subsequent Starbucks campaigns... expanded paid parental leave for barista dads and adoptive parents, scheduling technology updates to prevent 'clopening' shifts, and safe needle disposal in bathrooms"

Source: https://home.coworker.org/victories/
Source tier: primary
Source content: "expands paid parental leave to barista dads and adoptive parents"; "updates its scheduling technology to prevent 'clo-penings'"; "placed safe needle disposal receptacles in bathrooms after baristas spoke out"
Comparison: All three wins match the victories page near-verbatim.
Decision: primary-sourced

## Claim 15: "Wells Fargo employees used Coworker campaigns to successfully pressure the company to eliminate predatory internal sales goals"

Source: https://home.coworker.org/victories/
Source tier: primary
Source content: "eliminate product sales goals after employees reported that they faced unreasonable pressure to meet the bank's excessive sales targets"
Comparison: Matches; the causal credit to Coworker campaigns is the org's own victory framing.
Decision: primary-sourced

## Claim 16: "thousands of Uber drivers organized through Coworker and won the addition of an in-app tipping feature"

Source: https://home.coworker.org/victories/
Source tier: primary
Source content: "thousands of Uber drivers join together"; Uber "adds an in-app tipping feature"
Comparison: Matches the victories page; causal credit is the org's own framing.
Decision: primary-sourced

## Claim 17: "Workers at Chicago-area Amazon warehouses secured paid time off during extreme heat conditions — the first time Amazon workers won this protection"

Source: https://home.coworker.org/victories/
Source tier: primary
Source content: "Workers at an Amazon warehouse in Chicago win time off with pay - for the first time - during extreme heat"
Comparison: Matches verbatim including the firstness qualifier; the "first time" characterization is Coworker's own.
Decision: primary-sourced

## Claim 18: "In September 2018, Gig Workers Rising used the Coworker platform to launch 'Uber and Lyft: Give Drivers a Voice', gathering over 5,000 signatures" + the four demands (+ scalar:sources[5].note incl. Lyft HQ delivery November 14, 2018)

Source: https://www.coworker.org/petitions/uber-and-lyft-give-drivers-a-voice
Source tier: primary
Source content: Launched by Gig Workers Rising, first signatures September 19, 2018; "5,000 signatures reached by November 10, 2018"; demands include "clear communication with the driver before and after deactivation," a "transparent appeals process that includes an appeals panel led by drivers," addressing passenger discrimination affecting ratings, and restricting immediate deactivations to "extreme and clearly defined circumstances"; petition delivered to Lyft headquarters November 14, 2018.
Comparison: Launch month, signature count, demand roster, and the note's Lyft delivery date all match the petition page and its updates.
Decision: primary-sourced

## Claim 19: "delivering the petition in person to both companies' headquarters"

Source: https://www.coworker.org/petitions/uber-and-lyft-give-drivers-a-voice
Source tier: primary
Source content: Petition updates record delivery to Lyft HQ on November 14, 2018, and an "attempted delivery to Uber HQ on October 12, 2018 (incident occurred with security staff)."
Comparison: Delivery is confirmed for Lyft only; at Uber HQ the updates describe an attempted delivery disrupted by security. "Delivered to both companies' headquarters" is partially confirmed — drivers went to both HQs, but completed delivery at Uber is not attested.
Decision: uncorroborated

## Claim 20: "Bossware and Employment Tech Database, launched on November 17, 2021, cataloging over 550 labor-focused technology products... AI, location tracking, and biometric tools" (+ scalar:sources[2].note)

Source: https://home.coworker.org/worktech/
Source tier: primary
Source content: Launch date November 17, 2021; "more than 550 labor-focused technology products"; "products that use technology like AI, location tracking, and biometrics to manage employees and collect their data"
Comparison: Launch date, product count, and technology categories all match the database page.
Decision: primary-sourced

## Claim 21: report "authored by Wilneida Negrón, PhD — Coworker's Director of Policy and Research"

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf + https://restofworld.org/2025/employee-surveillance-software-vc-funding/
Source tier: primary
Source content: PDF cover: "LITTLE Tech Is Coming for Workers — A Framework for Reclaiming and Building Worker Power. By Wilneida Negrón, PhD". Rest of World: "Wilneida Negrón, director of research and policy at Coworker.org."
Comparison: Authorship verbatim on the report cover; director title corroborated independently (word order varies between "Policy and Research" and "research and policy").
Decision: corroborated

## Claim 22: "identified that over 30 percent of the database's products emerged between 2020 and 2021 alone, reflecting a surge of private capital" (+ scalar:sources[3].note "over 30% emerged between 2020–2021")

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
Source tier: primary
Source content: "Thirty-one percent of the products listed emerged between 2020 and 2021; the rest were developed between 2018 and 2020." Report includes an "Economic Drivers" section on pandemic-era investment.
Comparison: 31% supports "over 30 percent"; the private-capital surge framing matches the report's economic-drivers analysis.
Decision: primary-sourced

## Claim 23: "Specific systems documented included Amazon's automated termination algorithm that generates warnings and terminations based on productivity tracking without human review" (+ scalar:sources[3].note "documented Amazon automated termination")

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
Source tier: primary
Source content: Full-text probes of the report find no automated-termination content ("automated terminat*", "without human", "Time Off Task", "terminat*" near Amazon: zero matches). The report's Amazon-specific system is the Mentor app: "Amazon uses an app called Mentor to track and discipline delivery drivers" and "the use of the Mentor app by Amazon drivers, which has been found to track their location even after they clock out from work."
Comparison: The body and sources[3].note attribute to the Little Tech report a documented Amazon automated-termination algorithm that the report does not contain; that description matches 2019 press reporting on Amazon warehouse productivity systems, not this report. Fix location: body § Workplace technology research sentence + sources[3].note — replace the Amazon automated-termination example with the report's actual Amazon example (Mentor app tracking/disciplining delivery drivers) or re-cite. Replacement requires a sentence-level rewrite — Editor may `[editor-flag]` to Researcher.
Decision: correction

## Claim 24: "emotion detection tools used in hiring assessments"

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
Source tier: primary
Source content: Hiring/recruitment products (HiredScore, HireVue, Human, Pymetrics): "Some of these products claim to track emotions such as anger, contempt, disgust, engagement, joy, sadness, surprise and valence... by analyzing a video clip."
Comparison: Emotion detection in hiring assessments is documented in the report as claimed.
Decision: primary-sourced

## Claim 25: "The report coined the 'Little Tech' framing... harmful labor-management technologies were coming not from the largest consumer tech companies but from a swarm of smaller vendors"

Source: https://home.coworker.org/wp-content/uploads/2021/11/Little-Tech-Is-Coming-for-Workers.pdf
Source tier: primary
Source content: "an ecosystem of tech products, companies, and investors we dub Little Tech; the unregulated marketplace of tech products that are collecting and aggregating data about workers"; "While we still need to address the challenges posed by Big Tech companies (notably Facebook, Amazon, Google, Microsoft, and Apple), we increasingly also need to future-proof our strategies and interventions with emerging companies"; "Little Tech isnt little."
Comparison: The coinage and beyond-Big-Tech framing match; body's "most harmful... not from the largest" slightly sharpens the report's "we increasingly also need to" phrasing but stays within its argument.
Decision: primary-sourced

## Claim 26: scalar:sources[1].note — Ford Foundation grant via New Venture Fund: "$2,870,417 total ($2,720,417 approved September 2020; $150,000 increase August 2022; end date July 2024)" + funders: fund-ford-foundation

Source: https://www.fordfoundation.org/work/our-grants/awarded-grants/grants-database/new-venture-fund-134071/
Source tier: primary
Source content: "The grant approval was $2,720,417 in September 2020, with a grant increase of $150,000 in August 2022, bringing the total amount to $2,870,417. The grant ran from August 2020 to July 2024" — "core support for Coworker.org to facilitate worker engagement on workplace advocacy issues." (Ford grant record 134071 via search snippet; grants-database CAPTCHA-walled on direct fetch.)
Comparison: All figures, dates, and purpose language match Ford's own grant record.
Decision: primary-sourced

## Claim 27: "the more litigation-focused approach of organizations like the Worker Info Exchange, which uses GDPR access rights to extract algorithmic data from Uber and challenge its management systems in UK courts"

Source: https://www.workerinfoexchange.org/post/historic-digital-rights-win-for-wie-and-the-adcu-over-uber-and-ola-at-amsterdam-court-of-appeal + https://techcrunch.com/2023/04/05/uber-ola-gdpr-worker-data-access-rights-appeal/
Source tier: primary
Source content: WIE brought GDPR data-access and automated-decision-making cases against Uber and Ola "in support of members of the App Drivers & Couriers Union in Great Britain" at the Amsterdam District Court (2020 rulings) and won on appeal at the Amsterdam Court of Appeal (April 2023), including the robo-firing case.
Comparison: The GDPR-access and algorithmic-challenge characterization is right, but the litigation venue was the Dutch courts (Amsterdam District Court, then Amsterdam Court of Appeal — Uber BV's seat), not UK courts. Single-token fix: "UK courts" → "Dutch courts". Fix location: body § Place in the movement.
Decision: correction

## Claim 28: "the AI provisions in WGA and SAG-AFTRA contracts"

Source: https://www.wga.org/contracts/know-your-rights/artificial-intelligence + https://www.sagaftra.org/contracts-industry-resources/contracts/2023-tvtheatrical-contracts/artificial-intelligence-resources
Source tier: primary
Source content: "The WGA secured groundbreaking AI protections in the 2023 MBA"; SAG-AFTRA's 2023 TV/Theatrical contracts include AI provisions on digital replicas, consent, and compensation.
Comparison: Both unions' 2023 contracts contain AI provisions, as the edge claim assumes.
Decision: corroborated

## Claim 29: "The Bossware database has been cited in academic and policy research on algorithmic labor management"

Source: https://blogs.law.ox.ac.uk/business-law-blog/blog/2022/01/worker-data-subject-resources-data-protection-day + https://laborcenter.berkeley.edu/how-common-is-employers-use-of-workplace-management-technologies-a-review-of-prevalence-studies/
Source tier: database
Source content: Oxford Business Law Blog lists the report/database among worker-data-protection resources ("provides an up-to-date and thorough review of the algorithmic management industry and its (lack of) regulation"); UC Berkeley Labor Center's prevalence review and an algorithmic-management research-agenda paper cite it.
Comparison: Multiple independent academic/policy citations found.
Decision: corroborated

## Claim 30: "the first digital organizing infrastructure built from the ground up for the unorganized workforce"

Source: no canonical source found
Source tier: none
Source content: Coverage describes Coworker as "a digital platform that provides the tools to any worker, anywhere" and a pioneer in digital labor organizing, but no fetched source makes a firstness claim of this shape.
Comparison: Contested-firstness characterization; unattested in canonical sources this session.
Decision: uncorroborated

## Claim 31: "Coworker.org's Gig Economy project" exists with future-of-work focus (+ scalar:sources[0].note "gig economy project focus")

Source: https://home.coworker.org/about-us/
Source tier: primary
Source content: The Gig Economy project is "a place for continued innovation to ensure that the future of work is fair for workers."
Comparison: The project and its gig-work-fairness remit are confirmed on the about page; the body's elaboration of the algorithmic-opacity frontier is the entity's interpretive framing over the project's documented focus.
Decision: primary-sourced
