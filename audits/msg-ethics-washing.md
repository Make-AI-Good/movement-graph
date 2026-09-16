---
entity_id: msg-ethics-washing
entity_hash: 8d4650989be0e71696f0bab4db48bdf308451e40
audit_date: 2026-09-15
pass: 1
status: corrections-pending
claims_total: 27
claims_corroborated: 9
claims_primary_sourced: 10
claims_single_source: 2
claims_uncorroborated: 3
open_corrections: 3
sources_consulted:
  - https://www.business-humanrights.org/en/latest-news/expert-commentary-ethics-washing-made-in-europe/
  - https://algorithmwatch.org/en/industry-defuses-ethics-guidelines-for-artificial-intelligence/
  - https://theintercept.com/2019/12/20/mit-ethical-ai-artificial-intelligence/
  - https://www.commondreams.org/news/2019/04/05/worker-power-wins-google-scraps-controversial-ai-ethics-board-after-widespread
  - https://spectrum.ieee.org/timnit-gebru-dair-ai-ethics
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC9373109/
  - https://algorithmwatch.org/en/civil-society-statement-ai-act-protects-people-rights/
  - https://blog.google/innovation-and-ai/products/external-advisory-council-help-advance-responsible-development-ai/
  - https://www.dair-institute.org/press-release/
  - https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
  - https://www.technologyreview.com/2019/04/06/65905/google-cancels-ateac-ai-ethics-council-what-next/
  - https://www.statewatch.org/news/2023/july/eu-civil-society-calls-for-rights-to-be-prioritised-in-secret-ai-act-trilogue-negotiations/
  - https://www.degruyterbrill.com/document/doi/10.1515/9789048550180-016/html?lang=en
  - https://dc.tsinghuajournals.com/journal-of-social-computing/vol2/iss3/2/
  - https://www.cnbc.com/2019/04/04/google-cancels-controversial-ai-ethics-panel.html
---

## Claim 1: edge propagated_by_orgs → org-algorithmwatch

Source: https://algorithmwatch.org/en/civil-society-statement-ai-act-protects-people-rights/
Source tier: primary
Source content: "Drafted by: European Digital Rights, Algorithm Watch, Access Now, Amnesty International, ..."
Comparison: Edge resolves (product/entities/organizations/org-algorithmwatch.md exists). AlgorithmWatch drafted/published the civil-society statements deploying the critique and republished the founding Netzpolitik investigation on its own site — propagation supported by the org's own published statements.
Decision: primary-sourced

## Claim 2: edge propagated_by_orgs → org-edri

Source: https://algorithmwatch.org/en/civil-society-statement-ai-act-protects-people-rights/
Source tier: primary
Source content: "Drafted by: European Digital Rights, Algorithm Watch, Access Now, ..."
Comparison: Edge resolves (org-edri.md exists). EDRi named first drafter of the coalition statement demanding binding protections over voluntary mechanisms — the critique in regulatory practice.
Decision: primary-sourced

## Claim 3: edge propagated_by_orgs → org-access-now

Source: https://algorithmwatch.org/en/civil-society-statement-ai-act-protects-people-rights/
Source tier: primary
Source content: "Drafted by: European Digital Rights, Algorithm Watch, Access Now, ..."
Comparison: Edge resolves (org-access-now.md exists). Access Now named drafter of the same statement.
Decision: primary-sourced

## Claim 4: edge propagated_by_orgs → org-dair-institute

Source: https://www.dair-institute.org/press-release/
Source tier: primary
Source content: "an independent, community-rooted institute set to counter Big Tech's pervasive influence on the research, development and deployment of AI"
Comparison: Edge resolves (org-dair-institute.md exists). DAIR's own founding press release (2 Dec 2021) positions the institute as the institutional counter to corporate AI-ethics capture — the critique operationalised, as the body claims.
Decision: primary-sourced

## Claim 5: origin scalar — "The term entered the AI-governance register in April 2019 through two concurrent events"

