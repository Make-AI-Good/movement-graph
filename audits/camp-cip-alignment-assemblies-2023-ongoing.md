---
entity_id: camp-cip-alignment-assemblies-2023-ongoing
entity_hash: 52eb2fb00399872123559957abff25b0c30b0566
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 41
claims_corroborated: 7
claims_primary_sourced: 20
claims_single_source: 2
claims_uncorroborated: 7
open_corrections: 5
sources_consulted:
  - https://www.cip.org/alignmentassemblies
  - https://www.cip.org/blog/alignment-assemblies-nine-months-in
  - https://www.cip.org/research/participatory-ai-risk-prioritization
  - https://www.anthropic.com/research/collective-constitutional-ai-aligning-a-language-model-with-public-input
  - https://moda.gov.tw/en/press/press-releases/5243
  - https://democracy-technologies.org/participation/can-alignment-assemblies-bring-democracy-to-silicon-valley/
  - https://2024.cip.org/
  - https://www.cip.org/2025gdindex
  - https://arxiv.org/html/2406.07814v1
  - https://compdemocracy.org/case-studies/2014-vtaiwan/
  - https://globaldialogues.ai/methodology
  - https://en.wikipedia.org/wiki/Pol.is
---

Type-shape: campaign (connective). Claim surface is edges (lead_orgs, strategies, body cross-refs) and hard specifics (dates, counts, names, outcomes). Significance/framing prose (§ Significance, goals-scalar operating-premise framing, whitepaper characterisation) is interpretation, not claim — skipped per AUDITOR.md § Type-shape.

## Claim 1: edge lead_orgs → org-collective-intelligence-project (CIP leads Alignment Assemblies)

Source: https://www.cip.org/alignmentassemblies + https://moda.gov.tw/en/press/press-releases/5243
Source tier: primary
Source content: CIP's own program page presents the Alignment Assemblies roadmap (v0–v4); MODA press release: ministry "has become an official partner of the international non-governmental organization, the 'Collective Intelligence Project' (CIP)".
Comparison: Edge resolves to existing entity file; two independent primary parties confirm CIP runs the program.
Decision: corroborated

## Claim 2: edge strategies → strat-participatory-deliberation-as-policy-input

Source: https://www.cip.org/alignmentassemblies + https://moda.gov.tw/en/press/press-releases/5243
Source tier: primary
Source content: CIP page describes "state-of-the-art wikisurvey tools" and "adapting the vTaiwan process" to feed public deliberation into partner decisions; MODA: partnership aims at "building consensus among the public regarding the needs and risks associated with AI".
Comparison: Edge resolves to existing strategy entity ("Participatory deliberation as policy input on AI"); the campaign is a direct instance per both parties' own descriptions.
Decision: corroborated

## Claim 3: "launched Alignment Assemblies in February 2023" (body; start_date: 2023-02)

Source: https://www.cip.org/blog/alignment-assemblies-nine-months-in
Source tier: primary
Source content: Launch date stated as February 2023 in CIP's nine-months-in blog.
Comparison: Body and start_date match CIP's own launch dating.
Decision: primary-sourced

## Claim 4: scalar:outcomes — "February 2023: Alignment Assemblies launched with v0 at the US Summit for Democracy"

Source: https://www.cip.org/alignmentassemblies
Source tier: primary
Source content: CIP roadmap: "v0: Summit for Democracy (March 2023)".
Comparison: The scalar dates the v0-at-Summit event to February 2023; CIP's own roadmap dates v0 to March 2023 (the 2023 Summit for Democracy ran in late March), and the entity's own body correctly says "The first assembly (v0), in March 2023". The program *launch* was February 2023 (Claim 3) but the v0 assembly was March. Fix location: frontmatter `outcomes` scalar, token "February 2023" on the v0 event → "March 2023" (launch-in-February may stand as a separate clause).
Decision: correction

## Claim 5: v0 addressed global policymakers' views on generative AI's impact on democracy, at the US Summit for Democracy

Source: https://www.cip.org/alignmentassemblies
Source tier: primary
Source content: "v0: Summit for Democracy (March 2023) — What do global policymakers think about the impact of generative AI on democracy?"
Comparison: Body/outcomes focus statement matches CIP's own roadmap description.
Decision: primary-sourced

## Claim 6: v0 was covered in the New York Times

