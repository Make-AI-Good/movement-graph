---
entity_id: event-timnit-gebru-firing-google-2020-12-02
entity_hash: fa671a1d43fb0b6f9a28ca24429ca431c6fd7699
audit_date: 2026-08-31
pass: 1
status: corrections-pending
claims_total: 27
claims_corroborated: 12
claims_primary_sourced: 4
claims_single_source: 2
claims_uncorroborated: 7
open_corrections: 2
sources_consulted:
  - https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
  - https://en.wikipedia.org/wiki/Timnit_Gebru
  - https://techcrunch.com/2021/02/19/google-fires-top-ai-ethics-researcher-margaret-mitchell/
  - https://www.washingtonpost.com/technology/2021/12/02/timnit-gebru-dair/
  - https://dair-institute.org/press-release/
  - https://techcrunch.com/2021/12/02/google-timnit-gebru-ai-research-dair/
  - https://www.engadget.com/alex-hanna-dylan-baker-dair-233014682.html
  - https://en.wikipedia.org/wiki/Samy_Bengio
  - https://en.wikipedia.org/wiki/Stochastic_parrot
  - https://www.bloomberg.com/news/articles/2021-04-06/google-ai-research-manager-samy-bengio-resigns-in-email-to-staff
  - https://www.cnbc.com/2021/04/06/googles-samy-bengio-is-leaving-amid-fallout-from-ai-researcher-firing.html
  - https://www.bloomberg.com/news/articles/2022-02-02/google-loses-two-ethical-ai-staffers-to-timnit-gebru-s-institute
  - https://www.bloomberg.com/news/articles/2021-08-24/fired-at-google-after-critical-work-ai-researcher-mitchell-to-join-hugging-face
  - https://www.cnbc.com/2018/04/05/google-employees-protest-pentagon-partnership-to-ceo-sundar-pichai.html
  - https://dair-institute.org/team/dylan-baker/
  - https://techcrunch.com/2020/12/03/googles-co-lead-of-ethical-ai-team-says-she-was-fired-for-sending-an-email/
---

## Claim 1: frontmatter `date: 2020-12-02` + body "On 2 December 2020, Google cut off Timnit Gebru's corporate email access — an action Google described as accepting her resignation and Gebru described as an unannounced firing"

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/ ; https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: mainstream
Source content: MIT TR: "She was cut off from her corporate email account before her return" (from vacation). Wikipedia: Google terminated employment on December 2, 2020, and "declared that they accepted her resignation"; "Gebru has maintained that she was fired" and "only threatened to" resign.
Comparison: Date, email-cutoff mechanism, and both sides' framing match two independent canonical sources.
Decision: corroborated

## Claim 2: frontmatter `location: Mountain View, CA`

Source: no canonical source found
Source tier: none
Source content: No fetched source places the event at a physical location; MIT TR notes Gebru was cut off "before her return" from vacation.
Comparison: Scalar path `location`. Mountain View is Google's headquarters — an HQ-attribution convention for a corporate action, not sourced as the place anything physically occurred. Not an error finding; the audit reaches its limit here.
Decision: uncorroborated

## Claim 3: edges — `participating_people: [person-timnit-gebru]`, `related_events: [event-openai-employees-safety-letter-2024-06-04]`, and body cross-references to person-joy-buolamwini, pub-gender-shades, pub-stochastic-parrots, org-dair-institute

Source: local repository (`product/entities/` file check)
Source tier: primary
Source content: All six referenced entity files exist; each names the entity the edge intends (Gebru person entry; OpenAI employees safety letter 2024-06-04; Buolamwini; Gender Shades; Stochastic Parrots; DAIR).
Comparison: Mechanical edge check — every cross-reference resolves to the correct entity. The corpus's own files are the definitive record of what an edge points to.
Decision: primary-sourced

## Claim 4: "Gebru had joined Google in 2018 as co-lead, alongside Margaret Mitchell, of the Ethical AI team"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru ; https://techcrunch.com/2021/02/19/google-fires-top-ai-ethics-researcher-margaret-mitchell/
Source tier: mainstream
Source content: Wikipedia: Gebru "joined Google in 2018, where she co-led a team on the ethics of artificial intelligence with Margaret Mitchell." TechCrunch: Mitchell "was the founder and former co-lead of Google's Ethical AI team, which she built alongside Dr. Timnit Gebru."
Comparison: Join year and co-leadership with Mitchell match two canonical sources.
Decision: corroborated

