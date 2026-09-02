---
entity_id: fund-renewable-freedom-foundation
entity_hash: b696304b05d3b7cc0617a66c2c144336cd14f0bc
audit_date: 2026-09-02
pass: 1
status: corrections-pending
claims_total: 21
claims_corroborated: 1
claims_primary_sourced: 13
claims_single_source: 1
claims_uncorroborated: 2
open_corrections: 4
sources_consulted:
  - https://stiftungen.bayern.de/stiftung/11718
  - https://renewablefreedom.org/grants/history/
  - https://renewablefreedom.org/projects/technology-and-human-rights-hub/
  - https://renewablefreedom.org/projects/european-digital-rights-small-grants-program/
  - https://renewablefreedom.org/projects/digital-whistleblowing-fund/
  - https://renewablefreedom.org/
  - https://edri.org/tag/renewable-freedom-foundation/
  - https://edri.org/our-work/small-grants-support-digital-rights-groups/
  - https://digitalfreedomfund.org/digital-freedom-fund-launches-to-support-digital-rights-litigation-in-europe/
  - https://digitalfreedomfund.org/funding/
  - https://digitalfreedomfund.org/about/
  - https://digitalfreedomfund.org/grants/
  - https://digitalfreedomfund.org/uk-home-office-visa-application-streaming-algorithm/
---

## Claim 1: "established on 26 July 2012 by Georg Schäff, legally registered in Munich, Bavaria, as an allgemeine Stiftung des bürgerlichen Rechts"

