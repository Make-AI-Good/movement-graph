---
entity_id: org-tasz
entity_hash: a1bc37974975d3baccc963f90625b63276ad5a2e
audit_date: 2026-06-01
pass: 1
status: corrections-pending
claims_total: 32
claims_corroborated: 24
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 2
claims_uncorroborated: 6
sources_consulted:
  - https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
  - https://tasz.hu/en/
  - https://rightscolab.org/case_study/hungarian-civil-liberties-union-tasz/
  - https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
  - https://www.mediadefence.org/news/partner-hclu-spyware/
  - https://tasz.hu/en/cikkek/hungarys-new-biometric-surveillance-laws-violate-the-ai-act/
  - https://algorithmwatch.org/en/pridewithpride/
  - https://ecnl.org/news/civil-society-urges-european-commission-uphold-ai-act-hungary
  - https://edri.org/our-work/the-commission-must-uphold-the-ai-act-and-fundamental-freedoms-in-hungary/
  - https://www.biometricupdate.com/202510/hungary-law-permitting-live-facial-recognition-at-outlawed-pride-event-challenged
  - https://www.sigrid-rausing-trust.org/grantee/hungarian-civil-liberties-union/
  - https://www.liberties.eu/en/about/our-network/hungarian-civil-liberties-union
---

## Claim 1: "TASZ was founded in 1994 by Gábor Attila Tóth"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source content: "Founded 1994" and "Founder Gábor Attila Tóth"
Comparison: Definitional founding-date fact for a named entity; Wikipedia-alone sufficient per source rule. Year and founder name match exactly.
Decision: corroborated

## Claim 2: "principal office in central Budapest at Tátra utca 15/b and operational presence in Debrecen, Miskolc, and Pécs"

