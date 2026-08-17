# Technical Architecture — Deep Context

## Core strategic problem
The user is not merely trying to build an AI chatbot. The recurring objective is to construct systems in which models can act over persistent tools, memory, projects, and external knowledge while preserving continuity across providers.

## External cognition model
A recurring architecture pattern is an external cognition layer:

Model/UI -> Gateway/API/MCP -> Agent/Knowledge System -> Memory/Tools/External Services

The key idea is that the model should not need to contain every capability internally. The external system can provide memory, tools, search, project state, and specialized execution.

## Nexus pattern
Nexus has been explored as such an external cognition/agent layer. Multiple versions exist. The name should not be treated as one frozen implementation.

Recurring conceptual modules:
- Gateway
- agent/orchestration
- model routing
- tool access
- persistent memory
- retrieval
- project context
- external service connectors
- deployment

A previously discussed integration idea involved a cognition port/Gateway that exposes an MCP operation such as `nexus_consult`. ChatGPT can call the gateway while Nexus retains its own internal autonomy and context.

## Memory system
Memory should separate retrieval from storage. Obsidian/Markdown can remain canonical while embeddings, indexes, caches, or MCP services become disposable acceleration layers.

This separation matters because it allows:
- changing embedding models without rewriting the archive
- replacing MCP servers without losing knowledge
- moving between devices
- auditing source material
- human editing
- long-term portability

## Retrieval architecture
A high-quality retrieval path should operate in stages:

1. Identify the active project/context.
2. Retrieve anchor nodes.
3. Retrieve directly connected entities.
4. Resolve temporal state.
5. Retrieve supporting details.
6. Construct a compact context packet.
7. Generate.
8. Capture new decisions/facts for later archival.

This is better than dumping the entire vault into every model prompt.

## Semantic memory
Embeddings are useful for similarity but should not become the only memory mechanism. Structured metadata, links, exact text search, chronology, and provenance remain necessary.

A hybrid system can combine:
- exact search
- semantic search
- graph traversal
- recency
- importance
- project scope
- source confidence

## Deployment philosophy
The user has investigated Fly.io, Northflank, Oracle Cloud free tier, Docker, and GPU hosting. Cost and operational complexity are recurring constraints.

The architecture should therefore distinguish:
- canonical storage
- compute
- retrieval acceleration
- UI
- orchestration
- deployment

Only components that solve a demonstrated problem should become permanent.

## Hermes lessons
Hermes work involved CLI/YAML, Docker, Northflank deployment, knowledge storage, embeddings, and GitHub Actions. Tool limitations are part of the practical architecture: a system's theoretical capabilities do not matter if its actual runtime lacks the required tool.

## Android layer
Android accessibility/IME concepts have been explored as a universal context-injection interface. This layer can help applications that cannot directly expose their context APIs. It should remain separate from canonical memory.

## Portability principle
The archive should remain legible if every external service disappears tomorrow. Markdown is therefore strategic, not cosmetic.

## Long-term target
The mature system can become a personal knowledge OS where models are replaceable reasoning engines and the vault is persistent world state.
