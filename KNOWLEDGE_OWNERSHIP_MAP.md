# Knowledge Ownership Map

## Purpose
Define the canonical home for each kind of information so the archive can grow without becoming internally repetitive.

## Ownership rules

| Information type | Canonical owner | Secondary representation allowed |
|---|---|---|
| broad durable user memory | `MEMORY.md` | project-specific pointers |
| cross-domain reasoning model | `REASONING_ARCHITECTURE.md` | local task references |
| writing/artistic method | `CREATIVE_METHOD.md` | project-specific constraints |
| project purpose/state | `PROJECTS.md` | dedicated project README/state notes |
| project/version generation boundaries | `PROJECT_GENERATION_SEPARATION.md` | `PROJECT_STATE_TRANSITIONS.md`, version/project nodes |
| major recurring concept | `ANCHOR_GRAPH.md` | owning node |
| character identity | character node | memory-density / relationship references |
| character relationship | relationship node | causal/state-map references |
| event chronology | `TIMELINE.md` or project timeline | state-transition node |
| world-state change | `WORLD/WORLD_STATE_TRANSITIONS.md` | affected-node references |
| version-to-version change | version-transition ledger | lattice / project-state references |
| scene-level evidence and transitions | `WORLD/SCENE_RECOVERY_MATRIX.md` | canonical/entity references |
| motive evidence / psychological recovery targets | `WORLD/MOTIVE_RECOVERY.md` | scene-level references; never silently canonicalized |
| canonical claim | `CANON_AND_PROVENANCE.md` + domain canonical owner | source/evidence references |
| contradiction | `WORLD/CANON_CONFLICTS.md` or project conflict owner | affected-node warnings |
| unsupported interpretation / unsafe assumption | `NEGATIVE_KNOWLEDGE.md` | local warning only when necessary |
| source recovery target | recovery matrix / `RECOVERY_EVIDENCE_PIPELINE.md` | local question list |
| exact transcript | raw archive layer when available | extracted evidence references |
| derived consistency implication | analytical/derived file | canonical-node reference |
| repository evolution | `ARCHIVE_EVOLUTION_FROM_GIT.md` + Git history | knowledge-event reference |
| durable lesson / decision / experiment | `DECISIONS_AND_LESSONS.md` | `LESSON_PROVENANCE_MAP.md` |
| lesson evidence lineage | `LESSON_PROVENANCE_MAP.md` | lesson-owner references |
| archive-reconstruction methodology lessons | `ARCHIVE/ARCHIVE_LEARNING_CURVE.md` | maintenance/audit references |
| historical agent/prompt engineering recovery | `ARCHIVE/AGENT_AND_PROMPT_ENGINEERING_RECOVERY_01.md` | reasoning/technical references; exact prompts and runtime claims require source artifacts |
| historical technical tool/workflow recovery | `TECH/TOOL_WORKFLOW_HISTORY.md` | `TECH_STACK.md`, project-specific technical references; exact implementation requires source artifacts |
| NEXUS/Hermes historical recovery | `TECH/NEXUS_HERMES_HISTORY_RECOVERY.md` | `TECH_STACK.md`, agent/prompt recovery; exact implementation requires source artifacts |
| memory object/schema structure | `MEMORY_SCHEMA.md` | `MEMORY_LAYERS.md`, `MEMORY_OPERATIONS.md`; epistemic governance remains `CANON_AND_PROVENANCE.md` |
| navigation/atlas summary | root navigation files | pointers only; never a competing owner |
| cross-domain fiction synthesis | `FICTION_CANON_DEEP.md` | specialized fiction/world/cosmology owners; never a competing canon owner |
| cross-domain technical architecture synthesis | `TECHNICAL_ARCHITECTURE_DEEP.md` | `AI_MEMORY_ARCHITECTURE.md`, `TECH_STACK.md`, and project-specific technical owners |

## Governance / state-change owners

These files form an operational chain rather than competing knowledge stores:

