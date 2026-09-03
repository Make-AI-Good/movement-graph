---
entity_id: camp-controlai-uk-parliamentary-binding-regulation-campaign-2024-ongoing
entity_hash: ae94949b4d61ab91d9a9b8f4a192bd6091698b72
audit_date: 2026-09-03
pass: 2
status: corrections-pending
claims_total: 35
claims_corroborated: 12
claims_primary_sourced: 15
claims_single_source: 2
claims_uncorroborated: 5
open_corrections: 1
sources_consulted:
  - https://controlai.org/statement
  - https://blog.controlai.org/p/what-we-learned-from-briefing-140
  - https://blog.controlai.org/p/100-uk-parliamentarians-acknowledge
  - https://blog.controlai.org/p/85-uk-politicians-support-binding
  - https://blog.controlai.org/p/the-campaign
  - https://blog.controlai.org/p/a-narrow-path
  - https://controlai.org/dip
  - https://controlai.org/about
  - https://controlai.org/engagement-learnings
  - https://www.narrowpath.co/
  - https://www.theepochtimes.com/tech/more-than-100-uk-lawmakers-back-call-for-regulations-on-advanced-ai-5957244
  - https://labourlist.org/2025/12/ai-superintelligence-regulation/
  - https://www.transformernews.ai/p/a-brief-guide-to-anti-ai-activist-stop-ai-pauseai-controlai
  - https://www.lesswrong.com/posts/Xwrajm92fdjd7cqnN/what-we-learned-from-briefing-70-lawmakers-on-the-threat
  - https://www.alignmentforum.org/posts/Z8bthnjW52uTCFGku/a-narrow-path-a-plan-to-deal-with-ai-extinction-risk
  - https://forum.effectivealtruism.org/posts/hYJsycsFE3Rogyt7N/how-effective-is-controlai-s-parliamentary-outreach
  - https://en.wikipedia.org/wiki/ControlAI
  - https://londonfuturists.buzzsprout.com/2028982/episodes/15957825-a-narrow-path-to-a-good-future-with-ai-with-andrea-miotti
  - https://committees.parliament.uk/writtenevidence/148236/pdf/
  - https://dig.watch/updates/uk-lawmakers-push-for-binding-rules-on-advanced-ai
---

Pass-2 note: entity is connective (Campaign); claim surface is edges + hard specifics per `MISSION.md § Auditor § Type-shape awareness`. Delta since pass 1 is one added `strategies:` edge (Claim 2). Domain migration since pass 1: controlai.com → controlai.org, controlai.news → blog.controlai.org (301s); entity `sources:` URLs still resolve via redirect.

## Claim 1: edge — "lead_orgs: org-controlai; participating_orgs: org-controlai" (campaign led and run by ControlAI)

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140; https://www.transformernews.ai/p/a-brief-guide-to-anti-ai-activist-stop-ai-pauseai-controlai
Source tier: primary
Source content: "From November 2024, we began systematically briefing parliamentarians" (ControlAI Substack, García Martínez); Transformer News attributes the UK parliamentary statement campaign to ControlAI throughout.
Comparison: Edge resolves to existing entity org-controlai; every source consulted attributes the campaign to ControlAI alone.
Decision: corroborated

## Claim 2: edge — "strategies: [strat-coalition-lobbying-of-binding-regional-regulation]" (new since pass 1)

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140; https://www.transformernews.ai/p/a-brief-guide-to-anti-ai-activist-stop-ai-pauseai-controlai
Source tier: primary
Source content: Substack: systematic parliamentary briefing for a binding-regulation statement coalition; Transformer: "Unlike Stop AI or PauseAI, ControlAI doesn't organise demonstrations, instead pursuing a more 'inside game' strategy."
Comparison: Edge resolves to an existing strategy entity whose definition (coalition lobbying of a legislative process via "position papers... parliamentary briefings... aligned press" for binding regulation, travelling "to comparable parliamentary systems") matches the campaign's sourced M.O. Whether the classification fit is optimal (single-org UK-national vs. NGO-network regional) is Analyst judgment, out of audit remit; the factual substrate is multi-source confirmed.
Decision: corroborated

