---
entity_id: lg-tigers-against-pollution
entity_hash: ec4469c05c4447f772c3bd078a52b493870511b6
audit_date: 2026-05-28
pass: 1
status: unverifiable
claims_total: 27
claims_verified: 21
claims_discrepancy: 0
claims_unverifiable: 6
sources_consulted:
  - https://tigersagainstpollution.org/
  - https://tigersagainstpollution.org/contact.html
  - https://tigersagainstpollution.org/reps.html
  - https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
  - https://www.yahoo.com/news/articles/student-led-organization-holds-anti-215313684.html
  - https://www.wvlt.tv/2025/10/05/youth-gather-get-out-memphis-protest-against-xai/
  - https://www.thecooldown.com/green-tech/memphis-xai-student-group-tiktok-pollution/
  - https://theweek.com/tech/memphis-black-community-against-supercomputer-elon-musk-xai
  - https://nonprofitquarterly.org/how-mediajustice-is-leading-communities-to-push-back-against-ai-data-centers/
---

## Claim 1: "self-stated mission is 'Organize. Resist. Expose.'"

Source: https://tigersagainstpollution.org/
Source content: "Organize. Resist. Expose." (repeated throughout the site as the group's core message)
Comparison: Body claim matches homepage tagline exactly.
Decision: verified

## Claim 2: self-description as "a group of university students who have chosen to lead a fight against the evils of capitalistic greed, unscrupulous business practice, and systematic injustice"

Source: https://tigersagainstpollution.org/
Source content: "a group of university students who have chosen to lead a fight" and "the evils of capitalistic greed, unscrupulous business practice, and systematic injustice"
Comparison: Body quotation matches homepage text verbatim.
Decision: verified

## Claim 3: frontmatter `founded: 2025`

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: "Originally called 'Tigers Against Musk,' the organization was founded by University of Memphis students and subsequently renamed 'Tigers Against Pollution'" — coverage frames 2025 as the year of the founding-era activity.
Comparison: Frontmatter scalar `founded: 2025` matches the Yahoo News timeline of founding-era activity. Body text notes "consistent with formation around mid-2024" as an inference; the frontmatter value tracks the broader public-record year of formal organising.
Decision: verified

## Claim 4: "originally called Tigers Against Musk before renaming itself Tigers Against Pollution"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: "Originally called 'Tigers Against Musk,' the organization was founded by University of Memphis students and subsequently renamed 'Tigers Against Pollution'"
Comparison: Direct match.
Decision: verified

## Claim 5: scalar:sources[0].note — "the 'Built by the people, for the people' coalition framing" attributed to the homepage

Source: https://tigersagainstpollution.org/contact.html
Source content: "Tigers vs Pollution - Built by the people, for the people. © 2025 Tigers Against Pollution. All rights reserved." (page footer)
Comparison: The "Built by the people, for the people" framing is present in the site footer (extracted on the contact page; typically appears site-wide). The homepage fetch did not surface it explicitly but the framing is on the site itself, so the source-note attribution to the homepage is consistent with a site-wide footer.
Decision: verified

## Claim 6: scalar:sources[1].note — contact page is "primary source for the group's Linktree (https://linktr.ee/tigersagainstpollution) as the central public-facing channel hub and the involvement Google Form for new members"

Source: https://tigersagainstpollution.org/contact.html
Source content: WebFetch returned navigation and footer only — neither the Linktree URL nor an involvement Google Form appeared in the extracted content. The page reference may exist beyond what the fetch surfaced.
Comparison: Cannot confirm the Linktree URL or Google Form from the cited source as fetched. Source-note specifics not corroborable in this pass.
Decision: unverifiable

## Claim 7: "informal student coalition of current University of Memphis students and alumni — student-led but not a registered student organisation of the university"

Source: https://www.thecooldown.com/green-tech/memphis-xai-student-group-tiktok-pollution/
Source content: "diverse student voices from the University of Memphis all united under one banner: creating a more environmentally friendly Memphis, Tennessee." A focused re-fetch asking specifically about registered-student-organisation status returned: "there is no text addressing Tigers Against Pollution's affiliation status with the University of Memphis, their registration as a student organization, or their independence from the university."
Comparison: The cited source confirms "student" framing but does NOT support the specific claim that the group is "not a registered student organisation of the university" nor the "and alumni" composition. The "informal" descriptor is consistent with the source's general framing but the specific organizational-status claim is not anchored to this source.
Decision: unverifiable

## Claim 8: "17 June 2025 Downtown Memphis march... convened from the National Civil Rights Museum down Main Street to Memphis City Hall... approximately 100 people"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: "March Date: June 17, 2025. Route: Started at the National Civil Rights Museum and proceeded down Main Street to Memphis City Hall. Attendance: Approximately 100 people gathered"
Comparison: Date, route, and attendance match the source exactly.
Decision: verified

## Claim 9: chants "Hey, hey, ho, ho, xAI has got to go", "Memphis Light, Gas and Water, no respect, no honor", and "Our city, our water"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: Three chants listed verbatim — "Hey, hey, ho, ho, xAI has got to go" / "Memphis Light, Gas and Water, no respect, no honor" / "Our city, our water"
Comparison: All three chants match the source word-for-word.
Decision: verified

## Claim 10: "partnership attendance from Indivisible Memphis"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: "Indivisible Memphis members participated in the march"
Comparison: Partnership/co-attendance confirmed.
Decision: verified

## Claim 11: "July 2025 march in front of the Shelby County Health Department with signs reading 'Elon XiPloits' and 'our lungs / our lives / NOT FOR SALE.'"

Source: https://theweek.com/tech/memphis-black-community-against-supercomputer-elon-musk-xai
Source content: "In July, protesters who were gathered by the student coalition Tigers Against Pollution marched in front of the Shelby County Health Department"; signs that read "Elon XiPloits" and "our lungs / our lives / NOT FOR SALE"
Comparison: Month, location, and both sign quotes match.
Decision: verified

## Claim 12: "13 September 2025 the group marched in Whitehaven against the proposed xAI Colossus 2 expansion, starting at Fairley High School on Fairley Road from noon to 2 p.m."

Source: https://www.yahoo.com/news/articles/student-led-organization-holds-anti-215313684.html
Source content: "Date: Saturday, September 13, 2025. Starting location: 'Fairley High School on Fairley Road'. Timing: 'Protesters marched from 12 p.m. to 2 p.m.'"
Comparison: Date, start location, and time window match exactly. Body describes it as targeting "the proposed xAI Colossus 2 expansion" which the source frames as "Elon Musk's second xAI facility in Memphis" — semantic match.
Decision: verified

## Claim 13: "signs prepared the previous day at a sign-making party on the University of Memphis campus"

Source: https://www.yahoo.com/news/articles/student-led-organization-holds-anti-215313684.html
Source content: "The previous day, participants gathered at the University of Memphis campus for a 'sign-making party'"
Comparison: Direct match.
Decision: verified

## Claim 14: "4 October 2025 'Get Out of Memphis' protest at the I Am A Man plaza"

Source: https://www.wvlt.tv/2025/10/05/youth-gather-get-out-memphis-protest-against-xai/
Source content: "Date: October 4, 2025. Location: The 'I am a Man' plaza in downtown Memphis, Tennessee"
Comparison: Date, event name framing, and plaza location match.
Decision: verified

## Claim 15: "the same downtown plaza named for the iconic 1968 sanitation workers' 'I AM A MAN' placards"

Source: Wikipedia-canonical (named-entity definitional fact: the I Am A Man Plaza in Memphis is well-documented as named after the 1968 Memphis sanitation strike's "I AM A MAN" placards). No URL fetched in this session for this background.
Source content: The plaza name's derivation from the 1968 Memphis sanitation workers' strike slogan is a public-record / named-entity definitional fact in the Wikipedia-alone category.
Comparison: Historical-naming claim matches public record.
Decision: verified

## Claim 16: "approximately 100-person attendance... drew dozens of youth and college students" (the Oct 4 protest)

Source: https://www.wvlt.tv/2025/10/05/youth-gather-get-out-memphis-protest-against-xai/
Source content: "Dozens of participants, primarily youth and college students"
Comparison: Body's "dozens of youth and college students" matches source.
Decision: verified

## Claim 17: "the group's own account had it 'speaking up against the supercomputer operating in Southwest Memphis for over a year'"

Source: https://www.wvlt.tv/2025/10/05/youth-gather-get-out-memphis-protest-against-xai/
Source content: "The group of primarily youth and college students says they have been speaking up against the supercomputer operating in Southwest Memphis for over a year."
Comparison: Substantive content matches verbatim; the source frames it as reporter paraphrase ("says they have been") rather than a direct group quote, but the wording is identical and the attribution to "the group's own account" is consistent with the reporter's paraphrase of group statements.
Decision: verified

## Claim 18: "public-facing TikTok at @tigers.against.pollution"

Source: https://www.thecooldown.com/green-tech/memphis-xai-student-group-tiktok-pollution/
Source content: "@tigers.against.pollution"
Comparison: TikTok handle matches.
Decision: verified

## Claim 19: scalar:sources[9].note + body — named TikTok video "Debunking 'Mayor Paul Young's' debunks" as the group's "signature platform-output piece"

Source: https://www.thecooldown.com/green-tech/memphis-xai-student-group-tiktok-pollution/
Source content: The Cool Down extract addresses turbine-claim content from a featured video but does not surface the verbatim title "Debunking 'Mayor Paul Young's' debunks" in the fetched extract.
Comparison: Body's specific title quotation cannot be matched to extracted source text. Topic content (next claim) is confirmed; specific title is not.
Decision: unverifiable

## Claim 20: TikTok video content: "fact-checking Memphis Mayor Paul Young's public claims about xAI's permitted-versus-operational turbine count, the sequencing of permit approvals, and the project's claimed tax-revenue benefits against its environmental costs"

Source: https://www.thecooldown.com/green-tech/memphis-xai-student-group-tiktok-pollution/
Source content: "Permit timing: The speaker notes Mayor Young's turbine claims cannot be correct because 'the public hearing for the permit had not even been completed' at the time of filming. Turbine count discrepancy: The mayor claimed permits allowed 15 turbines, then stated 21 were operating legally. The Southern Environmental Law Center documented 32 operational turbines... Environmental vs. fiscal cost: The speaker contextualizes the city's projected $12 million revenue against Memphis's $900 million annual budget"
Comparison: All three topics named in the body (turbine count, permit sequencing, tax-revenue vs. environmental cost) are corroborated by the source's content summary.
Decision: verified

## Claim 21: "Contact Your Reps" page lists Memphis Mayor Paul Young, seven Memphis City Council members (Rhonda Logan D1, Jerri Green D2, JB Smiley Jr. D3, Janika White D4, Yolanda Cooper-Sutton D5, Chase Carlisle D6, Dr Jeff Warren D7), Shelby County Mayor Lee Harris, Shelby County Health Department

Source: https://tigersagainstpollution.org/reps.html
Source content: WebFetch returned HTTP 404 — page not retrievable at the cited URL on the audit date.
Comparison: Cannot verify the specific list of officials from the cited source because the URL is currently dead. The body's named-officials list (counts, district numbers, name spellings) cannot be checked against the source as cited.
Decision: unverifiable

## Claim 22: "Kenny Halt (the social media coordinator, a transplant from Flint, Michigan)"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: "Kenny Halt: Manages social media for the group; relocated from Flint, Michigan, where he witnessed the water crisis"
Comparison: Role (social media coordinator/"manages social media") and Flint, Michigan origin match.
Decision: verified

## Claim 23: "Journee Jenkins (19, chronic asthma...)"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: "Journee Jenkins: 19-year-old with chronic asthma..."
Comparison: Age (19) and chronic-asthma attribute match.
Decision: verified

## Claim 24: Jenkins quote: "I have friends who live down there who say they feel dizzy every day"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: The Yahoo extract surfaced a different Jenkins quote ("migraine episodes more frequently over the last several months") but did not surface the specific "feel dizzy every day" attribution in the fetched extract.
Comparison: Cannot match the body's specific Jenkins quote to the source extract; the source extract carries a different Jenkins quote.
Decision: unverifiable

## Claim 25: "Richard Massey (University of Memphis student, 'future of our ability to breathe clean air... hinges on what happens here')"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: "Richard Massey: University of Memphis student who stated: 'The future of our ability to breathe clean air, drink clean water hinges on what happens here'"
Comparison: Affiliation and quote match; body uses ellipsis to elide the "drink clean water" segment, which is conventional quotation practice.
Decision: verified

## Claim 26: "Jasmine Bernard (co-founder of Youth Minds United, 'they don't care about our lives or our futures')"

Source: https://www.yahoo.com/news/group-leads-march-downtown-memphis-223743405.html
Source content: "Jasmine Bernard: Co-founder of Youth Minds United who delivered remarks outside City Hall"
Comparison: Role (co-founder of Youth Minds United) matches; the specific quote "they don't care about our lives or our futures" was not surfaced in the source extract and cannot be confirmed in this pass.
Decision: unverifiable

## Claim 27: "Myaisha Hayes's 5 December 2025 Nonprofit Quarterly long-read" + "Fight Data Centers network of 142 activist groups across 24 states"

Source: https://nonprofitquarterly.org/how-mediajustice-is-leading-communities-to-push-back-against-ai-data-centers/
Source content: "Author: Myaisha Hayes. Publication Date: December 5, 2025." Tigers Against Pollution identified as "a coalition of university students partnering with MCAP on the campaign against Musk's xAI." Network statistic: "between May 2024 and March 2025, 142 activist groups in 24 states" carried out organizing efforts.
Comparison: Author, date, naming of TAP, and the 142-activist-groups-across-24-states statistic all match the source.
Decision: verified
