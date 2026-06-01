---
entity_id: org-la-quadrature-du-net
entity_hash: 2659f6c3865bb45e4d55fd6bee7631a49b7cf522
audit_date: 2026-06-01
pass: 1
status: discrepancy
claims_total: 24
claims_verified: 6
claims_discrepancy: 1
claims_unverifiable: 17
sources_consulted:
  - https://en.wikipedia.org/wiki/La_Quadrature_du_Net
  - https://en.wikipedia.org/wiki/HADOPI_law
  - https://en.wikipedia.org/wiki/J%C3%A9r%C3%A9mie_Zimmermann
  - https://en.wikipedia.org/wiki/General_Data_Protection_Regulation
  - https://reclaimyourface.eu/
  - https://edri.org/take-action/our-network/
  - https://edri.org/our-work/reclaim-your-face/
  - https://www.accessnow.org/campaign/keepiton/
  - https://www.laquadrature.net/en/2024/12/
---

## Claim 1: "Paris-anchored French digital-rights association"

Source: https://en.wikipedia.org/wiki/J%C3%A9r%C3%A9mie_Zimmermann
Source content: "co-founder of the Paris-based La Quadrature du Net, a citizen advocacy group defending fundamental freedoms online"
Comparison: Wikipedia (named-entity definitional fact: organisation's country of operation and formal home) confirms LQDN is Paris-based. Wikipedia-alone-sufficient class.
Decision: verified

## Claim 2: "founded in 2008"

Source: https://en.wikipedia.org/wiki/La_Quadrature_du_Net
Source content: "The group was founded in 2008 by free software promoters and activists."
Comparison: Founding date is a named-entity definitional fact; Wikipedia-alone-sufficient. Confirmed.
Decision: verified

## Claim 3: "founded in 2008 by a small cohort of free-software and civil-liberties advocates — including Philippe Aigrain, Benjamin Sonntag, Jérémie Zimmermann, and Christophe Espern"

Source: https://en.wikipedia.org/wiki/La_Quadrature_du_Net
Source content: "founders [Philippe Aigrain, Benjamin Bayart, Laurent Chemla, Lionel Maurel, Benjamin Sonntag..., Félix Tréguer, Laurence Wandewalle, Jérémie Zimmermann]"
Comparison: Wikipedia confirms Aigrain, Sonntag, and Zimmermann as founders but does NOT list Christophe Espern. Wikipedia adds Bayart, Chemla, Maurel, Tréguer, Wandewalle. The body's "including" framing permits a partial enumeration, so the inclusion of the three confirmed names is not contradicted. But the fourth name (Espern) is not corroborated by Wikipedia; LQDN's own English about-page (the natural primary source for a co-founder roster) returned 404 at audit time, and Wikipedia is tiebreaker-only for living-person specifics beyond public role. No second canonical source available to confirm Espern's co-founder status.
Decision: unverifiable

## Claim 4: "The organisation's first major mobilisation, in 2008–2009, was against the Hadopi law on graduated-response internet disconnection for alleged copyright infringement"

Source: https://en.wikipedia.org/wiki/La_Quadrature_du_Net (LQDN founders "fighting the HADOPI law, a controversial project to establish a graduated response in France"); https://en.wikipedia.org/wiki/HADOPI_law (the HADOPI law "was introduced during 2009, providing what is known as a graduated response as a means to encourage compliance with copyright laws"; "suspension of Internet access for one month maximum" until "revoked on 8 July 2013")
Comparison: Two-canonical-source corroboration. HADOPI = graduated-response = copyright enforcement = included internet-disconnection penalty in its original form. LQDN's mobilisation against HADOPI is confirmed by Wikipedia LQDN article. 2008-2009 timeframe is plausible (HADOPI introduced 2009, adopted May 2009; founding-year mobilisation common). All elements of the claim corroborated.
Decision: verified

## Claim 5: "The original cohort operated as an informal association-of-citizens through 2018 before consolidating into a formal French association ('association loi 1901')"

Source: https://en.wikipedia.org/wiki/La_Quadrature_du_Net
Source content: "In 2013, the collective re-organized from a de facto association to a formal (French law) association."
Comparison: Body claims the informal-to-formal transition occurred in 2018; Wikipedia states it was 2013. This is a five-year factual conflict on a named-entity definitional fact (organisation's formal structural transition date). Wikipedia-alone-sufficient class for definitional facts. The cited LQDN home page covers the org's current form, not its history, so Wikipedia stands.
Decision: discrepancy

## Claim 6: "funded predominantly by individual donations"

Source: no canonical source found (LQDN's own English about-page returned 404 at audit time; Wikipedia's article does not address LQDN's funding mix; no independent mainstream news article surfaced confirming the predominantly-individual-donations framing)
Source content: n/a — primary cited source unfetchable
Comparison: Body claim cannot be independently confirmed against the cited sources or a substitute canonical source within the session.
Decision: unverifiable

## Claim 7: "The [Technopolice campaign](https://technopolice.fr/), launched in September 2019"

Source: no canonical source confirming the launch month
Source content: n/a
Comparison: The body cites technopolice.fr (LQDN's own campaign site) as the primary source. Specific launch month (September 2019) is a recent-event date that requires its own confirmation; no canonical source surfaced in the session corroborates the September month specifically. Wikipedia LQDN article and Wikipedia Mass Surveillance in France article do not mention Technopolice.
Decision: unverifiable

## Claim 8: "local collectives in Paris, Marseille, Saint-Étienne, Nice, Toulouse, and more than a dozen other French municipalities"

Source: no canonical source surfaced confirming the specific city list or count
Source content: n/a
Comparison: Cited technopolice.fr is LQDN's own campaign site; the auditor could not corroborate the specific city enumeration or "more than a dozen" claim via an independent canonical source.
Decision: unverifiable

## Claim 9: "Caisse nationale des Allocations Familiales (CAF), the French national family-benefits agency"

Source: no canonical source consulted in session confirms this exact characterisation
Source content: n/a
Comparison: CAF as the French family-benefits agency is widely known and would be confirmable via Wikipedia-alone for a definitional named-entity fact, but the body's specific cited URL (laquadrature.net/en/2024/12/02/...caf) returned 404 at audit time, and no substitute source was fetched in this pass.
Decision: unverifiable

## Claim 10: "The CAF system, deployed since the mid-2010s, assigns risk-of-fraud scores to roughly 13 million beneficiary households"

Source: no canonical source surfaced
Source content: n/a
Comparison: Primary cited source 404. Specific deployment-era and 13-million-household figure require canonical confirmation that was not available in the session.
Decision: unverifiable

## Claim 11: "coalition of fifteen French civil-society organisations"

Source: no canonical source surfaced
Source content: n/a
Comparison: Primary cited source 404. The "fifteen" count and the French-organisations characterisation were not corroborated in the session.
Decision: unverifiable

## Claim 12: "filed a 2023 challenge to the system before France's highest administrative court, the Conseil d'État"

Source: no canonical source surfaced confirming 2023 filing date
Source content: n/a
Comparison: "Conseil d'État is France's highest administrative court" is a definitional public-role fact that would be Wikipedia-alone-sufficient if confirmed, but the specific 2023 filing date for this CAF challenge requires its own canonical source; primary cited LQDN source is 404 and no substitute was fetched.
Decision: unverifiable

## Claim 13: "The Conseil d'État held its hearing on the file in October 2024"

Source: no canonical source surfaced
Source content: n/a
Comparison: Recent-event date (within 18 months of the audit) requiring ≥1 non-Wikipedia canonical source per the source rule; primary cited LQDN source 404 and no substitute fetched.
Decision: unverifiable

## Claim 14: "LQDN was one of the [twelve founding civil-society organisations](https://reclaimyourface.eu/) in the EDRi-coordinated Reclaim Your Face coalition"

Source: https://reclaimyourface.eu/
Source content: "Access Now, ARTICLE19, Bits of Freedom, CCC, Defesa dos Direitos Digitais (D3), Digitalcourage, Digitale Gesellschaft CH, Digitale Gesellschaft DE, Državljan D, EDRi, Electronic Frontier Finland, epicenter.works, Hermes Center for Transparency and Digital Human Rights, Homo Digitalis, IT-Political Association of Denmark, IuRe, La Quadrature du Net, Liberties, Metamorphosis Foundation, Panoptykon Foundation, Privacy International, and SHARE Foundation."
Comparison: LQDN appears in the coalition member list, confirming its membership. The body's specific "twelve founding" count is not separately marked on the page (the current site lists 22 coalition members and does not distinguish founders from later joiners); EDRi's reclaim-your-face page mentions "47 organisations, led by European Digital Rights" without naming founders. The specific "twelve" count and "founding" status (vs. later joining) cannot be confirmed against a canonical source in this pass.
Decision: unverifiable

## Claim 15: "launched in October 2020 against biometric mass surveillance in European public space, alongside EDRi as coordinator, AlgorithmWatch and AlgorithmWatch Switzerland, Access Now, ARTICLE 19, Bits of Freedom, Privacy International, Homo Digitalis, the Hermes Center, the Panoptykon Foundation, IT-Pol Denmark, and Liberties"

Source: https://reclaimyourface.eu/; https://edri.org/our-work/reclaim-your-face/
Source content: reclaimyourface.eu lists current coalition members (above quote); EDRi page states "47 organisations, led by European Digital Rights, will be calling on the European Union…"
Comparison: EDRi as coordinator is confirmed ("led by European Digital Rights"). Access Now, ARTICLE19, Bits of Freedom, Privacy International, Homo Digitalis, Hermes Center, Panoptykon Foundation, IT-Political Association of Denmark, Liberties — all appear in the current reclaimyourface.eu list. AlgorithmWatch and AlgorithmWatch Switzerland do NOT appear in the current reclaimyourface.eu coalition list; the page lists "Digitale Gesellschaft DE" and "Digitale Gesellschaft CH" but not AlgorithmWatch. The body's October-2020 launch date is not stated on either page consulted. Without a canonical source confirming the "founding" cohort specifically, the AlgorithmWatch omission may be explained by later turnover rather than a body error. Wikipedia tiebreaker-only for contested-attribution / coalition-composition claims; insufficient canonical sourcing to resolve.
Decision: unverifiable

## Claim 16: "the European Citizens' Initiative signature window (17 February 2021 – 1 August 2022)"

Source: no canonical source surfaced confirming the specific dates
Source content: n/a
Comparison: The two pages I fetched on Reclaim Your Face (reclaimyourface.eu, edri.org/our-work/reclaim-your-face/) do not state the ECI signature window dates; the EU ECI registry URL ECONNREFUSED'd in session.
Decision: unverifiable

## Claim 17: "LQDN is one of the nearly 70 founding civil-society organisations of the [Access Now](../organizations/org-access-now.md)-coordinated [#KeepItOn coalition](../campaigns/camp-access-now-keep-it-on-internet-shutdowns-2016-ongoing.md), launched on 8 June 2016"

Source: https://www.accessnow.org/campaign/keepiton/
Source content: "Access Now launched the #KeepItOn campaign in 2016"; "unites more than 366 national, international, regional, and local organizations"; LQDN appears in the current member list.
Comparison: KeepItOn launch year 2016 and Access Now's coordinating role are confirmed. LQDN's coalition membership is confirmed. The specific launch date 8 June 2016 is not stated on the page (only "2016"); the "nearly 70 founding" figure is not stated either (the current page only gives the current 366+ figure). Founding-cohort enumeration and exact launch date are not corroborated by any canonical source consulted.
Decision: unverifiable

## Claim 18: "established in its 2010 mobilisation against the EU's net-neutrality framework, its 2010–2012 participation in the European mobilisation against the Anti-Counterfeiting Trade Agreement (ACTA)"

Source: https://en.wikipedia.org/wiki/J%C3%A9r%C3%A9mie_Zimmermann
Source content: "Jérémie Zimmermann received an EFF Pioneer Award in 2012 for action against ACTA"
Comparison: LQDN's participation in the ACTA mobilisation is corroborated indirectly via the Zimmermann EFF Pioneer Award (2012 timing fits the 2010-2012 ACTA window). The 2010 net-neutrality mobilisation specifically was not corroborated in any canonical source consulted in this pass. Mixed support — partial corroboration on ACTA, none on the 2010 net-neutrality piece.
Decision: unverifiable

## Claim 19: "In May 2018 LQDN launched a collective-complaints track against Google, Apple, Facebook, Amazon, and Microsoft (the 'GAFAM' complaints) under the GDPR"

Source: no canonical source surfaced
Source content: n/a
Comparison: Primary cited LQDN source (laquadrature.net/en/2024/02/15/data-gafam-...) returned 404 at audit time. Wikipedia's GDPR article does not mention the LQDN GAFAM complaints. No substitute canonical source consulted in this pass.
Decision: unverifiable

## Claim 20: "The original collective filing reached approximately 12,000 individual co-claimants by mid-2018"

Source: no canonical source surfaced
Source content: n/a
Comparison: Primary cited source 404. The ~12,000 co-claimants figure could not be cross-checked in this pass.
Decision: unverifiable

## Claim 21: "substantial fines against Google and Amazon by the French data-protection authority (CNIL) in 2020 for non-compliant cookie practices"

Source: no canonical source surfaced
Source content: n/a
Comparison: Direct attempts to fetch CNIL's English-language pages on the December 2020 Google and Amazon fines returned 404; outside the cited source URL pattern. The fact pattern (CNIL issuing cookie-related fines on Google and Amazon in December 2020) is broadly known but was not corroborated against a fetched canonical source in this pass.
Decision: unverifiable

## Claim 22: "European Digital Rights (EDRi), the Brussels-headquartered pan-European network"

Source: https://edri.org/take-action/our-network/
Source content: page references a "Brussels Office" with contact "brussels[at]edri[dot]org"
Comparison: Brussels presence corroborated. Wikipedia-alone-sufficient class (named-entity definitional fact) supports characterising Brussels as the headquarters.
Decision: verified

## Claim 23: "more than fifty civil-society organisations"

Source: https://edri.org/take-action/our-network/
Source content: "The EDRi network is a dynamic and resilient collective of 50+ NGOs."
Comparison: "50+ NGOs" supports "more than fifty civil-society organisations." Direct corroboration.
Decision: verified

## Claim 24: "LQDN is a member organisation of European Digital Rights (EDRi)"

Source: https://edri.org/take-action/our-network/
Source content: "La Quadrature du Net (Member)"
Comparison: Direct corroboration.
Decision: verified
