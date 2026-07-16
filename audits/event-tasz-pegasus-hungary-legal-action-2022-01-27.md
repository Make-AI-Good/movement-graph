---
entity_id: event-tasz-pegasus-hungary-legal-action-2022-01-27
entity_hash: a71bd7ea1a307238fbc2403160975f1a6b6f41ce
audit_date: 2026-07-15
pass: 1
status: corrections-pending
claims_total: 36
claims_corroborated: 14
claims_primary_sourced: 11
claims_single_source: 4
claims_uncorroborated: 4
open_corrections: 3
sources_consulted:
  - https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
  - https://tasz.hu/en/cikkek/the-hungarian-government-does-everything-to-cover-up-the-pegasus-affair-the-hclus-takeaways-from-the-first-year-of-the-scandal/
  - https://www.mediadefence.org/news/partner-hclu-spyware/
  - https://forbiddenstories.org/about-the-pegasus-project/
  - https://www.direkt36.hu/en/igy-hullottak-az-igazsag-morzsai-a-pegasus-ugy-ket-eve-alatt/
  - https://www.mfrr.eu/spying-scandal-further-increases-worries-of-hungarian-journalists/
  - https://bbj.hu/politics/domestic/government/kosa-admits-to-hungary-using-nso-groups-pegasus-spyware/
  - https://www.rferl.org/a/hungary-admits-pegasus-spyware/31546293.html
  - https://ifex.org/poland-hclu-and-other-groups-intervene-in-pegasus-case-before-ecthr/
  - https://tasz.hu/wp-content/uploads/2025/03/Brejza-v.-Lengyelorszag-beavatkozas.pdf
  - https://telex.hu/belfold/2021/07/19/ceu-pegasus-beauduin-lehallgatas-diak
  - https://vsquare.org/what-happend-in-hungary-after-the-pegasus-revelations/
  - https://en.wikipedia.org/wiki/Pegasus_Project_(investigation)
  - https://dailynewshungary.com/hungarian-prosecutors-drops-probe-into-pegasus-spyware/
  - https://abouthungary.hu/news-in-brief/investigative-prosecutor-drops-probe-into-pegasus-spyware-citing-absence-of-a-crime
  - https://epthinktank.eu/2024/06/02/what-action-has-parliament-taken-against-spyware-abuse/
  - https://eucrim.eu/news/ep-recommendation-on-lessons-learned-from-misused-spyware/
  - https://londondaily.com/pegasus-scandal-in-hungary-journalists-sue-state-over-spyware-dw-29-01-2022
  - https://www.szabadeuropa.hu/a/pegasus-botrany-eltelt-egy-ev-de-mintha-semmi-sem-tortent-volna/31952134.html
  - https://ipi.media/hungary-pegasus-scandal-i-was-absolutely-shocked-to-see-the-scale-of-this-surveillance/
  - https://hungarytoday.hu/civil-liberties-union-tasz-proceeding-orban-fidesz-surveillance-nso-pegasus/
  - https://www.pbs.org/newshour/world/amnesty-international-verifies-polish-senator-was-hacked-with-pegasus-spyware
---

## Claim 1: scalar:date "2022-01-27" + body "On Thursday 27 January 2022"

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: TASZ's own announcement page, dated 27 January 2022, announcing the coordinated legal action on behalf of the six clients.
Comparison: The primary artifact bears the 27 January 2022 date; 27 Jan 2022 was a Thursday. Note DW (via londondaily mirror) says "On January 28, the HCLU made an initial public announcement" — see Claim 2; the date of the announcement text itself is confirmed by the primary source.
Decision: primary-sourced

## Claim 2: "held a press conference in Budapest" (body, on 27 January 2022)

Source: https://londondaily.com/pegasus-scandal-in-hungary-journalists-sue-state-over-spyware-dw-29-01-2022
Source tier: mainstream
Source content: "On January 28, the HCLU made an initial public announcement to this effect in Budapest, and activated a dedicated page on its website."
Comparison: The cited TASZ announcement names no press conference and no location. The best mainstream source (DW) places the Budapest public announcement on 28 January, not 27. No source found confirms a press conference on 27 January; sources diverge on the announcement-event day.
Decision: uncorroborated

