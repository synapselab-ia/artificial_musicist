# CHECKPOINT

Last updated: 2026-09-04

## CURRENT_STATE

- Repository: `synapselab-ia/artificial_musicist`.
- Official group: **UNFRAME**.
- Approved releases:
  - **Last Train Home** — debut benchmark;
  - **HUMAN ERROR** — second release, approved/canon;
  - **THE QUIET PART** — third release, approved/canon;
  - **SECOND SKIN** — fourth release, accepted Flow master approximately 2:47.23 with minor renderer-induced lyric deviations.
- Current project priority: **music creation**.
- Current active phase: **F9 — fifth release / concept selection**.
- Flow Music hard generation ceiling: **3:00**.
- Canonical duration method: **two-budget strategy**.
  - internal authored budget: approximately **2:45–2:50** for all essential material;
  - Flow-facing generation target: approximately **2:55–2:58**;
  - required clean finish: approximately **2:59**, never exceeding **3:00**.
- The extra requested generation time is reserved for diction, breathing, complete lyric delivery, transitions, and a full ending; it must not be filled with new sections or filler repetition.
- Validated Flow vocal method: coherent section-level vocal blocks rather than fragile line-by-line singer switching.
- Existing non-canonical reserves remain:
  - **DRESS REHEARSAL**;
  - **NO SAINTS AFTER MIDNIGHT**.

## F8 — FOURTH RELEASE: SECOND SKIN

Status: **COMPLETE — CURRENT FLOW MASTER ACCEPTED / FURTHER EDITING CLOSED UNLESS USER REOPENS**.

Canonical path:

- concept: **SECOND SKIN**;
- sonic direction: **B — MIRROR FEVER**;
- architecture: **B — PERFECT FIT**;
- hook route: **B — WEAR ME BETTER**;
- written lyrics: **APPROVED / CANON**;
- current Flow master: **ACCEPTED**.

Canonical architecture:

`POLISHED INTRO -> VERSE 1 -> PRE-CHORUS -> CHORUS 1 / PERFECT FIT -> VERSE 2 / REWARD -> PROTOCOL RAP -> MIRO UNRAVEL -> BRIDGE / WHO IS UNDERNEATH -> FINAL CHORUS / SECOND SKIN TEARS -> OUTRO`

Canonical hook:

- Chorus 1: **“I wear it well / it wears me better.”**
- Final mutation: **“I wore it well / now it wears me.”**

### Accepted master metadata

The user supplied **`SECOND SKIN.mp3`** in chat after approval.

Measured profile:

- duration: approximately **2:47.23**;
- margin below Flow ceiling: approximately **12.77 seconds**;
- stereo, **48 kHz**;
- estimated tempo: approximately **117.45 BPM**;
- estimated tonal center: **F minor**;
- integrated loudness: approximately **-16.2 LUFS**;
- loudness range: approximately **8.2 LU**;
- measured true peak: approximately **0.0 dBFS**.

Canonical analysis:

- `songs/04-fourth-release/MASTER_ANALYSIS.md`.

Do not treat these measurements as a reason to remaster an already accepted result.

### Generation/edit lesson

The initial generation and two subsequent edit/remix passes demonstrated that Flow can trade one lyric line for another and shorten a song while attempting supposedly local corrections.

Observed pattern:

1. initial generation omitted **“No panic in the picture, no sweat in the frame”** and rendered **“They say my name like it’s the answer”** too quickly;
2. Edit Pass 01 restored the missing rap line but omitted **“Every gesture pre-approved before I lift a hand”**;
3. Edit Pass 02 again redistributed/omitted material and shortened the song by roughly **2 seconds**.

The user judged that the remaining deviations do **not materially change the song's meaning** and preferred leaving the result rather than continuing a degrading edit loop.

Therefore:

- preserve `songs/04-fourth-release/LYRICS.md` as the canonical written lyric;
- allow the accepted Flow master to contain minor renderer-induced deviations;
- do not rewrite canon to match accidental omissions;
- do not continue edit/remix passes unless the user explicitly reopens them;
- when renderer fidelity and musical quality conflict after repeated edits, prefer the stronger musical master if the semantic arc remains intact.

### Duration-method refinement after SECOND SKIN

For future releases, separate the duration used in composition from the duration requested from Flow.

The song itself must be architected so all essential material fits within approximately **2:45–2:50** at the intended tempo. The initial Flow prompt should nevertheless request approximately **2:55–2:58**, explicitly reserving the extra time for intelligible consonants, complete lyric delivery, breathing, section transitions, and a complete ending.

The prompt must also explicitly prohibit Flow from spending that margin on extra chorus cycles, post-choruses, dance breaks, solos, long intros/outros, or filler repetition.

Do not normally request `2:55–3:00`; keeping the requested target below the hard boundary reduces cutoff risk.

This is a heuristic, not a guarantee. Diagnose the actual audio.

Canonical duration record:

- `docs/FLOW_MUSIC_CONSTRAINTS.md`.

## F9 — FIFTH RELEASE

Status: **IN PROGRESS — CONCEPT SELECTION OPEN**.

Canonical concept-round record:

- `songs/05-fifth-release/CONCEPT_ROUND.md`.

Current fresh options:

- **A — AFTER THE CONFETTI** — emotional vacuum after achieving the milestone that was supposed to transform you;
- **B — YOU AWAKE?** — one small 4 a.m. distress message grows into chosen-family presence until dawn;
- **C — THE SKY CAME BACK** — a city blackout creates accidental community and makes people notice the sky and one another again;
- **D — EMERGENCY CONTACT** — a blank bureaucratic field exposes who the narrator can actually call when things go wrong;
- **E — PHOTO FINISH** — a decisive race forces a costly choice between victory and stopping for the rival who fell.

This round is intentionally fresh. It does not reopen `SECOND SKIN` and does not automatically reuse the reserved concepts `DRESS REHEARSAL` or `NO SAINTS AFTER MIDNIGHT`.

No sonic direction, architecture, hook, or lyric is locked yet.

After the user selects one option, preserve any explicitly liked non-selected concepts in `docs/IDEA_RESERVE.md` before advancing to **SONIC DIRECTION**.

## CURRENT CREATIVE STANDARD

Protect:

- memorable hooks;
- concrete emotional/thematic cores;
- native, semantically coherent English;
- purposeful rap/vocal contrast;
- bridges that change state;
- transformed final sections;
- section-level vocal blocks;
- the two-budget duration method;
- complete lyric delivery when feasible, but not at the cost of degrading a strong master through repeated unstable edits;
- strong generations as creative masters;
- concepts and arrangements native to a seven-member male K-pop performance act.

## NEXT_ACTION

Obtain the user's selection of **A, B, C, D, or E** from the fifth-release concept round. Do not advance to sonic direction until one concept is selected and any explicitly liked non-selected alternatives have been preserved in `docs/IDEA_RESERVE.md`.
