# Archive

This directory contains durable historical, recovery, evidence, and operational knowledge layers for the Obsidian memory project.

The archive is designed to grow by adding small, linked knowledge nodes rather than endlessly enlarging one monolithic memory file.

## Current node families
- Historical and context recovery
- Creative concept and idea lineage
- Collaboration / quality / working-history records
- Decisions, lessons, and provenance
- Archive-reconstruction methodology lessons
- Temporal and project evolution records
- Canon / provenance / knowledge-state audit records
- Evidence-recovery and atomic recovery structures
- Cross-domain memory and current-context recovery
- Repository health, maintenance, and Git-evolution audits

## Current governance path
The archive is not itself a competing canon owner. Current epistemic governance lives in the root/domain owners:

`CANON_AND_PROVENANCE.md` → `RECOVERY_EVIDENCE_PIPELINE.md` → `KNOWLEDGE_STATE_TRANSITIONS.md`

Knowledge-time history is recorded by `KNOWLEDGE_EVENTS.md`. Repository evolution is evidenced by `ARCHIVE_EVOLUTION_FROM_GIT.md` and Git history itself.

`ARCHIVE_LEARNING_CURVE.md` owns lessons specifically about archive reconstruction and preservation methodology. It is distinct from `ARCHIVE_EVOLUTION_FROM_GIT.md`, which records Git-evidenced repository development history.

## Audit surface
Dated repository audits and their addenda live in this directory. The root `INDEX.md` is the authoritative navigation surface for the complete current audit chain; the live Git tree and HEAD establish current repository state.

The audit chain is intentionally append-only in spirit: later maintenance findings are recorded as new dated addenda rather than rewriting earlier audit conclusions.

## Evidence / provenance orientation
This directory's previous wording as a single “source hierarchy” mixed evidence strength with epistemic status and could be mistaken for a second governance system.

For current evidence provenance and epistemic status, defer to `CANON_AND_PROVENANCE.md`. The archive layers can be understood as an orientation to how material is represented:
1. established/current knowledge;
2. explicitly sourced user or project evidence;
3. supported recurring patterns;
4. marked synthesis or inference;
5. labeled speculation or unresolved material.

This is an orientation for archive representation, not a replacement for the canonical provenance/status definitions.

## Maintenance rule
When a new conversation changes a durable concept, update the smallest relevant owner and record the relationship, evidence, or reason for the change. Avoid replacing an entire knowledge domain when a precise delta is sufficient.

When source evidence is unavailable, preserve the uncertainty and create or update a recovery target rather than inventing the missing history.
