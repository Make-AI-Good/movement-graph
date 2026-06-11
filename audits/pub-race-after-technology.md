---
entity_id: pub-race-after-technology
entity_hash: 23e7292ec45276a39988b6ab91602b27dc35e59f
audit_date: 2026-06-11
pass: 2
status: corrections-pending
claims_total: 28
claims_corroborated: 14
claims_primary_sourced: 7
claims_single_source: 3
claims_uncorroborated: 0
open_corrections: 4
sources_consulted:
  - https://en.wikipedia.org/wiki/Race_After_Technology
  - https://en.wikipedia.org/wiki/Ruha_Benjamin
  - https://www.macfound.org/fellows/class-of-2024/ruha-benjamin
  - https://thejustdatalab.com/
  - https://www.ruhabenjamin.com/race-after-technology
  - https://www.ruhabenjamin.com/about
  - https://openlibrary.org/isbn/9781509526406.json
  - http://www2.asanet.org/wp-content/uploads/savvy/sectionrem/awards.html
  - https://www.bklynlibrary.org/media/press/brooklyn-public-library-74
---

Pass-2 note: both pass-1 corrections (the Michelle Alexander blurb missing "pervasive" in body and sources[4].note) were fixed by the Editor and are CLEARED this pass (Claims 10-11, now primary-sourced). Pass 2 finds a new correction pair: the two 2020 award names carry swapped Prize/Award tokens against the awarding bodies' own usage (Claims 7-8, mirrored in scalar sources[0].note as Claims 27-28). The asanet.org and bklynlibrary.org URLs in sources_consulted returned HTTP 403 to direct fetch this session; their content was consulted via search-surfaced page titles and indexed text, as noted per claim — the corrections rest primarily on the directly-fetched ruhabenjamin.com primary page.

## Claim 1: "Race After Technology: Abolitionist Tools for the New Jim Code is a 2019 book by the sociologist of science and technology Ruha Benjamin"

Source: https://en.wikipedia.org/wiki/Race_After_Technology
Source tier: primary
Source content: "Full Title: Race After Technology: Abolitionist Tools for the New Jim Code; Author: Ruha Benjamin; Publication Year: 2019; Publisher: Polity."
Comparison: Title, subtitle, author, year all match Wikipedia; ruhabenjamin.com/about (primary) lists "Race After Technology: Abolitionist Tools for the New Jim Code (Polity 2019)" and the Berkeley sociology PhD plus Harvard Kennedy School STS fellowship that support the "sociologist of science and technology" descriptor; Open Library (database) confirms title/publisher/2019.
Decision: corroborated

## Claim 2: "published by Polity"

Source: https://www.ruhabenjamin.com/about
Source tier: primary
Source content: "Race After Technology: Abolitionist Tools for the New Jim Code (Polity 2019)."
Comparison: Matches; also confirmed by Wikipedia ("Publisher: Polity") and Open Library ("Publisher: Polity").
Decision: corroborated

## Claim 3: "hardcover ISBN 9781509526390"

Source: https://en.wikipedia.org/wiki/Race_After_Technology
Source tier: tiebreaker
Source content: "ISBN: 9781509526390."
Comparison: Wikipedia lists this ISBN for the book (book-ISBN mapping is a named-entity definitional fact, Wikipedia-alone sufficient). The "hardcover" format qualifier is not explicitly labelled in any fetched canonical source; it rests on the Wikipedia-infobox convention of listing the original print edition. One non-primary canonical source; qualifier uncontradicted.
Decision: single-source

## Claim 4: "paperback ISBN 9781509526406"

Source: https://openlibrary.org/isbn/9781509526406.json
Source tier: database
Source content: "Title: Race After Technology; Publisher: Polity; Publish Date: 2019; ISBN-13: 9781509526406."
Comparison: Open Library (Internet Archive bibliographic database) confirms this ISBN belongs to this book — an upgrade from pass 1, where no canonical source surfaced the ISBN at all. The "paperback" format qualifier is not stated in the record ("Physical Format: Not specified"); it is uncontradicted and consistent with the hardcover carrying the distinct ISBN 9781509526390. One canonical database source.
Decision: single-source

## Claim 5: New Jim Code "drawn explicitly from Michelle Alexander's The New Jim Crow as the named lineage"

Source: https://en.wikipedia.org/wiki/Race_After_Technology
Source tier: tiebreaker
Source content: "Benjamin develops this concept by referencing Michelle Alexander's The New Jim Crow."
Comparison: Match on the lineage claim. No second fetched source states the Alexander lineage (the MacArthur page describes the New Jim Code concept without naming Alexander). One non-primary canonical source.
Decision: single-source

