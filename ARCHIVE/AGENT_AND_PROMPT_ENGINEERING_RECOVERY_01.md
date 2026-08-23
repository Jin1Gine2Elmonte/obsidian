# Agent & Prompt Engineering Recovery — Pass 09

## Purpose
Preserve the historical working knowledge around how the user designs, diagnoses, and steers AI agents and model interactions. This is a recovery layer, not a canonical technical specification.

## Evidence boundary
This pass is reconstructed from durable conversational context and summaries currently accessible. Exact prompts, code, and chronology require original conversation exports or repository artifacts.

---

# I. Prompting philosophy

- The user often asks for prompts that cause another model/agent to **investigate rather than merely answer**.
- A useful prompt should define the objective, force exploration of competing explanations, preserve uncertainty, and require evidence before convergence.
- The user dislikes prompts that produce a polished answer without demonstrating that the underlying problem was actually explored.
- For difficult technical problems, a prompt may explicitly request parallel independent model analysis so that multiple hypotheses can be compared rather than allowing one model's first idea to dominate.
- The user values prompts that make the agent inspect the actual environment/repository/tooling instead of inventing a plausible architecture from the prompt alone.

## Investigation pattern
`Observe -> enumerate hypotheses -> inspect environment -> test/compare -> eliminate -> synthesize -> state confidence -> recommend next action`

This pattern recurs in debugging, repository analysis, memory recovery, and architecture design.

---

# II. Model-behavior diagnosis

When a model behaves unexpectedly, the user has considered several possible causes:
- system/developer prompt effects;
- model-specific behavior;
- tool availability;
- disabled tools;
- proxy/gateway behavior;
- routing or model-selection errors;
- context assembly or truncation;
- environment/runtime configuration;
- hidden provider limitations;
- SDK or API differences.

A recurring lesson is that identical apparent environments do not prove identical effective environments.

The user prefers investigations that keep these causes separate until evidence narrows the hypothesis space.

---

# III. Parallel-model investigation

The user has explicitly explored using multiple fast models in parallel for technical diagnosis, especially when a single model appears biased toward an attractive but unsupported explanation.

The preferred structure is:
- independent analyses;
- explicit hypotheses;
- cross-review/comparison;
- shared evidence layer;
- disagreement preservation;
- final synthesis only after independent passes.

The number of parallel models can vary by task; the principle is independence before consensus.

---

# IV. Hermes behavior and operational constraints

- Hermes has been treated as an actual agent/deployment environment rather than only as a prompt wrapper.
- Tool availability has varied by environment, including situations where browser or other tools were unavailable/disabled.
- When a tool was unavailable, the user wanted the diagnosis to distinguish between a model reasoning failure and an infrastructure/tooling failure.
- This encouraged a broader debugging principle: inspect the runtime/toolchain before rewriting the agent prompt indefinitely.

---

# V. NEXUS architectural direction

- NEXUS evolved around ideas of sovereignty, orchestration, external cognition, memory, MCP/tool routing, and an Omni-Server family of concepts.
- A persistent architectural concern is avoiding total dependence on a single external model/provider.
- External reasoning can be used as a cognition service while the system maintains a distinct internal state, memory, routing, and identity.
- This separation naturally produced the later distinction between:
  - durable memory/source of truth;
  - access layer;
  - reasoning engine;
  - orchestration layer.

---

# VI. MCP / gateway patterns

- MCP has been considered as a mechanism for exposing focused tools and memory operations to models.
- Gateway/proxy patterns can provide model access, tool routing, or external cognition without becoming the canonical source of knowledge.
- A bridge should be evaluated by what it actually enables and what failure modes it introduces, not only by architectural elegance.

---

# VII. Agent architecture evolution

A recurring evolutionary path is:

`single prompt -> tool-enabled agent -> orchestrated agent -> multi-model cognition -> external memory -> graph/retrieval layer -> distributed access`.

The user tends to push systems toward higher autonomy and continuity, but also reacts strongly when complexity grows faster than practical capability.

The resulting design tension is:

**maximum cognitive capability vs minimum necessary architecture**.

---

# VIII. Important failure mode: apparent intelligence vs actual operation

A model can produce sophisticated explanations while failing to perform the underlying operation or inspect the actual state.

The user therefore places high value on:
- direct tool execution;
- evidence from repositories/files;
- explicit state inspection;
- reproducible operations;
- commit/artifact traces;
- honest boundaries when an action was not actually performed.

This principle became especially relevant during the Obsidian/GitHub recovery work: architectural language must never substitute for real repository modification.

---

# IX. Prompt evolution as knowledge

Prompts themselves should be treated as historical artifacts when they materially change an agent's behavior.

A future recovery pass should preserve:
- prompt version;
- objective;
- constraints;
- model/tool environment;
- observed output;
- correction;
- resulting prompt change;
- why the change mattered.

This allows the archive to remember not only what an agent was asked to do, but how its behavior was shaped over time.

---

# X. Current recovery boundary

This pass preserves the durable architecture of the user's agent/prompt engineering practice. Exact prompt transcripts, model names/versions at each experiment, runtime configurations, error messages, and repository artifacts remain candidates for source-level recovery.