- `CANON_AND_PROVENANCE.md` — canonical definitions for epistemic status, provenance, confidence, contradiction handling, and supersession.
- `RECOVERY_EVIDENCE_PIPELINE.md` — evidence classes, decisive-source requirements, unresolved recovery lanes, and affected owners.
- `KNOWLEDGE_STATE_TRANSITIONS.md` — recorded knowledge-state changes, reasons, affected nodes, and propagation requirements.
- `WORLD/CANON_CONFLICTS.md` — active competing claims and unresolved contradictions.
- `ARCHIVE_MAINTENANCE_LOOP.md` — operational process that connects evidence, ownership, integration, propagation, audit, and safe compression; it is not itself a domain owner.

When these documents refer to one another, the links represent workflow dependencies, not shared ownership of the underlying facts.

## Domain owners

### Jin
- `WORLD/JIN_CORE.md` — broad identity.
- `WORLD/JIN_VARIANTS.md` — variant registry.
- `WORLD/JIN_VERSION_LATTICE.md` — variant-to-variant relationships.
- `WORLD/JIN_VERSION_TRANSITIONS.md` — evidence-led changes between variants.
- `WORLD/JIN_RYOTA_IDENTITY_AUDIT.md` — identity conflict.
- `WORLD/JIN_MEMORY_DENSITY.md` — memory completeness.
- `WORLD/JIN_CHILD_HISTORY.md` — child-history branch.
- `WORLD/JIN_CHILD_HISTORY_DENSITY.md` — child-history memory completeness.
- `WORLD/JIN_ALMONT_RELATIONSHIP.md` — Jin/Almont relationship surface.
- `WORLD/JIN_RYOTA_CAUSAL_FORK.md` — competing causal interpretations around Jin/Ryota.
- `WORLD/JIN_HUMAN_COSMIC_BRIDGE.md` — conditional human/cosmic continuity models.
- `WORLD/JIN_TO_HUMAN_SCALE.md` — human-scale bridge/recovery surface.

### Almont / Ryota / family
- `WORLD/ALMONT.md` — Almont identity.
- `WORLD/ALMONT_MEMORY_DENSITY.md` — Almont memory completeness.
- `WORLD/ALMONT_REIGN_PROFILE.md` — reign/institution-versus-person analysis.
- `WORLD/ALMONT_RYOTA_RELATIONSHIP_DYNAMICS.md` — relationship dynamics.
- `WORLD/ALMONT_RYOTA_STATE_MACHINE.md` — relationship state transitions.
- `WORLD/RYOTA_ARISA_BENJAMIN.md` — family-system node.
- `WORLD/RYOTA_ARISA_BENJAMIN_MEMORY.md` — family-memory completeness.
- `WORLD/RYOTA_RETURN_MECHANICS.md` — departure/return recovery surface.
- `WORLD/ARISA_RECOVERY_NODE.md` — Arisa recovery targets.
- `WORLD/BENJAMIN_RECOVERY_NODE.md` — Benjamin recovery targets.

### Empire / Dark Forest / power
- `WORLD/EMPIRE.md` — empire canon and broad world model.
- `WORLD/EMPIRE_MEMORY_DENSITY.md` — memory completeness.
- `WORLD/IMPERIAL_LOGISTICS.md` — derived consistency analysis.
- `WORLD/IMPERIAL_INSTITUTIONAL_MODEL.md` — recovery/institutional questions.
- `WORLD/IMPERIAL_POWER_REALITY.md` — stated-power/institutional-reality consistency boundary.
- `WORLD/CAPITAL_AND_COURT.md` — capital-specific knowledge.
- `WORLD/DARK_FOREST.md` — Dark Forest canon.
- `WORLD/DARK_FOREST_MEMORY_DENSITY.md` — memory completeness.
- `WORLD/DARK_FOREST_IMPERIAL_BOUNDARY.md` — boundary-specific analysis.
- `WORLD/POWER_SYSTEM.md` — broad power-system owner.
- `WORLD/POWER_SYSTEM_MEMORY_DENSITY.md` — memory completeness.
- `WORLD/POWER_POLITICS.md` — institutional consequences.
- `WORLD/POWER_LINEAGE_POLITICS.md` — lineage/inheritance political consequences.

