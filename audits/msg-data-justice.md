---
entity_id: msg-data-justice
entity_hash: 08406e9d0c6a8c3cc9b7de307a13163cf7c64cff
audit_date: 2026-09-05
pass: 1
status: corrections-pending
claims_total: 22
claims_corroborated: 6
claims_primary_sourced: 5
claims_single_source: 1
claims_uncorroborated: 5
open_corrections: 5
sources_consulted:
  - https://www.uio.no/studier/emner/matnat/ifi/IN5370/h24/readings/taylor-(2017).pdf
  - https://www.odbproject.org/our-data-bodies-project/
  - https://www.odbproject.org/tools/
  - https://www.odbproject.org/tag/stop-lapd-spying-coalition/
  - https://datajusticelab.org/
  - https://datajusticelab.org/people/
  - https://datajusticelab.org/event/data-justice-2018/
  - https://itforchange.net/research
  - https://itforchange.net/centering-equity-and-justice-global-data-governance/
  - https://researchonline.lse.ac.uk/id/eprint/100314/
  - https://researchonline.lse.ac.uk/id/eprint/100314/1/Gangadharan_Digital_defense_Published_English.pdf
  - https://alliedmedia.org/news/our-data-bodies-playbook-out
  - https://alliedmedia.org/projects/our-data-bodies-odb
  - https://just-tech.ssrc.org/citation/our-data-our-bodies-reclaiming-our-data/
  - https://www.cardiff.ac.uk/research/explore/research-units/the-data-justice-lab
  - https://en.wikipedia.org/wiki/MediaJustice
  - http://itforchange.net/aboutus/
  - https://www.cbinsights.com/company/aapti-institute
  - https://blogs.lse.ac.uk/lsereviewofbooks/2018/07/02/book-review-automating-inequality-how-high-tech-tools-profile-police-and-punish-the-poor-by-virginia-eubanks/
---

## Claim 1: scalar:origin — Taylor 2017 "proposed three foundational rights — the right to invisibility ... the right to representation ... and the right to engagement"

Source: https://www.uio.no/studier/emner/matnat/ifi/IN5370/h24/readings/taylor-(2017).pdf
Source tier: primary
Source content: "I propose three pillars as the basis of a notion of international data justice: (in)visibility, (dis)engagement with technology and antidiscrimination."
Comparison: The paper's actual framework is three pillars — (in)visibility, (dis)engagement with technology, antidiscrimination — not three rights named invisibility/representation/engagement. The entity splits (in)visibility into two "rights," recasts (dis)engagement as participation, and drops antidiscrimination entirely. Fix location: frontmatter scalar `origin`.
Decision: correction

## Claim 2: scalar:sources[0].note — "the paper's three-pillar rights framework (invisibility, representation, engagement)"

Source: https://www.uio.no/studier/emner/matnat/ifi/IN5370/h24/readings/taylor-(2017).pdf
Source tier: primary
Source content: "I propose three pillars as the basis of a notion of international data justice: (in)visibility, (dis)engagement with technology and antidiscrimination."
Comparison: Same mischaracterization as Claim 1 in the source note. The note's citation details (Big Data & Society, 4(2), 2017, title) are accurate; only the pillar names need replacing. Fix location: frontmatter scalar `sources[0].note`.
Decision: correction

## Claim 3: "Taylor proposed three foundational rights ... **Invisibility** — the right to be able to opt out ... **Representation** — the right to have data collected about you be accurate ... **Engagement** — the right to participate meaningfully"

Source: https://www.uio.no/studier/emner/matnat/ifi/IN5370/h24/readings/taylor-(2017).pdf
Source tier: primary
Source content: "This suggests an approach based on three pillars: visibility, digital (dis)engagement and countering data-driven discrimination ... the need to be represented but also the possibility of the need to opt out of data collection or processing, the need to preserve one's autonomy with regard to data-producing technologies and the need to be protected from and to challenge data-driven discrimination."
Comparison: Body §Origin paragraph presents an invented three-rights trio. In the paper, representation and opting out are both facets of the single (in)visibility pillar; the second pillar is autonomy over technology (dis)engagement, not participatory governance; the third pillar (antidiscrimination) is absent from the entity. Body fix requires prose judgment beyond single-token replacement — Editor should `[editor-flag]` to Researcher.
Decision: correction

