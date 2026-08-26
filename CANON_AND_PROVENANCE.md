# Canon, Provenance, Confidence & Status — Canonical Governance Owner

> This is the single canonical governance owner for epistemic status, provenance, confidence, contradictions, and supersession.

## Status classes

### CANONICAL
Explicitly established by the user or confirmed by project/source evidence.

### STRONGLY_SUPPORTED
Repeated across reliable sources and internally consistent, but not necessarily backed by one decisive scene.

### WORKING
A current synthesis/model used for orientation but still open to revision.

### DERIVED
An analytical implication inferred from established material rather than directly stated.

### SPECULATIVE
A hypothesis, creative extrapolation, or unresolved interpretation.

### HISTORICAL / SUPERSEDED
A previous state retained because it explains project or knowledge evolution but is not current.

### UNKNOWN
Insufficient evidence. Do not fill the gap by invention.

## Provenance
Important claims should identify their strongest available source:
- direct user statement;
- historical conversation/transcript;
- conversation summary;
- repository/file state;
- commit/version evidence;
- external reference;
- analytical inference.

A summary is evidence about what was remembered, not proof that the underlying claim was originally stated.

## Confidence
Confidence reflects evidence quality, not elegance or usefulness.

Suggested levels: `high`, `medium`, `low`.

## Relationship-label normalization
`RELATIONSHIPS.md` and `ANCHOR_GRAPH.md` use a compact operational vocabulary for graph edges. These labels are aliases for the governance classes above, not a second independent epistemic system:

| Graph label | Governance meaning |
|---|---|
| `CANON` | `CANONICAL` |
| `SUPPORTED` | `STRONGLY_SUPPORTED` |
| `INFERRED` | `DERIVED` |
| `SPECULATIVE` | `SPECULATIVE` |
| `UNKNOWN` | `UNKNOWN` |
| `UNRESOLVED` | active relationship-audit state; underlying evidence is insufficient or conflicting and must remain unresolved rather than being promoted to `CANONICAL` |

Graph files may retain their compact labels for readability. When a relationship is `UNRESOLVED`, the affected conflict owner should explain what evidence conflicts or is missing.

## Contradictions
When two records conflict:
1. preserve both claims;
2. identify context/time/project/version;
3. classify the conflict;
4. determine whether one superseded the other;
5. mark the current state explicitly;
6. propagate only verified changes.

Active conflict owner: `WORLD/CANON_CONFLICTS.md`.

## Creative canon
Fictional material should also distinguish:
- established canon;
- draft/current working canon;
- derived implications;
- idea-bank material;
- abandoned/rejected directions.

A plausible implication is not automatically canon.

## Technical canon
A proposed architecture is not a working system until implementation evidence exists. Experimental repositories should not be described as production systems merely because a plan or README says so.

## Memory canon
A memory synthesis must expose its uncertainty and preserve its provenance. It must not manufacture missing transcripts, scenes, or decisions.

## Relationship status
Relationships are first-class claims and must carry status/provenance. The fact that two nodes are conceptually adjacent does not make the relationship canonical. Use the normalized graph-label mapping above rather than introducing new unlabeled edge states.

## Temporal status
A claim may be current in archive time while referring to a historical project state or fictional-world event. Use the temporal model to prevent these clocks from collapsing.

## Supersession
When later evidence changes a claim, preserve the prior state as historical/superseded when it explains evolution. Never erase meaningful history merely to produce a cleaner current summary.

## Operational governance links
- State-change registry: `KNOWLEDGE_STATE_TRANSITIONS.md` — records why an epistemic state changed and what nodes must be propagated.
- Recovery evidence pipeline: `RECOVERY_EVIDENCE_PIPELINE.md` — identifies the evidence capable of changing unresolved claims and the downstream owners affected.
- Active conflict owner: `WORLD/CANON_CONFLICTS.md` — holds unresolved contradictions rather than resolving them inside the governance layer.

These links describe the governance workflow; they do not transfer ownership of facts or relationships to this file.

## Single-source-of-truth rule
This file owns governance definitions. `CANON_CONTROL.md` is a navigation pointer only. Project/world nodes own their actual facts; governance files do not become duplicate lore summaries.
