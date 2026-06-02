---
entity_id: person-maxime-fournes
entity_hash: 1c48122abe529c085be3bc3d034f754d66c9e47b
audit_date: 2026-06-02
pass: 2
status: unverifiable
claims_total: 5
claims_verified: 4
claims_discrepancy: 0
claims_unverifiable: 1
sources_consulted:
  - https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
  - https://pauseai.info/people
  - https://pauseia.fr/en/qui-sommes-nous
  - https://en.wikipedia.org/wiki/PauseAI
  - https://www.cnn.com/2026/04/17/tech/anti-ai-attack-sam-altman
---

## Claim 1: "CEO of PauseAI"

Source: https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes ; https://pauseai.info/people
Source content: Substack: "Maxime Fournes will be taking on the role of CEO at PauseAI Global." PauseAI's people roster: "Maxime Fournes — CEO PauseAI Global."
Comparison: Body claim matches both PauseAI's own announcement and the current people page.
Decision: verified

## Claim 2: "having taken over global leadership from founder Joep Meindertsma in late 2025"

Source: https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes ; https://en.wikipedia.org/wiki/PauseAI ; https://pauseai.info/people
Source content: Substack announcement published "Dec 02, 2025": "Maxime Fournes will be taking on the role of CEO at PauseAI Global." Wikipedia: "Founder Joep Meindertsma... founded PauseAI in May 2023." PauseAI people page: Meindertsma listed as "Founder PauseAI Global, Board Chair"; Fournes as "CEO PauseAI Global."
Comparison: All three sub-claims supported — Meindertsma as founder (Wikipedia + people page), Fournes taking on CEO at PauseAI Global (substack + people page), and "late 2025" matches the Dec 2, 2025 announcement date.
Decision: verified

## Claim 3: "previously founded and led PauseIA France, the organisation's French chapter"

Source: https://pauseia.fr/en/qui-sommes-nous ; https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
Source content: PauseIA France's "Qui sommes-nous" page lists Fournes as "Co-fondateur et Président" (Co-founder and President) and states "We are part of Pause AI Global, an international movement..." Substack: "After serving as the Director of PauseIA France, Maxime Fournes will be taking on the role of CEO at PauseAI Global."
Comparison: pauseia.fr confirms co-founder status (English "founded" customarily covers co-founders) and current leadership (Président); substack confirms he led/directed the chapter; pauseia.fr confirms the chapter is part of PauseAI Global.
Decision: verified

## Claim 4: scalar:sources[0].note "PauseAI's primary announcement of Fournes as CEO and his earlier role founding PauseIA France"

Source: https://pauseai.substack.com/p/meet-our-new-ceo-maxime-fournes
Source content: "Maxime Fournes will be taking on the role of CEO at PauseAI Global... After serving as the Director of PauseIA France... led a national chapter that's seen impressive growth in numbers." Dated Dec 02, 2025.
Comparison: The substack is PauseAI's own announcement of Fournes as CEO (matches "primary announcement of Fournes as CEO") and covers his earlier PauseIA France role (matches "earlier role"). The substack uses "Director" rather than "founder" for PauseIA France, but the note's broader framing — that this source covers his earlier role at PauseIA France — is supported, and the founding aspect is independently verified by pauseia.fr.
Decision: verified

## Claim 5: scalar:sources[1].note "CNN reporting carrying Fournes's CEO statement after the April 2026 Sam Altman incident"

Source: https://www.cnn.com/2026/04/17/tech/anti-ai-attack-sam-altman
Source content: CNN returned HTTP 451 "Unavailable For Legal Reasons" (CNN geo-blocks EU/non-US clients; the audit session cannot retrieve the article body). No alternate canonical source surfaces in Bing or DuckDuckGo searches for `"Maxime Fournes" PauseAI CNN Sam Altman April 2026` that would corroborate either the existence of this CNN article or a "Sam Altman incident" in April 2026.
Comparison: Cannot compare body/scalar claim to source content — the source is inaccessible from this audit's vantage and no canonical cross-check is available. Per the source rule, this is the "source dead" edge and resolves to unverifiable, not a discrepancy (the article may exist and may carry the quoted statement; this audit cannot tell).
Decision: unverifiable
