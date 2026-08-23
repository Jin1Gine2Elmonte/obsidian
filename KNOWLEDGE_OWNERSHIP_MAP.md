# Knowledge Ownership Map

## Purpose
Define the canonical home for each kind of information so the archive can grow without becoming internally repetitive.

## Ownership rules

| Information type | Canonical owner | Secondary representation allowed |
|---|---|---|
| broad durable user memory | `MEMORY.md` | project-specific nodes |
| project purpose/state | `PROJECTS.md` | dedicated project README |
| major recurring concept | `ANCHOR_GRAPH.md` | owning node |
| character identity | character node | memory-density / relationship references |
| character relationship | relationship node | causal map reference |
| event chronology | `TIMELINE.md` or project timeline | state transition node |
| world-state change | `WORLD_STATE_TRANSITIONS.md` | affected node references |
| canonical claim | `CANON_LEDGER.md` or project `CANON.md` | source/evidence node |
| contradiction | `CANON_CONFLICTS.md` | affected nodes |
| unsupported interpretation | `NEGATIVE_KNOWLEDGE.md` when unsafe | local speculative section |
| source recovery target | recovery matrix | local question list |
| exact transcript | raw archive layer when available | extracted evidence references |
| derived consistency implication | analytical/derived file | canonical node reference |
| project generation/change | `PROJECT_STATE_TRANSITIONS.md` | timeline reference |
| rejected/superseded direction | historical/negative layer | affected project node |

## One-source-of-truth principle
A summary file may link to a canonical node. It should not silently become a second canonical owner.

## Propagation rule
When a canonical node changes, dependent summaries should be updated or explicitly marked stale. The archive should never maintain two conflicting "current truths" merely because both were once generated.

## Cross-reference style
Prefer a short pointer such as `See [[WORLD/JIN_CORE]]` over copying the entire content of the target.

## Exceptions
Historical snapshots may preserve old content when the old wording itself matters for understanding project evolution. Such snapshots must be marked historical/superseded.

## Maintenance question
Before adding a file, identify its ownership role. If an existing node already owns the same knowledge type, update that node instead of creating a parallel owner.
