---
entity_id: event-ncc-out-of-control-report-launch-2020-01
entity_hash: 265fee62cabf10a6a8785ddcbd6f7d4649df239e
audit_date: 2026-08-31
pass: 1
status: supported
claims_total: 18
claims_corroborated: 7
claims_primary_sourced: 7
claims_single_source: 2
claims_uncorroborated: 2
open_corrections: 0
sources_consulted:
  - https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
  - https://edri.org/our-work/ncc-report-online-advertising-industry-is-out-of-control/
  - https://www.citizen.org/article/popular-dating-health-apps-violate-privacy/
  - https://techcrunch.com/2020/01/14/dating-and-fertility-apps-among-those-snitching-to-out-of-control-adtech-report-finds/
  - https://www.forbrukerradet.no/side/the-norwegian-consumer-council-awarded-epic-international-privacy-champion-award/
  - https://www.forbrukerradet.no/side/new-study-the-advertising-industry-is-systematically-breaking-the-law/
  - https://digitalfreedomfund.org/blog/how-ngos-are-joining-forces-against-adtech/
  - https://crackedlabs.org/en/outofcontrol
  - https://en.wikipedia.org/wiki/Norwegian_Consumer_Council
  - https://www.metroweekly.com/2020/01/grindr-accused-of-sharing-users-sensitive-data-to-multiple-companies/
  - https://pirg.org/arizona/articles/u-s-pirg-and-leading-groups-support-findings-of-norwegian-privacy-report/
  - https://ntic.ch/out-of-control-adtech-data-sharing-practices-on-dating-platforms/
---

Connective-type entity (Event): claim surface is edges + hard specifics per AUDITOR.md § Type-shape. Interpretive prose (deliberateness of the same-day structure, "transnational forcing mechanism," significance framing) carries no decision. The storage02.forbrukerradet.no report PDF (cited as primary) is image-compressed and unparseable via fetch (known workbench limit); NCC press pages and contributor pages substitute.

## Claim 1: "On 14 January 2020, the Norwegian Consumer Council published 'Out of Control' … and simultaneously filed three formal GDPR complaints" + scalar:date (2020-01-14)

Source: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: "Date of Filing: 14 January 2020 … Norwegian Consumer Council (Forbrukerrådet) led the project; noyb provided legal analysis and drafted formal complaints." EDRi: "The report was released on January 14, 2020"; TechCrunch and Public Citizen pages both dated January 14, 2020.
Comparison: Publication date and same-day complaint filing confirmed by the co-filer (noyb, primary) and ≥2 independent canonical sources (EDRi, TechCrunch, Public Citizen). Frontmatter `date` scalar matches.
Decision: corroborated

## Claim 2: scalar:location — "Oslo, Norway"

Source: https://en.wikipedia.org/wiki/Norwegian_Consumer_Council
Source tier: tiebreaker
Source content: "The Norwegian Consumer Council is headquartered in Oslo."
Comparison: No fetched source directly places the launch event in Oslo; the location is inferred from the NCC's Oslo headquarters (Wikipedia) and the Norwegian venue of the filing (Datatilsynet). Inference from org HQ to event location is a judgment-loaded edge, so the honest label is uncorroborated — not a finding of error; "Norway" is beyond doubt.
Decision: uncorroborated

## Claim 3: edge — scalar:campaign → camp-ncc-out-of-control-behavioral-advertising-2020

Source: corpus (product/entities/campaigns/camp-ncc-out-of-control-behavioral-advertising-2020.md) + https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: Target entity file exists; noyb/NCC sources establish this launch-and-filing event as the anchor of the NCC Out of Control campaign ("The Norwegian Consumer Council's research report is referenced … demonstrating widespread tracking practices").
Comparison: Edge resolves to an existing entity and is semantically correct — the event is the campaign's anchoring action.
Decision: corroborated

## Claim 4: edge — scalar:participating_orgs → org-norwegian-consumer-council

Source: corpus (product/entities/organizations/org-norwegian-consumer-council.md) + all fetched sources
Source tier: primary
Source content: "Norwegian Consumer Council (Forbrukerrådet) led the project" (noyb); "The Norwegian Consumer Council is now filing formal complaints…" (NCC press page).
Comparison: Edge resolves; NCC is the event's principal actor in every source.
Decision: corroborated

## Claim 5: edge + attribution — "EDRi characterised this framing at release as demonstrating that adtech illegality was structural rather than incidental" (body link → org-edri)

Source: https://edri.org/our-work/ncc-report-online-advertising-industry-is-out-of-control/
Source tier: primary
Source content: EDRi characterizes the finding as structural illegality: "the system in its current form is based on the comprehensive and systemic illegal collection and use of personal data," and adds "the comprehensive surveillance many of these companies engage in poses a systemic threat to fundamental rights."
Comparison: For a claim about what EDRi said, EDRi's own page is the primary source; the structural-not-incidental characterization matches. Edge to org-edri resolves in corpus.
Decision: primary-sourced

