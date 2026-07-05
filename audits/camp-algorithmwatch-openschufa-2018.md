---
entity_id: camp-algorithmwatch-openschufa-2018
entity_hash: 2f4afd0e5848835f6c6545400fc3efc563db4cc4
audit_date: 2026-07-04
pass: 2
status: corrections-pending
claims_total: 29
claims_corroborated: 11
claims_primary_sourced: 12
claims_single_source: 0
claims_uncorroborated: 5
open_corrections: 1
sources_consulted:
  - https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/
  - https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
  - https://openschufa.de/english/
  - https://openschufa.de/
  - https://algorithmwatch.org/en/openschufa-en/
  - https://www.startnext.com/en/openschufa/rws
  - https://www.startnext.com/openschufa/blog/beitrag/faq-die-antworten-auf-eure-fragen-zu-openschufa-p75812.html
  - https://de.wikipedia.org/wiki/Openschufa
---

Pass-2 context: the only entity change since the pass-1 audit (2026-05-18) is the frontmatter edge `strategies: [] → [strat-empirical-audit-and-expose]`; body and all other frontmatter are byte-identical. Campaign is a connective type (`mission/MISSION.md § Auditor § Type-shape awareness`), so this pass audits the edges (never covered in pass 1), the hard specifics, and the quoted attributions; body prose claims re-verified where sources were re-fetched this session, carried from the pass-1 record where the pass decision and quote are already on file and the text is unchanged.

## Claim 1: edge `lead_orgs: org-algorithmwatch`

Source: https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/ + https://openschufa.de/english/
Source tier: primary
Source content: "AlgorithmWatch – a German-based non-profit that evaluates and sheds light on algorithmic and automatization processes with social relevance" (co-launcher, 22 May 2018 announcement); impressum "Matthias Spielkamp - AW AlgorithmWatch gGmbH".
Comparison: Edge points to the correct corpus entity (`org-algorithmwatch` = AlgorithmWatch); AlgorithmWatch's lead role confirmed by its own announcement and by the campaign site's impressum naming AW as responsible party.
Decision: corroborated

## Claim 2: edge `participating_orgs: org-algorithmwatch`

Source: https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/ + https://openschufa.de/english/
Source tier: primary
Source content: As Claim 1 — AlgorithmWatch is a named co-running organization throughout both pages.
Comparison: Edge points to the correct entity. (The co-lead Open Knowledge Foundation Germany has no corpus entity; edge completeness is out of audit remit.)
Decision: corroborated

## Claim 3: edge `events: event-algorithmwatch-openschufa-launch-2018-05-22`

Source: https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/
Source tier: primary
Source content: Article date "May 22, 2018"; "Once the data donation platform is ready in May 2018 (financed by your Euro donations) you'll be able to upload your credit record".
Comparison: Target entity exists in the corpus and its name/date (data-donation platform launch, 22 May 2018) matches the announcement's date. Edge correct.
Decision: corroborated

## Claim 4: edge `strategies: [strat-empirical-audit-and-expose]` (the pass-2 delta)

Source: product/entities/strategies/strat-empirical-audit-and-expose.md + https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
Source tier: primary
Source content: The strategy entity's effects[2] is the OpenSCHUFA results publication itself, cross-linking `camp-algorithmwatch-openschufa-2018`; AW results page documents the empirical analysis of ~2,000 donated credit reports with published anomaly findings.
Comparison: Edge points to an existing corpus entity whose own record names this campaign as an instance; the campaign's shape (quantitative test of a deployed credit-scoring system, published anomaly numbers, press-routed) matches the strategy definition. Edge correct.
Decision: corroborated

## Claim 5: `start_date: 2018-02` (and outcomes "Early 2018: announced the partnership, opened a Startnext crowdfunding round")

Source: https://www.startnext.com/en/openschufa/rws + https://de.wikipedia.org/wiki/Openschufa
Source tier: primary
Source content: Startnext project page: funding period ran 2/14/18 to 3/15/18. de.wikipedia: "Die Kampagne startete im Februar 2018 damit, Spenden für das Projekt einzusammeln."
Comparison: February 2018 campaign start confirmed by the campaign's own crowdfunding page (primary) with Wikipedia concurring (campaign-launch date is in the Wikipedia-alone class).
Decision: corroborated

## Claim 6: `end_date: 2018-11-28` / "28 November 2018 ... published the analysis"

Source: https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
Source tier: primary
Source content: "The investigation results were published on November 28-29, 2018, by Spiegel Online and Bayerischer Rundfunk" (results page dated 29 Nov 2018 reporting publication "yesterday", per pass-1 record).
Comparison: 28 November 2018 publication date confirmed by the lead org's own results page; no second independent outlet fetched this session for the exact day.
Decision: primary-sourced

