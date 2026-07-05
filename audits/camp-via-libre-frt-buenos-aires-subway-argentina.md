---
entity_id: camp-via-libre-frt-buenos-aires-subway-argentina
entity_hash: c0f83a93c222acebc23e7e268c339d195020dc9b
audit_date: 2026-07-05
pass: 1
status: corrections-pending
claims_total: 37
claims_corroborated: 19
claims_primary_sourced: 6
claims_single_source: 5
claims_uncorroborated: 5
open_corrections: 2
sources_consulted:
  - https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system
  - https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/
  - https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/
  - https://www.vialibre.org.ar/en/justice-defines-whether-facial-recognition-returns-on-the-streets-of-buenos-aires-how-to-audit-the-artificial-surveillance/
  - https://www.vialibre.org.ar/en/we-participated-in-the-iachr-hearing-artificial-intelligence-and-human-rights/
  - https://www.biometricupdate.com/202403/buenos-aires-controversial-facial-recognition-network-remains-in-limbo
  - https://www.biometricupdate.com/202010/hrw-calls-for-public-biometric-surveillance-system-changes-in-russia-and-argentina
  - https://monitor.civicus.org/explore/buenos-aires-facial-recognition-suspended/
  - https://www.context.news/surveillance/reboot-of-buenos-aires-facial-recognition-plan-fuels-privacy-fears
  - https://ai-regulation.com/suspension-of-buenos-aires-facial-recognition-system/
  - https://ijudicial.gob.ar/2022/suspenden-el-sistema-de-reconocimiento-facial-de-profugos/
  - https://chequeado.com/el-explicador/porque-se-suspendio-el-sistema-de-reconocimiento-facial-de-la-ciudad-de-buenos-aires/
  - https://srfp.odia.legal/
  - https://amicus.odia.legal/
  - http://www2.cedom.gov.ar/es/legislacion/normas/leyes/ley6339.html
  - https://www.infobae.com/sociedad/policiales/2019/08/02/un-hombre-estuvo-seis-dias-preso-por-un-error-del-sistema-de-reconocimiento-facial/
  - https://adc.org.ar/2019/05/23/con-mi-cara-no-reconocimiento-facial-en-la-ciudad-de-buenos-aires/
  - https://reconoceme.org/contexto/
  - https://www.oas.org/en/iachr/jsForm/?File=/en/iachr/media_center/preleases/2025/039.asp
---

## Claim 1: edge — `lead_orgs`/`participating_orgs: org-fundacion-via-libre` (Vía Libre anchors the campaign)

Source: https://www.vialibre.org.ar/en/justice-defines-whether-facial-recognition-returns-on-the-streets-of-buenos-aires-how-to-audit-the-artificial-surveillance/ ; https://srfp.odia.legal/
Source tier: primary
Source content: Vía Libre "joined as amicus curiae (friend of the court), presenting arguments supporting ODIA and CELS's legal action"; ODIA's own amici list includes "Fundación Vía Libre"; Biometric Update identifies Busaniche (Vía Libre president) as the audit-standoff voice.
Comparison: Edge resolves to existing entity; Vía Libre's amicus role and audit-phase leadership confirmed by its own publications and ODIA's case page. Note the formal plaintiff is ODIA (not in corpus) — the entity body states this accurately.
Decision: corroborated

## Claim 2: edges — body cross-references and `strategies` resolve (org-human-rights-watch, person-beatriz-busaniche, camp-derechos-digitales-iachr-ai-hearing-2025, org-coding-rights, org-internet-freedom-foundation, org-edri, camp-edri-reclaim-your-face-eu-citizens-initiative-2020-2022, strat-local-rapid-response-against-single-deployment, strat-strategic-litigation-against-algorithmic-state-decisions)

Source: corpus entity files (mechanical existence check, this session)
Source tier: primary
Source content: All 10 referenced entity files exist under `product/entities/`.
Comparison: Every edge target resolves; each is used in body context consistent with its referent (HRW as letter author, Busaniche as Vía Libre president, IACHR-2025 campaign as coalition continuity).
Decision: primary-sourced

