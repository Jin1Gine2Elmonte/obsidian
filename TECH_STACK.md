# Technical Projects & Stack — Navigation Layer

> This file owns the high-level map of technical interests/projects and where their detailed records belong. It is not the canonical owner of implementation details.

## Core technical domains

### External AI memory / Obsidian
Purpose: portable memory across AI models and applications.

Architecture owner: `AI_MEMORY_ARCHITECTURE.md`.
Archive governance: `KNOWLEDGE_OWNERSHIP_MAP.md`, `ARCHIVE_MAINTENANCE_LOOP.md`.
Historical tool/workflow lineage: `TECH/TOOL_WORKFLOW_HISTORY.md`.

### Nexus
Purpose: evolving family of agent/server, orchestration, memory, tool-routing, and gateway experiments.

Generation rule: different repositories/iterations remain distinct until evidence links them.
Historical lineage: `TECH/NEXUS_HERMES_HISTORY_RECOVERY.md`.

### Hermes
Purpose: agent/deployment and knowledge-system experiments.

Historical implementation included CLI/YAML, Docker, Northflank, storage, embeddings, tool constraints, and workflow automation.
Historical lineage: `TECH/NEXUS_HERMES_HISTORY_RECOVERY.md`.

### MCP / bridges / Android interaction
MCP, local APIs, plugins, synchronization, Android accessibility services, and IME/context injection are **access layers** around durable knowledge rather than canonical storage.

### Model ecosystem
Recurring exploration includes Gemini, ChatGPT, DeepSeek, GLM, Nemotron, Google GenAI SDK, image/video/audio generation, voice generation, and agentic systems.

Model-specific experiments should be kept separate from durable knowledge unless they create a stable project requirement or decision.

### Deployment / infrastructure
Historical exploration includes Fly.io, Northflank, Oracle Cloud, Docker, GPU hosting, rclone, and related deployment approaches.

Operational rule: cost, reliability, practical simplicity, and actual utility outrank theoretical architectural complexity.

### Web / application experiments
Historical exploration includes WordPress, Netlify, dark novel websites, HTML RPG interfaces, React/Firestore concepts, Tachiyomi, and related personal applications.

Detailed historical tool/workflow context: `TECH/TOOL_WORKFLOW_HISTORY.md`.

## Technical constraints / lessons

- A technically larger architecture is not automatically better.
- Persistent memory should remain usable if a particular MCP server, semantic search system, provider, or hosted service disappears.
- External access layers should never silently replace the source of truth.
- New infrastructure should solve a demonstrated bottleneck or requirement.
- A tool is part of a workflow, not the workflow itself; replacement of a tool should not erase the underlying project intent or knowledge.

## Detailed-history boundary
For detailed deployment incidents, repository artifacts, model comparisons, code, or experiments, use the project-specific technical records rather than expanding this overview.

## Cross-project principle
Technical systems and fictional concepts may share vocabulary (memory, forgetting, agents, worlds, reality), but conceptual similarity does not create technical or fictional continuity.
