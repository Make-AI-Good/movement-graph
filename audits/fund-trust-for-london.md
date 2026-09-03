---
entity_id: fund-trust-for-london
entity_hash: b5f5c0923dbad966c98277c02941aad3ee95d929
audit_date: 2026-09-03
pass: 1
status: supported
claims_total: 19
claims_corroborated: 6
claims_primary_sourced: 8
claims_single_source: 3
claims_uncorroborated: 2
open_corrections: 0
sources_consulted:
  - https://trustforlondon.org.uk/about/
  - https://trustforlondon.org.uk/about/our-history/
  - https://trustforlondon.org.uk/about/finance-and-investment/
  - https://trustforlondon.org.uk/funding/
  - https://trustforlondon.org.uk/funding/economic-justice/decent-work/technological-advancements/
  - https://trustforlondon.org.uk/funding/economic-justice/decent-work/institute-for-future-of-work/
  - https://trustforlondon.org.uk/news/will-ai-deepen-or-disrupt-poverty-in-london-looking-ahead-to-2026/
  - https://trustforlondon.org.uk/news/manny-hothi-appointed-the-new-ceo-of-trust-for-london/
  - https://trustforlondon.org.uk/news/new-charity-ai-task-force-launched/
  - https://en.wikipedia.org/wiki/Trust_for_London
  - https://en.wikipedia.org/wiki/Wellcome_Trust
  - https://en.wikipedia.org/wiki/Sigrid_Rausing
  - https://register-of-charities.charitycommission.gov.uk/en/charity-search/-/charity-details/205629 (403 on direct fetch; content via search snippets of the register record)
  - https://www.influencewatch.org/organization/trust-for-london/ (via search snippets)
---

## Claim 1: "established in 1891 as the City Parochial Foundation, created by the City of London Parochial Charities Act 1883 to consolidate the endowments of more than a hundred City parishes"

Source: https://trustforlondon.org.uk/about/our-history/ + https://trustforlondon.org.uk/about/ + https://en.wikipedia.org/wiki/Trust_for_London
Source tier: primary
Source content: History page: "Over the centuries the 112 parishes within the City of London received around 1,400 separate charitable gifts and bequests"; the Central Fund and City Church Fund "together made up the City Parochial Foundation". About page: "supporting work for a fairer city since 1891". Wikipedia: established 1891 as City Parochial Foundation under the City of London Parochial Charities Act 1883.
Comparison: 1891 date, 1883 Act, and >100-parish consolidation all confirmed across the Trust's own pages and Wikipedia; "accumulated across four centuries" is a close paraphrase of the history page's "over the centuries" with ~1,400 gifts. Also covers scalar:sources[1].note (history-page note, same content).
Decision: corroborated

## Claim 2: "Registered as charity number 205629"

Source: https://trustforlondon.org.uk/about/ + Charity Commission register record for 205629 (via search snippet)
Source tier: primary
Source content: About page lists charity registration number 205629; the Charity Commission register record is titled "TRUST FOR LONDON - 205629".
Comparison: Exact match on both the Trust's own site and the official register. Also covers scalar:sources[0].note.
Decision: corroborated

## Claim 3: "In 2010, the Foundation and a separately-endowed entity also called Trust for London (established in 1986 with a £10 million government endowment when the Greater London Council was abolished) were amalgamated into the present single organisation"

Source: https://trustforlondon.org.uk/about/our-history/ + https://en.wikipedia.org/wiki/Trust_for_London
Source tier: primary
Source content: History page: "The government provided an endowment of £10 million when it abolished the Greater London Council in 1986 and asked City Parochial Foundation to manage this new organisation, Trust for London" and "In 2010, the Foundation and the Trust were amalgamated into one organisation to form the new Trust for London". Wikipedia: "changed its name to Trust for London in 2010".
Comparison: 1986, £10 million, GLC abolition, and 2010 amalgamation all match the primary source verbatim.
Decision: corroborated

## Claim 4: "governed by a 17-member Central Governing Body with trustees nominated by London councils, the Greater London Authority, the Church Commissioners, and the Corporation of the City of London"

