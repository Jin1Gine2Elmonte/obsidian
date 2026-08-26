# Temporal Event Types

The archive distinguishes three histories that can share a date but are not the same event.

## 1. WORLD EVENT
An event inside a fictional world.

Examples:
- Arisa's death.
- A character leaving the capital.
- A war, coronation, rupture, or world transition.

World events require world-time when known.

## 2. PROJECT EVENT
A change in the creative artifact itself.

Examples:
- replacing one Jin version with another;
- changing a character's name;
- rewriting the imperial branch;
- moving a concept into a different project generation.

Project events require project-generation context.

## 3. KNOWLEDGE EVENT
A change in what the archive knows or believes.

Examples:
- discovering a contradiction;
- correcting a previous summary;
- promoting a working interpretation to canon;
- marking a claim unsupported;
- merging or retiring a duplicate node.

Knowledge events require source/archive-time context.

The detailed knowledge-event ledger is `KNOWLEDGE_EVENTS.md`. State-transition semantics are owned by `KNOWLEDGE_STATE_TRANSITIONS.md`.

## Event identity
An event record should never be identified only by a date. Its identity is the tuple:

`event_class + source_context + project/version + world_context + affected_entities`

This prevents a later conversation discussing an older fictional event from being misread as a new world event.

## Why this matters
One conversation can describe an old world event while simultaneously creating a new project state and a new archival interpretation. These must not collapse into one timestamp.

## Event record minimum
When evidence permits, record:
- event class;
- archive/source time;
- project generation;
- world time;
- entities affected;
- predecessor state;
- successor state;
- evidence;
- confidence/canon state;
- downstream nodes requiring propagation;
- knowledge-event id when the event changes archival understanding.

## Jin / Almont / Ryota safety
A statement made today about a childhood event may refer to an older project generation. Do not use conversation date to place the childhood event after a later project rewrite.

## Preservation rule
When a new source changes the interpretation of an old event, preserve the old interpretation as historical knowledge and create an explicit knowledge-state transition. Do not rewrite the event's world-time merely because the archive's understanding changed.

## Related temporal owners
- `TEMPORAL_MODEL.md` — separates conversation, project, and fictional/world clocks.
- `TIMELINE.md` — broad reconstructed chronology and temporal evidence labels.
- `PROJECT_STATE_TRANSITIONS.md` — project-generation changes.
- `KNOWLEDGE_EVENTS.md` — chronological knowledge-event ledger.
- `KNOWLEDGE_STATE_TRANSITIONS.md` — epistemic state transitions and propagation requirements.
