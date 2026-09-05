---
entity_id: msg-data-is-a-civil-rights-issue
entity_hash: 73aa56e8cc2d65e6f593ec9b4fbab19a342e877e
audit_date: 2026-09-05
pass: 1
status: corrections-pending
claims_total: 33
claims_corroborated: 7
claims_primary_sourced: 8
claims_single_source: 8
claims_uncorroborated: 3
open_corrections: 7
sources_consulted:
  - https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
  - https://civilrights.org/2014/02/27/civil-rights-principles-era-big-data/
  - https://civilrights.org/2014/09/12/new-report-highlights-where-big-data-and-civil-rights-intersect/
  - https://d4bl.org/
  - https://d4bl.org/about
  - https://d4bl.org/conferences
  - https://d4bl.org/videos/19-abolish-big-data
  - https://d4bl.org/videos/21-opening-remarks-and-keynote-address
  - https://d4bl.org/videos/30-abolish-big-data-uci-bren-ics
  - https://d4bl.org/people/9-yeshimabeit-milner
  - https://d4bl.org/campaigns/47-abolish-big-data
  - https://d4bl.org/dispatch/72-introducing-no-more-data-weapons
  - https://civic.mit.edu/2017/11/18/data-for-black-lives-opening-panel-live-blog/
  - https://whatsworkingsolutions.org/resource/interview-with-yeshi-milner-data-for-black-lives/
  - https://en.wikipedia.org/wiki/Data_for_Black_Lives
  - https://en.wikipedia.org/wiki/Yeshimabeit_Milner
  - https://en.wikipedia.org/wiki/Home_Owners%27_Loan_Corporation
  - https://en.wikipedia.org/wiki/Race_After_Technology
  - https://www.usccr.gov/reports/2023/civil-rights-implications-algorithms
  - https://www.macfound.org/grantee/data-for-black-lives-10115070/
  - https://fellows.echoinggreen.org/fellow/yeshimabeit-milner/
  - https://datainfra.wordsinspace.net/spring2020/2020/02/19/databite-no-129-abolish-big-data-with-yeshimabeit-milner-march-4/
  - https://www.ajl.org/about
---

Type-shape: message (connective). Claim surface = edges + hard specifics (dates, counts, names, quotes, outcomes) per `AUDITOR.md § Type-shape`. Interpretive prose about significance/register received no decision.

## Claim 1: edge `propagated_by_orgs: org-algorithmic-justice-league`

Source: https://www.ajl.org/about
Source tier: primary
Source content: "losing the gains made with the civil rights movement and other movements for equality under the false assumption of machine neutrality"; mission "to raise public awareness about the impacts of AI, equip advocates with resources to bolster campaigns"
Comparison: Edge resolves to entities/organizations/org-algorithmic-justice-league.md; AJL's own site frames algorithmic harms in explicit civil-rights terms, supporting the propagation edge.
Decision: primary-sourced

## Claim 2: edges `related_messages` (msg-no-more-data-weapons, msg-coded-gaze, msg-ethics-washing, msg-data-colonialism) + body links (person-ruha-benjamin, org-algorithmic-justice-league)

Source: corpus files (mechanical resolution)
Source tier: primary
Source content: all six targets exist at entities/messages/, entities/persons/, entities/organizations/ (checked by ls this pass)
Comparison: Every cross-reference resolves to an existing entity file; relatedness itself is interpretive and not a claim.
Decision: corroborated

## Claim 3: "Civil Rights Principles for the Era of Big Data," released 27 February 2014 by fourteen organisations including ACLU, NAACP, Color of Change, Center for Media Justice, Free Press, National Urban League, the Leadership Conference

Source: https://civilrights.org/2014/02/27/civil-rights-principles-era-big-data/
Source tier: primary
Source content: "February 27, 2014"; 14 signatories listed including "American Civil Liberties Union", "NAACP", "ColorOfChange", "Center for Media Justice", "Free Press", "National Urban League", "The Leadership Conference on Civil and Human Rights"
Comparison: Date, count, and every org the entity names appear in the coalition's own release.
Decision: primary-sourced

## Claim 4: the five principles — ending high-tech profiling, fairness in automated decisions, constitutional protections, individual control over data, protection from inaccurate data