### Garthin / Adam
- `WORLD/GARTHIN.md` — Garthin identity and known canon.
- `WORLD/GARTHIN_MEMORY_DENSITY.md` — Garthin memory completeness.
- `WORLD/GARTHIN_RELATIONAL_ARCHITECTURE.md` — relationship structure.
- `WORLD/GARTHIN_SCENE_TARGETS.md` — defining-scene recovery targets.
- `WORLD/ADAM.md` — Adam identity and known canon.
- `WORLD/ADAM_MEMORY_DENSITY.md` — Adam memory completeness.
- `WORLD/ADAM_INTERWORLD_MODEL.md` — travel-mechanics investigation.
- `WORLD/ADAM_JIN_VARIANT_DISCRIMINATION.md` — Jin-version recognition investigation.

### Cosmology
- `COSMOS/COSMOLOGY_MEMORY_DENSITY.md` — cosmology memory completeness.
- `COSMOS/EXISTENCE_SUBLIME.md` — Existence Sublime anchor.
- `COSMOS/ENTITY_OF_FORGETTING.md` — Entity of Forgetting anchor.
- `COSMOS/PRIMORDIAL_RIFT.md` — Primordial Rift anchor.
- `COSMOS/SHADOWS_OF_FIRST_CREATION.md` — Shadows of the First Creation anchor.
- `COSMOS/CORRUPTION.md` — Corruption anchor.
- `COSMOS/CURSE_OF_THE_ANCIENTS.md` — Curse of the Ancients anchor.
- `COSMOS/BLOOD_FAMILY.md` — Blood family anchor.
- `COSMOS/DREAMS_OF_THE_INVERTED_UNIVERSE.md` — Dreams of the Inverted Universe anchor.

### Scene / motive recovery
- `WORLD/SCENE_RECOVERY_MATRIX.md` — scene-level evidence and transition extraction.
- `WORLD/MOTIVE_RECOVERY.md` — motive/psychological recovery targets and evidence boundaries.

### Strings of Fate
- `STRINGS_OF_FATE/CANON.md` — confirmed project canon.
- `STRINGS_OF_FATE/MEMORY_EXPANDED.md` — directly accessible project memory.
- `STRINGS_OF_FATE/MEMORY_TRUTH_AUDIT.md` — evidence/confidence audit.
- `STRINGS_OF_FATE/CONVERSATION_MEMORY_INDEX.md` — source-index layer.
- `STRINGS_OF_FATE/PROJECT_FRAME.md` — speculative design questions.
- `STRINGS_OF_FATE/RESEARCH_MATRIX.md` — recovery plan.
- `STRINGS_OF_FATE/VISUAL_IDENTITY.md` — visual canon.

### Navigation layers
`FICTION.md`, `COSMOLOGY.md`, `WORLD_SYSTEMS.md`, and `CREATIVE_PROJECTS_DEEP.md` are navigation/atlas surfaces only. They may summarize anchors, but they must not become competing canonical owners.

`FICTION_CANON_DEEP.md` is a cross-domain fiction synthesis layer. It may preserve useful historical/working synthesis across fiction, cosmology, character, and world-system material, but specialized domain nodes remain the actual factual/canonical owners.

`TECHNICAL_ARCHITECTURE_DEEP.md` is a cross-domain technical synthesis layer. It may connect architecture patterns across memory, agents, deployment, retrieval, Nexus, and Hermes, but `AI_MEMORY_ARCHITECTURE.md`, `TECH_STACK.md`, and project-specific technical history remain the owners of their respective domains.

## One-source-of-truth principle
A summary file may link to a canonical node. It should not silently become a second canonical owner.

## Propagation rule
When a canonical node changes, dependent summaries should be updated or explicitly marked stale. The archive should never maintain two conflicting current truths merely because both were once generated.

## Cross-reference style
Prefer a short pointer such as `See [[WORLD/JIN_CORE]]` over copying the entire content of the target.

## Cleanup control
`ARCHIVE_CLEANUP_BACKLOG.md` is the concrete maintenance queue derived from this ownership map. It does not own domain knowledge.

## Exceptions
Historical snapshots may preserve old content when the old wording itself matters for understanding project evolution. Such snapshots must be marked historical/superseded.

## Maintenance question
Before adding a file, identify its ownership role. If an existing node already owns the same knowledge type, update that node instead of creating a parallel owner.
