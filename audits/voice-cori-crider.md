---
entity_id: voice-cori-crider
entity_hash: 7b7631e449a6b0ca4725cb152d48211e98c6f4ae
audit_date: 2026-06-03
reclassified_at: 2026-06-10
pass: 1
status: corrections-pending
claims_total: 14
claims_corroborated: 10
claims_primary_sourced: 0
claims_single_source: 0
open_corrections: 2
claims_uncorroborated: 2
sources_consulted:
  - https://www.foxglove.org.uk/about/our-team/cori-crider/
  - https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
  - https://www.foxglove.org.uk/news/home-office-says-it-will-abandon-its-racist-visa-algorithm-nbsp-after-we-sued-them
  - https://www.foxglove.org.uk/news/press-release-u-turn-on-a-level-algorithm
  - https://www.foxglove.org.uk/2024/09/23/facebook-content-moderators-kenya-meta-appeal
  - https://www.foxglove.org.uk/who-we-are/people/
  - https://cmdg.tech/
  - https://finance.yahoo.com/news/frances-haugen-calls-solidarity-facebook-113605438.html
---

## Claim 1: "US-qualified lawyer (B.A. University of Texas; J.D. Harvard Law School)"

Source: https://www.foxglove.org.uk/about/our-team/cori-crider/
Source content: "She holds a B.A. from the University of Texas and a J.D. from Harvard Law School."
Comparison: Body claim matches the Foxglove team-page bio capsule on both institutions and degrees.
Decision: corroborated

## Claim 2: "the co-founder and former director (2019-September 2024) of Foxglove"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
Source content: "After five brilliant years, Foxglove co-founder and director Cori Crider is stepping back" (post dated 13.09.2024); "Cori co-founded Foxglove with Martha and Rosa in 2019" (Foxglove team page).
Comparison: Both the 2019 co-founding and the five-year directorship ending September 2024 are supported.
Decision: corroborated

## Claim 3: scalar:notable_for and body — "Senior Fellow at the Open Markets Institute's Center for Journalism & Liberty"; body — "Center for Journalism & Liberty ... whose self-description is 'Ensuring news media is fully independent in the 21st century's digital economy'"

Source: https://cmdg.tech/ (redirected from https://www.journalismliberty.org/ via 301 Moved Permanently)
Source content: "A CENTER WITHIN THE OPEN MARKETS INSTITUTE"; tagline "INFORMATION. POWER. DEMOCRACY."; "We changed our name from the Center for Journalism and Liberty to the Center for Media and Digital Governance to better reflect what our work looks like in the age of AI and Big Tech's increased stranglehold over our society and economy."
Comparison: The institution has been renamed — it is now the Center for Media and Digital Governance (CMDG), not the Center for Journalism & Liberty. The body's quoted self-description ("Ensuring news media is fully independent in the 21st century's digital economy") is no longer present at the cited URL after the rebrand; the live tagline is "INFORMATION. POWER. DEMOCRACY." The cited URL (journalismliberty.org) now redirects to cmdg.tech. Both the institution name and the quoted self-description in the body, and the duplicate reference in scalar `notable_for` (which names "the Open Markets Institute's Center for Journalism & Liberty"), are stale. Correction requires prose judgment beyond a single-token replacement (institution name change ripples across multiple sentences and the quoted tagline; URL fix to cmdg.tech; possible scope restructuring) — Editor flag to Researcher, not mechanical body backfill.
Decision: correction

## Claim 4: "Honorary Professor of Practice at the University College London Faculty of Laws"

Source: https://www.foxglove.org.uk/about/our-team/cori-crider/
Source content: "Honorary Professor of Practice at University College London Faculty of Laws"
Comparison: Title and institution match exactly.
Decision: corroborated

## Claim 5: scalar:sources[0].note — "twelve-year Reprieve career representing drone-strike survivors and Guantánamo detainees"

Source: https://www.foxglove.org.uk/about/our-team/cori-crider/
Source content: "twelve years at Reprieve, where she led an international team representing drone strike survivors and Guantánamo detainees"
Comparison: Duration (twelve years), employer (Reprieve), and described client groups (drone-strike survivors, Guantánamo detainees) all match.
Decision: corroborated

## Claim 6: "the August 2020 Home Office visa-streaming algorithm withdrawal with the Joint Council for the Welfare of Immigrants — the first successful UK judicial review of a government algorithmic decision-making system"

Source: https://www.foxglove.org.uk/news/home-office-says-it-will-abandon-its-racist-visa-algorithm-nbsp-after-we-sued-them
Source content: "Before the case could be heard, the Home Office caved in. They've agreed that from this Friday, August 7, they will get rid of the 'streaming algorithm.'"; "this was the first successful judicial review of a UK government algorithmic decision-making system"; "we've been working on with the Joint Council for the Welfare of Immigrants (JCWI)."
Comparison: Date (August 2020), the "first" framing, and the JCWI co-claimant all match.
Decision: corroborated

## Claim 7: "the parallel August 2020 Ofqual A-level grading algorithm reversal — taken down 'in seven days' in Foxglove's own framing"

Source: https://www.foxglove.org.uk/2024/09/13/cori-stepping-back/
Source content: "taking down the A Level grading algorithm in seven days"
Comparison: The "seven days" framing is exactly the wording the Foxglove stepping-back announcement uses to describe the Ofqual reversal. The Ofqual press release also cited in the body (dated 17.08.2020) confirms August 2020 as the timing.
Decision: corroborated

## Claim 8: "the 'fk-the-algorithm' episode after the slogan that appeared on student-protest placards"

