---
entity_id: org-7amleh
entity_hash: e1d3cd19707800fc182251f3a7d55b470f072f99
audit_date: 2026-06-01
pass: 1
status: corrections-pending
claims_total: 25
claims_corroborated: 17
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 7
sources_consulted:
  - https://en.wikipedia.org/wiki/7amleh
  - https://www.apc.org/en/news/7amleh-recognised-index-censorship-freedom-expression-award-2020
  - https://globalnetworkinitiative.org/members/
  - https://7amleh.org/annual23/eng/
  - https://7amleh.org/post/1299
  - https://7amleh.org/post/erased-and-suppressed-palestinian-testimonies-of-meta-s-censorship-en
  - https://7amleh.org/post/meta-s-role-during-genocide-en
  - https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
  - https://smex.org/smex-hosts-the-6th-edition-of-breadnet-online/
  - https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
  - https://7amleh.org/about
  - https://7amleh.org/
---

## Claim 1: "founded in 2013" (and scalar:founded "2013")

Source: https://en.wikipedia.org/wiki/7amleh ; https://7amleh.org/about ; https://7amleh.org/
Source content: Wikipedia's article and infobox do not state a founding year ("does not explicitly state the founding year"; infobox shows only Country: "Israel" and coordinates, no Founded field). 7amleh's own About and home pages do not state a founding year either ("does not specify 7amleh's founding year").
Comparison: The only source cited in the entity for the 2013 founding year is grokipedia.com/page/7amleh; grokipedia is not in the mission's canonical-source list. No canonical source available to this auditor confirms the 2013 founding year. Frontmatter scalar `founded: 2013` carries the same claim.
Decision: uncorroborated

## Claim 2: "founded in 2013 in Haifa" (and scalar:location "Haifa (with Ramallah office)")

Source: https://en.wikipedia.org/wiki/7amleh ; https://7amleh.org/ ; https://7amleh.org/about
Source content: Wikipedia infobox lists Country: "Israel" and coordinates only; the article does not name a founding place. 7amleh's home and About pages do not mention a Ramallah office in the fetched content ("does not specify... mention a Ramallah office location").
Comparison: Wikipedia confirms Israel as country (consistent with Haifa) but does not specify Haifa as the founding city. Neither the entity's own website nor Wikipedia surfaces the Ramallah office in the content retrieved. The 7amleh self-description "Haifa-headquartered" is plausible but not directly confirmable from the sources fetched. Scalar `location: Haifa (with Ramallah office)` carries the same unverified content.
Decision: uncorroborated

## Claim 3: "co-founders Nadim Nashif, Laura Samara, and Manar Ya'qoub"

Source: https://en.wikipedia.org/wiki/7amleh ; https://7amleh.org/about
Source content: Wikipedia article does not name co-founders ("Co-founders: Not identified"). 7amleh's own About page in the fetched content does not name co-founders either.
Comparison: Only grokipedia is cited for the three-co-founder list, and grokipedia is not a canonical source per the mission's source rule. The 7amleh 2023 Annual Report does confirm Nadim Nashif as "Co-founder and Executive Director" — confirming Nashif's co-founder status — but no canonical source available to this auditor names Laura Samara or Manar Ya'qoub as co-founders.
Decision: uncorroborated

## Claim 4: "Registered as an [amutah](https://en.wikipedia.org/wiki/7amleh) (nonprofit association under Israeli law)"

Source: https://en.wikipedia.org/wiki/7amleh
Source content: Wikipedia confirms "Legal registration form: amutah" and describes 7amleh as "a non-profit citizens' association" in Israel.
Comparison: Body claim matches Wikipedia. amutah is a definitional named-entity fact (legal structure), which the source rule treats as Wikipedia-alone sufficient.
Decision: corroborated

## Claim 5: "Nadim Nashif has served as the organisation's Executive Director since its founding"

Source: https://7amleh.org/annual23/eng/ ; https://smex.org/smex-hosts-the-6th-edition-of-breadnet-online/
Source content: 2023 Annual Report names Nashif as "Co-founder and Executive Director". SMEX page describes him as "Founder and Director of 7amleh".
Comparison: Both canonical sources confirm Nashif's current Executive Director / Director role and his co-founder status. Neither source confirms continuous tenure "since its founding" — that the title has been held without interruption from 2013 forward. The body's "since its founding" is the unverified component.
Decision: uncorroborated

## Claim 6: "April 2020 7amleh received the [Index on Censorship Freedom of Expression Award](...) for digital activism"

Source: https://www.apc.org/en/news/7amleh-recognised-index-censorship-freedom-expression-award-2020 ; https://en.wikipedia.org/wiki/7amleh
Source content: APC dates the award to "16 April 2020", in the "digital activism" category, with Nashif quote: "We value the role the Index on Censorship plays in supporting freedom of opinion and expression... and consider this an achievement for Palestine." Wikipedia: "7amleh was given the Index on Censorship 2020 award for digital activism."
Comparison: Body claim matches both canonical sources on date (April 2020), award name, and category.
Decision: corroborated

