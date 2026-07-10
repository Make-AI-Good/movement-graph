---
entity_id: camp-authors-guild-openai-class-action-2023
entity_hash: 5562b6722a281a4abf6f04975346a79bc18f720b
audit_date: 2026-07-10
pass: 2
status: corrections-pending
claims_total: 54
claims_corroborated: 6
claims_primary_sourced: 27
claims_single_source: 4
claims_uncorroborated: 14
open_corrections: 3
sources_consulted:
  - https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
  - https://authorsguild.org/news/ai-class-action-lawsuits/
  - https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
  - https://authorsguild.org/news/ag-supports-nonfiction-writers-in-lawsuit-against-openai/
  - https://authorsguild.org/about/
  - https://authorsguild.org/advocacy/artificial-intelligence/what-authors-need-to-know-about-the-anthropic-settlement/
  - https://www.lieffcabraser.com/openai-copyright/
  - https://bannerwitcoff.com/ip-alert-authors-copyright-battle-against-openai-survives-motion-to-dismiss/
  - https://www.publishersweekly.com/pw/by-topic/digital/copyright/article/98961-authors-class-action-lawsuit-against-openai-moves-forward.html
  - https://www.dww.com/articles/us-authors-guild-files-class-action-against-openai-for-copyright-infringement
  - https://docs.justia.com/cases/federal/district-courts/new-york/nysdce/1:2023cv08292/606655/59
  - https://www.courtlistener.com/docket/67810584/authors-guild-v-openai-inc/
---

Connective type (campaign): claim surface is the edges (`lead_orgs`, `events`,
`strategies`) and hard specifics per `AUDITOR.md § Type-shape` /
`MISSION.md § Auditor § Type-shape awareness`. Interpretive prose (the
"field-defining" framing, genre-bucket characterizations of the roster,
"highest-revenue commercial writers", Position-in-the-corpus significance
prose) received no decision. Court-record pages (CourtListener docket,
Justia order documents, Courthouse News) 403 on direct fetch; where a court
record is cited, the content was retrieved via web search this session with
the direct-fetch block noted. Pass-1 correction (Lang quote) remains open —
the body is unchanged at that location; two new corrections found in the
`outcomes` frontmatter scalar.

## Claim 1: edge lead_orgs → org-authors-guild

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: The Authors Guild's own announcement of the filing, with the Guild as institutional plaintiff alongside seventeen named authors.
Comparison: Edge target exists in corpus; the Guild's own release confirms it as the lead institutional plaintiff, which is the lead_orgs basis the entity asserts.
Decision: primary-sourced

## Claim 2: edge events → event-authors-guild-openai-class-action-filing-2023-09-20

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: Announcement of the class-action filing in the Southern District of New York, September 2023.
Comparison: Edge target exists in corpus and names the filing event this campaign is anchored on; referent correct. (The 19-vs-20 September day-grain question is Claim 5, not an edge defect.)
Decision: primary-sourced

## Claim 3: edge strategies → strat-class-action-litigation-against-private-ai

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: "Class-Action Suit Against OpenAI" — a putative class action by authors against a private AI developer.
Comparison: Edge target exists in corpus; the campaign is definitionally an instance of the strategy the edge names; referent correct.
Decision: primary-sourced

## Claim 4: edge strategies → strat-creator-class-collective-bargaining-on-generative-ai

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: Suit filed by the Guild and seventeen authors "on behalf of a class of fiction writers", seeking consent/compensation terms for training use.
Comparison: Edge target exists in corpus; the campaign's creator-class collective posture (professional guild + author class pressing licensing terms) matches the strategy's subject; referent correct.
Decision: primary-sourced

## Claim 5: Filing date "On 20 September 2023" (body; frontmatter start_date: 2023-09-20)

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: AG announcement: "September 20, 2023, in the Southern District of New York."
Comparison: The Guild's own release supports 20 September, but the pass-1 record already noted Variety's article header dating the filing 19 September, and independent coverage retrieved this session also states the case "was filed on September 19, 2023"; the court docket (the source that would settle the day-grain) 403s on direct fetch. Canonical sources conflict on the day; do not pick a winner. Affects body and `start_date` scalar equally.
Decision: uncorroborated

