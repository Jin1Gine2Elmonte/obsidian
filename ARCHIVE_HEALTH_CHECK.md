# Archive Health Check

## Purpose
A compact validation surface for the external-memory system. This file does not own project facts; it records structural health criteria and the current known risks.

## Integrity dimensions

### 1. Ownership
Every important knowledge type should have one clear canonical owner.

Primary reference: `KNOWLEDGE_OWNERSHIP_MAP.md`.

Ownership completeness must be checked against directory-level inventories such as `WORLD/README.md`, `COSMOS/README.md`, `STRINGS_OF_FATE/README.md`, and other explicit local navigation surfaces. A file may be locally discoverable yet still be an ownership-registry gap if its substantive role is absent from the canonical ownership map.

### 2. Provenance
Important claims should indicate whether they come from direct user evidence, recovered source material, repository state, synthesis, inference, or speculation.

Primary reference: `CANON_AND_PROVENANCE.md`.

Operational governance chain: `CANON_AND_PROVENANCE.md` → `RECOVERY_EVIDENCE_PIPELINE.md` → `KNOWLEDGE_STATE_TRANSITIONS.md`.

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

### 9. Sequence integrity
Numeric gaps in a recovery-series filename are not, by themselves, evidence of a missing file, deleted history, or incomplete knowledge. A sequence member should be treated as a real recovery gap only when repository references, Git history, an audit record, or source evidence establish that the member existed or is required by a defined specification.

Conversely, an existing numbered node must not be assumed to imply that all intervening numbers should exist. Maintenance should verify provenance and references before creating placeholders or synthetic continuation files.

## Consolidation completed in current phase
The following root/domain nodes have been narrowed or reassigned so they no longer compete with specialized owners:

- `MEMORY.md` — orientation layer rather than duplicate governance/detail store.
- `FICTION.md` — high-level fiction map rather than canonical character/world owner.
- `FICTION_CANON_DEEP.md` — cross-domain fiction synthesis rather than competing canon owner.
- `COSMOLOGY.md` — high-level cosmology map rather than competing cosmology canon.
- `PROJECTS.md` — project-state/navigation layer rather than duplicate project lore.
- `PROJECT_GENERATION_SEPARATION.md` — explicit owner for project/version-generation boundaries.
- `TECH_STACK.md` — technical navigation/history layer rather than duplicate project implementation notes.
- `TECHNICAL_ARCHITECTURE_DEEP.md` — cross-domain technical synthesis rather than competing implementation owner.
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
8. Major owner nodes should continue to expose provenance, dependency, contradiction, relationship, and recovery links consistently; this is now a linkage-depth concern rather than a top-level indexing problem.
9. Governance/transition/recovery owners should remain traversable as one operational chain: state definitions → decisive evidence → recorded state change. Breaks in that chain are maintenance defects even when the underlying knowledge is intact.
10. Recovery-series numbering should remain provenance-driven; missing numeric members should be recorded as open recovery questions only when evidence establishes that they represent omitted source material.
11. Directory-level inventories should be periodically reconciled with `KNOWLEDGE_OWNERSHIP_MAP.md` so locally navigable substantive nodes do not become unregistered owners.

## Pass criteria
A future maintenance pass should be considered healthy when:
- no important concept has competing current truths;
- stale summaries are marked, narrowed, or retired safely;
- high-impact conflicts have explicit owners;
- major relationships carry status/provenance;
- status vocabularies are internally defined and consistently used;
- knowledge changes are traceable;
- raw evidence and synthesis remain separable;
- major navigation layers expose the correct specialized owners;
- directory-level substantive inventories reconcile with the canonical ownership map;
- governance, recovery, and state-transition surfaces form a traversable chain;
- recovery-series gaps are distinguished from proven missing artifacts;
- additions measurably increase information value.

## Core invariant
**The archive must become more accurate faster than it becomes larger.**