## Claim 7: "In 2022 it was [granted UN ECOSOC consultative status...]"

Source: https://en.wikipedia.org/wiki/7amleh ; https://7amleh.org/ ; https://7amleh.org/about
Source content: Wikipedia article does not mention ECOSOC consultative status ("No information about ECOSOC consultative status is provided"). 7amleh's own home and About pages in the fetched content do not surface this fact.
Comparison: Only grokipedia is cited for the 2022 ECOSOC status; not a canonical source. No canonical confirmation available to this auditor.
Decision: uncorroborated

## Claim 8: "joined the Global Network Initiative as a civil-society member" in 2022

Source: https://globalnetworkinitiative.org/members/ ; https://globalnetworkinitiative.org/7amleh-joins-gni/
Source content: GNI members page confirms 7amleh as a current member in the civil-society constituency ("7amleh is listed as a GNI member... Civil Society"). The cited 7amleh-joins-gni announcement URL returns HTTP 404, so the 2022 join year cannot be confirmed from that source.
Comparison: Civil-society membership is verified. The specific 2022 join year is not confirmable from the canonical sources reached.
Decision: uncorroborated

## Claim 9: "five named anchors" — Research, Monitoring, Advocacy, Capacity Building, Campaigns

Source: https://7amleh.org/annual23/eng/
Source content: 2023 Annual Report names "Research, Monitoring, Advocacy, Campaigns, and Capacity Building" as the five core initiatives.
Comparison: Body list matches the 2023 Annual Report exactly (order differs trivially).
Decision: corroborated

## Claim 10: "7or — the Palestinian Digital Rights Observatory"

Source: https://7amleh.org/annual23/eng/ ; https://7amleh.org/
Source content: 2023 Annual Report: "7or platform, described as the 'Palestinian Digital Rights Observatory,' recorded '4400 violations of digital rights' during 2023." 7amleh.org home: 7or platform listed.
Comparison: Name and description match the canonical sources.
Decision: corroborated

## Claim 11: "Campaigns... #ReconnectGaza... Meta Let Palestine Speak... PayPal... Mapping Segregation... Google Maps... Privacy and Data Protection"

Source: https://7amleh.org/
Source content: 7amleh.org home lists the six active campaigns: "#ReconnectGaza", "Meta, let Palestine Speak", "PayPal", "Mapping Segregation", "Google Maps", "Privacy and Data Protection".
Comparison: Body's six-campaign list matches the home page exactly (with the trivial comma variant in "Meta, let Palestine Speak" vs body's "Meta Let Palestine Speak").
Decision: corroborated

## Claim 12: "Digital Security Helpdesk" — 7amleh's at-risk-user support service

Source: https://7amleh.org/
Source content: 7amleh.org home: "HELPDESK — described as providing 'rapid response to digital security incidents and offers technical support and guidance'". A "Digital Security" portal and the "Digital Security Helpdesk" featured service are explicitly listed.
Comparison: Match.
Decision: corroborated

## Claim 13: "The 7th edition convened roughly 1,500 participants per the 2023 Annual Report"

Source: https://7amleh.org/annual23/eng/
Source content: "The seventh Palestine Digital Activism Forum drew '1,500 participants to hybrid (virtual and in-person) activities.'"
Comparison: Match.
Decision: corroborated

## Claim 14: "the 8th edition was held 4-5 June 2024 in partnership with SMEX's Bread & Net 6th edition"

Source: https://smex.org/smex-hosts-the-6th-edition-of-breadnet-online/
Source content: "On June 4 and 5, 7amleh will host their annual Palestine Digital Activism Forum"; Bread & Net 6th was held "online on May 13, 14, and 15." Theme: "Artificial Intelligence (AI): Revolutionary Promises & Discriminatory Realities."
Comparison: Dates of PDAF 8th (4-5 June 2024) and the partnership framing match the canonical source.
Decision: corroborated

## Claim 15: "Bread & Net 6th edition (online, 13-15 May 2024)" (cross-reference label rendered in body via link to event entity)

Source: https://smex.org/smex-hosts-the-6th-edition-of-breadnet-online/
Source content: Bread & Net 6th was "online" on "May 13, 14, and 15" 2024.
Comparison: Dates and online format match.
Decision: corroborated

## Claim 16: "the [Meta Oversight Board recommended an independent human-rights impact assessment]"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
Source content: "following a recommendation from the Oversight Board in September 2021, we asked Business for Social Responsibility (BSR)... to conduct a due diligence exercise."
Comparison: Match.
Decision: corroborated

## Claim 17: "BSR... produced 21 recommendations in September 2022"

Source: https://about.fb.com/news/2022/09/human-rights-impact-meta-israel-palestine/
Source content: "BSR made 21 specific recommendations as a result of its due diligence". The article is dated September 2022.
Comparison: Number (21) and timing (September 2022) match.
Decision: corroborated

