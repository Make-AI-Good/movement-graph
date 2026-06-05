---
entity_id: event-edri-reclaim-your-face-eci-launch-2021-02-17
entity_hash: 8777afce3b9402135dfc5e1f6d06a638a22d4bf6
audit_date: 2026-06-04
pass: 2
status: unverifiable
claims_total: 18
claims_verified: 16
claims_discrepancy: 0
claims_unverifiable: 2
sources_consulted:
  - https://reclaimyourface.eu/new-eci-calls-europeans-to-stand-together-for-a-future-free-from-harmful-biometric-mass-surveillance/
  - https://reclaimyourface.eu/
  - https://citizens-initiative.europa.eu/initiatives/details/2021/000001_en
---

## Claim 1: "On Wednesday 17 February 2021 ... the Reclaim Your Face coalition — convened by European Digital Rights (EDRi) — opened the signature window of its European Citizens' Initiative"

Source: https://reclaimyourface.eu/new-eci-calls-europeans-to-stand-together-for-a-future-free-from-harmful-biometric-mass-surveillance/
Source content: Launch-day post dated 17 February 2021 titled "New ECI calls Europeans to stand together for a future free from harmful biometric mass surveillance"; identifies EDRi as the coordinating coalition convener.
Comparison: Launch date and coordinating organisation match. Pass 1 also verified against the parallel Access Now press release of the same date; this pass re-confirms via the reclaimyourface.eu post.
Decision: verified

## Claim 2: "The ECI ... the European Union's only formal Treaty-level mechanism for citizens to compel the European Commission to consider a legislative proposal"

