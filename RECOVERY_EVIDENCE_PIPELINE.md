# Recovery Evidence Pipeline

## Purpose
Turn the high-impact recovery order into an executable evidence pipeline. This file does not invent canon; it maps each unresolved question to the evidence capable of changing it and to the downstream nodes that must be rechecked.

## Evidence classes
- `DIRECT_USER_STATEMENT` — explicit user statement.
- `ORIGINAL_SCENE` — source scene/dialogue from the project.
- `PROJECT_VERSION_MARKER` — explicit rewrite/version/project-generation evidence.
- `SUMMARY_ONLY` — distilled memory without raw context.
- `INFERENCE` — analytical consequence.
- `UNKNOWN` — insufficient evidence.

## P0 — Jin ↔ Ryota identity

### Question
Are Jin and Ryota the same identity in any project/version, separate characters, or compressed memories from different generations?

### Evidence capable of deciding it
1. One source explicitly equating the names.
2. One source explicitly separating them.
3. A scene containing both names in the same continuity.
4. Explicit rewrite/version language connecting the two.
5. Incompatible ages/events/relationships that force separation.

### Current status
`UNRESOLVED / HIGH IMPACT`

### Owners affected if resolved
- `WORLD/JIN_CORE.md`
- `WORLD/JIN_VARIANTS.md`
- `WORLD/JIN_VERSION_LATTICE.md`
- `WORLD/JIN_RYOTA_IDENTITY_AUDIT.md`
- `WORLD/ALMONT.md`
- `WORLD/RYOTA_ARISA_BENJAMIN.md`
- `WORLD/ALMONT_RYOTA_RELATIONSHIP_DYNAMICS.md`
- `TIMELINE.md`
- `WORLD/CANON_CONFLICTS.md`
- dependent relationship/causal nodes

## P0 — Jin variant genealogy

### Question
Which Jin/Gin/Gene iterations exist, which project/version each belongs to, and what continuity edge connects them?

### Best evidence
- explicit "old/new/original/another Jin" statements;
- named rewrite or replacement events;
- project titles or phase markers next to a Jin reference;
- explicit statements of shared or non-shared memory.

### Current status
`PARTIALLY RECOVERED`

### Owners affected
- `WORLD/JIN_VARIANTS.md`
- `WORLD/JIN_VERSION_LATTICE.md`
- `WORLD/JIN_CORE.md`
- project-specific character/world nodes

## P1 — Arisa death

### Question
Who witnessed the death, what exactly happened, who caused it if known, and what immediate consequences were canonical?

### Best evidence
- original scene;
- direct user retelling tied to a named character/version;
- immediate before/after dialogue;
- explicit chronology markers.

### Current status
`PARTIALLY RECOVERED`

### Owners affected
- `WORLD/RYOTA_ARISA_BENJAMIN.md`
- `WORLD/ALMONT.md`
- `WORLD/CANON_CONFLICTS.md`
- child-history chronology
- relationship/state nodes

## P1 — Almont ↔ son

### Question
What does Almont actually want from his son, why does the son rebel, and what emotional/political mechanics govern the relationship?

### Best evidence
- dialogue;
- scene-level behavior;
- explicit user characterization;
- repeated decisions across time.

### Current status
`PARTIALLY RECOVERED`

## P1 — Adam ↔ Jin

### Question
How did they meet? Why does Adam follow Jin? Which Jin does Adam follow? Can Adam distinguish variants?

### Best evidence
- first-meeting scene;
- world-transition scenes;
- disagreement/independence scenes;
- explicit statements about variant recognition.

### Current status
`PARTIALLY RECOVERED`

## P1 — Garthin

### Question
What actions actually establish his contradiction?

### Best evidence
- defining scenes;
- acts of restraint or cruelty;
- behavior toward vulnerability;
- private/public contrasts.

### Current status
`STRONG CORE / LOW SCENE DETAIL`

## P2 — Power system

### Required evidence
- exact Magic rules;
- inherited Power rules;
- spiritual vessel mechanics;
- costs/limits;
- inheritance and interaction rules.

### Status
`PARTIAL CANON`

## P2 — Empire / Dark Forest

### Required evidence
- actual city hierarchy;
- military organization;
- communication/transport as explicitly designed;
- succession;
- Dark Forest policy/history.

### Status
`MACRO SCALE RECOVERED / INSTITUTIONAL DETAIL PARTIAL`

## P3 — Cosmology

### Required evidence
Explicit source-level relationships among:
- Existence Sublime;
- Entity of Forgetting;
- Primordial Rift;
- Shadows of the First Creation;
- Abyss;
- Corruption;
- Curse of the Ancients;
- related project anchors.

### Status
`ANCHORS STRONG / GLOBAL HIERARCHY UNKNOWN`

## P4 — Strings of Fate

### Required evidence
Separate story transcripts from visual-cover conversations. Prioritize:
- cast;
- plot;
- world;
- string ontology/mechanics;
- revisions;
- rejected ideas;
- ending.

### Status
`VISUAL MEMORY STRONG / STORY RECOVERY LOW`

## Governance and transition links
- Canon/provenance owner: `CANON_AND_PROVENANCE.md` — defines how evidence classes become epistemic states.
- State-transition registry: `KNOWLEDGE_STATE_TRANSITIONS.md` — records the actual change from one knowledge state to another and the nodes requiring propagation.
- Conflict owner: `WORLD/CANON_CONFLICTS.md` — holds unresolved competing claims instead of forcing a transition.

The pipeline answers **what evidence is needed**; the transition registry answers **what changed**; the governance owner answers **what the resulting state means**.

## Evidence-to-propagation rule
When a source is recovered, never update only the first matching file. First classify the evidence, assign project/version, then update the canonical owner and propagate only verified deltas to affected timelines, relationships, conflicts, and summaries.

## Stop condition
Do not create a new explanatory theory merely because a recovery lane is empty. Empty evidence lanes are valid knowledge states.
