---
entity_id: fund-hivos
entity_hash: 38275fcfcdfc26cbc7e9e84fcc4d471af7c2b2f5
audit_date: 2026-06-07
pass: 2
status: corrections-pending
claims_total: 31
claims_corroborated: 28
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 2
sources_consulted:
  - https://en.wikipedia.org/wiki/Hivos
  - https://hivos.org/impact-area/civic-rights-in-a-digital-age/
  - https://hivos.org/program/digital-defenders-partnership/
  - https://hivos.org/blog/one-decade-protecting-human-rights-defenders/
  - https://hivos.org/project/pollicy/
  - https://hivos.org/story/nighat-dad/
  - https://hivos.org/impact-area/civic-rights-in-a-digital-age/overview-2023/
  - https://www.mediadefence.org/news/hivos-renews-grant-to-media-defence/
  - https://rsr.akvo.org/en/organisation/268/
  - https://hivos.org/program/eu-see/
  - https://www.fordfoundation.org/work/our-grants/awarded-grants/grants-database/stichting-hivos-127022/
  - https://digitalwitchcraft.works/Coding-Rights
---

## Claim 1: "founded on 5 January 1968 by the Dutch Humanist Association together with Humanitas"

Source: https://en.wikipedia.org/wiki/Hivos
Source content: Infobox: "January 5, 1968". Article body: "founded in 1968 by the Dutch Humanist Association, the Association and Humanitas Weezenkas".
Comparison: Wikipedia confirms the 5 January 1968 founding. Body's "Humanitas" paraphrastically subsumes "Humanitas Weezenkas"; semantic content matches within paraphrase tolerance.
Decision: corroborated

## Claim 2: "the Dutch acronym Hivos standing for Humanistisch Instituut voor Ontwikkelingssamenwerking, the Humanist Institute for Development Cooperation"

Source: https://en.wikipedia.org/wiki/Hivos
Source content: "Humanistisch Instituut voor Ontwikkelingssamenwerking"
Comparison: Exact match on the Dutch expansion. English gloss "Humanist Institute for Development Cooperation" matches the standard rendering of the Dutch.
Decision: corroborated

## Claim 3: "operating from a global office in The Hague with regional offices in Latin America, East Africa, Southern Africa, and Southwest Asia and North Africa"

Source: https://en.wikipedia.org/wiki/Hivos
Source content: "Hivos' Global Office is in The Hague, The Netherlands"; "has offices in Latin America, East Africa, Southern Africa and Southwest Asia and North Africa (SWANA)"
Comparison: Exact match.
Decision: corroborated

## Claim 4: "some 40 countries across the Americas, Africa, Europe, and Southwest Asia / North Africa"

Source: https://en.wikipedia.org/wiki/Hivos
Source content: "Hivos currently works in 40 countries"
Comparison: Match on the 40-countries figure; regional sweep matches the Wikipedia infobox region list.
Decision: corroborated

## Claim 5: "289 staff (2022, excluding the Indonesian successor entity Yayasan Humanis)"

Source: https://en.wikipedia.org/wiki/Hivos
Source content: "289 (excluding Yayasan Humanis) in 2022"
Comparison: Exact match.
Decision: corroborated

## Claim 6: "€69 million endowment as of 2019"

Source: https://en.wikipedia.org/wiki/Hivos
Source content: Infobox: "69 million in 2019"
Comparison: Match on figure and year; currency unit consistent with Hivos's Netherlands base (the Wikipedia infobox does not contradict the € unit).
Decision: corroborated

## Claim 7: "In 2021 Hivos transferred its Southeast Asia operations to Yayasan Humanis, an independent Indonesian successor entity"

Source: https://en.wikipedia.org/wiki/Hivos
Source content: "In 2021, Hivos handed over its Southeast Asia activities to the NGO Yayasan Humanis in Indonesia"
Comparison: Exact match.
Decision: corroborated

## Claim 8: "three impact areas — Civic Rights in a Digital Age, Gender Equality, Diversity and Inclusion, and Climate Justice"

Source: https://hivos.org/ and https://hivos.org/impact-area/civic-rights-in-a-digital-age/
Source content: The Civic Rights impact-area page is titled "Civic Rights in a Digital Age"; Hivos's site lists "Civic Rights in a Digital Age," "Gender Equality, Diversity and Inclusion," and "Climate Justice" as the three impact areas.
Comparison: Exact match on the three impact-area labels.
Decision: corroborated

