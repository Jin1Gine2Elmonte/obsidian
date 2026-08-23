# Archive Deduplication Audit

## Purpose
Prevent the external memory system from becoming a collection of increasingly similar summaries.

## Current structural finding
Several layers intentionally repeat a concept from different angles: canonical fact, high-density synthesis, causal relation, recovery target, and negative rule. That repetition is useful only when each copy has a distinct function.

## Allowed repetition
A fact may appear in more than one place when the copies answer different questions:
- **Canon** — what is established.
- **Memory density** — how strongly/fully it is remembered.
- **Causal map** — what it changes or causes.
- **Relationship node** — how two entities affect one another.
- **Recovery matrix** — what evidence is still missing.
- **Negative knowledge** — what must not be assumed.

## Disallowed repetition
The same paragraph should not be cloned across files merely to make every file look complete.

Do not create:
- another generic Jin summary when `WORLD/JIN_CORE.md` already owns that function;
- another generic empire summary when `WORLD/EMPIRE.md` already owns it;
- another Strings of Fate memory dump when the dedicated archive already separates canon, memory, and recovery;
- another generic archive philosophy file when a protocol already governs the behavior.

## Consolidation rule
When two files converge on the same purpose:
1. choose the stronger canonical owner;
2. move genuinely new information into that owner;
3. convert the weaker file into a narrow cross-reference if it still has value;
4. delete it only when no unique information or historical value remains.

## Information-density test
Before adding content, ask:
- Does it add a fact?
- Does it add a relationship?
- Does it establish a temporal change?
- Does it preserve a correction/rejection?
- Does it reduce ambiguity?
- Does it improve source recovery?
- Does it change how another node should be interpreted?

If all answers are no, do not add it.

## Current duplication risk areas
- Jin core vs Jin memory-density vs Jin variant registry.
- Almont/Ryota dynamics vs state machine vs family triangle.
- Empire macro model vs institutional model vs logistics model.
- Garthin core vs memory-density extraction vs relational architecture.
- Adam core vs memory-density extraction vs interworld model vs variant discrimination.
- Strings of Fate canon vs expanded memory vs truth audit vs conversation index vs project frame.
- Timeline vs project-state transitions vs historical evolution map.

These are acceptable only when each file has a distinct ownership role. Ownership is now defined explicitly in `KNOWLEDGE_OWNERSHIP_MAP.md`.

## Concrete maintenance control
See `ARCHIVE_CLEANUP_BACKLOG.md` for the current node-by-node cleanup queue.

## Resolution status
The archive is no longer in a pure expansion phase. It has entered a **consolidation phase**: every new addition must be tested against existing ownership and duplicate risk, while existing nodes are progressively corrected and narrowed where necessary.

## Highest-priority cleanup principle
Prefer fewer high-integrity nodes with explicit ownership over many overlapping summaries.
