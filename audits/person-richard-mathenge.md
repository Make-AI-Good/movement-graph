---
entity_id: person-richard-mathenge
entity_hash: 66550e0345a775c39074b14a92e504a95427791a
audit_date: 2026-06-06
pass: 1
status: supported
claims_total: 20
claims_corroborated: 15
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 5
reclassified_at: 2026-06-10
sources_consulted:
  - https://citizen.digital/article/kenyas-richard-mathenge-makes-time-magazines-list-of-100-most-influential-people-in-ai-n327125
  - https://citizen.digital/tech/kenyan-moderators-behind-chatgpt-want-parliament-to-probe-openai-sama-over-exploitation-n323387
  - https://techcrunch.com/2023/07/14/workers-that-made-chatgpt-less-harmful-ask-lawmakers-to-stem-alleged-exploitation-by-big-tech/
  - https://www.techpolicy.press/checking-on-the-progress-of-content-moderators-in-africa/
  - https://www.business-humanrights.org/en/latest-news/kenya-chatgpt-content-moderators-decry-toll-of-ai-model-training-file-government-petition-for-investigation-on-exploitative-conditions/
  - https://nonprofitquarterly.org/can-african-unions-beat-big-tech/
  - https://www.techworkercommunityafrica.com/our-team
  - https://partnershiponai.org/pai-announces-policy-steering-committee/
  - https://www.foxglove.org.uk/open-letter-to-president-biden-from-tech-workers-in-kenya/
  - https://en.wikipedia.org/wiki/Sama_(company)
---

## Claim 1: "Billy Perrigo's profile recording his age at the time as 38"

Source: https://citizen.digital/article/kenyas-richard-mathenge-makes-time-magazines-list-of-100-most-influential-people-in-ai-n327125
Source content: Citizen Digital's TIME100 AI coverage records "38 years old" and "Kenyan" for Mathenge at the time of the September 2023 list.
Comparison: Body age claim matches the Kenyan-press summary of the TIME profile.
Decision: corroborated

## Claim 2: "former Samasource team lead on the OpenAI ChatGPT toxicity-classification project"

Source: https://www.techpolicy.press/checking-on-the-progress-of-content-moderators-in-africa/
Source content: Mathenge states he was "the designated team lead" and acted as "a bridge between the organization and the team" during his Sama tenure on the OpenAI/ChatGPT classification work.
Comparison: Body claim of team-lead role on the OpenAI/ChatGPT toxicity-classification project matches Mathenge's own statement in the TechPolicy.Press interview.
Decision: corroborated

## Claim 3: "paying less than USD 2 per hour"

Source: https://www.business-humanrights.org/en/latest-news/kenya-chatgpt-content-moderators-decry-toll-of-ai-model-training-file-government-petition-for-investigation-on-exploitative-conditions/ (TIME profile itself returned HTTP 403)
Source content: B&H summary of the Guardian coverage reports the workers were paid "$1.46-$3.74/hour" — range straddles USD 2 but is not the same framing as "less than USD 2".
Comparison: The "less than USD 2" framing in the body is sourced to the TIME profile, which the audit could not fetch (403). B&H corroborates the lower end of the pay range but does not confirm the body's specific framing.
Decision: uncorroborated

## Claim 4: ChatGPT toxicity-classification project "ran from late 2021 until Sama's February 2022 termination of the contract"

Source: https://en.wikipedia.org/wiki/Sama_(company) and others
Source content: Wikipedia's Sama article confirms the OpenAI labelling arrangement existed but does not state when the contract began or when Sama terminated it; the TIME profile (returned 403) and other accessible secondary sources consulted in this pass did not directly confirm the specific late-2021 start or the February 2022 termination date.
Comparison: Specific calendar dates could not be confirmed within this audit pass via canonical sources.
Decision: uncorroborated

## Claim 5: "150-plus African AI workers ... voted at the May 2023 Nairobi summit to establish the African Content Moderators Union"

