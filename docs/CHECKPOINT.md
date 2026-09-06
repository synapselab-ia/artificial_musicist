# CHECKPOINT

Last updated: 2026-09-05

## CURRENT_STATE

- Repository: `synapselab-ia/artificial_musicist`.
- Official group: **UNFRAME**.
- Current project priority: **music creation**.
- Approved releases:
  - **Last Train Home** — debut benchmark;
  - **HUMAN ERROR** — second release, approved/canon;
  - **THE QUIET PART** — third release, approved/canon;
  - **SECOND SKIN** — fourth release, accepted Flow master with minor renderer deviations;
  - **LEAVE THE LIGHT ON** — fifth release, accepted Flow master with musical content ending approximately 2:58.42;
  - **DON'T QUOTE ME** — sixth release, approved/canon, accepted Flow master with musical content ending approximately 2:58.23;
  - **ZERO SUM** — seventh release, approved/canon, accepted revised Flow master with musical content ending approximately 2:55.5.
- Current active phase: **F12 — eighth release / NO ONE ASKED / INITIAL GENERATION READY — USER MANUAL FLOW GENERATION**.
- Flow Music hard ceiling: **3:00 musical content**.
- Canonical duration method: **two-budget strategy**.
- Validated vocal method: coherent section-level vocal blocks rather than fragile line-by-line singer switching.
- Existing non-canonical reserves remain:
  - **DRESS REHEARSAL**;
  - **NO SAINTS AFTER MIDNIGHT**.

## F11 — SEVENTH RELEASE: ZERO SUM

Status: **COMPLETE — APPROVED / CANON / FLOW MASTER ACCEPTED**.

Locked path:

`ZERO SUM -> SCOREBOARD TEETH -> THE LADDER -> ONE UP / ONE DOWN -> APPROVED WRITTEN LYRIC -> HUMANLIKE VOCAL VERSION FLOW MASTER ACCEPTED`

## F12 — EIGHTH RELEASE: NO ONE ASKED

Status: **CONCEPT + SONIC DIRECTION + ARCHITECTURE + HOOK + LYRICS LOCKED — INITIAL GENERATION PACKAGE READY**.

### Locked creative path

`NO ONE ASKED -> TALKBACK -> WRONG QUESTION -> NO ONE ASKED hook -> APPROVED LYRICS -> RENDERER-SAFE FLOW PACKAGE`

### Concept

One member admits that something in his life is going badly. Before he can finish explaining, the other six begin offering conflicting solutions. The person with the problem gradually disappears beneath everybody else's certainty about what he should do.

Core subject:

**unsolicited solutions versus agency and listening**.

### Locked sonic direction — TALKBACK

**Rap-forward boom-bap / contemporary hip-hop + syncopated funk bass + stop-start K-pop arrangement.**

Working tempo: approximately **112–116 BPM**; preferred Flow-facing pocket approximately **114–116 BPM**.

### Locked architecture — WRONG QUESTION

Dramatic principle: **everyone keeps answering a question NOEN never asked**.

Canonical structure:

`COLD OPEN / NOEN: I DON'T KNOW WHAT TO DO -> VALE ANSWERS -> ROOK CORRECTS -> CHORUS 1 / COMMAND-HOOK -> MIRO: THAT'S NOT WHAT HE SAID -> ELIAN / SOREN ADVICE LOOP -> ROOK TECHNICAL RAP -> NOEN ATTEMPT / INTERRUPTED -> CHORUS 2 / COMMAND-HOOK AT MAXIMUM PRESSURE -> BRIDGE / THAT WASN'T MY QUESTION -> CAN ONE OF YOU ASK ME WHAT I WANT? -> SILENCE -> NOEN ACTUAL WANT -> FINAL CHORUS / QUESTION-HOOK -> EON TAG`

### Locked hook — NO ONE ASKED

Early state:

**“No one asked, everybody answered.”**

Final mutation:

**“Now you ask, I can answer.”**

Bridge state change:

