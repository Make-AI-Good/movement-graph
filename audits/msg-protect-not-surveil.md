---
entity_id: msg-protect-not-surveil
entity_hash: e47a5af6035f180423efbc556d65892c1d820ca0
audit_date: 2026-09-16
pass: 1
status: corrections-pending
claims_total: 25
claims_corroborated: 17
claims_primary_sourced: 0
claims_single_source: 0
claims_uncorroborated: 5
open_corrections: 3
sources_consulted:
  - https://protectnotsurveil.eu/
  - https://protectnotsurveil.eu/about
  - https://www.accessnow.org/press-release/protectnotsurveil-people-on-the-move/
  - https://edri.org/our-work/protect-not-surveil-eu-ai-act-fails-migrants-people-on-the-move/
  - https://privacyinternational.org/advocacy/5264/joint-statement-dangerous-precedent-how-eu-ai-act-fails-migrants-and-people-move
  - https://privacyinternational.org/advocacy/4995/joint-statement-eu-ai-act-must-protect-people-move
  - https://www.aljazeera.com/opinions/2023/4/20/ban-racist-and-lethal-ai-from-europes-borders
  - https://edri.org/our-work/protect-not-surveil-position-paper-stop-europols-expanding-digital-surveillance-against-migrants/
  - https://edri.org/our-work/european-parliament-backs-europol-expansion-a-dangerous-step-towards-mass-surveillance-in-the-eu/
  - https://algorithmwatch.org/en/automated-fortress-europe/
  - https://www.statewatch.org/news/2025/february/eu-digital-and-migrant-rights-groups-call-for-full-rejection-of-new-anti-smuggling-powers/
  - https://edri.org/our-work/reclaim-your-face-eci/
  - https://privacyinternational.org/examples/3141/eu-pilots-ai-lie-detectors-airports-hungary-latvia-and-greece
  - https://theintercept.com/2019/07/26/europe-border-control-ai-lie-detector/
  - https://www.libraryjournal.com/story/notechforice-campaign-protests-data-vendor-contracts-with-ice
  - https://www.euronews.com/next/2024/04/17/new-eu-migrant-pact-ushering-in-deadly-new-era-of-digital-surveillance-privacy-experts-war
  - https://notechforice.com/about/
---

## Claim 1: "The coalition formed in February 2023" / "The #ProtectNotSurveil coalition started in February 2023"

Source: https://edri.org/our-work/protect-not-surveil-eu-ai-act-fails-migrants-people-on-the-move/ and https://privacyinternational.org/advocacy/5264/joint-statement-dangerous-precedent-how-eu-ai-act-fails-migrants-and-people-move
Source tier: primary
Source content: "The #ProtectNotSurveil coalition started in February 2023 to advocate for the AI Act to protect people on the move and racialised people from harms emanating from the use of AI systems." (identical sentence on both EDRi and PI pages)
Comparison: Formation date February 2023 matches two coalition-member primary statements.
Decision: corroborated

## Claim 2: "publicly launched in April 2023" (origin; body lead "It launched in April 2023"; Origin § "publicly launched in April 2023"; "at the April 2023 launch" ×2; scalar sources[2].note "primary source for the campaign launch date (April 2023)")

Source: https://www.accessnow.org/press-release/protectnotsurveil-people-on-the-move/
Source tier: primary
Source content: "PUBLISHED: 9 February 2023" — "Launched today, 9 February, the new #ProtectNotSurveil coalition website led by Access Now, European Digital Rights (EDRi), Platform for International Cooperation on Undocumented Migrants (PICUM), and Refugee Law Lab..."
Comparison: The entity's own cited launch source dates the public launch 9 February 2023, not April 2023; EDRi/PI corroborate "started in February 2023." No source supports an April 2023 launch — the 20 April 2023 Al Jazeera op-ed post-dates the launch by two months. Single correct replacement: February 2023 (launch 9 February 2023). Fix locations: origin frontmatter, body lead sentence, Origin section, "The core argument" final paragraph ("at the April 2023 launch"), and scalar sources[2].note (the "(April 2023)" parenthetical). Origin's "formed in February 2023 and publicly launched in April 2023" two-date split collapses to February 2023.
Decision: correction

## Claim 3: Anchored/founded by Access Now, EDRi, PICUM, and the Refugee Law Lab (four anchor organisations)

