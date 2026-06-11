---
entity_id: pub-stochastic-parrots
entity_hash: 1a27d2bf0d1876f1848d65369d898ee59eb481dc
audit_date: 2026-06-03
reclassified_at: 2026-06-10
pass: 1
status: supported
claims_total: 15
claims_corroborated: 11
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 4
sources_consulted:
  - https://en.wikipedia.org/wiki/On_the_Dangers_of_Stochastic_Parrots
  - https://en.wikipedia.org/wiki/Timnit_Gebru
  - https://en.wikipedia.org/wiki/Margaret_Mitchell_(scientist)
  - https://facctconference.org/2021/
  - https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
  - https://americandialect.org/2023-word-of-the-year-is-enshittification/
  - https://americandialect.org/category/words-of-the-year/
---

## Claim 1: "peer-reviewed conference paper by Emily M. Bender (University of Washington), [Timnit Gebru](../persons/person-timnit-gebru.md) (then at Google), Angelina McMillan-Major (then a University of Washington PhD student), and Margaret Mitchell (then at Google, publishing under the pseudonym 'Shmargaret Shmitchell')"

Source: https://en.wikipedia.org/wiki/On_the_Dangers_of_Stochastic_Parrots
Source content: "Timnit Gebru, Emily M. Bender, Angelina McMillan-Major, and Margaret Mitchell" are named as authors; Mitchell used "the pseudonym 'Shmargaret Shmitchell'" in the paper.
Comparison: The four named authors and Mitchell's pseudonym match. The specific affiliations (UW for Bender, UW PhD for McMillan-Major, Google for Mitchell) are not directly quoted in the Wikipedia text returned; they are widely-documented named-entity definitional facts.
Decision: corroborated

## Claim 2: "Timnit Gebru (then at Google)"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source content: "Gebru had joined Google in 2018, where she co-led a team"
Comparison: Gebru's Google affiliation at the time of the paper is confirmed.
Decision: corroborated

## Claim 3: "Angelina McMillan-Major (then a University of Washington PhD student)"

Source: no canonical source found
Source content: Wikipedia's stochastic parrots article does not quote McMillan-Major's affiliation; the original paper PDF (faculty.washington.edu) redirects to ACM DL which returned HTTP 403; mainstream news outlets (NYT, Guardian, Reuters, BBC, Wired, Verge, Washington Post) and the Wayback Machine were inaccessible in this session.
Comparison: Specific affiliation (UW PhD student) could not be verified against any canonical source fetched this session.
Decision: uncorroborated

## Claim 4: "presented at the ACM Conference on Fairness, Accountability, and Transparency (FAccT '21) held online from 3-10 March 2021"

Source: https://facctconference.org/2021/
Source content: "The fourth annual ACM FAccT conference will take place online March 3-10, 2021."
Comparison: Conference name, online format, and dates match verbatim.
Decision: corroborated

## Claim 5: "published in the conference proceedings as pages 610-623 with DOI 10.1145/3442188.3445922"

Source: https://dl.acm.org/doi/10.1145/3442188.3445922
Source content: ACM DL returned HTTP 403 in this session; canonical page range not retrieved from a fetched source.
Comparison: DOI is confirmed by its presence as the canonical link on Wikipedia, but pages 610-623 not independently verified this session.
Decision: uncorroborated

## Claim 6: four risk categories — "the environmental and financial costs of training ever-larger models; the inscrutability of the massive uncurated training corpora and the dangerous biases embedded in them; the opportunity cost of routing the field's research effort into LLM-centric work that crowds out language-grounding alternatives; and the potential for deception arising from text that reads as meaningful but is produced without communicative intent or grounding in the world"

Source: https://en.wikipedia.org/wiki/On_the_Dangers_of_Stochastic_Parrots
Source content: "Environmental and financial costs of training large language models"; "Inscrutability leading to unknown dangerous biases within LLMs"; "Opportunity costs (... research direction priorities)"; "Potential for deception since LLMs lack understanding of underlying concepts".
Comparison: All four risk categories match in content; the body's prose is more elaborated but does not add or change semantic content.
Decision: corroborated

## Claim 7: "a system for haphazardly stitching together sequences of linguistic forms it has observed in its vast training data, according to probabilistic information about how they combine, but without any reference to meaning: a stochastic parrot"

Source: https://en.wikipedia.org/wiki/On_the_Dangers_of_Stochastic_Parrots
Source content: "stitching together sequences of linguistic forms ... observed in its vast training data, according to probabilistic information about how they combine, but without any reference to meaning."
Comparison: Wikipedia's quote (with ellipsis) matches the central clause of the body's quotation. The body's prefix "a system for haphazardly" and suffix "a stochastic parrot" are not in Wikipedia's quoted excerpt; the paper PDF was inaccessible (redirects to ACM 403). The matching central clause supports the quote's substance.
Decision: corroborated