Source: https://en.wikipedia.org/wiki/Trust_for_London
Source tier: tiebreaker
Source content: "There are now 17 members, mostly now nominated by the trust itself, although some members are still nominated by London councils, the Greater London Authority, the Church Commissioners, and the Corporation of the City of London."
Comparison: 17-member count and the four external nominating bodies match (named-entity formal-structure fact, Wikipedia-alone sufficient). Nuance: Wikipedia says most members are now nominated by the trust itself, with only some from the named bodies — the body's phrasing reads as if the four bodies nominate all trustees. No single wrong token, so not a correction. Also appears in scalar:focus.
Decision: single-source

## Claim 5: "Manny Hothi, who had previously served as the Trust's Director of Policy, became Chief Executive in July 2021"

Source: https://trustforlondon.org.uk/news/manny-hothi-appointed-the-new-ceo-of-trust-for-london/
Source tier: primary
Source content: "Manny, the current Director of Policy at the Trust for London, will take over as Chief Executive in July 2021."
Comparison: Role, prior position, and July 2021 date match the Trust's own announcement exactly. Also covers scalar:sources[6].note and the scalar:focus mention.
Decision: primary-sourced

## Claim 6: "distributes approximately £10 million annually" (scalar:focus; body "gives out around £10m each year" framing)

Source: https://trustforlondon.org.uk/about/ + Better Society Capital / Devex profiles (via search snippets)
Source tier: primary
Source content: About page: "We give out around £10m each year to groups fighting for a fairer London." Third-party profiles: "grants around £10 million each year"; "annual giving budget of £10.2 million (2025)".
Comparison: ~£10M/year confirmed by the Trust's own page and independent sector profiles. Also covers scalar:sources[0].note.
Decision: corroborated

## Claim 7: "an investment endowment of roughly £324–379 million" (also scalar:focus "Endowment base of roughly £324–379 million")

Source: https://www.influencewatch.org/organization/trust-for-london/ (via search snippet); cf. https://trustforlondon.org.uk/about/finance-and-investment/
Source tier: caution
Source content: InfluenceWatch (from filed accounts): long-term investments "over £379 million in 2021 and dropped slightly to £324 million in 2022". The Trust's own current finance page: "one of London's largest independent funders, with an endowment of around £300 million."
Comparison: The £324–379M range matches the 2021/2022 accounts vintage as reported by a caution-tier aggregator, but the Trust's own current page states "around £300 million" — no canonical source supports the range as stated today, and the figure is vintage-dependent. Not a correction (a rough range, no single wrong token), but sourcing does not confirm it.
Decision: uncorroborated

## Claim 8: "annual charitable expenditure that consistently exceeds income — £19.9 million against £9.98 million in 2024, the difference drawn from endowment returns"