Source: https://www.accessnow.org/press-release/protectnotsurveil-people-on-the-move/ and https://privacyinternational.org/advocacy/5264/joint-statement-dangerous-precedent-how-eu-ai-act-fails-migrants-and-people-move
Source tier: primary
Source content: "the new #ProtectNotSurveil coalition website led by Access Now, European Digital Rights (EDRi), Platform for International Cooperation on Undocumented Migrants (PICUM), and Refugee Law Lab"
Comparison: Launch-time press release names exactly these four as leading the coalition; all four also appear as March 2024 joint-statement signatories. Note: the live protectnotsurveil.eu/about page now names three leads (EDRi, Access Now, Equinox) — see Claim 24 for the source-note drift.
Decision: corroborated

## Claim 4: "more than 300 civil-society organisations" / "a 300+-organisation coalition"

Source: https://protectnotsurveil.eu/about
Source tier: primary
Source content: "The coalition also includes more than 300 supporters, who stay informed through our newsletter, support joint initiatives at the EU and national levels and participate in our events." The same page lists ~15 named member organisations plus 3 individual members, "led by" EDRi, Access Now, and Equinox. The launch press release: "Last month, nearly 200 organisations urged the EU to ensure the AI Act centres the rights of marginalised people" (the 6 Dec 2022 open letter, 192 signatories per PI advocacy/4995).
Comparison: No fetched source describes a coalition of 300+ *organisations*. The coalition self-describes as ~15 member organisations plus 300+ *supporters* (not stated to be organisations); the largest organisational signatory counts found are 192 (Dec 2022 letter) and 120+ (Nov 2025 Europol call). The claim conflates supporter count with organisational membership; the correct rewording requires prose judgment (member orgs vs. supporters), so no single-token replacement is asserted.
Decision: uncorroborated

## Claim 5: The four categorical demands (prohibit predictive analytics used to prevent migration; automated risk-assessment and profiling; "lie-detector"/emotion-inference systems; remote biometric identification at borders and detention facilities)

Source: https://www.accessnow.org/press-release/protectnotsurveil-people-on-the-move/ and https://privacyinternational.org/advocacy/4995/joint-statement-eu-ai-act-must-protect-people-move
Source tier: primary
Source content: Press release lists prohibition of "Predictive analytics systems used for preventing migration," automated risk assessments and profiling systems, emotion-inference technology ("lie-detectors"), and "Remote biometric identification at borders and detention facilities." Dec 2022 joint statement demands match: "predictive analytics for migration interdiction, automated risk assessments, emotion recognition systems, and remote biometric identification at borders."
Comparison: The entity's four demand categories match the coalition's own demand structure in two primary documents.
Decision: corroborated

## Claim 6: The right-to-move framing ("people exercising their right to move, seek safety, and pursue opportunity are entitled to do so without profiling, algorithmic risk-scoring, and discrimination")

Source: https://protectnotsurveil.eu/about
Source tier: primary
Source content: The coalition advocates "for the ability of people to move and to seek safety and opportunity without risking harm, surveillance or discrimination."
Comparison: Entity paraphrases the coalition's own mission language accurately (move / seek safety / opportunity / without surveillance and discrimination); also echoed on the homepage ("a world where people move freely").
Decision: corroborated

## Claim 7: propagated_by_orgs edges — org-edri, org-access-now, org-algorithmwatch, org-privacy-international all carry the framing

Source: https://privacyinternational.org/advocacy/5264/joint-statement-dangerous-precedent-how-eu-ai-act-fails-migrants-and-people-move and https://protectnotsurveil.eu/about
Source tier: primary
Source content: March 2024 joint-statement signatories include "Access Now, European Digital Rights (EDRi), ... AlgorithmWatch, ... Privacy International"; the live member list includes "Algorithm Watch" and "Privacy International"; EDRi and Access Now are named coalition leads.
Comparison: All four edge targets are documented coalition members/leads who signed coalition statements under the framing. Edges point at the correct in-corpus entities (files exist for all four).
Decision: corroborated

## Claim 8: The four propagated_by orgs are "all founding coalition members" (origin, final sentence)

