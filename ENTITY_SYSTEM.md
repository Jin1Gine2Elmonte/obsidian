# Entity System

This vault should evolve from document storage into an entity-oriented knowledge graph expressed in Markdown.

## Entity classes

### Person / Character
Fields:
- canonical name
- aliases
- role
- project/world
- relationships
- motivations
- contradictions
- history
- unresolved questions
- source notes
- confidence

### Concept
Fields:
- canonical term
- aliases
- definition
- implications
- parent concepts
- child concepts
- related projects
- tensions / contradictions
- origin
- status

### Project
Fields:
- canonical name
- purpose
- current state
- history
- goals
- constraints
- architecture
- dependencies
- decisions
- open loops

### System
Fields:
- purpose
- inputs
- transformations
- outputs
- dependencies
- failure modes
- current implementation
- desired future architecture

### Decision
Fields:
- decision
- date/context
- alternatives
- reason
- consequence
- reversibility
- current status

### Event
Fields:
- date or approximate period
- actors
- what happened
- consequences
- source
- confidence

## Entity quality rules
1. Never silently merge two entities because their names look similar.
2. Preserve aliases.
3. Record uncertainty explicitly.
4. Keep historical states when they explain evolution.
5. Prefer links between entities over repeating the same paragraph in many places.
6. Promote recurring concepts to first-class entities.

## Obsidian linking convention
Use `[[Canonical Name]]` for internal links whenever the target note exists. Use aliases when useful for human readability, but keep a single canonical node for each entity.

## Metadata direction
Future notes can use YAML frontmatter such as:

```yaml
type: concept
status: active
confidence: high
first_seen: 2026-08-17
updated: 2026-08-17
aliases: []
related: []
source: conversation-summary
```

The exact schema should evolve from actual use rather than becoming a rigid bureaucracy.
