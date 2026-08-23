# Obsidian Knowledge Archive

> Portable external memory and project continuity layer.

## What this vault is

This repository is being shaped into a model-independent knowledge system for long-term continuity across conversations, AI models, applications, creative projects, and technical experiments.

The goal is not simply to store facts. The goal is to preserve **identity, structure, causality, relationships, evolution, decisions, unresolved questions, and working methods** in a form that humans and future AI systems can both navigate.

## Core architecture

### Working memory
`MEMORY.md`

High-density durable synthesis. It should contain the minimum set of information needed to orient a future AI without pretending to be a transcript.

### Domain knowledge
- `FICTION.md`
- `COSMOLOGY.md`
- `WORLD_SYSTEMS.md`
- `CHARACTERS.md`
- `CREATIVE_PROJECTS_DEEP.md`
- `PROJECTS.md`
- `TECH_STACK.md`

### Graph / semantics
- `ANCHOR_GRAPH.md`
- `RELATIONSHIPS.md`
- `MEMORY_SCHEMA.md`
- `CANON_CONTROL.md`
- `CANON_AND_PROVENANCE.md`
- `KNOWLEDGE_OWNERSHIP_MAP.md`

### Memory operations
- `ARCHIVE_PROTOCOL.md`
- `CONTEXT_LAYERS.md`
- `ARCHIVE_CENSUS.md`
- `ARCHIVE_DEDUPLICATION_AUDIT.md`
- `CONVERSATION_ARCHIVE_SPEC_V2.md` — canonical conversation-import specification
- `QUESTIONS_AND_OPEN_LOOPS.md`
- `TECHNICAL_OPEN_LOOPS.md`
- `TIMELINE.md`
- `PROJECT_STATE_TRANSITIONS.md`
- `DECISIONS_AND_LESSONS.md`
- `NEGATIVE_KNOWLEDGE.md`

### Archive directory
`ARCHIVE/`

Contains deeper operational/status records and future atomic knowledge nodes. It should grow by adding genuinely useful nodes, not by duplicating root-level documents.

### World reconstruction
`WORLD/`

This directory contains high-density reconstruction of the Jin universe: Jin and his variants, Almont and the imperial family, the empire, Garthin, Adam, the Dark Forest, the power system, causal maps, relationship recovery, and scene-recovery matrices. These notes are intentionally conservative: remembered facts are preserved, while missing scene-level canon remains marked as a recovery target.

### Project-specific memory
`STRINGS_OF_FATE/`

A dedicated project branch containing the currently recoverable memory about «أوتار القدر» and its explicit visual/project constraints. It must not be treated as a substitute for historical transcripts.

## Evidence model

The vault distinguishes:
- canonical user statements
- confirmed repository/source state
- current state
- historical state
- working interpretation
- inference
- speculation
- retired ideas
- unknowns

See `CANON_CONTROL.md` and `ARCHIVE_PROTOCOL.md`.

## Ownership principle

Every knowledge type should have a primary owner. Use `KNOWLEDGE_OWNERSHIP_MAP.md` before creating a new node. A secondary file may reference a fact, but should not silently become a second canonical source by copying an entire existing summary.

## Editing principle

**Review before expansion.** Before creating a new node, inspect existing nodes for overlap. Update or merge when the information belongs to an existing concept. Create a new node only when it adds a genuinely distinct entity, relationship, decision, state, artifact, or evidence source.

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

More words alone do not qualify.

## Guiding principle

**Continuity should survive the model.**

Models may change. Applications may change. Agents may change. The user's accumulated knowledge, projects, fictional worlds, reasoning patterns, decisions, and creative identity should remain portable.
