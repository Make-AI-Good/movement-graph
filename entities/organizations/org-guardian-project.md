---
id: org-guardian-project
type: organization
name: Guardian Project
status: active
confidence: high
tags: [international, brooklyn, mobile-security, open-source, human-rights, content-provenance, proofmode, c2pa, digital-security, privacy, media-authenticity, cryptographic-authentication, activist-tools, journalist-tools]
created: 2026-09-02
last_updated: 2026-09-02
founded: 2009
location: Brooklyn, NY
website: https://guardianproject.info
strategies:
  - strat-content-provenance-and-cryptographic-authenticity
  - strat-civil-society-inside-technical-standards-bodies
  - strat-distribute-user-side-technical-countermeasures
key_people: []
board_and_advisors: []
related_orgs: [org-witness]
funders: [fund-macarthur-foundation, fund-knight-foundation]
sources:
  - url: https://guardianproject.info/
    last_checked: 2026-09-02
    note: Official website — mission statement, current projects (Orbot, ProofMode, Convene, ButterBox, Circulo, Clean Insights), organizational description as global collective of designers, trainers, researchers, and developers.
  - url: https://en.wikipedia.org/wiki/Guardian_Project_(software)
    last_checked: 2026-09-02
    note: Founding history — 2009, Nathan Freitas, Brooklyn; Orbot 20M+ downloads; funding from Google, MacArthur Foundation, Open Technology Fund, Knight Foundation, US State Department, Dutch Ministry of Foreign Affairs; partners include WITNESS, Tor Project, EFF, Freedom of the Press Foundation.
  - url: https://guardianproject.info/story/
    last_checked: 2026-09-02
    note: Organizational story — founding as open community in 2009; milestones include Orbot (2009), ObscuraCam (2011), ProofMode/CameraV (2013), Haven (2017); Tor Project, WITNESS, and OTF among early supporters.
  - url: https://cyber.harvard.edu/people/nfreitas
    last_checked: 2026-09-02
    note: Nathan Freitas Berkman Klein Center profile — Founder and Director of Guardian Project; nearly 15-year ProofMode collaboration with WITNESS; Affiliate at Berkman Klein Center for Internet and Society at Harvard; co-founder of Tibet Action Institute.
  - url: https://proofmode.org
    last_checked: 2026-09-02
    note: ProofMode project site — C2PA Android conformance certified May 2026; capture/notarize/verify suite on Android and iOS; collaboration among Guardian Project, WITNESS, and Okthanks since 2013; primary sponsorship from WITNESS and Filecoin Foundation for the Decentralized Web.
  - url: https://guardianproject.info/partners/
    last_checked: 2026-09-02
    note: Partners and funding page — Knight News Challenge 2012 for InformaCam; MacArthur Foundation founding support; OTF core apps support; Filecoin Foundation for Decentralized Web; NLnet; Google donation 2011; partners include Tor Project, WITNESS, F-Droid, Tibet Action Institute.
  - url: https://blog.witness.org/2017/07/media-activists-witness-guardian-project-back/
    last_checked: 2026-09-02
    note: WITNESS blog 2017 — Guardian Project collaboration on ObscuraCam and ProofMode for media activists; tools designed for human rights defenders and journalists in high-risk environments.
---

# Guardian Project

