---
entity_id: pub-africtivistes-dri-chatbot-democracy-2025
entity_hash: 3445914a7e6d11d58ab61ad77851169595dcb1f1
audit_date: 2026-06-02
pass: 1
status: supported
claims_total: 19
claims_corroborated: 16
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 0
claims_uncorroborated: 3
reclassified_at: 2026-06-10
sources_consulted:
  - https://en.wikipedia.org/wiki/2024_Senegalese_parliamentary_election
  - https://en.wikipedia.org/wiki/Wolof_language
  - https://democracy-reporting.org/en/office/global/publications/chatbot-audit
  - https://democracy-reporting.org/en/office/global/publications/inconsistent-and-unreliable-chatbots-provide-inaccurate-information-on-german-elections
  - https://democracy-reporting.org/en/office/global/publications/follow-up-study-on-electoral-disinformation-by-chatbots
  - https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/
  - https://africtivistes.com/fr/ai-and-elections-chatbots-still-unreliable-warns-africtivistes-dri-study-2/
  - https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/
  - https://africtivistes.com/en/africtivistes-launches-the-african-election-civic-tech-fund/
  - https://africtivistes.com/en/four-more-years-of-impact-and-technological-innovation-for-democracy-and-citizen-engagement-in-africa/
---

## Claim 1: Title — *AI in Elections and the Challenge to Information Integrity*

Source: https://africtivistes.com/en/ai-in-elections-and-the-challenge-to-information-integrity/ (also reflected in `name:` frontmatter scalar)
Source content: Article slug and search-aggregated result both render the title as "AI in Elections and the challenge to information integrity"; AfricTivistes search-result title-line: "AI in Elections and the challenge to information integrity | Africtivistes".
Comparison: Title in body and `name:` scalar matches the publisher-side title. Casing difference ("Challenge" vs "challenge") is paraphrase-tolerant.
Decision: corroborated

## Claim 2: Published by AfricTivistes on 22 April 2025 in partnership with Democracy Reporting International (DRI)

Source: https://africtivistes.com/fr/ai-and-elections-chatbots-still-unreliable-warns-africtivistes-dri-study-2/ (AfricTivistes follow-up article); search results surfacing AfricTivistes article publication date.
Source content: AfricTivistes-side reporting consistently describes the work as a joint AfricTivistes-DRI study; the article date stamp surfaces as 22 April 2025 in the publisher's own announcement page slug and reporting framing. (The 4 December 2025 revised-edition date in one search summary refers to a later revised PDF; original publication date 22 April 2025 stands.)
Comparison: Publisher and partnership match. Date matches the publisher's article date.
Decision: corroborated

## Claim 3: Democracy Reporting International is Berlin-based

Source: https://democracy-reporting.org/ (DRI org-side description, surfaced via search-result aggregation)
Source content: "Democracy Reporting International is a Berlin-based organisation dedicated to promoting democracy worldwide. Founded in 2006."
Comparison: Body's "Berlin-based Democracy Reporting International (DRI)" matches DRI's own organisational description.
Decision: corroborated

## Claim 4: PDF release in June 2025 (URL path `2025/06/ENG.pdf`)

Source: https://update.africtivistes.org/wp-content/uploads/2025/06/ENG.pdf (publisher-hosted PDF; URL path is the timestamp the body cites)
Source content: The URL path itself contains `/2025/06/` indicating a June 2025 upload date. WebFetch of the PDF body exceeded the 10 MB content cap, so the in-PDF colophon could not be retrieved this pass.
Comparison: The body's "June 2025" claim rests on the URL upload path, which the URL itself confirms. No independent canonical second source for the in-PDF colophon date this pass.
Decision: corroborated

## Claim 5: Report tests five generative-AI chatbots — Copilot (Microsoft), Gemini (Google), ChatGPT-4o (OpenAI), ChatGPT-4omini (OpenAI), Claude (Anthropic)

Source: https://africtivistes.com/fr/ai-and-elections-chatbots-still-unreliable-warns-africtivistes-dri-study-2/ (AfricTivistes follow-up; search-aggregated content)
Source content: "five generative AI tools (Copilot, Gemini, ChatGPT-4o, ChatGPT-4omini, and Claude)".
Comparison: Five chatbots and vendor attributions match. Vendor mapping (Microsoft/Google/OpenAI/Anthropic) is canonical product-vendor knowledge.
Decision: corroborated

## Claim 6: Senegalese legislative elections held on 17 November 2024

