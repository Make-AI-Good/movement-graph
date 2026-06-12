---
entity_id: msg-stop-killer-robots
entity_hash: 787be1aacac5383660a97a40cdf56cb15dd65970
audit_date: 2026-06-11
pass: 2
status: supported
claims_total: 28
claims_corroborated: 7
claims_primary_sourced: 13
claims_single_source: 3
claims_uncorroborated: 5
open_corrections: 0
sources_consulted:
  - https://www.hrw.org/news/2024/08/26/killer-robots-new-un-report-urges-treaty-2026
  - https://www.hrw.org/report/2012/11/19/losing-humanity/case-against-killer-robots
  - https://www.hrw.org/news/2013/04/23/arms-new-campaign-stop-killer-robots
  - https://www.stopkillerrobots.org/news/press-release-urgent-action-needed-to-ban-fully-autonomous-weapons-non-governmental-organizations-convene-to-launch-campaign-to-stop-killer-robots/
  - https://en.wikipedia.org/wiki/Campaign_to_Stop_Killer_Robots
  - https://www.stopkillerrobots.org/the-story-so-far/
  - https://www.stopkillerrobots.org/about-us/
  - https://www.stopkillerrobots.org/
  - https://news.un.org/en/story/2025/05/1163256
  - https://article36.org/updates/ngoconference/
  - https://www.stopkillerrobots.org/news/press-release-focus-on-meaningful-human-control-of-weapons-systems-third-united-nations-meeting-on-killer-robots-opens-in-geneva/
  - https://www.stopkillerrobots.org/news/passing-the-baton/
  - https://www.stopkillerrobots.org/news/new-executive-director/
  - https://www.stopkillerrobots.org/news/164-states-vote-against-the-machine/
  - https://www.stopkillerrobots.org/news/unga-resolution-on-autonomous-weapons-systems-gives-states-historic-opportunity-to-voteagainstthemachine/
  - https://www.penncerl.org/the-rule-of-law-post/magnifying-human-confusion-meaningful-human-control-and-the-ongoing-debate-on-autonomous-weapons/
  - https://fedsoc.org/bio/sunny-gandhi
---

Pass-2 context: pass 1 (2026-05-29) found one correction — the body linked the phrase "UN Secretary-General's August 2024 report" to a URL documenting the July 2023 *A New Agenda for Peace* brief. The Researcher fixed this (commit 991020a3) by replacing the URL with HRW's 26 August 2024 article in both body locations and adding a matching sources[9] entry. The fix is verified RESOLVED (Claims 19–20 below). No open corrections remain.

## Claim 1: "Human Rights Watch and Harvard Law School's International Human Rights Clinic's 19 November 2012 report *Losing Humanity: The Case against Killer Robots*"

Source: https://www.hrw.org/report/2012/11/19/losing-humanity/case-against-killer-robots
Source tier: primary
Source content: "Losing Humanity: The Case against Killer Robots" published by Human Rights Watch and Harvard Law School's International Human Rights Clinic on November 19, 2012.
Comparison: Title, date, and joint authorship all match the report's own page.
Decision: primary-sourced

## Claim 2: report defined "killer robots" as "fully autonomous weapons that could select and engage targets without human intervention"

Source: https://www.hrw.org/report/2012/11/19/losing-humanity/case-against-killer-robots
Source tier: primary
Source content: "Some military and robotics experts have predicted that 'killer robots'—fully autonomous weapons that could select and engage targets without human intervention—could be developed within 20 to 30 years."
Comparison: Quoted definition appears verbatim in the report's Summary.
Decision: primary-sourced

## Claim 3: report called on states to "prohibit the development, production, and use of fully autonomous weapons through an international legally binding instrument"

Source: https://www.hrw.org/report/2012/11/19/losing-humanity/case-against-killer-robots
Source tier: primary
Source content: Recommendations: "Prohibit the development, production, and use of fully autonomous weapons through an international legally binding instrument."
Comparison: Verbatim recommendation present.
Decision: primary-sourced