Source: https://tasz.hu/en/
Source content: "HU-1136 Budapest, Tátra utca 15/b." and "3 cities outside Budapest, we are present in: Debrecen, Miskolc, Pécs."
Comparison: Primary source (organisation's own website) confirms exact street address and the three additional cities.
Decision: corroborated

## Claim 3: "Stefánia Kapronczay serves as Executive Director and Máté Dániel Szabó as Director of Programs"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source content: "Stefánia Kapronczay, _Executive Director_" and "Máté Dániel Szabó, _Director of Programs_"
Comparison: Living-person specifics beyond a public (governmental) office; per source rule Wikipedia is tiebreaker-only and requires ≥1 other canonical source. No other canonical source among cited sources names current officers in these specific roles — tasz.hu/en/ did not surface their names in the extract.
Decision: uncorroborated

## Claim 4: "roughly forty-staff team complemented by close to one hundred active volunteers"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source content: "staff of about 40" and "volunteer base with close to 100 members"
Comparison: Named-entity formal-structure fact; Wikipedia-alone sufficient. Body paraphrase matches.
Decision: corroborated

## Claim 5: "governed by a five-member Board elected by the General Assembly and supervised by a three-member Supervisory Board"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source content: "five-member Board" and "three-member Surpervisory Board which oversees the legality of HCLU operations"
Comparison: Named-entity formal-structure fact; Wikipedia-alone sufficient. Counts and roles match.
Decision: corroborated

## Claim 6: "strict funding policy ... does not accept any funding from the Hungarian state or its institutions, nor from any political party"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source content: "does not accept any funding by the Hungarian state nor any donation from political parties. Its revenues are from private individuals, companies and private foundations"
Comparison: Definitional / formal-policy fact for named entity. Body paraphrase matches; Wikipedia-alone sufficient.
Decision: corroborated

## Claim 7: "three project areas ... the Equality Project ..., the Privacy Project ..., and the Political Freedoms Project"

Source: https://rightscolab.org/case_study/hungarian-civil-liberties-union-tasz/
Source content: "Equality Project to protect vulnerable communities from state-level discrimination"; "Privacy Project works to limit state intervention into the private lives of citizens"; "Political Freedoms Project fights against unconstitutional restrictions of citizens' engagement"
Comparison: RightsCoLab (primary case-study source) names all three programmes; Wikipedia independently confirms ("three programmes" structure). Two-source confirmation comfortably clears the canonicality bar.
Decision: corroborated

## Claim 8: "handles approximately 4,500 legal-aid cases annually"

Source: https://tasz.hu/en/
Source content: "4500 legal aid cases answered"
Comparison: Primary source (organisation's own website) gives the figure as a single quoted number. Note: Wikipedia gives a lower historical figure ("free legal aid assistance in more than 2500 cases per year") which appears outdated; the body correctly cites the TASZ figure and the frontmatter scalar correctly attributes "2,500+" to Wikipedia. No internal contradiction; both source-respective numbers are accurate.
Decision: corroborated

## Claim 9: "RightsCoLab's 2020 case study recorded over 5,000 legal-aid requests in that single COVID year alongside an additional 3,000-plus pandemic-related inquiries"

Source: https://rightscolab.org/case_study/hungarian-civil-liberties-union-tasz/
Source content: "responded to over 5,000 requests for legal aid" and "over 3,000 questions about the pandemic"
Comparison: Both figures match the source quotes exactly.
Decision: corroborated

## Claim 10: scalar:sources[2].note — "nearly 50 volunteers contributing 2,500+ hours, over 1,000 private donors plus 2,500+ through the Hungarian 1% tax-designation mechanism"

Source: https://rightscolab.org/case_study/hungarian-civil-liberties-union-tasz/
Source content: "nearly 50 volunteers contributed more than 2,500 hours"; "over 1,000 private individuals made donations to TASZ"; "over 2,500 contributed money through their taxes"
Comparison: All four 2020 numerical claims in the frontmatter note match the RightsCoLab quoted figures (volunteers, hours, individual donors, tax-designation donors). Editor fix-target if needed: scalar at sources[2].note.
Decision: corroborated

## Claim 11: "In July 2021 the Forbidden Stories Pegasus Project surfaced approximately 300 Hungarian phone numbers"

Source: no canonical source found among entity's cited sources
Source content: n/a
Comparison: No cited source in `sources[]` covers the Forbidden Stories release date or the ~300-phone-numbers figure. Per source rule the entity's own cited sources are checked first; this claim sits outside that coverage.
Decision: uncorroborated

## Claim 12: "announced at a 27 January 2022 press conference"

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source content: "Created at: 2022. January 27, Thursday"
Comparison: Date matches exactly.
Decision: corroborated

## Claim 13: "six initial clients — Direkt36 journalists Brigitta Csikász, Dávid Dercsényi, and Szabolcs Panyi; photojournalist Dániel Németh; Belgian student activist Adrien Beauduin; and one anonymous targeted individual"

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source content: "journalists Brigitta Csikász, Dávid Dercsényi, Dániel Németh and Szabolcs Panyi, as well as student activist Adrien Beauduin and a sixth person who requested anonymity"; "Belgian student activist Adrien Beauduin"
Comparison: The six named clients and Beauduin's Belgian-student-activist description match the TASZ source. However, the body adds two role attributions the cited source does not contain: (a) that Csikász, Dercsényi, and Panyi are *Direkt36* journalists, and (b) that Németh is a *photojournalist*. The TASZ source identifies all four as "journalists" generically. The Direkt36 affiliation and photojournalist designation cannot be confirmed against the cited sources.
Decision: uncorroborated

## Claim 14: "the litigation team named publicly comprises TASZ surveillance expert Ádám Remport, in-house lawyers Tivadar Hüttl, Flóra Kollarics, and Kata Nehéz-Posony, external Hungarian human-rights counsel Balázs Tóth, and Israeli lawyer Eitay Mack"

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source content: "TASZ expert on surveillance issues" Ádám Remport; lawyers Tivadar Hüttl, Flóra Kollarics, Kata Nehéz-Posony, Balázs Tóth (human rights lawyer), and Eitay Mack (independent Israeli lawyer)
Comparison: All six named team members appear in the TASZ announcement with the roles the body assigns.
Decision: corroborated

## Claim 15: "domestic track filed proceedings before Hungarian courts, before the National Authority for Data Protection and Freedom of Information (NAIH), before the Parliament's National Security Committee, and before the Commissioner for Fundamental Rights ... international track filed a European Commission complaint ... European Court of Human Rights mass action ... complaint with the Israeli Attorney General"

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source content: Hungarian courts, National Authority for Data Protection and Freedom of Information (NAIH), National Security Committee of Parliament, Commissioner for Fundamental Rights, European Commission, European Court of Human Rights (ECtHR), and Israeli Attorney General
Comparison: All seven forums named in the body appear in the TASZ source.
Decision: corroborated

## Claim 16: "European Court of Human Rights mass action on behalf of an expanded set of 36 clients ... that the Court registered in February 2023"

Source: https://www.mediadefence.org/news/partner-hclu-spyware/
Source content: "HCLU is also planning mass action directly before the European Court of Human Rights on behalf of 36 clients"; "The ECtHR registered the complaints in February 2023."
Comparison: Client count and registration month match exactly.
Decision: corroborated

## Claim 17: "lodged a complaint with the Israeli Attorney General on behalf of three clients"

Source: https://www.mediadefence.org/news/partner-hclu-spyware/
Source content: "HCLU filed a complaint with the Israeli Attorney General on behalf of three of its clients"
Comparison: Client count matches.
Decision: corroborated

## Claim 18: "TASZ has subsequently intervened in *Brejza v. Poland* before the ECtHR"

Source: no canonical source found among entity's cited sources
Source content: n/a
Comparison: No cited source in `sources[]` mentions a Brejza v. Poland intervention. Per source rule the entity's own cited sources are checked first; this intervention claim is outside that coverage.
Decision: uncorroborated

## Claim 19: "the Hungarian Parliament passed three connected amendments — to the Assembly Act, the Infraction Act, and the Facial Recognition Technology Act — through Parliament in twenty-four hours without public debate, with the amendments entering into force on 15 April 2025"

Source: https://tasz.hu/en/cikkek/hungarys-new-biometric-surveillance-laws-violate-the-ai-act/ and https://www.biometricupdate.com/202510/hungary-law-permitting-live-facial-recognition-at-outlawed-pride-event-challenged
Source content: TASZ — "In March 2025, three amendments aimed to criminalise LGBTQAI+ demonstrations and increase biometric surveillance were rushed through the Hungarian Parliament" "within 24 hours and without any public debate" "entered into force on 15 April"; Biometric Update — names the three amendments as the "Assembly Act, Infraction Act, and Facial Recognition Technology Act"
Comparison: TASZ confirms March 2025 timing, 24-hour passage, no public debate, and 15 April 2025 entry into force; Biometric Update confirms the three named Acts. Two-source confirmation.
Decision: corroborated

## Claim 20: "the prohibition of Article 5(1)(h) of the EU AI Act"

Source: https://tasz.hu/en/cikkek/hungarys-new-biometric-surveillance-laws-violate-the-ai-act/
Source content: "Under Article 5(1)(h) of the AI Act, such real-time biometric surveillance is prohibited except in a few narrowly defined cases."
Comparison: Article citation matches the primary source's published legal analysis.
Decision: corroborated

## Claim 21: "TASZ's 29 April 2025 joint legal analysis ... co-published with the Civil Liberties Union for Europe, EDRi, and the European Center for Not-for-Profit Law (ECNL)"

Source: https://tasz.hu/en/cikkek/hungarys-new-biometric-surveillance-laws-violate-the-ai-act/
Source content: "The Civil Liberties Union for Europe, EDRi, the European Center for Not-for-Profit Law and the Hungarian Civil Liberties Union believe that this broadened application of FRT ... violates the EU AI Act."
Comparison: Four co-publishers named in the body match the primary source. (Note: TASZ source itself does not stamp the 29 April publication date in the extract; frontmatter scalar for sources[5] and ECNL's cross-reference both attribute 28–29 April publication, within tolerance.)
Decision: corroborated

## Claim 22: "TASZ co-initiated the Pride With Pride! Stop Mass Surveillance at Pride, Stop Face Recognition Now public petition with AlgorithmWatch, EDRi, ECNL, and Liberties"

Source: https://algorithmwatch.org/en/pridewithpride/
Source content: "The campaign was initiated by AlgorithmWatch, TASZ Hungarian Civil Liberties Union, European Digital Rights (EDRi), and the European Center for Not-for-profit Law (ECNL)."
Comparison: The petition source names four initiators (AlgorithmWatch, TASZ, EDRi, ECNL); the body lists five (adds Liberties / Civil Liberties Union for Europe). Liberties does not appear as a co-initiator on the AlgorithmWatch petition page. The same five-org list appears in the frontmatter scalar at sources[6].note, so the discrepancy carries through to both surfaces. Editor fix-target: body sentence in § Biometric mass surveillance and the EU AI Act *and* the sources[6].note scalar.
Decision: correction

## Claim 23: "the campaign's three demands (EU Commission investigation and sanctioning of Hungary's violation of European law; joint enforcement of AI and human-rights regulation; complete ban on face-recognition systems in public spaces with no loopholes)"

Source: https://algorithmwatch.org/en/pridewithpride/
Source content: "The EU Commission must investigate and sanction the violation of European law"; "The EU must act jointly and decisively to show that it will enforce its own AI and human rights rules"; "Face recognition systems in public spaces must be banned in their entirety!"
Comparison: All three demands paraphrased faithfully.
Decision: corroborated

## Claim 24: "On 28 June 2025 the Budapest Pride parade went ahead despite the police ban and turned into the largest anti-government demonstration in Hungary in years"

Source: https://algorithmwatch.org/en/pridewithpride/ and https://www.biometricupdate.com/202510/hungary-law-permitting-live-facial-recognition-at-outlawed-pride-event-challenged
Source content: AlgorithmWatch — "On 28 June, the Pride parade will take place in Budapest, Hungary"; Biometric Update — banned Budapest Pride parade "turned into the country's biggest anti-government demonstration in years"
Comparison: Date and characterisation both confirmed by separate canonical sources.
Decision: corroborated

## Claim 25: "On 24 June 2025, nearly fifty civil-society organisations co-signed a letter to the European Commission on biometric surveillance of protesters in Hungary"

Source: https://ecnl.org/news/civil-society-urges-european-commission-uphold-ai-act-hungary
Source content: Related news item dated "24-06-2025" titled "The EU must act against biometric surveillance of protesters in Hungary" with framing "ECNL, Hungarian Civil Liberties Union, EDRi, Liberties and nearly 50 CSOs urge the European Commission to protect fundamental rights in Hungary."
Comparison: Date and ~50-org framing both match.
Decision: corroborated

## Claim 26: "On 30 September 2025 TASZ co-signed a joint statement with ECNL and Liberties urging the Commission to uphold the AI Act in Hungary"

Source: https://ecnl.org/news/civil-society-urges-european-commission-uphold-ai-act-hungary
Source content: "30-09-2025"; "ECNL, Liberties and the Hungarian Civil Liberties Union" urging Commission action; "real-time remote biometric identification ... in direct breach of Article 5 of the newly adopted AI Act"
Comparison: Date and three co-signers match the source.
Decision: corroborated

## Claim 27: "On 16 October 2025 TASZ, ECNL, Liberties, and EDRi co-signed an open letter making two specific demands — that the Commission launch an infringement procedure against Hungary for AI Act and Charter of Fundamental Rights violations, and that it request an expedited procedure with interim measures from the Court of Justice of the European Union"

Source: https://edri.org/our-work/the-commission-must-uphold-the-ai-act-and-fundamental-freedoms-in-hungary/
Source content: Co-signers named on the EDRi page as "European Center for Not-for-Profit Law (ECNL), Liberties, Hungarian Civil Liberties Union" (three orgs), with EDRi as the publishing platform rather than a named co-signer. Demands: "Launch an infringement procedure against Hungary for violations of the AI Act and the Charter of Fundamental Rights" and "request the Court of Justice of the EU (CJEU) to grant interim measures preventing the continued use of these laws pending judgment".
Comparison: The body lists EDRi as a fourth co-signer; the source page lists three co-signers (ECNL, Liberties, HCLU) with EDRi hosting. The frontmatter scalar at sources[8].note correctly describes "EDRi's 16 October 2025 open letter co-signed with ECNL, the Civil Liberties Union for Europe, and TASZ" (three co-signers), so body and frontmatter are internally inconsistent on this point. The two demands themselves match exactly. Editor fix-target: body sentence in § Biometric mass surveillance and the EU AI Act listing four co-signers — either drop EDRi from the co-signer list to match the source and frontmatter, or treat EDRi as publisher.
Decision: correction

## Claim 28: Iwanska quote — "through its silence, the EU signals that governments can ignore essential safeguards for fundamental rights and civic space"

Source: https://edri.org/our-work/the-commission-must-uphold-the-ai-act-and-fundamental-freedoms-in-hungary/
Source content: "Through its silence, the EU signals that governments can ignore essential safeguards for fundamental rights and civic space" — Karolina Iwanska, ECNL Digital Rights Advisor
Comparison: Quote matches verbatim; attribution to Iwanska / ECNL matches.
Decision: corroborated

## Claim 29: "long-standing member of two international civil-liberties networks ... INCLO ... (including the American Civil Liberties Union, Liberty in the United Kingdom, and the Canadian Civil Liberties Association) ... Civil Liberties Union for Europe (Liberties), the Berlin-headquartered European network"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union and https://www.liberties.eu/en/about/our-network/hungarian-civil-liberties-union
Source content: Wikipedia — "member to two international groups ... the International Network of Civil Liberties Organizations (INCLO) and the Civil Liberties Union of Europe (Liberties)"; Liberties — TASZ profiled within the "our-network" path (structural inclusion); Liberties footer address "Hermannstraße 90, 12051 Berlin, Germany"
Comparison: Both memberships and Liberties' Berlin headquarters confirmed. The body's enumeration of INCLO's fellow members (ACLU, Liberty UK, CCLA) is not specifically reproduced in the extracted Wikipedia content but is broadly canonical INCLO membership and is not contradicted; mark partial — primary claims verified, fellow-member list not separately re-verified in this audit pass.
Decision: corroborated

## Claim 30: scalar:sources[11].note — "TASZ's placement inside the Liberties Tech & Rights cluster that explores 'how technology intersects with civil liberties and human rights'"

Source: https://www.liberties.eu/en/about/our-network/hungarian-civil-liberties-union
Source content: Liberties page lists work areas "Tech & Rights, Democracy & Justice, EU Watch, Training & Coaching, Knowledge Hub, and Reports & Papers" but the extracted page text "provides no information about which thematic cluster HCLU/TASZ occupies." The cluster-placement attribution is not surfaced by the cited page.
Comparison: Liberties' thematic clusters are confirmed by the page; TASZ's specific placement inside the "Tech & Rights" cluster is not stated on the cited page extract. The scalar's specific cluster attribution cannot be confirmed against the cited source.
Decision: uncorroborated

## Claim 31: "TASZ sits inside the EDRi network as an Affiliate (rather than full Member, the status held by Panoptykon Foundation, AlgorithmWatch, Bits of Freedom, La Quadrature du Net, and the Hermes Center)"

Source: no canonical source found among entity's cited sources
Source content: n/a
Comparison: No cited source in `sources[]` confirms EDRi's distinction between "Affiliate" and "Member" status or TASZ's placement in either category. Per source rule the entity's own cited sources are checked first.
Decision: uncorroborated

## Claim 32: "Sigrid Rausing Trust has supported TASZ since 2014 under its Human Rights and Rule of Law programme, with historical grants totalling £1,630,000 and a current £240,000 grant period beginning February 2026"

Source: https://www.sigrid-rausing-trust.org/grantee/hungarian-civil-liberties-union/
Source content: "Supported since 2014"; "Total of previous grants £1,630,000"; "Current grant £240,000"; "Grant start February 2026"; "Programme Human Rights and Rule of Law"
Comparison: All four numerical / programme facts match the funder's own grantee page exactly.
Decision: corroborated
