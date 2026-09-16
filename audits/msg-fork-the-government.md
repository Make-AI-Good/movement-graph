---
entity_id: msg-fork-the-government
entity_hash: bf4060a056155e2542aeabe31dd459b3216699f3
audit_date: 2026-09-15
pass: 1
status: corrections-pending
claims_total: 28
claims_corroborated: 11
claims_primary_sourced: 3
claims_single_source: 6
claims_uncorroborated: 2
open_corrections: 6
sources_consulted:
  - https://g0v.tw/intl/en/manifesto/en/
  - https://g0v.tw/intl/en/
  - https://en.wikipedia.org/wiki/G0v_movement
  - https://en.wikipedia.org/wiki/Sunflower_Student_Movement
  - https://www.taiwan-panorama.com/en/Articles/Details?Guid=736828dd-9df4-48fe-9383-71a5353cf4b7&CatId=7&postname=Pioneers+of+Open+Government:+g0v%27s+Civic+Hackers
  - https://compdemocracy.org/case-studies/2014-vtaiwan/
  - https://www.freiheit.org/taiwan/how-public-participation-can-improve-ai-governance-vtaiwans-initiatives
  - https://rebootdemocracy.ai/blog/audrey-tang-ai-democracy/
  - https://europeandemocracyhub.epd.eu/exploring-worldwide-democratic-innovations-taiwan/
  - https://rightlivelihood.org/the-change-makers/find-a-laureate/audrey-tang/
  - https://congress.crowd.law/case-vtaiwan.html
  - https://taiwan.md/en/technology/open-source-and-g0v/
  - https://github.com/openai/democratic-inputs/blob/main/README.md
  - https://medium.com/g0v-tw/g0v-how-open-government-movement-has-made-civil-society-in-taiwan-125b538b61a4
  - https://g0v.hackmd.io/@jothon/Sk9f2CxBn
  - https://covid19.mohw.gov.tw/en/cp-4868-53923-206.html
  - https://fightcovid.edu.tw/specific-topics/mask-map
  - https://focustaiwan.tw/politics/201608250036
---

Connective-type audit (message): claims are edges + hard specifics per `AUDITOR.md § Type-shape`; interpretive prose in "Why it carries" and significance framing received no decision.

## Claim 1: Edges — `originating_org: org-g0v`, `propagated_by_orgs: [org-g0v]`; body cross-refs to org-g0v and person-audrey-tang

Source: https://g0v.tw/intl/en/manifesto/en/ + https://en.wikipedia.org/wiki/G0v_movement
Source tier: primary
Source content: "g0v is a non-partisan, not-for-profit, grassroots movement"; Wikipedia: "started by Chia-liang Kao ('clkao'), ipa, kirby and others in late 2012 in Taiwan"
Comparison: Both edge targets exist in the corpus (`org-g0v`, `person-audrey-tang`) and point to the correct entities; the message is g0v's founding practice per its own manifesto and site.
Decision: corroborated

## Claim 2: "g0v (gov-zero), the Taiwanese decentralised civic-tech community launched in late 2012" founded by "Chia-liang Kao (clkao), ipa, kirby"

Source: https://en.wikipedia.org/wiki/G0v_movement + Taiwan Panorama
Source tier: mainstream
Source content: Wikipedia: "started by Chia-liang Kao ('clkao'), ipa, kirby and others in late 2012 in Taiwan"; Taiwan Panorama describes Kao as "one of the founders of g0v"
Comparison: Founder names and late-2012 timing match; Wikipedia-alone-sufficient class (named-entity definitional facts) plus mainstream corroboration.
Decision: corroborated

## Claim 3: October 2012 Economic Power-up Plan advertisement as the catalyst for Kao's Budget Maps

Source: Taiwan Panorama + https://taiwan.md/en/technology/open-source-and-g0v/ + Wikipedia
Source tier: mainstream
Source content: Panorama: "saw a 40-second advertisement in support of the government's Economic Power-up Plan in October 2012"; Wikipedia: Budget Maps "created during Yahoo! Open Hack Day 2012 in response to criticism of the government's 'Power-Up Plan for the Economy' advertisement"
Comparison: Catalyst, month, and Budget Maps outcome all match across three sources.
Decision: corroborated

## Claim 4: Budget Maps "built at the Yahoo! Open Hack Day 'Hacker #15' team in October 2012. Kao registered g0v.tw"

