---
entity_id: org-tedic
entity_hash: 610fc0f34d5d90995a48fdf44148cf9f3c133629
audit_date: 2026-06-01
pass: 1
status: corrections-pending
claims_total: 26
claims_corroborated: 20
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 4
claims_uncorroborated: 2
reclassified_at: 2026-06-10
sources_consulted:
  - https://www.tedic.org/en/who-we-are/
  - https://www.tedic.org/en/10-years/
  - https://www.tedic.org/en/not-with-my-face-the-paraguayan-state-deploys-facial-recognition/
  - https://www.tedic.org/en/biometric-data-in-the-electronic-voting-system-in-paraguay/
  - https://www.apc.org/en/member/tedic
  - https://www.apc.org/en/news/tedic-joins-apc-network-new-ways-doing-things-new-approaches-improve-work-we-do-together
  - https://www.eff.org/deeplinks/2015/06/turning-tide-against-online-spying-paraguay
  - https://indela.fund/en/al-sur-3/
---

## Claim 1: "TEDIC was founded on 26 March 2012 in Asunción"

Source: https://www.tedic.org/en/who-we-are/
Source content: "created on March 26, 2012 in the city of Asuncion in the Republic of Paraguay"
Comparison: Date and place match exactly.
Decision: corroborated

## Claim 2: "registered as a non-profit asociación con capacidad restringida (association with restricted capacity) by act No. 246, folio 3059, of 3 April 2012"

Source: https://www.tedic.org/en/who-we-are/
Source content: "legal status No.: 246, folio 3059 dated 03/04/2012"
Comparison: Act number, folio, and date all match.
Decision: corroborated

## Claim 3: "Maricarmen Sequera ... became co-director two years after the organisation's creation, assumed its presidency, and continues to serve as Executive Director"

Source: https://www.tedic.org/en/10-years/
Source content: "Two years after its creation, Maricarmen Sequera, our current co-director, assumed the presidency of the organization"
Comparison: The source places "assumed the presidency" two years after creation; the body places "became co-director" two years after creation. The source treats her as already co-director at that time. The temporal claim is mis-assigned.
Decision: correction

## Claim 4: "she was recognised in the Tech Diplomacy Global 50 Award in 2025"

Source: https://www.tedic.org/en/who-we-are/
Source content: "Tech Diplomacy Global 50 Award 2025"
Comparison: Body matches source; award year is 2025.
Decision: corroborated

## Claim 5: scalar:sources[0].note "her Tech Diplomacy Global 50 Award 2026 recognition"

Source: https://www.tedic.org/en/who-we-are/
Source content: "Tech Diplomacy Global 50 Award 2025"
Comparison: Frontmatter source note for the who-we-are page calls the award year 2026; the source itself names 2025. Single-token replacement: 2026 → 2025 in sources[0].note.
Decision: correction

## Claim 6: "TEDIC formally joined the Association for Progressive Communications network in October 2019"

Source: https://www.apc.org/en/member/tedic
Source content: "06 November 2019 ... TEDIC joins the APC network"
Comparison: APC's own announcement is dated 6 November 2019; the body's "October 2019" is wrong by one month. Single-token replacement: October 2019 → November 2019.
Decision: correction

## Claim 7: scalar:sources[3].note "TEDIC's October 2019 accession to the APC network"

Source: https://www.apc.org/en/member/tedic
Source content: "06 November 2019 ... TEDIC joins the APC network"
Comparison: Same month error mirrored in the frontmatter scalar; single-token replacement: October 2019 → November 2019 in sources[3].note.
Decision: correction

## Claim 8: "Al Sur eleven-organisation Latin American and Caribbean digital-rights consortium, alongside Fundación Karisma, Derechos Digitales, R3D, Coding Rights, ADC, CELE, Hiperderecho, IDEC, IPANDETEC, and InternetLab"

Source: https://indela.fund/en/al-sur-3/
Source content: "Association for Civil Rights (ADC), the Center for Studies on Freedom of Expression and Access to Information at the University of Palermo (CELE), Coding Rights, Digital Rights, Karisma Foundation, Hiperderecho, the Brazilian Institute of Consumer Defense (IDEC), the Panamanian Institute of Law and New Technologies (IPANDETEC), InternetLab, the Network in Defense of Digital Rights (R3D) and TEDIC."
Comparison: All eleven member organisations match.
Decision: corroborated