Source: https://www.foxglove.org.uk/news/press-release-u-turn-on-a-level-algorithm
Source content: The Foxglove press release naming the Ofqual reversal cites the campaign slogan "grade the student, not the school"; it does not name "fk the algorithm" or describe student-protest placards bearing that slogan.
Comparison: The cited Foxglove sources do not carry the "fk the algorithm" placard-slogan attribution. The slogan was widely reported in 2020 UK mainstream news but is not in either Foxglove source on the file, and no canonical news source was checked in this pass.
Decision: uncorroborated

## Claim 9: "the June 2022 King's Place London panel at which Crider appeared alongside Daniel Motaung, Frances Haugen, and Mercy Mutemi"

Source: https://finance.yahoo.com/news/frances-haugen-calls-solidarity-facebook-113605438.html (Yahoo mirror of the TIME article — original https://time.com/6188272/... returned 403 Forbidden to the audit's WebFetch)
Source content: byline "Billy Perrigo/London June 16, 2022"; "when they met for the first time in front of an audience in London Tuesday"; "Foxglove's co-director Cori Crider was also on the panel, along with Mercy Mutemi, Motaung's lawyer in Kenya."
Comparison: The article's June 16, 2022 publication date and its reference to the panel having been held "Tuesday" place the King's Place London panel on June 14, 2022 — i.e., in June 2022 as the body asserts. Crider, Motaung, Haugen, and Mutemi (the latter via video link per the photo caption) are all named.
Decision: corroborated

## Claim 10: scalar:sources[5].note — "TIME (7 July 2022) on the King's Place London panel"

Source: https://finance.yahoo.com/news/frances-haugen-calls-solidarity-facebook-113605438.html
Source content: byline "Billy Perrigo/London June 16, 2022 4 min read"
Comparison: The Yahoo mirror of the TIME article carries a June 16, 2022 byline. The Researcher's note on `sources[5]` ascribes the article to 7 July 2022 — almost certainly a misreading of the URL slug `6188272` (an internal TIME ID, not a calendar date) as 7/7/22-ish. The TIME article publication date is 16 June 2022, not 7 July 2022. Single-token replacement: in `sources[5].note`, replace "TIME (7 July 2022)" with "TIME (16 June 2022)".
Decision: correction

## Claim 11: "the 2019 Al Jazeera English documentary *The World According to AI*, on which Crider presented"

Source: https://www.foxglove.org.uk/about/our-team/cori-crider/
Source content: "In 2019, she presented The World According to AI, a documentary"
Comparison: Year (2019), title (*The World According to AI*), and presenter role match.
Decision: corroborated

## Claim 12: "the 20 September 2024 Nairobi Court of Appeal ruling — that the case of 185 former Facebook content moderators against Meta will proceed to trial in Kenya"

Source: https://www.foxglove.org.uk/2024/09/23/facebook-content-moderators-kenya-meta-appeal/ + WebSearch corroboration (US News, Seattle Times, Business and Human Rights Centre, all dated 20.09.2024)
Source content: Foxglove article (dated 23.09.2024) — "The Nairobi Court of Appeal ruled on Friday"; "the case of 185 former Facebook content moderators against their unlawful mass firing by Meta should proceed to trial in a Kenyan court"; "the Court of Appeal ruled that both cases have jurisdiction to continue to trial in Kenya". WebSearch corroboration places the ruling on September 20, 2024 — which was indeed a Friday relative to the 23.09.2024 post.
Comparison: Date (20 September 2024 — consistent with Foxglove's "Friday" reference and corroborated by multiple mainstream-news cross-checks), number of moderators (185), and the "proceed to trial in Kenya" outcome all match.
Decision: corroborated

## Claim 13: "the December 2024 CNN coverage of the more-than-140 PTSD diagnoses among the moderators in the docket"

Source: WebSearch corroboration of CNN article at https://www.cnn.com/2024/12/22/business/facebook-content-moderators-kenya-ptsd-intl (direct WebFetch returned HTTP 451 Unavailable For Legal Reasons; mirror coverage at KTVZ, KRDO, KESQ, KVIA, KEYT, WRAL carries the identical CNN syndicated text dated 22 December 2024)
Source content: "Campaigners have accused Facebook parent Meta of inflicting 'potentially lifelong trauma' on hundreds of content moderators in Kenya, after more than 140 were diagnosed with PTSD"; "Of the 144 content moderators who volunteered to undergo psychological assessments – out of 185 involved in the legal claim – 81% were classed as suffering from 'severe' PTSD"
Comparison: December 2024 timing (article dated 22 December 2024), the "more than 140" PTSD diagnosis count, and the connection to the same 185-moderator docket all match the body claim.
Decision: corroborated

## Claim 14: "the Greater Manchester Coalition of Disabled People judicial review of the DWP General Matching Service from December 2021 onwards"

Source: no canonical source successfully fetched in this pass
Source content: n/a — the Foxglove team page and the stepping-back announcement reference Foxglove DWP-adjacent work in general terms ("getting the Home Office to drop its racist visa algorithm", etc.) but neither names the Greater Manchester Coalition of Disabled People, the DWP General Matching Service, or a December 2021 start date.
Comparison: The specific claim — the named claimant (Greater Manchester Coalition of Disabled People), the named DWP system (General Matching Service), and the December 2021 start date — was not corroborated by any source fetched this pass. Verification deferred to a future audit pass with a targeted source fetch (likely a Foxglove news post or a UK mainstream-news write-up of the JR).
Decision: uncorroborated
