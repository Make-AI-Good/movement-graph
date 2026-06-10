---
entity_id: msg-fairwork
entity_hash: f4cd16df1dfa96bf96284701d2f17a61d670176b
audit_date: 2026-06-05
pass: 1
status: corrections-pending
claims_total: 23
claims_corroborated: 18
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 2
claims_uncorroborated: 3
sources_consulted:
  - https://www.oii.ox.ac.uk/blog/introducing-a-fairwork-foundation/
  - https://www.oii.ox.ac.uk/research/projects/a-fairwork-foundation-towards-fair-work-in-the-platform-economy/
  - https://fair.work/en/fw/about/
  - https://fair.work/en/fw/principles/
  - https://fair.work/en/fw/methodology/
  - https://fair.work/en/fw/about/people/mark-graham/
  - https://api.crossref.org/works/10.1177/0308518X251336893
  - https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024L2831
  - https://www.oii.ox.ac.uk/research/projects/fairwork-for-ai/
  - https://www.oii.ox.ac.uk/news-events/new-oxford-report-shows-freelance-and-microwork-platforms-fail-to-provide-minimum-fairness-standards-for-their-global-workforce/
  - https://fair.work/en/fw/blog/new-fairwork-cloudwork-ratings-expose-the-precarious-working-conditions-of-online-work-platforms/
  - https://www.itnewsafrica.com/2019/03/rating-working-conditions-in-the-digital-economy-with-fairwork/
  - http://www.markgraham.space/fairwork
  - https://fair-work.shorthandstories.com/credits-and-funding/
  - https://fair.work/en/ratings/india/
---

## Claim 1: "The framing's [academic seed is the 24 March 2017 *Introducing a FairWork Foundation* post](https://www.oii.ox.ac.uk/blog/introducing-a-fairwork-foundation/) by Professor Mark Graham of the Oxford Internet Institute"

Source: https://www.oii.ox.ac.uk/blog/introducing-a-fairwork-foundation/
Source content: Publication date: 24 March 2017; author: Mark Graham.
Comparison: Date, title, and author match.
Decision: corroborated

## Claim 2: "The Fairwork project [formally launched in January 2018](https://www.oii.ox.ac.uk/research/projects/a-fairwork-foundation-towards-fair-work-in-the-platform-economy/) with Mark Graham as Principal Investigator"

Source: https://www.oii.ox.ac.uk/research/projects/a-fairwork-foundation-towards-fair-work-in-the-platform-economy/
Source content: "Project formal launch date: January 2018. Principal Investigator: Professor Mark Graham, Professor of Internet Geography."
Comparison: Launch date and PI match.
Decision: corroborated

## Claim 3: "the project lead (Professor Mark Graham, Professor of Internet Geography)" / "Director of the Fairwork project" / scalar:sources[5].note + sources[6].note

Source: https://fair.work/en/fw/about/people/mark-graham/
Source content: "He is a 'Professor of Internet Geography at the Oxford Internet Institute' [and] 'Director of the Fairwork project.'"
Comparison: Title and Fairwork role match.
Decision: corroborated

## Claim 4: "coordinated by the [Oxford Internet Institute] and the WZB Berlin Social Science Center"

Source: https://fair.work/en/fw/about/
Source content: "The Fairwork project is coordinated by the Oxford Internet Institute and the WZB Berlin Social Science Center."
Comparison: Both coordinating institutions match.
Decision: corroborated

## Claim 5: "[38 countries on five continents](https://fair.work/en/fw/about/)"

Source: https://fair.work/en/fw/about/
Source content: "Our global network of researchers and experts extends across 38 countries and 5 continents."
Comparison: Country and continent counts match.
Decision: corroborated

## Claim 6: "[rated more than 700 digital labour platforms](http://www.markgraham.space/fairwork)"

