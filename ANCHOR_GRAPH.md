# Anchor Graph

## Purpose
This is the vault's high-value relationship index. It is intentionally relational, but it must **not** imply that every edge is canonical.

## Edge labels
- `CANON` — explicitly established by the user/source.
- `SUPPORTED` — repeated and internally consistent across sources.
- `INFERRED` — analytical consequence or structural interpretation.
- `SPECULATIVE` — hypothesis or creative possibility.
- `UNKNOWN` — relationship not yet recoverable.
- `UNRESOLVED` — a specific relationship is known to exist as a problem under active audit, but its truth/identity/state has competing or insufficient evidence.

Every edge below is labeled rather than being silently treated as fact.

## HUMAN / CREATOR
The user's creative identity is strongly intuitive and architecture-oriented. This is a durable working characterization connected to creative-method and reasoning notes, not a fictional-canon claim.

## ANCHOR: OBSIDIAN MEMORY
Purpose: portable external continuity.
Edges:
- `SUPPORTED` -> AI memory
- `SUPPORTED` -> cross-model context
- `SUPPORTED` -> conversation export
- `SUPPORTED` -> MCP/API bridge exploration
- `SUPPORTED` -> GitHub archive

## ANCHOR: AI MEMORY
Purpose: preserve durable knowledge across model/provider changes.
Edges:
- `SUPPORTED` -> Obsidian
- `SUPPORTED` -> semantic retrieval
- `SUPPORTED` -> provenance
- `SUPPORTED` -> conversation normalization
- `SUPPORTED` -> Nexus

## ANCHOR: NEXUS
Purpose: agent/server and external-cognition experiments.
Edges:
- `SUPPORTED` -> MCP/tool orchestration
- `SUPPORTED` -> Google GenAI work
- `SUPPORTED` -> memory
- `SUPPORTED` -> remote deployment
- `SUPPORTED` -> gateway/external-cognition concepts

## ANCHOR: HERMES
Purpose: agent/deployment and knowledge-system experimentation.
Edges:
- `SUPPORTED` -> Docker
- `SUPPORTED` -> Northflank
- `SUPPORTED` -> embeddings/storage experiments
- `SUPPORTED` -> GitHub Actions
- `SUPPORTED` -> knowledge_os.py

## ANCHOR: JIN
Cosmic/meta-fictional fictional anchor.
Edges:
- `CANON` -> imagination / fictional-awareness premise at the durable broad level
- `CANON` -> extraordinary reality-level agency at the durable broad level
- `CANON` -> Adam as follower/traveler relationship
- `UNKNOWN` -> exact cosmological hierarchy
- `UNKNOWN` -> exact relationship to Almont/Ryota child-history branch
- `SUPPORTED` -> multiple Jin/Gin/Gene iterations exist in project history

## ANCHOR: ENTITY OF FORGETTING
Cosmological/philosophical anchor.
Edges:
- `CANON` -> The Last Thing to Be Forgotten as a related creative work/concept
- `CANON` -> ontological distinction from absolute nothingness
- `UNKNOWN` -> relationship to Primordial Rift
- `UNKNOWN` -> relationship to Existence Sublime
- `UNKNOWN` -> relationship to Jin
- `UNKNOWN` -> membership in the same universe as every other cosmological anchor

## ANCHOR: EXISTENCE SUBLIME
High-order cosmological anchor with incomplete formal definition.
Edges:
- `SUPPORTED` -> recurring cosmological vocabulary
- `UNKNOWN` -> hierarchy relative to Jin
- `UNKNOWN` -> hierarchy relative to Entity of Forgetting
- `UNKNOWN` -> relationship to Shadows of the First Creation
- `UNKNOWN` -> relationship to Primordial Rift

## ANCHOR: SHADOWS OF THE FIRST CREATION
Major mythology/title anchor.
Edges:
- `SUPPORTED` -> creation/primordial vocabulary
- `UNKNOWN` -> exact meaning of “First Creation”
- `UNKNOWN` -> relationship to Primordial Rift
- `UNKNOWN` -> relationship to Entity of Forgetting
- `UNKNOWN` -> relationship to Jin
- `UNKNOWN` -> relationship to Existence Sublime

