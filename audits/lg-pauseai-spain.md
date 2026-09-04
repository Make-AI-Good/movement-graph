---
entity_id: lg-pauseai-spain
entity_hash: 260260d817aebc0dcd903b8d31ad22d6304b8b16
audit_date: 2026-09-03
pass: 1
status: supported
claims_total: 18
claims_corroborated: 3
claims_primary_sourced: 8
claims_single_source: 1
claims_uncorroborated: 6
open_corrections: 0
sources_consulted:
  - https://pauseai.es
  - https://pauseai.es/nosotros
  - https://pauseai.es/propuesta
  - https://pauseai.info/communities
  - https://pauseai.info/protests
  - https://pauseaispanish.substack.com
  - https://en.wikipedia.org/wiki/PauseAI
  - https://humanstatement.org/thank-you/
  - https://www.change.org/p/las-conferencias-sobre-ia-tienen-que-volver-a-tomar-la-seguridad-en-serio/u/34409721
---

## Claim 1: "PauseAI Spain ... is the Spanish national chapter of PauseAI" (pauseai.es; parent_org: org-pauseai; website_or_contact: pauseai.es)

Source: https://pauseai.info/communities + https://pauseai.es + https://humanstatement.org/thank-you/
Source tier: primary
Source content: Communities directory Spain entry: "España[](https://pauseai.es)" — listed as a national community with pauseai.es as its site. Declaration roster: "Ayoze García González National leader, Spain, PauseAI".
Comparison: PauseAI Global's own directory lists España with pauseai.es; the site self-identifies as PauseAI's Spanish version; an independent third-party roster records a "National leader, Spain, PauseAI". Covers frontmatter `parent_org` and `website_or_contact` too.
Decision: corroborated

## Claim 2: PauseAI is "the international movement calling for a coordinated, treaty-backed pause on the training of the most powerful general-purpose AI systems"

Source: https://pauseai.es/propuesta + https://en.wikipedia.org/wiki/PauseAI
Source tier: primary
Source content: Propuesta: "El objetivo principal de estas cumbres debería ser un tratado." Wikipedia: PauseAI seeks to "implement a temporary pause on the training of the most powerful general AI systems"; Meindertsma argued "binding international treaties" are necessary.
Comparison: Definitional fact about a named org; own proposal page plus Wikipedia (canonical-alone class for named-entity definitional facts) both match the body's rendering.
Decision: corroborated

## Claim 3: The chapter "describes itself as grouping 'Spanish-speaking volunteers from Spain and Hispanic America' (voluntarios hispanohablantes de PauseAI, desde España e Hispanoamérica)" (also frontmatter `location` scalar "operating pan-Hispanic — Spain and Hispanic America")

Source: https://pauseai.es/nosotros + https://pauseaispanish.substack.com
Source tier: primary
Source content: /nosotros: "La web que estás leyendo agrupa a los voluntarios hispanohablantes de [PauseAI]" and "Entre los miembros de PauseAI en España e Hispanoamérica, figuran trabajadores y expertos". Substack: "Desde España e Hispanoamérica, nos sumamos a la iniciativa de la organización internacional PauseAI".
Comparison: The substance (grouping Spanish-speaking volunteers; Spain + Hispanic America scope, covering the `location` scalar) is live on two of the chapter's own properties. Source drift: the body's contiguous verbatim Spanish phrase no longer appears as one sentence on the live site — its two halves appear in separate sentences on /nosotros.
Decision: primary-sourced

## Claim 4: "among the minority of PauseAI national chapters to maintain a dedicated national website ... rather than a social-media-only contact presence"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Live directory national communities with own domains: Canada, Czechia, France, Germany, Serbia, Spain, Sweden, UK (8); social-media/mail/directory-only: Kenya, Italy, Netherlands, Nigeria, Romania, Poland, Australia (7).
Comparison: The live directory shows 8 of 15 national communities with dedicated national websites — roughly half, not clearly a minority; the roster has drifted since the 2026-06-09 draft (US no longer listed with a national site; Australia is a directory-page entry; Italy is WhatsApp-only). The past state cannot be checked (web.archive.org blocked). Not a token-level error; the characterization can no longer be confirmed.
Decision: uncorroborated

## Claim 5: "The chapter's national director is Ayoze García González, named on PauseAI Global's About page alongside the federation's other 14 national-chapter leads" (also frontmatter `key_people`)

