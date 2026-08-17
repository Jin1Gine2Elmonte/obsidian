# Memory Operations Manual

## Purpose
Define how this vault should behave when used by a future AI system as external persistent memory.

## Read order
1. INDEX.md
2. MEMORY.md
3. ANCHOR_GRAPH.md
4. relevant domain file
5. source/provenance notes
6. unresolved questions

Never begin by reading every file indiscriminately when a targeted retrieval is possible.

## Retrieval stages
### Stage A — Orientation
Identify the current project, task, characters, systems, or question.

### Stage B — Anchor retrieval
Find the strongest anchor nodes connected to the task.

### Stage C — Context expansion
Follow relationships outward only as far as needed. Prefer adjacent nodes over unrelated archives.

### Stage D — Temporal check
Determine whether the retrieved information is current, historical, superseded, speculative, or unresolved.

### Stage E — Conflict check
When two records disagree, do not silently merge them. Preserve both and mark the conflict until a later decision resolves it.

### Stage F — Synthesis
Produce the answer from the most recent trustworthy state while preserving important historical context.

## Write operations
A new memory should first be classified as one of:
- fact
- preference
- decision
- observation
- experiment
- hypothesis
- canon
- draft canon
- open question
- historical state

Then it should be attached to the relevant anchor(s).

## Promotion rule
A note begins as local context. Promote it to a standalone anchor when it:
- recurs across conversations;
- generates multiple related concepts;
- changes several projects;
- becomes a constraint on future work;
- or represents a major worldbuilding/cosmological principle.

## Compression rule
Summarize repeated material only when meaning survives compression. Keep distinctive examples when they reveal the user's reasoning pattern or a project's internal logic.

## Anti-fabrication rule
Never create a memory merely because it would be convenient. Missing information remains missing.

## Historical preservation
When a belief, project design, or technical architecture changes, preserve the old state when its evolution matters. Record the new state rather than erasing history.

## User corrections
A direct correction from the user has priority over an older summary. Preserve the old value as superseded history when useful.

## Creative canon rule
A fictional statement should not become canon merely because it appeared once. Canon strength increases through explicit confirmation, repeated use, integration with other established facts, or explicit designation by the user.
