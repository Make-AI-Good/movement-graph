---
entity_id: fund-internetstiftelsen
entity_hash: adf7a40c8052dd495ad05174433e649dd1f9a2ec
audit_date: 2026-09-01
pass: 1
status: corrections-pending
claims_total: 26
claims_corroborated: 3
claims_primary_sourced: 11
claims_single_source: 3
claims_uncorroborated: 5
open_corrections: 4
sources_consulted:
  - https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/
  - https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/records-and-regulations/
  - https://internetstiftelsen.se/om-oss/press/pressmeddelanden/internetstiftelsen-vill-lara-fler-om-ai-slapper-ny-kunskapssatsning/
  - https://svenskarnaochinternet.se/utvalt/svenskarna-och-ai-2024/
  - https://internetstiftelsen.se/nyheter/stora-risker-nar-algoritmerna-tar-besluten/
  - https://internetstiftelsen.se/nyheter/hur-ska-vi-kunna-lita-pa-artificiell-intelligens/
  - https://en.wikipedia.org/wiki/The_Swedish_Internet_Foundation
  - https://sv.wikipedia.org/wiki/Internetfonden
  - https://teknikfreak.se/nyheter/se-internetfonden-finansierar-14-nya-projekt/
  - https://internetmuseum.se/tidslinjen/internetstiftelsen-grundas/
  - https://internetstiftelsen.se/kunskap/for-samhallet/internetstiftelsen-stottar/projekt-vi-stottar/
  - https://internetstiftelsen.se/om-oss/press/pressmeddelanden/14-nya-internetframjande-projekt-delar-pa-29-miljoner-kronor/
  - https://internetstiftelsen.se/om-oss/press/pressmeddelanden/ny-teknikutlysning-fran-internetfonden-sok-pengar-till-ditt-projekt/
  - https://sv.wikipedia.org/wiki/Internetdagarna
  - https://internetstiftelsen.se/nyheter/internetdagarna-fyller-20-ar/
---

## Claim 1: "founded on 26 August 1997 and headquartered in Stockholm, established with an initial capital of SEK 200,000" (also scalar:focus, scalar:sources[1].note)

Source: https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/records-and-regulations/
Source tier: primary
Source content: "The charter of foundation is dated 'August 26, 1997.'" / "The undersigned hereby forms a foundation...and grants the Foundation...two hundred thousand Swedish kronor (SEK 200,000)." / Contact block: "Hammarby Kaj 10D, Box 92073, 120 07 Stockholm"
Comparison: Founding date, initial capital, and Stockholm HQ all match the foundation's own records page.
Decision: primary-sourced

## Claim 2: "responsible for managing Sweden's .se top-level domain and operating the .nu top-level domain" (also scalar:focus; body: "the Niuean .nu domain")

