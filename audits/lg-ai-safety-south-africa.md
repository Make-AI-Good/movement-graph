---
entity_id: lg-ai-safety-south-africa
entity_hash: dbf7332f2df1c8f97e7a6f55c01e24ef3fe1b485
audit_date: 2026-06-08
pass: 1
status: discrepancy
claims_total: 28
claims_verified: 14
claims_discrepancy: 9
claims_unverifiable: 5
sources_consulted:
  - https://www.aisafetysa.com/
  - https://forum.effectivealtruism.org/posts/9AmYzjxPAbRgzbgq8/announcing-the-cooperative-ai-research-fellowship
  - https://www.cai-research-fellowship.com/
  - https://luma.com/8b61gb0v
  - https://aisafety.com/communities
  - https://www.benjaminsturgeon.com/
  - https://ai.uct.ac.za/african-hub-ai-safety-peace-security
  - https://forum.effectivealtruism.org/posts/TzPwowQL3qH4EHYbt/the-ai-safety-conversation-is-missing-1-4-billion-people
---

## Claim 1: scalar:founded — "2023"

Source: https://www.aisafetysa.com/
Source content: Site lists Leo Hyams and Benjamin Sturgeon as Co-Founders; community-formation timeline starts 2023 per source 2 ("AISSA's inception"); founded year is consistent with the EA Forum post's narrative.
Comparison: Frontmatter scalar `founded: 2023` is consistent with the org's own site and the EA Forum announcement narrative.
Decision: verified

## Claim 2: scalar:location — "Cape Town, South Africa (Innovation City co-working space; expanding to Johannesburg and Stellenbosch)"

Source: https://www.aisafetysa.com/
Source content: "co-working space in Cape Town"; physical anchor at Innovation City (Kloof Street) and Workshop17; "Seeded Stellenbosch AI Safety (Stellies AI Safety)" volunteer program. No Johannesburg expansion mention found in current site.
Comparison: Cape Town / Innovation City / Stellenbosch portions of the scalar match source; the "expanding to Johannesburg" portion is not corroborated by any source consulted in this pass.
Decision: unverifiable

## Claim 3: scalar:sources[0].note — partners list ("partners include Open Philanthropy, Cooperative AI Foundation, UCT AI Initiative, EA South Africa, Lambda, Apart Research, and Ashgro")

Source: https://www.aisafetysa.com/
Source content: Current partners listed: "CoopAI, UCT AI Initiative, Open Philanthropy, Ashgro, Apart, Lambda, Effective Altruism South Africa, Ilina Program, Condor Initiative, Wits, Deep Learning Indaba X."
Comparison: All seven partners named in the scalar appear in the current source. Scalar's "partners include" framing is non-exhaustive, so the broader present-day list does not contradict it.
Decision: verified

## Claim 4: scalar:sources[0].note — participation/event/program/research numbers ("1,570 participations across 49 events, 13 programs, 6 research outputs")

Source: https://www.aisafetysa.com/
Source content: Current site shows "2,045 recorded participations / 98 events held / 13 programs offered / 6 research outputs."
Comparison: Programs (13) and research outputs (6) match. Participations (1,570 → 2,045) and events (49 → 98) no longer match — both have grown since the note's 2026-05-26 last_checked. Two of the four numeric claims in the scalar are stale.
Decision: discrepancy

## Claim 5: scalar:sources[0].note — quoted AISSA self-description ('"a capacity building organisation focused on developing skills and community in South Africa through events, courses, and co-working at AI Safety Cape Town"')

Source: https://www.aisafetysa.com/
Source content: Current self-description on the homepage reads: "AI Safety South Africa is concerned with the safe and beneficial development and deployment of advanced AI systems. We run community events, capacity building programs, and a research group from our co-working space in Cape Town."
Comparison: The quoted text in the scalar does not appear in the current homepage copy. Site has been reworded since last_checked.
Decision: discrepancy

## Claim 6: scalar:sources[1].note — "EA Forum post by Leo Hyams (11 September 2025)"

Source: https://forum.effectivealtruism.org/posts/9AmYzjxPAbRgzbgq8/announcing-the-cooperative-ai-research-fellowship
Source content: Post by Leo Hyams, published September 11, 2025.
Comparison: Author and date match exactly.
Decision: verified

## Claim 7: scalar:sources[1].note — quoted AISSA description in EA Forum post ('"a capacity building organisation focused on developing skills, networks, and community for preventing global catastrophic outcomes from advanced AI"')

Source: https://forum.effectivealtruism.org/posts/9AmYzjxPAbRgzbgq8/announcing-the-cooperative-ai-research-fellowship
Source content: "A capacity building organisation focused on developing skills, networks, and community for preventing global catastrophic outcomes from advanced AI."
Comparison: Quote matches verbatim.
Decision: verified

## Claim 8: scalar:sources[2].note — Cooperative AI Research Fellowship details (3-month, Jan–April 2026, Cape Town, 10 fellows, Lambda compute) and partners list

