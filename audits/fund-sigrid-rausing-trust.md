---
entity_id: fund-sigrid-rausing-trust
entity_hash: 4a9b097b12370e86807bfe4dc64db02a5ceeac6d
audit_date: 2026-05-23
pass: 2
status: discrepancy
claims_total: 16
claims_verified: 12
claims_discrepancy: 1
claims_unverifiable: 3
sources_consulted:
  - https://www.sigrid-rausing-trust.org/
  - https://www.sigrid-rausing-trust.org/who-we-are/
  - https://www.sigrid-rausing-trust.org/who-we-are/our-history/
  - https://www.sigrid-rausing-trust.org/programme/human-rights-and-the-rule-of-law/
  - https://www.sigrid-rausing-trust.org/programme/open-societies/
  - https://www.sigrid-rausing-trust.org/grantee/foxglove/
  - https://www.sigrid-rausing-trust.org/story/two-srt-grantees-celebrate-as-european-parliament-approves-draft-artificial-intelligence-act/
  - https://en.wikipedia.org/wiki/Sigrid_Rausing
  - https://en.wikipedia.org/wiki/Panoptykon_Foundation
  - https://en.wikipedia.org/wiki/Citizen_Lab
  - https://www.hrw.org/about/people/sigrid-rausing
  - https://www.hrw.org/topic/arms/killer-robots
  - https://www.foxglove.org.uk/wp-content/uploads/2025/03/2024_03_14-PUB-FINAL-SIGNED-Foxglove-Legal-CIC-2024-Accounts.pdf
---

