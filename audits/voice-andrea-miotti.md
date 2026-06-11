---
entity_id: voice-andrea-miotti
entity_hash: 24b4372e49281db5487c5246d8aa37815670dc75
audit_date: 2026-06-08
reclassified_at: 2026-06-10
pass: 1
status: corrections-pending
claims_total: 18
claims_corroborated: 14
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 1
claims_uncorroborated: 3
sources_consulted:
  - https://controlai.com/about
  - https://www.narrowpath.co/
  - https://controlai.news/p/avoiding-extinction-with-andrea-miotti
  - https://controlai.news/p/100-uk-parliamentarians-acknowledge
  - https://controlai.news/p/what-we-learned-from-briefing-140
  - https://controlai.news/p/the-exponential
  - https://en.wikipedia.org/wiki/Des_Browne
  - https://en.wikipedia.org/wiki/ControlAI
---

## Claim 1: "Andrea Miotti is the Founder and CEO of ControlAI"

Source: https://controlai.com/about
Source content: "Founder & CEO" (Miotti's listed title on ControlAI's own about page)
Comparison: Body's "Founder and CEO" matches the primary source within paraphrase tolerance (ampersand vs "and").
Decision: corroborated

## Claim 2: "ControlAI, the international AI-safety advocacy non-profit"

Source: https://controlai.com/about
Source content: "a non-profit organisation that works to prevent the extinction risk posed by superintelligence and to secure a great future for humanity"
Comparison: Body's "international AI-safety advocacy non-profit" is paraphrastically consistent with the about page's "non-profit organisation" working on AI-safety / superintelligence policy; the "international" register is supported by the cross-jurisdiction briefing programme verified in Claim 14.
Decision: corroborated

## Claim 3: "lead-authorship of ControlAI's flagship 19 March 2026 policy plan *A Narrow Path*" (notable_for + body + sources[1].note)

