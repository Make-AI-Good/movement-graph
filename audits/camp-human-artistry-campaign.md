---
entity_id: camp-human-artistry-campaign
entity_hash: 573ced7438be34e8e64836e19863f8ae9abf7582
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 20
claims_corroborated: 12
claims_primary_sourced: 3
claims_single_source: 2
claims_uncorroborated: 2
open_corrections: 1
sources_consulted:
  - https://www.riaa.com/human-artistry-campaign-launches-announces-ai-principles/
  - https://www.musicbusinessworldwide.com/riaa-and-over-30-other-groups-launch-ai-campaign-to-support-human-creativity/
  - https://www.humanartistrycampaign.com/
  - https://www.humanartistrycampaign.com/about-5
  - https://www.hollywoodreporter.com/business/business-news/celebrities-back-stealing-isnt-innovation-campaign-ai-1236479303/
  - https://techcrunch.com/2024/10/22/thousands-of-creatives-sign-petition-against-ai-data-scraping/
  - https://www.washingtonpost.com/technology/2024/10/22/thom-yorke-letter-ai-copyright/
  - https://www.nbcnews.com/tech/actors-artists-authors-open-letter-ai-copyright-rcna176681
  - https://www.aitrainingstatement.org/
  - https://www.usnews.com/news/business/articles/2025-05-21/industry-leaders-urge-senate-to-protect-against-ai-deepfakes-with-no-fakes-act
  - https://www.judiciary.senate.gov/imo/media/doc/2025-05-21_pm_testimony_mcbride.pdf
  - https://www.blackburn.senate.gov/2025/5/technology/video-tennessee-artist-martina-mcbride-urges-congress-to-pass-blackburn-s-no-fakes-act
  - https://www.billboard.com/pro/martina-mcbride-speaks-out-ai-deepfakes-senate-hearing/
  - https://www.congress.gov/bill/119th-congress/senate-bill/4591
  - https://www.govtrack.us/congress/bills/119/s4591
  - https://musically.com/2024/09/13/human-artistry-campaign-says-us-voters-back-deepfake-crackdown/
  - https://www.thewrap.com/human-artistry-campaign-moiya-mctier-ai/
  - https://www.musicbusinessworldwide.com/cyndi-lauper-bonnie-raitt-and-other-artists-join-ai-licensing-campaign-stealing-isnt-innovation/
  - https://www.digitalmusicnews.com/2024/10/22/creatives-demand-ai-training-guardrails/
  - https://www.publishersweekly.com/pw/newsbrief/index.html?record=4135
  - https://www.creativebloq.com/art/digital-art/these-digital-artists-have-made-progress-in-the-fight-against-unethical-ai
---

Pass 1 note: Campaign is a connective type — claim surface is the edges (participating_orgs, strategies, body cross-references) and hard specifics (start_date, launch venue, counts, named signatories, legislative record, polling figures). Interpretive prose (cross-sector-convergence framing, "full-spectrum advocacy playbook," significance language in § Place in the make-AI-good movement) is not claimed and receives no decisions. Harness limits this pass: variety.com (402 via tollbit), nbcnews.com, digitalmusicnews.com, and billboard.com/pro 403 on direct fetch — those claims verified via alternate canonical coverage and search-returned headline/snippet text, noted per claim. One correction found: the October 2024 "AI Training Guardrails" statement is attributed in the body and outcomes scalar to the coalition, but canonical coverage attributes it to Ed Newton-Rex (see Claim 10).

## Claim 1: launched on "16 March 2023 at South by Southwest in Austin, Texas" (also scalar:start_date 2023-03-16)

Source: https://www.riaa.com/human-artistry-campaign-launches-announces-ai-principles/; https://www.musicbusinessworldwide.com/riaa-and-over-30-other-groups-launch-ai-campaign-to-support-human-creativity/
Source tier: primary
Source content: RIAA release (fetched this pass): launch "March 16, 2023, at SXSW in Austin, Texas." MBW (fetched this pass) covers the same launch with over 30 groups.
Comparison: Body date and venue and scalar start_date 2023-03-16 match the founding coalition's own release and independent trade coverage exactly.
Decision: corroborated

## Claim 2: "coordinated 40+ founding organizations" at launch (also scalar:outcomes "grew from 40+ founding organizations")

