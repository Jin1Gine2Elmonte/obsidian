# Obsidian Knowledge Archive

> Portable external memory and project continuity layer.

## What this vault is

This repository is being shaped into a model-independent knowledge system for long-term continuity across conversations, AI models, applications, creative projects, and technical experiments.

The goal is not simply to store facts. The goal is to preserve **identity, structure, causality, relationships, evolution, decisions, unresolved questions, evidence, reasoning patterns, working methods, lessons, repository history, and the coverage gaps that still exist** in a form humans and future AI systems can both navigate.

## Core architecture

### Working memory
`MEMORY.md`

High-density durable orientation. It is not a transcript and not the owner of every detail.

### Reasoning / collaboration architecture
`REASONING_ARCHITECTURE.md`

Cross-domain reasoning model: internal/external perspectives, Anchor Core promotion, emergent expertise, architectural simplicity, perspective switching, purpose-first analysis, and correction discipline.

### Domain / navigation layer
- `FICTION.md` — fiction navigation layer.
- `COSMOLOGY.md` — cosmology navigation layer.
- `WORLD_SYSTEMS.md` — world-system navigation layer.
- `CHARACTERS.md` — legacy/optional character navigation if present.
- `CREATIVE_PROJECTS_DEEP.md` — conceptual/project navigation layer.
- `CREATIVE_METHOD.md` — writing/artistic method.
- `PROJECTS.md` — project-state/navigation layer.
- `TECH_STACK.md` — technical navigation/state layer.

### Graph / semantics
- `ANCHOR_GRAPH.md`
- `RELATIONSHIPS.md`
- `MEMORY_SCHEMA.md`
- `CANON_AND_PROVENANCE.md` — canonical evidence/status owner.
- `CANON_CONTROL.md` — compatibility pointer only.
- `KNOWLEDGE_OWNERSHIP_MAP.md`

### Memory / recovery operations
- `ARCHIVE_PROTOCOL.md`
- `CONTEXT_LAYERS.md`
- `ARCHIVE_CENSUS.md`
- `ARCHIVE_DEDUPLICATION_AUDIT.md`
- `ARCHIVE_CLEANUP_BACKLOG.md`
- `ARCHIVE_HEALTH_CHECK.md`
- `ARCHIVE_MAINTENANCE_LOOP.md`
- `CONVERSATION_ARCHIVE_SPEC_V2.md` — canonical conversation-import specification.
- `MEMORY_COVERAGE_AUDIT.md` — broad map of memory domains still missing, partial, or raw-evidence dependent.
- `MEMORY_RECOVERY_MATRIX.md` — high-impact recovery order across all memory domains.
- `ARCHIVE/CURRENT_CONTEXT_RECOVERY_01.md` through `_11.md` — concrete current-context recovery passes, with explicit provenance/non-canon boundaries.
- `ARCHIVE/CROSS_DOMAIN_MEMORY_RECOVERY_01.md` — cross-project thematic/structural links.
- `ARCHIVE/COLLABORATION_CORRECTION_HISTORY_01.md` — historical correction patterns in the collaboration.
- `ARCHIVE/AGENT_AND_PROMPT_ENGINEERING_RECOVERY_01.md` — prompt, model-behavior, agent, MCP, Nexus, and Hermes engineering history.
- `ARCHIVE/CREATIVE_MEDIA_HISTORY_01.md` — visual, manga, music/audio, naming, and creative-media workflow history.
- `ARCHIVE/CREATIVE_CONCEPT_EVOLUTION_RECOVERY_01.md` — evolution of recurring conceptual axes across projects.
- `ARCHIVE/IDEA_LINEAGE_RECOVERY_01.md` — how recurring ideas branch, transform, and migrate between projects/contexts.
- `ARCHIVE/GENERAL_INTERESTS_RESEARCH_RECOVERY_01.md` — durable knowledge interests, research/reading patterns, and naming/language preferences.
- `ARCHIVE/WORKING_PREFERENCES_AND_QUALITY_HISTORY_01.md` — historical development of working preferences, quality criteria, and recurring standards.
- `HIGH_IMPACT_RECOVERY_ORDER.md` — recovery priority by impact.
- `RECOVERY_EVIDENCE_PIPELINE.md` — evidence, decisive-source types, owners, and propagation targets.
- `KNOWLEDGE_STATE_TRANSITIONS.md`
- `KNOWLEDGE_EVENTS.md`
- `LESSON_PROVENANCE_MAP.md` — evidence and change lineage behind durable lessons.
- `ARCHIVE_EVOLUTION_FROM_GIT.md` — repository evolution proven by Git history.
- `QUESTIONS_AND_OPEN_LOOPS.md`
- `TECHNICAL_OPEN_LOOPS.md`
- `TIMELINE.md`
- `TEMPORAL_MODEL.md`
- `TEMPORAL_EVENT_TYPES.md`
- `PROJECT_STATE_TRANSITIONS.md`
- `DECISIONS_AND_LESSONS.md` — durable decisions, lessons, and technical experiment lineage.
- `NEGATIVE_KNOWLEDGE.md`

### Archive directory
`ARCHIVE/`

Contains deeper operational/status records and future atomic knowledge nodes. It should grow by adding genuinely useful nodes, not by duplicating root-level documents.

