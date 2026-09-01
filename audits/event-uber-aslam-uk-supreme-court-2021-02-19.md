---
entity_id: event-uber-aslam-uk-supreme-court-2021-02-19
entity_hash: 96e07846320df89c8705047cb520ed85d2f2c770
audit_date: 2026-09-01
pass: 1
status: corrections-pending
claims_total: 30
claims_corroborated: 5
claims_primary_sourced: 10
claims_single_source: 3
claims_uncorroborated: 10
open_corrections: 2
sources_consulted:
  - https://www.supremecourt.uk/cases/uksc-2019-0029
  - https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
  - https://www.judiciary.uk/wp-content/uploads/2016/10/aslam-and-farrar-v-uber-reasons-20161028.pdf
  - https://assets.publishing.service.gov.uk/media/5a046b06e5274a0ee5a1f171/Uber_B.V._and_Others_v_Mr_Y_Aslam_and_Others_UKEAT_0056_17_DA.pdf
  - https://en.wikipedia.org/wiki/Uber_BV_v_Aslam
  - https://academic.oup.com/ilj/article/51/4/955/6991308
  - https://www.gov.uk/employment-tribunal-decisions/mr-j-farrar-v-uber-london-ltd-and-others-2202551-slash-2015
  - https://responsibledata.io/rd-reflection-stories/data-rights-for-workers-in-the-gig-economy/
  - https://adcu.org.uk/about-us
  - https://www.sec.gov/Archives/edgar/data/1543151/000155278121000124/e21143_ex99-1.htm
  - https://www.cnbc.com/2021/03/18/uber-is-reclassifying-uk-drivers-as-workers-heres-what-happens-next.html
  - https://techcrunch.com/2023/04/05/uber-ola-gdpr-worker-data-access-rights-appeal/
  - https://www.landers.com.au/legal-insights-news/will-uk-supreme-court-classification-of-uber-drivers-as-workers-drive-change-in-australia
  - https://harvardlawreview.org/blog/2021/03/recent-case-_uber-bv-v-aslam_/
  - https://edition.cnn.com/2021/02/19/tech/uber-uk-workers/index.html
---

## Claim 1: scalar:date — "2021-02-19" (and body "On Friday 19 February 2021, the UK Supreme Court delivered a unanimous judgment")

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "JUDGMENT GIVEN ON 19 February 2021" (judgment heading); case page: "Judgment Date: 19 February 2021 … Neutral Citation: [2021] UKSC 5"; Wikipedia and ILJ concur. 19 Feb 2021 was a Friday.
Comparison: Frontmatter `date` scalar and body date match the judgment heading and the UKSC case page; independently confirmed by Wikipedia and the Industrial Law Journal.
Decision: corroborated

## Claim 2: scalar:location — "London, United Kingdom"

Source: https://en.wikipedia.org/wiki/Uber_BV_v_Aslam
Source tier: tiebreaker
Source content: The UK Supreme Court sits in London (Parliament Square); the case was heard and judgment delivered there.
Comparison: Named-entity definitional/public-record fact (seat of the court) — Wikipedia-alone-sufficient class. No source contradicts.
Decision: single-source

## Claim 3: edge:participating_people — org edge to person-james-farrar; body "Yaseen Aslam and James Farrar were the named test claimants"

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "the employment tribunal limited its consideration to two test claimants, Mr Yaseen Aslam and Mr James Farrar, both of whom were licensed to drive private hire vehicles in London" (¶4)
Comparison: Edge points to the correct entity (person-james-farrar exists); Farrar was a named test claimant per the judgment.
Decision: primary-sourced

## Claim 4: edge:participating_orgs — org-app-drivers-and-couriers-union; body "co-founders of what became the App Drivers and Couriers Union (ADCU)"

Source: https://adcu.org.uk/about-us
Source tier: primary
Source content: "ADCU was officially registered as an independent trade union in July 2020" (ADCU site); search-record: "Aslam and Farrar formed the United Private Hire Drivers (UPHD) association in 2015. The members decided to rebrand as the App Drivers and Couriers Union, and the rebranded ADCU was officially registered … July 2020" (Computer Weekly interview + Wikipedia, via search snippets)
Comparison: Edge points to the correct existing entity; "what became the ADCU" matches the UPHD→ADCU institutional history. Organization-founding facts are in the Wikipedia-alone-sufficient class; Computer Weekly independently concurs.
Decision: corroborated