Source: https://www.riaa.com/human-artistry-campaign-launches-announces-ai-principles/; https://www.musicbusinessworldwide.com/riaa-and-over-30-other-groups-launch-ai-campaign-to-support-human-creativity/
Source tier: primary
Source content: RIAA release: "40+ organizations representing artists, performers, writers, athletes, and related groups." MBW: "Over 30 groups launched the campaign, with the article listing approximately 40+ specific member organizations at the end."
Comparison: Body's 40+ founding count matches RIAA's own figure; MBW's "over 30" headline with a ~40-name roster is consistent.
Decision: corroborated

## Claim 3: founding members include RIAA, the Recording Academy, NMPA, SAG-AFTRA, the AFL-CIO, and SoundExchange

Source: https://www.riaa.com/human-artistry-campaign-launches-announces-ai-principles/; https://www.musicbusinessworldwide.com/riaa-and-over-30-other-groups-launch-ai-campaign-to-support-human-creativity/
Source tier: primary
Source content: RIAA release "specifically highlights statements from RIAA, Recording Academy, NMPA, SAG-AFTRA, SoundExchange, and Black Music Action Coalition. AFL-CIO is listed among the 40+ member organizations." MBW: "the article names RIAA, Recording Academy, SAG-AFTRA, and NMPA as signatories. The AFL-CIO is mentioned as the parent organization of the Department of Professional Employees, which is listed as a member."
Comparison: All six named founding members confirmed in the launch roster by two sources. Minor nuance: MBW lists the AFL-CIO's Department for Professional Employees as the roster entry with AFL-CIO as parent; RIAA's own roster lists AFL-CIO — the body's inclusion of AFL-CIO is supported.
Decision: corroborated

## Claim 4: scalar:participating_orgs[0] — edge `org-sag-aftra`; SAG-AFTRA as founding coalition member and creative-labor-union anchor

Source: product/entities/organizations/org-sag-aftra.md (edge-target identity); https://www.riaa.com/human-artistry-campaign-launches-announces-ai-principles/; https://www.hollywoodreporter.com/business/business-news/celebrities-back-stealing-isnt-innovation-campaign-ai-1236479303/
Source tier: primary
Source content: Edge target exists in corpus. RIAA launch release highlights a SAG-AFTRA statement among founding organizations. THR (fetched this pass) describes the Human Artistry Campaign as "a coalition of unions, artists' rights groups, and trade associations including the Writers Guild of America, SAG-AFTRA, and the Recording Industry Association of America."
Comparison: Edge points to the correct entity; SAG-AFTRA's founding membership and continuing coalition role confirmed by two independent canonical sources spanning launch (2023) and current activity (2026).
Decision: corroborated

## Claim 5: scalar:participating_orgs[1] — edge `org-authors-guild`; the Authors Guild "joined subsequently as the coalition expanded beyond music"

Source: product/entities/organizations/org-authors-guild.md (edge-target identity); https://www.humanartistrycampaign.com/
Source tier: primary
Source content: Edge target exists in corpus. The campaign's own site lists member organizations (fetched this pass; the page "lists numerous member organizations"); search-returned coverage of the membership states "The Authors Guild is among the member groups of the Human Artistry Campaign." The Authors Guild does not appear among the launch-roster names in the RIAA or MBW launch coverage fetched this pass, consistent with "joined subsequently."
Comparison: Edge points to the correct entity; membership rests on the coalition's own membership roster (primary). The "joined subsequently" timing is supported by absence from the founding roster rather than a positive dated joining announcement.
Decision: primary-sourced

## Claim 6: scalar:strategies[0] — edge `strat-creator-class-collective-bargaining-on-generative-ai`

Source: product/entities/strategies/strat-creator-class-collective-bargaining-on-generative-ai.md (edge-target identity); https://www.riaa.com/human-artistry-campaign-launches-announces-ai-principles/; https://www.hollywoodreporter.com/business/business-news/celebrities-back-stealing-isnt-innovation-campaign-ai-1236479303/
Source tier: primary
Source content: Edge target exists in corpus. RIAA release documents a coalition of 40+ creator organizations jointly announcing licensing/consent principles for generative AI; THR documents the same coalition ("unions, artists' rights groups, and trade associations") running collective public campaigns against unlicensed AI training in 2026.
Comparison: Edge points to the correct entity — the campaign's documented mechanics (union-heavy coalition acting collectively on generative-AI consent/licensing terms) match the strategy the edge names. The strategy mapping itself is Analyst-authored interpretation; the audit verifies the pointer and its factual basis, both confirmed.
Decision: corroborated

