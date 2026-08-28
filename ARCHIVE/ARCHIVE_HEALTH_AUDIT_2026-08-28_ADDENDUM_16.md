# Archive Health Audit — 2026-08-28 Addendum 16

## Finding
A repository-wide ownership review found `WORLD/ARCHIVE_LEARNING_CURVE.md` stored inside the fictional-world domain even though its content describes archive/reconstruction methodology rather than fictional-world facts. Its subject overlaps with repository-level learning and maintenance, not with a world-domain owner.

This created a misleading ownership signal: the file looked like a world node while its actual knowledge type was archive methodology.

## Repair
Created the canonical archive-methodology owner:

- `ARCHIVE/ARCHIVE_LEARNING_CURVE.md` — durable lessons about how the archive reconstructs and preserves knowledge.

The old `WORLD/ARCHIVE_LEARNING_CURVE.md` path was demoted to a compatibility pointer rather than left as a duplicate owner. This preserves discoverability while preventing two files from carrying the same substantive content.

`WORLD/README.md` now identifies the old path as a legacy pointer and routes maintenance to the archive owner.

## Ownership boundary
This file is distinct from:
- `ARCHIVE_EVOLUTION_FROM_GIT.md`, which owns Git-evidenced repository development history;
- `DECISIONS_AND_LESSONS.md`, which owns general durable decisions, lessons, and experiments;
- specialized `WORLD/` nodes, which own fictional-world facts and recovery surfaces.

## Evidence boundary
The repair is structural and ownership-based. No fictional fact, chronology, identity conclusion, relationship, canon state, or source-evidence claim was changed.

## Git evidence
The canonical file was created in commit `83621f7cac75fafd2fc22e92277f7cb9c59b6c01`.
The former world-domain file was then converted into a compatibility pointer in commit `0a735d2bb2dac6a61d9e6c7990b9a3d1315c56a8`.
The world navigation surface was synchronized in commit `c5e9eede6ee4594d6f0c92599b243d8bb47a2f8e`.

The original substantive history remains recoverable through Git history; the active ownership surface now points to the archive methodology owner.
