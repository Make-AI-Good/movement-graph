---
entity_id: lg-baish
entity_hash: 91195279d54c3cd99fe2413357d4d95889d09ca3
audit_date: 2026-06-11
pass: 1
status: corrections-pending
claims_total: 31
claims_corroborated: 6
claims_primary_sourced: 15
claims_single_source: 2
claims_uncorroborated: 7
open_corrections: 1
sources_consulted:
  - https://www.baish.com.ar/en
  - https://www.baish.com.ar/en/about
  - https://www.baish.com.ar/en/research
  - https://eitan-sprejer.github.io/
  - https://lvca.dev/about
  - https://aisafety.com/communities
  - https://apartresearch.com/sprints/global-south-ais-hackathon-2026-06-19-to-2026-06-21
  - https://safetytalent.org/org/baish/apply/ps7f9f08q1b8bmb90zfavg9hv584jzzn
  - https://forum.effectivealtruism.org/posts/DnqFsjiKW4ooC3DK4/lanais-latin-american-network-for-ai-safety-kick-off
  - https://arxiv.org/abs/2510.13912
  - https://bicyt.conicet.gov.ar/fichas/produccion/en/12709154
  - https://neurips.cc/virtual/2025/loc/san-diego/128037
---

## Claim 1: scalar:founded + body "Founded in 2024"

Source: https://lvca.dev/about
Source tier: primary
Source content: "In 2024 I cofounded BAISH, the Buenos Aires AI Safety Hub"
Comparison: Co-founder's own site states the 2024 founding year; scalar path is `founded`. One primary source.
Decision: primary-sourced

## Claim 2: "BAISH was co-founded in 2024 by Eitan Sprejer and Luca De Leo"

Source: https://eitan-sprejer.github.io/ ; https://lvca.dev/about
Source tier: primary
Source content: Sprejer: "Founding Director of BAISH (Buenos Aires AI Safety Hub)" / "I founded BAISH from scratch". De Leo: "In 2024 I cofounded BAISH".
Comparison: Both named co-founders attest the co-founding on their own sites.
Decision: corroborated

## Claim 3: scalar:location + body "based principally at the Facultad de Exactas y Naturales of the Universidad de Buenos Aires (UBA)"

Source: https://safetytalent.org/org/baish/apply/ps7f9f08q1b8bmb90zfavg9hv584jzzn
Source tier: database
Source content: Venue: "Facultad de Exactas y Naturales, UBA" in Buenos Aires
Comparison: Scalar path is `location`. Venue confirmed by the SafetyTalent course listing; the BAISH main/About pages as fetched this pass did not name the venue. One non-primary canonical source.
Decision: single-source

## Claim 4: "Argentina's first AI-safety community organisation"

Source: https://eitan-sprejer.github.io/ (via search-result snippet)
Source tier: primary
Source content: "BAISH is the first AI Safety community in Buenos Aires"
Comparison: The closest source statement claims first in *Buenos Aires*, not first in *Argentina*. "First" claims are contested-type; the broader Argentina-wide claim was not found in any canonical source this pass.
Decision: uncorroborated

## Claim 5: scalar:sources[0].note + body — "120+ community members, 3 weekly programs, 3+ published papers"; Telegram 190+ members; WhatsApp 140+ members

Source: https://www.baish.com.ar/en
Source tier: primary
Source content: "Overall community members: 120+; AI Safety Argentina Telegram: 190+ members; BAISH Community WhatsApp: 140+ members"; three programs listed; "Published papers: 3+ papers"
Comparison: All counts on BAISH's own site match the scalar note and the body's mid-2026 figures. Scalar path is `sources[0].note`.
Decision: primary-sourced

## Claim 6: "The AISafety.com global communities directory rates BAISH 'Very Active'" + scalar:sources[4].note description quote and platforms

Source: https://aisafety.com/communities
Source tier: database
Source content: "Activity Level: Very active. Description: 'Supporting students in entering the AI safety field and conducting research, including through regular discussion groups, reading clubs, and courses.' Platforms: Local, Telegram"
Comparison: The claim is about what the directory says, confirmed against the directory itself; description verbatim, platforms match. Scalar path is `sources[4].note`. One database-tier source.
Decision: single-source