Source: https://www.degruyterbrill.com/document/doi/10.1515/9789048550180-016/html?lang=en
Source tier: primary
Source content: Ben Wagner, "Ethics As An Escape From Regulation. From 'Ethics-Washing' To Ethics-Shopping?", in *Being Profiled: Cogitas Ergo Sum* (Amsterdam University Press, 2018) — per publisher record, Wagner "discusses the concepts of 'ethics shopping' and 'ethics washing'" in tech-governance context.
Comparison: Scalar path `origin`. Wagner's 2018 chapter deploys "ethics-washing" in the AI/data-governance register before April 2019, conflicting with the entry-date framing; whether "entered the register" means first use or popularisation is a contested-firstness judgment the sources do not settle. Per source rule, contested "who was first" claims cannot pass on the entity's own sources.
Decision: uncorroborated

## Claim 6: Metzinger, philosopher and member of the EU Commission's 52-member High-Level Expert Group, published op-ed in Der Tagesspiegel April 2019 calling the guidelines "ethics washing made in Europe"

Source: https://www.business-humanrights.org/en/latest-news/expert-commentary-ethics-washing-made-in-europe/
Source tier: primary
Source content: Title: "Expert commentary: 'Ethics washing' made in Europe", byline "Thomas Metzinger, Tagesspiegel", dated 9 Apr 2019; Metzinger "served on the '52-member High-Level Expert Group on Artificial Intelligence (HLEG AI)'". Corroborated by the AlgorithmWatch investigation (52 experts; Metzinger quoted).
Comparison: All tokens match: April 2019, Der Tagesspiegel, 52 members, his membership, the "ethics washing made in Europe" formulation. Two independent canonical sources.
Decision: corroborated

## Claim 7: "Ethics Guidelines for Trustworthy AI" published April 2019, drafted by the HLEG

Source: https://www.business-humanrights.org/en/latest-news/expert-commentary-ethics-washing-made-in-europe/
Source tier: primary
Source content: Op-ed dated 9 Apr 2019 on the just-released guidelines; HLEG "spent 'nine months'" developing them. AlgorithmWatch investigation covers the same publication.
Comparison: Publication timing and drafting body match across both sources.
Decision: corroborated

## Claim 8: industry representatives held roughly half the HLEG's 52 seats

Source: https://algorithmwatch.org/en/industry-defuses-ethics-guidelines-for-artificial-intelligence/
Source tier: mainstream
Source content: "52 experts total; 23 from companies (Nokia, Google, Airbus, IBM); 26 from industry when including lobbying associations—representing half the group."
Comparison: Body's "roughly half the seats" matches the investigation's 26-of-52 count. The Netzpolitik original and the AlgorithmWatch republication are one source; the composition figures were not found in a second independent canonical source this pass.
Decision: single-source

## Claim 9: the investigation documented deletion of red lines on autonomous weapons, citizen scoring, and mass facial-recognition surveillance

Source: https://algorithmwatch.org/en/industry-defuses-ethics-guidelines-for-artificial-intelligence/
Source tier: mainstream
Source content: "Draft prohibitions eliminated from final guidelines included: research on autonomous weapon systems, citizen scoring systems like China's, automated facial recognition for individual identification, and AI operating 'in disguise.'"
Comparison: Claim is about what this investigation documented; the investigation is the primary record of its own content. The entity's three named red lines all appear (it omits the fourth, "AI in disguise" — omission, not error).
Decision: primary-sourced

## Claim 10: Metzinger "had watched industry-affiliated members successfully remove non-negotiable red-line language from successive drafts"

Source: https://algorithmwatch.org/en/industry-defuses-ethics-guidelines-for-artificial-intelligence/
Source tier: mainstream
Source content: "The final document removed language about 'non-negotiable' principles and 'red lines,' replacing these with softer terms like 'concerns' and 'tensions'"
Comparison: Substance matches the investigation (industry defused; "non-negotiable" removed). Note: the body sentence hyperlinks the BHRRC republication for this, but that page is an excerpt carrying no red-lines-removal content (see Claim 12) — the support comes from the investigation, a single source for this specific.
Decision: single-source

## Claim 11: Metzinger characterisation in the investigation — companies "engage in an ethical debate with the goal of postponing or completely preventing legal regulations"

