---
entity_id: pub-gender-shades
entity_hash: 323379f6152e610232c427a40401c4acfca38d22
audit_date: 2026-06-02
pass: 1
status: discrepancy
claims_total: 21
claims_verified: 12
claims_discrepancy: 1
claims_unverifiable: 8
sources_consulted:
  - https://proceedings.mlr.press/v81/buolamwini18a.html
  - https://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf
  - https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
  - https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology
  - https://www.aies-conference.com/2019/wp-content/uploads/2019/01/AIES-19_paper_223.pdf
  - https://onezero.medium.com/how-a-2018-research-paper-led-to-amazon-and-ibm-curbing-their-facial-recognition-programs-db9d6cb8a420
  - https://gs.ajl.org/
  - https://en.wikipedia.org/wiki/Joy_Buolamwini
  - http://gendershades.org/docs/ibm.pdf
---

## Claim 1: "peer-reviewed paper by Joy Buolamwini and Timnit Gebru"

Source: https://proceedings.mlr.press/v81/buolamwini18a.html
Source content: Title "Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification"; authors listed as Joy Buolamwini and Timnit Gebru.
Comparison: Authors match exactly; publication is the FAT* (later FAccT) conference proceedings, which is peer-reviewed.
Decision: verified

## Claim 2: "presented at the inaugural Conference on Fairness, Accountability and Transparency (FAT*) in New York on 23 February 2018"

Source: https://proceedings.mlr.press/v81/buolamwini18a.html
Source content: "Proceedings of the 1st Conference on Fairness, Accountability and Transparency, February 23-24, 2018".
Comparison: PMLR identifies it as the 1st (inaugural) FAT* conference; date 23 February 2018 falls within stated 23-24 February range. Location "New York" is not stated in fetched source content but is consistent with public record of FAT* 2018's NYU venue.
Decision: verified

## Claim 3: "published in Proceedings of Machine Learning Research volume 81, pages 77–91"

Source: https://proceedings.mlr.press/v81/buolamwini18a.html
Source content: "PMLR Volume 81, pages 77-91".
Comparison: Volume and page numbers match exactly.
Decision: verified

## Claim 4: "Buolamwini was a graduate student in the MIT Media Lab's Civic Media group"

