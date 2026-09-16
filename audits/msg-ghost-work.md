---
entity_id: msg-ghost-work
entity_hash: 52b27c71b25d9a1ff8ef3d47dd2204c861414aca
audit_date: 2026-09-16
pass: 1
status: corrections-pending
claims_total: 39
claims_corroborated: 8
claims_primary_sourced: 6
claims_single_source: 10
claims_uncorroborated: 9
open_corrections: 6
sources_consulted:
  - https://ghostwork.info/ghost-work/
  - https://ghostwork.info/
  - https://www.technologyreview.com/2019/05/31/103015/the-ai-gig-economy-is-coming-for-you/
  - https://www.brookings.edu/techstream/the-urgent-need-for-regulating-global-ghost-work/
  - https://www.brookings.edu/articles/reimagining-the-future-of-data-and-ai-labor-in-the-global-south/
  - https://cwa-union.org/ghost-workers-ai-machine
  - https://data-workers.org/DLA/
  - https://data-workers.org/dla/
  - https://turkopticon.net/
  - https://blog.turkopticon.net/?page_id=758
  - https://www.macfound.org/fellows/class-of-2020/mary-l-gray
  - https://www.bmz-digital.global/en/5-questions-joan-kinyua/
  - https://en.wikipedia.org/wiki/Ghost_work
  - https://en.wikipedia.org/wiki/Lilly_Irani
  - https://www.morgan-klaus.com/readings/ghost-work.html
  - https://www.techimpactonworkers.iccr.org/6-exploitation-of-data-workers
  - https://sixpeas.substack.com/p/aisw-105-ai-software-wetware-joan-kinyua-kenya
  - https://datalabelers.org/the-team.html
  - https://www.fordham.edu/academics/research/office-of-research/initiatives-and-infrastructure/internal-funding-opportunities/fordham-strategic-research-consortia/mcgannon-center/events-and-news/mcgannon-center-book-prize-for-2019-gray-and-suris-ghost-work/
  - https://www.computerweekly.com/news/366619321/Kenyan-AI-workers-form-Data-Labelers-Association
  - https://time.com/6275995/chatgpt-facebook-african-workers-union/
  - https://www.geekwire.com/2019/ghost-work-explores-ups-mostly-downs-hidden-gig-economy/
---

## Claim 1: Gray and Suri coined "ghost work" in the 2019 book (edge: originating_person → person-mary-l-gray)

Source: https://en.wikipedia.org/wiki/Ghost_work + https://ghostwork.info/ + https://www.technologyreview.com/2019/05/31/103015/the-ai-gig-economy-is-coming-for-you/
Source tier: primary
Source content: "The term was coined by anthropologist Mary L. Gray and computer scientist Siddharth Suri in their 2019 book, _Ghost Work: How to Stop Silicon Valley from Building a New Global Underclass_."
Comparison: Coinage attribution matches across the book's own site, Wikipedia, and MIT Technology Review. Edge target `person-mary-l-gray.md` exists; co-author edge target `person-siddharth-suri.md` exists.
Decision: corroborated

## Claim 2: Published 7 May 2019 by Houghton Mifflin Harcourt

Source: https://www.publishersweekly.com/978-1-328-56624-9 + retail/library listings (Amazon, Strand, WorldCat, via search)
Source tier: database
Source content: Search-indexed listings confirm "published by Houghton Mifflin Harcourt in May 2019, and the publication date was May 7, 2019" (ISBN 9781328566249).
Comparison: Origin scalar says "7 May 2019 book ... (Houghton Mifflin Harcourt)" — matches publisher/bibliographic records.
Decision: corroborated

## Claim 3: Gray's definition quote — "any work that could be—at least in part—sourced, scheduled, managed, shipped, and built through an application programming interface"