Source: https://www.accessnow.org/press-release/protectnotsurveil-people-on-the-move/
Source tier: primary
Source content: Launch press release names the coalition as "led by Access Now, European Digital Rights (EDRi), ... PICUM, and Refugee Law Lab" — no February 2023 full membership roster is given, and no fetched source states when AlgorithmWatch or Privacy International joined.
Comparison: "Founding" is confirmed for EDRi and Access Now (launch leads). For AlgorithmWatch and Privacy International, earliest confirmed membership is the 13 March 2024 joint statement; no source establishes or contradicts founding (Feb 2023) membership. Wayback unavailable (fetch-blocked in this environment).
Decision: uncorroborated

## Claim 9: Al Jazeera opinion "Ban racist and lethal AI from Europe's borders," 20 April 2023, authored from within the coalition; framing border AI as "racist and lethal"

Source: https://www.aljazeera.com/opinions/2023/4/20/ban-racist-and-lethal-ai-from-europes-borders
Source tier: mainstream
Source content: "Published: 20 Apr 2023." Headline: "Ban racist and lethal AI from Europe's borders." Authors include "Lucie Audibert, Lawyer at Privacy International; ... Petra Molnar, Associate Director, Refugee Law Lab; ... Caterina Rodelli, EU Policy Analyst, Access Now; Alyna Smith, Platform for International Cooperation on Undocumented Migrants." "We call on them to ensure AI technologies are used to #ProtectNotSurveil."
Comparison: Date, "racist and lethal" characterisation, and coalition authorship all match.
Decision: corroborated

## Claim 10: Quote attributed to the April 2023 launch/op-ed: the systems "will never be fixed either via technical means nor with some procedural safeguards"

Source: https://www.aljazeera.com/opinions/2023/4/20/ban-racist-and-lethal-ai-from-europes-borders and https://privacyinternational.org/advocacy/4995/joint-statement-eu-ai-act-must-protect-people-move
Source tier: primary
Source content: The Al Jazeera op-ed does not contain this language (checked; no "never be fixed" sentence present). The 6 December 2022 joint statement (192 organisations) reads: "Some AI systems pose an 'unacceptable risk' to our fundamental rights, which will never be fixed by technical means or procedural safeguards."
Comparison: The quotation is real but misattributed and misquoted: it comes from the coalition's pre-launch 6 Dec 2022 joint statement, not the April 2023 op-ed, and the verbatim wording is "will never be fixed by technical means or procedural safeguards" (not "either via technical means nor with some procedural safeguards"). Fix: re-source the quote to the Dec 2022 joint statement and restore verbatim wording, in "The core argument" final paragraph. Substantive point (abolitionist stance — prohibition not regulation) is genuine.
Decision: correction

## Claim 11: "The EU AI Act's March 2024 plenary adoption"

Source: https://privacyinternational.org/advocacy/5264/joint-statement-dangerous-precedent-how-eu-ai-act-fails-migrants-and-people-move
Source tier: primary
Source content: "The final text of the EU AI Act adopted by the European Parliament on 13 March 2024 fails to prevent tech-enabled harm to migrants."
Comparison: Plenary adoption 13 March 2024 matches; the joint statement and EDRi article are both dated 13 March 2024.
Decision: corroborated

## Claim 12: Joint post-adoption statement "a dangerous precedent," signed by Privacy International, EDRi, Access Now, and coalition partners

Source: https://privacyinternational.org/advocacy/5264/joint-statement-dangerous-precedent-how-eu-ai-act-fails-migrants-and-people-move
Source tier: primary
Source content: Title: "Joint statement – A dangerous precedent: how the EU AI Act fails migrants and people on the move." Signatories listed verbatim include Access Now, European Digital Rights (EDRi), Privacy International, PICUM, Refugee Law Lab, AlgorithmWatch, Amnesty International, Statewatch, and others (15 organisations + 3 individuals).
Comparison: Title, characterisation, and the three named signatories all match.
Decision: corroborated

## Claim 13: The Act "included partial restrictions on remote biometric identification and partial bans on emotion recognition in workplaces and educational settings" but not the demanded migration-context prohibitions; migration carve-outs (wider latitude for law-enforcement/border authorities) the central failure

