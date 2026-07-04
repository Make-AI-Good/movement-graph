---
entity_id: camp-amnesty-ban-the-scan-facial-recognition-2020-ongoing
entity_hash: 8fd63d47a1ea3b2fcc90c166b2520ef486ce12d4
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 25
claims_corroborated: 6
claims_primary_sourced: 10
claims_single_source: 0
claims_uncorroborated: 6
open_corrections: 3
sources_consulted:
  - https://banthescan.amnesty.org/
  - https://banthescan.amnesty.org/decode/
  - https://banthescan.amnesty.org/nyc/index.html
  - https://banthescan.amnesty.org/opt/
  - https://www.amnesty.org/en/latest/press-release/2021/01/ban-dangerous-facial-recognition-technology-that-amplifies-racist-policing/
  - https://www.amnesty.org/en/latest/news/2021/05/decode-surveillance-nyc-launches/
  - https://www.amnesty.org/en/latest/news/2021/06/scale-new-york-police-facial-recognition-revealed/
  - https://www.amnesty.org/en/latest/news/2021/11/india-hyderabad-on-the-brink-of-becoming-a-total-surveillance-city/
  - https://www.amnesty.org/en/latest/news/2022/02/usa-facial-recognition-technology-reinforcing-racist-stop-and-frisk-policing-in-new-york-new-research/
  - https://www.amnesty.org/en/latest/news/2022/08/usa-nypd-black-lives-matter-protests-surveilliance/
  - https://www.amnesty.org/en/latest/news/2023/05/israel-opt-israeli-authorities-are-using-facial-recognition-technology-to-entrench-apartheid/
  - https://www.amnesty.org/en/latest/news/2025/11/amnesty-and-s-t-o-p-reveal-nypd-surveillance-abuses/
  - https://www.amnesty.org/en/petition/ban-the-scan-petition/
  - https://citizenevidence.org/2021/09/09/decode-surveillance-nyc/
  - https://dig.watch/updates/amnesty-international-and-other-ngos-calls-ban-facial-recognition-technologies-new-york
  - https://www.accessnow.org/campaign/ban-biometric-surveillance/
  - https://en.wikipedia.org/wiki/Police_surveillance_in_New_York_City
  - https://www.brennancenter.org/our-work/research-reports/public-oversight-surveillance-technology-post-act-resource-page
  - https://www.nysenate.gov/legislation/bills/2021/S79
  - https://queenseagle.com/all/new-city-law-compels-nypd-to-explain-surveillance-tools-and-strategies
  - https://thewire.in/law/telangana-hc-issues-notice-on-pil-challenging-use-of-facial-recognition-technology
  - https://maktoobmedia.com/india/activist-moves-telangana-hc-indias-first-legal-challenge-to-facial-recognition-technology/
  - https://gothamist.com/news/nypd-used-facial-recognition-unit-in-siege-of-black-lives-matter-activists-apartment
  - https://www.statewatch.org/news/2021/june/the-potential-for-abuse-is-too-great-global-call-to-ban-biometric-surveillance-in-public-spaces/
---

## Claim 1: edge lead_orgs / participating_orgs → org-amnesty-international ("Amnesty International's sustained multi-jurisdiction campaign")

Source: https://banthescan.amnesty.org/ + https://www.amnesty.org/en/latest/press-release/2021/01/ban-dangerous-facial-recognition-technology-that-amplifies-racist-policing/
Source tier: primary
Source content: Campaign hub is an Amnesty International property ("© 2022 AMNESTY INTERNATIONAL"); launch press release is Amnesty's own. dig.watch (26 Jan 2021) independently attributes the campaign to Amnesty International.
Comparison: Edge resolves to existing entity file; campaign leadership confirmed by Amnesty primary sources and independent coverage.
Decision: corroborated

## Claim 2: start_date 2021-01-26; "Launched on 26 January 2021 in New York City"

Source: https://www.amnesty.org/en/latest/press-release/2021/01/ban-dangerous-facial-recognition-technology-that-amplifies-racist-policing/
Source tier: primary
Source content: Press release dated 26 January 2021; first target city New York City. dig.watch coverage also dated January 26, 2021.
Comparison: start_date scalar and body launch date/place match the primary source and independent coverage exactly.
Decision: corroborated

