---
entity_id: camp-masaar-egypt-digital-surveillance-2020-ongoing
entity_hash: 03848f4e7b72923ece16e8c6257db75fdaa65699
audit_date: 2026-07-04
pass: 1
status: corrections-pending
claims_total: 30
claims_corroborated: 12
claims_primary_sourced: 10
claims_single_source: 1
claims_uncorroborated: 2
open_corrections: 5
sources_consulted:
  - https://ifex.org/human-rights-organizations-call-on-egypts-government-to-end-internet-censorship-and-website-blocking/
  - https://africandefenders.org/egypt-government-called-on-to-end-internet-censorship-and-website-blocking/
  - https://www.accessnow.org/new-middle-east-and-north-africa-coalition-to-combat-digital-surveillance/
  - https://www.anhri.info/?p=18965&lang=en
  - https://citizenlab.ca/2018/03/bad-traffic-sandvines-packetlogic-devices-deploy-government-spyware-turkey-syria/
  - https://www.qurium.org/alerts/egypt/how-operators-use-sandvine-to-block-independent-media-in-egypt/
  - https://ooni.org/post/2019-egypt-blocks-bbc-and-alhurra
  - https://masaar.net/en/about-us/
  - https://masaar.net/en/surveillance-companies-in-the-mena-region/
  - https://masaar.net/en/wasl-newsletter-the-second-issue
  - https://masaar.net/en/court-of-cassation-rules-against-expansive-use-of-website-blocking/
  - https://masaar.net/en/data-protection-center-masaars-proposal-on-the-executive-regulations-for-the-data-protection-law/
  - https://masaar.net/en/the-opportunities-and-challenges-in-using-strategic-litigation-to-defend-digital-rights/
  - https://masaar.net/en/press-and-human-rights-websites-blocked-in-egypt-using-sandvine-equipment/
  - https://manassa.news/en/news/29826
  - https://www.bakermckenzie.com/en/insight/publications/2026/01/egypt-important-data-protection-update
  - https://practiceguides.chambers.com/practice-guides/data-protection-privacy-2026/egypt
  - https://www.loc.gov/item/global-legal-monitor/2018-10-05/egypt-president-ratifies-anti-cybercrime-law/
  - https://ppc.land/egypt-finally-implements-data-protection-law-after-five-year-delay/
---

Fetch note: masaar.net, article19.org, smex.org, cihrs.org 403 on direct fetch; ooni.org/partners/ 429 (3 attempts). masaar.net and ooni.org content reached via search-mediated summaries of the same URLs; comparisons below name where a source was search-mediated rather than direct-fetched. web.archive.org fetch is harness-blocked.

## Claim 1: edge lead_orgs: org-masaar

Source: https://www.anhri.info/?p=18965&lang=en ; https://www.accessnow.org/new-middle-east-and-north-africa-coalition-to-combat-digital-surveillance/ ; https://www.qurium.org/alerts/egypt/how-operators-use-sandvine-to-block-independent-media-in-egypt/
Source tier: primary
Source content: ANHRI launch: campaign launched jointly by ANHRI and "Masaar"; Access Now: "Masaar – Technology and Law Community" founding coalition member; Qurium media-coverage section credits Masaar's Sandvine article.
Comparison: Every documented campaign activity (Stop the Block, Sandvine exposure, coalition co-founding, litigation, PDPL analysis) is attributed to Masaar by independent sources; the edge points at the correct entity.
Decision: corroborated

## Claim 2: edges participating_orgs: org-access-now, org-article-19, org-smex

Source: https://www.accessnow.org/new-middle-east-and-north-africa-coalition-to-combat-digital-surveillance/ ; https://africandefenders.org/egypt-government-called-on-to-end-internet-censorship-and-website-blocking/
Source tier: primary
Source content: Coalition founding members include "Access Now", "ARTICLE19", "SMEX", "Masaar – Technology and Law Community"; joint-statement signatories include Access Now, ARTICLE 19, SMEX, Masaar.
Decision: corroborated
Comparison: All three participating-org edges are co-members of the MENA Coalition and co-signatories of the joint statement alongside Masaar; edges point at the correct entities.

## Claim 3: "launched its sustained campaign ... in 2020" (start_date: 2020)

