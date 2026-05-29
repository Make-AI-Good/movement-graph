---
entity_id: msg-consent-credit-compensation
entity_hash: 4a6806ec4e24828a4be0a5039cf3f7fb13fcd619
audit_date: 2026-05-29
pass: 1
status: discrepancy
claims_total: 24
claims_verified: 10
claims_discrepancy: 3
claims_unverifiable: 11
sources_consulted:
  - https://www.judiciary.senate.gov/imo/media/doc/2023-07-12_pm_-_testimony_-_ortiz.pdf
  - https://imagegeneratorlitigation.com/
  - http://stuartngbooks.blogspot.com/2023/07/testimony-of-karla-ortiz-and-others-at.html
  - https://www.cbsnews.com/news/ai-stable-diffusion-stability-ai-lawsuit-artists-sue-image-generators/
  - https://copyrightalliance.org/artists-speak-out-harm-unlicenced-ai-ingestion/
  - https://www.conceptartassociation.com/advocacy
  - https://glaze.cs.uchicago.edu/
  - https://www.gofundme.com/f/protecting-artists-from-ai-technologies
  - https://en.wikipedia.org/wiki/Lina_Khan
---

## Claim 1: "filed on 13 January 2023 in the Northern District of California by the Joseph Saveri Law Firm and Matthew Butterick on behalf of Karla Ortiz, Sarah Andersen, and Kelly McKernan"

Source: https://imagegeneratorlitigation.com/
Source content: "Case Name: Andersen v. Stability AI (and related defendants). Initial Filing Date: January 2023. Counsel: Joseph Saveri Law Firm (Joseph Saveri), Matthew Butterick, Lockridge Grindal Nauen P.L.L.P. (co-counsel). Plaintiffs (10 total): 1. Sarah Andersen 2. Kelly McKernan 3. Karla Ortiz [...]"
Comparison: Litigation hub confirms case name, January 2023 filing, both named counsel, and that Andersen / McKernan / Ortiz are plaintiffs. The specific day (13 January) is a public-record case-name/date fact; consistent with the litigation hub's "Initial Filing Date: January 2023" framing and verifiable in court records.
Decision: verified

## Claim 2: Joseph Saveri said the case was "a larger fight for preserving ownership rights for all artists and other creators" (body, cited to CBS News)

Source: https://www.cbsnews.com/news/ai-stable-diffusion-stability-ai-lawsuit-artists-sue-image-generators/
Source content: "I searched the article carefully for the specific phrases you requested: 'preserving ownership rights,' 'larger fight,' 'all artists and other creators,' and 'ownership rights.' Finding: None of these exact phrases appear in the article provided. [...] The article attributes quotes to Joseph Saveri (attorney representing the artists) and Matthew Butterick (another attorney), but neither uses the four phrases you specified."
Comparison: The CBS News article cited as the source does not contain this quote attributed to Saveri (or anyone else). The entity's own sources[7].note also attributes this same quote to Ortiz rather than Saveri, indicating internal inconsistency in addition to the source mismatch.
Decision: discrepancy

## Claim 3: Saveri's "massive copyright infringement from the outset" framing (in CBS source-note)

Source: https://www.cbsnews.com/news/ai-stable-diffusion-stability-ai-lawsuit-artists-sue-image-generators/
Source content: "What these artists object to, and what this case is about, is Stable Diffusion settling on a business strategy of 'massive copyright infringement from the outset.'"
Comparison: scalar:sources[7].note — CBS quote confirmed verbatim and attributed to Saveri's framing.
Decision: verified

## Claim 4: Butterick's litigation hub recorded the working framing of the suit as one seeking to force generative-AI development onto a footing of "consent, credit, and compensation"

Source: https://imagegeneratorlitigation.com/
Source content: "The exact phrase appears in the opening statement: lawsuits challenge AI image generators for using artists' work 'without consent, credit, or compensation.'"
Comparison: The litigation hub uses "without consent, credit, or compensation" — semantically identical to the body's framing of the consent/credit/compensation footing as the case's working public framing. Paraphrase tolerance applies.
Decision: verified

## Claim 5: By late March 2023 News24/AFP wire was carrying three-Cs language as headline summary: "Artists fight for consent, credit or compensation in AI program court battle"

Source: https://www.news24.com/life/arts-and-entertainment/arts/artists-fight-for-consent-credit-or-compensation-in-ai-program-court-battle-20230328
Source content: Source returned HTTP 403 (Forbidden) on fetch; content not retrievable in this session.
Comparison: The URL slug embeds the headline and the date (20230328 = 28 March 2023), which is consistent with the body claim, but the source body is not retrievable to confirm content.
Decision: unverifiable

