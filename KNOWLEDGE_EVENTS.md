# Knowledge Events

## Purpose
A chronological ledger for events that change the archive's understanding, not events that merely happen inside a fictional world.

## Event classes
- `DISCOVERY` — a new fact or source is found.
- `CORRECTION` — an existing claim is shown to be wrong or incomplete.
- `SPLIT` — one compressed node is separated into multiple identities/projects/versions.
- `MERGE` — two nodes are proven to represent the same entity/state.
- `RECLASSIFICATION` — a claim changes epistemic status without changing its wording.
- `OWNERSHIP_CHANGE` — a fact moves to a better canonical owner.
- `CONFLICT_OPENED` — incompatible evidence becomes visible.
- `CONFLICT_RESOLVED` — sufficient evidence establishes the current interpretation.
- `SUPERSESSION` — a later state replaces an earlier working state while history remains preserved.
- `RECOVERY` — source material restores previously missing detail.
- `PROPAGATION` — a verified change is carried into dependent nodes.

## Current high-impact knowledge events

### KE-001 — Recognition of archive overgrowth
The archive was initially expanded through many summaries. The repeated user feedback established that volume without genuine information gain was not progress. This led to deduplication, ownership, and consolidation rules.

Class: `CORRECTION`

### KE-002 — Recognition of Jin/Ryota identity contamination
Two durable memory paths contained nearly overlapping child-history material under Jin and Ryota. Instead of resolving by intuition, the archive opened an explicit identity conflict and prohibited silent merging.

Class: `CONFLICT_OPENED` + `SPLIT`

Affected: Jin, Ryota, Almont, Arisa, timeline, Jin version lattice.

### KE-003 — Separation of project generations
Recurring names and concepts were recognized as potentially reused across different project generations. Similarity is no longer treated as continuity without evidence.

Class: `RECLASSIFICATION`

### KE-004 — Recognition of multi-clock chronology
The archive now distinguishes conversation time, project-generation time, and fictional-world time. A later conversation can discuss an earlier project or an earlier fictional event.

Class: `DISCOVERY` / `RECLASSIFICATION`

### KE-005 — Separation of world events from knowledge events
A death in a story, a rewrite of the story, and a correction to the archive are different event types and must not share one undifferentiated timeline.

Class: `RECLASSIFICATION`

### KE-006 — Ownership consolidation
Canonical identity owners were separated from memory-density, relationship, causality, recovery, and negative-knowledge nodes. This reduced competing versions of the same current truth.

Class: `OWNERSHIP_CHANGE`

### KE-007 — Relationship confidence hardening
The archive stopped treating conceptual adjacency or analytical usefulness as evidence of a canonical relationship. Relationship edges must carry provenance/status.

Class: `CORRECTION`

### KE-008 — Strings of Fate evidence boundary
The accessible memory for Strings of Fate was recognized as strongly visual/project-level but incomplete at plot/cosmology level. Unsupported mechanics must remain unsupported rather than being supplied from the title or from other worlds.

Class: `RECLASSIFICATION`

## Required event fields for future entries
- event id
- archive time
- source time if known
- project/version context
- event class
- affected nodes
- old state
- new state
- evidence
- confidence
- downstream propagation
- superseded material, if any
- unresolved remainder

## Integrity rule
Knowledge events describe changes to the archive's understanding. They must never be mistaken for fictional-world events merely because their subject is a fictional character.