## Claim 3: scalar:location "Budapest, Hungary"

Source: https://londondaily.com/pegasus-scandal-in-hungary-journalists-sue-state-over-spyware-dw-29-01-2022
Source tier: mainstream
Source content: "the HCLU made an initial public announcement to this effect in Budapest"
Comparison: One mainstream source (DW) confirms Budapest as the announcement location; the entity's own cited sources do not state a location. Scalar path: location.
Decision: single-source

## Claim 4: "six named clients — four investigative journalists, a Belgian student activist, and one anonymous individual" (+ the four names, scalar:sources[0].note)

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: "On behalf of journalists Brigitta Csikász, Dávid Dercsényi, Dániel Németh and Szabolcs Panyi, as well as student activist Adrien Beauduin and a sixth person who requested anonymity, the organisation is first pursuing the legal remedies offered by the National Security Act."
Comparison: Names and composition match exactly; corroborated by DW and hungarytoday coverage. Minor: Dániel Németh is a photojournalist (Media Defence: "photographer documenting officials' activities"), so "four investigative journalists" is loose for him but within the sources' collective "journalists" usage.
Decision: corroborated

## Claim 5: "Brigitta Csikász, Dávid Dercsényi, Dániel Németh, and Szabolcs Panyi, all journalists at Direkt36" (body § Clients and legal team)

Source: https://www.mfrr.eu/spying-scandal-further-increases-worries-of-hungarian-journalists/
Source tier: mainstream
Source content: "Szabolcs Panyi and András Szabó from investigative center Direkt36; Brigitta Csikász, who was working with investigative website Átlátszó at the time of her surveillance; and former hvg.hu journalist Dávid Dercsényi." Media Defence separately describes Németh as a "photographer documenting officials' activities" with no Direkt36 affiliation.
Comparison: Only Panyi is a Direkt36 journalist. Csikász was at Átlátszó at the time of surveillance, Dercsényi formerly at hvg.hu, Németh a freelance photojournalist. "all journalists at Direkt36" contradicts the sources; correct statement drops the shared Direkt36 affiliation (prose-judgment fix — affects this body sentence only; the § Context sentence "Szabolcs Panyi and fellow journalists at Direkt36" is separately fine, see Claim 18).
Decision: correction

## Claim 6: proceedings-track list — Hungarian courts, NAIH, Parliamentary National Security Committee, Commissioner for Fundamental Rights, European Commission, ECtHR, Israeli Attorney General (body § strategy + scalar:sources[0].note)

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: "...will initiate an investigation by the National Security Committee of Parliament and the Commissioner for Fundamental Rights... will take legal action before the courts and the National Authority for Data Protection and Freedom of Information... has therefore filed a complaint with the European Commission... is therefore also launching a multitude of lawsuits before the European Court of Human Rights... It is initiating an investigation by the Israeli Attorney General..."
Comparison: Each of the seven named tracks appears in the primary source. DW independently confirms the Hungarian-authorities / EC / ECtHR / Israel spread.
Decision: primary-sourced

## Claim 7: "seven distinct proceedings tracks" as the count (body + scalar:sources[0].note "the seven proceedings tracks")

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: The page gives no count; beyond the seven named tracks it also lists "complaints with the ministers overseeing the secret services" and "so-called subject access requests with the secret services" as remedy channels.
Comparison: "Seven" is the entity's own aggregation. The source enumerates additional channels and never counts; whether ministers-complaints and subject-access requests are "proceedings tracks" is a grouping judgment the audit cannot settle. Scalar path: sources[0].note.
Decision: uncorroborated