## Claim 6: "social hierarchies — and racism in particular — are embedded in the logical layer of internet-based technologies"

Source: https://en.wikipedia.org/wiki/Race_After_Technology
Source tier: mainstream
Source content: Wikipedia: the book examines "how social hierarchies, particularly racism, are embedded in the logical layer of internet-based technologies." MacArthur page: the book exposes "the racial hierarchies and systems of social control embedded in seemingly neutral algorithms and automated systems."
Comparison: Body is a close paraphrase of the Wikipedia line; the MacArthur Foundation's independent description confirms the same substance (racial hierarchies embedded in nominally neutral technical systems).
Decision: corroborated

## Claim 7: "won the American Sociological Association's 2020 Oliver Cromwell Cox Book Prize"

Source: https://www.ruhabenjamin.com/race-after-technology
Source tier: primary
Source content: "Oliver Cromwell Cox Book Award (2020) — American Sociological Association Section on Race & Ethnic Minorities — 'for anti-racist scholarship'." ASA's own section pages (www2.asanet.org SREM awards/bylaws, consulted via search-surfaced text; direct fetch 403) name it "The Oliver Cromwell Cox Book Award." Wikipedia alone renders it "2020 Oliver Cox Cromwell Book Prize" — garbling the name order as well as the Prize/Award token.
Comparison: The body token "Book Prize" contradicts the awarding body's and the author's own usage, "Book Award"; Wikipedia is tiebreaker-tier and cannot sustain the contradiction against primary sources. Single correct replacement: "Oliver Cromwell Cox Book Prize" → "Oliver Cromwell Cox Book Award". The 2020 year, ASA attribution, and the win itself are confirmed by all sources.
Decision: correction

## Claim 8: "the 2020 Brooklyn Public Library Literary Award for Nonfiction"

Source: https://www.ruhabenjamin.com/race-after-technology
Source tier: primary
Source content: "Brooklyn Public Library Literary Prize for Nonfiction (2020)." Brooklyn Public Library's own press release (bklynlibrary.org, consulted via search-surfaced title and indexed text; direct fetch 403) is titled "Brooklyn Public Library Announces 2020 Literary Prize Winners" and names Benjamin the nonfiction winner. Wikipedia alone renders it "Literary Award for Nonfiction".
Comparison: The body token "Literary Award" contradicts the library's own prize name and the author's own page, "Literary Prize"; Wikipedia is tiebreaker-tier and cannot sustain the contradiction. Single correct replacement: "Brooklyn Public Library Literary Award for Nonfiction" → "Brooklyn Public Library Literary Prize for Nonfiction". The 2020 year and the win itself are confirmed by all sources.
Decision: correction

## Claim 9: "Honorable Mention for the 2020 Communication, Information Technologies, and Media Sociology Book Award"

Source: https://en.wikipedia.org/wiki/Race_After_Technology
Source tier: primary
Source content: Wikipedia: "2020 Communication, Information Technologies, and Media Sociology Book Award (Honorable Mention)." ruhabenjamin.com: "Communications, Information Technologies, and Media Sociology (CITAMS) Book Award (2020) — Honorable Mention."
Comparison: Both sources confirm the honorable mention and year. Body's "Communication" (singular) matches Wikipedia and the official ASA CITAMS section name; the author's page uses a "Communications" variant, which does not contradict the body's correct form.
Decision: corroborated

## Claim 10: Michelle Alexander cover blurb — body quotes "these digital tools predictably replicate and deepen racial hierarchies — all too often strengthening rather than undermining pervasive systems of racial and social control"

Source: https://www.ruhabenjamin.com/race-after-technology
Source tier: primary
Source content: "These digital tools predictably replicate and deepen racial hierarchies — all too often strengthening rather than undermining pervasive systems of racial and social control."
Comparison: Verbatim match. Pass-1 correction (missing "pervasive") was applied by the Editor and is CLEARED.
Decision: primary-sourced

## Claim 11: scalar:sources[4].note — the Alexander blurb as quoted in the ruhabenjamin.com source note

Source: https://www.ruhabenjamin.com/race-after-technology
Source tier: primary
Source content: "These digital tools predictably replicate and deepen racial hierarchies — all too often strengthening rather than undermining pervasive systems of racial and social control."
Comparison: The sources[4].note quote now includes "pervasive" and matches the source verbatim. Pass-1 correction CLEARED.
Decision: primary-sourced