## Claim 4: campaign established by representatives of seven NGOs at a meeting in New York on 19 October 2012

Source: https://www.stopkillerrobots.org/news/press-release-urgent-action-needed-to-ban-fully-autonomous-weapons-non-governmental-organizations-convene-to-launch-campaign-to-stop-killer-robots/
Source tier: primary
Source content: "The Campaign to Stop Killer Robots was established by representatives of seven of these NGOs at a meeting in New York on 19 October 2012."
Comparison: Count (seven), city, and date match the coalition's own press release exactly.
Decision: primary-sourced

## Claim 5: the seven founding NGOs were "Article 36, Human Rights Watch, the International Committee for Robot Arms Control, IKV Pax Christi, Mines Action Canada, the Nobel Women's Initiative, and the Pugwash Conferences on Science and World Affairs" (body and scalar:sources[1].note)

Source: https://www.stopkillerrobots.org/news/press-release-urgent-action-needed-to-ban-fully-autonomous-weapons-non-governmental-organizations-convene-to-launch-campaign-to-stop-killer-robots/ (plus Wikipedia and the story-so-far page, neither of which enumerates founders)
Source tier: none
Source content: The press release says "seven of these NGOs" — "these" referring to its nine-member Steering Committee list ("five international NGOs Human Rights Watch, International Committee for Robot Arms Control, Nobel Women's Initiative, Pugwash Conferences on Science & World Affairs, and Women's International League for Peace and Freedom, and four national NGOs Article 36 (UK), Association for Aid and Relief Japan, Mines Action Canada, and IKV Pax Christi (The Netherlands)") — but does NOT enumerate which seven attended the October 2012 meeting. Wikipedia's article does not name the founders; the story-so-far page does not either.
Comparison: The entity's seven names are all among the press release's nine steering-committee members, so no source contradicts the list — but no canonical source fetched this session enumerates the seven. Note: pass 1 recorded the press release as naming the seven "exactly"; that was a verification error — the release contains no seven-name list. Honest state is uncorroborated, not error.
Decision: uncorroborated

## Claim 6: "23 April 2013 London global launch" of the campaign

Source: https://www.hrw.org/news/2013/04/23/arms-new-campaign-stop-killer-robots and https://en.wikipedia.org/wiki/Campaign_to_Stop_Killer_Robots
Source tier: primary
Source content: HRW article dated April 23, 2013, dateline London. Wikipedia: "The Campaign to Stop Killer Robots launched in London in April 2013."
Comparison: Date and place corroborated across the HRW announcement and Wikipedia (a Wikipedia-alone-sufficient claim type — date of public event — here with two sources).
Decision: corroborated

## Claim 7: HRW launch quotes — "civil society will lead the way to press governments to ban fully autonomous weapons"; "a preemptive and comprehensive ban on fully autonomous weapons"; (scalar:sources[2].note) "Lethal armed robots that could target and kill without any human intervention should never be built"; "A human should always be 'in-the-loop' when decisions are made on the battlefield"; HRW as the coalition's initial coordinator

Source: https://www.hrw.org/news/2013/04/23/arms-new-campaign-stop-killer-robots
Source tier: primary
Source content: All four quotes present verbatim in the April 23, 2013 article; "Human Rights Watch serves as the initial coordinator of the Campaign to Stop Killer Robots."
Comparison: All quoted tokens and the coordinator role match the source the entity cites.
Decision: primary-sourced

## Claim 8: "Article 36's NGO conference in London the same week supplying the coalition's launch venue" (Article 36 organized the April 2013 London NGO conference)

Source: https://article36.org/updates/ngoconference/
Source tier: primary
Source content: NGO conference "Monday, 22 April 2013 in London," organized by Article 36, designed to launch the international Campaign to Stop Killer Robots.
Comparison: Date (same week as the 23 April launch), city, organizer, and launch connection all match.
Decision: primary-sourced

## Claim 9: Article 36 "carried experience from the Mine Ban Treaty and Convention on Cluster Munitions processes" / supplied the coalition's "humanitarian-disarmament campaigning template inherited from the Mine Ban Treaty and Convention on Cluster Munitions processes" (body and scalar:sources[3].note)