## Claim 3: "From November 2024, ControlAI — the international AI-safety advocacy non-profit headquartered in the United Kingdom and founded by Andrea Miotti" + frontmatter start_date 2024-11

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140; https://controlai.org/about
Source tier: primary
Source content: "From November 2024, we began systematically briefing parliamentarians." About page: "Andrea Miotti - Founder & CEO"; "ControlAI operates as a not-for-profit entity in the United Kingdom under company law, and maintains separate status as a 501(c)(4) social welfare organization in the United States."
Comparison: November 2024 systematic-briefing start, UK non-profit form, Miotti founder, international (UK+US) footprint all confirmed by two ControlAI primary pages.
Decision: corroborated

## Claim 4: "By February 2026 the briefing programme had delivered more than 140 introductory briefings (126 directly with parliamentarians and 14 with parliamentary staff)"

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140; https://en.wikipedia.org/wiki/ControlAI
Source tier: primary
Source content: Post dated February 12, 2026: 140 introductory briefings, "Direct to parliamentarians: 126," "Staff-only briefings: 14." Wikipedia: "briefed more than 150 cross-party parliamentarians and the Prime Minister's office since November 2024" (search-index snippet, aggregate figure).
Comparison: 140/126/14 by Feb 2026 exact match to primary; aggregate independently echoed.
Decision: corroborated

## Claim 5: scalar:outcomes — "Between the November 2024 launch of the parliamentary-briefing programme and February 2026, ControlAI delivered more than 150 cross-party UK parliamentary meetings"

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140
Source tier: primary
Source content: "Between September 2024 and February 2026, I delivered over 150 parliamentary meetings"; separately, "From November 2024, we began systematically briefing parliamentarians."
Comparison: The 150+ count and Feb 2026 endpoint match, but the source ties the 150+ meetings to a September 2024 start, while the scalar binds them to the November 2024 launch. Both dates are individually sourced (Sept 2024 first meetings; Nov 2024 systematic-briefing start), so there is no single-token replacement — the fusion of count and window is what fails to match. Scalar path: `outcomes`, opening sentence; same fusion appears nowhere else.
Decision: uncorroborated

## Claim 6: "split roughly 42% MPs, 35% Lords, and 22% devolved-legislature members" (outcomes + body)

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140
Source tier: primary
Source content: "MPs (House of Commons): 42%; Lords (House of Lords): 35%; Devolved legislators (Scotland, Wales, Northern Ireland): 22%."
Comparison: Exact match. (dig.watch, which pass 1 used as second source, now 403s on direct fetch.)
Decision: corroborated

## Claim 7: "a parliamentary-briefing programme launched in November 2024 under UK Parliamentary Engagement Lead Leticia García Martínez"

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140; https://controlai.org/about
Source tier: primary
Source content: Post authored by "Leticia García Martínez, who leads ControlAI's UK parliamentary engagement"; about page lists "Leticia García Martínez - UK Parliamentary Engagement Lead"; "From November 2024, we began systematically briefing parliamentarians."
Comparison: Role and launch month confirmed by two primary pages.
Decision: corroborated

## Claim 8: "wider senior team — Head of Advocacy Mathias Bonde, Media Engagement Lead Grace Gonzales, Operations and Outreach Manager Sophie Toura, Campaigns Strategist Max Salmon" (body + scalar:sources[7].note)

Source: https://controlai.org/about
Source tier: primary
Source content: Current about page lists "Grace Gonzales - Media Engagement Lead" but "Sophie Toura - Head of UK Operations," "Max Salmon - Citizen Engagement Lead," and no Mathias Bonde entry at all.
Comparison: Source drift since the 2026-05-19 citation: Gonzales confirmed; Toura and Salmon now carry different titles; Bonde absent from the page. No canonical source fetched this session confirms the May-2026 titles (a LinkedIn snippet gives Salmon as "Campaign Strategist" — caution tier); nothing contradicts that they held those titles then, so this is not a correction. Fix, if any, requires prose judgment (Researcher), not a token swap. Scalar path: `sources[7].note` (controlai.com/about).
Decision: uncorroborated

