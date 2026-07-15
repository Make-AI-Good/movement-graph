---
entity_id: camp-bits-of-freedom-syri-welfare-algorithm-netherlands-2019-2020
entity_hash: 5ea30abb75fa863f8a599f7f1558828fbe82c9b3
audit_date: 2026-07-15
pass: 2
status: supported
claims_total: 21
claims_corroborated: 13
claims_primary_sourced: 4
claims_single_source: 1
claims_uncorroborated: 3
open_corrections: 0
sources_consulted:
  - https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878
  - https://pilp.nu/en/court-hearing-against-risk-profiling-of-dutch-citizens-by-syri/
  - https://privacyfirst.nl/en/articles/algorithm-syri-in-the-ban-after-ruling-court/
  - https://solv.nl/blog/procedure-tegen-de-nederlandse-staat-stop-met-risicoprofileringssysteem-syri/
  - https://bijvoorbaatverdacht.nl/fnv-sluit-zich-aan-rechtszaak-syri/
  - https://bijvoorbaatverdacht.nl/over/
  - https://www.bitsoffreedom.nl/pers/minister-sander-dekker-en-syri-winnen-big-brother-awards-2019/
  - https://algorithmwatch.org/en/syri-netherlands-algorithm/
  - https://www.hrw.org/news/2019/11/08/welfare-surveillance-trial-netherlands
  - https://iapp.org/news/a/digital-welfare-fraud-detection-and-the-dutch-syri-judgment
  - https://www.openglobalrights.org/landmark-judgment-from-netherlands-on-digital-welfare-states/
  - https://academic.oup.com/hrlr/article/22/2/ngac010/6568079
---

Pass-2 note: entity body unchanged since pass 1; the only entity change is the new `strategies:` edge (Claim 20). This pass re-fetched sources and resolved 7 of pass 1's 10 uncorroborated claims — the court's own judgment text became fetchable via the rechtspraak.nl open-data XML endpoint, and PILP's relocated site (pilp.nu; old pilpnjcm.nl domain now redirects off-org) restored the body's cited source.

## Claim 1: "In March 2018 a coalition of Dutch civil-society organisations launched simultaneous strategic litigation against the Dutch state and a public media campaign"

Source: https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878 ; https://bijvoorbaatverdacht.nl/over/
Source tier: primary
Source content: Judgment §1.1: "the summons of 27 March 2018 with exhibits". bijvoorbaatverdacht.nl/over/: "Begin 2018 startte een groep maatschappelijke organisaties een rechtszaak tegen de Nederlandse Staat … Rondom de rechtszaak wordt vanuit het Platform Bescherming Burgerrechten de campagne Bij Voorbaat Verdacht gevoerd."
Comparison: March 2018 filing confirmed by the court's own procedural record; the campaign running alongside the litigation confirmed by the campaign's own about-page.
Decision: corroborated

## Claim 2: "The litigation was led by Platform Bescherming Burgerrechten and coordinated through the Public Interest Litigation Project (PILP-NJCM)"

Source: https://pilp.nu/en/court-hearing-against-risk-profiling-of-dutch-citizens-by-syri/ ; https://privacyfirst.nl/en/articles/algorithm-syri-in-the-ban-after-ruling-court/
Source tier: primary
Source content: PILP: "The plaintiffs are represented by mr. A. Ekker (Ekker Advocatuur) and mr. D. Linders (SOLV Advocaten) and is coordinated by PILP." Privacy First: "The coalition … is coordinated by the NJCM's Public Interest Litigation Project (PILP)." Judgment claimant header lists Platform Bescherming Burgerrechten among the eisers.
Comparison: PILP coordination and Platform Bescherming Burgerrechten's lead role confirmed by the coordinating org's own page and a coalition member's account.
Decision: corroborated

## Claim 3: "Bits of Freedom — the Netherlands' principal digital-rights organisation"

