---
entity_id: pub-european-disability-forum-ai-position
entity_hash: 3a82b42a77b021873885c4a8948f9c04f164ea73
audit_date: 2026-06-10
pass: 2
status: discrepancy
claims_total: 28
claims_verified: 22
claims_discrepancy: 3
claims_unverifiable: 3
sources_consulted:
  - https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/
  - https://www.edf-feph.org/content/uploads/2021/11/EDF-Position-Paper-on-EU-Artificial-Intelligence-AI-Regulation-1.pdf
  - https://www.edf-feph.org/
  - https://www.edf-feph.org/about-us/
  - https://www.edf-feph.org/contact/
  - https://www.edf-feph.org/our-members/
  - https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
  - https://www.edf-feph.org/publications/resolution-on-the-eu-artificial-intelligence-act-for-the-inclusion-of-persons-with-disabilities/
  - https://www.edf-feph.org/projects/inclusive-artificial-intelligence-ai/
  - https://www.edf-feph.org/publications/a-disability-inclusive-artificial-intelligence-act-a-guide-to-monitor-implementation-in-your-country/
  - https://www.edf-feph.org/content/uploads/2024/10/AI-Act-implementation-toolkit-Final.pdf
  - https://www.edf-feph.org/ai-act-agreement-partial-win-on-accessibility/
  - https://www.edf-feph.org/what-edf-achieved-in-artificial-intelligence-ai-policy-in-2025/
  - https://www.edf-feph.org/european-parliaments-spotlight-on-disability-rights/
  - https://www.edf-feph.org/kave-noori/
  - https://europeanaifund.org/newspublications/interview-with-kave-noori-and-marine-uldry-from-the-european-disability-forum-nothing-about-us-without-us-including-ai/
  - https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
  - https://en.wikipedia.org/wiki/HireVue
---

## Claim 1: "published on 2 November 2021"

Source: https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/
Source content: "Publication Date: November 2, 2021" (EDF publication page)
Comparison: Body date matches the EDF publication page exactly.
Decision: verified

## Claim 2: "in direct response to the European Commission's proposed Artificial Intelligence Act (April 2021)"

Source: https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/ and https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
Source content: Publication page: responds to the "European Commission's proposal for regulating AI in the EU (dated April 2021, referenced as COM(2021)206)"; Wikipedia: "On 21 April 2021, the AI Act was officially proposed by the Commission."
Comparison: Body's April 2021 Commission-proposal framing matches both sources.
Decision: verified

## Claim 3: "representing the interests of 50 million persons with disabilities across the EU" (body claim, and parallel scalar:sources[7].note — "representing 50 million persons with disabilities across the EU")

Source: https://www.edf-feph.org/ and https://www.edf-feph.org/about-us/ and https://www.edf-feph.org/content/uploads/2021/11/EDF-Position-Paper-on-EU-Artificial-Intelligence-AI-Regulation-1.pdf
Source content: Homepage: "defends the interests of over 100 million persons with disabilities in Europe"; about-us: "We defend the interests of more than 100 million persons with disabilities in Europe"; the position paper itself: "The European Disability Forum is an independent NGO that advocates for the rights of 100 million Europeans with disabilities."
Comparison: Three EDF primary sources, including the audited publication itself, say 100 million; body and the frontmatter scalar `sources[7].note` (the homepage entry) say 50 million. Unambiguous numerical contradiction. Pass-1 discrepancy confirmed, now additionally against the position paper's own text.
Decision: discrepancy

## Claim 4: "EDF is the independent pan-European umbrella organisation"

Source: https://www.edf-feph.org/
Source content: "umbrella organisation of persons with disabilities" ... "independent non-governmental organisation (NGO)"
Comparison: EDF's self-description supports "independent" and "umbrella organisation"; "pan-European" is fair paraphrase of its Europe-wide scope.
Decision: verified