## Claim 9: "By late May 2025, ControlAI had delivered more than 70 cross-party UK parliamentary briefings (plus eight additional staffer-only meetings)"

Source: https://www.lesswrong.com/posts/Xwrajm92fdjd7cqnN/what-we-learned-from-briefing-70-lawmakers-on-the-threat
Source tier: primary
Source content: Post dated 27 May 2025: "Over 70 cross-party UK parliamentarians briefed between late 2024 and mid-May 2025"; "Eight sessions attended exclusively by parliamentary staffers."
Comparison: Exact match. The cited original (controlai.org/engagement-learnings) now renders a metadata-only shell on fetch; the LessWrong mirror of the same García Martínez write-up carries the full text and is the entity's own report (primary).
Decision: primary-sourced

## Claim 10: "split roughly evenly between MPs, House of Lords members, and members of the devolved legislatures (the Scottish Parliament, the Senedd, and the Northern Ireland Assembly)"

Source: https://www.lesswrong.com/posts/Xwrajm92fdjd7cqnN/what-we-learned-from-briefing-70-lawmakers-on-the-threat
Source tier: primary
Source content: "Just over one-third were MPs, a similar share were members of the House of Lords, and just under one-third came from devolved legislatures."
Comparison: "Roughly evenly" matches the one-third/one-third/one-third pattern; the three named legislatures match.
Decision: primary-sourced

## Claim 11: "Most briefings involved two ControlAI team members"

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140
Source tier: primary
Source content: "Most meetings involved two ControlAI team members, with occasional solo attendance."
Comparison: Match.
Decision: primary-sourced

## Claim 12: "the format was a roughly 30-minute introductory session ... ending with an invitation to sign the campaign statement and, when the lawmaker engaged further, a follow-up offer to discuss the draft bill"

Source: https://blog.controlai.org/p/what-we-learned-from-briefing-140; https://www.lesswrong.com/posts/Xwrajm92fdjd7cqnN/what-we-learned-from-briefing-70-lawmakers-on-the-threat
Source tier: none
Source content: Neither post specifies a ~30-minute session; the 70+ post mentions a "45-minute briefing" as a reference point for value given limited capacity. The statement-signing ask is supported ("encourage them to take a public stance"), but no fetched source carries the 30-minute figure or a draft-bill follow-up offer.
Comparison: The 30-minute duration and the draft-bill follow-up mechanics are unsupported by any source fetched this session; the adjacent 45-minute reference is not clean enough to assert a replacement token.
Decision: uncorroborated

## Claim 13: 'conversion rate "more than one in three lawmakers we brief" ... with 20-plus cross-party parliamentarians signing inside the first three months' (body + scalar:sources[6].note)

Source: https://controlai.org/dip; https://www.lesswrong.com/posts/Xwrajm92fdjd7cqnN/what-we-learned-from-briefing-70-lawmakers-on-the-threat
Source tier: primary
Source content: DIP page: "more than one in three lawmakers we brief" supported binding regulation, with "20 cross-party UK parliamentarians" publicly endorsing within three months. 70+ post: "when presented with a clear ask, 1 in 3 lawmakers we met chose to take a public stance by supporting our campaign."
Comparison: Both figures confirmed on two ControlAI primary pages (not independent of each other, hence not corroborated-tier).
Decision: primary-sourced

## Claim 14: "By mid-2025 the count stood at approximately 37 signatories" (body + scalar:outcomes "~37 backers by mid-2025")

Source: https://blog.controlai.org/p/85-uk-politicians-support-binding; https://forum.effectivealtruism.org/posts/hYJsycsFE3Rogyt7N/how-effective-is-controlai-s-parliamentary-outreach
Source tier: primary
Source content: 85-post (6 Nov 2025): "more than doubled from 37 to over 85!" — no date attached to the 37 baseline. EA Forum analysis charts signatory growth Jan 2025–May 2026 but "specific intermediate counts and dates are not labeled."
Comparison: The 37 baseline is confirmed; no fetched source dates it to mid-2025. The "mid-2025" timing token is unverifiable this session.
Decision: uncorroborated