## Claim 7: "In the spring of 2018 AlgorithmWatch and the Open Knowledge Foundation Germany launched OpenSCHUFA"

Source: https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/ + https://de.wikipedia.org/wiki/Openschufa
Source tier: primary
Source content: Announcement (22 May 2018) names "Open Knowledge Foundation Germany okfn.de" and "AlgorithmWatch" as the launching organizations; de.wikipedia confirms the joint project and Feb-2018 start.
Comparison: Joint launch and timing directly confirmed by two sources.
Decision: corroborated

## Claim 8: "data journalists at the public broadcaster Bayerischer Rundfunk and Spiegel Online"

Source: https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/ + https://de.wikipedia.org/wiki/Openschufa
Source tier: primary
Source content: "a group of data scientists, including data journalists from Bayerischer Runkfunk, a state broadcaster, and Spiegel Online, the German news site"; Wikipedia: data evaluated by journalists from Bavarian Broadcasting and Der Spiegel.
Comparison: Both named partners confirmed; "public broadcaster" matches "state broadcaster" (paraphrase tolerance).
Decision: corroborated

## Claim 9: "SCHUFA's scores effectively gate rental tenancies, mobile-phone contracts, and consumer credit for some seventy million German adults"

Source: https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/ + https://openschufa.de/english/
Source tier: primary
Source content: "SCHUFA holds data on round about 70 million people in Germany. That's nearly everyone in the country aged 18 or older."; openschufa.de: "the SCHUFA procedure to determine the creditworthiness of 67 million Germans".
Comparison: "Some seventy million" is consistent with both figures (~70M / 67M); use-domains consistent with the sources' discussion of banks/landlords/telecoms.
Decision: corroborated

## Claim 10: "raised more than €43,000 from more than 1,800 backers" (Startnext crowdfunding)

Source: https://openschufa.de/english/ + https://www.startnext.com/en/openschufa/rws
Source tier: primary
Source content: openschufa.de: "more than 1,800 people to donate money", "more than 43,000 euros"; Startnext page: 1,828 supporters, €43,367 raised, funding period 2/14/18–3/15/18.
Comparison: Both figures match exactly across two primary sources.
Decision: corroborated

## Claim 11: "more than 4,000 donated SCHUFA records, more than 30,000 subject-access requests to SCHUFA, and more than 100,000 subject-access requests across the German consumer-credit scoring field"

Source: https://openschufa.de/english/
Source tier: primary
Source content: "more than 4,000 people to provide us with their SCHUFA information"; "more than 100,000 subject data requests to credit scoring companies, more than of them 30,000 to SCHUFA".
Comparison: All three figures match the campaign site (final tally, last updated May 2019). The results-published page's contemporaneous "More than 3000 people have donated their SCHUFA reports" (Nov 2018) is an earlier snapshot, not a conflict. Single primary source for the final figures.
Decision: primary-sourced

## Claim 12: "under section 34 of the German Federal Data Protection Act (BDSG) at the campaign's launch, and from 25 May 2018 (three days after the public data-donation platform went live) under the directly applicable Article 15 of the European Union General Data Protection Regulation"

Source: https://gdpr.eu/article-15-right-of-access/ (entity-cited) + https://algorithmwatch.org/en/openschufa-shedding-light-on-germanys-opaque-credit-scoring-2/
Source tier: primary
Source content: Announcement dated 22 May 2018; GDPR (incl. Article 15) applicable from 25 May 2018 — public-record statutory fact.
Comparison: BDSG §34 → GDPR Art. 15 substitution is public statutory record; the three-day interval (22 → 25 May 2018) checks out arithmetically against the dated announcement.
Decision: corroborated

## Claim 13: "actively encouraged participants to file subject-access requests not only with SCHUFA but also with Germany's other consumer-credit scoring firms — Boniversum, CRIF Bürgel, infoscore Consumer Data, and Deltavista"

Source: no canonical source reachable this session
Source tier: none
Source content: Pass 1 (2026-05-18) confirmed this from https://okfn.de/blog/2018/02/get-involved-we-crack-the-schufa/ ("comparing multiple consumer credit scoring agencies including Boniversum, Bürgel, Deltavista and Infoscore"), but that URL now returns HTTP 404; web.archive.org is unreachable from this harness; the live openschufa.de pages, the Startnext FAQ, and de.wikipedia name no firm besides SCHUFA. openschufa.de confirms only the aggregate "more than 100,000 subject data requests to credit scoring companies" (plural).
Comparison: The four-firm naming and the encouragement claim cannot be re-verified against any currently reachable canonical source; partial confirmation (multi-firm SARs happened) only. Not a finding of error — the pass-1 confirming source has gone dead.
Decision: uncorroborated

