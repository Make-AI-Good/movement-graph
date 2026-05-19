---
entity_id: camp-karisma-moe-electoral-software-audit-colombia-2018
entity_hash: 0a0aec5cc1502372e440d510e6abc6b0bd6c943c
audit_date: 2026-05-19
pass: 1
status: discrepancy
claims_total: 20
claims_verified: 11
claims_discrepancy: 4
claims_unverifiable: 5
sources_consulted:
  - https://blog.karisma.org.co/protocolosoftwareelecciones/
  - https://blog.karisma.org.co/segundo-informe-de-observacion-electoral-primera-vuelta-presidencial-colombia-2022/
  - https://blog.karisma.org.co/comunicado-de-prensa-01-observacion-tecnica-a-las-elecciones-regionales-de-2023-continuan-los-problemas-de-acceso-a-informacion-previa-a-los-comicios/
  - https://blog.karisma.org.co/escrutinio-en-2022-tratando-de-dar-confianza-aunque-no-lo-sepamos-todo/
  - https://blog.karisma.org.co/klab/
  - https://blog.karisma.org.co/equipo/carolina-botero/
  - https://www.semana.com/elecciones-presidenciales2018/candidatos-elecciones-presidencia-2018/articulo/polemica-por-auditoria-al-software-de-la-registraduria/568155/
  - https://www.elespectador.com/politica/elecciones-colombia-2022/registraduria-y-cne-no-tienen-capacidad-tecnica-para-meterle-el-diente-a-la-tecnologia-electoral-pilar-saenz-de-karisma/
  - https://es.wikipedia.org/wiki/Movimiento_Independiente_de_Renovaci%C3%B3n_Absoluta
  - https://es.wikipedia.org/wiki/Manuel_Virg%C3%BCez
  - https://es.wikipedia.org/wiki/Carlos_Alberto_Baena
  - https://es.wikipedia.org/wiki/Alexandra_Moreno_Piraquive
---

## Claim 1: "In February 2018 Fundación Karisma and the Misión de Observación Electoral (MOE) publicly committed to a joint protocol for independent civil-society audit"

Source: https://blog.karisma.org.co/protocolosoftwareelecciones/
Source content: "the Electoral Observation Mission commissioned us to propose an audit protocol for Colombia's scrutiny and consolidation software."
Comparison: Karisma's own blog confirms MOE commissioned Karisma to develop the protocol; the joint-commitment framing is consistent with this commissioning relationship.
Decision: verified

## Claim 2: Protocol "published as an MOE civil-society document in April 2018 and authored by Karisma's K+LAB digital-security laboratory"

Source: cited PDF at moe.org.co/wp-content/uploads/2018/04/Protocolo-de-auditoria... (URL pattern includes "2018/04" date stamp); blog.karisma.org.co/klab/
Source content: K+LAB landing page describes the lab as Karisma's "laboratorio de seguridad digital y privacidad" supporting "audit-protocol design"; the protocol PDF's URL path encodes the April 2018 publication.
Comparison: The MOE PDF URL was inaccessible during this audit (HTTP 403), but the URL path and K+LAB's mandate as described on its landing page are consistent with the body claim. Cannot quote document text directly.
Decision: unverifiable

## Claim 3: "Colombia's first dedicated civil-society protocol for technical audit of state-deployed electoral algorithmic systems"

Source: no canonical source found
Source content: n/a
Comparison: This is a "first" characterization claim. Per the source rule, "contested events or attributions" require ≥2 canonical sources and Wikipedia is tiebreaker-only. No canonical source was located that establishes this as Colombia's first such protocol.
Decision: unverifiable

## Claim 4: Three formal rounds of technical observation in "the 2018 congressional and presidential elections, the 2022 presidential first round, and the 2023 regional elections"

Source: https://blog.karisma.org.co/segundo-informe-de-observacion-electoral-primera-vuelta-presidencial-colombia-2022/ ; https://blog.karisma.org.co/comunicado-de-prensa-01-observacion-tecnica-a-las-elecciones-regionales-de-2023-continuan-los-problemas-de-acceso-a-informacion-previa-a-los-comicios/
Source content: Karisma's 2022 report covers "the implementation and functioning of the two scrutiny software systems contracted by the National Civil Registry" during Colombia's 2022 first-round presidential election; the 2023 press release covers "elecciones regionales de 2023" technical observation.
Comparison: Three rounds at the stated cycles are documented across cited Karisma publications.
Decision: verified

## Claim 5: "8–9 February 2018 ruling of the Consejo de Estado"

Source: https://blog.karisma.org.co/protocolosoftwareelecciones/ ; https://es.wikipedia.org/wiki/Movimiento_Independiente_de_Renovaci%C3%B3n_Absoluta ; https://es.wikipedia.org/wiki/Carlos_Alberto_Baena
Source content: Karisma blog gives "8 de febrero"; MIRA Spanish Wikipedia gives "Sentencia 2014-00117/2014-00109 del 8 de febrero de 2018"; Baena Spanish Wikipedia gives "9 de febrero de 2018".
Comparison: Sources record both 8 February (ruling) and 9 February (publication/notification). The body's "8–9 February 2018" framing accommodates both. Per the source rule, named-statute / public-record dates are Wikipedia-eligible.
Decision: verified