## Claim 6: Filing venue "U.S. District Court for the Southern District of New York"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/ ; https://www.dww.com/articles/us-authors-guild-files-class-action-against-openai-for-copyright-infringement
Source tier: primary
Source content: AG: "in the Southern District of New York." DWW independently reports the SDNY class action; AG's case tracker styles it "No. 1:23-cv-8292 (S.D.N.Y.)".
Comparison: Two independent canonical sources confirm the venue.
Decision: corroborated

## Claim 7: Case number "1:23-cv-08292" and styling "Authors Guild et al. v. OpenAI Inc. et al."

Source: https://authorsguild.org/news/ai-class-action-lawsuits/ ; https://www.courtlistener.com/docket/67810584/authors-guild-v-openai-inc/
Source tier: primary
Source content: AG tracker: "Authors Guild v. OpenAI & Microsoft, No. 1:23-cv-8292 (S.D.N.Y.)". CourtListener docket (title retrieved via search; direct fetch 403): "Authors Guild v. OpenAI Inc., 1:23-cv-08292".
Comparison: Case number matches (leading-zero padding non-substantive); styling matches the docket title at original-complaint grain.
Decision: corroborated

## Claim 8: Seventeen named author plaintiffs — full roster (Baldacci, Bly, Connelly, Day, Franzen, Grisham, Hilderbrand, Kline, Lang, LaValle, Martin, Picoult, Preston, Robinson, Saunders, Turow, Vail)

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/ ; court-record plaintiff list via https://docs.justia.com/cases/federal/district-courts/new-york/nysdce/1:2023cv08292/606655/59 (search-retrieved)
Source tier: primary
Source content: AG lists all seventeen names verbatim as in the body; the consolidated-complaint plaintiff list from the SDNY docket independently carries all seventeen (interleaved with the nonfiction plaintiffs).
Comparison: Body roster matches both sources exactly.
Decision: corroborated

## Claim 9: "the first major U.S. federal class-action lawsuit by published novelists against an AI developer" and (outcomes scalar) "the first to advance to merits discovery on output-based copyright infringement"

Source: no canonical source found
Source tier: none
Source content: No fetched source asserts either firstness claim explicitly.
Comparison: Contested "first" attributions require a non-Wikipedia canonical source that states them; none surfaced. Appears in body and in scalar:outcomes item (i). Not a finding of error.
Decision: uncorroborated

## Claim 10: Open letter dated "18 July 2023"

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source tier: primary
Source content: "July 18, 2023."
Comparison: Date matches.
Decision: primary-sourced

## Claim 11: Letter "addressed to the CEOs of OpenAI, Alphabet, Meta, Stability AI, IBM, and Microsoft"

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source tier: primary
Source content: "OpenAI, Alphabet, Meta, Stability AI, IBM, and Microsoft."
Comparison: Addressee list matches exactly.
Decision: primary-sourced

## Claim 12: Letter "signed by 15,000+ writers"

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source tier: primary
Source content: "More than 15,000 writers and supporters."
Comparison: Count matches at the 15,000+ grain; source phrases the pool as "writers and supporters" where the body says "writers" — within paraphrase tolerance, no token contradiction.
Decision: primary-sourced

## Claim 13: Lead-author signature roster of the open letter (Brown, Patterson, Atwood, Picoult, Collins, Franzen, Gay, Ng, Erdrich, Nguyen, Saunders, Lee, Chabon, N. Roberts, Baldacci, Ward)

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source tier: primary
Source content: Notable signatories named: "Dan Brown, James Patterson, Jennifer Egan, David Baldacci, Michael Chabon, Nora Roberts, Jesmyn Ward, Jodi Picoult, Ron Chernow, Michael Pollan, Suzanne Collins, Margaret Atwood, Jonathan Franzen, Roxane Gay, Celeste Ng, Louise Erdrich, Viet Thanh Nguyen, George Saunders, Min Jin Lee, Andrew Solomon, Rebecca Makkai, and Tobias Wolff."
Comparison: Every body-listed name appears in the source's notable-signatory list; body's "bearing the lead-author signatures of" admits subset presentation.
Decision: primary-sourced

