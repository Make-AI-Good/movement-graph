---
entity_id: voice-joep-meindertsma
entity_hash: 5ee6a0c38700fd519aa55c694ef23f2b0b8ebfd5
audit_date: 2026-06-12
pass: 2
status: supported
claims_total: 17
claims_corroborated: 3
claims_primary_sourced: 13
claims_single_source: 0
claims_uncorroborated: 1
open_corrections: 0
sources_consulted:
  - https://pauseai.info/about
  - https://en.wikipedia.org/wiki/PauseAI
  - https://podcast.clearerthinking.org/episode/207/joep-meindertsma-should-we-pause-ai-development-until-we-re-sure-we-can-do-it-safely/
  - https://longerramblings.substack.com/p/5-joep-meindertsma-on-founding-pauseai-8f3
  - https://www.existentialriskobservatory.org/events/ai-safety-meetup-pauseais-joep-meindertsma/
  - https://pauseai.info/psychology-of-x-risk
  - https://pauseai.info/organization
  - https://www.thehumansurvivalproject.org/post/building-the-ai-pause-button-joep-meindertsma-pause-ai
  - https://pauseai.substack.com/p/traveling-around-the-world-to-pause
  - https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
  - https://news.berkeley.edu/2026/02/06/berkeley-talks-pause-ai/
  - https://www.linkedin.com/posts/joepmeindertsma_the-difficult-psychology-of-existential-risk-activity-7095685628473868288-jWBD
  - https://www.youtube.com/watch?v=BryJy9aL_LQ
  - https://www.corporatecrimereporter.com/news/200/joep-meindertsma-on-the-existential-threat-posed-by-artificial-intelligence/
  - https://github.com/PauseAI/pauseai-website/commits/main/src/posts/psychology-of-x-risk.md
  - https://www.amazon.com/Pause-Die-Humanity-Meindertsma-Interview/dp/B0CV18J91Q
  - https://dezwijger.nl/programma/pauseais-joep-meindertsma
---

Pass-2 note: the entity changed since pass 1 in exactly one place — the Editor's fix (commit 0b37159d) of pass-1's single open correction in sources[10].note. Pass 2 verifies that fix (Claim 12), re-attempts pass-1's uncorroborated claims with fresh fetches (Claims 10, 13, 15, 17 — three of four resolved), and re-states unchanged pass-1 records under the current decision vocabulary (single-source records carry pass-1 fetch quotes; entity text for those claims is unchanged).

## Claim 1: "founded PauseAI in Utrecht in May 2023"