## Claim 5: "with member organisations from every EU and EEA country and European-level NGOs representing specific disability types"

Source: https://www.edf-feph.org/our-members/ and https://www.edf-feph.org/about-us/
Source content: Members directory categorises "National Council - full member" entries (e.g. Austrian Disability Council, CERMI Spain) and "European NGO - full member" entries representing disability types (European Council of Autistic People, FIMITIC, ESCIF, EURORDIS); country filter spans EU, EEA, and candidate countries. About-us: "We bring together representative organisations of persons with disabilities from across Europe."
Comparison: The two-tier structure (national umbrella councils + European disability-type NGOs) is confirmed by the members directory. The universal quantifier "every EU and EEA country" is not stated by any EDF page consulted; no source enumerates complete EU/EEA coverage. The structural claim is supported but the "every" cannot be confirmed or refuted.
Decision: unverifiable

## Claim 6: scalar:sources[7].note (homepage source note) — "its Brussels headquarters"

Source: https://www.edf-feph.org/contact/
Source content: "Avenue des Arts 7-8, 1210 Brussels, Belgium"
Comparison: EDF's own contact page confirms Brussels headquarters — the underlying fact is verified (pass-1 unverifiable resolved; pass 1 tried /contact-us/, which 404s; the live page is /contact/). Note for the Editor: the scalar `sources[7].note` attributes this fact to the homepage, which does not state a location — the attribution is imprecise even though the fact is correct.
Decision: verified

## Claim 7: "grounded in the UN Convention on the Rights of Persons with Disabilities (UNCRPD)"

Source: https://www.edf-feph.org/content/uploads/2021/11/EDF-Position-Paper-on-EU-Artificial-Intelligence-AI-Regulation-1.pdf
Source content: "As signatories to the United Nations Convention on the Rights of Persons with Disabilities (CRPD), the European Union (EU) and all Member States are legally obliged to protect persons with disabilities from discrimination and promote their equality (Article 5)"; the paper also invokes "article 4.3 of the CRPD" and lists the UN CRPD first among Related Documents.
Comparison: The paper's own text grounds its demands in the CRPD throughout (pass 1 inferred this from secondary pages; pass 2 confirms from the paper itself).
Decision: verified

## Claim 8: organising principle is "'Nothing About Us Without Us' — the disability-rights proposition that persons with disabilities must be active participants, not passive subjects, in any policy that shapes their lives"

Source: https://europeanaifund.org/newspublications/interview-with-kave-noori-and-marine-uldry-from-the-european-disability-forum-nothing-about-us-without-us-including-ai/ and https://www.edf-feph.org/
Source content: "the moto of the disability movement is 'nothing about us, without us'. Because Artificial Intelligence increasingly impacts everyone's life, EDF decided to work more on AI" (EU AI Fund interview); EDF homepage carries "Nothing about us without us!" as its governing principle.
Comparison: EDF explicitly applies the frame to its AI advocacy; the body's gloss is consistent.
Decision: verified

## Claim 9: "five requirements" — accessibility, protection from harm, strong governance, global standards, meaningful inclusion

Source: https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/
Source content: "1. Accessibility of AI-based technologies and practices for persons with disabilities; 2. Protect persons with disabilities form potential AI-induced harm, including from any risk to their right to non-discrimination and equality, privacy and data protection; 3. Strong governance mechanisms, human rights impact assessment, and accessible feedback, complaints and redress mechanisms; 4. The same legal standards for European AI used outside of the EU; 5. Involvement of persons with disabilities and accessibility experts in the development of European and national AI policies"
Comparison: All five requirements match in name and substance; "meaningful inclusion" vs the source's "involvement of persons with disabilities" is within paraphrase tolerance.
Decision: verified

## Claim 10: "Austria's Public Employment Service (AMS) algorithm" cited as documented case of employment-screening AI discriminating against persons with disabilities