Guardian Project is a Brooklyn-based global collective of software developers, designers, advocates, and trainers who build open-source mobile security software and infrastructure for journalists, human rights defenders, and activists operating in high-risk contexts. Founded in 2009 by Nathan Freitas, the organization describes its mission as giving people a voice, enhancing safety, ensuring authenticity, and providing access to knowledge regardless of location or connectivity — building tools that serve those the internet was designed to surveil out of existence. Its applications have been downloaded and used by [millions worldwide across more than a dozen platforms](https://guardianproject.info/).

In the AI era, Guardian Project's core AI-facing work is [ProofMode](https://proofmode.org) — a mobile cryptographic authentication tool that establishes verifiable chain of custody for photos and videos at the moment of capture, co-developed with [WITNESS](org-witness.md) since 2013 and certified C2PA-conformant for Android in May 2026. ProofMode is the most widely deployed open-source mobile media authentication tool in civil-society use, and its C2PA conformance aligns grassroots human rights documentation with the industry standard being embedded in cameras, newsrooms, and platforms.

## Founding and organizational character

Guardian Project was [founded in 2009 by Nathan Freitas in Brooklyn](https://en.wikipedia.org/wiki/Guardian_Project_(software)), with early support from the MacArthur Foundation, the Open Technology Fund, WITNESS, and the Knight Foundation, among others. Freitas's prior work included digital security programs at the Tibet Action Institute — whose focus on Tibetan civil society under surveillance directly shaped the founding threat model — and the organization's design ethos from the outset placed activists and human rights defenders, not corporate or government users, as the primary beneficiaries. Guardian Project operates as an open community welcoming global contributions in code, translation, and mission support, while maintaining a core team responsible for flagship applications and the organization's technical infrastructure. Freitas serves as Founder and Director and holds an Affiliate position at the [Berkman Klein Center for Internet and Society at Harvard University](https://cyber.harvard.edu/people/nfreitas).

## Orbot and foundational digital security

Guardian Project's flagship tool, Orbot, brings the Tor anonymity and censorship-circumvention network to Android and iOS devices. [Orbot has been downloaded more than 20 million times](https://en.wikipedia.org/wiki/Guardian_Project_(software)), making it the most widely deployed mobile Tor client globally — a critical piece of infrastructure for journalists and activists in countries where the open internet is blocked or monitored. Guardian Project has maintained its collaboration with the Tor Project for more than 15 years, ensuring that Tor's desktop anonymity guarantees translate reliably into mobile contexts where frontline users most commonly operate.

Alongside Orbot, the organization has produced ObscuraCam (a privacy-protecting camera with automatic face-blurring, co-developed with [WITNESS](org-witness.md)), Haven (a physical security sensor application [co-developed with Edward Snowden and the Freedom of the Press Foundation](https://en.wikipedia.org/wiki/Guardian_Project_(software)) in 2017 to protect devices against physical tampering), and ChatSecure (an encrypted messaging client, now discontinued). Each tool in the portfolio has reflected the same underlying design discipline: security and privacy as constraints at the requirements stage, not features appended to a mainstream product, with the specific threat models of journalists, activists, and human rights defenders — not enterprise users — as the design reference.

## ProofMode and content authenticity

Guardian Project's most direct contribution to the AI-era accountability movement is [ProofMode](https://proofmode.org), a mobile authentication tool co-developed with [WITNESS](org-witness.md) beginning in 2013. ProofMode runs as a camera application on Android and iOS that captures media alongside a cryptographically signed bundle of metadata — GPS coordinates, device identifiers, sensor readings, and timestamps — establishing a verifiable chain of custody tied to the moment of capture. The cryptographic binding makes post-capture manipulation detectable: any alteration breaks the signature, and verification can be performed by any third party against a public key without requiring the documenter to reveal identifying information. ProofMode's threat model explicitly treats the safety and privacy of the person capturing evidence as constraints of equal standing to the verifiability of the evidence itself, a design choice that distinguishes it from enterprise authenticity tools built primarily for newsroom or platform compliance workflows.

[ProofMode achieved C2PA conformance for Android in May 2026](https://proofmode.org), aligning its provenance data with the industry-wide Coalition for Content Provenance and Authenticity standard now being embedded across cameras, newsrooms, and distribution platforms. The certification means that media captured via ProofMode can be inspected by any C2PA-aware verification tool — avoiding a siloed civil-society authenticity system and ensuring that human-rights-protective design principles (voluntary participation, privacy-preservation, safeguards against state weaponization) originate inside the standard rather than being negotiated in after-market policy discussions. ProofMode's mobile SDKs for Android and iOS allow newsrooms and human rights organizations to integrate authenticity infrastructure directly into their own applications. The ProofMode project is jointly sponsored by WITNESS and the Filecoin Foundation for the Decentralized Web; its development is a collaboration among Guardian Project, WITNESS, and [Okthanks](https://proofmode.org).

## Standards engagement and the AI-era mission

Beyond ProofMode, Guardian Project participates in the broader C2PA alongside [WITNESS](org-witness.md), the Content Authenticity Initiative (CAI), and industry members. This standards engagement is a deliberate strategy: provenance and authenticity infrastructure being embedded into cameras, phones, and platforms can become a surveillance surface as readily as an accountability tool — mandatory identity disclosure, platform-controlled trust hierarchies, forensic fingerprinting of journalists' devices. Guardian Project and WITNESS's shared presence in C2PA governance ensures that civil-society requirements (voluntary participation, independent verification, privacy by design) are articulated at the specification level, not bolted on post-ratification.

The organization's current portfolio also includes Convene (a Matrix-based encrypted chat platform), ButterBox (off-grid communication for low-connectivity contexts), Circulo (safety check-in and location-sharing), and [Clean Insights](https://guardianproject.info/) (a privacy-focused measurement platform enabling organizations to understand tool usage without collecting identifying data). Together these tools constitute an open-source mobile security stack purpose-built for the populations the AI-era authenticity and surveillance debates most directly concern — maintained outside the commercial incentive structures that shape mainstream platforms and governed by the design tradition that has defined Guardian Project since 2009.
