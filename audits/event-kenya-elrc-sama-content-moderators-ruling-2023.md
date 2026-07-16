---
entity_id: event-kenya-elrc-sama-content-moderators-ruling-2023
entity_hash: 3fc23daa0701b29b6f7ccd2db65bddf8f210e960
audit_date: 2026-07-15
pass: 1
status: corrections-pending
claims_total: 40
claims_corroborated: 15
claims_primary_sourced: 10
claims_single_source: 3
claims_uncorroborated: 8
open_corrections: 4
sources_consulted:
  - https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
  - https://www.foxglove.org.uk/2023/06/06/kenyan-court-ruling-outsourced-content-moderation-facebook/
  - https://indconlawphil.wordpress.com/2023/06/09/meta-labour-law-and-the-constitution-the-judgment-of-the-kenyan-employment-and-labour-relations-court/
  - https://www.corpwatch.org/article/kenyan-court-orders-facebook-moderation-contractor-pay-its-workers-back-wages
  - https://www.business-humanrights.org/en/latest-news/kenya-content-moderators-filed-a-lawsuit-against-meta-alleging-poor-working-conditions-including-insufficient-mental-health-support-and-low-pay/
  - https://new.kenyalaw.org/akn/ke/judgment/keca/2023/996/eng@2023-07-28
  - https://en.wikipedia.org/wiki/Kauna_Malgwi
  - https://time.com/6275995/chatgpt-facebook-african-workers-union/
  - https://time.com/6253180/meta-kenya-lawsuit-motaung/
  - https://www.aljazeera.com/news/2023/4/20/court-rules-meta-can-be-sued-in-kenya-over-alleged-unlawful-redundancies
  - https://restofworld.org/2023/meta-content-moderators-kenya-fired-unionize/
  - https://www.computerweekly.com/feature/Kenyan-workers-win-High-Court-appeal-to-take-Meta-to-trial
  - https://techcrunch.com/2023/06/02/meta-found-liable-as-court-blocks-firing-of-moderators/
---

Connective type (event): claim surface is edges + hard specifics per `mission/MISSION.md § Auditor § Type-shape awareness`. Interpretive significance prose ("crowded early-2023 period", "moment when the case moved", corpus-arc framing) carries no decisions.

## Claim 1: scalar:date — 2023-06-02

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: "Arendse & 42 others v Meta Platforms, Inc & 3 others (Constitutional Petition E052 of 2023) [2023] KEELRC 1398 (KLR) (2 June 2023)"; Foxglove post: "Last Friday, a judge in Kenya's Employment and Labour Relations Court made a ruling"
Comparison: Judgment date matches; Foxglove and BHRRC concur.
Decision: corroborated

## Claim 2: scalar:location — "Milimani Law Courts, Nairobi — Employment and Labour Relations Court of Kenya"

Source: https://www.techpolicy.press/how-lawsuits-in-kenya-seek-to-hold-meta-accountable-for-the-harm-it-causes/ (via search snippet)
Source tier: mainstream
Source content: "184 moderators who sued Meta and Sama Source in the Nairobi Milimani Courts in March 2023"; AFP caption (search snippet): "outside the labor court in Milimani, where they filed a complaint in Kenya against Meta"
Comparison: Judgment header places the ELRC at Nairobi; the Milimani venue specific rests on one mainstream snippet-level source.
Decision: single-source

