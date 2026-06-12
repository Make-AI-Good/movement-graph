---
entity_id: camp-access-now-ban-biometric-surveillance-global-2021-ongoing
entity_hash: 1092969ebd50236560b7e33103396bf9b9308c8b
audit_date: 2026-06-11
pass: 4
status: supported
claims_total: 20
claims_corroborated: 3
claims_primary_sourced: 14
claims_single_source: 2
claims_uncorroborated: 1
open_corrections: 0
sources_consulted:
  - https://www.accessnow.org/civil-society-ban-biometric-surveillance/
  - https://www.accessnow.org/campaign/ban-biometric-surveillance/
  - https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
  - https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
  - https://www.codastory.com/authoritarian-tech/global-facial-recognition-ban/
  - https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
  - https://edri.org/our-work/edri-network-launches-public-initiative-against-biometric-mass-surveillance/
---

Pass-4 trigger: entity_hash staled by a single body-token change (Editor applied the pass-3 Claim 16 correction, "October 2020" → "November 2020"). The fix is verified against EDRi's own launch announcement this pass; the correction is cleared and `open_corrections` returns to 0. All claims re-verified against fresh fetches this session.

## Claim 1: "On 7 June 2021, Access Now convened a global open letter signed by more than 175 civil society organisations, activists, researchers, and technologists from 55 countries"

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/ and https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source tier: primary
Source content: Access Now: press release date "7 June 2021"; "over 175 civil society organizations, activists, and researchers". EDRi: "The coalition launched in early June 2021 with over 175 organisations alongside leading academics, technologists and activists, representing an incredible 55 countries."
Comparison: Launch date and 175+ count confirmed by the Access Now launch release; the org count and the 55-country figure independently confirmed by EDRi. Two independent primary sources cover the composite claim. The `outcomes:` frontmatter scalar mirror carries the same figures and is verified.
Decision: corroborated

## Claim 2: "Drafted jointly by Access Now, Amnesty International, European Digital Rights (EDRi), Human Rights Watch, the Internet Freedom Foundation (India), and the Instituto Brasileiro de Defesa do Consumidor (IDEC, Brazil)"

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/
Source tier: primary
Source content: "Access Now, Amnesty International, Internet Freedom Foundation India, European Digital Rights (EDRi), Instituto Brasileiro de Defesa do Consumidor (IDEC), and Human Rights Watch."
Comparison: All six co-drafting organisations confirmed by the campaign's own launch release. The `sources[1].note` frontmatter scalar carries the identical six-organisation list and is verified as a mirror.
Decision: primary-sourced

## Claim 3: Verbatim demand — "prohibit the use of these technologies in publicly accessible spaces, by both public bodies and private entities, where such use could enable mass surveillance or discriminatory targeted surveillance"

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/
Source tier: primary
Source content: "Prohibit the use of these technologies in publicly accessible spaces, by both public bodies and private entities, where such use could enable mass surveillance"
Comparison: Verbatim match (case difference on initial "P" only; this pass's fetch truncates after "mass surveillance" but prior passes confirmed the full clause "or discriminatory targeted surveillance" on the same page). The `sources[1].note` frontmatter scalar carries the same verbatim quote and is verified as a mirror.
Decision: primary-sourced

## Claim 4: "The coalition grew to 178 signatories by 16 June"

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source tier: primary
Source content: Headline figure 178 organisations ("EDRi joins 178 organisations in global call to ban biometric surveillance"); "The coalition launched in early June 2021 with over 175 organisations".
Comparison: The 178 count confirmed by EDRi's own announcement (a co-drafting organisation's primary document), dated 16 June 2021 per prior passes' fetches of the same page. The `outcomes:` frontmatter scalar mirror carries the identical claim and is verified.
Decision: primary-sourced

## Claim 5: "and beyond 200 organisations in the months following launch"

Source: https://www.accessnow.org/campaign/ban-biometric-surveillance/
Source tier: primary
Source content: "More than 200 civil society organizations, activists, technologists, and other experts around the world have already joined together to sign the open letter below." Page last updated December 21, 2021.
Comparison: Campaign hub confirms 200+ signatories as of December 2021. The `outcomes:` frontmatter scalar mirror ("grown to over 200 organisations by the campaign page's last recorded update (December 2021)") is verified.
Decision: primary-sourced

## Claim 6: "the open letter became available in 17+ languages"

