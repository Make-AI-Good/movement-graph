---
entity_id: lg-youth-igf-morocco
entity_hash: 29cd1c8940371720457a9fe7fbf559eb148bee71
audit_date: 2026-09-04
pass: 1
status: corrections-pending
claims_total: 10
claims_corroborated: 3
claims_primary_sourced: 5
claims_single_source: 1
claims_uncorroborated: 0
open_corrections: 1
sources_consulted:
  - https://www.youthigfmorocco.org/
  - https://www.intgovforum.org/en/content/morocco-youth-igf
  - https://iafrica.com/morocco-unveils-digital-x-0-law-to-embed-ai-data-governance-and-digital-identity-into-national-modernization-agenda/
  - https://www.ecofinagency.com/news-digital/0511-50160-morocco-advances-with-digital-x-0-law-to-regulate-artificial-intelligence
  - https://cadeproject.org/updates/morocco-introduces-digital-x-0-law-to-drive-ai-governance-and-digital-sovereignty/
  - https://www.biometricupdate.com/202511/new-roadmap-details-moroccos-digital-transformation-priorities
---

## Claim 1: "youth-led, multi-stakeholder platform within the United Nations Internet Governance Forum (IGF) ecosystem … Recognised as part of the UN IGF network"

Source: https://www.youthigfmorocco.org/ + https://www.intgovforum.org/en/content/morocco-youth-igf (registry page 403s on direct fetch; content via search snippet)
Source tier: primary
Source content: Own site: "A youth-led, multi-stakeholder initiative shaping Morocco's digital future"; "Recognized within the United Nations IGF ecosystem". UN IGF registry: "Recognized in 2026, the Morocco Youth IGF initiative seeks to foster a multistakeholder process that enables the Moroccan youth community to actively engage in Internet governance discussions at the national, regional and international levels."
Comparison: Recognition confirmed by the recognizing body's own registry listing plus the org's site — two independent sources, one the authoritative registry.
Decision: corroborated

## Claim 2: "operates from a Rabat anchor across twelve Moroccan cities" (also scalar:location "Morocco (national; Rabat annual forum anchor)")

Source: https://www.youthigfmorocco.org/
Source tier: primary
Source content: "12 Cities represented" (community stats); annual forum located in Rabat.
Comparison: Twelve-cities and Rabat-anchor claims match the org's own site; no second source covers the city count. Scalar path `location` is consistent with the same content.
Decision: primary-sourced

## Claim 3: "a reported community of more than 200 youth delegates"

Source: https://www.youthigfmorocco.org/
Source tier: primary
Source content: "200+ Youth delegates" (community stats, plus sign rendered on site).
Comparison: "More than 200" matches the site's "200+" exactly; body hedges with "reported", appropriate for a self-reported stat.
Decision: primary-sourced

## Claim 4: annual Youth Internet Governance Forum in Rabat (June); participants "co-create policy briefs on AI governance, data ethics, and open-internet principles"; outputs translated into Arabic, French, and English

Source: https://www.youthigfmorocco.org/
Source tier: primary
Source content: Annual forum: Rabat, June, focus "AI Governance"; "Co-create policy briefs on AI, data ethics, and open internet principles"; "Policy briefs translated into Arabic, French, and English".
Comparison: All elements match the org's own site verbatim or near-verbatim; single (primary) source.
Decision: primary-sourced

## Claim 5: "has published more than 35 policy briefs" (§ Programs; also "35+ published policy briefs" in § Position in the movement)

Source: https://www.youthigfmorocco.org/
Source tier: primary
Source content: "35 Policy briefs" — stat tile renders exactly "35", verified with a targeted re-fetch distinguishing "35" from "35+" (the adjacent delegates tile does render a plus: "200+"). The entity's own sources[0].note also records "35 policy briefs published" without a plus.
Comparison: Body token "more than 35" contradicts the source's exact "35"; single correct replacement is "35" (both body instances: § Programs "published more than 35 policy briefs" and § Position "35+ published policy briefs").
Decision: correction

