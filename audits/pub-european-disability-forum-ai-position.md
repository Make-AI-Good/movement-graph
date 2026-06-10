---
entity_id: pub-european-disability-forum-ai-position
entity_hash: 3a82b42a77b021873885c4a8948f9c04f164ea73
audit_date: 2026-06-10
pass: 1
status: discrepancy
claims_total: 27
claims_verified: 17
claims_discrepancy: 3
claims_unverifiable: 7
sources_consulted:
  - https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/
  - https://www.edf-feph.org/
  - https://www.edf-feph.org/about-us/
  - https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
  - https://www.edf-feph.org/publications/resolution-on-the-eu-artificial-intelligence-act-for-the-inclusion-of-persons-with-disabilities/
  - https://www.edf-feph.org/projects/inclusive-artificial-intelligence-ai/
  - https://www.edf-feph.org/publications/a-disability-inclusive-artificial-intelligence-act-a-guide-to-monitor-implementation-in-your-country/
  - https://www.edf-feph.org/ai-act-agreement-partial-win-on-accessibility/
  - https://europeanaifund.org/newspublications/interview-with-kave-noori-and-marine-uldry-from-the-european-disability-forum-nothing-about-us-without-us-including-ai/
  - https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
  - https://en.wikipedia.org/wiki/HireVue
---

## Claim 1: "published on 2 November 2021"

Source: https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/
Source content: "Publication: 'Disability perspective on Regulating Artificial Intelligence' — Date: November 2, 2021"
Comparison: Body date matches the EDF publication page exactly.
Decision: verified

## Claim 2: "in direct response to the European Commission's proposed Artificial Intelligence Act (April 2021)"

Source: https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/
Source content: "The position paper responds to the European Commission's April 2021 proposed AI Regulation"
Comparison: Body's "April 2021 Commission proposal" framing matches.
Decision: verified

## Claim 3: "representing the interests of 50 million persons with disabilities across the EU" (body claim, and parallel `sources[].note` for the EDF homepage scalar: "representing 50 million persons with disabilities across the EU")

Source: https://www.edf-feph.org/ and https://www.edf-feph.org/about-us/
Source content: edf-feph.org homepage: "the interests of over 100 million persons with disabilities in Europe"; about-us page: "We defend the interests of more than 100 million persons with disabilities in Europe."
Comparison: EDF's own self-description states "over 100 million", not 50 million. The body and the homepage `sources[].note` scalar (frontmatter path `sources[0].note` — the entry whose `url:` is `https://www.edf-feph.org/`) both undercount by ~half. Numerical claim is unambiguous and contradicted by primary source.
Decision: discrepancy

## Claim 4: "EDF is the independent pan-European umbrella organisation"

Source: https://www.edf-feph.org/
Source content: "an umbrella organisation of persons with disabilities" and "an independent non-governmental organisation (NGO)"
Comparison: EDF's own self-description supports both "independent" and "umbrella organisation". "Pan-European" is reasonable paraphrase of EDF's Europe-wide scope.
Decision: verified

## Claim 5: "with member organisations from every EU and EEA country and European-level NGOs representing specific disability types"

Source: https://www.edf-feph.org/ and https://www.edf-feph.org/about-us/
Source content: "brings together representative organisations of persons with disabilities from across Europe" (homepage); about-us page contains no explicit enumeration of EU/EEA member countries or European-level disability-type NGOs.
Comparison: EDF's own pages describe membership as "from across Europe" without naming the specific "every EU and EEA country" structural composition or the "European-level NGOs representing specific disability types" subset. Wikipedia entry for EDF returned HTTP 404 on fetch and could not corroborate. No canonical source consulted in this pass confirms the specific structural claim.
Decision: unverifiable

## Claim 6: scalar:sources[7].note (homepage source note) — "its Brussels headquarters"