Source: https://citizen.digital/article/kenyas-richard-mathenge-makes-time-magazines-list-of-100-most-influential-people-in-ai-n327125
Source content: Citizen Digital's TIME100 AI summary records that Mathenge "went public as one of over 150 moderators who voted to establish the union in May" 2023.
Comparison: "150-plus" and the May 2023 founding-vote framing match the Kenyan-press summary of the TIME profile.
Decision: corroborated

## Claim 6: "one of the union's founding committee of six former employees"

Source: https://nonprofitquarterly.org/can-african-unions-beat-big-tech/
Source content: Nonprofit Quarterly (Chidinma Iwu, 1 May 2024) describes the ACMU founding as the work of "a committee of six former employees" of Sama, naming only James Oyange (as committee secretary) explicitly among the six.
Comparison: NPQ confirms the six-person founding-committee size but does not name Mathenge as one of the six. The body's chained inference (Mathenge as a member of the six-person founding committee) is not directly supported by NPQ or by the other sources consulted in this pass.
Decision: uncorroborated

## Claim 7: "serves as [its administrator]"

Source: https://www.techpolicy.press/checking-on-the-progress-of-content-moderators-in-africa/
Source content: Mathenge states he is "a current admin in as far as African Content Moderators Union is concerned."
Comparison: Body claim of ACMU administrator role matches Mathenge's own statement in the TechPolicy.Press interview.
Decision: corroborated

## Claim 8: scalar:affiliations[0].role "co-founder, founding committee member, and administrator"

Source: https://www.techpolicy.press/checking-on-the-progress-of-content-moderators-in-africa/ and https://nonprofitquarterly.org/can-african-unions-beat-big-tech/
Source content: TechPolicy.Press confirms Mathenge's self-described "admin" role only; NPQ confirms the six-person founding committee but does not name him. TIME profile (403 in this pass) names him as "an organizer of the recently formed African Content Moderators Union" per Citizen Digital's summary.
Comparison: Of the three role components in this frontmatter scalar, only "administrator" is directly verified. "Co-founder" and "founding committee member" are plausible-but-unverified inferences from his organizer status and the existence of a six-person founding committee. Scalar path: `affiliations[0].role` on `org-african-content-moderators-union`.
Decision: uncorroborated

## Claim 9: "co-founder and Chief Operating Officer since 2024 of Techworker Community Africa"

Source: https://www.techworkercommunityafrica.com/our-team
Source content: The TCA team page lists Mathenge as "Co-founder and Chief Operating Officer".
Comparison: Body claim matches the primary self-description on the TCA team page.
Decision: corroborated

## Claim 10: "four named petitioners" on the July 2023 parliamentary petition

Source: https://citizen.digital/tech/kenyan-moderators-behind-chatgpt-want-parliament-to-probe-openai-sama-over-exploitation-n323387
Source content: Citizen Digital (Dennis Musau, 12 July 2023) names the lead petitioner as "Richard Mwaura Mathenge" with three co-petitioners "Mophat Ochieng Okinyi, Alex Mwaura Kairu, and Bill Kelvin Mulinya".
Comparison: Body's roster of four named petitioners — Mathenge, Mophat Ochieng Okinyi, Alex Mwaura Kairu, Bill Kelvin Mulinya — matches Citizen Digital exactly.
Decision: corroborated

## Claim 11: "Richard Mwaura Mathenge" (full legal name on the parliamentary petition)

Source: https://citizen.digital/tech/kenyan-moderators-behind-chatgpt-want-parliament-to-probe-openai-sama-over-exploitation-n323387
Source content: Citizen Digital records the lead petitioner as "Richard Mwaura Mathenge".
Comparison: Body claim exactly matches the public-record formulation in the Kenyan press.
Decision: corroborated

## Claim 12: quoted "We were dealing with serious trauma... It was our obligation to reach out to Parliament"

Source: https://citizen.digital/article/kenyas-richard-mathenge-makes-time-magazines-list-of-100-most-influential-people-in-ai-n327125
Source content: Citizen Digital's TIME100 AI summary carries the quote: "We were dealing with serious trauma... It was our obligation to reach out to Parliament" attributed to Mathenge.
Comparison: Body quote matches the Kenyan-press carrying of Mathenge's framing.
Decision: corroborated

## Claim 13: quoted "destroyed me completely"