## Claim 14: Letter's three demands — consent before training, compensation for past training uses, compensation for AI outputs

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source tier: primary
Source content: "(1) Obtain permission for the use of copyrighted material in generative AI programs. (2) Fairly compensate writers for both past and ongoing use of their works in generative AI programs. (3) Fairly compensate writers for the use of their works in AI output, regardless of whether the outputs infringe upon current laws."
Comparison: Body's three-demand summary matches the source's demands.
Decision: primary-sourced

## Claim 15: "Six of the named litigation plaintiffs (Picoult, Franzen, Saunders, Baldacci, plus eventual class representatives Maya Shanbhag Lang and Jonathan Franzen) had been signatories to the open letter"

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source tier: none
Source content: The notable-signatory list contains Picoult, Franzen, Saunders, and Baldacci among the litigation plaintiffs; Lang appears on the page only as Guild president (quoted), not as a listed signatory.
Comparison: The sentence counts "six" while listing five unique names (Franzen appears twice); only four of the names are confirmable as signatories from the source's notable list, and signatory status of Lang (or any fifth/sixth plaintiff) cannot be determined from the 15,000-name pool. Count unverifiable; internal name-list inconsistency noted for the record but no single correct replacement token is source-derivable.
Decision: uncorroborated

## Claim 16: Franzen "designated as a class representative"; Saunders "the second author class representative"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: "Class Representatives: Maya Shanbhag Lang, George Saunders, and Jonathan Franzen."
Comparison: Franzen and Saunders confirmed as class representatives. The source names three representatives; the body's "second" ordinal is presentational, not a token contradiction.
Decision: primary-sourced

## Claim 17: Original complaint "named OpenAI Inc., OpenAI OpCo LLC, OpenAI GP LLC, and OpenAI Holdings LLC as defendants"

Source: https://www.dww.com/articles/us-authors-guild-files-class-action-against-openai-for-copyright-infringement
Source tier: none
Source content: DWW: "several OpenAI entities (the Defendants)" — no verbatim entity list. Search-level traces of the docket indicate a larger defendant set (including OpenAI LP, OpenAI Global LLC, and OpenAI Startup Fund entities) than the body's four.
Comparison: The four named entities cannot be confirmed as the complaint's defendant roster, and retrieved indications suggest the body's list under-enumerates; the docket caption (PACER/CourtListener) that would settle it 403s on direct fetch. Cannot confirm; cannot assert a specific token error.
Decision: uncorroborated

## Claim 18: Complaint "pleaded direct, vicarious, and contributory copyright infringement under 17 U.S.C. § 501"

Source: https://www.dww.com/articles/us-authors-guild-files-class-action-against-openai-for-copyright-infringement
Source tier: none
Source content: DWW identifies "copyright infringement under the US Copyright Act" without distinguishing direct/vicarious/contributory theories or citing § 501.
Comparison: The three-theory breakdown and statute citation were not confirmed by any fetched source; complaint text needed.
Decision: uncorroborated

## Claim 19: Books downloaded from "pirate ebook shadow-library repositories — Library Genesis, Z-Library, the now-shut-down Bibliotik tracker"

Source: no canonical source found
Source tier: none
Source content: DWW references books "downloaded from pirate ebook repositories" without naming the three repositories; no fetched source names Library Genesis, Z-Library, or Bibliotik in connection with this complaint.
Comparison: The general pirate-repository claim is supported; the specific three-repository enumeration is not confirmed by any fetched source.
Decision: uncorroborated

## Claim 20: Complaint "asked for statutory damages, injunctive relief preventing further training and operation of GPT models on the plaintiffs' works without licences"

Source: https://www.dww.com/articles/us-authors-guild-files-class-action-against-openai-for-copyright-infringement
Source tier: mainstream
Source content: Relief sought: injunctive relief "prohibiting the Defendants from infringing the Plaintiffs' and class members' copyrights, including enjoining the Defendants from using such copyrighted works in 'training' their LLMs without express authorization"; "Statutory damages up to $150,000 per infringed work."
Comparison: Both relief categories match the body's characterization.
Decision: single-source

## Claim 21: The Guild's framing of "a fair licensing regime" for AI training (quoted phrase)

Source: no canonical source found
Source tier: none
Source content: Neither AG announcement extraction surfaced the quoted phrase "a fair licensing regime".
Comparison: The body presents the phrase as a quotation; verbatim confirmation not obtained this session.
Decision: uncorroborated