Source: https://www.anhri.info/?p=18965&lang=en ; https://masaar.net/en/wasl-newsletter-the-second-issue (search-mediated)
Source tier: primary
Source content: ANHRI: "Campaign Launch Date: September 20, 2020" (Stop the Block); Wasl newsletter: Article 25 unconstitutionality memorandum filed in "case No. 246 of 2020".
Comparison: The campaign's earliest documented components (Stop the Block, the Art. 25 memorandum) date to 2020, matching start_date and the body's launch year.
Decision: corroborated

## Claim 4: "Egypt enacted a Personal Data Protection Law (Law 151/2020) in the same year Masaar formed" (Masaar formed 2020)

Source: https://masaar.net/en/about-us/ (search-mediated)
Source tier: primary
Source content: "Masaar is a human rights organization founded in 2020, specialized in digital rights and related freedoms."
Comparison: Masaar's own about page gives 2020, matching the body's implication. Note: the corpus's org-masaar frontmatter carries `founded: 2021` (possibly the Estonian MTÜ legal registration) — a cross-entity inconsistency for org-masaar's audit, not a defect in this body claim, which matches the entity's own primary source.
Decision: primary-sourced

## Claim 5: "mass blocking wave that had struck Egyptian ... websites since May 2017"

Source: https://ifex.org/human-rights-organizations-call-on-egypts-government-to-end-internet-censorship-and-website-blocking/ ; https://www.anhri.info/?p=18965&lang=en
Source tier: primary
Source content: IFEX statement condemns "the blocking of at least 600 websites since May 2017"; ANHRI: "the authorities launched a massive wave of website blocking in May 2017 and it is still underway."
Comparison: May 2017 as the onset of mass blocking matches both sources.
Decision: corroborated

## Claim 6: "Article 7 of the Cybercrime Law grants competent investigation bodies the right to order website blocks"

Source: https://masaar.net/en/court-of-cassation-rules-against-expansive-use-of-website-blocking/ (search-mediated) ; https://www.loc.gov/item/global-legal-monitor/2018-10-05/egypt-president-ratifies-anti-cybercrime-law/
Source tier: primary
Source content: "Under Article 7 of the Cybercrime Law, websites can only be blocked if the Public Prosecution or an investigating judge issues a judicial order as part of a criminal investigation."
Comparison: Body's summary of Art. 7 blocking authority matches Masaar's legal analysis and law coverage.
Decision: corroborated

## Claim 7: "Article 2 requires service providers to retain communications records for 180 consecutive days"

Source: https://www.loc.gov/item/global-legal-monitor/2018-10-05/egypt-president-ratifies-anti-cybercrime-law/ ; https://iclg.com/practice-areas/data-protection-laws-and-regulations/egypt/
Source tier: primary
Source content: "Article 2 of Law No. 175 requires telecommunications companies to retain and store users' data for 180 days"; "service providers to store user data on the user's online activity for a 180-day period."
Comparison: Article number and 180-day retention period match; body's "consecutive" matches the law's continuous-period phrasing in translations.
Decision: corroborated

## Claim 8: Sandvine PacketLogic DPI deployed at the Telecom Egypt chokepoint (technical layer)

Source: https://www.qurium.org/alerts/egypt/how-operators-use-sandvine-to-block-independent-media-in-egypt/ ; https://citizenlab.ca/2018/03/bad-traffic-sandvines-packetlogic-devices-deploy-government-spyware-turkey-syria/
Source tier: primary
Source content: Qurium: "For TE-Data, we have estimated that 3/4 of the connections/flows are teared down by Sandvine"; ISPs confirmed using Sandvine: Telecom Egypt (state-owned), Orange Egypt. Citizen Lab (2018) documented Sandvine PacketLogic middleboxes on Egyptian networks.
Comparison: Sandvine DPI on Telecom Egypt infrastructure confirmed by two independent technical investigations.
Decision: corroborated

## Claim 9: OONI research partnership; Masaar contributes to the Egyptian website-testing list

Source: https://ooni.org/partners/masaar/ (page exists; content unfetchable this session — HTTP 429 on three attempts)
Source tier: database
Source content: Partner page title: "Masaar - Technology and Law Community | OONI" (via search index).
Comparison: The partnership is confirmed by the existence of Masaar's dedicated OONI partner page; the specific testing-list-contribution detail rests on that page's content, which could not be fetched this session.
Decision: single-source