## Claim 7: body edge — link to `camp-concept-art-association-federal-policy-advocacy-2022-ongoing` as the parallel visual-art federal-policy campaign carrying "consent, credit, compensation" vocabulary in Washington since December 2022

Source: product/entities/campaigns/camp-concept-art-association-federal-policy-advocacy-2022-ongoing.md (edge-target identity); https://www.creativebloq.com/art/digital-art/these-digital-artists-have-made-progress-in-the-fight-against-unethical-ai
Source tier: mainstream
Source content: Edge target exists in corpus. Search-returned coverage: "The Concept Art Association had raised over $270,000 through crowdfunding to hire a lobbyist to advocate for creators in Washington D.C. ... in the context of late 2022, when artists discovered that their work had been swept up and used to train models for AI image generators without their consent."
Comparison: Edge points to the correct entity; the CAA's late-2022-origin DC federal advocacy is confirmed by one canonical source. The precise "December 2022" start and the shared-vocabulary framing are that entity's claims (audited in its own file); the mirroring/convergence framing here is interpretation and not claimed.
Decision: single-source

## Claim 8: the seven core principles as rendered in scalar:goals and body § Seven Core Principles

Source: https://www.riaa.com/human-artistry-campaign-launches-announces-ai-principles/
Source tier: primary
Source content: RIAA release (fetched this pass) lists the seven principles, including: use of copyrighted works and performer voices "requires authorization and licensing compliance"; governments "should not create copyright exemptions allowing AI developers to exploit creators" ("Creating special shortcuts or legal loopholes for AI would harm creative livelihoods, damage creators' brands..."); "Copyright should only protect unique human intellectual creativity"; "Trustworthiness and transparency are essential to AI success and creator protection"; "Creators' interests must be represented in policymaking."
Comparison: The entity's seven-item rendering (tool-not-replacement; human creativity irreplaceable; consent/credit/compensation with licensing; no new IP exemptions; human-only copyright; transparency and labeling; creator representation in policy) is a faithful paraphrase of the RIAA-published principle set — items 3–7 map near-verbatim; items 1–2 compress the release's empowerment/essential-role framing into the body's tool-vs-replacement framing without changing the factual content. One primary source (the announcing coalition's own release).
Decision: primary-sourced

## Claim 9: "by 2025–2026 the roster had grown past 70 member organizations" (also scalar:outcomes "70+ member organizations by 2025-2026")

Source: https://www.humanartistrycampaign.com/; https://www.sagaftra.org/human-artistry-campaign
Source tier: primary
Source content: Search-returned coalition text (February 2025): "Since its launch at South by Southwest (SXSW), the Human Artistry Campaign has expanded to include 70+ organizations and unions worldwide representing songwriters, composers, dancers, singers, publishers, journalists, photographers, voice actors, and independent musicians."
Comparison: The 70+ figure for 2025 matches the coalition's own current description. Rests on the coalition's self-description (primary for its own membership count); no independent tally found this pass.
Decision: primary-sourced

## Claim 10: "the coalition released an AI Training Guardrails statement" in October 2024 (body § AI Training Guardrails statement; also scalar:outcomes "October 2024: the coalition released an AI Training Guardrails statement")