## Claim 6: "a 186-page technical investigation"

Source: https://crackedlabs.org/en/outofcontrol
Source tier: primary
Source content: "The report was published in January 2020 and comprises 186 pages (with an additional 93-page technical report)." Corroborating (via search): ntic.ch — "released … a 186 pages study report."
Comparison: Cracked Labs (Wolfie Christl) is a listed contributor to the report, so its project page is primary-tier for the report's specs; page count matches.
Decision: primary-sourced

## Claim 7: ten-app list — "Grindr, Tinder, OkCupid, and Happn (dating), Clue and MyDays (women's health…), Perfect365 (beauty), Qibla Finder (Muslim prayer direction), My Talking Tom 2 (children's game), and Wave Keyboard" + scalar:sources[0].note

Source: https://techcrunch.com/2020/01/14/dating-and-fertility-apps-among-those-snitching-to-out-of-control-adtech-report-finds/
Source tier: mainstream
Source content: TechCrunch enumerates all ten: "Grindr, Happn, OkCupid, Tinder (dating); Clue, MyDays (fertility/period tracker); Perfect365 (makeup filter); Muslim: Qibla Finder (religious); My Talking Tom 2 (children's game); Wave Keyboard (keyboard app)."
Comparison: Full enumeration confirmed by one mainstream source; count and categories corroborated partially by EDRi ("Ten popular applications … including dating and period tracker apps") and Public Citizen ("10 apps—including Grindr, Tinder, and OkCupid"); the cited primary (report PDF) is unparseable via fetch. Complete-list support therefore rests on one canonical source.
Decision: single-source

## Claim 8: "transmitting user data to at least 135 different third parties" + scalar:sources[0].note

Source: https://edri.org/our-work/ncc-report-online-advertising-industry-is-out-of-control/
Source tier: mainstream
Source content: EDRi: user data transmitted to "at least 135 different third parties involved in advertising or behavioral profiling." TechCrunch: "The report identified at least 135 companies engaged in advertising." Wikipedia (NCC): apps "were transmitting user data to at least 135 different third parties involved in advertising and/or behavioural profiling."
Comparison: Figure matches across ≥2 independent canonical sources.
Decision: corroborated

## Claim 9: "developed the investigation in collaboration with Norwegian cybersecurity firm Mnemonic, which performed the technical traffic analysis, and independent US researcher Zach Edwards"

Source: https://crackedlabs.org/en/outofcontrol
Source tier: primary
Source content: "The investigation was led by the Norwegian Consumer Council, with contributions from Cracked Labs, mnemonic, Zach Edwards, and NOYB." NCC press page: "Mnemonic, a security company, performed the technical report." Search-corroborated (Wikipedia/NCC): "technical testing performed by Andreas Claesson and Tor E. Bjørstad from the cybersecurity company Mnemonic … help from researchers Wolfie Christl of Cracked Labs and Zach Edwards of Victory Medium."
Comparison: Both named collaborators confirmed by the NCC's own page (primary) and the contributor's page; Mnemonic's technical-analysis role explicit.
Decision: corroborated

## Claim 10: Grindr pipeline "exposed GPS location, IP addresses, advertising identifiers, age, gender, and … sexual orientation"

Source: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: Schrems (noyb): "Every time you open an app like Grindr advertisement networks get your GPS location, device identifiers and even the fact that you use a gay dating app." Metro Weekly: Grindr was "sharing location data, sexuality, and other information to 'a large number of shadowy entities.'"
Comparison: Subset confirmed (GPS location, advertising/device identifiers, sexual orientation); the full six-item enumeration — specifically IP addresses, age, and gender — rests on the unparseable report PDF and is not confirmed as stated by any fetched source. Sourcing-strength label, not a finding of error.
Decision: uncorroborated

## Claim 11: report quote — the adtech system "is based on the comprehensive and systemic illegal collection and use of personal data" + scalar:sources[0].note

Source: https://edri.org/our-work/ncc-report-online-advertising-industry-is-out-of-control/
Source tier: mainstream
Source content: "The report states: 'the system in its current form is based on the comprehensive and systemic illegal collection and use of personal data.'"
Comparison: Verbatim quote reproduced by EDRi; the quoted primary (report PDF) is unparseable via fetch, so support rests on one canonical reproduction.
Decision: single-source

## Claim 12: sexual orientation is special-category data under GDPR Article 9; the Grindr complaint targeted its sharing without valid legal basis

Source: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: Complaints cite "improper handling of special-category data revealing sexual orientation"; the Datatilsynet decision (per noyb fine pages/GDPRhub, via search) cited "Articles 4(11), 6, 7 and 9(2)(a) GDPR."
Comparison: Article 9 special-category framing confirmed by the co-filer's announcement and by the DPA decision's cited articles (9(2)(a)).
Decision: corroborated

## Claim 13: three complaints at Datatilsynet co-filed with NOYB, targeting Grindr and five adtech recipients — Twitter's MoPub, AT&T's AppNexus (later Xandr), OpenX, AdColony, Smaato + scalar:sources[1].note