## Claim 10: BBC and Alhurra blocked in September 2019 via DPI targeting TLS SNI fields

Source: https://ooni.org/post/2019-egypt-blocks-bbc-and-alhurra (search-mediated) ; https://www.vpncompare.co.uk/ooni-bbc-blocked-egypt/
Source tier: database
Source content: "both bbc.com and alhurra.com were blocked in Egypt on 22nd September 2019 ... DPI technology that is aware of TLS and which is most likely fingerprinting the SNI field of the TLS handshake ... strong indication that the blocking is happening by means of SNI filtering."
Comparison: Date (September 2019), targets (BBC, Alhurra), and mechanism (DPI on TLS SNI) all match OONI's published measurement report.
Decision: corroborated

## Claim 11: "In 2021, Masaar and the Arabic Network for Human Rights Information (ANHRI) jointly launched the 'Stop the Block' campaign"

Source: https://www.anhri.info/?p=18965&lang=en
Source tier: primary
Source content: Campaign launch date on the co-launcher's own announcement: "September 20, 2020". The IFEX joint statement in support of the campaign was published November 2020.
Comparison: The body's launch year "2021" contradicts the launch announcement's 2020 date; single correct replacement: 2020. Body-prose year token; mechanical fix.
Decision: correction

## Claim 12: 628 blocked URLs — 596 websites and 32 alternate domains

Source: https://www.anhri.info/?p=18965&lang=en ; https://masaar.net/en/anhri-masaar-launch-stop-the-block-campaign/ (search-mediated)
Source tier: primary
Source content: "The page contains 628 URLs that were blocked in Egypt, of which 596 websites, and 32 alternate domains that were used by the blocked websites to reach their audience."
Comparison: All three totals match exactly (628 = 596 + 32). ANHRI and Masaar are co-launchers publishing the same campaign documentation, so this is one primary source, not two independent ones.
Decision: primary-sourced

## Claim 13: category breakdown — 116 press/media, 349 VPN/proxy, 15 human rights, 27 political criticism, 8 blogs, 12 multimedia (body; also scalar:sources[0].note for 116/349/15/27)

Source: https://www.anhri.info/?p=18965&lang=en
Source tier: primary
Source content: "Press and media websites: 116; Proxy and VPN services: 349; Human rights websites: 15; Political criticism websites: 27; Blogs and blog hosting: 8; Multimedia sharing: 12."
Comparison: All six category counts in the body, and the four repeated in scalar:sources[0].note, match the campaign documentation exactly.
Decision: primary-sourced

## Claim 14: formal letters to the UN SR on Freedom of Expression, UN SR on Human Rights Defenders, UNESCO, NTRA, and SCMR (body; scalar:sources[0].note lists four of these)

Source: https://www.anhri.info/?p=18965&lang=en ; https://www.anhri.info/?p=18976&lang=en ; https://anhri.info/?lang=en&p=18981
Source tier: primary
Source content: Launch announcement names letters to "the UN Special Rapporteur on the Promotion and Protection of the Right to Freedom of Opinion and Expression, the Special Rapporteur on the Situation of Human Rights Defenders, ... UNESCO, the National Telecom Regulatory Authority (NTRA) and the Supreme Council for Media Regulation (SCMR)"; ANHRI separately published "A letter to the Supreme Council for Media Regulation submitted by [ANHRI] and ... Masaar" and "Letter to the National Telecommunications Regulatory Authority submitted by...".
Comparison: All five recipients match; the SCMR and NTRA letters are documented as actually submitted (published letter texts).
Decision: primary-sourced

## Claim 15: "A 29-organisation joint international statement" (body; also scalar:sources[1].note "the 29-organization joint statement" and outcomes "29-organisation international statement")

Source: https://ifex.org/human-rights-organizations-call-on-egypts-government-to-end-internet-censorship-and-website-blocking/ ; https://africandefenders.org/egypt-government-called-on-to-end-internet-censorship-and-website-blocking/
Source tier: primary
Source content: Two independent full enumerations of the statement's signatories (IFEX original and African Defenders republication) list the identical 28 organizations (Access Now, AFIC, ARTICLE 19, Bytes for All, CIHRS, CRNI, Derechos Civiles, EFF, EuroMed Rights, Free Media Movement, Globe International Center, GCHR, IFoX, IPI, Maharat, Masaar, MEAA, MFWA, MISA, PEN Canada, PEN Norway, SMEX, ANHRI, EHRF, Tunisian Committee, AMARC, Egyptian Front for Human Rights, CFJ).
Comparison: The signatory count is 28, not 29, on both enumerations (which agree name-for-name). Token fix in three locations: body prose, scalar:sources[1].note, and the outcomes frontmatter scalar. 29 → 28.
Decision: correction

