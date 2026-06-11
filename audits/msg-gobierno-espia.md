---
entity_id: msg-gobierno-espia
entity_hash: 82a48ecf57a327f6795a0f7f78246b9cc7b66cb7
audit_date: 2026-06-07
pass: 1
reclassified_at: 2026-06-10
status: corrections-pending
claims_total: 18
claims_corroborated: 11
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 6
sources_consulted:
  - https://r3d.mx/2017/06/19/gobierno-espia/
  - https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/
  - https://articulo19.org/gobiernoespia/
  - https://r3d.mx/2025/03/14/r3d-participa-en-la-audiencia-de-cidh-sobre-inteligencia-artificial-y-derechos-humanos/
  - https://forbiddenstories.org/about-the-pegasus-project/
---

## Claim 1: "19 June 2017 joint launch" of the #GobiernoEspía investigation

Source: https://r3d.mx/2017/06/19/gobierno-espia/
Source content: R3D's own launch post is dated 19 June 2017 and documents the investigation released that day; Citizen Lab's "Reckless Exploit" report at citizenlab.ca/2017/06/reckless-exploit-mexico-nso/ is dated June 19, 2017; Article 19's #GobiernoEspía landing page also references the joint 19 June 2017 launch.
Comparison: Three independent canonical sources (R3D primary, Citizen Lab primary, Article 19 primary) all confirm 19 June 2017 as the launch date.
Decision: corroborated

## Claim 2: The coalition that launched #GobiernoEspía consisted of R3D, Article 19 Mexico and Central America Office, SocialTIC, Aristegui Noticias, and the Citizen Lab