## Claim 3: launch coalition membership (S.T.O.P., EFF, NYCLU, Legal Aid Society, National Action Network, Warriors In The Garden, Immigrant Defense Project, Jumaane Williams, Brad Hoylman); edges → org-electronic-frontier-foundation, org-aclu

Source: https://www.amnesty.org/en/latest/press-release/2021/01/ban-dangerous-facial-recognition-technology-that-amplifies-racist-policing/ + https://dig.watch/updates/amnesty-international-and-other-ngos-calls-ban-facial-recognition-technologies-new-york
Source tier: primary
Source content: dig.watch: "Amnesty International, the Surveillance Technology Oversight Project (S.T.O.P.), New York City Public Advocate Jumaane Williams, New York State Senator Brad Hoylman, Legal Aid Society, National Action Network, Warriors In The Garden, Immigrant Defense Project, New York Civil Liberties Union, the Electronic Frontier Foundation and other advocates." Amnesty launch PR names AI for the People, S.T.O.P., Immigrant Defence Project, NYCLU, Public Advocate's office, Privacy NY Coalition, Hoylman, Rada Studios.
Comparison: Every named coalition member in body § Launch is confirmed across the two sources. The participating_orgs edge for NYCLU points to org-aclu (NYCLU is the ACLU's New York affiliate) — a defensible mapping; body link text says NYCLU. Cited amnestyusa.org coalition release (sources[2]) returns HTTP 403 to this harness; membership verified via the two sources above instead.
Decision: corroborated

## Claim 4: legislative demands — NY State Senate Bill S79 and an NYC Council ban; demand is categorical prohibition, not regulation (goals scalar + body § Launch)

Source: https://dig.watch/updates/amnesty-international-and-other-ngos-calls-ban-facial-recognition-technologies-new-york + https://www.nysenate.gov/legislation/bills/2021/S79
Source tier: primary
Source content: dig.watch: state level "Senate Bill S79" to "ban law enforcement use of biometric surveillance technology, including facial recognition"; city level a ban on facial recognition use by city agencies ("the New York City Council has not yet introduced such a bill"). NY Senate: S79 (2021, Hoylman) "prohibiting the use of biometric surveillance technology by law enforcement." Amnesty launch PR: "a total ban on the use, development, production, and sale, of facial recognition technology for mass surveillance purposes by the police and other government agencies."
Comparison: S79 exists as described (government record), was the named state-level ask, and the NYC Council + NY State two-track demand and categorical "total ban" framing match the sources.
Decision: corroborated

## Claim 5: campaign hub tagline verbatim ("Your face is being tracked. Find out where. Help ban facial recognition technology.") and three named geographic jurisdictions (NYC, Hyderabad, OPT) (body + scalar:sources[0].note)

Source: https://banthescan.amnesty.org/
Source tier: primary
Source content: Tagline rendered verbatim on the hub: "Your face is being tracked. Find out where. Help ban facial recognition technology." Page names New York City, Hyderabad, and the Occupied Palestinian Territories as the three regional focuses.
Comparison: Tagline and three-jurisdiction structure match the live hub exactly. Only the entity's own site can attest its own tagline — single primary source is the natural ceiling here.
Decision: primary-sourced

## Claim 6: "the Public Oversight of Surveillance Technology Act, signed into New York City law in June 2020" (body § Launch)

Source: https://queenseagle.com/all/new-city-law-compels-nypd-to-explain-surveillance-tools-and-strategies + https://en.wikipedia.org/wiki/Police_surveillance_in_New_York_City
Source tier: mainstream
Source content: "On July 15, 2020, then-Mayor Bill de Blasio signed the Public Oversight of Surveillance Technology ('POST') Act into law." Wikipedia/Brennan Center: "On June 18, 2020 the New York City Council voted 44–6 to enact the... POST Act."
Comparison: The POST Act was passed by the Council in June 2020 but signed into law 15 July 2020. Body token "signed into New York City law in June 2020" contradicts the source; single-token fix: "June 2020" → "July 2020" (or reword to "passed by the City Council in June 2020").
Decision: correction

## Claim 7: campaign website launched with "a POST Act public comment portal" (body § Launch; scalar:sources[0].note "the POST Act public comment portal"; scalar:sources[3].note "the POST Act public comment process it served")

Source: https://banthescan.amnesty.org/ + https://banthescan.amnesty.org/nyc/index.html + https://www.amnesty.org/en/latest/news/2021/05/decode-surveillance-nyc-launches/
Source tier: none
Source content: No fetched page mentions a POST Act comment portal. Hub fetch: "No mention of a POST Act public comment portal appears in the provided content." NYC page fetch: "The webpage contains no information about a POST Act comment portal." May 2021 Decode release fetch: "The document makes no mention of the POST Act or any public comment process."
Comparison: The portal plausibly existed on the 2021-era site (the POST Act comment period ran early 2021) but no page fetched this session carries it, and the Internet Archive is not reachable from this harness. The two sources[].note scalars (sources[0].note, sources[3].note) attribute the portal / POST Act process to pages that do not currently carry it. Cannot confirm or refute a historical page state — the audit reaches its limit here.
Decision: uncorroborated

## Claim 8: Derrick "Dwreck" Ingram — August 2020 NYPD siege of his apartment "for five hours" after apparent facial-recognition identification (body § Launch)

Source: https://banthescan.amnesty.org/nyc/index.html + https://gothamist.com/news/nypd-used-facial-recognition-unit-in-siege-of-black-lives-matter-activists-apartment
Source tier: primary
Source content: Amnesty NYC page: "Dwreck recounts how the NYPD brought dozens of officers, a helicopter, riot police, and police dogs in a five-hour-long attempt to arrest him." Gothamist reporting (via search): "after six tense hours of over 100 onlookers live-streaming... NYPD Commissioner Dermot Shea called off the operation"; NYPD "confirmed that facial recognition software was used during the course of the investigation"; raid dated August 7, 2020.
Comparison: The incident, its August 2020 date, and NYPD facial-recognition use are solidly sourced (Amnesty primary + Gothamist mainstream). The duration token conflicts: Amnesty says five hours, Gothamist says six. Canonical sources disagree — no winner picked. The body's "five hours" follows Amnesty's own framing; not asserted as error.
Decision: uncorroborated

## Claim 9: Decode Surveillance NYC launched May 2021 through Amnesty Decoders; volunteers classified street-level imagery to identify FRT-compatible cameras at NYC traffic intersections (body § Decode)

Source: https://www.amnesty.org/en/latest/news/2021/05/decode-surveillance-nyc-launches/ + https://citizenevidence.org/2021/09/09/decode-surveillance-nyc/
Source tier: primary
Source content: May 2021 release (dated May 4, 2021): "The ambitious project is the latest for the ground-breaking Amnesty Decoders, which sees a global community of digital activists participate in research through crowdsourcing data-driven projects"; volunteers "transported to different intersections across the city's five boroughs to tag and classify cameras." Citizen Evidence Lab: volunteers examined camera locations "using Google Street View imagery."
Comparison: Launch month, Decoders platform, and methodology match. Both confirming sources are Amnesty properties, so not independent of each other.
Decision: primary-sourced

## Claim 10: "The project enrolled more than 7,000 volunteers from 144 countries" (body § Decode; also outcomes scalar)

Source: https://citizenevidence.org/2021/09/09/decode-surveillance-nyc/ + https://www.amnesty.org/en/latest/news/2021/06/scale-new-york-police-facial-recognition-revealed/
Source tier: primary
Source content: Citizen Evidence Lab title: "How We Enrolled Seven Thousand Volunteers to Generate Data the NYPD Wouldn't Publish." June 2021 release: "It was a global effort – volunteers from 144 countries participated, with the largest group of volunteers (26%) being in the United States."
Comparison: Both tokens confirmed on Amnesty primary sources. Note the June 2021 release itself says "More than 5,500 volunteers have participated" — 7,000+ is the project's final count (per Citizen Evidence Lab, Sept 2021), so pairing 7,000+ with the June 2021 15,280-camera tally is a mild compression, not an error.
Decision: primary-sourced

## Claim 11: June 2021 Surveillance City findings — NYPD can use more than 15,000 cameras for FRT; 15,280 cameras tagged across Manhattan (3,590), Brooklyn (8,220), the Bronx (3,470); predominantly Argus cameras (body §§ Decode/June 2021; outcomes scalar)

Source: https://www.amnesty.org/en/latest/news/2021/06/scale-new-york-police-facial-recognition-revealed/
Source tier: primary
Source content: "Thousands of volunteers from around the world participated in the investigation, tagging 15,280 surveillance cameras at intersections across Manhattan (3,590), Brooklyn (8,220) and the Bronx (3,470)." Title: "NYPD can use more than 15,000 cameras to track people using facial recognition." Amnesty's Decode story: routes "mostly NYPD Argus cameras."
Comparison: All counts and the borough split match the June 2021 primary source exactly. NOTE for cross-reference: the body's February 2022 paragraph reuses these same figures with wrong attribution — see Claim 13.
Decision: primary-sourced

## Claim 12: "The [June 2021] report calculated that protesters marching to and from BLM protest sites at Times Square, the Theatre District, Washington Square Park, and Barclays Center during mid-2020 would have faced up to 100% coverage" (body § Decode/June 2021; scalar:sources[4].note "up to 100% FRT camera coverage on routes marched by BLM protesters..."; outcomes scalar "near-total FRT exposure on BLM march routes")

Source: https://banthescan.amnesty.org/decode/ + https://www.amnesty.org/en/latest/news/2021/06/scale-new-york-police-facial-recognition-revealed/
Source tier: primary
Source content: Amnesty's "Inside the NYPD's Surveillance Machine" story: "a protester marching in Times Square would have risked surveillance via facial recognition for 100% of their route"; Washington Square Park "surveilled for approximately 100% of their journey"; Barclays Center "approximately 95% of the route sampled." But the June 2021 amnesty.org release itself, on two targeted fetches, carries no route-coverage percentages and does not name Times Square/Theatre District/Barclays Center.
Comparison: The substance (up-to-100% route coverage at the named sites) is real and published by Amnesty — but in the later "Inside the NYPD's Surveillance Machine" story (which uses the post-Feb-2022 25,500-camera dataset), not verifiably in the June 2021 report the body and sources[4].note attribute it to. The amnestyusa.org mirror of the June 2021 release (which may carry the route analysis) returns HTTP 403. Attribution unverifiable; substance not in question.
Decision: uncorroborated

## Claim 13: "A February 2022 research report drew on the full Decode Surveillance NYC dataset — 15,280 cameras catalogued across traffic intersections in Manhattan (3,590), Brooklyn (8,220), and the Bronx (3,470)" (body § Racial disparities; scalar:sources[5].note "the Amnesty Decoders count of 15,280 cameras tagged by 7,000+ volunteers from 144 countries")

Source: https://www.amnesty.org/en/latest/news/2022/02/usa-facial-recognition-technology-reinforcing-racist-stop-and-frisk-policing-in-new-york-new-research/
Source tier: primary
Source content: Feb 2022 release: "The findings are based on crowdsourced data obtained by thousands of digital volunteers as part of the Decode Surveillance NYC project, who mapped more than 25,500 CCTV cameras across New York City." Targeted fetch confirms 15,280, the borough counts, 7,000, and 144 do NOT appear on the Feb 2022 page.
Comparison: The full Decode Surveillance NYC dataset behind the February 2022 research is 25,500+ cameras across all of New York City; 15,280 (Manhattan 3,590 / Brooklyn 8,220 / Bronx 3,470) is the June 2021 three-borough tally (see Claim 11) — the Feb 2022 analysis also covers Queens, which the 15,280 set excludes. Token fix in body: "15,280 cameras... Manhattan (3,590), Brooklyn (8,220), and the Bronx (3,470)" → "more than 25,500 cameras across New York City" — but the sentence's borough parentheticals make this a prose-judgment fix, and scalar:sources[5].note needs its 15,280/7,000+/144 attribution rewritten (those figures belong to the June 2021 release and Citizen Evidence Lab). Route via Editor flag to Researcher.
Decision: correction

## Claim 14: February 2022 finding — FRT-compatible camera concentration in the Bronx, Brooklyn, and Queens correlates with proportion of non-white residents and with stop-and-frisk risk (body § Racial disparities; outcomes scalar)

Source: https://www.amnesty.org/en/latest/news/2022/02/usa-facial-recognition-technology-reinforcing-racist-stop-and-frisk-policing-in-new-york-new-research/
Source tier: primary
Source content: "In the Bronx, Brooklyn and Queens, the research also showed that the higher the proportion of non-white residents, the higher the concentration of facial recognition compatible CCTV cameras." Also: "New Yorkers living in areas at greater risk of stop-and-frisk by police are also more exposed to invasive facial recognition technology."
Comparison: Boroughs, correlation direction, and stop-and-frisk linkage match the primary source exactly.
Decision: primary-sourced

## Claim 15: July 2021 — Amnesty International and S.T.O.P. sued the NYPD under New York's Freedom of Information Law; August 2022 — New York Supreme Court (New York County) ordered disclosure of more than 2,700 records on BLM protest surveillance (body § Strategic litigation; outcomes scalar)

Source: https://www.amnesty.org/en/latest/news/2022/08/usa-nypd-black-lives-matter-protests-surveilliance/
Source tier: primary
Source content: Court ordered the NYPD to share "2700 of documents and emails between March 1, 2020, to September 1, 2020, related to procurement and usage of facial recognition surveillance at the BLM protests" (Justice Laurence Love, ruling reported 1 August 2022). "Amnesty International USA and the Surveillance Technology Oversight Project (S.T.O.P.) filed the Article 78 lawsuit"; records request September 2020 under FOIL; "the lawsuit was announced in July 2021."
Comparison: Filing parties, July 2021 date, FOIL basis, August 2022 order, and 2,700+ records all match. Confirmed on Amnesty's own page (co-plaintiff S.T.O.P.'s page corroborates per search results but was not fetched).
Decision: primary-sourced