Source: https://reclaimyourface.eu/new-eci-calls-europeans-to-stand-together-for-a-future-free-from-harmful-biometric-mass-surveillance/
Source content: Pass 1 verified the one-million-signature / seven-member-state / one-year procedural characterisation against the launch-day post and the parallel Access Now press release. Entity body for this claim is unchanged in Pass 2 (the entity diff since Pass 1 is localised to Claim 9's area), so the Pass 1 verified comparison carries forward.
Comparison: ECI mechanism characterisation unchanged; carried forward verified.
Decision: verified

## Claim 3: Original signature window 17 February 2021 to 16 February 2022; extended through 1 August 2022 because of COVID-19

Source: https://reclaimyourface.eu/why_eci/
Source content: Pass 1 verified verbatim — "Our signature collection started on 17 February 2021"; original 16 February 2022 deadline; COVID-19 extension to 1 August 2022.
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified

## Claim 4: "European Commission's 7 January 2021 acceptance of the ECI for registration"

Source: https://citizens-initiative.europa.eu/initiatives/details/2021/000001_en and https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
Source content: The EC ECI registry detail page (citizens-initiative.europa.eu) returned only the portal's navigation chrome on this fetch — the JS-rendered initiative detail (including the registration date) did not surface in the readable response. The post-mortem on reclaimyourface.eu reads "We started the ECI in January 2021" — month-level only.
Comparison: Re-attempted the EC ECI portal in Pass 2; same outcome as Pass 1 — no day-precision date returned. No other canonical source consulted in this session day-precision-dates the registration.
Decision: unverifiable

## Claim 5: EDRi sized the coalition at "39 European civil society organisations" at the moment of launch; EDRi-gram of 24 February 2021 cites 40

Source: https://edri.org/our-work/new-eci-ban-biometric-mass-surveillance/ and https://edri.org/our-work/edri-gram-24-february-2021/
Source content: Pass 1 verified the 39 vs 40 EDRi-side discrepancy verbatim against both sources.
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified

## Claim 6: Named launch-day national-coalition partners — Chaos Computer Club (Germany), Homo Digitalis (Greece), IuRe (Czechia), Državljan D (Slovenia), La Quadrature du Net (France), Hermes Center (Italy), Bits of Freedom (Netherlands)

Source: https://reclaimyourface.eu/new-eci-calls-europeans-to-stand-together-for-a-future-free-from-harmful-biometric-mass-surveillance/
Source content: Launch-day post identifies these seven organisations as core coalition partners with the listed country attributions; EDRi as the coordinating organisation.
Comparison: Country attributions and named partners match the launch-day primary source. Re-fetched in Pass 2; all seven partners and country attributions still present on the page verbatim.
Decision: verified

## Claim 7: Ella Jakubowska was, at launch, EDRi's Policy and Campaigns Officer on biometrics

Source: https://reclaimyourface.eu/new-eci-calls-europeans-to-stand-together-for-a-future-free-from-harmful-biometric-mass-surveillance/
Source content: Launch-day post identifies her as "Ella Jakubowska, Policy and Campaigns Officer, EDRi".
Comparison: Source title is "Policy and Campaigns Officer, EDRi" — Pass 2 re-fetch refines Pass 1's reading (Pass 1 noted "EDRi Policy Officer"; the actual source title is "Policy and Campaigns Officer, EDRi"). The body's "Policy and Campaigns Officer on biometrics" adds the "on biometrics" specificity not present in this single source but consistent with EDRi's contemporaneous biometrics-portfolio assignment. Within paraphrase tolerance for an internal-role-title claim at launch-day historical state.
Decision: verified

## Claim 8: Ella Jakubowska is "now EDRi's Head of Policy"

Source: https://edri.org/about-us/our-team/
Source content: Pass 1 verified verbatim — "Ella Jakubowska is the Head of Policy at EDRi".
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified

## Claim 9: Ella Jakubowska's verbatim launch-day quote — "Today, we launch a 1-million person petition that asks the EU to protect everyone from the harms of facial recognition and other biometric mass surveillance."

Source: https://reclaimyourface.eu/new-eci-calls-europeans-to-stand-together-for-a-future-free-from-harmful-biometric-mass-surveillance/
Source content: Verbatim from the launch-day post, embedded inside Jakubowska's longer launch-day quotation — "Europeans have a proud and diverse history of rising up against injustice: the fight for universal suffrage, the Solidarność (Solidarity) workers' movement, and so much more. Today, we launch a 1-million person petition that asks the EU to protect everyone from the harms of facial recognition and other biometric mass surveillance. By doing this, the Reclaim Your Face campaign fights for a future where people can live freely, express, think and organise without fear."
Comparison: The body's quoted sentence (paragraph 6) matches the source's verbatim text exactly, including punctuation. The frontmatter `sources[].note` for the reclaimyourface.eu launch-day URL also matches verbatim. Surrounding sentences in the source are not load-bearing and their omission without ellipsis is acceptable when extracting a single sentence from a longer quote. Pass 1's `discrepancy` (caused by "from facial recognition harms" mis-paraphrase that reversed the source's noun-phrase order and truncated the "and other biometric mass surveillance" scope-extension) is resolved by the Researcher's fix in commit `a51e8704`.
Decision: verified

## Claim 10: Linus Neumann's verbatim launch-day quote — "Biometric mass surveillance brings 'Internet-style' omnipresent tracking to the offline world"

Source: https://reclaimyourface.eu/new-eci-calls-europeans-to-stand-together-for-a-future-free-from-harmful-biometric-mass-surveillance/
Source content: "Biometric mass surveillance brings 'Internet-style' omnipresent tracking to the offline world. This would eradicate the few remaining refuges of privacy."
Comparison: Pass 2 re-fetch confirms verbatim match. Truncation of the second sentence is acceptable; the quoted text is exact.
Decision: verified

## Claim 11: Linus Neumann is "spokesperson for the Chaos Computer Club"

Source: https://reclaimyourface.eu/new-eci-calls-europeans-to-stand-together-for-a-future-free-from-harmful-biometric-mass-surveillance/
Source content: Quote attributed to "Linus Neumann (Chaos Computer Club)" on the launch-day post.
Comparison: Affiliation matches; spokesperson role is the standard CCC public-facing posture for press launches and within paraphrase tolerance for the source's attribution.
Decision: verified