Source: https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
Source content: "Austria's employment agency was criticised for rolling out a sorting algorithm that gave lower scores to women and persons with disabilities, thereby reducing their chance of finding work."
Comparison: EDF's red-lines page cites the AMS case as the body describes.
Decision: verified

## Claim 11: AMS algorithm "applying disability status as a negative scoring signal in an automated gatekeeping tool"

Source: https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
Source content: "gave lower scores to women and persons with disabilities, thereby reducing their chance of finding work"
Comparison: "Disability status as a negative scoring signal" matches "gave lower scores to ... persons with disabilities" within paraphrase tolerance.
Decision: verified

## Claim 12: "EDF advocacy materials specifically cite the HireVue case"

Source: https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
Source content: HireVue's system "was found to massively discriminate against many persons with disabilities who have out of the 'norm' facial expressions and voice"
Comparison: HireVue is explicitly cited in EDF's red-lines advocacy.
Decision: verified

## Claim 13: "the AI-video-interviewing platform challenged by the US Federal Trade Commission in 2021"

Source: https://en.wikipedia.org/wiki/HireVue
Source content: "In November 2019, the Electronic Privacy Information Center filed a complaint to the Federal Trade Commission alleging that Hirevue's software caused harm to American workers through its collection of biometric data, bias towards those with different genders, races, sexual orientations and 'neurological differences'"
Comparison: Two errors, as in pass 1: (a) HireVue was not challenged BY the FTC — EPIC filed a complaint TO the FTC, which was the recipient, not the challenger; (b) the year was November 2019, not 2021. Dated public-record class — Wikipedia sufficient per Source rule. Pass-1 discrepancy confirmed.
Decision: discrepancy

## Claim 14: AI-based social-benefits gatekeeping systems "characterised by EDF as surveillance"