## Claim 16: "In March 2018, Citizen Lab published the first report revealing Sandvine devices in Egypt being used to redirect users across multiple ISPs for cryptocurrency mining and to deliver nation-state malware"

Source: https://citizenlab.ca/2018/03/bad-traffic-sandvines-packetlogic-devices-deploy-government-spyware-turkey-syria/
Source tier: primary
Source content: Report (published March 9, 2018): "The middleboxes were being used to hijack Egyptian Internet users' unencrypted web connections en masse, and redirect the users to revenue-generating content such as affiliate ads and browser cryptocurrency mining scripts." The report's malware-injection findings (StrongPity/FinFisher spyware) were documented in Turkey and Syria, NOT Egypt; scanning for FinFisher injection in Egypt was unsuccessful.
Comparison: Date (March 2018) and cryptocurrency-mining redirection match, but "and to deliver nation-state malware" contradicts the source for Egypt — spyware delivery was the Turkey/Syria finding. Replacement: the Egypt finding was redirection to affiliate ads and cryptomining scripts (AdHose); nation-state spyware delivery was documented in Turkey/Syria. Correction spans a clause, so it likely needs the Editor's prose-judgment flag to the Researcher rather than a single-token backfill.
Decision: correction

## Claim 17: "In October 2020, Egyptian authorities were confirmed to be using Sandvine devices to block at least 600 websites, including 100 independent news and media sites" (body; also scalar:sources[3].note "the October 2020 confirmation of Sandvine blocking 600 websites including 100 independent news sites")

Source: https://www.qurium.org/alerts/egypt/how-operators-use-sandvine-to-block-independent-media-in-egypt/
Source tier: database
Source content: Qurium's forensic confirmation is dated "21 September 2020": "more than 600 websites are blocked ... more than hundred of those are media and news websites." Qurium's media-coverage section dates Masaar's companion article ("Sandvine. The surveillance octopus in the Arab region") to 24 Sept 2020.
Comparison: The 600-website / 100-news-site figures match, but the confirmation dates to September 2020, not October 2020; no source supporting an October date was found. Month token fix in body and scalar:sources[3].note: October 2020 → September 2020. (Residual caveat: the English version of Masaar's octopus page could carry an October date — the page itself was unfetchable — but the confirmation event the sentence describes is Qurium's September investigation.)
Decision: correction

## Claim 18: Masaar testing found 15 of 20 sampled blocked news and human-rights websites blocked using Sandvine equipment, including Mada Masr and HRW's Egypt page (body; also scalar:sources[2].note)

Source: https://masaar.net/en/press-and-human-rights-websites-blocked-in-egypt-using-sandvine-equipment/ (search-mediated)
Source tier: primary
Source content: "finding that 15 of 20 websites in their test sample had been blocked by Sandvine equipment ... tests on the Internet service provided by WE network (AS8452) ... The websites targeted included Human Rights Watch, Reporters Without Borders, Al Jazeera, and Mada Masr."
Comparison: The 15-of-20 figure and the named examples (Mada Masr, HRW) match Masaar's own report.
Decision: primary-sourced

## Claim 19: octopus report "situates Egypt's Sandvine deployment inside a regional pattern across 50+ MENA countries" (body; also scalar:sources[3].note "Sandvine's operations across 50+ MENA countries")

Source: https://masaar.net/en/surveillance-companies-in-the-mena-region/ (search-mediated)
Source tier: primary
Source content: "Sandvine runs its operations in more than 50 countries, some of them Middle Eastern and North African countries."
Comparison: Masaar's own profile says Sandvine operates in 50+ countries GLOBALLY, some of which are MENA countries — not "50+ MENA countries" (the MENA region does not contain 50 countries). Token fix in body and scalar:sources[3].note: "50+ MENA countries" → "50+ countries, including MENA countries" (or equivalent).
Decision: correction

