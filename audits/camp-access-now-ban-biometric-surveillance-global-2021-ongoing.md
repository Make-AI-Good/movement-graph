---
entity_id: camp-access-now-ban-biometric-surveillance-global-2021-ongoing
entity_hash: 9c2243088668958beceec12409843b465c79a375
audit_date: 2026-06-01
pass: 2
status: supported
claims_total: 18
claims_corroborated: 14
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 4
sources_consulted:
  - https://www.accessnow.org/civil-society-ban-biometric-surveillance/
  - https://www.accessnow.org/campaign/ban-biometric-surveillance/
  - https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
  - https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
  - https://www.codastory.com/authoritarian-tech/global-facial-recognition-ban/
  - https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
  - https://reclaimyourface.eu/about/
---

## Claim 1: "On 7 June 2021, Access Now convened a global open letter signed by more than 175 civil society organisations, activists, researchers, and technologists from 55 countries"

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/ and https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source content: Access Now: "Date of Press Release: 7 June 2021. Organizations at Launch: Over 175 civil society organizations, activists, and researchers." EDRi: "178 organisations joined the global Ban Biometric Surveillance coalition... 55 countries represented."
Comparison: Launch date and 175+ count confirmed by the Access Now launch release; the 55-country figure is corroborated by EDRi. The Access Now release alone does not name the country count; EDRi supplies it.
Decision: corroborated

## Claim 2: "Drafted jointly by Access Now, Amnesty International, European Digital Rights (EDRi), Human Rights Watch, the Internet Freedom Foundation (India), and the Instituto Brasileiro de Defesa do Consumidor (IDEC, Brazil)"

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/
Source content: "Co-Drafting Organizations: Access Now, Amnesty International, Internet Freedom Foundation India, European Digital Rights (EDRi), Instituto Brasileiro de Defesa do Consumidor (IDEC), Human Rights Watch."
Comparison: All six co-drafting organisations confirmed. The `sources[1].note` frontmatter scalar carries the identical six-organisation list and is verified as a mirror.
Decision: corroborated

## Claim 3: Verbatim demand — "prohibit the use of these technologies in publicly accessible spaces, by both public bodies and private entities, where such use could enable mass surveillance or discriminatory targeted surveillance"

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/
Source content: "Prohibit the use of these technologies in publicly accessible spaces, by both public bodies and private entities, where such use could enable mass surveillance or discriminatory targeted surveillance."
Comparison: Verbatim match (case difference on initial "P" only). The `sources[1].note` frontmatter scalar carries the same verbatim quote and is verified as a mirror.
Decision: corroborated

## Claim 4: "The coalition grew to 178 signatories by 16 June"

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source content: "Announcement date: June 16, 2021. 178 organizations joined the coalition."
Comparison: Match on date and signatory count. The `outcomes:` frontmatter scalar ("the signatory count reached 178 by 16 June 2021") carries the identical claim and is verified as a mirror.
Decision: corroborated

## Claim 5: "and beyond 200 organisations in the months following launch"

Source: https://www.accessnow.org/campaign/ban-biometric-surveillance/
Source content: "More than 200 civil society organizations, activists, technologists, and other experts around the world have already joined together to sign the open letter" (last updated December 21, 2021).
Comparison: Campaign page confirms 200+ signatories as of December 2021. The `outcomes:` frontmatter scalar ("grown to over 200 organisations by the campaign page's last recorded update (December 2021)") carries the same claim and is verified as a mirror.
Decision: corroborated

## Claim 6: "the open letter became available in 17+ languages"

Source: https://www.accessnow.org/campaign/ban-biometric-surveillance/
Source content: This pass's fetch surfaced an internally-inconsistent count from the campaign page — the page's prose claims "15 languages" while the enumerated list (English, Spanish, Portuguese, French, Turkish, Assamese, Tamil, Hindi, Gujarati, Bengali, Mandarin, Korean, Japanese, Arabic, Thai, German) tallies 16. Pass 1 of this audit cited an exact 17-language enumeration from this same URL (including Russian). The campaign page's "We are continuously working to make this open letter available in additional languages" framing makes a stable count from a single fetch unreliable.
Comparison: The body's "17+ languages" floor claim cannot be affirmed against this pass's source content (which surfaces 15–16 languages, not 17+). Whether the page added then removed Russian, the WebFetch summary undercounted, or the page state has otherwise drifted, this audit cannot quote real source text supporting "17+" in this pass. The `outcomes:` frontmatter scalar mirror ("the open letter available in 17+ languages") carries the same limitation.
Decision: uncorroborated