Source: https://www.edf-feph.org/what-edf-achieved-in-artificial-intelligence-ai-policy-in-2025/
Source content: "Some governments use AI to screen persons with disabilities who request support. These systems can increase surveillance and force people to justify every detail of their needs simply to receive basic assistance." (EDF's own AI-policy summary, quoting its EP testimony)
Comparison: EDF's own published material characterises AI benefits-screening in surveillance terms — semantic match within paraphrase tolerance (pass-1 unverifiable resolved by a source pass 1 did not consult). Note for the Editor: the body and scalar `sources[1].note` attribute this characterisation to the red-lines page, which does not carry it; the support lives on EDF's 2025 AI-policy page.
Decision: verified

## Claim 15: paper "frames this as an application of the UNCRPD right to independent living and inclusion in the community (Article 19)"

Source: https://www.edf-feph.org/content/uploads/2021/11/EDF-Position-Paper-on-EU-Artificial-Intelligence-AI-Regulation-1.pdf
Source content: The paper's complete extracted text contains no reference to CRPD Article 19. Its CRPD/legal references are: "article 4.3 of the CRPD" (consultation obligation), Article 5 (equality/non-discrimination), and Articles 9, 22, 24, 25, 27 (an inventory of every "Article N" string in the full text); its two "independent living" mentions are generic ("bringing potential benefits for social inclusion and independent living") and a smart-home footnote — neither frames benefits gatekeeping.
Comparison: The body attributes a specific legal framing (Article 19, independent living and inclusion in the community) to the paper that the paper's full text does not contain; its benefits-gatekeeping demand is grounded in non-discrimination (Article 5), not Article 19. Pass 1 marked this unverifiable without fetching the paper; pass 2 fetched and searched the full document text. Caveat: text was extracted from the PDF programmatically; residual undecoded glyphs are ~0.1% of the text and all article-number references decoded cleanly.
Decision: discrepancy

## Claim 16: "Real-time biometric identification and categorisation in public spaces" listed by the position paper among uses that must be absolutely prohibited

Source: https://www.edf-feph.org/content/uploads/2021/11/EDF-Position-Paper-on-EU-Artificial-Intelligence-AI-Regulation-1.pdf
Source content: "The Regulation must prohibit use of AI for remote biometric identification by public and private entities in publicly accessible spaces, including in online spaces." and "The Regulation must prohibit use of biometric categorisation AI systems by public and private entities." The paper also notes remote biometric identification "can expose disability and health-related information of an individual without their knowledge and consent".
Comparison: The paper itself demands prohibition of biometric identification and categorisation in publicly accessible spaces — the body's claim is verified by the primary document (pass-1 unverifiable resolved; the paper's "remote" encompasses the body's "real-time", which the paper names in its high-risk-areas discussion: "real-time and post remote biometric identification"). The body's inference of disability-status exposure matches the paper. Note for the Editor: the body's inline link and scalar `sources[1].note` cite the red-lines page for this category, which does not enumerate it — the support is the position paper PDF.
Decision: verified

## Claim 17: "the final text (entered into force 1 August 2024)"

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
Source content: "It entered into force on 1 August 2024."
Comparison: Date matches. Public-record class — Wikipedia sufficient per Source rule.
Decision: verified

## Claim 18: "2023 Board Resolution on the EU AI Act, adopted on 1 April 2023"

Source: https://www.edf-feph.org/publications/resolution-on-the-eu-artificial-intelligence-act-for-the-inclusion-of-persons-with-disabilities/
Source content: "adopted by the Board of Directors of the European Disability Forum on the 1st of April 2023"
Comparison: Date and adopting body match exactly.
Decision: verified

## Claim 19: Resolution "sharpened the 2021 position paper into specific legislative demands: expansion of the prohibited AI practices list, stronger obligations for high-risk AI systems affecting disabled people's rights, and mandatory disability-inclusive conformity assessment procedures"

Source: https://www.edf-feph.org/publications/resolution-on-the-eu-artificial-intelligence-act-for-the-inclusion-of-persons-with-disabilities/
Source content: "Enlarge the list of prohibited uses of AI systems"; "Recognise the disproportionate risk to the rights of persons with disabilities" in high-risk areas; "AI systems, regardless of their level of risk, are subject to mandatory accessibility requirements"
Comparison: All three demands are present in the Resolution as described.
Decision: verified

## Claim 20: EDF described final Act accessibility requirements as "partial win on accessibility"

Source: https://www.edf-feph.org/ai-act-agreement-partial-win-on-accessibility/
Source content: "a partial victory has been achieved in terms of accessibility for persons with disabilities, as high-risk Artificial Intelligence systems will have to meet requirements for accessibility."
Comparison: "Partial win" matches "partial victory" and the page's URL slug; the body's falling-short framing matches EDF President Vardakastanis: "addresses human rights, but not as comprehensively as we hoped for".
Decision: verified

## Claim 21: "five-year Disability Inclusive Artificial Intelligence project (2023–2027)"

Source: https://www.edf-feph.org/projects/inclusive-artificial-intelligence-ai/
Source content: "Five years (January 1, 2023 – December 31, 2027)"
Comparison: Duration and year range match.
Decision: verified

## Claim 22: "Kave Noori — who joined EDF in January 2023" and his role as "AI Policy Officer" / "EDF's primary specialist in AI and disability rights"

Source: https://europeanaifund.org/newspublications/interview-with-kave-noori-and-marine-uldry-from-the-european-disability-forum-nothing-about-us-without-us-including-ai/ and https://www.edf-feph.org/projects/inclusive-artificial-intelligence-ai/ and https://www.edf-feph.org/kave-noori/
Source content: "Kave Noori is EDF's Artificial Intelligence Policy Officer and joined the organisation in January 2023" (EU AI Fund interview); the Inclusive AI project page names Noori as the Artificial Intelligence Policy Officer; EDF's profile page: "As Artificial Intelligence Policy Officer at EDF, Kave will advocate for EDF positions".
Comparison: Role title and January 2023 start date match across three sources, two of them EDF primary.
Decision: verified

## Claim 23: Noori "presenting to European Parliament committees on Internal Market and Civil Liberties and Justice matters"

Source: https://www.edf-feph.org/what-edf-achieved-in-artificial-intelligence-ai-policy-in-2025/
Source content: "Kave Noori spoke at the Committee on the Internal Market and Consumer Protection and Committee on Civil Liberties, Justice and Home Affairs on Artificial Intelligence (AI) and disability rights."
Comparison: EDF's own AI-policy summary confirms presentations to exactly the two committees the body names (IMCO and LIBE). Pass-1 unverifiable resolved by a source pass 1 did not consult.
Decision: verified

## Claim 24: Noori "participating in the UN Conference of State Parties to the CRPD"

Source: https://www.edf-feph.org/what-edf-achieved-in-artificial-intelligence-ai-policy-in-2025/
Source content: "EDF took part in the full three-day conference, led by our President, Yannis Vardakastanis" and EDF "co-organised a side event with the European Commission to discuss artificial intelligence in the European Union."
Comparison: EDF's organisational participation in COSP (including an AI side event) is confirmed, but no source consulted names Noori personally as a participant — the body attributes participation to him specifically. Cannot confirm or refute the person-level claim.
Decision: unverifiable

## Claim 25: "In October 2024 EDF published the *Disability-Inclusive Artificial Intelligence Act: A Guide to Monitor Implementation in Your Country*"

Source: https://www.edf-feph.org/publications/a-disability-inclusive-artificial-intelligence-act-a-guide-to-monitor-implementation-in-your-country/
Source content: "Publication Date: 15.10.2024"; title "A disability-inclusive Artificial Intelligence Act: A guide to monitor implementation in your country"
Comparison: Title and October 2024 date match.
Decision: verified

## Claim 26: implementation guide "authored by Kave Noori" (body claim and parallel scalar:sources[5].note — "October 2024, authored by Kave Noori")

Source: https://www.edf-feph.org/content/uploads/2024/10/AI-Act-implementation-toolkit-Final.pdf
Source content: The document's own running header/footer attribution, on every page: "By Kave Noori, EDF Artificial Intelligence Policy Officer | October 2024"
Comparison: The document itself attributes authorship to Kave Noori — the body claim and scalar `sources[5].note` are verified by the strongest primary source (the publication's own byline). This OVERTURNS pass 1's discrepancy: pass 1 compared against the publication web page's CMS byline ("Author: Andre Felix"), which records who posted the page, not who authored the document; pass 1 did not fetch the PDF. Hallucinated-discrepancy class catch — the pass-1 "Source content" was real but was the wrong attribution surface.
Decision: verified

## Claim 27: "an updated edition released in October 2025"

Source: https://www.edf-feph.org/projects/inclusive-artificial-intelligence-ai/
Source content: "A disability-inclusive Artificial Intelligence Act: updated guide to monitor implementation in your country" (October 2025), described as an updated version of the October 2024 guide.
Comparison: Updated October 2025 edition confirmed by EDF's project page.
Decision: verified

## Claim 28: "EDF's representative mandate across 50 member-country umbrella organisations and European disability-type NGOs" (Position in the corpus section)

Source: https://www.edf-feph.org/our-members/
Source content: The members directory lists 119 members across categories (National Council - full member, European NGO - full member, Ordinary, Associate, Observers) with a country filter spanning EU, EEA, and candidate countries; no EDF source consulted states a count of member countries or of national umbrella organisations.
Comparison: New claim not extracted in pass 1. The "50 member-country umbrella organisations" figure is stated by no source consulted; the members directory gives no per-country umbrella count to compare against (119 is total members of all categories, not comparable). Given the parallel 50-vs-100-million error in Claim 3, the figure is suspect, but no source directly contradicts it.
Decision: unverifiable
