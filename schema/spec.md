---
type: spec
last_updated: 2026-05-12
---

# Schema Spec

Defines entity types, frontmatter fields, and cross-reference rules.

Two layers, treated differently:

- **Entity types are locked.** Adding a new type is a deliberate schema change.
- **Vocabularies are emergent.** Tags start empty and grow from observed usage. Consolidation happens when patterns stabilize.

## Entity types

Ten types. Each lives in `product/entities/<type>/<id>.md` with YAML frontmatter and Markdown body.

- **Organization** — national or regional groups doing grassroots organizing or AI-good advocacy
- **Local Group** — smaller, city- or region-scoped, often informal
- **Campaign** — sustained, named effort with goals, tactics, and a time-arc
- **Event** — specific moment in time (action, protest, hearing, conference, launch)
- **Strategy** — high-level approach to AI-good organizing. *Defined but not currently populated — do not draft Strategy entries yet.*
- **Message** — memes, framings, slogans, narrative artifacts that propagate
- **Funder** — foundations, donors, grant programs
- **Person** — connector type; lightweight; records affiliations. Body is short and factual; no biographical synthesis. See "Person / Voice" below.
- **Voice** — content type; richer entries for individuals whose public output the corpus tracks. See "Person / Voice" below.
- **Publication** — substantive works (books, reports, manifestos, foundational essays, ongoing newsletters)

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

*Defined but not currently populated — do not draft Strategy entries yet.*

```yaml
parent_strategy: <strategy ID, optional>
practiced_by_orgs: [<org IDs>]
example_campaigns: [<campaign IDs>]
```

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

## Sourcing

**Person entries:** every affiliation needs a publicly verifiable source. `confidence: low` Person entries are not created — if it can't be sourced, it doesn't go in. Affiliations from secondhand reporting need a `note` on the source explaining context.

**Other entities:** every non-obvious factual claim in the body needs an inline source link.

## Vocabularies

`tags` is freeform — the vocabulary is emergent. Vocabulary files start empty in `product/schema/vocabularies/` and grow from observed usage. When a tag stabilizes (typically used in 5+ entities), it's promoted into a vocabulary file with a definition.

The `role` field on Person affiliations is also a candidate for an emergent vocabulary.
