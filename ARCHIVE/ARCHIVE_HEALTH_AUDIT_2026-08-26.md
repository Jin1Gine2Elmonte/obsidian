# Archive Health Audit — 2026-08-26

## Scope
Repository-wide maintenance pass against the current `main` tree, with Git history treated as state evidence. Focus: incomplete navigation, stale ranges, ownership boundaries, cross-link integrity, duplication risk, and knowledge gaps that can be resolved safely without inventing source material.

## Findings

### 1. The current-context recovery range was semantically wrong
`INDEX.md` had previously described the current-context recovery sequence as a contiguous range. The repository tree actually contains `_01`, `_02`, `_03`, `_04`, `_05`, `_08`, `_10`, `_11`, and `_12`; `_06`, `_07`, and `_09` are absent.

Git history does not show evidence that the missing numbers were merely omitted from the index by a recent deletion or repair. The safe interpretation is therefore that the numbering is historical and non-contiguous. `INDEX.md` now enumerates only the files that actually exist and states that the numbering is historical.

### 2. LM Arena is a real protected repository boundary
`LM_ARENA/README.md` defines an explicit two-way ownership boundary: LM Arena exclusively owns everything inside `LM_ARENA/`, while it must not modify anything outside it. The repository contains this directory as a dedicated workspace, so it is treated as a protected boundary rather than as missing shared-memory nodes.

This was exposed in the main navigation without modifying the protected workspace.

### 3. A deep fiction synthesis node had no explicit ownership role
`FICTION_CANON_DEEP.md` was created historically by commit `0531c77cd5ada15efeb23a072159dd3e9aaaedb5` with the message `Expand fiction canon deeply`. Its content spans cosmology, Jin, Garthin, the Almont family, empire scale, Dark Forest, and the power system, while the ownership map assigns those facts to specialized domain owners.

This created a real epistemic hazard: the filename could make the synthesis look like a competing canon owner even though the archive's governance rules require one-source ownership.

The file was therefore clarified as a **deep cross-domain fiction synthesis** rather than a competing canon source. `FICTION.md` now links to it explicitly, and `KNOWLEDGE_OWNERSHIP_MAP.md` records its role while preserving the specialized owners as the actual factual/canonical authorities. The substantive content was not removed or rewritten.

### 4. Three durable archive architecture nodes were outside the navigation surface
The repository contains:
- `ARCHIVE/README.md` — archive purpose, node families, source hierarchy, and maintenance principle.
- `ARCHIVE/KNOWLEDGE_STATUS.md` — state dimensions, provenance requirements, conflict protocol, and promotion rules.
- `ARCHIVE/MEMORY_SYSTEM_V3.md` — memory layers, lifecycle, retrieval model, context assembly, and anti-corruption rules.

They were not represented in `INDEX.md`. Because these documents define how the archive itself behaves rather than merely duplicating domain facts, they are now exposed in the index.

### 5. Major ownership and relationship structures remain coherent
`KNOWLEDGE_OWNERSHIP_MAP.md` still assigns clear primary owners for broad memory, reasoning architecture, projects, character identity, relationships, chronology, world state, canonical claims, contradictions, recovery targets, lessons, and repository evolution. `ANCHOR_GRAPH.md` uses explicit relationship states (`CANON`, `SUPPORTED`, `INFERRED`, `SPECULATIVE`, `UNKNOWN`, `UNRESOLVED`) and keeps recovery-layer bridges separate from canon edges.

No safe evidence was found that justified changing a current canonical owner or merging a disputed identity. The Jin/Ryota relationship remains correctly isolated as `UNRESOLVED`.

### 6. Atomic recovery is structurally linked but remains non-canonical
The atomic recovery layer is present for Jin-family events, Almont/Garthin/Adam events, Empire/Dark Forest events, and Power/Cosmology. `ANCHOR_GRAPH.md` already exposes these as recovery-layer bridges rather than canon edges. No promotion was justified during this pass.

### 7. The repository remains source-limited in several high-impact areas
The existing health records consistently identify the same unresolved evidence bottlenecks: Jin/Ryota identity and genealogy, Arisa's death scene and aftermath, Almont/Ryota dialogue and motives, Adam's first meeting and independent decisions, defining Garthin scenes, detailed power-system mechanics, cosmological hierarchy/project membership, and the full narrative history of Strings of Fate.

These cannot be safely completed from the repository alone. They remain explicit recovery targets rather than speculative expansions.

### 8. Root README is intentionally weak and remains low-value to duplicate
The root `README.md` contains only the repository title. `INDEX.md` is the actual navigation surface and already documents the vault's architecture. Expanding the README would mostly duplicate the index and is therefore not a high-value repair at this stage.

## Repairs made in this pass

1. Clarified `FICTION_CANON_DEEP.md` as a non-competing deep synthesis layer.
2. Added a direct deep-synthesis pointer in `FICTION.md`.
3. Recorded the explicit ownership role of `FICTION_CANON_DEEP.md` in `KNOWLEDGE_OWNERSHIP_MAP.md`.
4. Added `FICTION_CANON_DEEP.md` to `INDEX.md`.
5. Added `ARCHIVE/README.md`, `ARCHIVE/KNOWLEDGE_STATUS.md`, and `ARCHIVE/MEMORY_SYSTEM_V3.md` to `INDEX.md`.
6. Preserved all protected LM Arena contents and did not invent missing recovery passes.
7. Did not delete or merge files merely because terminology overlaps.

## Git evidence

The recent maintenance chain is:
- `cea2d3ffe333879ebfa9f46b8523a1d0d0c22594` — role-level index repair for template and conceptual fingerprint.
- `2c632acfc6290b43bf08b6aa1be45f0402f883ca` — recovery-range wording repair and LM Arena boundary exposure.
- `0eb31a9ff41f496883380516ce4a02903569deb6` — previous audit record.
- `738890ea53bda35594a709710a7eee31aea7afec` — clarified deep fiction synthesis ownership role.
- `fead8fc24b2c2fe6f24fa4e6557be57c743fd36c` — connected deep fiction synthesis to navigation.
- `6f1fe21d3b4f3ed1ab0d603f73bdc45007375416` — added explicit ownership mapping for the deep synthesis layer.
- `0bdafd5d34ff343f212cda84e1d102bce1a5c368` — updated the navigation index with the new ownership and archive-architecture links.

The repository history supports the interpretation that these are incremental maintenance repairs rather than a rewrite of the archive's knowledge model.

## Remaining safe work

The main unresolved maintenance frontier is still **owner-node linkage depth**: specialized domain owners should expose their provenance, dependency, contradiction, relationship, and recovery links consistently. That work should continue by inspecting the actual link surfaces of those owners rather than generating more summary text.

The largest knowledge gaps remain primary-source gaps, not documentation gaps. Completing them requires original conversations, scenes, or other unavailable evidence.

## Core conclusion

The archive's current structural weakness is no longer primarily missing top-level indexing. The more important remaining problem is **depth of linkage and source recovery**. The current maintenance state is healthier because the deep fiction synthesis is now epistemically bounded, the archive's own architecture nodes are discoverable, and the existing uncertainty model remains intact.
