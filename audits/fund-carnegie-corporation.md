---
entity_id: fund-carnegie-corporation
entity_hash: 746f9a5b6140b4667cd1156ef72ce3e5368df19a
audit_date: 2026-09-01
pass: 1
status: corrections-pending
claims_total: 24
claims_corroborated: 6
claims_primary_sourced: 10
claims_single_source: 1
claims_uncorroborated: 5
open_corrections: 2
sources_consulted:
  - https://en.wikipedia.org/wiki/Carnegie_Corporation_of_New_York
  - https://www.carnegie.org/programs/
  - https://www.carnegie.org/programs/strengthening-democracy/
  - https://carnegie.org/article/carnegie-corporation-of-new-york-changes-its-name-to-andrew-carnegie-foundation/
  - https://www.morningstar.com/news/business-wire/20260609055766/carnegie-corporation-of-new-york-changes-its-name-to-the-andrew-carnegie-foundation
  - https://www.carnegie.org/news/articles/carnegie-corporation-of-new-york-board-approves-63-grants-totaling-32855000/
  - https://www.commonsensemedia.org/press-releases/carnegie-corporation-of-new-york-awards-155m-to-common-sense-media-to-reimagine-digital-literacy
  - https://carnegie.org/article/carnegie-corporation-of-new-york-board-approves-94-grants-totaling-63219000/
  - https://carnegie.org/article/carnegie-corporation-of-new-york-board-approves-57-grants-totaling-38485000/
  - https://www.carnegie.org/grants/grants-database/grantee/campaign-legal-center/
  - https://carnegie.org/grantee/common-sense-media/
  - https://www.insidephilanthropy.com/home/2024-7-15-the-election-isnt-the-end-point-a-deep-dive-into-the-carnegie-corporations-democracy-giving
  - https://www.carnegie.org/about/staff/geri-mannion/
  - https://projects.propublica.org/nonprofits/organizations/131628151
  - https://www.ox.ac.uk/news/2021-11-18-professor-louise-richardson-become-president-carnegie-corporation-new-york-2023
  - https://www.businesswire.com/news/home/20211118005341/en/Carnegie-Corporation-of-New-York-Appoints-Louise-Richardson-Vice-Chancellor-of-the-University-of-Oxford-as-President
  - https://protectdemocracy.org/about-us/
  - https://campaignlegal.org/
  - https://www.techandciviclife.org/
  - https://www.inquirygroup.org/history
  - https://inquirygroup.org/about
  - https://newslit.org/ai/
  - https://ed.icivics.org/professional-development/what-students-need-know-about-ai
  - https://www.carnegie.org/news/articles/carnegie-corporation-of-new-york-board-approves-39-grants-totaling-20017000/
---

Audit context: the foundation renamed itself between the entity's drafting (2026-06-05) and this
audit — "Carnegie Corporation of New York" became "Andrew Carnegie Foundation" on June 9, 2026, and
carnegie.org was restructured (old `/news/articles/` and `/programs/` URLs 404 or redirect; new
patterns are `/article/`, `/grantee/`, `/staff/`). Several of the entity's cited URLs are dead as a
result; where cached content of the cited page was retrievable via search it is used and noted.

## Claim 1: "founded on June 9, 1911 by industrialist and philanthropist Andrew Carnegie with the mission to 'promote the advancement and diffusion of knowledge and understanding'" (+ "one of the oldest major private foundations in the United States")

Source: https://en.wikipedia.org/wiki/Carnegie_Corporation_of_New_York + https://carnegie.org/article/carnegie-corporation-of-new-york-changes-its-name-to-andrew-carnegie-foundation/
Source tier: primary
Source content: Wikipedia: "Founded June 9, 1911 by Andrew Carnegie ... 'to promote the advancement and diffusion of knowledge and understanding'". Foundation's own rename announcement: "the Scottish immigrant who established the philanthropic organization on June 9, 1911 ... one of the country's first philanthropic grantmaking institutions."
Comparison: Date, founder, mission quote, and "oldest major" framing all match across the foundation's own announcement and Wikipedia.
Decision: corroborated

## Claim 2: "Carnegie's initial endowment has grown to approximately $4.1 billion as of 2022"