## Claim 6: Annulment "of three 2014-2018 senators and awarding those seats to the MIRA movement — Alexandra Moreno Piraquive, Manuel Antonio Virgúez Piraquive, and Carlos Alberto Baena"

Source: https://es.wikipedia.org/wiki/Movimiento_Independiente_de_Renovaci%C3%B3n_Absoluta ; https://es.wikipedia.org/wiki/Manuel_Virg%C3%BCez
Source content: MIRA Spanish Wikipedia: "Alexandra Moreno Piraquive / Carlos Alberto Baena / Manuel Antonio Virgüez". Wikipedia article URL for the third senator is `Manuel_Virgüez` and the article confirms his Senate restoration for 2014-2018.
Comparison: The third senator's name in the entity body is "Manuel Antonio Virgúez Piraquive" — two differences from sources: (a) accent mark is "Virgúez" (acute ú) but canonical Spanish spelling is "Virgüez" (diaeresis ü), and (b) the entity appends "Piraquive" as a surname, but no source supports "Piraquive" as part of Virgüez's name (Piraquive is the second surname of Alexandra Moreno Piraquive, not of Virgüez). Annulment count (three) and the other two names match.
Decision: discrepancy

## Claim 7: "Forensic experts attached to the Fiscalía found evidence of sabotage in 3,630 records across 1,412 voting tables"

Source: https://blog.karisma.org.co/protocolosoftwareelecciones/
Source content: "3.630 records of 1.412 mesas" showed evidence of tampering per Fiscalía computer experts.
Comparison: Numbers and Fiscalía attribution match within paraphrase tolerance.
Decision: verified

## Claim 8: "the RNEC's contractor had, by mandate of the procurement contract, deleted the original electoral-data files three months after the 2014 elections"

Source: https://blog.karisma.org.co/protocolosoftwareelecciones/
Source content: Contractors destroyed original files "three months after the elections" per contract mandate.
Comparison: Three-month destruction timing per contract mandate matches; "2014 elections" is the relevant context (MIRA case is the 2014 Senate election).
Decision: verified

## Claim 9: "preceded by similar Consejo de Estado annulments of the 2002-2006 and 2006-2010 Senate elections, each delivered three to five years after the contested vote"

Source: no canonical source found (MOE press release at moe.org.co cited by entity was inaccessible — HTTP 403 — and Karisma blog does not name these prior annulments)
Source content: n/a
Comparison: Cannot verify the existence or timing of these prior annulments from accessible sources.
Decision: unverifiable

## Claim 10: "MOE — Colombia's principal civil-society electoral-observation organisation, led by Director Alejandra Barrios Cabrera"

Source: https://www.semana.com/elecciones-presidenciales2018/candidatos-elecciones-presidencia-2018/articulo/polemica-por-auditoria-al-software-de-la-registraduria/568155/
Source content: "Alejandra Barrios, directora de la Misión de Observación Electoral (MOE)"
Comparison: Title "MOE Director" and name "Alejandra Barrios" verified. The "Cabrera" suffix is not contradicted but not directly attested in accessible sources.
Decision: verified

## Claim 11: Karisma's "executive direction of Carolina Botero" in February 2018

Source: https://blog.karisma.org.co/equipo/carolina-botero/
Source content: "Fue directora de la Fundación Karisma durante una década hasta 2024" (was director of Karisma Foundation for a decade until 2024).
Comparison: Director role for ~10 years through 2024 places her as director in 2018. "Executive director" within paraphrase tolerance of "directora".
Decision: verified

## Claim 12: International comparators in the protocol — "Germany's 2009 constitutional prohibition on electronic voting followed by the Chaos Computer Club's 2017 findings"; Netherlands' retreat; Mexico's 2006 preliminary-results; Argentina's 2017 sole-proponent contract

Source: https://blog.karisma.org.co/protocolosoftwareelecciones/
Source content: "Germany (2017): Software for vote tallying was 'easily attackable' by Chaos Computer Club activists, following an earlier 2009 ban on electronic voting. Netherlands: Activists found vote counting software vulnerable after the country had abandoned electronic voting. Mexico (2006): Preliminary results software faced criticism due to 'great inconsistencies between manual count and software results.' Argentina (2017): Provisional results software contracted to a multinational amid fraud allegations during a tight election."
Comparison: All four comparator cases and dates align with the Karisma blog account.
Decision: verified

## Claim 13: 2018 substantive findings — "the escrutinio software was vulnerable, had not been designed to be controllable or auditable, and that no independent audit of the scrutiny system had ever been conducted"

Source: https://blog.karisma.org.co/protocolosoftwareelecciones/
Source content: Karisma's framing in the article: "the technology" had been treated as if "inocente, transparente e infranqueable" when in fact it is a vector for fraud and distrust; no independent audit exists.
Comparison: Substantive finding tracks the Karisma 2018 account within paraphrase tolerance.
Decision: verified