## Claim 20: surveillance-companies file profiles seven companies — NSO Group, Gamma Group, Blue Coat, Sandvine, Hacking Team, Candiru, Circles (body; also scalar:sources[4].note)

Source: https://masaar.net/en/surveillance-companies-in-the-mena-region/ (search-mediated)
Source tier: primary
Source content: "The publication covers 7 companies: NSO Group, Gamma Group, Blue Coat and also includes coverage of Sandvine, Hacking Team, Candiru, and Circles."
Comparison: The seven-company list matches exactly, name for name.
Decision: primary-sourced

## Claim 21: MENA Coalition to Combat Digital Surveillance co-founded June 7, 2021 at RightsCon; 12 founding members as listed; goal of ending surveillance-tool sales to repressive MENA governments (body; also scalar:sources[5].note and outcomes)

Source: https://www.accessnow.org/new-middle-east-and-north-africa-coalition-to-combat-digital-surveillance/
Source tier: primary
Source content: "officially launched on June 7, 2021, during a public session at RightsCon"; founding members: Access Now, ARTICLE19, CPJ, Front Line Defenders, GCHR, HRW, INSM, JOSA, Masaar, Red Line for Gulf, RSF, SMEX; goals: "end the sales of digital surveillance tools to repressive governments in the region, fight for a safe and open internet, defend human rights, and protect human rights defenders, journalists, and internet users from governments' prying eyes."
Comparison: Date, venue, all twelve founding members, and stated goals match the co-founder's announcement exactly. (Entity's expansion of INSM as "Iraq Network for Social Media" vs. Access Now's "Iraqi Network for Social Media" is not a factual divergence.)
Decision: primary-sourced

## Claim 22: "In 2020, Masaar filed a memorandum before Cairo's Misdemeanors Economic Court of Appeal arguing for the unconstitutionality of Article 25 of Law 175/2018" (body; also outcomes "Article 25 of Law 175/2018")

Source: https://masaar.net/en/wasl-newsletter-the-second-issue (search-mediated)
Source tier: primary
Source content: "Masaar filed a memorandum arguing for the unconstitutionality of Article 25 of law No. 175/2018 ... to Cairo's Misdemeanors Economic Court of Appeal ... in case No. 246 of 2020."
Comparison: Article number, law number, court, and 2020 dating (case No. 246 of 2020) all match Masaar's own account.
Decision: primary-sourced

## Claim 23: 2022 Court of Cassation ruling limited website-blocking authority to the NTRA; Ministry of Interior could not independently order/enforce blocks (body; also outcomes)

Source: https://masaar.net/en/court-of-cassation-rules-against-expansive-use-of-website-blocking/ (search-mediated) ; https://manassa.news/en/news/29826
Source tier: primary
Source content: "In 2022, the Court of Cassation issued a judgment that established clear limits: the Ministry of Interior has no legal capacity to enforce website blocking orders. That responsibility lies solely with the National Telecommunications Regulatory Authority (NTRA)"; Al Manassa: "Egypt court ruling limits Interior's online censorship powers, says rights group."
Comparison: Year, court, NTRA-only authority, and the MoI limitation match Masaar's analysis and independent news coverage.
Decision: corroborated

## Claim 24: Masaar's own assessment that blocking lawsuits "have clarified procedural aspects but have not produced radical policy change" with value in documentation, accountability, and legal-argument infrastructure

Source: https://masaar.net/en/the-opportunities-and-challenges-in-using-strategic-litigation-to-defend-digital-rights/ (search-mediated)
Source tier: primary
Source content: "Lawsuits filed to challenge website blocking decisions in Egypt have not successfully changed the public policy on blocking or overturned the laws upon which the authorities rely ... These lawsuits have ... documented violations, held authorities accountable, and provided legal arguments that could be referenced in the future."
Comparison: The attributed self-assessment matches the source's content on both the limits and the stated value of the litigation.
Decision: primary-sourced

## Claim 25: "Egypt enacted a Personal Data Protection Law (Law 151/2020) in [2020]"

Source: https://www.bakermckenzie.com/en/insight/publications/2026/01/egypt-important-data-protection-update ; https://practiceguides.chambers.com/practice-guides/data-protection-privacy-2026/egypt
Source tier: primary
Source content: "The PDPL was issued in July 2020" (Law No. 151 of 2020).
Comparison: Law number and 2020 enactment match multiple legal-practice sources; the law text itself is public record.
Decision: corroborated

