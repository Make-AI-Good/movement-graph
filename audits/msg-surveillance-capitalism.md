---
entity_id: msg-surveillance-capitalism
entity_hash: 15f4d6f8f0c0ea4766ebd51a89f6db907a04c666
audit_date: 2026-09-16
pass: 1
status: corrections-pending
claims_total: 25
claims_corroborated: 6
claims_primary_sourced: 8
claims_single_source: 2
claims_uncorroborated: 6
open_corrections: 3
sources_consulted:
  - https://en.wikipedia.org/wiki/The_Age_of_Surveillance_Capitalism
  - https://en.wikipedia.org/wiki/Surveillance_capitalism
  - https://news.harvard.edu/gazette/story/2019/03/harvard-professor-says-surveillance-capitalism-is-undermining-democracy/
  - https://www.amnesty.org/en/latest/press-release/2019/11/google-facebook-surveillance-privacy/
  - https://www.amnesty.org/en/documents/pol30/1404/2019/en/
  - https://www.amnesty.org/en/wp-content/uploads/2021/05/POL3014042019ENGLISH.pdf
  - https://api.semanticscholar.org/graph/v1/paper/DOI:10.1057/jit.2015.5
  - https://aisel.aisnet.org/jit/vol30/iss1/10/
  - https://cryptome.org/2015/07/big-other.pdf
  - https://opencuny.org/pnmarchive/files/2019/01/Zuboff-Digital-Declaration.pdf
  - https://shoshanazuboff.com/book/recent-work/
  - https://www.hachettebookgroup.com/titles/shoshana-zuboff/the-age-of-surveillance-capitalism/9781610395694/
  - https://privacyinternational.org/strategic-areas/challenging-corporate-data-exploitation
  - https://edri.org/our-work/orwells-wallet-european-electronic-identity-system-leads-us-straight-into-surveillance-capitalism/
  - https://algorithmwatch.org/en/awow-db/guide-to-understand-the-new-data-capitalism-platform-economy-and-their-risks/
  - https://www.accessnow.org/press-release/arzu-geybulla-donna-mckay-and-bruce-schneier-join-board-of-access-now/
---

## Claim 1: "Shoshana Zuboff — Harvard Business School professor emerita"

Source: https://news.harvard.edu/gazette/story/2019/03/harvard-professor-says-surveillance-capitalism-is-undermining-democracy/ ; https://aisel.aisnet.org/jit/vol30/iss1/10/
Source tier: primary
Source content: Gazette: "Professor emerita at Harvard Business School". AIS eLibrary author affiliation: "Harvard Business School Emerita; Berkman Center for Internet and Society".
Comparison: Role/affiliation matches across the journal's own record and Harvard's outlet. Also asserted in scalar:origin.
Decision: corroborated

## Claim 2: FAZ essay — "first appeared in Zuboff's September 2014 essay 'A Digital Declaration: Big Data as Surveillance Capitalism,' published in German and English in the Frankfurter Allgemeine Zeitung, which characterised surveillance capitalism as 'a radically disembedded and extractive variant of information capitalism'"

Source: https://opencuny.org/pnmarchive/files/2019/01/Zuboff-Digital-Declaration.pdf (full-page mirror of the FAZ article); https://en.wikipedia.org/wiki/Surveillance_capitalism
Source tier: primary
Source content: Mirror shows FAZ page "Shoshan[a] Zuboff on 'Big Data' as Surveillance Capitalism / A Digital Declaration ... 15.09.2014, von SHOSHANA ZUBOFF", German standfirst + English body, and verbatim: "The declaration thus established a radically disembedded and extractive variant of information capitalism that can I label 'surveillance capitalism.'" Wikipedia: essay dated September 15, 2014, same quote.
Comparison: Date, venue, bilingual publication, and quote all match; "first appeared" reads as scoped to Zuboff's framing (Wikipedia notes 2014 uses of the bare term by others, e.g. Vincent Mosco, which the entity does not contradict). Also asserted in scalar:origin.
Decision: corroborated

## Claim 3: "Big Other: Surveillance Capitalism and the Prospects of an Information Civilization," Journal of Information Technology 30: 75–89, March 2015