Source: https://www.cai-research-fellowship.com/
Source content: "Full-time for 3 months, ending 30 April 2026"; start "31 January"; located at "AI Safety Cape Town, a co-working space on Kloof Street in Cape Town"; 10 fellows in 2026 cohort; co-organisers AISSA, CAIF, UCT AI Initiative, PrincInt, Lambda.
Comparison: Duration, dates, location, fellow count, GPU compute provider, and co-organiser list all match.
Decision: verified

## Claim 9: scalar:sources[2].note — mentor institutions list ("mentors from Google DeepMind, Oxford, MIT, Carnegie Mellon, and University of Washington")

Source: https://www.cai-research-fellowship.com/
Source content: Named mentors are affiliated with Cooperative AI Foundation, Oxford, MIT, Google DeepMind, Microsoft, Max-Planck Institute for Intelligent Systems, University of Toronto, Carnegie Mellon, National University of Singapore, and University of Washington (8 mentors across these institutions).
Comparison: The five institutions named in the scalar all appear on the source, but the scalar reads as a closed list (terminated by "and"); the actual mentor pool includes additional institutions (University of Toronto, NUS, Microsoft / Max-Planck). The list is incomplete.
Decision: discrepancy

## Claim 10: scalar:sources[3].note — "Luma event page for AISSA x Apart Research AI Control Hackathon (20–22 March 2026, Cape Town)"

Source: https://luma.com/8b61gb0v
Source content: Event "AISSA x Apart: AI Control Hackathon", dates "March 20-22, 2026", location "Cape Town, South Africa".
Comparison: Event name, dates, and location all match.
Decision: verified

## Claim 11: scalar:sources[3].note — "hosted by Caleb Rudnick and Tegan Green"

Source: https://luma.com/8b61gb0v
Source content: Hosts listed as Caleb Rudnick and Tegan Green.
Comparison: Hosts match.
Decision: verified

## Claim 12: scalar:sources[3].note — "winning projects presented at ControlConf Berkeley, April 2026"

Source: https://luma.com/8b61gb0v
Source content: "Winning projects receive opportunities to present at ControlConf Berkeley in April 2026."
Comparison: Match.
Decision: verified

## Claim 13: scalar:sources[5].note — Sturgeon "describes himself as 'strongly involved with AI Safety South Africa as cofounder and strategic director'"

Source: https://www.benjaminsturgeon.com/
Source content: Page describes Sturgeon as "cofounder and strategic director" of AISSA.
Comparison: Quote matches.
Decision: verified

## Claim 14: scalar:sources[5].note — Sturgeon's research focus ("AI safety, agency in AI systems, and impacts of powerful AI on human agency")

Source: https://www.benjaminsturgeon.com/
Source content: Sturgeon's current stated research interests "center on personas and understanding phenomena like emergent misalignment in large language models, as well as how models think about themselves."
Comparison: The site no longer describes his focus as "agency in AI systems" or "impacts of powerful AI on human agency"; current framing centers on personas and emergent misalignment. Source content has shifted since the note's 2026-05-26 last_checked.
Decision: discrepancy

## Claim 15: scalar:sources[5].note — Sturgeon "pursuing MPhil in Applied Mathematics at UCT"

Source: https://www.benjaminsturgeon.com/
Source content: Site states he is "a MATS fellow, currently doing the MATS extension." No mention of an MPhil program at UCT.
Comparison: The MPhil claim is not supported by the current source — either the degree was completed/withdrawn or the page was updated to drop the mention.
Decision: discrepancy

## Claim 16: body — AISSA is "a Cape Town-based AI-safety capacity-building organization co-founded by Leo Hyams and Benjamin Sturgeon"

Source: https://www.aisafetysa.com/
Source content: Page lists both as Co-Founders; site operates from a Cape Town co-working space; current self-description names "capacity building programs."
Comparison: Cape Town, AI-safety, capacity-building, and the two co-founders all match.
Decision: verified

## Claim 17: body — "operating from a co-working and events space at Innovation City"

Source: https://www.aisafetysa.com/
Source content: Source lists physical anchors "Innovation City, Kloof Street; also Workshop17."
Comparison: Innovation City confirmed; the site also lists Workshop17 as a second co-working anchor, but the body's narrower "operating from … Innovation City" framing is still accurate.
Decision: verified

## Claim 18: body — AISSA positions itself as "a hub for AI safety work on the African continent"

Source: https://www.aisafetysa.com/
Source content: Current homepage copy retrieved in this pass does not contain the quoted phrase verbatim; site framing is around "developing skills, networks, and community in South Africa." The phrase may exist on a subpage not surfaced by this fetch.
Comparison: Cannot locate the exact quoted self-positioning in the canonical source as fetched.
Decision: unverifiable

## Claim 19: body — "By August 2024, the organization had a fast-growing community of around a hundred members"; Substack newsletter used "AI Safety Cape Town" masthead at that time