## Claim 3: scalar:name — "(2019–ongoing)"

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system ; https://adc.org.ar/2019/05/23/con-mi-cara-no-reconocimiento-facial-en-la-ciudad-de-buenos-aires/
Source tier: primary
Source content: SRFP "Launched April 24, 2019"; the coalition challenge narrated in the body opens with HRW's 9 October 2020 letter; ADC ran a separate 2019 action (#ConMiCaraNo / declarative constitutional challenge) outside the ODIA amparo.
Comparison: The name's "2019" conflicts internally with `start_date: 2020-10` and with the body's own timeline (first campaign act October 2020). "2019" is defensible only as the system-deployment era or via ADC's separate 2019 action, which the body does not narrate as part of this campaign. Ambiguous referent — cannot be compared to source as stated.
Decision: uncorroborated

## Claim 4: scalar:start_date — "2020-10"

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system
Source tier: primary
Source content: HRW letter dated "October 9, 2020" demanding immediate suspension — the first campaign act the entity narrates.
Comparison: Campaign start month matches the first documented advocacy act on the entity's own account.
Decision: primary-sourced

## Claim 5: "In April 2019 the City of Buenos Aires launched the SRFP, a network of approximately 300 cameras installed in the Buenos Aires subway and cross-referenced ... against the CONARC (Consulta Nacional de Rebeldías y Capturas) national fugitive database"

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system ; https://www.biometricupdate.com/202403/buenos-aires-controversial-facial-recognition-network-remains-in-limbo
Source tier: primary
Source content: HRW: "Launched April 24, 2019; initially deployed on 300 simultaneous CCTV cameras; operated in Buenos Aires subway stations." Biometric Update: "300 cameras in the system"; CONARC "run by federal Ministry of Justice." Ley 6339 text (cedom): searches restricted to persons "registered in the National Database of Rebelliousness and Captures (CONARC)."
Comparison: Launch date, camera count, subway placement, and CONARC cross-reference all match across a primary and two secondary sources.
Decision: corroborated

## Claim 6: "facial recognition software supplied by local company Danaide S.A. and built on technology developed by Russia-based NtechLab"

Source: https://www.biometricupdate.com/202010/hrw-calls-for-public-biometric-surveillance-system-changes-in-russia-and-argentina ; https://www.biometricupdate.com/202403/buenos-aires-controversial-facial-recognition-network-remains-in-limbo
Source tier: mainstream
Source content: "The facial recognition component was developed by Russian company NtechLab and was contracted to Buenos Aires-based company Danaide S.A."; "Danaide S.A. installed the system in 2019; NtechLab reportedly supplied the facial recognition technology."
Comparison: Vendor pair and NtechLab's Russian origin confirmed by two independent reports (2020 and 2024).
Decision: corroborated

## Claim 7: "The NtechLab engine ... was chosen by Danaide S.A. through a private tender process that did not follow the transparency requirements ordinarily applicable to public procurement"

Source: https://www.biometricupdate.com/202010/hrw-calls-for-public-biometric-surveillance-system-changes-in-russia-and-argentina ; https://ai-regulation.com/suspension-of-buenos-aires-facial-recognition-system/
Source tier: mainstream
Source content: "Danaide won the contract just six minutes after it was tendered. This was a direct procurement rather than a competitive tender process." ODIA's grounds cited "private tender procurement without transparency."
Comparison: Sources describe the *city's* opaque tender to Danaide; the body instead describes Danaide choosing the NtechLab engine "through a private tender," conflating the city→Danaide procurement with Danaide's technology-partner choice. Too paraphrastically garbled to match either reading cleanly; the transparency-deficit substance is real but the actor/object of the tender is misassembled.
Decision: uncorroborated