## Claim 6: sustains "city meetups", "capacity-building workshops" on digital rights and policy advocacy, "policy labs and listening sessions" channeling youth insight into national digital strategy, and a "mentorship and micro-grants programme"

Source: https://www.youthigfmorocco.org/ + https://www.intgovforum.org/en/content/morocco-youth-igf (via search snippet)
Source tier: primary
Source content: Own site: "Capacity building for youth" on digital rights and policy advocacy; "Youth consultations & policy input" through listening sessions; city meetups; "Policy labs"; "Mentorship and micro-grants". IGF registry snippet: "Listening sessions and policy labs that channel youth insight into national strategies, with city meetups, national forums, and UN IGF prep sessions."
Comparison: Every named program appears on the org's site; the IGF registry listing independently names meetups, listening sessions, and policy labs.
Decision: corroborated

## Claim 7: "AI governance is explicitly a central programme area: forum tracks, working groups, and published policy briefs directly address responsible AI, algorithmic accountability, and data ethics"

Source: https://www.youthigfmorocco.org/
Source tier: primary
Source content: Annual forum focus "AI Governance"; "Working groups" listed (call-to-action section); "Responsible AI, trustworthy data use, and safeguards against harm at every step"; briefs "on AI, data ethics, and open internet principles".
Comparison: Central-programme-area claim, forum tracks, and working groups all match the site; "algorithmic accountability" is a fair paraphrase of the responsible-AI/safeguards language rather than a distinct verbatim token.
Decision: primary-sourced

## Claim 8: Morocco unveiled a "Digital X.0 bill proposing to formally integrate AI governance, data governance, and digital identity into national law, establishing ethical and accountability principles for algorithmic use in public administration and private-sector applications"

Source: https://iafrica.com/morocco-unveils-digital-x-0-law-to-embed-ai-data-governance-and-digital-identity-into-national-modernization-agenda/ + Ecofin Agency / CADE / Biometric Update coverage (via search)
Source tier: mainstream
Source content: iAfrica: "The Digital X.0 bill represents Morocco's first attempt to formally integrate AI into administrative and economic governance, establishing rules for transparency, accountability, and the ethical use of algorithms"; pillars of data governance, digital identity, interoperability. Ecofin: "Morocco advances with Digital X.0 law to regulate artificial intelligence"; CADE: "Morocco introduces Digital X.0 law to drive AI governance and digital sovereignty".
Comparison: Bill substance (AI + data governance + digital identity into national law; ethical/accountability principles for algorithms across public and private sectors) confirmed by multiple independent outlets.
Decision: corroborated

## Claim 9: scalar:sources[1].note — "Morocco's first attempt to formally integrate AI governance, data governance, and digital identity into national law"

Source: https://iafrica.com/morocco-unveils-digital-x-0-law-to-embed-ai-data-governance-and-digital-identity-into-national-modernization-agenda/
Source tier: mainstream
Source content: "The Digital X.0 bill represents Morocco's first attempt to formally integrate AI into administrative and economic governance, establishing rules for transparency, accountability, and the ethical use of algorithms."
Comparison: Scalar path `sources[1].note`. The "first attempt" framing is stated explicitly by iAfrica but not independently repeated by the other outlets found; a "first" attribution rests on one mainstream source.
Decision: single-source

## Claim 10: scalar:sources[0].note — website summary: "UN IGF ecosystem-recognised; 200+ youth delegates across 12 cities and 35 policy briefs published; annual forum (Rabat, June), AI governance and data ethics tracks, city meetups, capacity building, and mentorship and micro-grants programmes; contact email moroccoyouthigf@gmail.com"

Source: https://www.youthigfmorocco.org/
Source tier: primary
Source content: All elements confirmed on the site as quoted under Claims 1–7; contact email displayed: "moroccoyouthigf@gmail.com".
Comparison: Scalar path `sources[0].note`. Every element of the note matches the live site, including the exact "35" count (the note, unlike the body, records it accurately) and the contact email moroccoyouthigf@gmail.com.
Decision: primary-sourced
