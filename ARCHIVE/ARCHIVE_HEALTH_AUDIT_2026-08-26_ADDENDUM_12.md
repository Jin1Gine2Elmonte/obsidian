# Archive Health Audit — 2026-08-26 Addendum 12

## Scope
Independent maintenance review of archive-local provenance language after the conversation-import vocabulary repair. Focus: preventing descriptive archive guidance from being mistaken for the canonical epistemic/provenance hierarchy.

## Finding — archive README used an ambiguous source-hierarchy label
`ARCHIVE/README.md` contained a five-level list under `Source hierarchy` that mixed established knowledge, explicit evidence, supported patterns, synthesis/inference, and speculation. This was useful as orientation, but its label could be interpreted as a second evidence/provenance hierarchy alongside `CANON_AND_PROVENANCE.md`.

The canonical governance owner already defines provenance sources and epistemic status separately. Therefore the archive-local list should not compete with that model.

## Repair
`ARCHIVE/README.md` now:
- renames the section to `Evidence / provenance orientation`;
- explicitly delegates current evidence provenance and epistemic status to `CANON_AND_PROVENANCE.md`;
- frames the list as an archive-representation orientation rather than a replacement governance hierarchy.

No factual content, canon, chronology, relationship status, identity conclusion, or source hierarchy inside the canonical conversation-import specification was changed.

## Git evidence
- `284bafdea707df31564cc35b62c9afbec3c0177d` — clarified the archive README provenance wording and removed the ambiguous hierarchy label.

## Validation boundary
`CANON_AND_PROVENANCE.md` remains the sole governance owner; `CONVERSATION_ARCHIVE_SPEC_V2.md` remains the sole conversation-import specification; `ARCHIVE/README.md` remains directory orientation only.

## Remaining gaps
All major primary-source recovery gaps remain unchanged. No speculative lore was introduced.
