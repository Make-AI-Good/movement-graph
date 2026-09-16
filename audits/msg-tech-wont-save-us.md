---
entity_id: msg-tech-wont-save-us
entity_hash: 1a80c0d680c4d62bdb20b6720048ca5dabd545f6
audit_date: 2026-09-16
pass: 1
status: corrections-pending
claims_total: 25
claims_corroborated: 10
claims_primary_sourced: 3
claims_single_source: 3
claims_uncorroborated: 6
open_corrections: 3
sources_consulted:
  - https://www.techwontsave.us/about
  - https://www.techwontsave.us/
  - https://www.techwontsave.us/episodes
  - https://radicalurbanist.substack.com/p/introducing-tech-wont-save-us
  - https://ssir.org/articles/entry/disrupting_the_gospel_of_tech_solutionism_to_build_tech_justice
  - https://ssir.org/putting_the_public_interest_in_front_of_technology
  - https://www.hachettebookgroup.com/titles/evgeny-morozov/to-save-everything-click-here/9781610393706/
  - https://blogs.lse.ac.uk/lsereviewofbooks/2013/05/01/book-review-to-save-everything-click-here-the-folly-of-technological-solutionism/
  - https://lareviewofbooks.org/article/the-god-that-failed-evgeny-morozovs-to-save-everything-click-here/
  - https://www.techpolicy.press/big-tech-will-not-save-us-from-the-climate-crisis/
  - https://nonprofitquarterly.org/they-say-climate-tech-will-save-us-but-who-will-save-us-from-climate-tech/
  - https://www.versobooks.com/products/2795-road-to-nowhere
  - https://en.wikipedia.org/wiki/Road_to_Nowhere_(book)
  - https://peacenews.info/node/10522/paris-marx-road-nowhere-what-silicon-valley-gets-wrong-about-future-transportation
  - https://www.boundary2.org/2022/08/zachary-loeb-where-were-going-well-still-probably-need-roads-review-of-paris-marx-road-to-nowhere-what-silicon-valley-gets-wrong-about-the-future-of-transportation/
  - https://www.springerin.at/en/2024/1/intelligenz-als-machtkonzentration/
  - https://www.trendingtopics.eu/signal-whittaker-ai-operating-system/
  - https://ainowinstitute.org/people/meredith-whittaker.html
  - https://www.dair-institute.org/
  - https://dair-institute.org/press-release/
  - https://www.washingtonpost.com/technology/2021/12/02/timnit-gebru-dair/
  - https://techcrunch.com/2021/12/02/google-timnit-gebru-ai-research-dair/
  - https://www.commondreams.org/news/stop-data-centers
  - https://www.foodandwaterwatch.org/2026/06/11/500-groups-from-47-states-call-for-nationwide-ai-data-center-moratorium/
  - https://en.wikipedia.org/wiki/Race_After_Technology
  - https://www.amazonclimatejustice.org/who-we-are
  - https://www.thenation.com/content/tech-wont-save-us/
---

Connective type (message): claims are edges + hard specifics per `AUDITOR.md § Type-shape`; interpretive prose about significance/arc (the "epistemic operation" passages, the adjacent-framings section, "Why it has carried") receives no decision.

## Claim 1: podcast *Tech Won't Save Us* "launched April 2020 during the first COVID-19 lockdown"; host Paris Marx, "Canadian critic"

Source: https://www.techwontsave.us/about
Source tier: primary
Source content: "Tech Won't Save Us is an award-winning left-wing tech podcast that began in April 2020 during the first Covid lockdown." / "Paris Marx is the host of Tech Won't Save Us. He is a Canadian technology writer and author of Road to Nowhere..."
Comparison: Launch month, lockdown context, host, and nationality all match the show's own about page; the cited Radical Urbanist launch post (April 2020) is live and search-indexed with an April 12, 2020 date. Appears in origin scalar, sources[1].note, and body.
Decision: corroborated

## Claim 2: the podcast "described itself as offering 'a healthy counter dose to the nauseating tech utopia idealism that usually surrounds Silicon Valley'" (origin scalar; sources[0].note calls the about page "primary source for the podcast's framing mandate" with this quote; body: "Marx described the project as a counter to the 'nauseating tech utopia idealism...'")

