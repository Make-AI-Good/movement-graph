---
entity_id: org-tasz
entity_hash: aaa6bf785b171ce53f20cc3738b0118aeb114cd8
audit_date: 2026-06-11
pass: 2
status: corrections-pending
claims_total: 32
claims_corroborated: 25
claims_primary_sourced: 0
claims_single_source: 1
claims_uncorroborated: 1
open_corrections: 5
sources_consulted:
  - https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
  - https://tasz.hu/en/
  - https://tasz.hu/en/staff-members
  - https://rightscolab.org/case_study/hungarian-civil-liberties-union-tasz/
  - https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
  - https://www.mediadefence.org/news/partner-hclu-spyware/
  - https://www.mediadefence.org/news/spotlight-on-hungary-fighting-back-against-pegasus/
  - https://tasz.hu/en/cikkek/hungarys-new-biometric-surveillance-laws-violate-the-ai-act/
  - https://algorithmwatch.org/en/pridewithpride/
  - https://ecnl.org/news/civil-society-urges-european-commission-uphold-ai-act-hungary
  - https://edri.org/our-work/the-commission-must-uphold-the-ai-act-and-fundamental-freedoms-in-hungary/
  - https://edri.org/about-us/our-network/
  - https://www.biometricupdate.com/202510/hungary-law-permitting-live-facial-recognition-at-outlawed-pride-event-challenged
  - https://www.sigrid-rausing-trust.org/grantee/hungarian-civil-liberties-union/
  - https://www.liberties.eu/en/about/our-network/hungarian-civil-liberties-union
  - https://telex.hu/direkt36/2021/07/19/pegasus-nso-hungary-viktor-orban-cyberweapon
  - https://ipi.media/spying-scandal-further-increases-worries-of-hungarian-journalists/
  - https://en.wikipedia.org/wiki/Pegasus_Project_(investigation)
  - https://tasz.hu/wp-content/uploads/2025/03/Brejza-v.-Lengyelorszag-beavatkozas.pdf
  - https://homodigitalis.gr/en/posts/135143/
---

Pass-2 note: the only entity change since pass 1 (hash a1bc3797) is a frontmatter `related_orgs` addition (`org-iure`) — an ID list, not a prose-bearing scalar, so it carries no new claims. The body is byte-identical to pass 1. Pass 2 re-researched the six pass-1 `uncorroborated` claims (3, 11, 13, 18, 30, 31) with fresh fetches and re-confirmed the two pass-1 corrections (22, 27), which remain open. Carried-forward claims keep their pass-1 records with a `Source tier` line added.

## Claim 1: "TASZ was founded in 1994 by Gábor Attila Tóth"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source tier: tiebreaker
Source content: "Founded 1994" and "Founder Gábor Attila Tóth"
Comparison: Definitional founding-date fact for a named entity; Wikipedia-alone sufficient per source rule. Year and founder name match exactly. Sigrid Rausing Trust grantee page independently confirms "established in Budapest, Hungary in 1994".
Decision: corroborated

## Claim 2: "principal office in central Budapest at Tátra utca 15/b and operational presence in Debrecen, Miskolc, and Pécs"