Source: https://www.cip.org (CIP's own site text, surfaced via search)
Source tier: primary
Source content: CIP text: the pilot "surfaced broad opinions from a wide set of participants, pulled from the White House's Summit for Democracy, on the relationship between generative AI and the future of democracy" and the work "was reported on in the New York Times."
Comparison: CIP's own statement of NYT coverage; the NYT piece itself was not independently located this session.
Decision: primary-sourced

## Claim 7: v1 (June 2023, OpenAI) engaged ~1,000 demographically representative Americans over two weeks via the AllOurIdeas wikisurvey

Source: https://www.cip.org/research/participatory-ai-risk-prioritization + https://democracy-technologies.org/participation/can-alignment-assemblies-bring-democracy-to-silicon-valley/
Source tier: primary
Source content: CIP report: "Approximately 1,000 demographically representative Americans participated over two weeks in June 2023" on "the AllOurIdeas wiki-survey platform"; Democracy Technologies independently: ~1,000 Americans over a two-week period in June 2023 on AllOurIdeas, with OpenAI as "committed audience".
Comparison: All tokens (count, representativeness, duration, month, platform, partner) match across two independent canonical sources.
Decision: corroborated

## Claim 8: v1 participants ranked statements completing "When it comes to making AI safe for the public, I want to make sure…"

Source: https://www.cip.org/research/participatory-ai-risk-prioritization
Source tier: primary
Source content: "Participants ranked statements completing: 'When it comes to making AI safe for the public, I want to make sure...'"
Comparison: Verbatim match.
Decision: primary-sourced

## Claim 9: v1 top-ranked categories were oversight, understanding, governance; overbearing-regulation concern ranked lowest; highest-ranked statement concerned overreliance on AI systems neither public nor researchers fully understand

Source: https://www.cip.org/research/participatory-ai-risk-prioritization
Source tier: primary
Source content: "oversight, understanding, and governance ranked highest," "overbearing regulation ranked lowest," "The top-ranked statement was avoiding overreliance on AI systems that people, and researchers, do not fully understand."
Comparison: Body and outcomes match the report's findings.
Decision: primary-sourced

## Claim 10: OpenAI committed to use findings to inform model evaluations, release criteria, and broader standards-setting processes

Source: https://www.cip.org/research/participatory-ai-risk-prioritization
Source tier: primary
Source content: "The outcomes of this process will be used to inform model evaluations and release criteria, standards-setting processes, and AI regulation"; OpenAI agreed to be a "committed audience: to participate in our roundtable, and to consider and respond to the outcomes of this report."
Comparison: Matches CIP's report language on intended use of outcomes.
Decision: primary-sourced

## Claim 11: six participants joined a follow-up roundtable with OpenAI representatives

Source: https://www.cip.org/research/participatory-ai-risk-prioritization
Source tier: primary
Source content: "Six participants attended a follow-up roundtable with OpenAI to discuss concerns."
Comparison: Count and event match.
Decision: primary-sourced

## Claim 12: Taiwan MODA partnership announced May 25, 2023; the ministry then led by Audrey Tang

Source: https://moda.gov.tw/en/press/press-releases/5243 + https://2024.cip.org/
Source tier: primary
Source content: MODA: ministry "announced that...it has become an official partner of...the 'Collective Intelligence Project' (CIP) today (25th)" (release dated May 25, 2023); CIP 2024 report attributes the Taiwan work to "Taiwan's Ministry of Digital Affairs under Audrey Tang's leadership". Tang's tenure as Minister of Digital Affairs (2022–2024) is an official-office fact; edge person-audrey-tang resolves.
Comparison: Date and leadership both confirmed by two independent primary parties.
Decision: corroborated

## Claim 13: v2 Ideathons titled "Democratizing AI Futures" launched July 2023; deliberative workshops ran August 2023 examining copyright, bias, fair use, and societal impacts