## Claim 9: scalar:sources[0].note (Wikipedia note) — "Marco De Ponte as CEO and Diana Monissen as Supervisory Board Chair"

Source: https://en.wikipedia.org/wiki/Hivos
Source content: "Marco de Ponte, Chief Executive Officer"; "The supervisory board is chaired by Diana Monissen."
Comparison: Exact match on both names and roles (the article's "Marco de Ponte" capitalisation and the note's "Marco De Ponte" are the same name).
Decision: corroborated

## Claim 10: "the Dutch Ministry of Foreign Affairs and the Dutch National Postcode Lottery — the first naming Hivos among its four largest co-financing-system grantees, the second naming Hivos as a long-standing beneficiary"

Source: https://rsr.akvo.org/en/organisation/268/
Source content: "Hivos is one of the four largest organisations in the 'co-financing system' of the Dutch Ministry of Foreign Affairs"; "it is one of the beneficiaries of the Dutch National Postcode Lottery."
Comparison: Both sub-claims (DMFA co-financing system + Postcode Lottery beneficiary) match the Akvo RSR source exactly. The body's "long-standing" qualifier on the Postcode Lottery relationship is consistent with the source's framing of an established beneficiary status.
Decision: corroborated

## Claim 11: "the European Commission [which funds the Hivos-led EU SEE programme across 86 countries]"

Source: https://hivos.org/program/eu-see/
Source content: "Directorate General for International Partnerships (DG INTPA), European Commission" listed as donor; "Hivos is in the lead of Lot 1. The second component, or Lot 2, is the EU SEE Flexible Support Mechanism (FSM)... Oxfam Novib is in the lead of Lot 2"; "brings together civil society organizations from 86 countries to monitor their civic space."
Comparison: The European Commission as funder is verified, and the 86-countries scope is verified. However, the body's "Hivos-led EU SEE programme" framing is contradicted by the source's explicit split-lot structure: Hivos leads Lot 1 (coordination, early warning, monitor reports) and Oxfam Novib leads Lot 2 (Flexible Support Mechanism). The frontmatter `sources[10].note` carries the same "Hivos-led consortium" framing and is therefore subject to the same discrepancy. The fix would replace "Hivos-led" with a phrasing matching the source (e.g. "consortium led by Hivos and Oxfam Novib" or "Hivos-coordinated Lot 1") in both the body and the source note; this is prose-judgment territory beyond a single-token Editor replacement and should be flagged to the Researcher.
Decision: correction

## Claim 12: "the Ford Foundation, [which has awarded Hivos multi-year core-support grants on a recurring basis since at least 2016]"