Source: https://api.semanticscholar.org/graph/v1/paper/DOI:10.1057/jit.2015.5 ; https://aisel.aisnet.org/jit/vol30/iss1/10/
Source tier: database
Source content: Semantic Scholar: "Publication Date: March 1, 2015; Journal of Information Technology, Volume 30, Pages 75-89". AIS eLibrary: Volume 30, Issue 1, DOI 10.1057/jit.2015.5.
Comparison: Title, journal, volume, pages, and month all match (note Wikipedia's surveillance-capitalism article says "April 2015" — the journal record's March 2015 governs). Also asserted in scalar:origin and scalar:sources[0].note.
Decision: corroborated

## Claim 4: "won the 2016 ICIS Best Paper Award" / "winner of the 2016 International Conference on Information Systems Best Paper Award"

Source: https://shoshanazuboff.com/book/recent-work/
Source tier: primary
Source content: "'Big Other: Surveillance Capitalism and the Prospects of an Information Civilization,' Journal of Information Technology, 2015. Recipient of the International Conference on Information Systems Senior Scholars Best Paper Award 2016."
Comparison: Award confirmed on Zuboff's own site; the full name is the ICIS *Senior Scholars* Best Paper Award 2016 — the entity's short form omits "Senior Scholars" but does not contradict. Asserted in scalar:origin, scalar:sources[0].note, and body § Origin.
Decision: primary-sourced

## Claim 5: The 2015 paper "named Google's AdWords as the first deployment of the logic" / "supplied the mechanism's precise anatomy: Google's AdWords system, recovering from the dot-com bust by monetizing behavioral exhaust ... That byproduct — behavioral surplus — was fed into machine-intelligence manufacturing processes to produce prediction products ... sold in a new market species Zuboff named behavioral futures markets"

Source: https://cryptome.org/2015/07/big-other.pdf (full text of the JIT 30 paper, extracted)
Source tier: primary
Source content: Full-text search of the paper: "behavioral surplus" — 0 occurrences; "behavioral futures" — 0 occurrences; "dot-com"/"bust" — 0 occurrences; "AdWords" — exactly 1 occurrence, inside a quoted passage from Levy 2009: "more eyeballs on the Web lead inexorably to more ad sales for Google. And since prediction and analysis are so crucial to AdWords, every bit of data, no matter how seemingly trivial, has potential value (Levy, 2009)." The paper's own apparatus is "surveillance assets," "surveillance capital," extraction/commodification/control, using "Google Inc.'s institutionalizing practices" as its lens.
Comparison: MISATTRIBUTION. The behavioral-surplus / prediction-products / behavioral-futures-markets / dot-com-bust-AdWords anatomy is the 2019 book's vocabulary (per the book's Wikipedia article: "unilaterally claiming human experience as free raw material for translation into behavioral data"), not the 2015 paper's. The paper does not name AdWords as the first deployment (AdWords appears only in a quoted secondary passage) and never uses "behavioral surplus" or "behavioral futures markets." Fix locations: scalar:origin ("which named Google's AdWords as the first deployment of the logic"), scalar:sources[0].note ("naming Google's AdWords as the first deployment ... articulating the behavioral surplus mechanism"), and body § Origin second-through-fifth sentences of the "Big Other" paragraph. The corrected attribution: the paper introduced surveillance capitalism as a logic of accumulation and the Big Other power architecture via Google as primary lens; the AdWords/behavioral-surplus anatomy belongs to the 2019 book (and later essays). Requires prose judgment beyond a single token — Editor should flag to Researcher.
Decision: correction

## Claim 6: "'Big Other' named the resulting architecture of distributed power: a computational system that observes, interprets, and acts on behavior without being observable in return, producing a new form of domination through asymmetric knowledge"

Source: https://cryptome.org/2015/07/big-other.pdf
Source tier: primary
Source content: "This architecture produces a distributed and largely uncontested new expression of power that I christen: 'Big Other.' It is constituted by unexpected and often illegible mechanisms of extraction, commodification, and control that effectively exile persons from their own behavior while producing new markets of behavioral prediction and modification." Also: "Unlike the centralized power of mass society, there is no escape from Big Other. There is no place to be where the Other is not."
Comparison: The body's paraphrase matches the paper's Big Other formulation in substance (distributed power, illegible/asymmetric observation, control of behavior). Also asserted in scalar:sources[0].note ("introducing the Big Other architecture of distributed power through extraction, commodification, and control") — that clause matches verbatim paper language.
Decision: primary-sourced

## Claim 7: Book bibliographic facts — *The Age of Surveillance Capitalism: The Fight for a Human Future at the New Frontier of Power* (PublicAffairs; UK: Profile Books; 704 pp; ISBN 978-1-78125-685-5; UK October 2018; US January 2019)