Source: https://www.business-humanrights.org/en/latest-news/kenya-chatgpt-content-moderators-decry-toll-of-ai-model-training-file-government-petition-for-investigation-on-exploitative-conditions/
Source content: B&H summary of the Guardian's August 2023 coverage attributes the quote to Mathenge directly: "'It has destroyed me completely,' he said", in the surrounding context of him becoming introverted, his physical relationship with his wife suffering, and his moving back in with his parents.
Comparison: Body claim of the "destroyed me completely" quote being Mathenge's framing matches B&H's attribution.
Decision: corroborated

## Claim 14: quoted "This is a win for all content moderators, not just for me"

Source: https://www.techpolicy.press/checking-on-the-progress-of-content-moderators-in-africa/
Source content: TechPolicy.Press carries Mathenge stating: "This is a win for all content moderators, not just for me."
Comparison: Body quote matches TechPolicy.Press verbatim.
Decision: corroborated

## Claim 15: "named to the inaugural TIME100 AI list" in September 2023

Source: https://citizen.digital/article/kenyas-richard-mathenge-makes-time-magazines-list-of-100-most-influential-people-in-ai-n327125
Source content: Citizen Digital records the TIME magazine listing publication as 11 September 2023 and confirms Mathenge's inclusion on the TIME 100 most influential people in AI list.
Comparison: TIME100 AI 2023 listing and September 2023 date match the Kenyan-press summary of the TIME release.
Decision: corroborated

## Claim 16: "listed among the Top 100 Kenyans of 2023"

Source: https://www.techworkercommunityafrica.com/our-team
Source content: TCA's team page records Mathenge as having secured "a spot in the Top 100 Kenyans of 2023".
Comparison: The Top 100 Kenyans 2023 listing claim is sourced only to TCA's own organization page (a self-attestation by an entity Mathenge co-founded); an independent canonical source confirming the listing was not located in this pass.
Decision: uncorroborated

## Claim 17: "in October 2023 was appointed to the inaugural Policy Steering Committee of Partnership on AI under his African Content Moderators Union affiliation"

Source: https://partnershiponai.org/pai-announces-policy-steering-committee/
Source content: Partnership on AI's announcement is dated 12 October 2023 and lists Mathenge as "Organizer, African Content Moderators Union" among the inaugural Policy Steering Committee members.
Comparison: October 2023 appointment date, inaugural-committee framing, and ACMU-affiliation attribution all match the PAI announcement.
Decision: corroborated

## Claim 18: PAI committee includes "Rumman Chowdhury, Alexandra Givens, Sam Gregory, Alondra Nelson, and Irene Solaiman"

Source: https://partnershiponai.org/pai-announces-policy-steering-committee/
Source content: PAI announcement lists Rumman Chowdhury (Humane Intelligence), Alexandra Givens (CDT), Sam Gregory (WITNESS), Alondra Nelson (IAS), and Irene Solaiman (Hugging Face) among the 21 inaugural members.
Comparison: Body roster of named co-committee members matches the PAI announcement exactly.
Decision: corroborated

## Claim 19: "May 2024 Open Letter to President Biden from tech workers in Kenya" had "72 named signatories"

Source: https://www.foxglove.org.uk/open-letter-to-president-biden-from-tech-workers-in-kenya/
Source content: The Foxglove-hosted open letter is dated 22 May 2024 and carries 72 named signatories (plus 25 anonymous additional signatories).
Comparison: Date (May 2024) and 72-named-signatory count match the primary publication.
Decision: corroborated

## Claim 20: Open Letter signatories include "Mophat Okinyi and other ACMU-and-DLA peers" — specifically Joan Kinyua, James Oyange, and Kauna Malgwi

Source: https://www.foxglove.org.uk/open-letter-to-president-biden-from-tech-workers-in-kenya/
Source content: Signatory list confirms Richard Mathenge (#63), Mophat Okinyi (#57), Joan Kinyua (#37), James Oyange (#35), and Kauna Ibrahim Malgwi (#42).
Comparison: All five named peers appear among the 72 named signatories of the open letter.
Decision: corroborated