## Claim 5: edge:participating_orgs — org-worker-info-exchange; body "Worker Info Exchange, which Farrar had incorporated as a vehicle for operationalising data-subject access rights for platform workers"

Source: https://responsibledata.io/rd-reflection-stories/data-rights-for-workers-in-the-gig-economy/
Source tier: mainstream
Source content: "Most recently, Farrar launched a nonprofit called the Worker Info Exchange, with the goal of helping app-based, gig economy workers take back control of their data" … WIE aims to "help workers file individual subject access requests"
Comparison: Edge points to the correct existing entity; Farrar-founded and the data-subject-access purpose both match one canonical source (TechCrunch confirms WIE as "not-for-profit data trust" but not the founder).
Decision: single-source

## Claim 6: "holding that Uber drivers are 'workers' within the meaning of section 230(3)(b) of the Employment Rights Act 1996 and are entitled to the national minimum wage and … paid annual leave"

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "the employment tribunal was entitled to find that drivers whose work is arranged through Uber's smartphone application … work for Uber under workers' contracts"; s.230(3) "limb (b)" definition analysed; claims include "rights under the National Minimum Wage Act 1998 … annual leave"
Comparison: Body holding matches the judgment's disposition and the statutory provision it construes.
Decision: primary-sourced

## Claim 7: "28 days of paid annual leave"

Source: https://en.wikipedia.org/wiki/Uber_BV_v_Aslam
Source tier: tiebreaker
Source content: "The Court held that Uber must pay drivers … national living wage … at least 28 days paid holidays"
Comparison: The judgment itself says "annual leave" without quantifying; the 28-day figure is the statutory full-time entitlement (Working Time Regulations 1998) — a named-statute/public-record fact in the Wikipedia-alone-sufficient class.
Decision: single-source

## Claim 8: "calculated from the time they have the Uber app switched on and are within the authorised territory and willing to accept assignments"

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "working under such contracts whenever they were logged into the Uber app within the territory in which they were licensed to operate and ready and willing to accept trips"; EAT: "any Uber driver who had the Uber app switched on, was within the territory in which they were authorised to work…"
Comparison: Body working-time formulation matches the judgment's affirmed holding.
Decision: primary-sourced

## Claim 9: "delivered by Lord Leggatt and joined without dissent by four further justices"

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "LORD LEGGATT: (with whom Lord Reed, Lord Hodge, Lady Arden, Lord Sales and Lord Hamblen agree)" — five further justices. Seven heard the appeal; "Lord Kitchin fell ill and it was uncertain when he would return to work" (he did not join the judgment). Wikipedia concurs: five agreed.
Comparison: The token "four" contradicts the judgment heading: Lord Leggatt was joined by FIVE further justices (six deciding; Kitchin heard argument but took no part). Single correct replacement: "four" → "five".
Decision: correction

## Claim 10: "the first time the UK Supreme Court addressed whether algorithmic platform control over workers constitutes employer control in law"

Source: no canonical source found
Source tier: none
Source content: No fetched source asserts this "first". HLR blog (via snippets) discusses "tight algorithmic control" but does not state a first-ness claim.
Comparison: Contested-"first" claim class (tiebreaker-insufficient); no canonical source found asserting it. Not contradicted — plausibly true — but the audit cannot support it.
Decision: uncorroborated

## Claim 11: "The proceedings began in 2015"

Source: https://www.gov.uk/employment-tribunal-decisions/mr-j-farrar-v-uber-london-ltd-and-others-2202551-slash-2015
Source tier: primary
Source content: Case numbers "2202550/2015" (Aslam) and "2202551/2015" (Farrar) on the gov.uk employment-tribunal register — 2015-year case numbers; body's "almost six years after the original claim was filed" (to Feb 2021) is arithmetically consistent.
Comparison: The 2015 commencement matches the tribunal case numbers on the government register.
Decision: primary-sourced

## Claim 12: "25 Uber drivers filed an employment tribunal claim" (and Significance: "organising the 25-driver claim in 2015")

Source: https://apps.eurofound.europa.eu/platformeconomydb/aslam-and-farrar-vs-uber-case-22025502015-95042
Source tier: database
Source content: Via search snippets: "law firm Leigh Day started the legal action against Uber on behalf of 25 members of the GMB union, which initially included J. Farrar and Y. Aslam" (Eurofound platform-economy DB); but another account: "as a test case on behalf of a group of 19 drivers". The cited primary (ET reasons PDF) is a scanned image with no text layer — unparseable.
Comparison: Canonical accounts conflict on the count (25 vs 19) and the entity's cited primary source could not be machine-read to resolve it. Per decision rules, conflicting canonical sources → uncorroborated; no correction asserted since 25 may well be the ET-recorded figure.
Decision: uncorroborated