## Claim 8: European Commission complaint on behalf of Adrien Beauduin, grounded in his Belgian/EU citizenship

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: "According to the HCLU, the surveillance of Belgian student activist Adrien Beauduin, who was studying in Hungary at the time of his surveillance, is a violation of EU law, namely the right to free movement of persons and workers. The organisation has therefore filed a complaint with the European Commission..."
Comparison: EC complaint is tied to Beauduin ✓. The source's stated legal basis is the EU free-movement right; the body's "standing as an EU citizen whose rights had been violated" is a compatible but broader paraphrase.
Decision: primary-sourced

## Claim 9: Israeli Attorney General investigation request re NSO's export licence (supply side)

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: "It is initiating an investigation by the Israeli Attorney General in the cases of Szabolcs Panyi, Adrien Beauduin and a third client... The aim of the investigation is to find out how the cyberweapon could have been authorised for export from Israel to a country that does not properly regulate secret surveillance..."
Comparison: Track and export-licence focus confirmed. The body's "whether NSO Group had committed a criminal offence in obtaining the... export licence" is a compressed framing; the source frames it as investigating how the export could have been authorised. Substance matches; framing slightly sharper than source.
Decision: primary-sourced

## Claim 10: legal team — in-house Tivadar Hüttl, Flóra Kollarics, Kata Nehéz-Posony; external Balázs Tóth and Eitay Mack (body + scalar:sources[0].note)

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: Page names Tivadar Hüttl, Flóra Kollarics, Kata Nehéz-Posony (lawyers), Balázs Tóth (human rights lawyer, cooperating on ECtHR cases), Eitay Mack (independent Israeli lawyer, external cooperation).
Comparison: All five names and in-house/external split confirmed; DW independently confirms Mack's representation. Minor: the source ties Tóth to the ECtHR cases, while the body says "domestic and European tracks" — the domestic half is not confirmed.
Decision: primary-sourced

## Claim 11: in-house lawyers "coordinated by Ádám Remport" (body § Clients and legal team)

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: The page's only Remport reference: "Said Ádám Remport, a TASZ expert on surveillance issues."
Comparison: No source found states that Remport coordinated the legal team; the primary source presents him as TASZ's surveillance expert, not team coordinator.
Decision: uncorroborated

## Claim 12: Remport quote "The use of the secret services to serve those in power rather than the nation as a whole is appallingly familiar in Central and Eastern Europe" + "TASZ surveillance expert" title (body + scalar:sources[0].note)

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: "The use of secret services to serve those in power rather than the nation as a whole is appallingly familiar in Central and Eastern Europe." — "Said Ádám Remport, a TASZ expert on surveillance issues."
Comparison: Quote confirmed on the primary source in substance and near-verbatim wording; title matches ("a TASZ expert on surveillance issues").
Decision: primary-sourced

## Claim 13: Adrien Beauduin — Belgian student activist whose participation in pro-democracy events in Budapest resulted in his phone being confirmed as a Pegasus target

Source: https://telex.hu/belfold/2021/07/19/ceu-pegasus-beauduin-lehallgatas-diak
Source tier: mainstream
Source content: Telex: Beauduin, a Belgian-Canadian CEU gender-studies student, took part in the 2018 CEU and "slave law" protests, was detained at a December 2018 rally, and his number appeared on the Pegasus target list; Amnesty's Security Lab "did find evidence of attempted intrusion" though forensics "could not clearly establish that the device had been successfully hacked."
Comparison: Belgian student activist ✓ (TASZ primary + Telex; Telex notes dual Belgian-Canadian nationality), protest participation and its causal link to targeting ✓ (targeted following protest detention). "Confirmed as a Pegasus target" matches the record precisely in the "targeted" sense (attempted-intrusion evidence; not confirmed infected).
Decision: corroborated

## Claim 14: Pegasus Project — published 18 July 2021, coordinated by Paris-based Forbidden Stories with Amnesty International's Security Lab and seventeen media partners, among them Direkt36 (body + scalar:sources[3].note in part)