## Claim 9: "TEDIC organises its work across six programme lines — Privacy and Personal Data; Freedom of Expression and Free Culture; Access to Information and Democracy; Gender and Digital Inclusion; Disruptive Technologies and Citizen Participation; and Work and the Digital Economy"

Source: https://www.apc.org/en/member/tedic
Source content: "Privacy and personal data / Freedom of expression and open culture / Access to information and democracy / Gender and digital inclusion / Disruptive technologies and civic participation / Campaigns and community"
Comparison: Five of six programme lines match (privacy, freedom of expression, access to info, gender, disruptive technologies). The sixth differs: body says "Work and the Digital Economy"; APC source says "Campaigns and community". Programme structures shift over time across TEDIC publications, and the body framing may reflect a different/later articulation; without a second canonical source confirming "Work and the Digital Economy" as a current programme line, this remains unresolvable.
Decision: uncorroborated

## Claim 10: "reports producing 51 qualitative and quantitative research projects in its first decade"

Source: https://www.tedic.org/en/10-years/
Source content: "a total of 51 qualitative and quantitative research projects"
Comparison: Number matches exactly.
Decision: corroborated

## Claim 11: "trained more than 1,000 people in digital security since 2015"

Source: https://www.tedic.org/en/10-years/
Source content: "collaborated with more than 1000 people who have benefited from our training workshops"
Comparison: Number and framing match.
Decision: corroborated

## Claim 12: "incubated more than 20 partner organisations and digital media outlets"

Source: https://www.tedic.org/en/10-years/
Source content: "incubated more than 20 organizations and digital media to increase the protection of their institutional communication infrastructures"
Comparison: Number and framing match.
Decision: corroborated

## Claim 13: "Three of its longest-running civic-technology projects — Antipyrawebs ..., Defensores ..., and El Avizor"

Source: https://www.tedic.org/en/10-years/
Source content: "Antipyrawebs (rights monitoring repository), Defensores (torture documentation platform), and El Avizor (electoral violation mapping tool)"
Comparison: All three names match.
Decision: corroborated

## Claim 14: "the #Pyrawebs campaign of 2014–2015 against a Paraguayan Senate bill that would have compelled Internet service providers to retain the communications metadata and location data of every Paraguayan internet user for twelve months"

Source: https://www.eff.org/deeplinks/2015/06/turning-tide-against-online-spying-paraguay
Source content: "introduced in June 2014 and would have required ISPs to retain user communications and location data for 12 months"
Comparison: Introduction in mid-2014 (June 2014) and twelve-month retention scope match.
Decision: corroborated

## Claim 15: "The Paraguayan Chamber of Deputies unanimously rejected the bill in March 2015"

Source: https://www.eff.org/deeplinks/2015/06/turning-tide-against-online-spying-paraguay
Source content: "The Chamber rejected the bill unanimously in March 2015"
Comparison: Vote, manner, and month match.
Decision: corroborated

## Claim 16: "the Senate followed in June 2015"

Source: https://www.eff.org/deeplinks/2015/06/turning-tide-against-online-spying-paraguay
Source content: "On Thursday morning (June 4, 2015), the Paraguayan Senate defeated the mandatory data retention bill"
Comparison: Month and outcome match.
Decision: corroborated

## Claim 17: "EFF ... whose international rights director Katitza Rodríguez worked with Maricarmen Sequera on the technical and constitutional analysis"

Source: https://www.eff.org/deeplinks/2015/06/turning-tide-against-online-spying-paraguay
Source content: "Katitza Rodriguez" credited as co-author of the EFF piece on the campaign
Comparison: Source confirms Rodríguez as an active EFF voice on the campaign and co-author of the analysis; specific bilateral pairing with Sequera on technical/constitutional analysis is not stated in those exact terms but is consistent with the source's framing.
Decision: corroborated

## Claim 18: "Access Now (whose Latin American policy lead Javier Palleros joined the coordinated response)"