Source: https://civilrights.org/2014/02/27/civil-rights-principles-era-big-data/
Source tier: primary
Source content: "Stop High-Tech Profiling"; "Ensure Fairness in Automated Decisions"; "Preserve Constitutional Principles"; "Enhance Individual Control of Personal Information"; "Protect People from Inaccurate Data"
Comparison: Body/origin paraphrase matches all five verbatim headings.
Decision: primary-sourced

## Claim 5: accompanying September 2014 report "Civil Rights, Big Data, and Our Algorithmic Future" by Robinson+Yu

Source: https://civilrights.org/2014/09/12/new-report-highlights-where-big-data-and-civil-rights-intersect/
Source tier: primary
Source content: "'Civil Rights and Big Data, and Our Algorithmic Future' by Robinson + Yu", released "September 12, 2014"
Comparison: Title, authorship, and September 2014 date confirmed by the Leadership Conference announcement; the report's own site (bigdata.fairness.io) also dates it "A September 2014 report".
Decision: corroborated

## Claim 6: the report "mapped the civil rights implications concretely across criminal justice, employment, credit, and healthcare" (origin; body: "criminal justice, employment, credit, and healthcare, the four domains")

Source: https://civilrights.org/2014/09/12/new-report-highlights-where-big-data-and-civil-rights-intersect/
Source tier: primary
Source content: "The report has four chapters that explore real-life examples of where big data intersects with civil rights related to financial inclusion, jobs, criminal justice and government data collection and use."
Comparison: The report's four chapters are financial inclusion (≈credit), jobs (≈employment), criminal justice, and government data collection and use — NOT healthcare. Replace "healthcare" with "government data collection and use" in both origin frontmatter and body.
Decision: correction

## Claim 7: D4BL founded/crystallised at its inaugural conference at the MIT Media Lab in November 2017

Source: https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
Source tier: mainstream
Source content: MIT News (Dec 13, 2017) covers the conference at MIT's Media Lab; d4bl.org home lists "D4BL I (November 16–18, 2017) at MIT Media Lab"; Wikipedia: "D4BL began in November 2017"
Comparison: Month, year, and venue confirmed by three independent sources. Note: D4BL's own pages conflict on exact days (conferences index says Nov 17–19; home/detail pages say Nov 16–18) — the entity's body wisely claims only "November 2017".
Decision: corroborated

## Claim 8: the inaugural conference drew 400 attendees

Source: https://whatsworkingsolutions.org/resource/interview-with-yeshi-milner-data-for-black-lives/
Source tier: mainstream
Source content: "I started the organization at a conference at the MIT Media Lab in 2017 where we convened 400 people."
Comparison: The 400 figure rests on Milner's own interview statement; the MIT News piece the body hyperlinks for this figure does not carry it (see Claim 32).
Decision: single-source

## Claim 9: over 300 more on the waiting list watching by Facebook livestream

Source: https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
Source tier: mainstream
Source content: "The registration filled up quickly, with more than 300 on the waiting list who were able to watch the conference sessions via Facebook livestream."
Comparison: Matches exactly; only MIT News carries this figure.
Decision: single-source

## Claim 10: co-founders Yeshimabeit Milner and Lucas Mason-Brown

Source: https://fellows.echoinggreen.org/fellow/yeshimabeit-milner/
Source tier: primary
Source content: Echoing Green: Milner "serves as co-founder and executive director"; Wikipedia: "founded by Yeshimabeit Milner and Lucas Mason-Brown"; d4bl.org names Milner "Founder & CEO" and its people page names Mason-Brown a co-founder
Comparison: Co-founder status of both confirmed. Note MIT News describes the conference as organized by Mason-Brown "with Yeshimabeit Milner of Miami and Max Clermont of Chicago" — a third organizer the entity omits; not an error in the co-founder claim itself.
Decision: corroborated

## Claim 11: mission stated as "make data a tool for social change instead of a weapon of political oppression"

Source: https://d4bl.org/
Source tier: primary
Source content: "Make data a tool for social change instead of a weapon of political oppression."
Comparison: Verbatim match on D4BL's own site.
Decision: primary-sourced

## Claim 12: Milner stated at the launch that "as our society and our injustices become increasingly automated, we believe this is one of the most important civil rights battles of our generation"