Source: https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/ ; https://en.wikipedia.org/wiki/The_Swedish_Internet_Foundation
Source tier: primary
Source content: Own site: "responsible for the internet's Swedish top-level domain .se and manages the operation and administration of the top-level domain .nu." Wikipedia: "responsible for the internet's Swedish top-level domain, .se, and the operation of the .nu top-level domain, that of Niue."
Comparison: Matches both the primary source and Wikipedia (which also confirms .nu is Niue's domain).
Decision: corroborated

## Claim 3: "whose charter mandates investing at least 25 percent of annual turnover in research, innovation, and education focused on internet development" (also scalar:focus, scalar:sources[0].note)

Source: https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/
Source tier: primary
Source content: "invest at least 25 percent of our turnover into different internet-developing projects."
Comparison: The 25% floor matches the foundation's own About page; the body's "research, innovation, and education" gloss is consistent with "internet-developing projects."
Decision: primary-sourced

## Claim 4: "Formerly known as IIS (Internet Infrastructure Foundation / Internet Foundation in Sweden), the organisation rebranded as Internetstiftelsen in 2017"

Source: https://en.wikipedia.org/wiki/The_Swedish_Internet_Foundation
Source tier: tiebreaker
Source content: "Until 2017, its name was Internet Foundation in Sweden, abbreviated IIS." / "Stiftelsen för Internetinfrastruktur, more commonly known as Internetstiftelsen"
Comparison: Named-entity definitional fact (formal name history) — Wikipedia-alone sufficient per the source rule; matches as stated.
Decision: single-source

## Claim 5: mission commitments quote — "security issues, personal privacy and an open internet" (also scalar:focus)

Source: https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/
Source tier: primary
Source content: "Through our commitment to security issues, personal privacy and an open internet, we want to make the net a safe place where everyone can participate."
Comparison: Quoted phrase matches the About page verbatim.
Decision: primary-sourced

## Claim 6: "self-governing entity with no owner or members — its seven-member board is elected by specified organisations ... with one additional member elected by the board itself" (also scalar:sources[1].note)

Source: https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/records-and-regulations/
Source tier: primary
Source content: "seven Board members" elected by designated organizations; "an eighth member shall be elected by the other members of the Board"; "A foundation is a type of legal entity that, in contrast to company and associations, does not have an owner and has no members."
Comparison: Governance structure (7 elected + 1 board-elected = 8) and no-owner/no-members status match the statutes page.
Decision: primary-sourced

## Claim 7: "Wikipedia's 2020 snapshot puts this investment at SEK 88.1 million for that year" (also scalar:sources[7].note)

Source: https://en.wikipedia.org/wiki/The_Swedish_Internet_Foundation
Source tier: tiebreaker
Source content: "In 2020, SEK 88.1 million was invested."
Comparison: The body explicitly attributes the figure to Wikipedia, and Wikipedia carries it verbatim; no second source sought since the claim is self-attributed.
Decision: single-source

## Claim 8: "surplus revenue from domain registrations ... is the sole funding source for its public-benefit activities ... no grant-seeking from other foundations and no government subsidy ... there is no separate endowment"

Source: https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/
Source tier: primary
Source content: "An independent, business-driven and public-benefit organization."
Comparison: The About page supports independence and the business-driven model, but the specific negatives (no government subsidy, no grant-seeking, no separate endowment) were not found stated in any source fetched this session; sole-funding-source as stated is unconfirmed.
Decision: uncorroborated

## Claim 9: public-benefit programme roster — Bredbandskollen, Internetkunskap, Internetmuseum, Digitala lektioner, Svenska federationer, Svenskarna och internet survey, InternetFonden, Internetdagarna (also scalar:focus, scalar:sources[0].note)

Source: https://internetstiftelsen.se/en/about-us/we-are-the-swedish-internet-foundation/
Source tier: primary
Source content: Named programmes on the About page: "Bredbandskollen (internet speed measurement); The Swedes and the Internet (annual survey); Internetkunskap (knowledge resources); Internetmuseum (digital museum); Digitala lektioner (educational resource); Svenska federationer (identity federation); Zonemaster (DNS infrastructure security)."
Comparison: Roster and per-programme descriptions (broadband measurement, public education, identity federation for described sectors) match the foundation's own programme listing.
Decision: primary-sourced

## Claim 10: "the Internetmuseum digital museum (the first entirely digital museum inducted by the Association of Swedish Museums, launched 2014)"

Source: https://en.wikipedia.org/wiki/The_Swedish_Internet_Foundation
Source tier: tiebreaker
Source content: "The Swedish Internet Foundation is responsible for Internetmuseum, a Swedish digital museum opened in 2014." / "In June 2016 Internetmuseum was inducted to The Association of Swedish Museums (Riksförbundet Sveriges museer) as the first entirely digital museum."
Comparison: Both tokens (2014 launch; first entirely digital museum inducted) match; named-entity definitional facts, Wikipedia-alone sufficient.
Decision: single-source

## Claim 11: scalar:sources[1].note — "the transferral of the .se domain (8 October 1997)"

Source: https://internetmuseum.se/tidslinjen/internetstiftelsen-grundas/
Source tier: primary
Source content: "Den 8 oktober samma år skriver Björn Eriksen på ett avtal där Internetstiftelsen tar över rätten till toppdomänen .se." (On 8 October the same year, Björn Eriksen signs an agreement in which Internetstiftelsen takes over the right to the .se top-level domain.)
Comparison: The date is correct per the foundation's own Internetmuseum timeline; note the note attributes it to the records-and-regulations page, where two targeted fetches did not surface the date — the token itself is confirmed, the attribution to that specific page could not be reproduced.
Decision: primary-sourced

## Claim 12: "CEO Carl Piva and communication chief Jannike Tillå have led the organisation" (also scalar:sources[0].note, scalar:sources[2].note)

Source: https://internetstiftelsen.se/en/about-us/press/press-releases/carl-piva-appointed-new-ceo-of-the-swedish-internet-foundation/ (via search); https://internetstiftelsen.se/om-oss/press/pressmeddelanden/internetstiftelsen-vill-lara-fler-om-ai-slapper-ny-kunskapssatsning/
Source tier: primary
Source content: Own press release: "Carl Piva appointed new CEO of the Swedish Internet Foundation" (effective April 2021); AI-initiative release names Jannike Tillå as business area and communications director. TechSverige interview "Hello CEO: Carl Piva, The Swedish Internet Foundation" independently confirms the CEO role.
Comparison: Piva-as-CEO confirmed by the foundation's own appointment release plus an independent industry outlet; Tillå's exact title is "business area and communications director" — the body's "communication chief" is a fair paraphrase.
Decision: corroborated

## Claim 13: "The AI knowledge initiative, launched on 15 June 2023 ... examples of AI deployment in Swedish public-sector contexts (including the Tax Agency's customer service chatbot and social-services robot handlers) ... developed with plans for further initiatives in collaboration with other organisations" (also scalar:sources[2].note)

Source: https://internetstiftelsen.se/om-oss/press/pressmeddelanden/internetstiftelsen-vill-lara-fler-om-ai-slapper-ny-kunskapssatsning/
Source tier: primary
Source content: Launch date June 15, 2023; examples include "Tax Agency's customer service chatbot named 'Skatti'" and "automated case handlers in social services departments"; Tillå: "Vi kommer att utveckla den här kunskapssatsningen, och framåt även göra andra initiativ på egen hand och tillsammans med andra."
Comparison: Launch date, public-sector examples, and further-initiatives plan all match the foundation's own press release.
Decision: primary-sourced

## Claim 14: "CEO Carl Piva's stated framing at launch was that 'understanding AI technology is essential to democratic participation, not merely conversational knowledge'"

Source: https://internetstiftelsen.se/om-oss/press/pressmeddelanden/internetstiftelsen-vill-lara-fler-om-ai-slapper-ny-kunskapssatsning/
Source tier: primary
Source content: Piva's quote is "Med AI kommer många möjligheter, men även utmaningar" (With AI come many opportunities, but also challenges). The democratic-participation framing belongs to Jannike Tillå: "Att förstå tekniken är inte längre bara en fråga om att kunna hänga med i samtalen ... det är en fråga om demokrati" (Understanding the technology is no longer just about keeping up with conversations ... it is a question of democracy).
Comparison: Misattributed quote — the body assigns Tillå's democracy framing to Piva; single correct replacement is to attribute the framing to Jannike Tillå (Piva's launch quote was the opportunities-and-challenges statement). Fix location: body § "AI public-education and research programmes", first paragraph.
Decision: correction

