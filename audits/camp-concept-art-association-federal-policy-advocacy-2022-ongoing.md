---
entity_id: camp-concept-art-association-federal-policy-advocacy-2022-ongoing
entity_hash: a86b5a36ff4abb0dc9c2859f99177fdd67c32902
audit_date: 2026-09-02
pass: 4
status: corrections-pending
claims_total: 23
claims_corroborated: 11
claims_primary_sourced: 6
claims_single_source: 2
claims_uncorroborated: 2
open_corrections: 2
sources_consulted:
  - https://www.gofundme.com/f/protecting-artists-from-ai-technologies (re-fetched pass 4)
  - https://www.conceptartassociation.com/advocacy (re-fetched pass 4)
  - https://lda.gov/api/v1/filings/?client_name=concept+art+association (Senate LDA public API; lda.senate.gov 301s here; fetches fine — primary record for federal lobbying registrations)
  - https://leginfo.legislature.ca.gov/faces/billHistoryClient.xhtml?bill_id=202520260AB412 (fetches fine — primary record for CA bill actions)
  - https://thehill.com/business-a-lobbying/lobbying-contracts/249571-lobbying-world/ (HTTP 403 pass 4; content via search snippets)
  - https://r2pstrategies.com/ (HTTP 401 pass 4)
  - https://www.opensecrets.org/federal-lobbying/firms/lobbyists?id=D000082161&year=2024 (HTTP 403 pass 4)
  - https://www.aol.com/lobbying-world-motion-picture-association-110000426.html (HTTP 404 pass 4)
  - product/entities/strategies/strat-creator-class-collective-bargaining-on-generative-ai.md (local corpus check for the strategies edge)
---

Pass-4 context: the only entity change since the pass-3 audit (2026-06-05) is the frontmatter edge `strategies: [] → [strat-creator-class-collective-bargaining-on-generative-ai]`; body and all other frontmatter are byte-identical. Campaign is a connective type (`mission/MISSION.md § Auditor § Type-shape awareness`), so this pass audits the new edge fresh, re-fetched the GoFundMe and CAA-advocacy cited sources, and newly reached two primary government records (Senate LDA API; CA LegInfo) that resolve pass 3's Merifield claim and surface two date corrections in the `outcomes` scalar. Claims whose text is unchanged and whose sources were not re-fetched carry the pass-1/2/3 recorded quotes, relabelled to the current decision vocabulary from the recorded source set. Pass 3's composite Merifield claim is split in two (retainer vs. MPAA history); the AB 412 milestone entries are split so each date token gets its own decision.

## Claim 1: "launched on 13 December 2022 with a 'Protecting Artists from AI Technologies' GoFundMe publicly fronted by CAA board member and concept artist Karla Ortiz"

Source: https://www.gofundme.com/f/protecting-artists-from-ai-technologies (entity-cited; re-fetched pass 4); https://x.com/kortizart/status/1603458805425410048 (entity-cited; pass-1 record)
Source tier: primary
Source content: "'Protecting Artists from AI Technologies' launched on December 13th, 2022"; "The Concept Art Association organized this fundraiser, based in Arcadia, CA." Ortiz's launch-day X post is on the pass-1 record as the public announcement.
Comparison: Date, campaign name, organiser, and Ortiz's fronting role all match; two primary sources on record.
Decision: corroborated

## Claim 2: "closed at $285,560 against a $270,000 goal"

Source: https://www.gofundme.com/f/protecting-artists-from-ai-technologies (entity-cited; re-fetched pass 4)
Source tier: primary
Source content: "$285,560 raised of $270K".
Comparison: Numbers match; single primary source (the campaign page itself is the authoritative record of its own totals).
Decision: primary-sourced

## Claim 3: "Year 2 budget allocated roughly $187,500 to a full-time D.C. lobbyist, $25,000 to advocacy events including D.C. visits, and $24,000 to contractor hours"

Source: https://www.gofundme.com/f/protecting-artists-from-ai-technologies (entity-cited; re-fetched pass 4)
Source tier: primary
Source content: "$187,500 for one year of a full-time lobbyist in D.C."; "$25K" for two D.C. visits and one California labor-focused event; "$24K Contractor hours for events and legislative pushes".
Comparison: All three line-items match within paraphrase tolerance; single primary source.
Decision: primary-sourced

