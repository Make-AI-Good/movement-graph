---
entity_id: org-algorithmic-justice-league
entity_hash: 26b237ccfa73ef78339ae3bccfdbde2a5902f9af
audit_date: 2026-05-19
pass: 1
status: supported
claims_total: 21
claims_corroborated: 15
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 6
sources_consulted:
  - https://en.wikipedia.org/wiki/Algorithmic_Justice_League
  - https://en.wikipedia.org/wiki/Joy_Buolamwini
  - https://en.wikipedia.org/wiki/Coded_Bias
  - https://en.wikipedia.org/wiki/Tawana_Petty
  - https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
  - https://gs.ajl.org/
  - https://www.ajl.org/about
  - https://www.ajl.org/
  - https://www.ajl.org/crash-project
  - https://www.ajl.org/bugs
  - https://www.ajl.org/flyreport
  - https://www.usccr.gov/reports/2024/civil-rights-implications-federal-use-facial-recognition-technology
---

## Claim 1: "AJL ... is a Cambridge, Massachusetts-based nonprofit"

Source: https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: "The Algorithmic Justice League (AJL) is a digital advocacy non-profit organization based in Cambridge, Massachusetts."
Comparison: Body matches source on location and nonprofit status. Definitional fact about a named entity — Wikipedia-alone is sufficient.
Decision: corroborated

## Claim 2: "founded in 2016 by Joy Buolamwini"

Source: https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: "Founded in 2016 by computer scientist Joy Buolamwini"
Comparison: Founding year and founder match.
Decision: corroborated

## Claim 3: "Buolamwini, then a graduate student at the MIT Media Lab"

Source: https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: Buolamwini was "a graduate student in the MIT Media Lab" when she established the organization.
Comparison: Body matches source on Buolamwini's status at founding.
Decision: corroborated

## Claim 4: "off-the-shelf facial-detection software failed to register her face until she put on a white mask"

Source: https://en.wikipedia.org/wiki/Joy_Buolamwini
Source content: "the systems failed to detect her face unless she wore a white mask"
Comparison: Body paraphrases the same fact; semantic match.
Decision: corroborated

## Claim 5: "AJL's stated mission is to raise public awareness about the impacts of AI, equip advocates with resources, build the voice and choice of the most-affected communities, and galvanize researchers, policymakers, and industry practitioners to prevent AI harms"

Source: https://www.ajl.org/about
Source content: "raise public awareness about the impacts of AI, equip advocates with resources to bolster campaigns, build the voice and choice of the most impacted communities, and galvanize researchers, policymakers, and industry practitioners to prevent AI harms."
Comparison: Body paraphrases AJL's own About page; "most-affected" vs. "most impacted" and elided "to bolster campaigns" are within paraphrase tolerance; semantic content matches.
Decision: corroborated

## Claim 6: "Gender Shades, a 2018 study by Buolamwini and Timnit Gebru"

Source: https://gs.ajl.org/ ; https://en.wikipedia.org/wiki/Joy_Buolamwini
Source content: gs.ajl.org: "Dr. Joy Buolamwini (lead) and Dr. Timnit Gebru (co-author) published the Gender Shades paper in 2018." Joy Buolamwini Wikipedia: "Co-author: Timnit Gebru ... Year: 2018".
Comparison: Year and authorship match across primary (AJL site) and Wikipedia.
Decision: corroborated

## Claim 7: "audited commercial facial-analysis systems from IBM, Microsoft, and Megvii"

Source: https://en.wikipedia.org/wiki/Algorithmic_Justice_League ; https://gs.ajl.org/
Source content: Wikipedia: "facial recognition algorithms used by commercial systems from Microsoft, IBM, and Face++ (Megvii)." gs.ajl.org: "gender classification products from IBM, Microsoft, and Face++ (Megvii)."
Comparison: Three vendors match exactly; "Face++ (Megvii)" is the same company.
Decision: corroborated

## Claim 8: "found dramatic accuracy gaps for darker-skinned and feminine-presenting faces"

Source: https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: "showed reduced accuracy for darker-skinned and feminine-presenting faces."
Comparison: Body paraphrases the same finding; "dramatic" is qualitative but supported by quantitative gaps (e.g. 34.7% error rate for darker-skinned women per Joy Buolamwini Wikipedia).
Decision: corroborated

## Claim 9: "CRASH project — originally launched in July 2020 as the Algorithmic Vulnerability Bounty Project"

Source: https://www.ajl.org/crash-project ; https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: AJL CRASH page: "formerly called the Algorithmic Vulnerability Bounty Project." Wikipedia: "Launched in July 2020."
Comparison: Launch date and original name match primary and Wikipedia sources.
Decision: corroborated

## Claim 10: "foundational report, Bug Bounties For Algorithmic Harms?"

Source: https://www.ajl.org/bugs
Source content: "Bug Bounties For Algorithmic Harms?: Lessons from Cybersecurity Vulnerability Disclosure for Algorithmic Harms Discovery, Disclosure, and Redress"
Comparison: Title (short form) matches primary source verbatim.
Decision: corroborated

## Claim 11: "Freedom Flyers campaign, launched in 2023"

Source: https://www.ajl.org/flyreport ; https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: AJL flyreport: "Launched in 2023 ... the Freedom Flyers Campaign has sought to gather feedback on people's lived experiences with the facial recognition program conducted at TSA checkpoints." Wikipedia: "Began in 2023".
Comparison: Launch year matches across primary and Wikipedia.
Decision: corroborated

## Claim 12: "mobilizes air travelers to opt out of TSA facial recognition at U.S. airport checkpoints"