Source: https://moda.gov.tw/en/press/press-releases/5243 + https://www.cip.org/alignmentassemblies
Source tier: primary
Source content: MODA: ministry planned to "launch the 'Democratizing AI Futures' dialogue through Ideathons" in July 2023 with deliberative workshops scheduled August 2023; CIP roadmap: "v2: Democratizing AI Futures (July 2023) — Taiwan's governmental policy response to generative AI, covering copyright, bias, fair use, and societal impacts".
Comparison: Title, dates, and topic list match across the two primary parties (MODA's own topic phrasing is "algorithms, intellectual property, technological ethics, public services, and social impact"; the entity's topic list matches CIP's phrasing).
Decision: corroborated

## Claim 14: v2 findings integrated into Taiwan policy recommendations

Source: https://moda.gov.tw/en/press/press-releases/5243
Source tier: primary
Source content: MODA (prospective, May 2023): partnership aims to "ensure the alignment of AI applications with the interests of the general public" and build public consensus; workshops "scheduled for August 2023".
Comparison: Sources fetched this session state intent before the fact; no post-hoc source confirming the findings were integrated into Taiwan's policy recommendations was found. Not a finding of error — an integration-outcome claim resting on prospective sources.
Decision: uncorroborated

## Claim 15: v3 (October 2023, Anthropic) convened ~1,000 representative Americans via the Polis platform

Source: https://www.anthropic.com/research/collective-constitutional-ai-aligning-a-language-model-with-public-input + https://www.cip.org/alignmentassemblies
Source tier: primary
Source content: Anthropic: "Approximately 1,000 Americans participated," "We sought a representative sample of U.S. adults across age, gender, income, and geography," Polis platform hosted the deliberation; CIP roadmap: "v3: Collective Constitutional AI (October 2023)".
Comparison: Count, representativeness, platform, date, and partner match across the two collaborating parties' independent pages.
Decision: corroborated

## Claim 16: the deliberation produced "a 275-statement constitution" (body; scalar:outcomes; scalar:sources[3].note)

Source: https://www.anthropic.com/research/collective-constitutional-ai-aligning-a-language-model-with-public-input + https://arxiv.org/html/2406.07814v1 + https://democracy-technologies.org/participation/can-alignment-assemblies-bring-democracy-to-silicon-valley/
Source tier: primary
Source content: Anthropic: "After moderation, we had 275 public statements, far more than the 58 principles in the Standard constitution" and "we combined statements that conveyed similar ideas in order to again preserve a similar length and number of distinct values as in the Standard constitution"; the paper: "We disaggregated the publicly submitted statements into distinct ideas and took the top statements by GAC up to 95 different ideas"; Democracy Technologies: CIP "trained a Claude bot on 75 principles derived from public input".
Comparison: 275 was the moderated statement *pool*, which was deduplicated and consolidated into a final public constitution of roughly the Standard constitution's size (~58–95 range; 75 per Democracy Technologies, and the entity's own sources[5].note says 75) — the constitution itself was not 275 statements. Appears in body § v2 and v3, scalar `outcomes`, and scalar `sources[3].note`; fix requires prose judgment (e.g. "a constitution distilled from 275 moderated public statements").
Decision: correction

## Claim 17: Anthropic trained a model on the public constitution and published the results as joint CIP–Anthropic research

Source: https://www.anthropic.com/research/collective-constitutional-ai-aligning-a-language-model-with-public-input + https://democracy-technologies.org/participation/can-alignment-assemblies-bring-democracy-to-silicon-valley/
Source tier: primary
Source content: Anthropic: "Anthropic trained two Claude Instant-sized models—one using the publicly sourced constitution ('Public' model) and one using Anthropic's constitution ('Standard' model)"; the research is published jointly with CIP (paper: Anthropic + Collective Intelligence Project authors); Democracy Technologies independently reports the trained bot.
Comparison: Training and joint publication confirmed by two independent sources.
Decision: corroborated

## Claim 18: quote — "one of the first instances in which members of the public have collectively directed the behavior of a language model via an online deliberation process"

Source: https://www.anthropic.com/research/collective-constitutional-ai-aligning-a-language-model-with-public-input
Source tier: primary
Source content: "We believe that our work may be one of the first instances in which members of the public have collectively directed the behavior of a language model via an online deliberation process."
Comparison: The quoted span is verbatim in-source. Note: the source hedges ("we believe... may be"); the body's introduction ("describes the project as") drops the hedge but the quotation itself is accurate.
Decision: primary-sourced

## Claim 19: Anthropic's in-house constitution is a 58-principle document

Source: https://www.anthropic.com/research/collective-constitutional-ai-aligning-a-language-model-with-public-input
Source tier: primary
Source content: "the 58 principles in the Standard constitution".
Comparison: Token matches.
Decision: primary-sourced

## Claim 20: the public constitution "placed notably greater weight on avoiding paternalism, protecting privacy, and providing balanced perspectives on contested topics" (body; scalar:outcomes; scalar:sources[3].note)

