---
entity_id: msg-data-for-black-lives
entity_hash: 8db97849897a24266eb01a5650042372f0b89f5e
audit_date: 2026-09-05
pass: 1
status: corrections-pending
claims_total: 27
claims_corroborated: 9
claims_primary_sourced: 8
claims_single_source: 0
claims_uncorroborated: 7
open_corrections: 3
sources_consulted:
  - https://d4bl.org/
  - https://d4bl.org/about
  - https://d4bl.org/conferences
  - https://d4bl.org/conferences/3-d4-bl-i
  - https://d4bl.org/videos/19-abolish-big-data
  - https://d4bl.org/campaigns/2-no-more-data-weapons
  - https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
  - https://civic.mit.edu/2017/11/18/data-for-black-lives-opening-panel-live-blog/
  - https://reif.mit.edu/speeches-writing/opening-remarks-inaugural-data-black-lives-d4bl-conference
  - https://en.wikipedia.org/wiki/Data_for_Black_Lives
  - https://en.wikipedia.org/wiki/Yeshimabeit_Milner
  - https://whatsworkingsolutions.org/resource/interview-with-yeshi-milner-data-for-black-lives/
  - https://www.macfound.org/grantee/data-for-black-lives-10115070/
  - https://dair-institute.org/press-release/
  - https://www.dair-institute.org/
---

Connective type (Message): claim surface is edges + hard specifics per `AUDITOR.md § Type-shape` and `MISSION.md § Auditor`. Interpretive prose (§ The core argument register comparisons, § Why it has carried framing) received no decisions. datasociety.net/library remains 403 on direct fetch (workbench note 2026-09-04); Abolish Big Data claims verified via D4BL's own pages and search snippets of the D&S entry.

## Claim 1: D4BL founded November 2017 by Yeshimabeit Milner and Lucas Mason-Brown in Cambridge, Massachusetts (origin scalar + body § Origin)

Source: https://en.wikipedia.org/wiki/Data_for_Black_Lives
Source tier: tiebreaker
Source content: "Data for Black Lives was founded by Yeshimabeit Milner and Lucas Mason-Brown" in "November 2017"; "Headquartered in Cambridge, Massachusetts". MIT News (Dec 2017, contemporaneous): "Lucas Mason-Brown, an MIT PhD candidate in mathematics, organized the Data for Black Lives (D4BL) conference with Yeshimabeit Milner of Miami and Max Clermont of Chicago."
Comparison: Founding date/founders/HQ are named-entity definitional facts (Wikipedia-alone sufficient) and are additionally confirmed by MIT News + d4bl.org (Milner listed as founder). MIT News names Max Clermont as a third conference co-organizer; org-founder attribution to Milner + Mason-Brown stands per Wikipedia (both articles) and D4BL's own pages — no contradiction.
Decision: corroborated

## Claim 2: Milner is a Brown University Africana Studies graduate (origin scalar + body § Origin)

Source: https://en.wikipedia.org/wiki/Yeshimabeit_Milner
Source tier: tiebreaker
Source content: "Milner attended Brown University, graduating in 2012 with a BA degree in Africana Studies." Echoing Green / Ashoka fellowship bios (search-confirmed) carry the same BA Africana Studies 2012.
Comparison: Definitional biographical fact; Wikipedia + fellowship-directory bios agree.
Decision: corroborated

## Claim 3: Milner "had organised communities in Miami and Chicago" (origin scalar + body § Origin)

