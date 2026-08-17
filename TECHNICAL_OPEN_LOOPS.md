# Technical Open Loops & Future Architecture

## Memory ingestion
A future ingestion pipeline should accept exported conversations and transform them into:
1. immutable raw source;
2. cleaned transcript;
3. summary;
4. extracted entities;
5. extracted relationships;
6. project references;
7. decisions and lessons;
8. unresolved questions;
9. embeddings/index records.

The raw transcript and distilled memory must remain separate so compression never becomes the only source of truth.

## Retrieval
A mature retrieval layer should combine:
- exact text search
- semantic similarity
- graph/relationship traversal
- recency
- importance
- project relevance
- current-vs-historical state

A single vector similarity score is not enough for deep personal context.

## Conflict resolution
Memory retrieval must avoid returning obsolete decisions as current truth. Recommended ranking signals include current status, update time, provenance quality, project relevance, and explicit supersession relationships.

## Context assembly
The AI context builder should assemble:
- immediate task context
- active project context
- relevant anchor neighborhood
- recent decisions
- constraints
- unresolved questions
- only the minimum supporting historical material required

The objective is not maximum context length. It is maximum useful coherence per token.

## Local-first principle
The canonical vault should remain usable offline. Cloud services should be optional accelerators, not single points of failure.

## Security boundary
Secrets, credentials, API keys, session tokens, and private authentication material must never be committed into the knowledge vault. The vault is for knowledge, not credentials.

## Scaling strategy
Start with Markdown + links + simple search. Add embeddings, databases, MCP routing, synchronization, and automation only when measured friction justifies them.

## Agent integration
An MCP layer can expose focused operations such as:
- search_memory
- fetch_anchor
- fetch_project_context
- fetch_relationships
- fetch_recent_decisions
- fetch_open_loops
- record_memory
- supersede_memory

Tools should return structured context rather than dumping the entire vault.

## Long-term goal
The architecture should make switching models cheap. A model may change, but the user's accumulated knowledge, project history, reasoning patterns, and relationships should remain intact.