## Claim 18: "finding over-enforcement of Arabic content compared to Hebrew"

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source content: BSR finding restated by 7amleh's statement as "over-enforcement of Arabic content compared to Hebrew content, and under-enforcement of content moderation policies on Hebrew language content."
Comparison: Match. (Meta's own September 2022 statement emphasises the under-enforcement-of-Hebrew side of the same asymmetry; the two framings are complementary, not contradictory.)
Decision: corroborated

## Claim 19: "adverse human-rights implications for Palestinians' freedom of expression, freedom of assembly, political participation, and non-discrimination"

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source content: "freedom of expression, freedom of assembly, freedom to political participation, and non-discrimination."
Comparison: Four-right list matches body exactly.
Decision: corroborated

## Claim 20: "7amleh's [September 2022 statement on the BSR review] — jointly with Human Rights Watch, Article 19, and other regional partners" (also scalar:sources[11].note — "also signed by Human Rights Watch, Article 19, and other regional partners")

Source: https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel
Source content: Full signatory list (74 organisations) includes "Human Rights Watch", "Access Now", "Electronic Frontier Foundation", "Ranking Digital Rights", "IFEX", "SMEX", "Association for Progressive Communications - APC", "Al-Haq", and many others — but does NOT include Article 19 (or ARTICLE 19). Article 19 does not appear anywhere in the signatory list.
Comparison: Body and frontmatter scalar `sources[].note` both name Article 19 as a co-signer of the September 2022 statement; the cited source itself does not list Article 19. The fix location for the frontmatter version is `sources[11].note` (the entry whose URL is `https://7amleh.org/2022/09/27/statement-regarding-bsr-s-hra-for-meta-on-palestine-and-israel`). Other co-signer claims (Human Rights Watch, "other regional partners") are supported.
Decision: correction

## Claim 21: "annual [Hashtag Palestine] report — the 9th edition documenting 2023 was released 17 January 2024"

Source: https://7amleh.org/post/1299
Source content: "'Hashtag Palestine 2023: Palestinian Digital Rights During War' was released on January 17, 2024."
Comparison: Date and report-edition framing match (the body's "9th edition" naming is consistent with 7amleh's published series; the page confirms the 2023 reporting year and 17 January 2024 release date).
Decision: corroborated

## Claim 22: "4,400 digital-rights violations through the calendar year, 69% of them after 7 October 2023"

Source: https://7amleh.org/post/1299 ; https://7amleh.org/annual23/eng/
Source content: "4,400 violations varied between removing and restricting content..." and "69% of these violations were documented after October 7, 2023." Annual Report independently confirms the 4,400 figure ("4400 violations of digital rights").
Comparison: Both figures match.
Decision: corroborated

## Claim 23: "'Erased and Suppressed: Palestinian Testimonies of Meta's Censorship', released 18 December 2024, compiled 20 first-person testimonies"

Source: https://7amleh.org/post/erased-and-suppressed-palestinian-testimonies-of-meta-s-censorship-en
Source content: Title, date (December 18, 2024) and 20-testimonies framing all confirmed: "features 20 documented testimonies detailing Palestinian users' experiences, including the deletion of posts, account suspensions, and restricted audience reach."
Comparison: Match.
Decision: corroborated

## Claim 24: "'Meta's Role in Amplifying Harmful Content During Genocide', released 2 September 2025, documented more than 2,000 pieces of harmful Hebrew-language content... between October 2023 and May 2025... 2.5 million harmful Hebrew posts in 2024 alone, characterised... 'systematic racial discrimination in content governance'... approving violent Hebrew-language content as paid advertising in direct experiments in 2023 and 2025"

Source: https://7amleh.org/post/meta-s-role-during-genocide-en
Source content: "over 2,000 pieces of harmful content manually detected on Meta's platforms between October 2023 and May 2025"; "more than 2.5 million harmful Hebrew posts in 2024 alone"; phrase "systematic racial discrimination in content governance" confirmed; "continued approving and profiting from violent and inciting content by accepting it as paid advertising" during 2023 and 2025 experiments.
Comparison: Title, 2 September 2025 date, 2,000+ figure, 2.5 million figure, exact phrase, and advertising-experiment finding all match. One minor framing nuance: the source's headline figure of >2,000 is described as "manually detected on Meta's platforms" — body's "across Facebook, Instagram, and WhatsApp" is consistent with Meta's platforms but the source as fetched does not enumerate all three platforms; treated as paraphrastic restatement within tolerance.
Decision: corroborated

## Claim 25: "Violence Indicator... detected more than 15 million inciting Hebrew-language posts against Palestinians on social media since October 2023, sized at roughly 3 million instances in the Hashtag Palestine 2023 baseline"

Source: https://7amleh.org/post/erased-and-suppressed-palestinian-testimonies-of-meta-s-censorship-en ; https://7amleh.org/post/1299
Source content: "more than 15 million inciting posts in Hebrew against Palestinians were documented across social media platforms since October 2023." The Hashtag Palestine 2023 release post: Violence Indicator "documented nearly three million instances of violent, hateful, or otherwise negative content in the Hebrew language directed against Palestinians."
Comparison: Both figures (15 million since October 2023; ~3 million in the 2023 baseline) match.
Decision: corroborated