Source: https://projects.propublica.org/nonprofits/organizations/131628151 + https://en.wikipedia.org/wiki/Carnegie_Corporation_of_New_York
Source tier: database
Source content: ProPublica Nonprofit Explorer, FY2022: "Total Assets: $4,065,280,317; Net Assets: $3,946,750,769". Wikipedia: "$4.1 billion as of 2022".
Comparison: ProPublica's FY2022 total assets ($4.07B) match "approximately $4.1 billion"; Wikipedia carries the same figure. Database + tiebreaker.
Decision: corroborated

## Claim 3: "Louise Richardson, a political scientist and counter-terrorism scholar who previously served as vice-chancellor of Oxford University, became president in January 2023 following the tenure of Vartan Gregorian"

Source: https://www.ox.ac.uk/news/2021-11-18-professor-louise-richardson-become-president-carnegie-corporation-new-york-2023 + https://www.businesswire.com/news/home/20211118005341/en/ + https://en.wikipedia.org/wiki/Carnegie_Corporation_of_New_York
Source tier: primary
Source content: "Louise Richardson joined Carnegie Corporation of New York as its 13th president in January 2023 at the end of her seven-year term as head of the University of Oxford ... a renowned academic leader and distinguished expert on terrorism"; Wikipedia: "Vartan Gregorian served from 1997–2021 and died in office."
Comparison: All elements match — January 2023 start, Oxford vice-chancellorship (2016–2022), terrorism scholarship, Gregorian as predecessor president.
Decision: corroborated

## Claim 4: "Carnegie Corporation of New York is one of the oldest major private foundations..." (present-tense name, body throughout + frontmatter `name:` scalar)

Source: https://carnegie.org/article/carnegie-corporation-of-new-york-changes-its-name-to-andrew-carnegie-foundation/ (+ Business Wire via Morningstar, 2026-06-09)
Source tier: primary
Source content: "Carnegie Corporation of New York Changes Its Name to the Andrew Carnegie Foundation" — announced June 9, 2026, the foundation's 115th anniversary; "The Andrew Carnegie Foundation's mission is staying the same."
Comparison: The entity's present-tense name is superseded: the foundation renamed itself Andrew Carnegie Foundation on 2026-06-09, after the entity was drafted (2026-06-05). Single correct replacement: current name "Andrew Carnegie Foundation" (formerly Carnegie Corporation of New York). Fix locations: frontmatter `name:` scalar and body first sentence — the rename touches prose throughout, so this needs Researcher prose judgment, not a mechanical single swap.
Decision: correction

## Claim 5: "Under Richardson the Corporation has framed its priorities around reducing political polarization in the United States while sustaining its long-running international peace and security mandate"

Source: https://www.carnegie.org/programs/strengthening-democracy/ (cached content via search; live URL restructured)
Source tier: primary
Source content: "Carnegie's Strengthening U.S. Democracy program supports nonpartisan organizations that are working to reduce political polarization in the United States"; rename announcement: mission focused on "education, democracy, and peace."
Comparison: The polarization framing matches the foundation's own program language; the continued peace/security mandate matches its stated mission areas.
Decision: primary-sourced

## Claim 6: "Carnegie organises its grantmaking across three programme areas: Education ... Strengthening U.S. Democracy ... and International Peace and Security" (present tense)

Source: https://www.carnegie.org/programs/ (cited; now restructured)
Source tier: primary
Source content: Live page (fetched this session) now lists: "Ladders of Opportunity (National Program)", "A More Peaceful World (International Program)", and "Libraries" — with Education and Democracy as sub-areas of Ladders of Opportunity.
Comparison: The three-programme structure was the cited page's content at drafting, but the June 2026 reorganization replaced it; the live primary source no longer supports the present-tense claim, and the pre-reorg version is unreachable (web.archive.org blocked; only fragments via search cache). Not a drafting error — world-drift; the prose update rides with the Claim 4 rename correction.
Decision: uncorroborated

## Claim 7: "[the Democracy programme] approved approximately $30.6 million in FY2025 grants across four strategy pillars: elections and governance, state community service, universal civic learning, and legal immigration pathways"

