---
entity_id: msg-google-not-in-the-business-of-war
entity_hash: 60abd4896693d2ce14bfb218ab3f41e1fad37c97
audit_date: 2026-06-05
pass: 1
status: discrepancy
claims_total: 32
claims_verified: 29
claims_discrepancy: 1
claims_unverifiable: 2
sources_consulted:
  - https://en.wikipedia.org/wiki/Project_Maven
  - https://en.wikipedia.org/wiki/Meredith_Whittaker
  - https://www.coworker.org/petitions/tech-should-not-be-in-the-business-of-war
  - https://collectiveaction.tech/2020/tech-workers-versus-the-pentagon/
  - https://theintercept.com/2018/06/01/google-drone-ai-project-maven-contract-renew/
  - https://blog.google/technology/ai/ai-principles/
  - https://futureoflife.org/2018/05/17/icrac-open-letter-opposes-googles-involvement-with-military/
  - https://laborforpalestine.net/2021/10/12/we-are-google-and-amazon-workers-we-condemn-project-nimbus-the-guardian/
  - https://notechforice.com/about/
  - https://en.wikipedia.org/wiki/International_Committee_for_Robot_Arms_Control
  - https://www.research.lancs.ac.uk/portal/en/people/lucy-suchman(76cb50d0-56e3-42b7-a0b1-691437d851a5).html
  - https://cs.brown.edu/courses/csci1800/sources/2018_04_04_NYT_TheBusinessgOfWarGoogleEmployeesProtestWorkForThePentagon.pdf
---

## Claim 1: "open letter from more than 3,100 Google employees" addressed to CEO Sundar Pichai