Source: https://privacyinternational.org/advocacy/5264/joint-statement-dangerous-precedent-how-eu-ai-act-fails-migrants-and-people-move and https://edri.org/our-work/protect-not-surveil-eu-ai-act-fails-migrants-people-on-the-move/
Source tier: primary
Source content: "Prohibitions on AI systems do not extend to the migration context"; "Emotion recognition bans exclude migration settings"; "Predictive analytics for migration interdiction remain unregulated"; "AI in large-scale databases like Eurodac exempt until 2030"; "it creates a dangerous precedent by creating a parallel legal framework for the use of AI by law enforcement, migration and national security authorities."
Comparison: The partial-bans-elsewhere / no-migration-prohibitions structure and the carve-out framing match the coalition's own verdict documents. (Workplace/education scope of the emotion-recognition ban is the AI Act's public statutory content, consistent with "bans exclude migration settings.")
Decision: corroborated

## Claim 14: April 2024 Migration and Asylum Pact — coalition warned it was "ushering in a deadly new era of digital surveillance"; Pact mandates expanded digital data collection and database interoperability

Source: https://www.euronews.com/next/2024/04/17/new-eu-migrant-pact-ushering-in-deadly-new-era-of-digital-surveillance-privacy-experts-war and coalition statement mirrors (accessnow.org, picum.org, statewatch.org, privacyinternational.org advocacy/5296)
Source tier: primary
Source content: Coalition statement (April 2024, following the Parliament's 10 April 2024 adoption): the Pact "ushers in a deadly new era of digital surveillance, expanding the digital infrastructure for an EU border regime based on the criminalisation and punishment of migrants and racialised people"; the framework "will enable and in some cases mandate the deployment of harmful surveillance technologies and practices against migrants." Euronews headline (17 Apr 2024): "New EU migrant pact ushering in 'deadly new era of digital surveillance,' privacy experts warn."
Comparison: Quote, timing (April 2024), and the expanded-data-collection/mandate characterisation all match the coalition's joint statement and mainstream coverage.
Decision: corroborated

## Claim 15: February 2025 #ProtectNotSurveil position paper opposing the proposed Europol Regulation's expanded biometric/predictive-analytics surveillance powers

Source: https://edri.org/our-work/protect-not-surveil-position-paper-stop-europols-expanding-digital-surveillance-against-migrants/ and https://www.statewatch.org/news/2025/february/eu-digital-and-migrant-rights-groups-call-for-full-rejection-of-new-anti-smuggling-powers/
Source tier: primary
Source content: EDRi page dated "February 20, 2025": "EDRi and the Protect Not Surveil coalition published position paper." Statewatch (20 February 2025): position paper titled "Stopping the unfettered expansion of Europol's digital surveillance powers against migrants"; the coalition demands "the full rejection of this reform" (Europol Regulation and Facilitation Directive). EDRi Nov 2025 describes the contested powers: authority to "collect, process and share data, including biometrics such as facial recognition."
Comparison: Existence, February 2025 date, and subject (Europol digital-surveillance expansion against migrants) match. Nuance for the Editor: the paper's headline demand per Statewatch is *full rejection* of the reform, slightly stronger than the entity's "demands to remove provisions" framing in sources[4].note — not contradictory (removal demands may appear inside the paper, which was not directly readable), so no correction asserted.
Decision: corroborated

## Claim 16: The February 2025 position paper was "signed by 120+ organisations"

Source: https://www.statewatch.org/news/2025/february/eu-digital-and-migrant-rights-groups-call-for-full-rejection-of-new-anti-smuggling-powers/ and https://edri.org/our-work/european-parliament-backs-europol-expansion-a-dangerous-step-towards-mass-surveillance-in-the-eu/
Source tier: primary
Source content: Neither the EDRi Feb 2025 page nor Statewatch gives a signatory count for the position paper; Statewatch attributes it to the coalition ("Statewatch is a member of #ProtectNotSurveil and supported the drafting of the paper"). The 120+ figure appears in the November 2025 context: "More than 120 organisations from across Europe called on MEPs to reject the proposal."
Comparison: The 120+ figure is documented for the November 2025 MEP call, not as the February position paper's signatory count; a separate February 2025 statement had 168 signatories per Statewatch-indexed reporting. The paper's actual signatory count is unestablished, so no single replacement token can be asserted — the body attaches a November figure to the February document.
Decision: uncorroborated

## Claim 17: November 2025 LIBE Committee vote to advance the Europol Regulation; EDRi characterisation "a dangerous step towards mass surveillance in the EU"; continuing mobilisation ahead of the full plenary vote

Source: https://edri.org/our-work/european-parliament-backs-europol-expansion-a-dangerous-step-towards-mass-surveillance-in-the-eu/
Source tier: primary
Source content: Article dated November 5, 2025: LIBE "voted on this date. The vote passed 59-10 with 4 abstentions"; headline "A dangerous step towards mass surveillance in the EU" (published on edri.org, authored by the Protect Not Surveil coalition as guest); "The proposal moves to plenary for a final vote later in November," where MEPs have "one last chance" to reverse course.
Comparison: Committee, month, characterisation quote, and pre-plenary mobilisation all match. The sources[7].note pairing of the 120+ opposition figure with this November vote is also correct per the same page. Minor attribution nuance: the headline is the coalition's guest post on EDRi's site; the entity's "EDRi characterised" is defensible (EDRi's publication, EDRi-hosted headline) — no correction.
Decision: corroborated