## Claim 4: "Early 2023: retainer of R2P Strategies' Cindi Merifield ... as CAA's federal lobbyist" / "R2P Strategies' retainer on the LDA record"

Source: https://lda.gov/api/v1/filings/?client_name=concept+art+association (Senate LDA public API; newly fetched pass 4)
Source tier: primary
Source content: LDA filings — registrant "R2P STRATEGIES, LLC", client "CONCEPT ART ASSOCIATION", lobbyist "CYNTHIA MERIFIELD IRION": 2023 Registration plus 1st–4th Quarter 2023 reports, on matters including copyright/arts-entertainment, both chambers.
Comparison: The Senate's own Lobbying Disclosure Act database confirms the R2P Strategies retainer, Merifield as the named lobbyist, and the 2023 registration timing ("early 2023" matches a 2023 Registration followed by a Q1 report). Resolves the retainer half of pass 3's uncorroborated composite claim.
Decision: primary-sourced

## Claim 5: Cindi Merifield "formerly chief lobbyist for the Motion Picture Association of America"

Source: https://thehill.com/business-a-lobbying/lobbying-contracts/249571-lobbying-world/ (HTTP 403 on direct fetch; content via search snippets, consistent across two independent queries)
Source tier: mainstream
Source content: The Hill "Lobbying World" column: "Longtime lobbyist Cindi Merifield Tripodi is opening her own lobby shop called R2P — harkening to the 'right to petition' portion of the Constitution's First Amendment. She spent a decade at the Nickles Group as a founding partner and, before that, was the chief lobbyist for the Motion Picture Association of America."
Comparison: A mainstream outlet with editorial standards carries the MPAA chief-lobbyist history as stated. Snippet-reached (direct fetch 403); R2P's own bio (401) and OpenSecrets (403) remain unfetchable, so no second canonical source. Upgraded from pass 3's uncorroborated to single-source on the strength of the attributed Hill text.
Decision: single-source

## Claim 6: "Concept Art Association, LLC as the registered federal-lobbying entity through which the retainer is reported on the Lobbying Disclosure Act record"

Source: https://www.legistorm.com/organization/summary/187721/Concept_Art_Association_LLC.html (entity-cited; pass-3 record); https://lda.gov/api/v1/filings/?client_name=concept+art+association (pass 4)
Source tier: primary
Source content: LegiStorm (pass 3): "Concept Art Association LLC has lobbied the U.S. government." LDA API (pass 4): client "CONCEPT ART ASSOCIATION" with R2P Strategies as registrant, 2023 registration + quarterly reports. (The LDA client-name string renders without the LLC suffix; LegiStorm's record of the same filings carries it — same entity, no contradiction asserted.)
Comparison: The lobbying-is-registered-and-LDA-reported fact is confirmed by the LDA record itself and LegiStorm's database view of it.
Decision: corroborated

## Claim 7: "2023: first series of D.C. visits, with named meetings in the offices of Representatives Michael McCaul, Don Beyer, Ted Lieu, and Darrell Issa, and Senators Martin Heinrich and Dick Durbin, alongside a virtual meeting with the FTC's Acting Director of Privacy and Identity Protections"

Source: https://www.conceptartassociation.com/advocacy (entity-cited; re-fetched pass 4)
Source tier: none
Source content: Current CAA advocacy page (pass-4 fetch) carries no mention of the named congressional offices or the named FTC official; page focus remains AB 412 and artist resources. Pass-3 WebSearch found confirmation of D.C. visits generally but "the publicly available sources do not detail which specific offices or members they met with." web.archive.org not fetchable from this environment.
Comparison: The cited source no longer carries the named six-office roster and no other canonical source confirms it. The general fact of 2023 D.C. meetings is confirmed; the specific roster is not. Same posture as passes 2–3.
Decision: uncorroborated

## Claim 8: "12 July 2023: Karla Ortiz's invited testimony before the U.S. Senate Judiciary Subcommittee on Intellectual Property hearing 'Artificial Intelligence and Intellectual Property – Part II: Copyright'"

Source: https://www.judiciary.senate.gov/imo/media/doc/2023-07-12_pm_-_testimony_-_ortiz.pdf (entity-cited); https://www.sfbar.org/sfam/q3-art-v-ai/ (pass-3 fetch); Coons press release (pass-1 record)
Source tier: primary
Source content: Senate Judiciary URL path "2023-07-12_pm_-_testimony_-_ortiz.pdf"; SF Bar: "She made this statement during a July 2023 hearing before the US Senate"; pass-1 Coons release named the hearing title and subcommittee.
Comparison: Date, witness, venue, and hearing title match across multiple sources on record.
Decision: corroborated

## Claim 9: hearing "chaired by Senator Chris Coons (D–DE) with Senator Thom Tillis (R–NC) as ranking member"

Source: https://www.coons.senate.gov/news/press-releases/video-senator-coons-chairs-second-judiciary-ip-subcommittee-hearing-on-artificial-intelligence-in-a-series (pass-1 quote retained)
Source tier: primary
Source content: Pass-1 quote: "Chair Chris Coons (D-Del.) and Ranking Member Thom Tillis (R-N.C.)".
Comparison: Chair and ranking member match the senator's own press release — one primary source on record (relabelled from pass 3's corroborated to reflect the single recorded source).
Decision: primary-sourced