## Claim 3: scalar:campaign — camp-foxglove-185-moderators-meta-kenya

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Petition E052 of 2023 is the mass-dismissal case brought by the moderator group (43 filers expanding to 184/185) — the case the campaign entity records (campaign start_date 2023-03-17 matches the petition's filing).
Comparison: Edge resolves to an existing entity; the ruling belongs to that campaign's case. Correct edge.
Decision: corroborated

## Claim 4: scalar:participating_orgs / participating_people — org-foxglove, org-nzili-sumbi-advocates, person-mercy-mutemi

Source: https://www.foxglove.org.uk/2023/06/06/kenyan-court-ruling-outsourced-content-moderation-facebook/
Source tier: primary
Source content: Foxglove's own post on the ruling; search-confirmed reporting names "their lawyer, Mercy Mutemi" (TechPolicy.Press/AFP) and Mutemi's firm Nzili & Sumbi as briefing the moderator cases (Time, TechCrunch).
Comparison: All three edges resolve to existing entities and are confirmed participants in the case.
Decision: corroborated

## Claim 5: scalar:related_events — motaung petition filing (2022-05-10), union founding vote (2023-05-01)

Source: https://time.com/6275995/chatgpt-facebook-african-workers-union/
Source tier: primary
Source content: KECA 996 record: "By a petition dated May 9, 2022, Daniel Motaung… sued Samasource… and Meta Platforms, Inc and Meta Platforms Ireland Limited… in constitutional petition number E071 of 2022"; Time: "On May 1, 2023, more than 150 workers gathered at the Mövenpick Hotel in Nairobi and voted to establish the African Content Moderators Union."
Comparison: Both edges resolve to existing entities; both underlying events are confirmed by primary/mainstream sources. (Motaung petition dated 9 May 2022 per KECA 996 vs. the related event's 10 May filing-date slug — the filing-vs-dating distinction belongs to that entity's own audit, not this one.)
Decision: corroborated

## Claim 6: scalar:sources[0].note — Paragraph 29 quotes and the affidavit strikes

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: "the 1st and 2nd respondents were the primary or principal employers of the applicants and the 3rd respondent was merely the agent, foreman, manager or factor"; Meta's Redmond affidavit struck for futuristic jurat date (sworn 08.06.2023, filed 09.05.2023); Sama's and Majorel's affidavits struck — commissioners without valid 2023 practising certificates.
Comparison: The note's Paragraph 29 quotes are verbatim; the affidavit-strike description (Meta futuristic jurat; Samasource and Majorel commissioner defects) matches the record.
Decision: primary-sourced

## Claim 7: scalar:sources[0].note — "the six-ground sham-redundancy analysis"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Targeted read: "The judgment does not explicitly enumerate six grounds in a single passage. The court discusses redundancy validity across multiple paragraphs but does not use that format."
Comparison: The record supports the sham-redundancy finding but no six-ground enumeration was located; the count "six" is the entity's construction. Scalar path: sources[0].note.
Decision: uncorroborated

## Claim 8: scalar:sources[0].note — "all twelve interim orders"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: "13 orders numbered 1-13 (using Arabic numerals): '1. That pending the hearing…' through '13. As the file was before this Court…'"
Comparison: The disposition enumerates thirteen orders (order 12 is costs, order 13 case-management). "Twelve interim orders" is reachable only under one exclusion reading (orders 1–12 excluding the mention direction); the count is ambiguous rather than confirmed. Scalar path: sources[0].note. See Claim 28.
Decision: uncorroborated

## Claim 9: scalar:sources[1].note — Foxglove post: "explosive potential consequences", six-day pause expiring 8 June 2023

Source: https://www.foxglove.org.uk/2023/06/06/kenyan-court-ruling-outsourced-content-moderation-facebook/
Source tier: primary
Source content: "And it is one with explosive potential consequences."; "The judge granted Facebook and Sama a six-day pause to study the ruling before it comes into effect" (expiring June 8, 2023); post dated 06.06.2023.
Comparison: Every element of the note verified against the cited post itself.
Decision: primary-sourced

## Claim 10: scalar:sources[3].note — CorpWatch as "primary source for … the 5th applicant's verbatim testimony on moderating Ethio-Tigray war content ('my life will never be the same again')"

Source: https://www.corpwatch.org/article/kenyan-court-orders-facebook-moderation-contractor-pay-its-workers-back-wages
Source tier: primary
Source content: Two targeted reads of the article: "The article does not mention Fasica, a fifth applicant/petitioner, testimony about Ethiopian Tigray war content, or the quote 'my life will never be the same again.'" The article does carry the 184 figure and back-wages/blacklisting coverage: "184 workers sued Sama for not giving them the required 30-day notice and for blacklisting them".
Comparison: The note's 184-figure and back-wages attributions check out, but the testimony attribution is contradicted by the article's own content — the testimony lives in the Kenya Law judgment (Fasica Berhane Gebrekidan, ¶56–84, quote at ¶64), not in CorpWatch. Scalar path: sources[3].note — fix is reattributing/removing the testimony clause (prose judgment; Editor should [editor-flag] to Researcher).
Decision: correction

## Claim 11: scalar:sources[4].note — BHRRC tracker chronology (March 2023 filing through February 2026 postponement)

Source: https://www.business-humanrights.org/en/latest-news/kenya-content-moderators-filed-a-lawsuit-against-meta-alleging-poor-working-conditions-including-insufficient-mental-health-support-and-low-pay/
Source tier: database
Source content: "The case was brought before Kenyan court in March 2023"; "On February 12, 2026, a judge…postponed rulings in a case brought by former content moderator Daniel Motaung and in a second case brought by a group of former content moderators."
Comparison: The tracker does carry the chronology the note claims, verified against the tracker itself.
Decision: single-source

## Claim 12: "holding, in Paragraph 29, that Meta Platforms Inc and Meta Platforms Ireland Ltd were 'the primary or principal employers of the applicants' and that Samasource… was 'merely the agent, foreman, manager or factor'" (Judge Byram Ongaya, 2 June 2023, Petition E052 of 2023)

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Paragraph 29: "the 1st and 2nd respondents were the primary or principal employers of the applicants and the 3rd respondent was merely the agent, foreman, manager or factor" (1st = Meta Platforms Inc, 2nd = Meta Platforms Ireland Ltd, 3rd = Samasource); Foxglove: "Judge Byram Ongaya ruled that Facebook is the 'true employer' of its content moderators in Kenya – not Sama".
Comparison: Quotes verbatim; attribution of the employer/agent roles to the correct parties; judge name and case citation match (judgment record + Foxglove + indconlawphil).
Decision: corroborated

## Claim 13: Foxglove "framed the decision as having 'explosive potential consequences'"

Source: https://www.foxglove.org.uk/2023/06/06/kenyan-court-ruling-outsourced-content-moderation-facebook/
Source tier: primary
Source content: "And it is one with explosive potential consequences."
Comparison: Verbatim quote confirmed in the cited post (an initial summarizer read missed it; a targeted exact-phrase read found it).
Decision: primary-sourced

## Claim 14: January 2023 Sama redundancies — "roughly 260 Nairobi-based Facebook content moderators redundant after Meta terminated its moderation contract with Sama and transferred the work to Majorel"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Judgment references "260 content moderators are set to lose their jobs"; Rest of World: Sama "cut its entire 260-person moderation team"; Wikipedia (Malgwi): "the company ended its contract with Meta, making Malgwi and approximately 260 colleagues redundant".
Comparison: The ~260 figure and the Sama→Majorel transfer are consistently reported across the record and mainstream coverage.
Decision: corroborated

## Claim 15: "On 17 March 2023 Kiana Monique Arendse, a former Sama moderator, filed the petition"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Judgment: "application dated 17.03.2023"; 1st applicant Kiana Monique Arendse; BHRRC: "The case was brought before Kenyan court in March 2023" by 43 moderators.
Comparison: Filing date and first-named petitioner match the record and the tracker.
Decision: corroborated

## Claim 16: "against Samasource Kenya EPZ Ltd as 1st Respondent, Meta Platforms Inc as 2nd Respondent, Meta Platforms Ireland Ltd as 3rd Respondent, and Majorel as 4th Respondent" (and "The 2nd respondent (Meta)" in the orders list)

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Case caption: "1st Respondent: Meta Platforms, Inc; 2nd Respondent: Meta Platforms Ireland Limited; 3rd Respondent: Samasource Kenya Epz Limited t/a Sama; 4th Respondent: Majorel Kenya Limited." Case name: "Arendse & 42 others v Meta Platforms, Inc & 3 others."
Comparison: The body's respondent numbering is wrong for three of four parties. Correct replacement: Meta Platforms Inc 1st, Meta Platforms Ireland Ltd 2nd, Samasource Kenya EPZ Ltd 3rd, Majorel 4th. (This numbering error also breaks the body's Paragraph 29 pairing — the judgment's "1st and 2nd respondents" as employers / "3rd respondent" as agent only reads correctly with the true ordering — and the orders-list gloss "The 2nd respondent (Meta)": the restraint on engaging replacements runs against the 1st and 2nd respondents, Meta Inc and Meta Ireland.)
Decision: correction

## Claim 17: the petition was "the only of the two parallel Nairobi petitions to join Meta's incoming outsourcer as a named respondent"

Source: https://new.kenyalaw.org/akn/ke/judgment/keca/2023/996/eng@2023-07-28
Source tier: primary
Source content: E071 of 2022 (Motaung): "sued Samasource Kenya Epz Limited T/a Sama… and Meta Platforms, Inc and Meta Platforms Ireland Limited" — no Majorel; E052 of 2023 caption includes Majorel Kenya Limited as 4th respondent.
Comparison: Confirmed by the two Kenya Law captions — only E052 names Majorel.
Decision: corroborated

## Claim 18: "By 13 April 2023 a further 184 petitioners had been joined by court order"

Source: https://www.business-humanrights.org/en/latest-news/kenya-content-moderators-filed-a-lawsuit-against-meta-alleging-poor-working-conditions-including-insufficient-mental-health-support-and-low-pay/
Source tier: database
Source content: "The ruling came after 43 moderators…filed a lawsuit…The moderators, who are now 184 in number"; TechCrunch (11 May 2023, search snippet): court "instructed Sama to pay the April salaries to the 184 former content moderators".
Comparison: 184 is the case's TOTAL petitioner count after joinder (43 filers expanding to 184), not the number of additional joiners — "a further 184" would imply 227 total. Correct replacement: "a further 141 petitioners had been joined…, bringing the total to 184". The "13 April 2023" date was not confirmed in any fetched source (the judgment's targeted read found no 13.04.2023 joinder reference; BHRRC ties the 184 figure to the 20 April jurisdiction ruling).
Decision: correction

