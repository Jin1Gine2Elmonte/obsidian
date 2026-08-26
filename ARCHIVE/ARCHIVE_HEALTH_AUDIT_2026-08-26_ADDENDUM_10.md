# Archive Health Audit — 2026-08-26 Addendum 10

## Scope
Independent maintenance review of the current repository state after the append-only audit-navigation repair. Focus: legacy governance language hidden inside historical architecture documents and root-level navigation coverage for canonical source-import specifications.

## Finding 1 — Memory System V3 carried a legacy confidence model without a current-governance boundary
`ARCHIVE/MEMORY_SYSTEM_V3.md` contained the historical confidence labels `confirmed / supported / inferred / speculative / unknown` in an unqualified section named `Confidence model`. The document is an architectural history record, so retaining the historical model is useful, but presenting it without qualification could cause a future maintainer or model to treat it as the active repository-wide epistemic vocabulary.

This is analogous to the earlier template/protocol vocabulary drift, but the correct repair is preservation plus explicit historical scoping rather than deletion: the V3 confidence model is part of the architecture's history and should remain recoverable.

### Repair
`ARCHIVE/MEMORY_SYSTEM_V3.md` now:
- labels the original confidence model as historical architecture;
- delegates current status/provenance authority to `CANON_AND_PROVENANCE.md`;
- warns that new or updated nodes must use the current governance model rather than reviving the historical V3 vocabulary;
- links to `CONVERSATION_ARCHIVE_SPEC_V2.md` for historical conversation-source import.

## Finding 2 — Canonical conversation import specification was not exposed by root navigation
`CONVERSATION_ARCHIVE_SPEC_V2.md` is explicitly the canonical specification for importing historical conversation material, while the superseded V1 is intentionally not to be recreated. The file existed and was internally coherent, but `INDEX.md` did not expose it from the root navigation surface.

This was a discoverability/ownership-path gap, not a missing specification. The file itself already identifies its canonical role and preserves the source hierarchy needed to keep raw evidence separate from derived knowledge.

### Repair
`INDEX.md` now exposes `CONVERSATION_ARCHIVE_SPEC_V2.md` as the canonical historical-conversation import specification.

## Validation boundary
- No fictional canon was changed.
- No identity, chronology, relationship, or cosmology claim was changed.
- The historical V3 confidence vocabulary was preserved rather than deleted.
- No superseded conversation specification was recreated.
- The protected `LM_ARENA/` workspace was not modified.

## Git evidence
- `dbf7b341d087cfee712b611aa81174a08ba9e91d` — scoped the V3 confidence model as historical and linked current governance.
- `06c72b71b142890ab658c0595717e0c8bfae9121` — exposed the canonical conversation archive specification in root navigation.

## Remaining evidence gaps
The repository still cannot safely resolve the major source-dependent gaps identified by the census and health model: Jin/Ryota identity and genealogy, scene-level Arisa/Almont/Ryota/Jin evidence, Adam and Garthin defining scenes, detailed power-system mechanics, cosmological hierarchy/project membership, and the full narrative history of Strings of Fate. These remain recovery targets rather than candidates for synthesis.