## Claim 10: Karla Ortiz spoken line "I have never been asked, never been credited, never been compensated"

Source: https://www.sfbar.org/sfam/q3-art-v-ai/ (entity-cited; pass-3 fetch)
Source tier: mainstream
Source content: SF Bar article: "I have never been asked…never been credited…never been compensated.", attributed to Karla Ortiz in the July 2023 Senate-hearing context.
Comparison: Quote and attribution match the one canonical source on record. Living-person quoted statement, so the stricter rule applies: one mainstream-standard document supports it; no second source recorded.
Decision: single-source

## Claim 11: "4 October 2023 CAA's Karla Ortiz and Steven Zapata represented the Concept Art Association on the panel of working creators at the FTC's Creative Economy and Generative AI public roundtable, convened by Chair Lina Khan"

Source: https://www.ftc.gov/news-events/events/2023/10/creative-economy-generative-ai (entity-cited; pass-1 record); ABA recap (pass-2 record); WebSearch Zapata confirmation (pass-3 record)
Source tier: primary
Source content: FTC event page names the 4 October 2023 roundtable convened under Chair Lina Khan; pass-3 search record: "Concept Art Association represented concept artists speaking before the FTC about generative AI, with Steven Zapata speaking as a concept artist on behalf of the organization."
Comparison: Date, convener, Khan's role, and both CAA representatives confirmed across the recorded sources.
Decision: corroborated

## Claim 12: Ortiz FTC-roundtable framing: "only works when the basic tenants of consent, credit, compensation, and transparency are followed" and "took our work and data to train for-profit technologies that then directly compete against us in our own market, using generative media that is meant to mimic us"

Source: VentureBeat "Our life's work" article (403 on direct fetch passes 3–4; pass-2 search-snippet quotes retained); https://www.conceptartassociation.com/advocacy and SF Public Press (corroborating the formulation)
Source tier: mainstream
Source content: Pass-2 retained quotes: "The creative economy only works when the basic tenants of consent, credit compensation and transparency are followed." and "took our work and data to train for-profit technologies that then directly compete against us in our own market, using generative media that is meant to mimic us."
Comparison: Both lines match within paraphrase tolerance; the consent-credit-compensation-transparency formulation is independently carried by CAA's own materials and SF Public Press coverage.
Decision: corroborated

## Claim 13: "15 December 2023: publication of the FTC staff report Generative Artificial Intelligence and the Creative Economy"

Source: https://www.ftc.gov/system/files/ftc_gov/pdf/12-15-2023AICEStaffReport.pdf (entity-cited)
Source tier: primary
Source content: FTC document URL path: "12-15-2023AICEStaffReport.pdf" — date 12-15-2023, title "AI and the Creative Economy Staff Report".
Comparison: Date and title consistent with the FTC's own URL path; one primary source on record (relabelled from pass 3's corroborated).
Decision: primary-sourced

## Claim 14: CAA co-sponsorship with SAG-AFTRA, NAVA, and the Authors Guild of California AB 412, Assemblymember Rebecca Bauer-Kahan's "AI Copyright Transparency Act"

