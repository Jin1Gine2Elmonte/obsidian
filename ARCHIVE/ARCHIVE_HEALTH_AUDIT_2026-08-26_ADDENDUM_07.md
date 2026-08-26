# Archive Health Audit — 2026-08-26 Addendum 07

## Purpose
Record the discovery and repair of a stale governance vocabulary in the canonical-node template.

## Finding — template carried a legacy status vocabulary
`CANONICAL_NODE_TEMPLATE.md` was still using `active`, `historical`, `superseded`, and a `Confirmed / Working model / Speculative` state split. Those labels predated the current canonical governance model and could have caused future nodes created from the template to reintroduce a second epistemic vocabulary.

## Repair
- Replaced the legacy status examples with the canonical classes defined by `CANON_AND_PROVENANCE.md`.
- Added `DERIVED`, `HISTORICAL / SUPERSEDED`, and `UNKNOWN` explicitly so the template does not collapse important epistemic distinctions.
- Added a direct governance reference and clarified that relationship labels follow the normalized graph vocabulary.
- Kept the template structural; it does not become a new governance owner.

## Validation
- `CANON_AND_PROVENANCE.md` remains the sole owner of epistemic status/provenance definitions.
- No fictional facts, chronology, identity conclusions, or source evidence were changed.
- The repair prevents future nodes generated from the template from drifting back to the retired status vocabulary.

## Evidence boundary
Source-dependent gaps remain unchanged, including Jin/Ryota identity, Jin variant genealogy, Arisa scene evidence, detailed Almont/Ryota and Adam/Garthin recovery, power mechanics, cosmological hierarchy/project membership, and full Strings of Fate narrative recovery.

## Git evidence
- `a1bca8fb66a754981ec3cf95bd742f0ff4327579` — aligned `CANONICAL_NODE_TEMPLATE.md` with the canonical governance vocabulary.