## Claim 7: "a seven-person organising team its founding director describes as 'almost self-running'"

Source: https://eitan-sprejer.github.io/
Source tier: primary
Source content: "I founded BAISH from scratch and built it into an almost self-running organization with a 7-person organizing team."
Comparison: Quote verified verbatim ("almost" confirmed present by targeted re-fetch); team size matches.
Decision: primary-sourced

## Claim 8: Sprejer is Founding Director and "a full-time AI-safety researcher" (AISAR Scholarship, Apart Lab Fellowship per scalar:sources[1].note)

Source: https://eitan-sprejer.github.io/ ; https://www.baish.com.ar/en/about
Source tier: primary
Source content: Sprejer site: "Founding Director of BAISH". BAISH About: "Eitan Sprejer: Full-time AI Safety researcher (AISAR Scholarships and Apart Lab Fellowship)"
Comparison: Role and researcher status confirmed by two sources; AISAR/Apart Lab credentials match `sources[1].note`.
Decision: corroborated

## Claim 9: Sprejer "holds a MARS Fellowship at the Cambridge AI Safety Hub, serves as a course facilitator for BlueDot Impact"

Source: https://eitan-sprejer.github.io/
Source tier: primary
Source content: "MARS Fellow at Cambridge AI Safety Hub"; "Course Facilitator at BlueDot Impact: 'Facilitating 2 Technical AI Safety Projects cohorts'"
Comparison: Both roles match his own site. One primary source.
Decision: primary-sourced

## Claim 10: Sprejer "co-founded LANAIS (Latin American Network for AI Safety)"

Source: https://eitan-sprejer.github.io/ ; https://forum.effectivealtruism.org/posts/DnqFsjiKW4ooC3DK4/lanais-latin-american-network-for-ai-safety-kick-off
Source tier: primary
Source content: Sprejer site: "Co-founder of LANAIS (Latin American Network for AI Safety)". EA Forum kick-off post lists a co-founder credited as "Eitan".
Comparison: His own site states it; the LANAIS announcement lists "Eitan" among co-founders (first name only, consistent).
Decision: corroborated

## Claim 11: De Leo "led the operations side"; "co-founded ASTN (the AI Safety Talent Network, safetytalent.org)"; "joined 80,000 Hours as an engineer in 2026"; ACX grant 2022; "ran grantmaking operations at Nonlinear 2023–2024" (scalar:sources[3].note)

Source: https://lvca.dev/about
Source tier: primary
Source content: "an ACX grant in 2022"; "2023–2024 doing ops at Nonlinear, running their grantmaking network"; "also cofounded ASTN, a career platform for the field"; "In 2026 I'm joining 80,000 Hours as an engineer."
Comparison: All elements match his own site. The expansion "AI Safety Talent Network, safetytalent.org" is consistent with the ASTN platform hosting BAISH's course listing but the page extract names ASTN only as "a career platform". Scalar path is `sources[3].note`. One primary source.
Decision: primary-sourced

## Claim 12: Organising team "includes staff members Gaspar Labastie, Tobias Bersia, Gonzalo Heredia, and Rocio Monjes, and advisors Sergio Abriola (PhD) and Guido Bergman"

Source: https://www.baish.com.ar/en/about
Source tier: primary
Source content: Staff: "Gaspar Labastie, Tobias Bersia, Gonzalo Heredia, Rocio Monjes, Augusto Esquivel Masciotta, Malena Cocozzella". Advisors: "Sergio Abriola, PhD; Guido Bergman; Nicolas Martorell"
Comparison: All six named people appear on the About page. The roster has grown since the entity's 2026-06-03 snapshot (two more staff, one more advisor); the body's "includes" phrasing remains accurate.
Decision: primary-sourced

## Claim 13: "Funding comes from Open Philanthropy ($14,500+ in grants to BAISH)"

Source: https://eitan-sprejer.github.io/
Source tier: primary
Source content: "received $14,500+ in OpenPhil funding"
Comparison: Amount and funder match the founding director's site. One primary source.
Decision: primary-sourced