Source: https://www.conceptartassociation.com/advocacy (entity-cited; re-fetched pass 4); https://www.sfpublicpress.org/california-creatives-rally-behind-state-ai-rules-to-save-their-artwork/ (pass-3 record)
Source tier: primary
Source content: CAA advocacy page (pass 4): CAA is "a Co-Sponsor (alongside SAG-AFTRA, NAVA and The Authors Guild)" of the AI Copyright Transparency Act. SF Public Press names Bauer-Kahan as AB 412's author.
Comparison: Co-sponsors, bill author, and bill name all match across two sources. (The "2024:" year label attached to this milestone in the `outcomes` scalar is treated as its own claim — Claim 15.)
Decision: corroborated

## Claim 15: scalar:outcomes — "2024: CAA co-sponsorship with SAG-AFTRA, the National Association of Voice Actors (NAVA), and the Authors Guild of California AB 412"

Source: https://leginfo.legislature.ca.gov/faces/billHistoryClient.xhtml?bill_id=202520260AB412 (newly fetched pass 4)
Source tier: primary
Source content: AB 412 bill history: "Read first time. To print" on 02/04/25 — the bill was introduced 4 February 2025.
Comparison: The `outcomes` scalar's milestone label dates the AB 412 co-sponsorship to 2024, but AB 412 did not exist until February 2025; the body proper correctly says "In February 2025 Assemblymember Rebecca Bauer-Kahan introduced California AB 412". The year token contradicts the Legislature's primary record; correct replacement is 2025. Fix location: the `outcomes` frontmatter scalar's "2024:" milestone entry. Note for the Editor: the same milestone entry also carries genuinely-2024 AB 2013 content, so if the fix requires splitting the entry rather than a single-token change, flag to the Researcher per the pipe.
Decision: correction

## Claim 16: AB 2013 ("California Generative AI Training Data Transparency Act") by Assemblymember Jacqui Irwin, signed by Newsom fall 2024, effective 1 January 2025, compliance deadline 1 January 2026

Source: https://www.sfpublicpress.org/california-creatives-rally-behind-state-ai-rules-to-save-their-artwork/ (entity-cited; pass-3 fetch); Morgan Lewis and Transparency Coalition write-ups (pass-3 search record)
Source tier: mainstream
Source content: Pass-3 record: SF Public Press names Irwin as lead sponsor and confirms the signing window and Jan 2025 / Jan 2026 dates; "California Governor Gavin Newsom signed AB 2013 into law on September 29, 2024" (Morgan Lewis). September 29 falls within "fall 2024".
Comparison: Author, signing window, effective date, and compliance deadline all match across multiple recorded sources.
Decision: corroborated

## Claim 17: scalar:outcomes — "21 July 2025: AB 412 passed out of the California State Assembly and went into the California Senate's Judiciary Committee"

Source: https://leginfo.legislature.ca.gov/faces/billHistoryClient.xhtml?bill_id=202520260AB412 (newly fetched pass 4); https://www.conceptartassociation.com/advocacy (re-fetched pass 4)
Source tier: primary
Source content: AB 412 bill history: 05/12/25 — "Read third time. Passed. Ordered to the Senate. (Ayes 45. Noes 16.)"; 05/13/25 — "In Senate. Read first time. To Com. on RLS. for assignment"; 05/21/25 — "Referred to Coms. on JUD. and APPR." CAA advocacy page: "AB-412 has passed out of the California State Assembly, and it is currently in the CA Senate's Judiciary Committee" as of July 21, 2025.
Comparison: The Legislature's primary record shows the Assembly passage on 12 May 2025 and Senate Judiciary referral on 21 May 2025. CAA's "July 21st 2025" is the date of its status update, not of the passage; the `outcomes` scalar misreads it as the event date. The date token "21 July 2025" contradicts the primary record; correct replacement for the passage milestone is 12 May 2025. The body proper's "As of July 2025 AB 412 had passed out of the California State Assembly" framing is consistent with the record and needs no fix — the fix location is the `outcomes` frontmatter scalar only. (Passes 1–3 accepted the CAA page's phrasing at face value; the primary record was first reached this pass.)
Decision: correction

## Claim 18: "model contract rider — a 'sample contract rider for work-for-hire contracts and license agreements' — that working artists can attach to client contracts to refuse the inclusion of their work in generative-AI training datasets without consent"

