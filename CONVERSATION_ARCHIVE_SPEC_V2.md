# Conversation Archive Specification

Future imported conversations should preserve both raw evidence and derived knowledge.

## Recommended structure
```text
CONVERSATIONS/
  YYYY/
    YYYY-MM-DD__topic/
      RAW.md
      SUMMARY.md
      DECISIONS.md
      ENTITIES.md
      OPEN_LOOPS.md
      SOURCES.md
```

## Raw evidence
RAW contains supplied or exported conversation material with minimal transformation. A summary must never be presented as verbatim transcript.

## Derived layers
SUMMARY captures purpose, developments, conclusions, and important context. DECISIONS records durable changes. ENTITIES records introduced or modified nodes. OPEN_LOOPS records unresolved questions. SOURCES preserves provenance.

## Extraction pipeline
1. Preserve source.
2. Detect projects and anchors.
3. Extract entities.
4. Extract decisions.
5. Detect state changes.
6. Detect contradictions.
7. Capture unresolved loops.
8. Update canonical notes.
9. Update relationship graph.
10. Update timeline.
11. Attach provenance and confidence.

Rejected ideas remain historical data and should not silently become current canon.
