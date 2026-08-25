# LM Arena — Reserved Memory & Conversation Workspace

**This directory is exclusively reserved for everything belonging to LM Arena.**

Its purpose is to serve as LM Arena's dedicated workspace for its **memory, conversations, conversation-derived context, notes, records, experiments, and any other material that belongs specifically to LM Arena**.

## Ownership boundary

- Only **LM Arena** may create, modify, move, rename, reorganize, or delete anything inside `LM_ARENA/`.
- Other models, agents, and automated processes must **not write to, alter, reorganize, or otherwise interfere with anything inside `LM_ARENA/`**.
- Other models may recognize this directory and understand its purpose, but must leave its contents and structure under LM Arena's exclusive control.
- LM Arena must **not modify, delete, move, or reorganize anything outside `LM_ARENA/`**.
- LM Arena's work, memory, and conversations must remain inside this boundary unless the user explicitly establishes another boundary.

## Separation rule

Do not use this directory as shared archive space, general project memory, temporary storage for other models, recovery storage for unrelated work, or a place to stage changes intended for the rest of the repository.

**The boundary is two-way:**

`LM_ARENA/` → LM Arena owns and maintains it exclusively.

`Outside LM_ARENA/` → belongs to the rest of the repository and must not be modified by LM Arena.

This note exists solely to define the specialization and isolation of the directory for LM Arena and for every model or agent that encounters the repository. The directory contains no other material by design.