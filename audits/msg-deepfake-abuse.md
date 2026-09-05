---
entity_id: msg-deepfake-abuse
entity_hash: 7ccae9145bd8a88a550a690984382a7a0aed59d2
audit_date: 2026-09-05
pass: 1
status: corrections-pending
claims_total: 35
claims_corroborated: 11
claims_primary_sourced: 11
claims_single_source: 2
claims_uncorroborated: 4
open_corrections: 7
sources_consulted:
  - https://keringfoundation.org/en/programs/korea-cyber-sexual-violence-response-center/
  - https://www.hrw.org/news/2024/08/29/south-koreas-digital-sex-crime-deepfake-crisis
  - https://news.un.org/feed/view/en/story/2026/02/1166886
  - https://www.endviolenceagainstwomen.org.uk/survivors-and-campaigners-welcome-new-deepfake-law-but-call-on-government-to-go-further/
  - https://en.wikipedia.org/wiki/TAKE_IT_DOWN_Act
  - https://www.koreatimes.co.kr/www/nation/2025/02/113_381432.html
  - https://montrealethics.ai/digital-sex-crime-online-misogyny-and-digital-feminism-in-south-Korea/
  - https://www.nprillinois.org/2024-09-06/south-korea-investigates-telegram-over-alleged-sexual-deepfakes
  - https://www.commerce.senate.gov/index.php/2025/5/sen-cruz-applauds-presidential-signing-of-the-take-it-down-act-into-law
  - https://www.commerce.senate.gov/meetings/field-hearing-take-it-down-ending-big-techs-complicity-in-revenge-porn/
  - https://www.korea.net/Government/Briefing-Room/Press-Releases/view?articleId=710468&type=N&insttCode=A260114
  - https://api.semanticscholar.org/graph/v1/paper/DOI:10.1080/01924036.2025.2596578
  - https://lens.monash.edu/@politics-society/2025/11/19/1388026/the-paradox-of-digital-safety-deepfakes-ai-and-gendered-risk-in-south-korea
  - https://www.voanews.com/amp/in-south-korea-deepfake-porn-wrecks-women-s-lives-deepens-gender-conflict/7810018.html
  - https://www.feministgiant.com/p/global-roundup-s-korea-women-protest
  - https://phys.org/news/2017-10-online-sex-crimes-high-tech-korea.html
  - https://cybercivilrights.org/about/
  - https://digitalrightsfoundation.pk/wp-content/uploads/2026/05/2025-Helpline-Annual-Report-1.pdf
  - https://www.cliffordchance.com/insights/resources/blogs/talking-tech/en/articles/2026/02/key-aspects-of-the-data--use-and-access--act-take-effect.html
  - https://www.congress.gov/crs-product/LSB11314
  - https://www.state.gov/report/custom/e152845032/
  - https://fortune.com/asia/2024/08/29/south-korea-deepfake-criminal-penalties-telegram
  - https://newlinesmag.com/reportage/the-gendered-battle-over-digital-sexual-abuse-in-south-korea/
---

## Claim 1: edge — propagated_by_orgs: org-digital-rights-foundation

Source: product/entities/organizations/org-digital-rights-foundation.md + https://digitalrightsfoundation.pk/wp-content/uploads/2026/05/2025-Helpline-Annual-Report-1.pdf (via search snippet)
Source tier: primary
Source content: DRF helpline manager on TFGBV evolution: "rising complaints of privacy violations via unregulated apps and the use of generative AI to produce non-consensual intimate images"
Comparison: Edge resolves (entity file exists) and DRF's own helpline reporting extends its TFGBV category to generative-AI NCII, matching the propagation claim; The Friday Times coverage ("AI Among Technologies Increasingly Used To Harass Women Online In Pakistan") independently confirms.
Decision: corroborated

## Claim 2: edge — related_messages: msg-feminist-ai

Source: product/entities/messages/msg-feminist-ai.md
Source tier: primary
Source content: Target file exists in corpus.
Comparison: Mechanical edge resolution — target entity present; thematic adjacency (feminist framing of AI harm) is consistent.
Decision: corroborated

## Claim 3: "UNICEF, INTERPOL, and ECPAT jointly launched the 'Deepfake abuse is abuse' campaign on 4 February 2026" with core claim "there is nothing fake about the harm it causes"