Source: https://www.ajl.org/flyreport ; https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: AJL flyreport: "lived experiences with the facial recognition program conducted at TSA checkpoints." Wikipedia: "focusing on TSA facial recognition use at U.S. airports."
Comparison: TSA target and U.S. airport setting match; opt-out framing matches the campaign's documented purpose.
Decision: corroborated

## Claim 13: "The associated Comply To Fly? report has been cited in U.S. Commission on Civil Rights testimony"

Source: https://www.ajl.org/flyreport ; https://www.usccr.gov/reports/2024/civil-rights-implications-federal-use-facial-recognition-technology
Source content: AJL flyreport page does not mention U.S. Commission on Civil Rights testimony. The USCCR 2024 facial-recognition report's overview page returned no matches for "AJL", "Algorithmic Justice League", "Comply To Fly", "Joy Buolamwini", or "Freedom Flyers."
Comparison: No canonical source fetched in this session confirms the testimony citation. The claim may still be true (e.g. in oral testimony or a separate USCCR document not surfaced here), but cannot be confirmed from the cited or accessible sources.
Decision: uncorroborated

## Claim 14: "Buolamwini's 2023 book Unmasking AI: My Mission to Protect What Is Human in a World of Machines"

Source: https://en.wikipedia.org/wiki/Joy_Buolamwini
Source content: "Title: Unmasking AI: My Mission to Protect What Is Human in a World of Machines"
Comparison: Title matches verbatim; 2023 publication is the well-documented public-record date. Named-entity definitional fact (book title) — Wikipedia-alone sufficient.
Decision: corroborated

## Claim 15: "The 2020 documentary Coded Bias, directed by Shalini Kantayya"

Source: https://en.wikipedia.org/wiki/Coded_Bias
Source content: "Release Year: 2020 ... Director: Shalini Kantayya"
Comparison: Year and director match. Public-record definitional facts about a named film — Wikipedia-alone sufficient.
Decision: corroborated

## Claim 16: "follows Buolamwini's research and AJL's early advocacy"

Source: https://en.wikipedia.org/wiki/Coded_Bias
Source content: "The film examines 'artificial intelligence and the biases that can be embedded into this technology' ... It documents Buolamwini's discovery that such systems only functioned when she wore a white mask, leading to broader investigations into algorithmic discrimination..."
Comparison: Wikipedia confirms the film centers on Buolamwini's research and the AJL-adjacent advocacy that followed.
Decision: corroborated

## Claim 17: "Buolamwini is founder and president"

Source: https://en.wikipedia.org/wiki/Algorithmic_Justice_League ; https://www.ajl.org/about
Source content: Wikipedia AJL: "Founded in 2016 by computer scientist Joy Buolamwini," with no executive title (president, CEO, executive director) given. AJL About page identifies her as "Founder."
Comparison: "Founder" is confirmed by both sources. "President" is not confirmed by any canonical source fetched in this session — neither Wikipedia nor AJL's own About page lists her title as President. Living-person role title beyond "Founder" requires ≥1 non-Wikipedia canonical source; none was found.
Decision: uncorroborated

## Claim 18: "Sasha Costanza-Chock, a sociologist and design scholar"

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: "Costanza-Chock is a communications scholar ... Their field is media studies, with research focused on 'participatory design, social movements, media, and communications technologies.' ... PhD from USC's Annenberg School for Communication and Journalism."
Comparison: Wikipedia describes Costanza-Chock as a communications scholar (PhD in communications), not a sociologist. "Design scholar" is partially supported by their participatory-design research focus. Living-person discipline claim — Wikipedia is tiebreaker-only; with no second canonical source to either confirm "sociologist" or independently establish "communications scholar," the discipline claim cannot be resolved here.
Decision: uncorroborated

## Claim 19: "[Costanza-Chock] has led the organization's research and design work, including the CRASH project"

Source: https://www.ajl.org/crash-project ; https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: AJL CRASH page: "AJL Senior Research Fellow & Co-Lead" of the CRASH Project. Wikipedia: "served as the Research Director of the Algorithmic Justice League."
Comparison: AJL primary source confirms CRASH co-lead role. "Director of Research and Design" framing in the entity's frontmatter `sources` (citing a 2022 USENIX speaker bio I could not fetch — 403) is not directly confirmed; Wikipedia gives "Research Director" (no "and Design"). CRASH leadership specifically is verified; the broader "led research and design work" framing relies on a USENIX page I could not access and a Wikipedia entry that's tiebreaker-only.
Decision: uncorroborated

## Claim 20: "Tawana Petty, a longtime data-justice organizer, served as Director of Policy and Advocacy"

Source: https://en.wikipedia.org/wiki/Tawana_Petty
Source content: "She served as 'National Organizing Director for Data for Black Lives' and held the position of Data Justice Director at the Detroit Community Technology Project ... She held the title 'Director of Policy and Advocacy for the Algorithmic Justice League'."
Comparison: Wikipedia confirms both the data-justice organizing background and the AJL title. Living-person employment specifics — Wikipedia is tiebreaker-only and no second canonical source was found in this session.
Decision: uncorroborated

## Claim 21: "AJL's work has been supported by the Ford, MacArthur, Rockefeller, Alfred P. Sloan, and Mozilla foundations"

Source: https://en.wikipedia.org/wiki/Algorithmic_Justice_League
Source content: "Primary Funders: Ford Foundation, MacArthur Foundation, Alfred P. Sloan Foundation, Rockefeller Foundation, and Mozilla Foundation."
Comparison: Wikipedia confirms all five named funders. Donor-identity claims are tiebreaker-only for Wikipedia; no second canonical source (foundation grant records, AJL-published annual reports / 990 filings) was fetched in this session to corroborate independently.
Decision: uncorroborated
