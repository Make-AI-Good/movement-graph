---
entity_id: camp-ilaw-pegasus-civil-society-thailand-2022
entity_hash: cc2a94fbf7c620b915963ca99d400be9ebaaed74
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 42
claims_corroborated: 17
claims_primary_sourced: 9
claims_single_source: 7
claims_uncorroborated: 5
open_corrections: 4
sources_consulted:
  - https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
  - https://www.amnesty.org/en/latest/news/2022/07/pegasus-thailand-activists-protests/
  - https://www.aljazeera.com/news/2022/7/18/pegasus-malware-targeted-thai-democracy-activists-report
  - https://www.manushyafoundation.org/post/pai-jatupat-and-the-pegasus-spyware-a-three-year-legal-battle
  - https://www.amnesty.org/en/latest/news/2024/11/thailand-dismissal-of-landmark-case-a-critical-and-alarming-setback-in-fight-against-unlawful-use-of-spyware/
  - https://therecord.media/thai-court-dismisses-activists-lawsuit-spyware
  - https://www.ilaw.or.th/articles/48013 (search snippet; 403 on direct fetch)
  - https://www.ilaw.or.th/articles/39389 (search snippet; 403 on direct fetch)
  - https://www.ilaw.or.th/articles/35057 (search snippet; 403 on direct fetch)
  - https://citizenlab.ca/research/forcedentry-nso-group-imessage-zero-click-exploit-captured-in-the-wild/ (search snippet)
  - https://www.usnews.com/news/world/articles/2022-07-22/thai-minister-backtracks-on-spyware-admission-as-government-denies-pegasus-use (Reuters mirror; search snippet)
  - https://www.newmandala.org/the-ten-demands-that-shook-thailand/ (search snippet)
  - https://time.com/5890121/thai-king-thailand-monarchy-vajiralongkorn-arnon-nampa/ (search snippet)
  - https://www.apple.com/newsroom/2021/11/apple-sues-nso-group-to-curb-the-abuse-of-state-sponsored-spyware/ (search snippet)
  - https://techcrunch.com/2021/09/13/apple-zero-day-nso-pegasus/ (search snippet)
---

Connective type (campaign): claim surface is edges (`lead_orgs`/`participating_orgs`/`events`/`strategies`) and hard specifics (dates, counts, outcomes, named actors) per `mission/MISSION.md § Auditor § Type-shape awareness`. Narrative significance prose in § Place in the make-AI-good movement audited only for its embedded hard specifics. `events`/`strategies` edges are empty — nothing to check.

## Claim 1: edge lead_orgs/participating_orgs → org-ilaw

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; corpus file product/entities/organizations/org-ilaw.md
Source tier: primary
Source content: "A report with detailed contextual analysis by iLaw and DigitalReach" titled "The Parasite That Smiles"; corpus entity is "Internet Law Reform Dialogue (iLaw)", Thailand.
Comparison: Edge resolves to the correct entity — the Thai NGO that co-authored the companion report and filed the class action; Amnesty and Al Jazeera also name iLaw as co-investigator.
Decision: corroborated

## Claim 2: edge lead_orgs/participating_orgs → org-citizen-lab

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; corpus file product/entities/organizations/org-citizen-lab.md
Source tier: primary
Source content: GeckoSpy is a Citizen Lab report (authors John Scott-Railton, Bill Marczak, et al.); corpus entity is Citizen Lab, Toronto.
Comparison: Edge resolves to the correct entity — the research lab that authored GeckoSpy; Al Jazeera names "Canadian organization Citizen Lab" as co-investigator.
Decision: corroborated

## Claim 3: scalar:start_date — "2021-11"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: "On November 23, 2021, Apple began sending notifications to iPhone users targeted by state-backed attacks"; "shortly thereafter, multiple recipients of the notification made contact with the Citizen Lab and regional groups."
Comparison: Campaign start pegged to the November 2021 Apple notifications matches GeckoSpy and Al Jazeera ("notifications from Apple in November 2021").
Decision: corroborated

## Claim 4: scalar:goals — "targeting of at least 30 individuals who participated in or supported Thailand's 2020–2021 pro-democracy protest wave"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; https://www.amnesty.org/en/latest/news/2022/07/pegasus-thailand-activists-protests/
Source tier: primary
Source content: "at least 30 forensically-confirmed victims of NSO Group's Pegasus spyware between October 2020 and November 2021"; Amnesty: "30 people who were targeted or infected".
Comparison: Count and protest-wave linkage match both sources.
Decision: corroborated

