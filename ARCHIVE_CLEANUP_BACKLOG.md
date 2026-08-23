# Archive Cleanup Backlog

## Purpose
Convert deduplication rules into concrete maintenance actions. This is a work queue, not a new knowledge source.

## Tier 0 — identity safety
### Jin
- `WORLD/JIN_CORE.md` is the broad identity owner.
- `WORLD/JIN_VARIANTS.md` is the variant registry owner.
- `WORLD/JIN_VERSION_LATTICE.md` is the version-relationship owner.
- `WORLD/JIN_RYOTA_IDENTITY_AUDIT.md` is the identity-conflict owner.
- `WORLD/JIN_MEMORY_DENSITY.md` is the memory-completeness owner.
- Do not copy broad Jin identity prose into other nodes.

### Almont / Ryota
- `WORLD/ALMONT.md` is the broad identity owner.
- `WORLD/ALMONT_REIGN_PROFILE.md` owns reign/institution-versus-person analysis.
- `WORLD/ALMONT_RYOTA_RELATIONSHIP_DYNAMICS.md` owns relationship mechanics.
- `WORLD/ALMONT_RYOTA_STATE_MACHINE.md` owns relationship state transitions.
- `WORLD/RYOTA_ARISA_BENJAMIN.md` owns the family-system node.
- `WORLD/CANON_CONFLICTS.md` owns contradictions; the Jin/Ryota ambiguity must not be resolved locally in another file.

## Tier 1 — world systems
### Empire
Canonical owner: `WORLD/EMPIRE.md`.
- `WORLD/EMPIRE_MEMORY_DENSITY.md` now owns only memory strength and recovery gaps.
- `WORLD/IMPERIAL_LOGISTICS.md` remains derived/analytical.
- `WORLD/IMPERIAL_INSTITUTIONAL_MODEL.md` remains recovery/consistency targets.
- `WORLD/CAPITAL_AND_COURT.md` owns capital-specific material.

### Dark Forest
Canonical owner: `WORLD/DARK_FOREST.md`.
- `WORLD/DARK_FOREST_MEMORY_DENSITY.md` should remain evidence/completeness focused.
- Boundary analysis belongs in `DARK_FOREST_IMPERIAL_BOUNDARY.md` or as links from the canonical node.

### Power system
Canonical owner: `WORLD/POWER_SYSTEM.md`.
- `WORLD/POWER_SYSTEM_MEMORY_DENSITY.md` owns memory completeness.
- `WORLD/POWER_POLITICS.md` owns institutional consequences.
- Unsupported mechanics remain recovery targets.

## Tier 2 — characters
### Garthin
Canonical owner: `WORLD/GARTHIN.md`.
- `WORLD/GARTHIN_MEMORY_DENSITY.md` now owns only evidence strength and missing evidence.
- `WORLD/GARTHIN_RELATIONAL_ARCHITECTURE.md` owns relationship structure.

### Adam
Canonical owner: `WORLD/ADAM.md`.
- `WORLD/ADAM_MEMORY_DENSITY.md` now owns only evidence strength and retrieval gaps.
- `WORLD/ADAM_INTERWORLD_MODEL.md` owns travel hypotheses.
- `WORLD/ADAM_JIN_VARIANT_DISCRIMINATION.md` owns variant-recognition investigation.

## Tier 3 — project branches
### Strings of Fate
Ownership remains split by function:
- `STRINGS_OF_FATE/CANON.md` — confirmed project canon.
- `STRINGS_OF_FATE/MEMORY_EXPANDED.md` — direct accessible memory.
- `STRINGS_OF_FATE/MEMORY_TRUTH_AUDIT.md` — evidence/confidence audit.
- `STRINGS_OF_FATE/CONVERSATION_MEMORY_INDEX.md` — source-index layer.
- `STRINGS_OF_FATE/PROJECT_FRAME.md` — speculative design questions.
- `STRINGS_OF_FATE/RESEARCH_MATRIX.md` — recovery plan.
- `STRINGS_OF_FATE/VISUAL_IDENTITY.md` — visual canon.

### Cosmology
- Individual files own individual cosmological definitions.
- `COSMOS/COSMOLOGY_MEMORY_DENSITY.md` now owns only memory completeness, project-membership uncertainty, and recovery gaps.
- `NEGATIVE_KNOWLEDGE.md` owns unsafe global assumptions.
- Thematic resemblance is not a canonical edge.

## Tier 4 — time/evolution
Canonical ownership:
- `TIMELINE.md` — broad historical sequence.
- `PROJECT_STATE_TRANSITIONS.md` — project state changes.
- `HISTORICAL_EVOLUTION_MAP.md` — recurring idea evolution.
- `INTENT_AND_DISCARDED_PATHS.md` — rejected/abandoned reasoning.
- `NEGATIVE_KNOWLEDGE.md` — unsafe assumptions.

## Tier 5 — technical memory
### AI memory architecture
- `AI_MEMORY_ARCHITECTURE.md` owns system architecture and technical boundaries.
- `KNOWLEDGE_OWNERSHIP_MAP.md` owns information ownership.
- `ARCHIVE_PROTOCOL.md` owns archive behavior.
- `ARCHIVE_MAINTENANCE_LOOP.md` owns maintenance lifecycle.
- Technical architecture files should link to these instead of restating canon/provenance rules.

## Completed consolidation in this pass
- Adam memory-density node reduced to evidence/gaps rather than identity duplication.
- Empire memory-density node reduced to memory strength/recovery rather than world-system duplication.
- Garthin memory-density node reduced to memory strength/recovery rather than repeating the canonical character page.
- Cosmology memory-density node reduced to evidence gaps rather than repeating individual cosmology definitions.
- Strings of Fate truth-audit node reduced to evidence-boundary information rather than acting as a second canon or design document.
- AI memory architecture reduced to technical architecture rather than re-stating archive governance.

## Next cleanup rule
When a memory-density node contains canonical identity prose already owned elsewhere, move the prose into the owner only if it is genuinely stronger/new evidence; otherwise replace it with a compact pointer and recovery information.

## Completion definition
Cleanup is complete for a node when:
1. one file clearly owns each knowledge type;
2. duplicate files contain no conflicting current claims;
3. historical information remains where materially useful;
4. cross-references point to the owner;
5. a future update has an obvious destination.

No deletion should occur solely because two filenames look similar. Unique information and historical value must be checked first.