## Claim 12: Stephen Kearse / The Nation review quote — body quotes "as much as we try to purge ourselves from our tools and view them as external to our flaws, they are always extensions of us"

Source: https://www.ruhabenjamin.com/race-after-technology
Source tier: primary
Source content: "Her inventive and wide-ranging analyses remind us that as much as we try to purge ourselves from our tools and view them as external to our flaws, they are always extensions of us."
Comparison: Body's quoted substring matches the source verbatim, with the body's framing clause ("frames Benjamin's analyses as a reminder that") accurately mirroring the source's "remind us that".
Decision: primary-sourced

## Claim 13: "holds the Alexander Stewart 1886 Professor of African American Studies chair at Princeton University"

Source: https://www.macfound.org/fellows/class-of-2024/ruha-benjamin
Source tier: primary
Source content: "Alexander Stewart 1886 Professor of African American Studies at Princeton University."
Comparison: Match; identically confirmed by ruhabenjamin.com/about ("Alexander Stewart 1886 Professor of African American Studies at Princeton University").
Decision: corroborated

## Claim 14: "founding director of the Ida B. Wells Just Data Lab"

Source: https://www.macfound.org/fellows/class-of-2024/ruha-benjamin
Source tier: primary
Source content: "Benjamin serves as founding director of this lab (established 2020)."
Comparison: Match; ruhabenjamin.com/about confirms "Founding Director of the IDA B. WELLS Just Data Lab."
Decision: corroborated

## Claim 15: "earned her MA and PhD in Sociology at the University of California, Berkeley in 2008"

Source: https://www.ruhabenjamin.com/about
Source tier: primary
Source content: "MA and PhD in Sociology, University of California, Berkeley (2008)."
Comparison: Match; Wikipedia ("PhD in sociology at the University of California, Berkeley in 2008") and the MacArthur bio ("an MA (2004) and PhD (2008) from the University of California, Berkeley") confirm. The 2008 token attaches to the doctorate, as the body's phrasing carries.
Decision: corroborated

## Claim 16: "previously Assistant Professor of African American Studies and Sociology at Boston University (2010-2014)"

Source: https://www.macfound.org/fellows/class-of-2024/ruha-benjamin
Source tier: mainstream
Source content: "an assistant professor role at Boston University spanning 2010-2014."
Comparison: Match on institution, rank, and years; Wikipedia confirms the full title and span ("From 2010 to 2014, Benjamin was assistant professor of African American Studies and Sociology at Boston University"). Living-person employment-history specific: Wikipedia is tiebreaker, the MacArthur bio is the second canonical source.
Decision: corroborated

## Claim 17: "held a postdoctoral fellowship at UCLA's Institute for Society and Genetics"

Source: https://www.macfound.org/fellows/class-of-2024/ruha-benjamin
Source tier: mainstream
Source content: "She held a postdoctoral fellowship at UCLA's genetics institute from 2008-2010."
Comparison: Match; Wikipedia confirms the institute's full name ("completed a postdoctoral fellowship at UCLA's Institute for Society and Genetics in 2010"). The body asserts no year, so the sources' 2008-2010 span vs completion-in-2010 phrasing raises no comparison issue.
Decision: corroborated

## Claim 18: "a faculty fellowship at the Harvard Kennedy School's Science, Technology, and Society Program"

Source: https://www.macfound.org/fellows/class-of-2024/ruha-benjamin
Source tier: mainstream
Source content: "a visiting faculty fellow at Harvard's science program during 2012-2013."
Comparison: Match in substance; Wikipedia carries the precise program name ("a faculty fellowship at the Harvard Kennedy School's Science, Technology, and Society Program") that the body uses. Living-person employment-history specific with Wikipedia plus one further canonical source.
Decision: corroborated

## Claim 19: "first book People's Science: Bodies and Rights on the Stem Cell Frontier (Stanford University Press, 2013)"

Source: https://www.ruhabenjamin.com/about
Source tier: primary
Source content: "People's Science: Bodies & Rights on the Stem Cell Frontier (Stanford University Press 2013)."
Comparison: Title (ampersand/"and" variance is rendering, not substance), publisher, and year match; Wikipedia confirms ("People's Science: Bodies and Rights on the Stem Cell Frontier (Stanford University Press, 2013)").
Decision: corroborated

## Claim 20: "co-edited Captivating Technology: Race, Carceral Technoscience, and Liberatory Imagination in Everyday Life (Duke University Press, 2019)"

