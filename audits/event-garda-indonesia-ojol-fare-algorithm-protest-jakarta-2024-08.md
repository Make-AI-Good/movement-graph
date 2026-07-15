---
entity_id: event-garda-indonesia-ojol-fare-algorithm-protest-jakarta-2024-08
entity_hash: 4d33789d7ba399486481acc46785c7e568a28d12
audit_date: 2026-07-15
pass: 1
status: supported
claims_total: 30
claims_corroborated: 12
claims_primary_sourced: 0
claims_single_source: 9
claims_uncorroborated: 9
open_corrections: 0
sources_consulted:
  - https://www.thejakartapost.com/business/2024/08/28/protesting-drivers-to-suspend-online-delivery-ride-hailing-services.html
  - https://www.thejakartapost.com/business/2024/08/30/app-based-ojek-drivers-strike-over-low-pay.html
  - https://www.dealstreetasia.com/stories/indonesia-drivers-couriers-protest-410479
  - https://en.tempo.co/read/1910190/online-ojek-courier-drivers-stage-protest-gojek-manpower-ministry-respond
  - https://www.ituc-csi.org/long-silenced-gig-workers-in
  - https://www.tempo.co/cekfakta/sebagian-benar-demonstrasi-ojek-online-tuntut-tutup-aplikasi-gojek-dan-grab-347257
  - https://money.kompas.com/read/2024/08/29/111100626/ojol-demo-hari-ini-serikat-pekerja-tuntut-upah-layak-dan-kesejahteraan
  - https://www.kompas.com/jawa-timur/read/2025/05/19/140915288/demo-ojol-aksi-205-ribuan-driver-tuntut-keadilan-di-depan-istana
  - https://www.beritasatu.com/dki-jakarta/2905951/aksi-217-50000-ojol-klaim-siap-kepung-istana-dan-lumpuhkan-jakarta
  - https://www.tribunnews.com/metropolitan/2025/07/21/aksi-217-jeritan-50-ribu-pengemudi-ojol-kepung-istana-tuntut-keadilan-di-era-digital
  - https://indonesiabusinesspost.com/4801/society-environment-and-culture/thousands-of-ojol-drivers-rally-at-presidential-palace-seek-lower-commission-fees
  - https://www.cnnindonesia.com/otomotif/20250903181024-579-1269830/garda-ribuan-ojol-bakal-demo-17-september-di-dpr-bawa-tuntutan-baru
  - https://koran-jakarta.com/2025-09-09/ribuan-ojol-akan-demo-di-dpr-ri-17-september-garda-bawa-7-tuntutan-utama
  - https://en.tempo.co/read/2110789/how-govt-will-enforce-the-new-8-ride-hailing-fee-cap
  - https://en.antaranews.com/news/420677/indonesia-to-enforce-8-percent-ride-hailing-fee-cap-from-july-1
  - https://wageindicator.org/what-we-do/news-stories/indonesia-ride-hailing-platforms-commission
---

Type-shape: connective (event). Claim surface = edges + hard specifics per
`AUDITOR.md § What counts as a factual claim § Type-shape`; interpretive prose about
significance/register is not audited. Fetch notes: en.tempo.co (both cited and uncited
articles) and ituc-csi.org 403 on direct fetch this session — their content reached via
search snippets. The cited Tempo article (1909850) could therefore not be read in full;
claims resting solely on it are `uncorroborated` (honest limit, not error).

## Claim 1: scalar:date — "2024-08-29" (national one-day strike and protest on 29 August 2024)

Source: https://www.thejakartapost.com/business/2024/08/28/protesting-drivers-to-suspend-online-delivery-ride-hailing-services.html
Source tier: mainstream
Source content: "Date of Protest: August 29, 2024 (Thursday)" (Jakarta Post 28 Aug); DealStreetAsia day-of piece dated 29 August 2024; Jakarta Post 30 Aug: "Over 1,000 drivers protested ... on Thursday, August 29, 2024."
Comparison: Frontmatter `date` and body date match three independent outlets.
Decision: corroborated