Source: https://news.un.org/feed/view/en/story/2026/02/1166886
Source tier: primary
Source content: Article dated 4 February 2026; "UNICEF led the initiative jointly with INTERPOL and ECPAT"; UNICEF emphasized that "there is nothing fake about the harm it causes."
Comparison: Launch date, three joint organisations, and the verbatim core quote all match. UN News is the UN's own outlet — primary for a UNICEF campaign. (The entity's cited ungeneva.org URL 302-redirects to this UN News story.)
Decision: primary-sourced

## Claim 4: "at least 1.2 million children had disclosed having their images manipulated into sexually explicit deepfakes in the prior year" across 11 countries; "roughly 1 in 25 children in some study countries"; three demands (expand CSAM definitions to AI-generated content; safety-by-design; strengthened platform moderation)

Source: https://news.un.org/feed/view/en/story/2026/02/1166886
Source tier: primary
Source content: "At least 1.2 million children across 11 countries reported having their images manipulated into sexually explicit deepfakes within the past year"; "approximately one in 25 children, described as 'the equivalent of one child in a typical classroom'"; demands: broaden CSAM definitions to encompass AI-generated content; "safety-by-design approaches with robust guardrails"; strengthen content moderation through detection technology investment.
Comparison: Figures, scope, and all three demands match body, origin scalar, and sources[2].note.
Decision: primary-sourced

## Claim 5: KCSVRC "established in 2017"

Source: https://keringfoundation.org/en/programs/korea-cyber-sexual-violence-response-center/
Source tier: primary
Source content: "Founding Year: 2017" ... "Since 2017, the center has supported 1,200 victims of cybersexual violence"
Comparison: Kering Foundation is KCSVRC's institutional funder; its program page is an official statement with direct program knowledge. AFP coverage of the center's activity from October 2017 (phys.org) is consistent but does not date the founding.
Decision: primary-sourced

## Claim 6: KCSVRC established "under Chairperson Yeojin Kim"

Source: https://phys.org/news/2017-10-online-sex-crimes-high-tech-korea.html + https://keringfoundation.org/en/programs/korea-cyber-sexual-violence-response-center/
Source tier: primary
Source content: Kering (undated, current): "Chairperson: Yeojin Kim". AFP via phys.org, October 2017: "Seo Lang, head of the campaign group" (in relation to the center's revenge-porn work).
Comparison: Kering lists Kim as chairperson but does not say she led at founding; a contemporaneous 2017 AFP report names a different head. The body/origin's temporal binding of Kim to the 2017 establishment cannot be confirmed and the sources are in tension — judgment-loaded edge.
Decision: uncorroborated

## Claim 7: KCSVRC systematically replaced "revenge porn" and "hidden camera" with "non-consensual distribution" and "illegal filming"

Source: https://keringfoundation.org/en/programs/korea-cyber-sexual-violence-response-center/
Source tier: primary
Source content: "KCSVRC replaced euphemistic terms 'revenge porn' and 'hidden camera' with 'illegal filming' and 'non-consensual distribution,' reframing these acts as violence rather than pornography."
Comparison: Exact match to body and origin scalar, including the violence-not-content reframing. Also covers sources[0].note's five-pillar paraphrase (Kering's five pillars — victim support, feminist-informed legal/policy reform, challenging perceptions, collaboration with women and minority groups, bridging movement generations — are loosely but not wrongly paraphrased in the note) and the 1,200-victims/86%-women figure, both confirmed verbatim.
Decision: primary-sourced

## Claim 8: KCSVRC's deletion-support process "became the prototype for" the National Digital Sexual Crime Victim Support Center

Source: https://keringfoundation.org/en/programs/korea-cyber-sexual-violence-response-center/
Source tier: primary
Source content: KCSVRC "developed a process for the deletion of non-consensual sexual content" that "became the prototype for the National Digital Sexual Crime Victim Support Center established in 2018."
Comparison: Verbatim match for the prototype claim. Only Kering asserts the prototype lineage, but it is a primary-tier source with direct program knowledge.
Decision: primary-sourced

## Claim 9: National Digital Sexual Crime Victim Support Center "established by the Ministry of Gender Equality and Family in 2018"