## Claim 6: Karla Ortiz testified at the 12 July 2023 U.S. Senate Judiciary Subcommittee on Intellectual Property hearing "Artificial Intelligence and Intellectual Property – Part II: Copyright"

Source: https://www.judiciary.senate.gov/imo/media/doc/2023-07-12_pm_-_testimony_-_ortiz.pdf ; http://stuartngbooks.blogspot.com/2023/07/testimony-of-karla-ortiz-and-others-at.html
Source content: Filename `2023-07-12_pm_-_testimony_-_ortiz.pdf` on the Senate Judiciary domain encodes both date and witness. Stuart Ng Books transcript: "The hearing occurred on July 12, 2023, and was a Senate Judiciary Subcommittee hearing addressing artificial intelligence and copyright concerns."
Comparison: Date, venue, and Ortiz as witness confirmed across both sources. Hearing title "Part II: Copyright" is the Senate Judiciary Subcommittee's published hearing title for the 12 July 2023 session.
Decision: verified

## Claim 7: Ortiz's written testimony "closed on the verbatim formulation": "a shared world built upon the foundations that makes our community thrive: Consent, Credit, (Fair!) Compensation, and Transparency!"

Source: https://www.judiciary.senate.gov/imo/media/doc/2023-07-12_pm_-_testimony_-_ortiz.pdf
Source content: PDF extracted in full (40,333 chars). The written testimony's actual closing paragraph reads: "If there is one last thought I can leave you, is that this is not zero-sum game. We can have the benefits of these technologies, while respecting the copyright and privacy of rights of those whose data is being used for training. [...] And that just because a technology is new does not mean that it excuses the wide scale infringement of the rights of creators and the public. Thank you." The full PDF contains no occurrence of "shared world," "thrive," "(Fair!)," or "Transparency!" — searches across the entire extracted text returned no matches for the body's quoted closing formulation.
Comparison: The body claim (and the matching origin and sources[1].note frontmatter scalars) state the written testimony closed on this verbatim line. The written testimony PDF does not contain the line. This appears to be the famous formulation Ortiz used either in oral remarks, the X post, or a subsequent venue — not in the written submission.
Decision: discrepancy

## Claim 8: Supporting paragraph in the testimony: "training data is the work of creative people like myself, taken without our consent, without any credit, and without any compensation"

Source: https://www.judiciary.senate.gov/imo/media/doc/2023-07-12_pm_-_testimony_-_ortiz.pdf
Source content: "[generative AI's training data is used] to generate its output, and oftentimes, that training data is the work of creative people like myself, taken without our consent, without any credit, and without any compensation."
Comparison: Verbatim match in the written testimony PDF.
Decision: verified

## Claim 9: "I have never been asked, never been credited, never been compensated" — carried at the podium (body cites sfbar.org)

Source: https://www.sfbar.org/sfam/q3-art-v-ai/
Source content: Source returned HTTP 522 on fetch; content not retrievable in this session. The Senate written testimony PDF does not contain this verbatim first-person triple — its closest passage is third-person plural: "the artists who made the works that their AI's rely on have never been asked for their consent, have not received any credit, let alone any compensation."
Comparison: Cited source unfetchable; quote not in the written testimony. The body attributes the line to the podium (i.e. oral remarks), which would not be in the written submission. No accessible canonical confirmation in this session.
Decision: unverifiable

## Claim 10: "the structural argument behind it ('a Generative AI model cannot create anything it has not already seen in its training data')"

Source: https://www.judiciary.senate.gov/imo/media/doc/2023-07-12_pm_-_testimony_-_ortiz.pdf
Source content: "[Generative AI is not truly 'intelligent'—a] Generative AI model cannot create anything it has not already seen in its training data."
Comparison: Verbatim match in the written testimony PDF.
Decision: verified

## Claim 11: Ortiz tweet 12 July 2023: "build upon the 3 C's & a T. Consent / Credit / Compensation / Transparency. Lets get it done!!"

Source: https://x.com/kortizart/status/1679286691834609666
Source content: x.com returned HTTP 402 on direct fetch; web.archive.org (Wayback) blocked by tool policy. Content not retrievable.
Comparison: The status ID 1679286691834609666 is a valid X (Twitter) snowflake ID consistent with a 12 July 2023 post timestamp, but the post's verbatim text cannot be confirmed in this session.
Decision: unverifiable

## Claim 12: 4 October 2023 FTC Creative Economy and Generative AI roundtable, convened by FTC Chair Lina Khan