## Claim 22: Counsel Lieff Cabraser Heimann & Bernstein, Rachel Geman as lead counsel / partner-in-charge

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/ ; https://www.lieffcabraser.com/openai-copyright/
Source tier: primary
Source content: AG: "Lieff Cabraser Heimann & Bernstein, LLP (Rachel Geman)". Lieff Cabraser's own case page confirms the firm as plaintiffs' counsel (no attorney names on the current page).
Comparison: Firm role confirmed by both; Geman attribution rests on the AG release (primary for its own case's counsel).
Decision: primary-sourced

## Claim 23: Cowan, DeBaets, Abrahams & Sheppard LLP / Scott J. Sholder as co-counsel

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: "Cowan, DeBaets, Abrahams & Sheppard LLP (Scott Sholder)."
Comparison: Co-counsel firm and attorney match. Resolves pass-1's uncorroborated finding — the attribution is on the Guild's own release.
Decision: primary-sourced

## Claim 24: Mary Rasenberger quote "it is imperative that we stop this theft in its tracks…"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: "It is imperative that we stop this theft in its tracks or we will destroy our incredible literary culture, which feeds many other creative industries in the U.S."
Comparison: Body quote matches the release verbatim through the passage quoted (case variation on embedded "it" tolerated).
Decision: primary-sourced

## Claim 25: Maya Shanbhag Lang quote "the Authors Guild serves to protect the literary landscape and the profession of writing. This case is merely the beginning of our battle to defend authors from theft by OpenAI."

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: "The Authors Guild serves to protect the literary landscape and the profession of writing. This case is merely the beginning of our battle to defend authors from theft by OpenAI and other generative AI."
Comparison: Re-confirmed this session: the body's quotation truncates the final four words "and other generative AI", narrowing whom Lang names as adversary, and (per pass 1) concatenates two source-separate statements without an ellipsis. Fix location: body, § "The 20 September 2023 complaint" — restore the quote's ending "…by OpenAI and other generative AI." Open since pass 1 (2026-05-18); body unchanged at this location.
Decision: correction

## Claim 26: Jonathan Franzen quote "generative AI is a vast new field for Silicon Valley's longstanding exploitation of content providers"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: "Generative AI is a vast new field for Silicon Valley's longstanding exploitation of content providers. Authors should have the right to decide when their works are used to 'train' AI."
Comparison: Body quotes the first sentence verbatim; trailing-sentence omission is quotation-length tolerance, not content alteration.
Decision: primary-sourced

## Claim 27: George Saunders quote "writers should be fairly compensated for their work. Fair compensation means that a person's work is valued."

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: "…Writers should be fairly compensated for their work. Fair compensation means that a person's work is valued, plain and simple. …" (two sentences from the middle of a longer Saunders statement).
Comparison: Both quoted sentences appear verbatim in the source; the trailing "plain and simple" is dropped from the second sentence — meaning unaltered, within tolerance per pass 1.
Decision: primary-sourced

## Claim 28: "On 4 December 2023 … amended complaint adding Microsoft Corporation as a co-defendant"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source tier: primary
Source content: "Microsoft was named as a defendant on December 4, 2023."
Comparison: Date and defendant addition match. Appears in body and in scalar:outcomes milestone one.
Decision: primary-sourced

## Claim 29: Microsoft amendment's basis — "multi-billion-dollar investment in OpenAI and … commercial distribution … through Bing Chat (later Copilot), the Microsoft 365 Copilot product line, and the Azure OpenAI Service" (body; parallel in scalar:goals and scalar:outcomes)

Source: no canonical source found
Source tier: none
Source content: The entity's cited Courthouse News article 403s on direct fetch; no fetched source enumerates the distribution channels or the investment predicate.
Comparison: The channel enumeration and investment-basis specifics could not be compared this session.
Decision: uncorroborated

## Claim 30: Alter v. OpenAI (aka Sancton) filed 21 November 2023, amended 19 December 2023, case number 1:23-cv-10211

Source: https://authorsguild.org/news/ag-supports-nonfiction-writers-in-lawsuit-against-openai/ ; https://authorsguild.org/news/ai-class-action-lawsuits/
Source tier: primary
Source content: AG nonfiction release: original filing November 21, 2023; amended complaint December 19, 2023; case name "Sancton v. OpenAI et al". AG tracker: "Alter v. OpenAI & Microsoft, No. 1:23-cv-10211 (S.D.N.Y.)".
Comparison: All three tokens match. Resolves pass-1's uncorroborated finding on the 21 November original-filing date.
Decision: primary-sourced

## Claim 31: Alter/Sancton nonfiction plaintiff roster (Sancton, Tolentino, Shapiro, Okrent, Sides, Alter, Branch, Linden, Schiff, Winchester, Bird, Cohen) — body § "The Alter case"

Source: https://authorsguild.org/news/ag-supports-nonfiction-writers-in-lawsuit-against-openai/
Source tier: primary
Source content: "Julian Sancton, Jia Tolentino, James Shapiro, Daniel Okrent, Wade Hampton Sides, Jonathan Alter, Taylor Branch, Eugene Linden, Stacy Schiff, Simon Winchester, Kai Bird, and Rich Cohen."
Comparison: Body roster matches exactly. Michael Chabon is not on this roster (see Claim 33).
Decision: primary-sourced

## Claim 32: Rasenberger quote "these lawsuits send a clear message to AI companies that authors are taking a strong stand against uses of their works without consent or compensation"

Source: https://authorsguild.org/news/ag-supports-nonfiction-writers-in-lawsuit-against-openai/
Source tier: primary
Source content: "These lawsuits send a clear message to AI companies that authors are taking a strong stand against uses of their works without consent or compensation."
Comparison: Verbatim match.
Decision: primary-sourced

## Claim 33: scalar:outcomes — Alter v. OpenAI described as "the parallel nonfiction-authors case led by Julian Sancton, Jonathan Alter, Jia Tolentino, Michael Chabon, and others"

Source: https://authorsguild.org/news/ag-supports-nonfiction-writers-in-lawsuit-against-openai/ ; https://authorsguild.org/news/ai-class-action-lawsuits/
Source tier: primary
Source content: The AG nonfiction release's twelve-name roster does not include Michael Chabon; the AG tracker lists "Chabon v. OpenAI" as a separate case (a Northern District of California suit transferred to SDNY in April 2025), not part of the Alter nonfiction action.
Comparison: The name token "Michael Chabon" in the Alter parenthetical contradicts the Guild's own roster — Chabon led a separate case, correctly handled elsewhere in the same scalar. Fix location: scalar:outcomes, second milestone parenthetical — remove "Michael Chabon" from the Alter plaintiff list (the body's § "The Alter case" roster is already correct).
Decision: correction