## Claim 18: The broader EDRi-led AI Act civil-society coalition "had operated since the Commission's April 2021 proposal"; #ProtectNotSurveil narrowed the framing to migration/border contexts (edge: camp-edri-eu-ai-act-fundamental-rights-coalition-2021-2024)

Source: https://privacyinternational.org/advocacy/5264/joint-statement-dangerous-precedent-how-eu-ai-act-fails-migrants-and-people-move
Source tier: primary
Source content: "The #ProtectNotSurveil coalition started in February 2023 to advocate for the AI Act to protect people on the move and racialised people from harms emanating from the use of AI systems." (The Commission's AI Act proposal of 21 April 2021 is public legislative record; the entity's edge target camp-edri-eu-ai-act-fundamental-rights-coalition-2021-2024 exists in-corpus and carries the 2021 start.)
Comparison: The migration-specific narrowing is the coalition's own stated purpose; the April 2021 proposal date is public record; the edge points at the correct campaign entity.
Decision: corroborated

## Claim 19: Reclaim Your Face — EDRi campaign infrastructure, "had run since 2020," overlapping demands with #ProtectNotSurveil (edge: msg-ban-biometric-mass-surveillance)

Source: https://edri.org/our-work/reclaim-your-face-eci/
Source tier: primary
Source content: EDRi article of 13 January 2021: "Since its launch just 2 months ago, the Reclaim Your Face campaign to ban biometric mass surveillance has gone from strength to strength" (placing launch ~November 2020). ECI demand: "we ask the Commission to prohibit, in law and in practice, indiscriminate or arbitrarily-targeted uses of biometrics which can lead to unlawful mass surveillance."
Comparison: RYF running since 2020 and the overlapping remote-biometric-identification prohibition demand both confirmed; edge points at the correct in-corpus message entity.
Decision: corroborated

## Claim 20: RYF and #ProtectNotSurveil shared "several founding organisational members"

Source: https://protectnotsurveil.eu/about and https://edri.org/our-work/reclaim-your-face-eci/
Source tier: primary
Source content: No fetched source enumerates RYF's founding organisational roster against #ProtectNotSurveil's February 2023 founding membership.
Comparison: Plausible (EDRi led both; Homo Digitalis, Hermes Center et al. were active in both spaces) but no roster-to-roster comparison was possible from fetched sources, and #ProtectNotSurveil's founding membership beyond its four leads is itself unestablished (Claim 8).
Decision: uncorroborated

## Claim 21: "Pseudo-scientific 'lie-detector'" systems "which several EU member states piloted at border crossing points"

Source: https://privacyinternational.org/examples/3141/eu-pilots-ai-lie-detectors-airports-hungary-latvia-and-greece and https://theintercept.com/2019/07/26/europe-border-control-ai-lie-detector/
Source tier: mainstream
Source content: "EU pilots AI lie detectors at airports in Hungary, Latvia, and Greece" (PI); the iBorderCtrl project "was piloted between 2016 and 2019 in Greece, Hungary and Latvia"; The Intercept tested the system at the Serbian-Hungarian border and "immediately triggered a false positive."
Comparison: Multiple member states (Hungary, Latvia, Greece) did pilot AI "lie-detector" systems at border crossings (iBorderCtrl); the claim matches.
Decision: corroborated