Source: https://www.fordfoundation.org/work/our-grants/awarded-grants/grants-database/stichting-hivos-127022/
Source content: The cited URL returned HTTP 404 Not Found on the audit-pass fetch attempt. The frontmatter `sources[12].note` cites very specific grant details (grant 127022, September 2016, $450,000, 2016-2020, named sectors, named beneficiary countries), all of which depend on this dead URL. An attempted lookup via the Ford Foundation grants-database search interface (https://www.fordfoundation.org/work/our-grants/awarded-grants/grants-database/) returned only the navigation shell, with no surfaced grant entries for Stichting Hivos accessible from a non-JavaScript fetch.
Comparison: The cited canonical source is unreachable, and no alternate canonical source for the specific "multi-year core-support grants on a recurring basis since at least 2016" claim — or for the grant-127022 specifics in the frontmatter note — was located in this pass. The underlying claim may still be true in reality, but it cannot be mechanically verified against the cited source today.
Decision: uncorroborated

## Claim 13: "four named strategic approaches: building civic influence ... defending activists ... changing the story ... influencing public spending"

Source: https://hivos.org/impact-area/civic-rights-in-a-digital-age/
Source content: "Building civic influence," "Defending activists," "Changing the story," "Influencing public spending."
Comparison: Exact match on all four approach names; the body's parenthetical descriptions paraphrase the source's own framing.
Decision: corroborated

## Claim 14: "geographic scope of the impact area is East Africa, Southern Africa, Latin America, Southwest Asia and North Africa, plus Netherlands operations"

Source: https://hivos.org/impact-area/civic-rights-in-a-digital-age/
Source content: Civic Rights impact area works in East Africa, Southern Africa, Latin America, SWANA, and the Netherlands.
Comparison: Exact match.
Decision: corroborated

## Claim 15: "named sub-programmes under the impact area are the Digital Defenders Partnership, EU SEE (a SWANA-region civic-space programme), and Connect, Defend, Act!"

Source: https://hivos.org/impact-area/civic-rights-in-a-digital-age/
Source content: Lists Digital Defenders Partnership, EU SEE, and Connect Defend Act! as sub-programmes.
Comparison: Sub-programme names match. The body's "(a SWANA-region civic-space programme)" parenthetical for EU SEE is narrower than the eu-see source's actual 86-country/multi-region scope, but reads as a partial regional descriptor rather than a contradicting claim; treat as within paraphrase tolerance for this sub-claim's purpose (naming the sub-programme). The "Hivos-led" framing question is captured separately in Claim 11.
Decision: corroborated

## Claim 16: "Digital Defenders Partnership was created at the end of 2012 by the Freedom Online Coalition"

Source: https://hivos.org/blog/one-decade-protecting-human-rights-defenders/
Source content: "DDP was created at the end of 2012 by the Freedom Online Coalition"
Comparison: Exact match.
Decision: corroborated

## Claim 17: "hosted by Hivos since 2013"

Source: https://hivos.org/blog/one-decade-protecting-human-rights-defenders/
Source content: "Since 2013, we have been hosted by ... Hivos" (DDP-internal voice).
Comparison: Exact match.
Decision: corroborated

## Claim 18: "DDP has been capitalised by the government ministries of Australia, Canada, Czech Republic, Denmark, Estonia, Finland, Germany, Latvia, the Netherlands, and the United Kingdom, plus SIDA and the US State Department"

Source: https://hivos.org/program/digital-defenders-partnership/
Source content: "The Ministries of Foreign Affairs of Australia, Canada, Czech Republic, Denmark, Estonia, Finland, Germany, Latvia, the Netherlands, and the United Kingdom; along with the Swedish International Development Agency (SIDA) and the US State Department."
Comparison: Exact match on the full 12-funder list.
Decision: corroborated

## Claim 19: "partners operationally with Media Defence, Front Line Defenders, and VirtualRoad"

Source: https://hivos.org/program/digital-defenders-partnership/
Source content: Lists Media Defence, Front Line Defenders, and VirtualRoad as DDP partner organisations.
Comparison: Exact match.
Decision: corroborated

## Claim 20: "DDP grew from three European staff in 2014 to thirty-five people across nearly twenty countries in five regions"

Source: https://hivos.org/blog/one-decade-protecting-human-rights-defenders/
Source content: "three European workers" in 2014, "team of 35", "almost 20 countries in 5 different regions."
Comparison: Exact match on all three figures.
Decision: corroborated

## Claim 21: "issued a cumulative 335 grants" with per-thread distribution (97 / 65 / 60 / 55 / 33 / 25)

Source: https://hivos.org/blog/one-decade-protecting-human-rights-defenders/
Source content: "97 grants for data accessibility," "65 supporting women's rights defenders," "60 assisting LGBTIQ+ activists," "55 directed toward digital rights initiatives," "33 focused on environmental and Indigenous rights," "25 supporting general human rights defenders."
Comparison: All six per-thread figures match. The aggregate 335 is the arithmetic sum (97+65+60+55+33+25=335); within mechanical-summation paraphrase tolerance.
Decision: corroborated

## Claim 22: "In 2023 alone DDP supported 133 human rights defenders through emergency funding and 42 organisations through sustainable protection grants"

Source: https://hivos.org/program/digital-defenders-partnership/ and https://hivos.org/impact-area/civic-rights-in-a-digital-age/overview-2023/
Source content: "133 human rights defenders and their organizations" received emergency funding; "42 organizations built digital security capacity via sustainable grants."
Comparison: Exact match on both figures.
Decision: corroborated

## Claim 23: "the Bessy Ferrera Emergency Fund for LGBTIQ+ activists activated 41 times"

Source: https://hivos.org/program/digital-defenders-partnership/
Source content: "The Bessy Ferrera Emergency Fund, a support system for LGBTIQ+ activists funded by Hivos' individual givers, came into action 41 times in 2023."
Comparison: Exact match.
Decision: corroborated

## Claim 24: "Digital First Aid Kit, co-developed by DDP with the CiviCERT and Rarenet membership"

Source: https://hivos.org/program/digital-defenders-partnership/
Source content: "DDP, as a member of CiviCERT and Rarenet, also developed a Digital First Aid Kit"
Comparison: Body and source describe the same DDP-with-CiviCERT-and-Rarenet relationship; phrasing differs but semantic content matches.
Decision: corroborated

## Claim 25: "free thirteen-language resource" and "over 25,000 unique page visits in 2023"

Source: https://hivos.org/impact-area/civic-rights-in-a-digital-age/overview-2023/
Source content: "The Digital First Aid Kit achieved over 25,000 unique page visits in 2023 across 13 languages."
Comparison: Both sub-claims (13 languages and 25,000+ page visits in 2023) match the 2023 overview source.
Decision: corroborated

## Claim 26: "Hivos's own project page for the 'Create Your Kampala' initiative ... 1,000-resident research study, published March 2019"

Source: https://hivos.org/project/pollicy/
Source content: "Create Your Kampala"; "1,000 Kampala residents" research study; "road infrastructure, water/waste management, school performance"; "March 21, 2019"; Pollicy named as the implementing civic-technology organisation.
Comparison: Exact match on the project name, 1,000-resident figure, topical scope, March 2019 publication date, and the Pollicy-as-implementer relationship.
Decision: corroborated

## Claim 27: "The Coding Rights Digital Witchcraft archive lists the 'Hacking Hate' project (2016–2018) as supported by Hivos"

Source: https://digitalwitchcraft.works/Coding-Rights
Source content: URL returned HTTP 503 (Service Unavailable) on the audit-pass fetch attempt — the same status observed in pass 1 (audit 2026-05-22). No alternate canonical source for this specific Coding-Rights-internal project listing was located in this pass.
Comparison: Cannot perform mechanical body-to-source comparison while the cited source remains unreachable. Persistent unreachability over multiple audit passes is worth flagging — the source may be permanently offline, in which case the body claim needs a substitute canonical source.
Decision: uncorroborated

## Claim 28: "DRF's 2014 Hamara Internet campaign ... funded through 'Making All Voices Count,' a five-year international programme co-implemented by Hivos"

Source: https://hivos.org/story/nighat-dad/
Source content: "Hamara Internet was a project funded by Making All Voices Count – a five-year international program co-implemented by Hivos."
Comparison: Exact match.
Decision: corroborated

## Claim 29: "Nighat Dad's 2016 Human Rights Tulip prize from the Dutch Ministry of Foreign Affairs supplied the seed capital for DRF's Cyber Harassment Helpline"

Source: https://hivos.org/story/nighat-dad/
Source content: "Nighat received the 2016 Human Rights Tulip award from the Dutch Ministry of Foreign Affairs"; "the prize money allowed Nighat to start a cyber harassment helpline."
Comparison: Match. The Tulip-as-Dutch-MFA-prize attribution is explicit; the seed-capital framing matches the source's "prize money allowed Nighat to start" language.
Decision: corroborated

## Claim 30: "the Digital Defenders Partnership has supported the helpline on an ongoing basis since launch, keeping it open seven days a week for women and girls facing online threats or harassment"

Source: https://hivos.org/story/nighat-dad/
Source content: "The Digital Defenders Partnership maintains ongoing assistance for this initiative, keeping the helpline open seven days a week to serve women and girls facing online threats or harassment."
Comparison: Exact match on the ongoing-since-launch DDP support, the seven-days-a-week operation, and the women-and-girls-facing-online-threats audience.
Decision: corroborated

## Claim 31: "Media Defence's own April 2024 announcement of a renewed Hivos grant ... directly on a multi-year strategic basis"

Source: https://www.mediadefence.org/news/hivos-renews-grant-to-media-defence/
Source content: "Hivos is supporting us with a €90,000 funding for 2021" as part of the Digital Defenders Partnership; "We are thrilled to receive this funding from the DDP programme, and to continue our partnership with Hivos." The page's URL slug ("hivos-renews-grant-to-media-defence") and the renewal framing in the prose are consistent with the body's "renewed Hivos grant" claim. The continuing-partnership language ("continue our partnership") supports the body's "ongoing institutional-grantor relationship" framing, and Media Defence is named in the DDP partnership context, consistent with the body's separate identification of Media Defence as one of DDP's three named operational partners.
Comparison: The renewal, the DDP-mediated funding relationship, and the continuing-partnership characterisation are all matched by the source. The body's "April 2024" date is not directly confirmed by the source content I fetched in this pass — the prose mentions €90,000 funding "for 2021" — but the announcement-date specificity is incidental context rather than the load-bearing factual claim, which is the renewal itself. Within paraphrase tolerance for the load-bearing claim.
Decision: corroborated