## Claim 34: "On 24 January 2024 Judge Sidney H. Stein ordered the consolidation … and set a 2 February 2024 deadline for … a consolidated class-action complaint and a 16 February 2024 deadline for the defendants to respond"

Source: https://docs.justia.com/cases/federal/district-courts/new-york/nysdce/1:2023cv08292/606655/59 (court order; retrieved via search — direct fetch 403)
Source tier: primary
Source content: Consolidation order signed by Judge Sidney H. Stein on January 24, 2024, consolidating 23-cv-8292 with Alter 23-cv-10211 under Fed. R. Civ. P. 42 for pre-trial purposes; plaintiffs "were given until February 2, 2024, to file a consolidated class action complaint, and defendants were given until February 16, 2024, to respond."
Comparison: Order date, judge's full name, both deadlines, and the two consolidated cases all match. Resolves pass-1's uncorroborated finding.
Decision: primary-sourced

## Claim 35: "2 February 2024: the consolidated class-action complaint was filed, joining the fiction-side and nonfiction-side plaintiff rosters into a single pleading" with DMCA / trademark-dilution / unjust-enrichment counts

Source: SDNY docket records via https://docs.justia.com/cases/federal/district-courts/new-york/nysdce/1:2023cv08292/606655/59 (search-retrieved; direct fetch 403)
Source tier: primary
Source content: "The consolidated complaint was amended and filed on February 2, 2024, listing as plaintiffs John Grisham, Scott Turow, David Baldacci, James Shapiro, Authors Guild, … Julian Sancton, Michael Connelly, Stacy Schiff, and Sylvia Day" — a combined fiction + nonfiction roster. The DMCA, trademark-dilution, and unjust-enrichment counts appear in the consolidated pleading per the motion-to-dismiss record (Claim 41).
Comparison: Filing date and roster-joining match the court record; the counts' presence is confirmed indirectly by their survival at the October 2025 ruling.
Decision: primary-sourced