## Claim 16: November 2025 — further Amnesty/S.T.O.P. investigation revealed new NYPD surveillance abuses from the disclosure process; litigation track remains active (body § Strategic litigation; outcomes scalar)

Source: https://www.amnesty.org/en/latest/news/2025/11/amnesty-and-s-t-o-p-reveal-nypd-surveillance-abuses/
Source tier: primary
Source content: Dated November 13, 2025: "Records obtained by Amnesty International and the Surveillance Technology Oversight Project (S.T.O.P.)... after a five-year long lawsuit against the New York Police Department (NYPD) reveal concerning surveillance abuses." References the 2022 court order compelling release of over 2,700 documents.
Comparison: Date, parties, and lawsuit lineage match the primary source.
Decision: primary-sourced

## Claim 17: India phase — November 2021, three-organisation partnership (Amnesty + Internet Freedom Foundation + ARTICLE 19), targeting the Command and Control Centre in Hyderabad designed for data from up to 600,000 cameras; edges → org-internet-freedom-foundation, org-article-19 (body § India phase; outcomes scalar)

Source: https://www.amnesty.org/en/latest/news/2021/11/india-hyderabad-on-the-brink-of-becoming-a-total-surveillance-city/
Source tier: primary
Source content: Release dated 9 November 2021, "an update to the ongoing Ban The Scan campaign"; research by Amnesty International, Internet Freedom Foundation, and ARTICLE 19; the CCC in Hyderabad's Banjara Hills "will reportedly support the processing of data from up to 600,000 cameras at once."
Comparison: Month, partnership, CCC target, and camera figure all match the primary source; ARTICLE 19 mirrors the same release on its own site. Both org edges resolve. Minor: body says "600,000 cameras across the state" — the release says "at once" and does not specify Hyderabad vs. Telangana-wide; the qualifier is unsourced but not contradicted.
Decision: primary-sourced