Source: https://pauseai.info/about
Source tier: primary
Source content: "We were founded in Utrecht, Netherlands in May 2023 by Joep Meindertsma"
Comparison: Primary source (org's own about page) names the same founder, city, and month. Wikipedia (https://en.wikipedia.org/wiki/PauseAI) corroborates: "The movement was established in Utrecht in May 2023" and "software entrepreneur Joep Meindertsma". Named-entity definitional fact; two independent canonical sources. (Pass-1 verification; entity text unchanged.)
Decision: corroborated

## Claim 2: "now runs the organisation as Founder and Board Chair following the late-2025 handover of the CEO seat to Maxime Fournes"

Source: https://pauseai.info/about
Source tier: primary
Source content: "Joep Meindertsma - Founder PauseAI Global, Board Chair"; Maxime Fournes listed as "CEO PauseAI Global" under Executive Team.
Comparison: Primary source confirms current roles exactly. The "late-2025" specificity matches the Fournes announcement dated 2 December 2025 (https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes): "Maxime Fournes will be taking on the role of CEO at PauseAI Global". Both confirming sources are PauseAI's own (not independent of each other), so this rests on primary-tier sourcing rather than two-source corroboration. (Pass-1 verification; entity text unchanged.)
Decision: primary-sourced

## Claim 3: "Utrecht-based Dutch software entrepreneur"

Source: https://en.wikipedia.org/wiki/PauseAI
Source tier: primary
Source content: "He founded PauseAI in May 2023, putting his job as the CEO of a software firm on hold."
Comparison: Wikipedia confirms the software-firm-CEO background; pauseai.info/about independently confirms Utrecht and uses the "put his job on hold" framing. Two independent canonical sources (strongest: primary). (Pass-1 verification; entity text unchanged.)
Decision: corroborated

## Claim 4: scalar:sources[1].note "PauseAI's own about page — primary source for ... the Microsoft Brussels lobbying-office protest as the org's first public action"

Source: https://pauseai.info/about
Source tier: primary
Source content: "We began with our first public action, which was a protest outside Microsoft's Brussels lobbying office"
Comparison: Source matches the scalar claim verbatim on substance. Wikipedia corroborates with date: "PauseAI's first public action was to protest in front of Microsoft's Brussels lobbying office in May 2023". Two independent canonical sources. (Pass-1 verification; entity text unchanged.)
Decision: corroborated

## Claim 5: scalar:sources[6].note "ClearerThinking podcast episode 207 ... with host Spencer Greenberg (25 April 2024)"

Source: https://podcast.clearerthinking.org/episode/207/joep-meindertsma-should-we-pause-ai-development-until-we-re-sure-we-can-do-it-safely/
Source tier: primary
Source content: Episode 207; host Spencer Greenberg; dated April 25, 2024.
Comparison: All three specifics (episode number, host, date) match the show's own episode page — one primary source (the publication itself). (Pass-1 verification; entity text unchanged.)
Decision: primary-sourced

## Claim 6: "current frontier AI systems are 'provably not safe' through their jailbreak vulnerability"

Source: https://podcast.clearerthinking.org/episode/207/joep-meindertsma-should-we-pause-ai-development-until-we-re-sure-we-can-do-it-safely/
Source tier: primary
Source content: Meindertsma: "the models out there right now are provably not adhering to the safety constraints that they should be adhering to"; supports it by noting "virtually every large language model that has been released has been jailbroken."
Comparison: The body's "provably not safe" condenses Meindertsma's "provably not adhering to the safety constraints they should be adhering to" within paraphrase tolerance; the jailbreak-vulnerability framing matches. One primary source (the episode transcript itself). (Pass-1 verification; entity text unchanged.)
Decision: primary-sourced

## Claim 7: "the compute-governance route through TSMC and ASML answers the 'bad actors will continue' objection"

Source: https://podcast.clearerthinking.org/episode/207/joep-meindertsma-should-we-pause-ai-development-until-we-re-sure-we-can-do-it-safely/
Source tier: primary
Source content: "Virtually all these chips are created in Taiwan by TSMC. Basically, all the hardware that TSMC is getting is coming from this Dutch company called ASML. NVIDIA is currently producing pretty much all of these AI training chips, like H-100s." Concludes: "the pipeline is very much controllable and centralized."
Comparison: TSMC-and-ASML as the compute-governance chokepoint is named exactly; the controllable-pipeline framing matches "answers the 'bad actors will continue' objection". One primary source. (Pass-1 verification; entity text unchanged.)
Decision: primary-sourced

## Claim 8: "catastrophic-risk strands include cybersecurity (AI finding zero-day exploits at scale), biological hazards (AI-assisted bioweapon creation), and control loss"

Source: https://podcast.clearerthinking.org/episode/207/joep-meindertsma-should-we-pause-ai-development-until-we-re-sure-we-can-do-it-safely/
Source tier: primary
Source content: Three risk strands named — cybersecurity with reference to Stuxnet using "seven zero-day exploits"; bioweapons as capability risk; control loss as AI "going rogue — basically pursuing its own objective without being able to be shut down".
Comparison: All three strands and the zero-day, bioweapon, and shutdown-incapability framings match the body. One primary source. (Pass-1 verification; entity text unchanged.)
Decision: primary-sourced

## Claim 9: scalar:sources[7].note "Consistently Candid Substack episode 5 'Joep Meindertsma on founding PauseAI and strategies for communicating AI risk' with host Sarah Hastings-Woodhouse (22 February 2024)"

Source: https://longerramblings.substack.com/p/5-joep-meindertsma-on-founding-pauseai-8f3
Source tier: primary
Source content: "#5 Joep Meindertsma on founding PauseAI and strategies for communicating AI risk"; published February 22, 2024; host Sarah Hastings-Woodhouse.
Comparison: Episode number, title, host, and date all match the show's own page — one primary source (the publication itself). (Pass-1 verification; entity text unchanged.)
Decision: primary-sourced

## Claim 10: scalar:sources[8].note "For Humanity AI Safety Podcast Episode 14 'Pause AI or Die' with host John Sherman (February 2024)"

Source: https://www.youtube.com/watch?v=BryJy9aL_LQ
Source tier: primary
Source content: The episode's own YouTube publication title (surfaced verbatim in this pass's search of the listing): "\"Pause AI or Die\" For Humanity: An AI Safety Podcast Episode #14, Joep Meindertsma Interview". The show's own distribution page (podcasters.spotify.com/pod/show/john-sherman1) identifies John Sherman as the show's host; the Audible/Amazon listing of the same episode (https://www.amazon.com/Pause-Die-Humanity-Meindertsma-Interview/dp/B0CV18J91Q) carries the identical "Episode #14" title, and podcast-directory listings date the episode's release to February 7, 2024.
Comparison: Pass 1 could not confirm the episode number, host, or date from the YouTube page surface. This pass confirms episode #14 verbatim from the episode's own publication title, John Sherman as host from the show's own hosting page, and the February 2024 date from directory listings — resolving all three previously-unconfirmable specifics. Strongest source is the episode's own publication.
Decision: primary-sourced

## Claim 11: scalar:sources[9].note "The Human Survival Project interview ... (8 February 2024)" and "'seen the dangers of AI firsthand' framing"

Source: https://www.thehumansurvivalproject.org/post/building-the-ai-pause-button-joep-meindertsma-pause-ai
Source tier: primary
Source content: Published February 8, 2024 (with update noted March 6, 2024). Exact phrase appears: "As a software engineer, he has lots of experience with technology and has seen the dangers of AI firsthand."
Comparison: Date and the verbatim "seen the dangers of AI firsthand" framing both confirmed against the publication's own page — one primary source. (Pass-1 verification; entity text unchanged.)
Decision: primary-sourced

## Claim 12: scalar:sources[10].note "Existential Risk Observatory event listing for 'AI Safety Meetup: PauseAI's Joep Meindertsma' at Pakhuis de Zwijger, Amsterdam (18 March 2024)"

Source: https://www.existentialriskobservatory.org/events/ai-safety-meetup-pauseais-joep-meindertsma/
Source tier: primary
Source content: Page heading (re-fetched this pass): "AI Safety Meetup: PauseAI's Joep Meindertsma"; "March 18th, 19.30-21.30 at Pakhuis de Zwijger", Amsterdam. The title does not contain "#2".
Comparison: Pass-1's single open correction — the scalar quoted the title with a "#2" not present in the page heading — was fixed by Editor commit 0b37159d; the scalar's quoted title now matches the cited page's heading verbatim, and date and venue match. (Side note, no action: the venue's own listing at dezwijger.nl titles the event "AI Safety Meetup #2: PauseAI's Joep Meindertsma", so the event was indeed the series' second — but the scalar quotes the ERO listing, which it now reproduces accurately.) One primary source (the host org's own event listing).
Decision: primary-sourced