## Claim 36: Cases folded into the SDNY proceeding through 2024 — Basbanes, The New York Times Co., Raw Story Media, The Intercept Media, Daily News L.P., Center for Investigative Reporting

Source: https://authorsguild.org/news/ai-class-action-lawsuits/
Source tier: primary
Source content: Consolidated-cases list includes "Basbanes v. Microsoft Corp., OpenAI; New York Times Co. v. Microsoft Corp.; Raw Story Media v. OpenAI; Intercept Media v. OpenAI; Daily News v. Microsoft Corp.; Center for Investigative Reporting v. OpenAI."
Comparison: All six body-named cases appear on the Guild's consolidated list. The "throughout 2024" timing of each fold-in is not dated by the source but is consistent with the April-2025 transfer note covering the remaining cases.
Decision: primary-sourced

## Claim 37: "3 April 2025: the Northern District of California OpenAI book-and-author cases (Tremblay v. OpenAI, Silverman v. OpenAI, Chabon v. OpenAI, Millette v. OpenAI) were transferred to the SDNY"

Source: https://authorsguild.org/news/ai-class-action-lawsuits/
Source tier: primary
Source content: "In re OpenAI ChatGPT Litigation (transferred to Southern District of New York on April 3, 2025)" naming three cases: Tremblay, Silverman, and Chabon. Millette v. OpenAI appears in the twelve-case consolidated list but is not placed inside the April 3, 2025 transfer note.
Comparison: Three of the four body-named cases confirmed in the 3 April 2025 transfer; whether Millette moved in the same transfer or separately remains unresolved (as in pass 1).
Decision: uncorroborated

## Claim 38: "the twelve-case consolidated proceeding" / "twelve-case multi-district book-and-news class-action proceeding" (scalar:outcomes and body)

Source: https://authorsguild.org/news/ai-class-action-lawsuits/
Source tier: primary
Source content: The Guild's consolidated-cases list enumerates exactly twelve cases: Authors Guild, Alter, Basbanes, New York Times, Raw Story Media, Intercept Media, Daily News, Center for Investigative Reporting, Tremblay, Silverman, Chabon, Millette.
Comparison: Count matches exactly.
Decision: primary-sourced

## Claim 39: "In October 2025 Judge Stein issued his ruling on the defendants' motions to dismiss"

Source: https://www.publishersweekly.com/pw/by-topic/digital/copyright/article/98961-authors-class-action-lawsuit-against-openai-moves-forward.html ; https://bannerwitcoff.com/ip-alert-authors-copyright-battle-against-openai-survives-motion-to-dismiss/
Source tier: mainstream
Source content: Publishers Weekly dates the ruling October 28, 2025; Banner Witcoff (posted October 30, 2025) reports the ruling issued the Monday of that week.
Comparison: Month-grain claim confirmed by two independent canonical sources. (Pass 1's recorded "October 6" from Banner Witcoff does not match this session's extract of the same page; the body claims month grain only, which both sources support.)
Decision: corroborated

## Claim 40: ChatGPT-generated summaries and the "A Dance with Shadows" sequel outline of George R. R. Martin's A Song of Ice and Fire as the substantial-similarity exemplars

