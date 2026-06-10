---
entity_id: msg-bossware
entity_hash: ff0e518c6a10ba4aa6c8fb6034ce9cbdff44f88f
audit_date: 2026-06-06
pass: 1
status: corrections-pending
claims_total: 25
claims_corroborated: 17
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 3
claims_uncorroborated: 5
sources_consulted:
  - https://www.eff.org/deeplinks/2020/06/inside-invasive-secretive-bossware-tracking-workers
  - https://home.coworker.org/worktech/
  - https://www.nelp.org/insights-research/when-bossware-manages-workers-digital-surveillance-automated-decision-system-abuses/
  - https://restofworld.org/2025/employee-surveillance-software-vc-funding/
  - https://restofworld.org/2025/code-ai-filipino-tech-workers/
  - https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/
  - https://bidenwhitehouse.archives.gov/ostp/news-updates/2022/10/04/blueprint-for-an-ai-bill-of-rightsa-vision-for-protecting-our-civil-rights-in-the-algorithmic-age/
  - https://www.govtrack.us/congress/bills/118/s262
  - https://www.govtrack.us/congress/bills/118/hr7690
---

## Claim 1: EFF investigation "Inside the Invasive, Secretive 'Bossware' Tracking Workers" was published 30 June 2020

Source: https://www.eff.org/deeplinks/2020/06/inside-invasive-secretive-bossware-tracking-workers
Source content: "June 30, 2020" — header date on the EFF Deeplinks post.
Comparison: Body date matches source date exactly.
Decision: corroborated

## Claim 2: EFF article authored by Bennett Cyphers and Karen Gullo

Source: https://www.eff.org/deeplinks/2020/06/inside-invasive-secretive-bossware-tracking-workers
Source content: Byline "Bennett Cyphers and Karen Gullo" on the article.
Comparison: Body attribution matches source byline exactly, including author order.
Decision: corroborated

## Claim 3: EFF investigation surveyed ten vendor products — ActivTrak, CleverControl, DeskTime, Hubstaff, InterGuard, StaffCop, Teramind, Time Doctor, Work Examiner, WorkPuls

Source: https://www.eff.org/deeplinks/2020/06/inside-invasive-secretive-bossware-tracking-workers
Source content: Article surveys "ActivTrak, CleverControl, DeskTime, Hubstaff, InterGuard, StaffCop, Teramind, TimeDoctor, Work Examiner, WorkPuls".
Comparison: All ten vendors match. EFF spells "TimeDoctor" as one word; body uses "Time Doctor" (a stylistic variant of the same product name) — within paraphrase tolerance.
Decision: corroborated

## Claim 4: scalar:origin and body — EFF "characterised them as 'tools that put workers' privacy and security at risk by logging every click and keystroke, covertly gathering information for lawsuits, and using other spying features that go far beyond what is necessary and proportionate to manage a workforce'"

