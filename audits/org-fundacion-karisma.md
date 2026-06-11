---
entity_id: org-fundacion-karisma
entity_hash: 56575820f51d6ad123e2cd7fbae6697d87724819
audit_date: 2026-05-30
reclassified_at: 2026-06-10
pass: 1
status: corrections-pending
claims_total: 21
claims_corroborated: 16
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 4
sources_consulted:
  - https://blog.karisma.org.co/press-release-01-2024/
  - https://globalnetworkinitiative.org/member/karisma/
  - https://www.eff.org/press/releases/electronic-frontier-foundation-present-annual-eff-awards-carolina-botero-connecting
  - https://blog.karisma.org.co/klab/
  - https://www.indexoncensorship.org/2019/10/fundacion-karisma-tension-free-speech-social-media-big-issues/
  - https://indela.fund/en/al-sur-3/
  - https://blog.karisma.org.co/protocolosoftwareelecciones/
  - https://blog.karisma.org.co/inteligencia-artificial-y-su-regulacion-en-colombia-y-que-hay-de-la-participacion-ciudadana/
  - https://info.karisma.org.co/
---

## Claim 1: "Founded in 2003"

Source: https://globalnetworkinitiative.org/member/karisma/
Source content: "Fundación Karisma, founded in 2003"
Comparison: GNI member profile names 2003 directly. EFF 2024 press release independently confirms 2003. Frontmatter field `founded: 2003` matches.
Decision: corroborated

## Claim 2: "Bogotá-headquartered Colombian civil-society organisation"

Source: https://globalnetworkinitiative.org/member/karisma/
Source content: organization "located in Bogotá, Colombia"
Comparison: Body and frontmatter `location: Bogotá, Colombia` both match the GNI page.
Decision: corroborated

## Claim 3: Carolina Botero "served as Executive Director for more than a decade"

Source: https://www.eff.org/press/releases/electronic-frontier-foundation-present-annual-eff-awards-carolina-botero-connecting
Source content: tenure described as "more than a decade" as Executive Director, departing in 2024
Comparison: Body claim matches EFF framing; press-release-01-2024 also references "more than 10 years" of leadership. Consistent across two canonical sources.
Decision: corroborated

## Claim 4: EFF characterization quote "an outspoken voice fostering freedom of expression, privacy, access to knowledge, justice, and self-determination" (body + scalar:sources[3].note)

Source: https://www.eff.org/press/releases/electronic-frontier-foundation-present-annual-eff-awards-carolina-botero-connecting
Source content: EFF text "transformed the organization into an outspoken voice fostering freedom of expression, privacy, access to knowledge, justice, and self-determination in our digital world"
Comparison: The quoted span in body and in `sources[3].note` matches the EFF text verbatim. Body's surrounding paraphrase "in the digital realm across Latin America" is outside the quotation marks and acceptably extends the source's "in our digital world" to corpus-relevant scope.
Decision: corroborated

## Claim 5: "On 1 February 2024 Botero voluntarily stepped down"

Source: https://blog.karisma.org.co/press-release-01-2024/
Source content: "voluntarily stepping down from her position" effective February 1, 2024
Comparison: Body and `sources[1].note` match.
Decision: corroborated

## Claim 6: "Co-directorship: María Catalina Moreno ... and Juan Diego Castañeda" effective 1 February 2024

Source: https://blog.karisma.org.co/press-release-01-2024/
Source content: "María Catalina Moreno and Juan Diego Castañeda assumed co-leadership roles as of February 1, 2024"
Comparison: Names and effective date match.
Decision: corroborated

## Claim 7: "Moreno, who had led the Social Inclusion line for the previous two and a half years"

Source: https://blog.karisma.org.co/press-release-01-2024/
Source content: Moreno led the Social Inclusion line for "two and a half years" prior to the announcement
Comparison: Match.
Decision: corroborated

## Claim 8: Castañeda "had managed the foundation since September 2023"

Source: https://blog.karisma.org.co/press-release-01-2024/
Source content: Castañeda "held the management position since September 2023"
Comparison: Match.
Decision: corroborated

## Claim 9: Botero "remained with the organisation as an advisor to the new leadership"