Source: https://tasz.hu/en/
Source tier: primary
Source content: "HU-1136 Budapest, Tátra utca 15/b." and "3 cities outside Budapest, we are present in: Debrecen, Miskolc, Pécs."
Comparison: Primary source (organisation's own website) confirms exact street address and the three additional cities.
Decision: corroborated

## Claim 3: "Stefánia Kapronczay serves as Executive Director and Máté Dániel Szabó as Director of Programs"

Source: https://tasz.hu/en/staff-members
Source tier: primary
Source content: TASZ's own staff page (fetched this pass) lists "Dalma Dojcsák" as "Executive Director" and "Máté Szabó" as "Director of Programs"; "No, Stefánia Kapronczay is not listed as Executive Director. The role is held by Dalma Dojcsák instead."
Comparison: The body's Executive Director attribution contradicts the entity's own current staff page — the best (primary-tier) source. Wikipedia still names Kapronczay, but living-person role specifics are tiebreaker-only territory and Wikipedia cannot resolve a contradiction; the org's own staff roster governs the present-tense claim. The Director of Programs half (Máté Dániel Szabó / Máté Szabó — same person) is confirmed by the same primary source. Single correct replacement: "Dalma Dojcsák" as Executive Director. Editor fix-targets: body sentence in § Founding and structure; the sources[1].note scalar also attributes "the current Executive Director Stefánia Kapronczay" to Wikipedia — accurate as a description of Wikipedia's (stale) content but worth a Researcher prose-judgment flag alongside the body fix.
Decision: correction

## Claim 4: "roughly forty-staff team complemented by close to one hundred active volunteers"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source tier: tiebreaker
Source content: "staff of about 40" and "volunteer base with close to 100 members"
Comparison: Named-entity formal-structure fact; Wikipedia-alone sufficient. Body paraphrase matches.
Decision: corroborated

## Claim 5: "governed by a five-member Board elected by the General Assembly and supervised by a three-member Supervisory Board"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source tier: tiebreaker
Source content: "five-member Board" and "three-member Surpervisory Board which oversees the legality of HCLU operations"
Comparison: Named-entity formal-structure fact; Wikipedia-alone sufficient. Counts and roles match.
Decision: corroborated

## Claim 6: "strict funding policy ... does not accept any funding from the Hungarian state or its institutions, nor from any political party"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union
Source tier: tiebreaker
Source content: "does not accept any funding by the Hungarian state nor any donation from political parties. Its revenues are from private individuals, companies and private foundations"
Comparison: Definitional / formal-policy fact for named entity. Body paraphrase matches; Wikipedia-alone sufficient.
Decision: corroborated

## Claim 7: "three project areas ... the Equality Project ..., the Privacy Project ..., and the Political Freedoms Project"

Source: https://rightscolab.org/case_study/hungarian-civil-liberties-union-tasz/
Source tier: mainstream
Source content: "Equality Project to protect vulnerable communities from state-level discrimination"; "Privacy Project works to limit state intervention into the private lives of citizens"; "Political Freedoms Project fights against unconstitutional restrictions of citizens' engagement"
Comparison: RightsCoLab case study names all three programmes; Wikipedia independently confirms ("three programmes" structure). Two-source confirmation comfortably clears the canonicality bar.
Decision: corroborated

## Claim 8: "handles approximately 4,500 legal-aid cases annually"

Source: https://tasz.hu/en/
Source tier: primary
Source content: "4500 legal aid cases answered"
Comparison: Primary source (organisation's own website) gives the figure as a single quoted number. Note: Wikipedia gives a lower historical figure ("free legal aid assistance in more than 2500 cases per year") which appears outdated; the body correctly cites the TASZ figure and the frontmatter scalar correctly attributes "2,500+" to Wikipedia. No internal contradiction; both source-respective numbers are accurate.
Decision: corroborated

## Claim 9: "RightsCoLab's 2020 case study recorded over 5,000 legal-aid requests in that single COVID year alongside an additional 3,000-plus pandemic-related inquiries"

Source: https://rightscolab.org/case_study/hungarian-civil-liberties-union-tasz/
Source tier: mainstream
Source content: "responded to over 5,000 requests for legal aid" and "over 3,000 questions about the pandemic"
Comparison: Both figures match the source quotes exactly.
Decision: corroborated

## Claim 10: scalar:sources[2].note — "nearly 50 volunteers contributing 2,500+ hours, over 1,000 private donors plus 2,500+ through the Hungarian 1% tax-designation mechanism"

Source: https://rightscolab.org/case_study/hungarian-civil-liberties-union-tasz/
Source tier: mainstream
Source content: "nearly 50 volunteers contributed more than 2,500 hours"; "over 1,000 private individuals made donations to TASZ"; "over 2,500 contributed money through their taxes"
Comparison: All four 2020 numerical claims in the frontmatter note match the RightsCoLab quoted figures (volunteers, hours, individual donors, tax-designation donors). Editor fix-target if needed: scalar at sources[2].note.
Decision: corroborated

## Claim 11: "In July 2021 the Forbidden Stories Pegasus Project surfaced approximately 300 Hungarian phone numbers in the leaked NSO Group surveillance-targets database, including those of investigative journalists, lawyers, activists, and members of the Hungarian opposition"

Source: https://telex.hu/direkt36/2021/07/19/pegasus-nso-hungary-viktor-orban-cyberweapon
Source tier: mainstream
Source content: "From over 300 leaked Hungarian telephone numbers, we have identified the following Hungarian targets so far:" — the Direkt36 investigation (published on Telex, 19 July 2021) lists four journalists, "a prominent lawyer and an opposition politician", and "a foreign student (Adrien Beauduin) detained during anti-government protests". Wikipedia's Pegasus Project article independently confirms the target categories ("János Bánáti, president of the Hungarian Bar Association, and nine other lawyers"; opposition figures) but does not state the ~300 count.
Comparison: The full claim — count, July 2021 timing, and all four target categories — is confirmed by the originating Direkt36/Telex investigation ("over 300" matches the body's "approximately 300" within paraphrase tolerance). Wikipedia confirms the categories but not the count, so the complete claim rests on one canonical mainstream source. Upgraded from pass-1 uncorroborated (pass 1 checked only the entity's cited sources, which do not cover this).
Decision: single-source

## Claim 12: "announced at a 27 January 2022 press conference"

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: "Created at: 2022. January 27, Thursday"
Comparison: Date matches exactly.
Decision: corroborated

## Claim 13: "six initial clients — Direkt36 journalists Brigitta Csikász, Dávid Dercsényi, and Szabolcs Panyi; photojournalist Dániel Németh; Belgian student activist Adrien Beauduin; and one anonymous targeted individual"

Source: https://ipi.media/spying-scandal-further-increases-worries-of-hungarian-journalists/ and https://telex.hu/direkt36/2021/07/19/pegasus-nso-hungary-viktor-orban-cyberweapon
Source tier: mainstream
Source content: IPI — "Brigitta Csikász, who was working with the investigative website Átlátszó at the time of her surveillance" and "former hvg.hu journalist Dávid Dercsényi"; Telex/Direkt36 — the journalists identified in the leak were "two Direkt36 staff members (Szabolcs Panyi and András Szabó), a former hvg.hu journalist (Dávid Dercsényi), and another investigative journalist who requested anonymity".
Comparison: The six client names match the TASZ announcement (pass 1), but the body's "Direkt36 journalists" grouping of Csikász, Dercsényi, and Panyi is affirmatively contradicted by two canonical mainstream sources: only Panyi is Direkt36; Csikász was at Átlátszó at the time of her surveillance and Dercsényi is a former hvg.hu journalist. TASZ's own announcement calls all four "journalists" generically. The "photojournalist" designation for Németh remains unconfirmed by name in fetched sources (Telex mentions only an unnamed "photographer working with an American journalist"). Upgraded from pass-1 uncorroborated to correction on the affiliation tokens. Editor fix-target: body sentence in § Pegasus and the surveillance-accountability litigation track — the affiliation rewrite (Panyi = Direkt36; Csikász = Átlátszó; Dercsényi = ex-hvg.hu) spans multiple tokens, so likely a Researcher prose-judgment flag rather than a single mechanical replacement.
Decision: correction

## Claim 14: "the litigation team named publicly comprises TASZ surveillance expert Ádám Remport, in-house lawyers Tivadar Hüttl, Flóra Kollarics, and Kata Nehéz-Posony, external Hungarian human-rights counsel Balázs Tóth, and Israeli lawyer Eitay Mack"

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: "TASZ expert on surveillance issues" Ádám Remport; lawyers Tivadar Hüttl, Flóra Kollarics, Kata Nehéz-Posony, Balázs Tóth (human rights lawyer), and Eitay Mack (independent Israeli lawyer)
Comparison: All six named team members appear in the TASZ announcement with the roles the body assigns.
Decision: corroborated

## Claim 15: "domestic track filed proceedings before Hungarian courts, before the National Authority for Data Protection and Freedom of Information (NAIH), before the Parliament's National Security Committee, and before the Commissioner for Fundamental Rights ... international track filed a European Commission complaint ... European Court of Human Rights mass action ... complaint with the Israeli Attorney General"

Source: https://tasz.hu/en/cikkek/pegasus-case-hclu-takes-coordinated-domestic-and-foreign-legal-action/
Source tier: primary
Source content: Hungarian courts, National Authority for Data Protection and Freedom of Information (NAIH), National Security Committee of Parliament, Commissioner for Fundamental Rights, European Commission, European Court of Human Rights (ECtHR), and Israeli Attorney General
Comparison: All seven forums named in the body appear in the TASZ source.
Decision: corroborated

## Claim 16: "European Court of Human Rights mass action on behalf of an expanded set of 36 clients ... that the Court registered in February 2023"

Source: https://www.mediadefence.org/news/partner-hclu-spyware/
Source tier: mainstream
Source content: "HCLU is also planning mass action directly before the European Court of Human Rights on behalf of 36 clients"; "The ECtHR registered the complaints in February 2023."
Comparison: Client count and registration month match exactly.
Decision: corroborated

## Claim 17: "lodged a complaint with the Israeli Attorney General on behalf of three clients"

Source: https://www.mediadefence.org/news/partner-hclu-spyware/
Source tier: mainstream
Source content: "HCLU filed a complaint with the Israeli Attorney General on behalf of three of its clients"
Comparison: Client count matches.
Decision: corroborated

## Claim 18: "TASZ has subsequently intervened in *Brejza v. Poland* before the ECtHR"

Source: https://tasz.hu/wp-content/uploads/2025/03/Brejza-v.-Lengyelorszag-beavatkozas.pdf and https://homodigitalis.gr/en/posts/135143/
Source tier: primary
Source content: TASZ's own site hosts the intervention document (March 2025 upload, filename "Brejza-v.-Lengyelorszag-beavatkozas" = "Brejza v. Poland intervention"), confirmed on fetch as "a third-party intervention submission in the Brejza v. Poland case before the European Court of Human Rights", document title "Brejza 3rd party intervention - submission_final". Homo Digitalis's Pega-Coalition announcement lists "Társaság a Szabadságjogokért (Hungarian Civil Liberties Union)" among the coalition members and states "We have already collaborated with these organizations on related legal actions, such as the successful filing of an amicus curiae intervention in the case of _Brejza and Others v. Poland_".
Comparison: Two independent canonical sources jointly confirm the intervention: the entity's own hosted submission (primary; PDF body text was not machine-extractable in this fetch, so the submitter list rests on the document's title, its hosting on tasz.hu, and the upload context) and the partner organisation's announcement naming TASZ among the coalition that filed the amicus. Upgraded from pass-1 uncorroborated.
Decision: corroborated

## Claim 19: "the Hungarian Parliament passed three connected amendments — to the Assembly Act, the Infraction Act, and the Facial Recognition Technology Act — through Parliament in twenty-four hours without public debate, with the amendments entering into force on 15 April 2025"

Source: https://tasz.hu/en/cikkek/hungarys-new-biometric-surveillance-laws-violate-the-ai-act/ and https://www.biometricupdate.com/202510/hungary-law-permitting-live-facial-recognition-at-outlawed-pride-event-challenged
Source tier: primary
Source content: TASZ — "In March 2025, three amendments aimed to criminalise LGBTQAI+ demonstrations and increase biometric surveillance were rushed through the Hungarian Parliament" "within 24 hours and without any public debate" "entered into force on 15 April"; Biometric Update — names the three amendments as the "Assembly Act, Infraction Act, and Facial Recognition Technology Act"
Comparison: TASZ confirms March 2025 timing, 24-hour passage, no public debate, and 15 April 2025 entry into force; Biometric Update confirms the three named Acts. Two-source confirmation.
Decision: corroborated

## Claim 20: "the prohibition of Article 5(1)(h) of the EU AI Act"

Source: https://tasz.hu/en/cikkek/hungarys-new-biometric-surveillance-laws-violate-the-ai-act/
Source tier: primary
Source content: "Under Article 5(1)(h) of the AI Act, such real-time biometric surveillance is prohibited except in a few narrowly defined cases."
Comparison: Article citation matches the primary source's published legal analysis.
Decision: corroborated

## Claim 21: "TASZ's 29 April 2025 joint legal analysis ... co-published with the Civil Liberties Union for Europe, EDRi, and the European Center for Not-for-Profit Law (ECNL)"

Source: https://tasz.hu/en/cikkek/hungarys-new-biometric-surveillance-laws-violate-the-ai-act/
Source tier: primary
Source content: "The Civil Liberties Union for Europe, EDRi, the European Center for Not-for-Profit Law and the Hungarian Civil Liberties Union believe that this broadened application of FRT ... violates the EU AI Act."
Comparison: Four co-publishers named in the body match the primary source. (Note: TASZ source itself does not stamp the 29 April publication date in the extract; frontmatter scalar for sources[5] and ECNL's cross-reference both attribute 28–29 April publication, within tolerance.)
Decision: corroborated

## Claim 22: "TASZ co-initiated the Pride With Pride! Stop Mass Surveillance at Pride, Stop Face Recognition Now public petition with AlgorithmWatch, EDRi, ECNL, and Liberties"

Source: https://algorithmwatch.org/en/pridewithpride/
Source tier: primary
Source content: "The campaign was initiated by AlgorithmWatch, TASZ Hungarian Civil Liberties Union, European Digital Rights (EDRi), and the European Center for Not-for-profit Law (ECNL)."
Comparison: The petition source names four initiators (AlgorithmWatch, TASZ, EDRi, ECNL); the body lists five (adds Liberties / Civil Liberties Union for Europe). Liberties does not appear as a co-initiator on the AlgorithmWatch petition page. The same five-org list appears in the frontmatter scalar at sources[6].note, so the discrepancy carries through to both surfaces. Editor fix-target: body sentence in § Biometric mass surveillance and the EU AI Act *and* the sources[6].note scalar. REMAINS OPEN at pass 2 — body unchanged since pass 1.
Decision: correction

## Claim 23: "the campaign's three demands (EU Commission investigation and sanctioning of Hungary's violation of European law; joint enforcement of AI and human-rights regulation; complete ban on face-recognition systems in public spaces with no loopholes)"

Source: https://algorithmwatch.org/en/pridewithpride/
Source tier: primary
Source content: "The EU Commission must investigate and sanction the violation of European law"; "The EU must act jointly and decisively to show that it will enforce its own AI and human rights rules"; "Face recognition systems in public spaces must be banned in their entirety!"
Comparison: All three demands paraphrased faithfully.
Decision: corroborated

## Claim 24: "On 28 June 2025 the Budapest Pride parade went ahead despite the police ban and turned into the largest anti-government demonstration in Hungary in years"

Source: https://algorithmwatch.org/en/pridewithpride/ and https://www.biometricupdate.com/202510/hungary-law-permitting-live-facial-recognition-at-outlawed-pride-event-challenged
Source tier: mainstream
Source content: AlgorithmWatch — "On 28 June, the Pride parade will take place in Budapest, Hungary"; Biometric Update — banned Budapest Pride parade "turned into the country's biggest anti-government demonstration in years"
Comparison: Date and characterisation both confirmed by separate canonical sources.
Decision: corroborated

## Claim 25: "On 24 June 2025, nearly fifty civil-society organisations co-signed a letter to the European Commission on biometric surveillance of protesters in Hungary"

Source: https://ecnl.org/news/civil-society-urges-european-commission-uphold-ai-act-hungary
Source tier: primary
Source content: Related news item dated "24-06-2025" titled "The EU must act against biometric surveillance of protesters in Hungary" with framing "ECNL, Hungarian Civil Liberties Union, EDRi, Liberties and nearly 50 CSOs urge the European Commission to protect fundamental rights in Hungary."
Comparison: Date and ~50-org framing both match.
Decision: corroborated

## Claim 26: "On 30 September 2025 TASZ co-signed a joint statement with ECNL and Liberties urging the Commission to uphold the AI Act in Hungary"

Source: https://ecnl.org/news/civil-society-urges-european-commission-uphold-ai-act-hungary
Source tier: primary
Source content: "30-09-2025"; "ECNL, Liberties and the Hungarian Civil Liberties Union" urging Commission action; "real-time remote biometric identification ... in direct breach of Article 5 of the newly adopted AI Act"
Comparison: Date and three co-signers match the source.
Decision: corroborated

## Claim 27: "On 16 October 2025 TASZ, ECNL, Liberties, and EDRi co-signed an open letter making two specific demands — that the Commission launch an infringement procedure against Hungary for AI Act and Charter of Fundamental Rights violations, and that it request an expedited procedure with interim measures from the Court of Justice of the European Union"

Source: https://edri.org/our-work/the-commission-must-uphold-the-ai-act-and-fundamental-freedoms-in-hungary/
Source tier: primary
Source content: Co-signers named on the EDRi page as "European Center for Not-for-Profit Law (ECNL), Liberties, Hungarian Civil Liberties Union" (three orgs), with EDRi as the publishing platform rather than a named co-signer. Demands: "Launch an infringement procedure against Hungary for violations of the AI Act and the Charter of Fundamental Rights" and "request the Court of Justice of the EU (CJEU) to grant interim measures preventing the continued use of these laws pending judgment".
Comparison: The body lists EDRi as a fourth co-signer; the source page lists three co-signers (ECNL, Liberties, HCLU) with EDRi hosting. The frontmatter scalar at sources[8].note correctly describes "EDRi's 16 October 2025 open letter co-signed with ECNL, the Civil Liberties Union for Europe, and TASZ" (three co-signers), so body and frontmatter are internally inconsistent on this point. The two demands themselves match exactly. Editor fix-target: body sentence in § Biometric mass surveillance and the EU AI Act listing four co-signers — either drop EDRi from the co-signer list to match the source and frontmatter, or treat EDRi as publisher. REMAINS OPEN at pass 2 — body unchanged since pass 1.
Decision: correction

## Claim 28: Iwanska quote — "through its silence, the EU signals that governments can ignore essential safeguards for fundamental rights and civic space"

Source: https://edri.org/our-work/the-commission-must-uphold-the-ai-act-and-fundamental-freedoms-in-hungary/
Source tier: primary
Source content: "Through its silence, the EU signals that governments can ignore essential safeguards for fundamental rights and civic space" — Karolina Iwanska, ECNL Digital Rights Advisor
Comparison: Quote matches verbatim; attribution to Iwanska / ECNL matches.
Decision: corroborated

## Claim 29: "long-standing member of two international civil-liberties networks ... INCLO ... (including the American Civil Liberties Union, Liberty in the United Kingdom, and the Canadian Civil Liberties Association) ... Civil Liberties Union for Europe (Liberties), the Berlin-headquartered European network"

Source: https://en.wikipedia.org/wiki/Hungarian_Civil_Liberties_Union and https://www.liberties.eu/en/about/our-network/hungarian-civil-liberties-union
Source tier: primary
Source content: Wikipedia — "member to two international groups ... the International Network of Civil Liberties Organizations (INCLO) and the Civil Liberties Union of Europe (Liberties)"; Liberties — TASZ profiled within the "our-network" path (structural inclusion); Liberties footer address "Hermannstraße 90, 12051 Berlin, Germany"
Comparison: Both memberships and Liberties' Berlin headquarters confirmed. The body's enumeration of INCLO's fellow members (ACLU, Liberty UK, CCLA) is not specifically reproduced in the extracted Wikipedia content but is broadly canonical INCLO membership and is not contradicted; mark partial — primary claims verified, fellow-member list not separately re-verified in this audit pass.
Decision: corroborated

## Claim 30: scalar:sources[11].note — "TASZ's placement inside the Liberties Tech & Rights cluster that explores 'how technology intersects with civil liberties and human rights'"

Source: https://www.liberties.eu/en/about/our-network/hungarian-civil-liberties-union
Source tier: none
Source content: Liberties page lists work areas "Tech & Rights, Democracy & Justice, EU Watch, Training & Coaching, Knowledge Hub, and Reports & Papers" but the extracted page text "provides no information about which thematic cluster HCLU/TASZ occupies." The cluster-placement attribution is not surfaced by the cited page.
Comparison: Liberties' thematic clusters are confirmed by the page; TASZ's specific placement inside the "Tech & Rights" cluster is not stated on the cited page extract. The scalar's specific cluster attribution cannot be confirmed against the cited source.
Decision: uncorroborated

## Claim 31: "TASZ sits inside the EDRi network as an Affiliate (rather than full Member, the status held by Panoptykon Foundation, AlgorithmWatch, Bits of Freedom, La Quadrature du Net, and the Hermes Center)"

Source: https://edri.org/about-us/our-network/
Source tier: primary
Source content: EDRi's own network page (fetched twice this pass, the second with an explicit string-search prompt) lists "Hungarian Civil Liberties Union (Affiliate)", distinguishes "3 ways of being part of EDRi: Members, Affiliates and Observers", and lists Panoptykon, Bits of Freedom, La Quadrature du Net, and HERMES Center as Members — but "AlgorithmWatch does not appear anywhere on this page as a Member, Affiliate, or Observer of the EDRi network." A follow-up search surfaced AlgorithmWatch only as an EDRi "partner" and coalition collaborator, never as a network member.
Comparison: TASZ's Affiliate status and the Member status of Panoptykon, Bits of Freedom, La Quadrature du Net, and Hermes Center are all confirmed by the network's own primary listing — but the body's inclusion of AlgorithmWatch among the full Members is contradicted by that same authoritative complete registry, which does not list AlgorithmWatch in any category. Single correct replacement: drop AlgorithmWatch from the fellow-Member parenthetical (it is an EDRi partner/collaborator, not a network member). Upgraded from pass-1 uncorroborated to correction. Editor fix-target: body sentence in § Coalition work.
Decision: correction

## Claim 32: "Sigrid Rausing Trust has supported TASZ since 2014 under its Human Rights and Rule of Law programme, with historical grants totalling £1,630,000 and a current £240,000 grant period beginning February 2026"

Source: https://www.sigrid-rausing-trust.org/grantee/hungarian-civil-liberties-union/
Source tier: primary
Source content: "Supported since 2014"; "Total of previous grants £1,630,000"; "Current grant £240,000"; "Grant start February 2026"; "Programme Human Rights and Rule of Law"
Comparison: All four numerical / programme facts match the funder's own grantee page exactly.
Decision: corroborated