Source: https://stiftungen.bayern.de/stiftung/11718
Source tier: primary
Source content: Name "Stiftung Erneuerbare Freiheit"; founding date "26.07.2012"; founder "Herr Geog Schäff" [registry's own spelling]; seat "München, Landeshauptstadt, kreisfreie Stadt, Oberbayern"; legal form "Stiftung des bürgerlichen Rechts"
Comparison: Bavarian government registry confirms date, founder, Munich seat, and civil-law-foundation form (registry spells the founder "Geog", an evident registry typo). Also covers scalar:sources[0].note and the focus scalar's founding sentence.
Decision: primary-sourced

## Claim 2: "operates with an English-language surface at renewablefreedom.org and a German-language counterpart at erneuerbare-freiheit.de"

Source: https://renewablefreedom.org/
Source tier: primary
Source content: Homepage carries "a language toggle link to a German site at erneuerbare-freiheit.de"
Comparison: The foundation's own homepage links its German-language counterpart; both surfaces exist as claimed.
Decision: primary-sourced

## Claim 3: "The Foundation's stated aim is to protect and preserve civil liberties, particularly in the digital landscape, working through civic education, networking, civil-society support, and grantmaking"

Source: web search snippets of renewablefreedom.org site text (mission page not directly fetchable: homepage carries only a Krishnamurti quote and nav; /the-foundation/ 404s)
Source tier: primary
Source content: "The Renewable Freedom Foundation aims to protect and preserve civil liberties, especially in the digital landscape. Their mission is based on a vision of the digital sphere that truly respects and promotes human rights and liberties."
Comparison: Aim phrase matches the foundation's own site text via search snippet; the four-method list (civic education, networking, civil-society support, grantmaking) is consistent with the registry's Stiftungszweck (societal education per liberal-democratic principles) and the documented programs but was not independently confirmable as a list on a fetched page.
Decision: single-source

## Claim 4: "A Berlin-based coworking and coordination space for developers building privacy-enhancing and anti-censorship tools, investigative journalists, and political activists ... early infrastructure for ... a full-fledged digital freedom institute. The Foundation cites Berlin's historical experience as a surveilled city as the rationale"

Source: https://renewablefreedom.org/projects/technology-and-human-rights-hub/
Source tier: primary
Source content: "used by developers working on technology that respect human rights, such as anti-censorship tools and privacy enhancing communication technologies, as well as by investigative journalists and activists"; "designed to grow into a full-fledged digital freedom institute"; "Berlin, with its added historical experience of mass surveillance in the GDR, provides the best setting for a technology activism and policy hub"
Comparison: All hub claims match the foundation's own project page. Also covers scalar:sources[1].note.
Decision: primary-sourced

## Claim 5: Direct portfolio 2014–2016 — "Large grants went to GNUnet ... the Activist Hub Berlin"; "Privacy International, jointly with the Open Rights Group, received a large grant"; "La Quadrature du Net received a small grant"; other grantees Library of Freedom, Open Knowledge Foundation, iRights.info, Stiftung Neue Verantwortung (privacy research); "Small (under €10k), Medium (under €50k), and Large (over €50k)"

Source: https://renewablefreedom.org/grants/history/
Source tier: primary
Source content: "Range: small (<10k EUR); medium (<50k EUR); large (>50k EUR)"; Large: GNUnet (2014-2016), Activist Hub Berlin (2015-2016), "Joint project Privacy International/Open Rights Group UK" (2014); Medium: Stiftung Neue Verantwortung (2014) "Privacy Project"; Small: La Quadrature du Net, Library of Freedom, Open Knowledge Foundation, iRights.info, and others
Comparison: Grant tiers, thresholds, years, and grantee names match the foundation's published past-grants page for every entity named in this claim (Tor is handled separately in Claim 6; the body makes no tier claim for SNV, so its "privacy research project" description passes here).
Decision: primary-sourced

## Claim 6: "Large grants went to ... the Tor Anonymization Project for Tor operations and exit nodes"

Source: https://renewablefreedom.org/grants/history/
Source tier: primary
Source content: Tor Anonymization Project, 2014-2016, listed under category **medium** (<50k EUR): "Support for Tor and the Torservers.net project; our own Tor exit"
Comparison: The body places Tor among the Large (>€50k) grants; the foundation's own grants page lists it as a Medium grant (<€50k). Single-token fix: "Large" → "Medium" for the Tor entry (i.e., move Tor out of the Large-grants sentence). The same error appears in scalar:sources[3].note (Claim 19).
Decision: correction

## Claim 7: "In 2017 the Foundation designed and launched the European Digital Rights Fund in partnership with European Digital Rights (EDRi), inviting over 100 digital-rights experts from the EDRi network to participate in a peer-driven grantmaking platform"

Source: https://renewablefreedom.org/projects/european-digital-rights-small-grants-program/ ; https://edri.org/our-work/small-grants-support-digital-rights-groups/
Source tier: primary
Source content: RFF page: "In 2017, we invited over 100 leading digital rights experts from the European Digital Rights Initiative (EDRi) network to participate in an innovative peer-driven support platform". EDRi (6 Feb 2017): the program was "designed by the Renewable Freedom Foundation (RFF)" with "peer-led decisions from our digital rights community"
Comparison: Two independent publishers (RFF and EDRi) confirm the 2017 launch, RFF's designer role, the 100+ experts figure, and the peer-driven model.
Decision: corroborated

## Claim 8: "grants up to €5,000 for workshops, cross-sector meetings, project planning, and small project execution, and micro-grants below €2,000 for immediate operational needs such as travel, campaign materials, and essential equipment ... operates on a rolling basis through the EDRi membership network"

Source: https://edri.org/our-work/small-grants-support-digital-rights-groups/
Source tier: primary
Source content: "small grants are capped at 5 000 euro" (for "workshops and meetings with other civil society organisations, project planning, and the inception and execution of small projects"); "micro grants, below 2 000 euro" (for "travel for all-volunteer organisations, flyers for quick campaigns, the replacement or initial purchase of essential equipment"); "submissions are evaluated on a rolling basis, and independent from each other"
Comparison: All amounts, uses, and the rolling basis match the EDRi launch article (a foundational program document by the operating partner). Note: the current RFF project page no longer carries these amounts — see Claim 18.
Decision: primary-sourced

## Claim 9: Digital Whistleblowing Fund — "programme supporting organisations standing up digital whistleblowing platforms, providing financial, operational, and strategic support across strategy, law, IT, and security to investigative journalists, human-rights and environmental activists, and anti-corruption organisations. Thematic calls, with an initial focus on anti-corruption activism ... selection committee drawn from whistleblowing, journalism, activism, anti-corruption, and hacking fields"

Source: https://renewablefreedom.org/projects/digital-whistleblowing-fund/
Source tier: primary
Source content: "grassroots organisations that set up digital whistleblowing projects, including investigative journalists and groups, human rights and environmental activists, anti-corruption groups"; "apply for and receive financial, operational and strategic support"; skills "in essential areas: strategic, organisational, legal, IT, and security"; "runs periodical thematic calls. Our initial call is for 'Anti-corruption activism.'"; "A selection committee composed of key individuals and organisations from the whistleblowing, journalism, activism, anti-corruption and hacking ecosystems"
Comparison: All whistleblowing-fund claims match the foundation's own project page. Also covers scalar:sources[4].note.
Decision: primary-sourced

## Claim 10: "one of four seed funders of the Digital Freedom Fund at its launch on 25 January 2018 ... capitalised at founding by Adessium Foundation, Open Society Foundations, Omidyar Network, and the Renewable Freedom Foundation" (+ scalar:sources[5].note naming "founding director Nani Jansen Reventlow")

Source: https://digitalfreedomfund.org/digital-freedom-fund-launches-to-support-digital-rights-litigation-in-europe/
Source tier: primary
Source content: "Launched on 25 January, the Digital Freedom Fund (DFF) supports strategic litigation to advance and protect digital rights in Europe"; "The Digital Freedom Fund is grateful for the support of the Open Society Foundation, Adessium Foundation, Omidyar Network and the Renewable Freedom Foundation"; "DFF is led by Nani Jansen Reventlow, an experienced human rights lawyer and strategic litigator"
Comparison: The launch announcement (2018) names exactly the four funders claimed, the 25 January launch, the litigation mission, and Jansen Reventlow as lead. Also covers scalar:sources[5].note.
Decision: primary-sourced

## Claim 11: "The DFF's funding-transparency page lists RFF among its previous funders" alongside Robert Bosch Stiftung, Stiftung Mercator, Sigrid Rausing Trust, EU CERV programme, and the Democracy and Media Foundation

Source: https://digitalfreedomfund.org/funding/
Source tier: primary
Source content: Previous funders: "Robert Bosch Stiftung, Mercator Stiftung, Renewable Freedom Foundation and the Sigrid Rausing Trust, and project funding from the Citizens, Equality, Rights and Values (CERV) programme of the European Union and the Democracy and Media Foundation (Stichting Democratie en Media)"
Comparison: RFF appears among previous funders exactly alongside the organisations the body and scalar:sources[6].note name.
Decision: primary-sourced

## Claim 12: "Since 2018 the DFF has made nearly 150 grants"

Source: https://digitalfreedomfund.org/about/ ; https://digitalfreedomfund.org/grants/
Source tier: primary
Source content: About page: "150 Supported grants". Grants page: "Since 2018, we have supported more than 100 groups and individuals, funded through 164 grants worth EUR 5.5 million."
Comparison: DFF's own two pages currently disagree on the grant count (150 vs 164 — different update vintages). Canonical sources conflict; no winner picked.
Decision: uncorroborated

## Claim 13: "totalling over €5 million"

Source: https://digitalfreedomfund.org/grants/
Source tier: primary
Source content: "funded through 164 grants worth EUR 5.5 million" (about page concurs: "€5.5 million Awarded")
Comparison: €5.5M satisfies "over €5 million"; both DFF pages agree on the amount.
Decision: primary-sourced

## Claim 14: "across 30 countries"

Source: https://digitalfreedomfund.org/about/
Source tier: primary
Source content: "30 Countries"
Comparison: Matches DFF's own stated geographic reach.
Decision: primary-sourced

## Claim 15: "supporting some 90 organisations"

Source: https://digitalfreedomfund.org/grants/
Source tier: primary
Source content: "Since 2018, we have supported more than 100 groups and individuals"
Comparison: The body's "some 90 organisations" contradicts DFF's current grants page, which states more than 100 groups and individuals (the figure has moved since drafting). Single replacement: "some 90 organisations" → "more than 100 groups and individuals". Fix location: body § Seed funding of the Digital Freedom Fund (the focus scalar does not carry this figure).
Decision: correction

## Claim 16: "producing over 200 positive legal, policy, and social outcomes"

Source: https://digitalfreedomfund.org/about/
Source tier: primary
Source content: "200+ Positive outcomes" — "Legal, policy, and social outcomes"
Comparison: Matches DFF's own stated outcomes figure and its legal/policy/social framing.
Decision: primary-sourced

## Claim 17: DFF-supported outcomes "ranging from the SyRI welfare-risk-scoring ruling to the Foxglove–JCWI visa-streaming algorithm challenge"

Source: https://digitalfreedomfund.org/about/ ; https://digitalfreedomfund.org/uk-home-office-visa-application-streaming-algorithm/
Source tier: primary
Source content: About page highlights work that "stopped discriminatory welfare systems," referencing support for litigation against the Dutch SyRI risk-scoring algorithm. Case page: "Foxglove and JCWI argued that the algorithm entrenched inaccurate and unfair decision making"; DFF supported the case through "an emergency grant, followed by a single instance litigation support grant for the rest of the litigation"; "In August 2020, ahead of the court hearing, the UK government announced it would halt use of the algorithm"
Comparison: DFF's own pages confirm it funded both the SyRI litigation and the Foxglove–JCWI visa-streaming challenge.
Decision: primary-sourced

## Claim 18: scalar:sources[2].note — the RFF European Digital Rights Fund page "confirms ... the grants-up-to-€5,000 structure for workshops, project planning, and small project execution, the micro-grants-below-€2,000 track for immediate needs"

Source: https://renewablefreedom.org/projects/european-digital-rights-small-grants-program/
Source tier: primary
Source content: Fetched page carries the 2017 invitation, 100+ experts, and peer-driven model, but "there are no grant sizes, funding figures, or specific monetary amounts (such as €5,000 or €2,000) listed" and no micro-grants track
Comparison: The note asserts the cited page confirms the €5,000/€2,000 specifics; the page as fetched today does not carry them (they appear in EDRi's 6 Feb 2017 article — Claim 8; the page may have changed since last_checked 2026-06-10, and Wayback is unreachable from this harness). Scalar path: sources[2].note. Not an error assertion — the underlying amounts are confirmed elsewhere; the note's page-content attribution cannot be confirmed.
Decision: uncorroborated

## Claim 19: scalar:sources[3].note — "Large grants (>€50k) to GNUnet, Activist Hub Berlin, and Tor Anonymization Project"

Source: https://renewablefreedom.org/grants/history/
Source tier: primary
Source content: Large: GNUnet, Activist Hub Berlin, Privacy International/ORG. Medium: "Tor Anonymization Project (2014-2016)" — "Support for Tor and the Torservers.net project; our own Tor exit"
Comparison: The note places Tor among the Large grants; the source lists it as Medium. Single replacement in scalar:sources[3].note: move "Tor Anonymization Project" from the Large list to the Medium list. Same error as body Claim 6.
Decision: correction

## Claim 20: scalar:sources[3].note — "Small grants (<€10k) to La Quadrature du Net (internet rights defence), Library of Freedom, Open Knowledge Foundation, iRights.info, Stiftung Neue Verantwortung (privacy research), and travel grants"

Source: https://renewablefreedom.org/grants/history/
Source tier: primary
Source content: Medium grants include "Stiftung Neue Verantwortung (2014): 'Privacy Project'"; Small grants include La Quadrature du Net, Library of Freedom, Open Knowledge Foundation, iRights.info, travel grants
Comparison: The note places Stiftung Neue Verantwortung among the Small grants; the source lists it as a Medium grant (2014, "Privacy Project"). Single replacement in scalar:sources[3].note: move "Stiftung Neue Verantwortung (privacy research)" from the Small list to the Medium list. (The body makes no tier claim for SNV and passes — Claim 5.)
Decision: correction

## Claim 21: scalar:sources[7].note — EDRi archive confirms "the February 2017 announcement that the Foundation designed a peer-led grants initiative for the EDRi community"

Source: https://edri.org/tag/renewable-freedom-foundation/
Source tier: primary
Source content: Tag archive carries "Funding is Caring: Small Grants to Support Digital Rights Groups" (6 Feb 2017) — the program was "designed by the Renewable Freedom Foundation (RFF)" with "peer-led decisions" — and "European Fund for Digital Rights Launched" (8 Feb 2017)
Comparison: The EDRi tag archive exists and carries the February 2017 announcements exactly as the note describes.
Decision: primary-sourced
