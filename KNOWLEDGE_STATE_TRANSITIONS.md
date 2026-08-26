# Knowledge State Transitions

This registry records how the archive's understanding changes. It is separate from story chronology.

## Transition model
`UNOBSERVED -> OBSERVED -> EXTRACTED -> CLASSIFIED -> LINKED -> CANONICAL/WORKING/INFERRED -> SUPERSEDED/RETRACTED`

Not every fact passes through every state, and a state change does not necessarily mean the underlying world event changed.

## Transition types
### Discovery
A source reveals information that was not previously present.

### Correction
A previous statement is shown to be inaccurate or malformed.

### Disambiguation
A single ambiguous node is split into distinct entities, versions, or projects.

### Merge
Two records are proven to refer to the same entity/state and are unified.

### Supersession
A later project state replaces an earlier working state while preserving history.

### Reclassification
The evidence remains the same but the epistemic status changes, for example `WORKING -> CANON` or `INFERRED -> UNKNOWN`.

### Propagation
A verified change updates dependent relationships, timelines, conflicts, or derived notes.

## High-impact example: Jin / Ryota
If a future transcript proves that Jin and Ryota are the same identity in one project generation, that is not merely a rename. The transition must update:
- identity registry;
- version lattice;
- Almont relationship;
- Arisa event references;
- childhood chronology;
- project membership;
- dependent relationship nodes;
- affected canon conflicts;
- any derived summaries.

If instead a transcript proves they are separate characters, the same propagation occurs in the opposite direction.

## Evidence discipline
A knowledge transition should cite:
- source;
- relevant passage/scene;
- prior state;
- new state;
- reason for transition;
- affected nodes.

## Governance and recovery links
- Canon/provenance owner: `CANON_AND_PROVENANCE.md` — defines the epistemic classes and provenance rules used by each transition.
- Recovery evidence pipeline: `RECOVERY_EVIDENCE_PIPELINE.md` — identifies the evidence that can trigger a transition and the downstream owners that must be rechecked.
- Conflict owner: `WORLD/CANON_CONFLICTS.md` — records competing states that prevent a transition from being silently finalized.

A transition record explains **why** the state changed; the governance owner defines **what the states mean**; the recovery pipeline defines **what evidence can cause the change**.

## Historical preservation
Never delete the previous interpretation merely because it is no longer current. Preserve it as historical/superseded when it explains the path by which the archive changed.

## Quality principle
The archive should remember both:

**what is currently believed**

and

**why that belief became current.**