Source: https://www.eff.org/deeplinks/2020/06/inside-invasive-secretive-bossware-tracking-workers
Source content: "bossware puts workers' privacy and security at risk by logging every click and keystroke, covertly gathering information for lawsuits, and using other spying features that go far beyond what is necessary and proportionate to manage a workforce."
Comparison: The body twice presents this as a verbatim EFF quote (scalar `origin` in frontmatter and the body's Origin section), but the entity's quoted opener "tools that put workers'" does not appear in the source — EFF's sentence begins "bossware puts workers'". The remainder of the quoted phrase is verbatim, but the subject substitution materially changes what was actually said, and presenting it inside quotation marks asserts a wording the source does not carry. The Editor's Audit-discrepancy backfill should replace the opener — both occurrences — with EFF's actual wording (substitute "bossware puts" for "tools that put").
Decision: correction

## Claim 5: scalar:origin and body — the EFF investigation set out a "six-category audit" / "six surveillance-category architecture": application/website (and email) monitoring; screenshots and screen recordings; keystroke logging; webcam and microphone activation; GPS tracking; remote desktop control

Source: https://www.eff.org/deeplinks/2020/06/inside-invasive-secretive-bossware-tracking-workers
Source content: The EFF "What can they do?" section enumerates seven distinct monitoring features: (1) activity monitoring (applications, websites, email, social media), (2) screenshots and screen recordings, (3) keystroke logging, (4) webcam and microphone activation, (5) location/GPS tracking, (6) remote desktop control, and (7) productivity metrics ("minute-by-minute breakdown of how much a user types and clicks").
Comparison: The six categories the body lists all appear in the EFF article, but the body asserts EFF's architecture is six-category whereas the article describes a seventh feature category (productivity metrics) that the body omits. Whether EFF presents these as numbered sections or as a single flowing taxonomy is a structural judgment call about the source — the source clearly enumerates more than six distinct features, but it does not announce an explicit "six-category" or "seven-category" count. Per the source-canonicality discipline, judgment-loaded counting is unverifiable.
Decision: uncorroborated

## Claim 6: Coworker.org Bossware and Employment Tech Database launched 17 November 2021

Source: https://home.coworker.org/worktech/
Source content: "NOVEMBER 17, 2021 | COWORKER.ORG" — explicit date header on the resource page.
Comparison: Body date matches source exactly.
Decision: corroborated

## Claim 7: Coworker.org database catalogues more than 550 products

Source: https://home.coworker.org/worktech/
Source content: "more than 550 labor-focused technology products."
Comparison: Body's "550-plus-product registry" and "catalogues more than 550 labour-focused technology products" both match the source's "more than 550" claim within paraphrase tolerance.
Decision: corroborated

## Claim 8: scalar:origin and body — database was launched alongside Wilneida Negrón's report "Little Tech Is Coming for Workers"

Source: https://home.coworker.org/worktech/
Source content: Database resource page identifies the accompanying report as "Little Tech Is Coming for Workers" by Wilneida Negrón, PhD ("A Framework for Reclaiming and Building Worker Power").
Comparison: Report title, author, and pairing with the database launch all match.
Decision: corroborated

## Claim 9: Coworker.org database uses an "eighteen-category audit framework" — specifically: hardware utilised, permission requests, facial recognition, algorithm claims, encryption, data-collection timing, informed consent, data-sharing arrangements, grievance mechanism, forced use, discrimination potential, freedom of association, workplace health and safety, environmental impact, supply chain worker safety, security, regulatory arbitrage, law enforcement data access

Source: https://home.coworker.org/worktech/
Source content: Database applies systematic evaluation across multiple dimensional categories spanning product details, business model, surveillance methods (hardware, permission requests, facial recognition), data practices (encryption, retention period, anonymisation), worker protections (consent, grievance mechanisms, access rights), and risk assessments (discrimination potential, freedom of association). The page does not explicitly enumerate "eighteen categories" as a single named framework.
Comparison: A majority of the body's eighteen items (hardware, permission requests, facial recognition, encryption, informed consent, grievance mechanism, discrimination potential, freedom of association) are clearly present in the database's audit structure. Whether the full set is exactly eighteen items matching the body's enumeration cannot be confirmed from the public-facing summary alone — the database's column structure may differ in number and naming from the body's list. Per source-canonicality discipline, a category-count claim that cannot be matched line-for-line against the source is unverifiable.
Decision: uncorroborated

## Claim 10: White House Blueprint for an AI Bill of Rights released 4 October 2022

Source: https://bidenwhitehouse.archives.gov/ostp/news-updates/2022/10/04/blueprint-for-an-ai-bill-of-rightsa-vision-for-protecting-our-civil-rights-in-the-algorithmic-age/
Source content: White House OSTP archive page dated "2022/10/04" — "Blueprint for an AI Bill of Rights: A Vision for Protecting Our Civil Rights in the Algorithmic Age."
Comparison: Body's 4 October 2022 matches the OSTP archive URL's publication date.
Decision: corroborated

## Claim 11: Blueprint designates employment as a "sensitive domain" deserving heightened oversight

Source: https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/
Source content: "Automated systems with an intended use within sensitive domains, including, but not limited to, criminal justice, employment, education, and health …" Employment is explicitly named as a sensitive domain warranting heightened protections.
Comparison: Body's characterisation matches source content directly.
Decision: corroborated

## Claim 12: Blueprint frames continuous workplace monitoring as a domain where automated systems "should not be used" without strong protections

Source: https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/
Source content: "Continuous surveillance and monitoring should not be used in education, work, housing, or in other contexts where the use of such surveillance technologies is likely to limit rights, opportunities, or access."
Comparison: The "should not be used" phrasing the body uses appears verbatim in the source applied to continuous surveillance in work contexts. Paraphrase-tolerant match.
Decision: corroborated

## Claim 13: Stop Spying Bosses Act introduced 2 February 2023 as S. 262

Source: https://www.govtrack.us/congress/bills/118/s262 (118th Congress S. 262 record)
Source content: S. 262, 118th Congress (2023-2024), "Stop Spying Bosses Act", introduced 2 February 2023 in the Senate, read twice and referred to the Committee on Health, Education, Labor, and Pensions.
Comparison: Both the date and bill number match the canonical congressional record.
Decision: corroborated

## Claim 14: Stop Spying Bosses Act introduced by Senators Bob Casey (D-PA), Cory Booker (D-NJ), and Brian Schatz (D-HI)

Source: https://www.govtrack.us/congress/bills/118/s262
Source content: Sponsor: Sen. Robert P. Casey, Jr. (D-PA); original cosponsors include Cory Booker (D-NJ), Brian Schatz (D-HI), John Fetterman (D-PA), and Elizabeth Warren (D-MA).
Comparison: The three named lead introducers, with parties and states, all match the congressional record. Body does not assert these were the only original cosponsors (it names Casey, Booker, Schatz as the lead trio); the existence of additional cosponsors (Fetterman, Warren) is consistent with the body's framing.
Decision: corroborated

## Claim 15: companion House bill is H.R. 7690

Source: https://www.govtrack.us/congress/bills/118/hr7690
Source content: H.R. 7690, 118th Congress (2023-2024), "Stop Spying Bosses Act" — the House companion to S. 262.
Comparison: Body bill number matches canonical record.
Decision: corroborated

## Claim 16: Stop Spying Bosses Act establishes employer disclosure requirements, prohibitions on surveilling protected labour activity, off-duty monitoring restrictions, prohibitions on health and disability data collection, third-party data-sale prohibitions, and a new Privacy and Technology Division at the Department of Labor

Source: https://www.govtrack.us/congress/bills/118/s262
Source content: Bill summary: requires employers to disclose to workers what data is collected and how it is used; prohibits using workplace surveillance to identify or monitor workers involved with labour organisations, to ascertain political opinions, to identify health conditions unrelated to job duties, or to monitor workers who report employer violations. Bill text creates the Privacy and Technology Division at the Department of Labor and contains restrictions on off-duty monitoring and third-party data sale.
Comparison: The architecture clauses the body lists all map onto provisions in the canonical bill summary and text.
Decision: corroborated

## Claim 17: NELP report "When 'Bossware' Manages Workers" published 15 July 2025 by Irene Tung, Paul K. Sonn, Maya Pinto, Sally Dworak-Fisher, Josh Boxerman

Source: https://www.nelp.org/insights-research/when-bossware-manages-workers-digital-surveillance-automated-decision-system-abuses/
Source content: NELP page lists the report as published 15 July 2025 with authors (in order) Irene Tung, Paul K. Sonn, Maya Pinto, Sally Dworak-Fisher, Josh Boxerman, under the full title "When 'Bossware' Manages Workers: A Policy Agenda to Stop Digital Surveillance and Automated-Decision-System Abuses."
Comparison: Date, full title, and author list (with order) match exactly.
Decision: corroborated

## Claim 18: NELP report treats bossware as the umbrella for "digital surveillance and automated decision systems" used for "employee monitoring, pay-setting, staffing, performance evaluation, and discipline"

Source: https://www.nelp.org/insights-research/when-bossware-manages-workers-digital-surveillance-automated-decision-system-abuses/
Source content: Report conceptualises bossware as encompassing "digital surveillance and automated decision systems" used for management functions including "employee monitoring, pay-setting, staffing, performance evaluation, and discipline."
Comparison: Body's quoted umbrella framing matches source content verbatim across both quoted phrases.
Decision: corroborated

## Claim 19: Rest of World article "more than 150 employee-surveillance startups across six developing nations" published 3 June 2025 by Gayathri Vaidyanathan

Source: https://restofworld.org/2025/employee-surveillance-software-vc-funding/
Source content: Article by Gayathri Vaidyanathan dated 3 June 2025; audited "more than 150 startups and regional companies."
Comparison: Date, author, and "more than 150" startup count all match.
Decision: corroborated

## Claim 20: the six developing nations in the Rest of World audit include "Chile (Rankmi), Mexico (Cincel), Brazil (Ahgora), Colombia (Rappi-affiliated tooling), among others"

Source: https://restofworld.org/2025/employee-surveillance-software-vc-funding/
Source content: The article identifies the six nations audited as Kenya, Nigeria, Colombia, Brazil, Mexico, and India. The article does discuss Chile-based Rankmi by name and describes its biometric/geolocation tracking, but Chile is not listed among the six audited nations. Mexico (Cincel), Brazil (Ahgora), Colombia (Rappi) are all named in the article and are among the six.
Comparison: The body's phrasing "across six developing nations — Chile (Rankmi), Mexico (Cincel), Brazil (Ahgora), Colombia (Rappi-affiliated tooling), among others" reads Chile as one of the six. It is not — the article's six are Kenya, Nigeria, Colombia, Brazil, Mexico, India. Rankmi/Chile is mentioned in the article but as additional coverage, not part of the six-country audit set. The Editor's Audit-discrepancy backfill should either drop Chile/Rankmi from the six-country listing or rewrite the sentence to surface a country actually in the six (Kenya, Nigeria, or India), since this needs prose judgment beyond a single replacement, an `[editor-flag]` to the Researcher is appropriate.
Decision: correction

## Claim 21: 2024 OECD survey found more than 90% of American managers used such tools

Source: https://restofworld.org/2025/employee-surveillance-software-vc-funding/
Source content: "More than 90% of American managers used such tools, especially to reward or sanction employees" (based on a 2024 survey of over 6,000 employers).
Comparison: Survey year, percentage, and the "more than 90%" framing all match.
Decision: corroborated

## Claim 22: scalar:sources note for CODE-AI article — Rest of World "(Michael Beltran, 27 January 2025) on the formation of CODE-AI" documents Concentrix sentiment-analysis tooling that scores agents in real time on tone, pitch, mood, positive language use, interruptions, hold times, and issue-resolution speed, and an AI co-pilot suggesting real-time customer-information responses

Source: https://restofworld.org/2025/code-ai-filipino-tech-workers/
Source content: Article references "advanced AI tools deployed by Concentrix Corporation and Accenture — including AI co-pilots and sentiment analysis." Repeated focused fetches confirm that none of the phrases "tone", "pitch", "mood", "positive language", "interruptions", "hold times", or "issue-resolution speed" appear in the article body. The article quotes a worker saying "Our productivity is closely monitored by AI" but does not enumerate the specific scoring metrics the body attributes to it. The AI co-pilot is named but its "suggesting real-time customer-information responses" function is not described.
Comparison: The article supports the high-level claims that Concentrix uses sentiment-analysis tooling and AI co-pilots, but it does not document the specific metric set (tone, pitch, mood, positive language use, interruptions, hold times, issue-resolution speed) the body's body section and `sources[].note` frontmatter scalar attribute to it. Two repeated focused fetches both returned the same null result on these specific phrases. Body is making a more granular factual claim about the source's content than the source supports. The body's specific metric list, repeated near-verbatim in the SCOPE-EDGE section, would need either a different source (e.g. a CODE-AI primary statement or a different press piece) or attenuation to "AI co-pilots and sentiment analysis tooling" without the granular metric enumeration. This requires prose judgment, so an `[editor-flag]` to Researcher is appropriate.
Decision: correction

## Claim 23: scalar:sources note — Rest of World CODE-AI article published date

Source: https://restofworld.org/2025/code-ai-filipino-tech-workers/
Source content: WebFetch returned "28 January 2025" as the article's publication date.
Comparison: The body's `sources[].note` scalar says "27 January 2025" while the WebFetch summary reports 28 January 2025. The one-day gap is plausibly a publication time-zone display difference (Manila vs. US East Coast or UTC) and the WebFetch's date extraction may itself round to a display date rather than the article's embargo-lift timestamp. Without a primary metadata source confirming one or the other, the source-canonicality call here is judgment-loaded.
Decision: uncorroborated

## Claim 24: NY State Senator Brad Hoylman-Sigal introduced an AI-and-bossware workplace-restrictions bill in 2023

Source: no canonical source successfully fetched in this audit pass (the linked nysenate.gov URL was not retrieved).
Source content: not available in this pass.
Comparison: not performed.
Decision: uncorroborated

## Claim 25: Negrón's "Little Tech" thesis names the strategic premise that "proliferation of small-vendor, low-cost workplace-surveillance products has produced an industry-wide labour-relations infrastructure that operates below the regulatory threshold of larger AI systems"

Source: https://home.coworker.org/worktech/
Source content: The Coworker.org resource page foregrounds the "Little Tech Is Coming for Workers" report as "A Framework for Reclaiming and Building Worker Power" by Wilneida Negrón, PhD; the page summarises Negrón's thesis as concerning small-vendor workplace-surveillance proliferation but does not surface the specific "below the regulatory threshold of larger AI systems" framing as a verbatim quote.
Comparison: The high-level claim that Negrón names a "Little Tech" thesis around small-vendor surveillance proliferation is supported by the source page, but the body's specific characterisation of the thesis (operating "below the regulatory threshold of larger AI systems while exerting cumulative effects on labour-conditions, organising rights, and wage-setting practices") cannot be verified against the Coworker.org page summary alone — it would require fetching the Negrón report PDF directly. Per source-canonicality discipline, a load-bearing characterisation that cannot be checked against the primary source is unverifiable.
Decision: uncorroborated
