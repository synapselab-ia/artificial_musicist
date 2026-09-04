# AGENTS.md

## Purpose

This repository is the canonical source of truth for the `artificial_musicist` fictional music-group project.

## Continuation protocol

When asked to continue the project:

1. Read this file.
2. Read `docs/CHECKPOINT.md`.
3. Read `docs/EXECUTION_PLAN.md`.
4. Read any canonical documents referenced by the checkpoint.
5. Verify the real repository state when relevant.
6. Execute only the current `NEXT_ACTION`.
7. Do not repeat completed phases unless the user explicitly requests revision.
8. Update the canonical documents and checkpoint before ending the work session.
9. Leave exactly one clear `NEXT_ACTION`.

## Canon hierarchy

If documents conflict, use this priority:

1. explicit user instruction in the current conversation;
2. `docs/GROUP_CANON.md`;
3. `docs/CHECKPOINT.md`;
4. member-specific canon under `members/`;
5. song-specific approved canon under `songs/`;
6. other planning documents and templates.

## Creative rules

- The project represents an original fictional male K-pop group, not a simulation of a real group.
- Real artists may be used only as broad references for qualities; do not copy melodies, lyrics, distinctive arrangements, signature performances, or recognizable song sections.
- Once member identities are approved, preserve the same seven fictional characters across releases.
- Preserve member IDs `M01` through `M07` permanently. Stage names, roles, and visual profiles become canonical only after explicit approval.
- Same group does not mean same genre. Releases may change genre while preserving member identity, vocal personality, group dynamics, quality standards, and visual continuity.
- Protect strong generations. If most of a track works, prefer surgical edits over rebuilding or remixing.

## Language rule

All content intended for use inside Flow Music / Lyria must be written in English, including concepts, titles, hooks, lyrics, SOUND instructions, DETAILS, generation prompts, edit prompts, remix prompts, and production notes.

Repository project-management notes may be written in English by default for consistency.

## Song workflow

Use the iterative pipeline:

`CONCEPT -> SONIC DIRECTION -> SONG ARCHITECTURE -> HOOK -> LYRICS -> INITIAL GENERATION -> DIAGNOSE -> EDIT/REMIX -> REFINE -> APPROVED VERSION`

Do not skip directly to full lyrics unless the user explicitly asks.

## Member continuity

When the seven members are defined:

- assign lines intentionally by member ID;
- preserve each member's vocal/rap personality across songs;
- do not randomly reassign core specialties;
- allow members to stretch beyond their usual role only when musically justified;
- distinguish between canonical member identity and generation-engine variability.

Do not claim Flow/Lyria reproduces an identical synthetic voice across tracks unless this is actually verified.

## Media policy

Do not treat Git as a general-purpose archive for large WAV/video files. Keep canonical text, prompts, metadata, small references, and approved notes in Git. Use Git LFS, releases, or external storage for large media only when explicitly configured.