Source: http://www.markgraham.space/fairwork
Source content: "712 digital labour platforms have been studied and rated by Fairwork."
Comparison: 712 satisfies "more than 700".
Decision: corroborated

## Claim 7: Five principles named — "fair pay, fair conditions, fair contracts, fair management, and fair representation"; "maximum of two points... for a maximum scorecard score of ten"

Source: https://fair.work/en/fw/principles/
Source content: "1. Fair Pay; 2. Fair Conditions; 3. Fair Contracts; 4. Fair Management; 5. Fair Representation. Each of the five principles can earn a maximum of 2 points... Total maximum score: 10 points."
Comparison: Principle names and scoring match.
Decision: corroborated

## Claim 8: "three-method audit" — desk research, worker surveys/interviews, manager interviews; "six to ten interviews per gig-work platform and at least ten workers per continent for cloudwork platforms"

Source: https://fair.work/en/fw/methodology/
Source content: "Desk Research... Worker Surveys and Interviews... Manager Interviews... Gig Work Platforms: 'We interview 6-10 workers at each platform'... Cloudwork Platforms: 'We aim to survey at least 10 workers in each continent that a platform operates in.'"
Comparison: Three methods and interview targets match.
Decision: corroborated

## Claim 9: scalar:sources[11].note — "Mark Graham, Oğuz Alyanak, Alessio Bertolini, Patrick Feuerstein, Tobias Kuttler, Funda Ustek Spilda, and Jonas Valente, 'Pressure and praise as an action research methodology: The case of Fairwork', *Environment and Planning A: Economy and Space*"

Source: https://api.crossref.org/works/10.1177/0308518X251336893
Source content: "Title: 'Pressure and praise as an action research methodology: The case of Fairwork'. Authors (in order): 1. Mark Graham; 2. Oğuz Alyanak; 3. Alessio Bertolini; 4. Patrick Feuerstein; 5. Tobias Kuttler; 6. Funda Ustek Spilda; 7. Jonas Valente. Journal: Environment and Planning A: Economy and Space."
Comparison: Title, author list, and journal name all match.
Decision: corroborated

## Claim 10: scalar:sources[11].note — "published online 23 April 2025"

Source: https://api.crossref.org/works/10.1177/0308518X251336893
Source content: "publication_date media_type='online': 2025-04-28; crm-item name='created' type='date': 2025-04-28T08:52:03Z."
Comparison: Crossref's canonical DOI metadata records online publication as 28 April 2025, not 23 April 2025 as the source note claims. Editor fix location: frontmatter `sources[].url == https://journals.sagepub.com/doi/10.1177/0308518X251336893` `note` scalar — update "23 April 2025" to "28 April 2025" or drop the day-precise date.
Decision: correction

## Claim 11: scalar:origin (frontmatter) — "what its [2025 *Geography and Environment* paper](https://journals.sagepub.com/doi/10.1177/0308518X251336893) calls the *pressure-and-praise* dynamic"

Source: https://api.crossref.org/works/10.1177/0308518X251336893
Source content: "Journal: Environment and Planning A: Economy and Space."
Comparison: The origin scalar names the journal of DOI 10.1177/0308518X251336893 as "*Geography and Environment*", italicised as a journal title. Crossref records the journal as "Environment and Planning A: Economy and Space" — and the entity body itself, in § "The pressure-and-praise methodology", correctly cites "[2025 *Environment and Planning A* paper]" against the same DOI. Editor fix location: frontmatter `origin` scalar — replace "*Geography and Environment*" with "*Environment and Planning A*" to align with the body and the canonical journal name.
Decision: correction

## Claim 12: "[more than 300 pro-worker policy changes](http://www.markgraham.space/fairwork)"

Source: http://www.markgraham.space/fairwork
Source content: "'over 300 pro-worker changes to company policies' have been implemented by platforms in response to Fairwork's engagement."
Comparison: "More than 300" matches "over 300".
Decision: corroborated