## Claim 5: "credentials from the 2018 Gender Shades audit with Joy Buolamwini"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: tiebreaker
Source content: "While at Microsoft, Gebru co-authored a research paper called Gender Shades" with Joy Buolamwini; found "Black women were 35% less likely to be recognized than White men."
Comparison: Co-authorship and the 2018 work confirmed; named-publication definitional fact within the Wikipedia-alone claim class. One source in this session.
Decision: single-source

## Claim 6: Stochastic Parrots paper description and co-authors "Emily M. Bender (University of Washington), Angelina McMillan-Major, and Margaret Mitchell"

Source: https://en.wikipedia.org/wiki/Stochastic_parrot ; https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: Wikipedia: paper "On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜" authored by Gebru, Emily M. Bender, Angelina McMillan-Major, and Margaret Mitchell. MIT TR identifies Bender as coauthor. Search-confirmed (IEEE Spectrum, UW faculty page): Bender is a University of Washington computational-linguistics professor.
Comparison: Named co-authors and Bender's UW affiliation match. Nuance not asserted as error: MIT TR notes the internal draft had "six coauthors, four of whom are Google researchers" — the body's "all four names were on the Google-internal draft" is literally true of the four named authors, though the draft carried additional authors.
Decision: corroborated

## Claim 7: "Megan Kacholia, a Google engineering vice-president, sent Gebru an email demanding that she either withdraw the Stochastic Parrots paper … or remove the names of all Google-affiliated authors"