Source: https://article36.org/updates/ngoconference/
Source tier: primary
Source content: The conference page does not mention Mine Ban Treaty or Convention on Cluster Munitions experience; its footer shows Article 36 works with the International Campaign to Ban Landmines and the Cluster Munitions Coalition.
Comparison: The heritage/template claim is plausible and weakly supported by Article 36's coalition affiliations, but no fetched source states that Article 36 carried that campaigning template into the launch. Too indirect to confirm; not contradicted.
Decision: uncorroborated

## Claim 10: long form "Campaign to Stop Killer Robots" and shortened "Stop Killer Robots" used interchangeably as institutional name and home-page brand

Source: https://en.wikipedia.org/wiki/Campaign_to_Stop_Killer_Robots and https://www.stopkillerrobots.org/
Source tier: primary
Source content: Wikipedia: both names used interchangeably ("formally called 'Campaign to Stop Killer Robots,' but it's also referred to as 'Stop Killer Robots'"). The coalition's home page brands itself "Stop Killer Robots".
Comparison: Interchangeable-use claim corroborated by the coalition's own site and Wikipedia.
Decision: corroborated

## Claim 11: scalar:sources[4].note — home-page working subtitle "Less Autonomy, More humanity." and supplementary slogan "Technology should be used to empower all people, not to reduce us."