Source: https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
Source tier: mainstream
Source content: "As our society and our injustices becomes increasingly automated, we believe this is one of the most important civil rights battles of our generation."
Comparison: Matches MIT News's rendering except the entity regularises "becomes" to "become"; substance identical, single inflection difference, no fix routed.
Decision: single-source

## Claim 13: built "from a Twitter account to a 400-person inaugural conference in eight months" (body, twice)

Source: https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
Source tier: none
Source content: "The idea grew from a Twitter account to the conference just last summer."
Comparison: The Twitter-account origin is sourced, but no canonical source states "eight months"; MIT News's "last summer" (2017) to November 2017 implies roughly four months. No source offers a definite replacement figure, so this is a sourcing limit rather than a token fix.
Decision: uncorroborated

## Claim 14: "Abolish Big Data" first distributed as a pamphlet at the second D4BL conference in January 2019

Source: https://d4bl.org/campaigns/47-abolish-big-data
Source tier: primary
Source content: "Abolish Big Data was first distributed as a pamphlet at Yeshi's opening speech at the second Data for Black Lives conference on January 11–13, 2019."
Comparison: Verbatim confirmation on D4BL's own campaign page, including the January 2019 dating of D4BL II.
Decision: primary-sourced

## Claim 15: the manifesto was "published by Data & Society in 2020" (origin, body, sources[3].note)

Source: https://datainfra.wordsinspace.net/spring2020/2020/02/19/databite-no-129-abolish-big-data-with-yeshimabeit-milner-march-4/
Source tier: caution
Source content: "The event occurred on March 4, 2020, at Data & Society in New York"
Comparison: Data & Society's 2020 "Abolish Big Data" artifact is a March 2020 Databite talk in its library (datasociety.net/library 403s on direct fetch); no fetchable source shows D&S publishing the manifesto text as a 2020 publication. The claim may conflate the D&S library talk entry with publication of the document.
Decision: uncorroborated

## Claim 16: naming big data as "a philosophy, an ideological regime, one that determines how decisions are made and who makes them" (origin, body, sources[3].note)

Source: https://d4bl.org/videos/19-abolish-big-data
Source tier: primary
Source content: "It has become a philosophy, an ideological regime, about how decisions are made and who makes them."
Comparison: Paraphrase-as-quote: the source text reads "about how decisions are made", not "one that determines how decisions are made". Replace the quoted words with the source wording (or unquote the paraphrase). Appears in origin frontmatter, body § The core argument, and sources[3].note.
Decision: correction

## Claim 17: tracing data technologies to "a long and pervasive historical legacy of scientific oppression" from chattel slavery through the Prison Industrial Complex

Source: https://d4bl.org/videos/30-abolish-big-data-uci-bren-ics
Source tier: primary
Source content: "Big Data is part of a long and pervasive historical legacy of scientific oppression, aggressive public policy and the most influential political and economic institution that has and continues to shape this country's economy: chattel slavery."; "Algorithms and other data technologies are the engines that have facilitated the ongoing evolution of chattel slavery into the Prison Industrial Complex"
Comparison: Quoted phrase and the slavery→PIC arc verbatim in the talk abstract on D4BL's own page.
Decision: primary-sourced

## Claim 18: demanding "redistribution of data power to communities that need it most"

Source: https://en.wikipedia.org/wiki/Yeshimabeit_Milner
Source tier: tiebreaker
Source content: "They use the slogan, 'Abolish Big Data!' with hopes to redesign big data and to 'put data into the hands of those who need it most'."
Comparison: Matches Milner's stated demand; also carried in the Data & Society Databite description ("To abolish Big Data would mean to put data in the hands of people who need it the most", quoted via the course-blog reproduction, caution tier). No second canonical source fetched.
Decision: single-source

## Claim 19: Milner "a Brown University Africana Studies graduate"

Source: https://en.wikipedia.org/wiki/Yeshimabeit_Milner
Source tier: tiebreaker
Source content: Wikipedia: "Brown University, graduated 2012 with a BA in Africana Studies"; Echoing Green: "a BA from Brown University"
Comparison: Brown BA is corroborated (Echoing Green + Wikipedia); the field "Africana Studies" rests on Wikipedia alone.
Decision: single-source

## Claim 20: Milner "had worked as a community organiser in Miami and Chicago" (body)