Source: https://forbiddenstories.org/about-the-pegasus-project/
Source tier: primary
Source content: "more than 80 reporters from 17 media organizations in 10 countries coordinated by Forbidden Stories" with "technical support of Amnesty International's Security Lab"; partner list includes Direkt36; publication 18 July 2021.
Comparison: Date, 17-newsroom scope, Amnesty Security Lab partnership, and Direkt36's inclusion all confirmed by the project's own page; IPI and Wikipedia corroborate. "Paris-based" is a definitional org fact (Wikipedia-alone class), widely documented.
Decision: corroborated

## Claim 15: leaked database "contained approximately fifty thousand phone numbers across more than fifty countries"

Source: https://forbiddenstories.org/about-the-pegasus-project/
Source tier: primary
Source content: "An unprecedented leak of more than 50,000 phone numbers selected for surveillance" across "more than 50 countries since 2016."
Comparison: Matches; universally reported figures (Wikipedia, VSquare corroborate).
Decision: corroborated

## Claim 16: "approximately three hundred numbers" appeared in the database in Hungary (body §§ opening and Context)

Source: https://vsquare.org/what-happend-in-hungary-after-the-pegasus-revelations/
Source tier: mainstream
Source content: "The leak provided to Forbidden Stories included 300 Hungarian phone numbers." Wikipedia's Pegasus Project article and IPI ("reporting 300 Hungarian phone numbers that were possibly targeted in 2018 and 2019") carry the same figure.
Comparison: The figure is correct and multiply corroborated — but neither hyperlink target the body attaches it to carries it: the forbiddenstories.org page does not mention Hungarian numbers, and the TASZ one-year page contains no 300 figure. Claim true; the two in-body citations misattribute (see Claim 17 for the frontmatter half).
Decision: corroborated

## Claim 17: scalar:sources[3].note — the Forbidden Stories page as "source for... the leaked NSO Group surveillance-targets database in which approximately 300 Hungarian phone numbers were identified"

Source: https://forbiddenstories.org/about-the-pegasus-project/
Source tier: primary
Source content: Two independent extractions of the page found no mention of Hungary-specific numbers: "No mention of 300 Hungarian phone numbers appears in this content."
Comparison: The note asserts the cited page contains the ~300-Hungarian-numbers figure; it does not. Single correct replacement: drop the "~300 Hungarian numbers" clause from sources[3].note (or re-cite to a source that carries it, e.g. VSquare/Direkt36). Scalar path: sources[3].note.
Decision: correction

## Claim 18: "Among those whose phones were forensically confirmed as infected or targeted were Szabolcs Panyi and fellow journalists at Direkt36"

Source: https://forbiddenstories.org/about-the-pegasus-project/
Source tier: primary
Source content: Panyi's phone was "compromised during a seven-month period in 2019." MFRR: "Szabolcs Panyi and András Szabó from investigative center Direkt36" were among those surveilled.
Comparison: Panyi confirmed infected ✓; at least one fellow Direkt36 journalist (András Szabó) also confirmed ✓. This sentence, unlike Claim 5's, is accurate.
Decision: corroborated

## Claim 19: Direkt36 "co-published the Hungarian story on the same day as the global consortium release"

Source: https://ipi.media/hungary-pegasus-scandal-i-was-absolutely-shocked-to-see-the-scale-of-this-surveillance/
Source tier: mainstream
Source content: "From Hungary, investigative online outlet Direkt36 was the only participant in the international Pegasus Project investigation"; Direkt36/Telex published "Hungarian journalists and critics of Orbán were targeted with Pegasus" on 18 July 2021.
Comparison: Confirmed by IPI and by the Forbidden Stories partner list; the Hungarian story ran 18 July 2021, the consortium release date.
Decision: corroborated

## Claim 20: initial government denial; "by November 2021, the chair of Parliament's Defence Committee, Lajos Kósa, had publicly confirmed that Hungary had used Pegasus"