## Claim 13: "[Directive (EU) 2024/2831 of 23 October 2024](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024L2831)" on platform work

Source: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024L2831
Source content: "Official Citation: Directive (EU) 2024/2831. Date: 23 October 2024 (published 11 November 2024). Subject: Improving working conditions in platform work."
Comparison: Number, date, and subject match.
Decision: corroborated

## Claim 14: "[*Fairwork for AI* workstream]..., running from July 2021 to March 2024 with INRIA funding"

Source: https://www.oii.ox.ac.uk/research/projects/fairwork-for-ai/
Source content: "Project Dates: July 2021 - March 2024. Funder: INRIA."
Comparison: Dates and funder match.
Decision: corroborated

## Claim 15: "Funda Ustek-Spilda as a key researcher" (Fairwork for AI)

Source: https://www.oii.ox.ac.uk/research/projects/fairwork-for-ai/
Source content: "Dr Funda Ustek-Spilda (Former Research Associate) - described as 'a postdoctoral researcher and project manager on the Fairwork project at the Oxford Internet Institute.'"
Comparison: Source confirms Ustek-Spilda's involvement as a postdoctoral researcher / project manager on the Fairwork for AI project. "Key researcher" is within paraphrase tolerance.
Decision: corroborated

## Claim 16: "first cloudwork ratings drew on [surveys with 792 workers across 75 countries between July and November 2020 on 17 platforms]"

Source: https://www.oii.ox.ac.uk/news-events/new-oxford-report-shows-freelance-and-microwork-platforms-fail-to-provide-minimum-fairness-standards-for-their-global-workforce/
Source content: "Survey Scale: 792 workers across 75 countries evaluating 17 cloudwork platforms. Survey Dates: July - November 2020."
Comparison: Worker count, country count, platform count, and date range all match.
Decision: corroborated

## Claim 17: "Amazon Mechanical Turk, Rev, PeoplePerHour, and Freelancer scored at the bottom of the league table with zero to one points, while Jovoto and TranscribeMe led with seven out of ten"

Source: https://www.oii.ox.ac.uk/news-events/new-oxford-report-shows-freelance-and-microwork-platforms-fail-to-provide-minimum-fairness-standards-for-their-global-workforce/
Source content: "Amazon Mechanical Turk, Rev, PeoplePerHour, and Freelancer.com received scores of 0-1 points... Jovoto and TranscribeMe jointly topped the rankings with 7/10 scores."
Comparison: Bottom-tier and top-tier platforms and scores match.
Decision: corroborated

## Claim 18: "[second cloudwork wave in August 2022]... expanded the platform set to include Prolific, Workana, Appen, 5 Euros, Clickworker, Scale/Remotasks, 99designs, Fiverr, Soy Freelancer, Upwork, Microworkers, and PeoplePerHour, with four of the fifteen rated platforms failing to meet any threshold"

Source: https://fair.work/en/fw/blog/new-fairwork-cloudwork-ratings-expose-the-precarious-working-conditions-of-online-work-platforms/
Source content: "Publication Date: August 24, 2022. 15 Platforms Rated: Prolific, Jovoto, Workana, Appen, 5 euros, Clickworker, Scale/Remotasks, 99designs, Fiverr, Soy Freelancer, Upwork, Amazon Mechanical Turk, Freelancer, Microworkers, and PeoplePerHour. Platforms Meeting No Thresholds: Four platforms could not demonstrate compliance with any of Fairwork's ten thresholds."
Comparison: Date (August 2022 ≈ August 24, 2022), platform list (15 total, set matches), and "four of the fifteen failed to meet any threshold" all match.
Decision: corroborated

## Claim 19: "[Fairwork India Ratings 2024] — the project's sixth consecutive annual India scorecard, covering Amazon Flex, bigbasket, BluSmart, Flipkart, Ola, Porter, Swiggy, Uber, Urban Company, Zepto, and Zomato"; "no Indian platform scored above six out of ten in 2024"

