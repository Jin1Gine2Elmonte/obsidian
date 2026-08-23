# Jin — Version Lattice

## Purpose
The archive currently knows that multiple Jin/Gin/Gene iterations exist but does not know their complete genealogy. A linear version list is therefore insufficient; the versions may branch, rewrite, reincarnate, or become separate concepts.

## Node model
Each recovered Jin variant should have:
- `id`
- `name`
- `project`
- `world`
- `phase`
- `parent_variant` when known
- `branch_reason`
- `shared_memory`
- `lost_memory`
- `new_memory`
- `power_delta`
- `personality_delta`
- `relationship_delta`
- `cosmological_delta`
- `visual_delta`
- `canon_status`
- `source`

## Edge types
- `rewrites`
- `branches-from`
- `reincarnates-as`
- `incarnates`
- `parallels`
- `supersedes`
- `contradicts`
- `merges-with`
- `unknown-relation`

## Why a lattice
If one Jin creates another Jin through a rewrite, that does not necessarily make the second Jin a simple chronological successor. The two may coexist as historical artifacts of different project states.

## Invariant extraction
The goal is to identify the smallest set of properties that survive across versions without flattening their differences. Candidate axes include:
- imagination;
- fiction/reality boundary;
- reality-level agency;
- world travel;
- relationship to choice;
- relationship to creation;
- recurring emotional wound or desire.

These are search dimensions, not canon.

## High-value evidence
The most valuable recovered statements are explicit transitions such as:
- "this version replaced..."
- "the old Jin..."
- "another Jin..."
- "same person..."
- "not the same Jin..."
- "in this version..."
- "original Jin..."

Such wording should update the lattice immediately and propagate to affected nodes.