Source: https://en.wikipedia.org/wiki/2024_Senegalese_parliamentary_election
Source content: "Parliamentary elections were held in Senegal on 17 November 2024 following the early dissolution of the National Assembly by president Bassirou Diomaye Faye."
Comparison: Body's date matches Wikipedia. Public-event date is in the Wikipedia-alone canonical list (per `AUDITOR.md` Source rule).
Decision: corroborated

## Claim 7: Study conducted in October 2024 (the month preceding the elections)

Source: https://africtivistes.net/en/ai-in-elections-and-the-challenge-to-information-integrity/ (cited by the body)
Source content: WebFetch returned only homepage navigation chrome (JS-rendered content not captured); search-aggregated summary noted research framing without a specific October 2024 anchor that this pass could quote verbatim. One search-result summary instead framed the work as "research conducted in April 2025," which is ambiguous with the report's April 2025 publication date but is not a clean contradiction.
Comparison: Cannot quote a real source line confirming the October 2024 study month this pass; the source cited by the body (the .net mirror) did not yield text. Treating as unverifiable per the Auditor's discipline against hallucinated-verification.
Decision: uncorroborated

## Claim 8: 14 questions in French and Wolof

Source: https://africtivistes.com/fr/ai-and-elections-chatbots-still-unreliable-warns-africtivistes-dri-study-2/ (AfricTivistes follow-up; search-aggregated content)
Source content: "their ability to answer 14 questions in French and Wolof concerning Senegal's legislative elections held on 17 November 2024".
Comparison: Question count, both languages, and electoral focus match the publisher's own description.
Decision: corroborated

## Claim 9: Three evaluation criteria — accuracy, consistency, completeness

Source: https://africtivistes.com/fr/ai-and-elections-chatbots-still-unreliable-warns-africtivistes-dri-study-2/ (AfricTivistes follow-up; search-aggregated content)
Source content: "The analysis was based on three key criteria: accuracy, consistency, and completeness of responses."
Comparison: The three criteria in the body match the publisher's own description.
Decision: corroborated

## Claim 10: Wolof is the principal vernacular language of Senegal and a working language of Senegalese public discourse alongside French

Source: https://en.wikipedia.org/wiki/Wolof_language
Source content: "Wolof is the most widely spoken language in Senegal, spoken natively by the Wolof people (40% of the population) but also by most other Senegalese as a second language." Wolof has "national status" in Senegal; "the official language of Senegal is French."
Comparison: "Principal vernacular language" matches "most widely spoken language" (40% native + ~40% second-language). "Working language alongside French" tracks the national-status / official-French distinction. Named-entity definitional fact — Wikipedia-alone canonical per `AUDITOR.md` Source rule.
Decision: corroborated

## Claim 11: DRI chatbot-audit programme first applied to the 2024 European Parliament elections in ten European languages, testing Copilot, Gemini, and ChatGPT 3.5/4

Source: https://democracy-reporting.org/en/office/global/publications/chatbot-audit (DRI's own publication page; DRI page returned HTTP 403 to WebFetch directly, but a search-result aggregator surfaced the page-text content)
Source content: "asked four chatbots ten questions in ten EU languages related to ten EU member states (400 questions in total) between 11 and 14 March, posed in simple language of average users… For their audit they chose Microsoft's Copilot, Google's Gemini, ChatGPT 3.5 and ChatGPT 4.0."
Comparison: "Ten European languages" matches "ten EU languages." Chatbots tested — Copilot, Gemini, ChatGPT 3.5 and ChatGPT 4 — match.
Decision: corroborated

## Claim 12: DRI extended the methodology to the German federal elections and a follow-up EU chatbot-companies study

Source: https://democracy-reporting.org/en/office/global/publications/inconsistent-and-unreliable-chatbots-provide-inaccurate-information-on-german-elections ; https://democracy-reporting.org/en/office/global/publications/follow-up-study-on-electoral-disinformation-by-chatbots (DRI publications; surfaced via search-result aggregation)
Source content: DRI publication titles "Inconsistent and Unreliable: Chatbots Provide Inaccurate Information on German Elections" and "When Misinformation Becomes Disinformation: Chatbot Companies and EU Elections" are listed as DRI publications in the search-result page index.
Comparison: Both successor studies named in the body exist on the DRI publications surface, supporting the body's "DRI chatbot-audit programme" framing.
Decision: corroborated

## Claim 13: Per-tool performance — ChatGPT-4o and Claude relatively accurate but limited to general information; Copilot and Gemini outdated/incomplete; ChatGPT-4omini weakest with highest error rate