Source: https://www.stopkillerrobots.org/
Source tier: primary
Source content: The home page renders the tagline (hero text fetched as "Less autonomy. More humanity."; the site's HTML title carries "Stop Killer Robots – Less Autonomy, More humanity.") and the exact slogan "Technology should be used to empower all people, not to reduce us."
Comparison: Slogan verbatim. The subtitle exists on the primary source in both orthographic renderings (title-tag form matches the entity's comma form; hero text uses a period form) — substance confirmed, orthography variance is presentation-level, not a factual contradiction.
Decision: primary-sourced

## Claim 12: "more than 270 international, regional, and national NGO members across 70 or more countries" (body and scalar:sources[5].note)

Source: https://www.stopkillerrobots.org/about-us/
Source tier: primary
Source content: About page currently states "300+ member organisations" across "75+ countries" (footer: "over 70 countries").
Comparison: "More than 270" is a soft lower bound entailed by the current 300+ figure; "70 or more countries" entailed by 75+/over-70. Both hold.
Decision: primary-sourced

## Claim 13: scalar:sources[5].note — "the About page citing '300+ member organisations' in current copy and '250+ member organisations' as a recent retained figure"

Source: https://www.stopkillerrobots.org/about-us/
Source tier: primary
Source content: Current About page shows "300+ member organisations"; no "250+ member organisations" figure was found on the page as fetched this session.
Comparison: The 300+ element is confirmed; the "250+ retained figure" element is not present in current copy (the note's last_checked is 2026-05-15 — the page has likely been updated since). Not a contradiction with a single correct replacement; the note describes page state at check time. The Editor may wish to refresh the note's page-state description on a future sweep, but this is not an error finding.
Decision: uncorroborated

## Claim 14: scalar:sources[6].note — story-so-far page records milestones "from the 2012 founding through the November 2023 UN First Committee resolution, the August 2024 UN Secretary-General report, and the September 2025 42-state joint statement at the Geneva GGE"

Source: https://www.stopkillerrobots.org/the-story-so-far/
Source tier: primary
Source content: Page records the 1 November 2023 First Committee resolution (164-5-8), the 6 August 2024 Secretary-General report, and 5 September 2025: "Brazil delivered a joint statement on behalf of 42 states" ready to move towards negotiations, representing one-third of the 128 CCW states parties.
Comparison: All three named milestones present on the cited page; the 42-state September 2025 Geneva statement matches.
Decision: primary-sourced

## Claim 15: "Article 36's Richard Moyes coined [meaningful human control] in 2013" as a "political concept"

Source: https://www.penncerl.org/the-rule-of-law-post/magnifying-human-confusion-meaningful-human-control-and-the-ongoing-debate-on-autonomous-weapons/ and Article 36 publications (https://article36.org/wp-content/uploads/2016/12/Control-or-Judgment_-Understanding-the-Scope.pdf)
Source tier: mainstream
Source content: "In 2013, Richard Moyes, the head and Managing Partner of the UK disarmament NGO Article 36, coined the phrase 'Meaningful Human Control' (MHC)... Moyes proclaimed that MHC was a 'political concept' designed to get States to a negotiating table."
Comparison: Coiner, date, organization, and "political concept" framing all attested across the CERL analysis and Article 36's own publications.
Decision: corroborated

## Claim 16: scalar:sources[7].note — Stop Killer Robots' 11 April 2016 press release at the third CCW meeting pairs the coalition name and the "meaningful human control" demand

Source: https://www.stopkillerrobots.org/news/press-release-focus-on-meaningful-human-control-of-weapons-systems-third-united-nations-meeting-on-killer-robots-opens-in-geneva/
Source tier: primary
Source content: Press release dated 11 April 2016, third CCW meeting on lethal autonomous weapons in Geneva: "Countries should affirm the necessity of meaningful human control over the capacity to select and attack targets"; "The Campaign to Stop Killer Robots fundamentally objects to permitting machines to take a human life."
Comparison: Date, meeting, and the paired name/demand registers all match.
Decision: primary-sourced

## Claim 17: "UN General Assembly First Committee adopted the first stand-alone resolution on lethal autonomous weapons systems on 1 November 2023 — 164 in favour, 5 against, 8 abstaining"

Source: https://www.stopkillerrobots.org/news/164-states-vote-against-the-machine/ and https://www.stopkillerrobots.org/the-story-so-far/
Source tier: primary
Source content: "First-ever UN General Assembly First Committee resolution on autonomous weapons systems, adopted on November 1, 2023... 164 states in favour and 5 against, with 8 abstentions" (resolution L.56). Story-so-far confirms the same tally and "first" attribution.
Comparison: Date, "first" attribution, and vote tally all match. HRW's August 2024 article independently references the resolution (as resolution 78/241, adopted by the GA plenary in December 2023 after the 1 November First Committee vote).
Decision: corroborated

## Claim 18: "the coalition's #VoteAgainstTheMachine push around the vote"

Source: https://www.stopkillerrobots.org/news/unga-resolution-on-autonomous-weapons-systems-gives-states-historic-opportunity-to-voteagainstthemachine/ and https://www.stopkillerrobots.org/news/164-states-vote-against-the-machine/
Source tier: primary
Source content: The coalition's own pre-vote release is titled "UNGA Resolution on Autonomous Weapons Systems Gives States Historic Opportunity to #VoteAgainstTheMachine"; the post-vote release headline is "164 states Vote Against the Machine at the UN General Assembly". Campaign social-media posts carried the #VoteAgainstTheMachine hashtag around the vote.
Comparison: The hashtag campaign and its pairing with the vote are documented on the coalition's own site.
Decision: primary-sourced

## Claim 19: "[UN Secretary-General's August 2024 report](https://www.hrw.org/news/2024/08/26/killer-robots-new-un-report-urges-treaty-2026) — produced in response to the November 2023 resolution and now widely titled in coalition and press output as a 'Killer Robots' report"; "has urged states to conclude by 2026" (body, two locations)

Source: https://www.hrw.org/news/2024/08/26/killer-robots-new-un-report-urges-treaty-2026 and https://www.stopkillerrobots.org/the-story-so-far/
Source tier: mainstream
Source content: HRW article (August 26, 2024) covers the Secretary-General's report on autonomous weapons released August 6, 2024; headline "Killer Robots: New UN Report Urges Treaty by 2026"; the SG calls for states to conclude by 2026 a treaty "to prohibit weapons systems that function without human control or oversight and that cannot be used in compliance with international humanitarian law"; "The UN report was mandated by a December 2023 UN resolution." Story-so-far independently records the 6 August 2024 report.
Comparison: PASS-1 CORRECTION RESOLVED — the link target now documents the August 2024 report the link text names. The report's existence, date, 2026 deadline, and "Killer Robots" press titling all confirmed. One nuance, not a contradiction: HRW dates the mandating resolution to December 2023 (resolution 78/241's GA plenary adoption) while the entity says "the November 2023 resolution" (the same resolution's First Committee adoption on 1 November 2023, which the entity documents in the same paragraph) — both describe the same instrument at different procedural stages.
Decision: corroborated

## Claim 20: scalar:sources[9].note — "Human Rights Watch's 26 August 2024 article on the UN Secretary-General's report on autonomous weapons systems — primary source for the Secretary-General's call for states to conclude a legally binding instrument to prohibit and regulate autonomous weapons by 2026, produced in response to the November 2023 UNGA First Committee resolution"

Source: https://www.hrw.org/news/2024/08/26/killer-robots-new-un-report-urges-treaty-2026
Source tier: mainstream
Source content: Article dated August 26, 2024; documents the SG's call to conclude by 2026 a treaty to prohibit weapons without human control and regulate others; "mandated by a December 2023 UN resolution that asked the secretary-general to seek the views of countries."
Comparison: This is the new source note added in the Researcher's fix (commit 991020a3). Article date, subject, and the 2026 prohibit-and-regulate call all match. Same November/December procedural nuance as Claim 19 (the mandate is resolution 78/241, First-Committee-adopted 1 November 2023, GA-adopted December 2023) — defensible as written. Fix location if the team ever wants the tighter form: scalar sources[9].note.
Decision: corroborated

## Claim 21: the ban demand is "now operationalised as the prohibition tier of the campaign's two-tier treaty model"

Source: https://www.hrw.org/news/2024/08/26/killer-robots-new-un-report-urges-treaty-2026
Source tier: mainstream
Source content: The SG's call (which the campaign endorses) is two-part — prohibit weapons systems that function without human control or that cannot comply with IHL, and regulate other autonomous weapons systems.
Comparison: The two-tier prohibit/regulate structure matches the HRW account of the treaty model; the campaign's own framing of its model as two-tier rests on this one fetched source this session.
Decision: single-source

## Claim 22: "the first UN General Assembly informal consultations on autonomous weapons in May 2025, at which Secretary-General António Guterres described autonomous weapons as 'politically unacceptable, morally repugnant'"

Source: https://news.un.org/en/story/2025/05/1163256 and https://www.stopkillerrobots.org/the-story-so-far/
Source tier: primary
Source content: UN News (14 May 2025) on the two-day New York meeting quotes Guterres calling autonomous weapons "politically unacceptable" and "morally repugnant" and saying "There is no place for lethal autonomous weapon systems in our world." Story-so-far: 12–13 May 2025, "the first UN General Assembly meeting specifically on autonomous weapons," 96 states participating.
Comparison: Quote verbatim (UN News); "first" attribution and May 2025 timing corroborated by the coalition's history page.
Decision: corroborated

## Claim 23: "the corpus's published [msg-keepiton](msg-keepiton.md) entry explicitly names 'Stop Killer Robots' as the closest sibling pattern"

Source: product/entities/messages/msg-keepiton.md (corpus-internal cross-reference, read this session)
Source tier: primary
Source content: "The pattern's closest analogue inside the corpus is the [Stop Killer Robots](../organizations/org-stop-killer-robots.md) coalition's 'Stop Killer Robots' framing, which similarly combines coalition-name, public chant, and substantive demand into one form."
Comparison: The cross-referenced corpus entry says exactly what the entity claims it says.
Decision: primary-sourced

## Claim 24: "[Encode Justice] — which has worked on U.S. federal restrictions on AI in nuclear-weapons command-and-control"

Source: https://fedsoc.org/bio/sunny-gandhi (with Section 1638 of the FY2025 NDAA documented at https://www.klgates.com/Key-Provisions-on-Artificial-Intelligence-in-Fiscal-Year-2025-NDAA-1-2-2025)
Source tier: database
Source content: Sunny Gandhi (Vice President of Political Affairs at Encode) "spearheaded efforts leading to the first U.S. law establishing guardrails for AI use in nuclear weapons systems, ensuring human control while enabling security benefits." Section 1638 of the FY2025 NDAA upholds "the principle of requiring positive human actions in execution of decisions by the President with respect to the employment of nuclear weapons."
Comparison: Encode's role in the federal AI-nuclear-C2 restriction is attested via its VP's bio; Section 1638's existence and content are independently documented, but Encode's organizational role rests on the one bio source.
Decision: single-source

## Claim 25: Encode Justice "explicitly draw on the 'stop killer robots' public-affairs register in their nuclear and military-AI work"

Source: no canonical source found
Source tier: none
Source content: No fetched source this session documents Encode Justice explicitly invoking the "stop killer robots" register in its nuclear or military-AI advocacy.
Comparison: The claim that Encode's work exists in this space is supported (Claim 24), but the specific assertion that they explicitly draw on the "stop killer robots" register could not be confirmed or refuted from canonical sources fetched this session.
Decision: uncorroborated

## Claim 26: "the Mary Wareham and Nicole van Rooijen leadership track through HRW's Arms Division and the secretariat"

Source: https://www.stopkillerrobots.org/news/passing-the-baton/ and https://www.stopkillerrobots.org/news/new-executive-director/
Source tier: primary
Source content: Mary Wareham is "advocacy director of the Arms Division of Human Rights Watch" and coordinated the Campaign from its inception until March 2021. "Stop Killer Robots is excited to announce its new Executive Director Nicole van Rooijen... Nicole will lead our global civil society coalition in its mission to create new international law on autonomous weapons" (announced 12 March 2025).
Comparison: Both figures' roles match — Wareham through HRW's Arms Division, van Rooijen as Executive Director leading the secretariat. Both sources are the coalition's own site (one publisher), so primary-sourced rather than corroborated.
Decision: primary-sourced

## Claim 27: scalar:sources[8].note — Wikipedia corroborates "the April 2013 London launch, the eight-organisation Steering Committee (Amnesty International, Handicap International, Human Rights Watch, International Committee for Robot Arms Control, Nobel Women's Initiative, Pax Christi International, Pugwash Conferences on Science and World Affairs, and Women's International League for Peace and Freedom), [and] the interchangeable use of 'Campaign to Stop Killer Robots' and 'Stop Killer Robots'"

Source: https://en.wikipedia.org/wiki/Campaign_to_Stop_Killer_Robots
Source tier: tiebreaker
Source content: Wikipedia: "The Campaign to Stop Killer Robots launched in London in April 2013"; steering committee listed as "Amnesty International, Handicap International, Human Rights Watch, International Committee for Robot Arms Control, Nobel Women's Initiative, Pax Christi International, Pugwash Conferences on Science and World Affairs, Women's International League for Peace and Freedom"; both names used interchangeably.
Comparison: The note describes Wikipedia's content, and Wikipedia (fetched this session) contains exactly the eight-organisation list, the launch, and the interchangeable use the note attributes to it. Note: this list is Wikipedia's current steering committee, which differs from the 2012 press release's nine-member founding committee — the entity's note correctly attributes each list to its source, so there is no internal contradiction.
Decision: single-source

## Claim 28: scalar:sources[8].note — Wikipedia corroborates "the Pakistan May 2013 endorsement as the first state to call for prohibition"

Source: https://en.wikipedia.org/wiki/Campaign_to_Stop_Killer_Robots
Source tier: tiebreaker
Source content: Wikipedia lists "Pakistan on 30 May 2013" first among nations calling for prohibition, with a citation link, but the fetched content did not yield an explicit "first state" statement to quote.
Comparison: "Who was first" is a contested-attribution claim type where Wikipedia is tiebreaker-only and a second canonical source is required; no second source was fetched, and even Wikipedia's explicit "first" language could not be quoted from this session's fetch (Pakistan is listed first chronologically, which is consistent but not an explicit attribution).
Decision: uncorroborated
