---
entity_id: event-te-hiku-media-kaitiakitanga-license-release-2018-10-02
entity_hash: 3f9a5265e02d8f9908d63366e7ec5887d921c151
audit_date: 2026-06-08
pass: 1
status: discrepancy
claims_total: 29
claims_verified: 19
claims_discrepancy: 4
claims_unverifiable: 6
sources_consulted:
  - https://github.com/TeHikuMedia/Kaitiakitanga-License
  - https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/commits
  - https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/LICENSE.md
  - https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/README.md
  - https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/papareo_api.md
  - https://tehiku.nz/te-hiku-tv/haukainga/8037/indigenous-data-theft
  - https://www.1news.co.nz/2018/08/27/free-te-reo-language-software-developer-upset-about-multinationals-forays/
  - https://papareo.nz/
  - https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
  - https://www.nzherald.co.nz/northern-advocate/news/te-hiku-media-ceo-peter-lucas-jones-on-time-magazines-time100-ai-list/JDG3MXQY5FGTJMBGS7PB4TBZ3Q/
  - https://tehiku.nz/te-hiku-tech/te-hiku-dev-korero/25141/data-sovereignty-and-the-kaitiakitanga-license
---

## Claim 1: "On 2 October 2018, Te Hiku Media ... published the Kaitiakitanga License to a public GitHub repository"

Source: https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/commits
Source content: Earliest commit `17787df8 Initial commit` dated `2018-10-02T12:51:02Z`; follow-on `43a0fe18 Create LICENSE.txt` `2018-10-02T13:06:09Z`; `a620ffde Rename LICENSE.txt to LICENSE.md` `2018-10-02T13:06:46Z`.
Comparison: The initial publication date on GitHub matches 2 October 2018 (UTC).
Decision: verified

## Claim 2: Te Hiku Media is "the Kaitaia-based Māori iwi broadcaster and indigenous-AI organisation"

Source: https://www.nzherald.co.nz/northern-advocate/news/te-hiku-media-ceo-peter-lucas-jones-on-time-magazines-time100-ai-list/JDG3MXQY5FGTJMBGS7PB4TBZ3Q/ ; https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
Source content: NZ Herald: "Peter-Lucas Jones, CEO of Te Hiku Media in Kaitāia, New Zealand". MIT Technology Review: "Te Hiku Media, a Māori nonprofit radio station in rural New Zealand".
Comparison: Both location (Kaitāia) and Māori broadcaster character confirmed by ≥2 canonical sources.
Decision: verified

## Claim 3: "the 2017-2018 Kōrero Māori project — a crowdsourcing campaign"

Source: no canonical source found in this pass
Source content: Papa Reo describes Kōrero Māori as a Te Hiku Media crowdsourcing initiative but does not give an explicit 2017-2018 date range; the linked scoop.co.nz funding announcement was not fetched in this pass.
Comparison: The campaign existence is verified but the specific 2017-2018 date range is not confirmed in the sources consulted this pass.
Decision: unverifiable

## Claim 4: scalar:sources[].note — "funded under New Zealand's Ka Hao: Māori Digital Technology Fund"

Source: no canonical source found in this pass
Source content: The cited scoop.co.nz URL was not fetched in this pass; no other source consulted names the Ka Hao fund.
Comparison: Plausible (Ka Hao is a known NZ Māori digital tech fund) but unverified against a canonical source in this pass.
Decision: unverifiable

## Claim 5: "in May 2018, Lionbridge ... launched a Facebook recruitment campaign offering Māori speakers $45 USD per hour for te reo audio recordings"

Source: https://tehiku.nz/te-hiku-tv/haukainga/8037/indigenous-data-theft ; https://www.1news.co.nz/2018/08/27/free-te-reo-language-software-developer-upset-about-multinationals-forays/
Source content: tehiku.nz: "In May 2018, Lionbridge posted on Facebook seeking Māori speakers for language research projects at $45 USD per hour, aiming to teach Māori to robots through voice recognition technology." 1News: same recruitment campaign cited.
Comparison: Date (May 2018), platform (Facebook), rate ($45 USD/hour), and purpose all match.
Decision: verified

## Claim 6: "Lionbridge ... an American translation-services company"

