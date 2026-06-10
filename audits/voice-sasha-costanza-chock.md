---
entity_id: voice-sasha-costanza-chock
entity_hash: 0cce74598f60425961d1ccaabff1f5a9f7254db3
audit_date: 2026-06-09
pass: 1
status: corrections-pending
claims_total: 22
claims_corroborated: 14
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 7
sources_consulted:
  - https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
  - https://just-tech.ssrc.org/our-network/sasha-costanza-chock/
  - https://news.mit.edu/2020/design-justice-book-0304
  - http://designjustice.org/djnhistory
  - https://transfeministech.codingrights.org/about
  - https://alliedmedia.org/leader/sasha-costanza-chock
  - https://www.ajl.org/crash-project
---

## Claim 1: scalar:notable_for "*Design Justice: Community-Led Practices to Build the Worlds We Need* (MIT Press, March 2020; 2021 PROSE Award finalist)"

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock and https://news.mit.edu/2020/design-justice-book-0304
Source content: Wikipedia lists "*Design Justice: Community-Led Practices to Build the Worlds We Need* (MIT Press, 2020)" and "2021 PROSE Award Finalist (Engineering & Technology category) for *Design Justice*". MIT News dates the book "March 3, 2020".
Comparison: Frontmatter scalar `notable_for` matches: publisher, month/year, PROSE Award status and year.
Decision: corroborated

## Claim 2: scalar:notable_for "Head-of-Research-and-Sensemaking appointment at One Project"

Source: https://just-tech.ssrc.org/our-network/sasha-costanza-chock/ and https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: SSRC Just Tech states the current title as "Director of Research & Sensemaking at OneProject.org". Wikipedia states "Head of Research at One Project" (no "Sensemaking" qualifier).
Comparison: The `notable_for` scalar's compound title "Head-of-Research-and-Sensemaking" is supported by no canonical source — SSRC (the entity's own cited primary source on the One Project title) gives "Director of Research & Sensemaking"; Wikipedia gives "Head of Research" without "Sensemaking". The body prose (Claim 3 below) correctly carries the SSRC version "Director of Research & Sensemaking", so the `notable_for` scalar is also internally inconsistent with the body. Fix location: `notable_for`.
Decision: correction

## Claim 3: body "Director of Research & Sensemaking at One Project"

Source: https://just-tech.ssrc.org/our-network/sasha-costanza-chock/
Source content: "Director of Research & Sensemaking at OneProject.org".
Comparison: Body claim matches the cited SSRC source verbatim. (Wikipedia's "Head of Research" diverges, but per the source rule the entity's own cited primary source carries the body claim.)
Decision: corroborated

## Claim 4: body "Associate Professor at Northeastern University's College of Arts, Media, and Design with joint appointments in Communication Studies and Design"

Source: https://just-tech.ssrc.org/our-network/sasha-costanza-chock/
Source content: "Associate Professor at Northeastern University's College of Arts, Media, and Design (CAMD) with a joint appointment in the Dept. of Communication Studies and Dept. of Design".
Comparison: Body matches; "joint appointments in Communication Studies and Design" paraphrases the source's two-department appointment.
Decision: corroborated

## Claim 5: body "Faculty Associate at Harvard's Berkman Klein Center for Internet & Society"

Source: https://just-tech.ssrc.org/our-network/sasha-costanza-chock/, https://en.wikipedia.org/wiki/Sasha_Costanza-Chock, https://alliedmedia.org/leader/sasha-costanza-chock
Source content: SSRC: "Faculty Associate with the Berkman-Klein Center for Internet & Society at Harvard University". Wikipedia: "Faculty affiliate at Berkman Klein Center for Internet & Society". AMP: "Faculty Associate at the Berkman-Klein Center for Internet & Society at Harvard University".
Comparison: Multiple canonical sources agree; body claim matches.
Decision: corroborated

## Claim 6: body "Steering Committee member of the Design Justice Network"

Source: https://just-tech.ssrc.org/our-network/sasha-costanza-chock/ and https://alliedmedia.org/leader/sasha-costanza-chock
Source content: SSRC: "member of the Steering Committee of the Design Justice Network". AMP: "Steering Committee, Design Justice Network".
Comparison: Matches both sources.
Decision: corroborated

## Claim 7: body "board member of Allied Media Projects"

Source: https://alliedmedia.org/leader/sasha-costanza-chock and https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: AMP: "a board member of Allied Media Projects". Wikipedia: "Board member of Allied Media Projects".
Comparison: Matches.
Decision: corroborated

## Claim 8: body "founding of the MIT Codesign Studio"

Source: https://alliedmedia.org/leader/sasha-costanza-chock
Source content: "creator of the MIT Codesign Studio (codesign.mit.edu)".
Comparison: "Founding" paraphrases "creator"; semantic match.
Decision: corroborated

## Claim 9: body "Director-of-Research-and-Design role at the Algorithmic Justice League"