## Claim 2: scalar:location — "Jakarta, Indonesia"

Source: https://www.dealstreetasia.com/stories/indonesia-drivers-couriers-protest-410479
Source tier: mainstream
Source content: DealStreetAsia: "Date: August 29, 2024. Location: Jakarta, Indonesia." Jakarta Post 28 Aug names three Jakarta sites.
Comparison: Location matches; the action's centre was Jakarta with spread elsewhere (Claim 19).
Decision: corroborated

## Claim 3: edge:participating_orgs → org-garda-indonesia

Source: https://www.thejakartapost.com/business/2024/08/28/protesting-drivers-to-suspend-online-delivery-ride-hailing-services.html
Source tier: mainstream
Source content: JP 28 Aug names "Two-Wheeler Action Movement (Garda)" as organizer with leader Igun Wicaksono; the target entity `org-garda-indonesia` is "Gabungan Aksi Roda Dua Indonesia (GARDA)", the same organization (tribunnews/disway: "Ketua Umum Garda Indonesia Igun Wicaksono").
Comparison: Edge points to the correct entity; organizer role confirmed by multiple outlets.
Decision: corroborated

## Claim 4: "drivers suspending all ride-hailing, food delivery, and courier services on the day" (Greater Jakarta)

Source: https://www.thejakartapost.com/business/2024/08/28/protesting-drivers-to-suspend-online-delivery-ride-hailing-services.html
Source tier: mainstream
Source content: "we...will not accept any food [delivery], ride or package [delivery] orders on Aug. 29"; "Food delivery, instant delivery, and ride-hailing services in the Greater Jakarta area on August 29." Liputan6 (search snippet) covers the same suspension.
Comparison: Matches body; scope (Greater Jakarta, all three service classes) matches source.
Decision: corroborated

## Claim 5: three protest sites — Merdeka Palace, Gojek office Petojo (Central Jakarta), Grab office Cilandak (South Jakarta)

Source: https://www.thejakartapost.com/business/2024/08/28/protesting-drivers-to-suspend-online-delivery-ride-hailing-services.html
Source tier: mainstream
Source content: "Merdeka Palace in Gambir, Central Jakarta ... Gojek office in Petojo, Central Jakarta; Grab office in Cilandak, South Jakarta." Tempo Indonesian and Kompas pre-event coverage (search snippets) name the same three sites.
Comparison: All three sites and their districts match.
Decision: corroborated

## Claim 6: "Over 1,000 drivers assembled at three sites"

Source: https://www.thejakartapost.com/business/2024/08/30/app-based-ojek-drivers-strike-over-low-pay.html
Source tier: mainstream
Source content: JP 30 Aug: "Over 1,000 drivers protested across multiple cities on Thursday, August 29, 2024." ITUC (search snippet): "thousands of striking motorcycle taxi gig workers and their allies filled the streets around the Presidential palace and the headquarters of Grab and GoJek in Jakarta."
Comparison: JP gives 1,000+ (across cities); ITUC puts "thousands" at the Jakarta three-site cluster specifically — jointly the body's binding of 1,000+ to the Jakarta sites holds.
Decision: corroborated

## Claim 7: SPAI (Serikat Pekerja Angkutan Indonesia) co-organised alongside GARDA; Lily Pujiati as SPAI leader

Source: https://www.ituc-csi.org/long-silenced-gig-workers-in
Source tier: database
Source content: ITUC (search snippet): "Lily Pujiati, Chairperson of the Indonesian Transport Workers Union (SPAI), stated that the online ojek drivers protest was intended to demand the online ojek platforms fulfill partners' welfare." Kompas (29 Aug 2024, search snippet): "Ojol Demo Hari Ini, Serikat Pekerja Tuntut Upah Layak dan Kesejahteraan Pengemudi" (SPAI demands).
Comparison: SPAI's organising role in the 29 Aug action and Pujiati's leadership both confirmed by two independent sources (a union-confederation feature and mainstream news).
Decision: corroborated