Source: https://www.technologyreview.com/2019/05/31/103015/the-ai-gig-economy-is-coming-for-you/
Source tier: mainstream
Source content: "It's any work that could be—at least in part—sourced, scheduled, managed, shipped, and built through an application programming interface, the internet, and maybe a sprinkle of artificial intelligence."
Comparison: Entity quote (origin scalar + body) is a verbatim substring; it truncates before ", the internet, and maybe a sprinkle of artificial intelligence" without an ellipsis but does not misrepresent. Article confirmed as Karen Hao, 31 May 2019 (entity's "May 2019" ✓; sources[1].note date ✓).
Decision: single-source

## Claim 4: Companies "market the output as fully automated while relying on hidden human labor" — quoted as Gray's formulation

Source: https://www.technologyreview.com/2019/05/31/103015/the-ai-gig-economy-is-coming-for-you/
Source tier: mainstream
Source content: String probe: "market the output as fully automated" — not found; "hidden human labor" — not found; "fully automated" — not found anywhere in the article. Gray's actual formulation: "It arguably becomes ghost work when the proposition is that there are no humans involved in that loop, that it's just a matter of software working its magic."
Comparison: The quoted string appears in the origin scalar (scalar path: origin) and body lede, in quotation marks attributed as Gray's formulation in this interview, but exists nowhere in the cited article — paraphrase-as-quote. Fix: replace with Gray's actual sentence or de-quote to paraphrase, in both origin scalar and body.
Decision: correction

## Claim 5: Gray characterized the shift as "the dismantlement of employment itself"

Source: https://www.technologyreview.com/2019/05/31/103015/the-ai-gig-economy-is-coming-for-you/
Source tier: mainstream
Source content: "This is really about the dismantlement of employment." (String probe: "the dismantlement of employment itself" — not found.)
Comparison: The word "itself" is not in Gray's quote. Appears inside quotation marks in the origin scalar, sources[1].note (scalar path: sources[1].note), and body § Automation's last mile. Fix: drop "itself" / quote verbatim.
Decision: correction

## Claim 6: Gray quote — "we've never quite had industries so completely sell contract labor as automation...to say that there's really not a person working here at all"

Source: https://www.technologyreview.com/2019/05/31/103015/the-ai-gig-economy-is-coming-for-you/
Source tier: mainstream
Source content: "we've never quite had industries so completely sell contract labor as automation—not just to make it difficult for a consumer to see the supply chain as we can in textiles, in food, and in agriculture, but also to say that there's really not a person working here at all."
Comparison: Entity elides the middle clause with an ellipsis marker — legitimate elision; both quoted fragments verbatim.
Decision: single-source

## Claim 7: Five-year ethnographic study across the United States and India

Source: https://ghostwork.info/ + https://www.morgan-klaus.com/readings/ghost-work.html
Source tier: primary
Source content: "Drawing on a pioneering five-year study of workers in the United States and India, the authors provide a revealing view..."
Comparison: Matches book's own site; independently echoed in book summaries ("five years of anthropological study of workers in the US and India").
Decision: corroborated

## Claim 8: Study platforms "including Amazon Mechanical Turk (MTurk) and CrowdFlower (later Figure Eight)"

Source: https://www.morgan-klaus.com/readings/ghost-work.html + book-description search results
Source tier: mainstream
Source content: "Their participants worked using four different platforms: AMT, UHRS, LeadGenius, and Amara.org." CrowdFlower appears in the book only as an example ("Uber routes the task of confirming the driver through crowdsource platforms, like CrowdFlower") and via the 2012 worker lawsuit — "not among the four platforms where the authors conducted their research."
Comparison: MTurk ✓, but CrowdFlower was not a study platform; the four were MTurk, Microsoft's UHRS, LeadGenius, and Amara. Appears in origin scalar and body § Origin. Fix: replace "and CrowdFlower (later Figure Eight)" with the actual study platforms (e.g. "Microsoft's UHRS, LeadGenius, and Amara") or drop it.
Decision: correction

## Claim 9: Approximately 8% of Americans had at some point participated in the ghost economy

Source: https://ghostwork.info/ghost-work/
Source tier: primary
Source content: "An estimated 8 percent of Americans have worked at least once in this 'ghost economy,'"
Comparison: Matches the book's own site verbatim in substance.
Decision: primary-sourced

## Claim 10: Book named Amazon, Google, Microsoft, and Uber as reliant on ghost work

Source: https://ghostwork.info/ghost-work/
Source tier: primary
Source content: "services delivered by companies like Amazon, Google, Microsoft, and Uber"
Comparison: Exact company roster matches the book's own site.
Decision: primary-sourced

## Claim 11: Workers operated "in isolation, amid great uncertainty, without feedback or benefits"

Source: https://ghostwork.info/
Source tier: primary
Source content: "in isolation, amid great uncertainty, without feedback or benefits, and under no clear labor laws."
Comparison: Quoted fragment verbatim (source continues "and under no clear labor laws"). The body's adjacent demographic roster (young mothers, early retirees, recent graduates) was not confirmed on fetched pages but is descriptive book-content summary.
Decision: primary-sourced

## Claim 12: Won the 2019 McGannon Center Book Prize (Fordham) and named a Financial Times 2019 Critic's Pick

Source: https://www.fordham.edu/.../mcgannon-center-book-prize-for-2019-gray-and-suris-ghost-work/ + https://ghostwork.info/
Source tier: primary
Source content: Fordham page title: "McGannon Center Book Prize for 2019: Gray and Suri's 'Ghost Work'"; ghostwork.info: "A 2019 Financial Times Critic's Pick" / "Fordham University Center's Book Prize, 2019".
Comparison: Both designations match; prize confirmed by the awarding institution's own page.
Decision: corroborated

## Claim 13: Gray named 2020 MacArthur Fellow "for her investigation of 'how labor, identity, and human rights are transformed by the digital economy'"

Source: https://www.macfound.org/fellows/class-of-2020/mary-l-gray
Source tier: primary
Source content: "Investigating the ways in which labor, identity, and human rights are transformed by the digital economy."
Comparison: Fellowship (class of 2020) confirmed. But the entity's quoted string is not verbatim — MacArthur's citation reads "the ways in which labor..." not "how labor...". Body § Origin quotes it with "how". Fix: quote verbatim ("the ways in which labor, identity, and human rights are transformed by the digital economy") or de-quote.
Decision: correction

## Claim 14: "Automation's last mile" is the book's animating concept

Source: https://ghostwork.info/
Source tier: primary
Source content: "mind-numbing, volatile, and low wage work required to bridge what Gray and Suri deem 'automation's last mile.'"
Comparison: Concept and attribution match the book's own site.
Decision: primary-sourced

## Claim 15: "Subsequent research by Brookings Institution analysts estimated 150–430 million ghost workers globally by 2025"

Source: https://www.brookings.edu/articles/reimagining-the-future-of-data-and-ai-labor-in-the-global-south/
Source tier: mainstream
Source content: "The World Bank estimates there are between 150 and 430 million data laborers" (Michelle Du and Chinasa T. Okolo, Brookings, October 7, 2025).
Comparison: The range matches but the attribution token is wrong: it is a World Bank estimate cited by Brookings analysts, not an estimate produced by Brookings analysts. The estimate is also absent from the entity's cited Brookings techstream article (Royer, 9 Feb 2021). Appears in origin scalar and underlies body § The global supply chain dimension. Fix: attribute to the World Bank (as cited in the 2025 Brookings article).
Decision: correction

## Claim 16: Ghost workers paid "$1–$8 per hour" (origin scalar; body: "at $1–$8 per hour")

Source: no canonical source found
Source tier: none
Source content: String probes of both Brookings articles found no $1–$8 range (Royer article's dollar figures are macro-investment numbers; Du/Okolo mentions "$10 a day" for Teleperformance workers). Adjacent published figures: "paid an average between $1.46 and $3.74 an hour" (WSJ-reported, via search).
Comparison: The specific range as stated is attributed contextually to Brookings research but appears in neither Brookings piece; no canonical source found for "$1–$8 per hour". Not demonstrably false — adjacent figures exist — so not a correction.
Decision: uncorroborated

## Claim 17: Ghost workforce concentrated in sub-Saharan Africa, South Asia, and Southeast Asia; North American/European (US-largest) demand

Source: https://www.brookings.edu/articles/reimagining-the-future-of-data-and-ai-labor-in-the-global-south/ + https://www.brookings.edu/techstream/the-urgent-need-for-regulating-global-ghost-work/
Source tier: mainstream
Source content: Du/Okolo: workers concentrated in "Africa and South and Southeast Asia"; Royer: "U.S. employers are the largest users of online labor, followed by the United Kingdom, India, and Australia" and "Western enterprises are profiting from the lucrative and cheaply-sourced labor input of African digital workers."
Comparison: Geographic triad and US-as-largest-demand supported (both sources are Brookings, so not independent; Royer's demand list also includes India/Australia, which the "North American and European demand sources" phrasing simplifies).
Decision: single-source

## Claim 18: Approximately 10,000 tasks published and 7,500 completed per hour on MTurk

Source: https://www.brookings.edu/techstream/the-urgent-need-for-regulating-global-ghost-work/
Source tier: mainstream
Source content: "Approximately 10,000 new tasks are published and 7,500 are completed per hour on MTurk."
Comparison: Verbatim match (body and sources[2].note).
Decision: single-source

## Claim 19: Royer article quotes — "basic labor protections, such as minimum wages, safety regulations, and clarity regarding taxation regimes" and ILO call for "an international governance system for digital labor platforms" (scalar: sources[2].note)

Source: https://www.brookings.edu/techstream/the-urgent-need-for-regulating-global-ghost-work/
Source tier: mainstream
Source content: "digital platform workers without basic labor protections, such as minimum wages, safety regulations, and clarity regarding taxation regimes"; "development of an international governance system for digital labor platforms that sets and requires platforms (and their clients) to respect certain minimum rights and protections"
Comparison: Both quoted fragments verbatim in the cited article; scalar path sources[2].note and body § The global supply chain dimension.
Decision: single-source

## Claim 20: 2025 analysis of 76 workers across Colombia, Ghana, and Kenya documented 60 independent incidents of psychological harm

Source: https://www.brookings.edu/articles/reimagining-the-future-of-data-and-ai-labor-in-the-global-south/
Source tier: mainstream
Source content: "A 2025 Equidem survey of 76 workers from Colombia, Ghana, and Kenya reported 60 independent incidents of psychological harm, including anxiety, depression, irritability, panic attacks, post-traumatic stress disorder (PTSD), and substance dependence."
Comparison: Figures and harms list match (Brookings' rendering of the Equidem survey; the Equidem report PDF is the underlying primary, not fetched).
Decision: single-source

## Claim 21: One former moderator described reading "up to 700 sexually explicit and violent pieces of text per day"

Source: https://www.brookings.edu/articles/reimagining-the-future-of-data-and-ai-labor-in-the-global-south/
Source tier: mainstream
Source content: "One former content moderator said he read up to 700 sexually explicit and violent pieces of text per day" (Brookings, linking Guardian reporting).
Comparison: Quoted fragment verbatim.
Decision: single-source

## Claim 22: Workers in Kenya earn ~$2/hour for work identical in content to work performed at $20/hour by US contractors

Source: https://time.com/6247678/openai-chatgpt-kenya-workers/ (via search) + https://www.techimpactonworkers.iccr.org/6-exploitation-of-data-workers
Source tier: mainstream
Source content: TIME: "OpenAI Used Kenyan Workers on Less Than $2 Per Hour"; ICCR: "a fraction of the $12.50 per hour paid to the U.S. outsourcing data training company, Sama" — no canonical source found carrying the $20/hour US-contractor comparator.
Comparison: The Kenya ~$2/hour half is well attested (TIME, mainstream). The $20/hour US comparator and the "identical in content" pairing were not found in a canonical source (ICCR's comparator is $12.50 paid to Sama, a different construct).
Decision: uncorroborated

## Claim 23: DLA launched in Nairobi on 13 February 2025 under "Empowering the People Powering AI"; Kinyua's launch frame "AI does not exist on its own. Behind every algorithm, every dataset, and every technological advancement, there is invisible labor" (edge: propagated_by_orgs → org-data-labellers-association)

Source: https://data-workers.org/DLA/ + https://www.computerweekly.com/news/366619321/Kenyan-AI-workers-form-Data-Labelers-Association (via search)
Source tier: primary
Source content: "The Data Labelers Association was officially launched on February 13th, 2025" under the theme "Empowering the People Powering AI"; Kinyua quote present verbatim: "AI does not exist on its own. Behind every algorithm, every dataset, and every technological advancement, there is invisible labor".
Comparison: Date, theme, and quote match the cited Data Workers' Inquiry page; launch independently covered by Computer Weekly. Edge target `org-data-labellers-association.md` exists.
Decision: corroborated

## Claim 24: The DLA drew 339 members in its first week

Source: https://www.computerweekly.com/news/366619321/Kenyan-AI-workers-form-Data-Labelers-Association (via search snippet; direct fetch 403)
Source tier: mainstream
Source content: "...with 339 members joining the organisation in its first week."
Comparison: Figure matches; absent from the DLA's own pages, so rests on the one Computer Weekly report.
Decision: single-source

## Claim 25: Kinyua has 5+ years of annotation experience spanning self-driving cars, medical diagnostics, and content moderation; DLA president

Source: https://data-workers.org/DLA/ + https://www.bmz-digital.global/en/5-questions-joan-kinyua/
Source tier: primary
Source content: DLA page: "over five years of experience in remote digital tasks"; BMZ: "President of the Data Labellers Association", "AI projects like self-driving cars", "I ended up working with medical data—X-rays and scans", labeling "violent, pornographic, and drug-related content".
Comparison: Years, work-type span, and leadership role all confirmed across two pages carrying her own account.
Decision: corroborated

## Claim 26: Kinyua is "a former Sama data labeller"

Source: no canonical source found
Source tier: none
Source content: Sama probed and absent from: data-workers.org/DLA/, her essay at data-workers.org/dla/, bmz-digital.global interview, sixpeas.substack interview, datalabelers.org/the-team.html ("No mention of Sama... anywhere").
Comparison: The Sama-employment token was not found in any of five Kinyua-adjacent sources; not contradicted, so not a correction.
Decision: uncorroborated

## Claim 27: DLA advocacy targets "fair compensation, mental health support, legal protections, collective bargaining"; members on "Sama, Majorel, and Teleperformance"

Source: https://www.computerweekly.com/news/366619321/Kenyan-AI-workers-form-Data-Labelers-Association (via search) + https://data-workers.org/dla/
Source tier: mainstream
Source content: Computer Weekly: launched "to fight for fair pay, mental health support and better overall working conditions". Kinyua essay mission areas: "Policy and Advocacy," "Mental Health Workshops," "Civic Education," "Reskilling," "Litigation Support" — Sama/Majorel/Teleperformance "never named as workplaces where members are employed."
Comparison: Fair compensation and mental health support attested; "legal protections, collective bargaining" as stated and the member-platform roster not found in fetched sources.
Decision: uncorroborated

## Claim 28: Kinyua interview quote "We are the labour behind AI but remain excluded from its profits"

Source: https://www.bmz-digital.global/en/5-questions-joan-kinyua/
Source tier: primary
Source content: "We are the labour behind AI but remain excluded from its profits."
Comparison: Verbatim in the cited interview.
Decision: primary-sourced

## Claim 29: ACMU founded in Nairobi on 1 May 2023 (edge: propagated_by_orgs → org-african-content-moderators-union)

Source: https://time.com/6275995/chatgpt-facebook-african-workers-union/ + https://www.foxglove.org.uk/2023/05/15/nairobi-content-moderation-summit/ (via search)
Source tier: mainstream
Source content: "150 workers subcontracted to work on ChatGPT, TikTok and Meta formed the African Content Moderator's Union on May 1, 2023" in Nairobi; Foxglove: the vote took place at the Nairobi content moderation summit.
Comparison: Date and place corroborated across TIME and Foxglove/Context coverage. Edge target `org-african-content-moderators-union.md` exists.
Decision: corroborated

## Claim 30: ACMU members are content moderators for "Meta, TikTok, YouTube, and OpenAI" at outsourced Nairobi operations

Source: https://time.com/6275995/chatgpt-facebook-african-workers-union/ (via search)
Source tier: mainstream
Source content: "150 workers subcontracted to work on ChatGPT, TikTok and Meta" — YouTube absent from founding coverage surfaced this session.
Comparison: Meta, TikTok, OpenAI attested; the YouTube token was not found in the coverage checked (not contradicted, so not a correction).
Decision: uncorroborated

## Claim 31: AWU-CWA + TechEquity 2025 report "Ghost Workers in the AI Machine" — median wage $15/hr, median 29 paid hours/week, 86% financial hardship, 66% unpaid waiting, 34% disability / 7% accommodated, "tens of thousands" of US data workers

Source: https://cwa-union.org/ghost-workers-ai-machine
Source tier: primary
Source content: "Ghost Workers in the AI Machine: U.S. Data Workers Speak Out About Big Tech's Exploitation" (AWU-CWA + TechEquity, 2025 survey); "Workers reported a median hourly wage of $15"; "median workweek of 29 hours of paid time"; "eighty-six percent of surveyed workers worry about meeting their financial responsibilities"; "66% report spending at least three hours weekly sitting at their computers waiting for tasks"; "Thirty-four percent of survey respondents reported having a disability, but only 7% (three out of 42) reported having an accommodation"; workforce "likely tens of thousands".
Comparison: Title, publishers, and every figure match the publishing union's own page (body and sources[3].note).
Decision: primary-sourced

## Claim 32: The report's "five advocacy demands (fair wages, evaluation transparency, training, career pathways, mental health protections)" (scalar: sources[3].note)

Source: https://cwa-union.org/ghost-workers-ai-machine
Source tier: primary
Source content: "The findings in the survey and interviews presented in this report demonstrate that U.S.-based data workers need:" followed by seven items — fair wages; clear and transparent evaluation and metrics; adequate training; opportunities for growth and advancement; mental health safety protocols and access to care; transparency and clear communication; employer accountability.
Comparison: The cited page enumerates seven requirements, not five — the note lists the first five and drops transparency/communication and employer accountability. Scalar path: sources[3].note. Fix: "five" → "seven" (or reproduce the full list).
Decision: correction

## Claim 33: Turkopticon founded in 2009 by Lilly Irani and Six Silberman at the University of California, Irvine

Source: https://en.wikipedia.org/wiki/Lilly_Irani + https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2729498 (via search) + Sage Handbook of Digital Labour chapter (via search)
Source tier: tiebreaker
Source content: Founders (Irani + Silberman) consistent everywhere. Founding year diverges across sources: Irani's project page (search-indexed; direct fetch 404) says "co-founded in 2009"; the Sage chapter subtitle is "(2009–2024)"; but the SSRN paper by the founders is titled "Operating an Employer Reputation System: Lessons from Turkopticon, 2008-2015" and other accounts say "In 2008 ... Irani and Silberman designed Turkopticon." Wikipedia confirms Irani's PhD was at UC Irvine (2013) but does not state the founding year; no fetched source directly places the founding at UC Irvine.
Comparison: Founders solid; the 2009 vs 2008 founding year conflicts across the founders' own materials (design 2008 / launch 2009 is the likely reconciliation but no fetched source states it), and the UCI placement is inferred rather than attested.
Decision: uncorroborated

## Claim 34: Turkopticon is a reputation/mutual-aid system letting MTurk workers rate requesters and share information

Source: https://en.wikipedia.org/wiki/Lilly_Irani (citing Irani & Silberman 2013, "Turkopticon: interrupting worker invisibility in Amazon Mechanical Turk") + https://turkopticon.net/
Source tier: primary
Source content: The founders' peer-reviewed CHI 2013 paper is titled "Turkopticon: interrupting worker invisibility in Amazon Mechanical Turk"; search-indexed descriptions: "a web site and browser extension that workers can use to review requesters"; turkopticon.net (current): "organize data workers to build collective power, improve working conditions, and hold platforms, companies, and institutions accountable."
Comparison: Functional description matches the founders' own paper and the project's site; the requester-review specifics rest on the one academic lineage.
Decision: single-source

## Claim 35: By 2021 Turkopticon transitioned to worker-led, with MTurk worker Sherry Stanley as lead organizer

Source: https://techworkerscoalition.org/blog/2021/03/10/issue-6/ (via search) + https://blog.turkopticon.net/?page_id=758
Source tier: caution
Source content: Tech Workers Coalition (Mar 2021): "Sherry Stanley, the first Amazon Mechanical Turk (AMT) worker ... to take the role of lead organizer of the Turkopticon project"; "Twelve years later, workers were leading the project". Turkopticon's own pages: "Turkopticon is led by data workers, for data workers" (no timeline, no Stanley mention).
Comparison: Current worker-led status confirmed by the project's own site; the 2021 timing and Stanley's lead-organizer role rest on a movement-blog source outside the canonical set (consistent, not contradicted).
Decision: uncorroborated

## Claim 36: Gray and Suri documented Turkopticon-era worker self-organization as "the very beginning of a labor movement among independent workers"

Source: https://www.geekwire.com/2019/ghost-work-explores-ups-mostly-downs-hidden-gig-economy/ (via search snippet; direct fetch 403)
Source tier: mainstream
Source content: Book quote confirmed as: "We are at the very beginning of a labor movement among independent workers finding their common cause in calling on a right to fair treatment and control over their lives."
Comparison: The quoted fragment is genuine book text, but no fetched source ties it to Turkopticon specifically — the entity (body § Propagation and sources[5].note) presents it as the book's characterization of Turkopticon's history, a tie not established this session.
Decision: uncorroborated

## Claim 37: Lilly Irani, cited by the Wikipedia ghost-work article, observed tech companies cultivate a perception of "technological magic" while obscuring human labor

Source: https://en.wikipedia.org/wiki/Ghost_work
Source tier: tiebreaker
Source content: "the computer science world and tech companies are invested in producing the image of technological magic" and "hides the people involved in the production, whose visibility could otherwise obstruct this favorable perception."
Comparison: The claim names Wikipedia as its source and Wikipedia does carry the Irani attribution with "technological magic" verbatim (entity's "perception of" vs source's "image of" is outside the quoted fragment).
Decision: single-source

## Claim 38: The book included "ten policy and technical recommendations" (portable benefits, data portability, minimum-wage/overtime protections, platform-design requirements)

Source: no canonical source found for the count
Source tier: none
Source content: ghostwork.info blurbs confirm recommendations exist ("offer creative suggestions for changes in the design of socio-technical systems") without a count; the site's reader-guide PDF is image-encoded/unparseable; a portable-benefits recommendation is attested in secondary summaries ("adding a so-called 'portable benefit' that attaches benefits to the work and the worker") but no fetched canonical source enumerates ten items.
Comparison: Recommendation themes are real; the specific count "ten" (origin scalar, sources[0].note, body § Why the framing has carried) could not be confirmed or refuted.
Decision: uncorroborated

## Claim 39: Cross-reference edges resolve (originating_person, propagated_by_orgs, related_messages, body links)

Source: repository file check (product/entities/)
Source tier: primary
Source content: All nine referenced entity files exist: person-mary-l-gray, person-siddharth-suri, person-joan-kinyua, pub-ghost-work-gray-suri-2019, org-data-labellers-association, org-african-content-moderators-union, msg-bossware, msg-algorithmic-management, msg-modern-slavery-content-moderation.
Comparison: Mechanical worktree check; every edge target resolves and matches the entity it names.
Decision: corroborated