Source: https://fellows.echoinggreen.org/fellow/yeshimabeit-milner/
Source tier: primary
Source content: Echoing Green: she "began organizing against the school-to-prison pipeline at Power U Center for Social Change [Miami] as a high school senior", returned to Power U in 2013, then was "a campaign manager at Color of Change"; MIT News: "Yeshimabeit Milner of Miami and Max Clermont of Chicago"
Comparison: Every biographical source (Echoing Green, Wikipedia, WWS interview) places her organizing in Miami; none mentions Chicago. MIT News attaches Chicago to third organizer Max Clermont — the body likely conflates the two. Replace "in Miami and Chicago" with "in Miami".
Decision: correction

## Claim 21: Lucas Mason-Brown, "mathematician"

Source: https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
Source tier: mainstream
Source content: "Lucas Mason-Brown, an MIT PhD candidate in mathematics"
Comparison: Confirmed; his Echoing Green/d4bl bios (Oxford mathematics research fellow, MIT PhD in mathematics) agree.
Decision: corroborated

## Claim 22: "The opening panel heard from Ruha Benjamin on the substrate of anti-Black racism that algorithmic systems encoded" (body)

Source: https://civic.mit.edu/2017/11/18/data-for-black-lives-opening-panel-live-blog/
Source tier: primary
Source content: Live blog lists the opening-panel participants as "Yeshimabeit Milner (moderator), Cathy O'Neil, Malika Saada Saar, Dr. Atyia Martin, and Purvi Shah"; d4bl.org/videos/21: "Opening Remarks: Rafael Reif ... Keynote Address: Ruha Benjamin (45 min)" (D4BL I, November 16, 2017)
Comparison: Ruha Benjamin was not on the opening panel — she delivered the conference's 45-minute keynote address. Replace "The opening panel heard from Ruha Benjamin" with keynote attribution (O'Neil's panel attribution in the same sentence is correct).
Decision: correction

## Claim 23: Cathy O'Neil's "Algorithms are opinions embedded in code" at the opening panel

Source: https://civic.mit.edu/2017/11/18/data-for-black-lives-opening-panel-live-blog/
Source tier: mainstream
Source content: "Algorithms are opinions embedded in code."
Comparison: Verbatim in the contemporaneous live blog, which seats O'Neil on the opening panel.
Decision: single-source

## Claim 24: "The Obama White House's 2014 and 2016 Big Data reviews engaged the civil rights framing directly"

Source: https://obamawhitehouse.archives.gov/sites/default/files/microsites/ostp/2016_0504_data_discrimination.pdf
Source tier: primary
Source content: 2016 report is titled "Big Data: A Report on Algorithmic Systems, Opportunity, and Civil Rights"; the 2014 Podesta report ("Big Data: Seizing Opportunities, Preserving Values") found "Big data analytics have the potential to eclipse longstanding civil rights protections in how personal information is used"
Comparison: The 2016 review's title is itself the civil-rights engagement; the 2014 review's key finding names civil rights protections. Both reports live on obamawhitehouse.archives.gov.
Decision: corroborated

## Claim 25: "the U.S. Civil Rights Commission's 2023 report on algorithms and civil rights drew a direct line from the 2014 principles to federal algorithmic accountability policy" (body)

Source: https://www.usccr.gov/reports/2023/civil-rights-implications-algorithms
Source tier: primary
Source content: "The Connecticut Advisory Committee to the U.S Commission on Civil Rights" examined "the civil rights implications in the use of algorithms ... by state actors and agencies" (April 6, 2023)
Comparison: The 2023 "Civil Rights Implications of Algorithms" report was issued by a state advisory committee, not the national Commission; its scope is Connecticut state agencies, not federal policy; and no reference to the 2014 principles was found. The sentence misattributes issuer and scope; correction requires prose judgment (rewrite or drop the sentence).
Decision: correction

## Claim 26: MacArthur Foundation grantmaking to D4BL (2019–2021)

Source: https://www.macfound.org/grantee/data-for-black-lives-10115070/
Source tier: primary
Source content: "2021: $500,000 (1 year); 2019: $400,000 (2 years) ... Both grants provided general operating support."
Comparison: Matches; Wikipedia concurs ("Between 2019 and 2021, D4BL was awarded a grant by the MacArthur Foundation for broad operating support").
Decision: corroborated

## Claim 27: D4BL "grew to a network of over 20,000 scientists and activists"