Source: https://www.carnegie.org/programs/strengthening-democracy/ (cached content via search)
Source tier: primary
Source content: "initiatives focused on elections and governance, state community service, universal civic learning, and legal immigration pathways. The program has allocated $30.6M in FY2025 grants."
Comparison: Figure and all four pillar names match the cited primary page's cached content verbatim.
Decision: primary-sourced

## Claim 8: "The programme's managing director, Geri Mannion"

Source: https://www.carnegie.org/about/staff/geri-mannion/ (via search) + https://cof.org/person/geri-mannion
Source tier: primary
Source content: "Geri Mannion is Managing Director for Strengthening U.S. Democracy and Special Opportunities Fund at Carnegie Corporation ... has directed the program since 1998."
Comparison: Title matches; the foundation's own staff page and Council on Foundations both confirm.
Decision: corroborated

## Claim 9: "[Mannion] described its scope as deliberately spanning the full voter-engagement continuum and sustaining grantees through non-election years rather than concentrating capital in final-stretch campaign spending"

Source: https://www.insidephilanthropy.com/home/2024-7-15-the-election-isnt-the-end-point-a-deep-dive-into-the-carnegie-corporations-democracy-giving (403 on direct fetch; fragments via search snippets)
Source tier: mainstream
Source content: Article title "'The Election Isn't the End Point.' A Deep Dive into the Carnegie Corporation's Democracy Giving"; snippets confirm the sustained-support theme but the specific "continuum"/non-election-years paraphrase could not be retrieved for comparison.
Comparison: The cited article exists and its title/theme are consistent, but the paraphrase is too loosely checkable against retrievable fragments to confirm as stated.
Decision: uncorroborated

## Claim 10: "The Campaign Legal Center — the nonpartisan legal organisation focused on campaign finance reform and voting-rights litigation"

Source: https://campaignlegal.org/ + Inside Philanthropy (via search snippets)
Source tier: primary
Source content: CLC site: campaign finance ("Voters Have a Right to Know") and voting rights ("Every Voice Must Be Heard") issue areas with active voting-rights litigation. Inside Philanthropy: "nonpartisan organization established in 2002 that employs litigation, policy advocacy and strategic communications."
Comparison: Nonpartisan status, campaign-finance focus, and voting-rights litigation each confirmed across the org's own site and Inside Philanthropy.
Decision: corroborated

## Claim 11: "[CLC] received a two-year $300,000 Democracy grant in 2024"

Source: https://www.carnegie.org/news/articles/carnegie-corporation-of-new-york-board-approves-63-grants-totaling-32855000/ + https://www.carnegie.org/grants/grants-database/grantee/campaign-legal-center/
Source tier: primary
Source content: Board article (meeting June 6, 2024): "24-month grant of $300,000". Grants database: "$300,000, June 6, 2024, 24 months, Strengthening U.S. Democracy."
Comparison: Amount, duration, and year match two records of the funder's own primary trail (plus Inside Philanthropy).
Decision: corroborated

## Claim 12: "[the CLC grant was] specifically for work on 'how AI can influence elections'" (echoed in frontmatter `focus` scalar and the insidephilanthropy sources[].note)

Source: https://www.carnegie.org/grants/grants-database/grantee/campaign-legal-center/ + June 2024 board article + Inside Philanthropy (snippets)
Source tier: primary
Source content: Grants database and board article both: "24-month grant of $300,000 for general support" — no AI-specific purpose. Inside Philanthropy itself: "a two-year, $300,000 general support grant" to an organization that "is addressing concerns about how AI can influence elections."
Comparison: The funder's own records designate the grant as general support; even the cited Inside Philanthropy piece frames AI-elections work as CLC's focus, not the grant's designated purpose. The body token "specifically for work on" contradicts the best sources; correct replacement: a general-support grant (with AI-elections work as CLC's focus per Inside Philanthropy). Fix locations: body § "The Democracy program and its AI-adjacent lane" and the frontmatter `focus` scalar's "funds legal-policy work on AI's influence on elections" phrasing — rewording is prose judgment, so Editor should flag to Researcher.
Decision: correction