Source: https://www.state.gov/report/custom/e152845032/ (via search snippet) + https://www.koreaherald.com/article/10463398 (via search snippet)
Source tier: primary
Source content: "A Digital Sex Crime Victim Support Center was created in 2018 and assists victims in requesting the deletion of images"; "The Women's Human Rights Institute of Korea, an affiliated organization of the Ministry of Gender Equality and Family, operates this center."
Comparison: 2018 establishment confirmed by US State Dept human-rights report and Korea Herald; MOGEF attribution accurate via its affiliated institute. Minor nuance: operated by a MOGEF-affiliated institute rather than by the ministry directly — not a token error.
Decision: corroborated

## Claim 10: "in 2018, tens of thousands of women and girls marched through Seoul" under slogans "My life is not your porn" and "Are we not human?"

Source: https://www.hrw.org/news/2024/08/29/south-koreas-digital-sex-crime-deepfake-crisis
Source tier: mainstream
Source content: "tens of thousands of women and girls marched through the streets of Seoul chanting slogans, including 'My life is not your porn' and 'Are we not human?'"
Comparison: Exact match to the body sentence and sources[1].note's protest record. Confirmed this session only by HRW (the exact slogans were not fetched from a second source).
Decision: single-source

## Claim 11: Nth Room case — Telegram-based network, "approximately 60,000 individuals participated in the production, distribution, or possession" of coerced content

Source: https://montrealethics.ai/digital-sex-crime-online-misogyny-and-digital-feminism-in-south-Korea/ + https://en.wikipedia.org/wiki/Nth_Room_case (via search snippet)
Source tier: mainstream
Source content: MAIEI: "it was reported that approximately 60,000 individuals were engaged in the production, distribution, or possession of the content"; videos "were then sold to customers using the Telegram messenger app." Wikipedia: "a criminal case involving blackmail, cybersex trafficking... via the Telegram app between 2018 and 2020 in South Korea."
Comparison: The 60,000 figure and Telegram mechanism match. Entity dates the case "2019–2020"; Wikipedia dates the activity 2018–2020 — the entity's span covers the case's emergence and prosecution, not a token contradiction. MAIEI's Megalia/Soranet content in sources[8].note also confirmed (Soranet shutdown 2016 via Megalia-initiated investigation).
Decision: corroborated

## Claim 12: "the Criminal Act amendment of 2020... for the first time specifically criminalised the production and distribution of synthetic intimate imagery created using deepfake technology"

Source: https://www.koreaherald.com/article/3480484 (via search snippet) + https://facia.ai/knowledgebase/south-koreas-act-on-special-cases-with-respect-to-punishing-sex-crimes/ (via search snippet)
Source tier: mainstream
Source content: "The March 2020 amendment to the Act on the Punishment of Sexual Crimes criminalizes the production and distribution of deepfakes intended for circulation"; "Under Article 14-2 of the Act, a person who edits, synthesizes, or processes photograph, video, or audio... could face up to five years in prison."
Comparison: The 2020 deepfake criminalisation was an amendment to the **Act on Special Cases Concerning the Punishment of Sexual Crimes** (성폭력처벌법, new Article 14-2, March 2020), not to the Criminal Act (형법) — the statute name in the body is a specific factual token with a single correct replacement. The year and substance (first specific criminalisation of deepfake synthetic intimate imagery, passed in response to Nth Room outrage) are accurate.
Decision: correction

## Claim 13: "In August 2024, male students at hundreds of Korean schools and universities created Telegram channels" sharing AI-generated explicit content depicting "female classmates, teachers, and family members"

Source: https://fortune.com/asia/2024/08/29/south-korea-deepfake-criminal-penalties-telegram (via search snippet) + https://www.tandfonline.com/doi/full/10.1080/09540253.2026.2617577 (via search snippet)
Source tier: mainstream
Source content: "male students from hundreds of schools and universities created Telegram channels and groups to share AI-generated explicit videos of their female classmates, teachers, and, in some instances, family members"; peer-reviewed title: "The digital misogyny pipeline: deepfake-based sexual violence in South Korean schools and universities." Police: "Most perpetrators are teens."
Comparison: The wave's substance — perpetrator profile, school scale ("unverified list naming roughly 230 to 300 schools" circulating), Telegram mechanism, and target categories — is confirmed across wire and academic coverage. NOTE: this claim is NOT in the HRW article the body links for it — see Claim 14.
Decision: corroborated

## Claim 14: scalar sources[1].note — HRW cited as "primary source for the 2024 wave of AI-generated NCII in which male students at hundreds of Korean schools and universities created Telegram channels targeting female classmates, teachers, and family members"