Source: https://www.ruhabenjamin.com/about
Source tier: primary
Source content: "Captivating Technology: Race, Carceral Technoscience, and Liberatory Imagination in Everyday Life (Duke University Press 2019, edited)."
Comparison: Title, publisher, year, and edited-volume status all match; Wikipedia confirms ("edited by Benjamin (Duke University Press, 2019)").
Decision: corroborated

## Claim 21: "Viral Justice: How We Grow the World We Want (Princeton University Press, 2022)"

Source: https://www.ruhabenjamin.com/about
Source tier: primary
Source content: "Viral Justice: How We Grow the World We Want (Princeton University Press 2022)."
Comparison: Match; Wikipedia confirms (Princeton University Press, October 2022).
Decision: corroborated

## Claim 22: "Imagination: A Manifesto (Norton, 2024)"

Source: https://www.ruhabenjamin.com/about
Source tier: primary
Source content: "Imagination: A Manifesto (Norton 2024)."
Comparison: Match; Wikipedia confirms (Norton, June 2024).
Decision: corroborated

## Claim 23: Lab mission — body quotes "to bring together students, educators, activists, and artists to develop a critical and creative approach to data conception, production, and circulation"

Source: https://thejustdatalab.com/
Source tier: primary
Source content: The Lab's stated mission is to bring together "students, educators, activists, and artists to develop a critical and creative approach to data conception, production, and circulation"; the Lab also states it works to "rethink and retool data for justice."
Comparison: Verbatim match against the Lab's own homepage. One primary source covers the quote.
Decision: primary-sourced

## Claim 24: Lab project register — body lists "Algorithmic Accountability, Clearview AI, Digital Border Wall Project, Digital IDs & Smart Cities, Policing & Surveillance, Prisons, Housing & Neighborhoods, Education, Hospitals & Healthcare, Mutual Aid, Work"

Source: https://thejustdatalab.com/
Source tier: primary
Source content: Named projects include "Algorithmic Accountability; Clearview AI; Digital Border Wall Project; Digital IDs & Smart Cities; Policing & Surveillance; Prisons; Housing & Neighborhoods; Education; Hospitals & Healthcare; Mutual Aid; Work" plus others (Phoenix of Gaza, ShotSpotter Zine, Art & Alternative Futures, Mourning & Mental Health, NYCHA, Tests & Treatment, and more).
Comparison: Every project the body names appears on the Lab's homepage; the body's register is an explicit subset of a register that has since grown, which is verified rather than discrepant.
Decision: primary-sourced

## Claim 25: Lab named programmes "Tech Freedom School, Critical + Creative Career Fair"

Source: https://thejustdatalab.com/
Source tier: primary
Source content: "Tech Freedom School Initiative (2022-23)"; "Critical + Creative Career Fair (Spring 2023)."
Comparison: Both programmes confirmed on the Lab's own homepage.
Decision: primary-sourced

## Claim 26: "named a 2024 MacArthur Fellow with the citation 'Illuminating how technology reflects and reproduces inequality and championing the role of imagination in social transformation'"

Source: https://www.macfound.org/fellows/class-of-2024/ruha-benjamin
Source tier: primary
Source content: "Illuminating how technology reflects and reproduces inequality and championing the role of imagination in social transformation."
Comparison: Verbatim match against the Foundation's own 2024 Fellow page — the awarding body's record.
Decision: primary-sourced

## Claim 27: scalar:sources[0].note — the note names "the American Sociological Association's 2020 Oliver Cromwell Cox Book Prize"

Source: https://www.ruhabenjamin.com/race-after-technology
Source tier: primary
Source content: "Oliver Cromwell Cox Book Award (2020) — American Sociological Association Section on Race & Ethnic Minorities"; ASA's own section pages (via search-surfaced text) name "The Oliver Cromwell Cox Book Award."
Comparison: Same token error as Claim 7, carried in the frontmatter scalar sources[0].note: "Book Prize" → "Book Award". The Editor's fix needs to touch both the body award sentence and this scalar.
Decision: correction

## Claim 28: scalar:sources[0].note — the note names "the 2020 Brooklyn Public Library Literary Award for Nonfiction"

Source: https://www.ruhabenjamin.com/race-after-technology
Source tier: primary
Source content: "Brooklyn Public Library Literary Prize for Nonfiction (2020)"; Brooklyn Public Library's own press release (via search-surfaced title) reads "Brooklyn Public Library Announces 2020 Literary Prize Winners."
Comparison: Same token error as Claim 8, carried in the frontmatter scalar sources[0].note: "Literary Award for Nonfiction" → "Literary Prize for Nonfiction". The Editor's fix needs to touch both the body award sentence and this scalar.
Decision: correction
