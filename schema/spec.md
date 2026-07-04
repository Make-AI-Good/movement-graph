---
type: spec
last_updated: 2026-07-03
---

# Schema Spec

Defines entity types, frontmatter fields, and cross-reference rules.

Two layers, treated differently:

- **Entity types are locked.** Adding a new type is a deliberate schema change.
- **Vocabularies are emergent.** Tags start empty and grow from observed usage. Consolidation happens when patterns stabilize.

## Entity types

Ten types. Each lives in `product/entities/<type>/<id>.md` with YAML frontmatter and Markdown body.

- **Organization** — national or regional groups doing grassroots organizing or AI-good advocacy. National scale makes a group an Organization regardless of its organizational character — a national member-led or worker-led collective is an Organization, not a Local Group (ratified 2026-06-10).
- **Local Group** — true local groups: city- or sub-regional scope, often informal. Scope is the discriminator against Organization; member-led character does not keep a national-scale group in this type.
- **Campaign** — sustained, named effort with goals, tactics, and a time-arc
- **Event** — specific moment in time (action, protest, hearing, conference, launch)
- **Strategy** — the Analyst's layer: a named approach the movement uses (or could use) to pursue its aims, true by its form (naming needs no evidence); evidence enters only when evaluating a strategy as good vs. bad (see `../../agents/analyst/ANALYST.md`)
- **Message** — memes, framings, slogans, narrative artifacts that propagate
- **Funder** — foundations, donors, grant programs
- **Person** — connector type; lightweight; records affiliations. Body is short and factual; no biographical synthesis. See "Person / Voice" below.
- **Voice** — content type; richer entries for individuals whose public output the corpus tracks. See "Person / Voice" below.
- **Publication** — substantive works (books, reports, manifestos, foundational essays, ongoing newsletters)

## Frontmatter syntax — strict YAML 1.2

Every entity's frontmatter MUST parse with a stock YAML 1.2 library (PyYAML, js-yaml, `yq`, etc.). The schema is the published product's data contract; downstream consumers may use any conforming parser, and producers do not assume consumer-side tolerance.

The most common strict-mode failure: unquoted scalar values containing colon-space (`: `) — typically a `sources[].note` of the form `Title: Subtitle`. YAML 1.2 parses this as a nested mapping, not a string. Single-quote the whole scalar. Other YAML-indicator characters at the start of a scalar (`*` `&` `!` `|` `>` `%` `?` `,` `[` `]` `{` `}` `#`) require the same quoting. The Editor's `Frontmatter validity` and `Frontmatter prose-quoting repair` acts enforce this mechanically.

## Common frontmatter

Every entity has these:

```yaml
id: <type-prefix>-<slug>
type: <one of the ten types>
name: <display name>
status: active | inactive | historical | unverified
confidence: high | medium | low
tags: [<freeform vocabulary>]
created: <ISO date>
last_updated: <ISO date>
sources:
  - url: <source URL>
    last_checked: <ISO date>
    note: <optional context>
```

Date precision: `YYYY-MM-DD`, `YYYY-MM`, or `YYYY`. Use the highest precision the source record supports. Don't invent precision the source doesn't back.

## Type-specific frontmatter

### Organization
```yaml
founded: <year>
location: <city, region, "national", or "international">
website: <url>
strategies: [<strategy IDs>]
key_people: [<person IDs>]
board_and_advisors: [<person IDs>]
related_orgs: [<org IDs>]
funders: [<funder IDs>]
```

### Local Group
```yaml
founded: <year, optional>
location: <city, region>
parent_org: <org ID, optional>
website_or_contact: <url or contact>
key_people: [<person IDs>, optional]
```

### Campaign
```yaml
start_date: <ISO date>
end_date: <ISO date or "ongoing">
goals: <short prose>
lead_orgs: [<org IDs>]
participating_orgs: [<org IDs>]
events: [<event IDs>]
strategies: [<strategy IDs>]
outcomes: <short prose, optional>
```

### Event
```yaml
date: <ISO date>
location: <city or "online">
event_type: <freeform tag, e.g. "protest", "hearing", "conference">
campaign: <campaign ID, optional>
participating_orgs: [<org IDs>]
participating_people: [<person IDs>, optional]
related_events: [<event IDs>]
```

### Strategy

The Analyst's layer: a named **strategy** the movement uses (or could use) to pursue its aims, plus — where the Analyst has done the work — a judgment of how well it works. A strategy is **true by its form, not by evidence**: naming one requires no sourcing. What requires evidence is the *evaluation* of a strategy as good or bad. Authored only by the Analyst.