## Claim 13: "Mannion naming AI deepfake technology's capacity to 'promote conspiracy theories before and during the 2024 election' as the driver"

Source: https://www.insidephilanthropy.com/home/2024-7-15-the-election-isnt-the-end-point-a-deep-dive-into-the-carnegie-corporations-democracy-giving (via search snippets)
Source tier: mainstream
Source content: "Geri Mannion ... mentioned coming across a story about Arizona officials running tests using AI and deepfakes to see how the technology could promote conspiracy theories before and during the 2024 election."
Comparison: The quoted fragment matches the source verbatim; single non-primary canonical source (article 403s on direct fetch).
Decision: single-source

## Claim 14: "Carnegie also funds Protect Democracy ($450,000 general support, September 2025)"

Source: https://carnegie.org/article/carnegie-corporation-of-new-york-board-approves-94-grants-totaling-63219000/
Source tier: primary
Source content: Board meeting September 11, 2025: Protect Democracy (Washington, DC) — "24-month grant of $450,000 for general support."
Comparison: Amount, purpose, and date match the funder's own record.
Decision: primary-sourced

## Claim 15: "[Protect Democracy] whose work spans election monitoring, media scrutiny, and litigation against democratic backsliding"

Source: https://protectdemocracy.org/about-us/
Source tier: primary
Source content: "a cross-ideological nonprofit group dedicated to defeating the authoritarian threat"; litigation "to defend the rule of law ... to counter disinformation"; "a strategic communications and coalition partner"; operates VoteShield, which "analyzes public data to improve transparency, security, and confidence in elections."
Comparison: Election monitoring (VoteShield), communications/media work, and litigation against authoritarian threat all confirmed on the org's own site.
Decision: primary-sourced

## Claim 16: "the Center for Tech and Civic Life ($1,000,000 general support, December 2025)"

Source: https://carnegie.org/article/carnegie-corporation-of-new-york-board-approves-57-grants-totaling-38485000/
Source tier: primary
Source content: Board meeting December 11, 2025: Center for Tech and Civic Life — "24-month grant of $1,000,000 for general support."
Comparison: Amount, purpose, and date match the funder's own record.
Decision: primary-sourced

## Claim 17: "[CTCL] the nonpartisan election-administration organisation that helps states run digital voter registration and poll-worker programmes and has integrated AI considerations into its election-security work"

Source: https://www.techandciviclife.org/
Source tier: primary
Source content: Mission: "Catalyzing excellent election administration across every jurisdiction in the U.S."; Ballot Information Project ("who and what is on the ballot"); course "Leading a Successful Poll Worker Program"; course "Cybersecurity for Election Officials."
Comparison: Election-administration focus and poll-worker programmes confirmed on the org's own site; but "helps states run digital voter registration" is not supported (CTCL's tools are ballot information and election-official training, and it works with local officials rather than running state voter registration), "nonpartisan" appears only in Alliance-coalition materials via snippets, and no source was found for "integrated AI considerations into its election-security work" (the security offering found is a cybersecurity course). Partial support on a judgment-loaded characterization.
Decision: uncorroborated

## Claim 18: "In June 2024 Carnegie approved a $350,000 twelve-month grant to Common Sense Media for an AI ratings system designed to assess 'the ethical use, transparency, safety, and impact of AI products for families'"

Source: https://www.carnegie.org/news/articles/carnegie-corporation-of-new-york-board-approves-63-grants-totaling-32855000/ (+ https://carnegie.org/grantee/common-sense-media/)
Source tier: primary
Source content: Board meeting June 6, 2024: Common Sense Media — $350,000, 12 months, "project support of an artificial intelligence ratings system designed to assess the ethical use, transparency, safety, and impact of AI products for families."
Comparison: Amount, duration, date, purpose, and the quoted language match the funder's record verbatim.
Decision: primary-sourced

## Claim 19: "a $1.55 million eighteen-month grant announced in March 2025, supporting development of fifty-four new and updated K–8 ... lessons, public-library teen workshops at five pilot locations nationwide, and the 2025 Common Sense Summit" (+ release quote on "AI-generated content that make it challenging to distinguish fact from fiction")

