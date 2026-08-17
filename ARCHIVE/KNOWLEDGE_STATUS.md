# Knowledge Status Model

A durable memory item should carry both content and state.

## State dimensions

### Certainty
- `confirmed`: directly established.
- `supported`: strongly supported by repeated context.
- `inferred`: synthesized from patterns.
- `speculative`: a possibility, not established fact.
- `unknown`: intentionally unresolved.

### Temporal state
- `current`
- `historical`
- `superseded`
- `abandoned`
- `recurring`
- `undated`

### Ontological type
- person
- character
- project
- world
- concept
- system
- decision
- event
- preference
- constraint
- question
- artifact
- relationship

### Provenance
Every important node should be able to answer:
- where did this originate?
- was it explicitly stated or synthesized?
- what other nodes support it?
- what changed it later?

## Conflict protocol
If two records conflict:
1. Do not silently choose one.
2. Compare dates and provenance.
3. Determine whether they describe different project generations.
4. Preserve both when historically meaningful.
5. Mark the current winner explicitly.
6. Record the reason for the resolution.

## Memory promotion
A transient statement becomes durable when it affects:
- a project direction;
- a character canon;
- a world rule;
- a technical architecture;
- a persistent preference;
- a major decision;
- a recurring concept;
- a future dependency.

Minor conversational noise should not be promoted unless it later gains importance.