Source: no canonical source found in this pass (Substack newsletter not in entity's cited sources; not surfaced by other consulted sources)
Source content: n/a — no source consulted in this pass contains the August-2024 membership figure or the masthead claim.
Comparison: Specific membership count and dated masthead claim could not be cross-checked against any consulted source.
Decision: unverifiable

## Claim 20: body — "Hyams serves as Executive Director"

Source: https://www.aisafetysa.com/
Source content: Leo Hyams listed as "Co-Founder, Executive Director."
Comparison: Match.
Decision: verified

## Claim 21: body — "Sturgeon … serves as Strategic Advisor"

Source: https://www.aisafetysa.com/ and https://www.benjaminsturgeon.com/
Source content: AISSA's site labels him "Strategic Advisor"; Sturgeon's personal site labels him "strategic director."
Comparison: Two canonical sources (the org's own listing and the person's own page) disagree on the title. Per the source rule, two canonical sources in conflict cannot be tiebroken; the body's "Strategic Advisor" matches one but contradicts the other.
Decision: unverifiable

## Claim 22: body — Sturgeon "is pursuing an MPhil in Applied Mathematics at UCT with a focus on AI safety and agency"

Source: https://www.benjaminsturgeon.com/
Source content: Site describes him as a MATS fellow doing the MATS extension; no MPhil/UCT mention. Research focus framed as "personas … emergent misalignment … how models think about themselves."
Comparison: Both clauses (the MPhil and the "AI safety and agency" focus) lack current source support.
Decision: discrepancy

## Claim 23: body — "the website notes plans to expand presence to Johannesburg and Stellenbosch"

Source: https://www.aisafetysa.com/
Source content: Site mentions "Seeded Stellenbosch AI Safety (Stellies AI Safety)" volunteer program; no Johannesburg expansion mention found.
Comparison: Stellenbosch presence is confirmed by the source as an active seeded program, but no Johannesburg expansion language was located in this pass — could be on a subpage not surfaced.
Decision: unverifiable

## Claim 24: body — AISSA "worked alongside the University of Cape Town to integrate AI safety into the university's curriculum since the organization's inception"

Source: https://forum.effectivealtruism.org/posts/9AmYzjxPAbRgzbgq8/announcing-the-cooperative-ai-research-fellowship
Source content: "AISSA has been working alongside the University of Cape Town to integrate AI safety topics into the university's curriculum since AISSA's inception."
Comparison: Verbatim match.
Decision: verified

## Claim 25: body — "The Luma calendar records 49 events through mid-2026 with 1,570 total participations"

Source: https://www.aisafetysa.com/
Source content: Current site reports "2,045 recorded participations" and "98 events held."
Comparison: Both numbers in the body are now stale relative to the canonical site (events and participations roughly doubled since 2026-05-26).
Decision: discrepancy

## Claim 26: body — Cooperative AI Research Fellowship is "a three-month full-time in-person research program (January–April 2026, Cape Town)" co-run with "the Cooperative AI Foundation (CAIF), the UCT AI Initiative, and Principles of Intelligence (PrincInt), with Lambda providing GPU compute"

Source: https://www.cai-research-fellowship.com/
Source content: "Full-time for 3 months, ending 30 April 2026"; start 31 January; Cape Town; co-organisers AISSA, CAIF, UCT AI Initiative, "Principles of Intelligent Behavior in Biological and Social Systems (PrincInt)", Lambda.
Comparison: Program duration, dates, location, partners, and Lambda's compute role all match — but the body's expansion of the PrincInt acronym ("Principles of Intelligence") does not match the source's expansion ("Principles of Intelligent Behavior in Biological and Social Systems"). The abbreviation matches; the full name does not.
Decision: discrepancy

## Claim 27: body — 2026 cohort "comprised ten fellows drawn from diverse global backgrounds, mentored by researchers from Google DeepMind, Oxford, MIT, Carnegie Mellon University, and the University of Washington"

Source: https://www.cai-research-fellowship.com/
Source content: 10 fellows confirmed. Named mentors affiliated with Cooperative AI Foundation, Oxford, MIT, Google DeepMind, Microsoft, Max-Planck Institute, University of Toronto, Carnegie Mellon, National University of Singapore, and University of Washington.
Comparison: Fellow count verified. The closed-list mentor institutions ("Google DeepMind, Oxford, MIT, Carnegie Mellon, and the University of Washington") omit additional institutions (University of Toronto, NUS, Microsoft, Max-Planck) that the source explicitly names.
Decision: discrepancy

## Claim 28: body — EA Forum post by Anthonio Oladimeji from March 2024 titled "The AI Safety Conversation Is Missing 1.4 Billion People"

Source: https://forum.effectivealtruism.org/posts/TzPwowQL3qH4EHYbt/the-ai-safety-conversation-is-missing-1-4-billion-people
Source content: Post by Anthonio Oladimeji, March 2024, title "The AI Safety Conversation Is Missing 1.4 Billion People."
Comparison: Author, date, and title all match.
Decision: verified