Source: https://medium.com/g0v-tw/g0v-how-open-government-movement-has-made-civil-society-in-taiwan-125b538b61a4 (via search snippet) + Wikipedia + taiwan.md
Source tier: primary
Source content: g0v Medium history (search snippet): the "Hacker #15" team of four pivoted to Budget Maps at Yahoo Open Hack Day 2012 (just before October 19); "Team member CL Kao registered the domain name g0v.tw, dedicated to citizens' remixes of government websites"; taiwan.md: "He changed the 'o' in the government's domain name gov.tw to a '0,' making it g0v.tw" (October 2012)
Comparison: Team name, event, month, and Kao's registration all confirmed; g0v's own Medium publication is the primary carrier of the "Hacker #15" token.
Decision: corroborated

## Claim 5: Domain practice — replacing the "o" in ".gov.tw" with "0" loads the forked civic alternative, with the expectation forked content "can then be merged back into the government agency's website" (also scalar sources[1].note quote)

Source: https://en.wikipedia.org/wiki/G0v_movement + taiwan.md + g0v Medium
Source tier: primary
Source content: Wikipedia (verbatim): "Continuing this inspiration from the software development world, the forked content can then be \"merged\" back into the government agency's website."
Comparison: The exact formulation quoted in the entity's Wikipedia sources note appears verbatim in the article; the o→0 practice is corroborated by g0v's own materials and taiwan.md.
Decision: corroborated

## Claim 6: Manifesto quotations — "polycentric community of self-organised contributors", "dig into problems", "act to change the status quo", "open-source, allowing more people to use, improve, comment", "non-partisan, not-for-profit", "no single center or representative", "bring more citizens to participate in public issues and influence government actions" (body + scalar sources[0].note)

Source: https://g0v.tw/intl/en/manifesto/en/
Source tier: primary
Source content: "We are a polycentric community of self-organized contributors"; "We the g0v contributors love to dig into problems"; "We act to change the status quo"; "Project outcomes are open-source, allowing more people to use, improve, comment, and maximize their usage"; "g0v is a non-partisan, not-for-profit, grassroots movement"; "There is no single center or representative of g0v"
Comparison: Every quoted phrase in body and sources[0].note verified verbatim against the manifesto (entity uses British "self-organised" vs manifesto "self-organized" — trivial regional-spelling variant, not a misquote); the manifesto indeed does not use "fork the government" verbatim, as the note states.
Decision: primary-sourced

## Claim 7: The manifesto was "drafted by ipa and refined through community deliberation"

Source: https://g0v.hackmd.io/@jothon/Sk9f2CxBn (g0v Civic Tech Project & Community Handbook, via search snippet)
Source tier: primary
Source content: The manifesto "was originally drafted by ipa and, after many rounds of community deliberation and discussion, now clearly represents and defines the g0v spirit"
Comparison: Authorship and deliberative refinement match g0v's own handbook.
Decision: primary-sourced

## Claim 8: Co-founding slogan "Ask not why nobody is doing this. You are the nobody!" (origin scalar + body)

Source: https://en.wikipedia.org/wiki/G0v_movement (via search snippet) + Taiwan Panorama
Source tier: mainstream
Source content: Wikipedia/Plurality rendering: "Ask not why nobody is doing this. You are the 'nobody'!"; Panorama's variant rendering: "Don't ask why 'no one' is doing a particular thing. First, admit that you yourself are 'no one.'"
Comparison: The entity's rendering matches g0v's standard English rendering (carried by Wikipedia and the Plurality book); Panorama independently confirms the slogan's content in a variant translation. Note: the body hyperlinks this quote to Taiwan Panorama, whose rendering differs — the wording actually follows the g0v-standard rendering, a link-attribution imprecision below correction threshold.
Decision: corroborated

## Claim 9: Campaign-finance digitisation — "more than thirty thousand politician-donation files in twenty-four hours"

Source: Taiwan Panorama
Source tier: mainstream
Source content: "within 24 hours of g0v's launch of a project to track political contributions, civic hackers had digitized more than 30,000 files"
Comparison: Figures match the cited source exactly; no second source checked.
Decision: single-source

## Claim 10: Sunflower Movement "March–April 2014"; Tang and g0v collaborators "built real-time civic communication infrastructure inside the occupied parliament"