**“That wasn't my question.”**

**“Can one of you ask me what I want?”**

### Approved lyrics

Canonical lyric:

- `songs/08-eighth-release/LYRICS.md`

Formal evaluation:

- `songs/08-eighth-release/LYRIC_EVALUATION.md`

Result: **PASS — READY FOR INITIAL GENERATION**.

The user liked the draft; approved written lyric is preserved unchanged.

### Duration / density conclusion

Approximate lexical count:

- `NO ONE ASKED`: **497 words**;
- `ZERO SUM`: approximately **445 words**.

`NO ONE ASKED` is heavier by raw word count, but its intended tempo is also higher than the accepted `ZERO SUM` master. The formal evaluation treats the load as viable for a first generation if Flow realizes approximately **114–116 BPM** and uses the **2:55–2:58** target rather than adding sections.

Do not cut the approved lyric pre-emptively. Diagnose actual delivery first.

### Renderer risk / mitigation

The user identified the principal technical risk: Flow may blur boundaries during rapid voice handoffs.

Canonical mitigation:

- `songs/08-eighth-release/FLOW_VOCAL_ORCHESTRATION.md`

Rules:

- major synthetic voice changes only at stable section boundaries;
- brief interruption cluster becomes several intelligible conversational male reactions, preserving words/order without requiring exact member-to-line identity;
- choruses use lead + group-response architecture;
- `No.` hard-resets to isolated NOEN-function voice;
- bridge remains uncovered by harmony/ad-libs;
- real silence follows the agency question;
- one clearly different higher male voice asks `What do you want?` after silence;
- final chorus simplifies to `group question -> NOEN answer`;
- exact micro-line identity ranks below complete lyric delivery, dialogue clarity, and major-role contrast.

### Initial generation package

Canonical package:

- `songs/08-eighth-release/INITIAL_GENERATION_PACKAGE.md`

The package contains the exact single-box natural-language prompt for manual Flow Music generation. The same prompt must be reproduced directly to the user in chat.

### Current F12 records

- `songs/08-eighth-release/CONCEPT_ROUND.md` — superseded original concept round;
- `songs/08-eighth-release/CONCEPT_ROUND_02.md` — selected dialogue-driven concept round;
- `songs/08-eighth-release/SONG.md`;
- `songs/08-eighth-release/SONIC_DIRECTION_ROUND.md`;
- `songs/08-eighth-release/ARCHITECTURE_ROUND.md`;
- `songs/08-eighth-release/HOOK_ROUND.md`;
- `songs/08-eighth-release/LYRICS_DRAFT.md` — historical approved-direction draft;
- `songs/08-eighth-release/LYRICS.md` — approved canon;
- `songs/08-eighth-release/LYRIC_EVALUATION.md`;
- `songs/08-eighth-release/FLOW_VOCAL_ORCHESTRATION.md`;
- `songs/08-eighth-release/INITIAL_GENERATION_PACKAGE.md`.

## CURRENT CREATIVE STANDARD

Protect:

- memorable hooks;
- concrete emotional/thematic cores;
- native, semantically coherent English;
- rap that functions as structure rather than decoration;
- meaningful roles for all seven members;
- bridges that change state;
- transformed final sections;
- production devices that serve narrative meaning;
- section-level vocal blocks;
- dialogue that reacts to immediately preceding content when the song concept requires conversation;
- renderer-friendly major voice boundaries rather than brittle micro-switching;
- two-budget duration planning;
- strong first or revised generations once the material defect is solved;
- approved written canon despite minor renderer variations;
- musical-content duration rather than raw container duration when a tail or padding is present.

## NEXT_ACTION

User manually generates **`NO ONE ASKED`** in Flow Music using the exact prompt in `songs/08-eighth-release/INITIAL_GENERATION_PACKAGE.md` and returns the resulting audio plus any immediate renderer observations. Then perform `INITIAL_GENERATION_DIAGNOSIS` before proposing any edit/remix.