Source: https://www.edf-feph.org/ and https://www.edf-feph.org/about-us/
Source content: Neither EDF page consulted in this pass states a Brussels headquarters location.
Comparison: The frontmatter scalar `sources[7].note` (the homepage source entry, `url: https://www.edf-feph.org/`) claims EDF's homepage is the source for its "Brussels headquarters" — but the homepage and about-us page consulted do not state Brussels. Contact-us page returned HTTP 404. EDF Wikipedia page also returned HTTP 404. No canonical source consulted confirms the Brussels HQ claim in this pass.
Decision: unverifiable

## Claim 7: "grounded in the UN Convention on the Rights of Persons with Disabilities (UNCRPD)"

Source: https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/
Source content: The EDF publication page frames the paper as setting out disability-rights requirements for AI regulation; the position paper itself (referenced from the publication page) is structured around UNCRPD principles. The EU AI Fund interview ("Nothing About Us Without Us Including AI") confirms EDF positions AI policy work within the UNCRPD frame.
Comparison: Foundational framing in UNCRPD is consistent with all EDF advocacy material consulted.
Decision: verified

## Claim 8: organising principle is "'Nothing About Us Without Us' — the disability-rights proposition that persons with disabilities must be active participants, not passive subjects, in any policy that shapes their lives"

Source: https://europeanaifund.org/newspublications/interview-with-kave-noori-and-marine-uldry-from-the-european-disability-forum-nothing-about-us-without-us-including-ai/
Source content: "the moto of the disability movement is 'nothing about us, without us'. Because Artificial Intelligence increasingly impacts everyone's life, EDF decided to work more on AI"
Comparison: EDF explicitly applies the "Nothing About Us Without Us" frame to AI advocacy; body's gloss on its meaning is consistent.
Decision: verified

## Claim 9: "five requirements" — accessibility, protection from harm, strong governance, global standards, meaningful inclusion

Source: https://www.edf-feph.org/publications/disability-perspective-on-regulating-artificial-intelligence/
Source content: "Accessibility: 'Accessibility of AI-based technologies and practices for persons with disabilities'; Protection from Harm: 'Protect persons with disabilities form potential AI-induced harm...'; Strong Governance: 'Strong governance mechanisms, human rights impact assessment, and accessible feedback, complaints and redress mechanisms'; Global Standards: 'The same legal standards for European AI used outside of the EU'; Meaningful Participation: 'Involvement of persons with disabilities and accessibility experts in the development of European and national AI policies'"
Comparison: All five requirements match in name and substance. Body's "Meaningful inclusion" vs. source's "Meaningful Participation" is within paraphrase tolerance — the substantive content (structural mandate for disabled-persons involvement) matches.
Decision: verified

## Claim 10: "Austria's Public Employment Service (AMS) algorithm" cited as documented case of employment-screening AI discriminating against persons with disabilities

Source: https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
Source content: "Austria's employment agency was criticised for rolling out a sorting algorithm that gave lower scores to women and persons with disabilities, thereby reducing their chance of finding work."
Comparison: EDF red-lines page directly cites the AMS case as named in the body.
Decision: verified

## Claim 11: AMS algorithm "applying disability status as a negative scoring signal in an automated gatekeeping tool"

Source: https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
Source content: "gave lower scores to women and persons with disabilities, thereby reducing their chance of finding work"
Comparison: Body's framing ("disability status as a negative scoring signal") matches the source's "gave lower scores to ... persons with disabilities" within paraphrase tolerance.
Decision: verified

## Claim 12: "EDF advocacy materials specifically cite the HireVue case"

Source: https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
Source content: "HireVue, an AI-powered video-interviewing system used by large firms such as Goldman Sachs and Unilever, was found to massively discriminate against many persons with disabilities..."
Comparison: HireVue is explicitly cited by EDF as a case study in its red-lines advocacy.
Decision: verified

## Claim 13: "the AI-video-interviewing platform challenged by the US Federal Trade Commission in 2021"