## Claim 7: Amnesty verbatim quote — "these tools have the capacity to identify, follow, single out, and track people everywhere they go"

Source: https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
Source content: "these tools have the capacity to identify, follow, single out, and track people everywhere they go"
Comparison: Verbatim match. The `sources[2].note` frontmatter scalar carries the same verbatim quote and is verified as a mirror.
Decision: corroborated

## Claim 8: Amnesty verbatim quote — "The potential for abuse is too great, and the consequences too severe"

Source: https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
Source content: "the potential for abuse is too great, and the consequences too severe"
Comparison: Verbatim match (case difference on initial "the" only). The `sources[2].note` frontmatter scalar carries the same verbatim quote and is verified as a mirror.
Decision: corroborated

## Claim 9: Amnesty press release cited documented abuse cases in "China, Russia, Myanmar, Argentina, Brazil, the United States, India, Uganda, Kenya, and Thailand"

Source: https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
Source content: "Countries with documented abuses: China, United States, Russia, England, Uganda, Kenya, Slovenia, Myanmar, United Arab Emirates, Israel, India, Argentina, Brazil, and Thailand."
Comparison: All ten countries the body enumerates appear in the Amnesty press release's cited list; the source also names additional countries (England, Slovenia, UAE, Israel), but the body's claim is that the ten named were cited, which holds. The `sources[2].note` frontmatter scalar carries the identical ten-country list and is verified as a mirror.
Decision: corroborated

## Claim 10: EDRi verbatim demand language — "stop their own biometric surveillance practices and adopt laws which prohibit others from doing it, too"

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source content: "stop their own biometric surveillance practices and adopt laws which prohibit others from doing it, too"
Comparison: Verbatim match. The `sources[3].note` frontmatter scalar carries the same verbatim quote and is verified as a mirror.
Decision: corroborated

## Claim 11: EDRi's framing — the global coalition provides political support for the Reclaim Your Face ECI by countering claims that the ban demand is "unrealistic"

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source content: "Some EU policymakers have dismissed the demands of the Reclaim Your Face campaign as unrealistic... the worldwide coalition demonstrates this position has broad support... [provides] additional momentum and evidence of the need for action to present to European institutions negotiating the proposed AI Act."
Comparison: Match on framing — the EDRi announcement explicitly frames the global coalition as countering "unrealistic" dismissals of the RYF ECI demand. The `sources[3].note` frontmatter scalar carries the same framing claim and is verified as a mirror.
Decision: corroborated

## Claim 12: Daniel Leufer of Access Now articulated the view that "the window for regulating such technologies has passed"

Source: https://www.codastory.com/authoritarian-tech/global-facial-recognition-ban/
Source content: Leufer's actual quoted statement in the article is: "If we have cameras capable of running live facial recognition or live gait or voice analysis to detect aggressive behavior littered throughout public spaces, our belief is that there is no way to safely and adequately regulate that and keep it in check." The phrase "the window for regulating such technologies has passed" appears in the article as the journalist's *paraphrase* of Leufer's position, not as a direct Leufer quotation.
Comparison: The body presents the quoted phrase as Leufer's view ("publicly articulated by Access Now's Daniel Leufer as the view that '[the window for regulating such technologies has passed]'"), with quotation marks that read most naturally as Leufer's verbatim statement. The Coda Story article does state the phrase, but as its own framing rather than Leufer's words; Leufer's substantive view (no way to safely regulate) matches, but the verbatim phrasing does not. Per the profile's living-person-quoted-statement source rule, this judgment-loaded edge produces unverifiable rather than a decision call. The `sources[4].note` frontmatter scalar ("Daniel Leufer (Access Now) as the campaign's public spokesperson articulating the 'ban not regulate' position ('the window for regulating such technologies has passed')") carries the identical attribution and the identical limitation.
Decision: uncorroborated

## Claim 13: "The three specific deployment categories named for prohibition are: remote facial recognition in publicly accessible spaces; mass tracking via gait analysis and biometric behavioural data; and predictions and inferences from biometric characteristics about protected attributes including gender identity, sexuality, emotional state, and ethnicity"