Source: https://d4bl.org/about
Source tier: primary
Source content: "With our national network of over 20,000 scientists and activists"
Comparison: Verbatim on D4BL's own about page.
Decision: primary-sourced

## Claim 28: "It established regional chapters, hosted annual conferences at MIT" (body)

Source: https://d4bl.org/conferences
Source tier: primary
Source content: Conference index lists exactly three conferences: "D4BL I (November 17-19, 2017) — MIT Media Lab"; "D4BL II (2019)"; "D4BL III (November 18-20, 2024) — Pérez Art Museum in Miami". Home page lists "DMV (DC/Maryland/Virginia) Hub" and "Detroit Hub".
Comparison: Regional hubs confirmed. "Annual conferences at MIT" is contradicted by D4BL's own record: three conferences across seven years (2017, 2019, 2024), the latest in Miami, not MIT. MIT News 2017 records only the organizers' "hope the three-day conference will become an annual event". Correction requires prose judgment (e.g. "hosted conferences at the MIT Media Lab (2017, 2019) and in Miami (2024)").
Decision: correction

## Claim 29: launched "#NoMoreDataWeapons (2021)"

Source: https://d4bl.org/dispatch/72-introducing-no-more-data-weapons
Source tier: primary
Source content: "Introducing #NoMoreDataWeapons" dispatch dated February 25, 2021 — "This is a call for no more investing in Data Weapons, no more building new Data Weapons, no more disguising Data Weapons as legitimate and neutral."
Comparison: Campaign introduced 2021 on D4BL's own site.
Decision: primary-sourced

## Claim 30: "the Home Owners' Loan Corporation's property-assessment maps encoded racial and ethnic characterisations into lending criteria" (body)

Source: https://en.wikipedia.org/wiki/Home_Owners%27_Loan_Corporation
Source tier: tiebreaker
Source content: HOLC maps "also used demographic information (such as the racial, ethnic, and immigrant composition of neighborhoods) to categorize creditworthiness"
Comparison: Matches; public-record historical fact, Wikipedia-alone sufficient under the corpus source rule. (Wikipedia also notes scholarly debate about HOLC's causal role in segregation, which the entity does not overstate.)
Decision: single-source

## Claim 31: "Ruha Benjamin's 2019 *Race After Technology* built a scholarly framework around the 'New Jim Code' — the reproduction of racial inequality through seemingly neutral technology"

Source: https://en.wikipedia.org/wiki/Race_After_Technology
Source tier: tiebreaker
Source content: "Published in 2019"; Benjamin "develops her concept of the 'New Jim Code' ... to analyze how seemingly 'neutral' algorithms and applications can replicate or worsen racial bias"
Comparison: Publication year and concept match; the entity paraphrases without quotation marks. Named-work definitional fact, Wikipedia-alone sufficient.
Decision: single-source

## Claim 32: scalar:sources[1].note — MIT News as "primary source for the 400-attendee figure" and for conference dates "(November 17–19, 2017, MIT Media Lab)"

Source: https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
Source tier: mainstream
Source content: The article's only attendance figure is "more than 300 on the waiting list"; it gives no date range ("last month" from Dec 13, 2017)
Comparison: The note misattributes both the 400 figure (which lives in Milner's What's Working Solutions interview — see Claim 8) and the Nov 17–19 dates (not in MIT News; D4BL's own pages conflict, 17–19 vs 16–18) to MIT News. Fix location: sources[1].note. Same misattribution class as the correction filed on msg-data-for-black-lives sources[1].note (2026-09-05 pass).
Decision: correction

## Claim 33: scalar:sources[0].note — d4bl.org as primary source for "the D4BL programme areas (democracy, economic justice, algorithms, data governance, abolition, climate justice)"

Source: https://d4bl.org/
Source tier: primary
Source content: Live site's focus list: "Abolition, Political education, Data weapons, Data governance, Algorithms, Democracy, Artificial Intelligence, Economic justice, Social determinants, Climate justice, Education justice, Organizing, Participatory ML Research"
Comparison: The six-area list in the note no longer matches the live site's expanded list (source drift since the 2026-06-04 check; same drift noted on the msg-data-for-black-lives pass). web.archive.org is blocked, so the note's accuracy at check time is unverifiable. Fix location: sources[0].note (last_checked/note refresh), prose judgment required.
Decision: uncorroborated