Pass-2 trigger note: this re-audit was triggered by an `entity_hash` mismatch with pass 1. The diff against the pass-1 hash (`7d3bfdc…`) is **frontmatter prose-quoting only** — every `sources[].note` scalar was single-quoted (Editor's *Frontmatter prose-quoting repair* act, 2026-05-22). Body claims are byte-identical to pass 1; all sources re-fetched this session except the Foxglove PDF (re-attempted, still binary). Outcomes mirror pass 1 by construction.

## Claim 1: "UK private grantmaking trust [established in 1995]"

Source: https://www.sigrid-rausing-trust.org/who-we-are/our-history/
Source content: "The Trust was founded in 1995." Timeline 1995 entry: "Sigrid Rausing establishes the Trust. The Trust's initial focus included human rights, women's rights and environmental protection."
Comparison: Body's "established in 1995" matches the Trust's own history page verbatim.
Decision: verified

## Claim 2: "renamed from the Ruben and Elisabeth Rausing Trust to its current name in 2003"

Source: https://en.wikipedia.org/wiki/Sigrid_Rausing
Source content: "In 1996, she transferred the funds to the Ruben and Elisabeth Rausing Trust... the trust was renamed the Sigrid Rausing Trust in 2003."
Comparison: Wikipedia confirms prior name and 2003 renaming. Named-entity definitional fact about formal name — Wikipedia-alone-sufficient per the source rule.
Decision: verified

## Claim 3: "Trust reports having awarded more than £575 million to over 950 organisations since founding"

Source: https://www.sigrid-rausing-trust.org/
Source content: "£591m in grants committed" and "The Trust has supported more than 950 organisations around the world."
Comparison: Current homepage figure (£591m) is consistent with body's "more than £575 million" (true lower bound); the "over 950 organisations" matches "more than 950 organisations" on the homepage.
Decision: verified

## Claim 4: "Sigrid Rausing — a Swedish-British anthropologist and publisher"

Source: https://en.wikipedia.org/wiki/Sigrid_Rausing
Source content: "Swedish-British philanthropist, anthropologist and publisher"
Comparison: Body's three identity descriptors match Wikipedia's lead verbatim.
Decision: verified

## Claim 5: "her family is associated with the Tetra Pak packaging fortune"

Source: https://en.wikipedia.org/wiki/Sigrid_Rausing
Source content: "Her paternal grandfather was Ruben Rausing, who co-founded the Swedish packaging company Tetra Pak."
Comparison: Wikipedia confirms the family-Tetra Pak link via the paternal grandfather.
Decision: verified

## Claim 6: "also publishes the literary magazine *Granta*"

Source: https://en.wikipedia.org/wiki/Sigrid_Rausing
Source content: "Rausing acquired Granta in autumn 2005 and became its publisher."
Comparison: Wikipedia confirms publisher role with Granta.
Decision: verified

## Claim 7: "is an [emeritus member of Human Rights Watch's international board]"

Source: https://www.hrw.org/about/people/sigrid-rausing
Source content: "She serves on the boards of Human Rights Watch in New York and Charleston, the former home of Vanessa Bell and Duncan Grant, in Sussex." The word "emeritus" does not appear anywhere on the HRW page; the phrase "international board" does not appear either.
Comparison: HRW describes Sigrid Rausing as currently serving on the New York and Charleston boards, with no "emeritus" qualifier and no use of the "international board" framing. The body's claim that she is an "emeritus member of HRW's international board" contradicts both the role status (currently serving, not emeritus) and the board name (New York / Charleston, not "international").
Decision: discrepancy

## Claim 8: "Trust now organises its grantmaking around three programmes: Human Rights and the Rule of Law, Open Societies, and Environment"

Source: https://www.sigrid-rausing-trust.org/who-we-are/ ; programme pages at /programme/human-rights-and-the-rule-of-law/ and /programme/open-societies/
Source content: "support the values and principles of human rights and the rule of law; promote cohesive, creative and open societies; and support the preservation of nature and the regulation of harmful chemicals."
Comparison: The three thematic areas on the who-we-are page map directly to the three named programmes; programme pages exist at the matching URLs for HRRoL and Open Societies.
Decision: verified

## Claim 9: "Human Rights and Rule of Law programme covers access to justice, accountability for international crimes, torture prevention, criminal justice, and reparations work"

Source: https://www.sigrid-rausing-trust.org/programme/human-rights-and-the-rule-of-law/
Source content: Three priority areas listed: "Protecting the rule of law and access to justice; Accountability and redress for gross human rights violations; Preventing torture and promoting fairer criminal justice systems"
Comparison: Four of the body's five items map to the source's three priority areas. "Reparations work" is not used on the programme page — the closest term is "redress for gross human rights violations". The paraphrase between "reparations" and "redress" is judgment-loaded, so this is unverifiable rather than verified.
Decision: unverifiable

## Claim 10: "Open Societies programme covers freedom of expression and public-interest media, freedom of association and civic participation, anti-corruption and undue influence, and the arts"

Source: https://www.sigrid-rausing-trust.org/programme/open-societies/
Source content: "Freedom of expression and public interest media; Freedom of association and civic participation; Corruption and undue influence; The Arts"
Comparison: The body's four-item list matches the source's four priority areas exactly.
Decision: verified

## Claim 11: "In November 2022 the Trust approved a £450,000 grant to Foxglove under the Human Rights and Rule of Law programme, with a previous £100,000 in grants since 2021"

Source: https://www.sigrid-rausing-trust.org/grantee/foxglove/
Source content: "Total of previous grants £550,000"; "Supported from 2021 to 2026"; programme "Human Rights and Rule of Law".
Comparison: Aggregate total (£550,000) is consistent with the body's £450k + £100k breakdown; programme name matches; 2021 start year matches. However, the page does not show the specific November 2022 date or the £450,000 individual grant amount — only the aggregated total. Cannot independently confirm the specific date/amount breakdown from this primary source.
Decision: unverifiable

## Claim 12: "Foxglove's annual accounts to 30 June 2024 confirm the relationship from the grantee side and place the Trust among the small set of named foundation funders for Foxglove's UK strategic-litigation work"

Source: https://www.foxglove.org.uk/wp-content/uploads/2025/03/2024_03_14-PUB-FINAL-SIGNED-Foxglove-Legal-CIC-2024-Accounts.pdf
Source content: PDF could not be parsed into readable text via WebFetch (re-attempted this pass; still returns binary/flate-encoded stream).
Comparison: Cannot verify the grantee-side confirmation in this pass without readable PDF content. No textual content from the document is available to compare to the body's claim.
Decision: unverifiable

## Claim 13: "[Human Rights Watch] anchored the [Stop Killer Robots] coalition through its Arms Division"

Source: https://www.hrw.org/topic/arms/killer-robots
Source content: "a founding member of Stop Killer Robots campaign, a civil society coalition that calls for a new international treaty to prohibit and restrict autonomous weapons systems." Staff bylines on the page include "Senior Advisor, Crisis, Conflict and Arms Division" and "Deputy Director, Crisis, Conflict and Arms Division".
Comparison: Source confirms HRW's founding-member role in the coalition; the page is at /topic/arms/ and the responsible division is the "Crisis, Conflict and Arms Division" (commonly shortened to Arms Division). Body's "anchored... through its Arms Division" is within paraphrase tolerance of "founding member" + the arms-focused division attribution.
Decision: verified

## Claim 14: "Panoptykon Foundation in Poland, focused on mass-surveillance and platform accountability"

Source: https://en.wikipedia.org/wiki/Panoptykon_Foundation
Source content: "Polish NGO whose primary goal is to defend basic freedom and human rights against threats posed by the development of modern surveillance technologies." Stated objectives include "Protection of the human rights in the surveillance society" and analysing legislation on surveillance and data collection in Poland and the EU.
Comparison: Polish location verified; surveillance focus verified. "Platform accountability" framing is within tolerance for the foundation's stated work on commercial-entity technology and EU-level data regulation.
Decision: verified

## Claim 15: "Citizen Lab at the University of Toronto, which researches state surveillance and digital-rights abuses"

Source: https://en.wikipedia.org/wiki/Citizen_Lab
Source content: "The Citizen Lab is an interdisciplinary laboratory based at the Munk School of Global Affairs & Public Policy at the University of Toronto." "The laboratory studies information controls that impact the openness and security of the Internet and that pose threats to human rights."
Comparison: University of Toronto location verified; surveillance / digital-rights research focus is within paraphrase tolerance of "information controls... that pose threats to human rights".
Decision: verified

## Claim 16: "Irish Council for Civil Liberties and Fair Trials' two-year campaign on the regulation"

Source: https://www.sigrid-rausing-trust.org/story/two-srt-grantees-celebrate-as-european-parliament-approves-draft-artificial-intelligence-act/
Source content: Named grantees are "The Irish Council for Civil Liberties" (ICCL) and "Fair Trials"; "Two SRT grantees... have been campaigning for this law for two years".
Comparison: Both named grantees and the two-year duration match the body.
Decision: verified
