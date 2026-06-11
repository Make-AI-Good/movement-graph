---
entity_id: lg-ai-safety-india
entity_hash: 7068a0ab53ae23cb11d00d57b08b20dc3a7c5c62
audit_date: 2026-06-11
pass: 1
status: corrections-pending
claims_total: 23
claims_corroborated: 2
claims_primary_sourced: 12
claims_single_source: 2
claims_uncorroborated: 5
open_corrections: 2
sources_consulted:
  - https://aisafetyindia.com/
  - https://aisafetyindia.com/about
  - https://aisafetyindia.com/fundamentals-of-safe-ai
  - https://forum.effectivealtruism.org/posts/DYbxFGaFvhnBrQAoD/applications-open-ai-safety-india-phase-1-fundamentals-of
  - https://rajsecrets.medium.com/storyfounding-ai-safety-india-1-18c836842c55
  - https://aisafety.com/communities
  - http://web.archive.org/web/20260124092340/https://aisafetyindia.com/about
  - http://web.archive.org/web/20250514023525/https://aisafetyindia.com/
---

## Claim 1: mission is to "bring together students, researchers to work on the most important challenge of our time — aligning advanced AI systems with human values"

Source: https://aisafetyindia.com/about + https://aisafety.com/communities
Source tier: primary
Source content: About page: "We bring together students, researchers to work on the most important challenge of our time — aligning advanced AI systems with human values." Directory: "Bringing together students and researchers to work on aligning advanced AI systems with human values."
Comparison: Verbatim match on the entity's own About page; independently paraphrase-confirmed by the aisafety.com communities directory.
Decision: corroborated

## Claim 2: "Founded in 2025" (also frontmatter `founded: 2025`)

Source: https://forum.effectivealtruism.org/posts/DYbxFGaFvhnBrQAoD/applications-open-ai-safety-india-phase-1-fundamentals-of + Internet Archive CDX for aisafetyindia.com
Source tier: primary
Source content: EA Forum launch post by Aditya Raj dated April 28, 2025 opens applications for the inaugural Phase 1 cohort; Wayback Machine's first captures of aisafetyindia.com date from April 1, 2025.
Comparison: The entity's own 2025 launch announcement plus independent Internet Archive capture history both place the group's start in 2025.
Decision: corroborated

## Claim 3: "led by Aditya Prasad (Founder), Aditya Raj (Partnerships Lead), and Sireesha Chavali (Advisor)"

Source: https://aisafetyindia.com/about (live, confirmed identical in the 2026-01-24 Wayback snapshot) + https://rajsecrets.medium.com/storyfounding-ai-safety-india-1-18c836842c55
Source tier: primary
Source content: The About page's Team section is an absolutely-positioned grid; pairing by layout coordinates: "Aditya Raj" (top 639, left 109) sits directly above "Founder" (top 684, left 109); "Sireesha Chavali" (top 638, left 721) sits directly above "Partnerships Lead" (top 684, left 721); "Aditya Prasad" (top 1384, left 721) and "Evander Hammer" (top 1382, left 103) sit below the "Advisors" heading (top 850). The 2026-01-24 Wayback snapshot (predating the entity's 2026-06-03 draft) carries identical coordinates, so the page has not changed. The Medium founding story corroborates: Aditya Raj describes deciding to start the initiative, consulting field builders, and "As i am in to Designing, so i just put a website."
Comparison: The body rotates all three role assignments. Correct assignment: Aditya Raj is Founder; Sireesha Chavali is Partnerships Lead; Aditya Prasad is an Advisor (alongside Evander Hammer). The error pattern matches a misreading of the page's scrambled DOM order (the grid renders names and role labels in non-adjacent document order). Fix location: body lede sentence "led by Aditya Prasad (Founder), Aditya Raj (Partnerships Lead), and Sireesha Chavali (Advisor)" — each parenthetical role token has a single correct replacement per the list above.
Decision: correction