Source: https://www.usenix.org/conference/enigma2022/speaker-or-organizer/sasha-costanza-chock-algorithmic-justice-league-0 (entity-cited; 403 Forbidden when fetched 2026-06-09) and https://en.wikipedia.org/wiki/Sasha_Costanza-Chock
Source content: USENIX Enigma 2022 speaker page (the entity's cited primary source on this exact title) returned HTTP 403 Forbidden — content not retrievable. Wikipedia gives a similar but distinct phrasing: "Research Director of Algorithmic Justice League". `notable_for` repeats "Director-of-Research-and-Design".
Comparison: The precise title "Director of Research and Design" could not be verified — the cited primary source is unreachable, and Wikipedia gives "Research Director" (different word order and missing "Design"). Cannot resolve which is canonical from sources fetched in this session.
Decision: uncorroborated

## Claim 10: body "Design justice is both 'a community of practice, and a framework for analysis'"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: "Design justice is both a community of practice, and a framework for analysis."
Comparison: Verbatim quote.
Decision: corroborated

## Claim 11: body "Patricia Hill Collins's framework of the 'matrix of domination'"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: "the black feminist sociologist Patricia Hill Collins calls a 'matrix of domination'".
Comparison: Attribution to Patricia Hill Collins matches.
Decision: corroborated

## Claim 12: body "structured by white supremacy, heteropatriarchy, capitalism, ableism, and settler colonialism"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: "white supremacy, heteropatriarchy, capitalism, and settler colonialism" (no "ableism" in the MIT News framing).
Comparison: The MIT News framing omits "ableism" from the matrix list. The entity-cited MIT Press product page (which the entity sources note quotes as including ableism) returned HTTP 403 when fetched; cannot confirm whether the book itself includes ableism in the named list. Two canonical sources show two different list compositions; cannot resolve.
Decision: uncorroborated

## Claim 13: body "airport millimeter-wave scanner's binary-gender classification of nonbinary bodies"

Source: https://news.mit.edu/2020/design-justice-book-0304
Source content: "Trans and gender nonconforming people's bodies, black women's hair, head wraps, and assistive devices are regularly flagged as 'risky'" — referring to airport security scanners.
Comparison: The airport scanner example and the nonbinary-flagging mechanism are confirmed; the source's framing matches the body's characterization.
Decision: corroborated

## Claim 14: body "2014. The Future Design Lab practice space launches at the Allied Media Conference"

Source: http://designjustice.org/djnhistory
Source content: "The Future Design Lab at the Allied Media Conference served as an early collaborative space".
Comparison: Year and event match (named the practice space and AMC).
Decision: corroborated

## Claim 15: body "21 June 2015. Thirty designers, artists, technologists, and community organisers convene at AMC Detroit for a session titled 'Generating Shared Principles for Design Justice'"

Source: http://designjustice.org/djnhistory
Source content: "30 people gathered in a session called 'Generating Shared Principles for Design Justice' at the Allied Media Conference in Detroit." Attendees: "designers, artists, technologists, and community organizers".
Comparison: Date, attendee count, session title, location, and attendee categories all match.
Decision: corroborated

## Claim 16: body "2018. The Design Justice Network officially shares finalised principles at the AMC's Design Justice Track, released under a Creative Commons licence"

Source: http://designjustice.org/djnhistory
Source content: principles "shared officially with the network in 2018 at the Design Justice Track at the Allied Media Conference" and made available "under a creative commons license".
Comparison: Year, venue, and licence all match.
Decision: corroborated

## Claim 17: body "reaching more than 300 paid members by early 2021"

Source: http://designjustice.org/djnhistory
Source content: "over 300 paid members (as of the beginning of 2021)".
Comparison: Matches.
Decision: corroborated

## Claim 18: body "the book has been cited more than 3,000 times"

Source: https://just-tech.ssrc.org/our-network/sasha-costanza-chock/ (cited)
Source content: The SSRC Just Tech profile content extracted in this session does not contain a specific citation-count figure.
Comparison: The specific "more than 3,000 times" citation count could not be located in any canonical source fetched this session.
Decision: uncorroborated

## Claim 19: body "*Bug Bounties For Algorithmic Harms?* report (January 2022), of which Costanza-Chock is a named author alongside Josh Kenway, Camille François, Inioluwa Deborah Raji, and Joy Buolamwini"

Source: https://www.ajl.org/crash-project
Source content: The AJL CRASH project page mentions the project will "explore the feasibility of mechanisms such as bug bounties, coordinated bias disclosure, intersectional AI audits, education, and more" but does not name the *Bug Bounties For Algorithmic Harms?* report, its January 2022 date, or its specific authors.
Comparison: Neither the report's publication date nor its co-authors could be confirmed from the canonical sources fetched in this session.
Decision: uncorroborated

## Claim 20: body "Costanza-Chock co-conceived the Oracle for Transfeminist Technologies workshop methodology with Joana Varon ... in partnership with the Design Justice Network and with design and illustration by Clarote"

Source: https://transfeministech.codingrights.org/about
Source content: "concept and coordination: joana varon, executive directress and researcher"; "concept and coordination: sasha costanza-chock, steering committee member"; "design and illustration: clarote, designer and researcher"; "this project is developed in partnership with coding rights and design justice network".
Comparison: Co-conception with Varon, Clarote's role, and the Design Justice Network partnership all match.
Decision: corroborated

## Claim 21: body "originated at the Global Symposium on AI & Inclusion in Rio de Janeiro in November 2017 and was formally published on 13 September 2021"

Source: https://transfeministech.codingrights.org/about
Source content: The page does not specify an origin event, location, date, or formal publication date.
Comparison: Neither the Rio de Janeiro symposium origin nor the 13 September 2021 publication date appears on the entity-cited primary source. No other canonical source was located in this session.
Decision: uncorroborated

## Claim 22: body "*Out of the Shadows, Into the Streets! Transmedia Organizing and the Immigrant Rights Movement* (MIT Press, 2014)"

Source: https://en.wikipedia.org/wiki/Sasha_Costanza-Chock and https://just-tech.ssrc.org/our-network/sasha-costanza-chock/
Source content: Wikipedia: "*Out of the Shadows, into the Streets! Transmedia Organizing and the Immigrant Rights Movement* (MIT Press, 2014)". SSRC: "'Out of the Shadows, Into the Streets!' (2014)".
Comparison: Title, publisher, and year all match.
Decision: corroborated