Source: https://www.accessnow.org/campaign/ban-biometric-surveillance/
Source tier: primary
Source content: This pass's fetch enumerates 16 languages beyond English: "Spanish, Portuguese, French, Turkish, Assamese, Tamil, Hindi, Gujarati, Bengali, Mandarin, Korean, Japanese, Arabic, Thai, and German, Russian."
Comparison: 16 languages beyond English plus the English original = 17 languages, satisfying the body's "17+" floor. Matches pass-3's enumeration (pass 2's fetch had been unstable at 15–16). The `outcomes:` frontmatter scalar mirror is verified.
Decision: primary-sourced

## Claim 7: Amnesty verbatim quote — "these tools have the capacity to identify, follow, single out, and track people everywhere they go"

Source: https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
Source tier: primary
Source content: "identify, follow, single out, and track people everywhere they go, undermining our human rights"
Comparison: Verbatim match on the quoted span against Amnesty's own press release (the claim is about what that release says, so the release is the primary document). The `sources[2].note` frontmatter scalar mirror is verified.
Decision: primary-sourced

## Claim 8: Amnesty verbatim quote — "The potential for abuse is too great, and the consequences too severe"

Source: https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
Source tier: primary
Source content: "The potential for abuse is too great, and the consequences too severe."
Comparison: Verbatim match. The `sources[2].note` frontmatter scalar mirror is verified.
Decision: primary-sourced

## Claim 9: Amnesty press release cited documented abuse cases in "China, Russia, Myanmar, Argentina, Brazil, the United States, India, Uganda, Kenya, and Thailand"

Source: https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
Source tier: primary
Source content: "China, United States, Russia, England, Uganda, Kenya, Slovenia, Myanmar, United Arab Emirates, Israel, India, Argentina, Brazil, Thailand, and Italy"
Comparison: All ten countries the body enumerates appear in the Amnesty release's list; the source names additional countries (England, Slovenia, UAE, Israel, Italy), but the body's claim is that the ten named were cited, which holds. The `sources[2].note` frontmatter scalar mirror is verified.
Decision: primary-sourced

## Claim 10: EDRi verbatim demand language — "stop their own biometric surveillance practices and adopt laws which prohibit others from doing it, too"

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source tier: primary
Source content: "stop their own biometric surveillance practices and adopt laws which prohibit others from doing it" (this pass's fetch truncates the trailing ", too"; prior passes confirmed the full clause verbatim on the same page).
Comparison: Verbatim match against EDRi's own announcement. The `sources[3].note` frontmatter scalar mirror is verified.
Decision: primary-sourced

## Claim 11: EDRi's framing — the global coalition provides political support for the Reclaim Your Face ECI by countering claims that the ban demand is "unrealistic"

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source tier: primary
Source content: This pass's fetch: "Some EU officials have rejected Reclaim Your Face demands as 'unrealistic,' though the global coalition demonstrates widespread support for the ban." (Pass-3 verbatim: "Whilst some EU policymakers have dismissed the demands of the Reclaim Your Face campaign as unrealistic, this new global coalition shows that there is nothing niche about banning biometric mass surveillance.")
Comparison: Match on framing — EDRi's announcement explicitly frames the global coalition as countering "unrealistic" dismissals of the RYF demand. The `sources[3].note` frontmatter scalar mirror is verified.
Decision: primary-sourced

## Claim 12: Daniel Leufer of Access Now articulated the view that "the window for regulating such technologies has passed"

Source: https://www.codastory.com/authoritarian-tech/global-facial-recognition-ban/
Source tier: mainstream
Source content: "The phrase 'the window for regulating such technologies has passed' appears to be the journalist's paraphrase, not a direct quotation." Leufer's actual quoted words in the article: "If we have cameras capable of running live facial recognition or live gait or voice analysis to detect aggressive behavior littered throughout public spaces, our belief is that there is no way to safely and adequately regulate that and keep it in check."
Comparison: Re-confirmed this pass: the quoted phrase is the journalist's paraphrase of Leufer's position, not his verbatim words, though the article attributes the view to Leufer directly. The body's quotation marks read most naturally as a verbatim Leufer statement; his substantive view (no way to safely regulate) matches. Per the living-person quoted-statement rule this is a judgment-loaded edge with no single-token fix — the resolution requires prose judgment (unquoting or requoting), not a mechanical replacement. The `sources[4].note` frontmatter scalar carries the identical attribution and limitation.
Decision: uncorroborated

## Claim 13: "The three specific deployment categories named for prohibition are: remote facial recognition in publicly accessible spaces; mass tracking via gait analysis and biometric behavioural data; and predictions and inferences from biometric characteristics about protected attributes including gender identity, sexuality, emotional state, and ethnicity"

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/ (with partial corroboration from https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/)
Source tier: primary
Source content: EDRi: "remote facial recognition in public spaces, gait recognition systems, and automated predictions of gender identity, sexuality, emotional state, and ethnicity using biometric data". Amnesty: banning uses that identify or track individuals via facial recognition, gait identification, voice recognition; inferences about gender identity and emotional state.
Comparison: EDRi's announcement (a co-drafting organisation's primary document summarising the open letter) enumerates all three categories including all four protected attributes; Amnesty's release independently confirms gait-based tracking and protected-attribute inferences but its fetched enumeration does not explicitly name sexuality and ethnicity, so full two-source corroboration of the claim as stated is not affirmed. Residual limitation (carried from pass 3): the `sources[0].note` scalar attributes these three categories to the Access Now campaign hub, which this pass's hub fetch again does not surface ("The document does not enumerate three specific technology categories") — the attribution in that scalar remains unconfirmed even though the underlying fact is supported; mirrors in `goals:` and `outcomes:` carry the supported fact.
Decision: primary-sourced

## Claim 14: "its launch in June 2021 followed the European Commission's AI Act proposal by approximately seven weeks" (Significance section); equivalently in `outcomes:` "The campaign's launch followed the European Commission's April 2021 AI Act proposal by approximately seven weeks"

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act and https://www.accessnow.org/civil-society-ban-biometric-surveillance/
Source tier: primary
Source content: Wikipedia: Commission proposal "21 April 2021". Access Now: launch press release dated "7 June 2021".
Comparison: 21 April 2021 to 7 June 2021 is 47 days ≈ 6.7 weeks, rounding to "approximately seven weeks". Both constituent dates canonically confirmed (Wikipedia-alone is sufficient for official-action dates; the launch date is primary-sourced). The `outcomes:` scalar mirror is verified.
Decision: corroborated

## Claim 15: "partial prohibition language on remote biometric identification survived into the final 21 May 2024 EU AI Act"

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
Source tier: tiebreaker
Source content: EU Council unanimous approval "21 May 2024"; the Act bans "real-time remote biometric identification systems in publicly accessible spaces" with exceptions such as law-enforcement use against "a real and present or real and foreseeable threat of terrorist attack."
Comparison: The date and the partial (exception-carrying) prohibition on remote biometric identification in publicly accessible spaces are both confirmed. Wikipedia-alone is sufficient for the official-action date; the prohibition-content characterisation rests on this single source. The `outcomes:` scalar mirror is verified.
Decision: single-source

## Claim 16: "Reclaim Your Face (European Union, EDRi-coordinated) — the European Citizens' Initiative campaign demanding a prohibition on biometric mass surveillance in public space under EU law, launched November 2020"

Source: https://edri.org/our-work/edri-network-launches-public-initiative-against-biometric-mass-surveillance/
Source tier: primary
Source content: "Launched in November 2020, #ReclaimYourFace is a European movement that brings people's voices into the democratic debate"; the same release records the ECI's registration by the European Commission on 7 January 2021 and the demand for "the European Commission to ban biometric mass surveillance, for example the use of live facial recognition in city centers."
Comparison: Pass-3 correction CLEARED. The Editor's fix ("October 2020" → "November 2020", the sole change staling this audit) now matches EDRi's own statement — EDRi is the campaign's coordinator, making this its primary document. The launch month, the ECI mechanism, and the prohibition demand all match the body. No frontmatter scalar carries this date.
Decision: primary-sourced

## Claim 17: "providing a standing 55-country civil-society mandate that national and regional campaigns can invoke" (Significance section)

Source: https://edri.org/our-work/edri-joins-178-organisations-in-global-call-to-ban-biometric-surveillance/
Source tier: primary
Source content: "representing an incredible 55 countries"
Comparison: The 55-country figure matches EDRi's announcement. This pass's Access Now launch-release fetch does not surface a country count, so the figure rests on EDRi alone — one primary source. Internal consistency with the body's lede and the `outcomes:` scalar holds.
Decision: primary-sourced

## Claim 18: Four-actor demand structure — "Governments", "Private companies", "Investors", and "International organisations — including the UN and its specialised agencies"

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/ and https://www.accessnow.org/campaign/ban-biometric-surveillance/
Source tier: primary
Source content: Launch release actor categories: "governmental bodies (through calls to stop public investment), law enforcement agencies, private sector companies..., and investors (urged to pressure funded companies)". Campaign hub: "This campaign is designed to support advocates fighting biometric surveillance at every level, from their city council to the UN."
Comparison: Governments, private companies, and investors are directly confirmed by the launch release (law enforcement subsumed under governments in the body's reading); the international-organisations/UN category is supported via the hub's "city council to the UN" framing rather than a discrete fourth actor enumeration. Both sources are Access Now's own pages — one independent primary source. The `sources[0].note` scalar mirror ("the four-actor demand structure") tracks the same structure.
Decision: primary-sourced

## Claim 19: scalar:participating_orgs — org-amnesty-international listed as a participating organisation

Source: https://www.accessnow.org/civil-society-ban-biometric-surveillance/ and https://www.amnesty.org/en/latest/press-release/2021/06/amnesty-international-and-more-than-170-organisations-call-for-a-ban-on-biometric-surveillance/
Source tier: primary
Source content: Access Now: co-drafting organisations include "Amnesty International". Amnesty's own release announces "Amnesty International and more than 170 organisations call for a ban on biometric surveillance".
Comparison: Amnesty International's participation is confirmed by two independent primary documents — it is one of the six co-drafting organisations and issued its own launch press release. The structured `participating_orgs` entry is consistent with the body's co-drafter list (claim 2).
Decision: corroborated

## Claim 20: "Named coalition members alongside the six co-drafting organisations include Privacy International and Big Brother Watch"

Source: https://www.codastory.com/authoritarian-tech/global-facial-recognition-ban/
Source tier: mainstream
Source content: "Signatories from Asia, Africa, Europe and Latin America include Big Brother Watch and Privacy International."
Comparison: Both organisations are named as coalition signatories in the Coda Story coverage (7 June 2021). One mainstream canonical source; the `sources[4].note` scalar mirror carries the same claim and is verified.
Decision: single-source
