---
id: msg-open-washing
type: message
name: Open washing
status: active
confidence: high
tags: [framing, open-source, transparency, generative-ai, eu-ai-act, corporate-critique, meta, llama, regulatory, digital-rights, 2023, 2024, 2025, global]
created: 2026-09-17
last_updated: 2026-09-17
origin: |
  "Openwashing" — presenting something as open when it is not — was coined by Michelle Thorne,
  an internet and climate policy scholar, in 2009, using a Berlin Partner marketing campaign
  ("be open. be free. be Berlin") that adopted open language while maintaining restrictive terms
  of use. The term entered the AI register beginning in 2023 as civil society organizations,
  researchers, and standards bodies challenged major AI companies' use of the "open source"
  label for systems that release only model weights while withholding training data and imposing
  licensing restrictions. The specific AI application crystallized through two concurrent
  developments in 2024: Andreas Liesenfeld and Mark Dingemanse (Max Planck Institute for
  Psycholinguistics) published "Rethinking open source generative AI: open-washing and the EU AI
  Act" at ACM FAccT 2024, surveying 45+ generative AI systems across 14 openness dimensions and
  finding most were "open weight" at best; and the Open Source Initiative released the Open
  Source AI Definition v1.0 at All Things Open in October 2024, establishing a formal standard
  requiring training data, training code, and model weights all to be publicly available under
  permissive licenses. The primary target was Meta's Llama family — which releases model weights
  but withholds training data and imposes licensing restrictions including, in later versions,
  prohibition on use by EU residents. A November 2024 Nature article characterized Llama 3 as
  "openwashing." The EU AI Act's open source exemptions gave the accusation regulatory stakes:
  companies had financial incentive to claim the label to access exemptions regardless of whether
  they met genuine openness standards.
originating_person:
originating_org:
propagated_by_orgs:
  - org-mozilla-foundation
  - org-electronic-frontier-foundation
  - org-algorithmwatch
related_messages:
  - msg-ethics-washing
  - msg-public-ai
sources:
  - url: https://en.wikipedia.org/wiki/Openwashing
    last_checked: 2026-09-17
    note: 'Wikipedia article on "Openwashing" — source for Michelle Thorne coining the term in 2009 via the Berlin Partner campaign; core definition as "presenting something as open when it is not actually open"; and early application to Meta''s Llama, including the November 2024 Nature article characterizing Llama 3 as "providing little more than an API or the ability to download a model subject to distinctly non-open use restrictions"'
  - url: https://dl.acm.org/doi/10.1145/3630106.3659005
    last_checked: 2026-09-17
    note: 'Andreas Liesenfeld and Mark Dingemanse (Max Planck Institute for Psycholinguistics), "Rethinking open source generative AI: open-washing and the EU AI Act," ACM FAccT 2024 — primary academic source for the open-washing framing applied to AI; surveyed 45+ generative AI systems across 14 openness dimensions including training datasets, fine-tuning data, model weights, training code, and scientific documentation; found that while "open source" was widely claimed, most systems were "open weight" at best; providers withheld training and fine-tuning data to "evade scientific, legal and regulatory scrutiny"; openness argued to be "necessarily composite and gradient" rather than binary; EU AI Act''s partial-disclosure approach argued to "inadvertently enable open-washing"'
  - url: https://opensource.org/ai/open-source-ai-definition
    last_checked: 2026-09-17
    note: 'Open Source Initiative, "The Open Source AI Definition – 1.0" (released October 2024 at All Things Open) — first formal standard for open source AI, requiring public availability of training data sufficient to reproduce the training pipeline, training code, and model weights under permissive licenses; result of multi-year co-design process including an international roadshow of workshops; addresses openwashing by establishing an evidence-based threshold distinguishing genuine from nominal openness'
  - url: https://opensource.org/blog/metas-llama-license-is-still-not-open-source
    last_checked: 2026-09-17
    note: 'Jordan Maris, "Meta''s LLaMa license is still not Open Source," Open Source Initiative blog, February 18, 2025 — OSI''s formal finding that Llama 3.x licenses violate the Open Source Definition: arbitrary exclusion of EU residents, purpose limitations, and field-of-use restrictions violate OSD Points 5 and 6 (non-discrimination among persons and fields of endeavor) and Freedom 0 (use for any purpose)'
  - url: https://the-decoder.com/meta-accused-of-open-washing-ai-models-clashing-with-open-source-purists/
    last_checked: 2026-09-17
    note: 'The Decoder, "Meta accused of ''open washing'' AI models, clashing with open-source purists," September 22, 2024 — source for OSI head Stefano Maffulli accusing Zuckerberg of "really bullying the industry to follow his lead" in defining open-source AI; Ali Farhadi (Allen Institute for AI) stating Llama models "are just not open source"; Mark Surman (Mozilla Foundation) warning of "open-washing" risks without precise definitions; Mistral relabeling its approach "open weight" rather than "open source"'
  - url: https://openfuture.eu/observatory/aia-open-source/
    last_checked: 2026-09-17
    note: 'Open Future, AI Act and Open Source Observatory (tracked April 2021–April 2025) — source for Meta''s Llama 2 (August 2023) demonstrating "the mirage of open-source AI"; December 2023 AI Act final compromise granting open source models exemptions from documentation and compliance obligations while permitting partial disclosures; Open Future''s critique that the exemption creates accountability asymmetry and that "openness alone will not democratize AI"'
---

# Open washing