Source: https://humanstatement.org/thank-you/
Source tier: primary
Source content: "Ayoze García González National leader, Spain, PauseAI" (Pro-Human AI Declaration signatory roster, March 2026).
Comparison: The role is confirmed by one canonical source (a signatory roster carrying his self-attested title), consistent with his authorship of PauseAI España protest updates on change.org ("PauseAI En Español apoya esta iniciativa", March 2026 Madrid protest update from Las Palmas de Gran Canaria). The cited pauseai.info/about roster cannot be re-verified: its National Leaders section is JS-loaded and renders empty on fetch.
Decision: single-source

## Claim 6: "No founding date is stated on the website or the Substack"

Source: https://pauseai.es + https://pauseaispanish.substack.com
Source tier: primary
Source content: Homepage: "Founding Date: Not provided on this page." Substack: "No founding date is provided."
Comparison: Absence claim verified directly against both named properties; neither carries a founding date.
Decision: primary-sourced

## Claim 7: The chapter "describes its membership as including 'workers and experts in AI, computing, neuroscience, communication, and teaching'"

Source: https://pauseai.es/nosotros
Source tier: primary
Source content: "trabajadores y expertos en los sectores de la IA, la informática, la neurociencia, la comunicación y la docencia"
Comparison: Body's English rendering matches the live Spanish sentence field-for-field (AI, informatics/computing, neuroscience, communication, teaching/docencia).
Decision: primary-sourced

## Claim 8: "The website notes content was developed as 'local adaptation and translation' of the international PauseAI site"

Source: https://pauseai.es
Source tier: primary
Source content: "Esta versión en español añade adaptación y traducción locales" and "Basado en el contenido de PauseAI.info" (CC BY 4.0).
Comparison: Direct match on the live homepage.
Decision: primary-sourced

## Claim 9: "The chapter frames this alongside pandemic prevention and nuclear disarmament as equivalent global-priority existential-risk reduction work"

Source: https://pauseai.es
Source tier: primary
Source content: "Mitigar el riesgo de extinción de la IA debe ser una prioridad global junto con otros riesgos a escala social como las pandemias y la guerra nuclear"
Comparison: Live homepage carries the pandemics-and-nuclear-war global-priority framing verbatim (the CAIS-statement formulation).
Decision: primary-sourced

## Claim 10: "PauseAI Spain's central demand is a pause on the development of advanced AI systems beyond GPT-4 capability — specifically AI that 'possesses autonomy and agency'"

Source: https://pauseai.es + https://pauseai.es/propuesta
Source tier: primary
Source content: The only GPT-4/autonomy-agency text on the live homepage is a quoted endorsement attributed to Yoshua Bengio: "Prohibir los sistemas de IA poderosos (digamos más allá de las capacidades de GPT-4) que se les da autonomía y agencia sería un buen comienzo." The live central demand reads: "Detener el desarrollo de los sistemas de IA general más potentes hasta que sepamos cómo hacerlos seguros." /propuesta contains no autonomy/agency language.
Comparison: On the live site the GPT-4/autonomy-agency formulation is Bengio's quoted remark displayed by the chapter, not the chapter's own stated central demand — the body may have lifted a displayed endorsement quote as the platform. Whether the June 2026 site framed it differently cannot be checked (archive blocked), so this is a source-conflict/drift edge, not an assertable token error. Flagged for attention at any Researcher revisit: if the live site is representative, this sentence misattributes a Bengio quote as the chapter's demand.
Decision: uncorroborated

## Claim 11: The chapter's central call: "do not allow AI companies to play with our future"

Source: https://pauseai.es
Source tier: none
Source content: "Phrase 'jueguen con nuestro futuro': Not found on the page." Search still indexes the phrase against pauseai.es and the @pauseai_es X profile, but no live fetchable page carries it.
Comparison: The quoted call is not on the live homepage or /propuesta; search-index residue suggests it existed at draft time (or lives in the X bio, which is not directly fetchable). Cannot be confirmed against a canonical source today.
Decision: uncorroborated

## Claim 12: "The platform follows PauseAI Global's treaty-backed pause proposal without articulating Spain-specific demands"

Source: https://pauseai.es/propuesta
Source tier: primary
Source content: "El objetivo principal de estas cumbres debería ser un tratado"; page is a Spanish rendering of the international proposal (international AI safety agency modeled on the IAEA; "La participación de Estados Unidos y China es crucial"); no Spain-specific demands appear.
Comparison: The chapter's proposal page tracks the global proposal with no Spain-framed conditions, matching the body. (The comparative clause about Serbia/Germany formulations is corpus-internal characterization, not audited.)
Decision: primary-sourced

## Claim 13: Channels — "X / Twitter (@pauseai_es), YouTube (@pauseai-es), a Substack newsletter (PauseAI en español), Discord, WhatsApp, and Spotify. Contact is via contacto@pauseai.es"