Source: https://algorithmwatch.org/en/industry-defuses-ethics-guidelines-for-artificial-intelligence/
Source tier: mainstream
Source content: "Metzinger characterized this practice as companies engaging 'in an ethical debate with the goal of postponing or completely preventing legal regulations.'"
Comparison: Verbatim match; entity correctly locates the quote in the investigation ("his characterisation in that investigation").
Decision: primary-sourced

## Claim 12: scalar:sources[0].note — BHRRC republication as source for "his argument that industry-dominated committee composition converted ethical deliberation into a vehicle for preventing legally enforceable regulation"

Source: https://www.business-humanrights.org/en/latest-news/expert-commentary-ethics-washing-made-in-europe/
Source tier: primary
Source content: Three keyword probes: "'industry': No sentences containing this word were found... 'prevent': No sentences containing this word were found... 'regulation': [none]". The page's closest passage: "using ethics debates as elegant public decorations for a large-scale investment strategy."
Comparison: Scalar path `sources[0].note`, final clause. The BHRRC page is an excerpt republication and carries no industry-composition or prevent-legal-regulation argument; that argument lives in sources[1] (the AlgorithmWatch/Netzpolitik investigation — composition figures, Claim 8; postponing-regulations quote, Claim 11). Fix: strike the final clause of sources[0].note or repoint it to sources[1]. The note's other two elements pass (Claims 6, and "lukewarm, short-sighted and deliberately vague" verbatim on the page).
Decision: correction

## Claim 13: Ochigame, "The Invention of 'Ethical AI': How Big Tech Manipulates Academia to Avoid Regulation", The Intercept, 20 December 2019 — thesis and FAccT/university-centre funding documentation

Source: https://theintercept.com/2019/12/20/mit-ethical-ai-artificial-intelligence/
Source tier: mainstream
Source content: "The Invention of 'Ethical AI': How Big Tech Manipulates Academia to Avoid Regulation" by Rodrigo Ochigame, December 20, 2019; "the discourse of 'ethical AI'...was aligned strategically with a Silicon Valley effort seeking to avoid legally enforceable restrictions of controversial technologies"; Ito sponsored "the creation of a prominent conference on 'Fairness, Accountability, and Transparency'...other sponsors of the conference included Google, Facebook, and Microsoft."
Comparison: Title, author, date, thesis, and FAccT/university-centre funding claims all match the article itself (primary for its own content and thesis).
Decision: primary-sourced

## Claim 14: "The same month as Metzinger's op-ed, April 2019 ... Google announced its Advanced Technology External Advisory Council (ATEAC)"

Source: https://blog.google/innovation-and-ai/products/external-advisory-council-help-advance-responsible-development-ai/
Source tier: primary
Source content: Kent Walker announcement post dated "March 26, 2019"; editor's note "dated April 4, 2019: 'It's become clear that in the current environment, ATEAC can't function as we wanted. So we're ending the council...'"
Comparison: Google's own announcement is dated 26 March 2019 — the announcement did not fall in April; only the dissolution (4 April 2019) did. Single replacement: the announcement was late March 2019 (the body's "same month" framing attaches to the dissolution, not the announcement).
Decision: correction

## Claim 15: ATEAC dissolved less than two weeks after formation

Source: https://blog.google/innovation-and-ai/products/external-advisory-council-help-advance-responsible-development-ai/
Source tier: primary
Source content: Post dated March 26, 2019; editor's note April 4, 2019 ending the council. Common Dreams: "about a week after Google announced the formation."
Comparison: 26 March → 4 April is 9 days — "less than two weeks" holds across Google's own record and news coverage.
Decision: corroborated

## Claim 16: protest by over 2,300 Google employees and more than 300 civil-society signatories

Source: https://www.commondreams.org/news/2019/04/05/worker-power-wins-google-scraps-controversial-ai-ethics-board-after-widespread
Source tier: mainstream
Source content: "Nearly 2,500 Google employees signed the worker-led petition, along with 'more than 300 outside experts and advocates.'" CNBC/MIT Technology Review coverage: "More than 2,300 Google employees signed a petition."
Comparison: "Over 2,300" is a floor consistent with both the 2,300+ contemporaneous count and the cited source's "nearly 2,500" (petition grew over days); 300+ outside signatories matches.
Decision: corroborated