Source: https://techcrunch.com/2024/10/22/thousands-of-creatives-sign-petition-against-ai-data-scraping/; https://www.washingtonpost.com/technology/2024/10/22/thom-yorke-letter-ai-copyright/; https://www.aitrainingstatement.org/; https://www.digitalmusicnews.com/2024/10/22/creatives-demand-ai-training-guardrails/
Source tier: mainstream
Source content: TechCrunch (fetched this pass): "Organizer: British composer Ed Newton-Rex, a former executive at Stability AI, organized the petition. Human Artistry Campaign: Not mentioned in the provided content." The statement text: "The unlicensed use of creative works for training generative AI is a major, unjust threat to the livelihoods of the people behind those works, and must not be permitted." Washington Post headline (search-returned): "Thom Yorke, Julianne Moore join letter protesting unauthorized AI training"; search-returned synthesis of the same coverage set: "The petition was organized by British composer Ed Newton-Rex, a former exec at Stability AI." The statement's own home is aitrainingstatement.org ("Statement on AI training"). "AI Training Guardrails" appears as Digital Music News' 2024-10-22 headline phrasing ("11,500+ Creatives Demanding 'AI Training Guardrails'"), not as the statement's name.
Comparison: The body and outcomes scalar attribute the October 2024 11,500-signatory statement to the Human Artistry Campaign ("the coalition released..."). Canonical coverage (TechCrunch fetched; Washington Post, NBC, Artnet per search) uniformly attributes it to Ed Newton-Rex's Statement on AI Training, and none of the consulted coverage mentions the Human Artistry Campaign in connection with it; "AI Training Guardrails" is a Digital Music News headline, not a coalition release title. The specific factual token — the releasing/organizing party — contradicts the best sources and has a single correct replacement (organized by Ed Newton-Rex, published at aitrainingstatement.org). Fix location: body § "AI Training Guardrails statement (October 2024)" and scalar:outcomes; note the fix likely requires prose judgment beyond a single token (the section presents the statement as a coalition milestone), so Editor may route to Researcher per its act.
Decision: correction

## Claim 11: the October 2024 statement "drew more than 11,500 signatories"

