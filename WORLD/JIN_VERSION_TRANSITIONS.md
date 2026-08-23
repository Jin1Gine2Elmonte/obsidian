# Jin Version Transitions — Evidence-Led Transition Ledger

## Purpose
Record transitions between Jin/Gin/Gene variants without duplicating identity or version definitions.

This is an **event/transition layer**. It owns what changed between states, not who Jin is in general (`JIN_CORE`) and not the variant registry/lattice (`JIN_VARIANTS`, `JIN_VERSION_LATTICE`).

## Required transition record
Every recovered transition should record:
- `transition_id`
- `source_variant`
- `target_variant`
- `transition_type`
- `conversation_time`
- `project_time`
- `fiction_time`
- `trigger`
- `changed_properties`
- `preserved_properties`
- `lost_memory`
- `new_memory`
- `power_delta`
- `personality_delta`
- `relationship_delta`
- `cosmological_delta`
- `reason_for_change`
- `canon_status`
- `source_evidence`
- `downstream_impact`

Unknown fields must remain `UNKNOWN`; they must not be filled through narrative inference.

## Allowed transition types
Use only when supported:
- `REWRITE`
- `BRANCH`
- `REPLACEMENT`
- `RETCON`
- `REINCARNATION`
- `INCARNATION`
- `PARALLELIZATION`
- `MERGE`
- `SPLIT`
- `SUPERCESSION`
- `UNKNOWN`

## Current recovered transition state
No individual Jin-to-Jin transition is currently source-recovered strongly enough to be entered as canon here.

What is supported is only the existence of multiple iterations/versions and the need to distinguish them. The version lattice records the possible edge types; this ledger waits for source-level transition evidence.

## Recovery prompts
Prioritize statements such as:
- "I changed Jin into..."
- "the old Jin..."
- "this version replaced..."
- "in the previous version..."
- "the original Jin..."
- "another Jin..."
- "same Jin but..."
- "not the same Jin..."
- "I rewrote..."
- "this is an alternate version..."

Always preserve surrounding context so the transition can be scoped to a project/version rather than a keyword match.

## Propagation rule
A verified transition can affect:
- `JIN_VERSION_LATTICE.md`
- `JIN_VARIANTS.md`
- `JIN_CORE.md` only if a broad invariant is actually established
- `JIN_RYOTA_IDENTITY_AUDIT.md` / `CANON_CONFLICTS.md` when identity boundaries change
- `TIMELINE.md` when the transition has project or fictional temporal consequences
- relationship and causal nodes affected by changed history
- project-state records when the transition represents a rewrite/generation change

## Anti-conflation rule
A transition must never be inferred merely because two versions share a name, theme, power, trauma, or visual motif.

## Current priority
Highest value: recover the first explicit Jin version change and the first explicit statement that defines whether two named Jin representations are continuous or separate.