## Claim 4: scalar:sources[1].note — "lists team as Aditya Prasad (Founder), Aditya Raj (Partnerships Lead), Sireesha Chavali (Advisor)"

Source: https://aisafetyindia.com/about (live + 2026-01-24 Wayback snapshot)
Source tier: primary
Source content: Same coordinate-paired evidence as Claim 3: Aditya Raj + "Founder" (left 109), Sireesha Chavali + "Partnerships Lead" (left 721), Aditya Prasad under "Advisors".
Comparison: Same rotation error in the frontmatter scalar. Fix location: scalar sources[1].note — correct list is Aditya Raj (Founder), Sireesha Chavali (Partnerships Lead), Aditya Prasad (Advisor). Note this scalar correction sits in frontmatter prose, which is outside the Editor's plain body-backfill pipe per mission routing.
Decision: correction

## Claim 5: the programme is a three-phase pipeline, Phase 1 "Fundamentals of Safe AI", Phase 2 "Research Fellowship"

Source: https://aisafetyindia.com/about + https://aisafetyindia.com/fundamentals-of-safe-ai
Source tier: primary
Source content: About page: "3 Phase Program to get started from Basics to advanced AI Safety." Fundamentals page: "This Fundamentals program (Phase 1) is designed as the primary launchpad for our intensive **Phase 2: AI Safety Research Fellowship**."
Comparison: Three-phase structure and the names of Phases 1 and 2 are confirmed on the entity's own site (Phase 2's full name is "AI Safety Research Fellowship"; body's "Research Fellowship" is a fair short form).
Decision: primary-sourced

## Claim 6: Phase 3 is named "Research Paper" and advances participants "through to a completed publication"

Source: no canonical source found
Source tier: none
Source content: The live homepage names only "Fundamentals of Safe AI" plus an "AI Safety Hackathon (November)" and "More workshops and reading sessions soon"; the fundamentals page names Phase 2 but no Phase 3; the EA Forum post "focuses entirely on this initial offering without mentioning any subsequent phases"; the Medium story "does not describe a three-phase programme structure."
Comparison: No fetched source names Phase 3 "Research Paper" or describes a completed-publication outcome; no source contradicts it either (the About page confirms three phases exist). Affects the body lede pipeline listing and the "Phase 3 — Research Paper" paragraph.
Decision: uncorroborated

## Claim 7: scalar:sources[0].note — homepage is "entry point for the three-phase programme pipeline (Fundamentals of Safe AI → Research Fellowship → Research Paper)"

Source: https://aisafetyindia.com/
Source tier: primary
Source content: Homepage confirms "Free Courses & Research" and "Fundamentals of Safe AI: Free AI Safety Course"; it does not present a named three-phase pipeline ending in "Research Paper".
Comparison: The free-courses portion of the scalar is supported, but the pipeline naming (specifically the "Research Paper" phase) is not on the page; partial support means the scalar as stated cannot be confirmed.
Decision: uncorroborated

## Claim 8: "India's first structured AI-safety cohort programme"

Source: https://rajsecrets.medium.com/storyfounding-ai-safety-india-1-18c836842c55
Source tier: primary
Source content: "there are so many people in AI Safety from India, but nothing significant is happening for India"
Comparison: A contested "first" claim supported only by the founder's own gap framing; no independent source establishes priority over other India offerings. Per the source rule, contested "first" attributions are judgment-loaded.
Decision: uncorroborated

## Claim 9: founding-motivation quote "there are so many people in AI Safety from India, but nothing significant is happening for India"

Source: https://rajsecrets.medium.com/storyfounding-ai-safety-india-1-18c836842c55
Source tier: primary
Source content: "there are so many people in AI Safety from India, but nothing significant is happening for India"
Comparison: Verbatim match in the cited founding story.
Decision: primary-sourced

## Claim 10: Raj consulted 40+ field builders before launch, built the website using his design background, and produced a vision document