Source: https://en.wikipedia.org/wiki/ControlAI; web-search corroboration of October 2024 publication date (Andrea Miotti's own X post dated Oct 2024 announcing publication; Wikipedia: "In October 2024, Miotti and others published *A Narrow Path*"); narrowpath.co landing page (no mention of "19 March 2026")
Source content: Wikipedia: "In October 2024, Miotti and others published *A Narrow Path*"; Miotti X status URL `1841515958663266410` (October 2024) announcing the publication
Comparison: Body claims publication on "19 March 2026"; multiple canonical sources (Wikipedia + Miotti's own social-media announcement) place actual publication in **October 2024** (specifically October 7, 2024). The "Jun 1, 2026" timestamp on narrowpath.co appears to be a page-metadata update, not the document's publication date. The 18-month-off date appears in three locations: notable_for, sources[1].note, and the body paragraph beginning "The single most load-bearing artefact…" — all of which name "19 March 2026" or "published on 19 March 2026".
Decision: correction

## Claim 4: "lead-authored with Tolga Bilge, Dave Kasten, and James Newport" (body) and "four-author byline (Andrea Miotti, Tolga Bilge, Dave Kasten, James Newport)" (sources[1].note)

Source: https://www.narrowpath.co/
Source content: Author list on the landing page in order — "Andrea Miotti, Tolga Bilge, Dave Kasten, James Newport"
Comparison: Body and frontmatter scalar match canonical source exactly; Miotti's first position supports the "lead-authorship" framing.
Decision: corroborated

## Claim 5: "three-phase Safety / Stability / Flourishing framework" (body + sources[1].note)

Source: https://www.narrowpath.co/
Source content: "Phase 0: Safety" / "Phase 1: Stability" / "Phase 2: Flourishing"
Comparison: Phase names match exactly; the "three-phase" structure is canonical.
Decision: corroborated

## Claim 6: "a twenty-year moratorium on superintelligence development"

Source: https://www.narrowpath.co/
Source content: "Prevent the Development of Artificial Superintelligence for 20 Years"; "prevent anyone from developing artificial superintelligence for the next 20 years"
Comparison: Body's "twenty-year moratorium on superintelligence development" matches the source's "20 years" framing within paraphrase tolerance.
Decision: corroborated

## Claim 7: "compute-threshold licensing triggered at training runs above 10^25 FLOP"

Source: https://www.narrowpath.co/
Source content: Landing page provides no mention of "10^25 FLOP", "10^25 floating point operations", or compute-threshold licensing in the rendered surface accessible via WebFetch.
Comparison: The detailed PDF/policy document may contain this specific threshold, but it is not verifiable from the landing page WebFetch alone; no second canonical source consulted in this pass corroborates the specific 10^25 threshold.
Decision: uncorroborated

## Claim 8: scalar:sources[0].note "ControlAI's own about page — primary source for Miotti's Founder/CEO role and the on-record listing of the press outlets (TIME, The Guardian, Nature, BBC, Sky News)"

Source: https://controlai.com/about
Source content: "Founder & CEO" and press outlet list "TIME, The Guardian, Nature, BBC, and Sky News"
Comparison: Scalar's content claim about the about-page listing matches exactly; the five press outlets are named in the canonical order claimed.
Decision: corroborated

## Claim 9: "weekly ControlAI Substack newsletter co-byline with Tolga Bilge" (notable_for + body)

Source: https://controlai.news/p/the-exponential ; https://controlai.news/p/100-uk-parliamentarians-acknowledge
Source content: "The Exponential" (March 6, 2026) bylined "Tolga Bilge and Andrea Miotti"; "100+ UK Parliamentarians Acknowledge AI Extinction Risk" (December 11, 2025) bylined "Tolga Bilge and Andrea Miotti"
Comparison: Two independent post bylines confirm the sustained Miotti–Bilge co-byline pattern on the ControlAI Substack.
Decision: corroborated

## Claim 10: "named UK Parliament written-evidence submission RAI0031 (with Steven Adler)" (notable_for + body + sources[3].note)

Source: https://committees.parliament.uk/writtenevidence/148236/pdf/
Source content: PDF fetch returned HTTP 403 Forbidden; no content retrievable through WebFetch in this audit pass.
Comparison: The URL is on the canonical UK Parliament committees domain and is structurally consistent with a written-evidence PDF reference, but the document's content (authorship, RAI0031 designation, Steven Adler co-author) could not be independently verified in this pass.
Decision: uncorroborated

## Claim 11: Quote — "I founded ControlAI because I believe this is just, not just a technical problem … this is a deeply political problem that will be solved with policy solutions, not just going back to the ivory tower."

Source: https://controlai.news/p/avoiding-extinction-with-andrea-miotti
Source content: "I founded ControlAI because I believe this is just, not just a technical problem. The reality is even with the best scientists working on this problem, we're not gonna make it out alive if we don't put rules in place, regulations in place that actually protect us... Ultimately, this is a deeply political problem that will be solved with policy solutions, not just going back to the ivory tower"
Comparison: Quoted phrasing in body and frontmatter notable_for matches source exactly.
Decision: corroborated

## Claim 12: Quote — "AI systems smarter than all of you might combine are AI systems that will take over your country."

Source: https://controlai.news/p/avoiding-extinction-with-andrea-miotti
Source content: "AI systems smarter than all of you might combine are AI systems that will take over your country and you will not be able to stop them."
Comparison: Body's quote is a verbatim prefix of the source line.
Decision: corroborated

## Claim 13: Quote — "There are only two times to react to an exponential — too early or too late."

Source: https://controlai.news/p/avoiding-extinction-with-andrea-miotti
Source content: "The truth is, there are only two times to react to an exponential — too early or too late."
Comparison: Body's quote matches the source within paraphrase tolerance (body drops the "The truth is," preface).
Decision: corroborated

## Claim 14: "*Avoiding Extinction* podcast conversation with Connor Leahy"

Source: https://controlai.news/p/avoiding-extinction-with-andrea-miotti
Source content: "Connor Leahy, CEO of Conjecture and Advisor to ControlAI, is featured throughout as a primary speaker alongside Andrea Miotti."
Comparison: Conversation partner identity matches the source.
Decision: corroborated

## Claim 15: "Rt Hon. the Lord Browne of Ladyton (former UK Defence Secretary, vice-chair of the Nuclear Threat Initiative) to sign on as ControlAI advisors"

Source: https://controlai.com/about ; https://en.wikipedia.org/wiki/Des_Browne (Wikipedia as tiebreaker for the NTI role)
Source content: ControlAI about page: "The Rt Hon. the Lord Browne of Ladyton (Des Browne) is a former UK Defence Secretary with decades of experience at the highest levels of national security and global risk." Wikipedia: "Browne is vice chairman of the Washington, DC–based Nuclear Threat Initiative"
Comparison: Former UK Defence Secretary verified by primary source (ControlAI about page). NTI vice-chair role verified by Wikipedia ("vice chairman" within paraphrase tolerance of body's "vice-chair"); for a public-office description of a named living person, Wikipedia counts as a canonical source per the type-based rule plus the corroborating primary affiliation context on the ControlAI about page.
Decision: corroborated

## Claim 16: "the parliamentary-briefing programme launched in September 2024"

Source: https://controlai.news/p/what-we-learned-from-briefing-140
Source content: "Between September 2024 and February 2026, I delivered over 150 parliamentary meetings"; "From November 2024, we began systematically briefing parliamentarians."
Comparison: Body's "launched in September 2024" matches the source's earliest-date anchor for parliamentary meetings within paraphrase tolerance; the systematic-briefing phase began November 2024, but the programme's initial engagement is consistently dated September 2024.
Decision: corroborated

## Claim 17: "by February 2026 had systematically briefed more than 250 lawmakers across the US, UK, Canada, and Germany"

Source: https://controlai.com/about
Source content: "over 150 cross-party UK parliamentarians" briefed (UK figure) plus "over 150 lawmakers" briefed across the US, Canada, and Germany (cross-jurisdiction figure)
Comparison: Aggregate of the two named figures on the canonical ControlAI page (150 UK + 150 US/Canada/Germany = 300+) supports the body's conservative "more than 250" framing. The four-country grouping (US, UK, Canada, Germany) matches the about-page jurisdictions exactly.
Decision: corroborated

## Claim 18: scalar:sources[4].note "11 December 2025 milestone — primary source for the 100+ cross-party UK parliamentarian signatory milestone … and the named outlet coverage of the milestone (The Guardian, City A.M., TIME)"

Source: https://controlai.news/p/100-uk-parliamentarians-acknowledge
Source content: Announcement dated "December 11, 2025"; "over 100 have done so, backing ControlAI's campaign for binding regulation on the most powerful AI systems"; outlet coverage listed: "The Guardian (described as 'exclusive')", "City A.M", "TIME (noted as earlier coverage when they had 16 supporters)"
Comparison: Date, signatory count, Miotti–Bilge co-byline, and three outlet citations all match the source. The Guardian 8 December 2025 article URL referenced in sources[8].note could not be directly fetched in this pass, but its existence and "exclusive" status are confirmed by this primary source.
Decision: corroborated