## Claim 22: PICUM = "Platform for International Cooperation on Undocumented Migrants"; Refugee Law Lab brought refugee-law legal expertise

Source: https://www.accessnow.org/press-release/protectnotsurveil-people-on-the-move/ and https://www.aljazeera.com/opinions/2023/4/20/ban-racist-and-lethal-ai-from-europes-borders
Source tier: primary
Source content: "Platform for International Cooperation on Undocumented Migrants (PICUM)" (press release); "Petra Molnar, Associate Director, Refugee Law Lab, York University; Fellow, Harvard Law School" (op-ed byline).
Comparison: PICUM's full name matches; the Refugee Law Lab is a York University refugee-law research lab, consistent with the legal-expertise characterisation.
Decision: corroborated

## Claim 23: related_messages edge — msg-no-tech-for-ice, "the 2018 Mijente-launched US framing against tech-company contracts with ICE"

Source: https://www.libraryjournal.com/story/notechforice-campaign-protests-data-vendor-contracts-with-ice and https://notechforice.com/about/
Source tier: mainstream
Source content: "The #NoTechForICE campaign was launched in 2018 and spearheaded by the grassroots organization Mijente, highlighting the connections between the tech industry and the surveillance of immigrants."
Comparison: Launch year (2018), launching org (Mijente), and target (tech-company/data-vendor contracts with ICE) all match; edge points at the correct in-corpus message entity.
Decision: corroborated

## Claim 24: scalar sources[6].note — AlgorithmWatch "The Automated Fortress Europe" documents "Frontex's EUROSUR situation-awareness platform, member-state predictive-analytics pilots for migration-flow forecasting, and biometric registration systems at EU external borders"

Source: https://algorithmwatch.org/en/automated-fortress-europe/
Source tier: primary
Source content: Two full-text checks: "EUROSUR: Not found in the provided document." The report ("The Automated Fortress Europe: No Place for Human Rights," May 24, 2024) does discuss Frontex ("A driving force in border security is also one of the main customers: Frontex"; Horizon 2020 project involvement; "EFFECTOR project's 'objectives and outcomes' were 'translated to Frontex systems'"), the ITFLOWS project's EuMigraTool ("monthly predictions of asylum applications in the EU"), and biometrics (EURODAC expansion; D4FLY "2D+thermal facial, 3D facial, iris and somatotype biometrics").
Comparison: Scalar path: sources[6].note (the algorithmwatch.org entry). The EUROSUR attribution is confabulated — the report does not mention EUROSUR; its actual content is Frontex's role in EU research-and-innovation projects, EU-funded predictive-analytics research (ITFLOWS, an EU Horizon project rather than "member-state pilots"), and biometric systems (EURODAC, D4FLY). The biometric-registration clause is supported; the EUROSUR clause contradicts the source and the predictive-analytics clause misdescribes provenance. Fix requires reworded note prose (not a single-token swap) — Editor should route via [editor-flag] to the Researcher.
Decision: correction

## Claim 25: scalar sources[0].note — protectnotsurveil.eu as "primary source for ... the four anchor organisations (Access Now, EDRi, PICUM, Refugee Law Lab)"

Source: https://protectnotsurveil.eu/ and https://protectnotsurveil.eu/about
Source tier: primary
Source content: The live site's About page states "The Coalition is led by" EDRi, Access Now, and Equinox; PICUM and Refugee Law Lab appear only as ordinary members; the homepage carries no founding-anchor history.
Comparison: Scalar path: sources[0].note. Source drift: the site no longer carries the four-anchor attribution the note claims of it (leads are now EDRi/Access Now/Equinox). The four-anchor fact itself is corroborated at launch time via the Access Now press release (Claim 3), so the entity body is right but this note's description of what the cited page shows is stale. Re-pointing the anchor claim's sourcing to the press release is a prose-judgment fix; noted for the Editor, no body error asserted.
Decision: uncorroborated

## Note on claims not audited

Interpretive prose carrying no hard specific or edge — the "Why it has carried" section's three features, the framing-inversion analysis in origin, the "to the left of much digital-rights advocacy" positioning, and the structural-parallel commentary linking to msg-no-tech-for-ice beyond its factual tokens — is out of remit for a connective-type entity per AUDITOR.md § Type-shape and received no decisions.
