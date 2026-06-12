---
id: org-masakhane-nlp
type: organization
name: Masakhane
status: active
confidence: high
tags: [africa, pan-african, nlp, multilingual, open-source, decolonial-ai, participatory, community-research, grassroots-research, kenya, global-south, data-sovereignty, language-technology, machine-translation]
created: 2026-06-11
last_updated: 2026-06-11
founded: 2019
location: international
website: https://www.masakhane.io
strategies: [strat-parallel-community-research-institution]
key_people: []
board_and_advisors: []
related_orgs: []
funders: []
sources:
  - url: https://www.masakhane.io/home
    last_checked: 2026-06-11
    note: 'Homepage — mission statement, Ubuntu philosophy ("Umuntu Ngumuntu Ngabantu"), open membership model, community overview.'
  - url: https://arxiv.org/abs/2003.11529
    last_checked: 2026-06-11
    note: '"Masakhane — Machine Translation For Africa" (2020) — foundational community paper; 40+ neural MT models for 38+ African languages; participatory research methodology. Wikimedia Foundation Research Award of the Year 2021.'
  - url: https://idrc-crdi.ca/en/what-we-do/projects-we-support/project/masakhane-ai-languages-hub
    last_checked: 2026-06-11
    note: 'IDRC project page — Masakhane African Languages Hub established July 2025 in Kilifi, Kenya; 5-year AI for Development partnership with FCDO; Chenai Chair named as Hub Director.'
  - url: https://www.gatesfoundation.org/about/committed-grants/2025/09/inv-088221
    last_checked: 2026-06-11
    note: 'Gates Foundation committed grant (2025) — co-funder of LINGUA Africa alongside Google.org and Microsoft AI for Good Lab.'
  - url: https://brittlepaper.com/2026/05/masakhane-african-languages-hub-microsoft-gates-foundation-and-google-org-launch-open-call-for-ai-projects-in-african-languages-grants-of-up-to-250000-available-apply-by-15-june-2026/
    last_checked: 2026-06-11
    note: 'Brittlepaper coverage of LINGUA Africa 2026 open call — up to $250,000 cash plus $400,000 compute credits per project across 50+ African languages; 93 applications from 22 countries in the 2025 cohort.'
  - url: https://slator.com/the-masakhane-project-puts-africa-on-the-machine-translation-map/
    last_checked: 2026-06-11
    note: 'Slator profile (2020) — founding at Deep Learning Indaba 2019, co-founders Jade Abbott and Laura Martinus, participatory model overview.'
---

# Masakhane

