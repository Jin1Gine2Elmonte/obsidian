# AI Memory Architecture

## Vision
The long-term objective is a portable external memory layer that survives changes in AI models, applications, and providers. Obsidian is the primary source of truth. Hosted services, when used, should be minimal bridges/gateways rather than the authoritative storage layer.

## Target environment
The user has specifically explored Obsidian on Android with long-term memory accessible by ChatGPT, Gemini, Qwen, and other AI systems through MCP.

## Desired knowledge model
The memory system should represent:
- conversations
- messages
- summaries
- projects
- characters
- worlds
- concepts
- technologies
- decisions
- dates
- importance
- provenance
- relationships
- synchronization state

The goal is not merely keyword retrieval. The archive should preserve semantic relationships and explain why a fact matters.

## Retrieval philosophy
A useful memory system should distinguish:
1. Stable facts.
2. Current decisions.
3. Historical experiments.
4. Speculative ideas.
5. Abandoned approaches.
6. Relationships between concepts.
7. Source/provenance.

When information changes, preserve the historical state when it is useful rather than silently replacing it.

## Obsidian role
Obsidian is the human-readable knowledge substrate. It should remain the canonical source of truth. AI access requires a bridge such as a local API, MCP server, plugin, or synchronization mechanism.

The user prefers avoiding unnecessary cloud storage and unnecessary terminal/Termux complexity. The simplest genuinely workable architecture should win.

## Cross-model continuity
A recurring objective is continuity between ChatGPT, Gemini, Qwen, and other models. Conversation exports can be transformed into durable Markdown records. The resulting vault should be readable by both humans and machines.

## Android direction
The user has explored Android accessibility-service and input-method approaches that could automatically provide relevant context to AI applications. This is a possible interaction layer, not the canonical memory store.

## Possible data flow
AI conversation -> capture/export -> normalization -> entity/project extraction -> Markdown notes -> links/indexes -> semantic retrieval -> AI context.

The archive should remain useful even if semantic search or an MCP gateway is temporarily unavailable.

## Design principle
The memory system should behave more like a knowledge graph expressed through Markdown than a folder full of disconnected summaries. High-impact concepts become anchor nodes; related material links back to them.