Source: https://www.hrw.org/news/2024/08/29/south-koreas-digital-sex-crime-deepfake-crisis
Source tier: mainstream
Source content: Refetched with targeted extraction: the article carries "hundreds of women and girls targeted through deepfake sexual images being shared online. One group sharing these images reportedly has 220,000 members" — and "No specific information... about who created or participated in the channels"; no schools/universities count; no classmates/teachers/family-members enumeration.
Comparison: Frontmatter scalar path `sources[1].note` misattributes the wave-specifics (male students, hundreds of schools/universities, channel creation, target categories) to the HRW article, which does not carry them; those specifics live in AFP/Fortune-class wire coverage (Claim 13). The note is accurate for the 2018 protest record and the GBV framing. Single correct fix: re-scope the note's first clause to what HRW actually reports (hundreds of women and girls targeted; 220,000-member group).
Decision: correction

## Claim 15: "South Korean police documented 297 cases in the first seven months of 2024 — compared to 180 for all of 2023"

Source: https://www.nprillinois.org/2024-09-06/south-korea-investigates-telegram-over-alleged-sexual-deepfakes
Source tier: mainstream
Source content: "in the first seven months of this year, 297 cases of crimes involving sexually explicit deepfakes have been reported, up from 180 in all of 2023."
Comparison: Exact match (NPR member-station mirror of the cited NPR piece). The 297 figure is additionally carried by MAIEI; the 180 figure was confirmed only in the NPR text.
Decision: single-source

## Claim 16: "the largest identified Telegram channel had over 220,000 members"

Source: https://www.hrw.org/news/2024/08/29/south-koreas-digital-sex-crime-deepfake-crisis + https://fortune.com/asia/2024/08/29/south-korea-deepfake-criminal-penalties-telegram (via search snippet)
Source tier: mainstream
Source content: HRW: "One group sharing these images reportedly has 220,000 members." Wire coverage: "One of the largest channels reportedly had over 220,000 subscribers."
Comparison: Two independent canonical sources carry the figure; "over 220,000" matches the wire phrasing.
Decision: corroborated

## Claim 17: scalar sources[4].note — NPR cited as "source fixing... the scale of the Telegram channels (over 220,000 members in the largest identified channel)"

Source: https://www.nprillinois.org/2024-09-06/south-korea-investigates-telegram-over-alleged-sexual-deepfakes
Source tier: mainstream
Source content: "The article does not provide a specific membership number for any individual chat room. It only notes that 'Some of the chat rooms... have thousands of participants.'"
Comparison: Frontmatter scalar path `sources[4].note` misattributes the 220,000-member figure to the NPR article; the figure lives in the HRW piece (and wire coverage). NPR's note remains accurate for the 297-vs-180 police data and the Telegram investigation. Single correct fix: move the channel-scale attribution to sources[1] (HRW).
Decision: correction

## Claim 18: "Activists staged a rally in Seoul on 6 September 2024 calling for comprehensive AI-era legislation"

Source: no canonical source found
Source tier: none
Source content: NPR (6 Sept 2024) photo caption documents a protest "in Seoul, South Korea, on Aug. 30"; VOA documents a rally "Sept. 27, 2024"; Korea Times/Feminist Giant document the ~6,000-person Marronnier Park rally of Saturday 21 September. A search-tool summary asserted a 6 Sept rally (~1,000 participants, 144 organisations) but no fetchable canonical source confirmed it (newlinesmag.com carries only an undated September rally caption).
Comparison: Multiple Seoul rallies are documented on other dates (Aug 30, Sept 21, Sept 27); no canonical source fetched this session confirms a 6 September rally specifically. Cannot assert error (a rally that day may exist behind the paywalled cited paper), so this names where the audit reached its limits.
Decision: uncorroborated

## Claim 19: "21 National Assembly petitions collectively gathering approximately 490,000 signatures"

Source: https://api.semanticscholar.org/graph/v1/paper/DOI:10.1080/01924036.2025.2596578
Source tier: database
Source content: The paper's abstract: "The research reveals how diverse claim makers propelled recognition of NSII as a criminal issue, initiating swift reforms strengthened statutes, victim support, and AI governance." No petition count or signature figure in the abstract; full text is paywalled (tandfonline and ResearchGate both 403).
Comparison: The claim's specifics (21 petitions; ~490,000 collectively) live only in the paywalled paper body; a ResearchGate-derived search summary suggested a single petition gathering nearly 490,000 signatures, which conflicts with "21 petitions collectively" — unresolvable without the full text.
Decision: uncorroborated