## Claim 8: Igun Wicaksono is GARDA's General Chairman (Ketua Umum)

Source: https://en.tempo.co/read/1910190/online-ojek-courier-drivers-stage-protest-gojek-manpower-ministry-respond
Source tier: mainstream
Source content: Tempo EN (search snippet): "Wicaksono, the General Chairperson of the National Garda Indonesia Online Two-Wheeled Transportation Drivers Association"; tribunnews/disway tags: "Ketua Umum Garda Indonesia Igun Wicaksono."
Comparison: Title matches (General Chairman/Chairperson = Ketua Umum).
Decision: corroborated

## Claim 9: Igun Wicaksono quote — "We want the government to determine a fair price or tariff for online motorcycle taxis, and be a regulatory enforcer and impose sanctions on any platform that harms online motorcycle taxi drivers."

Source: https://en.tempo.co/read/1910190/online-ojek-courier-drivers-stage-protest-gojek-manpower-ministry-respond
Source tier: mainstream
Source content: Search snippet reproduces the quote verbatim: "Igun Wicaksono, chairperson of Garda (representing 400,000 members), stated: 'We want the government to determine a fair price or tariff for online motorcycle taxis, and be a regulatory enforcer and impose sanctions on any platform that harms online motorcycle taxi drivers.'"
Comparison: Verbatim match; living-person quote resting on one mainstream outlet (Tempo; direct fetch 403'd, snippet-confirmed).
Decision: single-source

## Claim 10: the demands formed a "five-point demand package" (per the cited Tempo article)

Source: https://en.tempo.co/read/1909850/online-ojek-drivers-to-protest-welfare-at-merdeka-palace-and-gojek-grab-offices
Source tier: none
Source content: Cited Tempo article 403s on direct fetch; no reachable source reproduces a five-point enumeration. Other coverage enumerates differently: VOI/Kompas (search snippets) report "six main demands from the National Ojol Coalition (KON)".
Comparison: The individual demands are separately supported (Claims 9, 11, 13), but the five-point packaging as attributed to Tempo cannot be compared — and adjacent coverage counts six. Honest limit, not a finding of error.
Decision: uncorroborated

## Claim 11: women workers' demands — paid leave for pregnancy, childbirth, and miscarriage; childcare access; breastfeeding support — raised by Lily Pujiati

Source: https://www.ituc-csi.org/long-silenced-gig-workers-in
Source tier: database
Source content: ITUC (search snippet): partner status costs drivers "the right to maternity leave, childbirth leave, and miscarriage leave for female drivers. Lily requested that platforms also provide opportunities for nursing mothers and childcare facilities provided by the platforms."
Comparison: All three specifics and the Pujiati attribution match; rests on the one ITUC feature.
Decision: single-source

## Claim 12: demand 4 composite — accident insurance, health coverage, and recognition of right to form unions / collective bargaining

Source: https://www.ituc-csi.org/long-silenced-gig-workers-in
Source tier: database
Source content: ITUC (search snippet) confirms union-recognition and lost-labor-rights framing ("With partner status, online ojek drivers and couriers automatically lose their workers' rights"); no reachable source this session confirms accident-insurance or health-coverage demands for this specific action.
Comparison: Partial confirmation only — union recognition yes, insurance/health specifics unverified (they may sit in the unreachable Tempo article).
Decision: uncorroborated

## Claim 13: commission-reduction demand — greater driver share per fare, ceiling on platform commission percentage

Source: https://www.thejakartapost.com/business/2024/08/30/app-based-ojek-drivers-strike-over-low-pay.html
Source tier: mainstream
Source content: "Protesters sought two main changes: raising driver revenue share from the current 80 percent per trip, and obtaining special government employment status to strengthen bargaining power over fees."
Comparison: Raising the driver share above 80% = lowering commission below 20%; matches the body's commission-cap demand.
Decision: single-source

## Claim 14: demand 3 — removal of platforms' unilateral suspension/termination options

Source: no canonical source found
Source tier: none
Source content: The claim is attributed to the cited Tempo article (403 on fetch); no reachable source this session ties an anti-deactivation demand to this specific action.
Comparison: Cannot compare; consistent with SPAI's broader platform-labor agenda but unverified for 29 Aug 2024.
Decision: uncorroborated

## Claim 15: one driver reported ten-hour shifts earning less than Rp 150,000 (~US $9.73) most days, below Jakarta's minimum wage

Source: https://www.thejakartapost.com/business/2024/08/30/app-based-ojek-drivers-strike-over-low-pay.html
Source tier: mainstream
Source content: "One driver named Wandi reported working 10-hour daily shifts but earning less than Rp 150,000 (approximately $9.73) most days—below Jakarta's minimum wage of Rp 5 million."
Comparison: Figures match exactly (hours, rupiah, USD conversion, below-minimum-wage framing). The body's causal elaboration ("fare levels and platform fees together stripped enough value...") is interpretive gloss on the sourced figures.
Decision: single-source

## Claim 16: platform list — fares/commissions set algorithmically by "Gojek, Grab, Maxim, Shopee, inDrive, Lalamove, Borzo"

Source: https://www.tempo.co/cekfakta/sebagian-benar-demonstrasi-ojek-online-tuntut-tutup-aplikasi-gojek-dan-grab-347257
Source tier: mainstream
Source content: Tempo cekfakta (search snippet): "online ojek drivers' income is decreasing due to fare wars between platforms such as Gojek, Grab, Maxim, Shopee, Indrive, Lalamove, Borzo, and others" (per Lily Pujiati). JP 28 Aug names five of the seven ("Grab, Gojek, Maxim, Shopee and Lalamove").
Comparison: The full seven-platform list matches one source verbatim; the second source overlaps on five.
Decision: single-source

## Claim 17: attribution — "GARDA characterised this arrangement as structurally exploitative: competing platforms algorithmically undercut fares in a race to the bottom"

Source: https://www.tempo.co/cekfakta/sebagian-benar-demonstrasi-ojek-online-tuntut-tutup-aplikasi-gojek-dan-grab-347257
Source tier: none
Source content: The reachable source attributes the fare-war characterization to Lily Pujiati (SPAI): "According to labor union leader Lily Pujiati, online ojek drivers' income is decreasing due to fare wars between platforms."
Comparison: Body attributes the race-to-the-bottom characterization to GARDA; the reachable source attributes it to SPAI's Pujiati. The cited Tempo article (which might carry a GARDA version) is unreachable, so this is an attribution the audit cannot confirm — flagged as a possible GARDA-vs-SPAI attribution slip, but with no verifiable single-token replacement it is not a correction.
Decision: uncorroborated

## Claim 18: placard quote — "Driver take hikmah (wisdom), applicator takes as many pieces as possible"

Source: https://www.thejakartapost.com/business/2024/08/30/app-based-ojek-drivers-strike-over-low-pay.html
Source tier: mainstream
Source content: JP 30 Aug: "A placard read: 'Driver take wisdom, applicator takes as many pieces as possible' (translating the concept of 'hikmah')." DealStreetAsia photo caption: "Driver take hikmah (wisdom), applicator takes as many pieces as possible."
Comparison: Verbatim match in two independent outlets.
Decision: corroborated

## Claim 19: the action spread to other Indonesian cities (nationally coordinated character)

Source: https://www.thejakartapost.com/business/2024/08/30/app-based-ojek-drivers-strike-over-low-pay.html
Source tier: mainstream
Source content: "Over 1,000 drivers protested across multiple cities on Thursday, August 29, 2024."
Comparison: "Multiple cities" supports the national-spread claim; only JP 30 Aug carries it among sources reached.
Decision: single-source

## Claim 20: the service withdrawal generated social media complaints about disruption

Source: no canonical source found
Source tier: none
Source content: No source reached this session covers public/social-media reaction to the service withdrawal.
Comparison: Cannot compare; plausible but unverified.
Decision: uncorroborated

## Claim 21: platform responses — Gojek: operations normal, "open to drivers' input"; Grab: tariffs balance stable demand with driver earnings; no commitments to alter commissions

Source: https://www.thejakartapost.com/business/2024/08/30/app-based-ojek-drivers-strike-over-low-pay.html
Source tier: mainstream
Source content: "Gojek stated operations ran normally and the company remained 'open to drivers' input'. Grab's Tirza Munusamy explained tariffs were 'designed to ensure stable demand...while keeping in mind drivers' earnings'."
Comparison: Both responses match closely; rests on the one JP 30 Aug piece.
Decision: single-source

## Claim 22: government responses — Transportation Ministry declined regulatory authority over fees and urged platforms to address drivers; Manpower Ministry gave no immediate comment

Source: https://www.thejakartapost.com/business/2024/08/30/app-based-ojek-drivers-strike-over-low-pay.html
Source tier: mainstream
Source content: "The Transportation Ministry declined to regulate fees, urging platforms to 'listen to drivers.' The Manpower Ministry did not immediately respond to requests for comment."
Comparison: Matches body on both ministries.
Decision: single-source

## Claim 23: "fare amounts and the commission share ... set algorithmically by each company, with no regulatory floor" / "no Indonesian ministry claimed binding authority over platform commission structures"

Source: https://en.tempo.co/read/2110789/how-govt-will-enforce-the-new-8-ride-hailing-fee-cap
Source tier: none
Source content: Coverage of Perpres 27/2026 (Tempo EN / wageindicator, search-confirmed): "Before this regulation, the commission cap was set at 20% under the Ministry of Transportation's Decree KP 1001 of 2022." Against that, JP 30 Aug 2024: "The Transportation Ministry declined to regulate fees."
Comparison: Canonical sources are in tension: a Transportation Ministry decree (KP 1001/2022) did nominally cap commissions at 20% before Perpres 27/2026, while the ministry's stated 2024 position was that it would not regulate fees. The body's blanket "no regulatory floor / no ministry claimed binding authority" overstates the regulatory vacuum as literal fact, though it tracks the ministry's own 2024 posture. Sources conflict — no winner picked, and no single-token fix exists.
Decision: uncorroborated

## Claim 24: Aksi 205 (May 2025, coordinated multi-city strikes)

Source: https://www.kompas.com/jawa-timur/read/2025/05/19/140915288/demo-ojol-aksi-205-ribuan-driver-tuntut-keadilan-di-depan-istana
Source tier: mainstream
Source content: Kompas / Pojoksatu (search snippets): Aksi 205 held 20 May 2025; "thousands of ojol drivers ... drivers coming from various regions outside Jakarta such as Bogor, Palembang, Subang, and East Java"; "accompanied by a mass offbid (collective suspension of services through app shutdown) predicted to significantly paralyze online transportation and delivery services."
Comparison: Date (May 2025) and coordinated-strike character (mass offbid, multi-region participation) match two independent outlets.
Decision: corroborated

## Claim 25: Aksi 217 (July 2025, 50,000+ drivers at the Presidential Palace)

Source: https://www.tribunnews.com/metropolitan/2025/07/21/aksi-217-jeritan-50-ribu-pengemudi-ojol-kepung-istana-tuntut-keadilan-di-era-digital
Source tier: mainstream
Source content: Tribunnews (21 July 2025): "Jeritan 50 Ribu Pengemudi Ojol Kepung Istana" [the cry of 50 thousand ojol drivers surrounding the Palace]. Indonesia Business Post: "tens of thousands of ojol drivers rallied in front of the Presidential Palace ... Chairman Raden Igun Wicaksono estimating over 50,000 drivers in participation."
Comparison: Date and location corroborated by multiple outlets; the 50,000+ figure traces to the organizer's estimate (Beritasatu pre-event headline frames it as a claim: "50.000 Ojol Klaim Siap Kepung Istana"), with Tribunnews asserting it directly. The body states the figure as fact; support is real but the count rests on organizer-derived reporting.
Decision: single-source

## Claim 26: the September 2025 DPR demonstration

Source: https://www.cnnindonesia.com/otomotif/20250903181024-579-1269830/garda-ribuan-ojol-bakal-demo-17-september-di-dpr-bawa-tuntutan-baru
Source tier: mainstream
Source content: CNN Indonesia / Koran Jakarta / Kompas (search snippets): GARDA-led demonstration at the DPR on 17 September 2025 with seven main demands including revising application cuts; DPR Commission V agreed to include the Online Transportation Bill in the 2025–2026 legislative program.
Comparison: A GARDA demonstration at the DPR in September 2025 is confirmed by multiple outlets.
Decision: corroborated

## Claim 27: Perpres 27/2026 capping platform commissions at 8%, down from up to 20%

Source: https://en.antaranews.com/news/420677/indonesia-to-enforce-8-percent-ride-hailing-fee-cap-from-july-1
Source tier: mainstream
Source content: ANTARA: "Indonesia to enforce 8 percent ride-hailing fee cap from July 1 [2026]" under Presidential Regulation No. 27 of 2026; Tempo EN / wageindicator: prior cap "set at 20% under the Ministry of Transportation's Decree KP 1001 of 2022"; announced by President Prabowo Subianto on 1 May 2026.
Comparison: Regulation number, 8% cap, and prior 20% ceiling all match multiple outlets. (The body's "traceable to the mobilisation energy" framing is interpretation, not audited.)
Decision: corroborated

## Claim 28: "the first major national public action" in GARDA's campaign against platform commission structures

Source: no canonical source found
Source tier: none
Source content: No reached source ranks this action as the first major national action in GARDA's campaign; JP 30 Aug notes only that it distinguished itself from "previous localised driver demonstrations" indirectly via the multi-city framing.
Comparison: "First"-class claims are contested-attribution territory (source rule); no source confirms or refutes the ranking.
Decision: uncorroborated

## Claim 29: scalar:sources[3].note — DealStreetAsia confirms "the protest across platforms including Gojek, Grab, Shopee, and inDrive"

Source: https://www.dealstreetasia.com/stories/indonesia-drivers-couriers-protest-410479
Source tier: none
Source content: The fetchable (unpaywalled) portion shows only the headline, photo, and placard caption: "The article does not specify which ride-hailing or delivery platforms were affected" — the platform list sits behind the paywall, as the note itself acknowledges.
Comparison: The note's platform-list characterization (scalar path `sources[3].note`) cannot be checked against the visible portion; notably inDrive appears in no other reached source's list for this action's targets.
Decision: uncorroborated

## Claim 30: scalar:sources[0].note — JP 28 Aug as source for "Lily Pujiati (SPAI) as co-organising voice alongside GARDA head Igun Wicaksono"

Source: https://www.thejakartapost.com/business/2024/08/28/protesting-drivers-to-suspend-online-delivery-ride-hailing-services.html
Source tier: none
Source content: The 28 Aug JP article as fetched names Garda and Igun Wicaksono as organizers; Pujiati does not surface in the fetched content.
Comparison: Pujiati's co-organising role is real (Claim 7, via ITUC/Kompas) but does not appear attributable to this particular article (scalar path `sources[0].note`) — a possible source-note misattribution; not a correction since the fetch summary may be incomplete and the underlying fact stands.
Decision: uncorroborated