## Claim 15: Swedes and AI 2024 findings — "nationally representative sampling (1,090 interviews, August 2024) ... one-third of Swedish adults (ages 18–84) had used AI tools ... 60% versus 10% adoption disparity between the 18–34 and 65–84 cohorts; nearly 4 in 10 Swedes expressed uncertainty or reluctance ... deepening use among existing adopters rather than broadening" (also scalar:sources[3].note incl. ChatGPT 29%)

Source: https://svenskarnaochinternet.se/utvalt/svenskarna-och-ai-2024/
Source tier: primary
Source content: "Omkring en tredjedel av den vuxna befolkningen i åldern 18–84 år har använt något AI-verktyg"; "29% har använt ChatGPT"; ages 18–34: 60%, ages 65–84: 10%; "4 av 10 svenskar uppger att de antingen är osäkra eller inte alls vill använda AI i framtiden"; "Totalt genomfördes 1090 intervjuer under perioden 7–14 augusti 2024"; "användandet har däremot fördjupats till fler användningsområden."
Comparison: Every quantitative token (1/3 adults, 29% ChatGPT, 60/10 split, 4-in-10 reluctance, 1,090 interviews August 2024, deepening-not-broadening pattern) matches the report.
Decision: primary-sourced

## Claim 16: the Svenskarna och AI series "published its first full report in 2024"

Source: https://svenskarnaochinternet.se/utvalt/svenskarna-och-ai-2024/
Source tier: primary
Source content: The 2024 report page does not state whether it is the inaugural report of the series: "This appears to be part of an established reporting series ... specific confirmation of whether this is the inaugural AI-focused report isn't explicitly stated."
Comparison: The "first full report" token could not be confirmed or refuted from the sources fetched; the report's own page does not assert series position.
Decision: uncorroborated

## Claim 17: "InternetFonden is Internetstiftelsen's open grant programme for internet-promoting projects, running since 2004. The fund distributes grants twice yearly to open applicants"

Source: https://internetstiftelsen.se/om-oss/press/pressmeddelanden/14-nya-internetframjande-projekt-delar-pa-29-miljoner-kronor/ ; https://sv.wikipedia.org/wiki/Internetfonden
Source tier: primary
Source content: Own release: "Sedan starten 2004..." and "Två gånger om året delas pengar ut till projekt..."; "både privatpersoner och organisationer kan söka finansiering." Wikipedia: "Internetfonden är en fond instiftad år 2004"; "Fonden har två ansökningsomgångar per år."
Comparison: Since-2004, twice-yearly cadence, and open application (individuals and organisations) confirmed by the foundation's own release and Wikipedia independently.
Decision: corroborated

