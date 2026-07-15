---
entity_id: event-google-project-maven-petition-2018-04
entity_hash: fc8fb5e48577238cef6f59c2487df1079965e909
audit_date: 2026-07-15
pass: 1
status: corrections-pending
claims_total: 26
claims_corroborated: 12
claims_primary_sourced: 0
claims_single_source: 4
claims_uncorroborated: 7
open_corrections: 3
sources_consulted:
  - https://gizmodo.com/thousands-of-google-employees-protest-companys-involvem-1824988565
  - https://theintercept.com/2018/06/01/google-drone-ai-project-maven-contract-renew/
  - https://theintercept.com/2018/05/31/google-leaked-emails-drone-ai-pentagon-lucrative/
  - https://logicmag.io/the-making-of-the-tech-worker-movement/full-text/
  - https://www.armscontrol.org/act/2018-07/news/google-renounces-ai-work-weapons
  - https://collectiveaction.tech/2020/tech-workers-versus-the-pentagon/
  - https://blog.google/technology/ai/ai-principles/
  - https://www.forbes.com/sites/thomasbrewster/2021/09/08/project-maven-amazon-and-microsoft-get-50-million-in-pentagon-drone-surveillance-contracts-after-google/
  - https://nsarchive.gwu.edu/document/18583-national-security-archive-department-defense
  - https://cwa-union.org/news/releases/google-workers-launch-union-with-cwa
  - https://en.wikipedia.org/wiki/2018_Google_walkouts
  - https://en.wikipedia.org/wiki/Meredith_Whittaker
---

Connective type (event): claim surface is edges + hard specifics per `mission/MISSION.md § Auditor § Type-shape awareness`. `participating_orgs: []` and `related_events: []` are empty edges — nothing to verify. Significance-arc prose without a hard specific ("founding event", "shifted workers' self-understanding", "drew directly on the Maven campaign's networks") is interpretation, not claim, and receives no decision.

## Claim 1: scalar:date — "2018-04"

Source: https://gizmodo.com/thousands-of-google-employees-protest-companys-involvem-1824988565
Source tier: mainstream
Source content: "Published April 4, 2018, 2:55 pm ET"; Arms Control Association: petition signed "in April 2018".
Comparison: Frontmatter `date` matches the petition's April 2018 publication, confirmed by the Gizmodo dateline and ACA coverage.
Decision: corroborated

## Claim 2: scalar:location — "Mountain View, CA"

Source: no canonical source found
Source tier: none
Source content: Gizmodo: "The petition, which has floated through the company's internal communications systems for several weeks"; Jacobin/Collective Action in Tech: "People began organizing their own initiatives at offices all over the world, from Mountain View to Seattle to New York to Montreal to Dublin to Zurich."
Comparison: Scalar `location` is an HQ-based editorial assignment; no source names a venue for the petition, and the campaign's own record describes organizing across global offices. Not an error finding — the audit cannot corroborate a location no source states.
Decision: uncorroborated

## Claim 3: edge:participating_people — person-meredith-whittaker

Source: https://logicmag.io/the-making-of-the-tech-worker-movement/full-text/
Source tier: mainstream
Source content: Logic: Whittaker was "one of the core anti-Maven organizers"; Wikipedia (tiebreaker): she "wrote a petition against Project Maven, which more than three thousand Google employees signed."
Comparison: Edge points to the correct entity (`product/entities/persons/person-meredith-whittaker.md` exists); her core-organizer role is confirmed by Logic with Wikipedia as tiebreaker.
Decision: corroborated

## Claim 4: scalar:event_type — "employee petition"

Source: https://gizmodo.com/thousands-of-google-employees-protest-companys-involvem-1824988565
Source tier: mainstream
Source content: "thousands have now signed a petition"; ACA: "About 4,000 Google employees signed a letter."
Comparison: Event-type classification matches every source's description of the action.
Decision: corroborated

## Claim 5: scalar:sources[0].note — "confirms 3,100 signers, CEO Sundar Pichai as addressee, dual demands (cancel Maven; establish weapons policy), and resignations over the contract"