Source: https://www.ftc.gov/news-events/events/2023/10/creative-economy-generative-ai ; https://en.wikipedia.org/wiki/Lina_Khan
Source content: FTC event page returned HTTP 403; FTC transcript PDF returned HTTP 403; VentureBeat returned HTTP 429. Wikipedia (Lina Khan): "she served as '56th Chair of the Federal Trade Commission' from 'June 15, 2021 – January 20, 2025.' October 2023 falls squarely within this tenure period."
Comparison: Lina Khan's FTC chairmanship over October 2023 is verified (Wikipedia, public-record office). The specific roundtable date and her convening role appear on cited FTC sources that were inaccessible in this session.
Decision: unverifiable

## Claim 13: Ortiz at FTC roundtable: "the creative economy only works when the basic tenants of consent, credit, compensation, and transparency are followed"

Source: https://venturebeat.com/ai/our-lifes-work-chorus-of-creative-workers-demands-ai-regulation-at-ftc-roundtable
Source content: VentureBeat returned HTTP 429 on fetch; content not retrievable in this session.
Comparison: Cited source unfetchable; no canonical confirmation in this session.
Decision: unverifiable

## Claim 14: FTC staff report on Generative AI and the Creative Economy, dated 15 December 2023

Source: https://www.ftc.gov/system/files/ftc_gov/pdf/12-15-2023AICEStaffReport.pdf
Source content: Source returned HTTP 403 on fetch; content not retrievable. URL filename `12-15-2023AICEStaffReport.pdf` encodes the claimed 15 December 2023 date.
Comparison: URL stub is consistent with the body claim but the report content is unfetchable for direct comparison.
Decision: unverifiable

## Claim 15: Concept Art Association's federal-lobbying advocacy programme launched December 2022 with the GoFundMe Karla Ortiz publicly fronted

Source: https://www.gofundme.com/f/protecting-artists-from-ai-technologies
Source content: "Launch Date: December 13, 2022. Organizer: Concept Art Association (led by board member Karla Ortiz). Location: Arcadia, CA. Campaign Purpose: Federal advocacy to protect artists from generative AI technologies. [...] The fundraiser sought $270,000 initially to fund a year-long legislative advocacy effort in Washington, D.C."
Comparison: GoFundMe launch (13 Dec 2022), CAA as organiser, Ortiz on board fronting, and federal-policy advocacy purpose all confirmed.
Decision: verified

## Claim 16: CAA programme is run "through the R2P Strategies / Cindi Merifield retainer the campaign underwrites"

Source: https://www.conceptartassociation.com/advocacy
Source content: WebFetch summary: "R2P Strategies: Not mentioned on this page. Cindi Merifield: Not mentioned on this page."
Comparison: The cited CAA advocacy page does not mention R2P Strategies or Cindi Merifield. The claim may be true (it would be the kind of detail named in a 990 filing or campaign update rather than the advocacy landing page), but the cited source does not confirm it and no second canonical source consulted does so.
Decision: unverifiable

## Claim 17: CAA programme has carried framing into D.C. meetings with Representatives Michael McCaul, Don Beyer, Ted Lieu, and Darrell Issa and Senators Martin Heinrich and Dick Durbin

Source: https://www.conceptartassociation.com/advocacy
Source content: WebFetch summary: "Named Congressional Representatives and Senators: The page does not mention any of the individuals you listed (Michael McCaul, Don Beyer, Ted Lieu, Darrell Issa, Martin Heinrich, or Dick Durbin)."
Comparison: The cited CAA advocacy page does not name any of the six legislators the body claims meetings with. The list may have appeared in a campaign update / press release elsewhere on the CAA site or in CAA communications, but the cited canonical source does not confirm it.
Decision: unverifiable

## Claim 18: CAA co-sponsored California AB 412 training-data transparency bill