Source: https://rajsecrets.medium.com/storyfounding-ai-safety-india-1-18c836842c55
Source tier: primary
Source content: Over 40 people consulted for feedback before launch; "As i am in to Designing, so i just put a website"; created "a doc for envisioning How AI Safety India should look like."
Comparison: All three tokens match the founding story.
Decision: primary-sourced

## Claim 11: "operates nationally and primarily online, with no single city base" (also frontmatter `location`)

Source: https://aisafetyindia.com/fundamentals-of-safe-ai + https://aisafetyindia.com/about
Source tier: primary
Source content: "This Phase 1 program is conducted entirely online, allowing participation from anywhere globally." About page address line: "India" (no city).
Comparison: Online-first national operation matches the entity's own pages; no city base is listed anywhere on the site.
Decision: primary-sourced

## Claim 12: "Supporting and collaborating organisations include ARENA, EA Hungary, ENAIS, Stanford Center for AI Safety, AI Safety Asia, and AI Plans"

Source: https://aisafetyindia.com/about
Source tier: primary
Source content: A "Special Thanks ✨" section headed "Your Feedbacks shaped this Initiative" lists individuals: "James Hindmarch (ARENA)", "Lili (EA Hungary + Scaling Altruism)", "Gergo Gaspar (ENAIS + AI Safety Collab)", "Mansur Maturidi Arief (Stanford Center for AI Safety)", "Edward (AI Safety Asia)", "Kabir (AI Plans)".
Comparison: All six organisation names appear, but as affiliations of individually thanked feedback-givers, not as organisational supporters or collaborators; the body's "supporting and collaborating organisations" (and sources[1].note's "supporting organisations") characterizes a relationship the page does not state. Too paraphrastic to confirm as stated.
Decision: uncorroborated

## Claim 13: Phase 1 is a 10-week free online cohort, 6–10 hours weekly, covering foundations (alignment, risks, ethics, governance) and technical topics (interpretability, robustness) with hands-on projects, modelled after BlueDot and Atlas

Source: https://forum.effectivealtruism.org/posts/DYbxFGaFvhnBrQAoD/applications-open-ai-safety-india-phase-1-fundamentals-of
Source tier: primary
Source content: "free, 10-week online program (8 weeks learning + 2 weeks project)"; "Dedicate 6–10 hours/week (and more during the project phase)"; foundations of "AI Safety (alignment, risks, ethics, governance)" plus "Technical introductions to Interpretability, Robustness"; inspired by "top global programs (e.g., BlueDot, Atlas)".
Comparison: Every token matches the entity's own launch post.
Decision: primary-sourced

## Claim 14: "Sessions run in small groups of 5–10 participants"

Source: https://forum.effectivealtruism.org/posts/DYbxFGaFvhnBrQAoD/applications-open-ai-safety-india-phase-1-fundamentals-of
Source tier: primary
Source content: "Small-group online sessions (5–10 people)"
Comparison: Match.
Decision: primary-sourced

## Claim 15: inaugural cohort opened applications April 28, 2025, received 100+ applications, accepted ~40, and ran June through mid-August 2025

Source: https://forum.effectivealtruism.org/posts/DYbxFGaFvhnBrQAoD/applications-open-ai-safety-india-phase-1-fundamentals-of + https://rajsecrets.medium.com/storyfounding-ai-safety-india-1-18c836842c55
Source tier: primary
Source content: EA Forum post dated April 28, 2025; programme "Tentatively June 1st – Mid-August 2025"; Medium story: 100+ applications received, 40 participants selected, first cohort completed.
Comparison: Dates and numbers match the entity's own launch post and founding story ("approximately 40" against the story's "40" is a fair hedge).
Decision: primary-sourced

## Claim 16: Phase 1 is "designed for students and early-career professionals with basic Python knowledge but no prior AI-safety background"