## Claim 4: Taylor paper title, venue, and global-bridge case — "What is data justice? The case for connecting digital rights and freedoms globally", Big Data & Society, 2017, arguing for connecting Global North digital-rights and Global South frameworks

Source: https://www.uio.no/studier/emner/matnat/ifi/IN5370/h24/readings/taylor-(2017).pdf
Source tier: primary
Source content: "What is data justice? The case for connecting digital rights and freedoms globally. Linnet Taylor ... Big Data & Society"; "Two trends make developing a global perspective on the just use of digital data urgently necessary ... Of the world's seven billion mobile phones, 5.5 billion are in low- and middle-income countries (LMICs)"
Comparison: Title, journal, year, and the paper's global North/South connective case all match; "bridge between traditions" is a fair paraphrase of the title's case and the LMIC-centred argument.
Decision: primary-sourced

## Claim 5: Data Justice Lab "founded by Lina Dencik, Arne Hintz, Joanna Redden, and Emiliano Treré" (origin scalar, sources[3].note, and body §Origin)

Source: https://datajusticelab.org/ and https://datajusticelab.org/people/ and https://www.cardiff.ac.uk/research/explore/research-units/the-data-justice-lab (search snippet)
Source tier: primary
Source content: Lab homepage: "created in 2017 at Cardiff University, UK"; people page lists all four as "Co-Director of the Data Justice Lab" with no founding attribution; Cardiff research-unit snippet: "The lab is co-directed by Dr Lina Dencik, Dr Arne Hintz, and Dr Joanna Redden."
Comparison: Creation at Cardiff in 2017 is primary-confirmed, but no fetched source states who *founded* the lab; Cardiff-side sources name three co-directors while lab pages list four, and the March 2017 launch article (cardiff.ac.uk/news/view/663809) 403s. Whether Treré was a founder or a later-joining co-director is unresolvable from canonical sources this pass. Scalar fix locations if resolved later: `origin`, `sources[3].note`.
Decision: uncorroborated

## Claim 6: scalar:origin — Data Justice Lab "organised the first Data Justice Conference in 2019"

Source: https://datajusticelab.org/event/data-justice-2018/
Source tier: primary
Source content: "The first 'Data Justice' Conference took place on 21-22 May 2018 at Cardiff University, Cardiff, UK."
Comparison: The first Data Justice Conference was May 2018, not 2019. Single-token replacement: 2019 → 2018. Fix location: frontmatter scalar `origin`.
Decision: correction

## Claim 7: "its 2019 Data Justice Conference convened researchers and civil-society practitioners globally for the first time under this framing" (body §Origin)

Source: https://datajusticelab.org/event/data-justice-2018/
Source tier: primary
Source content: "The first 'Data Justice' Conference took place on 21-22 May 2018 at Cardiff University, Cardiff, UK." (Page also notes over 200 participants from around the globe.)
Comparison: Same year error as Claim 6 in body prose: 2019 → 2018.
Decision: correction

## Claim 8: ODB "based in Charlotte, Detroit, and Los Angeles" (origin scalar and body)

Source: https://www.odbproject.org/our-data-bodies-project/ and https://researchonline.lse.ac.uk/id/eprint/100314/1/Gangadharan_Digital_defense_Published_English.pdf
Source tier: primary
Source content: "Based in marginalized neighborhoods in Charlotte, North Carolina, Detroit, Michigan, and Los Angeles, California, we are..."; Playbook names local partners The Center for Community Transitions (Charlotte), Detroit Community Technology Project, Stop LAPD Spying Coalition (LA).
Comparison: Three cities match across the project's own overview page, the Playbook, and the SSRC Just Tech record.
Decision: corroborated

## Claim 9: ODB active "2015–2019" (origin scalar and body §Grassroots application)

Source: https://www.odbproject.org/tools/
Source tier: primary
Source content: "gathered through our work across three U.S. cities since 2015."
Comparison: The 2015 start is primary-confirmed, but no fetched canonical source states a 2019 end year — ODB's own pages carry no end date (the site continued posting into 2019), and Allied Media's project page gives no date range. The span as stated cannot be confirmed.
Decision: uncorroborated

## Claim 10: Playbook full title "Digital Defense Playbook: Community Power Tools for Reclaiming Data"