## Claim 18: January 2022 PIL at the Telangana High Court by Hyderabad activist S.Q. Masood with IFF legal support — India's first major judicial challenge to police facial recognition (body § India phase; outcomes scalar)

Source: https://thewire.in/law/telangana-hc-issues-notice-on-pil-challenging-use-of-facial-recognition-technology + https://maktoobmedia.com/india/activist-moves-telangana-hc-indias-first-legal-challenge-to-facial-recognition-technology/
Source tier: primary
Source content: Per IFF's own notice ("Telangana High Court issues notice in India's first legal challenge to the deployment of facial recognition technology") and The Wire: "The Telangana High Court on January 3 issued notice to the state government on a public interest litigation (PIL) challenging the increasing use of facial recognition technology"; "The petition was filed by SQ Masood in January 2022 with Internet Freedom Foundation's (IFF) assistance and was the first legal challenge to the rising use of FRT in India."
Comparison: Filer, court, January 2022 date, IFF support, and the contested "first" characterisation are each confirmed by ≥2 canonical sources (IFF primary + The Wire/Maktoob mainstream). The body's framing of the PIL as the campaign's "downstream artefact" is interpretation (the triggering police stop predates the campaign phase, May 2021) — connective-type discipline: not a claim, no decision.
Decision: corroborated

