# Archive Protocol

This document defines how the external memory should grow, be corrected, compacted, and maintained over time.

## Core law
**Review before expansion.** The vault is not a landfill for progressively longer summaries. Every substantial change must first inspect the closest existing node and determine whether the correct operation is update, merge, supersede, delete, or create.

## Status labels
Use explicit epistemic status where appropriate:
- `CANON`: directly established by the user or confirmed project source.
- `CURRENT`: latest known state, potentially replaceable.
- `HISTORICAL`: true of an earlier phase.
- `INFERRED`: supported by context but not directly established.
- `SPECULATIVE`: creative possibility, not canon.
- `RETIRED`: intentionally abandoned.
- `UNKNOWN`: insufficient information.

## Provenance
Whenever practical, each important note should record where it came from:
- direct user statement
- conversation summary
- supplied artifact
- repository file/commit
- technical experiment
- model inference

Do not transform an inference into a fact merely because it appears repeatedly in summaries.

## Temporal rule
Projects evolve. A later decision should not erase the fact that an earlier architecture, idea, or interpretation existed. Preserve historical evolution when it explains the current state.

## Correction rule
When a later user statement explicitly corrects an earlier record, update the relevant authoritative node. Preserve the superseded version only when it is useful for understanding history or avoiding repetition of a known mistake.

## Duplicate rule
If two notes contain substantially the same conceptual role:
1. identify the more authoritative node;
2. merge unique information into it;
3. update references;
4. delete or mark the duplicate as superseded.

Do not keep V1/V2 documents alive merely because both exist.

## Anchor promotion
Promote a concept into an anchor when it:
1. recurs across conversations;
2. generates dependent concepts;
3. affects important decisions;
4. bridges separate projects;
5. has enough internal structure to justify its own node.

## Relationship rule
When two notes repeatedly influence one another, create an explicit semantic relationship instead of relying on keyword overlap.

## Contradiction rule
If two records conflict:
1. preserve both;
2. check dates and project generation;
3. determine whether one superseded the other;
4. mark unresolved contradictions explicitly;
5. never silently harmonize incompatible canon.

## Memory compaction
Summaries may compress repetition, but they must preserve meaning, uncertainty, causality, chronology, constraints, exceptions, and why the information matters. A shorter document is not automatically a better memory.

## Evidence versus synthesis
Raw transcripts, supplied artifacts, and direct statements are evidence. Domain summaries, graphs, interpretations, and cross-project models are synthesis. Never let synthesis masquerade as raw evidence.

## Conversation import
Use the canonical `CONVERSATION_ARCHIVE_SPEC_V2.md`. Keep raw transcripts separate from distilled memory. When transcripts are unavailable, do not fabricate them from memory.

## Quality gate for new additions
A new change should provide at least one genuine value delta:
- new fact
- new entity
- new relationship
- state change
- decision and rationale
- rejected alternative
- constraint
- evidence
- consequence
- resolved contradiction
- meaningful open question
- operational capability

Pure paraphrase, decorative wording, or increased file count is not a value delta.

## Update cycle
For a substantial update:
1. inspect the existing authoritative node;
2. compare current versus proposed state;
3. correct stale/inaccurate material;
4. merge non-duplicative information;
5. update affected relationships;
6. preserve historical transitions where useful;
7. update index/census if structure changed;
8. commit the change with a meaningful message.

## Retrieval principle
Retrieve the smallest coherent neighborhood capable of answering the current task, then expand only where relationships or historical context require it. The objective is maximum useful coherence per token.
