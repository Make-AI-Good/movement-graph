---
id: event-ncc-out-of-control-report-launch-2020-01
type: event
name: Norwegian Consumer Council "Out of Control" report launch and GDPR complaint filing (14 January 2020)
status: historical
confidence: high
tags: [norway, oslo, scandinavia, nordics, behavioral-advertising, surveillance-advertising, adtech, gdpr, data-protection, privacy, consumer-rights, dating-apps, health-apps, regulatory-complaints, datatilsynet, report-launch, empirical-audit, special-category-data, mnemonic, noyb, grindr]
created: 2026-06-08
last_updated: 2026-06-08
date: 2020-01-14
location: Oslo, Norway
event_type: report launch
campaign: camp-ncc-out-of-control-behavioral-advertising-2020
participating_orgs:
  - org-norwegian-consumer-council
participating_people: []
related_events: []
sources:
  - url: https://storage02.forbrukerradet.no/media/2020/01/2020-01-14-out-of-control-final-version.pdf
    last_checked: 2026-06-08
    note: '"Out of Control: How consumers are exploited by the online advertising industry" (14 January 2020) — primary source for the ten-app scope (Grindr, Tinder, OkCupid, Happn, Clue, MyDays, Perfect365, Qibla Finder, My Talking Tom 2, Wave Keyboard), the finding that these apps transmitted data to at least 135 different third parties, the summary conclusion that the adtech system represents "comprehensive and systemic illegal collection and use of personal data", and the simultaneous filing of three GDPR complaints at Datatilsynet'
  - url: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
    last_checked: 2026-06-08
    note: 'NOYB announcement of the three GDPR complaints co-filed with the NCC on 14 January 2020 — primary source for NOYB''s co-filing role, the named respondents (Grindr, Twitter''s MoPub, AT&T''s AppNexus, OpenX, AdColony, Smaato), and the complaints'' legal basis under GDPR Article 7 (absence of valid consent for special-category sexual-orientation data processing)'
  - url: https://techcrunch.com/2020/01/14/dating-and-fertility-apps-among-those-snitching-to-out-of-control-adtech-report-finds/
    last_checked: 2026-06-08
    note: 'TechCrunch coverage of the "Out of Control" report on the day of publication — independent secondary source corroborating the ten-app list, the 135-third-party finding, and the global media reach of the report at release'
  - url: https://www.citizen.org/article/popular-dating-health-apps-violate-privacy/
    last_checked: 2026-06-08
    note: 'Public Citizen''s January 2020 action page — primary source for the nine US consumer groups'' joint request to the FTC, Congress, and the state AGs of California, Texas, and Oregon; names the ACLU of California, Campaign for a Commercial-Free Childhood, Center for Digital Democracy, Consumer Action, Consumer Federation of America, Consumer Reports, EPIC, Public Citizen, and US PIRG as the nine co-signers'
  - url: https://edri.org/our-work/ncc-report-online-advertising-industry-is-out-of-control/
    last_checked: 2026-06-08
    note: 'EDRi coverage of the "Out of Control" report at release — secondary source confirming the January 2020 publication, the NCC''s framing of adtech illegality as structural rather than incidental, and the report''s positioning within the European digital-rights advocacy ecosystem'
---

# Norwegian Consumer Council "Out of Control" report launch and GDPR complaint filing (14 January 2020)

