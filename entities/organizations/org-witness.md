---
id: org-witness
type: organization
name: WITNESS
status: active
confidence: high
tags: [international, brooklyn, human-rights, video-documentation, content-provenance, deepfake-defense, c2pa, proofmode, media-authenticity, ai-governance, standards-participation, cryptographic-authentication]
created: 2026-09-02
last_updated: 2026-09-02
founded: 1992
location: Brooklyn, NY
website: https://witness.org
strategies:
  - strat-content-provenance-and-cryptographic-authenticity
  - strat-civil-society-inside-technical-standards-bodies
key_people: []
board_and_advisors: []
related_orgs: [org-guardian-project]
funders: [fund-macarthur-foundation]
sources:
  - url: https://witness.org/about/
    last_checked: 2026-09-02
    note: Official about page — mission, global scale across five continents, programs on earth defense, conflict accountability, and emerging technologies.
  - url: https://en.wikipedia.org/wiki/Witness_(organization)
    last_checked: 2026-09-02
    note: 'Founding history — 1992, Peter Gabriel, Human Rights First, Reebok Human Rights Foundation $1M seed grant; independent since 2001; Brooklyn HQ; 300+ partner groups in 80+ countries.'
  - url: https://blog.witness.org/2021/12/witness-and-the-c2pa-harms-and-misuse-assessment-process/
    last_checked: 2026-09-02
    note: 'C2PA Harms and Misuse Assessment Process (December 2021) — WITNESS co-chairs Threats and Harms Task Force; harms process convened across Latin America, Africa, Asia, US, and Europe; human rights principles advocated (voluntary, privacy-preserving, independent verification, no weaponization).'
  - url: https://www.gen-ai.witness.org/deepfakes-rapid-response-force/
    last_checked: 2026-09-02
    note: Deepfakes Rapid Response Force — connects journalists and fact-checkers with media forensics and AI synthesis experts; case studies include Indian political audio clips, Burkinabe military footage, election-related deepfakes; TRIED Benchmark checklist for evaluating detection tools.
  - url: https://www.witness.org/portfolio_page/sam-gregory/
    last_checked: 2026-09-02
    note: 'Sam Gregory profile — Executive Director; co-created ObscuraCam and ProofMode with Guardian Project; led Prepare Don''t Panic since 2018; 2024 PhD on participatory media, AI, and trust (University of Westminster); WITNESS received inaugural 2024 Peabody Global Impact Award.'
  - url: https://proofmode.org/blog/witness-techadvo
    last_checked: 2026-09-02
    note: WITNESS and Guardian Project ProofMode collaboration since 2013 — mobile cryptographic authentication adding chain-of-custody metadata to photos and video for human rights defenders and journalists.
  - url: https://guardianproject.github.io/info/code/c2pa/
    last_checked: 2026-09-02
    note: Guardian Project C2PA integration page — ProofMode adds C2PA-compatible provenance data plus sensor information to strengthen evidentiary chain of custody.
  - url: https://www.macfound.org/grantee/witness-39751/
    last_checked: 2026-09-02
    note: 'MacArthur Foundation grantee record — $3,985,000 total across eight grants since 2013; most recent $750,000 three-year general operating support grant (2024) for continued training and platform accountability work.'
  - url: https://www.witness.org/navigating-human-rights-in-the-eu-ai-act-witnesss-call-for-thoughtful-transparency/
    last_checked: 2026-09-02
    note: 'EU AI Act Article 50 consultation submission — transparency must be privacy-preserving by design, non-mandatory, unable to be weaponized by states; C2PA involvement since 2020 framed as shaping authenticity infrastructure for human rights rather than corporate interests.'
---

# WITNESS