Source: https://www.direkt36.hu/en/igy-hullottak-az-igazsag-morzsai-a-pegasus-ugy-ket-eve-alatt/
Source tier: mainstream
Source content: The government "first denied everything, then tried to keep silent"; Kósa "seemingly accidentally revealed that the Ministry of Interior had indeed purchased the Pegasus spyware." BBJ: "Kósa admits to Hungary using NSO Group's Pegasus spyware" (4 November 2021); RFE/RL: "Top Hungarian Official Admits Government Bought Pegasus Spyware."
Comparison: Denial-then-confirmation trajectory and Kósa's early-November 2021 admission of purchase and use confirmed across three sources. Minor precision: Kósa chairs the parliamentary Defence and Law Enforcement Committee — the body's "Defence Committee" is the common short form.
Decision: corroborated

## Claim 21: Kósa "characterising the surveillance as 'completely legal' under Hungarian national-security law"

Source: https://www.direkt36.hu/en/igy-hullottak-az-igazsag-morzsai-a-pegasus-ugy-ket-eve-alatt/
Source tier: mainstream
Source content: "The government subsequently maintained that 'all the surveillance was completely legal.'" RFE/RL: "Kósa insisted the government had not used the malicious software to spy on Hungarians."
Comparison: The quoted phrase "completely legal" is attributed by the cited source to the government's subsequent position, not to Kósa personally; Kósa's own reported words were a lawfulness insistence in different terms. Attribution of the verbatim phrase to Kósa is not confirmed and not clearly wrong — sources vary.
Decision: uncorroborated

## Claim 22: "The confirmed operator was the Special Service for National Security (SSNS), operating under the Interior Ministry" (+ scalar:sources[4].note)

Source: https://www.direkt36.hu/en/igy-hullottak-az-igazsag-morzsai-a-pegasus-ugy-ket-eve-alatt/
Source tier: mainstream
Source content: "The Special Service for National Security (SSNS), overseen by the Interior Ministry," operated the spyware and "conducted the technical surveillance" for other national security services.
Comparison: Matches the cited source (a specialist investigative outlet with editorial standards). No second independent canonical source consulted this session.
Decision: single-source

## Claim 23: National Security Committee members boycotted proceedings; minutes classified until 2050 (body ×2 + scalar:sources[1].note)

Source: https://tasz.hu/en/cikkek/the-hungarian-government-does-everything-to-cover-up-the-pegasus-affair-the-hclus-takeaways-from-the-first-year-of-the-scandal/
Source tier: primary
Source content: "minutes were classified until 2050" — in the page's account of the committee boycott and closure of the parliamentary channel.
Comparison: Both specifics confirmed on TASZ's own one-year analysis (the entity's cited source for them). The body's "Fidesz-majority members" attribution of the boycott is consistent with the page's account.
Decision: primary-sourced

## Claim 24: Commissioner for Fundamental Rights deflected complaints to the DPA "without legal basis" (body + scalar:sources[1].note)

Source: https://tasz.hu/en/cikkek/the-hungarian-government-does-everything-to-cover-up-the-pegasus-affair-the-hclus-takeaways-from-the-first-year-of-the-scandal/
Source tier: primary
Source content: The Commissioner "deflected the task, claiming that it was the responsibility of the National Authority for Data Protection and Freedom of Information (DPA)."
Comparison: Deflection confirmed verbatim on the primary source. The "without legal basis" qualifier is TASZ's framing carried by the same page's argument; not separately confirmed in the extraction but attributed to the same primary source the entity cites.
Decision: primary-sourced

## Claim 25: the DPA found no violations, "examining only Hungarian domestic-law compliance" (body + scalar:sources[1].note)

Source: https://tasz.hu/en/cikkek/the-hungarian-government-does-everything-to-cover-up-the-pegasus-affair-the-hclus-takeaways-from-the-first-year-of-the-scandal/
Source tier: primary
Source content: The authority "found everything to be in order, because it was only concerned with compliance with Hungarian law."
Comparison: Both the no-violation finding and the domestic-law-only scope match the primary source near-verbatim.
Decision: primary-sourced

