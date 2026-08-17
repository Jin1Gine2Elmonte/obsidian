# Decisions, Lessons, and Evolution

## Why this archive exists
The user wants continuity across AI systems instead of repeatedly rebuilding context from scratch. The repository therefore functions as a durable external memory layer.

## Important architectural lesson
When a platform appears unable to integrate directly with another platform, the preferred response is not to stop at "impossible". Find a technically correct alternate integration path. A prior Nexus concept used an external cognition port with a Gateway server, where ChatGPT interacts with the Gateway through an MCP operation such as `nexus_consult`, while Nexus retains its internal autonomy.

## Important workflow lesson
A recurring risk is architectural overexpansion: a promising idea can immediately become a grand system, followed by a move to another tool before the previous system reaches a stable working state. Future planning should distinguish:
- idea
- prototype
- working minimum
- stable system
- expansion

Do not confuse the conceptual scale of an idea with the amount of infrastructure it needs today.

## Memory lesson
A large text dump is not automatically good memory. Durable memory requires structure, provenance, relationships, temporal state, and distinction between fact, decision, experiment, and speculation.

## Writing lesson
Depth and mystery are not substitutes for movement. If a scene is obscure, first diagnose whether the obscurity is intentional or whether the scene lacks causal clarity, emotional progression, or a clear purpose.

## Tool lesson
The user expects tools to perform real work when they are available. When a tool cannot execute a requested operation, state the exact boundary rather than replacing the task with a generic tutorial.

## Preservation lesson
Existing work should be preserved unless a change is explicitly requested. When revising an artifact, protect its established composition and constraints.

## Current strategic principle
Build the smallest complete foundation first, then let complexity emerge from actual need. The user's ambitions can remain enormous without forcing every first implementation to be enormous.
