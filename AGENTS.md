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

## Creative option preservation gate

`docs/IDEA_RESERVE.md` is the permanent non-canonical memory for creative alternatives that the user explicitly likes but does not select for the current path.

Whenever a creative round presents multiple options and the user makes a selection:

1. identify any non-selected alternatives the user explicitly marks as interesting, worth keeping, or potentially useful later;
2. store those alternatives in `docs/IDEA_RESERVE.md` with enough context to recover the idea faithfully;
3. mark them clearly as reserve material rather than approved canon;
4. only after that reserve pass is complete may the project advance to the next creative stage.

This reserve pass is mandatory whenever the user has marked alternatives for preservation. Do not rely on chat memory alone and do not silently discard liked alternatives.

## Language rule

All content intended for use inside Flow Music / Lyria must be written in English, including concepts, titles, hooks, lyrics, internal SOUND directions, internal DETAILS instructions, generation prompts, edit prompts, remix prompts, and production notes.

Repository project-management notes may be written in English by default for consistency.

## Song workflow

Use the iterative pipeline:

`CONCEPT -> SELECTION / RESERVE PASS -> SONIC DIRECTION -> SONG ARCHITECTURE -> HOOK -> LYRICS -> INITIAL GENERATION -> DIAGNOSE -> EDIT/REMIX -> REFINE -> APPROVED VERSION`

Do not skip directly to full lyrics unless the user explicitly asks.

## Flow Music / Lyria manual handoff rule

The user performs Flow Music / Lyria generation manually. GitHub is the canonical archive; chat is the operational handoff surface.

Current Google Flow Music uses a **single natural-language prompt box** for song creation. Do not describe internal project headings such as `SOUND`, `DETAILS`, `NEGATIVE CONSTRAINTS`, or `LYRICS` as separate Flow UI fields unless the verified current interface actually exposes them.

For Google Flow Music generation handoff:

1. store the canonical package in the repository;
2. reproduce the exact copy-ready operational content directly in chat;
3. by default, provide **one single prompt block** ready to paste into Flow Music `New session`;
4. combine the internal sound direction, performance/arrangement guidance, and critical constraints into the natural-language instruction portion of that one prompt;
5. when supplying user-written lyrics, place `Lyrics:` immediately before the full lyric block, consistent with Lyria prompting guidance;
6. clearly state that bracketed section/member labels are performance instructions and must not be sung if such labels are included;
7. keep internal `SOUND`, `DETAILS`, and related sections in repository documents only when they improve project organization; they are not presumed to map one-to-one to Flow UI controls;
8. if the verified Flow Music UI changes later, update this protocol before giving interface-specific instructions.

Do not make the user open GitHub merely to retrieve content that must be pasted into Flow/Lyria. When the package contains a long lyric, include the full operational prompt in chat rather than linking to the repository only.

The assistant must not attempt the user's manual Flow/Lyria generation unless the user explicitly asks and an appropriate authenticated environment is actually available. Normally, after delivering the single-prompt handoff, the next action is for the user to generate manually and return the resulting audio or observations for diagnosis.

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