## Claim 15: 'On 6 November 2025 the Substack milestone post recorded that the figure had "more than doubled from 37 to over 85"'

Source: https://blog.controlai.org/p/85-uk-politicians-support-binding
Source tier: primary
Source content: Post dated Nov 06, 2025: "the number of politicians who've backed our campaign statement has more than doubled from 37 to over 85!"
Comparison: Date and both figures exact match.
Decision: primary-sourced

## Claim 16: "Viscount Camrose (former Minister for AI), Lord Browne of Ladyton (former Defence Minister), Baroness Kidron OBE, and Sir John Whittingdale OBE MP (former Minister of State for the Department of Science, Innovation and Technology)"

Source: https://blog.controlai.org/p/85-uk-politicians-support-binding
Source tier: primary
Source content: "Viscount Camrose: 'former Minister for AI'; Lord Browne of Ladyton: 'former Defence Minister'; Baroness Kidron OBE; Sir John Whittingdale OBE, MP: 'former Minister of State for the Department of Science, Innovation and Technology.'"
Comparison: All four names and titles match.
Decision: primary-sourced

## Claim 17: 'At that point ControlAI reported it had delivered "over 120 briefings to lawmakers"'

Source: https://blog.controlai.org/p/85-uk-politicians-support-binding
Source tier: primary
Source content: "Members of our team have now given over 120 briefings to lawmakers."
Comparison: Match.
Decision: primary-sourced

## Claim 18: "On 11 December 2025, ControlAI announced the campaign had passed the 100-signatory threshold ... described by ControlAI as the first time a cross-party coalition of UK parliamentarians had publicly acknowledged the extinction threat from advanced AI"

Source: https://blog.controlai.org/p/100-uk-parliamentarians-acknowledge; https://www.theepochtimes.com/tech/more-than-100-uk-lawmakers-back-call-for-regulations-on-advanced-ai-5957244
Source tier: primary
Source content: Post dated December 11, 2025; "over 100" UK parliamentarians; "the world's first such coalition to recognize the threat posed by AI." Epoch Times (12/12/2025): over 100 UK lawmakers backing the campaign.
Comparison: Date, count, and first-coalition framing confirmed by primary plus independent mainstream coverage.
Decision: corroborated

## Claim 19: "naming Alex Sobel MP, Lord Goldsmith of Richmond Park, the Lord Bishop of Oxford, Viscount Camrose, and Lord Browne among the milestone signatories"

Source: https://blog.controlai.org/p/100-uk-parliamentarians-acknowledge
Source tier: primary
Source content: "Named signatories: Alex Sobel MP, Lord Goldsmith of Richmond Park, Lord Bishop of Oxford, Viscount Camrose (former AI Minister), Lord Browne (former Secretary of State for Defence)."
Comparison: All five names confirmed in the announcement.
Decision: primary-sourced

## Claim 20: 'Andrea Miotti's framing of the moment in the announcement was that the campaign had reached this milestone "within a year" with "more...joining every week"'

Source: https://www.theepochtimes.com/tech/more-than-100-uk-lawmakers-back-call-for-regulations-on-advanced-ai-5957244
Source tier: mainstream
Source content: Miotti quoted: "more are joining every week"; the article frames the support growth "within a year-long timeframe."
Comparison: Both quoted elements confirmed as Miotti's via Epoch Times. This session's extraction of the announcement itself surfaced no Miotti quote (pass 1 recorded it there), so the "in the announcement" location rests on the pass-1 record; the quotes themselves are confirmed.
Decision: single-source

## Claim 21: "The Guardian published an exclusive on the milestone the same week"