Source: https://gizmodo.com/thousands-of-google-employees-protest-companys-involvem-1824988565
Source tier: mainstream
Source content: Targeted re-fetch: "No. The article does not mention any employees resigning. It only states that 'thousands have now signed a petition' and that 'some 3,100 of whom have since signed the petition.'"
Comparison: Scalar path `sources[0].note`. Signers, addressee, and dual demands are confirmed in the article, but the cited 4 April 2018 article contains no resignation mention — the ~dozen resignations were reported in mid-May 2018, weeks after this article. Fix: delete the clause "and resignations over the contract" from the note.
Decision: correction

## Claim 6: scalar:sources[1].note — "confirms Google non-renewal announcement by Diane Greene; documents initial contract value ($15M, projected $250M/year) and that Microsoft and Amazon subsequently took on similar work"

Source: https://theintercept.com/2018/06/01/google-drone-ai-project-maven-contract-renew/
Source tier: mainstream
Source content: Targeted re-fetch: "the article does not mention $15 million anywhere. The only dollar figures provided are $9 million (what executives claimed) and $250 million annually"; "No, the article does not mention Microsoft or Amazon anywhere."
Comparison: Scalar path `sources[1].note`. The Greene non-renewal announcement and $250M/yr projection are confirmed, but the cited article carries neither the $15M figure (that is in The Intercept's 31 May 2018 leaked-emails piece, https://theintercept.com/2018/05/31/google-leaked-emails-drone-ai-pentagon-lucrative/: "Total deal $25-$30M, $15M to Google over the next 18 months") nor any Microsoft/Amazon content (the takeover is documented by Forbes, 8 Sep 2021). Fix: replace "$15M, projected $250M/year" with "projected $250M/year" and delete "and that Microsoft and Amazon subsequently took on similar work" (or re-point those clauses to the correct sources).
Decision: correction

## Claim 7: scalar:sources[2].note — "documents Maven campaign organising methods across global offices and its catalytic role for the 2018 global walkout and subsequent tech-worker campaigns"

Source: https://logicmag.io/the-making-of-the-tech-worker-movement/full-text/
Source tier: mainstream
Source content: Two targeted fetches found organizing methods ("compiling Maven-related research, asking pointed questions at company meetings, even distributing anti-Maven memes") and the walkout/#TechWontBuildIt through-line, but "The text does not provide: Specific named office locations."
Comparison: Scalar path `sources[2].note`. The methods and catalytic-role clauses are supported; the "across global offices" clause could not be located in the cited source (the offices detail appears instead in the Jacobin organizer interview). Fetch extraction of this long page may be incomplete, so this is recorded as a sourcing limit, not an error.
Decision: uncorroborated

## Claim 8: "more than 3,100 Google employees signed an internal petition addressed to CEO Sundar Pichai demanding the company cancel its Pentagon contract ... and commit to never building weapons technology"

Source: https://gizmodo.com/thousands-of-google-employees-protest-companys-involvem-1824988565
Source tier: mainstream
Source content: "some 3,100 of whom have since signed the petition"; petition addressed to "CEO Sundar Pichai"; demands: "Cancel this project immediately" and "Draft, publicize, and enforce a clear policy stating that neither Google nor its contractors will ever build warfare technology." ICRAC open letter corroborates: "in solidarity with the 3100+ Google employees."
Comparison: Signer count, addressee, and both demands match Gizmodo's publication of the petition, independently corroborated by the ICRAC academics' letter and ACA coverage.
Decision: corroborated

## Claim 9: "Reported first by Gizmodo on 4 April 2018"

Source: https://gizmodo.com/thousands-of-google-employees-protest-companys-involvem-1824988565
Source tier: mainstream
Source content: "Published April 4, 2018, 2:55 pm ET"; Jacobin: media coverage was "largely driven by Kate Conger at Gizmodo."
Comparison: The 4 April 2018 date is confirmed by the article's own dateline. The priority claim ("first") is supported by Jacobin's crediting of Gizmodo's Kate Conger, but the New York Times also published the petition the same day, and no canonical source explicitly adjudicates publication priority.
Decision: single-source

## Claim 10: "the earliest large-scale collective mobilisation of tech workers specifically targeting their employer's AI-ethics decisions — and the first successful employee campaign to cancel a military AI contract"

Source: no canonical source found
Source tier: none
Source content: Targeted fetch of the Collective Action in Tech mirror: "The article does not contain any explicit statement characterizing this campaign as a 'first' for the tech industry."
Comparison: Contested "first/earliest" superlatives per the source rule's contested-attribution class; no canonical source asserts either superlative in a comparable form. Honest sourcing-strength label, not an error finding.
Decision: uncorroborated

## Claim 11: "Project Maven — formally the Pentagon's Algorithmic Warfare Cross-Functional Team — was launched by the US Department of Defense in April 2017 to accelerate military integration of machine learning"

Source: https://nsarchive.gwu.edu/document/18583-national-security-archive-department-defense
Source tier: primary
Source content: DoD memorandum "Establishment of an Algorithmic Warfare Cross-Functional Team (Project Maven)," signed by Deputy Secretary of Defense Robert O. Work, 26 April 2017; it "directed the Department of Defense to accelerate the integration of big data, machine learning, and computer vision into intelligence workflows."
Comparison: Formal name, sponsor, April 2017 launch, and purpose all match the establishing DoD memo (primary), corroborated by ACA and Wikipedia coverage.
Decision: corroborated

## Claim 12: "Google was contracted to develop computer-vision algorithms to analyse video footage captured by US military drones for object detection and tracking"

Source: https://www.armscontrol.org/act/2018-07/news/google-renounces-ai-work-weapons
Source tier: mainstream
Source content: ACA: Google used AI "to analyze drone footage through computer vision" for "detecting and identifying objects"; Gizmodo: "a customized AI surveillance engine that uses 'Wide Area Motion Imagery' data captured by US Government drones to detect vehicles and other objects."
Comparison: Contract purpose matches two independent canonical sources.
Decision: corroborated

## Claim 13: "The initial contract value was $15 million over 18 months, with internal Google projections estimating potential growth to $250 million annually"

Source: https://theintercept.com/2018/05/31/google-leaked-emails-drone-ai-pentagon-lucrative/
Source tier: mainstream
Source content: Internal Google email quoted by The Intercept: "Total deal $25-$30M, $15M to Google over the next 18 months" and "As the program grows expect spend is budgeted at 250 M per year." Gizmodo's leaked-emails reporting (30 May 2018) independently: "the initial contract was worth at least $15 million ... expected to grow as high as $250 million."
Comparison: All three tokens ($15M, 18 months, $250M/yr) match the leaked internal emails as reported by two outlets. Note the body's inline citation points to the 1 June Intercept piece, which carries the $250M and 18-month figures but not $15M; the widely-cited $9M figure was executives' downplayed characterization, not a contradiction.
Decision: corroborated

## Claim 14: "Knowledge of the contract spread unevenly through Google from late 2017; by early 2018 at least a dozen engineering teams had learned of it through informal internal channels"

Source: https://collectiveaction.tech/2020/tech-workers-versus-the-pentagon/
Source tier: caution
Source content: "It started around September 2017, and picked up speed in October. By January 2018, at least a dozen different teams knew about Project Maven."
Comparison: Content matches the anonymous organizer interview (Jacobin, mirrored by Collective Action in Tech) nearly verbatim, but that is a partisan outlet reporting on its advocacy subject via a single participant — caution tier, not canonical; no canonical source carries this detail.
Decision: uncorroborated

## Claim 15: "carried approximately 3,100 signatories — including dozens of senior engineers"

Source: https://gizmodo.com/thousands-of-google-employees-protest-companys-involvem-1824988565
Source tier: mainstream
Source content: "The petition included 'dozens of senior engineers,' per the New York Times."
Comparison: The senior-engineers detail traces through a single reporting chain (Gizmodo relaying the NYT); the 3,100 count itself is corroborated under Claim 8.
Decision: single-source

## Claim 16: "Its core argument was that 'Google should not be in the business of war' and that the contract contradicted the company's historical 'Don't Be Evil' standard"

Source: https://gizmodo.com/thousands-of-google-employees-protest-companys-involvem-1824988565
Source tier: primary
Source content: Petition text as published: "We believe that Google should not be in the business of war" and "Google's unique history, its motto Don't Be Evil, and its direct reach into the lives of billions of users set it apart."
Comparison: Both quoted elements appear verbatim in the petition text itself (a primary document published in full by Gizmodo; the "business of war" line also independently quoted by ICRAC and ACA-era coverage).
Decision: corroborated

## Claim 17: "A smaller number of employees resigned outright in protest rather than sign"

Source: https://www.armscontrol.org/act/2018-07/news/google-renounces-ai-work-weapons
Source tier: mainstream
Source content: ACA: "A dozen resignations" followed the petition; search-corroborated May 2018 reporting (FedScoop/KQED): "Google employees resign in protest against Air Force's Project Maven."
Comparison: The resignations themselves are well-documented (~a dozen, reported mid-May 2018, weeks after the petition). But the sentence's framing — that they resigned "rather than sign" — is supported by no source and sits against the timeline (the resignations followed the petition rather than substituting for it). Too paraphrastic to compare as written; no single-token fix, so not a correction.
Decision: uncorroborated

## Claim 18: "Organising ran across multiple internal tracks: one group tracked colleagues who had resigned; another monitored media coverage; a third systematically submitted Maven questions at company all-hands meetings and recruited co-workers to upvote them"

Source: https://collectiveaction.tech/2020/tech-workers-versus-the-pentagon/
Source tier: caution
Source content: "One group got together to start tracking the list of employees who had resigned...Another group tracked all of the media coverage...Another group got employees to submit questions about Project Maven to every single all-hands meeting, and then got other employees to up-vote those questions."
Comparison: Near-verbatim match — but the sole source is the anonymous organizer interview in Jacobin (partisan outlet, advocacy beat, single participant account), which is caution tier, not canonical. Note the body's inline citation attributes this to the Logic Magazine piece, where two targeted fetches could not locate it.
Decision: uncorroborated

## Claim 19: "The campaign was distributed across Google's global offices — Mountain View, Seattle, New York, Montreal, Dublin, and Zurich — and operated without any formal union structure"

Source: https://collectiveaction.tech/2020/tech-workers-versus-the-pentagon/
Source tier: caution
Source content: "People began organizing their own initiatives at offices all over the world, from Mountain View to Seattle to New York to Montreal to Dublin to Zurich."; "The different initiatives were mostly autonomous."
Comparison: The office list matches the organizer interview verbatim, but that interview (Jacobin/Collective Action in Tech) is the only source found and is caution tier. The body's inline citation points to Logic Magazine, where the list could not be located.
Decision: uncorroborated

## Claim 20: "the Alphabet Workers Union–CWA did not exist yet and would not launch until January 2021"

Source: https://cwa-union.org/news/releases/google-workers-launch-union-with-cwa
Source tier: primary
Source content: CWA release: workers "announced the creation of the Alphabet Workers Union" on January 4, 2021, "with support from the Communications Workers of America"; Wikipedia (tiebreaker) concurs.
Comparison: Launch date matches the union's own announcement (primary) with mainstream and Wikipedia corroboration; named-entity founding-date class.
Decision: corroborated

## Claim 21: "On 1 June 2018, Google Cloud CEO Diane Greene announced that Google would not renew the Maven contract when it expired in March 2019"

Source: https://theintercept.com/2018/06/01/google-drone-ai-project-maven-contract-renew/
Source tier: mainstream
Source content: "Google executives announced to company staff this morning that the tech giant won't renew its contract to work on Project Maven" (Greene, at a Friday all-hands, 1 June 2018); "Google will continue work on the project through March 2019 ... but once the 18-month contract concludes, it will not be renewed." ACA: "A Google executive informed employees on June 1, 2018 that the company would not extend the work."
Comparison: Date, announcer, non-renewal decision, and March 2019 expiry all match two independent canonical sources.
Decision: corroborated

## Claim 22: "The following month Google published its Artificial Intelligence Principles"

Source: https://blog.google/technology/ai/ai-principles/
Source tier: primary
Source content: Google's AI Principles post by Sundar Pichai is dated June 7, 2018; ACA: "Google published its ethical principles on June 7, 2018."
Comparison: Greene's announcement was 1 June 2018; the AI Principles were published 7 June 2018 — six days later, in the same month, not "the following month." Single correct replacement: "Six days later" (or "On 7 June 2018"). The temporal token contradicts both the entity's own cited ACA source and Google's primary publication.
Decision: correction

## Claim 23: "[the AI Principles] explicitly prohibiting AI applications for weapons or surveillance violating international norms"

Source: https://blog.google/technology/ai/ai-principles/
Source tier: primary
Source content: Applications Google "will not pursue": "Weapons or other technologies whose principal purpose or implementation is to cause or directly facilitate injury to people" and "Technologies that gather or use information for surveillance violating internationally accepted norms."
Comparison: Both prohibition clauses match the primary document verbatim, corroborated by ACA coverage.
Decision: corroborated

## Claim 24: "Microsoft and Amazon Web Services subsequently assumed the drone-AI contract work Google had declined"

Source: https://www.forbes.com/sites/thomasbrewster/2021/09/08/project-maven-amazon-and-microsoft-get-50-million-in-pentagon-drone-surveillance-contracts-after-google/
Source tier: mainstream
Source content: Forbes (8 Sep 2021): Microsoft and Amazon "scored $50 million in Pentagon surveillance contracts after Google quit" — Microsoft from 2019 (~$30M), AWS from 2020 (~$20M); Palantir also took Maven-linked work.
Comparison: Supported by Forbes' procurement-records reporting (the trade-press echoes are derivative, not independent). Incomplete rather than wrong: Palantir was the most prominent Maven successor and is unmentioned. The body's inline citation points to the 1 June 2018 Intercept piece, which contains no Microsoft/Amazon content (see Claim 6).
Decision: single-source

## Claim 25: "catalysed a wave of analogous campaigns within weeks: Microsoft employees mobilised against ICE facial-recognition contracts; Amazon employees raised objections to Rekognition sales to law enforcement; Salesforce workers organised similarly"

Source: https://logicmag.io/the-making-of-the-tech-worker-movement/full-text/
Source tier: mainstream
Source content: "Microsoft employees demanded ICE contract termination; Amazon workers called for facial recognition restrictions; Salesforce employees opposed CBP ties—collectively known as '#TechWontBuildIt.'" All three campaigns date to June 2018.
Comparison: The three named follow-on campaigns and their timing (weeks after the June 1 Maven outcome) match the Logic retrospective; no second independent source fetched this session.
Decision: single-source

## Claim 26: "The November 2018 global Google walkout, in which approximately 20,000 workers across 50 offices protested the company's handling of sexual harassment"

Source: https://en.wikipedia.org/wiki/2018_Google_walkouts
Source tier: mainstream
Source content: "On November 1, 2018, more than 20,000 Google employees engaged in a worldwide walkout to protest the way in which the company handled cases of sexual harassment... The walkout included Google offices in 50 cities"; Logic: "more than twenty thousand employees and contractors" across "fifty cities around the world"; Fortune (3 Nov 2018) headline: "20,000 Walk Out in Sexual Harassment Protest."
Comparison: Count, date-month, cause, and scale match multiple canonical sources (public-event class; body's "50 offices" vs sources' "50 cities/offices in 50 cities" is an equivalent formulation). The adjoining clause that the walkout "drew directly on the Maven campaign's networks and tactics" is movement-arc narrative without a hard specific — interpretation, no decision.
Decision: corroborated