## Claim 8: "authorised the system through Resolution 398 and subsequently incorporated it into local public security law via Law 6.339, passed in October 2020 — ... a system already operational since 2019"

Source: https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/ ; http://www2.cedom.gov.ar/es/legislacion/normas/leyes/ley6339.html
Source tier: primary
Source content: FPF: amparo challenged the city "for i) issuing Resolution 398, which created the SRFP; ii) approving Law 6.339, which incorporated the SRFP into the local public security law (Law 5.688)." Legislative record: "Ley 6339 was sanctioned on October 22, 2020 ... This law reformed Ley 5688 of Public Safety." System operational since April 2019 (HRW).
Comparison: Resolution number, law number, October 2020 passage, incorporation into Law 5.688, and the retroactive sequence (2019 deployment → 2020 statute) all match.
Decision: corroborated

## Claim 9: "Neither Resolution 398 nor Law 6.339 required a data-protection impact assessment before the SRFP began operation"

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system ; https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/
Source tier: primary
Source content: HRW demanded a "privacy and human rights impact assessment" the city had not conducted; FPF: the 2022 ruling made a "data protection impact assessment on the system" a condition of any reinstatement — i.e., none existed.
Comparison: The absence of a pre-deployment DPIA is affirmed by both the 2020 demand and the 2022 judicial condition.
Decision: corroborated

## Claim 10: "the city government refused freedom of information requests for procurement documents, classifying them as confidential"

Source: https://reconoceme.org/contexto/ (search-confirmed; with MPD repository paper)
Source tier: caution
Source content: "After the city's second round of information requests, not all questions were answered, citing exceptions under articles 6 (sections b and e) of Law 104 and article 32 of Law 5688 ... particularly refusing to provide a detailed explanation of how the facial recognition algorithm functions or release the software's source code"; a Danaide developer testified system information was contractually "confidential."
Comparison: FOI refusals on confidentiality grounds are confirmed in substance, though sources specify refusals over algorithm/source-code detail rather than "procurement documents" narrowly, and the confirming pages are coalition-run/advocacy-adjacent. Note: the body's inline citation for this claim (CIVICUS Monitor) does not contain it — the CIVICUS entry carries no FOI or procurement-confidentiality material.
Decision: single-source

## Claim 11: "HRW wrote to Mayor Rodríguez Larreta on 9 October 2020 demanding the SRFP's immediate suspension" and a privacy and human-rights impact assessment

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system ; https://www.biometricupdate.com/202010/hrw-calls-for-public-biometric-surveillance-system-changes-in-russia-and-argentina
Source tier: primary
Source content: Letter dated October 9, 2020; demands: "Immediate suspension of the SRFP; privacy and human rights impact assessment; publication of verifiable system performance statistics; removal of all children under 18 from the public CONARC database."
Comparison: Date, addressee, and both demands the body names match the letter; secondary coverage confirms.
Decision: corroborated

## Claim 12: "at least 166 minors had been listed in CONARC between May 2017 and 2020"

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system
Source tier: primary
Source content: "At least 166 minors listed between May 2017 and May 2020."
Comparison: Count and range match (body's "2020" endpoint slightly less precise than the letter's "May 2020" — not a contradiction).
Decision: primary-sourced

## Claim 13: "NtechLab's algorithms had shown six-times higher false-match rates for children aged 10–16 compared to adults aged 24–40"

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system
Source tier: primary
Source content: "Children aged 10-16 falsely identified approximately 'six times more often than an adult aged 24 to 40.'"
Comparison: Multiplier and both age bands match HRW's calculation from NIST testing data.
Decision: primary-sourced

## Claim 14: "the system had been tested only on police employee faces with no bias-minimisation checks for any demographic group"

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system
Source tier: primary
Source content: "Only tested on the adult faces of employees from the city's police department and the Justice and Security Ministry" prior to deployment; no bias-minimization testing requested.
Comparison: The body's "only on police employee faces" contradicts the source's tested population, which also includes Justice and Security Ministry employees; the word "only" makes the narrower set factually wrong. Single replacement: "tested only on the adult faces of city police department and Justice and Security Ministry employees." The no-bias-testing half of the sentence is confirmed. Fix location: body, § HRW's October 2020 letter (same wording echoed in `goals`-adjacent prose is not present; single body occurrence).
Decision: correction