Source: https://www.1news.co.nz/2018/08/27/free-te-reo-language-software-developer-upset-about-multinationals-forays/ ; https://tehiku.nz/te-hiku-tv/haukainga/8037/indigenous-data-theft
Source content: 1News characterises the company as one of the "American corporates"; Te Hiku Media's own article frames Lionbridge as an American actor seeking to extract te reo for commercial speech-recognition.
Comparison: American origin and translation/language-services business confirmed by two canonical sources.
Decision: verified

## Claim 7: "Peter-Lucas Jones, then General Manager (later Chief Executive) of Te Hiku Media"

Source: https://www.1news.co.nz/2018/08/27/free-te-reo-language-software-developer-upset-about-multinationals-forays/ ; https://www.nzherald.co.nz/northern-advocate/news/te-hiku-media-ceo-peter-lucas-jones-on-time-magazines-time100-ai-list/JDG3MXQY5FGTJMBGS7PB4TBZ3Q/
Source content: 1News (Aug 2018): "Te Hiku Media general manager". NZ Herald (TIME100 AI 2024 coverage): "Peter-Lucas Jones, CEO of Te Hiku Media".
Comparison: Both the earlier General Manager role and the later CEO role are confirmed in canonical sources.
Decision: verified

## Claim 8: Peter-Lucas Jones quote "translate apps of any description into the native languages of indigenous people, and sell that back"

Source: https://www.1news.co.nz/2018/08/27/free-te-reo-language-software-developer-upset-about-multinationals-forays/
Source content: "American corporates who are looking at ways to translate apps of any description into the native languages of indigenous people, and sell that back".
Comparison: Body quote is exact substring of source quote.
Decision: verified

## Claim 9: Peter-Lucas Jones quote "the last frontier of colonisation" (linked to tehiku.nz Indigenous Data Theft article)

Source: https://tehiku.nz/te-hiku-tv/haukainga/8037/indigenous-data-theft
Source content: "Digital misappropriation of indigenous language and cultural data is the last frontier of colonisation".
Comparison: Body's three-word quote matches the closing phrase of the source attribution.
Decision: verified

## Claim 10: Keoni Mahelona quote "the icing on the cake of colonisation" — linked to https://tehiku.nz/te-hiku-tv/haukainga/8037/indigenous-data-theft

Source: https://tehiku.nz/te-hiku-tv/haukainga/8037/indigenous-data-theft (cited) ; https://www.1news.co.nz/2018/08/27/free-te-reo-language-software-developer-upset-about-multinationals-forays/ (where the quote actually appears)
Source content: 1News carries Mahelona's statement "It's just the icing on the cake of colonisation"; the tehiku.nz Indigenous Data Theft article (the citation target in the body) does not surface this Mahelona quote in the content read.
Comparison: The quote itself is real and attributed correctly to Mahelona, but the body's inline citation points at the wrong source within the entity's own `sources:` list. The 1News URL (already in `sources:`) is the canonical carrier of this quote.
Decision: discrepancy

## Claim 11: "Keoni Mahelona, Te Hiku Media's Native Hawaiian Chief Technology Officer"