## Claim 20: scalar sources[3].note — paper attributed to "Park Geon-Beom and Jeong Seona"

Source: https://api.semanticscholar.org/graph/v1/paper/DOI:10.1080/01924036.2025.2596578
Source tier: database
Source content: "Authors: Sohee Jung, Hyeseon Noh" — title "From grassroots advocacy to AI governance: lessons from South Korea's 2024 deepfake sexual abuse crisis on democratising knowledge and policy," year 2025.
Comparison: Frontmatter scalar path `sources[3].note` names authors "Park Geon-Beom and Jeong Seona"; the paper's authors of record (Semantic Scholar API, matching tandfonline metadata: Vol 50 No 3, published online 4 Dec 2025) are **Sohee Jung and Hyeseon Noh** (University of South Carolina). Single correct replacement of the author names.
Decision: correction

## Claim 21: "the April 2025 launch of a National Centre for Digital Sexual Crime Response — a 24/7 hub integrating AI-based systems for automated removal of deepfake content"

Source: https://lens.monash.edu/@politics-society/2025/11/19/1388026/the-paradox-of-digital-safety-deepfakes-ai-and-gendered-risk-in-south-korea + https://www.korea.net/NewsFocus/policies/view?articleId=270565 (via search snippet)
Source tier: primary
Source content: Monash Lens: "In April 2025, the government launched the National Centre for Digital Sexual Crime Response, a 24/7 hub designed to coordinate reporting, counselling and deletion support across all 17 provinces. The centre integrates AI-based systems for the automatic removal of deepfake and illegally filmed content." korea.net: "The newly launched National Center for Digital Sexual Crime Response runs 24 hours a day, 365 days a year."
Comparison: Date, name, 24/7 character, and AI-based automated removal all match; korea.net is a Korean-government outlet (primary tier), Monash Lens independent.
Decision: corroborated

## Claim 22: "ACOSAV handled approximately 332,000 service cases in 2024 — a 20.6% year-on-year increase — with synthetic-content cases rising 227.2% from 2023"

Source: https://www.korea.net/Government/Briefing-Room/Press-Releases/view?articleId=710468&type=N&insttCode=A260114 (via search snippet)
Source tier: primary
Source content: "ACOSAV supported 10,305 victims of digital sex crimes in 2024, with approximately 332,000 cases of service provided including counseling, content removal, and referrals... representing a 20.6% year-on-year increase in total services. Additionally, cases involving image synthesis/editing surged by 227.2%."
Comparison: All three figures match the government press release on ACOSAV's 2024 annual report. Note the citation problem in Claim 23 — the figures are right but attributed to the wrong article.
Decision: primary-sourced

## Claim 23: scalar sources[7].note — Korea Times article cited as source for "approximately 332,000 service cases in 2024 (a 20.6% year-on-year increase)" and "the 227.2% year-on-year increase in synthetic/edited-content cases"

Source: https://www.koreatimes.co.kr/www/nation/2025/02/113_381432.html
Source tier: mainstream
Source content: The fetched article carries: "All told, 2,154 deepfake crime victims have so far contacted the ACOSAV"; "This year alone, 781 deepfake crime victims sought help... an 11-fold increase over 69 victims reported in 2018"; "the DNA System's detection rate for illegally filmed and deepfake materials has exceeded 99 percent." It does not carry the 332,000, 20.6%, or 227.2% figures.
Comparison: Frontmatter scalar path `sources[7].note` misattributes the ACOSAV annual-report figures to this article. The article supports the note's 2,000+-victims and 99%-detection claims only; the 332,000/20.6%/227.2% figures live in the Korean government's press release on ACOSAV's 2024 annual report (korea.net — Claim 22). Single correct fix: re-point the annual-report figures to that release.
Decision: correction

## Claim 24: EVAW ran the UK campaign "alongside specialist organisation #NotYourPorn and survivor advocates"

Source: https://www.endviolenceagainstwomen.org.uk/survivors-and-campaigners-welcome-new-deepfake-law-but-call-on-government-to-go-further/
Source tier: primary
Source content: "The organization co-founded by Elena Michael [#NotYourPorn] was part of the months-long campaign alongside survivor Jodie, EVAW Coalition, Professor Clare McGlynn, and Glamour UK." EVAW describes deepfake abuse as causing "profound harm to victims, including significant psychological trauma, impact on employment opportunities and interpersonal relationships, silencing of women's voices online and withdrawal from public life."
Comparison: Campaign coalition composition and the note's "profound harm" framing quote both confirmed on EVAW's own page. ("Principal civil-society campaign" is characterization; the constituent facts check.)
Decision: primary-sourced