Source: https://en.wikipedia.org/wiki/HireVue
Source content: "In November 2019, the Electronic Privacy Information Center filed a complaint to the Federal Trade Commission alleging that Hirevue's software caused harm to American workers through its collection of biometric data, bias towards those with different genders, races, sexual orientations and 'neurological differences'..."
Comparison: Two factual discrepancies. (a) HireVue was not "challenged by the US Federal Trade Commission" — the complaint was filed BY EPIC TO the FTC; the FTC was the recipient, not the challenger. (b) The year was 2019, not 2021. The cited source (EU AI Fund interview) does not contain this claim either. Named-entity and dated public-record class — Wikipedia is sufficient as canonical source per Source rule.
Decision: discrepancy

## Claim 14: AI-based social-benefits gatekeeping systems "characterised by EDF as surveillance"

Source: https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
Source content: "There have also been cases of discriminatory use of AI technologies against persons with disabilities by state and private entities in the allocation of social benefits."
Comparison: The red-lines page mentions discriminatory AI use in social-benefits allocation but the page consulted does not use the "surveillance" characterisation. The specific framing as surveillance may live in the position paper PDF (not fetched), but the canonical EDF web sources consulted in this pass do not corroborate the surveillance framing.
Decision: unverifiable

## Claim 15: paper "frames this as an application of the UNCRPD right to independent living and inclusion in the community (Article 19)"

Source: no canonical source found
Source content: The EDF publication page does not quote the paper's text on Article 19; the position paper PDF itself was not fetched.
Comparison: A claim about specific UNCRPD article invocation inside the paper text requires reading the paper itself, which was not retrievable in this pass. Cannot be verified or refuted from sources consulted.
Decision: unverifiable

## Claim 16: "Real-time biometric identification and categorisation in public spaces" listed as a red line by EDF

Source: https://www.edf-feph.org/red-lines-for-the-use-of-artificial-intelligence/
Source content: The fetched red-lines page mentions AMS (employment), HireVue (emotion-recognition in hiring/education), and social-benefits gatekeeping, but does not mention real-time biometric identification in public spaces.
Comparison: The body cites the red-lines URL as the source for this claim, but the fetched red-lines page consulted does not enumerate real-time biometric identification in public spaces among its red lines. The claim may live on a different EDF page or in the position paper PDF, but is not verified by the cited source.
Decision: unverifiable

## Claim 17: "the final text (entered into force 1 August 2024)"

Source: https://en.wikipedia.org/wiki/Artificial_Intelligence_Act
Source content: "It entered into force on 1 August 2024 and is described by the European Commission as the world's first comprehensive legal framework on AI."
Comparison: Body's entry-into-force date matches. Named-entity definitional / public-record class — Wikipedia sufficient as canonical source per Source rule.
Decision: verified

## Claim 18: "2023 Board Resolution on the EU AI Act, adopted on 1 April 2023"

Source: https://www.edf-feph.org/publications/resolution-on-the-eu-artificial-intelligence-act-for-the-inclusion-of-persons-with-disabilities/
Source content: "adopted by the Board of Directors of the European Disability Forum on the 1st of April 2023"
Comparison: Body's date matches exactly.
Decision: verified

## Claim 19: Resolution "sharpened the 2021 position paper into specific legislative demands: expansion of the prohibited AI practices list, stronger obligations for high-risk AI systems affecting disabled people's rights, and mandatory disability-inclusive conformity assessment procedures"

Source: https://www.edf-feph.org/publications/resolution-on-the-eu-artificial-intelligence-act-for-the-inclusion-of-persons-with-disabilities/
Source content: "Enlarge the list of prohibited uses of AI systems" (expanded prohibited practices); "the disproportionate risk to the rights of persons with disabilities in the areas identified as high risk" (high-risk obligations); "AI systems...are subject to mandatory accessibility requirements" (mandatory disability-inclusive conformity).
Comparison: All three demands are present in the Resolution as described.
Decision: verified