Source: https://algorithmwatch.org/en/syri-netherlands-algorithm/ ; https://en.wikipedia.org/wiki/Bits_of_Freedom (pass-1 fetch)
Source tier: mainstream
Source content: AlgorithmWatch: "the Dutch digital rights organization Bits of Freedom." Wikipedia (pass-1 record): "a Dutch non-profit advocacy group focused on digital rights"; a "leading player."
Comparison: "Principal" is within paraphrase tolerance of "leading"; named-entity definitional fact.
Decision: corroborated

## Claim 4: "On 29 November 2019 … Bits of Freedom's jury awarded SyRI the Expert Prize at the 2019 Dutch Big Brother Awards"

Source: https://www.bitsoffreedom.nl/pers/minister-sander-dekker-en-syri-winnen-big-brother-awards-2019/ ; https://algorithmwatch.org/en/syri-netherlands-algorithm/
Source tier: primary
Source content: Bits of Freedom press release, dateline "29 november 2019": "Vrijdagavond 29 november" … "De Expertprijs ging naar het Systeem Risico Indicatie (SyRI)". AlgorithmWatch: "On 29 November 2019, SyRI won the Big Brother Award of the Dutch digital rights organization Bits of Freedom."
Comparison: Date, presenter, and Expertprijs designation all confirmed by the awarding organisation's own press release plus one independent canonical source. (A December-ceremony doubt raised by BoF's 11-Dec retrospective post was checked and ruled out — the ceremony was 29 November.)
Decision: corroborated

## Claim 5: "On 5 February 2020 the District Court of The Hague [ruled in case C-09-550982] (ECLI:NL:RBDHA:2020:1878) that the SyRI legislation … violated Article 8 of the European Convention on Human Rights and declared it to have no binding effect"

Source: https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878 ; https://algorithmwatch.org/en/syri-netherlands-algorithm/
Source tier: primary
Source content: The judgment itself (ECLI:NL:RBDHA:2020:1878, District Court of The Hague) is the fetched document. AlgorithmWatch: "On 5 February 2020" with "ECLI:NL:RBDHA:2020:1878."
Comparison: Date, court, ECLI, Article 8 finding, and no-binding-effect declaration confirmed against the court's own text plus independent coverage.
Decision: corroborated

## Claim 6: "In May 2020 the Ministry of Social Affairs and Employment announced it would not appeal, making the judgment final"

Source: https://bijvoorbaatverdacht.nl/over/ ; https://iapp.org/news/a/digital-welfare-fraud-detection-and-the-dutch-syri-judgment
Source tier: primary
Source content: bijvoorbaatverdacht.nl/over/: "In mei 2020 maakte het Ministerie van Sociale Zaken bekend niet in beroep te gaan tegen de uitspraak." IAPP: "Soon after the judgment, the Dutch government said it would not appeal the ruling."
Comparison: May 2020 non-appeal by the Ministry confirmed by the campaign's own record and an independent canonical source.
Decision: corroborated

## Claim 7: scalar:body — "SyRI (Systeem Risico Indicatie) was a legal instrument introduced by an amendment to the SUWI Act (Wet structuur uitvoeringsorganisatie werk en inkomen) that came into force in 2014"

Source: https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878
Source tier: primary
Source content: Judgment ¶4.1: "SyRI now has a legal basis in Section 65 SUWI Act viewed in conjunction with Section 64 SUWI Act and Chapter 5a SUWI Decree"; the SUWI Act was amended for this purpose "as of 1 January 2014." HRW independently confirms the year: "the system was authorized by Parliament as part of a package of welfare reforms enacted in 2014."
Comparison: The SUWI-Act-amendment attribution rests on the court's own text (pass 1 could not confirm it); the 2014 date is independently confirmed. The SUWI-specific attribution has one (primary) source.
Decision: primary-sourced

## Claim 8: "[17 broadly-defined categories] including identity, employment, movable and immovable property, education, retirement, business activity, income and assets, pensions, housing, and debt"