Source: https://en.wikipedia.org/wiki/Stochastic_parrot
Source tier: tiebreaker
Source content: Wikipedia (Stochastic parrot): Gebru "emailed Google Research vice president Megan Kacholia that if the company could not explain the request for retraction … she would plan to resign"; Wikipedia (Gebru): "Google management requested that Gebru either withdraw the paper or remove the names of all the authors employed by Google" — Kacholia not named in the Gebru article as fetched today.
Comparison: The demand itself (withdraw or remove Google names) is well confirmed; the specific attribution that *Kacholia sent the demand email* is not confirmed by any canonical source fetched this session (Kacholia's involvement as the VP in the dispute is, via the Stochastic-parrot article). Kacholia-as-sender circulates in non-canonical sources (Wikibooks, Platformer newsletter). Not an error finding — attribution unverifiable at this session's source reach.
Decision: uncorroborated

## Claim 8: "Gebru responded listing conditions under which she would consider either step — conditions Google declined to engage"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru ; https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: Wikipedia: she asked for "an account of who had reviewed the work and how, and established a more transparent review process" and "would work with Google on an employment end date" if unmet. MIT TR: "Gebru had conditions for staying, which Google was unwilling to meet."
Comparison: Conditions-and-refusal structure matches both sources.
Decision: corroborated

## Claim 9: "separately sent an email to the Google Brain Women and Allies internal listserv describing the institutional pressure"

Source: https://techcrunch.com/2020/12/03/googles-co-lead-of-ethical-ai-team-says-she-was-fired-for-sending-an-email/ ; https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: mainstream
Source content: Search-confirmed (TechCrunch, Fortune, Platformer): "Gebru sent an email to the Google Brain Women and Allies listserv in early December 2020" detailing her struggles as a Black leader doing ethics research. Wikipedia: "sent a second email to an email list for women who worked in Google Brain, accusing the company of 'silencing marginalized voices.'"
Comparison: Listserv name and the email's substance match mainstream coverage plus Wikipedia's unnamed-list account.
Decision: corroborated

## Claim 10: "Jeff Dean publicly characterised the decision as finding the paper had not met Google's publication bar and framed Google's action as accepting a resignation"

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/ ; https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: mainstream
Source content: MIT TR: Dean said the paper "didn't meet our bar for publication" and "ignored too much relevant research." Wikipedia: Google "declared that they accepted her resignation."
Comparison: Both halves of the claim match the two sources.
Decision: corroborated

## Claim 11: "over a thousand Google employees signed a letter demanding an explanation and institutional changes, joined by thousands of researchers across academia and industry"

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: "More than 1,400 Google staff members and 1,900 other supporters" signed a protest letter supporting Gebru.
Comparison: "Over a thousand" is consistent with 1,400+ (figures grew over subsequent days); external-supporter count consistent with "thousands." One canonical source consulted for the numbers this session.
Decision: single-source

## Claim 12: "Samy Bengio, … Gebru's manager, publicly stated he stood by her"

Source: https://en.wikipedia.org/wiki/Samy_Bengio ; https://www.bloomberg.com/news/articles/2021-04-06/google-ai-research-manager-samy-bengio-resigns-in-email-to-staff
Source tier: mainstream
Source content: Search-confirmed (Bloomberg/TechTarget/CNBC): "Ousted Ethical AI co-leads Timnit Gebru and Margaret Mitchell had reported to Bengio"; he "conveyed his support for Gebru on Facebook days after she left Google." Wikipedia: "Bengio said that he had been 'stunned' by what happened to Gebru."
Comparison: Manager relationship and public support match multiple canonical sources.
Decision: corroborated

## Claim 13: Samy Bengio described as "Google Brain co-founder"

Source: https://en.wikipedia.org/wiki/Samy_Bengio
Source tier: tiebreaker
Source content: Wikipedia describes him only as "a longtime scientist at Google" who "led a large group of researchers working in machine learning" — no co-founder statement. Contemporary coverage (Bloomberg/Reuters/CNBC) calls him a "research manager"/"AI scientist"; an AI Business headline calls him "Google Brain co-founder."
Comparison: Sources characterize his Google Brain status inconsistently (co-founder vs. longtime scientist/early member); no canonical source fetched confirms "co-founder." Canonicality conflict — no winner picked.
Decision: uncorroborated

## Claim 14: "he resigned from Google approximately eighteen months later"

Source: https://www.bloomberg.com/news/articles/2021-04-06/google-ai-research-manager-samy-bengio-resigns-in-email-to-staff ; https://www.cnbc.com/2021/04/06/googles-samy-bengio-is-leaving-amid-fallout-from-ai-researcher-firing.html
Source tier: mainstream
Source content: Bengio "announced his resignation on Tuesday, April 6, 2021 … his last day being April 28" (Bloomberg/CNBC/Reuters coverage, search-confirmed; Wikipedia's referenced source: "Google AI manager resigns following controversial firings of two top researchers," April 6, 2021).
Comparison: December 2, 2020 → April 2021 is approximately four months, not eighteen. Single correct replacement: "approximately eighteen months later" → "approximately four months later."
Decision: correction

## Claim 15: "The Stochastic Parrots paper was eventually published at the 2021 ACM FAccT conference — with Mitchell publishing under a pseudonym"

Source: https://en.wikipedia.org/wiki/Stochastic_parrot
Source tier: tiebreaker
Source content: The paper "was presented at the 2021 ACM Conference on Fairness, Accountability, and Transparency" (March 2021, ACM); Mitchell published "using the pseudonym 'Shmargaret Shmitchell.'"
Comparison: Venue, year, and pseudonym match; publication venue/date is a public-record fact within the Wikipedia-alone class, additionally consistent with the UW faculty-hosted paper copy surfaced in search.
Decision: corroborated

## Claim 16: "On 19 February 2021, Google terminated Margaret Mitchell … citing code-of-conduct and security-policy violations. Mitchell had used automated scripts to search Google's internal servers …; Mitchell stated publicly that her effort to document mistreatment and support Gebru's account was central"

Source: https://techcrunch.com/2021/02/19/google-fires-top-ai-ethics-researcher-margaret-mitchell/ ; https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: mainstream
Source content: TechCrunch: Google cited "multiple violations of our code of conduct, as well as of our security policies"; she "allegedly used automated scripts to locate examples of mistreatment directed at Dr. Timnit Gebru"; Mitchell: her actions aimed "to raise concerns to Google about race and gender inequity, and to speak up about Google's deeply problematic firing of Dr. Gebru." Wikipedia: terminated 19 February 2021 "after allegedly creating automated scripts to crawl Google's internal servers for evidence of Gebru's mistreatment."
Comparison: Date, stated grounds, script conduct, and Mitchell's response all match two canonical sources.
Decision: corroborated

## Claim 17: "She joined Hugging Face in August 2021"

Source: https://www.bloomberg.com/news/articles/2021-08-24/fired-at-google-after-critical-work-ai-researcher-mitchell-to-join-hugging-face
Source tier: mainstream
Source content: Bloomberg (Aug 24, 2021): Mitchell "joined artificial intelligence startup Hugging Face"; "Mitchell planned to start in October."
Comparison: The hire was announced in August 2021 but per the announcement her start was planned for October 2021. "Joined in August" is too loose to confirm as stated and has no single clean token replacement (announcement date vs. start date) — a paraphrastic edge, not an asserted error.
Decision: uncorroborated

## Claim 18: "On 2 December 2021 — exactly one year after her Google exit — Gebru announced the founding of the Distributed AI Research Institute (DAIR) with $3.7 million in initial funding"

Source: https://dair-institute.org/press-release/ ; https://techcrunch.com/2021/12/02/google-timnit-gebru-ai-research-dair/
Source tier: primary
Source content: DAIR press release: "Dec. 2, 2021 — Timnit Gebru announces the launch of the Distributed Artificial Intelligence Research institute (DAIR)." TechCrunch: "So far the institute has raised $3.7 million."
Comparison: Date (the anniversary of 2020-12-02) and funding amount match primary plus mainstream sources.
Decision: corroborated

## Claim 19: DAIR funding "from the Ford Foundation, MacArthur Foundation, Kapor Center, Open Society Foundation, and Rockefeller Foundation"

Source: https://techcrunch.com/2021/12/02/google-timnit-gebru-ai-research-dair/ ; https://dair-institute.org/press-release/
Source tier: primary
Source content: TechCrunch: "the institute has raised $3.7 million, from the Ford Foundation, the MacArthur Foundation, the Kapor Center and the Open Society Foundation." DAIR's own press release likewise names those four; "The Rockefeller Foundation is not mentioned."
Comparison: The entity's five-funder list (per the cited Washington Post piece, which 403s on fetch) conflicts with the four-funder list in both the primary press release and TechCrunch. Canonical sources conflict on Rockefeller's inclusion — no winner picked. Also applies to scalar `sources[3].note`.
Decision: uncorroborated

## Claim 20: "In February 2023, Alex Hanna and Dylan Baker … joined DAIR"

Source: https://www.engadget.com/alex-hanna-dylan-baker-dair-233014682.html ; https://www.bloomberg.com/news/articles/2022-02-02/google-loses-two-ethical-ai-staffers-to-timnit-gebru-s-institute
Source tier: mainstream
Source content: Engadget (Feb 2, 2022): "researcher Alex Hanna and software engineer Dylan Baker left the company to join Timnit Gebru's Distributed AI Research Institute"; Hanna: "Today's my last day at Google. Starting tomorrow I'm joining @timnitGebru at @DAIRInstitute." Bloomberg's dateline is 2022-02-02; MIT TR profiled Hanna at DAIR in October 2022.
Comparison: The joins occurred in February 2022, not February 2023. Single correct replacement: "February 2023" → "February 2022." (A stray "February 2023" circulates in low-tier aggregators — the likely origin of the error — but primary-adjacent and mainstream sources are unanimous on 2022.)
Decision: correction

## Claim 21: Hanna and Baker "both from Google's Ethical AI team"; Hanna joined as "Director of Research"

Source: https://www.engadget.com/alex-hanna-dylan-baker-dair-233014682.html ; https://www.bloomberg.com/news/articles/2022-02-02/google-loses-two-ethical-ai-staffers-to-timnit-gebru-s-institute
Source tier: mainstream
Source content: Engadget: both "were members of Google's Ethical AI research group"; Hanna: "I'm joining … as Director of Research." Bloomberg headline: "Two of Google's Ethical AI Staffers Leave to Join Ousted Colleague's Institute."
Comparison: Team provenance and Hanna's DAIR title match two canonical sources.
Decision: corroborated

## Claim 22: Baker joined DAIR as "Lead Research Engineer"

Source: https://dair-institute.org/team/dylan-baker/
Source tier: primary
Source content: DAIR's own team page (search-confirmed): "Dylan K. Baker is the lead research engineer at the Distributed AI Research (DAIR) Institute." At joining, Baker's own announcement said "as an engineer and researcher."
Comparison: The title matches DAIR's own site (one primary source); whether it was his title at joining vs. later is a nuance the sources don't settle, but the claim as a role attribution matches the entity's own record.
Decision: primary-sourced

## Claim 23: "The Maven employee petition (April 2018) established the model of collective employee action"

Source: https://www.cnbc.com/2018/04/05/google-employees-protest-pentagon-partnership-to-ceo-sundar-pichai.html
Source tier: mainstream
Source content: CNBC (Apr 5, 2018) and C4ISRNET (Apr 4, 2018): thousands of Google employees (reported 3,100–4,000) signed a letter to Sundar Pichai protesting Project Maven: "Google should not be in the business of war."
Comparison: The hard specific — the petition and its April 2018 date — matches multiple canonical sources; the "established the model" framing is interpretation, not audited.
Decision: corroborated

## Claim 24: scalar `sources[0].note` — MIT TR article "documents the retraction demand …, Jeff Dean's public statement …, and the employee petition response with over a thousand Google signatories"

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: primary
Source content: The article covers the paper rejection/retraction dispute, Dean's "didn't meet our bar for publication," and "more than 1,400 Google staff members and 1,900 other supporters" signing.
Comparison: Scalar path `sources[0].note`. For a claim about a document's contents the document itself is the primary evidence; the note accurately describes the article.
Decision: primary-sourced

## Claim 25: scalar `sources[1].note` — Wikipedia article covers "Megan Kacholia's role, Gebru's email to the Google Brain Women and Allies listserv, the disputed resignation framing, and Margaret Mitchell's 19 February 2021 termination"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source tier: tiebreaker
Source content: The article as fetched today covers the disputed resignation, the Mitchell 19 Feb 2021 termination, and an email "to an email list for women who worked in Google Brain" — but "Megan Kacholia is not mentioned anywhere in this Wikipedia article," and the listserv is not named "Google Brain Women and Allies."
Comparison: Scalar path `sources[1].note`. Two of the four content claims about the cited article no longer hold against its current text (the article may have changed since `last_checked: 2026-06-10`). Fixing the note requires prose judgment (trimming the Kacholia/listserv-name items), not a single token replacement.
Decision: uncorroborated

## Claim 26: scalar `sources[2].note` — TechCrunch as "primary source for Margaret Mitchell's termination date, Google's stated justification …, and Mitchell's public response"

Source: https://techcrunch.com/2021/02/19/google-fires-top-ai-ethics-researcher-margaret-mitchell/
Source tier: primary
Source content: The article carries the Feb 19, 2021 date, Google's "multiple violations of our code of conduct, as well as of our security policies," the scripts allegation, and Mitchell's quoted response.
Comparison: Scalar path `sources[2].note`. The note accurately describes the article's contents, verified directly against the fetched article.
Decision: primary-sourced

## Claim 27: scalar `sources[3].note` — Washington Post as "primary source for DAIR founding on the one-year anniversary; $3.7 million in initial funding from Ford Foundation, MacArthur Foundation, Kapor Center, Open Society Foundation, and Rockefeller Foundation"

Source: https://www.washingtonpost.com/technology/2021/12/02/timnit-gebru-dair/
Source tier: none
Source content: The URL returns HTTP 403 on direct fetch; its contents could not be examined. Fetched canonical sources (DAIR press release, TechCrunch) confirm the founding date and $3.7M but name four funders, without Rockefeller.
Comparison: Scalar path `sources[3].note`. The note's description of what the Post article contains is unverifiable (paywall), and its five-funder list conflicts with the fetched primary and mainstream sources (see Claim 19). Not an asserted error — the Post may indeed name Rockefeller.
Decision: uncorroborated
