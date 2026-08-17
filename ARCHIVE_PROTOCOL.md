# Archive Protocol

This document defines how the external memory should grow over time.

## Status labels
Use explicit epistemic status where appropriate:
- CANON: directly established by the user.
- CURRENT: latest known state, potentially replaceable.
- HISTORICAL: true of an earlier phase.
- INFERRED: supported by context but not directly established.
- SPECULATIVE: creative possibility, not canon.
- RETIRED: intentionally abandoned.
- UNKNOWN: insufficient information.

## Provenance
Whenever practical, each important note should record where it came from:
- direct user statement
- conversation summary
- artifact/repository
- technical experiment
- model inference

Do not transform an inference into a fact merely because it appears in a summary.

## Temporal rule
Projects evolve. A later decision should not erase the fact that an earlier architecture existed. Preserve evolution when it explains why the current design looks the way it does.

## Anchor promotion
Promote a concept from an ordinary note into an anchor when it:
1. recurs across multiple conversations;
2. generates multiple dependent concepts;
3. affects important decisions;
4. acts as a bridge between separate projects;
5. has enough internal structure to justify its own knowledge node.

## Relationship rule
When two notes repeatedly influence one another, create an explicit relationship instead of relying on both files merely mentioning the same word.

## Contradiction rule
If two records conflict:
1. preserve both;
2. check their dates;
3. determine whether one superseded the other;
4. mark unresolved contradictions explicitly.

Never silently harmonize incompatible canon.

## Memory compaction
Summaries should compress repetition without destroying causality or nuance. A summary is successful only if another model can reconstruct why a fact matters, not merely what the fact says.

## Conversation import rule
When full conversation transcripts become available, keep the raw transcript separate from the distilled memory. Raw history is evidence; distilled memory is the working model.

## Update rule
Every substantial future change should preferably create a versioned commit and update the relevant anchor, relationship, project, and timeline notes rather than appending an undifferentiated wall of text.