## Claim 19: "briefed by Mercy Mutemi of Nzili & Sumbi Advocates with Foxglove as international partner — the same Foxglove–Nzili & Sumbi architecture… [as] the Motaung petition"

Source: https://www.foxglove.org.uk/2023/06/06/kenyan-court-ruling-outsourced-content-moderation-facebook/
Source tier: primary
Source content: Foxglove's post on its own role in the case; TechPolicy.Press/AFP: moderators "consult with their lawyer, Mercy Mutemi"; Time/openDemocracy coverage of the Motaung case names the same Mutemi–Foxglove pairing.
Comparison: Counsel and partnership structure consistently confirmed across party and mainstream sources for both petitions.
Decision: corroborated

## Claim 20: union founding vote "at the Mövenpick Hotel on 1 May 2023 — thirty-two days before Judge Ongaya's ruling"

Source: https://time.com/6275995/chatgpt-facebook-african-workers-union/
Source tier: mainstream
Source content: "On May 1, 2023, more than 150 workers gathered at the Mövenpick Hotel in Nairobi and voted to establish the African Content Moderators Union."
Comparison: Venue and date confirmed (Time + Foxglove's summit post); 1 May → 2 June is 32 days — arithmetic checks.
Decision: corroborated

## Claim 21: control facts — Meta "owned the job"; SRT proprietary platform; community guidelines as standards; "tickets" as units of work; performance metrics governing contracts

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: "The Court returns that it is the 1st and 2nd respondents who owned the job and therefore had the obligation to provide the job." (¶29); "Through the SRT the 1st and 2nd respondents were able to…issue the content moderators with tickets…the Facebook Community Standards; issue them with performance metrics…the average handling time and the accuracy metrics"; indconlawphil concurs on all four control facts.
Comparison: All control facts verbatim-confirmed in the record and corroborated by the cited academic analysis. (Judgment says "Facebook Community Standards"; body's "community guidelines" is a fair paraphrase.)
Decision: corroborated

## Claim 22: "Article 41 of the Kenyan Constitution — guaranteeing fair labour practices — could not be defeated by the contractual arrangement"

Source: https://indconlawphil.wordpress.com/2023/06/09/meta-labour-law-and-the-constitution-the-judgment-of-the-kenyan-employment-and-labour-relations-court/
Source tier: mainstream
Source content: Article 41 establishes "a constitutional right to fair labour practices" and the court held that "contractual arrangements cannot be used to defeat these guarantees".
Comparison: Matches the cited analysis; targeted reads of the judgment could not confirm the Article-41-specific passage directly (the record's constitutional discussion was returned under other articles), so support rests on the one cited analysis.
Decision: single-source

## Claim 23: affidavit strikes — Meta's "futuristic jurat date"; Samasource's and Majorel's "commissioners whose valid practising certificates could not be established"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Redmond affidavit (Meta) struck — "futuristic date went 'to the root' of affidavit's validity" (sworn 08.06.2023, filed 09.05.2023); Alwala affidavits (Sama) and De Cauter affidavits (Majorel) struck — commissioned by advocates "without valid 2023 practicing certificate".
Comparison: Both strike grounds match the record exactly.
Decision: primary-sourced

## Claim 24: "The respondents' principal evidentiary submissions were accordingly excluded from the record before the court ruled"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: "Annpeace Alwala (3rd respondent, 11.05.2023)… Allowed — filed with leave per 27.04.2023 order; no prejudice given applicants' extensive response."
Comparison: Overstated: Sama's replacement affidavit was allowed and remained on the record, so not all principal evidentiary submissions were excluded. Not a single-token fix — prose-level qualification needed.
Decision: uncorroborated

## Claim 25: "The court identified six distinct grounds on which it found the declared redundancy a sham"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: "The judgment does not explicitly enumerate six grounds in a single passage." The individual grounds are supported: work remained available ("cannot be redundant as such because the survival of social media platforms largely depends on the content moderators"), contradictory explanations, Majorel engaged for identical work, blacklisting ("recruiters' texts revealed there was an effective blacklist" — Foxglove), Motaung timing ("The redundancy was calculated to get rid of the applicants").
Comparison: The substance of each listed ground is record-supported, but the "six distinct grounds" enumeration attributed to the court was not located; the count is the entity's construction.
Decision: uncorroborated

## Claim 26: "The court also found that the work of content moderation was 'inherently hazardous with serious mental health impacts'"

Source: https://www.foxglove.org.uk/2023/06/06/kenyan-court-ruling-outsourced-content-moderation-facebook/
Source tier: primary
Source content: Foxglove presents it as a court finding: the Court finds the work of content moderation "inherently hazardous with serious mental health impacts". Three targeted reads of the Kenya Law record did not locate the word "hazardous" ("No sentences containing the word 'hazardous' appear in this judgment text").
Comparison: The cited party source quotes the phrase as court text but the primary record could not confirm it (possible fetch truncation of a long judgment, or Foxglove paraphrase); sources conflict, so the verbatim attribution to the court stands unconfirmed.
Decision: uncorroborated

## Claim 27: 5th applicant's testimony — moderating Ethio-Tigray war content, "my life will never be the same again"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Fasica Berhane Gebrekidan (5th applicant), supporting affidavit ¶56–84: reviewed "graphic videos back-to-back from the Ethio-Tigray war"; "my life will never be the same again" (¶64).
Comparison: Testimony content and quote confirmed in the judgment record. (The body hyperlinks this to CorpWatch, which does not carry the testimony — see Claim 10.)
Decision: primary-sourced

## Claim 28: "The ruling issued twelve interim orders"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: "13 orders numbered 1-13": injunctive/directive orders 1–11, costs at 12 ("jointly or severally pay the costs of the application"), case-management mention at 13.
Comparison: The disposition enumerates thirteen orders. "Twelve" is reachable only by excluding the mention direction while counting costs — a defensible but unconfirmed counting convention; no source states twelve.
Decision: uncorroborated

## Claim 29: the seven listed principal orders (restraint on redundancy; contract extension; restraint on engaging Majorel replacements unless applicants retained; no recruitment refusal based on prior Sama employment; no retaliation; "proper medical, psychiatric and psychological care"; immigration regularisation)

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Orders include restraint on redundancy implementation; extension of lapsing contracts; Meta/Meta Ireland "cannot engage new moderators via Majorel or others… unless applicants retained on same/better terms"; Majorel "cannot refuse recruitment based on prior Sama employment"; no retaliation; "an order compelling the 1st, 2nd and 3rd respondents to provide proper medical, psychiatric and psychological care for the petitioners… in place of 'wellness counselling'"; immigration-status regularisation and deportation protection.
Comparison: All seven orders match the record; the medical-care quote is verbatim. (The "(2nd respondent (Meta))" gloss in item 3 is covered by the Claim 16 correction.)
Decision: primary-sourced

## Claim 30: "Five interested parties — the Kenya Human Rights Commission, the Attorney General, the Ministry of Labour Social Security and Services, the Ministry of Health, and the Ministry of Foreign Affairs — were directed to report"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Order 9: "the 4th, 5th, 6th, 7th, and 8th interested parties shall review the status of the law and policy for protection of employees' occupational safety and health…" — i.e. the Kenya National Human Rights and Equality Commission (4th), Central Organisation of Trade Unions (5th), Attorney General (6th), Ministry of Labour Social Security and Services (7th), Ministry of Health (8th). The Kenya Human Rights Commission is the 1st interested party and the Ministry of Foreign Affairs the 9th — neither is in the directive.
Comparison: Count of five is right; two members are wrong. Correct replacement: "Kenya Human Rights Commission" → "Kenya National Human Rights and Equality Commission", and "Ministry of Foreign Affairs" → "Central Organisation of Trade Unions".
Decision: correction

## Claim 31: directed review of law and policy for occupational safety and health "in the sector of 'virtual or digital work'"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: Order directing review of "occupational safety and health in the sector of virtual or digital work, digital workspaces, and digital workplace".
Comparison: Quoted phrase verbatim in the order.
Decision: primary-sourced

## Claim 32: "Costs were awarded to the applicants" and the court "encouraged the parties to pursue alternative dispute resolution"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/1398/eng@2023-06-02
Source tier: primary
Source content: "1st, 2nd and 3rd respondents ordered to 'jointly or severally pay the costs of the application'"; ADR order: "parties encouraged to pursue negotiation, conciliation, or mediation".
Comparison: Both match the record.
Decision: primary-sourced

## Claim 33: "A six-day pause before the orders took effect — expiring 8 June 2023"

Source: https://www.foxglove.org.uk/2023/06/06/kenyan-court-ruling-outsourced-content-moderation-facebook/
Source tier: primary
Source content: "The judge granted Facebook and Sama a six-day pause to study the ruling before it comes into effect," expiring June 8, 2023.
Comparison: Matches the cited Foxglove post exactly (the body attributes the specific to Foxglove); the judgment's disposition text itself carries no grace period, so support rests on the party's contemporaneous account.
Decision: primary-sourced

## Claim 34: "the June 2022 refusal of Meta's gag-order application against Daniel Motaung"

Source: https://time.com/6253180/meta-kenya-lawsuit-motaung/
Source tier: mainstream
Source content: "In a court hearing one month later [after the May 2022 filing], lawyers for Facebook and Sama called for a gag order on Motaung… The judge refused to grant the gagging order."
Comparison: Confirmed by Time and openDemocracy coverage of the Motaung case.
Decision: corroborated

## Claim 35: "the 6 February 2023 ruling in Petition E071 of 2022 that Meta was a 'proper party'"

Source: https://new.kenyalaw.org/akn/ke/judgment/keelrc/2023/320/eng@2023-02-06
Source tier: primary
Source content: Kenya Law: "Motaung v Samasource Kenya EPZ Limited t/a Sama & 2 others (Petition E071 of 2022) [2023] KEELRC 320 (KLR) (6 February 2023) (Ruling)"; Time: "A judge in Nairobi's employment and labor relations court ruled… that Meta is a 'proper party' to the case" (6 February 2023).
Comparison: Case number, date, and holding all confirmed (Kenya Law citation + Time).
Decision: corroborated

## Claim 36: "the 20 April 2023 dismissal of a further Meta jurisdictional challenge"

Source: https://www.aljazeera.com/news/2023/4/20/court-rules-meta-can-be-sued-in-kenya-over-alleged-unlawful-redundancies
Source tier: mainstream
Source content: Al Jazeera (20 April 2023): "Court rules Meta can be sued in Kenya over alleged unlawful redundancies"; BHRRC: "On April 20, 2023, a Kenyan judge ruled the court had jurisdiction".
Comparison: Date and outcome confirmed by mainstream coverage and the BHRRC tracker.
Decision: corroborated

## Claim 37: "the July 2023 Court of Appeal dismissal of Meta's stay application"

Source: https://new.kenyalaw.org/akn/ke/judgment/keca/2023/996/eng@2023-07-28
Source tier: primary
Source content: Meta Platforms, Inc & another v Motaung & another (Civil Appeal (Application) E232 of 2023) [2023] KECA 996 (KLR) (28 July 2023): Meta sought to "stay further proceedings in ELRC No E071 of 2022…pending the hearing and determination of this appeal"; "the application dated 27th April 2023 is dismissed with costs".
Comparison: A July 2023 Court of Appeal dismissal of Meta's stay application exists and is confirmed — but that ruling arises from the Motaung petition (E071), while the body's sentence situates it in this campaign's (E052) arc. The date/court/outcome tokens are record-confirmed; the case-scoping is an ambiguity for the Editor/Researcher to note, not a token error.
Decision: primary-sourced

## Claim 38: "It is the first ruling in the Kenyan courts to make a substantive finding on the labour-side of the… Nairobi accountability cluster" / "the first time a Kenyan court went beyond… and addressed who Meta was, in law, to the workers"

Source: no canonical source found
Source tier: none
Source content: No fetched source asserts the "first" characterization; the documented sequence (procedural rulings of June 2022, 6 February 2023, 20 April 2023 preceding this substantive finding) is consistent with it but no source states it.
Comparison: Contested-first claim (Wikipedia-tiebreaker-only class); defensible from the verified timeline but externally unattested.
Decision: uncorroborated

## Claim 39: Kauna Malgwi — "Nigerian clinical psychologist whose four-year Sama tenure had ended in the January redundancies… was among the petitioners"

Source: https://en.wikipedia.org/wiki/Kauna_Malgwi
Source tier: mainstream
Source content: Wikipedia: "Kauna Ibrahim Malgwi… is a Nigerian clinical psychologist"; "In 2019, Malgwi began working for Sama"; redundancy with "approximately 260 colleagues"; "Malgwi became one of 185 former content moderators bringing a legal challenge against Meta and Sama in Kenyan courts." Rest of World and Time (TIME100 AI 2024) confirm the psychologist background, 2019 start, and union role.
Comparison: All profile specifics confirmed by ≥2 mainstream sources (Wikipedia serving as tiebreaker alongside Rest of World/Time/Computer Weekly, per the living-person rule).
Decision: corroborated

## Claim 40: Malgwi "was present at the union founding vote the month before"

Source: no canonical source found
Source tier: none
Source content: Wikipedia: no information on her presence at the 1 May 2023 Mövenpick meeting; Time's founding-vote report does not name her among attendees in fetched content.
Comparison: Her union chapter leadership is confirmed, but no fetched source places her at the 1 May 2023 founding vote specifically.
Decision: uncorroborated
