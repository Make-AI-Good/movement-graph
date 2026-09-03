---
id: org-freedom-of-the-press-foundation
type: organization
name: Freedom of the Press Foundation
status: active
confidence: high
tags: [usa, national, international, press-freedom, whistleblower-protection, digital-security, source-protection, open-source-tools, ai-surveillance, surveillance, nonprofit]
created: 2026-09-02
last_updated: 2026-09-02
founded: 2012
location: national (headquartered in Brooklyn, New York)
website: https://freedom.press/
strategies: [strat-ai-whistleblower-protection-infrastructure, strat-distribute-user-side-technical-countermeasures]
key_people: []
board_and_advisors: []
related_orgs: [org-fight-for-the-future, org-electronic-frontier-foundation, org-ai-whistleblower-initiative]
funders: [fund-craig-newmark-philanthropies, fund-macarthur-foundation, fund-open-society-foundations]
sources:
  - url: https://freedom.press/about/
    last_checked: 2026-09-02
    note: 'FPF About page — mission and programs overview: SecureDrop (100+ installations), digital security education (8,800+ journalists trained in five years), U.S. Press Freedom Tracker (2,000+ published incident reports), Dangerzone.'
  - url: https://en.wikipedia.org/wiki/Freedom_of_the_Press_Foundation
    last_checked: 2026-09-02
    note: 'Wikipedia — founded December 17 2012; co-founders Daniel Ellsberg, John Perry Barlow, Trevor Timm, Rainey Reitman; SecureDrop originally created by Aaron Swartz; board includes Edward Snowden (joined 2014), Laura Poitras, Azmat Khan, John Cusack, Katie Drummond; 2024 revenue $5.2M / expenses $7.2M; Hugh Hefner First Amendment Award 2013; SPJ James Madison Award 2016.'
  - url: https://securedrop.org/news/looking-back-at-2025/
    last_checked: 2026-09-02
    note: 'SecureDrop 2025 review — Workstation exited pilot stage; WEBCAT project and new SecureDrop Protocol in development with ETH Zurich security audit underway; CTO Dr. Jennifer Helsby; automated Ubuntu Noble server migration completed without manual intervention for most installations.'
  - url: https://www.freepress.net/news/civil-rights-and-civil-liberties-groups-launch-solidarity-over-surveillance-campaign
    last_checked: 2026-09-02
    note: 'Solidarity Over Surveillance coalition — launched May 28 2026; organized by Free Press and Disinfo Defense League; 23+ member orgs including FPF, NAACP, Fight for the Future, GLAAD, UnidosUS, Reporters Without Borders, 18 Million Rising, America''s Voice, Common Cause, VotoLatino; campaign addresses AI-powered surveillance, data broker sales to law enforcement, and extractive data centers.'
  - url: https://freedom.press/digisec/
    last_checked: 2026-09-02
    note: 'Digital Security Education program — services include organizational security audits, journalism school curriculum, source protection guides; AI safety newsroom guidance active (newsroom AI policy reviews, December 2025 journalist security checklist); training covers security novices through highest-risk environments.'
---

# Freedom of the Press Foundation

The Freedom of the Press Foundation (FPF) is a Brooklyn-based nonprofit founded in December 2012 to fund and support freedom of the press through open-source security tools, journalist digital security training, and press freedom advocacy. Its two central contributions to the movement are SecureDrop — the world's most widely deployed open-source whistleblower submission system — and a digital security education program that has trained [more than 8,800 journalists](https://freedom.press/about/) over five years. FPF operates as cross-cutting infrastructure: the journalists, documentary filmmakers, and civil-society actors it serves are non-AI professionals who depend on its tools and training to protect sources and communicate securely in an era of advancing surveillance, including AI-powered surveillance systems that have lowered the cost of network-metadata analysis and targeted journalist monitoring.

## Founding and background

