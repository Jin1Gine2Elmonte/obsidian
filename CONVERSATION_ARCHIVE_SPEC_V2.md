# Conversation Archive Specification (Canonical)

This is the single canonical specification for importing historical conversation material into the vault. The older `CONVERSATION_ARCHIVE_SPEC.md` is superseded and should not be recreated unless it is explicitly needed as historical evidence.

## Purpose
Preserve conversation history without confusing raw evidence with the derived knowledge model. Historical wording matters because later summaries can lose corrections, uncertainty, tone, chronology, or the reason a decision changed.

## Required source hierarchy
1. Raw/exported transcript when available.
2. User-supplied artifact or direct statement.
3. Repository/project artifact.
4. Conversation-derived synthesis.
5. Explicitly labeled inference.
6. Speculation.

A lower layer must never be presented as stronger evidence than its source.

## Recommended structure
```text
CONVERSATIONS/
  YYYY/
    YYYY-MM-DD__topic/
      RAW.md
      SUMMARY.md
      DECISIONS.md
      ENTITIES.md
      RELATIONSHIPS.md
      STATE_CHANGES.md
      OPEN_LOOPS.md
      SOURCES.md
```

## RAW.md
Preserve the supplied/exported conversation with minimal normalization. Keep speaker identity, timestamps, ordering, and original wording when those are available. Do not silently remove corrections, disagreements, rejected ideas, or failed interpretations that explain later state.

## SUMMARY.md
Summarize purpose, developments, conclusions, important context, and current state. A summary is not a transcript. It may compress language, but it must preserve uncertainty, chronology, causality, and meaningful distinctions.

## DECISIONS.md
Record decisions that changed project state. For every major decision, preserve:
- decision
- date/context
- reason
- alternatives considered
- rejected alternatives
- affected nodes
- later reversal/supersession if any

## ENTITIES.md
Record entities introduced or modified in the conversation. Entity types include project, person/character, concept, world, location, system, technology, artifact, event, question, decision, and relationship.

## RELATIONSHIPS.md
Capture relationships whose existence or meaning changed. Do not merely list co-occurrence. Record the semantic edge and its direction when direction matters.

## STATE_CHANGES.md
Record before -> after changes. This is critical when a conversation corrects earlier memory, changes canon, retires an approach, or changes the current implementation.

## OPEN_LOOPS.md
Preserve unresolved questions, missing information, dependencies, and decisions intentionally deferred. Unknown must remain unknown.

## SOURCES.md
Record provenance for important extracted facts. When possible include conversation identifier, timestamp, source location, artifact path, or other stable reference.

## Extraction pipeline
1. Preserve raw source.
2. Identify the conversation's actual purpose.
3. Detect projects and anchor concepts.
4. Extract durable entities.
5. Extract explicit decisions.
6. Detect corrections and reversals.
7. Detect state changes.
8. Detect contradictions.
9. Capture relationships.
10. Capture unresolved loops.
11. Update canonical nodes only where evidence warrants it.
12. Update the relationship graph.
13. Update the timeline.
14. Attach provenance and certainty.
15. Re-check whether the resulting summary adds genuinely new information or merely paraphrases existing memory.

## Correction protocol
When the user corrects the assistant, the correction becomes the authoritative current statement when the user clearly establishes it. Preserve the prior mistaken interpretation only as historical context when it explains project evolution or avoids repeating the same mistake.

## Conflict protocol
If two conversations disagree:
- preserve both source claims;
- compare dates and context;
- determine whether one superseded the other;
- mark the current state explicitly;
- preserve unresolved conflict when the evidence cannot decide.

Never silently harmonize incompatible canon.

## Compression protocol
Compression is permitted only when it preserves:
- meaning
- uncertainty
- causality
- chronology
- constraints
- exceptions
- relationships
- why the information matters

A shorter file is not automatically a better memory.

## Retrieval protocol
For a future task, retrieve:
1. task purpose;
2. active project;
3. relevant anchors;
4. relevant relationships;
5. latest decisions/state changes;
6. unresolved loops;
7. raw evidence only where precision requires it.

The objective is maximum useful coherence per token, not maximum context length.

## Anti-hallucination rule
Never fill missing historical context with a plausible invention. Use the current epistemic status classes defined by `CANON_AND_PROVENANCE.md`—for example `UNKNOWN`, `DERIVED`, or `SPECULATIVE` as appropriate. Do not revive the historical V3 `INFERRED` label as a current status vocabulary.

## Maintenance rule
Before creating a new archive document, check for an existing document with overlapping purpose. Prefer updating, merging, or superseding an existing node over creating another near-duplicate.