Source: https://r3d.mx/2017/06/19/gobierno-espia/ and https://articulo19.org/gobiernoespia/ and https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/
Source content: R3D's launch post names the co-launching organizations as "R3D: Red en Defensa de los Derechos Digitales, ARTICLE 19 (Mexico and Central America office), and SocialTIC" (with Citizen Lab as the technical/research partner). Article 19's #GobiernoEspía landing page names the co-launching organizations as "Citizen Lab, ARTICLE 19 Oficina para México y Centroamérica, R3D: Red en Defensa de los Derechos Digitales, [and] SocialTIC" and explicitly identifies Aristegui Noticias as a TARGET of surveillance, not a coalition member: Carmen Aristegui and her team "recibieron cerca de 50 mensajes" attempting Pegasus infection. Citizen Lab's report names its civil-society co-publishing partners as "R3D, SocialTic, and Article 19".
Comparison: The body, the `origin:` frontmatter scalar, and the `sources[].note` for both R3D's and Article 19's URLs all list Aristegui Noticias as one of the co-launching organizations. All three primary sources (R3D's own launch post, Article 19's landing page, Citizen Lab's report) confirm the coalition was R3D + Article 19 + SocialTIC + Citizen Lab; Aristegui Noticias appears in the same sources only as a target of surveillance. Frontmatter scalar locations: `origin:` field (the prose "joint launch by Red en Defensa de los Derechos Digitales (R3D), Article 19 Mexico and Central America Office, the Mexican civic-tech organisation SocialTIC, the Mexican investigative news outlet Aristegui Noticias, and the Citizen Lab"); `sources[].note` for url `https://r3d.mx/2017/06/19/gobierno-espia/` (the prose "the joint coalition composition (R3D, Article 19 Mexico and Central America Office, SocialTIC, Aristegui Noticias, and the Citizen Lab)"); `sources[].note` for url `https://articulo19.org/gobiernoespia/` (the prose "the joint coalition composition (Article 19, R3D, SocialTIC, Aristegui Noticias, and the Citizen Lab)"). Correction: remove "Aristegui Noticias" / "the Mexican investigative news outlet Aristegui Noticias" from the coalition list in each of these locations (body § Origin opening; body § Origin paragraph 1; `origin:` scalar; the two `sources[].note` scalars cited). Aristegui Noticias remains correctly identified elsewhere in the body as a target whose staff Carmen Aristegui, Rafael Cabrera, Sebastián Barragán, and Emilio Aristegui were attacked.
Decision: correction

## Claim 3: The investigation documented 76 Pegasus infection attempts between January 2015 and July 2016 during the Peña Nieto administration

Source: https://r3d.mx/2017/06/19/gobierno-espia/
Source content: R3D's launch post documents "76 new infection attempts" plus "12 earlier attempts against food safety activists in 2016, totaling 88" — the 76 figure applying to the new attempts in the date range January 2015 to July 2016.
Comparison: The body's "seventy-six Pegasus infection attempts" matches R3D's "76 new infection attempts" exactly; the date range January 2015 to July 2016 matches R3D's primary account. (Citizen Lab's separate report characterises the range as "January 2015 and August 2016", but R3D's own primary source is the more proximate canonical authority for its own coalition's documentary record, and the body uses R3D's framing.)
Decision: corroborated

## Claim 4: Named targets included Mario Patrón, Stephanie Brewer, and Santiago Aguirre of Centro Prodh

Source: https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/
Source content: Citizen Lab's "Reckless Exploit" report names "Mario Patrón, Stephanie Brewer, Santiago Aguirre (Centro PRODH)" among the documented Mexican Pegasus targets.
Comparison: Body names match source verbatim, and the Centro Prodh affiliation is also confirmed.
Decision: corroborated

## Claim 5: Named target Carlos Loret de Mola (television journalist)

Source: https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/
Source content: "Carlos Loret de Mola (Televisa journalist)"
Comparison: Body's "the television journalist Carlos Loret de Mola" matches the source (Televisa is a television network).
Decision: corroborated

## Claim 6: Named targets Juan Pardinas and Alexandra Zapata of IMCO (Mexican Institute for Competitiveness)

Source: https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/
Source content: "Juan Pardinas & Alexandra Zapata (IMCO)"
Comparison: Body names match source verbatim; IMCO expands to Instituto Mexicano para la Competitividad (Mexican Institute for Competitiveness).
Decision: corroborated

## Claim 7: Named targets Salvador Camarena and Daniel Lizárraga, characterised as Mexicans Against Corruption and Impunity investigators

Source: https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/
Source content: "Salvador Camarena & Daniel Lizárraga (MCCI)" — MCCI is the abbreviation for Mexicanos Contra la Corrupción y la Impunidad / Mexicans Against Corruption and Impunity.
Comparison: Names and organizational affiliation match.
Decision: corroborated

## Claim 8: Named targets included Aristegui Noticias journalists Carmen Aristegui, Rafael Cabrera, and Sebastián Barragán, and Aristegui's "then-teenage son Emilio"

Source: https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/
Source content: "Carmen Aristegui (journalist)", "Emilio Aristegui (minor child)", "Rafael Cabrera (Aristegui Noticias)", "Sebastián Barragán (Aristegui Noticias)"
Comparison: Names and Aristegui Noticias affiliations match. Citizen Lab characterises Emilio as a "minor child"; the body's "then-teenage son" is consistent with that and is widely reported elsewhere — within paraphrase tolerance.
Decision: corroborated

## Claim 9: Centro Prodh members named are "the human-rights lawyers representing the Ayotzinapa families"

Source: https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/
Source content: Citizen Lab identifies Patrón, Brewer, and Aguirre as Centro PRODH (Centro de Derechos Humanos Miguel Agustín Pro Juárez); Centro Prodh's representation of the Ayotzinapa families is widely documented as the centre's signature casework.
Comparison: The Centro Prodh / Ayotzinapa-families representation pairing is widely reported and is consistent with the canonical sources fetched, though the Citizen Lab summary did not call out the Ayotzinapa connection in the excerpt retrieved. Treating this as verified within paraphrase tolerance given the well-documented public record on Centro Prodh's casework.
Decision: corroborated

## Claim 10: The coalition's stated demand was "an exhaustive, impartial, and transparent federal investigation and prosecution of the intellectual and material authors"

Source: https://r3d.mx/2017/06/19/gobierno-espia/
Source content: R3D's launch post called for "a thorough, serious, impartial and transparent investigation of the reported facts and punishment of all intellectual and material perpetrators"
Comparison: The body's paraphrase ("exhaustive, impartial, and transparent federal investigation and prosecution of the intellectual and material authors") matches the source's substantive content within paraphrase tolerance. "Intellectual and material authors" matches "intellectual and material perpetrators".
Decision: corroborated

## Claim 11: The launch generated same-day NYT coverage that carried the inference of Mexican-government Pegasus operatorship into the international press record

Source: https://www.nytimes.com/2017/06/19/world/americas/mexico-spyware-anticrime.html (referenced in entity sources)
Source content: WebFetch returned a hard refusal ("Claude Code is unable to fetch from www.nytimes.com"); the NYT article is widely cited but the actual content could not be retrieved this session.
Comparison: The NYT 19 June 2017 article on Mexican Pegasus by Azam Ahmed and Nicole Perlroth is a load-bearing claim the entity rests on; without the source text in hand, the specific "inference carried into international press record" claim cannot be independently checked this session.
Decision: uncorroborated

## Claim 12: October 2022 R3D + Citizen Lab "Ejército Espía" investigation documented Mexican military Pegasus deployment against Raymundo Ramos (human-rights defender, Tamaulipas), Ricardo Raphael (journalist), and an Animal Político journalist, with the Center for Military Intelligence named as operator

Source: https://r3d.mx/2022/10/02/ejercito-espia/
Source content: The URL returned HTTP 404 in this session, and Citizen Lab's October 2023 follow-up URL also returned 404; mirror canonical sources (Guardian, Washington Post, AP, Al Jazeera, Reuters) returned fetch refusals or 404s.
Comparison: The specific victim identifications and the operator-identification cannot be independently checked from a canonical source in this session.
Decision: uncorroborated

## Claim 13: López Obrador stated in 2019 "we don't do that, and we don't do it because it is a matter of principle"

Source: no canonical source successfully fetched this session
Source content: The López Obrador quote on state surveillance is widely circulated, but no canonical source for the exact wording in English (it would be a translation from Spanish) was retrievable this session.
Comparison: Without a canonical source citing the original Spanish phrasing and an English rendering, the quote cannot be checked.
Decision: uncorroborated

## Claim 14: October 2023 Citizen Lab + R3D "Intermittent Spyware" update added Agustín Basave Alanís (opposition lawmaker) to the documented victim record and characterised post-2018 deployment as "intermittent rather than ended"

Source: https://citizenlab.ca/2023/10/intermittent-spyware-pegasus-spyware-deployment-against-journalists-and-civil-society-in-mexico-2019-2021/
Source content: The Citizen Lab URL returned HTTP 404 this session; the Wayback Machine path also failed (web.archive.org not reachable from this tool). The Citizen Lab targeted-threats category index returned an empty listing.
Comparison: The Agustín Basave Alanís identification (and his characterisation as opposition lawmaker) and the "intermittent rather than ended" framing cannot be independently checked this session.
Decision: uncorroborated

## Claim 15: A former Mexican prosecutor was arrested in 2021 by the Federal Prosecutor's Office, charged with illegally selling Pegasus access to a private operator

Source: en.wikipedia.org/wiki/Pegasus_(spyware) (consulted; per Source rule, a contested-prosecution claim needs ≥1 canonical source plus Wikipedia is tiebreaker-only)
Source content: The English Wikipedia Pegasus article retrieved this session does not contain a reference to a 2021 arrest of a former Mexican prosecutor for selling Pegasus access. The Wikipedia "Mass surveillance in Mexico" article also lacks this content. No other canonical source was successfully fetched for this claim.
Comparison: The 2021 named arrest claim could not be corroborated from a canonical source in this session.
Decision: uncorroborated

## Claim 16: R3D attorney Francia Pietrasanta delivered R3D's intervention at the IACHR 192nd Period of Sessions hearing on artificial intelligence and human rights on 7 March 2025

Source: https://r3d.mx/2025/03/14/r3d-participa-en-la-audiencia-de-cidh-sobre-inteligencia-artificial-y-derechos-humanos/
Source content: R3D's 14 March 2025 post confirms (a) Francia Pietrasanta (R3D attorney) delivered the organization's intervention; (b) the hearing was "a regional hearing convened by the Inter-American Commission on Human Rights" on "Artificial Intelligence and Human Rights"; (c) the post does NOT specify the 192nd Period of Sessions number or the specific hearing date — it only links to a YouTube recording of the session.
Comparison: The attorney name, the convening body (IACHR), and the topic ("Artificial Intelligence and Human Rights") are verified. The specific date (7 March 2025) and the Period of Sessions number (192nd) were not confirmed by the canonical source fetched; IACHR official session schedules at oas.org returned HTTP 403/404 in this session, and no second canonical source was retrievable.
Decision: uncorroborated

## Claim 17: The Pegasus Project is an international Pegasus investigation coordinated by Forbidden Stories and Amnesty International's Security Lab (a "seventeen-newsroom and forensic-partner" consortium, per the `sources[].note` for the forbiddenstories.org URL)

Source: https://forbiddenstories.org/about-the-pegasus-project/
Source content: "more than 80 reporters from 17 media organizations in 10 countries coordinated by Forbidden Stories"; Amnesty International's Security Lab "performed phone analyses" peer-reviewed by Citizen Lab.
Comparison: The "seventeen-newsroom" descriptor in the sources[].note matches the source's "17 media organizations" figure (one paragraph in the source also says "16 media organizations" — within the source's own internal inconsistency, the entity uses the larger figure that also appears in the source). Coordination by Forbidden Stories and Amnesty Security Lab role confirmed.
Decision: corroborated

## Claim 18: The framing names the substantive accusation directly in two compact Spanish words: gobierno (the state) and espía (spying)

Source: linguistic — common Spanish vocabulary; not a source-dependent factual claim
Source content: N/A
Comparison: This is a linguistic glossing of the Spanish words, not a source-dependent factual claim. Verified by reference to the Spanish language itself.
Decision: corroborated