## Claim 5: scalar:goals — reform goals naming the Computer-Related Crime Act, Cybersecurity Act, and National Intelligence Act; global moratorium advocacy

Source: https://www.amnesty.org/en/latest/news/2022/07/pegasus-thailand-activists-protests/
Source tier: mainstream
Source content: Amnesty demands amendments to "the Computer Crimes Act, the Cybersecurity Act, and the National Intelligence Act in line with international human rights law" and "a global moratorium on the sale, transfer, and use of spyware".
Comparison: The three named statutes and the moratorium demand are on the public record via Amnesty's statement; iLaw's own recommendations page (the campaign's channel for these goals) 403s on direct fetch, so only one source confirms the goals as campaign goals.
Decision: single-source

## Claim 6: scalar:outcomes + body — "Apple sent state-sponsored-attack notifications to six Thai activists" (November 2021)

Source: https://www.aljazeera.com/news/2022/7/18/pegasus-malware-targeted-thai-democracy-activists-report
Source tier: mainstream
Source content: "six Thai activists received notifications from Apple in November 2021 advising that they had been the victims of 'state-sponsored attacks'".
Comparison: The count of six rests on Al Jazeera alone; GeckoSpy says only that "multiple recipients" contacted Citizen Lab and regional groups after notifications began 23 November 2021.
Decision: single-source

## Claim 7: scalar:outcomes + body — iLaw field survey of Thai civil society, March–June 2022

Source: https://www.ilaw.or.th/articles/35057 (search snippet; direct fetch 403)
Source tier: primary
Source content: "iLaw conducted a field survey from March to June 2022 in order to identify more victims."
Comparison: iLaw's own published account of the investigation confirms the survey and its months exactly; matches body and scalar:sources[1].note.
Decision: primary-sourced

## Claim 8: scalar:outcomes + body — 17–18 July 2022 simultaneous publication of GeckoSpy and Parasite That Smiles; 30 forensically confirmed infections Oct 2020–Nov 2021; circumstantial attribution to Thai government operator(s)

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; https://www.amnesty.org/en/latest/news/2022/07/pegasus-thailand-activists-protests/ ; https://www.aljazeera.com/news/2022/7/18/pegasus-malware-targeted-thai-democracy-activists-report
Source tier: primary
Source content: GeckoSpy published July 17, 2022; "at least 30 forensically-confirmed victims... between October 2020 and November 2021"; "we do not conclusively attribute the Pegasus hacking operation to a specific governmental operator" but circumstantial evidence points to Thai government; companion report "The Parasite That Smiles" by iLaw and DigitalReach.
Comparison: Dates, count, dual publication, and attribution-on-circumstantial-grounds phrasing all match; the entity's careful "on circumstantial grounds" wording tracks the report's non-conclusive attribution.
Decision: corroborated

## Claim 9: scalar:outcomes + body — Amnesty International Security Lab independently verified five infections

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; https://www.amnesty.org/en/latest/news/2022/07/pegasus-thailand-activists-protests/
Source tier: primary
Source content: GeckoSpy: Amnesty examined five cases, "findings matched the Citizen Lab's assessments"; Amnesty: "independently confirmed five of the cases in the report through forensic analysis."
Comparison: Exact match, both sides of the verification.
Decision: corroborated

## Claim 10: scalar:outcomes + body — 15 November 2022 class action by eight victims against NSO at Bangkok Civil Court; dismissed because infections did not occur simultaneously / could not form a single case

Source: https://www.ilaw.or.th/articles/48013 (search snippet) ; https://therecord.media/thai-court-dismisses-activists-lawsuit-spyware ; https://www.manushyafoundation.org/post/pai-jatupat-and-the-pegasus-spyware-a-three-year-legal-battle
Source tier: primary
Source content: "Eight victims of Pegasus filed a class lawsuit against NSO Group on November 15, 2022... the class lawsuit was dismissed as the court ruled that the infection did not happen at the same time"; "the Civil Court did not accept the lawsuit... the eight plaintiffs were violated differently and could not be sued together as a single case"; The Record: "dismissed by the Civil Court in Bangkok on grounds that the cases could not be combined."
Comparison: Date, plaintiff count, court, and non-simultaneity dismissal grounds all confirmed.
Decision: corroborated

## Claim 11: scalar:outcomes + body — Yingcheep Atchanont among the eight class-action plaintiffs; described as "iLaw's manager"

Source: no canonical source found for his inclusion among the eight
Source tier: none
Source content: Manushya: "Eight Thai citizens, including Pai, filed a class action lawsuit" (names only Jatupat); The Record: after the dismissal "Yingcheep then plans to file a suit with himself as the plaintiff."
Comparison: No fetched source names Yingcheep among the eight class-action filers, and The Record's phrasing suggests his suit was planned separately after the dismissal; his title also varies across sources (programme manager / Director of iLaw). Not contradicted, but unsupported.
Decision: uncorroborated

## Claim 12: scalar:outcomes + body — June 2023 civil lawsuit by Arnon Nampa and Yingcheep Atchanont against nine Thai government agencies for unlawful surveillance

Source: https://www.manushyafoundation.org/post/pai-jatupat-and-the-pegasus-spyware-a-three-year-legal-battle
Source tier: mainstream
Source content: "In June 2023, Yingcheep Atchanont and pro-democracy lawyer Arnon Nampa filed another lawsuit against nine Thai government agencies, including the Office of the Prime Minister, for unlawful surveillance."
Comparison: Exact match on date, plaintiffs, defendant count, and claim; only Manushya's account confirms the filing itself (Reuters/Bangkok Post coverage from February 2023 documents the plan, not the filing).
Decision: single-source

## Claim 13: body — the nine-agencies lawsuit "was still pending as of late 2024"

Source: no canonical source found
Source tier: none
Source content: Manushya (August 2024 account) describes the suit as filed but does not state its status; the November 2024 dismissal coverage does not mention it.
Comparison: No fetched source states the suit's status in late 2024. Not contradicted; the audit reaches its limits here.
Decision: uncorroborated

## Claim 14: scalar:outcomes + body — 13 July 2023: Jatupat's individual lawsuit against NSO seeking 2.5 million baht, access to his data, deletion, and a halt order

Source: https://www.ilaw.or.th/articles/48013 (search snippet) ; https://therecord.media/thai-court-dismisses-activists-lawsuit-spyware ; https://www.manushyafoundation.org/post/pai-jatupat-and-the-pegasus-spyware-a-three-year-legal-battle
Source tier: primary
Source content: iLaw: Jatupat "filed a lawsuit as the sole plaintiff on July 13, 2023 in the Thai Civil Court"; The Record: "He sought 2,500,000 Thai baht ($72,129) in damages along with access to the data taken from his device and the deletion of it"; Manushya: "seeking 2.5 million Baht in damages... and has called for a court order to halt NSO Group's use of Pegasus spyware against Thai citizens."
Comparison: Filing date, amount, and all three remedies confirmed across three sources.
Decision: corroborated

## Claim 15: scalar:outcomes + body — June 2024 mediation failed: NSO declined to identify the Thai government purchaser, offered a partial settlement of ~1,250,000 baht (half) with a non-disclosure clause; Jatupat rejected it

Source: https://www.ilaw.or.th/articles/39389 (search snippet) ; https://www.manushyafoundation.org/post/pai-jatupat-and-the-pegasus-spyware-a-three-year-legal-battle
Source tier: primary
Source content: iLaw: mediation on June 21, 2024; Jatupat offered to withdraw if NSO disclosed "the name of the agency that sold Pegasus", in which case "he would claim only half of the damages, which is 1,250,000 baht"; "The defendant refused to acknowledge violations and instead proposed a settlement of 1,250,000 baht"; mediation "failed to reach an agreement". Manushya: "offered a partial settlement with a non-disclosure clause, which Pai rejected."
Comparison: Amount (half = 1,250,000 baht), NSO's refusal to disclose its Thai government client, the NDA condition, and the rejection all confirmed.
Decision: corroborated

## Claim 16: scalar:outcomes + body — September 2024 witness hearings at Ratchada Civil Court, Bangkok

Source: https://www.manushyafoundation.org/post/pai-jatupat-and-the-pegasus-spyware-a-three-year-legal-battle
Source tier: mainstream
Source content: Hearings occurred "from September 3-5 and 10, 2024, at the Ratchada Civil Court in Bangkok."
Comparison: Dates and court confirmed by Manushya; DigitalReach's published hearing summary confirms the hearings occurred but its page 403s on direct fetch, so the specific dates/court rest on one source.
Decision: single-source

## Claim 17: scalar:outcomes + body — 21 November 2024: Bangkok Civil Court dismissed Jatupat's case for inadequately presented forensic evidence; Amnesty called it "a critical and alarming setback in fight against unlawful use of spyware" and said it "won't deter the fight"

Source: https://www.amnesty.org/en/latest/news/2024/11/thailand-dismissal-of-landmark-case-a-critical-and-alarming-setback-in-fight-against-unlawful-use-of-spyware/ ; https://therecord.media/thai-court-dismisses-activists-lawsuit-spyware
Source tier: primary
Source content: Amnesty (21 Nov 2024): "The court dismissed the case on the basis that there was insufficient evidence to prove that Jatupat's device was infected. The court cited that the plaintiff did not adequately present details about the forensic investigation and its outcome"; "it won't deter the fight against the unlawful use of spyware"; the "critical and alarming setback" phrase is the piece's title. The Record: "The court dismissed the case, saying there was not enough evidence to prove his device was infected."
Comparison: Date, court, grounds, and both Amnesty statements confirmed (Amnesty is primary for its own characterisation).
Decision: corroborated

## Claim 18: body §Infection targets — Panusaya "was forensically confirmed infected six times between June and September 2021"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: "Our analysis revealed that Panusaya was repeatedly hacked with Pegasus throughout June (15, 20, and 23), and again on or around September 24, 2021." (Table 1 lists exactly four infection dates.)
Comparison: GeckoSpy records FOUR infections for Panusaya, not six — the body token "six times" contradicts the report and has a single correct replacement ("four times"); the June–September 2021 window is correct. Likely conflated with Jutatip Sirikhan's six infections. Fix location: body § "Infection targets: activists, lawyers, and academics".
Decision: correction

## Claim 19: scalar:sources[0].note — "named infection counts for Panusaya Sithijirawattanakul (6 infections June–September 2021)"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: Same as Claim 18 — four dated infections (2021-06-15, 06-20, 06-23, 09-24).
Comparison: Same token error as Claim 18 in the frontmatter source note. Fix location: scalar:sources[0].note — replace "6 infections" with "4 infections".
Decision: correction

## Claim 20: body — Panusaya described as "a University of Thammasat Student Union member and UFTD (United Front of Thammasat and Demonstration) spokesperson"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; https://www.newmandala.org/the-ten-demands-that-shook-thailand/ (search snippet)
Source tier: none
Source content: GeckoSpy: "Panusaya, who is also a spokesperson for the Student Union of Thailand", with table affiliation "United Front of Thammasat and Demonstration"; other coverage describes her as spokesperson for UFTD.
Comparison: Canonical sources conflict on which body she was spokesperson for (GeckoSpy: Student Union of Thailand spokesperson + UFTD member; other coverage: UFTD spokesperson), and no source uses the name "University of Thammasat Student Union" (the organisation is the Student Union of Thailand). The entity's phrasing inverts GeckoSpy's roles, but with sources in conflict there is no single determinate replacement.
Decision: uncorroborated

## Claim 21: body — Panusaya's "August 2020 speech formulating the protest movement's ten-point monarchy-reform agenda"

Source: https://www.newmandala.org/the-ten-demands-that-shook-thailand/ (search snippet) ; https://en.wikipedia.org/wiki/2020%E2%80%932021_Thai_protests (tiebreaker)
Source tier: mainstream
Source content: At the 10 August 2020 "Thammasat will not tolerate" rally by the United Front of Thammasat and Demonstration, "the declaration of ten demands to reform the monarchy by Rung Panusaya."
Comparison: The August 2020 ten-demands declaration by Panusaya is confirmed by mainstream coverage plus Wikipedia as tiebreaker.
Decision: corroborated

## Claim 22: body — Panusaya "faced at least ten lèse-majesté charges and 85 days of detention"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: "has been charged with at least 10 lèse-majesté offenses, and was detained for a total of 85 days between 2020 and 2021".
Comparison: Exact match; rests on the GeckoSpy report alone.
Decision: primary-sourced

## Claim 23: body — Arnon Nampa "confirmed infected five times across 2020 and 2021"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: Five infections: "December 3, 15, 2020; July 10, 14; August 31, 2021".
Comparison: Count and years match exactly (also matches scalar:sources[0].note "5 infections 2020–2021").
Decision: primary-sourced

## Claim 24: body — Arnon Nampa "was among the first to publicly call for constitutional monarchy reform at a Bangkok rally in August 2020"

Source: https://time.com/5890121/thai-king-thailand-monarchy-vajiralongkorn-arnon-nampa/ (search snippet) ; https://www.nationthailand.com/news/politics/40044310 (search snippet)
Source tier: mainstream
Source content: "On 3 August 2020, Arnon Nampa openly criticized the monarchy in front of 200 protesters... at the Democracy Monument... regarded as the first time in Thai history that the monarchy's powers were [questioned] in an unusually frank public speech."
Comparison: The 3 August 2020 Harry Potter-themed rally at Bangkok's Democracy Monument matches the body's "Bangkok rally in August 2020" and the first-to-call framing.
Decision: corroborated

## Claim 25: body — Arnon "had faced fourteen or more lèse-majesté charges and been detained 339 days" by the report's publication

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: "charged with at least 14 lèse-majesté charges and was detained for a total of 339 days between 2020-2022".
Comparison: Exact match; rests on the GeckoSpy report alone.
Decision: primary-sourced

## Claim 26: body — Jatupat Boonpattararaksa: Thalufah movement leader, protest name Pai Dao Din, "confirmed infected three times in June and July 2021"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; https://www.manushyafoundation.org/post/pai-jatupat-and-the-pegasus-spyware-a-three-year-legal-battle
Source tier: primary
Source content: GeckoSpy: three infections "June 23, 28; July 9, 2021", "Thalufah leader"; Amnesty amicus coverage: "whose phone was infected with Pegasus spyware three times between June and July 2021"; Manushya refers to him throughout as "Pai".
Comparison: Count, months, movement affiliation, and nickname all confirmed across sources.
Decision: corroborated

## Claim 27: body — "Jutatip Sirikhan, a FreeYOUTH member, was confirmed infected six times starting October 2020"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: Six infections: "October 21, 26, 2020; February 15, 20; March 18; September 6, 2021"; described as "FreeYOUTH president".
Comparison: Count and start month match exactly; source says "president", the body's "member" is compatible (weaker claim). Rests on GeckoSpy alone.
Decision: primary-sourced

## Claim 28: body — infections documented "across WEVO and UFTD network activists, academics..., artists, journalists, and civil society workers"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: "at least 30 Pegasus victims among key civil society groups in Thailand, including activists, academics, lawyers, and NGO workers"; "individuals associated with FreeYOUTH, United Front of Thammasat and Demonstration (UFTD), and We Volunteer (WEVO), were infected".
Comparison: WEVO/UFTD activists, academics, and civil-society workers confirmed; "artists" and "journalists" as victim categories were not found in the fetched source content. Partial confirmation only — not contradicted, but the full category list is unsupported as stated.
Decision: uncorroborated

## Claim 29: body — KISMET: "zero-click exploit transmitted via malicious image files, active from October 2020 to early 2021"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: "The earliest cases of infections we identify in this report were carried out with the KISMET exploit, starting in October 2020. KISMET was a zero-click iOS exploit that appears to have been deployed by NSO Group customers between July and December 2020"; "malicious image files were sent to phones and hijacked control of IMTranscoderAgent".
Comparison: Delivery mechanism and October 2020 start confirmed, but the window end contradicts the source: KISMET deployment ended December 2020 (FORCEDENTRY took over from February 2021). Token "early 2021" has a single correct replacement, "December 2020". Fix location: body § "Zero-click exploits: KISMET and FORCEDENTRY".
Decision: correction

## Claim 30: body — FORCEDENTRY: "zero-click iMessage exploit using malicious PDF files, active from February to November 2021 until Apple patched the vulnerability in iOS 14.8 following Citizen Lab's disclosure to Apple in September 2021"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; https://citizenlab.ca/research/forcedentry-nso-group-imessage-zero-click-exploit-captured-in-the-wild/ (search snippet) ; https://techcrunch.com/2021/09/13/apple-zero-day-nso-pegasus/ (search snippet)
Source tier: primary
Source content: GeckoSpy: FORCEDENTRY deployed February–November 2021, "delivered via iMessage" using "malicious PDF files with JBIG2 streams", "Apple fixed FORCEDENTRY in iOS 14.8"; Citizen Lab "forwarded the artifacts to Apple on Tuesday, September 7 [2021]" and Apple patched on September 13, 2021.
Comparison: Mechanism, active window, patch version, and September 2021 disclosure sequence all confirmed.
Decision: corroborated

## Claim 31: body — "FORCEDENTRY was, at the time of its use, the most sophisticated commercially sold spyware exploit then known; NSO Group had charged governments a premium for access to it"

Source: https://projectzero.google/2021/12/a-deep-dive-into-nso-zero-click.html (search snippet)
Source tier: mainstream
Source content: Google Project Zero "assessed this to be one of the most technically sophisticated exploits they've ever seen."
Comparison: Project Zero's assessment is "one of the most technically sophisticated" — weaker than the body's flat superlative "the most sophisticated... then known" — and no canonical source was found for the claim that NSO charged a premium for FORCEDENTRY access. Partial, paraphrastic support only.
Decision: uncorroborated

## Claim 32: body — "the first technically confirmed documentation of NSO Group's Pegasus... deployed against a Thai civil society population"

Source: https://www.amnesty.org/en/latest/news/2022/07/pegasus-thailand-activists-protests/
Source tier: mainstream
Source content: "the first time its use in the country has been confirmed through technical analysis."
Comparison: Matches; rests on Amnesty's statement alone among fetched sources.
Decision: single-source

## Claim 33: body §Place — "the corpus's first Thailand campaign entry"; "the corpus had campaign entries for Indonesia, the Philippines, and Pakistan"

Source: corpus (mechanical grep of product/entities/)
Source tier: primary
Source content: campaigns directory contains camp-safenet-civil-society-surveillance-indonesia, camp-fma-sim-card-registration-philippines, camp-drf-cyber-harassment-helpline-pakistan; no other Thailand-anchored campaign entity exists.
Comparison: Corpus-internal claims verified mechanically against the corpus itself, which is the authoritative record for them.
Decision: corroborated

## Claim 34: body §Place — reference to "the Apple v. NSO case in US federal court"

Source: https://www.apple.com/newsroom/2021/11/apple-sues-nso-group-to-curb-the-abuse-of-state-sponsored-spyware/ (search snippet) ; https://therecord.media/judge-rejects-nso-effort-to-dismiss-apple-lawsuit (search snippet)
Source tier: primary
Source content: Apple sued NSO Group in November 2021 in US federal court (Northern District of California), with FORCEDENTRY central to the complaint.
Comparison: The embedded public-record fact (such a case exists in US federal court) is confirmed by Apple's own announcement and court coverage; the "structurally distinct" framing is interpretation, not audited.
Decision: corroborated

## Claim 35: body — attribution evidence: infection timing aligned with protest events, court hearings, and arrests; targets of known state interest; Pegasus operator evidence in Thailand "extending back to 2014"

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: "some of the hacking took place shortly before, during, or after protests"; "Benja's device was infected with Pegasus while she was in detention after being arrested on October 7, 2021"; "The first evidence of a Pegasus operator in Thailand we observed dates to May 2014"; 2018 Hide and Seek report identified operator "CHANG" active in Thailand.
Comparison: All three evidence categories and the 2014 historical anchor confirmed; rests on the GeckoSpy report alone.
Decision: primary-sourced

## Claim 36: scalar:sources[0].note — remainder (report authors, Arnon/Jatupat/Jutatip counts, 30 infections Oct 2020–Nov 2021, KISMET/FORCEDENTRY, Amnesty five-case verification, circumstantial attribution)

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
Source tier: primary
Source content: Authors "John Scott-Railton, Bill Marczak, Irene Poetranto, Bahr Abdul Razzak, Sutawan Chanprasert, Ron Deibert"; other figures as quoted in Claims 4, 8, 9, 23, 26, 27.
Comparison: Note accurately describes the cited report's contents except the Panusaya count handled as Claim 19.
Decision: primary-sourced

## Claim 37: scalar:sources[1].note — iLaw page as source for iLaw/DigitalReach co-authorship, Thai reform recommendations, and the March–June 2022 survey

Source: https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/ ; https://www.ilaw.or.th/articles/35057 (search snippet; direct fetch 403)
Source tier: primary
Source content: GeckoSpy: companion report "by iLaw and DigitalReach" titled "The Parasite That Smiles"; iLaw materials: report "written by iLaw and DigitalReach", survey March–June 2022, recommendations to the legislature.
Comparison: The note's claims are confirmed by GeckoSpy plus iLaw's own materials via search index; the cited URL itself 403s on direct fetch but remains live in search indexes.
Decision: corroborated

## Claim 38: scalar:sources[2].note — Amnesty 18 July 2022 piece: five-case verification, moratorium demand, three named acts, names Arnon Nampa, Benja Apan, Panusaya Sithijirawattanakul

Source: https://www.amnesty.org/en/latest/news/2022/07/pegasus-thailand-activists-protests/
Source tier: primary
Source content: "independently confirmed five of the cases"; moratorium and three-act amendment demands as quoted in Claims 5 and 9; "confirms Arnon Nampa, Benja Apan, and Panusaya Sithijirawattanakul (known as Rung) as targets."
Comparison: Note verified directly against the cited article, which is the definitive document for its own contents (and primary for Amnesty's own demands); all elements match.
Decision: primary-sourced

## Claim 39: scalar:sources[3].note — "records Thai government spokesman Thanakorn Wangboonkongchana's denial that the reports were 'untrue' and Digital Economy Minister's statement he could 'guarantee there are no attacks'"

Source: https://www.aljazeera.com/news/2022/7/18/pegasus-malware-targeted-thai-democracy-activists-report ; https://www.usnews.com/news/world/articles/2022-07-22/thai-minister-backtracks-on-spyware-admission-as-government-denies-pegasus-use (Reuters mirror; search snippet)
Source tier: mainstream
Source content: The cited Al Jazeera article states "The Thai government and NSO did not immediately respond to Al Jazeera's requests for comment" and contains neither statement. Reuters coverage: "Government spokesman Thanakorn Wangboonkongchana argued that the report of state-sponsored attacks 'is untrue'... Digital Economy and Society Minister Chaiwut Thanakamanusorn stated in December 2021 that he 'can guarantee there are no attacks on anyone's information.'"
Comparison: Misattribution — both quoted statements are real but come from Reuters coverage (Thanakorn July 2022; Chaiwut December 2021, i.e. pre-dating the reports), not from the cited Al Jazeera article. Fix location: scalar:sources[3].note. The fix requires prose judgment (re-source or trim the note's last clause), beyond a single token replacement — Editor should route to Researcher per its Audit-discrepancy backfill act.
Decision: correction

## Claim 40: scalar:sources[3].note — remainder (names iLaw/DigitalReach/Citizen Lab as co-investigating organisations; names Emilie Pradichit of the Manushya Foundation as a Bangkok human rights commentator)

Source: https://www.aljazeera.com/news/2022/7/18/pegasus-malware-targeted-thai-democracy-activists-report
Source tier: mainstream
Source content: Names "Canadian organization Citizen Lab, and Thai NGOs iLaw and DigitalReach"; quotes Emilie Pradichit, "founder of the Manushya Foundation, a Bangkok-based human rights non-profit."
Comparison: Verified directly against the cited article; matches (the article calls DigitalReach a Thai NGO — a divergence in the source, not in the entity, which is not asserting that here).
Decision: single-source

## Claim 41: scalar:sources[4].note — Manushya post as source for the class action, June 2023 suit, June 2024 mediation with NDA offer, and September 3–5 and 10, 2024 hearings at Ratchada Civil Court

Source: https://www.manushyafoundation.org/post/pai-jatupat-and-the-pegasus-spyware-a-three-year-legal-battle
Source tier: mainstream
Source content: "In November 2022, eight Thai citizens, including Pai, filed a class action lawsuit against NSO Group"; June 2023 nine-agencies suit; "offered a partial settlement with a non-disclosure clause, which Pai rejected"; hearings "from September 3-5 and 10, 2024, at the Ratchada Civil Court in Bangkok."
Comparison: Note verified directly against the cited post; all described contents present.
Decision: single-source

## Claim 42: scalar:sources[5].note — Amnesty 21 November 2024 piece: dismissal, inadequate-forensic-presentation grounds, "critical and alarming setback" characterisation, "won't deter the fight" statement

Source: https://www.amnesty.org/en/latest/news/2024/11/thailand-dismissal-of-landmark-case-a-critical-and-alarming-setback-in-fight-against-unlawful-use-of-spyware/
Source tier: primary
Source content: As quoted in Claim 17 — grounds, title phrase, and "it won't deter the fight against the unlawful use of spyware" all present in the cited piece.
Comparison: Note verified directly against the cited article (primary for Amnesty's own statements); all elements match.
Decision: primary-sourced