A strategy is **born as a sharp claim, not an essay** — an org-agnostic name carrying most of the meaning, plus a few sentences (what the approach is, why an actor would choose it, what it trades off). It accretes the fields below only as depth work earns them; a strategy with none of them is a complete, valid entity.

```yaml
parent_strategy: <strategy ID, optional>     # this strategy is a move inside a larger one
related_strategies: [<strategy IDs>]          # strategies this one reinforces, feeds, or conflicts with (the ecology)
effects:                                       # OPTIONAL depth layer — real-world effects, each a sourced FACT; causal attribution to the strategy is labeled inference
  - description: <prose — the effect, stated as fact>
    type: earned-media | legislation-draft | legislation-enacted | regulatory-action | judicial-outcome | corporate-behavior-change | coalition-adoption | public-mobilization
    source: <source URL>
    attribution_confidence: high | medium | low   # confidence that THIS strategy produced the effect (judgment, not fact)
counter_read: <prose, optional — the strongest opposing reading of the strategy's effectiveness>
```

The common `confidence` field, when present, carries the Analyst's confidence in its *evaluation* of the strategy (not in its existence).

**Rigor lives at the edges, not in body prose.** Strategy is a connective type: its substance is edge-anchored — its adopters (reverse-inferred from `org.strategies[]` / `campaign.strategies[]`), its `effects[]` (sourced facts with per-attribution confidence), its ecology (`parent_strategy`, `related_strategies`, `counter_read`). Sourcing and factual claims belong on these edges; the common `sources[]` field is typically empty on Strategy entities because whole-body sourcing has no anchor. A long body essaying the strategy is a register defect, not a depth signal — depth accretes at the edges.

**Connections carry the observed/unobserved signal:** a strategy linked to adopters via `org.strategies[]` / `campaign.strategies[]` (canonical side — see Cross-references) is one seen employed in the movement; a strategy with no connections is one not yet seen adopted — a valid entity and a signal for gap-analysis, not a defect. The Analyst may connect a strategy to an adopter on the strength of its own pattern-recognition, even where no source draws the line.

**Body register:** the body names the approach and its trade-offs crisply; it does not catalogue adopters (they live in the connections) or narrate effects (they live in `effects[]`). Where evaluative depth work does write body prose (a verdict, an ecology discussion), it keeps what is *observed fact* distinct from what is the Analyst's *reading* — a reader is never invited to mistake a judgment for a fact, but the reading itself needs no source. `related_strategies` is Analyst-maintained and exempt from the Editor's reciprocal / canonical-direction cleanup.

### Message
```yaml
origin: <prose — where did this come from, when>
originating_person: <person ID, optional>
originating_org: <org ID, optional>
propagated_by_orgs: [<org IDs>]
related_messages: [<message IDs>]
```

### Funder
```yaml
funder_type: foundation | individual-donor | grant-program | other
website: <url, optional>
funded_orgs: [<org IDs>]
focus: <short prose — what kinds of work they fund>
```

### Person
*Lightweight by design.*
```yaml
affiliations:
  - org: <org ID>
    role: <freeform string, e.g. "executive director", "co-founder", "advisor">
    period: <year-year, year-, or date range, optional>
public_profiles:
  - platform: <e.g. personal-site, linkedin, substack>
    url: <url>
voice_entry: <voice ID, optional>
```

### Voice
```yaml
person_entry: <person ID, optional>
notable_for: <short prose>
public_profiles:
  - platform: <e.g. twitter, substack, personal>
    url: <url>
recent_works: [<publication IDs>, optional]
```

### Publication
```yaml
authors: [<person IDs or voice IDs>]
publisher: <string or org ID>
date: <ISO date>
url: <url>
publication_type: book | report | manifesto | essay | newsletter | other
```

## ID conventions

- Lowercase, hyphenated
- Prefixed by type: `org-`, `lg-`, `camp-`, `event-`, `strat-`, `msg-`, `fund-`, `person-`, `voice-`, `pub-`
- Stable for the lifetime of the entity — renames update display name, not ID
- Slug derived from canonical name. For persons and voices: `firstname-lastname`. For orgs: common short name.

## Cross-references

References are ID strings in frontmatter fields. The build step infers reverse links from the canonical direction. For most pairs, store the reference on only one side; see "Canonical cross-reference direction" below for which side stores which pair, and for the symmetric pairs that require both sides.