Source: https://www.commonsensemedia.org/press-releases/carnegie-corporation-of-new-york-awards-155m-to-common-sense-media-to-reimagine-digital-literacy
Source tier: primary
Source content: "$1.55 million over 18 months," announced March 27, 2025; "54 new and updated K–8 lessons"; "public library teen center workshops with 5 pilot program sites across the country"; "sponsorship of the 2025 Common Sense Summit"; "Today's students are bombarded with misinformation, conspiracy theories, and AI-generated content that make it challenging to distinguish fact from fiction."
Comparison: Amount, duration, announcement date, lesson count, workshop pilot-site count, Summit, and the framing quote all match the grantee's own press release.
Decision: primary-sourced

## Claim 20: the fifty-four lessons are "media and AI literacy lessons" (body + sources[].note for the commonsensemedia URL)

Source: https://www.commonsensemedia.org/press-releases/carnegie-corporation-of-new-york-awards-155m-to-common-sense-media-to-reimagine-digital-literacy
Source tier: primary
Source content: The release describes the 54 lessons as covering "media literacy, cyberbullying, and online harms"; the phrase "AI literacy" does not appear in the release, whose only AI mention is landscape framing ("a digital landscape shaped by misinformation, artificial intelligence, and social media algorithms").
Comparison: The "media literacy" half is supported; the "AI literacy" characterization of the lessons is not found in the cited source. Absence rather than contradiction (Common Sense's curriculum does carry AI-literacy strands, and the release's topic list may be non-exhaustive), so not asserted as error.
Decision: uncorroborated

## Claim 21: "A separate $400,000 grant to the Digital Inquiry Group (June 2025) updated school-based digital literacy resources to include navigating AI across multiple classroom subjects"

Source: no canonical source found
Source tier: none
Source content: The cited carnegie.org June-2025 article URL 404s (site restructure). No DIG grant found in: the Carnegie grants database (grantee-page slugs 404; DB query shell), search across carnegie.org's relocated board-approval articles, DIG's own site (inquirygroup.org/history lists U.S. Dept of Education, Library of Congress, Google.org as funders; no Carnegie mention), or general search for the amount. The located June-2025-adjacent board record found via search (June 12 meeting, 39 grants totaling $20,017,000) could not be confirmed to carry a DIG line.
Comparison: The claim rests on a now-dead primary URL and no substitute source was reachable (web.archive.org blocked in this harness). Not contradicted — unverifiable this pass.
Decision: uncorroborated

## Claim 22: "The News Literacy Project ($1.2 million general support, December 2025)"

Source: https://carnegie.org/article/carnegie-corporation-of-new-york-board-approves-57-grants-totaling-38485000/
Source tier: primary
Source content: Board meeting December 11, 2025: News Literacy Project — "24-month grant of $1,200,000 for general support."
Comparison: Amount, purpose, and date match the funder's own record.
Decision: primary-sourced

## Claim 23: "iCivics ($2.5 million general support, September 2025)" (frontmatter note: $2,544,000)

Source: https://carnegie.org/article/carnegie-corporation-of-new-york-board-approves-94-grants-totaling-63219000/
Source tier: primary
Source content: Board meeting September 11, 2025: iCivics (Cambridge, MA) — "24-month grant of $2,544,000 for general support."
Comparison: Frontmatter's exact $2,544,000 matches the record; the body's "$2.5 million" is consistent rounding.
Decision: primary-sourced

## Claim 24: "[NLP and iCivics] whose core work — news literacy for students and civic education games for classrooms — has been reshaped by the AI content environment and now integrates AI-literacy components"

Source: https://newslit.org/ai/ + https://ed.icivics.org/professional-development/what-students-need-know-about-ai (via search)
Source tier: primary
Source content: NLP maintains a "Teaching About AI" resource hub with AI lessons on its Checkology platform; iCivics offers "What Students Need to Know About AI" and the Civic Digital Literacy Project, including "videos where students explore the role that AI could play in influencing elections."
Comparison: Each organization's own site confirms integrated AI-literacy offerings; core-work characterizations (news literacy; civic education for classrooms) match their self-descriptions.
Decision: primary-sourced