## Claim 15: "HRW argued this violated the Convention on the Rights of the Child ... and the UN Standard Minimum Rules for the Administration of Juvenile Justice (the Beijing Rules)"

Source: https://www.hrw.org/news/2020/10/09/letter-buenos-aires-mayor-horacio-rodriguez-larreta-re-facial-recognition-system
Source tier: primary
Source content: Instruments cited: "Convention on the Rights of the Child; UN Standard Minimum Rules for the Administration of Juvenile Justice ('Beijing Rules')."
Comparison: Both instruments match the letter.
Decision: primary-sourced

## Claim 16: "In December 2020 ODIA filed an amparo — the constitutional-protection action provided by Article 43 of Argentina's Constitution — ... challenging Resolution 398, Law 6.339, and the system's implementation" with Convention 108 and laws 5688/6339 among the grounds

Source: https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/ ; https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/
Source tier: mainstream
Source content: FPF: ODIA filed December 2020; "The amparo is recognized as a right in Article 43 of the Argentinian Constitution"; challenged "i) issuing Resolution 398 ... ii) approving Law 6.339, which incorporated the SRFP into the local public security law (Law 5.688); and iii) implementing the system without adequate mechanisms"; cites "the Convention for the Protection of Individuals with regard to Automatic Processing of Personal Data (Convention 108)." CELS: ODIA "initiated the amparo action in 2020"; case number 182908/2020.
Comparison: Filing date, Article 43 mechanism, challenged instruments, and Convention 108 reference all match. ODIA's own case page shows an initial in-limine rejection with a 2021 expanded claim — procedural arc, not a contradiction of the December 2020 filing (case number is /2020).
Decision: corroborated

## Claim 17: "Fundación Vía Libre joined the case as amicus curiae, submitting technical AI-systems analysis and human-rights arguments"

Source: https://srfp.odia.legal/ ; https://www.vialibre.org.ar/en/justice-defines-whether-facial-recognition-returns-on-the-streets-of-buenos-aires-how-to-audit-the-artificial-surveillance/
Source tier: primary
Source content: ODIA's amici list includes "Fundación Vía Libre"; Vía Libre's own article: "Joined as amicus curiae (friend of the court), presenting arguments supporting ODIA and CELS's legal action."
Comparison: Amicus role confirmed by both the plaintiff's case page and Vía Libre's own account.
Decision: corroborated

## Claim 18: CELS participated in the amparo (contributing human-rights litigation architecture)

Source: https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/ ; https://srfp.odia.legal/
Source tier: primary
Source content: "CELS participated in the collective process"; CELS appears on ODIA's amici list.
Comparison: Participation confirmed by CELS's own announcement and ODIA's case page. (The body's characterization of CELS's amparo experience is interpretive gloss, not audited.)
Decision: corroborated

## Claim 19: "the Asociación por los Derechos Civiles (ADC) also participated" / Vía Libre joined "alongside ... the Asociación por los Derechos Civiles (ADC)"

Source: https://srfp.odia.legal/ ; https://adc.org.ar/2019/05/23/con-mi-cara-no-reconocimiento-facial-en-la-ciudad-de-buenos-aires/
Source tier: primary
Source content: ODIA's case page lists amici as "Fundación Vía Libre, CELS, Access Now, Derechos Digitales, CORREPI, ATE, Cybercirujas, Gaspar Pisanu, Legaltech Seed, RLAB" — ADC absent. Search record: "In 2019, the Asociación por los Derechos Civiles (ADC) presented a separate action of constitutional challenge against the facial recognition system."
Comparison: No fetched source places ADC inside the ODIA amparo (FPF, CELS, and Vía Libre accounts also never name it); ADC's documented role is a separate 2019 constitutional challenge and the #ConMiCaraNo campaign. ODIA's enumeration may be partial, so this is recorded as unsupported rather than asserted error — but both body occurrences (intro and § The ODIA amparo) need a source or removal; a re-audit or Researcher pass should resolve whether ADC belongs in this campaign's amparo narrative at all.
Decision: uncorroborated

