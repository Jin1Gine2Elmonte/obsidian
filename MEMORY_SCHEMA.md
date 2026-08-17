# Memory Schema

The vault should eventually treat knowledge as typed objects rather than undifferentiated notes.

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
status: current
certainty: canon
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

## Certainty
Use `canon`, `inferred`, `speculative`, `historical`, or `unknown`.

## Status
Use `active`, `current`, `historical`, `retired`, `blocked`, `experimental`, or `unknown`.

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
