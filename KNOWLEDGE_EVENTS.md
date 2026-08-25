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
The archive was initially expanded through many summaries. Repeated feedback established that volume without genuine information gain was not progress. This led to deduplication, ownership, and consolidation rules.

Class: `CORRECTION`

### KE-002 — Recognition of Jin/Ryota identity contamination
Two durable memory paths contained nearly overlapping child-history material under Jin and Ryota. Instead of resolving by intuition, the archive opened an explicit identity conflict and prohibited silent merging.

Class: `CONFLICT_OPENED` + `SPLIT`

Affected: Jin, Ryota, Almont, Arisa, timeline, Jin version lattice.

### KE-003 — Separation of project generations
Recurring names and concepts were recognized as potentially reused across different project generations. Similarity is no longer treated as continuity without evidence.

Class: `RECLASSIFICATION`

### KE-004 — Recognition of multi-clock chronology
The archive now distinguishes conversation time, project-generation time, fictional-world time, and archive knowledge time. A later conversation can discuss an earlier project or an earlier fictional event without changing the original event's place in the world.

Class: `DISCOVERY` / `RECLASSIFICATION`

### KE-005 — Separation of world, project, and knowledge events
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

### KE-009 — Memory compression / orientation split
`MEMORY.md` was narrowed into a high-density orientation layer. Detailed governance, ownership, temporal rules, relationship confidence, and maintenance behavior remain in specialized canonical operational nodes.

Class: `OWNERSHIP_CHANGE` + `CORRECTION`

Reason: prevent the persistent-memory file from becoming a second copy of the entire archive.

### KE-010 — Root fiction/cosmology documents demoted to navigation layers
`FICTION.md` and `COSMOLOGY.md` were converted from competing detail-heavy summaries into navigation/atlas layers. Specialized world, character, project, and cosmology nodes now own detailed claims.

Class: `OWNERSHIP_CHANGE` + `RECLASSIFICATION`

### KE-011 — Archive-wide health model
A dedicated `ARCHIVE_HEALTH_CHECK.md` was introduced to test ownership, provenance, temporal integrity, identity safety, relationship status, historical preservation, deduplication, and source-recovery priority as measurable dimensions.

Class: `DISCOVERY` / `OWNERSHIP_CHANGE`

### KE-012 — Knowledge-change history becomes first-class
The archive now records not only what is currently believed, but how a claim changed state: discovery, correction, split, merge, reclassification, ownership change, supersession, recovery, and propagation.

Class: `RECLASSIFICATION`

### KE-013 — Atomic event recovery becomes a distinct memory layer
Recent recovery work showed that character summaries were insufficient to preserve the local structure of memory. The archive therefore introduced atomic event records for the Jin/Almont/Ryota/Arisa branch and then for Almont/Garthin/Adam.

Class: `OWNERSHIP_CHANGE` + `RECOVERY`

Effect: character nodes remain identity owners while event nodes preserve event order, local uncertainty, consequences, and unresolved identity/version questions.

### KE-014 — World-state/event separation expanded to macro systems
The empire and Dark Forest were separated into world-state/event recovery rather than having inferred institutional consequences silently promoted to canon.

Class: `RECLASSIFICATION` + `RECOVERY`

Effect: declared scale and boundary facts remain distinct from derived logistics, politics, and hidden causes.

### KE-015 — Power/cosmology recovery boundary hardened
The archive confirmed that Magic, inherited Powers, and the spiritual-vessel concept are durable memory anchors, while detailed mechanics remain source-recovery targets. Likewise, recurring cosmological names are not merged into a hierarchy without direct evidence.

Class: `RECLASSIFICATION`

Effect: prevents title-based or motif-based cosmology invention.

### KE-016 — General-interest and research memory promoted to an explicit layer
Repeated recovery showed that reading/research patterns, naming/language concerns, and broader knowledge interests were a missing category rather than incidental metadata.

Class: `OWNERSHIP_CHANGE` + `RECOVERY`

Effect: these patterns can now be preserved without contaminating fictional canon or private biography.

### KE-017 — Project-only titles promoted from atlas entries to historical owners
`The Last Thing to Be Forgotten`, `Shadows of the First Creation`, `Dreams of the Inverted Universe`, and `Lord of the Abyss` were promoted from title-level project anchors to explicit historical-owner nodes with evidence boundaries and recovery targets.

Class: `OWNERSHIP_CHANGE`

Important boundary: creating a project owner did not imply that the project's narrative or cosmology was recovered.

### KE-018 — Recovery process itself decoupled from fixed task text
A recurring operation was scheduled as a minimal `@Thinking / جارٍ التفكير / Details` signal after it became clear that a detailed task prompt would overconstrain an intentionally open-ended process. The meaningful context must come from the live state of the archive and conversation, not from a frozen task-specific instruction.

Class: `CORRECTION` + `RECLASSIFICATION`

Important boundary: this is an operational scheduling decision, not a fictional or identity claim.

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