## ANCHOR: GARTHIN
Character anchor.
Edges:
- `CANON` -> ruler
- `CANON` -> brutality/monstrous behavior
- `CANON` -> hidden/difficult-to-explain kindness as contradiction
- `UNKNOWN` -> political relationship to Almont
- `UNKNOWN` -> relationship to Jin
- `UNKNOWN` -> relationship to Adam

## ANCHOR: ALMONT / ARISA / RYOTA
Family and political anchor.
Edges:
- `CANON` -> Almont as emperor/husband/father in the remembered imperial branch
- `CANON` -> Arisa as wife and pivotal death event
- `CANON` -> long-running father/son conflict in the durable family memory
- `SUPPORTED` -> rebellion/departure/return pattern involving the son
- `UNRESOLVED` -> Jin ↔ Ryota identity relation
- `SUPPORTED` -> connection to the empire
- `SUPPORTED` -> connection to inheritance/authority themes

## ANCHOR: DARK FOREST
Worldbuilding anchor.
Edges:
- `CANON` -> dangerous territory outside effective imperial control
- `SUPPORTED` -> boundary to imperial totality
- `UNKNOWN` -> exact nature/mechanics/history
- `UNKNOWN` -> relation to cosmological anchors

## ANCHOR: POWER SYSTEM
Worldbuilding/system anchor.
Edges:
- `CANON` -> distinction between Magic and inherited Powers at the broad level
- `SUPPORTED` -> inheritance through blood for Powers
- `SUPPORTED` -> spiritual-vessel concept exists in the system
- `UNKNOWN` -> detailed mechanics/costs/limits
- `UNKNOWN` -> exact relationship to Blood family institutions

## ANCHOR: STRINGS OF FATE
Independent project boundary.
Edges:
- `CANON` -> dedicated creative project/title
- `CANON` -> strong visual cover requirements preserved in dedicated archive
- `UNKNOWN` -> plot mechanics
- `UNKNOWN` -> cosmological membership
- `UNKNOWN` -> relationship to Jin and other mythological anchors

## ANCHOR: CREATIVE BALANCE
A durable craft principle.
Edges:
- `SUPPORTED` -> mystery/depth must coexist with clarity/pacing/causality/emotional movement

## ANCHOR: ARCHITECTURAL SIMPLICITY
A durable technical-design preference.
Edges:
- `SUPPORTED` -> prefer minimal architecture until requirements justify complexity

## RECOVERY-LAYER BRIDGES
These are navigation links into the atomic recovery layer. They are **not additional canon edges**. Their purpose is to make recovered evidence discoverable from the high-value anchors without promoting the recovery layer into source authority.

- `JIN` -> `WORLD/EVENT_ATOMIC_RECOVERY_JIN_FAMILY_01.md`
- `ALMONT / ARISA / RYOTA` -> `WORLD/EVENT_ATOMIC_RECOVERY_JIN_FAMILY_01.md`
- `ALMONT / ARISA / RYOTA` -> `WORLD/EVENT_ATOMIC_RECOVERY_ALMONT_GARTHIN_ADAM_01.md`
- `GARTHIN` -> `WORLD/EVENT_ATOMIC_RECOVERY_ALMONT_GARTHIN_ADAM_01.md`
- `JIN` -> `WORLD/EVENT_ATOMIC_RECOVERY_ALMONT_GARTHIN_ADAM_01.md`
- `DARK FOREST` -> `WORLD/EVENT_ATOMIC_RECOVERY_EMPIRE_DARKFOREST_01.md`
- `POWER SYSTEM` -> `WORLD/POWER_COSMOLOGY_ATOMIC_RECOVERY_01.md`
- `ENTITY OF FORGETTING` -> `WORLD/POWER_COSMOLOGY_ATOMIC_RECOVERY_01.md`
- `EXISTENCE SUBLIME` -> `WORLD/POWER_COSMOLOGY_ATOMIC_RECOVERY_01.md`
- `SHADOWS OF THE FIRST CREATION` -> `WORLD/POWER_COSMOLOGY_ATOMIC_RECOVERY_01.md`

## Promotion rule
A new repeated concept becomes an anchor when it repeatedly generates distinct relationships or decisions. A thematic resemblance alone never creates a canonical edge.

## Maintenance rule
When a source changes an edge:
1. update the edge label;
2. update the owning node;
3. update conflict/negative knowledge if necessary;
4. propagate only verified downstream changes;
5. preserve the previous edge state when historically meaningful.