Source: https://www.anthropic.com/research/collective-constitutional-ai-aligning-a-language-model-with-public-input + https://arxiv.org/html/2406.07814v1
Source tier: primary
Source content: Anthropic page: differences are that public principles "appear to largely be self-generated and not sourced from existing publications, they focus more on objectivity and impartiality, they place a greater emphasis on accessibility" and "tend to promote desired behavior rather than avoid undesired behavior"; the paper: "One of the greatest differences is the Public constitution's focus on objectivity and impartiality"; the paper does not mention paternalism, and privacy appears as a *shared* element ("Both constitutions included principles around privacy and human rights"), not a public-constitution distinctive.
Comparison: One of the three claimed distinctives (balanced perspectives) is confirmed; "avoiding paternalism" appears in neither the cited Anthropic page nor the paper, and "protecting privacy" is described as common to both constitutions rather than a difference. The cited source contradicts two of the three tokens. Appears in body § v2 and v3, scalar `outcomes`, and scalar `sources[3].note`; fix requires prose judgment (source-given replacement list: self-generation, objectivity/impartiality, accessibility, promoting desired over avoiding undesired behavior).
Decision: correction

## Claim 21: v4 (October 2023) with the Creative Commons Foundation addressed AI training use of CC-licensed materials

Source: https://www.cip.org/alignmentassemblies
Source tier: primary
Source content: "v4: Creative Commons (October 2023) — How should Creative Commons respond to the use of CC-licensed work in AI training?"
Comparison: Date, partner, and topic match the CIP roadmap.
Decision: primary-sourced

## Claim 22: scalar:outcomes — "engagement with the UK Frontier AI Taskforce as a committed government audience"

Source: https://www.cip.org/blog/alignment-assemblies-nine-months-in
Source tier: primary
Source content: The blog lists six collaborators: "UK Frontier AI Taskforce, OpenAI, Anthropic, US Summit for Democracy, Taiwan Ministry of Digital Affairs, Creative Commons Foundation."
Comparison: The UK Frontier AI Taskforce is confirmed among CIP's committed-audience partners.
Decision: primary-sourced

## Claim 23: body — "By mid-2025 the programme had run assemblies with OpenAI, Anthropic, Taiwan's Ministry of Digital Affairs, the UK Frontier AI Taskforce, and the Creative Commons Foundation"