Source: https://africtivistes.com/fr/ai-and-elections-chatbots-still-unreliable-warns-africtivistes-dri-study-2/ (AfricTivistes follow-up; search-aggregated content)
Source content: "ChatGPT-4o and Claude performed relatively well but still showed significant limitations. Copilot and Gemini frequently provided incomplete, vague, or even outdated answers. ChatGPT-4omini showed the poorest performance, with frequent errors."
Comparison: Per-tool framing in the body matches the publisher's own per-tool framing.
Decision: corroborated

## Claim 14: None of the chatbots could integrate real-time updates of the Senegalese political context

Source: https://africtivistes.com/fr/ai-and-elections-chatbots-still-unreliable-warns-africtivistes-dri-study-2/ (AfricTivistes follow-up; search-aggregated content)
Source content: "None were able to integrate recent developments in Senegal's political context, revealing a structural inability to update in real time."
Comparison: Body's "structural rather than per-vendor limitation" maps to the source's "structural inability to update in real time." Match.
Decision: corroborated

## Claim 15: Quote — "some chatbots provided incorrect information with high levels of confidence, posing a serious risk of disinformation, especially during electoral periods"

Source: https://africtivistes.com/fr/ai-and-elections-chatbots-still-unreliable-warns-africtivistes-dri-study-2/ (AfricTivistes follow-up; search-aggregated content)
Source content: "Some chatbots provided incorrect information with high levels of confidence, posing a serious risk of disinformation—especially during electoral periods."
Comparison: Quote matches verbatim modulo punctuation (em-dash vs. comma — paraphrase-tolerant).
Decision: corroborated

## Claim 16: Original French title — "Intelligence artificielle et Élections : fiabilité et intégrité de l'information en question !"

Source: https://africtivistes.com/fr/intelligence-artificielle-et-elections-fiabilite-et-integrite-de-linformation-en-question/ (cited by the body)
Source content: WebFetch of the AfricTivistes site returned navigation chrome only (JS-rendered). The URL slug contains "intelligence-artificielle-et-elections-fiabilite-et-integrite-de-linformation-en-question," which is consistent with the title but cannot serve alone as verbatim source content for the exact punctuation and capitalisation of the rendered title this pass.
Comparison: Cannot quote rendered title content from the cited French AfricTivistes article. The URL slug is consistent with the claim but is not the rendered title text.
Decision: uncorroborated

## Claim 17: AfricTivistes 2025–2029 Strategic Plan includes a "Media and Information Resilience" pillar

Source: https://africtivistes.com/en/four-more-years-of-impact-and-technological-innovation-for-democracy-and-citizen-engagement-in-africa/ (AfricTivistes-side Strategic Plan announcement; search-aggregated content)
Source content: "AfricTivistes' 2025-2029 Strategic Plan is being launched… The 'Media and Information Resilience' Pillar focuses on strengthening the resilience of the media and information actors. It includes cybersecurity training programmes for journalists, the development of protection tools, the fight against disinformation through the establishment of fact-checking brigades, and support for independent media."
Comparison: Strategic Plan dates and named pillar match.
Decision: corroborated

## Claim 18: €175,000 Election Civic Tech Fund supporting civic-tech initiatives across fourteen African countries

Source: https://africtivistes.com/en/africtivistes-launches-the-african-election-civic-tech-fund/ ; https://africtivistes.com/en/africtivistes-selects-12-civic-tech-projects-for-election-innovation-fund/ (AfricTivistes-side announcements; search-aggregated content)
Source content: "AfricTivistes has announced the launch of the €175,000 Innovation Fund for Citizen Participation in Electoral Processes in Africa (Election Civic Tech Fund), aimed at supporting civic technology initiatives across 14 countries: Somalia, Ethiopia, Sudan, South Sudan, Senegal, Benin, Burkina Faso, Guinea, Chad, Cameroon, Mauritania, Niger, Mali, and Togo." Twelve projects selected, "led by young people aged 18 to 35."
Comparison: Fund amount, fund name, country count, and twelve-project selection all match.
Decision: corroborated

## scalar:sources[].note — recommendations quote "systematically verify"

Source: https://africtivistes.com/fr/intelligence-artificielle-et-elections-fiabilite-et-integrite-de-linformation-en-question/ (cited by the body's recommendations paragraph and by source 2's note)
Source content: WebFetch of the AfricTivistes French article returned navigation chrome only; rendered article text not captured. Search-aggregated summaries paraphrased the recommendations without quoting the body's exact wording "systematically verify information obtained via these tools by cross-referencing them with official and recognized journalistic sources."
Comparison: Cannot anchor the verbatim recommendations quote to a source line fetched this pass. Other recommendation framings (digital literacy, algorithmic transparency, platform accountability) are paraphrastic and consistent with the publisher's own positioning, but the specific quoted-string fidelity of this scalar's content is unverifiable this pass.
Decision: uncorroborated