## Claim 14: "AlgorithmWatch's responsible-party named on the campaign site's impressum was Matthias Spielkamp, AlgorithmWatch's co-founder and Executive Director"

Source: https://openschufa.de/english/ + https://algorithmwatch.org/en/team/matthias-spielkamp/ (pass-1 record)
Source tier: primary
Source content: Impressum (re-fetched this session): "Matthias Spielkamp - AW AlgorithmWatch gGmbH - Bergstr. 22 10115 Berlin". Team page (pass-1 record): "Executive Director, Co-Founder & Shareholder".
Comparison: Impressum naming re-confirmed this session; co-founder/Executive-Director titles per pass-1 record (entity text unchanged).
Decision: corroborated

## Claim 15: "the analysis of approximately 2,000 of the more than 4,000 donated SCHUFA records"

Source: https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
Source tier: primary
Source content: "data journalists of the two German media companies analyzed about 2000 credit reports".
Comparison: ~2,000 figure matches; the >4,000 total is the campaign site's final tally (Claim 11).
Decision: primary-sourced

## Claim 16: quoted finding 1 — "a number of people were rated rather negatively although SCHUFA had no negative information on them, e.g. on debt defaults"

Source: https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
Source tier: primary
Source content: "A number of people were rated rather negatively although SCHUFA had no negative information on them, e.g. on debt defaults."
Comparison: Verbatim match, re-verified this session.
Decision: primary-sourced

## Claim 17: "divergences of up to ten per cent between SCHUFA's two simultaneously-operating scoring versions, with the older version 2 still in active commercial use alongside the newer version 3 even though SCHUFA's own internal assessment recognised the older version as inferior"