Source: https://researchonline.lse.ac.uk/id/eprint/100314/ and https://researchonline.lse.ac.uk/id/eprint/100314/1/Gangadharan_Digital_defense_Published_English.pdf
Source tier: primary
Source content: "Digital defense playbook: community power tools for reclaiming data." (LSE record citation; the PDF's own suggested citation matches.)
Comparison: Full title matches the document itself and the LSE Research Online record.
Decision: corroborated

## Claim 11: Playbook publication year "(2019)" (body §Grassroots application)

Source: https://researchonline.lse.ac.uk/id/eprint/100314/1/Gangadharan_Digital_defense_Published_English.pdf and https://alliedmedia.org/news/our-data-bodies-playbook-out
Source tier: primary
Source content: Playbook suggested citation: "Lewis, T., Gangadharan, S. P., Saba, M., Petty, T. (2018). Digital defense playbook: Community power tools for reclaiming data. Detroit: Our Data Bodies." vs. Allied Media announcement dated February 7, 2019: the Playbook "is out."
Comparison: Canonical sources conflict on the year token: the document self-cites 2018 while its public release announcement (Allied Media, Feb 2019) and ODB's own April 2019 "It's Published!" launch post support 2019. Both primary; not picking a winner.
Decision: uncorroborated

## Claim 12: "produced through approximately 135 in-depth community interviews"

Source: https://just-tech.ssrc.org/citation/our-data-our-bodies-reclaiming-our-data/
Source tier: primary
Source content: "has completed nearly 135 in-depth interviews with residents of these cities' most historically marginalized neighborhoods" (record of ODB's own "Reclaiming Our Data" interim report).
Comparison: "Approximately 135" matches the ODB report's own "nearly 135"; the figure traces to the project's interim report (primary), surfaced via the SSRC record.
Decision: primary-sourced

## Claim 13: Playbook premise "data threats facing marginalized communities are political problems requiring collective response, not hygiene lapses requiring individual behavior change" (body; scalar:sources[2].note attributes it to odbproject.org/tools/)

Source: https://www.odbproject.org/tools/
Source tier: primary
Source content: Tools page: the Playbook "offers practical tips, tools, and activities for communities to better understand, navigate, and push back against the pervasive data collection and surveillance practices by which they are disproportionately affected." (No political-problems/behavioral-adjustment formulation on the page.)
Comparison: The cited tools page does not carry the premise language the note attributes to it (misattribution/source drift). The Playbook's collective-organizing orientation is real ("collective organizing strategies for anti-surveillance"), but the entity's specific formulation is a paraphrase too loose to compare to any fetched source text. Fix location if resourced: `sources[2].note`.
Decision: uncorroborated

## Claim 14: "The 'Power Not Paranoia' framework, drawn from the Stop LAPD Spying Coalition's counter-surveillance practice and embedded in the Playbook"

Source: https://www.odbproject.org/tag/stop-lapd-spying-coalition/ and https://researchonline.lse.ac.uk/id/eprint/100314/1/Gangadharan_Digital_defense_Published_English.pdf
Source tier: primary
Source content: ODB post: "The framework was conceived through conversations and in the work of the Stop LAPD Spying Coalition." Playbook: "Power Not Paranoia: The activities in this section are designed to build community knowledge, defense, health and wellness, and collective organizing strategies for anti-surveillance, digital privacy, and safe and connected communities."
Comparison: Both the Stop LAPD Spying provenance and the framework's embedding as a named Playbook section confirm against ODB's own materials.
Decision: primary-sourced

## Claim 15: "Virginia Eubanks, an ODB co-founder"

Source: https://www.odbproject.org/our-data-bodies-project/ and https://www.ischool.berkeley.edu/events/2018/automating-inequality-how-high-tech-tools-profile-police-and-punish-poor (search snippet)
Source tier: primary
Source content: ODB overview lists "Virginia Eubanks (writer, teacher, and welfare rights organizer)" among "We are a five-person team"; Berkeley event bio: "a founding member of the Our Data Bodies Project."
Comparison: Founding-member status confirmed by the project's own team roster plus an independent institutional bio.
Decision: corroborated

## Claim 16: Automating Inequality (2018) argues algorithmic systems "perpetuate and automate the structural inequities that welfare and criminal-legal systems had previously administered through human discretion"

Source: https://blogs.lse.ac.uk/lsereviewofbooks/2018/07/02/book-review-automating-inequality-how-high-tech-tools-profile-police-and-punish-the-poor-by-virginia-eubanks/
Source tier: mainstream
Source content: "outlines the life-and-death impacts of automated decision-making on public services in the USA through three case studies relating to welfare provision, homelessness and child protection services" (2018 review; publisher listings confirm 2018, St. Martin's Press).
Comparison: 2018 publication and the book's thesis match multiple independent accounts (LSE review, publisher listing, author site).
Decision: corroborated

## Claim 17: "MediaJustice (Oakland, formerly Center for Media Justice)"

Source: https://en.wikipedia.org/wiki/MediaJustice
Source tier: tiebreaker
Source content: "Until 2019, MediaJustice was known as the Center for Media Justice"; Idealist/BrightFunds records: "The Center for Media Justice DBA Mediajustice", Oakland, CA.
Comparison: Named-entity definitional facts (formal name, rename, seat) — Wikipedia-alone sufficient under the type rule, and independently matched by nonprofit-registry records.
Decision: corroborated

## Claim 18: "MediaJustice ... was a structural partner in ODB's formation" (body; also grounds the propagated_by_orgs: org-mediajustice edge)

Source: no canonical source found
Source tier: none
Source content: ODB's own materials name its partners as: "The Center for Community Transitions, Inc. (CCT): An organization in Charlotte ... The Detroit Community Technology Project (DCTP) ... Stop LAPD Spying Coali[tion]" (Playbook); search across ODB, Allied Media, and MediaJustice pages surfaces DCTP (Allied Media), Stop LAPD Spying/LACAN, and New America (fiscal sponsor) — no Center for Media Justice.
Comparison: No fetched canonical source connects the Center for Media Justice/MediaJustice to ODB's formation; every partner roster found omits it. Absence of evidence is not a determinate contradiction with a single replacement, so this is not a correction — but the claim and the org-mediajustice propagation edge rest on no found source.
Decision: uncorroborated

## Claim 19: "IT for Change (Bengaluru, founded 2000), led by Anita Gurumurthy"

Source: http://itforchange.net/aboutus/ (search snippet) and https://itforchange.net/Anita/
Source tier: primary
Source content: "established in 2000 as a not for profit society registered under the Karnataka Societies Registration Act 1960"; Gurumurthy profiles: "founding member and Executive Director of IT for Change," Bengaluru.
Comparison: Founding year, seat, and leadership all match the organization's own pages.
Decision: primary-sourced

## Claim 20: IT for Change carries the framing via its "Centering Equity and Justice in Global Data Governance" research programme (body; scalar:sources[4].note cites itforchange.net/research for it)

Source: https://itforchange.net/centering-equity-and-justice-global-data-governance/
Source tier: primary
Source content: "a collaborative research initiative led by IT for Change" engaging "pressing debates at the intersection of data justice and longstanding development challenges," aiming to "advance sector-specific, contextually grounded data justice principles rooted in Global South perspectives."
Comparison: The programme exists, is ITfC-led, and is explicitly in the data-justice register. Note: the entity's cited URL (itforchange.net/research) no longer lists the programme — the dedicated project page above does. Fix location if updated: `sources[4]` URL/note.
Decision: primary-sourced

## Claim 21: "Aapti Institute (Bengaluru, founded 2019)" working on "data cooperatives and participatory data governance"

Source: https://www.cbinsights.com/company/aapti-institute (search snippet) and https://aapti.in/
Source tier: primary
Source content: "Aapti Institute was founded in 2019 and is based in Bengaluru, India"; aapti.in pages: "Unlocking Data Cooperative Opportunities in South East Asia," "Fostering Participatory Data Stewardship," Data Economy Lab researching "data sharing, data stewardship and governance."
Comparison: The stewardship/cooperatives work confirms against Aapti's own site (primary); the 2019 founding year rests on a single database-tier profile — one confirming source overall for the composite claim.
Decision: single-source

## Claim 22: Edge integrity — related_messages (msg-data-colonialism, msg-indigenous-data-sovereignty, msg-nothing-about-us, msg-feminist-ai), propagated_by_orgs (org-our-data-bodies, org-it-for-change, org-mediajustice), and body links (person-virginia-eubanks, person-anita-gurumurthy, pub-automating-inequality, org-aapti-institute, msg-banthescan, msg-meaningful-human-control)

Source: corpus check against product/entities/ (this worktree)
Source tier: primary
Source content: All 13 referenced entity files exist at their expected paths and match the named entities.
Comparison: Mechanical resolution — every cross-reference points to an existing, correctly-named entity. Substantive support for the org-mediajustice propagation edge is Claim 18's separate finding.
Decision: corroborated