Source: https://pauseai.es
Source tier: primary
Source content: "Email: contacto@pauseai.es; Platforms: X, YouTube, Substack, Discord, WhatsApp, Spotify, Instagram, TikTok, LinkedIn". X handle confirmed via search-index title "PauseAI en Español ⏸️ (@pauseai_es) on X".
Comparison: All six named channels plus the contact address are live on the homepage; the channel set has since grown (Instagram, TikTok, LinkedIn added) — additive drift, not an error. YouTube handle spelling not independently re-verified.
Decision: primary-sourced

## Claim 14: Substack self-description — "from Spain and Hispanic America, we join the international PauseAI initiative"

Source: https://pauseaispanish.substack.com
Source tier: primary
Source content: "Desde España e Hispanoamérica, nos sumamos a la iniciativa de la organización internacional PauseAI para pausar el desarrollo de la IA avanzada."
Comparison: Verbatim match, publication name "PauseAI en español" confirmed.
Decision: primary-sourced

## Claim 15: "No Spanish-language protest events appeared on PauseAI Global's documented protest history at draft time; the chapter does not appear in the May 2024 thirteen-country international wave or the February 2025 Paris AI Action Summit wave"

Source: https://pauseai.info/protests + https://en.wikipedia.org/wiki/PauseAI
Source tier: primary
Source content: Protests page: no Spain/Madrid/Spanish-speaking-country entries anywhere; "13th of May [2024], San Francisco, London, Stockholm, Berlin, Den Haag, Rome, Paris…"; "7th - 11th of February [2025], 15+ cities". Wikipedia: May 13, 2024 demonstrations "across thirteen countries"; Spain not mentioned.
Comparison: Absence holds on the live protests page and in Wikipedia's account; the thirteen-country figure for May 2024 is confirmed. (A Madrid "Stop The AI Race" protest occurred 21–22 March 2026 per the chapter's change.org update — it postdates the draft and is not on the protests page, so the "at draft time" scoping stands.)
Decision: corroborated

## Claim 16: scalar:sources[0].note — communities directory "lists España as a national chapter with a dedicated national website ... alongside Czechia, Germany, France, Serbia, Sweden, Australia, Canada, UK, and US"

Source: https://pauseai.info/communities
Source tier: primary
Source content: Live own-domain national communities: Canada, Czechia, France, Germany, Serbia, Spain, Sweden, UK. Australia is a pauseai.info directory page; US is not in the own-domain list; Italy is WhatsApp-only; Poland mailto-only.
Comparison: Scalar path sources[0].note. The España-with-pauseai.es core is confirmed live, but the companion roster (Australia, US as national-website chapters) no longer matches the directory, and the 2026-06-09 state cannot be checked. Dated source note overtaken by directory drift.
Decision: uncorroborated

## Claim 17: scalar:sources[1].note — About page "names Ayoze García González as national director of PauseAI Spain alongside ... other national-chapter leads" (15-name roster)

Source: https://pauseai.info/about
Source tier: none
Source content: The About page's National Leaders section is JS-loaded and renders empty on fetch; the roster is also absent from the site's GitHub markdown. No fetchable source carries the 15-name roster; known drift since June: Maxime Fournes took the international directorship at the end of 2025 (per pauseai.es/nosotros), and PauseAI Serbia/other chapter rosters have shifted.
Comparison: Scalar path sources[1].note. The Ayoze-specific fact is separately supported (Claim 5); the full 15-lead roster as quoted cannot be re-verified against any fetchable canonical source.
Decision: uncorroborated

## Claim 18: scalar:sources[2].note — pauseai.es homepage summary (pan-Hispanic self-description; "not allow AI companies to play with our future"; pandemic/nuclear framing; "prohibits AI systems beyond GPT-4 capability that possess autonomy and agency"; channels; contact; adaptation note; CC BY 4.0)

Source: https://pauseai.es
Source tier: primary
Source content: Confirmed live: pandemic/nuclear framing (Claim 9), channels + contact (Claim 13), adaptation note "Esta versión en español añade adaptación y traducción locales", "Licencia: CC BY 4.0". Not confirmed live: the "play with our future" call (Claim 11); the GPT-4/autonomy-agency text appears only as a Yoshua Bengio quote (Claim 10); the pan-Hispanic phrase now lives on /nosotros, not the homepage.
Comparison: Scalar path sources[2].note. A dated composite note: majority of elements verify against the live page; the prohibition framing and central-call phrase do not, per Claims 10–11. Mixed state resolves to the audit's limit, not to an assertable error.
Decision: uncorroborated