## Claim 26: Masaar submitted formal proposals on the independence of the Personal Data Protection Center, recommending full independence from the executive branch (body; also outcomes)

Source: https://masaar.net/en/data-protection-center-masaars-proposal-on-the-executive-regulations-for-the-data-protection-law/ (search-mediated)
Source tier: primary
Source content: "Masaar proposes that the Personal Data Protection Law and its executive regulations should include rules ensuring the Center's complete legal independence from executive authority."
Comparison: The proposal's existence and its full-independence recommendation match Masaar's own publication.
Decision: primary-sourced

## Claim 27: February 2025 Alexandria Economic Court ruling ordering Orange Egypt to pay EGP 10 million over an unauthorized SIM replacement enabling WhatsApp takeover and extortion; framed as first significant judicial application of the PDPL against a telecom company (body; also outcomes and scalar:sources[8].note)

Source: https://practiceguides.chambers.com/practice-guides/data-protection-privacy-2026/egypt ; https://www.mondaq.com/data-protection/1752796/data-breach-real-consequences-egyptian-court-orders-egp-10-million-compensation-against-telecom-operator
Source tier: database
Source content: "In February 2025, the Alexandria Economic Court ordered Orange Egypt to pay EGP 10 million in compensation to a female customer whose personal data was compromised due to the company's unauthorized replacement of her SIM card, which allowed third parties to access her WhatsApp account and led to extortion attempts ... This marked the first judicial application of Egypt's Personal Data Protection Law."
Comparison: Date, court, amount, fact pattern, and the "first judicial application" framing all match independent legal coverage. (Chambers notes liability was grounded in general tort law given the then-absent regulations — consistent with the body's "first significant judicial application" framing, which is how Masaar and legal commentators described it.)
Decision: corroborated

## Claim 28: executive regulations not issued for five years after the law's passage; Minister of Telecommunications issued them in 2025 as Decree 816/2025 (body)

Source: https://www.bakermckenzie.com/en/insight/publications/2026/01/egypt-important-data-protection-update ; https://ppc.land/egypt-finally-implements-data-protection-law-after-five-year-delay/
Source tier: database
Source content: "Egypt's government issued the Executive Regulations to the Personal Data Protection Law (Law No. 151 of 2020) by virtue of Minister of Telecommunications Decree No. 816 of 2025 ... formally published on 1 November 2025"; "Egypt finally implements data protection law after five-year delay."
Comparison: Decree number, issuing minister, 2025 date, and the five-year gap all match multiple independent sources.
Decision: corroborated

## Claim 29: AI paper proposes "24+ governance principles" (body; also scalar:sources[9].note "the 24+ governance principles proposed")

Source: no canonical source found (https://masaar.net/en/regulating-artificial-intelligence-in-egypt-proposed-standards-and-principles/ unfetchable — HTTP 403; search-mediated summaries do not state a principle count)
Source tier: none
Source content: Search-mediated summaries of Masaar's AI-regulation work describe standards and red lines but give no count of principles.
Comparison: The "24+" count could not be confirmed or contradicted; the paper itself was unreachable this session. Not a finding of error — the count may well be accurate to the paper's structure.
Decision: uncorroborated

## Claim 30: AI paper's principles include prohibition of mass surveillance, prohibition of lethal autonomous weapons, non-discrimination, human oversight, and mandatory human-rights impact assessments (body; also scalar:sources[9].note)

Source: https://masaar.net/en/regulating-artificial-intelligence-in-egypt-proposed-standards-and-principles/ (search-mediated, partial)
Source tier: primary
Source content: "Masaar's explicit red lines prohibit behavioural manipulation, social-scoring and profiling, unrestricted facial recognition/biometric tracking, emotion-inference from private data, mass surveillance and lethal autonomous weapons ... insisting on human oversight, thorough documentation ... and impact assessments."
Comparison: Mass-surveillance and lethal-autonomous-weapons prohibitions and human oversight are confirmed in Masaar's AI-governance output, but the search-mediated summary may blend adjacent Masaar papers, and the non-discrimination and mandatory-HRIA items were not individually confirmable against the cited paper (unfetchable). Partial match on a judgment-loaded comparison.
Decision: uncorroborated
