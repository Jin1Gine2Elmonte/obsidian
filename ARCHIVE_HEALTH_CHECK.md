# Archive Health Check

## Purpose
A compact validation surface for the external-memory system. This file does not own project facts; it records structural health criteria and the current known risks.

## Integrity dimensions

### 1. Ownership
Every important knowledge type should have one clear canonical owner.

Primary reference: `KNOWLEDGE_OWNERSHIP_MAP.md`.

### 2. Provenance
Important claims should indicate whether they come from direct user evidence, recovered source material, repository state, synthesis, inference, or speculation.

Primary reference: `CANON_AND_PROVENANCE.md`.

### 3. Temporal integrity
World events, project-generation changes, conversation events, and knowledge-state changes must remain distinct.

Primary references: `TEMPORAL_MODEL.md`, `TEMPORAL_EVENT_TYPES.md`, `KNOWLEDGE_STATE_TRANSITIONS.md`.

### 4. Identity integrity
Named variants must not be merged merely because names overlap or biographies resemble one another.

Current highest-risk case: Jin ↔ Ryota.

Primary references: `WORLD/JIN_VERSION_LATTICE.md`, `WORLD/JIN_RYOTA_IDENTITY_AUDIT.md`.

### 5. Relationship integrity
Relationships should carry evidence/status. Conceptual similarity is not enough. Status labels must themselves be defined before they are used; active audit states such as `UNRESOLVED` must not appear as undocumented edge types.

Primary reference: `RELATIONSHIPS.md` and `ANCHOR_GRAPH.md`.

### 6. Historical integrity
Superseded interpretations should remain available when they explain project evolution or correction history.

Primary references: `PROJECT_STATE_TRANSITIONS.md`, `KNOWLEDGE_EVENTS.md`, `NEGATIVE_KNOWLEDGE.md`.

### 7. Deduplication
A repeated concept is acceptable only when each occurrence serves a distinct retrieval purpose. Otherwise update the canonical owner and link outward.

Primary references: `ARCHIVE_DEDUPLICATION_AUDIT.md`, `ARCHIVE_CLEANUP_BACKLOG.md`.

### 8. Source recovery
When high-impact knowledge is missing, prioritize direct conversation/scene recovery instead of creative reconstruction.

Highest-impact current recovery areas:
- Jin variant genealogy;
- Jin/Ryota identity;
- Arisa death scene;
- Almont/Ryota dialogue and motive structure;
- Adam's first meeting and independent decisions;
- defining Garthin scenes;
- detailed power-system mechanics;
- global cosmological relations;
- full Strings of Fate story history.

## Consolidation completed in current phase
The following root/domain nodes have been narrowed or reassigned so they no longer compete with specialized owners:

- `MEMORY.md` — orientation layer rather than duplicate governance/detail store.
- `FICTION.md` — high-level fiction map rather than canonical character/world owner.
- `COSMOLOGY.md` — high-level cosmology map rather than competing cosmology canon.
- `PROJECTS.md` — project-state/navigation layer rather than duplicate project lore.
- `TECH_STACK.md` — technical navigation/history layer rather than duplicate project implementation notes.
- `CANON_CONTROL.md` — pointer/quick gate; `CANON_AND_PROVENANCE.md` is the canonical provenance/status owner.
- character/world `*_MEMORY_DENSITY.md` nodes — evidence-strength and recovery-gap records rather than identity duplicates.

## Current known risks
1. The archive is rich in distilled context but does not yet contain a verbatim import of every historical conversation.
2. The Jin/Ryota conflict remains unresolved.
3. The complete Jin version genealogy remains missing.
4. Some detailed character relationships remain under-recovered, especially Adam and Garthin.
5. Cosmological project membership and hierarchy remain partially unresolved.
6. Strings of Fate has much stronger visual memory than narrative-memory recovery.
7. Some specialized nodes may still contain useful historical prose that should be checked when raw transcripts are imported; do not delete it merely for textual similarity.

## Pass criteria
A future maintenance pass should be considered healthy when:
- no important concept has competing current truths;
- stale summaries are marked, narrowed, or retired safely;
- high-impact conflicts have explicit owners;
- major relationships carry status/provenance;
- status vocabularies are internally defined and consistently used;
- knowledge changes are traceable;
- raw evidence and synthesis remain separable;
- additions measurably increase information value.

## Core invariant
**The archive must become more accurate faster than it becomes larger.**