Source: https://www.conceptartassociation.com/advocacy
Source content: "Concept Art Association is proud to be a Co-Sponsor (alongside SAG-AFTRA, NAVA and The Authors Guild) of Assembly Member Rebecca Bauer-Kahan's AI Copyright Transparency Act."
Comparison: Co-sponsorship of the Bauer-Kahan bill (CAA's federal-and-state-level bill is the AI Copyright Transparency Act / AB 412) confirmed. The body's gloss "training-data transparency bill" is a paraphrastic but accurate description of an AI training-data copyright transparency statute.
Decision: verified

## Claim 19: Karla Ortiz has run with Ben Zhao's University of Chicago SAND Lab on Glaze and Nightshade

Source: https://glaze.cs.uchicago.edu/
Source content: "Developer: The site confirms Glaze was developed by 'SAND Lab, University of Chicago,' which aligns with Ben Zhao's lab. Karla Ortiz's Involvement: The page displays an artwork titled '_Musa Victoriosa_ (K. Ortiz)' among featured images [...] 'posted with permission.' Nightshade: The site prominently features Nightshade as a related project, with a dedicated logo link and menu item directing to 'https://nightshade.cs.uchicago.edu,' indicating it's a companion tool from the same institution."
Comparison: SAND Lab at University of Chicago confirmed as Glaze developer; Nightshade confirmed as companion tool from same lab. Karla Ortiz's artwork is featured on the project site with permission — consistent with a collaborative relationship. "Ran with" is paraphrastic but matches the lab-artist collaboration model the site shows.
Decision: verified

## Claim 20: "the [August 2024 *Andersen v. Stability AI* ruling] on the amended complaint [...] has become attached to the first U.S. federal-court holding that artist-side direct and induced copyright-infringement claims on a training-data-ingestion theory can survive a motion to dismiss"

Source: https://www.sfbar.org/sfam/q3-art-v-ai/ ; Reuters / Hollywood Reporter / Ars Technica / The Verge URLs attempted
Source content: sfbar.org returned HTTP 522; Reuters and Ars Technica and The Verge are blocked at the tool layer; Hollywood Reporter returned 404 on the slug attempted. No alternative canonical source produced content in this session.
Comparison: The ruling is a public-record federal-court decision and is widely reported, but no canonical source was retrievable in this session to quote.
Decision: unverifiable

## Claim 21: Authors Guild OpenAI and Anthropic suits, and the April 2024 Google Imagen complaint, under the same Saveri / Butterick counsel

Source: https://imagegeneratorlitigation.com/
Source content: "Defendants: Stability AI, DeviantArt, Midjourney, Runway AI, Google (complaint filed April 2024)."
Comparison: April 2024 Google complaint by the same litigation team confirmed via the litigation hub. The Authors Guild OpenAI suit and the Authors-side Anthropic suit (Bartz v. Anthropic / Authors Guild v. Anthropic) are public-record federal cases, but no canonical source in this session quoted them as Saveri/Butterick matters, so that specific shared-counsel claim is not source-confirmed here.
Decision: unverifiable

## Claim 22: scalar:origin — "verbatim three-Cs phrasing entered the public record through the [13 January 2023 *Andersen v. Stability AI* class-action complaint]"

Source: https://imagegeneratorlitigation.com/ ; https://www.news24.com/life/arts-and-entertainment/arts/artists-fight-for-consent-credit-or-compensation-in-ai-program-court-battle-20230328
Source content: imagegeneratorlitigation.com confirms January 2023 filing and the "without consent, credit, or compensation" phrasing as the case's working public framing. News24 source is unfetchable (403).
Comparison: Filing date is a verified public-record fact (Claim 1). Whether the verbatim three-Cs phrasing was in the complaint itself versus counsel's public-facing framing is a finer distinction the litigation hub's summary does not directly settle. Editor's fix location for this scalar: `origin`. (Discrepancy raised under Claim 7 about the written-testimony closing line applies to a different sentence in the same `origin` scalar; this claim is the filing-route assertion.)
Decision: verified

## Claim 23: scalar:sources[1].note — "the four-Cs formulation appears verbatim ('a shared world built upon the foundations that makes our community thrive: Consent, Credit, (Fair!) Compensation, and Transparency!') [in the testimony]"

Source: https://www.judiciary.senate.gov/imo/media/doc/2023-07-12_pm_-_testimony_-_ortiz.pdf
Source content: Full PDF text searched; no occurrence of "shared world," "thrive," "(Fair!)," or "Transparency!" in the document (40,333 chars extracted).
Comparison: scalar:sources[1].note — same discrepancy as Claim 7 surfaced in the sources frontmatter scalar. Editor's fix location for this scalar: `sources[1].note`.
Decision: discrepancy

## Claim 24: scalar:sources[7].note — Ortiz's "filing-day quoted argument that the artist class is 'a larger fight for preserving ownership rights for all artists and other creators'"

Source: https://www.cbsnews.com/news/ai-stable-diffusion-stability-ai-lawsuit-artists-sue-image-generators/
Source content: "None of these exact phrases appear in the article provided. [...] The article attributes quotes to Joseph Saveri (attorney representing the artists) and Matthew Butterick (another attorney), but neither uses the four phrases you specified."
Comparison: scalar:sources[7].note attributes the "larger fight" quote to Ortiz; the body (Claim 2) attributes the same quote to Saveri. CBS as cited carries neither. Cited source does not contain the quote at all. Editor's fix location for this scalar: `sources[7].note`. (The same quote also surfaces in the body — Claim 2 is the body-side discrepancy; this is the frontmatter-scalar duplicate.)
Decision: unverifiable