Source: https://blog.karisma.org.co/press-release-01-2024/
Source content: Botero will "accompany the transition process as an advisor to the leadership"
Comparison: Match. The companion clause "and as coordinator of the K+LAB digital-security and privacy laboratory" (and the body's later "Post-2024, Carolina Botero coordinates K+LAB in her advisor role") is treated separately in Claim 17 below — neither the press release nor the K+LAB page returned that role assignment in the fetched content.
Decision: corroborated

## Claim 10: Karisma is a "[member of the Global Network Initiative] ... which it joined in 2017"

Source: https://globalnetworkinitiative.org/member/karisma/
Source content: GNI member profile shows "Joined: 2017"
Comparison: Body and `sources[2].note` both match.
Decision: corroborated

## Claim 11: 2019 Index on Censorship Freedom of Expression Award (Digital Activism category)

Source: https://www.indexoncensorship.org/2019/10/fundacion-karisma-tension-free-speech-social-media-big-issues/
Source content: Karisma received the "Index on Censorship Freedom of Expression Award in 2019 for digital activism"
Comparison: Body framing in `sources[5].note` ("Digital Activism category, 2019") matches.
Decision: corroborated

## Claim 12: Index on Censorship characterization quote — `scalar:sources[5].note` "a civil society organisation devoted to encouraging the use of digital technology and enhancing freedom of expression on the internet"

Source: https://www.indexoncensorship.org/2019/10/fundacion-karisma-tension-free-speech-social-media-big-issues/
Source content: article describes Karisma verbatim as "a civil society organisation devoted to encouraging the use of digital technology and enhancing freedom of expression on the internet"
Comparison: Quote in `sources[5].note` matches the source verbatim.
Decision: corroborated

## Claim 13: Al Sur is an "eleven-organisation Latin American ... digital-rights consortium (ADC, CELE, Coding Rights, Derechos Digitales, Karisma, Hiperderecho, IDEC, IPANDETEC, InternetLab, R3D, and TEDIC)" and AI is among its thematic areas

Source: https://indela.fund/en/al-sur-3/
Source content: IndeLA's Al Sur page lists 11 member organizations (ADC, CELE, Coding Rights, Derechos Digitales, Karisma, Hiperderecho, IDEC, IPANDETEC, InternetLab, R3D, TEDIC) and lists artificial intelligence among the thematic areas
Comparison: Membership count, named members, and AI inclusion all match. Body's "and Caribbean" extension of the consortium's geographic scope is not contradicted, though the IndeLA page foregrounds "Latin America"; this is paraphrase tolerance, not a discrepancy.
Decision: corroborated

## Claim 14: K+LAB "was established in 2017 as the first civil-society digital-security laboratory in Colombia"

Source: https://blog.karisma.org.co/klab/
Source content: "Creado en el año 2017 por la Fundación Karisma, K+LAB es el primer laboratorio de seguridad digital y privacidad de Colombia pensado desde y para la sociedad civil"
Comparison: Year, "first," and "civil-society" framing all match. `sources[7].note` quote matches verbatim.
Decision: corroborated

## Claim 15: "The OECD has recognised K+LAB in its policy work on coordinated vulnerability disclosure"

Source: https://blog.karisma.org.co/klab/
Source content: "La Organización para la Cooperación y el Desarrollo Económico (OCDE) reconoció el trabajo de karisma en la construcción de una ruta para la divulgación de vulnerabilidades en Colombia"
Comparison: OECD recognition of Karisma's vulnerability-disclosure work confirmed.
Decision: corroborated

## Claim 16: 10 August 2023 publication of "Inteligencia artificial y su 'regulación' en Colombia — ¿Y qué hay de la participación ciudadana?" — Stanford AI Index reference; "absence of mechanisms for citizen participation" framing

Source: https://blog.karisma.org.co/inteligencia-artificial-y-su-regulacion-en-colombia-y-que-hay-de-la-participacion-ciudadana/
Source content: publication date August 10, 2023; references Stanford's "Artificial Intelligence Index" for Colombia's role in AI public-policy design; verbatim "la ausencia de mecanismos para la participación ciudadana en el desarrollo de estos documentos es un problema"
Comparison: Date, Stanford AI Index reference, and the citizen-participation quote all match (the body's English "the absence of mechanisms for citizen participation in the development of these documents is a problem" is a faithful translation of the Spanish source text).
Decision: corroborated

## Claim 17: "a Consejo de Estado ruling annulling three congressional seats over electoral-software disputes"

Source: https://blog.karisma.org.co/protocolosoftwareelecciones/
Source content: "todo esto se confirmó con el 8 de febrero con la decisión del Consejo de Estado de regresarle tres curules al partido Movimiento Independiente de Renovación Absoluta (MIRA)"
Comparison: The cited source characterizes the Consejo de Estado decision as one to *return* ("regresarle") three seats to the MIRA party — i.e. the ruling restored seats to MIRA after they had been awarded elsewhere on the basis of the disputed counting-software outputs. The body frames the same ruling as *annulling* three congressional seats. Those are opposite-direction characterizations of the same decision; "annulling" implies seats were taken away (from MIRA or anyone else), whereas the cited source describes seats being returned to MIRA. A correction to "restoring three congressional seats to MIRA" (or equivalent prose) requires Researcher judgment, not a mechanical Editor replacement — flag accordingly.
Decision: correction

## Claim 18: Karisma's electoral-software audit produced the conclusion that "the software is vulnerable, has not been designed to be auditable or controllable, and that no independent audit of the scrutiny system has ever been conducted" (also `scalar:sources[8].note` and `scalar:sources[9].note`)

Source: https://blog.karisma.org.co/protocolosoftwareelecciones/
Source content: source references "indicios de la debilidad del sistema híbrido colombiano" and notes the audit team worked "a ciegas" (blindly) due to lack of information about the system; the specific aggregate conclusion "is vulnerable, has not been designed to be controlled, and an independent audit of the scrutiny system had never been conducted" was not surfaced in the fetched content of this URL
Comparison: The phrase quoted in `sources[8].note` and paraphrased in the body could not be located verbatim in the fetched content of the cited URL. The source does carry weaker-form conclusions ("signs of weakness", "blind audit") consistent with the spirit of the body claim, but does not surface the stronger triple ("vulnerable" + "not designed to be controlled" + "no independent audit had ever been conducted") that the entity attributes to it. The claim may be carried in another Karisma publication or in the MOE-published audit-protocol PDF (`sources[9]`), neither of which independently surfaced this conclusion through fetched content in this pass. Without a quotable source for the specific aggregate conclusion, this is at the limit of audit.
Decision: uncorroborated

## Claim 19: Four programme lines named (Civic Participation, Autonomy and Dignity, Social Inclusion, Democratization of Knowledge and Culture)

Source: https://blog.karisma.org.co/press-release-01-2024/ (per `sources[1].note`) and https://info.karisma.org.co/ (the current home page, per `sources[0].note`)
Source content: fetched content of the press release surfaces "Social Inclusion line" and "Autonomy and Dignity line" verbatim; fetched content of the current home page returned only the bare organization name, no programme-line list
Comparison: Two of the four lines are confirmed by name in the press release. The remaining two ("Civic Participation" and "Democratization of Knowledge and Culture") are attributed in `sources[1].note` to the same press release but were not surfaced in the fetched summary, and the current home page fetch did not enumerate them. Fetched-content summaries can omit content present elsewhere on the page, so this is not a clean discrepancy; it is, however, also not independently confirmable from the fetched sources.
Decision: uncorroborated

## Claim 20: Post-2024 "Carolina Botero coordinates K+LAB in her advisor role"

Source: https://blog.karisma.org.co/press-release-01-2024/ and https://blog.karisma.org.co/klab/
Source content: press release confirms Botero's continuing role as an advisor to the new leadership but does not assign her coordination of K+LAB; K+LAB page describes the lab's mandate and work but does not name Botero as its coordinator in the fetched content
Comparison: The advisor-to-leadership half of the body claim is verified (see Claim 9). The "coordinator of K+LAB" half is not confirmed by either fetched source.
Decision: uncorroborated

## Claim 21: Karisma "is also a participant in the international KeepItOn coalition through its parallel Observatorio de Bloqueos de Internet (OBI) project"

Source: no canonical source found in this pass
Source content: the entity's `sources:` list does not include a KeepItOn-coalition page or an OBI page; the `keepiton` tag in frontmatter is unsourced in this entity's source list and the body's KeepItOn / OBI claim was not cross-checked against a canonical KeepItOn or Karisma OBI page in this audit pass
Comparison: No canonical source consulted in this pass supports the KeepItOn participation or the OBI project name. Could be confirmed by a future pass via the Access Now KeepItOn member list or a Karisma OBI landing page; out of scope for this pass.
Decision: uncorroborated
