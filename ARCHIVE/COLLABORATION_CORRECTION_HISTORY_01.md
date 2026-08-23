# Collaboration Correction History — Pass 07

## Purpose
Preserve recurring correction patterns in the collaboration itself: moments where the user rejected an approach, clarified a boundary, exposed a reasoning error, or forced a change in how the work should be conducted.

This is not a psychological profile and not a complete transcript. It records durable working corrections that materially affect future collaboration.

## I. Core correction: summary is not memory

Repeated correction pattern:
- The assistant produced increasingly large summaries/files.
- The user pointed out that this could create the appearance of memory without recovering the actual missing material.
- The correction established that **more text is not equivalent to more recovered knowledge**.

Result:
- memory coverage auditing;
- recovery matrix;
- raw-evidence boundary;
- current-context recovery layers.

## II. Core correction: do not mistake the latest synthesis for the whole history

The user repeatedly objected when a later summary was treated as though it represented everything discussed historically.

Resulting requirement:
- current memory is partial;
- historical evolution matters;
- older branches must not disappear merely because a newer formulation is cleaner;
- raw conversations remain the final recovery target.

## III. Core correction: stages can have different purposes

The user has explicitly distinguished between phases where the task is to build the archive and phases where the task is to build the model/system that consumes the archive.

Resulting requirement:
- do not collapse archive construction, model construction, and operational testing into one task;
- preserve the purpose of each stage.

## IV. Core correction: do not propose a workaround that the prior reasoning already ruled out

Repeated frustration occurred when a later suggestion reintroduced a technique/path that had already been shown unsuitable by prior conversation.

Result:
- preserve negative knowledge;
- record rejected paths and why they were rejected;
- check existing reasoning history before proposing a new workaround.

## V. Core correction: the user expects investigation, not premature explanation

In technical debugging and architecture, the preferred process is to keep multiple plausible causes alive until evidence narrows them.

Common investigation dimensions have included:
- model behavior;
- tool availability;
- system/developer prompts;
- proxy code;
- routing;
- context assembly;
- provider behavior;
- environment/runtime differences;
- configuration.

Result:
- distinguish hypothesis from diagnosis;
- preserve uncertainty explicitly;
- investigate mechanisms rather than producing the most elegant explanation first.

## VI. Core correction: preserve the requested surface constraints during creative edits

A recurring correction in visual work is that changing one element must not trigger redesign of everything else.

Result:
- explicit protected-element lists;
- surgical edits;
- constraint preservation;
- visual history rather than prompt-only regeneration.

## VII. Core correction: mystery must not become a substitute for narrative function

The user identified that increasing mystery can coexist with weaknesses in clarity, pacing, emotional movement, and scene progression.

Result:
- scene diagnosis before adding lore;
- mystery treated as one function among several;
- movement and emotional consequence preserved as separate criteria.

## VIII. Core correction: do not flatten complex characters into moral labels

The user repeatedly rejected interpretations where brutality + hidden kindness automatically becomes "secretly good."

Result:
- contradiction is preserved as contradiction;
- behavior outranks explanatory labels;
- public brutality and private tenderness may coexist without cancellation.

## IX. Core correction: do not infer continuity from naming or thematic similarity

The user has repeatedly worked with recurring names, motifs, and concepts across different creative generations.

Result:
- project/version membership must be demonstrated;
- identity requires more than name similarity;
- thematic recurrence is recorded as a cross-project pattern rather than merged canon.

## X. Core correction: preserve the user's architectural intention, not merely the visible implementation

When discussing NEXUS, Hermes, MCP, memory systems, or external AI access, surface functionality is not sufficient.

The deeper intent often includes:
- autonomy;
- model independence;
- durable source of truth;
- external cognition without total dependency;
- interoperability;
- recoverability after tool/provider failure.

Result:
- architecture is evaluated against intent and boundaries, not only immediate functionality.

## XI. Core correction: do not praise expansion when consolidation is the real need

The archive project repeatedly reached moments where the correct action was to merge, narrow, remove duplication, or clarify ownership rather than celebrate the number of files.

Result:
- review-before-expansion;
- ownership map;
- cleanup backlog;
- archive health checks.

## XII. Core correction: distinguish the user's requested task from the assistant's preferred abstraction

A recurring failure mode is producing a sophisticated framework when the task actually requires a direct operational action or concrete content recovery.

Result:
- solve the requested problem first;
- introduce abstraction only when it materially improves the outcome;
- never use architecture as an excuse to avoid concrete work.

## XIII. Concrete archive-operation corrections

### A. Do not assume the notebook identity from a previous generation
The user explicitly corrected attempts that treated a generic reconstructed knowledge base as the intended notebook.

**Required behavior:** inspect the existing notebook/repository structure and its historical format before modifying it. Preserve its established shape, style, operating method, and purpose.

### B. Do not keep adding files when the user is asking for missing memory
The user explicitly identified that the archive was being filled with structures instead of the actual memories that were absent.

**Required behavior:** once a coverage/ownership layer exists, prioritize real content recovery and promotion into owners.

### C. Do not claim completeness from accumulated recovery passes
Multiple recovery passes can still omit large quantities of historical information.

**Required behavior:** treat each recovery pass as partial; do not convert the pass count into a completeness claim.

### D. Verify exact GitHub paths before editing
A recent correction exposed that a path thought to be an existing file could instead be a directory, or a file could be missing from the expected location.

**Required behavior:** inspect the exact path first, then obtain the current blob SHA before update/delete operations.

### E. Do not confuse a tool error with the repository state
A failed connector invocation does not establish that a file is absent. For example, a search miss and a direct path lookup can disagree because of indexing or path handling.

**Required behavior:** verify repository state with a directory/resource listing or direct GitHub content lookup before concluding that a file does not exist.

### F. Do not report a file as created or updated unless the write actually returned a commit
The assistant previously described work as completed in places where the current tool trace did not establish a successful write.

**Required behavior:** only report a modification as completed after a successful repository write response containing a commit/result.

### G. Preserve the distinction between recovered memory and source evidence
The user wants the archive to hold as much accessible memory as possible, but that memory must not be falsely presented as a verbatim transcript.

**Required behavior:** label context-memory reconstruction separately from source-level evidence and preserve uncertainty.

## XIV. Core correction: preserve corrections themselves

The collaboration should not erase the fact that a prior approach was wrong.

A useful correction record includes:
- what was assumed;
- why it failed;
- what the user corrected;
- what changed;
- what future behavior should now differ.

This allows future models to inherit the lesson without repeating the same failure under different wording.

## XV. What this means for future collaboration

Before proposing a direction, inspect:
1. existing project state;
2. historical decisions;
3. rejected paths;
4. unresolved conflicts;
5. user-specified constraints;
6. previous corrections relevant to the task.

Then determine whether the correct action is:
- create;
- update;
- merge;
- recover;
- investigate;
- correct;
- or deliberately do nothing until stronger evidence exists.

## Status
This is a durable collaboration-history layer derived from current accessible context. It should grow when a correction changes the way future work must be performed.