## Claim 20: EDF described final Act accessibility requirements as "partial win on accessibility"

Source: https://www.edf-feph.org/ai-act-agreement-partial-win-on-accessibility/
Source content: "a partial victory has been achieved in terms of accessibility for persons with disabilities, as high-risk Artificial Intelligence systems will have to meet requirements for accessibility."
Comparison: Body's "partial win" matches the source's "partial victory" and the URL slug `partial-win-on-accessibility`. Paraphrase tolerance.
Decision: verified

## Claim 21: "five-year Disability Inclusive Artificial Intelligence project (2023–2027)"

Source: https://www.edf-feph.org/projects/inclusive-artificial-intelligence-ai/
Source content: "Five years (January 1, 2023 – December 31, 2027)"
Comparison: Duration and year range match.
Decision: verified

## Claim 22: "Kave Noori — who joined EDF in January 2023" and "became EDF's primary specialist in AI and disability rights" / "AI Policy Officer"

Source: https://europeanaifund.org/newspublications/interview-with-kave-noori-and-marine-uldry-from-the-european-disability-forum-nothing-about-us-without-us-including-ai/ and https://www.edf-feph.org/projects/inclusive-artificial-intelligence-ai/
Source content: "Kave Noori is EDF's Artificial Intelligence Policy Officer and joined the organisation in January 2023" (EU AI Fund interview); "Kave Noori serves as the Artificial Intelligence Policy Officer responsible for this work" (Inclusive AI project page).
Comparison: Role title and start date match exactly across two independent sources.
Decision: verified

## Claim 23: Noori "presenting to European Parliament committees on Internal Market and Civil Liberties and Justice matters"

Source: no canonical source found
Source content: The Inclusive AI project page and the EU AI Fund interview describe Noori's policy-officer role generally but do not name presentations to specific European Parliament committees (IMCO / LIBE).
Comparison: Specific committee-presentation claim cannot be confirmed from sources consulted in this pass.
Decision: unverifiable

## Claim 24: Noori "participating in the UN Conference of State Parties to the CRPD"

Source: no canonical source found
Source content: Sources consulted in this pass do not mention Noori's participation in the UN Conference of State Parties to the CRPD.
Comparison: Specific UN-conference participation claim cannot be confirmed from sources consulted.
Decision: unverifiable

## Claim 25: "In October 2024 EDF published the *Disability-Inclusive Artificial Intelligence Act: A Guide to Monitor Implementation in Your Country*"

Source: https://www.edf-feph.org/publications/a-disability-inclusive-artificial-intelligence-act-a-guide-to-monitor-implementation-in-your-country/
Source content: "Publication Date: October 2024 ... a comprehensive guide to support organisations of persons with disabilities in understanding, implementing, and monitoring [the EU AI Act]"
Comparison: Title and October 2024 date match.
Decision: verified

## Claim 26: implementation guide "authored by Kave Noori" (body claim and parallel scalar:sources[5].note — "October 2024, authored by Kave Noori, ... Noori's role as EDF AI Policy Officer")

Source: https://www.edf-feph.org/publications/a-disability-inclusive-artificial-intelligence-act-a-guide-to-monitor-implementation-in-your-country/
Source content: The publication page lists Andre Felix as the author: "Andre Felix" (linked to https://www.edf-feph.org/profile/andre/). No mention of Kave Noori as an author on this page.
Comparison: Body claim and the frontmatter scalar `sources[5].note` (the entry whose `url:` is the implementation-toolkit page) both attribute authorship to Kave Noori. The publication page itself attributes authorship to Andre Felix. Direct contradiction with primary source.
Decision: discrepancy

## Claim 27: "an updated edition released in October 2025"

Source: https://www.edf-feph.org/projects/inclusive-artificial-intelligence-ai/
Source content: "an 'updated guide to monitor implementation in your country' (October 2025)"
Comparison: Inclusive AI project page references an October 2025 updated guide. Matches.
Decision: verified