## Claim 13: "Corporate Crime Reporter July 2025 interview ... (Volume 39, Issue 29(12), 21 July 2025)" and associated content claims (AGI definition, Yudkowsky anthill analogy, ~14% catastrophic-outcome probability framing)

Source: https://www.corporatecrimereporter.com/news/200/joep-meindertsma-on-the-existential-threat-posed-by-artificial-intelligence/
Source tier: none
Source content: The page returned HTTP 403 again this pass (as in pass 1); web.archive.org is unreachable from this audit's fetch tooling. Search-indexed content of the page surfaced this pass partially supports the interview's existence and bibliographic frame — "a complete interview with Joep Meindertsma in Corporate Crime Reporter Volume 39 ... (July 21, 2025, print edition only)" — and the 14%/test-flight framing ("AI researchers' average belief that there's a 14 percent chance superintelligent AI will lead to very bad outcomes like human extinction, with Meindertsma asking whether someone would board a test flight with those crash odds").
Comparison: The interview's existence, date (21 July 2025), volume (39), and the ~14%/airplane-test-flight framing now have partial support from search-indexed content of the named source, strengthening pass-1's null result. But the primary page remains unreachable for direct comparison, the exact issue numbering ("29(12)") cannot be checked, and the AGI-definition and anthill-analogy quotes are not surfaced by any source fetched this pass. Partial confirmation of a composite claim — the honest label remains uncorroborated. Future passes should retry the source.
Decision: uncorroborated