## Claim 17: board structure — unpaid advisory function with no enforcement authority and four scheduled meetings per year

Source: https://blog.google/innovation-and-ai/products/external-advisory-council-help-advance-responsible-development-ai/
Source tier: primary
Source content: The council would "serve over the course of 2019, holding four meetings starting in April," providing "diverse perspectives to inform our work." MIT Technology Review: "an unpaid, toothless position that cannot possibly, in four meetings over the course of a year, arrive at a clear understanding of everything Google is doing."
Comparison: Four meetings (Google primary), unpaid and advisory-without-enforcement (MIT Tech Review) — all three structural specifics confirmed across two canonical sources.
Decision: corroborated

## Claim 18: December 2020 firing of Timnit Gebru from Google's Ethical AI team

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: "Timnit Gebru, the co-lead of Google's ethical AI team" (Karen Hao, December 4, 2020); IEEE Spectrum: "Google apparently exiled Gebru from its AI ethics team...in response to a paper about the dangers of the large language models."
Comparison: Date (December 2020), team, and firing confirmed by two canonical sources.
Decision: corroborated

## Claim 19: "after Google retracted a paper she co-authored on the risks of large language models"

Source: https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/
Source tier: mainstream
Source content: Wall Street Journal (via search record): the researcher "says she was fired by Google after she refused to retract a research paper"; MIT Technology Review: Jeff Dean "told colleagues in an internal email...that the paper 'didn't meet our bar for publication'"; the paper ("On the Dangers of Stochastic Parrots") was subsequently published.
Comparison: Google did not retract the paper — it demanded retraction (or name removal), Gebru refused, and she was fired; the paper was published at FAccT 2021. Single replacement: "after Google demanded she retract a paper she co-authored on the risks of large language models." Paper-subject token is correct.
Decision: correction

## Claim 20: Gebru founded the Distributed AI Research Institute (DAIR) in December 2021

Source: https://www.dair-institute.org/press-release/
Source tier: primary
Source content: "Press Release: Announcing DAIR" (December 2, 2021); "Distributed Artificial Intelligence Research institute (DAIR)"; founded by Timnit Gebru. IEEE Spectrum: Gebru founded DAIR in December 2021.
Comparison: Founding date, founder, and institute name confirmed by the institute's own press release plus IEEE Spectrum.
Decision: corroborated

## Claim 21: DAIR founded "explicitly outside corporate and government funding structures" (body; same claim in scalar:sources[4].note as "outside tech-company and government funding structures")