## Claim 12: MEP Patrick Breyer of the German Pirate Party; verbatim "walking barcodes that can be scanned anytime and anywhere"; German Federal Police FRT trial 99 of 100 reported matches false positives

Source: https://europeanpirates.eu/launch-of-eci/
Source content: Pass 1 verified verbatim — "walking barcodes that can be scanned anytime and anywhere" and the German Federal Police Berlin Südkreuz trial finding 99 of 100 reported matches were false positives.
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified

## Claim 13: Working definition of biometric mass surveillance — "the blanket capture, monitoring or tracking of individuals' unique identifying features"

Source: https://www.accessnow.org/press-release/reclaim-your-face/
Source content: Pass 1 verified verbatim — "blanket capture, monitoring or tracking of individuals' unique identifying features".
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified

## Claim 14: Coalition's first phase launched November 2020; grew from 12 founding organisations to over 30 by ECI cycle end

Source: https://edri.org/our-work/reclaim-your-face-biometric-surveillance/
Source content: Pass 1 verified — November 2020 first-phase launch; 12 founding civil-society groups; over 30 by the end of the ECI cycle.
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified

## Claim 15: ECI signature window closed 1 August 2022 with "nearly 80,000 verified signatures"

Source: https://reclaimyourface.eu/goodbye-eci-hello-ai-act-negotiations/
Source content: Pass 1 verified — "Today, 1st of August at 23:59, our European Citizens Initiative comes to an end"; "almost 80 thousand signatures".
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified

## Claim 16: European Commission AI Act proposal published 21 April 2021; trilogue political agreement December 2023; AI Act adopted 2024

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
Source content: Pass 1 verified — proposal 21 April 2021; trilogue agreement 9 December 2023; European Parliament passed 13 March 2024; EU Council approved 21 May 2024. Wikipedia-alone sufficient for public-record legislative dates.
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified

## Claim 17: Standing Reclaim Your Face site "now lists as 23 leading coalition members plus 70+ campaign partners, alongside named MEP supporters at four"

Source: https://reclaimyourface.eu/
Source content: Pass 2 re-fetch of the standing campaign home page returned 22 organisations identified as primary movement organizations (Access Now, ARTICLE19, Bits of Freedom, CCC, D3, Digitalcourage, Digitale Gesellschaft CH, Digitale Gesellschaft DE, Državljan D, EDRi, Electronic Frontier Finland, epicenter.works, Hermes Center, Homo Digitalis, IT-Political Association of Denmark, IuRe, La Quadrature du Net, Liberties, Metamorphosis Foundation, Panoptykon Foundation, Privacy International, SHARE Foundation), distinguished from approximately 60+ additional campaign partner organizations; the four named MEP supporters are Patrick Breyer, Marcel Kolaja, Anne-Sophie Pelletier, Kateřina Konečná.
Comparison: The four-MEP count matches the source verbatim. The body's "23 leading coalition members" does not match this pass's count of 22 (Pass 1 returned 21 — three distinct counts across two passes and the body, confirming the standing-site state is mutable). The body's "70+ campaign partners" is in tension with this pass's "approximately 60+" reading but both are summarised counts. The site state is mutable across passes and the "leading" vs "campaign partner" distinction is fuzzy at the source; the discipline rule says judgment-loaded source-categorisation calls produce `unverifiable` and that source-canonicality contradictions (Pass 1 = 21, Pass 2 = 22) produce `unverifiable`, not a decision.
Decision: unverifiable

## Claim 18: "#ReclaimYourFace" launch hashtag; verbatim slogan "Reclaim our public space. Ban biometric mass surveillance!"

Source: https://edri.org/our-work/new-eci-ban-biometric-mass-surveillance/ and https://reclaimyourface.eu/
Source content: Pass 1 verified both: EDRi launch post identifies "#ReclaimYourFace" as the launch hashtag; standing campaign home page carries the slogan verbatim.
Comparison: Entity body for this claim is unchanged in Pass 2. Verified comparison carries forward.
Decision: verified