Source: https://noyb.eu/en/three-gdpr-complaints-filed-against-grindr-twitter-and-adtech-companies-smaato-openx-adcolony-and
Source tier: primary
Source content: noyb title/body: "Three GDPR Complaints filed against Grindr, Twitter and the AdTech companies Smaato, OpenX, AdColony and AT&T's AppNexus," filed at the Norwegian DPA. NCC press page: "filing formal complaints against Grindr … and companies that were receiving personal data through the app; Twitter`s MoPub, AT&T's AppNexus, OpenX, AdColony and Smaato … directed to the Norwegian Data Protection Authority."
Comparison: Complaint count (three documents), respondent set (six companies), venue, and NOYB co-filing all match across the two filing organizations' own pages. GDPRhub (via search) likewise: "three strategic GDPR complaints … AppNexus (now Xandr)."
Decision: corroborated

## Claim 14: legal argument — consent via forced full-policy acceptance was not "freely given, specific, informed, and unambiguous" per GDPR Article 7; the defect propagated to downstream recipients + scalar:sources[1].note

Source: https://noyb.eu/en/ncc-noyb-gdpr-complaint-grindr-fined-eu-63-mio-over-illegal-data-sharing
Source tier: primary
Source content: Complaints cite "lack of valid user consent for data sharing"; the DPA's draft decision fined Grindr "for the violation of Articles 4(11), 6, 7 and 9(2)(a) GDPR"; complaints were also filed against the five recipient companies for processing without valid legal basis.
Comparison: Article 7 (conditions for consent) confirmed among the cited articles; the "freely given, specific, informed, unambiguous" formula is the GDPR's own consent definition (Art 4(11), cited alongside Art 7). The downstream-propagation argument matches the structure of the three filings (complaints against all five recipients). Note the sources[1].note scalar's "GDPR Article 7" attribution is supported, with Art 4(11)/6/9(2)(a) cited alongside.
Decision: primary-sourced

## Claim 15: nine US organisations (ACLU of California, Campaign for a Commercial-Free Childhood, Center for Digital Democracy, Consumer Action, Consumer Federation of America, Consumer Reports, EPIC, Public Citizen, US PIRG) jointly urged the FTC, Congress, and the AGs of California, Texas, and Oregon + scalar:sources[3].note

Source: https://www.citizen.org/article/popular-dating-health-apps-violate-privacy/
Source tier: primary
Source content: "Public Citizen, American Civil Liberties Union of California, Campaign for a Commercial-Free Childhood, Center for Digital Democracy, Consumer Action, Consumer Federation of America, Consumer Reports, Electronic Privacy Information Center (EPIC), and U.S. PIRG" asked "the Federal Trade Commission (FTC), U.S. Congress, State Attorneys General of California, Texas, and Oregon."
Comparison: All nine names and all three target categories match a co-signer's own page (primary). The page is dated 14 January 2020 — same day as the Oslo filing — so the body's "within weeks" framing is loose but consistent (same-day ⊂ within weeks); not a correction-grade token.
Decision: primary-sourced

## Claim 16: the joint request "called for a strong federal digital privacy law with a data protection agency, a private right of action, and strong enforcement mechanisms"

Source: https://pirg.org/arizona/articles/u-s-pirg-and-leading-groups-support-findings-of-norwegian-privacy-report/
Source tier: primary
Source content: (via search snippet of the co-signer's article) "The groups called for a strong federal digital privacy law that includes a new data protection agency, a private right of action and strong enforcement mechanisms." Public Citizen page: "Congress should use the findings of this report as a roadmap for a new law…"
Comparison: The specific triple (agency, private right of action, enforcement) matches the co-signer PIRG's own account verbatim; the Public Citizen page carries the general legislative ask.
Decision: primary-sourced

## Claim 17: "The report received media coverage in more than 70 countries"

Source: https://digitalfreedomfund.org/blog/how-ngos-are-joining-forces-against-adtech/
Source tier: primary
Source content: "media coverage in more than 70 countries"; "A total of 43 organisations in 20 countries participated, sending letters to several data protection authorities." (NCC-authored guest post — first-person: "we filed complaints against six companies for breaching the GDPR.")
Comparison: Figure confirmed by the NCC's own account. Note: the entity's inline citation for this claim (the forbrukerradet.no EPIC-award page) does not state the 70-countries figure — a citation-pointer mismatch, but the factual token itself is accurate, so no correction; flagging here for the record.
Decision: primary-sourced

## Claim 18: "the corpus's first Scandinavia-based event entry"

Source: corpus scan (product/entities/events/ location fields)
Source tier: primary
Source content: Only this event carries a Scandinavian primary location ("Oslo, Norway"). Two PauseAI events list Oslo/Stockholm among many cities but are located "international."
Comparison: Corpus-internal claim, mechanically verified against the corpus itself (the authoritative record); no earlier-created event entity is Scandinavia-based.
Decision: primary-sourced