## Claim 20: "Judge Andrés Gallardo ordered inspections of the Urban Monitoring Centre and the Ministry of Security"

Source: https://ijudicial.gob.ar/2022/suspenden-el-sistema-de-reconocimiento-facial-de-profugos/ ; https://ai-regulation.com/suspension-of-buenos-aires-facial-recognition-system/
Source tier: primary
Source content: iJudicial (city judiciary's own outlet): judge named "Andrés Gallardo, presiding over Court No. 2 of the Administrative, Tax, and Consumer Relations jurisdiction"; order "mandated a comprehensive forensic investigation of computer systems." MIAI: "the judge ordered raids on the Urban Monitoring Centre and the headquarters of the Buenos Aires Ministry of Security."
Comparison: Judge name matches the official judiciary source (Chequeado uses "Roberto Gallardo" — the judge's full name is Roberto Andrés Gallardo, so the variants are consistent, not conflicting); both inspection locations confirmed.
Decision: corroborated

## Claim 21: "The legal challenge produced a suspension order in April 2022"

Source: https://monitor.civicus.org/explore/buenos-aires-facial-recognition-suspended/ ; https://ijudicial.gob.ar/2022/suspenden-el-sistema-de-reconocimiento-facial-de-profugos/
Source tier: primary
Source content: CIVICUS: suspension order dated "April 12, 2022"; iJudicial announcement of the suspension published April 12, 2022; Context: system "remains suspended" since the 2022 order.
Comparison: Month and year match across official, monitoring, and press sources.
Decision: corroborated

## Claim 22: "more than nine million biometric queries against a CONARC database of only around 35,000 to 40,000 active fugitive entries"

Source: https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/ ; https://chequeado.com/el-explicador/porque-se-suspendio-el-sistema-de-reconocimiento-facial-de-la-ciudad-de-buenos-aires/
Source tier: mainstream
Source content: FPF: "9,392,372 requests to access biometric data" against "up to 35,000 active fugitive registries." Chequeado: "more than 9 million consultas" vs CONARC "between 35 thousand and 40 thousand registros."
Comparison: Query count and database range match both sources (CELS/MIAI's "about 10 million" is a rounding of the same expert-report figure; "more than nine million" is consistent with all).
Decision: corroborated

## Claim 23: "The biometric data of approximately 7.5 million Buenos Aires residents had been accessed without warrant"

Source: https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/ ; https://ai-regulation.com/suspension-of-buenos-aires-facial-recognition-system/
Source tier: primary
Source content: CELS: "approximately 10 million queries were conducted on 7.5 million people." MIAI: "in relation to a total of 7.5 million of the city's inhabitants between April 2019 and March 2022." CIVICUS: "7 million people" without search warrant.
Comparison: 7.5 million matches the expert-report figure in CELS and MIAI; CIVICUS's ~7 million is a looser rounding, not a conflict. (Note: the body's inline citation for this figure points at CIVICUS, whose number is 7 million — the figure itself is right per the stronger sources.)
Decision: corroborated

## Claim 24: "Seventeen anonymous administrative accounts were found to have unrestricted access to RENAPER ... data"

Source: https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/
Source tier: database
Source content: "Seventeen unidentifiable 'admin' users had unrestricted access" with ability to manipulate/erase data without accountability.
Comparison: Count and access description match; no second independent source fetched carries the specific count.
Decision: single-source

## Claim 25: "Three hundred and fifty-six search records had been manually erased"

Source: https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/ (search-confirmed passage)
Source tier: database
Source content: "The court determined that at least 356 search records for individuals whose biometric data was incorporated into the SFRP ... were manually erased, making it impossible to assess whether those searches were legally justified."
Comparison: Count matches (source says "at least 356"; body states the count flatly — consistent).
Decision: single-source

## Claim 26: those surveilled without warrant included "journalists, politicians across party lines, human rights leaders including Estela de Carlotto (president of the Abuelas de Plaza de Mayo), and members of Argentina's Supreme Court"

Source: https://www.vialibre.org.ar/en/justice-defines-whether-facial-recognition-returns-on-the-streets-of-buenos-aires-how-to-audit-the-artificial-surveillance/ ; https://monitor.civicus.org/explore/buenos-aires-facial-recognition-suspended/
Source tier: primary
Source content: Vía Libre names journalists (Sylvestre, Feinmann), politicians across the spectrum (Fernández de Kirchner, Alberto Fernández, Espert, Morales, Milei), "Activists: Estela de Carlotto," and "Supreme Court justices: Carlos Rosenkrantz." CIVICUS: "Estela Carlotto, leader of Abuelas de Plaza de Mayo, was among those affected."
Comparison: Every category the body names is instantiated in the sources, including cross-party politicians and a Supreme Court justice; Carlotto's Abuelas role confirmed.
Decision: corroborated

## Claim 27: Guillermo Ibarrola, "a factory worker ... arrested in Buenos Aires and held for nearly a week in Bahía Blanca — a city almost 400 miles away — before authorities discovered that a data-entry error had caused his national ID number to be registered in CONARC under the name of a wanted fugitive who shared his surname"

Source: https://www.context.news/surveillance/reboot-of-buenos-aires-facial-recognition-plan-fuels-privacy-fears ; https://www.infobae.com/sociedad/policiales/2019/08/02/un-hombre-estuvo-seis-dias-preso-por-un-error-del-sistema-de-reconocimiento-facial/
Source tier: mainstream
Source content: Context: "Ibarrola, who was 39 at the time and worked in a chicken processing factory, was whisked away to Bahia Blanca" — ~400 miles/650 km — "held in custody for nearly a week"; a data-entry error put his ID in place of the actual fugitive's. Infobae/Página12: detained six days after arrest at Retiro; the wanted man was Guillermo Walter Ibarrola (same surname, different DNI).
Comparison: Occupation, arrest location, transfer to and detention in Bahía Blanca, ~week duration, ~400-mile distance, and the DNI data-entry error under a same-surname fugitive all match.
Decision: corroborated

## Claim 28: "On 7 September 2022 City Administrative Judge Elena Liberatori declared the SRFP's implementation unconstitutional," finding deployment without due protection of rights, contrary to the presumption of innocence, and without the Special Committee, Registry, and impact assessment required by laws 5688 and 6339

Source: https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/ ; https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/
Source tier: primary
Source content: FPF: September 7, 2022 ruling declaring the SRFP unconstitutional; missing oversight bodies under Laws 5.688/6.339. CELS: "Judge Elena Liberatori's September 2022 ruling declaring the SRFP ... implementation unconstitutional."
Comparison: Date, judge, holding, and the missing-oversight grounds match; the presumption-of-innocence reasoning matches the query-ratio finding both sources carry.
Decision: corroborated

## Claim 29: "The ruling specified four conditions for any reinstatement: establishment of a functional Special Committee; a proper surveillance Registry ...; a full data-protection impact assessment; and a public consultation process"

Source: https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/ ; https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/
Source tier: mainstream
Source content: FPF verbatim: "i) the Special Committee for the Monitoring of Video Surveillance Systems be established and that the Public Defender must be able to effectively exercise its oversight obligations; ii) the Registry of the surveillance systems be created; iii) a data protection impact assessment on the system be performed, and iv) the public must be consulted regarding the implementation of the SRFP."
Comparison: Exactly four conditions; each of the body's four matches one of FPF's enumerated items.
Decision: corroborated

## Claim 30: "On 28 April 2023 the Court of Appeals of the City of Buenos Aires, Chamber I, confirmed the unconstitutionality ruling ..., rejecting appeals submitted by the City Government and the Public Prosecutor's Office," adding a requirement to investigate "differentiated impact depending on personal features"

Source: https://www.cels.org.ar/web/en/2023/04/the-court-of-appeals-of-the-city-of-buenos-aires-confirmed-the-unconstitutionality-of-the-use-of-the-fugitive-facial-recognition-system-srfp-implemented-by-the-buenos-aires-city-government/
Source tier: primary
Source content: "April 28, 2023, Chamber I of the Court of Appeals of Buenos Aires ... The City Government and the Public Prosecutor's Office both had their appeals rejected"; conditions include investigations into whether the system produces "differentiated impact depending on the personal features of the affected individuals."
Comparison: Date, chamber, both rejected appellants, and the added demographic-impact condition (which the body quotes) all match the litigant coalition's announcement — a party-primary source for its own case outcome.
Decision: primary-sourced

## Claim 31: "In February 2024 the court found the parties deadlocked" — city proposing operational testing without independent access ("black box"), coalition demanding a full independent audit; city holding public seminars; "the system remained suspended with no reactivation date"

Source: https://www.vialibre.org.ar/en/justice-defines-whether-facial-recognition-returns-on-the-streets-of-buenos-aires-how-to-audit-the-artificial-surveillance/ ; https://www.biometricupdate.com/202403/buenos-aires-controversial-facial-recognition-network-remains-in-limbo ; https://www.context.news/surveillance/reboot-of-buenos-aires-facial-recognition-plan-fuels-privacy-fears
Source tier: primary
Source content: Vía Libre: February 21, 2024 execution hearing; coalition demands "an appropriate control system ... so that we can know how the system works, with what datasets it was trained, its architecture." Biometric Update: "the Buenos Aires Ministry of Security attempted to activate the system and audit it in operation"; "Suspended as of February 2024. No reactivation date defined." Context: "A court ruled in February 2024 that city government and rights groups must reach an agreement on system auditing"; "City authorities are holding seminars to inform the public about the SRFP as part of the reintroduction process."
Comparison: Deadlock timing, the city's audit-in-operation proposal vs the coalition's access demand, the seminars, and the open-ended suspension all match. The body's quoted term "black box" is editorial shorthand — no fetched source uses that phrase — but the substance it labels (testing without access to architecture/training data) is directly sourced.
Decision: corroborated

## Claim 32: Busaniche quote — "facial recognition is still too unreliable to be deployed freely"

Source: https://www.context.news/surveillance/reboot-of-buenos-aires-facial-recognition-plan-fuels-privacy-fears
Source tier: mainstream
Source content: "Busaniche stated: 'Facial recognition is still too unreliable to be deployed freely.'"
Comparison: Quote confirmed verbatim in the Context/Thomson Reuters Foundation piece. The body's inline citation for the surrounding sentence points at the Vía Libre audit article, which does not contain this quote (see Claim 35); attribution to Busaniche is nonetheless accurate. Living-person quoted statement on one mainstream source.
Decision: single-source

## Claim 33: Busaniche framing — "who does the audit and how" as the unresolved question

Source: https://www.biometricupdate.com/202403/buenos-aires-controversial-facial-recognition-network-remains-in-limbo
Source tier: mainstream
Source content: "Busaniche (Vía Libre Foundation President) stated: 'The big problem is who does the audit and how.'"
Comparison: The quoted fragment matches; the Vía Libre article carries her adjacent audit-quality warnings ("An audit that audits nothing") consistent with the body's framing sentence.
Decision: single-source

## Claim 34: "The coalition subsequently appeared together at the March 2025 Inter-American Commission on Human Rights hearing on AI and human rights"

Source: https://www.vialibre.org.ar/en/we-participated-in-the-iachr-hearing-artificial-intelligence-and-human-rights/ ; https://www.oas.org/en/iachr/jsForm/?File=/en/iachr/media_center/preleases/2025/039.asp
Source tier: primary
Source content: Vía Libre's participant list for the March 7, 2025 hearing includes "Centre for Legal and Social Studies (CELS), ... Fundación Vía Libre, ... Observatorio de Derecho Informático Argentino (ODIA)"; OAS lists the 192nd-session hearing schedule (March 3–7, 2025).
Comparison: All three coalition organizations appear on the hearing's participant roster; date matches.
Decision: corroborated

## Claim 35: scalar:sources[0].note — the Vía Libre audit article as "primary source for ... Busaniche's framing that 'facial recognition is still too unreliable to be deployed freely'"

Source: https://www.vialibre.org.ar/en/justice-defines-whether-facial-recognition-returns-on-the-streets-of-buenos-aires-how-to-audit-the-artificial-surveillance/
Source tier: primary
Source content: Targeted quote extraction against the article: "no direct quotes from Beatriz Busaniche stating that facial recognition is 'unreliable' or 'too unreliable to be deployed'" — her quotes there concern audit adequacy ("You can opt for a ... light, decorative, harmless audit ... An audit that audits nothing").
Comparison: The scalar attributes to this source a quote it does not contain; the quote's actual source is the Context/TRF article (Claim 32). Fix location: `sources[0].note` — remove or reattribute the "too unreliable" clause (the note's other content — amicus role, surveilled-figures scope, audit-impasse framing, "who does the audit and how" adjacency — is accurate). Reattribution wording is prose judgment; Editor may flag to Researcher.
Decision: correction

## Claim 36: scalar:sources[4].note — Biometric Update (March 2024) as source for "UltraIP software" and "the government's public seminars as part of a reintroduction preparation process"

Source: https://www.biometricupdate.com/202403/buenos-aires-controversial-facial-recognition-network-remains-in-limbo
Source tier: mainstream
Source content: Fetch of the article (asked directly about both tokens): no mention of UltraIP software and "no mention of government-held public seminars in this article." The article does carry Danaide/NtechLab, ~300 cameras, ~40,000 CONARC entries, the 1,700-fugitives credit claim, and Busaniche's audit position — all as the note states.
Comparison: Two of the note's attributed items (UltraIP; seminars) are not in the cited article — the seminars claim traces to Context/TRF instead, and UltraIP was not found in any source fetched this session. Recorded as unsupported rather than error because a fetch-extraction miss on a long page can't be fully excluded; the note's remaining items verify.
Decision: uncorroborated

## Claim 37: scalar:outcomes — the 7 September 2022 ruling conditioned "any reinstatement ... on a full system audit, establishment of oversight bodies, a privacy impact assessment, and public consultation"

Source: https://fpf.org/blog/judge-declares-buenos-aires-fugitive-facial-recognition-system-unconstitutional/ ; https://www.vialibre.org.ar/en/justice-defines-whether-facial-recognition-returns-on-the-streets-of-buenos-aires-how-to-audit-the-artificial-surveillance/
Source tier: mainstream
Source content: FPF's verbatim September 2022 enumeration is Special Committee (+ Public Defender oversight), surveillance Registry, DPIA, public consultation — no audit item. Vía Libre's 2024 summary of the court-mandated regime: "submit the system to an independent audit, establish control mechanisms per existing regulations, and conduct a privacy impact assessment."
Comparison: The scalar's condition list (naming a "full system audit" among the September 2022 conditions, omitting the Registry) matches neither FPF's verbatim 2022 enumeration nor the body's own correct four-condition list (Claim 29); the audit requirement is attested for the ruling's execution phase (2024), not the original enumeration. Canonical summaries conflict across phases — enumeration conflation, no single-token replacement. Fix location if the team acts: `outcomes` scalar, the "7 September 2022" sentence.
Decision: uncorroborated