## Claim 14: scalar:sources[11].note PauseAI Substack interview "Traveling around the world to pause AI" (16 September 2024) — Meindertsma interviews Chris Gerrby; activism "across Georgia, the UK, Japan, and San Francisco"

Source: https://pauseai.substack.com/p/traveling-around-the-world-to-pause
Source tier: primary
Source content: Published September 16, 2024; Meindertsma is the interviewer, Gerrby (Swedish PauseAI activist) the interviewee. Intro framing names "countries from the UK to Japan to Georgia"; the transcript explicitly discusses Georgia and San Francisco.
Comparison: Date, interviewer/interviewee roles, and four-country reach in the intro frame are confirmed against the publication's own page — one primary source. (Pass-1 verification; entity text unchanged.)
Decision: primary-sourced

## Claim 15: scalar:sources[11].note Meindertsma's "'dark thoughts about the future' alongside fitting 'all the checkboxes of a really big optimist'" framing

Source: https://pauseai.substack.com/p/traveling-around-the-world-to-pause
Source tier: primary
Source content: Re-fetched this pass; both halves located verbatim. Meindertsma: "You obviously have some really dark thoughts about the future, and so do I, right?" and "Like, I fit all the checkboxes of a really big optimist and I think you're the same, right?"
Comparison: Pass 1 confirmed only the "really big optimist" half. This pass locates "dark thoughts about the future" verbatim in the transcript, spoken by Meindertsma and applied to himself ("and so do I") — exactly the paired self-description the scalar claims. Both halves now verbatim-confirmed against the publication's own page — one primary source.
Decision: primary-sourced

## Claim 16: scalar:sources[4].note and body "PauseAI flagship essay 'The Difficult Psychology of Existential Risk'" — four-stage framework, ~80% normalcy bias, "ridicule, denial and disbelief" progression

Source: https://pauseai.info/psychology-of-x-risk
Source tier: primary
Source content: Four headed sections appear verbatim: "Difficult to bring up", "Difficult to believe", "Difficult to understand", "Difficult to act on". Verbatim: "about 80% of people show symptoms of normalcy bias during disasters". Opening: "Most people initially respond to the topic of AI existential risk with a mix of ridicule, denial and disbelief. The fear often only sets in after a long time of thinking about it." Page title re-confirmed this pass.
Comparison: All three substantive claims (four-stage framework, ~80% normalcy bias rate, ridicule-denial-disbelief-then-fear progression) match the essay's text within paraphrase tolerance. One primary source (the essay itself).
Decision: primary-sourced

## Claim 17: Authorship of "The Difficult Psychology of Existential Risk" essay by Meindertsma — body "PauseAI flagship essay ... which he authored"

Source: https://github.com/PauseAI/pauseai-website/commits/main/src/posts/psychology-of-x-risk.md
Source tier: primary
Source content: The pauseai.info website's own public repository history for the essay's source file: created by "joepio" on May 21, 2023 with commit message "Psychology of x-risk"; joepio made the most subsequent edits ("Flyer, psychology", "Add tweets", "Various improvements", multiple refinements through July 2023), with later smaller contributions by other contributors (typo fixes, a 2024 section update by Pato-desu).
Comparison: Pass 1 found no byline on the essay page and could not establish authorship from the LinkedIn repost. This pass establishes it from the org's own repo history: the file was created and primarily written by GitHub user joepio — Meindertsma's own confirmed handle (the entity's cited profile, github.com/joepio). Later collaborative edits do not displace the authorship claim; the essay page itself still carries no byline, so this rests on one primary source (the org's own version-control record).
Decision: primary-sourced