Source: https://en.wikipedia.org/wiki/Sunflower_Student_Movement + https://rightlivelihood.org/the-change-makers/find-a-laureate/audrey-tang/ + https://europeandemocracyhub.epd.eu/exploring-worldwide-democratic-innovations-taiwan/
Source tier: database
Source content: Wikipedia: "Date: March 18 – April 10, 2014"; Right Livelihood: g0v's tools "enabled the public to livestream debates, co-translate content and engage decision-makers in real time"; EDH: g0v activists "built digital infrastructure connecting online and offline participants"
Comparison: Dates fall in the Wikipedia-alone-sufficient public-event class; Tang/g0v infrastructure role corroborated by two further sources (the body's rightlivelihood.org link checks out).
Decision: corroborated

## Claim 11: The Sunflower Movement "led the Taiwan government to ask the g0v community to build vTaiwan"

Source: https://compdemocracy.org/case-studies/2014-vtaiwan/ + https://congress.crowd.law/case-vtaiwan.html
Source tier: primary
Source content: compdemocracy: "The government conceded, and requested that the g0v (pronounced 'gov zero') civic tech community create a scalable listening process for national use."; crowd.law: Minister without Portfolio Jaclyn Tsai "attended a g0v.tw hackathon in December 2014 and asked the volunteers if they could 'create a platform for rational discussion and deliberation of policy issues'"
Comparison: The government-request origin matches both sources.
Decision: corroborated

## Claim 12: vTaiwan "2014–2015 launch" with "the August 2015 ride-sharing deliberation as the first case" (scalar sources[3].note + body)

Source: https://compdemocracy.org/case-studies/2014-vtaiwan/ + https://congress.crowd.law/case-vtaiwan.html
Source tier: primary
Source content: compdemocracy: "The first test of vTaiwan was in August 2015 on how to regulate the ride sharing service Uber."; crowd.law: request made December 2014, platform launched 2015
Comparison: The 2014–2015 build window (Dec 2014 request → Aug 2015 first test) and first-case identification match.
Decision: corroborated

## Claim 13: vTaiwan is "the longest-running national-scale Polis implementation"

Source: https://compdemocracy.org/case-studies/2014-vtaiwan/
Source tier: primary
Source content: "today vTaiwan contains the longest running, national-scale implementation of Polis"
Comparison: Verbatim match; compdemocracy is the Computational Democracy Project — Polis's own maintainers, primary for claims about Polis deployments.
Decision: primary-sourced

## Claim 14: "approximately eighty percent of its twenty-eight deliberation issues leading to legislative or regulatory action" (body)

Source: https://congress.crowd.law/case-vtaiwan.html (cited compdemocracy source carries no figures)
Source tier: database
Source content: crowd.law: "It has been used to craft 26 pieces of legislation... More than 80% of processes once initiated lead to 'decisive government action.'" Other coverage (search snippets) gives "26 cases by February 2018" and "more than 28 issues" — counts conflict across sources.
Comparison: The ~80% rate is well-attested, but the 28-issue count conflicts with crowd.law's 26 and with by-2018 figures, and the entity's cited source (compdemocracy) carries neither number (probed twice: "no numbers... regarding how many issues... nor any percentages"). Canonical sources disagree — no winner picked.
Decision: uncorroborated

## Claim 15: scalar:sources[3].note — compdemocracy case study cited "for the 28-issue count with approximately 80-percent legislative-action rate"

Source: https://compdemocracy.org/case-studies/2014-vtaiwan/
Source tier: primary
Source content: Targeted probe of the full text: "I found no numbers regarding how many issues, cases, or topics vTaiwan has deliberated, nor any percentages of them leading to government or legislative action."
Comparison: Scalar path `sources[3].note` (compdemocracy entry): the page does not contain the 28-issue count or the 80% rate the note attributes to it — misattribution; the clause should be removed or reattributed (the 26/80% figures live at congress.crowd.law). Fix location is frontmatter prose, and the paired body figure (Claim 14) is source-conflicted — prose judgment needed, Editor may flag to Researcher.
Decision: correction

## Claim 16: "Audrey Tang's 2016 appointment as Minister without Portfolio"

Source: https://focustaiwan.tw/politics/201608250036 (via search snippet) + Right Livelihood + Wikipedia
Source tier: mainstream
Source content: Tang "was appointed Taiwan's Minister without Portfolio responsible for digital policies in October 2016... Before her appointment, Tang was an active member in g0v"; Right Livelihood: "minister without portfolio responsible for digital affairs", "Taiwan's first digital minister"
Comparison: Year, title, and g0v provenance match across mainstream and database sources.
Decision: corroborated

## Claim 17: The appointment was "the first direct pipeline from a civic-tech community into national government in Taiwan's history"

Source: no canonical source found
Source tier: none
Source content: Sources confirm Tang was "Taiwan's first digital minister" and a g0v activist (Right Livelihood, Focus Taiwan), but none asserts a first-civic-tech-pipeline-into-government claim.
Comparison: Contested-firstness characterization — no canonical source states this historical first; Wikipedia is tiebreaker-only for who-was-first claims and carries nothing here either.
Decision: uncorroborated

## Claim 18: "Hong Kong branch g0vhk (founded 2016)" and "Italian branch g0v.it (founded 2019)"

Source: https://en.wikipedia.org/wiki/G0v_movement
Source tier: tiebreaker
Source content: g0vhk "founded in 2016 by data scientist Ho Wa Wong"; g0v.it "founded in 2019 by the Copernicani NPO"
Comparison: Founding dates match; org founding dates are in the Wikipedia-alone-sufficient class (named-entity definitional facts), so the single source suffices, recorded here as supported-on-one-source.
Decision: single-source

## Claim 19: "The Hong Kong Umbrella Movement of 2014 reused g0v source code"

Source: Taiwan Panorama
Source tier: mainstream
Source content: "Participants in Hong Kong's 2014 Umbrella Movement went on to use g0v's source code"
Comparison: Matches the cited source; no second source checked (Wikipedia's g0v article does not mention it).
Decision: single-source

## Claim 20: "By 2018 the European Democracy Hub was treating Taiwan's participatory digital-governance model... as one of the leading global democratic-innovation cases" (body)

Source: https://europeandemocracyhub.epd.eu/exploring-worldwide-democratic-innovations-taiwan/
Source tier: mainstream
Source content: "The article was published on June 17, 2022 by Ming-sho Ho for the European Democracy Hub."
Comparison: The cited EDH Taiwan case study dates from 2022, not 2018; no source supports a 2018 EDH treatment. Single token fix: "By 2018" → "By 2022" (the surrounding "International diffusion (2014–2022)" section bound is consistent with 2022).
Decision: correction

## Claim 21: scalar:sources[6].note — EDH case study cited for "the Alignment Assemblies as the AI-governance continuation of the g0v civic-tech-to-policy arc"

Source: https://europeandemocracyhub.epd.eu/exploring-worldwide-democratic-innovations-taiwan/
Source tier: mainstream
Source content: Targeted probe: "Alignment Assemblies — This term does not appear in the provided document." Article published 17 June 2022, predating the Alignment Assemblies entirely.
Comparison: Scalar path `sources[6].note` (europeandemocracyhub entry): the article cannot and does not cover the Alignment Assemblies — the clause should be struck from the note (the note's other elements verify; see Claim 28). Frontmatter-prose fix.
Decision: correction

## Claim 22: vTaiwan "relaunched as a community-based project specifically targeting AI governance" in 2023; four-stage model (Proposal, Opinion Collection, Deliberation, Realization); AI topics incl. data protection and market concentration; consensus outcomes (cultural sensitivity, open-source AI promotion, source code and training topics publicly accessible)

Source: https://www.freiheit.org/taiwan/how-public-participation-can-improve-ai-governance-vtaiwans-initiatives
Source tier: mainstream
Source content: "In 2023, vTaiwan was relaunched as a community-based project."; stages "Proposal, Opinion Collection, Deliberation, and Realization"; consensus: "AI systems should have higher cultural sensitivity from development to deployment", open-source AI encouraged, "the source code and training topics should be publicly accessible for scrutiny"; topics included personal data protection and market concentration
Comparison: All elements match the cited source; only this one source checked for the relaunch specifics.
Decision: single-source

## Claim 23: "Bridging the Recursive Public" project "in partnership with UK-based Chatham House, was selected as one of ten teams to receive a $100,000 grant under OpenAI's Democratic Input to AI initiative (2023)" (body + scalar sources[4].note)

Source: https://github.com/openai/democratic-inputs/blob/main/README.md + freiheit.org
Source tier: primary
Source content: OpenAI repo: "The Democratic Inputs to AI grant program funded 10 teams..."; team 10 listed as "vTaiwan and Chatham House: Bridging the Recursive Public"; freiheit: ten teams, $100,000 each, "vTaiwan, in collaboration with the UK-based Chatham House, was selected with their 'Bridging the Recursive Public' project"
Comparison: Project name, Chatham House partnership, ten teams, $100,000, and 2023 all corroborated — but the program name is "Democratic Inputs to AI" (plural) per OpenAI's own materials; the entity's "Democratic Input to AI" (in body and `sources[4].note`) follows freiheit's rendering and contradicts the primary. Single token fix: "Input" → "Inputs" in both locations.
Decision: correction

## Claim 24: "In March 2024 the Ministry of Digital Affairs (moda)... launched the Alignment Assemblies of AI in partnership with the Collective Intelligence Project, Anthropic, OpenAI, The GovLab, and the GETTING-Plurality research network, inviting hundreds of thousands of randomly selected Taiwanese citizens by SMS" to deliberate AI evaluation guidelines (body heading + body + scalar sources[5].note)

Source: https://rebootdemocracy.ai/blog/audrey-tang-ai-democracy/
Source tier: mainstream
Source content: "the moda has advanced Alignment Assemblies with the Collective Intelligence Project (CIP) and world-class partners such as Anthropic, OpenAI, The GovLab and GETTING-Plurality research network."; "Through the 111 SMS number, hundreds of thousands of randomly selected citizens were invited by the moda in March this year [2024] to co-create guidelines for AI evaluation in the context of information integrity." The article describes a prior "moda–CIP Alignment Assembly in 2023" with Taipei and Tainan workshops.
Comparison: Partners, SMS mechanism, scale, and deliberation topics (AI-content detection/labelling, falsehood-exposure notification, digital IDs for content accountability, citizen oversight) all match — but "launched... in March 2024" misdates the program: the moda–CIP Alignment Assemblies began in 2023; March 2024 was the SMS citizen deliberation within them. Fix spans body heading "(March 2024)", body sentence, and `sources[5].note` ("the March 2024 Alignment Assemblies of AI launched by...") — needs a phrase-level rewrite, prose judgment beyond one token; Editor should flag to Researcher.
Decision: correction

## Claim 25: Tang quote — "progress can only be achieved when AI is grounded in participation: to build AI for the people, with the people" (body + scalar sources[5].note)

Source: https://rebootdemocracy.ai/blog/audrey-tang-ai-democracy/
Source tier: mainstream
Source content: "Unnecessary trade-offs between the rapidity of rollout and safety are unacceptable when it comes to transformative technologies. Progress can only be achieved when they are grounded in participation: to build AI for the people, with the people."
Comparison: Paraphrase-as-quote: the source says "when they are grounded" (they = transformative technologies), not "when AI is grounded" — the entity substitutes "AI" inside quotation marks, in both body and `sources[5].note`. Single replacement: restore "they" (or quote only the "to build AI for the people, with the people" clause).
Decision: correction

## Claim 26: "the COVID mask-availability map" as a g0v civic fork the government then operationalised in pandemic response

Source: https://covid19.mohw.gov.tw/en/cp-4868-53923-206.html + https://fightcovid.edu.tw/specific-topics/mask-map (via search snippets) + taiwan.md
Source tier: primary
Source content: MOHW: "Digital Minister Audrey Tang gathered private sectors to use the open data of National Health Insurance Administration to develop the face mask inquiry platform (map of face mask stock)"; fightcovid.edu.tw: mask map built by the g0v community (Feb 2020, Howard Wu), government then released pharmacy inventory data updated every 30 minutes
Comparison: The mask map as a g0v-community fork subsequently operationalised with government open data is confirmed by two Taiwan-government primary pages.
Decision: corroborated

## Claim 27: scalar:sources[2].note — Taiwan Panorama cited for Kao's founder role, the Oct 2012 ad catalyst, the "Don't ask why no one..." slogan rendering, the 30,000-files/24-hours digitisation, and "the Taiwan Panorama ranking of g0v among the top three global civic-tech communities"

Source: Taiwan Panorama
Source tier: mainstream
Source content: "Taiwan's civic hacker community one of the top three in the world"; "Don't ask why 'no one' is doing a particular thing. First, admit that you yourself are 'no one.'"; "within 24 hours... digitized more than 30,000 files"; Kao "one of the founders of g0v"
Comparison: Scalar path `sources[2].note`: every element accurately relays the cited article ("g0v" vs the article's "Taiwan's civic hacker community" for the ranking is a fair contextual equivalence); the ranking is Panorama's own single-outlet claim.
Decision: single-source

## Claim 28: scalar:sources[6].note — "the JOIN platform (5,000-endorsement threshold for a formal government response)" and "the bimonthly hackathon cadence"

Source: https://europeandemocracyhub.epd.eu/exploring-worldwide-democratic-innovations-taiwan/
Source tier: mainstream
Source content: initiatives with "more than 5,000 endorsements, the relevant governmental agencies have to respond with a formal explanation"; g0v "holds bimonthly events called 'hackathons'"
Comparison: Scalar path `sources[6].note`: these elements match the cited article (its Alignment-Assemblies clause is the Claim 21 correction).
Decision: single-source