Referenced IDs must point to existing entity files of the correct type.

## Canonical cross-reference direction

When the schema allows the same relationship to be stored on either of two entity types, the canonical side below is the one that should be populated. The build infers the reverse-link. **The non-canonical side must stay empty.** If both sides are populated, the canonical side is authoritative; the non-canonical side should be cleared. The Editor performs this cleanup mechanically, ensuring no data loss — entries are first reflected on the canonical side, then removed from the non-canonical side. Symmetric pairs are the exception: both sides must be populated.

The Editor's reciprocal cross-reference resolution uses this table to decide where to write. Its canonical-direction cleanup uses the same table to decide what to clear.

| Relationship | Canonical side | Reason |
|---|---|---|
| Org ↔ Funder | `org.funders[]` | Funding is a load-bearing org fact |
| Org ↔ Org (related) | **both sides** | Symmetric — both must list each other |
| Org ↔ Strategy | `org.strategies[]` | Shorter and more meaningful from the org side |
| Campaign ↔ Event | **both sides** | `event.campaign` (singular) and `campaign.events[]` (list) — both required |
| Campaign ↔ Strategy | `campaign.strategies[]` | Shorter from campaign side |
| Event ↔ Event (related) | **both sides** | Symmetric |
| Person ↔ Voice | **both sides** | Bidirectional pointer; both required when the pair exists |

Other cross-reference fields in the schema are one-way — the field exists on only one side and the reverse is build-inferred. No canonical-direction decision required for those.

**Note on `org.key_people` and `person.affiliations`:** these are NOT a canonical-direction pair, despite both being cross-reference fields between Org and Person. They track different relationships — `person.affiliations[]` records a person's full employment history with structured role/period fields; `org.key_people[]` is a curated short list of an org's most notable people. Neither is a denormalization of the other. The Editor does not apply reciprocal cross-reference resolution or canonical-direction cleanup between them; populating each is Researcher judgment.

## Person / Voice interaction

Most people are Persons, never Voices. Voices are a deliberate subset for individuals whose public words and influence the corpus actively tracks.

When recording a person who's also a Voice:

1. Create or update the Person entry with affiliations.
2. Create the Voice entry with `person_entry` pointing to the Person.
3. Update the Person's `voice_entry` to point back to the Voice.

Promotion to Voice is a deliberate decision — typically when public output is itself worth tracking, not just an org affiliation.

**Body-link target convention.** When a body in any entity names an individual who has both a Person and a Voice entry, body links target the Person entry (e.g., `[Joy Buolamwini](../persons/person-joy-buolamwini.md)`). The Voice entry remains reachable via the Person entry's `voice_entry` pointer (build-inferred reverse link). Rationale: Person entries are the canonical connector type, guaranteed to exist whenever a Voice exists; targeting Person gives the Editor's body-link acts an unambiguous mechanical rule and matches majority corpus practice (counted 2026-05-19: ~99 person-side vs ~43 voice-side body links across the 12 individuals with both entries). This convention applies to all three Editor body-link acts (insertion, repair, target replacement); the prior skip-on-Person/Voice-ambiguity case is now an act-not-skip case. **Target rule is keyed on the referenced individual, not the display-text shape.** Whether the display text is the person's name (`[Apar Gupta](...)`), the entity ID (`[voice-apar-gupta](...)`), or a role/title, the *target* is determined by who the link references — if both Person and Voice exist for that individual, the target is the Person entry. The display text is the Researcher's prose choice and is not changed by this rule.

## Body shape

Every entity body begins with an H1 of the entity's display name — `# <name>`, matching the frontmatter `name:` field — as the first non-empty line after the frontmatter. (Ratified at the V3 Define meeting 2026-07-03, codifying the convention the corpus had settled on organically; the historical backlog is drained by the Editor's body-H1-insertion act.)

## Sourcing

**Person entries:** every affiliation needs a publicly verifiable source. `confidence: low` Person entries are not created — if it can't be sourced, it doesn't go in. Affiliations from secondhand reporting need a `note` on the source explaining context.

**Other entities:** every non-obvious factual claim in the body needs an inline source link.

## Vocabularies

`tags` is freeform — the vocabulary is emergent. Vocabulary files start empty in `product/schema/vocabularies/` and grow from observed usage. When a tag stabilizes (typically used in 5+ entities), it's promoted into a vocabulary file with a definition.

The `role` field on Person affiliations is also a candidate for an emergent vocabulary.