Source: https://en.wikipedia.org/wiki/ControlAI; https://blog.controlai.org/p/100-uk-parliamentarians-acknowledge
Source tier: primary
Source content: Wikipedia citation: "Booth, Robert (8 December 2025). 'Scores of UK parliamentarians join call to regulate most powerful AI systems'. The Guardian." Announcement post notes "an additional MP joining after initial Guardian coverage."
Comparison: Guardian article confirmed, dated 8 December 2025 — same calendar week as the 11 December announcement. The "exclusive" descriptor traces to dig.watch (pass-1 record; dig.watch now 403s) and is not re-confirmed, but the load-bearing facts (Guardian, that week, on the milestone) hold.
Decision: corroborated

## Claim 22: "coverage was carried by The Epoch Times (12 December 2025), TechRepublic, and City A.M."

Source: https://www.theepochtimes.com/tech/more-than-100-uk-lawmakers-back-call-for-regulations-on-advanced-ai-5957244
Source tier: mainstream
Source content: Epoch Times: "Publication Date: 12/12/2025 (Updated: 12/15/2025)." Search index: TechRepublic, "UK Lawmakers Call for Tougher AI Controls"; City A.M., December 9, 2025, "More than 100 UK lawmakers call for AI regulation to prevent extinction risk."
Comparison: All three outlets' coverage confirmed (Epoch by direct fetch; TechRepublic and City A.M. via search-index titles/snippets).
Decision: corroborated

## Claim 23: 15 December 2025 LabourList op-ed by Alex Sobel (Leeds Central and Headingley), title, ControlAI/100-coalition citation, superintelligence-illegal + AI Security Institute as regulator + Labour manifesto delivery

Source: https://labourlist.org/2025/12/ai-superintelligence-regulation/
Source tier: primary
Source content: "15th December, 2025"; "Alex Sobel MP, Leeds Central and Headingley"; title "AI superintelligence regulation is what we owe voters of this generation and those to come"; cites "a statement by the UK non-profit ControlAI" backed by "a coalition of more than 100 cross-party parliamentarians"; "The AI Security Institute is well positioned to become the regulator of choice"; invokes Labour's promise to "ensure the safe development and use of AI models by introducing binding regulation."
Comparison: Every element matches the op-ed itself — the defining document for this claim.
Decision: primary-sourced

## Claim 24: "By May 2026 the named-signatory list on the live campaign-statement page included [16 named MPs/peers/faith leaders with party labels]" (body + scalar:outcomes)

Source: https://controlai.org/statement; https://blog.controlai.org/p/100-uk-parliamentarians-acknowledge; https://blog.controlai.org/p/85-uk-politicians-support-binding
Source tier: primary
Source content: Current statement page lists 14 of the 16 with matching party labels (Dodds, McDonnell, Sobel — Labour; Whittingdale, Camrose — Conservative; Hobhouse — Lib Dem; Denyer — Green; Lake — Plaid Cymru; Blackman — SNP; Hanna — SDLP; Eastwood — Alliance; Kidron — Crossbench; Goldsmith — Conservative; Bishop of Hereford). Lord Browne of Ladyton and the Lord Bishop of Oxford are absent from the current page but are named signatories in the Nov/Dec 2025 milestone posts.
Comparison: The claim is time-indexed to May 2026; 14/16 confirmed on the live page and the remaining two confirmed as signatories by primary milestone posts. Current-page drift (two names no longer listed) noted; does not contradict the May-2026 claim.
Decision: primary-sourced

## Claim 25: "ControlAI has prepared a draft AI bill with parliamentary lawyers ... and presented it at the Prime Minister's office" (+ scalar:sources[0].note)

Source: https://controlai.org/statement
Source tier: primary
Source content: "With the assistance of top Parliamentary lawyers, we prepared a full draft bill and presented it to No. 10."
Comparison: Confirmed by the statement page. Note for the Editor: the body hyperlinks this fact partly to the Epoch Times article, which does not mention the draft bill or No. 10 — the fact stands on the primary source; the link placement is a body-citation issue, not a factual error.
Decision: primary-sourced

## Claim 26: "Andrea Miotti and Steven Adler submitted ControlAI's written evidence RAI0031 to a UK parliamentary inquiry on AI regulation"