Source: https://forum.effectivealtruism.org/posts/DYbxFGaFvhnBrQAoD/applications-open-ai-safety-india-phase-1-fundamentals-of
Source tier: primary
Source content: Aimed at "Students," "Engineers and developers," "Researchers and early professionals"; "No previous experience in AI Safety is needed!"; basic Python helpful for projects.
Comparison: Audience, Python prerequisite, and no-prior-background tokens match.
Decision: primary-sourced

## Claim 17: scalar:sources[0].note — tagline "Tackling AI Risks to Save Humanity"; free courses and research opportunities

Source: https://aisafetyindia.com/
Source tier: primary
Source content: "Made with ❤️ in India | Tackling AI Risks to Save Humanity"; "Free Courses & Research"
Comparison: Tagline verbatim; free courses and research confirmed on the homepage.
Decision: primary-sourced

## Claim 18: scalar:sources[2].note — EA Forum post by Aditya Raj (April 28, 2025); deadline May 10, 2025; programme June 1 – mid-August 2025; 6–10 hours weekly; groups of 5–10

Source: https://forum.effectivealtruism.org/posts/DYbxFGaFvhnBrQAoD/applications-open-ai-safety-india-phase-1-fundamentals-of
Source tier: primary
Source content: Author "Aditya Raj - AI Safety India Community, April 28, 2025"; deadline "May 10th, 2025"; "Tentatively June 1st – Mid-August 2025"; "6–10 hours/week"; "Small-group online sessions (5–10 people)".
Comparison: All scalar tokens match the post.
Decision: primary-sourced

## Claim 19: scalar:sources[3].note — Medium founding story by Aditya Raj published February 2, 2026; first in a multi-part series

Source: https://rajsecrets.medium.com/storyfounding-ai-safety-india-1-18c836842c55
Source tier: primary
Source content: Author Aditya Raj, February 2, 2026; titled "Story of Founding AI Safety India — 1" with a closing promise of further posts.
Comparison: Author, date, and series position match.
Decision: primary-sourced

## Claim 20: SAAR (Safety & Alignment Research India) is a Discord community rated "Very Active" on aisafety.com, a peer space for Indian alignment researchers and newcomers

Source: https://aisafety.com/communities
Source tier: database
Source content: "Safety & Alignment Research India" listed "Very active", platforms "Discord, Local"; "Space for Indian AI safety researchers, new entrants, and relevant stakeholders to collaborate on technical aspects of research and support each other."
Comparison: Rating, platform, and characterization match the directory entry (body and sources[4].note both supported); single canonical directory source.
Decision: single-source

## Claim 21: scalar:sources[4].note — aisafety.com lists AI Safety India as "Active" with description "Bringing together students and researchers to work on aligning advanced AI systems with human values", platform Local

Source: https://aisafety.com/communities
Source tier: database
Source content: "AI Safety India" listed with status "Active", platform "Local", description "Bringing together students and researchers to work on aligning advanced AI systems with human values."
Comparison: Status, platform, and description match; single canonical directory source.
Decision: single-source

## Claim 22: "the corpus's first entry covering the AI-safety community-building layer in South Asia"

Source: the corpus itself (product/entities/local-groups/, created-date frontmatter)
Source tier: primary
Source content: lg-ai-safety-india (created 2026-06-03) is the only India/South Asia local-group entity; no earlier South Asia entry exists in the local-groups layer.
Comparison: Corpus-internal claim verified directly against the corpus, which is the authoritative record for claims about itself.
Decision: primary-sourced

## Claim 23: "Berlin and Tokyo are built around regular monthly meetup-and-talk formats"

Source: no canonical source fetched this session
Source tier: none
Source content: Not checked against external canonical sources in this session (the claim concerns two other entities' programme formats).
Comparison: A factual claim about peer groups used for contrast; consistent with the corpus's own Berlin/Tokyo entries but not verified against canonical sources within this entity's audit scope. No contradiction found.
Decision: uncorroborated