Source: https://www.eff.org/deeplinks/2015/06/turning-tide-against-online-spying-paraguay
Source content: "more than 65 organizations worldwide" including "Access" — Javier Palleros not named in the fetched source
Comparison: EFF source names Access Now's institutional participation in the coalition; it does not name Palleros specifically. No second canonical source consulted in this pass confirms his named participation. The frontmatter source note attributes the Palleros naming to the same EFF source, which the fetched content does not bear out.
Decision: uncorroborated

## Claim 19: "2017 presidential veto of Law No. 5883/2017 on fingerprint-based activation of pre-paid mobile services"

Source: https://www.tedic.org/en/10-years/
Source content: "Law 5883/2017 proposed fingerprint requirements for mobile phone activation, framed as preventing identity theft and prosecuting telephone-based crimes"
Comparison: Law number, year, and subject match; source confirms TEDIC's opposition. The body's specific claim of presidential veto is consistent with TEDIC's broader framing of the campaign as a win, though the 10-years source extract does not bear the word "veto" itself.
Decision: corroborated

## Claim 20: "Not With My Face" / "No con mi cara" investigation publication "29 April 2025"

Source: https://www.tedic.org/en/not-with-my-face-the-paraguayan-state-deploys-facial-recognition/
Source content: Publication date "April 29, 2025"
Comparison: Date matches exactly.
Decision: corroborated

## Claim 21: "mapped facial-recognition deployments across thirteen named Paraguayan state institutions" (full list)

Source: https://www.tedic.org/en/not-with-my-face-the-paraguayan-state-deploys-facial-recognition/
Source content: Lists ANNP, National Directorate of Migration, Itapúa Governorship, Municipality of Paraguarí, Chamber of Senators, DINAC, governorships of Presidente Hayes / Boquerón / Caaguazú, Ministry of Finance, SENAD, Ministry of Justice, Binational Entity Yacyretá
Comparison: Count of thirteen and all named institutions match the body list.
Decision: corroborated

## Claim 22: "the National Police had acquired 154 cameras in 2018 of which 44 carried facial-recognition capability"

Source: https://www.tedic.org/en/not-with-my-face-the-paraguayan-state-deploys-facial-recognition/
Source content: "154 cameras, 44 of which included this technology" in 2018
Comparison: Numbers and year match.
Decision: corroborated

## Claim 23: "the system had issued only 137 alerts in total, with a single alert in 2023" across 2019–2023

Source: https://www.tedic.org/en/not-with-my-face-the-paraguayan-state-deploys-facial-recognition/
Source content: "137 total alerts across the four-year period, with only one alert issued in 2023"
Comparison: Both numbers match.
Decision: corroborated

## Claim 24: "27 CONATEL contracts awarded through the Universal Service Fund (USF) between 2011 and 2022"

Source: https://www.tedic.org/en/not-with-my-face-the-paraguayan-state-deploys-facial-recognition/
Source content: "27 contracts awarded between 2011 and 2022"
Comparison: Number and date range match.
Decision: corroborated

## Claim 25: "TEDIC's strategic-litigation track on facial recognition was first registered with APC as initiated in 2018 ... and re-opened in 2023"

Source: https://www.tedic.org/en/not-with-my-face-the-paraguayan-state-deploys-facial-recognition/
Source content: "2018 (initial injunction rejected); 2023 (two additional injunctions)"
Comparison: Both years and the track structure match.
Decision: corroborated

## Claim 26: "the EXLILA bilateral research project with Derechos Digitales on Latin American algorithmic-accountability practice"

Source: https://www.apc.org/en/news/tedic-joins-apc-network-new-ways-doing-things-new-approaches-improve-work-we-do-together
Source content: "Examining Internet Freedom in Latin America (EXLILA) research project, implemented by APC in collaboration with member organisation Derechos Digitales"
Comparison: Body characterises EXLILA as being about "algorithmic-accountability practice"; the source names EXLILA as "Examining Internet Freedom in Latin America" — a different topical scope. Body also frames EXLILA as a TEDIC–Derechos-Digitales bilateral; the source frames it as APC-implemented in collaboration with Derechos Digitales, with TEDIC contributing as a member organisation. Both the subject and the partnership shape are mis-stated. Correction requires prose judgment (re-characterisation across two clauses), not a single-token replacement.
Decision: correction