Source: https://bannerwitcoff.com/ip-alert-authors-copyright-battle-against-openai-survives-motion-to-dismiss/ ; https://www.publishersweekly.com/pw/by-topic/digital/copyright/article/98961-authors-class-action-lawsuit-against-openai-moves-forward.html
Source tier: mainstream
Source content: Banner Witcoff: the court analyzed an AI-generated sequel outline titled "A Dance with Shadows" (a sequel to Martin's A Clash of Kings) and found "a reasonable jury…could determine that this output is substantially similar to Martin's original work based on the output's incorporation of setting, plot, and characters." Publishers Weekly: "summaries and sequel outlines produced by ChatGPT could be found substantially similar to original works."
Comparison: Outline title and holding match; the body's series-level framing ("of A Song of Ice and Fire") is consistent with the source's book-level detail (A Clash of Kings is within that series).
Decision: corroborated

## Claim 41: Surviving claims — DMCA Section 1202 copyright-management-information, federal trademark dilution, unjust enrichment, and the "download claim"

Source: https://bannerwitcoff.com/ip-alert-authors-copyright-battle-against-openai-survives-motion-to-dismiss/
Source tier: mainstream
Source content: Surviving: "Direct copyright infringement based on ChatGPT outputs; DMCA violations for stripping copyright management information; Trademark dilution claims; Unjust enrichment claims; The 'download claim' for copyright infringement."
Comparison: All categories match. Publishers Weekly confirms only the copyright-output survival, so the full enumeration rests on Banner Witcoff.
Decision: single-source

## Claim 42: Allegations against GPT-4V, GPT-4.5, GPT-5 struck as exceeding the operative complaint's scope; case limited to GPT-3 through GPT-4o Mini

Source: https://bannerwitcoff.com/ip-alert-authors-copyright-battle-against-openai-survives-motion-to-dismiss/
Source tier: mainstream
Source content: "Judge Stein granted motions to strike allegations regarding GPT-4V, GPT-4.5, GPT-5, and their 'derivatives' or 'successors' because they exceeded the court's prior directive. The case remains limited to 'GPT-3 through GPT-4o Mini.'"
Comparison: Struck-model list and operative scope both match; no second source covers this detail.
Decision: single-source

## Claim 43: Court "expressly declined to opine on fair use", stating "nothing in this Opinion is intended to suggest a view on whether the allegedly infringing outputs are protected as fair uses of the original works"

Source: https://www.publishersweekly.com/pw/by-topic/digital/copyright/article/98961-authors-class-action-lawsuit-against-openai-moves-forward.html ; https://bannerwitcoff.com/ip-alert-authors-copyright-battle-against-openai-survives-motion-to-dismiss/
Source tier: mainstream
Source content: Publishers Weekly quotes Judge Stein: "Nothing in this opinion is intended to suggest a view on whether the allegedly infringing outputs are protected as fair uses of the original works." Banner Witcoff confirms fair use "remains unsettled in this case."
Comparison: The body's verbatim opinion quote matches Publishers Weekly's quotation exactly; the substantive declination is confirmed by both sources. Resolves pass 1's note that the quote's wording was unverified.
Decision: corroborated

## Claim 44: "The ruling sent the surviving claims into merits discovery"

Source: https://bannerwitcoff.com/ip-alert-authors-copyright-battle-against-openai-survives-motion-to-dismiss/
Source tier: mainstream
Source content: Magistrate Judge Ona T. Wang is "overseeing discovery" and the case "now continues forward."
Comparison: Post-ruling discovery posture confirmed by one source.
Decision: single-source

## Claim 45: "status conferences were held into the spring of 2026 with the case in active discovery as of May 2026" / scalar:outcomes "in active merits discovery with no trial date yet set"

Source: no canonical source found
Source tier: none
Source content: No fetched canonical source covers the spring-2026 status conferences, the May-2026 posture, or the absence of a trial date.
Comparison: The dated 2026 posture specifics could not be compared this session; docket access (PACER/CourtListener) blocked.
Decision: uncorroborated

## Claim 46: Authors Guild founded 1912 / "100+ years of standing copyright-and-contract advocacy"

Source: https://authorsguild.org/about/
Source tier: primary
Source content: "Since our founding in 1912, we have served as the collective voice of American authors."
Comparison: Founding year and century-plus duration both match the Guild's own about page.
Decision: primary-sourced

## Claim 47: Authors Guild has "17,000+ members"

Source: https://authorsguild.org/about/
Source tier: primary
Source content: "With more than 17,000 members, the Authors Guild is the nation's oldest and largest professional organization for published writers."
Comparison: Matches the Guild's own current about page. Pass 1's conflict rested on Wikipedia's "over 9,000" figure; Wikipedia is tiebreaker-tier for quantitative membership claims and a stale tiebreaker figure does not lower support against the entity's own primary source (quality-raises-support invariant). Resolves pass-1's uncorroborated finding.
Decision: primary-sourced

## Claim 48: scalar:outcomes — "the parallel $1.5 billion Bartz v. Anthropic settlement that the Authors Guild administered in 2025–2026"

Source: https://authorsguild.org/advocacy/artificial-intelligence/what-authors-need-to-know-about-the-anthropic-settlement/
Source tier: primary
Source content: The Guild's own settlement page shows a separate Settlement Administrator ("Contact Settlement Administrator … by calling 877-206-2314 or emailing info@AnthropicCopyrightSettlement.com") and describes the Guild's role as providing information, resources, legal assistance with claim forms, FAQs, and webinars. The $1.5 billion amount is confirmed: "The $1.5 billion award will be split among the rightsholders…"
Comparison: The settlement amount matches, but "administered" contradicts the Guild's own page — the settlement is administered by a court-appointed third-party administrator; the Guild's role was member support and advocacy. Fix location: scalar:outcomes, item (iv). The replacement requires a small prose judgment (e.g. "supported authors through" rather than "administered") — Editor should route via `[editor-flag]` if beyond a single mechanical replacement.
Decision: correction

## Claim 49: Lieff Cabraser's "AI-training-data docket includes parallel actions against Meta, Databricks, NVIDIA, and Google through 2023–2026"

Source: no canonical source found
Source tier: none
Source content: Search-level traces confirm Lieff Cabraser as counsel in author cases against Meta (Kadrey v. Meta, as additional counsel) and Databricks (O'Nan, Makkai); its role in the NVIDIA (Nazemian, Dubus) and Google (Zhang, Leovy) author cases was not confirmed by any fetched source, and the firm's own case page does not enumerate the docket.
Comparison: Two of four companies confirmable at search level only; the four-company enumeration as the firm's docket is not confirmed.
Decision: uncorroborated

## Claim 50: "Douglas Preston (an Authors Guild Council member)"

Source: https://authorsguild.org/app/uploads/2022/10/WIT-Bios_Douglas-Preston.pdf (surfaced via search this session)
Source tier: primary
Source content: The Guild's own bio describes Preston as "a journalist, novelist, and Authors Guild Council member"; Guild pages also record his service as Authors Guild President (elected 2019).
Comparison: Council membership confirmed on the Guild's own materials.
Decision: primary-sourced

## Claim 51: "Maya Shanbhag Lang (then Authors Guild President)"

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source tier: primary
Source content: Lang is named as president of the Authors Guild on the July 2023 letter page and quoted in that capacity.
Comparison: Presidency at the campaign's 2023 timeframe confirmed.
Decision: primary-sourced

## Claim 52: The Guild set up its AI advocacy programme "in response to the discovery — through the LLaMA training-corpus disclosure and subsequent reporting on the Books3 dataset — that books … had been ingested at scale"

Source: no canonical source found
Source tier: none
Source content: The Guild's standing AI-advocacy page exists (authorsguild.org/advocacy/artificial-intelligence/), but no fetched source states the programme's causal origin in the LLaMA/Books3 disclosures.
Comparison: Causal claims require a source asserting the causation; none surfaced. Programme existence is not in dispute.
Decision: uncorroborated

## Claim 53: scalar:goals — proposed class quoted as "fiction writers whose copyrighted works of fiction have been used by OpenAI to train its GPT large language models"

Source: https://www.dww.com/articles/us-authors-guild-files-class-action-against-openai-for-copyright-infringement
Source tier: none
Source content: DWW paraphrases the class as "a class of fiction writers whose works have been used to train GPT" — close but not the verbatim wording the scalar presents in quotation marks.
Comparison: The quoted class definition was not confirmed verbatim against the complaint; too paraphrastic to compare at quotation grain.
Decision: uncorroborated

## Claim 54: scalar:outcomes item (iii) — Guild engagement via "U.S. Copyright Office ex parte advocacy, Capitol Hill engagement on the NO FAKES Act, the AI Accountability and Personal Data Protection Act, and the COPIED Act"

Source: no canonical source found
Source tier: none
Source content: No fetched source this session covers the Guild's engagement with the named bills or the Copyright Office ex parte advocacy.
Comparison: The named-statute engagement list could not be compared; the Guild's advocacy pages would be the primary source for a future pass.
Decision: uncorroborated
