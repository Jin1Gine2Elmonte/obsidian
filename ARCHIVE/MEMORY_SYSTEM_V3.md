# Memory System V3

## Objective
Create a durable, model-independent knowledge system that can preserve the user's long-term creative and technical continuity across AI providers, applications, and time.

## Memory is not one thing
The archive should maintain distinct layers:
- **Identity:** stable working preferences, creative orientation, reasoning architecture.
- **Semantic memory:** durable facts, concepts, definitions, world rules, technical architecture.
- **Episodic memory:** events, conversations, experiments, turning points, failures, discoveries.
- **Procedural memory:** how the user prefers tasks performed and how recurring workflows operate.
- **Project state:** current status, next actions, blockers, decisions, and dependencies.
- **Relational memory:** links among concepts, projects, people/characters, tools, and decisions.
- **Evidence:** source material from transcripts, files, code, screenshots, URLs, and explicit user statements.

## Memory lifecycle
Capture -> normalize -> classify -> deduplicate -> link -> validate -> index -> retrieve -> apply -> revise -> preserve history.

Never let a summary silently destroy an older state. When a statement changes, preserve the previous state when historically useful and record the new one with a date/status.

## Confidence model
- `confirmed`: directly stated or directly observed.
- `supported`: strongly supported by multiple context signals.
- `inferred`: reasonable synthesis, not directly stated.
- `speculative`: creative hypothesis or unresolved possibility.
- `unknown`: genuinely unavailable.

AI systems consuming the archive should never silently convert `inferred`, `speculative`, or `unknown` into `confirmed`.

## Retrieval model
A useful retrieval pass should consider:
1. Direct keyword relevance.
2. Semantic similarity.
3. Anchor-node relevance.
4. Project relevance.
5. Temporal relevance.
6. Contradiction/conflict risk.
7. Source confidence.
8. User-stated priority.

The best context is not necessarily the largest context. It is the smallest coherent set that preserves the meaning and constraints of the current task.

## Context assembly
Before answering a complex request, construct a context packet from:
- active project
- relevant anchors
- current state
- recent decisions
- historical constraints
- unresolved questions
- source evidence
- known contradictions

## Anti-corruption rules
- Do not invent missing history.
- Do not merge two similarly named concepts unless their identity is proven.
- Do not flatten separate project generations into one.
- Do not overwrite old decisions without recording the change.
- Do not treat an assistant inference as user canon.
- Do not assume that a repeated statement is still current if later context contradicts it.
- Preserve the exact wording of high-value user decisions when possible.

## Knowledge graph principle
The vault should evolve from files into a graph. A concept that repeatedly connects multiple areas becomes a first-class node. Relationships should answer questions such as `depends_on`, `contradicts`, `derived_from`, `inspires`, `implements`, `replaces`, `belongs_to`, `character_in`, `part_of_world`, and `historically_precedes`.

## Long-term goal
The model should be replaceable. The user's accumulated knowledge should not be.