## Claim 19: Automated Apartheid (May 2023) — Red Wolf scans Palestinians' faces without consent, automatically enrols new faces, and is connected to Wolf Pack (comprehensive database on Palestinians) and Blue Wolf (smartphone app querying it) (body § OPT phase; scalar:sources[7].note systems description)

Source: https://www.amnesty.org/en/latest/news/2023/05/israel-opt-israeli-authorities-are-using-facial-recognition-technology-to-entrench-apartheid/
Source tier: primary
Source content: Report "Automated Apartheid" (May 2, 2023). Red Wolf "automatically biometrically enrols any new face it scans"; "linked with two other military-run surveillance systems, Wolf Pack and Blue Wolf"; Wolf Pack is "a vast database containing all available information on Palestinians from the OPT"; Blue Wolf is "an app which Israeli forces can access via smartphones and tablets, and which can instantly pull up the information stored in the Wolf Pack database."
Comparison: Report date, all three system names, their functions, and auto-enrolment match the primary source.
Decision: primary-sourced

## Claim 20: Red Wolf deployed "at military checkpoints in Hebron and East Jerusalem" (body § OPT phase; outcomes scalar "Red Wolf FRT deployment against Palestinians at Hebron and East Jerusalem checkpoints"; scalar:sources[7].note "the Red Wolf facial recognition system at military checkpoints in Hebron and East Jerusalem")