## Claim 14: Funding from "Coefficient Giving (via its Navigating Transformative AI fund), and the Kairos Pathfinder programme"

Source: https://www.baish.com.ar/en/about
Source tier: primary
Source content: Funders: "Coefficient Giving" and "Kairos (Pathfinder Program)"
Comparison: Coefficient Giving and Kairos Pathfinder confirmed by BAISH's own About page. The qualifier "via its Navigating Transformative AI fund" was not found in any source this pass (a web search for BAISH + the fund name returned no link); the fund exists at Coefficient Giving but its routing of the BAISH grant is unanchored.
Decision: uncorroborated

## Claim 15: "BAISH's educational offering runs across three tracks, all in Spanish and free of charge"

Source: https://www.baish.com.ar/en ; https://safetytalent.org/org/baish/apply/ps7f9f08q1b8bmb90zfavg9hv584jzzn
Source tier: primary
Source content: Main site lists the three tracks. SafetyTalent confirms the Technical AI Safety Course is "In Spanish" and "Free".
Comparison: Three tracks confirmed. Spanish + free confirmed for the flagship Technical course only; no source this pass states language or cost for the Project and Governance tracks. Partial confirmation of a generalisation.
Decision: uncorroborated

## Claim 16: Technical AI Safety Course — BlueDot Impact, 30-hour, in-person weekly sessions at Exactas, in Spanish, free, targeting "ML researchers, software engineers, and policy professionals"

Source: https://safetytalent.org/org/baish/apply/ps7f9f08q1b8bmb90zfavg9hv584jzzn ; https://www.baish.com.ar/en
Source tier: database
Source content: "BlueDot Impact's Technical AI Safety course"; "30 hours"; "Facultad de Exactas y Naturales, UBA"; "In Spanish"; "Free"; "ML researchers, software engineers, policy professionals, and anyone driven to make AI go well". Main site: "Technical AI Safety Course — 30 hours, in-person".
Comparison: All elements match across the listing and BAISH's own site.
Decision: corroborated

## Claim 17: "March 2026 and April–June 2026 editions both oversubscribed, indicating a quarterly cadence and steady demand"

Source: https://safetytalent.org/org/baish/apply/ps7f9f08q1b8bmb90zfavg9hv584jzzn
Source tier: database
Source content: "The March 2026 cohort applications have closed. The April-June 2026 cohort applications are also now closed." The page "does not indicate whether previous cohorts were oversubscribed".
Comparison: Both cohorts' existence confirmed; "oversubscribed" is not stated by any source this pass — applications closing is not oversubscription. The quarterly-cadence inference rests on the unconfirmed element.
Decision: uncorroborated

## Claim 18: Technical AI Safety Project — "A five-week, 30-hour programme in which participants replicate recent AI-safety research through programming"

Source: https://www.baish.com.ar/en
Source tier: primary
Source content: "Technical AI Safety Project — 5 weeks, 30 hours, in-person project sprint for 'making a first concrete contribution to AI safety research or engineering'"
Comparison: Duration and hours match; "replicate recent research" is a close paraphrase of the project sprint's first-contribution framing. One primary source.
Decision: primary-sourced

## Claim 19: "Frontier AI Governance Course. A third track, covering AI governance, with dates yet to be confirmed as of mid-2026"

Source: https://www.baish.com.ar/en
Source tier: primary
Source content: "Frontier AI Governance — 'Explore governance challenges from frontier AI systems: coordination, compute governance, accountability, and risk assessment.' Dates TBD."
Comparison: Track and dates-TBD status match.
Decision: primary-sourced

## Claim 20: "BAISH runs a paper-reading club, introductory socials, and open community channels (Telegram and WhatsApp)"

Source: https://www.baish.com.ar/en ; https://aisafety.com/communities
Source tier: primary
Source content: Main site lists the Telegram and WhatsApp community channels. Directory description: "regular discussion groups, reading clubs, and courses".
Comparison: Channels confirmed by BAISH's site; reading club confirmed by the directory description.
Decision: corroborated

## Claim 21: "The hub has also extended its reach beyond Argentina, serving as a teaching assistant at two ML4Good bootcamps in Colombia and Brazil in 2025"