Source: https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878 ; https://www.openglobalrights.org/landmark-judgment-from-netherlands-on-digital-welfare-states/
Source tier: primary
Source content: Judgment ¶4.17 enumerates the 17 categories of Article 5a.1(3) SUWI Decree: "work data, administrative measures/sanctions, tax data, property data, benefit exclusion data, trade data, housing data, identifying data, civic integration data, compliance data, education data, pension data, reintegration data, debt burden data, social benefit/allowances data, permits/exemptions, and healthcare insurance data." OpenGlobalRights: "cooperating authorities to share up to 17 broadly defined categories of previously siloed data."
Comparison: The count 17 (unconfirmable in pass 1) is now confirmed by the court's enumeration plus a second canonical source; the body's "including" list maps onto the decree categories (identity≈identifying, employment≈work, property, education, pensions, business≈trade, housing, debt).
Decision: corroborated

## Claim 9: "the Dutch tax authority (Belastingdienst), the social security agency (UWV), the Social Insurance Bank (SVB), municipalities, the Inspectorate of Social Affairs and Employment (Inspectie SZW), and the immigration and naturalisation service (IND)"

Source: https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878
Source tier: primary
Source content: Judgment ¶3.3 lists the cooperating bodies: "Municipal Executives, UWV, SVB (Social Insurance Bank), Netherlands Tax and Customs Administration, IND (Immigration Service), and supervisory authorities including the Social Affairs & Employment Inspectorate."
Comparison: The body's agency list (unverifiable in pass 1) matches the court's enumeration one-for-one.
Decision: primary-sourced

## Claim 10: "[deployed not population-wide but geographically targeted] — applied to residents of designated neighbourhoods … Known deployment areas included two neighbourhoods in Rotterdam-Zuid … as well as designated areas in Eindhoven and Haarlem"

Source: https://www.hrw.org/news/2019/11/08/welfare-surveillance-trial-netherlands ; https://privacyfirst.nl/en/articles/algorithm-syri-in-the-ban-after-ruling-court/ (Rotterdam-Zuid detail per pass-1 fetch)
Source tier: primary
Source content: HRW: "Rotterdam, the Netherlands' second largest city, which has the highest poverty rate in the country, as well as Eindhoven and Haarlem"; "the government admitted that SyRI has been targeted at neighborhoods with higher numbers of residents on welfare, despite the lack of evidence that these neighborhoods are responsible for higher rates of benefits fraud." Privacy First (pass-1 record): "two neighborhoods in Rotterdam-Zuid."
Comparison: Geographic targeting and the three deployment cities confirmed; the two-neighbourhoods-in-Rotterdam-Zuid specific stands on the coalition member's account.
Decision: corroborated

## Claim 11: "The legal challenge was filed on [27 March 2018]"

Source: https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878
Source tier: primary
Source content: Judgment §1.1 procedural record: "the summons of 27 March 2018 with exhibits."
Comparison: The day-precise filing date (unconfirmable in pass 1) is confirmed by the court's own procedural record.
Decision: primary-sourced

## Claim 12: "FNV — the Netherlands' largest trade union — joined the coalition in July 2018"

Source: https://bijvoorbaatverdacht.nl/fnv-sluit-zich-aan-rechtszaak-syri/ ; https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878
Source tier: primary
Source content: bijvoorbaatverdacht.nl announcement dated "17 juli 2018": "Ook de grootste vakbond van Nederland voegt zich bij de juridische [strijd]." Judgment §2.5 records FNV as an intervening third party joining the claimants; Privacy First lists "trade union FNV" among the coalition.
Comparison: FNV's coalition membership is multiply confirmed; the July-2018 join date rests on the campaign's own dated announcement (one primary source). "Largest Dutch trade union" is stated in the same announcement.
Decision: primary-sourced

## Claim 13: "[lawyers A. Ekker of Ekker Advocatuur and D. Linders of SOLV Advocaten]"

