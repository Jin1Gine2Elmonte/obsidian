# AI Memory Architecture

## Ownership
This file owns the **technical architecture and operating assumptions** of the external AI-memory system. It does not own fiction canon, project facts, or detailed archive rules.

## Vision
Build a portable external memory layer that survives changes in AI models, applications, and providers. Obsidian remains the human-readable source of truth; MCP/API/gateway layers are access mechanisms, not authoritative storage.

## Target environment
The user has explored Obsidian on Android with long-term memory exposed to ChatGPT, Gemini, Qwen, and other AI systems through MCP and related bridges.

## System boundary
The architecture has four conceptual layers:

1. **Evidence layer** — raw conversations and source material when available.
2. **Knowledge layer** — structured Markdown entities, projects, relationships, decisions, chronology, and canon.
3. **Retrieval layer** — indexes, semantic search, graph navigation, and context assembly.
4. **Access layer** — MCP, APIs, plugins, agents, Android interaction mechanisms, and other clients.

The repository is durable only when the knowledge layer remains usable without the access layer.

## Knowledge model
The memory system needs to represent at minimum:
- conversations and messages;
- entities and projects;
- worlds and concepts;
- decisions and changes;
- dates and temporal state;
- provenance;
- relationships;
- synchronization state.

Detailed ownership and epistemic rules live elsewhere:
- `KNOWLEDGE_OWNERSHIP_MAP.md`
- `CANON_AND_PROVENANCE.md`
- `ARCHIVE_PROTOCOL.md`
- `CONVERSATION_ARCHIVE_SPEC_V2.md`

## Retrieval philosophy
Retrieval should assemble the smallest context that preserves the meaning required for the current task. A retrieval system should be able to distinguish current state from historical state and evidence from synthesis.

It should preferentially follow anchor and relationship edges before falling back to broad keyword dumps.

## Update flow
```text
conversation/source
    -> capture
    -> normalize
    -> identify entities and project/version
    -> extract evidence
    -> update canonical owner
    -> propagate dependent changes
    -> update indexes/retrieval views
    -> record superseded state where necessary
```

The archive-maintenance rules governing this flow are defined in `ARCHIVE_MAINTENANCE_LOOP.md`.

## Obsidian role
Obsidian is the durable, human-readable substrate. A hosted service may provide a bridge or retrieval layer, but must not silently become the canonical store.

## Cross-model continuity
The same knowledge model should be consumable by ChatGPT, Gemini, Qwen, and other systems. Model-specific prompts or adapters may change; the underlying knowledge should not need to be rewritten for each model.

## Android interaction layer
The user has explored accessibility-service and IME approaches for injecting relevant context into AI applications. These are interface strategies only; they do not own memory state.

## Architecture constraint
Prefer the simplest architecture that actually satisfies the requirement. Complexity is justified by measurable retrieval, synchronization, provenance, or automation needs—not by theoretical elegance alone.

## Failure tolerance
The vault should remain useful when semantic search, MCP, a bridge server, or a particular AI provider is unavailable. No single access mechanism should become a single point of failure for the accumulated knowledge.