Source: https://www.conceptartassociation.com/advocacy (entity-cited; re-fetched pass 4)
Source tier: primary
Source content: CAA advocacy page (pass 4): "sample contract rider for their work-for-hire contracts and license agreements to help protect their works from being added to generative AI datasets".
Comparison: The rider is CAA's own artifact and its own page is the authoritative source for it; quote matches.
Decision: primary-sourced

## Claim 19: "Andersen v. Stability AI [filed] the following month [January 2023] in the Northern District of California"

Source: https://copyrightalliance.org/andersen-v-stability-ai-copyright-case/ (pass-3 fetch); BuzzFeed News profile (entity-cited; pass-1 record)
Source tier: mainstream
Source content: Pass-3 record: "In early 2023, visual artists Sarah Andersen, Kelly McKernan, and Karla Ortiz filed a class-action lawsuit against Stability AI, Midjourney, and DeviantArt"; venue "Northern District of California".
Comparison: Filing window, venue, and plaintiff roster match across the recorded sources.
Decision: corroborated

## Claim 20: "The named California-side individuals carrying the work at the state-legislative level — Karla Ortiz, Nicole Hendrix, Kelly McKernan, Reid Southen, Andrew Leung, and Tiana Oreglia — overlap substantially with the federal-policy roster"

Source: https://www.sfpublicpress.org/california-creatives-rally-behind-state-ai-rules-to-save-their-artwork/ (entity-cited; pass-3 fetch)
Source tier: mainstream
Source content: Pass-3 record: SF Public Press names all six individuals in the California state-policy context; only Oreglia and Hendrix are explicitly CAA-affiliated there.
Comparison: All six names appear in the cited source as California-creator AI-policy participants, but the composite "carrying the work" list-membership framing is broader than what the source establishes; partially supported, no source contradicts it. Same posture as passes 2–3.
Decision: uncorroborated

## Claim 21: Karla Ortiz "would become a co-plaintiff in Andersen v. Stability AI one month after launch"

Source: https://copyrightalliance.org/andersen-v-stability-ai-copyright-case/ (pass-3 fetch); BuzzFeed News profile (pass-1 record)
Source tier: mainstream
Source content: Pass-3 record: "visual artists Sarah Andersen, Kelly McKernan, and Karla Ortiz filed a class-action lawsuit"; Andersen is the lead-named plaintiff, Ortiz a co-plaintiff.
Comparison: Ortiz as co-plaintiff (not lead-named) matches; December 2022 launch → January 2023 filing is "one month after". The pass-2 discrepancy on this claim remains resolved (Editor backfill, commit 322cecae).
Decision: corroborated

## Claim 22: "31 August 2022 virtual town hall hosted by Karla Ortiz and the Concept Art Association — a public organising event with Abhishek Gupta of the Montreal AI Ethics Institute as a co-presenter"

Source: https://disconnect.blog/how-artists-are-fighting-generative-ai/ (pass-2 fetch; quote retained); entity-cited YouTube URL
Source tier: mainstream
Source content: Pass-2 retained quote — Ortiz: "I did get to bring in a machine learning expert, in this case Abhishek Gupta from the Montreal AI Ethics Institute"; CAA identified as town-hall host; article dates the event "early September 2022".
Comparison: Participants and host match; the specific 31 August 2022 date rests on the YouTube record and is approximately consistent with "early September 2022".
Decision: corroborated

## Claim 23: edge — strategies: strat-creator-class-collective-bargaining-on-generative-ai (the pass-4 delta)

Source: local corpus check (product/entities/strategies/strat-creator-class-collective-bargaining-on-generative-ai.md) + campaign facts verified in Claims 1–22
Source tier: primary
Source content: Strategy entity file exists. Its Verdict names this campaign in the adopter set ("the [Concept Art Association federal-policy advocacy track](../campaigns/camp-concept-art-association-federal-policy-advocacy-2022-ongoing.md)") and names the Concept Art Association "on the visual-artist side"; its opening scope explicitly includes "federal-policy advocacy on training-data disclosure" among the strategy's instruments; its Ecology section cites this campaign again as an open-letter-launched sectoral track.
Comparison: Edge target exists, the campaign's verified shape (professional-association federal-and-state policy advocacy on training-data consent/credit/compensation/transparency) matches the named strategy's stated instrument set, and the reciprocal adopter record on the strategy side agrees.
Decision: corroborated