Source: https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
Source tier: primary
Source content: "The scores differ by up to 10 per cent between version 2 and 3, depending on the version of the scoring the client uses as a reference. This is an indicator that the SCHUFA itself deems its version 2 to be somewhat lacking." (per this session's fetch and pass-1 record)
Comparison: 10% figure and version-2-still-in-use both match; "own internal assessment recognised as inferior" is a fair rendering of "SCHUFA itself deems its version 2 to be somewhat lacking".
Decision: primary-sourced

## Claim 18: "SCHUFA's separate decision to forbid the editors at Bayerischer Rundfunk and Spiegel Online to cite or present even a digest of SCHUFA's extensive written answers"

Source: https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
Source tier: primary
Source content: "The SCHUFA again chose a strategy of forbidding the editors to cite or present even a digest of the extensive answers to their questions."
Comparison: Direct paraphrase, re-verified this session.
Decision: primary-sourced

## Claim 19: "the German Consumer Affairs Council to demand that scoring agencies improve their information policy and provide more transparency"

Source: https://algorithmwatch.org/en/schufa-a-black-box-openschufa-results-published/
Source tier: primary
Source content: The advisory body called for agencies to "improve their information policy and provide more transparency".
Comparison: Direct paraphrase, re-verified this session.
Decision: primary-sourced

## Claim 20: "AlgorithmWatch had been founded as a non-profit gGmbH in Berlin in 2017"

Source: https://algorithmwatch.org/de/wer-steht-hinter-algorithmwatch/ (pass-1 record)
Source tier: primary
Source content: "AW AlgorithmWatch gGmbH, Boyenstraße 41, 10115 Berlin, gegründet 2017." (pass-1 fetch, 2026-05-18)
Comparison: Year, legal form, and Berlin location all match; entity text unchanged since pass 1, decision carried.
Decision: primary-sourced

## Claim 21: "the 2020–2021 Instagram newsfeed monitoring [...] shut down by Facebook on terms-of-service grounds in July 2021"

Source: https://algorithmwatch.org/en/instagram-research-shut-down-by-facebook/ (pass-1 record)
Source tier: primary
Source content: "On 13 July, we took the decision to terminate the project and delete any collected data"; Facebook pressured AlgorithmWatch with terms-of-service claims; launch 3 March 2020. (pass-1 fetch, 2026-05-18)
Comparison: 2020 launch, July 2021 shutdown, ToS grounds all per pass-1 record; entity text unchanged, decision carried.
Decision: primary-sourced

## Claim 22: "the 2020-ongoing DataSkop infrastructure [...] BMBF-funded five-organisation consortium with election-year cycles on YouTube (2021 German federal election) and TikTok (2023)"

Source: https://dataskop.net/ (pass-1 record)
Source tier: primary
Source content: "Das dreijährige Vorhaben wird durch das Bundesministerium für Bildung und Forschung (BMBF) [...] gefördert"; five partners "AlgorithmWatch, der Europa-Universität Viadrina, der Fachhochschule Potsdam, der Universität Paderborn und dem Verein Mediale Pfade"; YouTube during the 2021 Bundestagswahl; TikTok "vom 26. Januar bis zum 21. April 2023." (pass-1 fetch, 2026-05-18)
Comparison: All specifics per pass-1 record; entity text unchanged, decision carried.
Decision: primary-sourced

## Claim 23: scalar:goals — quoted public suspicion "the SCHUFA procedure for calculating scores is flawed and reinforces discrimination" (attributed to the openschufa.de campaign site)

Source: https://openschufa.de/english/
Source tier: primary
Source content: "The results substantiated our suspicion that the SCHUFA procedure to determine the creditworthiness of 67 million Germans is flawed and reinforces discrimination"
Comparison: The predicate "is flawed and reinforces discrimination" is verbatim on the cited page, but the quoted lead-in differs ("procedure for calculating scores" vs. "procedure to determine the creditworthiness of 67 million Germans"). The entity may faithfully quote the pre-results 2018 wording of the page (last updated May 2019; earlier versions unverifiable — web.archive.org unreachable from this harness), so this is not asserted as error. Scalar path: `goals`.
Decision: uncorroborated

## Claim 24: scalar:sources[2].note — campaign framing quoted as "Shed light on the black box SCHUFA"

Source: https://openschufa.de/english/
Source tier: primary
Source content: "to bring some light into the „Black Box Schufa"."
Comparison: The framing characterization is accurate — "Black Box Schufa" is verbatim on the page and the light-shedding framing is present — though the note's quoted phrase is a paraphrase rather than the page's exact wording. Scalar path: `sources[2].note`.
Decision: primary-sourced

## Claim 25: body quote — "Unfortunately, we lacked the resources to forcefully pursue the implementation of the demands we had stated", presented with "the campaign site reads"

Source: https://openschufa.de/english/
Source tier: primary
Source content: The page's only resource-constraint sentences (fetched this session, full-sentence extraction): "We simply did not have the resources to follow up on it forcefully – to force Minister Barley to explain concretely what she is going to do to bring the change she publicly demanded." and "On the one hand, this failed because we didn't have enough resources to invest in it, on the other hand because of the low interest of local media."
Comparison: The body asserts a verbatim quote of the current campaign site ("the campaign site reads", explicitly the last-updated-May-2019 post-mortem — i.e. the live page), but the quoted sentence appears nowhere on that page. The substance matches, but the quotation as presented is inaccurate. Single correct replacement: "We simply did not have the resources to follow up on it forcefully". Fix location: body, § "Public verdict and post-publication response", final sentence (single quoted-string replacement; sentence framing "the campaign site reads" can stand).
Decision: correction

## Claim 26: "post-mortem (last updated May 2019)"

Source: https://openschufa.de/english/
Source tier: primary
Source content: "Last update: May 2019"
Comparison: Matches exactly, re-verified this session.
Decision: primary-sourced

## Claim 27: "the country's two most-read news outlets"

Source: no canonical source found
Source tier: none
Source content: Fetched sources describe Bayerischer Rundfunk as "a state broadcaster" and Spiegel Online as "the German news site"; no source supports the comparative ranking that these two are Germany's two most-read news outlets (BR is a regional broadcaster within ARD).
Comparison: Comparative-ranking claim unsupported; unchanged from pass 1.
Decision: uncorroborated

## Claim 28: "the first concrete legislative-track pressure on the German credit-scoring sector since the BDSG's own scoring-transparency provisions had been adopted a decade earlier"

Source: no canonical source found
Source tier: none
Source content: Fetched sources describe the post-publication political demands (Claim 19) but none makes the "first since the BDSG scoring provisions" comparative-historical claim, which would require a systematic review of German parliamentary credit-scoring activity 2008–2018.
Comparison: Negative-existence comparative claim unsupported; unchanged from pass 1.
Decision: uncorroborated

## Claim 29: "the first widely-noticed European participatory-data-donation campaign on an algorithmic-accountability target"

Source: no canonical source found
Source tier: none
Source content: Sources describe OpenSCHUFA as the partners' first participatory-data-donation project; none makes the field-wide "first widely-noticed European" superlative.
Comparison: Superlative comparative claim, judgment-loaded across the field; unchanged from pass 1.
Decision: uncorroborated
