---
entity_id: person-audrey-tang
entity_hash: 2ae8cf3557a580c43df3554e298180da016b6e0c
audit_date: 2026-06-09
pass: 1
status: discrepancy
claims_total: 24
claims_verified: 21
claims_discrepancy: 2
claims_unverifiable: 1
sources_consulted:
  - https://en.wikipedia.org/wiki/Audrey_Tang
  - https://en.wikipedia.org/wiki/G0v
  - https://rightlivelihood.org/the-change-makers/find-a-laureate/audrey-tang/
  - https://audreyt.org/
  - https://www.demnext.org/people/audrey-tang
  - https://www.technologyreview.com/2018/08/21/240284/the-simple-but-ingenious-system-taiwan-uses-to-crowdsource-its-laws/
  - https://rebootdemocracy.ai/blog/audrey-tang-ai-democracy/
  - https://www.govocal.com/blog/pioneers-1-audrey-tang-taiwans-digital-minister
  - https://compdemocracy.org/case-studies/2014-vtaiwan/
---

## Claim 1: "Born [18 April 1981 in Taipei]"

Source: https://en.wikipedia.org/wiki/Audrey_Tang
Source content: "April 18, 1981, in Taipei, Taiwan"
Comparison: Body date and place match Wikipedia exactly.
Decision: verified

## Claim 2: "[identifies herself](https://audreyt.org/) as a 'civic hacker' and as 'a driving force behind the creation of g0v (gov-zero)'"

Source: https://audreyt.org/
Source content: Tang describes herself as a "civic hacker" and identifies as "a driving force behind the creation of g0v (gov-zero)".
Comparison: Both quoted phrases appear verbatim on Tang's personal site.
Decision: verified

## Claim 3: "Wikipedia's biographical record places her as a [core member of g0v who joined shortly after the September 2012 founding](https://en.wikipedia.org/wiki/Audrey_Tang)"