Source: https://www.techwontsave.us/about
Source tier: primary
Source content: "A healthy counter dose to the nauseating tech utopia idealism that usually surrounds Silicon Valley" — displayed on the about page attributed to **Mashable** (full Mashable line per search index: "...that usually surrounds Silicon Valley and enthusiast tech press coverage").
Comparison: The quoted words are real but the attribution is wrong: this is Mashable's press description of the show, displayed on the about page as review praise — not the podcast's self-description and not Marx's own framing. Correct replacement: attribute the quote to Mashable (as quoted on the show's about page). Fix locations: frontmatter `origin` scalar ("which described itself as offering..."), `sources[0].note`, and body § Origin ("Marx described the project as a counter to..."). Prose-judgment fix — the surrounding sentences frame it as self-description.
Decision: correction

## Claim 3: Evgeny Morozov, *To Save Everything, Click Here: The Folly of Technological Solutionism* (2013); "solutionism" as the doctrine that complex social problems are engineering problems solvable by technological redesign

Source: https://www.hachettebookgroup.com/titles/evgeny-morozov/to-save-everything-click-here/9781610393706/
Source tier: primary
Source content: Publisher page confirms full title/subtitle and author; description: solutionism converts "deeply political, moral, and irresolvable dilemmas" into "uncontroversial and easily manageable matters of technological efficiency." LSE Review of Books (dated 2013-05-01, reviewing the then-new book) and LA Review of Books corroborate the 2013 first publication and the definition ("an instrumental engagement with public life that regards all social and political issues as problems to be solved").
Comparison: Title, subtitle, author, year, and the definition of solutionism all match across publisher + two editorial reviews. (Hachette's listed date, March 2014, is the paperback edition; the 2013 original is fixed by the May 2013 review date.)
Decision: corroborated

## Claim 4: Morozov's example problems — "political disengagement, obesity, dishonesty in public life, criminal recidivism" (body § Origin)

Source: https://blogs.lse.ac.uk/lsereviewofbooks/2013/05/01/book-review-to-save-everything-click-here-the-folly-of-technological-solutionism/ (via search snippet; direct fetch renders empty)
Source tier: mainstream
Source content: "every problem we face—from political disengagement to obesity—can and must be addressed with a technological solution" (LSE review, via search); Hachette description: "to fix everything — from crime to corruption to pollution to obesity".
Comparison: Two of the four listed examples (political disengagement, obesity) are attested; "dishonesty in public life" and "criminal recidivism" appear in no fetched source's example list. The quartet is not quote-marked and the unattested half is plausible book content, but as stated the specific enumeration could not be matched to a canonical source. Not a finding of error.
Decision: uncorroborated

## Claim 5: podcast thesis "that separating technology from politics has consequences for everyone, especially the most vulnerable" (body; sources[0].note)

Source: https://www.techwontsave.us/about
Source tier: primary
Source content: "They challenge the notion that tech alone can drive our world forward by showing that separating tech from politics has consequences for everyone, especially the most vulnerable."
Comparison: Body paraphrase (not quote-marked) matches the about page nearly verbatim ("technology" for "tech").
Decision: primary-sourced

## Claim 6: Luddite grounding — "the Luddite tradition's argument that technological development under capitalist imperatives is structured to control workers and commodify life" (origin scalar; sources[0].note; body)

Source: https://www.techwontsave.us/about
Source tier: primary
Source content: "Inspired by the Luddites, it examines how technological development is constrained by capitalist imperatives, which include controlling workers and commercializing everything."
Comparison: Paraphrase (not quote-marked) matches the about page's substance; "commodify life" renders "commercializing everything" — acceptable outside quote marks.
Decision: primary-sourced

## Claim 7: "200+ episodes since 2020, with a ... YouTube presence, and *The Nation* partnership" (origin scalar)

Source: https://www.techwontsave.us/episodes
Source tier: primary
Source content: Episodes page lists episodes to #345 (latest: "Data Vampires Redux: Opposing Data Centers," 2026-09-10); site footer links YouTube "@techwontsaveus"; The Nation's own content hub (thenation.com/content/tech-wont-save-us/) and platform listings state the show is "made in partnership with The Nation."
Comparison: 345 episodes ≥ 200+ ✓; YouTube presence ✓ (own site); Nation partnership ✓ (The Nation's own page). The remaining token of this sentence — "a Substack" — is audited separately (Claim 8).
Decision: corroborated

## Claim 8: the podcast has "a Substack" (origin scalar, same sentence as Claim 7)

Source: no canonical source found
Source tier: none
Source content: techwontsave.us homepage and about page name no newsletter or Substack ("No newsletter or Substack is mentioned on this page"); Marx's Radical Urbanist Substack predates the show and his current newsletter activity is not tied to Substack on any fetched page.
Comparison: No fetched or search-indexed source ties a Substack to the podcast as of audit date. Possibly stale (Marx historically published on Substack) but unverifiable as stated; no single correct replacement token identified, so not filed as a correction.
Decision: uncorroborated

## Claim 9: Marx's 2022 book *Road to Nowhere: What Silicon Valley Gets Wrong about the Future of Transportation* (Verso), applying the framing to ridesharing, autonomous vehicles, the Hyperloop vs. public transit/urban planning

Source: https://www.versobooks.com/products/2795-road-to-nowhere
Source tier: primary
Source content: Verso product page: "Road to Nowhere: What Silicon Valley Gets Wrong about the Future of Transportation" by Paris Marx, published July 2022. Wikipedia: "covers emerging technologies in mass transportation, particularly those widely advocated by corporations in Silicon Valley, such as ridesharing companies, electric cars, and the Hyperloop."
Comparison: Publisher, year, title/subtitle, and domain argument all match (publisher page + Wikipedia + multiple reviews).
Decision: corroborated

## Claim 10: book quote — proposals "constrained by the elite perspectives of the people dreaming them up" (body § Origin)

Source: https://peacenews.info/node/10522/paris-marx-road-nowhere-what-silicon-valley-gets-wrong-about-future-transportation (book text via review, search-indexed)
Source tier: mainstream
Source content: "Technology alone cannot resolve the inequities of the existing transport system, especially when the visions in question are constrained by the elite perspectives of the people dreaming them up."
Comparison: The quoted fragment is verbatim book text; confirmed in one review quoting the book (not on the Verso page or in the boundary2 review fetched this session).
Decision: single-source

## Claim 11: Ruha Benjamin, *Race After Technology: Abolitionist Tools for the New Jim Code* (2019); argument that systems marketed as neutral reproduce/automate structural inequity

Source: https://en.wikipedia.org/wiki/Race_After_Technology
Source tier: tiebreaker
Source content: "a 2019 American non-fiction book by Ruha Benjamin published by Polity... Benjamin argues that automation has the potential to hide, speed up, and deepen discrimination while appearing neutral and benevolent."
Comparison: Title/subtitle/year are named-entity definitional facts (Wikipedia-alone sufficient per source rule) and additionally corroborated by publisher listings and the Social Forces (OUP) review record; the argument summary matches. Edge `pub-race-after-technology` resolves in corpus.
Decision: corroborated

## Claim 12: Byrum & Benjamin, "Disrupting the Gospel of Tech Solutionism to Build Tech Justice," SSIR, June 16 2022; "gospel" formulation; Just Tech at the SSRC; "ecosystem of support..." quote; centering affected communities

Source: https://ssir.org/articles/entry/disrupting_the_gospel_of_tech_solutionism_to_build_tech_justice
Source tier: primary
Source content: "Greta Byrum & Ruha Benjamin, Jun. 16, 2022"; "the gospel of tech solutionism"; "the SSRC's Just Tech program was designed to highlight and interrogate questions of justice, power, and equity, creating an ecosystem of support for analysts, artists, and activists experimenting with both speculative and trusted methods"; "the perspectives and leadership of those who have been most impacted by rampant tech solutionism must be central..."
Comparison: Authors, date (sources[2].note's June 16, 2022 and body's June 2022 both match), gospel formulation, SSRC attribution, and the quote-marked "ecosystem of support for analysts, artists, and activists experimenting with both speculative and trusted methods" (verbatim) all check against the article itself.
Decision: primary-sourced

## Claim 13: the SSIR essay was "the inaugural essay of the Just Tech fellowship at the Social Science Research Council" (body § Academic and organizing crystallisation)

Source: https://ssir.org/putting_the_public_interest_in_front_of_technology
Source tier: none
Source content: The article belongs to SSIR's "Putting the Public Interest in Front of Technology" series, "sponsored by the Ford Foundation"; the article says the Just Tech fellowship "launched in November 2021 with an open call for proposals."
Comparison: No source describes the essay as the Just Tech fellowship's inaugural essay; the series it opens under is Ford-sponsored SSIR, and the fellowship launched seven months before the essay. Absence of attestation rather than direct contradiction, so recorded as unsupported rather than a correction.
Decision: uncorroborated

## Claim 14: DAIR "founded by Timnit Gebru in December 2021 outside corporate and government funding structures" (body § AI-accountability register; edge propagated_by_orgs → org-dair-institute)

Source: https://dair-institute.org/press-release/
Source tier: primary
Source content: DAIR announced December 2, 2021 by Timnit Gebru as "an independent, community-rooted institute set to counter Big Tech's pervasive influence"; launch funding "$3.7 million from the Ford, MacArthur, Rockefeller and Open Society foundations, as well as the Kapor Center" (per launch coverage: Washington Post and TechCrunch, both 2021-12-02).
Comparison: Founder, month/year, and independence premise match; funders are philanthropic, consistent with "outside corporate and government funding structures." DAIR's own positioning supports the propagated_by_orgs edge as the body states it.
Decision: corroborated

## Claim 15: Meredith Whittaker — "president of Signal Foundation and a co-founder of the AI Now Institute"

Source: https://www.springerin.at/en/2024/1/intelligenz-als-machtkonzentration/
Source tier: primary
Source content: "Meredith Whittaker is president of the non-profit Signal Foundation which oversees the eponymous messaging app." AI Now Institute's own people page lists her as Co-Founder (now Chief Advisor).
Comparison: Both role facts confirmed — Signal presidency by the interview byline (and WEF coverage), AI Now co-founder by the institute's own page.
Decision: corroborated

## Claim 16: Whittaker quote — the case against framing AI "as a solution to the problems in cases where it is a hunger for data, and the companies push for billions of dollars in investment" (body § AI-accountability register)

Source: no canonical source found
Source tier: none
Source content: Searched the exact string and fragments; fetched the springerin interview (carries her "relationships of power" passage but "does not contain a direct passage where Whittaker explicitly discusses AI framed as 'a solution' while simultaneously describing corporate 'hunger for data' or 'billions of dollars in investment'") and the trendingtopics.eu piece (closest: "with AI intensifying the hunger for data" — reporter paraphrase, not her quote).
Comparison: The quote-marked string appears in no located source and reads as a garbled composite of separate statements. Living-person quoted statement requires a primary or mainstream document; none found. If no source exists, this is a candidate for de-quoting by the Researcher, but without a located true wording there is no single correct replacement, so it is recorded as unsupported rather than a correction. Hallucinated-quote risk — flagging for re-audit attention.
Decision: uncorroborated

## Claim 17: Whittaker argument — AI governance "comes back to 'relationships of power,' whose problems technology has historically solved, who decides which technical approaches get developed and deployed"

Source: https://www.springerin.at/en/2024/1/intelligenz-als-machtkonzentration/
Source tier: mainstream
Source content: "I am interested in whose problems technology has solved traditionally and which questions are answered with technology. And ultimately, who gets to make the decisions about what technological approaches to these problems get developed, designed, maintained, built, deployed, and used. After all, it comes back to relationships of power."
Comparison: The quote-marked fragment "relationships of power" is verbatim; the surrounding paraphrase tracks the source closely. One canonical source.
Decision: single-source

## Claim 18: AlgorithmWatch "has developed the same critique in the legislative register: the impulse to address AI risks through AI-specific technical standards and auditing requirements is itself a solutionist move" (body; edge propagated_by_orgs → org-algorithmwatch)

Source: no canonical source found
Source tier: none
Source content: Search for AlgorithmWatch paired with "tech won't save us" / solutionism framing returned no attestation of this position.
Comparison: AlgorithmWatch's EU advocacy is well attested generally, but no located source attributes to it the specific standards-and-auditing-as-solutionism critique, and no source attests it propagating this framing. Judgment-loaded edge; the outcome is uncorroborated per decision rules.
Decision: uncorroborated

## Claim 19: TechPolicy.Press quotes — commitments as "flimsiness" that "pacify demands for livable communities, clean air, and drinkable water" (body; sources[4].note renders it "pacifies demands...")

Source: https://www.techpolicy.press/big-tech-will-not-save-us-from-the-climate-crisis/
Source tier: mainstream
Source content: "The 'solutions' Big Tech pushes [are showing] the flimsiness of [their] commitments to pacify our demands for livable communities, clean air, and drinkable water – and the dangers we face when we rely on their promises." Also: "The technologies are unproven, the companies' initiatives are voluntary, and the longevity of their commitments are guided only by the whims of their leaders."
Comparison: "flimsiness" is verbatim ✓ and the unproven/voluntary sentence supports the body's structural criticism ✓, but the quote-marked pacify-string drops "our": actual wording is "pacify **our** demands for livable communities, clean air, and drinkable water". Single correct replacement exists. Fix locations: body § Climate justice register (quoted string) and `sources[4].note` ("pacifies demands..."). Mechanical single-replacement quote fix. (Note: sources[4].note frames the article as critiquing "Microsoft's voluntary net-zero commitments" — the flimsiness sentence is about Big Tech generally, though Microsoft's renewables retreat is the article's lead example; acceptable outside quote marks.)
Decision: correction

## Claim 20: NPQ quote — climate tech "operates within racial capitalism and extractivism rather than confronting them, keeping old hierarchies intact, just in shinier packaging" (origin scalar; sources[5].note; body)

Source: https://nonprofitquarterly.org/they-say-climate-tech-will-save-us-but-who-will-save-us-from-climate-tech/
Source tier: mainstream
Source content: "Instead of confronting racial capitalism, extractivism, or colonial-era global supply chains, climate disruption tends to operate within them—upgrading the software without touching the operating system. The result? Climate tech keeps old hierarchies intact, just in shinier packaging." (Abdullahi Lawal, July 21, 2025.)
Comparison: The entity's quote-marked string is a stitched composite of two sentences, reworded ("operates within racial capitalism and extractivism rather than confronting them" is not verbatim; only "old hierarchies intact, just in shinier packaging" is). Paraphrase-as-quote. Correct replacement: quote the second sentence verbatim — "Climate tech keeps old hierarchies intact, just in shinier packaging." — and paraphrase the first without quote marks. Fix locations: `sources[5].note` and body § Climate justice register (same string in both). Article title in entity ✓ matches.
Decision: correction

## Claim 21: NPQ names community-owned cooperative alternatives — Green Worker Cooperatives, South Bronx (sources[5].note; body "worker cooperatives, democratic utility control, participatory governance")

Source: https://nonprofitquarterly.org/they-say-climate-tech-will-save-us-but-who-will-save-us-from-climate-tech/
Source tier: mainstream
Source content: "worker-owned cooperatives in the South Bronx, where organizations like Green Worker Cooperatives have incubated community-led green businesses for over a decade"; "These approaches privilege equity, local knowledge, and shared ownership."
Comparison: Green Worker Cooperatives / South Bronx / cooperative-alternatives framing all present in the article. One canonical source.
Decision: single-source

## Claim 22: "the Stop Data Centers coalition (which demanded a federal moratorium on new AI data center construction)" (body § Climate justice register)

Source: https://www.foodandwaterwatch.org/2026/06/11/500-groups-from-47-states-call-for-nationwide-ai-data-center-moratorium/
Source tier: primary
Source content: Stop Data Centers coalition (Food & Water Watch, Greenpeace, Friends of the Earth et al., launched June 2026); 500+ organizations wrote to Congress calling for "a national moratorium on the approval and construction of new data centers" (Common Dreams, commondreams.org/news/stop-data-centers, corroborating).
Comparison: Coalition name, demand, and federal scope match (coalition lead's own press page + Common Dreams).
Decision: corroborated

## Claim 23: "The Amazon Employees for Climate Justice campaign, tech worker organizing at Alphabet and Microsoft" connect the climate register to tech (body § Climate justice register)

Source: https://www.amazonclimatejustice.org/who-we-are
Source tier: primary
Source content: AECJ's own site: organization of Amazon corporate workers organizing on climate; 2019 walkout pledge preceding Amazon's Climate Pledge; 2023 Seattle walkout covered by KUOW/Axios.
Comparison: AECJ existence and climate-organizing campaign confirmed by its own site plus mainstream coverage. (Alphabet/Microsoft worker organizing is broadly attested in the same coverage ecosystem; the sentence's load-bearing named token is AECJ.)
Decision: corroborated

## Claim 24: cross-reference integrity — frontmatter edges (propagated_by_orgs: org-dair-institute, org-mediajustice, org-algorithmwatch; related_messages: msg-ethics-washing, msg-surveillance-capitalism, msg-data-colonialism) and body links (person-ruha-benjamin, person-timnit-gebru, person-meredith-whittaker, pub-race-after-technology, org-mediajustice, org-algorithmwatch, org-dair-institute)

Source: corpus filesystem check (ls product/entities/*/<id>.md)
Source tier: database
Source content: All ten referenced entity files exist at their expected paths.
Comparison: Every edge and body cross-reference resolves to an existing corpus entity of the expected type.
Decision: corroborated

## Claim 25: MediaJustice propagates the framing (edge propagated_by_orgs → org-mediajustice; body: "MediaJustice's community-centred work ... attempts to fill that gap")

Source: no canonical source found
Source tier: none
Source content: Search for MediaJustice paired with "tech won't save us" / solutionism framing returned no attestation.
Comparison: MediaJustice exists in corpus and its community-centred organizing is attested elsewhere, but no located source ties it to propagating the counter-solutionism framing specifically. Judgment-loaded edge; honest outcome is unsupported, not error.
Decision: uncorroborated