Source: Charity Commission register record for 205629 (403 on direct fetch; figures via search snippet) + https://trustforlondon.org.uk/about/finance-and-investment/
Source tier: primary
Source content: Register record: "for the financial year ending 31 December 2024, the charity had total gross income of £9.98 million and total expenditure of £19.88 million". Finance page: the Trust aims to distribute approximately 4% of its endowment annually. Wikipedia (2023): revenue £11.4M against expenses £23M — same pattern.
Comparison: 2024 figures match the official register (£19.88M rounds to the body's £19.9M); the excess-over-income pattern recurs in 2023, supporting "consistently"; endowment-draw mechanism consistent with the Trust's stated 4%-of-endowment distribution policy.
Decision: primary-sourced

## Claim 9: scalar:sources[5].note — "charity number (205629), 2024 income (£9,978,639), 2024 expenditure (£19,881,100), 27 employees, and legal description as 'a charitable organisation that exists to reduce poverty and inequality in London'"

Source: Charity Commission register record for 205629 (403 on direct fetch; content via search snippets)
Source tier: primary
Source content: "Trust for London has 27 employees and 1 trustee. The organization exists to reduce poverty and inequality in London by funding the voluntary and community sector and others" + FY2024 gross income £9.98M / expenditure £19.88M.
Comparison: Scalar path sources[5].note. Employee count (27), rounded 2024 figures, and the legal description all match the register record as surfaced in snippets; the pound-exact figures could not be re-read directly (register 403s) but round correctly to the snippet values.
Decision: primary-sourced

## Claim 10: "Its grantmaking is restricted to Greater London" / scalar:focus "London-only grantmaker; does not fund outside Greater London"

Source: https://trustforlondon.org.uk/about/ + https://en.wikipedia.org/wiki/Trust_for_London
Source tier: primary
Source content: About page: "We give out around £10m each year to groups fighting for a fairer London"; "one of London's largest funders". Wikipedia: "aims to tackle poverty and inequality in London and its root causes"; register description: "exists to reduce poverty and inequality in London".
Comparison: Every source frames the Trust's giving as London-scoped; the London-only restriction is consistent across the Trust's own pages, Wikipedia, and the register description.
Decision: corroborated

## Claim 11: "two broad aims: economic justice (decent work, social security, ending the poverty premium, housing) and social justice (ending migrant destitution, racial justice, disability justice)"

Source: https://trustforlondon.org.uk/funding/
Source tier: primary
Source content: Economic justice: "decent work, improving social security, ending the poverty premium and tackling the housing crisis." Social justice: "ending migrant destitution, racial justice and disability justice."
Comparison: The two aims and all seven sub-areas match the Trust's own funding page exactly. Also covers the scalar:focus listing.
Decision: primary-sourced

## Claim 12: "The Trust supports up to 300 organisations at any one time"

Source: Better Society Capital / Devex organisation profiles (via search snippets)
Source tier: database
Source content: "supporting around 300 organisations at any given time"; "the Trust supports 300 organisations at any time working to tackle poverty and inequality in London".
Comparison: "Up to 300" is consistent with the profiles' "around 300 at any given time"; not found on a page of the Trust's own site fetched this session.
Decision: single-source

## Claim 13: "deliberately prioritises work that government will not or is unlikely to fund"

Source: https://en.wikipedia.org/wiki/Trust_for_London
Source tier: tiebreaker
Source content: The Trust supports "activities which government will not or is unlikely to fund," focusing on work considered challenging.
Comparison: Wikipedia matches the body's wording near-verbatim, but this is an organisational-approach characterization, not a named-entity definitional fact — outside the Wikipedia-alone list, and no second canonical source surfaced this session. Honest sourcing-strength label, not an error finding.
Decision: uncorroborated

## Claim 14: Technological-advancements strand goal — "the introduction of technology and artificial intelligence in workplaces is informed by the experiences of low-paid workers" — and its four funded categories (campaigns and policy, design and development, research, innovation testing)

Source: https://trustforlondon.org.uk/funding/economic-justice/decent-work/technological-advancements/
Source tier: primary
Source content: Goal verbatim: "The introduction of technology and artificial intelligence in workplaces is informed by the experiences of low-paid workers." Categories: "Campaigns and policy work to ensure that the development of fast-moving AI regulation is informed by voices of low paid workers"; "Work that brings the experiences of low paid workers into the design, development and testing of workplace technology, including algorithmic systems"; "High-quality research from worker-led groups, academics, think-tanks or civil society organisations"; "Testing new ways of using technology and artificial intelligence to improve pay and conditions of workers in London."
Comparison: Goal quote is verbatim; the body's four bullet categories map one-to-one onto the strand page's four funded-work types. Also covers scalar:sources[2].note and the scalar:focus description.
Decision: primary-sourced

## Claim 15: "Institute for the Future of Work (IFOW) is a named grantee under this strand, receiving £150,000 over three years (2025–2028) to act as a 'bridge between frontline groups and the legislative and regulatory ecosystem'"

Source: https://trustforlondon.org.uk/funding/economic-justice/decent-work/institute-for-future-of-work/
Source tier: primary
Source content: Grant page: amount £150,000, duration 2025–2028 (3 years); IFOW serves as a "bridge between frontline groups and the legislative and regulatory ecosystem" by amplifying worker voices in policy debates, developing practical guidance, conducting participatory impact assessments, and building partnerships to promote corporate accountability.
Comparison: Amount, duration, years, and the bridge quote all match the Trust's own grant page; the body's list of IFOW activities (amplifying voices, practical guidance, participatory impact assessments, corporate accountability frameworks) matches. Also covers scalar:sources[3].note.
Decision: primary-sourced

## Claim 16: 2026 outlook — Hothi "stated that 'workers must have a say over how AI will impact their jobs' and called for government to 'work with civil society, businesses and regulators' on AI governance" (+ scalar:sources[4].note mention of the Organise AI early warning system)

Source: https://trustforlondon.org.uk/news/will-ai-deepen-or-disrupt-poverty-in-london-looking-ahead-to-2026/
Source tier: primary
Source content: "workers must have a say over how AI will impact their jobs"; "government will need to work with civil society, businesses and regulators to manage the impacts of AI"; on Organise: "the AI early warning system. We'll help workers, primarily in low paid and insecure work, to evaluate AI roll-outs in real time".
Comparison: Both quoted fragments appear verbatim in the piece (Chief Executive's introduction by Manny Hothi); the Organise AI early-warning-system reference in scalar:sources[4].note is present in the piece.
Decision: primary-sourced

## Claim 17: "Trust for London also participates in the charity-sector AI task force convened by CAST and Zoe Amar Digital — a 20+ organisation coalition shaping government AI policy to benefit communities"

Source: https://trustforlondon.org.uk/news/new-charity-ai-task-force-launched/ + https://www.wearecast.org.uk/our-work/how-we-work-with-funders-and-partners/charity-ai-task-force/ (via search)
Source tier: primary
Source content: Trust's own news page: task force "convened by CAST and Zoe Amar Digital"; "more than 20 member organisations" with Trust for London explicitly listed; Zoe Amar: immediate priority is "responding to the government's AI plan, to help shape responsible innovation that truly serves communities."
Comparison: Conveners, 20+ membership, Trust for London's participation, and the shaping-government-AI-policy-for-communities framing all match; independently confirmed by CAST's task-force page and sector press coverage.
Decision: corroborated

## Claim 18: "identifies technology and AI as a key focus within its 2030 funding strategy"

Source: https://trustforlondon.org.uk/news/new-charity-ai-task-force-launched/ (+ "Our 2030 funding strategy" page confirmed extant via search)
Source tier: primary
Source content: Trust's news page: the Trust aims to fund initiatives ensuring "workers' experiences inform the roll out of AI in the workplace" as part of its broader technology-and-AI focus; a Trust page titled "Our 2030 funding strategy" exists, and the technological-advancements strand sits within the strategy's economic-justice aim.
Comparison: The 2030 strategy exists and the Trust's own pages tie a technology/AI funding focus to it; "key focus" is a fair gloss of a named funding sub-strand plus the Trust's stated AI framing.
Decision: primary-sourced

## Claim 19: "It sits alongside Sigrid Rausing Trust and Wellcome Trust as UK-headquartered foundations in the corpus... a private family foundation (Sigrid Rausing) or a biomedical research funder (Wellcome)"

Source: https://en.wikipedia.org/wiki/Sigrid_Rausing + https://en.wikipedia.org/wiki/Wellcome_Trust
Source tier: tiebreaker
Source content: Sigrid Rausing Trust: grant-making foundation established 1995 by Sigrid Rausing, Swedish-British philanthropist. Wellcome Trust: "a charitable foundation focused on health research based in London, United Kingdom," established 1936 from Henry Wellcome's legacies "to fund research to improve human and animal health."
Comparison: Both edge targets exist in the corpus (fund-sigrid-rausing-trust.md, fund-wellcome-trust.md). The definitional characterizations — SRT a founder-named private family foundation, Wellcome a London-based biomedical/health research funder — match Wikipedia (named-entity definitional facts, Wikipedia-alone sufficient). The rest of the positioning paragraph is corpus framing, not claim.
Decision: single-source