## Claim 26: "Hungarian prosecutors closed their criminal investigations in June 2022, finding the documented surveillance lawful" (+ scalar notes in sources[1] and sources[4])

Source: https://www.direkt36.hu/en/igy-hullottak-az-igazsag-morzsai-a-pegasus-ugy-ket-eve-alatt/
Source tier: mainstream
Source content: The prosecutor's office "considered the surveillance to be lawful" and noted surveilled journalists "are not necessarily suspected of committing a crime." DailyNewsHungary/abouthungary: investigative prosecutors terminated the probe citing "absence of a crime" (June 2022).
Comparison: Closure, June 2022 timing, and lawfulness grounds confirmed across the cited source and two further outlets.
Decision: corroborated

## Claim 27: "Hungarian state surveillance had grown 40% between 2015 and 2021" (body + scalar:sources[1].note)

Source: https://tasz.hu/en/cikkek/the-hungarian-government-does-everything-to-cover-up-the-pegasus-affair-the-hclus-takeaways-from-the-first-year-of-the-scandal/
Source tier: primary
Source content: "The number of surveillance orders is constantly increasing: by around 40% between 2015 and 2021."
Comparison: Figure and period match; note the source's metric is surveillance orders, which the body renders as "state surveillance."
Decision: primary-sourced

## Claim 28: TASZ's summation quote "even unlawful surveillance is legal if carried out for national security purposes"

Source: https://tasz.hu/en/cikkek/the-hungarian-government-does-everything-to-cover-up-the-pegasus-affair-the-hclus-takeaways-from-the-first-year-of-the-scandal/
Source tier: primary
Source content: "In Hungary, even unlawful surveillance is legal if carried out for national security purposes."
Comparison: Verbatim match on the primary source (body omits only the leading "In Hungary," which its sentence context supplies).
Decision: primary-sourced

## Claim 29: "By February 2023 the European Court of Human Rights had registered a mass action" on behalf of 36 clients — journalists, activists, and civil-society organisation members (body + scalar:sources[2].note)

Source: https://www.mediadefence.org/news/partner-hclu-spyware/
Source tier: mainstream
Source content: "HCLU is also planning mass action directly before the European Court of Human Rights on behalf of 36 clients—different from the ones targeted with Pegasus—who work in areas that make them particularly exposed to abuse: journalists, activists and members of CSOs." "The ECtHR registered the complaints in February 2023." RFE/RL Hungary (szabadeuropa.hu) confirms the Strasbourg court accepted TASZ's 36-client mass application in February 2023.
Comparison: Registration date, 36-client count, and client categories confirmed by two sources. Nuance the body softens: Media Defence states the 36 are "different from the ones targeted with Pegasus" (at-risk persons); the frontmatter note's "targeted or at risk" hedge covers this, the body's "the Pegasus surveillance of its civil society" framing less so.
Decision: corroborated

## Claim 30: separate domestic track against the Constitutional Protection Office and Information Office on behalf of the journalist-clients (scalar:sources[2].note)

Source: https://www.mediadefence.org/news/partner-hclu-spyware/
Source tier: mainstream
Source content: "In Hungary, HCLU launched proceedings against the Constitutional Protection Office (CPO) under the Ministry of the Interior, and the Information Office (IO) under the Ministry of Foreign Affairs and Trade, in order to bring the surveillance abuses to light, as well as to bring justice to the journalists targeted."
Comparison: Both agencies and the journalists' interest confirmed by the cited source. Scalar path: sources[2].note. The note's "on behalf of the four journalist-clients" is slightly more specific than the source's "the journalists targeted."
Decision: single-source

## Claim 31: "TASZ also intervened in Brejza v. Poland before the ECtHR"