Source: https://fair.work/en/ratings/india/
Source content: "Platforms Rated in 2024: Amazon Flex (2/10), BigBasket (6/10), BluSmart (5/10), Flipkart (1/10), Ola (no rating), Porter (no rating), Swiggy (6/10), Uber (no rating), Urban Company (6/10), Zepto (4/10), Zomato (6/10). Highest score: 6/10 shared by four platforms. Sixth Consecutive India Ratings: Yes — 2024, 2023, 2022, 2021, 2020, 2019."
Comparison: Platform list, "sixth consecutive" attribute, and "no platform above 6/10" all match. Note: Ola, Porter, Uber appear in the 2024 ratings page but did not return scores; the entity's framing "covering" remains accurate for inclusion.
Decision: corroborated

## Claim 20: "[funder coalition](https://fair-work.shorthandstories.com/credits-and-funding/)" — ERC, ESRC GCRF, BMZ via GIZ, Ford Foundation, John Fell Fund, Minderoo-Oxford Challenge Fund in AI Governance, GPAI, IDRC FoWIGS

Source: https://fair-work.shorthandstories.com/credits-and-funding/
Source content: "1. European Research Council (ERC); 2. Economic and Social Research Council (ESRC) through the Global Challenges Research Fund (GCRF, grant number ES/S00081X/1); 3. Deutsche Gesellschaft für Internationale Zusammenarbeit (GIZ), commissioned by the Federal Ministry for Economic Cooperation and Development (BMZ); 4. Ford Foundation; 5. The John Fell Fund; 6. The Minderoo-Oxford Challenge Fund in AI Governance; 7. Global Partnership on Artificial Intelligence (GPAI); 8. International Development Research Centre's Future of Work in the Global South initiative (FoWIGS)."
Comparison: Full funder list matches.
Decision: corroborated

## Claim 21: "Jamie Woodcock as a founding researcher" (origin frontmatter scalar)

Source: no canonical source found
Source content: The OII project page (https://www.oii.ox.ac.uk/research/projects/a-fairwork-foundation-towards-fair-work-in-the-platform-economy/) names only Mark Graham as Principal Investigator in the content I could fetch; Jamie Woodcock is not named there. Both https://en.wikipedia.org/wiki/Jamie_Woodcock and https://en.wikipedia.org/wiki/Jamie_Woodcock_(sociologist) returned HTTP 404 in this session — no Wikipedia page was reachable to confirm or refute his Fairwork founding role.
Comparison: The claim is widely held in secondary discussion of Fairwork's origins, but I could not surface a canonical primary source for it in this pass. Editor would not change the claim on the strength of this audit alone; flag for Researcher only if a future pass continues to find no canonical source.
Decision: uncorroborated

## Claim 22: "the freelancer platform NoSweat led the rankings with eight out of ten points" (South Africa 2019 pilot, body § Origin)

Source: https://www.itnewsafrica.com/2019/03/rating-working-conditions-in-the-digital-economy-with-fairwork/
Source content: "The text notes that NoSweat introduced 'significant changes in all five areas of fairness' but does not provide a numerical rating." Specifically: "No specific score of 8/10 is mentioned in the article."
Comparison: The entity's primary cited source for this paragraph does not contain the 8/10 figure. The figure is plausible (NoSweat is mentioned as a top performer in the SA pilot), but the numerical claim is not supported by the source as fetched.
Decision: uncorroborated

## Claim 23: "The five principles... were refined through multi-stakeholder workshops held in Cape Town, Johannesburg, and Bangalore in 2018" (body § Origin)

Source: no canonical source found
Source content: None of the entity's cited Fairwork or OII pages I fetched in this pass enumerated these three workshop locations or the 2018 date.
Comparison: The claim is specific (three cities, year) but no source I could fetch in this pass carried it. Not contradicted; not confirmed.
Decision: uncorroborated
