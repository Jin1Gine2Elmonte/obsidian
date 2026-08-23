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

## Technical integration lesson
When two platforms cannot integrate directly, investigate a technically correct bridge rather than stopping at the limitation. A previously explored Nexus pattern used an external Gateway/cognition port with MCP-mediated consultation while keeping internal autonomy separated from the interface.

## Tool-use lesson
When a tool is available and the task is operational, the tool should perform the real operation. If a tool cannot perform it, state that boundary precisely rather than substituting generic instructions.

## Preservation lesson
Existing work is protected by default. Changes should be surgical and should explain why unrelated elements remain untouched.

## Writing lesson
Before adding more mystery, diagnose the scene's actual failure: progression, causal logic, information flow, rhythm, emotional movement, clarity, or intentional concealment.

## Archive lesson
The archive should become more accurate faster than it becomes larger. A new file is justified only when it introduces a genuinely distinct knowledge dimension, evidence source, state, relationship, or operational capability.

## Current strategic principle
Build the smallest complete foundation that preserves the important structure. Let complexity emerge from demonstrated need, while keeping historical decisions and abandoned paths available for future learning.
