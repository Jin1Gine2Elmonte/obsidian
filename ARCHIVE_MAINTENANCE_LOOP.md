# Archive Maintenance Loop

## Purpose
Turn every new piece of evidence into a controlled state change instead of an uncontrolled accumulation of notes.

## Loop

### 1. Capture
Preserve the source-level statement or artifact reference before interpreting it.

### 2. Localize
Assign the statement to its exact project, world, version, entity, and temporal state.

### 3. Classify
Mark it as canon, working, inferred, speculative, superseded, historical, or unknown.

Operational governance: `CANON_AND_PROVENANCE.md` defines these epistemic meanings and provenance expectations.

### 4. Compare
Check the knowledge-ownership map and existing nodes for overlap or contradiction.

### 5. Integrate
Update the canonical owner first. Add secondary references only where they express a different relationship or purpose.

### 6. Propagate
Identify dependent nodes. Recheck relationships, causal chains, timelines, summaries, and version mappings that depend on the changed fact.

### 7. Retire safely
If an old statement is no longer current, preserve it as superseded/historical when it explains the project's evolution. Do not erase it merely to make the archive look clean.

### 8. Audit
Run identity, source, temporal, causal, relationship, version, constraint, and anti-hype checks before treating the update as durable.

For unresolved recovery lanes, use `RECOVERY_EVIDENCE_PIPELINE.md` to identify the decisive evidence. For an actual knowledge-state change, record the transition through `KNOWLEDGE_STATE_TRANSITIONS.md` and preserve conflicts in the appropriate conflict owner.

### 9. Compress
After integration, remove duplicated prose where possible. The final archive should become more connected, not merely larger.

## Governance workflow
The operational sequence is:

`source/evidence → RECOVERY_EVIDENCE_PIPELINE.md → CANON_AND_PROVENANCE.md → KNOWLEDGE_STATE_TRANSITIONS.md → propagation to affected owners`

This is a workflow, not a new knowledge owner. The governance file defines status meaning, the recovery pipeline defines decisive evidence, the transition registry records the state change, and domain owners retain the actual facts.

## Change impact levels

### Local
Only one node changes.

### Relational
A relationship or small cluster changes.

### Systemic
A world rule, institution, power system, or major project assumption changes.

### Identity-critical
A name/version/continuity decision changes. These require the broadest propagation audit.

## Identity-critical protocol
For Jin, Ryota, or any recurring character/version:
1. preserve the pre-change state;
2. record the source that triggered the change;
3. update the variant/identity registry;
4. recheck relationships;
5. recheck chronology;
6. recheck project membership;
7. recheck affected world rules;
8. recheck high-level summaries;
9. record any newly resolved or newly created contradictions.

## Success condition
The archive should become more truthful and more navigable after each evidence update. A larger archive that becomes harder to distinguish, search, or trust is a failed update.