Source: https://eitan-sprejer.github.io/ ; https://www.baish.com.ar/en/about
Source tier: primary
Source content: Sprejer site: "Teaching Assistant at 2 ML4Good bootcamps (Colombia & Brazil, 2025)". About page: "Teaching assistant at ML4Good camps (Eitan Sprejer, two occasions)".
Comparison: The underlying facts (two bootcamps, Colombia and Brazil, 2025) are confirmed, but both sources attribute the TA role to Sprejer personally, not to the hub as an organisation. The body's hub-level attribution is a paraphrastic shift the sources do not directly anchor; whether to reframe is prose judgment beyond a single token.
Decision: uncorroborated

## Claim 22: Research focus stated as "Chain of Thought interpretability, LLM evaluations, Mechanistic interpretability of neural networks" (body + scalar:sources[1].note)

Source: https://www.baish.com.ar/en/about
Source tier: primary
Source content: "Chain of Thought interpretability," "LLM evaluations," and "Mechanistic interpretability of neural networks"
Comparison: Verbatim match against BAISH's own About page.
Decision: primary-sourced

## Claim 23: "Eitan Sprejer is first author of 'Approximating Human Preferences Using a Multi-Judge Learned System,' presented at the NeurIPS 2025 LatinX in AI and Reliable ML workshops"

Source: https://eitan-sprejer.github.io/ ; https://www.baish.com.ar/en/research
Source tier: primary
Source content: Sprejer site: first author, "NeurIPS 2025 workshops (LatinX & Reliable ML)". BAISH research page: "Approximating Human Preferences Using a Multi-Judge Learned System — NeurIPS Workshop (Sep 2025)"
Comparison: Author position and venues match across both sources.
Decision: corroborated

## Claim 24: "He is second author (with Austin Meek) of 'Measuring Chain-of-Thought Monitorability Through Faithfulness and Verbosity,' submitted to AAAI 2026"

Source: https://eitan-sprejer.github.io/
Source tier: primary
Source content: "Second author (with Austin Meek)"; "Submitted to AAAI 2026"
Comparison: Both elements match his site; the BAISH research page lists the paper (arXiv, Oct 2025) without the AAAI-submission detail.
Decision: primary-sourced

## Claim 25: "The BAISH FAIR research group contributed to 'AI Debaters are More Persuasive when Arguing in Alignment with Their Own Beliefs' (NeurIPS 2024 workshop)"

Source: https://neurips.cc/virtual/2025/loc/san-diego/128037 ; https://bicyt.conicet.gov.ar/fichas/produccion/en/12709154 ; https://arxiv.org/abs/2510.13912
Source tier: primary
Source content: arXiv: "Submitted on 15 Oct 2025"; authors include Eitan Sprejer and Guido Ernesto Bergman. CONICET production record title: "MTI-LLM Workshop @ NeurIPS 2025 - AI Debaters are More Persuasive when Arguing in Alignment with Their Own Beliefs"; the paper has a NeurIPS 2025 virtual page.
Comparison: The paper was presented at the MTI-LLM Workshop at NeurIPS **2025**, not a NeurIPS **2024** workshop — it was only submitted to arXiv in October 2025, so a 2024 venue is impossible. BAISH involvement is confirmed (Sprejer and Bergman among authors; the BAISH research page lists the paper). Single-token fix: "NeurIPS 2024 workshop" → "NeurIPS 2025 workshop".
Decision: correction

## Claim 26: "the arXiv preprint 'Mind the Performance Gap: Capability-Behavior Trade-offs in Feature Steering,' with Sprejer as first author"

Source: https://eitan-sprejer.github.io/
Source tier: primary
Source content: "Mind the Performance Gap: Capability-Behavior Trade-offs in Feature Steering — First author, BAISH FAIR — arXiv preprint"
Comparison: Title, author position, BAISH FAIR affiliation, and preprint status match.
Decision: primary-sourced

## Claim 27: "A formal research fellowships programme is in planning for 2026" (body + scalar:sources[0].note)