Source: https://whatsworkingsolutions.org/resource/interview-with-yeshi-milner-data-for-black-lives/
Source tier: primary
Source content: Interview (Milner's own account) discusses Miami youth organizing and infant-mortality campaign work; "contains no mention of Chicago organizing." MIT News: "Yeshimabeit Milner of Miami and Max Clermont of Chicago" — Chicago attaches to conference co-organizer Max Clermont, not Milner. Wikipedia Milner: Miami (Power U Center for Social Change) only.
Comparison: Every consulted source places Milner's organizing in Miami; none ties her to Chicago. The "and Chicago" token appears to conflate MIT News's description of Max Clermont with Milner. Fix: drop "and Chicago" in the origin scalar (frontmatter `origin`) and body § Origin. Single-token deletion, but it appears in two locations.
Decision: correction

## Claim 4: Milner "documented that Black children in Massachusetts school districts were being suspended at disproportionately higher rates than white children using publicly-available district data" (origin scalar + body § Origin, body-linked to MIT News)

Source: https://whatsworkingsolutions.org/resource/interview-with-yeshi-milner-data-for-black-lives/
Source tier: primary
Source content: "We surveyed over 600 young people in Miami-Dade County public schools about their experiences with suspensions, arrests, and police brutality in schools." Wikipedia (D4BL): she "discovered through research that black children were getting suspended at a much higher rate than white children" (no location). The body-cited MIT News article carries no suspension-research account at all (only "activist since high school, when she started organizing around the school-to-jail pipeline issue").
Comparison: The documented suspension research is Miami-Dade (Power U survey of 600 students, turned into the comic book "Telling It Like It Is"), not Massachusetts, and it was community survey data the campaign collected, not "publicly-available district data." The body also misattributes the account to the MIT News article, which does not carry it. Fix location: frontmatter `origin` scalar + body § Origin sentence with the MIT News inline link. Requires prose judgment beyond a single token (location + method + citation) — Editor should `[editor-flag]` to Researcher.
Decision: correction

## Claim 5: Inaugural conference held November 17–19, 2017 at the MIT Media Lab (body § Origin; scalar:sources[1].note)

Source: https://reif.mit.edu/speeches-writing/opening-remarks-inaugural-data-black-lives-d4bl-conference
Source tier: primary
Source content: MIT President Reif's opening remarks are dated "Friday, November 17, 2017" and reference "the next two days." d4bl.org/conferences index: "On November 17-19 2017 we brought together... for the inaugural Data for Black Lives conference at the MIT Media Lab." BUT D4BL's own detail page (d4bl.org/conferences/3-d4-bl-i) states "November 16–18, 2017."
Comparison: Two canonical sources (MIT president's contemporaneous remarks; D4BL's conferences index) support Nov 17–19 as stated; D4BL's own conference detail page conflicts with both (16–18). Canonical sources conflict — per decision rules the audit does not pick a winner. MIT Media Lab venue is uncontested across all sources. Not an error finding; the weight of contemporaneous evidence favors the entity's dates.
Decision: uncorroborated

## Claim 6: Inaugural conference drew 400 participants, with 300+ on the waiting list watching by livestream (origin scalar + body § Origin)

Source: https://whatsworkingsolutions.org/resource/interview-with-yeshi-milner-data-for-black-lives/
Source tier: primary
Source content: Milner: "I started the organization at a conference at the MIT Media Lab in 2017 where we convened 400 people." MIT News: "The registration filled up quickly, with more than 300 on the waiting list who were able to watch the conference sessions via Facebook livestream."
Comparison: The 400 figure rests on Milner's own first-person account (entity-primary); the 300+ waitlist-via-livestream detail matches MIT News exactly. Each half is supported by one source; the 400 half's source is primary-tier.
Decision: primary-sourced

## Claim 7: scalar:sources[1].note — MIT News as "primary source for the 400-attendee figure, the 300+ waiting-list figure, the founding by Milner and Mason-Brown"

Source: https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
Source tier: mainstream
Source content: The article states "more than 300 on the waiting list who were able to watch the conference sessions via Facebook livestream" but "does not specify total attendees present" — no 400 figure anywhere in the article. It also names three organizers (Mason-Brown, Milner, Max Clermont), not two.
Comparison: The note asserts the MIT News article carries the 400-attendee figure; it does not (the figure lives in Milner's own statements, e.g. the What's Working Solutions interview). Fix location: scalar:sources[1].note — remove "the 400-attendee figure" from the list of facts this source is claimed to carry (the 300+ waitlist and conference-framing elements are accurate). Same misattribution class as msg-carceral-tech sources[4].note (pass-1 correction).
Decision: correction

## Claim 8: D4BL founding mission — "make data a tool for social change instead of a weapon of political oppression" (origin scalar; scalar:sources[0].note; body ¶1)

Source: https://d4bl.org/
Source tier: primary
Source content: "make data a tool for social change instead of a weapon of political oppression" (verbatim on D4BL's own site).
Comparison: Exact match, entity's own published mission statement.
Decision: primary-sourced

## Claim 9: Self-description quote — "a movement of activists, organizers, and scientists committed to the mission of using data to create concrete and measurable change in the lives of Black people" (scalar:sources[0].note; body § The core argument)

Source: https://d4bl.org/about
Source tier: primary
Source content: "a movement of activists, organizers, and scientists committed to the mission of using data to create concrete and measurable change in the lives of Black people" (verbatim, also on the homepage).
Comparison: Exact match on D4BL's own pages.
Decision: primary-sourced

## Claim 10: Network of over 20,000 scientists and activists (scalar:sources[0].note; body § Propagation)

Source: https://d4bl.org/about
Source tier: primary
Source content: "national network of over 20,000 scientists and activists"
Comparison: Exact match. (MacArthur's grantee page says "a national network of thousands" — consistent, less specific.)
Decision: primary-sourced

## Claim 11: Programme areas — Abolition, Political Education, Data Weapons, Data Governance, Algorithms, Democracy (scalar:sources[0].note; body § Propagation and § Why it has carried)

Source: https://d4bl.org/
Source tier: primary
Source content: Site lists focus areas including "Abolition, Political Education, Data Weapons, Data Governance, Algorithms, Democracy, Artificial Intelligence, Economic Justice, Education Justice, Social Determinants, and Climate Justice."
Comparison: All six named areas appear on D4BL's site. The live site now lists five additional areas — the entity's list is a subset, phrased as "programme work spanning," not exhaustive; no contradiction (source drift: list has expanded since the 2026-06-09 draft).
Decision: primary-sourced

## Claim 12: Milner's founding framing — data and technologies "have far too often been weaponized against black communities" (scalar:sources[2].note; body § Origin)

Source: https://civic.mit.edu/2017/11/18/data-for-black-lives-opening-panel-live-blog/
Source tier: primary
Source content: "Yeshimabeit opens with a reminder that data and technologies have far too often been weaponized against black communities."
Comparison: Verbatim match in the MIT Center for Civic Media contemporaneous live blog, attributed to Milner as panel moderator.
Decision: primary-sourced

## Claim 13: scalar:sources[2].note — live blog documents the "D4BL opening panel, 17 November 2017"

Source: https://civic.mit.edu/2017/11/18/data-for-black-lives-opening-panel-live-blog/
Source tier: primary
Source content: The live blog's URL path and page date are November 18, 2017.
Comparison: The note dates the opening panel 17 November; the live blog itself is dated 18 November. A live blog is normally posted during the event, implying the panel ran the 18th — but with the conference's start date itself carrying conflicting records (Claim 5) and the panel's occurrence date not stated in the page body, asserting a single correct replacement would be judgment. Fix location if the Editor acts on Claim 5's resolution: scalar:sources[2].note date token.
Decision: uncorroborated

## Claim 14: "Abolish Big Data" quote — Big Data is "a philosophy; an ideological regime, one that determines how decisions are made and who makes them" (scalar:sources[3].note; body § The core argument)

Source: https://d4bl.org/videos/19-abolish-big-data
Source tier: primary
Source content: D4BL's own page: "It has become a philosophy, an ideological regime, about how decisions are made and who makes them." Data & Society library entry (search snippet; page 403s): "it has become a philosophy; an ideological regime that determines how decisions are made, and who makes them."
Comparison: The substance is confirmed by two sources, but the entity's exact quoted string ("...one that determines...") matches neither fetched rendering, and the cited datasociety.net page is unfetchable to confirm the pamphlet's exact wording. Quote-wording variant, not a substantive error.
Decision: uncorroborated

## Claim 15: The redistributive demand — "put data in the hands of people who need it the most" (scalar:sources[3].note; body § The core argument)

Source: https://d4bl.org/videos/19-abolish-big-data
Source tier: primary
Source content: "A call to action to dismantle the structures that concentrate the power of Big Data into the hands of a few and to put data in the hands of people who need it the most." Data & Society entry (search snippet): "To abolish Big Data would mean to put data in the hands of people who need it the most."
Comparison: Verbatim match in two independent canonical renderings (D4BL's own page + the publisher's entry).
Decision: corroborated

## Claim 16: Historical continuity argument tracing data technologies through chattel slavery to the Prison Industrial Complex (scalar:sources[3].note)

Source: https://www.informatics.uci.edu/?p=5527
Source tier: mainstream
Source content: UCI account of the talk: Milner "exposed how algorithms (and its designers) have transmuted chattel slavery into the prison-industrial complex present today." California OAG-filed Milner testimony / Berkeley Belonging collection (search-confirmed): "the economic model of big data is rooted in chattel slavery" and data "central to the expansion of the prison industrial complex."
Comparison: The continuity argument is confirmed in two independent records of the work.
Decision: corroborated

## Claim 17: D4BL II conference held January 2019 (scalar:sources[3].note)

Source: https://www.racialhealthequity.org/events/2019/1/11/data-for-black-lives-conference-d4bl-at-mit
Source tier: database
Source content: D4BL II "took place January 11-13, 2019 at the MIT Media Lab" (search-confirmed; d4bl.org/conferences/4-d4-bl-ii lists the conference).
Comparison: January 2019 as stated matches the event listing and D4BL's own conference page.
Decision: corroborated

## Claim 18: "Abolish Big Data" first distributed as pamphlet at D4BL II (January 2019), published Data & Society, 2020 (scalar:sources[3].note)

Source: https://datasociety.net/library/abolish-big-data/
Source tier: none
Source content: The cited Data & Society library page 403s on direct fetch; search snippets confirm the D&S entry and a 2020-era D&S podcast episode exists, and UCI's account confirms the framework was introduced at the January 2019 conference — but neither the "first distributed in pamphlet form" element nor the "2020" publication year could be read from a fetchable canonical source this session.
Comparison: The conference-date element is confirmed (Claim 17); the pamphlet-first and publication-year elements remain unverified. Not an error finding.
Decision: uncorroborated

## Claim 19: #No More Data Weapons campaign launched February 2021, targeting predictive policing, facial recognition, social-media monitoring, demanding no more "investing in data weapons, building new data weapons, [and] disguising data weapons as legitimate and neutral" (body § Propagation; related_messages edge)

Source: https://d4bl.org/campaigns/2-no-more-data-weapons
Source tier: primary
Source content: "No more investing in Data Weapons, No more building new Data Weapons, no more disguising Data Weapons as legitimate and neutral." Campaign page names facial recognition, predictive policing, and social media surveillance. D4BL dispatch "Introducing #NoMoreDataWeapons" (search-confirmed): campaign launched February 25, 2021.
Comparison: The entity's bracket-elided quote faithfully renders the campaign's demand; launch month and named technologies match D4BL's own pages.
Decision: primary-sourced

## Claim 20: DAIR founded by Timnit Gebru in Oakland in December 2021 (body § Propagation)

Source: https://dair-institute.org/press-release/
Source tier: primary
Source content: Press release dated December 2, 2021; institute address "1440 Broadway Ste #200, Oakland, CA, 94612." Washington Post and TechCrunch (both Dec 2, 2021, search-confirmed) covered Gebru's launch of DAIR.
Comparison: Founder, month, and Oakland base all match the institute's own press release plus two mainstream outlets.
Decision: corroborated

## Claim 21: DAIR quoted as "grounded in community expertise and local needs" (body § Propagation)

Source: https://www.dair-institute.org/
Source tier: primary
Source content: DAIR's site: "The Distributed AI Research Institute is an independent organization conducting community-rooted research"; "All of our innovation is driven by local expertise and community need"; press release: "AI research rooted in their communities and lived experiences."
Comparison: The substance (community-rooted, local-needs-driven research) is well supported, but the quoted string "grounded in community expertise and local needs" appears verbatim in none of DAIR's fetched pages — a paraphrase presented as quotation. No single-token replacement exists; if corrected, the sentence should either quote DAIR's actual wording ("driven by local expertise and community need") or drop the quotation marks. Prose judgment — beyond mechanical fix.
Decision: uncorroborated

## Claim 22: DAIR's founding institutional funding from Ford Foundation, MacArthur Foundation, Kapor Center, and Open Society Foundations (body § Why it has carried)

Source: https://dair-institute.org/press-release/
Source tier: primary
Source content: Press release names funders: "Ford Foundation, John D. and Catherine T. MacArthur Foundation, Kapor Center, Open Society Foundation." TechCrunch/WaPo coverage (search-confirmed): "$3.7 million in funding from the Ford Foundation, MacArthur Foundation, Kapor Center, Open Society Foundation, and Rockefeller Foundation."
Comparison: All four funders the entity names appear in the press release and launch coverage. Coverage adds Rockefeller; the entity's list is not phrased as exhaustive — no contradiction.
Decision: corroborated

## Claim 23: Movement Scientist Fellows Program launched 2024 (body § Propagation)

Source: https://d4bl.org/
Source tier: primary
Source content: "the inaugural D4BL Movement Scientist Fellows cohort was announced in August 2024"
Comparison: Launch year matches D4BL's own announcement.
Decision: primary-sourced

## Claim 24: MacArthur Foundation operational grant to D4BL, 2019–2021 (scalar:sources[4].note; body § Propagation)

Source: https://www.macfound.org/grantee/data-for-black-lives-10115070/
Source tier: primary
Source content: 2019 grant: "$400,000 (2 years)" for "general operating support to the organization" (spanning 2019–2021); a further 2021 grant of $500,000.
Comparison: The 2019 two-year general-operating grant matches the entity's "operational grant (2019–2021)"; Wikipedia corroborates ("Between 2019 and 2021, D4BL was awarded a grant by the MacArthur Foundation for broad operating support").
Decision: corroborated

## Claim 25: Regional chapters launched "beginning with Pittsburgh" (body § Propagation; scalar:sources[4].note "expansion to regional chapters")

Source: https://en.wikipedia.org/wiki/Data_for_Black_Lives
Source tier: tiebreaker
Source content: "D4BL has regional organization chapters, including a group in Pittsburgh, Pennsylvania." Pittsburgh Post-Gazette (Oct 2020, search-confirmed): CMU student Alex Jackson "launched a Data for Black Lives Pittsburgh chapter."
Comparison: The Pittsburgh chapter's existence is confirmed (Wikipedia + Post-Gazette), but no source establishes Pittsburgh as the *first* chapter ("beginning with"). D4BL's current site references DMV and Detroit hubs without chapter chronology. The distinguishing token is unverifiable, not contradicted.
Decision: uncorroborated

## Claim 26: The inaugural conference was "built from a Twitter account in eight months" (body § Why it has carried)

Source: https://news.mit.edu/2017/mit-data-for-black-lives-conference-calculates-cost-of-tech-driven-discrimination-1213
Source tier: mainstream
Source content: "The idea grew from a Twitter account to the conference just last summer."
Comparison: The Twitter-account origin is confirmed by MIT News, but no consulted source states "eight months"; MIT News's "just last summer" (summer 2017 → November 2017) suggests a shorter run-up, while a GuideStar-derived August 2016 start (search-confirmed) would imply ~15 months. Duration unverifiable and records point in different directions.
Decision: uncorroborated

## Claim 27: Edges — propagated_by_orgs: org-algorithmic-justice-league, org-dair-institute; related_messages: msg-data-is-a-civil-rights-issue, msg-no-more-data-weapons, msg-machine-bias, msg-indigenous-data-sovereignty

Source: https://en.wikipedia.org/wiki/Data_for_Black_Lives
Source tier: tiebreaker
Source content: "Algorithmic Justice League" and the "Distributed Artificial Intelligence Research Institute (DAIR)" are listed as D4BL's "community of other organizations working towards the same goals."
Comparison: All six edge targets resolve in the corpus. org-dair-institute is the Gebru-founded Distributed AI Research Institute (Claim 20's sources) and org-algorithmic-justice-league the facial-recognition-auditing AJL — both correctly identified and both named in D4BL's documented ecosystem. msg-no-more-data-weapons corresponds to the campaign verified in Claim 19. originating_person / originating_org are empty (no edge to verify).
Decision: corroborated