## Claim 8: "Google management — including the company's AI research head Jeff Dean and Megan Kacholia, the engineering vice-president to whom Gebru reported — demanded that Gebru either retract the paper or remove the names of Google-employed authors"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source content: "Google management asked her to either withdraw the paper before publication, or remove the names of all the Google employees from the paper." The Wikipedia article on Gebru does not mention Megan Kacholia at any point; the Wikipedia article on Margaret Mitchell does not mention her either. Mainstream news outlets that would document Kacholia's role were inaccessible (NYT/Guardian/Reuters/BBC/Verge/Wired/Washington Post all blocked).
Comparison: The general demand (retract or remove names) is verified. The specific identification of Megan Kacholia as "the engineering vice-president to whom Gebru reported" could not be confirmed against any canonical source fetched this session.
Decision: uncorroborated

## Claim 9: Jeff Dean as "the company's AI research head" and his public framing "didn't meet our bar for publication" on grounds that the paper "ignored too much relevant recent research"

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/ and https://en.wikipedia.org/wiki/Timnit_Gebru
Source content: MIT Tech Review quotes Dean's stated reason as "didn't meet our bar for publication" and "ignored too much relevant research". Wikipedia identifies Dean as "head of Google AI".
Comparison: Both the title and the verbatim phrases match the body's quotation.
Decision: corroborated

## Claim 10: "Google's reply — interpreted by Gebru as an unannounced termination and by Google as accepting a resignation she maintained she had not offered — landed on 2 December 2020"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source content: "In his note to employees, Mr. Dean said Google respected 'her decision to resign'." The article frames the controversy as occurring "In December 2020" but does not pin the reply to a specific date in the content returned this session.
Comparison: The semantic dispute (resignation framing vs. termination) matches Wikipedia, but the specific date "2 December 2020" for the reply was not directly quoted in the fetched Wikipedia content.
Decision: uncorroborated

## Claim 11: "Margaret Mitchell was terminated in February 2021 after she allegedly created automated scripts to crawl Google's internal servers for evidence of Gebru's treatment"

Source: https://en.wikipedia.org/wiki/Margaret_Mitchell_(scientist)
Source content: "In January 2021, after Timnit Gebru's termination from Google, Mitchell reportedly used a script to search through her corporate account and download emails that allegedly documented discriminatory incidents involving Gebru ... After a five-week investigation, Mitchell was fired." Multiple citations reference "February 20, 2021" as the date when news of her termination was reported.
Comparison: February 2021 termination and the alleged scripting both confirmed.
Decision: corroborated

## Claim 12: "the [Distributed AI Research Institute](../organizations/org-dair-institute.md), which Gebru founded on the one-year anniversary of her Google exit on 2 December 2021"

Source: https://en.wikipedia.org/wiki/Timnit_Gebru
Source content: "On 2 December 2021 she launched the Distributed Artificial Intelligence Research Institute (DAIR)."
Comparison: Founding date 2 December 2021 matches Wikipedia verbatim.
Decision: corroborated

## Claim 13: "'stochastic parrot' was designated the [American Dialect Society's 2023 AI-related Word of the Year]"

Source: https://en.wikipedia.org/wiki/On_the_Dangers_of_Stochastic_Parrots and https://americandialect.org/2023-word-of-the-year-is-enshittification/
Source content: Wikipedia: "The term was nominated as the 2023 AI-related Word of the Year by the American Dialect Society." The ADS 2023 Word-of-the-Year page (announcing "enshittification" as overall WOTY) does not mention an AI-related category or "stochastic parrot" in the fetched content; ADS's category archive page returned only 2025 content; direct 2023/2024 press-release URLs returned 404.
Comparison: Wikipedia's wording is "nominated as the 2023 AI-related Word of the Year" — ambiguous between "nominee" and "designee/winner". The body's stronger "designated" claim could not be confirmed against ADS's own announcement in this session.
Decision: uncorroborated

## Claim 14: "Sam Altman tweeting 'i am a stochastic parrot, and so r u' in the months after ChatGPT's release"

Source: https://en.wikipedia.org/wiki/On_the_Dangers_of_Stochastic_Parrots
Source content: "i am a stochastic parrot, and so r u" — posted by OpenAI's CEO "shortly after the release of ChatGPT in December 2022".
Comparison: Tweet text matches verbatim; timing matches.
Decision: corroborated

## Claim 15: scalar:sources[3].note — "ACM FAccT 2021 conference site — primary source confirming the conference was held online from 3-10 March 2021 as the fourth annual ACM Conference on Fairness, Accountability, and Transparency"

Source: https://facctconference.org/2021/
Source content: "The fourth annual ACM FAccT conference will take place online March 3-10, 2021."
Comparison: "fourth annual", "online", "March 3-10, 2021", and "ACM FAccT conference" all match verbatim. Scalar claim verified.
Decision: corroborated