On [14 January 2020](https://storage02.forbrukerradet.no/media/2020/01/2020-01-14-out-of-control-final-version.pdf), the [Norwegian Consumer Council (Forbrukerrådet)](../organizations/org-norwegian-consumer-council.md) published "Out of Control: How consumers are exploited by the online advertising industry" — a 186-page technical investigation of data-sharing practices in ten popular consumer apps — and simultaneously filed three formal GDPR complaints at Norway's Data Protection Authority (Datatilsynet), co-filed with the privacy-law organisation NOYB. The simultaneous publication-and-complaint structure was deliberate: by converting audit findings into regulatory filings on the same day, the NCC ensured that international media coverage of the report coincided exactly with a live enforcement proceeding, making it difficult for companies or regulators to treat the findings as informational rather than actionable. The report [received media coverage in more than 70 countries](https://www.forbrukerradet.no/side/the-norwegian-consumer-council-awarded-epic-international-privacy-champion-award/) and catalysed parallel advocacy in the United States within weeks. The event anchors the [NCC Out of Control campaign](../campaigns/camp-ncc-out-of-control-behavioral-advertising-2020.md) and is the corpus's first Scandinavia-based event entry.

## The audit methodology and scope

The NCC developed the investigation in collaboration with Norwegian cybersecurity firm Mnemonic, which performed the technical traffic analysis, and independent US researcher Zach Edwards. Ten consumer apps were selected to represent high-risk categories — dating, women's health, religion, children's games, and utilities — that handled personal data users might expect to be treated with heightened sensitivity. The apps were [Grindr, Tinder, OkCupid, and Happn](https://storage02.forbrukerradet.no/media/2020/01/2020-01-14-out-of-control-final-version.pdf) (dating), Clue and MyDays (women's health and period tracking), Perfect365 (beauty), Qibla Finder (Muslim prayer direction), My Talking Tom 2 (children's game), and Wave Keyboard (keyboard). The methodology intercepted and catalogued network traffic from each app, identifying every third-party recipient of user data and characterising the data types transmitted.

## Core findings

The traffic analysis found that the ten apps were [transmitting user data to at least 135 different third parties](https://storage02.forbrukerradet.no/media/2020/01/2020-01-14-out-of-control-final-version.pdf) involved in advertising or behavioral profiling. The most sensitive data flows involved Grindr: the gay and bisexual dating app's pipeline exposed GPS location, IP addresses, advertising identifiers, age, gender, and — by the nature of the app — the user's sexual orientation, a special-category data type under GDPR Article 9 commanding the regulation's strongest consent and processing protections. The report's summary conclusion was that the adtech system ["is based on the comprehensive and systemic illegal collection and use of personal data"](https://storage02.forbrukerradet.no/media/2020/01/2020-01-14-out-of-control-final-version.pdf) — framing the problem as structural to behavioral advertising as a business model, not a collection of individual design failures correctable through better consent interfaces. [EDRi](../organizations/org-edri.md) characterised this framing at release as demonstrating that adtech illegality was [structural rather than incidental](https://edri.org/our-work/ncc-report-online-advertising-industry-is-out-of-control/).

## The GDPR complaints

On the same day, the NCC, [in cooperation with NOYB](https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and), filed three complaints at Datatilsynet. The complaints targeted Grindr directly (for sharing sexual orientation — a special-category datum under GDPR Article 9 — with adtech partners without a valid legal basis), and the five adtech companies that had received Grindr users' data: Twitter's MoPub, AT&T's AppNexus (later Xandr), OpenX, AdColony, and Smaato. The core legal argument was that Grindr's consent mechanism — requiring users to accept the full privacy policy to access the app, with no granular ask about third-party sharing — did not constitute the freely given, specific, informed, and unambiguous consent that GDPR Article 7 requires; and that this defect propagated to every adtech recipient downstream, who accordingly also lacked a valid legal basis for processing.

## Immediate international response

The "Out of Control" report's US reception produced parallel action within weeks. Nine American consumer and privacy organisations — the ACLU of California, the Campaign for a Commercial-Free Childhood, the Center for Digital Democracy, Consumer Action, the Consumer Federation of America, Consumer Reports, the Electronic Privacy Information Center (EPIC), Public Citizen, and US PIRG — [jointly urged](https://www.citizen.org/article/popular-dating-health-apps-violate-privacy/) the Federal Trade Commission, congressional lawmakers, and the state attorneys general of California, Texas, and Oregon to investigate the apps identified in the NCC report. The joint request called for a strong federal digital privacy law with a data protection agency, a private right of action, and strong enforcement mechanisms. The US coalition response, drawing nine major advocacy organisations across a jurisdictional and cultural divide within weeks of a Norwegian DPA filing, demonstrated that the NCC's audit-to-complaint methodology could function as a transnational civil-society forcing mechanism — a single technically rigorous report converting simultaneously into enforcement pressure in Europe and legislative pressure in the United States.
