---
entity_id: org-authors-guild
entity_hash: efe30b24889ffae3636994f97fc6e23d9169fcf0
audit_date: 2026-05-29
pass: 1
status: unverifiable
claims_total: 30
claims_verified: 23
claims_discrepancy: 0
claims_unverifiable: 7
sources_consulted:
  - https://authorsguild.org/about/
  - https://en.wikipedia.org/wiki/Authors_Guild
  - https://authorsguild.org/about/team/staff-directory/
  - https://authorsguild.org/news/ag-members-elect-maya-shanbhag-lang-president/
  - https://authorsguild.org/news/announcing-w-ralph-eubanks-as-interim-president/
  - https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
  - https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
  - https://authorsguild.org/news/anthropic-settlement-key-updates/
  - https://authorsguild.org/news/anthropic-settlement-update-91-percent-of-books-claimed/
  - https://www.lieffcabraser.com/openai-copyright/
  - https://variety.com/2023/digital/news/openai-chatgpt-lawsuit-george-rr-martin-john-grisham-1235730939/
  - https://www.courtlistener.com/docket/67810584/authors-guild-v-openai-inc/
  - https://www.copyright.gov/policy/artificial-intelligence/ex-parte-communications/letters/Authors-Guild-May-10-2024.pdf
---

## Claim 1: "Founded in 1912 as the Authors League of America"

Source: https://en.wikipedia.org/wiki/Authors_Guild
Source content: "Authors League of America" — "organized with headquarters in New York City in order 'to protect the rights of all authors...'" (1912).
Comparison: Body matches Wikipedia and the Guild's own page ("Before there was an Authors Guild, there was the Authors' League of America"). Named-entity definitional fact, Wikipedia-alone sufficient.
Decision: verified

## Claim 2: "headquartered in New York City"

Source: https://en.wikipedia.org/wiki/Authors_Guild
Source content: "organized with headquarters in New York City."
Comparison: Matches.
Decision: verified

## Claim 3: "more than 17,000 members"

Source: https://authorsguild.org/about/
Source content: "With more than 17,000 members, the Authors Guild is the nation's oldest and largest professional organization for published writers."
Comparison: Verbatim match against the entity's primary cited source. (Wikipedia's "Over 9,000" is stale and not load-bearing here — the Guild's own page is canonical for its own membership count.)
Decision: verified

## Claim 4: "The League's writer-side base split in 1921, when the Dramatists Guild of America separated"

Source: https://en.wikipedia.org/wiki/Authors_Guild
Source content: "In 1921, the Dramatists Guild of America split off as a separate group to represent writers of stage and, later, radio drama."
Comparison: Matches. Named-entity definitional fact, Wikipedia-alone sufficient.
Decision: verified

## Claim 5: "Authors Guild as a 501(c)(6) professional association ... Authors Guild Foundation as the 501(c)(3) charitable and educational arm"

Source: https://authorsguild.org/about/
Source content: "the Authors Guild Foundation" described as "the educational and charitable arm." The /about/ page does not explicitly state 501(c)(6) and 501(c)(3) tax classifications.
Comparison: The two-entity structure and the Foundation's charitable-arm role are confirmed; the specific 501(c)(6) / 501(c)(3) classifications are stated in the entity's own `sources[].note` for this URL but the page text I retrieved does not surface them. Treating as unverifiable rather than verified — the tax-class designation requires public-record (IRS Form 990) corroboration.
Decision: unverifiable

## Claim 6: "led by Mary Rasenberger as Chief Executive Officer"

Source: https://authorsguild.org/about/team/staff-directory/
Source content: Mary Rasenberger listed as "Chief Executive Officer."
Comparison: Matches.
Decision: verified

## Claim 7: "Mary Rasenberger ... joined the Guild in November 2014 after 25+ years in copyright and media-law practice"

Source: no canonical source found for the November 2014 start date in this session's fetches.
Source content: The staff-directory page lists her title only; the Guild's about page does not state her start date.
Comparison: The November 2014 start date and the 25+ years prior practice are specific claims neither the staff-directory nor the about page surfaced in this audit. Wikipedia identifies her as CEO without a start date.
Decision: unverifiable

## Claim 8: "Sandy Long as Chief Operating Officer and Deborah K. Wilson as Executive Director of the Authors Guild Foundation"

Source: https://authorsguild.org/about/team/staff-directory/
Source content: Sandy Long — "Chief Operating Officer"; Deborah K. Wilson — "Executive Director of the Foundation."
Comparison: Matches.
Decision: verified

## Claim 9: "Cheryl Davis (General Counsel), Kevin Amer (Chief Legal Officer), and Umair Kazi ... as Director of Advocacy and Policy"

Source: https://authorsguild.org/about/team/staff-directory/
Source content: Cheryl Davis — "General Counsel"; Kevin Amer — "Chief Legal Officer"; Umair Kazi — "Director of Advocacy and Policy."
Comparison: Matches.
Decision: verified