FPF was [co-founded on December 17, 2012](https://en.wikipedia.org/wiki/Freedom_of_the_Press_Foundation) by Daniel Ellsberg, John Perry Barlow, Trevor Timm, and Rainey Reitman in direct response to the multi-year financial blockade against WikiLeaks by major payment processors following the Cablegate publication. The initial mandate was crowdfunding for independent journalism organizations facing similar financial pressure; that mandate evolved rapidly toward technical infrastructure and digital security training as the surveillance threats facing journalists and their sources sharpened over the following decade.

Trevor Timm, a co-founder, serves as executive director. The board is led by president Rainey Reitman and includes Laura Poitras (documentary filmmaker, *Citizenfour*), Edward Snowden (NSA whistleblower, joined 2014), Azmat Khan (investigative journalist), John Cusack, and Katie Drummond. Co-founders Daniel Ellsberg and John Perry Barlow are listed in memoriam.

## SecureDrop

SecureDrop is FPF's central technical contribution to the movement — an [open-source whistleblower submission system](https://freedom.press/about/) installed on-premises by news organizations that allows sources to submit documents and communicate with journalists over the Tor network without leaving identifying metadata. It was originally created in 2012 by Aaron Swartz under the name DeadDrop and was adopted by FPF following Swartz's death in January 2013. [More than 100 news organizations](https://freedom.press/about/) operate SecureDrop installations, including The New York Times, The Washington Post, The Guardian, and [ProPublica](../organizations/org-propublica.md).

SecureDrop's architecture defeats the network-metadata surveillance that AI-powered traffic analysis has made more tractable: sources access a unique codename over Tor, the journalist-side workstation is air-gapped from the internet, and no IP logs are kept. As of 2025, the [SecureDrop Workstation](https://securedrop.org/news/looking-back-at-2025/) — the journalist-facing desktop client — officially exited its pilot stage. The technical team is developing two next-generation projects: WEBCAT, which addresses a long-standing limitation in browser-based cryptography, and a new SecureDrop Protocol providing end-to-end encryption between sources and journalists, with a security audit underway at ETH Zurich.

## Digital security education

FPF's digital security education program delivers training to journalists, documentary filmmakers, and news organizations across the full spectrum from security beginners to reporters in the highest-risk environments. Curriculum covers account hardening, encrypted communications, anonymous web browsing, harassment mitigation, and source protection protocols. FPF also provides comprehensive organizational security audits for newsrooms and a curriculum designed specifically for journalism school integration.

As AI-enabled threats have emerged as a distinct threat category, FPF's training has incorporated AI-specific guidance — including [newsroom AI safety policy reviews](https://freedom.press/digisec/) and an annually updated journalist digital security checklist (revised December 2025) — positioning the program as a distribution channel for practical countermeasures against AI-powered surveillance and targeting of journalists.

## Dangerzone and open-source tool portfolio

[Adopted by FPF in 2022](https://en.wikipedia.org/wiki/Freedom_of_the_Press_Foundation), Dangerzone is an open-source tool that converts potentially hostile documents — PDFs, Office files, images — into safe versions by processing them inside an isolated, network-disconnected container that strips malware and metadata before re-rendering a clean PDF. It addresses the attack vector of weaponized documents delivered to journalists, a mechanism commonly used in state-level targeting operations. Dangerzone extends FPF's infrastructure posture from secure submission (SecureDrop) through secure document handling (Dangerzone).

FPF also co-developed Haven, a mobile security application built with the Guardian Project, designed to detect physical surveillance of activists and journalists. Haven predates FPF's formal partnership with Guardian Project on the Dangerzone era but represents the same model: open-source, journalist-oriented security tools distributed through civil-society channels.

## U.S. Press Freedom Tracker

The U.S. Press Freedom Tracker is a public database of documented press freedom violations in the United States, with [more than 2,000 published incident reports](https://freedom.press/about/). Tracked incidents include journalist arrests, assaults at protests, newsroom raids, equipment seizures, and subpoenas for source identification. The Tracker functions as both an accountability record and a mobilization surface: it provides the empirical basis for advocacy, litigation support, and public campaigns. Lauren Harper serves in the organization's Daniel Ellsberg Chair on Government Secrecy, anchoring FPF's FOIA transparency and classification-accountability work alongside the Tracker.

## Solidarity Over Surveillance and the AI surveillance coalition

FPF is a member of the Solidarity Over Surveillance (SOS) coalition, [launched May 28, 2026](https://www.freepress.net/news/civil-rights-and-civil-liberties-groups-launch-solidarity-over-surveillance-campaign) by Free Press and the Disinfo Defense League. The coalition brings together more than 23 civil-rights and civil-liberties organizations — including the NAACP, [Fight for the Future](../organizations/org-fight-for-the-future.md), GLAAD, UnidosUS, Reporters Without Borders, 18 Million Rising, America's Voice, Common Cause, and VotoLatino — in a campaign explicitly targeting AI-powered surveillance systems. The coalition's priorities include stopping data brokers from selling sensitive user data to law enforcement, protecting dissent and anonymity against AI surveillance infrastructure, exposing local and state government surveillance partnerships through open-records requests, and mobilizing resistance to the construction of extractive data centers. FPF's SOS membership situates its source-protection mandate inside a broader civil-rights coalition directly challenging AI surveillance systems as a threat to press freedom and democratic dissent.