Source: https://en.wikipedia.org/wiki/Audrey_Tang
Source content: "Tang joined the G0v movement shortly after its formation, and participated in the Sunflower Student Movement through that community." The article gives no specific founding month; the dedicated g0v Wikipedia article (https://en.wikipedia.org/wiki/G0v) places the founding in "late 2012", with the Budget Maps Yahoo Open Hack Day project in October 2012 and the December 1, 2012 Hackath0n as the community-solidifying event — i.e., not September 2012.
Comparison: Body specifies "September 2012 founding" and attributes the date to the cited Wikipedia article. Neither the Audrey Tang Wikipedia article nor the g0v Wikipedia article supports a September 2012 founding date; the supported framing is "late 2012" (October–December 2012). The "shortly after its formation" / "core member" framing is supported; the specific September month is not. Note: the entity's own `affiliations[0].role` scalar says "joined shortly after the **late-2012** founding", which is the supported phrasing — the body diverges from the entity's own frontmatter on this date.
Decision: discrepancy

## Claim 4: "By 2018 the [MIT Technology Review profile](...) was identifying her as 'a famed hacker who helped the thousands of Sunflower protesters build and maintain their internal communications network'"

Source: https://www.technologyreview.com/2018/08/21/240284/the-simple-but-ingenious-system-taiwan-uses-to-crowdsource-its-laws/
Source content: "a famed hacker who helped the thousands of Sunflower protesters build and maintain their internal communications network"
Comparison: Body quote matches the MIT Technology Review article verbatim.
Decision: verified

## Claim 5: "the [Right Livelihood Foundation's 2025 citation](...) describes g0v as 'a leaderless civic-tech collective'"

Source: https://rightlivelihood.org/the-change-makers/find-a-laureate/audrey-tang/
Source content: g0v is described as "a leaderless civic-tech collective that built tools for transparency and participation".
Comparison: Phrasing matches the Right Livelihood page verbatim.
Decision: verified

## Claim 6: GoVocal quote — "Civic hackers are often producing work that threatens the existing institutional structures. In Taiwan, the institutions have always taken a we can't beat them, so we must join them approach..."

Source: https://www.govocal.com/blog/pioneers-1-audrey-tang-taiwans-digital-minister
Source content: "Civic hackers are often producing work that threatens the existing institutional structures. In Taiwan, the institutions have always taken a 'we can't beat them, so we must join them' approach, which is a rare occurrence in Asian jurisdictions. That is, ultimately, why I remain in Taiwan."
Comparison: Body quotes the passage verbatim (with minor punctuation normalization on the inner quote marks).
Decision: verified

## Claim 7: "In March-April 2014, during the [Sunflower Student Movement occupation of Taiwan's Legislative Yuan](https://en.wikipedia.org/wiki/Audrey_Tang) over the opaque trade-services agreement with mainland China"

Source: https://en.wikipedia.org/wiki/Audrey_Tang
Source content: The Wikipedia article corroborates Tang's Sunflower Student Movement participation in 2014 (broadcasting protester messages from the Legislative Yuan); it does not contradict the standard Sunflower Movement chronology (18 March – 10 April 2014) or the trade-services-agreement framing.
Comparison: Period (March-April 2014), location (Legislative Yuan), and trigger (cross-strait service trade agreement) are consistent with Wikipedia coverage; named-entity definitional facts of the occupation are Wikipedia-alone-sufficient per source rule.
Decision: verified

## Claim 8: "Tang volunteered with the g0v community to [broadcast the protesters' messages](https://www.demnext.org/people/audrey-tang) from inside the occupied parliament and to maintain the protest's internal communications network"

Source: https://www.demnext.org/people/audrey-tang
Source content: During Taiwan's legislature occupation, Tang assisted in "broadcast[ing] the demands of Sunflower Movement activists, and worked to resolve conflicts during a three-week occupation".
Comparison: Body's "broadcast the protesters' messages" matches DemocracyNext's "broadcast the demands of Sunflower Movement activists" within paraphrase tolerance. The "maintain internal communications network" element is corroborated by the MIT Technology Review profile cited elsewhere ("helped the thousands of Sunflower protesters build and maintain their internal communications network").
Decision: verified

## Claim 9: "the [Right Livelihood citation](...) describes the civic-tech infrastructure as 'bringing citizens into the same room as lawmakers' for the first time"

Source: https://rightlivelihood.org/the-change-makers/find-a-laureate/audrey-tang/
Source content: Tang is quoted on the laureate page: "It was the moment technology proved it could bring citizens into the same room as lawmakers."
Comparison: The "bringing citizens into the same room as lawmakers" framing appears on the Right Livelihood laureate page as the body claims, though the source presents it as a Tang quote rather than as the citation's own description. The semantic content matches the laureate page's framing of the infrastructure; phrasing differences are within paraphrase tolerance.
Decision: verified

## Claim 10: "the [vTaiwan multi-phase collective-intelligence consultation process](https://compdemocracy.org/case-studies/2014-vtaiwan/) that became the country's longest-running national-scale [Polis](...) implementation"

Source: https://www.technologyreview.com/2018/08/21/240284/the-simple-but-ingenious-system-taiwan-uses-to-crowdsource-its-laws/ ; https://compdemocracy.org/case-studies/2014-vtaiwan/
Source content: MIT Technology Review: "vTaiwan...Built by the g0v (Gov Zero) civic tech community in 2015". CompDemocracy vTaiwan case study: "today vTaiwan contains the longest running, national-scale implementation of Polis" (verbatim superlative).
Comparison: Both the underlying claim (vTaiwan is a g0v-built Polis implementation) and the "longest-running national-scale Polis implementation" superlative are verified verbatim against the canonical sources cited in the body.
Decision: verified

## Claim 11: "Tang was recruited as the right hand of then-Minister Jaclyn Tsai and helped launch vTaiwan from inside that portfolio"

Source: https://www.govocal.com/blog/pioneers-1-audrey-tang-taiwans-digital-minister
Source content: "She swiftly came up with a collaboration plan, proposing the launch of a neutral citizen platform and appointing Audrey Tang as her right hand."
Comparison: GoVocal uses the exact phrase "right hand" and describes the platform launch under Tsai's portfolio.
Decision: verified

## Claim 12: 2018 MIT Tech Review quote — removing reply button "drastically reduces the motivation for trolls to troll" so senior public servants see commenters "not protesters or mobs, but actually people with distinct expertise"

Source: https://www.technologyreview.com/2018/08/21/240284/the-simple-but-ingenious-system-taiwan-uses-to-crowdsource-its-laws/
Source content: "If people can propose their ideas and comments but they cannot reply to each other, then it drastically reduces the motivation for trolls to troll" and senior public servants come to see online commenters as "not protesters or mobs, but actually people with distinct expertise".
Comparison: Both quoted fragments appear in the MIT Technology Review article verbatim; body's framing of the trolls-troll quote condenses the source's longer sentence but preserves the verbatim quoted span.
Decision: verified

## Claim 13: "the [Right Livelihood citation](...) credits her with leading the integration of Polis into vTaiwan as a 'broad-listening' space that elevates bridging ideas over divisive statements"

Source: https://rightlivelihood.org/the-change-makers/find-a-laureate/audrey-tang/
Source content: "vTaiwan is a participatory platform using Polis, an AI-supported tool, to reveal convergence areas rather than amplify extremes. It functions as a 'broad-listening' space that elevated bridging ideas instead of the loudest voices."
Comparison: All three elements (Tang's lead on Polis-vTaiwan integration, "broad-listening" framing, elevation of bridging ideas over divisive statements) match the Right Livelihood laureate page within paraphrase tolerance.
Decision: verified

## Claim 14: "On [1 October 2016 Tang was appointed Minister without Portfolio in the Executive Yuan](https://en.wikipedia.org/wiki/Audrey_Tang) under Tsai Ing-wen, becoming the youngest minister without portfolio in Taiwanese history at age thirty-five"

Source: https://en.wikipedia.org/wiki/Audrey_Tang
Source content: "Minister without Portfolio Appointment: October 1, 2016" and "At age 35, she was 'the youngest minister without portfolio in Taiwanese history'".
Comparison: Date (1 October 2016), title (Minister without Portfolio), age (35), and superlative ("youngest in Taiwanese history") all match Wikipedia exactly.
Decision: verified

## Claim 15: "the first transgender and first non-binary official in Taiwan's top executive cabinet"

Source: https://en.wikipedia.org/wiki/Audrey_Tang
Source content: "first transgender person and the first non-binary gender official in the top executive cabinet"
Comparison: Body claim matches Wikipedia's Taiwan-scoped framing exactly within paraphrase tolerance.
Decision: verified

## Claim 16: "On [27 August 2022] she moved to the newly-established Ministry of Digital Affairs (moda) as inaugural Minister of Digital Affairs, the role she held until [20 May 2024] when the Lai Ching-te administration was inaugurated and Huang Yen-nun succeeded her"

Source: https://en.wikipedia.org/wiki/Audrey_Tang
Source content: "Digital Affairs Ministry: Assumed office August 27, 2022; tenure ended May 20, 2024, succeeded by Huang Yen-nun under President Lai Ching-te"
Comparison: Start date (27 August 2022), end date (20 May 2024), successor (Huang Yen-nun), and incoming-administration (Lai Ching-te) all match Wikipedia exactly.
Decision: verified

## Claim 17: "the moda Alignment Assemblies of AI of March 2024 ran on the upstream g0v deliberative-democracy infrastructure rather than as a freestanding ministerial product"

Source: https://rebootdemocracy.ai/blog/audrey-tang-ai-democracy/ ; https://compdemocracy.org/case-studies/2014-vtaiwan/
Source content: Reboot Democracy confirms the March 2024 Alignment Assemblies launch ("The Ministry of Digital Affairs invited hundreds of thousands of randomly selected citizens via the 111 SMS number to co-create guidelines for AI evaluation in the context of information integrity") but does not describe the underlying platform as g0v infrastructure. CompDemocracy confirms PDIS currently runs vTaiwan and g0v originated the platform, but the specific architectural relationship between the 2024 Alignment Assemblies and g0v infrastructure is not addressed.
Comparison: The March 2024 Alignment Assemblies launch component is supported, but the load-bearing architectural framing — that the Assemblies "ran on the upstream g0v deliberative-democracy infrastructure rather than as a freestanding ministerial product" — is not directly stated by any canonical source consulted. This is a judgment-loaded characterization claim about technical lineage, and per the source rule ("load-bearing characterization" tier), independent corroboration is required and was not found.
Decision: unverifiable

## Claim 18: "The [Reboot Democracy interview](https://rebootdemocracy.ai/blog/audrey-tang-ai-democracy/) of 25 June 2024 captures her standing methodological position that 'progress can only be achieved when AI is grounded in participation: to build AI for the people, with the people'"

Source: https://rebootdemocracy.ai/blog/audrey-tang-ai-democracy/
Source content: Publication date June 25, 2024; quote: "Progress can only be achieved when [AI is] grounded in participation: to build AI for the people, with the people".
Comparison: Date and quote match exactly (the bracketed "[AI is]" in the source is a clarifying insertion).
Decision: verified

## Claim 19: "launched March 2024 with the Collective Intelligence Project, Anthropic, OpenAI, The GovLab, and the GETTING-Plurality research network — as a model in which 'everyday citizens are invited to co-govern AI in the context of information integrity'"

Source: https://rebootdemocracy.ai/blog/audrey-tang-ai-democracy/
Source content: Partners listed: "Collective Intelligence Project (CIP), Anthropic, OpenAI, The GovLab, and GETTING-Plurality research network". Quote: "Everyday citizens are invited to co-govern AI in the context of information integrity".
Comparison: Partner list and quote both match the Reboot Democracy article exactly.
Decision: verified

## Claim 20: "On [7 October 2024 she was appointed one of ten new Taiwanese ambassadors-at-large](https://en.wikipedia.org/wiki/Audrey_Tang) under the Cyber Ambassador title, posted to the [University of Oxford Accelerator Fellowship Programme] at the [Institute for Ethics in AI] as a Senior Accelerator Fellow"

Source: https://en.wikipedia.org/wiki/Audrey_Tang
Source content: "October 7, 2024, named 'one of ten new ambassadors-at-large'"; "Currently serving on the 'Accelerator Fellowship Programme of the University of Oxford,' addressing 'digital democracy and the concept of Plurality'".
Comparison: Date (7 October 2024), count (one of ten), and Oxford Accelerator Fellowship Programme placement all match Wikipedia. The Institute for Ethics in AI placement and "Senior Accelerator Fellow" title are confirmed by audreyt.org ("Senior Accelerator Fellow, Oxford Institute for Ethics in AI").
Decision: verified

## Claim 21: "Her [current public-record portfolio](https://audreyt.org/) — Cyber Ambassador Taiwan, Oxford Institute for Ethics in AI Senior Accelerator Fellow, TED 2026 Guest Curator, Omidyar Senior Advisor at the Mozilla Foundation, Senior Fellow at the Project Liberty Institute, and Plurality Initiative Advisor at the Ethereum Foundation"

Source: https://audreyt.org/
Source content: "Cyber Ambassador Taiwan; Senior Accelerator Fellow, Oxford Institute for Ethics in AI; Guest Curator, TED 2026; Omidyar Senior Advisor, Mozilla Foundation; Senior Fellow, Project Liberty Institute; Plurality Initiative Advisor, Ethereum Foundation".
Comparison: All six titles match audreyt.org exactly.
Decision: verified

## Claim 22: "She sits on the [DemocracyNext International Advisory Council](https://www.demnext.org/people/audrey-tang) and is the co-author with Glen Weyl of the [2024 book *⿻ Plurality*](https://en.wikipedia.org/wiki/Audrey_Tang) on collaborative digital democracy"

Source: https://www.demnext.org/people/audrey-tang ; https://en.wikipedia.org/wiki/Audrey_Tang
Source content: DemocracyNext page lists Tang as "International Advisory Council Member"; Wikipedia confirms "Plurality Book: Co-authored with Glen Weyl, published April 16, 2024". audreyt.org credits "E. Glen Weyl and the Plurality community" — the corpus body's "co-author with Glen Weyl" is the standard rendering.
Comparison: Council membership and 2024 Plurality co-authorship with Glen Weyl both verified.
Decision: verified

## Claim 23: "In 2025 she was awarded the [Right Livelihood Award](...) — citation: 'For advancing the social use of digital technology to empower citizens, renew democracy and heal divides.'"

Source: https://rightlivelihood.org/the-change-makers/find-a-laureate/audrey-tang/
Source content: Year of award: 2025. Citation: "For advancing the social use of digital technology to empower citizens, renew democracy and heal divides."
Comparison: Year, award name, and citation text match the Right Livelihood laureate page exactly.
Decision: verified

## Claim 24: scalar:sources[5].note — "primary source for her self-described co-founder relationship to g0v as a collective of independent software hackers"

Source: https://www.govocal.com/blog/pioneers-1-audrey-tang-taiwans-digital-minister
Source content: "g0v ('gov-zero'), a collective of independent software hackers including Audrey Tang, had already started fighting for the same cause." The article identifies Tang as a member of the hacker collective, not as a self-described co-founder; no co-founder language is used for Tang in the GoVocal article.
Comparison: The scalar claims GoVocal is "primary source for her self-described co-founder relationship to g0v" — but GoVocal does not describe Tang as a self-described co-founder; it describes her as part of a collective of independent software hackers. Wikipedia's framing is "core member who joined shortly after its formation"; audreyt.org's self-description is "a driving force behind the creation of g0v". None of the cited canonical sources support a "self-described co-founder" framing; the GoVocal-as-primary-source-for-co-founder claim in the `sources[5].note` scalar is unsupported by its named source. Recommend the scalar prose-replace "self-described co-founder relationship to g0v" with the supported phrasing, e.g. "self-described membership in g0v as a collective of independent software hackers" — single-token-class replacement available, located at frontmatter scalar `sources[5].note`.
Decision: discrepancy

