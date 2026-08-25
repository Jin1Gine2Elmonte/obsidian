# Decisions, Lessons, Experiments, and Evolution

## Purpose
This file owns lessons learned from actual work, decisions that changed project direction, and experiments whose outcomes materially affect future choices. It is not the owner of canon, reasoning architecture, or raw conversation evidence.

## Decision model
A decision should record:
- decision;
- context/problem;
- options considered;
- chosen direction;
- reason;
- constraints preserved;
- downstream effects;
- current status;
- historical status when later superseded.

## Lesson model
A lesson should record:
- observation;
- repeated evidence or triggering failure;
- lesson extracted;
- domains where it applies;
- confidence;
- what future work should do differently.

## Experiment model
An experiment should record:
- hypothesis;
- implementation/test;
- result;
- failure mode;
- what changed in the model;
- whether the approach remains viable.

## High-value lessons established so far

### L-001 — Volume is not memory
Repeated expansion showed that adding summaries without adding genuinely new information, provenance, relationships, or historical state produces archive inflation rather than knowledge gain.

Applies to: memory, fiction archives, technical documentation, project management.

### L-002 — Review before expansion
Existing nodes must be inspected before creating new ones. Update, merge, narrow, or retire when the information already has a legitimate owner.

### L-003 — Evidence beats elegant synthesis
A direct user statement or original scene outranks a beautiful interpretation. When stronger evidence appears, revise the current model and preserve the old interpretation as history when useful.

### L-004 — Similarity is not identity
Shared names, motifs, biographies, powers, or themes do not prove continuity across project generations. This lesson is directly relevant to the unresolved Jin/Ryota problem and the Jin version lattice.

### L-005 — Mystery cannot replace movement
Depth and mystery must not be used to hide missing causality, emotional progression, pacing, or scene purpose.

### L-006 — Protect established constraints
When revising an artifact, unrelated changes are regressions. Explicit composition, visual, narrative, or technical constraints must remain protected unless intentionally changed.

### L-007 — Complexity must earn its place
Promising concepts can produce oversized architectures too early. Distinguish idea -> prototype -> minimum working system -> stable system -> expansion. Conceptual ambition does not require immediate infrastructure maximalism.

### L-008 — Preserve the failure path
When a previous approach is corrected, preserve what failed and why rather than only keeping the polished replacement. The failure often contains the most useful future guardrail.

### L-009 — Canon and analysis must remain separate
A logically necessary consequence is not automatically canon. Analytical consequences should remain marked as derived until source evidence establishes them.

### L-010 — Relationships deserve first-class status
A relationship may carry more explanatory value than either endpoint. Preserve its origin, changes, asymmetry, evidence, and consequences rather than merely listing the two entities together.

### L-011 — An instruction layer should not imprison an open-ended process
A recent memory-recovery automation was initially given a detailed execution prompt. That prompt became an unwanted constraint because it prescribed the search path, even though the intended operation was open-ended continuation driven by the live context. The durable lesson is that an autonomous recurring process can require a minimal trigger rather than a fixed mission statement when the real objective is to preserve freedom of navigation and allow the next path to emerge from current state.

**Decision:** when the user's intended recurring action is intrinsically open-ended, preserve the trigger with the smallest sufficient instruction and let the current context, repository state, and active continuity determine the local work.

**Status:** durable collaboration/automation lesson, scoped to open-ended continuation rather than all scheduled tasks.

## Technical experiment lineage

### T-001 — External access should not own memory
Experiments around MCP, gateways, agent servers, Android context injection, and cross-model access repeatedly led to the same architectural boundary: access layers may retrieve or write knowledge, but the durable vault must remain independently usable.

**Decision:** keep Obsidian/Markdown as the human-readable durable knowledge substrate; treat MCP, APIs, gateways, plugins, accessibility/IME bridges, semantic indexes, and hosted services as replaceable access or acceleration layers.

**Why:** a provider, bridge, model, MCP server, or retrieval service can disappear or fail without the user's accumulated knowledge becoming inaccessible or rewritten.

**Status:** durable architectural principle.

### T-002 — Retrieval must be hybrid rather than vector-only
Memory-system exploration exposed that semantic similarity alone cannot reliably preserve chronology, supersession, identity/version boundaries, relationships, or current-vs-historical state.

**Decision:** a mature retrieval layer should combine exact search, semantic similarity, graph/relationship traversal, recency, importance, project relevance, and temporal state.

**Status:** architecture target; detailed implementation remains open.

### T-003 — Tool availability is a runtime constraint, not a theoretical capability
Agent/Hermes work repeatedly exposed cases where a capability could exist in an architecture but be disabled, unavailable, or constrained at runtime.

**Lesson:** design operational paths around actually available tools and permissions, and preserve explicit fallback behavior.

**Status:** durable operational lesson.

### T-004 — Deployment limits are part of architecture
Experiments involving hosted deployment, containers, GPU/resource availability, and service providers showed that theoretical server architecture can be invalidated by hard platform limits, quotas, or resource availability.

**Lesson:** architecture decisions must be checked against provider constraints before being treated as executable plans.

**Status:** durable engineering lesson.

### T-005 — External cognition should remain separated from internal autonomy
The Nexus/Gateway exploration established a useful architectural pattern: an agent can consult an external cognition service or model through a bridge while retaining its own orchestration/autonomy boundary.

**Lesson:** consultation, memory, tool execution, and core control do not need to be collapsed into one service.

**Status:** reusable architectural pattern, not a requirement for every implementation.

### T-006 — Model changes should not force knowledge rewrites
Exploration across multiple model ecosystems reinforced that model-specific prompts, adapters, and tool integrations should sit above a stable knowledge model.

**Decision:** changing the model/provider should be treated as a transport/runtime change, not a reason to rewrite durable memory.

**Status:** durable architectural principle.

### T-007 — Minimum viable memory before advanced retrieval
The memory architecture repeatedly converged on a simpler base: Markdown + explicit ownership + links + provenance should remain useful before embeddings, databases, MCP routing, synchronization, or automation are added.

**Lesson:** advanced retrieval should solve measured friction rather than serve as proof of architectural sophistication.

**Status:** durable design principle.

## Technical preservation rules
Technical experiments should preserve:
- what was actually tested versus merely proposed;
- the provider/tool constraints encountered;
- the failure mode;
- the workaround, if any;
- whether the workaround became architecture or remained an experiment;
- whether a later project generation superseded the approach.

A technical architecture summary must never retroactively turn an untested idea into an implemented system.

## Meta-lesson
A durable lesson should remain linked to the evidence pattern that produced it. When future work contradicts a lesson, update the lesson's confidence or scope rather than silently preserving it as universal law.

## Ownership
- Lesson definitions and current strategic interpretation: `DECISIONS_AND_LESSONS.md`
- Reasoning principles: `REASONING_ARCHITECTURE.md`
- Evidence/status: `CANON_AND_PROVENANCE.md`
- Knowledge-state change: `KNOWLEDGE_STATE_TRANSITIONS.md`
- Archive structure: `KNOWLEDGE_OWNERSHIP_MAP.md`