Source: https://committees.parliament.uk/writtenevidence/148236/pdf/; https://policymogul.com/committee-publication/28878/
Source tier: primary
Source content: Document title (search index; direct fetch 403s): "WRITTEN EVIDENCE SUBMITTED BY ANDREA MIOTTI AND STEVEN ADLER (RAI0031)." Policymogul: "Andrea Miotti (Founder and CEO at ControlAI), and Steven Adler (Machine Learning Researcher... formerly OpenAI...) (RAI0031)" — submitted to the Joint Committee on Human Rights inquiry "Human Rights and the Regulation of AI," September 2025.
Comparison: Authors, reference number, and inquiry confirmed; "a UK parliamentary AI-regulation inquiry" is a fair description of the JCHR human-rights-and-regulation-of-AI inquiry. Resolves pass-1's uncorroborated Claim 24.
Decision: corroborated

## Claim 27: DIP four pillars — "ban deliberate superintelligence development; prohibit dangerous AI capabilities such as automated AI research and hacking; require companies to demonstrate that AI systems will not use forbidden capabilities before deployment; and licence advanced AI development"

Source: https://controlai.org/dip
Source tier: primary
Source content: "Banning deliberate superintelligence development; Prohibiting dangerous capabilities including 'automated AI research and hacking'; Requiring companies to demonstrate systems won't use forbidden capabilities before deployment; Establishing licensing for advanced AI development."
Comparison: All four pillars match.
Decision: primary-sourced

## Claim 28: "The UK campaign is, in ControlAI's own framing, the pilot deployment of the Direct Institutional Plan ahead of international scaling"

Source: https://controlai.org/dip
Source tier: primary
Source content: "The organization frames the UK effort as a foundation for broader impact... expanding similar approaches to the US and supporting parallel efforts internationally."
Comparison: UK-pilot-for-international-scaling framing confirmed.
Decision: primary-sourced

## Claim 29: "A Narrow Path ... by Miotti, Tolga Bilge, Dave Kasten, and James Newport"

Source: https://www.narrowpath.co/
Source tier: primary
Source content: "Andrea Miotti, Tolga Bilge, Dave Kasten, James Newport."
Comparison: All four authors listed on the plan's own site.
Decision: primary-sourced

## Claim 30: "A Narrow Path plan, published 19 March 2026" (body §2 + scalar:sources[13].note "published 19 March 2026")

Source: https://blog.controlai.org/p/a-narrow-path; https://en.wikipedia.org/wiki/ControlAI; https://www.alignmentforum.org/posts/Z8bthnjW52uTCFGku/a-narrow-path-a-plan-to-deal-with-ai-extinction-risk
Source tier: primary
Source content: ControlAI's own announcement post, dated "Oct 02, 2024": A Narrow Path "is now available." Wikipedia: "In October 2024, Miotti and others published A Narrow Path." Alignment Forum presentation by the authors dated "7th Oct 2024"; London Futurists podcast episode discussing the published plan dated October 21, 2024.
Comparison: The plan was published 2 October 2024 — seventeen months before the entity's "19 March 2026." Four mutually independent sources place publication in early October 2024; nothing supports a March 2026 date (narrowpath.co shows only a rolling metadata timestamp, which pass 1 already flagged as unstable). Single correct replacement: "19 March 2026" → "2 October 2024", in body § "The campaign statement and the policy ask" and in scalar `sources[13].note` (narrowpath.co). Mechanical token swap — Editor-applicable.
Decision: correction

## Claim 31: Narrow Path three phases — "a twenty-year moratorium on superintelligence development (Phase 0: Safety), an international oversight architecture (Phase 1: Stability), and the eventual development of safe-by-design transformative AI (Phase 2: Flourishing)"