## Claim 13: "At the time of the original tribunal hearing, approximately 40,000 Uber drivers were operating in the UK, around 30,000 of them in the London area"

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "At the time of the employment tribunal hearing in 2016, there were about 30,000 Uber drivers operating in the London area and 40,000 in the UK as a whole" (¶5)
Comparison: Both figures and the timing anchor match the judgment exactly.
Decision: primary-sourced

## Claim 14: "The Central London Employment Tribunal ruled unanimously for the drivers on 28 October 2016"

Source: https://www.judiciary.uk/wp-content/uploads/2016/10/aslam-and-farrar-v-uber-reasons-20161028.pdf
Source tier: primary
Source content: ET reasons dated 28 October 2016 (document date in cited source); legal summaries via search snippets: "The employment tribunal unanimously held that the drivers were 'workers' within the definition in section 230(3)(b) of the Employment Rights Act 1996"
Comparison: Date matches the cited reasons document; unanimity independently reported by legal-sector summaries (Personnel Today, charteredaccountants.ie digest).
Decision: corroborated

## Claim 15: "The Employment Appeal Tribunal upheld the finding in 2017"

Source: https://assets.publishing.service.gov.uk/media/5a046b06e5274a0ee5a1f171/Uber_B.V._and_Others_v_Mr_Y_Aslam_and_Others_UKEAT_0056_17_DA.pdf
Source tier: primary
Source content: "Judgment handed down on 10 November 2017 … HER HONOUR JUDGE EADY QC" … "In the circumstances and for all those reasons, I dismiss Uber's appeal."
Comparison: EAT dismissed Uber's appeal in November 2017 — matches "upheld the finding in 2017".
Decision: primary-sourced

## Claim 16: "the Court of Appeal upheld it again in 2018"

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: Judgment heading: "On appeal from: [2018] EWCA Civ 2748"; ILJ: "in December 2018, the majority of the Court of Appeal arrived at a similar conclusion in rejecting Uber's further appeal"
Comparison: 2018 CA decision confirmed by the UKSC citation line and the ILJ account (majority, not unanimous — body does not claim CA unanimity, so no conflict).
Decision: corroborated

## Claim 17: "on 19 February 2021 … dismissed Uber's appeal unanimously, affirming all three lower courts"

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "I would affirm the conclusion of the Employment Appeal Tribunal and the majority of the Court of Appeal that the employment tribunal was entitled to decide both questions in the claimants' favour" — with all five other participating justices agreeing, no dissent.
Comparison: Unanimous among the six deciding justices; appeal dismissed; ET/EAT/CA all affirmed. Matches.
Decision: primary-sourced

## Claim 18: The five factors — fares fixed by Uber; contract terms imposed; ride-acceptance constrained (penalised or logged off); service delivery controlled via star-rating system with removal below threshold; driver-passenger communication restricted

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "First … the remuneration paid to drivers … is fixed by Uber and the drivers have no say in it"; "Second, the contractual terms … are dictated by Uber"; "Third … a driver's choice about whether to accept requests for rides is constrained by Uber" (warnings, "automatically logged off"); "Fourth, Uber exercises a significant degree of control over the way in which drivers deliver their services … failure of a driver to maintain a specified average rating will result in warnings and ultimately in termination"; "A fifth significant factor is that Uber restricts communication between passenger and driver to the minimum necessary to perform the particular trip"
Comparison: All five body factors match ¶¶94–100 of the judgment in substance and order.
Decision: primary-sourced

## Claim 19: Purposive reasoning — "courts must interpret employment status legislation to give effect to its protective purpose and must not allow that purpose to be defeated by contractual drafting"; rejection of Uber's face-value contract argument

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: purpose of protecting "vulnerable workers from being paid too little for the work they do, required to work excessive hours or subjected to other forms of unfair treatment"; "The efficacy of such protection would be seriously undermined if the putative employer could by the way in which the relationship is characterised in the written contract determine, even prima facie, whether or not the other party is to be classified [as a worker]"
Comparison: Body's purposive-reasoning account matches the judgment's own words. (The cited ukscblog.com page failed fetch — TLS certificate error — but the underlying content is verified against the primary source.)
Decision: primary-sourced