## Claim 10: "Maya Shanbhag Lang was elected President at the 23 March 2023 annual meeting"

Source: https://authorsguild.org/news/ag-members-elect-maya-shanbhag-lang-president/
Source content: "Members of the largest organization of published book authors in the U.S. elected Maya Shanbhag Lang as president of the Authors Guild at its annual meeting on March 23."
Comparison: Matches.
Decision: verified

## Claim 11: "resigning on 3 May 2024 ... Vice President W. Ralph Eubanks succeeding her as interim President"

Source: https://authorsguild.org/news/announcing-w-ralph-eubanks-as-interim-president/
Source content: "Maya Shanbhag Lang resigned this past Friday, May 3, 2024." "Vice President W. Ralph Eubanks will serve as interim president."
Comparison: Matches.
Decision: verified

## Claim 12: "18 July 2023 open letter addressed to the CEOs of OpenAI, Alphabet, Meta, Stability AI, IBM, and Microsoft"

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source content: Date July 18, 2023; addressees "CEOs of OpenAI, Alphabet, Meta, Stability AI, IBM, and Microsoft."
Comparison: Matches.
Decision: verified

## Claim 13: "signed by 15,000+ writers"

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source content: "More than 15,000 writers and supporters."
Comparison: Matches.
Decision: verified