Source: https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
Source content: MIT Technology Review describes Mahelona as "co-leader of Te Hiku Media" but does not, in the content read this pass, confirm the specific "Chief Technology Officer" title or "Native Hawaiian" heritage attribution. The tehiku.nz Indigenous Data Theft article (the corpus's other natural source for this) was not retrievable in detail this pass.
Comparison: Mahelona's leadership at Te Hiku Media is established; the specific CTO title and Native Hawaiian heritage are not confirmed in the sources consulted this pass and Wikipedia-alone is insufficient (living-person specific beyond public role, per source rule).
Decision: unverifiable

## Claim 12: "Te Hiku Media published its 'Indigenous Data Theft' article on 10 August 2018"

Source: https://tehiku.nz/te-hiku-tv/haukainga/8037/indigenous-data-theft
Source content: Article publication date "Aug. 10, 2018, 6:59 p.m."
Comparison: Body's 10 August 2018 date matches the source.
Decision: verified

## Claim 13: "1News carried the controversy on 27 August 2018"

Source: https://www.1news.co.nz/2018/08/27/free-te-reo-language-software-developer-upset-about-multinationals-forays/
Source content: Article URL slug and publication date confirm 27 August 2018.
Comparison: Matches.
Decision: verified

## Claim 14: "the Kaitiakitanga License followed six weeks later, on 2 October 2018"

Source: https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/commits ; https://www.1news.co.nz/2018/08/27/free-te-reo-language-software-developer-upset-about-multinationals-forays/
Source content: 1News date 27 August 2018; GitHub initial commit 2018-10-02. Interval = 36 days ≈ 5 weeks 1 day.
Comparison: The "six weeks" framing rounds upward by ~5 days; within paraphrase tolerance for a rough temporal interval.
Decision: verified

## Claim 15: License preamble framing "by simply open sourcing our data and knowledge, we further allow ourselves to be colonised digitally in the modern world"

Source: https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/LICENSE.md
Source content: "By simply open sourcing our data and knowledge, we further allow ourselves to be colonised digitally in the modern world."
Comparison: Verbatim match.
Decision: verified

## Claim 16: "The word *kaitiakitanga* has no direct English translation but carries the meaning of guardian, protector, and custodian"

Source: https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/LICENSE.md
Source content: "Kaitiaki is a Māori word without specific English translation, but its meaning is similar to the words guardian, protector, and custodian."
Comparison: The license preamble defines the related but lexically distinct word *kaitiaki* (the role: guardian/custodian), not *kaitiakitanga* (the practice: guardianship). The body conflates the two words. The source-mapping is semantically adjacent but not the same word the body asserts the source defines.
Decision: discrepancy

## Claim 17: "Its four core terms are: users must contact Te Hiku Media and obtain permission ...; commercial use without explicit authorisation is prohibited; code derived from the repository remains bound by the same licence; and works utilising the repository's content are subject to the same terms downstream."

Source: https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/LICENSE.md
Source content: "1. You must contact us and seek permission to access, use, contribute towards, or modify code in this repository; 2. You may not use code in this repository or any derivations for commercial purposes unless we explicitly grant you the right to do so; 3. All works derived from code in this repository are bound by the Kaitiakitanga License; 4. All works that make use of any code in this repository are bound by the Kaitiakitanga License."
Comparison: Four terms in body match four terms in the LICENSE.md in count, ordering, and content within paraphrase tolerance.
Decision: verified

## Claim 18: "data is not owned but is cared for under the principle of kaitiakitanga and any benefit derived from data flows to the source of the data"

Source: https://papareo.nz/
Source content: "data is not owned but is cared for under the principle of kaitiakitanga and any benefit derived from data flows to the source of the data".
Comparison: Verbatim match.
Decision: verified

## Claim 19: "The preamble states that Te Hiku Media will always make time to help indigenous and other underrepresented groups, while noting the licence is unlikely to be applicable within a non-indigenous context"

Source: https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/LICENSE.md ; https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/README.md
Source content: The "always make time to help Indigenous and other underrepresented groups" sentence and the "It is unlikely that the Kaitiakitanga License can be applied within a non-Indigenous context" note both appear in `README.md`, not in the `LICENSE.md` "Preamble" section. The LICENSE preamble carries different content (the kaitiaki gloss, the open-source-colonisation framing, the "living license" sentence).
Comparison: Body misattributes README sentences to the License preamble. The substance of what is said is verified; the structural location is misnamed.
Decision: discrepancy

## Claim 20: "described at publication as a 'living license' intended to evolve"

Source: https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/LICENSE.md
Source content: "The Kaitiakitanga License is a work in progress. It's a living license. It will evolve as we see fit."
Comparison: "Living license" phrasing and the evolve-as-needed framing both confirmed in the LICENSE.md preamble (i.e. present at publication).
Decision: verified

## Claim 21: Peter-Lucas Jones quote "In the digital world, data is like land. If we do not have control, governance, and ongoing guardianship of our data as indigenous people, we will be landless in the digital world, too."

Source: https://www.nzherald.co.nz/northern-advocate/news/te-hiku-media-ceo-peter-lucas-jones-on-time-magazines-time100-ai-list/JDG3MXQY5FGTJMBGS7PB4TBZ3Q/
Source content: "In the digital world, data is like land. If we do not have control, governance, and ongoing guardianship of our data as indigenous people, we will be landless in the digital world, too."
Comparison: Verbatim match.
Decision: verified

## Claim 22: Keoni Mahelona quote "Data is the last frontier of colonization"

Source: https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
Source content: '"Data is the last frontier of colonization," according to Keoni Mahelona, co-leader of Te Hiku Media.'
Comparison: Verbatim quote; attribution to Mahelona confirmed.
Decision: verified

## Claim 23: "the licence has been adopted by a New Zealand government department and a social enterprise"

Source: https://tehiku.nz/te-hiku-tech/te-hiku-dev-korero/25141/data-sovereignty-and-the-kaitiakitanga-license
Source content: The fetched content of the cited blog post does not contain a statement about NZ government department or social enterprise adoption in the portion surfaced; the page redirects much of its substance to linked resources rather than rendering it inline.
Comparison: Cannot confirm the claim from the cited source's read in this pass. No other consulted source carries the adoption claim.
Decision: unverifiable

## Claim 24: "Five further Māori Data Sovereignty licences have since been developed incorporating Te Hiku Media's original framework"

Source: https://tehiku.nz/te-hiku-tech/te-hiku-dev-korero/25141/data-sovereignty-and-the-kaitiakitanga-license ; https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents
Source content: GitHub repository contains application-specific licence files `kaituhi.md`, `papareo_api.md`, `piki.md`, `piki_eula.md`, `rongo.md`, `wharekorero_app.md` — six derivative documents. The cited blog post does not enumerate "five further" in the content surfaced.
Comparison: The repository carries 5–6 derivative files (depending on whether `piki.md` and `piki_eula.md` count as one application or two). The "five further" specific count is not explicitly verified against the cited source, though it is plausibly consistent with the file structure. Conservatively unverifiable for the exact count.
Decision: unverifiable

## Claim 25: "Te Hiku Media has been invited internationally to speak on the licence"

Source: https://tehiku.nz/te-hiku-tech/te-hiku-dev-korero/25141/data-sovereignty-and-the-kaitiakitanga-license
Source content: The blog post lists past international presentations (Creative Commons Global Summit 2023, UN's AI for Good, PAI Policy Forum UK 2023) but does not phrase them as "invited internationally to speak on the licence" in the content surfaced.
Comparison: Body claim is broadly consistent with the listed presentations but the exact framing was not confirmable in the cited source's content as read this pass.
Decision: unverifiable

## Claim 26: "more than 2,500 contributors provided over 300 hours of labelled te reo Māori speech"

Source: https://papareo.nz/ ; https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
Source content: papareo.nz: "~2,500 contributors", "~300 hours of labeled te reo Māori speech". MIT Tech Review: "Assembled 310 hours of speech data from ~2,500 community contributors in 10 days".
Comparison: Both figures (2,500+ contributors, 300+ hours) confirmed by two canonical sources within rounding.
Decision: verified

## Claim 27: "It also explicitly prohibits use of Te Hiku Media's tools for surveillance, discrimination, or tracking"

Source: https://api.github.com/repos/TeHikuMedia/Kaitiakitanga-License/contents/papareo_api.md
Source content: papareo_api.md prohibits "Surveillance / Tracking / Discrimination" as restricted uses.
Comparison: The Papa Reo API licence (a Kaitiakitanga-License-family document under the same repository) explicitly carries the prohibition. Body's "It also explicitly prohibits..." refers to the present-day licence framework, which includes the application-specific Papa Reo licence; the claim is supported within that context.
Decision: verified

## Claim 28: "Peter-Lucas Jones ... was named to TIME magazine's TIME100 AI 2024 list"

Source: https://www.nzherald.co.nz/northern-advocate/news/te-hiku-media-ceo-peter-lucas-jones-on-time-magazines-time100-ai-list/JDG3MXQY5FGTJMBGS7PB4TBZ3Q/
Source content: "Peter-Lucas Jones ... earned a spot on TIME Magazine's 2024 TIME100 AI list".
Comparison: Match.
Decision: verified

## Claim 29: scalar:sources[].note (MIT Technology Review entry) — "MIT Technology Review feature by Sandeep Ravindran (22 April 2022)"

Source: https://www.technologyreview.com/2022/04/22/1050394/artificial-intelligence-for-the-people/
Source content: Article byline: "Karen Hao, April 22, 2022".
Comparison: Date (22 April 2022) correct; author attribution "Sandeep Ravindran" does not match the actual byline "Karen Hao".
Decision: discrepancy
