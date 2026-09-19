# RECOVERY PROTOCOL

## Purpose
Restore project continuity after a new chat, interrupted work session or repository change.

## Recovery order
1. Read PROJECT_STATE.md.
2. Read MASTER_PLAN.md.
3. Read CANON/CANON.md.
4. Read CONTINUITY.md.
5. Read relevant WORLD_BIBLE files.
6. Read CHARACTER_BIBLE files.
7. Read BOOK_01 architecture, clue map, scene blueprint and drafting specification.
8. Read DECISIONS logs.
9. Read latest QA audit.
10. Continue only from the latest recorded stage.

## Rules
- Never assume a chat statement is canon if repository status does not confirm it.
- Never silently overwrite a stronger existing decision.
- Record new major decisions.
- Keep rejected concepts documented where useful.
- Before a major milestone, commit a coherent checkpoint.
- If a new version invalidates an earlier one, preserve the old file history rather than deleting the reasoning.

Git commits provide snapshots and revision history that can be used to recover earlier project states.
