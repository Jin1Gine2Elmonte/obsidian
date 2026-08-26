# NEXUS / Hermes — Historical Recovery Record

## Purpose
This file is a **historical recovery owner** for the evolution of the user's NEXUS/Hermes/agent-infrastructure work. It deliberately separates durable remembered context from repository-level evidence that has not yet been recovered.

## Evidence boundary
The current assistant context preserves a substantial amount of project history, but the present Obsidian repository does not yet contain the original NEXUS/Hermes repositories, full deployment logs, or complete conversation transcripts. Therefore this record must not pretend that remembered summaries are equivalent to source evidence.

## Durable remembered history

### NEXUS
NEXUS has appeared as an evolving agent/server architecture rather than one immutable implementation. The remembered design space includes:
- agent orchestration;
- model routing;
- external cognition;
- durable memory;
- MCP/tool integration;
- gateway/bridge concepts;
- context assembly;
- a "NEXUS OMNI-SERVER" direction;
- later architectural thinking around sovereign/central coordination.

Different NEXUS generations must remain distinct until source evidence links them.

### Hermes
Hermes has appeared as a practical agent/deployment environment involving:
- CLI operation;
- YAML configuration;
- Docker;
- Northflank deployment;
- storage and embeddings;
- tool availability/constraints;
- browser/tool disablement in some environments;
- deployment and workflow automation.

The exact mapping between Hermes generations, repositories, configs, and later NEXUS architecture is not fully recovered here.

## Technical lessons already remembered
- Tool availability is an architectural variable, not a cosmetic feature.
- A model's explanation of its own failure is not proof of the true cause.
- When behavior differs between models in an apparently identical environment, investigate prompt/context assembly, model configuration, routing, proxy behavior, tool permissions, and runtime state.
- Memory should remain external to the model where portability matters.
- Access/orchestration layers must not become the source of truth.
- Swapping models should not require rewriting durable memory.
- Complexity must answer a demonstrated requirement.

## Concrete incident / investigation memory
These are remembered from prior collaboration and remain **contextual until original logs or source conversations are recovered**.

### 1. Hermes tool-availability anomaly
Hermes was observed in environments where browser access and/or other tools were disabled. The important lesson was that an agent can appear architecturally capable on paper while behaving very differently at runtime because the actual tool surface is narrower than the nominal design.

### 2. 401 investigation
A remembered debugging branch involved an HTTP **401 Unauthorized** failure around the NEXUS/Hermes/tool-routing ecosystem. The correct diagnostic framing was not to immediately blame the language model. Possible layers included credentials/authentication, proxy configuration, routing, the upstream service, environment variables, or a tool adapter. The exact root cause is **not recovered here** and must not be invented.

### 3. Same-environment / different-model behavior
A recurring debugging situation involved models operating in an apparently shared environment but exhibiting materially different behavior. The investigation direction expanded beyond model quality to include prompt layering, context assembly, proxy behavior, model routing, tool exposure, configuration, and runtime state.

### 4. Parallel-model investigation
The user explicitly explored using multiple independent models in parallel to investigate difficult failures rather than trusting one model's diagnosis. The intent was to reduce correlated blind spots and force comparison of competing explanations.

### 5. Architecture versus implementation
NEXUS concepts sometimes became much larger than the amount of code or infrastructure actually verified. A recurring correction was therefore to distinguish:
`idea -> architecture proposal -> prototype -> deployed implementation -> tested behavior`.
A later conceptual architecture must not be treated as an implemented generation merely because it is more complete on paper.

### 6. Memory as an external substrate
A recurring design direction moved durable memory outside the active model. Obsidian/Markdown was treated as a human-readable persistence layer; MCP, APIs, gateways, agents, and model-specific adapters were treated as access paths rather than owners.

### 7. Deployment constraints as design variables
Northflank, Fly.io, Oracle Cloud, local GPU deployment, and other hosting routes were repeatedly evaluated against practical cost, resource, and platform constraints. These constraints were treated as architecture inputs rather than as after-the-fact inconveniences.

## Deployment incidents remembered
- Fly.io produced an organization-level CPU limitation indicating a maximum of 4 CPU cores per machine for the relevant organization state.
- Northflank was used/explored for Hermes and related deployments.
- Oracle Cloud was explored as a possible hosting/free-tier route.
- GPU hosting and local-model deployment were evaluated against practical cost/resource limits.

## Historical experiments to recover from source
1. Exact NEXUS repository/repository-generation map.
2. Exact Hermes repository and configuration history.
3. Dockerfiles, YAML files, deployment manifests, and scripts.
4. The chronology of NEXUS OMNI-SERVER iterations.
5. The transition from ordinary agent behavior to external-cognition architecture.
6. Model-routing experiments and model/provider comparisons.
7. Proxy/tool-routing failures, including the remembered 401 investigation.
8. Browser/tool disablement incidents inside Hermes.
9. Northflank/Fly.io/Oracle deployment attempts and their exact outcomes.
10. Embedding/storage architecture experiments and what was actually deployed.
11. MCP/OpenClaw/gateway integration experiments.
12. Any architecture that was proposed but never implemented.

## Required recovery record for each generation
For each NEXUS/Hermes generation, capture:
- generation identifier/name;
- repository;
- approximate date/phase;
- goal;
- model(s);
- tools;
- memory mechanism;
- routing/orchestration;
- deployment target;
- implemented state;
- failures;
- known constraints;
- design decisions;
- what replaced it;
- evidence source.

## Anti-conflation rule
Do not merge NEXUS, Hermes, OpenClaw, MCP gateway concepts, or ordinary model configurations merely because they solve related problems. Similar architecture is not proof of shared implementation lineage.

## Why this gap matters
The technical memory has been summarized repeatedly, but implementation-level history is precisely where many high-value causal details live: what actually worked, what failed, which constraints were real, and which architectures were only speculative.

The next definitive recovery target is therefore **original repository/configuration/log evidence**, not another summary of the same remembered concepts.

## Cross-links
- Relationship registry: `RELATIONSHIPS.md` — central historical/technical relationship states involving Nexus, Gateway, and Hermes/deployment.
- Technical navigation: `TECH_STACK.md`.
- AI-memory architecture: `AI_MEMORY_ARCHITECTURE.md`.