Source: https://www.dair-institute.org/press-release/
Source tier: primary
Source content: "an independent, community-rooted institute set to counter Big Tech's pervasive influence"; initial funders "the Ford Foundation, the John D. and Catherine T. MacArthur Foundation, the Kapor Center, and the Open Society Foundation." IEEE Spectrum keyword probe: no instance of "funding" or "funded" in the article; no independence-from-government statement.
Comparison: The Big-Tech/corporate-independence half is well supported (DAIR's own framing; foundation funders). The "and government funding structures" element appears in neither the cited IEEE piece nor DAIR's press release — partial confirmation, so the compound claim cannot pass as stated. Scalar path for the note instance: sources[4].note.
Decision: uncorroborated

## Claim 22: scalar:sources[4].note — IEEE Spectrum as source for "her critique that 'AI ethics' at major labs functioned as institutional cover rather than substantive accountability"

Source: https://spectrum.ieee.org/timnit-gebru-dair-ai-ethics
Source tier: mainstream
Source content: Keyword probe for "cover"/"accountability"/"ethics team" surfaced only: "Google apparently exiled Gebru from its AI ethics team..." and Gebru's "I'm wary of being a third-party auditor that people can point to as a green light: 'Well, they said it's okay.'"
Comparison: Scalar path `sources[4].note`. The cited article does not carry the "institutional cover rather than substantive accountability" critique as attributed; the nearest passage (the green-light quote) is thematically adjacent but not the stated claim. Too paraphrastic to pass; no contradiction of a specific token, so not a correction.
Decision: uncorroborated

## Claim 23: AlgorithmWatch, EDRi, and Access Now coordinated civil-society statement waves 2021–2023, ultimately signed by more than 150 organisations, demanding binding rights protections

Source: https://www.statewatch.org/news/2023/july/eu-civil-society-calls-for-rights-to-be-prioritised-in-secret-ai-act-trilogue-negotiations/
Source tier: mainstream
Source content: "A statement signed by more than 150 civil society organisations, including Statewatch, called for fundamental rights to be put at the centre of the talks" (July 2023). AlgorithmWatch April 2023 statement: drafted by EDRi, AlgorithmWatch, Access Now et al., demanding bans on unacceptable-risk systems and enforceable rights "rather than voluntary mechanisms."
Comparison: Coordinators, the 150+ signatory count (July 2023 trilogue statement), the 2021–2023 wave pattern, and the binding-over-voluntary demand all confirmed across two canonical sources.
Decision: corroborated

## Claim 24: Ben Green's 2021 "The Contestation of Tech Ethics" (Journal of Social Computing) identified ethics washing as "embracing the language of ethics to defuse criticism and resist government regulation, without committing to ethical behavior"

Source: https://dc.tsinghuajournals.com/journal-of-social-computing/vol2/iss3/2/
Source tier: primary
Source content: Journal of Social Computing, Vol. 2, Iss. 3 (2021): tech ethics "enables corporate 'ethics-washing': embracing the language of ethics to defuse criticism and resist government regulation, without committing to ethical behavior."
Comparison: Journal, year, and the characterisation match near-verbatim (peer-reviewed paper's own text; full title continues "...A Sociotechnical Approach to Technology Ethics in Practice" — entity's short title is standard shorthand).
Decision: primary-sourced

## Claim 25: van Maanen, "AI Ethics, Ethics Washing, and the Need to Politicize Data Ethics", Digital Society vol. 1 no. 2 (August 2022) — ethics-shopping argument, Buolamwini and Data Feminism frameworks (body + scalar:sources[5].note)

Source: https://pmc.ncbi.nlm.nih.gov/articles/PMC9373109/
Source tier: primary
Source content: Gijs van Maanen, *Digital Society*, Vol. 1, Issue 2 (August 2, 2022): "Ethics allows one to strategically 'shop' for the principles that limit one's action as little as possible"; notes D'Ignazio and Klein's *Data Feminism* includes "Joy Buolamwini's analysis of the racist features of face-analysis software."
Comparison: Citation tokens (author, title, journal, volume/issue, date), the ethics-shopping argument, and the Buolamwini/Data Feminism grounding all match the paper's own text.
Decision: primary-sourced

## Claim 26: scalar:sources[1].note — investigation authored by Chris Klöver and Alexander Fanta, translated by Kristina Penner, first published by Netzpolitik.org, titled "No red lines: Industry defuses ethics guidelines for artificial intelligence"

Source: https://algorithmwatch.org/en/industry-defuses-ethics-guidelines-for-artificial-intelligence/
Source tier: mainstream
Source content: "German version by Chris Klöver and Alexander Fanta"; "translation by Kristina Penner"; "first published by Netzpolitik.org"; title "No red lines: Industry defuses ethics guidelines for artificial intelligence."
Comparison: All metadata tokens in the note match the cited page's own credits character-for-character (page renders the surname "Klöver").
Decision: primary-sourced

## Claim 27: scalar:sources[3].note — Common Dreams, "'Worker Power Wins'...", 5 April 2019; ATEAC dissolved less than two weeks after formation following protest by over 2,300 employees and 300+ civil-society signatories

Source: https://www.commondreams.org/news/2019/04/05/worker-power-wins-google-scraps-controversial-ai-ethics-board-after-widespread
Source tier: mainstream
Source content: "'Worker Power Wins': Google Scraps Controversial AI Ethics Board After Widespread Outrage" (April 5, 2019); "Nearly 2,500 Google employees signed the worker-led petition, along with 'more than 300 outside experts and advocates.'"
Comparison: Title and date exact; counts consistent (see Claim 16; the note's "over 2,300" is a floor under the source's "nearly 2,500"); dissolution timeline corroborated by Google's own dated posts (Claim 15).
Decision: corroborated