Source: https://www.narrowpath.co/; https://www.alignmentforum.org/posts/Z8bthnjW52uTCFGku/a-narrow-path-a-plan-to-deal-with-ai-extinction-risk
Source tier: primary
Source content: narrowpath.co: "Phase 0 Safety: Prevent the Development of Artificial Superintelligence for 20 Years"; "Phase 1 Stability: Build an International AI Oversight System that Does Not Collapse"; "Phase 2 Flourishing: Build Controllable, Transformative AI." AF post: measures should "prevent anyone from developing artificial superintelligence for the next 20 years."
Comparison: Phases and 20-year horizon confirmed by the plan's site and the authors' own presentation.
Decision: corroborated

## Claim 32: "all anchored on a compute-threshold licensing regime triggered at training runs above 10^25 FLOP"

Source: https://www.narrowpath.co/; https://blog.controlai.org/p/a-narrow-path; https://committees.parliament.uk/writtenevidence/148236/pdf/
Source tier: primary
Source content: narrowpath.co: no compute threshold mentioned. Announcement post: "a licensing regime to monitor and control these advanced AI systems," no numerical threshold. RAI0031 (search snippet): ControlAI "proposes... a licensing requirement triggered when systems are trained above a compute threshold of 10^25 FLOP."
Comparison: The 10^25 FLOP licensing threshold is confirmed as ControlAI policy (RAI0031), but no fetched source attaches it to A Narrow Path specifically; the figure may live in the full plan PDF, which was not parseable this session. As at pass 1, the anchoring claim cannot be confirmed or refuted.
Decision: uncorroborated

## Claim 33: theory of change — "articulated by Andrea Miotti and Tolga Bilge in the 18 September 2025 Substack post 'The Campaign' ... public education on superintelligence risk paired with frictionless civic-engagement tooling — including a public action page enabling constituents to email their MP in under 17 seconds"; "The campaign explicitly does not organise street protests"

Source: https://blog.controlai.org/p/the-campaign; https://www.transformernews.ai/p/a-brief-guide-to-anti-ai-activist-stop-ai-pauseai-controlai
Source tier: primary
Source content: Post "Sep 18, 2025" by Tolga Bilge and Andrea Miotti: "We provide the public the information to learn about the problem, and tools to enable citizens to make a difference"; contact capability "in as little as 17 seconds." Transformer: "ControlAI doesn't organise demonstrations."
Comparison: Date, authors, two-pronged theory, and no-protests posture confirmed by primary plus independent coverage. Minor wording: source says "in as little as 17 seconds" vs. body "in under 17 seconds" — within paraphrase tolerance, noted for precision.
Decision: corroborated

## Claim 34: 'what Transformer News, in its 28 November 2025 comparative guide, characterised as ControlAI's "inside game," distinguishing it from PauseAI's street-protest ... and from Stop AI's civil-disobedience tactics at lab sites' + Transformer naming the UK statement ControlAI's most notable achievement (scalar:sources[11].note)

Source: https://www.transformernews.ai/p/a-brief-guide-to-anti-ai-activist-stop-ai-pauseai-controlai
Source tier: primary
Source content: "November 28, 2025"; "Unlike Stop AI or PauseAI, ControlAI doesn't organise demonstrations, instead pursuing a more 'inside game' strategy"; PauseAI: organized protests at corporate offices; Stop AI: "direct action civil disobedience, with members arrested for blocking OpenAI's doors"; "the organization's most notable achievement getting UK MPs and Lords to sign a statement on AI's extinction risk."
Comparison: All elements match the article itself — the defining document for this attributed characterisation.
Decision: primary-sourced

## Claim 35: scalar:sources[12].note — dig.watch "confirms ... the campaign's call on Prime Minister Keir Starmer to distance the UK from the US stance against strict federal AI rules, and Jaan Tallinn's named backing of ControlAI"

Source: https://dig.watch/updates/uk-lawmakers-push-for-binding-rules-on-advanced-ai
Source tier: database
Source content: Via search snippets (direct fetch now 403s): the campaign "urges Prime Minister Keir Starmer to distance the UK from the US stance against strict federal AI rules"; "backed by tech figures including Skype co-founder Jaan Tallinn."
Comparison: Both elements of the dig.watch summary confirmed via search snippets of the same page. Scalar path: `sources[12].note`.
Decision: single-source