Source: https://www.amnesty.org/en/latest/news/2023/05/israel-opt-israeli-authorities-are-using-facial-recognition-technology-to-entrench-apartheid/
Source tier: primary
Source content: "Red Wolf is deployed at military checkpoints in the city of Hebron in the occupied West Bank." East Jerusalem surveillance is a separate system: "In occupied East Jerusalem, Israel operates a network of thousands of CCTV cameras across the Old City, known as Mabat 2000," upgraded since 2017 for facial recognition.
Comparison: The primary source places Red Wolf at Hebron checkpoints only; East Jerusalem's documented FRT surveillance is the distinct Mabat 2000 CCTV network, not Red Wolf. Token fix: "Hebron and East Jerusalem" → "Hebron" in all three locations (body § OPT phase sentence, outcomes scalar, scalar:sources[7].note); the body sentence's appositive ("the only two cities... with Israeli settlements inside their bounds" — the report's *focus*, see Claim 21) makes the body fix a prose-judgment edit. Route via Editor flag to Researcher for the body; the scalar and outcomes fixes are closer to mechanical.
Decision: correction

## Claim 21: Hebron and East Jerusalem are "the only two cities in the OPT with Israeli settlements inside their bounds" (body § OPT phase)

Source: https://www.amnesty.org/en/latest/news/2023/05/israel-opt-israeli-authorities-are-using-facial-recognition-technology-to-entrench-apartheid/
Source tier: primary
Source content: "Automated Apartheid focuses on Hebron and East Jerusalem, the only cities in the Occupied Palestinian Territories with Israeli settlements inside their bounds."
Comparison: Body reproduces the report's own characterisation accurately.
Decision: primary-sourced

## Claim 22: standing global petition "calling on UN leaders to prohibit the use of facial recognition for mass surveillance by state agencies and private-sector actors worldwide" (body § Global petition; goals scalar "calls on UN leaders to prohibit state and private-sector deployment")

Source: https://www.amnesty.org/en/petition/ban-the-scan-petition/
Source tier: primary
Source content: The live petition demands "a global ban on facial recognition technology now," addressed to world governments: "We must fight for a global ban on facial recognition technologies that are used for mass and discriminatory targeted surveillance," plus "A ban on the export of facial recognition systems to other countries." No "UN leaders" addressee found on the fetched page.
Comparison: The petition exists and demands a global ban — but the fetched page frames the addressee as world governments, not UN leaders, and does not name private-sector actors as a distinct target. The "UN leaders" framing may reflect an earlier petition text; too divergent from the current page to confirm, not clearly contradicted (no single replacement token).
Decision: uncorroborated

## Claim 23: #BanBS open letter — launched June 2021 with 175+ signatories from 55 countries, co-drafted by Amnesty International; standing commitment across 200+ organisations; edge → camp-access-now-ban-biometric-surveillance-global-2021-ongoing (body § Global petition)

Source: https://www.accessnow.org/campaign/ban-biometric-surveillance/ + https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/ + https://www.statewatch.org/news/2021/june/the-potential-for-abuse-is-too-great-global-call-to-ban-biometric-surveillance-in-public-spaces/
Source tier: primary
Source content: Access Now: the statement "was drafted by Access Now, Amnesty International, European Digital Rights (EDRi), Human Rights Watch, Internet Freedom Foundation (IFF), and Instituto Brasileiro de Defesa do Consumidor (IDEC)"; "More than 200 civil society organizations, activists, technologists, and other experts around the world have already joined." Letter released 7 June 2021; launch coverage reports 179 signatories from 55 countries.
Comparison: June 2021 launch, 175+ signatories (179 at launch), 55 countries, Amnesty as co-drafter, and the 200+ standing count all confirmed across Access Now (primary), Amnesty (primary), and Statewatch/LRWC mirrors. Edge resolves.
Decision: corroborated

## Claim 24: scalar:sources[8].note — banthescan.amnesty.org/opt/ as "primary source for the OPT phase as the campaign's third named geographic phase and for the Red Wolf system's deployment at Hebron checkpoints"

Source: https://banthescan.amnesty.org/opt/
Source tier: none
Source content: The page returned only a "Ban the Scan" header to this harness (JavaScript-rendered body; no content retrievable).
Comparison: The note's substance is consistent with other Amnesty sources (the hub names OPT as a jurisdiction; the May 2023 report places Red Wolf at Hebron checkpoints — note this scalar, unlike sources[7].note, states the Hebron-only deployment correctly), but the specific page's content could not be retrieved to verify the attribution.
Decision: uncorroborated

## Claim 25: "No legislative ban on NYPD facial recognition has been enacted in New York City or New York State as of 2026; the campaign's primary legislative demands remain unmet" (outcomes scalar; body § Launch context)

Source: no canonical source found
Source tier: none
Source content: Consistent with everything found: S.T.O.P.'s "Law Enforcement Facial Recognition Ban" state-slate page (Nov 2023) still advocates for the ban; an April 2025 NYC Council announcement describes an "Expanded POST Act Legislative Package to Strengthen Transparency and Oversight of NYPD Surveillance Technology" — transparency measures, not a ban.
Comparison: A negative claim ("no ban enacted as of 2026") has no single affirming source; all evidence found is consistent with it (bills S79 and successors not enacted; NYC Council activity through April 2025 is POST Act transparency expansion, not prohibition). Not asserting error — the audit's honest limit on proving a negative.
Decision: uncorroborated