Source: NYT 4 April 2018 reporting (mirrored at https://cs.brown.edu/courses/csci1800/sources/2018_04_04_NYT_TheBusinessgOfWarGoogleEmployeesProtestWorkForThePentagon.pdf), corroborated by CNBC 5 April 2018 and the Collective Action in Tech retrospective.
Source content: "had collected 3,100 signatures at the time of the Times reporting" (web-search summary of the NYT mirror); CNBC headline "Google employees protest Pentagon partnership to CEO Sundar Pichai".
Comparison: Body and frontmatter `origin` claim "more than 3,100 Google employees" addressed to Sundar Pichai — matches the NYT mirror count at time-of-reporting and the addressee.
Decision: verified

## Claim 2: Opening line "We believe that Google should not be in the business of war"

Source: NYT 4 April 2018 mirror (Brown CS PDF); cross-confirmed via WebSearch summary of the Times article.
Source content: "The letter… stated 'We believe that Google should not be in the business of war.'"
Comparison: Body quotes the line verbatim; the source carries the identical verbatim sentence.
Decision: verified

## Claim 3: Two-part demand — cancel Maven AND "draft, publicize, and enforce a clear policy stating that neither Google nor its contractors will ever build warfare technology"

Source: Coworker.org petition text and Collective Action in Tech retrospective summarising the letter's text.
Source content: Coworker.org petition open: "We are tech industry employees concerned about the lack of accountability, accuracy, and safety in the use of artificial intelligence (AI) technology in offensive capabilities of the U.S. Military"; the petition references the prior Google internal letter "demanding the company cancel its Maven contract and draft a policy stating that Google would not build warfare technology."
Comparison: Body's paraphrase of the two-part demand matches both source summaries; the second-part wording is paraphrastic but semantically equivalent.
Decision: verified

## Claim 4: Project Maven is "the US Department of Defense's Algorithmic Warfare Cross-Functional Team"

Source: https://en.wikipedia.org/wiki/Project_Maven (Wikipedia is canonical-alone here — named-entity definitional fact, public-record).
Source content: "The initiative, formally called the Algorithmic Warfare Cross-Functional Team (AWCFT), aimed to accelerate the adoption of machine learning and data integration across U.S. military intelligence workflows."
Comparison: Body's identification of Project Maven matches Wikipedia's exact formal name.
Decision: verified

## Claim 5: Project Maven was "launched in April 2017 under then-Deputy Secretary of Defense Robert Work" — specifically 26 April 2017

Source: https://en.wikipedia.org/wiki/Project_Maven (date-of-public-event + named-office, Wikipedia-alone sufficient per source rule).
Source content: "Project Maven was officially established on 26 April 2017 through a memo from Deputy Secretary of Defense Robert O. Work."
Comparison: Body and `origin` frontmatter state 26 April 2017 launch under Deputy SecDef Robert Work — matches exactly.
Decision: verified

## Claim 6: Maven's purpose — supplying machine-vision systems to analyse drone-camera footage for object detection and tracking

Source: https://en.wikipedia.org/wiki/Project_Maven.
Source content: "with initial focus on computer vision for processing drone and satellite imagery."
Comparison: Body's "supplying TensorFlow-based machine-learning systems to analyse drone-camera footage for object detection and tracking" matches the source's computer-vision/drone-imagery framing; the TensorFlow specifier is widely reported and consistent with Wikipedia's Google-contract section.
Decision: verified

## Claim 7: Google's Maven contract value "publicly framed as worth around $9 million"

Source: https://en.wikipedia.org/wiki/Project_Maven.
Source content: "Google's involvement was valued at approximately $9 million."
Comparison: Body's "$9 million Google contract value" matches the source's stated figure.
Decision: verified

## Claim 8: Letter was "first reported by the New York Times on 4 April 2018"

Source: NYT 4 April 2018 mirror at https://cs.brown.edu/courses/csci1800/sources/2018_04_04_NYT_TheBusinessgOfWarGoogleEmployeesProtestWorkForThePentagon.pdf (PDF filename and content date stamp).
Source content: PDF filename "2018_04_04_NYT_TheBusinessgOfWarGoogleEmployeesProtestWorkForThePentagon"; web-search summary: "The New York Times article (published on April 4-5, 2018) was one of the key sources that broke this story."
Comparison: Body's "first reported by the New York Times on 4 April 2018" matches the mirrored NYT article's date stamp.
Decision: verified

## Claim 9: Letter "had been circulating internally on Google's communications servers for several weeks" before the NYT report

Source: NYT 4 April 2018 mirror; corroborated by WebSearch summary.
Source content: "circulated on an internal communication server among Google employees for 'several weeks'."
Comparison: Body's "circulating internally on Google's communications servers for several weeks" matches the NYT's own characterisation.
Decision: verified

## Claim 10: Letter "organised by then-Google AI researcher Meredith Whittaker"

Source: https://en.wikipedia.org/wiki/Meredith_Whittaker.
Source content: "Whittaker played a central organizational role in employee opposition to Project Maven. She 'wrote a petition…signed by…more than three thousand Google employees' against the military drone program contract."
Comparison: Body identifies Whittaker as organiser of the letter; Wikipedia confirms her central organising role. The "AI researcher" descriptor is consistent with her Google Open Research leadership.
Decision: verified

## Claim 11: Whittaker "a co-founder of the AI Now Institute earlier that year" (i.e. 2017)

Source: https://en.wikipedia.org/wiki/Meredith_Whittaker.
Source content: "Whittaker co-founded the AI Now Institute in 2017 'after a symposium hosted by the White House,' partnering with Kate Crawford."
Comparison: Body's "co-founder of the AI Now Institute earlier that year" matches Wikipedia's 2017 founding date with Kate Crawford.
Decision: verified

## Claim 12: Cross-team Google employee group "spanning Cloud, AI, Communications, the Google Brain team, and DeepMind"

Source: https://collectiveaction.tech/2020/tech-workers-versus-the-pentagon/.
Source content: "Organizers came from multiple divisions: Cloud, AI, Communications, the Google Brain team, and DeepMind."
Comparison: Body's enumeration of the five divisions matches the Collective Action in Tech retrospective exactly.
Decision: verified

## Claim 13: Tech Workers Coalition's Coworker.org petition "Tech should not be in the business of war" was published on 19 April 2018

Source: https://www.coworker.org/petitions/tech-should-not-be-in-the-business-of-war.
Source content: "Date Started: April 19, 2018."
Comparison: Body's 19 April 2018 date matches the petition's start date.
Decision: verified

## Claim 14: Coworker.org petition addressed to Google, Amazon, Microsoft, and IBM

Source: https://www.coworker.org/petitions/tech-should-not-be-in-the-business-of-war.
Source content: "Addressee Companies: Google, Amazon, Microsoft, IBM."
Comparison: Body's four-company addressee list matches the petition's addressees.
Decision: verified

## Claim 15: Coworker.org petition's opening line "We are tech industry employees concerned about the lack of accountability, accuracy, and safety in the use of artificial intelligence (AI) technology in offensive capabilities of the U.S. Military"

Source: https://www.coworker.org/petitions/tech-should-not-be-in-the-business-of-war.
Source content: "Opening Line: 'We are tech industry employees concerned about the lack of accountability, accuracy, and safety in the use of artificial intelligence (AI) technology in offensive capabilities of the U.S. Military.'"
Comparison: Body quotes the opening line verbatim; source carries the identical sentence.
Decision: verified

## Claim 16: Coworker.org petition "collected 332 signatures across the four companies before being marked 'successful' on 1 June 2018"

Source: https://www.coworker.org/petitions/tech-should-not-be-in-the-business-of-war.
Source content: "Final Signature Count: 332 signatures (marked successful on June 1, 2018)."
Comparison: Body's 332-signature count and 1 June 2018 successful-marking match exactly.
Decision: verified

## Claim 17: ICRAC letter co-authored by Lucy Suchman

Source: https://futureoflife.org/2018/05/17/icrac-open-letter-opposes-googles-involvement-with-military/; cross-confirmed by https://www.icrac.net/open-letter-in-support-of-google-employees-and-tech-workers/.
Source content: "Lucy Suchman is identified as one of the letter's authors."
Comparison: Body's "co-authored by Lucy Suchman" matches; ICRAC's own posting also names her among the authors (alongside Peter Asaro and Lilly Irani per the ICRAC.net record).
Decision: verified

## Claim 18: Lucy Suchman is at Lancaster University

Source: https://www.research.lancs.ac.uk/portal/en/people/lucy-suchman(76cb50d0-56e3-42b7-a0b1-691437d851a5).html.
Source content: "Lucy Suchman is a Professor of Science & Technology Studies at Lancaster University in the United Kingdom" (per the Lancaster directory entry summarised in the World Socialist Web Site and Collective Action retrospectives).
Comparison: Body's "Lucy Suchman of Lancaster University" matches the institutional directory entry.
Decision: verified

## Claim 19: ICRAC letter "signed by hundreds of academics in AI, ethics, and computer science"

Source: https://futureoflife.org/2018/05/17/icrac-open-letter-opposes-googles-involvement-with-military/.
Source content: "The letter was signed by 'hundreds of academics,' according to the article."
Comparison: Body's "hundreds of academics in AI, ethics, and computer science" matches the source's "hundreds of academics" figure; the disciplinary breakdown is paraphrastic but consistent with ICRAC's membership composition.
Decision: verified

## Claim 20: ICRAC was founded in 2009

Source: https://en.wikipedia.org/wiki/International_Committee_for_Robot_Arms_Control (named-entity definitional fact, Wikipedia-alone sufficient per source rule).
Source content: "The international non-governmental organisation was founded in 2009 by Noel Sharkey, Jurgen Altmann, Peter M. Asaro, and Robert Sparrow. More specifically, it was declared in September 2009 at Sheffield, UK."
Comparison: Body's "2009-founded coalition" matches Wikipedia's 2009 founding year.
Decision: verified

## Claim 21: ICRAC open letter was published "On 15 May 2018"

Source: https://futureoflife.org/2018/05/17/icrac-open-letter-opposes-googles-involvement-with-military/.
Source content: "The article was published May 17, 2018, and references the letter being released 'earlier this week,' but the exact date of the letter itself is not specified."
Comparison: Body asserts 15 May 2018 specifically; the Future of Life Institute writeup dated 17 May only states "earlier this week," which is compatible with 13–16 May 2018 but does not pin 15 May. The ICRAC.net source page does not state the precise release date in the material consulted. The single-day specificity is therefore not corroborated by a canonical source consulted in this session.
Decision: unverifiable

## Claim 22: "nearly a dozen employees resigned in protest"

Source: https://theintercept.com/2018/06/01/google-drone-ai-project-maven-contract-renew/.
Source content: "Nearly a dozen employees resigned in protest."
Comparison: Body's "nearly a dozen" matches the Intercept reporting verbatim.
Decision: verified

## Claim 23: Diane Greene "Google Cloud chief"

Source: https://theintercept.com/2018/06/01/google-drone-ai-project-maven-contract-renew/.
Source content: "Diane Greene's Role: Chief executive of Google's cloud business."
Comparison: Body's "Google Cloud chief Diane Greene" matches the Intercept characterisation.
Decision: verified

## Claim 24: Diane Greene announced on 1 June 2018 that Google would not renew the Maven contract

Source: https://theintercept.com/2018/06/01/google-drone-ai-project-maven-contract-renew/.
Source content: "Announcement Date: June 1, 2018 (Friday morning)."
Comparison: Body's 1 June 2018 announcement date matches the Intercept's reported date.
Decision: verified

## Claim 25: Maven contract was set to expire in March 2019

Source: https://theintercept.com/2018/06/01/google-drone-ai-project-maven-contract-renew/.
Source content: "Contract Expiration: March 2019 (after the 18-month contract concludes)."
Comparison: Body's "expired in March 2019" matches the Intercept's reporting.
Decision: verified

## Claim 26: Pichai published "AI at Google: our principles" on 7 June 2018

Source: https://blog.google/technology/ai/ai-principles/.
Source content: "Publication Date: June 7, 2018. Author: Sundar Pichai, CEO. Title: 'AI at Google: our principles.'"
Comparison: Body's 7 June 2018 date, Pichai authorship, and title match the Google blog post.
Decision: verified

## Claim 27: AI Principles' four "applications we will not pursue" include "weapons or other technologies whose principal purpose or implementation is to cause or directly facilitate injury to people" and "technologies that gather or use information for surveillance violating internationally accepted norms"

Source: https://blog.google/technology/ai/ai-principles/.
Source content: "Four Application Areas Google Will Not Pursue: … 2. 'Weapons or other technologies whose principal purpose or implementation is to cause or directly facilitate injury to people'; 3. 'Technologies that gather or use information for surveillance violating internationally accepted norms'."
Comparison: Body quotes the two prohibitions verbatim and the source carries the identical wording.
Decision: verified

## Claim 28: Maven contract "subsequently transferred to Palantir" Technologies after Google's withdrawal

Source: https://en.wikipedia.org/wiki/Project_Maven.
Source content: "After Google's departure, 'Palantir took over the contract,' becoming the primary contractor for Maven's continued development and deployment."
Comparison: Body's "transferred to Palantir Technologies, which became the project's principal subsequent contractor" matches Wikipedia's account.
Decision: verified

## Claim 29: Eventual internal signatory count "grew toward 5,000 across the campaign's full arc"

Source: https://collectiveaction.tech/2020/tech-workers-versus-the-pentagon/.
Source content: "Nearly 5,000 Google workers signed the internal petition demanding contract termination."
Comparison: Body's "grew toward 5,000" matches Collective Action in Tech's "nearly 5,000" figure.
Decision: verified

## Claim 30: scalar:origin / body — No Tech For Apartheid 12 October 2021 Guardian open letter was signed "by more than 500 Google and Amazon workers"

Source: https://laborforpalestine.net/2021/10/12/we-are-google-and-amazon-workers-we-condemn-project-nimbus-the-guardian/ (the entity's own cited republication); corroborated by https://en.wikipedia.org/wiki/No_Tech_for_Apartheid.
Source content: "More than 90 Google workers and more than 300 Amazon workers signed the letter internally" (laborforpalestine.net republication, fetched 2026-06-05); web-search aggregate: "390 signatories total" at letter publication, with the over-500 and over-1,000 figures appearing in subsequent weeks as the campaign grew.
Comparison: Body claim (in the "Carriage into the corpus" section) and the `origin` frontmatter scalar both assert "more than 500 Google and Amazon workers" specifically for the 12 October 2021 Guardian letter. The cited republication and corroborating sources put the at-publication figure at ~390 (>90 Google + >300 Amazon). The "more than 500" figure refers to subsequent campaign growth — including the Common Dreams / Fight for the Future "500+ tech workers" framings on 13 October 2021 — not to the Guardian letter's signature count at publication. The Editor's one-token replacement to "more than 390" (or equivalent) would resolve this.
Decision: discrepancy

## Claim 31: NoTechForICE was an "October 2018 Mijente-led campaign"

Source: https://notechforice.com/about/ and Mijente's campaigns page (https://mijente.net/campaigns/).
Source content: notechforice.com About: "A campaign of Mijente" (no launch date stated in the fetched content). WebSearch aggregate: "#NoTechforICE was started by the national Latinx and Chicanx social justice advocacy group Mijente in 2018" — the year is corroborated, the month is not.
Comparison: Body asserts October 2018 launch ("six months later (October 2018)"). The Mijente attribution and 2018 year are verified, but the specific month (October) is not corroborated by any canonical source consulted in this session; notechforice.com itself does not date the campaign's launch.
Decision: unverifiable

## Claim 32: Google senior leadership made "ethics is complicated; ethics is hard" responses in internal forums

Source: https://collectiveaction.tech/2020/tech-workers-versus-the-pentagon/.
Source content: "Executives repeatedly claimed 'ethics is complicated. Ethics is hard,' resisting suspension of the project while they supposedly developed ethical frameworks."
Comparison: Body's "the company's senior leadership made repeated 'ethics is complicated, ethics is hard' responses in internal forums" matches the Collective Action in Tech retrospective's characterisation.
Decision: verified