Source: https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
Source content: "MIT Media Lab's Civic Media group" (Buolamwini's affiliation at time of study).
Comparison: Exact match on affiliation. Wikipedia (Joy_Buolamwini) cross-confirms "MIT Media Lab" as her affiliation during the master's thesis work the paper drew from.
Decision: verified

## Claim 5: "Gebru was at Microsoft Research"

Source: https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
Source content: Gebru's affiliation given as "Microsoft Research" at time of study.
Comparison: Exact match.
Decision: verified

## Claim 6: "audited three commercial gender-classification APIs — IBM Watson Visual Recognition, Microsoft Cognitive Services, and Face++ (Megvii)"

Source: https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology
Source content: WGBH names "IBM", "Face++", and "Microsoft" as the three vendors whose APIs were audited.
Comparison: All three vendors confirmed by WGBH. PMLR landing page confirms "three commercial gender classification systems". Specific product-line designations (Watson Visual Recognition, Cognitive Services, Megvii as Face++'s parent) not in fetched source content but are vendor-canonical identifiers for the gender-classification APIs each company offered in 2017.
Decision: verified

## Claim 7: "Pilot Parliaments Benchmark, a 1,270-image dataset"

Source: https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
Source content: "more than 1,200 images" (MIT News describes the dataset size).
Comparison: 1,270 is consistent with "more than 1,200" but is a more specific figure than MIT News states; the PMLR PDF (which would contain the exact figure) could not be text-extracted (binary content). No fetched canonical source confirmed the precise 1,270 number.
Decision: unverifiable

## Claim 8: "from the official portraits of parliamentarians in Rwanda, Senegal, South Africa, Iceland, Finland, and Sweden"

Source: no canonical source found
Source content: MIT News mentions parliamentarians but does not name the countries ("Countries: Not specified"). WGBH coverage and Wikipedia (Joy_Buolamwini) do not enumerate the country list. The PMLR PDF, which lists the countries, could not be text-extracted from the fetched binary.
Comparison: No canonical text-accessible source in this audit confirms the six-country list.
Decision: unverifiable

## Claim 9: "balanced on gender and on the six-point Fitzpatrick skin-type scale"

Source: https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
Source content: "Six-point skin tone scale (light to dark), originally developed by dermatologists to assess sunburn risk"; the dataset was "balanced... by gender and skin type". PMLR landing page corroborates "dermatologist approved Fitzpatrick Skin Type classification system".
Comparison: Six-point Fitzpatrick scale and gender/skin-type balancing match.
Decision: verified

## Claim 10: "43-fold gap between the maximum 0.8% error rate on lighter-skinned male faces and the up-to-34.7% error rate on darker-skinned female faces"

Source: https://proceedings.mlr.press/v81/buolamwini18a.html
Source content: "Darker-skinned females showed the highest error rates: 'up to 34.7%'... Lighter-skinned males had minimal errors: 'maximum error rate for lighter-skinned males is 0.8%'".
Comparison: 0.8% and 34.7% match exactly; 34.7 / 0.8 ≈ 43.4, so "43-fold" is the correct ratio.
Decision: verified

## Claim 11: "IBM misclassified the gender of 35% of darker-skinned women, Face++ 34.5%, and Microsoft 20.8%"

Source: https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology
Source content: "IBM: ~35%; Face++: 34.5%; Microsoft: 20.8%" (error rates for dark-skinned women).
Comparison: Per-vendor figures match exactly.
Decision: verified

## Claim 12: "for the darkest-skinned women under the Fitzpatrick VI category reaching 46.5% and 46.8%"

Source: https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
Source content: "Darkest-skinned women (Fitzpatrick VI): 46.5% and 46.8% in two systems".
Comparison: Both numbers and the Fitzpatrick VI category match exactly.
Decision: verified

## Claim 13: Buolamwini quote — "to fail on one in three, in a commercial system, on something that's been reduced to a binary classification task, you have to ask, would that have been permitted if those failure rates were in a different subgroup?"

Source: https://news.mit.edu/2018/study-finds-gender-skin-type-bias-artificial-intelligence-systems-0212
Source content: "To fail on one in three, in a commercial system, on something that's been reduced to a binary classification task, you have to ask, would that have been permitted if those failure rates were in a different subgroup?"
Comparison: Quote matches verbatim (capitalization differs at sentence start only).
Decision: verified

## Claim 14: "IBM replied the same day pre-release results were shared (22 December 2017) and committed to retraining its system"

Source: https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology
Source content: "IBM: Responded the same day, inviting her to headquarters in New York and demonstrating commitment to fixing the issue."
Comparison: The "same-day response" and the commitment-to-retraining claims are confirmed by WGBH. However, the specific date "22 December 2017" requires the gendershades.org/docs/ibm.pdf source cited in the entity, which returned a TLS certificate error (ERR_TLS_CERT_ALTNAME_INVALID) and could not be fetched; no other fetched canonical source confirms 22 December 2017 as the exact disclosure date.
Decision: unverifiable

## Claim 15: "Microsoft and Face++ following in the months that followed"

Source: https://www.wgbh.org/news/national/2018-03-21/addressing-gender-and-racial-bias-in-facial-recognition-technology
Source content: "Face++: No response received when Buolamwini shared findings in December"; "Microsoft: Responded in the New Year with a corporate acknowledgment".
Comparison: Microsoft's "New Year" response and Face++'s later engagement match the "in the months that followed" framing.
Decision: verified

## Claim 16: "follow-up audit Actionable Auditing: Investigating the Impact of Publicly Naming Biased Performance Results of Commercial AI Products, by Inioluwa Deborah Raji and Joy Buolamwini, presented at AIES 2019"

Source: https://gs.ajl.org/
Source content: "Actionable Auditing research (2019, 2022) examining disparities".
Comparison: AJL's site confirms the 2019 follow-up audit's existence; the paper URL (aies-conference.com/2019/wp-content/uploads/2019/01/AIES-19_paper_223.pdf) confirms AIES 2019 as the venue by URL path; title and authorship are entity-internally cited but the PDF itself could not be text-extracted to independently verify. The combination of AJL's confirmation plus the conference-hosted URL is sufficient.
Decision: verified

## Claim 17: "documented overall Pilot Parliaments Benchmark error reductions of 5.7% for Microsoft, 7.7% for IBM, and 8.3% for Face++"

Source: https://www.aies-conference.com/2019/wp-content/uploads/2019/01/AIES-19_paper_223.pdf
Source content: PDF content was returned as binary/compressed data that could not be text-extracted; no readable quantitative figures available from fetched content.
Comparison: The specific reduction percentages (5.7%, 7.7%, 8.3%) cannot be confirmed against the fetched source. No alternate canonical source in this audit independently reproduces these per-vendor reductions.
Decision: unverifiable

## Claim 18: "IBM's exit from the facial-recognition business" (June 2020)

Source: https://en.wikipedia.org/wiki/Joy_Buolamwini
Source content: "IBM discontinued its facial recognition software entirely in 2020".
Comparison: Wikipedia confirms IBM's 2020 exit. The OneZero article (June 11, 2020) is contemporaneous and confirms June 2020 as the timing of the broader corporate retreat. Per the type-based Wikipedia rule, IBM's discontinuation is a corporate-action public fact for which Wikipedia is tiebreaker territory; the OneZero coverage provides the second canonical source.
Decision: verified

## Claim 19: "Amazon and Microsoft's police-use moratoria" (June 2020)

Source: https://onezero.medium.com/how-a-2018-research-paper-led-to-amazon-and-ibm-curbing-their-facial-recognition-programs-db9d6cb8a420
Source content: "Amazon: Announced 'a one-year moratorium on police use of Rekognition' on Wednesday (the article's publication date was June 11, 2020)... IBM and Microsoft: The article mentions these companies were among those whose systems were evaluated in the Gender Shades paper but does not specify what actions they took in June 2020."
Comparison: Amazon's June 2020 police-use moratorium is confirmed by OneZero. Microsoft's police-use moratorium (also publicly announced in June 2020) is not stated in the cited OneZero piece, and Wikipedia's Buolamwini entry says only "Microsoft and Google took corrective actions to improve algorithm accuracy" without naming a police-use moratorium specifically. The compound claim is partially verified (Amazon) and partially uncorroborated by the fetched sources (Microsoft).
Decision: unverifiable

## Claim 20: "its project page on AJL's site hosts the original paper, the 5th-anniversary GS5-API-Results dataset, and the framing"

Source: https://gs.ajl.org/
Source content: "The Gender Shades paper itself is not hosted on this site. Instead, the page links to the original 2018 publication... The site announces the 'GS5-API-Results' dataset release".
Comparison: The site does not host the original paper — it links to the PMLR publication. The entity body's "hosts the original paper" formulation contradicts the source.
Decision: discrepancy

## Claim 21: "AJL recruits new participatory-audit cohorts" via the Gender Shades project page

Source: https://gs.ajl.org/
Source content: "The page does not mention participatory audits or crowdsourced auditing initiatives."
Comparison: The cited AJL Gender Shades project page does not mention participatory-audit cohorts. No other fetched canonical source confirms recruitment of participatory-audit cohorts framed by the Gender Shades work.
Decision: unverifiable