**Open washing** (also "openwashing") is the civil society framing that names the deployment of the label "open source" for AI systems that do not meet genuine open-source standards — releasing model weights to the public while withholding training data, training code, or imposing commercial and field-of-use licensing restrictions that prevent genuine replication, modification, and redistribution. The framing follows the rhetorical pattern of [ethics washing](msg-ethics-washing.md): borrowing the credibility of a well-understood normative commitment — openness as transparency, access, and democratic participation — while withholding the substantive practices that justify that credibility. In the generative AI context, it names a specific substitution: "open weights" standing in for "open source," granting companies the reputational benefits of openness — and, from 2024 onward, significant regulatory benefits under the EU AI Act's open source exemptions — without the transparency that makes open source meaningful.

## Origin

The term was coined by Michelle Thorne, an internet and climate policy scholar, in 2009, using a Berlin Partner marketing campaign as her founding case: the campaign urged Berlin to "be open. be free. be Berlin" while the actual terms of use were restrictive. The word entered general technology-policy circulation as a broadly applicable accusation — any actor invoking open-source credibility without open-source practice could be charged with it. Its application to generative AI gained momentum in 2023 as [Mozilla Foundation](../organizations/org-mozilla-foundation.md) and the Open Source Initiative identified Meta's Llama models as a central case, and as debates over the EU AI Act's open source exemptions gave definitional disputes practical regulatory weight.

## The framing's architecture

The accusation's academic consolidation came in "Rethinking open source generative AI: open-washing and the EU AI Act," presented by Andreas Liesenfeld and Mark Dingemanse at ACM FAccT 2024. Surveying [45+ generative AI systems](https://dl.acm.org/doi/10.1145/3630106.3659005) across 14 openness dimensions — training datasets, fine-tuning data, model weights, training code, and scientific documentation — the paper found that while "open source" was widely claimed, most systems were "open weight" at best. Providers withheld training and fine-tuning data specifically to "evade scientific, legal and regulatory scrutiny." The paper argued that openness in generative AI is "necessarily composite and gradient": a system is not simply open or closed, but open or closed across distinct dimensions, and releasing model weights captures only one of them. Claiming "open source" on the basis of weights-only release is the mechanism the paper named as open-washing.

## Meta's Llama and the OSI response

The Open Source Initiative addressed the definitional vacuum directly. After years of criticism over the use of "open source" for weights-only releases, the OSI [released the Open Source AI Definition v1.0](https://opensource.org/ai/open-source-ai-definition) at All Things Open in October 2024 — the result of a multi-year co-design process including an international workshop roadshow. The OSAID establishes that genuine open source AI requires four components all publicly available under permissive licenses: architecture, training code, model weights, and training data sufficient to reproduce the training pipeline.

By this standard, Meta's Llama family — the primary target of the openwashing charge — does not qualify. The OSI's formal analysis found that [Llama 3.x licenses violated the Open Source Definition](https://opensource.org/blog/metas-llama-license-is-still-not-open-source) on multiple grounds: they arbitrarily exclude EU residents, impose purpose and field-of-use limitations, and violate OSD Points 5 and 6 (non-discrimination among persons and fields of endeavor) and Freedom 0 (use for any purpose). OSI head Stefano Maffulli accused Mark Zuckerberg of "really bullying the industry to follow his lead" in defining open-source AI. Ali Farhadi of the Allen Institute for AI [stated](https://the-decoder.com/meta-accused-of-open-washing-ai-models-clashing-with-open-source-purists/) that Llama models "are just not open source." A November 2024 *Nature* article characterized Llama 3 as "openwashing," providing "little more than an API or the ability to download a model subject to distinctly non-open use restrictions." Mistral, another widely labeled "open source" LLM, [responded](https://the-decoder.com/meta-accused-of-open-washing-ai-models-clashing-with-open-source-purists/) by relabeling its release approach "open weight" rather than "open source."

## Regulatory stakes: the EU AI Act

The openwashing framing acquired concrete policy stakes through the EU AI Act. The Act grants open source AI models exemptions from certain documentation, transparency, and compliance obligations that apply to proprietary systems. This creates structural incentives to claim the "open source" label regardless of actual openness, because the label translates into regulatory benefit. Open Future, which tracked the AI Act's open source provisions through the full legislative process from 2021 to 2025, [named this as the Act's core accountability vulnerability](https://openfuture.eu/observatory/aia-open-source/): by permitting partial disclosures — model weights without training data — and descriptive dataset summaries rather than full training-pipeline transparency, the Act "inadvertently enables open-washing." The FAccT 2024 paper made the same argument: the EU AI Act "will be putting legal weight on the term 'open source,'" creating "stronger incentives for lobbying operations driven by corporate interests to water down its definition." The [Mozilla Foundation](../organizations/org-mozilla-foundation.md)'s Mark Surman [warned publicly](https://the-decoder.com/meta-accused-of-open-washing-ai-models-clashing-with-open-source-purists/) of "open-washing" risks without precise definitions — framing the definitional dispute as inseparable from the regulatory outcome.

## Relationship to adjacent framings

Open washing sits in the same family as [ethics washing](msg-ethics-washing.md) — deploying the vocabulary of a public good (ethics, openness) as cover rather than commitment — and in structural tension with the [Public AI](msg-public-ai.md) framing, which argues that the appropriate response to concentrated private AI development is genuine public ownership of AI infrastructure, not voluntarily "open" releases on companies' own terms. Where ethics washing named the substitution of voluntary principles for binding accountability, open washing names the substitution of weights-only release for genuine transparency. Both framings position the civil society response as demanding binding, verifiable standards rather than trusting company-provided labels.