Source: https://www.cip.org/alignmentassemblies + https://www.cip.org/blog/alignment-assemblies-nine-months-in
Source tier: primary
Source content: The roadmap's versioned assemblies are v0 Summit for Democracy, v1 OpenAI, v2 Taiwan MODA, v3 Anthropic, v4 Creative Commons; the UK Frontier AI Taskforce appears only as a listed committed-audience partner, with no versioned assembly.
Comparison: Four of the five named partners had assemblies run; no source found showing an assembly *run with* the UK Frontier AI Taskforce (the entity's own frontmatter says "engagement", the weaker form). Too strong to pass as stated, not a token error.
Decision: uncorroborated

## Claim 24: body edges — org-g0v and camp-g0v-vtaiwan-participatory-platform-governance-2015-ongoing as the methodological precedent CIP carries forward

Source: https://www.cip.org/alignmentassemblies + https://compdemocracy.org/case-studies/2014-vtaiwan/
Source tier: primary
Source content: CIP page references "adapting the vTaiwan process"; Computational Democracy Project case study: after the 2014 Sunflower Movement "the government of Taiwan requested that the g0v civic tech community create a scalable listening process... The resulting... process became known as vTaiwan."
Comparison: Both edges resolve to existing entity files; the vTaiwan/g0v-precedent link is CIP's own stated lineage.
Decision: primary-sourced

## Claim 25: body — "the vTaiwan and g0v methodological tradition from which the Polis tool — the consensus-mapping platform CIP uses in its most complex assemblies — descends"

Source: https://en.wikipedia.org/wiki/Pol.is + https://compdemocracy.org/case-studies/2014-vtaiwan/
Source tier: primary
Source content: Polis was co-founded by Colin Megill, Christopher Small, and Michael Bjorkegren in Seattle around 2012, after Occupy Wall Street and the Arab Spring; vTaiwan (post-2014 Sunflower Movement) then adopted it — "vTaiwan contains the longest running, national-scale implementation of Polis." The startup open-sourced the technology at the 2016 g0v summit.
Comparison: The provenance is reversed: Polis predates vTaiwan and was created independently in Seattle; the vTaiwan/g0v tradition *adopted* Polis (and hosted its open-sourcing), it did not produce it. Fix requires prose judgment (e.g. "the vTaiwan and g0v methodological tradition in which the Polis tool... found its flagship national-scale use").
Decision: correction

## Claim 26: "March 2024: nationwide US assembly on information integrity" (body; scalar:outcomes)

Source: https://2024.cip.org/
Source tier: primary
Source content: "Their nationwide Alignment Assembly on information integrity in March of 2024 showed how democratic processes could scale to address urgent challenges while preserving cultural context and local values" — where "their" refers to Taiwan's Ministry of Digital Affairs under Audrey Tang's leadership.
Comparison: The cited annual report attributes the March 2024 nationwide information-integrity assembly to Taiwan, not the United States. Token "US" → Taiwan, in body § Expanding infrastructure and scalar `outcomes` (the scalar's "nationwide US assembly" and the body's "nationwide US assembly... across a nationally diverse participant sample" both carry it).
Decision: correction

## Claim 27: Global Dialogues 2024 pilot engaged 1,200 participants across 68 countries in 8 languages on AI governance and values questions

Source: https://2024.cip.org/
Source tier: primary
Source content: "engaged 1,200 participants, in 68 countries and 8 languages, through forty questions."
Comparison: All three tokens match the annual report.
Decision: primary-sourced

## Claim 28: the pilot produced "the first systematic multinational public-opinion dataset specifically on AI governance"

Source: https://2024.cip.org/
Source tier: primary
Source content: The annual report describes the pilot and its findings but "does not explicitly characterize it as 'the first systematic multinational public-opinion dataset on AI governance.'"
Comparison: A "first"-superlative (contested-attribution class); no canonical source found asserting it. Not a finding of error.
Decision: uncorroborated

## Claim 29: Community Models 2024 cohort included the Grandmothers' Collective, ITS Rio, Equiano Institute, and Civis

Source: https://2024.cip.org/
Source tier: primary
Source content: Named Community Models partners: "Grandmothers' Collective, ITS RIO (Brazil), Equiano Institute (Africa), Civis (India), Youth Ki Awaaz (India), Second Life Project."
Comparison: All four named entities appear in the report's cohort; the entity's "among the 2024 cohort" correctly signals a non-exhaustive list.
Decision: primary-sourced

## Claim 30: 2025 Global Dialogues Index compiled from seven rounds of deliberation with over 6,000 people across 70 countries, structured as Usage/Trust/Perception indices, framed as "actionable signals for policymakers and developers" (also: end_date ongoing)

Source: https://www.cip.org/2025gdindex
Source tier: primary
Source content: "Seven rounds of deliberation," "over 6,000 participants across 70 countries," findings organized through Usage, Trust, and Perception, "actionable signals for policymakers and developers navigating decisions that will shape how AI enters economic and social life."
Comparison: All tokens match; 2025 activity also supports `end_date: ongoing` and `status: active`.
Decision: primary-sourced

## Claim 31: 58 percent of respondents trust AI chatbots more than their elected representatives

Source: https://www.cip.org/2025gdindex
Source tier: primary
Source content: "58% of people trust AI chatbots more than elected representatives."
Comparison: Token matches.
Decision: primary-sourced

## Claim 32: trust gap — AI chatbots 55 percent vs AI companies 34 percent (body)

Source: https://www.cip.org/2025gdindex
Source tier: primary
Source content: "55% of people trust AI chatbots while only about 34% trust AI companies."
Comparison: Both tokens match.
Decision: primary-sourced

## Claim 33: "75 percent of employees expect weekly AI use at work" (body; scalar:outcomes; scalar:sources[7].note)

Source: https://www.cip.org/2025gdindex
Source tier: primary
Source content: "75% of employees reported being expected to use AI at least weekly, with 44% now expected to use it daily."
Comparison: The number and cadence match, but the source says employees *are expected* (by employers) to use AI weekly, while the entity says employees *expect* weekly AI use — the subject of the expectation is inverted. A paraphrase-direction issue rather than a token error; flagged here for the record.
Decision: uncorroborated

## Claim 34: 44.5 percent report increased certainty about existing beliefs after AI interaction (body)

Source: https://www.cip.org/2025gdindex
Source tier: primary
Source content: "44.5% of people report feeling more certain about beliefs after interacting with AI while only 4.8% less certain."
Comparison: Token matches.
Decision: primary-sourced

## Claim 35: body — "AI reinforces certainty about existing beliefs more powerfully than social media"

Source: https://www.cip.org/2025gdindex
Source tier: primary
Source content: The index page fetched this session reports the 44.5%-vs-4.8% certainty finding without the social-media comparison.
Comparison: The comparative-to-social-media element was not found in the source consulted; the underlying figure passes as Claim 34. Not a finding of error.
Decision: uncorroborated

## Claim 36: the Global Dialogues dataset was released open-source for any party to build on

Source: https://globaldialogues.ai/methodology
Source tier: primary
Source content: "After every cadence, cleaned data and code required to replicate findings are released under an open-source license"; the dataset "will always be open-source for anyone to build on" (repo at github.com/collect-intel/global-dialogues).
Comparison: CIP's own methodology page confirms the open-source commitment.
Decision: primary-sourced

## Claim 37: Divya Siddarth quote — "Every time we run something, we get the most interesting, engaged, thoughtful responses, and we show it can be done"

Source: https://democracy-technologies.org/participation/can-alignment-assemblies-bring-democracy-to-silicon-valley/
Source tier: mainstream
Source content: "Every time we run something, we get the most interesting, engaged, thoughtful responses, and we show it can be done."
Comparison: Verbatim match in the cited article (specialist democracy-tech outlet, in-beat). Living-person quote on a single non-primary source.
Decision: single-source

## Claim 38: scalar:sources[5].note — "Saffron Huang framing of assemblies as 'pilots to show what is possible'"

Source: https://democracy-technologies.org/participation/can-alignment-assemblies-bring-democracy-to-silicon-valley/
Source tier: mainstream
Source content: The article's Saffron Huang quote is: "How can we create pilots that we can actually use to affect real change, leading to real outcomes and decisions?"
Comparison: The note's quoted phrase "pilots to show what is possible" was not found in the article; the actual Huang quote frames pilots around affecting real change. A paraphrase presented as a quotation in scalar `sources[5].note` — too paraphrastic to pass, not a single-token fix.
Decision: uncorroborated

## Claim 39: scalar:sources[5].note — "characterisation of the Anthropic assembly as identifying 75 public principles emphasising positive behaviours"

Source: https://democracy-technologies.org/participation/can-alignment-assemblies-bring-democracy-to-silicon-valley/
Source tier: mainstream
Source content: CIP "trained a Claude bot on 75 principles derived from public input"; "statements that attracted public support tended to promote positive behaviour, rather than trying to avoid negative behaviour."
Comparison: The note accurately reports the article's content (and this 75-principle figure is part of the evidence behind Claim 16's correction).
Decision: single-source