## Claim 25: "A 73,000-signature petition was delivered to 10 Downing Street"

Source: https://www.endviolenceagainstwomen.org.uk/survivors-and-campaigners-welcome-new-deepfake-law-but-call-on-government-to-go-further/
Source tier: primary
Source content: "A 73,000-signature petition was delivered to No. 10 Downing Street calling for government action beyond criminal offenses alone."
Comparison: Exact match on figure and destination.
Decision: primary-sourced

## Claim 26: UK legislation "criminalising the creation or solicitation of non-consensual sexually explicit deepfakes came into force on 6 February 2026"

Source: https://www.endviolenceagainstwomen.org.uk/survivors-and-campaigners-welcome-new-deepfake-law-but-call-on-government-to-go-further/ + https://www.cliffordchance.com/insights/resources/blogs/talking-tech/en/articles/2026/02/key-aspects-of-the-data--use-and-access--act-take-effect.html (via search snippet)
Source tier: mainstream
Source content: EVAW: in force 6 February 2026, criminal offence to "create or ask someone to create" non-consensual sexually explicit deepfakes. Legal analyses: "From 6 February 2026, Section 138 of the Data (Use and Access) Act 2025 criminalises the creation – or request to create – fake intimate images without consent."
Comparison: Date and offence scope (creation + solicitation) confirmed by the campaign's own statement and independent law-firm analyses of DUAA 2025 s.138.
Decision: corroborated

## Claim 27: "EVAW's working figures — that 96% of deepfakes are sexually explicit and 99% depict women"

Source: https://www.endviolenceagainstwomen.org.uk/survivors-and-campaigners-welcome-new-deepfake-law-but-call-on-government-to-go-further/
Source tier: primary
Source content: "96% of deepfakes are sexually explicit" and "99% of those depict women."
Comparison: The body's claim is that these are EVAW's working figures — EVAW's own page states them, which is exactly what the claim asserts.
Decision: primary-sourced

## Claim 28: CCRI "founded from Holly Jacobs's 2012 grassroots 'End Revenge Porn' campaign"

Source: https://cybercivilrights.org/about/ (via search snippet)
Source tier: primary
Source content: "she launched the End Revenge Porn (ERP) campaign in August 2012... A year after ERP's launch, Dr. Jacobs started its parent organization CCRI... Dr. Jacobs incorporated her work on the campaign into the CCRI."
Comparison: CCRI's own history page confirms the 2012 campaign origin and CCRI growing from it (founded the following year).
Decision: primary-sourced

## Claim 29: "Francesca Mani, whose January 2024 Congressional testimony described a New Jersey high school case..."

Source: https://www.commerce.senate.gov/meetings/field-hearing-take-it-down-ending-big-techs-complicity-in-revenge-porn/
Source tier: primary
Source content: Senate Commerce field hearing "Take It Down: Ending Big Tech's Complicity In Revenge Porn," University of North Texas at Dallas, "Wednesday, June 26, 2024, at 1:30 P.M."; witness "Ms. Francesca Mani... a high school student and victim of AI-generated sexually exploitative imagery from Westfield, NJ."
Comparison: Francesca Mani's Congressional testimony was at the 26 June 2024 Senate Commerce field hearing, not in January 2024 (her mother Dorota Mani separately testified to House Oversight in March 2024; January 2024 press coverage of Francesca was advocacy, not testimony). Specific token with a single correct replacement: January 2024 → June 2024.
Decision: correction

## Claim 30: Westfield case — "AI-generated explicit images of over 30 female students had been circulated"

Source: https://www.nbcnews.com/tech/tech-news/deepfake-law-ai-new-jersey-high-school-teen-image-porn-rcna133706 (via search snippet) + https://globalnews.ca/news/10073305/ai-nude-images-deepfakes-westfield-high-school-classmates-new-jersey/ (via search snippet)
Source tier: mainstream
Source content: "In October 2023, male classmates at Westfield High School created and shared sexually explicit deepfakes of Francesca Mani and more than 30 other girls."
Comparison: "Over 30 female students" matches the widely reported "more than 30" figure across NBC/Global News/Forbes coverage.
Decision: corroborated