Source: https://pilp.nu/en/court-hearing-against-risk-profiling-of-dutch-citizens-by-syri/ ; https://solv.nl/blog/procedure-tegen-de-nederlandse-staat-stop-met-risicoprofileringssysteem-syri/ ; https://privacyfirst.nl/en/articles/algorithm-syri-in-the-ban-after-ruling-court/
Source tier: primary
Source content: PILP: "The plaintiffs are represented by mr. A. Ekker (Ekker Advocatuur) and mr. D. Linders (SOLV Advocaten)." SOLV's own blog: "SOLV-partner Douwe Linders en zijn oud-kantoorgenoot Anton Ekker." Privacy First: "Anton Ekker (Ekker Advocatuur) and Douwe Linders (SOLV Advocaten)." Judgment names "mr. A.H. Ekker" as counsel of record.
Comparison: Both lawyers and both firms (unverifiable in pass 1 — the cited PILP page 403'd; it has since moved to pilp.nu and fetches) confirmed by three independent sources including the firm's own site.
Decision: corroborated

## Claim 14: "The court hearing in case C-09-550982 took place on [29 October 2019]"

Source: https://pilp.nu/en/court-hearing-against-risk-profiling-of-dutch-citizens-by-syri/ ; https://www.hrw.org/news/2019/11/08/welfare-surveillance-trial-netherlands
Source tier: primary
Source content: PILP: "On Tuesday, October 29, 2019 at 9:30 a.m. in the District Court of The Hague, the hearing against the Dutch State in the proceedings on the merits regarding the System Risk Indication (SyRI) will take place." HRW: "On 29 October, the District Court of the Hague held hearings on the legality of Systeem Risico Indicatie (SyRI)."
Comparison: Hearing date confirmed by the coordinating org's own notice and independent coverage.
Decision: corroborated

## Claim 15: "Philip Alston — United Nations Special Rapporteur on Extreme Poverty and Human Rights"

Source: https://www.ohchr.org/en/press-releases/2020/02/landmark-ruling-dutch-court-stops-government-attempts-spy-poor-un-expert (via search snippets; direct fetch 403) ; https://en.wikipedia.org/wiki/Philip_Alston (pass-1 fetch)
Source tier: primary
Source content: OHCHR press release: "the UN Special Rapporteur on extreme poverty and human rights, Philip Alston, applauded a landmark ruling by the District Court of the Hague." Wikipedia (pass-1 record): Special Rapporteur "from 2014-2020."
Comparison: Title confirmed by the UN's own press release; 2019 falls within tenure.
Decision: corroborated

## Claim 16: "[submitted a letter to the court on 26 September 2019]"

Source: no canonical source found for the date
Source tier: none
Source content: The amicus brief exists and is hosted by OHCHR (https://www.ohchr.org/Documents/Issues/Poverty/Amicusfinalversionsigned.pdf), but the PDF is image-compressed and unparseable via fetch, and the OHCHR press pages 403. OpenGlobalRights (co-author of the brief) refers to "the October 2019 amicus brief prepared by the UN Special Rapporteur and the project I direct at NYU" — a month inconsistent with the body's 26 September 2019. The Oxford HRLR article cites the brief without a submission date. The judgment text as extracted does not carry a dated procedural entry for the amicus.
Comparison: The brief's existence is well-attested; its specific date is not confirmed by any fetched source, and the one canonical source giving a month says October 2019 (possibly loosely covering Alston's 29 Oct 2019 reply to the government, also hosted by OHCHR). Judgment-loaded — cannot pick a winner.
Decision: uncorroborated

## Claim 17: "Alston's intervention placed SyRI explicitly inside the global discourse on the 'digital welfare state' … comparable systems existed in at least fifty other countries"

Source: no canonical source found for the "fifty" figure
Source tier: none
Source content: OHCHR press release (via search snippets): "Such tools are part of a global trend toward the introduction and expansion of digital technologies in welfare states"; "In October, Alston presented a groundbreaking report to the UN General Assembly about the emergence of the 'digital welfare state' in countries around the globe." OpenGlobalRights: "the Netherlands is not unique in this area." No fetched source states "at least fifty" countries.
Comparison: The digital-welfare-state framing is confirmed; the specific "at least fifty other countries" figure is not found in any fetched source (the amicus PDF itself is unparseable).
Decision: uncorroborated

## Claim 18: 'verbatim court quote — "the SyRI legislation in no way provides information on which objective factual data can justifiably lead to the conclusion that there is an increased risk"'

Source: https://iapp.org/news/a/digital-welfare-fraud-detection-and-the-dutch-syri-judgment
Source tier: mainstream
Source content: IAPP (by van Bekkum & Zuiderveen Borgesius): "the SyRI legislation in no way provides information on … which objective factual data can justifiably lead to the conclusion that there is an increased risk." The court's official English translation renders the finding at ¶6.87 as: "the SyRI legislation does not make clear on the basis of which objective factual data the conclusion of an increased risk is reached."
Comparison: The body's quote now matches its cited source's rendering verbatim (pass 1's extraction of the IAPP page was itself truncated, which manufactured an apparent mismatch — resolved this pass). The substance is confirmed by the judgment's official translation, but in different translation wording, so the quote-as-quoted rests on the single IAPP rendering; the body's elision of IAPP's internal ellipsis is a fidelity nuance, not a contradiction.
Decision: single-source

## Claim 19: scalar:outcomes — "the Netherlands' first and the corpus's first Article-8-ECHR welfare-algorithm ruling — and the earliest in the corpus to produce a court-ordered statutory invalidity on human rights grounds"

Source: https://www.ohchr.org/en/press-releases/2020/02/landmark-ruling-dutch-court-stops-government-attempts-spy-poor-un-expert (via search snippets)
Source tier: primary
Source content: OHCHR, quoting Alston: "This is one of the first times a court anywhere has stopped the use of digital technologies and abundant digital information by welfare authorities on human rights grounds."
Comparison: "One of the first times … anywhere" supports but does not establish the Netherlands-first sub-claim as stated; contested-"first" characterisations require more than framing consistency, and the corpus-first sub-claims are internal and not externally checkable.
Decision: uncorroborated

## Claim 20: edge — strategies: [strat-strategic-litigation-against-algorithmic-state-decisions]

Source: product/entities/strategies/strat-strategic-litigation-against-algorithmic-state-decisions.md ; https://data.rechtspraak.nl/uitspraken/content?id=ECLI:NL:RBDHA:2020:1878
Source tier: primary
Source content: The strategy entity's effects list opens with: "The Hague District Court declared the Dutch SyRI welfare-fraud risk-profiling system an unlawful violation of Article 8 … on 5 February 2020, in a coalition challenge" (type: judicial-outcome, attribution_confidence: high), and its verdict section names SyRI "the strongest of the four" adopter cases.
Comparison: New edge since pass 1 (Analyst wire, 2026-07-14). The edge points to the correct, existing entity; the campaign is strategic litigation against an algorithmic state decision on the corroborated facts above, and the strategy entity reciprocally names this case.
Decision: corroborated

## Claim 21: edge — participating_orgs: [org-bits-of-freedom]

Source: https://www.bitsoffreedom.nl/pers/minister-sander-dekker-en-syri-winnen-big-brother-awards-2019/ ; https://algorithmwatch.org/en/syri-netherlands-algorithm/
Source tier: primary
Source content: Bits of Freedom's own press release records its jury awarding SyRI the Expertprijs; AlgorithmWatch situates the award within the civil-society mobilisation against SyRI. The target entity file product/entities/organizations/org-bits-of-freedom.md exists.
Comparison: Edge points to the correct, existing entity; the body accurately scopes BoF's participation to the broader campaign (not a litigant), consistent with the judgment's claimant header, which does not list BoF.
Decision: corroborated