## Claim 40: scalar:sources[0].note — the overview page is "primary source for... the full list of committed audiences (UK Frontier AI Taskforce, OpenAI, Anthropic, US Summit for Democracy, Taiwan Ministry of Digital Affairs, Creative Commons Foundation)"

Source: https://www.cip.org/alignmentassemblies
Source tier: primary
Source content: The overview page as fetched this session lists "The GovLab, OpenAI, Anthropic, Creative Commons Foundation, and Taiwan's Ministry of Digital Affairs"; "The UK Frontier AI Taskforce is not mentioned."
Comparison: The full six-partner list (including the UK taskforce) currently lives on the nine-months-in blog, not the overview page the note attributes it to. The page may have changed since last_checked 2026-06-08, so this is recorded as unconfirmed rather than error; fix location if acted on: scalar `sources[0].note`.
Decision: uncorroborated

## Claim 41: v1 findings "inverted what AI-industry conversations might have predicted" — participant-generated insights rivaled/exceeded expert seed statements (scalar:sources[1].note)

Source: https://www.cip.org/blog/alignment-assemblies-nine-months-in
Source tier: primary
Source content: "the top 5 most popular statements at the end were produced by participants" (despite more seed statements than public inputs being provided); "people are able and willing to have nuanced, complex conversations about AI—and are, in fact, generally far less divided than policymakers seem to be."
Comparison: The note's participant-insights-rivaled-experts claim matches the blog's stated lesson.
Decision: primary-sourced