## Claim 18: applicants are "companies, organisations, or individuals holding a Swedish organisation number or personal identification number"

Source: https://internetstiftelsen.se/om-oss/press/pressmeddelanden/14-nya-internetframjande-projekt-delar-pa-29-miljoner-kronor/
Source tier: primary
Source content: "både privatpersoner och organisationer kan söka finansiering" (both private individuals and organisations may apply) — no source fetched states the Swedish organisation-number / personal-identity-number requirement.
Comparison: The general open-eligibility shape is supported, but the specific org-number/personnummer requirement was not found in any reachable source (the historical internetfonden.se application pages are offline; Wayback unreachable this session).
Decision: uncorroborated

## Claim 19: "The grant ceiling is SEK 399,000 per project (including VAT), with projects lasting up to one year"

Source: https://internetstiftelsen.se/om-oss/press/pressmeddelanden/ny-teknikutlysning-fran-internetfonden-sok-pengar-till-ditt-projekt/
Source tier: primary
Source content: "Finansierade projekt kan få upp till 400 000 kronor under max ett år" (funded projects can receive up to 400,000 kronor for max one year).
Comparison: The one-year cap matches; the ceiling token differs (399,000 incl VAT vs the fetched release's 400,000). Terms may have varied by round/era and the original internetfonden.se FAQ is offline, so no single canonical value could be established — flagged as sources-conflict rather than error.
Decision: uncorroborated

## Claim 20: "A single illustrative 2016 round disbursed SEK 2.9 million across 14 projects spanning this breadth" — accessibility, coding education for teenagers, language platforms for newly arrived immigrants, web standards, IoT (also scalar:sources[6].note)

Source: https://internetstiftelsen.se/om-oss/press/pressmeddelanden/14-nya-internetframjande-projekt-delar-pa-29-miljoner-kronor/
Source tier: primary
Source content: "Internetstiftelsen i Sverige, IIS, delar i maj genom Internetfonden ut 2,9 miljoner kronor till 14 nya internetfrämjande projekt" (May 2016); funded projects included a coding tutorial portal for ages 16–19, Swedish language material for newly arrived immigrants, web browser cache standards work, IoT ambient-backscatter research, and digital accessibility apps.
Comparison: Round total, project count, year, and breadth categories all match the foundation's own release (the Cision mirror cited in frontmatter returned HTTP 403; the identical release on internetstiftelsen.se was used).
Decision: primary-sourced

## Claim 21: "Cumulative totals reported from the programme's inception: 323 projects funded for a total of 65 million SEK (approximately €5.8 million at mid-2020s exchange rates) through the point in time when sources were last compiled"

Source: https://internetstiftelsen.se/om-oss/press/pressmeddelanden/14-nya-internetframjande-projekt-delar-pa-29-miljoner-kronor/ ; https://internetstiftelsen.se/kunskap/for-samhallet/internetstiftelsen-stottar/projekt-vi-stottar/
Source tier: primary
Source content: The cited 2016 release itself states "Sedan starten 2004 har sammanlagt 357 projekt fått dela på 71 miljoner kronor" (357 projects, 71 million kronor). The foundation's current page states "Sedan 2004 har Internetstiftelsen finansierat nästan 400 projekt för totalt cirka 75 miljoner kronor" (nearly 400 projects, ~75 million kronor). Wikipedia (older snapshot): 280 projects, 56 million.
Comparison: The tokens 323 projects / 65 million SEK match no source found — including the entity's own cited release (357/71M). Anchored to the sentence's own "point in time when sources were last compiled" (2026-06), the correct replacement is "nearly 400 projects for a total of approximately 75 million SEK" per the foundation's live page (the €5.8M conversion updates accordingly, ≈€6.6–6.8M). Fix location: body § "InternetFonden — the grant programme".
Decision: correction

## Claim 22: September 2024 article content — Gothenburg school-placement algorithm ("as the crow flies", hour-long commutes, officials denying error and refusing algorithm disclosure, Kronblad litigation) and Dutch childcare-subsidy scandal (~35,000 flagged for repayment, 94% erroneously, foreign-background applicants marked higher risk); expert voices Charlotta Kronblad and Jacob Dexe (also scalar:sources[4].note)

Source: https://internetstiftelsen.se/nyheter/stora-risker-nar-algoritmerna-tar-besluten/
Source tier: primary
Source content: Distance measured "fågelvägen" (as the crow flies); "vissa elever fick nästan en timmes resväg till sin nya skola"; officials initially denied errors and refused algorithm disclosure; Kronblad sued in administrative court. Dutch case: approximately 35,000 demanded to repay; "94 procent av dessa fall krävdes på återbetalning felaktigt"; foreign background flagged as risk factor. Publication date September 11, 2024.
Comparison: All hard specifics match the article. Two paraphrase notes: the source counts ~35,000 people/cases where the body says "families"; and the body's "refusing to disclose the algorithm until sued" — the article records that Kronblad sued and lost for lack of code access, so "until sued" should be read temporally (refusal persisted up to litigation), which the article supports.
Decision: primary-sourced

## Claim 23: "Jacob Dexe of RISE Research Institutes on the need to treat AI failures as learning opportunities" (also scalar:sources[4].note — "RISE researcher Jacob Dexe")

Source: https://internetstiftelsen.se/nyheter/stora-risker-nar-algoritmerna-tar-besluten/
Source tier: primary
Source content: "Jacob Dexe har tidigare jobbat på forskningsinstitutet RISE och skrivit om transparensfrågor och algoritmer." (Jacob Dexe previously worked at the research institute RISE and has written about transparency issues and algorithms.) His quote: "Vi måste vara medvetna om att AI-system kommer att göra fel ... Det är genom dessa misstag vi lär oss hur vi ska utveckla och förbättra systemen."
Comparison: Affiliation token wrong — the article describes Dexe as a former RISE researcher, not current; single correct replacement: "formerly of RISE Research Institutes" (body § "Algorithmic-accountability publishing") and "former RISE researcher" (scalar:sources[4].note). The learning-opportunities substance of the quote matches.
Decision: correction

## Claim 24: companion article — "outlines the EU's seven principles for trustworthy AI, and cites legal sociologist Stefan Larsson on the non-binding character of the EU guidelines" (also scalar:sources[5].note listing the seven principles)

Source: https://internetstiftelsen.se/nyheter/hur-ska-vi-kunna-lita-pa-artificiell-intelligens/
Source tier: primary
Source content: The article lists seven EU requirements (human agency; technical robustness & safety; privacy & data governance; transparency; diversity/non-discrimination & fairness; societal & environmental wellbeing; accountability). Stefan Larsson, "socio-legal scholar, lawyer, and technology researcher at Lund University," calls the guidelines a good starting point but "not legally binding" with no specific requirements or standards.
Comparison: Seven principles match the frontmatter note's list in substance; Larsson's identity ("legal sociologist" ≈ socio-legal scholar) and non-binding assessment match; the note's "excellent starting point" vs the article's "good starting point" is within paraphrase range.
Decision: primary-sourced

## Claim 25: "The annual Internet Days (Internetdagarna) conference, running since 1999"

Source: https://internetstiftelsen.se/nyheter/internetdagarna-fyller-20-ar/ ; https://sv.wikipedia.org/wiki/Internetdagarna
Source tier: primary
Source content: Foundation's own anniversary article: the first Internetdagarna conference was held in 2000 (20-year milestone marked in 2019). Wikipedia: "Internetdagarna är en årlig konferens som arrangeras av Internetstiftelsen sedan år 2000."
Comparison: Start-year token wrong — both the foundation's own account and Wikipedia give 2000, not 1999; single correct replacement: "running since 2000". The body's citation (internetdagarna.se/en/) now returns HTTP 404, so the original claimed support could not be checked. Fix location: body § "Algorithmic-accountability publishing", final sentence.
Decision: correction

## Claim 26: Internetdagarna is "Sweden's most significant annual internet conference ... brings together the technical community with civil-society groups including DFRI (Föreningen för digitala fri- och rättigheter — Sweden's primary digital rights civil-society organisation)"

Source: https://internetstiftelsen.se/nyheter/internetdagarna-fyller-20-ar/
Source tier: caution
Source content: "Internetdagarna har blivit Sveriges viktigaste kunskapsnav för alla som jobbar med internet och digitalisering" (Sweden's most important knowledge hub for all who work with internet and digitalisation) — the foundation's own self-characterization.
Comparison: The superlative rests on the entity's own self-description (tier caution for a load-bearing ranking claim about itself); no independent canonical source confirming "most significant annual internet conference" as stated was found, and DFRI's co-presence at the conference was not confirmed in any source fetched this session. Honest sourcing-strength label, not a finding of error.
Decision: uncorroborated