## Claim 20: "The court left open whether drivers were also 'employees' … but indicated that the indicia of employment were substantially satisfied"

Source: no canonical source found
Source tier: none
Source content: The extracted judgment text contains no passage on "employee" status being left open or "indicia of employment … substantially satisfied"; the case concerned limb (b) worker status only. ILJ: "The judgment focused on 'limb (b) worker' status specifically."
Comparison: The "left open" half is accurate by omission, but the "indicated that the indicia of employment were substantially satisfied" assertion is found in no fetched source and not in the judgment. Judgment-loaded edge; cannot support.
Decision: uncorroborated

## Claim 21: "worker rights run from app-switch-on within the authorised territory, not only from the moment a ride is accepted … minimum wage applied to all the time drivers were on the app and available"

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: "whether … the drivers … were working under such contracts whenever they were logged into the Uber app within the territory … and ready and willing to accept trips; or whether, as Uber argues, they were working only when driving passengers to their destinations. For the reasons given in this judgment, I would affirm the conclusion of the Employment Appeal Tribunal…"
Comparison: The working-time consequence matches the affirmed holding (Uber's narrower driving-only argument rejected).
Decision: primary-sourced

## Claim 22: Yaseen Aslam "told CNN Business on the day of the ruling" that compensation was "small" compared to the effort but "someone had to do it" (body + scalar:sources[2].note)

Source: https://edition.cnn.com/2021/02/19/tech/uber-uk-workers/index.html
Source tier: none
Source content: The cited CNN article returns HTTP 451 (Unavailable For Legal Reasons) on both URL forms; the quoted phrases were not found in any search snippet or alternative coverage this session.
Comparison: The cited source is unreachable and the specific quotes could not be located elsewhere. Living-person quoted statement — tiebreaker-insufficient class. Not contradicted; cannot be supported this pass.
Decision: uncorroborated

## Claim 23: WIE "framed the ruling as establishing that algorithmic managerial control and contractual control are legally equivalent — a reading that directly shaped WIE's subsequent data-rights litigation strategy in the Amsterdam courts"

Source: https://techcrunch.com/2023/04/05/uber-ola-gdpr-worker-data-access-rights-appeal/
Source tier: mainstream
Source content: "The appeal was brought by the not-for-profit data trust Worker Info Exchange (WIE) in support of members of the App Drivers & Couriers Union (ADCU)" (Amsterdam appellate data-rights litigation confirmed)
Comparison: The Amsterdam WIE/ADCU data-rights litigation is real and well-sourced, but no source was found for WIE's specific "legally equivalent" framing of this ruling, and "directly shaped" is a causal claim (tiebreaker-insufficient class) no source states.
Decision: uncorroborated

## Claim 24: "Within weeks of the ruling, Uber announced … automatic holiday-pay accrual, and enrolling UK drivers into an auto-enrolled pension scheme. These changes applied to approximately 70,000 UK Uber drivers"

Source: https://www.sec.gov/Archives/edgar/data/1543151/000155278121000124/e21143_ex99-1.htm
Source tier: primary
Source content: Uber's March 2021 announcement (SEC exhibit / press release, via search record): "more than 70,000 drivers in the UK would be treated as workers"; "paid holiday time based on 12.07% of their earnings, paid out on a fortnightly basis"; "automatically be enrolled into a pension plan with contributions from Uber" — also carried by CNBC, Forbes, Fortune.
Comparison: Announcement ~16 March 2021 ("within weeks" of 19 Feb ✓); holiday pay, auto-enrolled pension, and ~70,000-driver scope all match Uber's own announcement and mainstream coverage.
Decision: corroborated

## Claim 25: Uber's changes included "paying drivers the national living wage for time on the app"

Source: https://www.cnbc.com/2021/03/18/uber-is-reclassifying-uk-drivers-as-workers-heres-what-happens-next.html
Source tier: primary
Source content: Uber's announcement: drivers "earning at least the National Living Wage … after accepting a trip request and after expenses" (Uber press release via SEC exhibit and CNBC/Forbes coverage). Wikipedia: "Uber indicated that it intended to violate the Supreme Court ruling, by only paying drivers the minimum wage while driving, not when being available for work."
Comparison: The token "for time on the app" contradicts the best sources: Uber's implementation paid NLW from trip acceptance, not from app-on time — that gap was the central post-ruling criticism (ADCU: drivers "short-changed to the tune of 40-50%"). Single correct replacement: "for time on the app" → "from trip acceptance".
Decision: correction

## Claim 26: "represented the largest single statutory-worker benefit extension in the UK gig economy to that date"

Source: no canonical source found
Source tier: none
Source content: No fetched source makes this superlative claim.
Comparison: Load-bearing superlative characterization (contested-class; tiebreaker-insufficient); no canonical source found asserting it.
Decision: uncorroborated

## Claim 27: "subsequent courts in other jurisdictions — including Australia and Canada — cited it when addressing analogous gig-worker classification questions"

Source: https://www.landers.com.au/legal-insights-news/will-uk-supreme-court-classification-of-uber-drivers-as-workers-drive-change-in-australia
Source tier: caution
Source content: Via search record: "when referred to in Australian proceedings, one deputy president said that Aslam was 'of no assistance' because it concerned the 'worker' category, which was more expansive than the employee category under Australian law"; no Canadian court citation of Aslam surfaced (Canadian Uber litigation — Uber v Heller — concerns arbitration, not this ruling).
Comparison: Australia: referred to but expressly distinguished — weak support for "cited … when addressing analogous questions". Canada: no citation found. The claim as stated is not supported by canonical sources found this session.
Decision: uncorroborated

## Claim 28: "the Harvard Law Review characterised the ruling as a landmark in the developing global body of law on algorithmic labour control" (body + scalar:sources[4].note)

Source: https://harvardlawreview.org/blog/2021/03/recent-case-_uber-bv-v-aslam_/
Source tier: mainstream
Source content: HLR blog (direct fetch 403; via search snippets): "Aslam is a major victory for gig workers"; five elements highlighted including "information asymmetries created by the app to exercise tight algorithmic control once a driver is logged on"
Comparison: The HLR case note exists (March 2021, matching the note's date) and discusses algorithmic control, but the specific "landmark in the developing global body of law on algorithmic labour control" characterization — and sources[4].note's "legally equivalent to traditional employer control … precedent … beyond the UK" — could not be verified against retrievable text; too paraphrastic to compare on snippet evidence. Scalar path for any future fix: sources[4].note.
Decision: uncorroborated

## Claim 29: "Farrar and Aslam organising the 25-driver claim in 2015, losing their accounts, building the ADCU, and filing the original tribunal claim before either Farrar's 2016 GDPR data-access request or Worker Info Exchange existed"

Source: https://www.trtworld.com/magazine/the-pakistan-origin-driver-behind-a-landmark-uber-case-41040
Source tier: caution
Source content: Via search snippets: "In February 2015, when [Aslam] tried to log in, he found he had been 'deactivated' for the first time with no reason given or warning." No source found for Farrar losing his account, nor for a 2016 Farrar data-access request (responsibledata.io describes subject access requests beginning ~2018–2019 leading to the March 2019 lawsuit; a 2016 request would predate the GDPR's 2018 application, making the "GDPR" label doubtful).
Comparison: Compound claim: 2015 organising ✓ (Claim 11), 25-driver count unresolved (Claim 12), Aslam's deactivation thinly sourced, Farrar's account loss and the "2016 GDPR data-access request" unsupported — and the GDPR label is anachronistic for 2016. Multiple judgment-loaded edges; prose-judgment fix territory, not a single-token correction.
Decision: uncorroborated

## Claim 30: scalar:sources[0].note and scalar:sources[1].note — the cited primary documents support the facts attributed to them

Source: https://supremecourt.uk/uploads/uksc_2019_0029_judgment_19c9de2253.pdf
Source tier: primary
Source content: sources[0].note's attributed facts (19 Feb 2021, [2021] UKSC 5, Leggatt lead judgment with no dissent among participants, five-factor analysis) all verified against the case page and judgment (Claims 1, 9, 17, 18) — with the caveat that the case page hosts, rather than displays, the five-factor analysis. sources[1].note attributes to the ET reasons: Aslam/Farrar co-lead claimants ✓ (verified via UKSC ¶4), 2015 originating claim ✓ (case numbers), unanimous finding ✓ (legal summaries) — but "the 2015 originating claim by 25 drivers" could not be verified: the ET reasons PDF is a scanned image with no text layer, and secondary counts conflict (Claim 12).
Comparison: sources[0].note fully supported by primary; sources[1].note's "25 drivers" component unverifiable against its own cited document. Scalar path for any future fix: sources[1].note. Note also the "unanimous judgment" phrasing is accurate only of the six participating justices (see Claim 9).
Decision: uncorroborated