Source: https://www.accessnow.org/campaign/ban-biometric-surveillance/ and https://www.accessnow.org/civil-society-ban-biometric-surveillance/
Source content: The campaign hub specifies only the two umbrella categories — "facial recognition" and "remote biometric recognition technologies" — without distinguishing the three subcategories the body enumerates. The Access Now launch release similarly names "facial recognition" and "remote biometric recognition technologies" as the technology categories, without itemising the three subcategories or naming the protected attributes (gender identity, sexuality, emotional state, ethnicity).
Comparison: The body's three-way subcategory enumeration (and the mirrored claim in the `goals:` and `outcomes:` frontmatter scalars and in `sources[0].note` — "the three prohibited technology categories (remote facial recognition; gait/biometric-behavioural tracking; protected-attribute predictions)") cannot be verified as the cited Access Now sources' content; the audit cannot affirm these three subcategories as content of the open letter or campaign page. The substantive claim may originate from another document not in the entity's cited sources.
Decision: uncorroborated

## Claim 14: "its launch in June 2021 followed the European Commission's AI Act proposal by approximately seven weeks" (Significance section); equivalently in `outcomes:` "The campaign's launch followed the European Commission's April 2021 AI Act proposal by approximately seven weeks"

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act and https://www.accessnow.org/civil-society-ban-biometric-surveillance/
Source content: Wikipedia: "The European Commission formally proposed the AI Act on 21 April 2021." Access Now: launch date "7 June 2021."
Comparison: 21 April 2021 to 7 June 2021 is 47 days, or ~6.7 weeks (rounding to seven). The body's direction (launch followed proposal) and magnitude (~7 weeks) match the canonical dates. This claim was a discrepancy in pass 1 (body had said "preceded... by approximately ten weeks"); the audit-D backfill has correctly resolved it. The `outcomes:` frontmatter scalar mirror carries the same corrected claim and is verified.
Decision: corroborated

## Claim 15: "the final 21 May 2024 EU AI Act"

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
Source content: "The EU Council unanimously approved the final regulation on 21 May 2024."
Comparison: 21 May 2024 is correctly identified as the date the EU Council adopted the AI Act. The `outcomes:` frontmatter scalar mirror ("partial prohibition language on remote biometric identification in publicly accessible spaces appeared in the final 21 May 2024 EU AI Act") carries the identical date and is verified.
Decision: corroborated

## Claim 16: "Reclaim Your Face (European Union, EDRi-coordinated) — the European Citizens' Initiative campaign demanding a prohibition on biometric mass surveillance in public space under EU law, launched October 2020"

Source: https://reclaimyourface.eu/about/ (and no other canonical source surfaced for the date in this pass)
Source content: The RYF about page does not surface a launch date in the fetched content; no October 2020 reference appears.
Comparison: The October 2020 launch date for Reclaim Your Face cannot be confirmed against a canonical source in this audit pass. As noted in pass 1, the corpus carries a separate entity `camp-edri-reclaim-your-face-eu-citizens-initiative-2020-2022` whose own audit pass is the appropriate locus to settle this date; this entity's audit cannot resolve a cross-entity date claim without independent canonical confirmation.
Decision: uncorroborated

## Claim 17: "providing a standing 55-country civil-society mandate that national and regional campaigns can invoke" (Significance section)

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source content: "178 organizations joined the coalition... 55 countries represented."
Comparison: 55-country count matches the EDRi figure (corroborated by Access Now's launch release at 175+ orgs and 55 countries). This claim was a discrepancy in pass 1 (body had said "178-country civil-society mandate" — conflating organisation count with country count); the audit-D backfill has correctly resolved it. Body's own lede sentence ("175+ civil society organisations... from 55 countries") and `outcomes:` frontmatter scalar are now internally consistent.
Decision: corroborated

## Claim 18: Four-actor demand structure — "Governments", "Private companies", "Investors", and "International organisations — including the UN and its specialised agencies"

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/ and https://www.accessnow.org/campaign/ban-biometric-surveillance/
Source content: Access Now launch press: "Actors Addressed: Governments, Law enforcement, Private actors/companies, Investors." Campaign hub: "Governments, Private sector" (with bans applied at city, national, and UN levels).
Comparison: The Access Now launch release confirms governments, private companies, and investors as actor categories addressed (with law enforcement subsumed under governments in the body's reading); the UN-level / international-organisation category is named via the campaign hub's "decision makers at... UN levels" framing. The body's four-actor enumeration is substantively supported across the two cited Access Now sources. The `sources[0].note` frontmatter scalar mirror ("the four-actor demand structure (governments, companies, investors, international organisations)") tracks the same structure and is verified.
Decision: corroborated