Source: https://ifex.org/poland-hclu-and-other-groups-intervene-in-pegasus-case-before-ecthr/
Source tier: primary
Source content: "The Hungarian Civil Liberties Union, together with three other human rights organisations... has intervened in the case of Brejza v. Poland, currently before the European Court of Human Rights." TASZ's own third-party-intervention brief is published at tasz.hu (Brejza-v.-Lengyelorszag-beavatkozas.pdf).
Comparison: Intervention confirmed by TASZ's own filed brief (primary) and IFEX. Note: the body cites mediadefence.org for this, which does not mention Brejza — a miscitation, though the claim is sound.
Decision: corroborated

## Claim 32: Citizen Lab "conducted the forensic analysis of targeting during Poland's 2019 election campaign" (Brejza)

Source: https://www.pbs.org/newshour/world/amnesty-international-verifies-polish-senator-was-hacked-with-pegasus-spyware
Source tier: mainstream
Source content: Citizen Lab experts asserted forensic evidence that data was stolen from Senator Brejza's phone; "An expert with Amnesty International's Security Lab confirmed Citizen Lab's finding after receiving raw backups of Brejza's phone." Brejza's "private information was used against him during an election campaign" (2019).
Comparison: Citizen Lab's forensic role and the 2019 election-campaign context both confirmed (PBS/AP plus the PACE/analyst record). Edge to org-citizen-lab resolves correctly.
Decision: corroborated

## Claim 33: "In June 2023 the European Parliament's PEGA Committee... condemned Hungary in its final report"

Source: https://epthinktank.eu/2024/06/02/what-action-has-parliament-taken-against-spyware-abuse/
Source tier: primary
Source content: The PEGA report found Hungarian spyware use "part of a calculated and strategic campaign to destroy media freedom and freedom of expression by the government"; "on 15 June 2023, the EP adopted a recommendation." Direkt36 (cited): Parliament adopted the PEGA Committee report "by a large majority."
Comparison: The condemnation of Hungary and the June 2023 date are confirmed (Direkt36 + EP sources). Precision note: the committee adopted its report earlier in 2023; June 2023 is the Parliament plenary's adoption of the PEGA recommendation — the body's phrasing folds the two.
Decision: corroborated

## Claim 34: "the first systematic public civil-society legal challenge in Hungary" following the Pegasus Project

Source: https://londondaily.com/pegasus-scandal-in-hungary-journalists-sue-state-over-spyware-dw-29-01-2022
Source tier: mainstream
Source content: "This is the first legal case brought by Pegasus victims against an EU state."
Comparison: One mainstream source supports a compatible (indeed stronger) first-ness claim. "First" claims are contested-attribution class; only one source found.
Decision: single-source

## Claim 35: edges — participating_orgs [org-tasz]; body cross-references to org-tasz, org-citizen-lab, org-panoptykon-foundation, camp-r3d-pegasus-mexico-civil-society-response-2017-ongoing, event-edri-reclaim-your-face-eci-launch-2021-02-17, event-bbw-stop-facial-recognition-joint-statement-2023-10-06

Source: corpus entity files (local resolution check)
Source tier: primary
Source content: All six referenced files exist; names match the roles the body assigns them (TASZ = Hungarian Civil Liberties Union; Citizen Lab; Panoptykon Foundation; R3D Mexican Pegasus response 2017–ongoing; EDRi Reclaim Your Face ECI launch 17 Feb 2021; BBW joint statement 6 Oct 2023). The R3D entity's own text confirms the comparison's specifics (federal criminal complaints, Inter-American human-rights system, Pegasus Project investigative coalition).
Comparison: Every edge resolves to the correct entity; the R3D forum characterization matches the target entity's mission and outcomes text.
Decision: corroborated

## Claim 36: "the only one that opens simultaneous judicial proceedings on three continents on the day of its public announcement" (body § Significance)

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: The proceedings named are in Hungary (courts, NAIH, parliamentary committee, Commissioner), before EU institutions (European Commission, ECtHR in Strasbourg), and in Israel (Attorney General).
Comparison: The jurisdictions span Europe (Hungary, Strasbourg, Brussels) and Asia (Israel) — two continents, not three. No proceeding in the announcement touches a third continent. Single correct replacement: "three continents" → "two continents."
Decision: correction