Source: https://www.baish.com.ar/en ; https://www.baish.com.ar/en/research
Source tier: none
Source content: Neither the main page nor the research page as fetched this pass mentions a research fellowships programme for 2026.
Comparison: The source note attributes this to the main site as of 2026-06-03; the statement was not found on the site this pass (page may have changed). No canonical source currently anchors it. Scalar path is `sources[0].note`.
Decision: uncorroborated

## Claim 28: "LANAIS … launched with a kick-off event on 28 June 2025 and aims to connect researchers, students, and organisers across the region through a public directory, career resources, and virtual and in-person networking events" (+ scalar:sources[7].note four goals)

Source: https://forum.effectivealtruism.org/posts/DnqFsjiKW4ooC3DK4/lanais-latin-american-network-for-ai-safety-kick-off
Source tier: primary
Source content: "Launch Event: Saturday, June 28, 2025"; goals: "Strengthen connections between people working on AI Safety across Latin America"; "Support high-impact career pipelines"; "Increase awareness about AI risks and alignment challenges throughout the region"; "Foster collaboration between the growing number of AI Safety communities in Latin America"; offerings: "public map and database", "Resource hub with career guides", virtual and in-person events.
Comparison: Launch date exact; the body's and `sources[7].note`'s four-goal paraphrase matches the announcement's four goals; offerings match.
Decision: primary-sourced

## Claim 29: "Regional sister groups include AI Safety Colombia (Bogotá), AI Safety Brazil (São Paulo), and AISMX (Mexico)"

Source: https://apartresearch.com/sprints/global-south-ais-hackathon-2026-06-19-to-2026-06-21 ; https://aisafetybrazil.org/ (existence via search)
Source tier: primary
Source content: Hackathon hubs: "Bogotá: AI Safety Colombia"; "Mérida and Guadalajara: AISMX"; "São Paulo: EA Brasil". AI Safety Brazil exists (aisafetybrazil.org) but no source this pass places it in São Paulo — the hackathon's São Paulo hub is EA Brasil, a different organisation.
Comparison: Colombia/Bogotá and AISMX/Mexico confirmed; the "AI Safety Brazil (São Paulo)" pairing is unanchored and possibly conflates two groups. Composite claim partially confirmed; the fix requires prose judgment.
Decision: uncorroborated

## Claim 30: Apart Research Global South AI Safety Hackathon (19–21 June 2026) — BAISH one of five LatAm hubs (with EA Brazil São Paulo, AI Safety Colombia Bogotá, AISMX Mérida and Guadalajara, Santa Cruz Hub Bolivia); "USD 3,000 prize pool across three winning teams"; eligible topics incl. "AI fairness for Spanish and Portuguese language models and regulatory analysis of emerging Latin American AI legislation" (+ scalar:sources[5].note)

Source: https://apartresearch.com/sprints/global-south-ais-hackathon-2026-06-19-to-2026-06-21
Source tier: primary
Source content: "Jun 19, 2026 - Jun 21, 2026"; hubs: Buenos Aires (BAISH), São Paulo (EA Brasil), Bogotá (AI Safety Colombia), Mérida and Guadalajara (AISMX), Santa Cruz (Bolivia); "Three winning teams ($3,000 total)"; "AI fairness for Portuguese and Spanish language models"; "regulatory analysis of emerging legislation across the region"
Comparison: Dates, all five hubs, prize structure, and topic framings match the organiser's own page. Scalar path is `sources[5].note`.
Decision: primary-sourced

## Claim 31: "BAISH's research output — four papers across NeurIPS workshops, an AAAI submission, and arXiv in its first two years — and its 150+ member community"

Source: https://eitan-sprejer.github.io/ ; https://www.baish.com.ar/en/research
Source tier: primary
Source content: Sprejer site: "150+ members". The research page and Sprejer's site together list the four papers the body enumerates (Multi-Judge, AI Debaters, CoT Monitorability, Mind the Performance Gap) across NeurIPS workshops, an AAAI submission, and arXiv; BAISH's main page states "3+ published papers".
Comparison: The 150+ figure matches the founding director's site (the main site says 120+ community members — the two figures coexist in the entity, each cited to its source). The four-paper count is consistent with the enumerated outputs, noting the venue-year correction in Claim 25.
Decision: primary-sourced