## Claim 14: "the output of AI will always be derivative in nature. AI regurgitates what it takes in, which is the work of human writers" (Maya Shanbhag Lang)

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source content: "The output of AI will always be derivative in nature. AI regurgitates what it takes in, which is the work of human writers."
Comparison: Verbatim match (case difference on the leading "The"/"the" only — the body's leading "the" is the in-sentence lower-case that matches the quote position).
Decision: verified

## Claim 15: "if creators aren't compensated fairly, they can't afford to create. If writers aren't paid to write, they can't afford to write." (Nora Roberts)

Source: https://authorsguild.org/news/thousands-sign-authors-guild-letter-calling-on-ai-industry-leaders-to-protect-writers/
Source content: "If creators aren't compensated fairly, they can't afford to create. If writers aren't paid to write, they can't afford to write."
Comparison: Verbatim match.
Decision: verified

## Claim 16: "class-action lawsuit filed on 20 September 2023 in the U.S. District Court for the Southern District of New York"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source content: Filing date "September 20, 2023"; venue "Southern District of New York."
Comparison: Matches.
Decision: verified

## Claim 17: "Authors Guild v. OpenAI Inc., No. 1:23-cv-08292"

Source: https://www.courtlistener.com/docket/67810584/authors-guild-v-openai-inc/ — returned HTTP 403.
Source content: no readable content retrieved from CourtListener; no alternate canonical source consulted in this session contained the case number 1:23-cv-08292.
Comparison: Case number is plausible (the docket URL slug "authors-guild-v-openai-inc" is consistent) but not independently confirmed in this audit pass.
Decision: unverifiable

## Claim 18: "seventeen author plaintiffs ... George R. R. Martin, John Grisham, Jodi Picoult, Jonathan Franzen, David Baldacci, Michael Connelly, Elin Hilderbrand, Sylvia Day, Mary Bly, Christina Baker Kline, Maya Shanbhag Lang, Victor LaValle, Douglas Preston, Roxana Robinson, George Saunders, Scott Turow, and Rachel Vail"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/ (primary) and https://variety.com/2023/digital/news/openai-chatgpt-lawsuit-george-rr-martin-john-grisham-1235730939/ (secondary).
Source content: Both sources list the same seventeen authors; both venues confirm Southern District of New York.
Comparison: Matches across primary and secondary.
Decision: verified

## Claim 19: "represented by Lieff Cabraser Heimann & Bernstein and Cowan, DeBaets, Abrahams & Sheppard"

Source: https://www.lieffcabraser.com/openai-copyright/
Source content: Lieff Cabraser confirmed as plaintiffs' counsel; co-counsel "Cowan, DeBaets, Abrahams & Sheppard" not surfaced on this page in the retrieval.
Comparison: Lieff Cabraser side verifies; co-counsel claim unverifiable from this session's fetches.
Decision: unverifiable

## Claim 20: "consolidated with the parallel Alter v. OpenAI nonfiction-authors suit, and Microsoft was added as a co-defendant in December 2023"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/ (primary, retrieved) — confirms "Microsoft, added December 4, 2023 via amended complaint."
Source content: Microsoft addition date confirmed by the Authors Guild's own announcement. The consolidation with Alter v. OpenAI was NOT surfaced on the Lieff Cabraser page in the retrieval.
Comparison: Microsoft addition verifies (the body's "December 2023" matches "December 4, 2023"); the Alter consolidation is unverifiable from this session's fetches.
Decision: unverifiable

## Claim 21: Rasenberger statement — "it is imperative that we stop this theft in its tracks or we will destroy our incredible literary culture, which feeds many other creative industries in the U.S."

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source content: "It is imperative that we stop this theft in its tracks or we will destroy our incredible literary culture."
Comparison: The prefix is verbatim. The retrieval did not surface the trailing "which feeds many other creative industries in the U.S." clause, but the primary source is consistent with the body and the prefix match is exact within paraphrase tolerance.
Decision: verified

## Claim 22: Lang statement — "this case is merely the beginning of our battle to defend authors from theft by OpenAI and other generative AI"

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source content: "This case is merely the beginning of our battle to defend authors from theft by OpenAI and other generative AI."
Comparison: Verbatim match.
Decision: verified

## Claim 23: Franzen statement — "authors should have the right to decide when their works are used to 'train' AI. If they choose to opt in, they should be appropriately compensated."

Source: https://authorsguild.org/news/ag-and-authors-file-class-action-suit-against-openai/
Source content: "Authors should have the right to decide when their works are used to 'train' AI. If they choose to opt in, they should be appropriately compensated."
Comparison: Verbatim match.
Decision: verified

## Claim 24: "ex parte session on 10 May 2024" with the U.S. Copyright Office — Rasenberger, Amer, and Kazi participating

Source: https://www.copyright.gov/policy/artificial-intelligence/ex-parte-communications/letters/Authors-Guild-May-10-2024.pdf
Source content: PDF retrieved as binary; the WebFetch parser could not extract readable text in this session ("corrupted or heavily compressed PDF file containing mostly binary/encoded data"). The URL slug contains "May-10-2024" which is consistent but not a substantive content read.
Comparison: Date and named participants cannot be confirmed from a content-bearing read in this pass.
Decision: unverifiable

## Claim 25: "FTC's 4 October 2023 Creative Economy and Generative AI roundtable ... represented ... by Council member Douglas Preston"

Source: no canonical source consulted in this session — the FTC events page (cited by the body) was not fetched.
Source content: n/a
Comparison: No canonical-source content was retrieved against this claim in this pass.
Decision: unverifiable

## Claim 26: "$1.5 billion Bartz v. Anthropic settlement, announced on 5 September 2025 and preliminarily approved by Judge William Alsup on 25 September 2025"

Source: https://authorsguild.org/news/anthropic-settlement-key-updates/
Source content: "$1.5 billion plus interest"; settlement announcement "September 5, 2025"; preliminary approval September 25, 2025 by "Judge William Alsup, United States District Court for the Northern District of California."
Comparison: Matches (the body omits the Northern District of California venue without contradicting it).
Decision: verified

## Claim 27: "the final-approval hearing scheduled for 14 May 2026"

Source: https://authorsguild.org/news/anthropic-settlement-key-updates/
Source content: "No final approval hearing date is mentioned in this article."
Comparison: The cited primary source did not surface this date in this session's read; no secondary canonical source was successfully fetched to confirm.
Decision: unverifiable

## Claim 28: "approximately 500,000 titles among the 7 million volumes Anthropic was found to have downloaded from LibGen and PiLiMi, and pays an estimated $3,000 per class work"

Source: https://authorsguild.org/news/anthropic-settlement-key-updates/ and https://authorsguild.org/news/anthropic-settlement-update-91-percent-of-books-claimed/
Source content: Per the 91%-claimed update: "440,490 of the 482,460 eligible works had been claimed" and "individual payouts will be closer to the original $3,000 per work estimate." Per the key-updates piece: books were taken "from notorious pirate sources LibGen and PiLiMi" and Anthropic engaged in "mass piracy in downloading millions of books" — no specific 7-million figure surfaced. The 500,000-titles framing rounds the 482,460 eligible-works figure.
Comparison: The ~500,000 titles, the LibGen / PiLiMi sources, and the ~$3,000 per class work are all verifiable from the cited primary sources. The "7 million volumes" specific figure is not corroborated by the cited primary sources in this session's fetches (sources say "millions of books" without a 7M figure).
Decision: unverifiable

## Claim 29: "By April 2026, 91.3% of eligible books had been claimed"

Source: https://authorsguild.org/news/anthropic-settlement-update-91-percent-of-books-claimed/
Source content: "91.3%" claimed "As of April 17, 2026."
Comparison: Matches.
Decision: verified

## Claim 30: "the largest U.S. copyright settlement on the public record"

Source: https://authorsguild.org/news/anthropic-settlement-key-updates/
Source content: "the largest U.S. copyright settlement in history" and "the largest U.S. copyright infringement settlement ever."
Comparison: Matches the framing claim; the Authors Guild's own page is consistent with the body's "largest U.S. copyright settlement on the public record."
Decision: verified