Masakhane — meaning "We build together" in isiZulu — is a pan-African grassroots research community working to strengthen natural language processing for African languages, built on the premise that Africans should shape and own the AI systems that affect them. Founded in 2019 at the Deep Learning Indaba in Nairobi by Jade Abbott and Laura Martinus, it [grew from an informal volunteer project](https://slator.com/the-masakhane-project-puts-africa-on-the-machine-translation-map/) into the most consequential producer of open-source African-language NLP infrastructure in the world: 3,000+ members from 30+ African countries collaborating through a Slack-anchored community, 400+ open-source models and 20+ datasets on Hugging Face, and a participatory research model that integrates language speakers as co-researchers from the first stage of dataset design. The community's guiding philosophy is Ubuntu — *Umuntu Ngumuntu Ngabantu*, a person is a person through another person — which it operationalises as an open-membership structure where linguists, students, software engineers, and community members participate alongside academic researchers rather than appearing only as paid annotators.

## Founding and community model

The community emerged from the 2019 Deep Learning Indaba in Nairobi, catalysed by the observation that despite Africa hosting more than 2,000 of the world's living languages, African languages were near-absent from the machine translation systems and language models then reshaping global communication. Abbott and Martinus launched Masakhane — framed from the start as a community, not a company or institution — as a vehicle for African ML researchers to collaborate across national and linguistic boundaries at a moment when most such work required institutional affiliation in the Global North.

Participation requires no formal credentials beyond adherence to a code of conduct. Members contribute across the research lifecycle — dataset creation, model training, qualitative evaluation, documentation, mentoring — and vote in weekly open meetings on research directions and annotation-protocol disputes. This embeds participatory governance into the research process itself rather than treating community engagement as a downstream validation step. The goal stated from founding is to refuse the extractive model in which African language speakers generate data that platforms commodify and to build, instead, toward AI systems that African communities own and govern.

## Datasets and models

Masakhane's most durable contribution is a body of open-source datasets covering NLP tasks for which African languages previously had no public training data. The flagship datasets include:

- **MasakhaNER** — named entity recognition for 10 African languages (2021), later extended to 20; the first large-scale publicly available NER dataset for African languages, accompanied by the [foundational 2020 ArXiv paper](https://arxiv.org/abs/2003.11529) on machine translation across 38+ African languages
- **MasakhaPOS** — part-of-speech tagging for 20 African languages, the largest publicly available POS dataset for African languages
- **MasakhaNEWS** — news topic classification across 16 African languages; again the largest publicly available dataset for the task
- **NaijaNLP** — sentiment analysis and hate-speech detection corpora for Hausa, Yorùbá, Igbo, and Nigerian Pidgin, drawing on 30,000+ annotated tweets per language

The machine translation work documented in the [foundational 2020 community paper](https://arxiv.org/abs/2003.11529) produced 40+ neural models covering 38+ languages. All releases are open-source and made available without charge, in explicit rejection of the convention under which commercial labs treat such language data as proprietary infrastructure. The paper received the Wikimedia Foundation Research Award of the Year in 2021.

## Participatory annotation and community research

The participatory annotation model is the community's most methodologically distinctive contribution. Rather than the standard outsourced annotation pipeline — workers labelling data according to instructions they did not help design — Masakhane integrates native speakers into research design from the outset. Community workshops for each target language enable annotators to deliberate on contested cases rather than applying rules mechanically, producing annotation schemas that encode local linguistic norms. Annotation drives have reached beyond the academic network through Facebook groups, WhatsApp broadcasts, Mozilla Common Voice, and targeted apps, engaging speakers with no prior connection to AI research as community researchers.

The model is grounded in a specific ethical refusal: Africans should not appear in the AI research pipeline only as a source of cheap labour or raw data. The community's framing positions participatory research as a structural intervention in who has standing to define what counts as correct in African-language AI — a question with real consequences for the systems deployed in education, healthcare, and public administration on the continent.

## Data sovereignty and the JW300 controversy

Masakhane operates with an explicit decolonial framing that positions African-language NLP as a site where the dynamics of AI extraction are visible and contestable. An early controversy illustrated the stakes: the JW300 corpus — a parallel text collection derived from Jehovah's Witnesses scripture, widely used in NLP for its language breadth — was adopted in early Masakhane work before researchers identified legal and ethical problems: copyright issues, contract provisions overriding open-access claims, and cross-border implications for communities that had not consented to having their religious texts repurposed as AI training data. The community's subsequent move toward community-generated data with clear provenance and consent-based licensing was formative: a standing commitment to sourcing data through channels that embed community ownership from collection to deployment, rather than treating existing text as a free resource.

## Institutional evolution

In July 2025 Masakhane established the **Masakhane Research Foundation** as its formal nonprofit structure, [based in Kilifi, Kenya](https://idrc-crdi.ca/en/what-we-do/projects-we-support/project/masakhane-ai-languages-hub), with Chenai Chair as director. The Foundation provides the legal and financial infrastructure for the community's funding relationships with the IDRC (through a five-year AI for Development programme jointly funded with the UK FCDO), the Gates Foundation, Google.org, and Microsoft AI for Good Lab, while preserving the open, participatory governance model the community has run since 2019.

The Foundation's current flagship initiative is **LINGUA Africa** — an [open call](https://brittlepaper.com/2026/05/masakhane-african-languages-hub-microsoft-gates-foundation-and-google-org-launch-open-call-for-ai-projects-in-african-languages-grants-of-up-to-250000-available-apply-by-15-june-2026/) for AI projects across 50 African languages, offering grants of up to $250,000 cash plus $400,000 in compute credits per project. The 2025 cohort received 93 applications from 22 countries; four projects were selected. The initiative extends Masakhane's model from producing shared open-source infrastructure to funding African organisations to build locally anchored products and services using that infrastructure — a progression from commons-building to commons-enabled deployment.
