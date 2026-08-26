# Archive

This directory contains durable historical, recovery, evidence, and operational knowledge layers for the Obsidian memory project.

The archive is designed to grow by adding small, linked knowledge nodes rather than endlessly enlarging one monolithic memory file.

## Current node families
- Historical and context recovery
- Creative concept and idea lineage
- Collaboration / quality / working-history records
- Decisions, lessons, and provenance
- Temporal and project evolution records
- Canon / provenance / knowledge-state audit records
- Evidence-recovery and atomic recovery structures
- Cross-domain memory and current-context recovery
- Repository health, maintenance, and Git-evolution audits

## Current governance path
The archive is not itself a competing canon owner. Current epistemic governance lives in the root/domain owners:

`CANON_AND_PROVENANCE.md` → `RECOVERY_EVIDENCE_PIPELINE.md` → `KNOWLEDGE_STATE_TRANSITIONS.md`

Knowledge-time history is recorded by `KNOWLEDGE_EVENTS.md`. Repository evolution is evidenced by `ARCHIVE_EVOLUTION_FROM_GIT.md` and Git history itself.

## Audit surface
Dated repository audits and their addenda live in this directory. The root `INDEX.md` is the authoritative navigation surface for the complete current audit chain; the live Git tree and HEAD establish current repository state.

The audit chain is intentionally append-only in spirit: later maintenance findings are recorded as new dated addenda rather than rewriting earlier audit conclusions.

## Source hierarchy
1. Explicitly established canon.
2. Explicit user preferences and decisions.
3. Repeated patterns supported by multiple interactions.
4. Carefully marked synthesis/inference.
5. Speculation, which must always be labeled.

## Maintenance rule
When a new conversation changes a durable concept, update the smallest relevant owner and record the relationship, evidence, or reason for the change. Avoid replacing an entire knowledge domain when a precise delta is sufficient.

When source evidence is unavailable, preserve the uncertainty and create or update a recovery target rather than inventing the missing history.