Source: https://www.hachettebookgroup.com/titles/shoshana-zuboff/the-age-of-surveillance-capitalism/9781610395694/ ; https://en.wikipedia.org/wiki/The_Age_of_Surveillance_Capitalism
Source tier: primary
Source content: Hachette (PublicAffairs' own catalog): "PublicAffairs", US publication "Jan 15, 2019", "704 pages". Wikipedia: publisher Profile Books, 704 pages, ISBN 9781781256855, publication October 4, 2018; subtitle "The Fight for a Human Future at the New Frontier of Power".
Comparison: All tokens match (ISBN 978-1-78125-685-5 = 9781781256855). US publisher and date from the publisher's own page; UK/Profile October 2018 rests on Wikipedia, acceptable alone for named-entity definitional bibliographic facts. Also asserted in scalar:origin and scalar:sources[1].note.
Decision: corroborated

## Claim 8: "The Financial Times called it 'a masterwork of original thinking and research'"

Source: https://en.wikipedia.org/wiki/The_Age_of_Surveillance_Capitalism ; https://www.hachettebookgroup.com/titles/shoshana-zuboff/the-age-of-surveillance-capitalism/9781610395694/
Source tier: tiebreaker
Source content: Wikipedia attributes "masterwork of original thinking and research" to the Financial Times. The publisher's own praise section carries a *different* FT quote ("groundbreaking, magisterial, alarming ... unmissable") and not this phrase. The FT review itself is paywalled/unfetchable.
Comparison: A quoted review attribution is tiebreaker-only territory; the only canonical carrier found is Wikipedia (the phrase otherwise circulates on promotional/speaker pages). Not a finding of error — the attribution is plausible and widely repeated — but no second canonical source confirms the exact wording.
Decision: uncorroborated

## Claim 9: "named among The New Yorker's top nonfiction of 2019 and Barack Obama's favorite books of that year"

Source: https://en.wikipedia.org/wiki/The_Age_of_Surveillance_Capitalism ; https://www.hachettebookgroup.com/titles/shoshana-zuboff/the-age-of-surveillance-capitalism/9781610395694/ ; CNN via search ("Barack Obama lists his favorite books of 2019", cnn.com 2019-12-28)
Source tier: mainstream
Source content: Wikipedia: The New Yorker listed it among its top non-fiction of 2019; Obama included it among his favorite books of 2019. Publisher's page: "Jia Tolentino selected the book as one of the best books of 2019 [The New Yorker]"; "Barack Obama selected the book as one of the best books of 2019." CNN/Newsweek/Variety headlines confirm the Obama 2019 list inclusion.
Comparison: Both reception facts match across Wikipedia, the publisher's page, and mainstream coverage. Also asserted in scalar:origin.
Decision: corroborated

## Claim 10: Harvard Gazette launch (March 2019) — "Zuboff named the two channels through which the model threatens democracy: internally, behavioral modification at scale erodes ... autonomy; externally, the platforms' accumulating knowledge asymmetry ... power without accountability" (+ scalar:sources[2].note three-arena solution framework)

Source: https://news.harvard.edu/gazette/story/2019/03/harvard-professor-says-surveillance-capitalism-is-undermining-democracy/
Source tier: mainstream
Source content: Article dated March 4, 2019. Autonomy channel: surveillance capitalists develop "economies of action" to "tune, herd, and condition our behavior"; "What is abrogated here is our right to the future tense, which is the essence of free will." Asymmetry channel: democracy erodes "as surveillance capitalism represents an unprecedented concentration of knowledge"; "They know everything about us, but we know little about them." Solutions: "the power of naming" / public indignation; "law and regulation ... new laws and regulatory institutions"; an "alliance of companies" building "an alternative ecosystem."
Comparison: The body's two-channel summary and the sources[2].note three-arena framework (public opinion, new law, competitive alternatives) both match the article's content. Single mainstream source, but it is the very article the claim describes. Fix location if ever needed: scalar:sources[2].note.
Decision: single-source

## Claim 11: Amnesty press release, 21 November 2019 — quotes "inherently incompatible with the right to privacy," "unprecedented danger to human rights," "a radical transformation of the tech giants' core business model"; announcing "Surveillance Giants: How the Business Model of Google and Facebook Threatens Human Rights" (Index POL 30/1404/2019, November 2019)

Source: https://www.amnesty.org/en/latest/press-release/2019/11/google-facebook-surveillance-privacy/ ; https://www.amnesty.org/en/documents/pol30/1404/2019/en/
Source tier: primary
Source content: Press release dated 21 November 2019, titled "Facebook and Google's pervasive surveillance poses an unprecedented danger to human rights"; carries verbatim "inherently incompatible with the right to privacy," "unprecedented danger to human rights," and "radical transformation of the tech giants' core business model," announcing the report *Surveillance Giants*. Document page: title "Surveillance giants: How the business model of Google and Facebook threatens human rights," Index POL 30/1404/2019, 21 November 2019.
Comparison: Date, quotes, report title, and index number all match Amnesty's own pages. Also asserted in scalar:sources[3].note and scalar:sources[4].note.
Decision: primary-sourced

## Claim 12: "mapping the extraction mechanism across the Universal Declaration of Human Rights framework — five specific rights: privacy, freedom of opinion and expression, freedom of thought, equality and non-discrimination, and control over personal information" (+ scalar:sources[3].note "the five specific rights the report maps the mechanism onto")

Source: https://www.amnesty.org/en/wp-content/uploads/2021/05/POL3014042019ENGLISH.pdf (full text, extracted); https://www.amnesty.org/en/latest/press-release/2019/11/google-facebook-surveillance-privacy/
Source tier: primary
Source content: Report: "Firstly, an assault on the right to privacy on an unprecedented scale, and then a series of knock-on effects that pose a serious risk to a range of other rights, from freedom of expression and opinion, to freedom of thought and the right to non-discrimination." The word "five" does not occur in the report in a rights-enumeration context (0 occurrences). Press release: the model "is incompatible with every element of the right to privacy, including the freedom from intrusion into our private lives, the right to control information about ourselves, and the right to a space in which we can freely express our identities" — i.e. control over information is an *element of* the right to privacy, not a fifth right.
Comparison: The sources enumerate FOUR rights (privacy; freedom of opinion and expression; freedom of thought; equality and non-discrimination), with control over personal information an element of privacy. "Five specific rights" with control-over-personal-information as a distinct fifth is contradicted by both the report and the press release. Fix locations: body § Amnesty International sentence beginning "mapping the extraction mechanism across..." AND scalar:sources[3].note ("the five specific rights the report maps the mechanism onto"). Also note the report grounds its rights framework in UDHR *and* ICCPR citations, so "Universal Declaration of Human Rights framework" is loose but not false. Recasting the enumeration requires more than a single token — Editor should flag to Researcher.
Decision: correction

## Claim 13: "demanding 'a radical transformation of the tech giants' core business model' alongside government enforcement of data protection law that prohibits conditioning service access on consent to data surveillance for marketing"

Source: https://www.amnesty.org/en/wp-content/uploads/2021/05/POL3014042019ENGLISH.pdf ; https://www.amnesty.org/en/latest/press-release/2019/11/google-facebook-surveillance-privacy/
Source tier: primary
Source content: Report recommendations for states: "Governments must take measures to ensure that access to and use of essential digital services [is not conditioned] on 'consenting' to the collection, processing or sharing of their personal data for marketing or advertising" and "Governments must enact and enforce strong data protection laws with human rights at the front and centre." Report body: "the companies have conditioned access to their services on 'consenting' to processing and sharing of their personal data for marketing and advertising, directly countering the right to decide when and how our personal [data is used]." Press release: "radical transformation of the tech giants' core business model."
Comparison: Both halves of the demand claim match Amnesty's own texts.
Decision: primary-sourced

## Claim 14: "The Cambridge Analytica scandal and documented electoral manipulation were named as downstream effects of the behavioral modification capacity the model accumulates" (+ scalar:sources[4].note "demonstrates Cambridge Analytica and electoral manipulation as downstream effects")

Source: https://www.amnesty.org/en/wp-content/uploads/2021/05/POL3014042019ENGLISH.pdf
Source tier: primary
Source content: Report contents include "Hidden manipulation at scale ... BOX 4: The Cambridge Analytica Scandal"; Box 4 details the harvested-profiles scandal with Guardian citations ("Cambridge Analytica kept Facebook data models through US election," Guardian, May 2018) and voter-data points ("4,000 to 5,000 data points on each voter").
Comparison: The report does treat Cambridge Analytica and electoral manipulation as knock-on effects of the surveillance-based model, within its "Hidden manipulation at scale" chapter. Matches.
Decision: primary-sourced

## Claim 15: scalar:sources[4].note — "first major human rights organisation deployment of the framing as a full advocacy document"

Source: no canonical source found
Source tier: none
Source content: Amnesty's own pages do not claim firstness; no canonical source found asserting no earlier major human-rights-organisation advocacy document deployed the framing.
Comparison: Contested-firstness class — a "first" claim that would need a source explicitly establishing priority. Fix location if resolved: scalar:sources[4].note.
Decision: uncorroborated

## Claim 16: "The Amnesty report became the framing's most-cited civil society deployment in the subsequent EU regulatory campaign period"

Source: no canonical source found
Source tier: none
Source content: No citation-count or survey source found supporting a "most-cited" comparison.
Comparison: Superlative empirical claim with no located canonical support.
Decision: uncorroborated

## Claim 17: Edge propagated_by_orgs → org-algorithmwatch ("the framing moved through AlgorithmWatch")

Source: https://algorithmwatch.org/en/awow-db/guide-to-understand-the-new-data-capitalism-platform-economy-and-their-risks/
Source tier: primary
Source content: "This guide explains in simple language the main features of what's being called 'data capitalism' or also 'surveillance capitalism' (following Shoshana Zuboff's book of the same name, published in 2019)."
Comparison: AlgorithmWatch's own published material deploys the framing, explicitly following Zuboff. Edge resolves to product/entities/organizations/org-algorithmwatch.md.
Decision: primary-sourced

## Claim 18: Edge propagated_by_orgs → org-edri ("the framing moved through ... the European Digital Rights network (EDRi)")

Source: https://edri.org/our-work/orwells-wallet-european-electronic-identity-system-leads-us-straight-into-surveillance-capitalism/
Source tier: primary
Source content: EDRi article (2 February 2022): "Orwell's Wallet: European electronic identity system leads us straight into surveillance capitalism." Search of edri.org also shows the framing in EDRi's who-we-are/events material ("this 'surveillance capitalism' has had a global impact on democracy"; Zuboff has keynoted EDRi events).
Comparison: EDRi's own site repeatedly deploys the framing in campaign work. Edge resolves to product/entities/organizations/org-edri.md.
Decision: primary-sourced

## Claim 19: Edge propagated_by_orgs → org-access-now ("the framing moved through ... Access Now as part of the coordinated civil society campaign [on] the EU AI Act")

Source: https://www.accessnow.org/press-release/arzu-geybulla-donna-mckay-and-bruce-schneier-join-board-of-access-now/
Source tier: primary
Source content: The only located use of the term on Access Now's own site is a quote from incoming board member Bruce Schneier: "We need to prevent the normalization of unaccountable government surveillance, and also to take meaningful steps to rein in 'surveillance capitalism' by corporations that profit from our data." A targeted search for Access Now EU-AI-Act material using "surveillance capitalism" or "surveillance-based business model" found none; Access Now's AI Act campaigning (e.g. #ProtectNotSurveil) runs on state-surveillance framings.
Comparison: A board member's quoted remark does not establish organizational deployment of the framing, and no source ties Access Now's EU AI Act campaign to the surveillance-capitalism framing specifically. The edge resolves (org-access-now.md exists), but the propagation claim as stated lacks canonical support. Not asserting error — evidence may exist beyond reach — but nothing found.
Decision: uncorroborated

## Claim 20: Edge propagated_by_orgs → org-privacy-international ("Privacy International deployed the framing")

Source: https://privacyinternational.org/strategic-areas/challenging-corporate-data-exploitation
Source tier: primary
Source content: "Companies are innovating on surveillance capitalism, reducing people to data for exploitation." PI's site also carries e.g. "Generative AI won't take over the world, surveillance capitalism already has" (news-analysis 5331, per site search).
Comparison: PI's own strategic-area page deploys the framing. Edge resolves to product/entities/organizations/org-privacy-international.md.
Decision: primary-sourced

## Claim 21: PI specifics — "in its campaign on the adequacy of data protection law for the surveillance-capitalism era, focusing on the gap between the GDPR's consent-based framework and a business model in which meaningful individual consent is structurally impossible"

Source: https://privacyinternational.org/strategic-areas/challenging-corporate-data-exploitation
Source tier: primary
Source content: The strategic-area page says "Our laws are not yet able to address these risks" but does not discuss GDPR adequacy or consent mechanics; no PI campaign matching the described consent-gap/opt-out-as-behavioral-signal characterization was located.
Comparison: PI's use of the framing is attested (Claim 20), but this specific campaign characterization — including the "opt-out decision is itself a behavioral signal" argument — was not found in PI's material. Too paraphrastic/unlocated to confirm.
Decision: uncorroborated

## Claim 22: Book content — "the graduation from behavioral prediction to behavioral modification ('actuarial' → 'tuning' → 'herding' products)"

Source: https://news.harvard.edu/gazette/story/2019/03/harvard-professor-says-surveillance-capitalism-is-undermining-democracy/ ; academic reviews of the book via search (euppublishing.com Journal of Social and Political Philosophy review)
Source tier: primary
Source content: Gazette (Zuboff speaking at the book's launch): surveillance capitalists develop "economies of action" to "tune, herd, and condition our behavior." Academic review: "Zuboff identifies three kinds of technique: tuning, herding, and conditioning, each of which allows some to affect the behavior of others without the targeted individuals being aware." No source uses "actuarial" as a stage in this progression, and the attested trio describes behavioral-modification *techniques*, not a product-maturation sequence.
Comparison: The scare-quoted progression "'actuarial' → 'tuning' → 'herding' products" misrenders Zuboff's attested vocabulary: her trio is tuning / herding / conditioning. "Actuarial" is unattested in any located source as part of this typology. Fix location: body § Origin, third paragraph. Same invented-trio class as previously caught misquotes (cf. Taylor 2017 pillars, Kwet trio). Replacement requires recasting the parenthetical — Editor should flag to Researcher.
Decision: correction

## Claim 23: Book content — "Facebook's development of behavioral modification as surveillance capitalism's second stage after Google's discovery of the extraction logic, and ... the two companies' combined dominance over search, social media, mobile operating systems, video, and browser markets"

Source: no source fetched covers these formulations
Source tier: none
Source content: The book's text is not fetchable; located reviews and the Gazette launch coverage do not carry the "second stage" staging or the five-market dominance enumeration in this form.
Comparison: Plausible summaries of book argument but too paraphrastic to compare against any fetchable source. Not asserting error.
Decision: uncorroborated

## Claim 24: 2018 context dates — "the Cambridge Analytica scandal (March 2018), the Facebook Congressional hearings (April 2018), and the GDPR's first enforcement actions (beginning May 2018)"

Source: mainstream coverage via search (nbcnews.com Facebook 2018 timeline; cnbc.com Cambridge Analytica timeline; privacyinternational.org "Cambridge Analytica, GDPR — 1 year on"); https://www.amnesty.org/en/wp-content/uploads/2021/05/POL3014042019ENGLISH.pdf (footnotes dated 2018/03)
Source tier: mainstream
Source content: Guardian revelations 17 March 2018; Zuckerberg testified before Senate committees April 10 and House April 11, 2018; "The GDPR ... finally took effect across the EU on 25 May 2018."
Comparison: March 2018 and April 2018 match. The GDPR token is loosely worded — 25 May 2018 is when the regulation took effect and first complaints were filed, not strictly "first enforcement actions" (the first headline fines came later) — but the dating itself is right and the phrasing is not a token-level contradiction.
Decision: corroborated

## Claim 25: Related edge msg-data-colonialism — "developed in Latin American civil society organising over the same 2019–2022 period — explicitly positions itself as a supplement to and partial critique of the surveillance-capitalism frame"

Source: LSE Review of Books and Surveillance & Society reviews of Couldry & Mejias via search snippets; cross-checked against product/entities/messages/msg-data-colonialism.md
Source tier: mainstream
Source content: Reviews: "Couldry and Mejias argue that what is taking place under data colonialism is merely the extension of capitalism as it has developed over the last two centuries, in contrast to Shoshana Zuboff's theory of 'The Age of Surveillance Capitalism,' which treats it as a new type of capitalism." The sibling entity anchors the framing's academic crystallisation in Couldry & Mejias 2019 with its working public life in Latin American civil-society organising (Derechos Digitales, Coding Rights) — consistent with this entity's characterization.
Comparison: The explicit-positioning-against-Zuboff claim is attested in academic reviews (snippet-level); the Latin American development locus is consistent with the sibling entity's sourced account. Edge resolves to msg-data-colonialism.md. Supported on lighter sourcing.
Decision: single-source