WITNESS is a Brooklyn-based international human rights organization founded in 1992 that helps people everywhere use video and audiovisual technology to document the truth and defend human rights. Founded by musician and activist Peter Gabriel in the wake of the Rodney King beating — which demonstrated that bystander video could expose state violence at global scale — WITNESS has [partnered with over 300 human rights groups in more than 80 countries](https://en.wikipedia.org/wiki/Witness_(organization)) across five continents. In the AI era it operates on two complementary tracks: building open cryptographic-authenticity infrastructure (ProofMode, C2PA governance) that enables human rights defenders to prove their documentation genuine, and training journalists, fact-checkers, and frontline communities globally to detect and respond to AI-generated deception.

## Founding and history

WITNESS was established in 1992 with a [$1 million seed grant from the Reebok Human Rights Foundation](https://en.wikipedia.org/wiki/Witness_(organization)), with Peter Gabriel as the public founder alongside Human Rights First. Gabriel's motivating experience was the 1988 Amnesty International Human Rights Now! Tour, on which he used a Sony Handycam to document survivor testimonies, and the 1991 Rodney King beating, whose bystander footage demonstrated at worldwide scale that ordinary cameras could create accountability for official abuses. The founding premise was that this capability should belong to every human rights defender, not just lucky bystanders: WITNESS would provide cameras, training, and institutional support so that video documentation of rights violations could happen systematically wherever they occurred. The organization became independent in 2001, relocated its operations to Brooklyn, and evolved from camera-and-training provision to advocacy infrastructure, legal evidence support, and — with the smartphone era — mobile-first documentation tools and digital authenticity systems. Sam Gregory has served as Executive Director, [leading WITNESS's global team and its "Fortify the Truth" strategic initiative](https://www.witness.org/portfolio_page/sam-gregory/) with over 25 years of experience at the intersection of video, technology, and human rights.

## ProofMode and content authenticity

WITNESS's most direct contribution to the AI-era accountability movement is [ProofMode](https://proofmode.org/blog/witness-techadvo), a mobile authentication tool co-developed with the [Guardian Project](org-guardian-project.md) beginning in 2013. ProofMode runs as a background service on Android devices, adding a cryptographically signed bundle of metadata to every photo or video captured — including sensor readings, device identifiers, GPS coordinates, and timestamps — that establishes a verifiable chain of custody tied to the moment of capture. The signed metadata makes after-the-fact manipulation detectable: any modification to the image breaks the cryptographic binding, and the verification can be performed by any third party against a public key without requiring the documenter to disclose identifying information. ProofMode is specifically designed for human rights contexts where the person capturing evidence is at risk; its threat model treats the privacy and safety of the documenter as constraints as fundamental as the verifiability of the evidence.

From 2024, [ProofMode has incorporated C2PA-compatible provenance data](https://guardianproject.github.io/info/code/c2pa/) alongside its additional sensor information, aligning civil-society documentation infrastructure with the technical standard that newsrooms, platforms, and camera manufacturers have begun embedding in professional workflows. This interoperability is deliberate strategy: ProofMode is positioned to produce content that any C2PA-aware verification tool can inspect, avoiding a siloed civil-society authenticity system while ensuring human-rights-protective design principles originate inside the standard rather than being grafted on post-hoc.

## C2PA governance: Threats and Harms Task Force

WITNESS has been [actively involved in the Coalition for Content Provenance and Authenticity (C2PA) since 2020](https://www.witness.org/navigating-human-rights-in-the-eu-ai-act-witnesss-call-for-thoughtful-transparency/), working to shape authenticity and provenance infrastructure so that it protects privacy and serves human-rights defenders and journalists rather than only corporate and state interests. Within the C2PA, WITNESS [co-chairs the Threats and Harms Task Force](https://blog.witness.org/2021/12/witness-and-the-c2pa-harms-and-misuse-assessment-process/), which produces systematic assessments of how the specification could be misused — how provenance infrastructure designed to verify authenticity could simultaneously be deployed to surveil dissidents, compel photojournalists to disclose their identities, or create platform-controlled trust hierarchies that crowd out civil society voices.

The Harms and Misuse Assessment Process, convened beginning in 2021, engaged participants across Latin America, Africa, Asia, the United States, and Europe in mapping how populations in different geopolitical contexts would be affected by different design choices in the specification. WITNESS's advocacy inside the C2PA has concentrated on three principles that reflect the dual-use character of provenance infrastructure: participation must remain voluntary and non-identity-based (mandatory provenance credentials tied to personal identity would make camera use dangerous for activists in authoritarian contexts); the ecosystem should support independent verification tools not controlled by founding industry members; and civil-society representation in governance must be meaningful rather than nominal, preventing the specification from becoming a corporate compliance surface that uses rights-adjacent vocabulary to defang accountability demands.

## "Prepare, Don't Panic" and the Deepfakes Rapid Response Force

[Since 2018](https://www.witness.org/portfolio_page/sam-gregory/), WITNESS has led the **Prepare, Don't Panic** initiative — a globally-inclusive, human-rights-led approach to deepfakes, synthetic media, and media manipulation. The initiative identified three structural problems in how frontline actors were equipped to respond: limited access to forensics expertise, unreliable detection tools, and insufficient guidance on interpreting ambiguous results from existing detection methods.

The initiative's primary operational output is the [Deepfakes Rapid Response Force](https://www.gen-ai.witness.org/deepfakes-rapid-response-force/), which WITNESS describes as the only global operation connecting journalists and fact-checkers with specialists in media forensics and AI synthesis. The force provides in-depth analysis of content suspected of being AI-generated or manipulated, with particular focus on content that could fuel violence or undermine democratic institutions in lower-resource contexts where dedicated detection capacity is weakest. Case investigations have included analysis of Indian political audio clips, Burkinabe military footage, and election-related synthetic media. The force also produced the TRIED Benchmark — a checklist for evaluating the effectiveness of AI detection tools designed for newsrooms operating without forensics staff.

WITNESS frames deepfake detection as a complement to, not a substitute for, provenance infrastructure: computational detection is technically outpaced by adversarial generation, and the durable solution is authenticity at the moment of capture rather than forensic reconstruction at the point of distribution. The ProofMode/C2PA track and the Rapid Response Force are explicitly positioned as complementary layers of the same defensive architecture — upstream prevention and downstream response.

## Policy advocacy and AI governance

Beyond its technical and training programs, WITNESS engages directly in AI policy at national and international levels. Sam Gregory has [testified before the US House and Senate](https://www.witness.org/portfolio_page/sam-gregory/) on AI and media transparency. In the European Union, WITNESS [submitted a formal position to the Article 50 consultation](https://www.witness.org/navigating-human-rights-in-the-eu-ai-act-witnesss-call-for-thoughtful-transparency/) on the EU AI Act's Code of Practice for AI transparency, arguing that disclosure requirements must be privacy-preserving by design, must account for hybrid human-AI production and context collapse, and must carry structural safeguards against weaponization by states against dissidents. The submission connected WITNESS's C2PA governance work to the policy track: meaningful AI transparency requires infrastructure whose design is shaped by civil society, not delegated to industry incumbents.

In 2024, WITNESS received the [inaugural Peabody Global Impact Award](https://www.witness.org/portfolio_page/sam-gregory/) for media and organizations that have profoundly changed the world. [MacArthur Foundation has provided over $3.9 million in cumulative grants since 2013](https://www.macfound.org/grantee/witness-39751/), most recently a $750,000 three-year general operating support grant in 2024 for continued training and platform accountability work.