### World reconstruction
`WORLD/`

This directory contains reconstruction of the Jin-related world material: Jin and variants, Almont and the imperial family, the empire, Garthin, Adam, Dark Forest, power system, causal maps, relationship recovery, motive recovery, and scene-evidence matrices. Remembered facts are preserved while missing scene-level canon remains marked as recovery work.

For Jin specifically:
- `WORLD/JIN_CORE.md` — broad identity.
- `WORLD/JIN_VARIANTS.md` — variant registry.
- `WORLD/JIN_VERSION_LATTICE.md` — relationships among variants.
- `WORLD/JIN_VERSION_TRANSITIONS.md` — evidence-led changes between variants.
- `WORLD/JIN_RYOTA_IDENTITY_AUDIT.md` — unresolved identity conflict.
- `WORLD/JIN_MEMORY_DENSITY.md` — memory completeness and gaps.

### Cosmology reconstruction
`COSMOS/`

Contains cosmological anchors and memory-density/recovery notes. Shared themes are not treated as shared canon without evidence.

### Project-specific memory
`STRINGS_OF_FATE/`

A dedicated project branch containing the currently recoverable memory about «أوتار القدر» and its explicit visual/project constraints. It must not be treated as a substitute for historical transcripts.

Dedicated historical project owners also exist under `PROJECTS/` for `WHISPERS_OF_FOG.md` and `MAIN_NOVEL_DEVELOPMENT.md`.

### Technical historical memory
- `AI_MEMORY_ARCHITECTURE.md` — durable external-memory architecture and its evolution.
- `TECH/NEXUS_HERMES_HISTORY_RECOVERY.md` — NEXUS/Hermes historical recovery and technical incident lineage.
- `TECH/TOOL_WORKFLOW_HISTORY.md` — platform/tool/workflow history across creative and technical work.

## Evidence model

The vault distinguishes:
- canonical user statements
- confirmed repository/source state
- strongly supported material
- current state
- historical state
- working interpretation
- inference
- speculation
- retired ideas
- unknowns

The canonical evidence/status owner is `CANON_AND_PROVENANCE.md`.

Repository evolution has an independent evidence source: Git history, summarized in `ARCHIVE_EVOLUTION_FROM_GIT.md`.

## Editing principle

**Review before expansion.** Before creating a new node, inspect existing nodes for overlap. Update or merge when the information belongs to an existing concept. Create a new node only when it adds a genuinely distinct entity, relationship, decision, state, artifact, evidence source, or operational capability.

## Current maintenance mode

The archive is in **consolidation + source-recovery mode**. New information must be placed under an explicit owner, and existing overlapping files should be narrowed, linked, merged, or retired when appropriate.

See:
- `KNOWLEDGE_OWNERSHIP_MAP.md` — where each class of information belongs.
- `ARCHIVE_DEDUPLICATION_AUDIT.md` — useful vs harmful repetition.
- `ARCHIVE_CLEANUP_BACKLOG.md` — concrete cleanup.
- `ARCHIVE_MAINTENANCE_LOOP.md` — change propagation.
- `ARCHIVE_HEALTH_CHECK.md` — structural health.
- `MEMORY_COVERAGE_AUDIT.md` — what still has not reached the vault meaningfully.
- `MEMORY_RECOVERY_MATRIX.md` — which missing domains should be recovered first and why.
- `HIGH_IMPACT_RECOVERY_ORDER.md` — what evidence matters most.
- `RECOVERY_EVIDENCE_PIPELINE.md` — how recovery should affect the graph.
- `KNOWLEDGE_STATE_TRANSITIONS.md` — why a claim changed state.
- `TEMPORAL_EVENT_TYPES.md` — how world, project, and knowledge events differ.
- `REASONING_ARCHITECTURE.md` — cross-domain reasoning and collaboration model.
- `DECISIONS_AND_LESSONS.md` — durable decisions, lessons, and experiment lineage.
- `LESSON_PROVENANCE_MAP.md` — why those lessons became durable.
- `ARCHIVE_EVOLUTION_FROM_GIT.md` — what the repository's own history proves.
- `TECHNICAL_OPEN_LOOPS.md` — open architecture and retrieval work.

## Graph principle

Major recurring concepts should become explicit anchors. Their relationships should be recorded as first-class data. A future retrieval layer should be able to navigate from a project to its concepts, from a concept to its decisions, from a character to its world, and from a current decision to the historical context that produced it.

## Raw history vs distilled memory

When historical conversation transcripts become available, raw transcripts must remain distinct from distilled memory. Raw material is evidence. Distilled files are the current working model. Summaries must never pretend to be verbatim transcripts.

## Quality test

A change is valuable only when it adds at least one of:
- new factual knowledge
- a real relationship
- a historical state change
- a decision and its reason
- a constraint
- an evidence source
- a consequence
- a resolved contradiction
- a useful open question
- a new operational capability
- a lesson backed by real work or repeated evidence
- a verifiable repository-history fact

More words alone do not qualify.

## Guiding principle

**Continuity should survive the model.**

Models may change. Applications may change. Agents may change. The user's accumulated knowledge, projects, fictional worlds, reasoning patterns, decisions, creative identity, and the history of how the archive evolved should remain portable.