Source: https://techcrunch.com/2024/10/22/thousands-of-creatives-sign-petition-against-ai-data-scraping/; https://www.nbcnews.com/tech/actors-artists-authors-open-letter-ai-copyright-rcna176681
Source tier: mainstream
Source content: TechCrunch (fetched this pass): "Number of Signatories: 11,500." NBC headline (search-returned; direct fetch 403): "More than 11,000 creatives condemn unauthorized use of content for AI development"; search-returned coverage: "an open letter signed by 11,500 actors, musicians, authors, photographers, and composers."
Comparison: The 11,500+ count matches two independent canonical sources. (The count is accurate even though the statement's attribution is corrected in Claim 10.)
Decision: corroborated

## Claim 12: October 2024 named signatories "including James Patterson, Thom Yorke, Robert Smith, Julianne Moore, Kevin Bacon, Kazuo Ishiguro, and Scarlett Johansson"

Source: https://techcrunch.com/2024/10/22/thousands-of-creatives-sign-petition-against-ai-data-scraping/; https://www.nbcnews.com/tech/actors-artists-authors-open-letter-ai-copyright-rcna176681
Source tier: mainstream
Source content: TechCrunch (fetched this pass) names Kevin Bacon, Thom Yorke, Julianne Moore, Kazuo Ishiguro, Robert Smith; "James Patterson and Scarlett Johansson do not appear in this article." NBC coverage (search-returned) names Thom Yorke, Julianne Moore, Kazuo Ishiguro, Robert Smith, Rosario Dawson, Max Richter, Ann Patchett.
Comparison: Five of the seven body-named signatories (Yorke, Smith, Moore, Bacon, Ishiguro) confirmed; James Patterson and Scarlett Johansson not found in any coverage consulted this pass (the entity's cited NBC source 403s on direct fetch, so its full signatory list could not be checked). Partial confirmation — not a finding of error.
Decision: uncorroborated

## Claim 13: May 2025 — coalition-organized petition of "nearly 400 prominent artists" (outcomes) "including LeAnn Rimes, Bette Midler, Missy Elliott, Scarlett Johansson, and Sean Astin" (body)

Source: https://www.usnews.com/news/business/articles/2025-05-21/industry-leaders-urge-senate-to-protect-against-ai-deepfakes-with-no-fakes-act; https://www.billboard.com/pro/martina-mcbride-speaks-out-ai-deepfakes-senate-hearing/
Source tier: mainstream
Source content: AP coverage via US News (search-returned): "Nearly 400 artists, actors and performers signed on in support of the legislation, including LeAnn Rimes, Bette Midler, Missy Elliott, Scarlett Johansson and Sean Astin." Billboard (search-returned; direct fetch paywalled): "the Human Artistry Campaign announced that 393 artists have signed on in support of the NO FAKES Act, including Cardi B, Randy Travis, Mary J. Blige and the Dave Matthews Band."
Comparison: The "nearly 400" count (393 per Billboard's Human Artistry Campaign announcement), the coalition's organizing role, and all five body-named signatories match two independent canonical sources.
Decision: corroborated

## Claim 14: Martina McBride "delivered in-person testimony before the Senate Judiciary Subcommittee hearing titled 'The Good, the Bad, and the Ugly: AI-Generated Deepfakes in 2025,' alongside RIAA and YouTube witnesses" (May 2025)

Source: https://www.judiciary.senate.gov/imo/media/doc/2025-05-21_pm_testimony_mcbride.pdf; https://www.blackburn.senate.gov/2025/5/technology/video-tennessee-artist-martina-mcbride-urges-congress-to-pass-blackburn-s-no-fakes-act
Source tier: primary
Source content: Senate Judiciary Committee document (search-returned): "STATEMENT OF MARTINA MCBRIDE ON S. 1367, THE 'NO FAKES ACT OF 2025'," dated 2025-05-21. Search-returned hearing coverage: "Martina McBride testified at the Senate Judiciary Subcommittee on Privacy, Technology, and the Law hearing titled 'The Good, the Bad, and the Ugly: AI-Generated Deepfakes in 2025' on Wednesday, May 21st"; her testimony urged Congress to pass the NO FAKES Act. TechPolicy.Press transcript confirms the hearing included industry witnesses.
Comparison: Testimony, date, subcommittee, and exact hearing title all match the Senate's own record and member-office release. The "alongside RIAA and YouTube witnesses" detail is consistent with hearing coverage (industry leaders including RIAA championed the bill at the hearing) though the witness list was not independently enumerated this pass; the load-bearing specifics (McBride, in person, subcommittee, title) are confirmed by primary record.
Decision: corroborated

## Claim 15: the NO FAKES Act ("Nurture Originals, Foster Art, and Keep Entertainment Safe Act") is the campaign's primary legislative vehicle, "backed across multiple congressional sessions"

Source: https://www.congress.gov/bill/119th-congress/senate-bill/4591; https://www.blackburn.senate.gov/2026/5/technology/blackburn-coons-salazar-dean-colleagues-introduce-revised-version-of-no-fakes-act; https://www.usnews.com/news/business/articles/2025-05-21/industry-leaders-urge-senate-to-protect-against-ai-deepfakes-with-no-fakes-act
Source tier: primary
Source content: Congress.gov (search-returned): "S.1367 - 119th Congress (2025-2026): NO FAKES Act of 2025" and "S.4591 ... NO FAKES Act of 2026"; Coons office one-pager: "NURTURE ORIGINALS, FOSTER ART, AND KEEP ENTERTAINMENT SAFE (NO FAKES) ACT"; Salazar office release: "Salazar, Dean, Blackburn, Coons, Bipartisan Colleagues Reintroduce NO FAKES Act"; Billboard (search-returned) confirms the Human Artistry Campaign announced the 393-artist support petition for the bill.
Comparison: Full name matches the sponsors' own expansion (body renders "Foster Art, and Keep" with Oxford comma; Coons one-pager identical). The bill's repeated introduction (2023 discussion draft era through S.1367 of 2025 and revised S.4591 of 2026) confirms multi-session backing, and the campaign's organizing of artist support for it is documented (Claim 13). The superlative framing ("single most consequential") is interpretation, not claimed.
Decision: corroborated

## Claim 16: "As of mid-2026 the NO FAKES Act had not yet been enacted" (body and scalar:outcomes)

Source: https://www.congress.gov/bill/119th-congress/senate-bill/4591; https://www.govtrack.us/congress/bills/119/s4591
Source tier: primary
Source content: Search-returned legislative status: the Senate Judiciary Committee "unanimously advanced by voice vote S. 4591 ... on June 18, 2026, with the bipartisan bill moving to the full Senate for approval"; GovTrack: "the bill is still in the legislative process and awaiting full Senate passage before it can become law."
Comparison: Matches — as of this audit (2026-07-04) the act has advanced out of committee but is not enacted, exactly the body's "not yet been enacted ... continues active legislative advocacy."
Decision: corroborated

## Claim 17: January 2026 — coalition launched "Stealing Isn't Innovation" with "700+ supporters — including Scarlett Johansson, Cate Blanchett, Joseph Gordon-Levitt, R.E.M., and Bonnie Raitt"

Source: https://www.hollywoodreporter.com/business/business-news/celebrities-back-stealing-isnt-innovation-campaign-ai-1236479303/; https://www.musicbusinessworldwide.com/cyndi-lauper-bonnie-raitt-and-other-artists-join-ai-licensing-campaign-stealing-isnt-innovation/
Source tier: mainstream
Source content: THR (fetched this pass): the campaign "launched Thursday, January 21, 2026," is "organized by the Human Artistry Campaign," with "more than 700 supporters"; named backers include Scarlett Johansson, Cate Blanchett, Joseph Gordon-Levitt, R.E.M., LeAnn Rimes, Sean Astin, Fran Drescher. Bonnie Raitt is not named in THR but is headline-confirmed by MBW: "Cyndi Lauper, Bonnie Raitt and other artists join AI licensing campaign: 'Stealing isn't innovation'."
Comparison: Launch month/year, coalition attribution, 700+ count, and all five body-named supporters confirmed across two independent canonical sources. The body's counter-framing description matches THR's quoted campaign statement ("Big Tech is trying to change the law so they can keep stealing American artistry...").
Decision: corroborated

## Claim 18: coalition-commissioned polling "found 64% of US voters regard voice cloning and deepfakes as a major problem and 66% strongly support Congressional action to protect artists' voices and images"

Source: https://musically.com/2024/09/13/human-artistry-campaign-says-us-voters-back-deepfake-crackdown/
Source tier: mainstream
Source content: Music Ally (search-returned; September 2024): "Human Artistry Campaign says US voters back deepfake crackdown" — "64% of registered US voters agreed that voice cloning and deepfakes are 'a major problem', and 66% strongly support Congress 'creating new policies to protect artists' voices and images from unauthorized use by artificial technology'."
Comparison: Both figures match exactly, and the poll is the coalition's own commission as the body states. One canonical source; the coalition's homepage (cited in the entity) did not surface the polling on this pass's fetch. Note: the poll dates from September 2024 — the body's framing that it "support[ed] the January 2026 push" is compatible (a standing poll cited in the later push) but the poll is not itself a January 2026 product; the outcomes scalar states the figures without a date, which is accurate.
Decision: single-source

## Claim 19: "A Senior Advisor, Dr. Moiya McTier — an astrophysicist and author who serves as the coalition's public 'Explainer-in-Chief' — handles external-facing education of policymakers and the creative community"

Source: https://www.humanartistrycampaign.com/about-5; https://www.thewrap.com/human-artistry-campaign-moiya-mctier-ai/
Source tier: primary
Source content: Coalition About page (search-returned): Dr. Moiya McTier "serves as Senior Advisor & Public Communicator for the Human Artistry Campaign"; "In her explainer-in-chief role advising the Human Artistry Campaign, she helps educate policymakers and fellow creatives about the promise and the risks of AI"; she is "a scientist (with a focus in astronomy and astrophysics) and a published author," "the first Black woman to graduate from Columbia's astronomy PhD program" (2021). TheWrap: "Creators Now Have a Voice to Counter AI" — profile of McTier's Human Artistry Campaign role.
Comparison: Title (Senior Advisor), the Explainer-in-Chief epithet, astrophysicist-and-author credentials, and the policymaker/creative-community education remit all match the coalition's own page, independently covered by TheWrap.
Decision: corroborated

## Claim 20: "The coalition's coordination structure is decentralized: member organizations collectively endorse campaign principles and jointly sign public statements, with no single executive director or traditional nonprofit governance"

Source: no canonical source found
Source tier: none
Source content: Consulted the coalition's homepage and About page (fetched/search-returned this pass): the site lists member organizations, the seven principles, and a Senior Advisor role, and names no executive director or corporate governance structure — but no source affirmatively describes the governance model as decentralized or states the absence of an executive director.
Comparison: The claim is consistent with everything observed (no ED appears anywhere in the coalition's self-presentation; campaigns are released as joint member statements) but rests on absence of evidence rather than a source's positive statement. Cannot be cleanly verified; not a finding of error.
Decision: uncorroborated
