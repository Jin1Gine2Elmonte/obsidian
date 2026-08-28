# Memory Schema

The vault should eventually treat knowledge as typed objects rather than undifferentiated notes.

## Governance boundary
This file describes a structural/implementation schema for typed memory objects. It does **not** define a second epistemic status or certainty system. Current epistemic status, provenance, confidence, contradiction, and supersession definitions are owned exclusively by `CANON_AND_PROVENANCE.md`.

If this schema is implemented in frontmatter or tooling, map its fields to the canonical governance vocabulary rather than creating parallel meanings for `certainty` or `status`.

## Entity types
- Person / character
- Project
- World
- Location
- Concept
- System
- Technology
- Decision
- Event
- Conversation
- Artifact
- Relationship
- Question
- Hypothesis
- Lesson

## Suggested frontmatter

```yaml
type: concept
epistemic_status: UNKNOWN
confidence: low
created: YYYY-MM-DD
updated: YYYY-MM-DD
source: conversation
anchors:
  - anchor-id
related:
  - other-id
supersedes: null
superseded_by: null
```

`epistemic_status` should use the canonical governance classes:
- `CANONICAL`
- `STRONGLY_SUPPORTED`
- `WORKING`
- `DERIVED`
- `SPECULATIVE`
- `HISTORICAL / SUPERSEDED`
- `UNKNOWN`

`confidence` is an evidence-quality signal and should use the canonical suggested levels: `high`, `medium`, or `low`.

For current provenance and the meaning of these classes, see `CANON_AND_PROVENANCE.md` rather than maintaining local definitions here.

## Operational state
A consuming system may still need a separate lifecycle field such as `active`, `historical`, `retired`, `blocked`, or `experimental`. Such operational state is not an epistemic status and must not be interpreted as one.

## Relationship types
Prefer explicit semantic edges:
- inspired-by
- depends-on
- contradicts
- supersedes
- caused-by
- causes
- contains
- belongs-to
- related-to
- influences
- instantiated-by
- implemented-by
- depicts
- references
- derived-from

## Why types matter
Typed notes make the vault useful to future AI retrieval systems. A future MCP layer can retrieve not only a matching note but also the graph neighborhood around the note.

## Graph neighborhood principle
When retrieving a major anchor, return enough adjacent context to answer:
1. What is it?
2. Why does it matter?
3. What does it connect to?
4. What decisions depend on it?
5. What changed over time?
6. Which parts are certain versus speculative?

## Canonical governance link
`CANON_AND_PROVENANCE.md` is the single source of truth for epistemic status, provenance, confidence, contradiction, and supersession. This schema must remain subordinate to that owner.
