# Conversation Archive Specification

## Purpose
Define how future exported conversations should enter this vault without destroying chronology, provenance, or context.

## One conversation record
Recommended metadata:
- conversation id
- date/time
- model/provider
- title
- project
- participants
- source format
- import date
- checksum when available
- summary
- extracted entities
- decisions
- open loops
- canonical updates

## Message preservation
When a verbatim transcript is available, preserve it separately from its synthesis. Never overwrite the raw source with a summary.

## Extraction passes
1. Preserve raw transcript.
2. Detect durable facts.
3. Detect project changes.
4. Detect new concepts.
5. Detect decisions and reversals.
6. Detect unresolved questions.
7. Detect relationships.
8. Update relevant entity notes.
9. Append timeline events.
10. Recompute high-density summaries.

## Conflict handling
If two conversations disagree:
- preserve both source claims;
- identify dates;
- determine whether one supersedes the other;
- record the conflict explicitly;
- do not silently merge incompatible canon.

## Compression rule
Summaries may compress language but must preserve meaning, uncertainty, chronology, and causal relationships. A summary must never become more certain than its source.

## Future AI behavior
Before answering a new question, retrieve the narrowest relevant anchor set first; then expand to related nodes only as needed. This keeps context dense without flooding the model with unrelated history.