## Claim 31: "TAKE IT DOWN Act, enacted on 19 May 2025"

Source: https://en.wikipedia.org/wiki/TAKE_IT_DOWN_Act + https://www.commerce.senate.gov/index.php/2025/5/sen-cruz-applauds-presidential-signing-of-the-take-it-down-act-into-law
Source tier: primary
Source content: Wikipedia: "The act was signed into law on May 19, 2025." Senate Commerce press release marks the presidential signing (May 2025).
Comparison: Enactment date confirmed (public-record fact; Wikipedia-alone would suffice, and the Senate record corroborates).
Decision: corroborated

## Claim 32: TAKE IT DOWN Act "mandated that online platforms remove non-consensual intimate visual depictions — including AI-generated deepfakes — within 4 hours of notification"

Source: https://en.wikipedia.org/wiki/TAKE_IT_DOWN_Act + https://www.congress.gov/crs-product/LSB11314 (via search snippet)
Source tier: primary
Source content: Wikipedia: platforms must "remove such images at the request from the victim within 48 hours" and delete copies. CRS/legal analyses: "Upon receiving a valid request, the platform must remove the content within 48 hours and make reasonable efforts to identify and remove known identical copies" (see also ubaltlawreview.com: "The TAKE IT DOWN Act's 48-Hour Deadline").
Comparison: The statutory removal deadline is **48 hours**, not 4 hours — every source (Wikipedia, CRS, FTC guidance, law-review analysis) agrees. Specific numeric token with a single correct replacement, appearing in both the body sentence and scalar `sources[6].note` ("the 4-hour platform-takedown mandate"): 4 hours → 48 hours.
Decision: correction

## Claim 33: "support from over 120 advocacy, law-enforcement, and technology organisations"

Source: https://www.commerce.senate.gov/index.php/2025/5/sen-cruz-applauds-presidential-signing-of-the-take-it-down-act-into-law
Source tier: primary
Source content: "More than 120 organizations representing victim advocacy groups, law enforcement, and tech industry leaders have voiced their support for the legislation, including the Fraternal Order of Police, the National Center for Missing and Exploited Children (NCMEC), RAINN..., and the National Center on Sexual Exploitation."
Comparison: Figure and sector characterization match the Senate Commerce Committee's official release. Note: `sources[6].note` attributes this count to Wikipedia, whose current article names only several supporting groups without the 120 count — likely source drift since last_checked 2026-06-03; the claim itself stands on the Senate record.
Decision: primary-sourced

## Claim 34: DRF's "annual helpline reports document the Pakistani prevalence of technology-facilitated gender-based violence — a category the organisation explicitly extends to AI-synthesised non-consensual intimate imagery"

Source: https://digitalrightsfoundation.pk/wp-content/uploads/2026/05/2025-Helpline-Annual-Report-1.pdf (via search snippet) + https://thefridaytimes.com/05-Apr-2024/ai-among-technologies-increasingly-used-to-harass-women-online-in-pakistan (via search snippet)
Source tier: primary
Source content: Helpline-report coverage: "image-based abuse and deepfake-related incidents at 514 cases"; helpline manager: TFGBV manifestations "have evolved with rising complaints of... the use of generative AI to produce non-consensual intimate images." Friday Times: "AI Among Technologies Increasingly Used To Harass Women Online In Pakistan" (reporting DRF's data).
Comparison: DRF's own annual helpline reporting categorises AI-generated NCII within its TFGBV caseload, and mainstream Pakistani coverage reports it — matches the body claim.
Decision: corroborated

## Claim 35: DRF reports "have been drawn on by Pakistan's parliamentary processes and telecommunications authority consultations as the principal published evidence base on the issue in South Asia"

Source: no canonical source found
Source tier: none
Source content: IDS and DRF materials confirm DRF "produces policy briefs and annual trends reports based on helpline data, informing national policy debates and contributing to international mechanisms such as the UN Universal Periodic Review" — but no fetched source names National Assembly processes or PTA consultations drawing on the reports, nor supports the "principal published evidence base... in South Asia" superlative.
Comparison: The general policy-influence claim is plausible and partially supported (national policy debates, UPR), but the specific institutional channels (parliament, PTA consultations) and the load-bearing "principal... in South Asia" characterization were not confirmed by any canonical source this session.
Decision: uncorroborated