## Claim 14: "MOE published a post-election audit-analysis volume in November 2018"

Source: cited PDF at moe.org.co/wp-content/uploads/2018/11/Protoloco-Software-Auditoria-Analisis-de-Escrutinios_Digital.pdf
Source content: PDF inaccessible during this audit (HTTP 403). URL path includes "2018/11" date stamp consistent with November 2018 publication.
Comparison: Cannot quote source content. URL-pattern consistent but not a direct verification of the document.
Decision: unverifiable

## Claim 15: "Karisma's executive director Carolina Botero argued in Colombian mainstream press the case for independent audit ahead of the 2018 presidential election" — body link points to Semana 22 May 2018 article

Source: https://www.semana.com/elecciones-presidenciales2018/candidatos-elecciones-presidencia-2018/articulo/polemica-por-auditoria-al-software-de-la-registraduria/568155/
Source content: "Carolina Botero from Karisma is not mentioned or quoted in this article. The piece focuses primarily on statements from Barrios and Galindo regarding electoral software audits." Quotes attributed to MOE Director Alejandra Barrios, e.g. "El fallo habla de las vulnerabilidades del software de la Registraduría y dice que hay que trabajar en dar más garantías al proceso".
Comparison: The body sentence credits Carolina Botero with the public-press argument and links to the Semana article as evidence; the Semana article does not name or quote Botero. The argument in that article is made by Alejandra Barrios (MOE Director), not Botero.
Decision: discrepancy

## Claim 16: Karisma applied the protocol to "two scrutiny-software systems the RNEC deployed" in 2022 and published the "Segundo informe de observación electoral" on the first round

Source: https://blog.karisma.org.co/segundo-informe-de-observacion-electoral-primera-vuelta-presidencial-colombia-2022/
Source content: "the implementation and functioning of the two scrutiny software systems contracted by the National Civil Registry" — Disproel and Indra; published May 27, 2022.
Comparison: Two-system observation framing and the publication match the Karisma source.
Decision: verified

## Claim 17: K+LAB's coordinator/lead Pilar Sáenz and her institutional-capacity argument in El Espectador

Source: https://www.elespectador.com/politica/elecciones-colombia-2022/registraduria-y-cne-no-tienen-capacidad-tecnica-para-meterle-el-diente-a-la-tecnologia-electoral-pilar-saenz-de-karisma/ ; https://blog.karisma.org.co/escrutinio-en-2022-tratando-de-dar-confianza-aunque-no-lo-sepamos-todo/
Source content: El Espectador interview quotes Sáenz: "la Registraduría y el CNE no tienen capacidad técnica para meterle el diente a los temas de tecnología del proceso electoral"; Karisma blog identifies Sáenz as "coordinator of K+LAB at Fundación Karisma".
Comparison: The substantive argument verifies; "K+LAB's lead" is within paraphrase tolerance of "coordinator of K+LAB".
Decision: verified

## Claim 18: 2023 regional elections — "civil-society observers were now being required by the RNEC's contractor DISPROEL to sign non-disclosure agreements as a condition of access to the scrutiny software at all"

Source: https://blog.karisma.org.co/comunicado-de-prensa-01-observacion-tecnica-a-las-elecciones-regionales-de-2023-continuan-los-problemas-de-acceso-a-informacion-previa-a-los-comicios/
Source content: "aún no tenemos certeza si para revisar el código se exigirá firmar acuerdos de confidencialidad con Registraduría o con DISPROEL como se hizo el año pasado" (we still lack certainty whether reviewing the code will require signing confidentiality agreements with the Registry or DISPROEL as occurred last year).
Comparison: The press release reports NDAs were required in 2022 ("el año pasado") and expresses uncertainty about 2023. The body sentence presents NDA requirement as an established 2023 finding ("were now being required... as a condition of access... at all"), which is a stronger claim than the source supports.
Decision: discrepancy

## Claim 19: "K+LAB, the only dedicated civil-society digital-security and privacy laboratory in Colombia"

Source: https://blog.karisma.org.co/klab/
Source content: K+LAB describes itself as "el primer laboratorio de seguridad digital y privacidad de Colombia pensado desde y para la sociedad civil" (Colombia's first digital security and privacy laboratory designed from and for civil society).
Comparison: K+LAB's own page claims "first" (primer), not "only". The entity body's "only" is a stronger claim than the source supports.
Decision: discrepancy

## Claim 20: K+LAB supports "Colombian civil-society organisations, journalists, human-rights defenders, and activists on digital security, vulnerability identification, audit-protocol design, and public-interest-technology policy recommendations"

Source: https://blog.karisma.org.co/klab/
Source content: K+LAB "focuses on technical analysis and research to support civil society's digital security and privacy work... providing training and vulnerability assessments for organizations, activists, journalists, and human rights defenders".
Comparison: Constituency list (organizations / journalists / activists / human-rights defenders) and topic list (digital security, vulnerability, training) align within paraphrase tolerance.
Decision: verified
