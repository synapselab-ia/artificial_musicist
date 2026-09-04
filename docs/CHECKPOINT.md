# CHECKPOINT

Last updated: 2026-09-04

## CURRENT_STATE

- Repository: `synapselab-ia/artificial_musicist`.
- Official group: **UNFRAME**, seven-member fictional male K-pop group.
- Permanent member IDs: `M01`–`M07`.
- Approved debut and quality benchmark: **Last Train Home**.
- Current priority: **music creation**.
- F6 next release: **IN PROGRESS — HUMAN ERROR / INITIAL GENERATION READY**.
- Selected concept: **HUMAN ERROR**.
- Selected sonic route: **A — PRECISION BREAKS INTO BLOOD**.
- Selected song architecture: **A — CONTROLLED FRACTURE**.
- Selected hook route: **B — SAME MISTAKE TWICE**.
- Canonical hook nucleus: **“I’d make the same mistake twice.”**
- Canonical title anchor: **“Call it human error.”**
- Complete lyric draft: `songs/02-human-error/LYRICS.md`.
- Lyric evaluation: `songs/02-human-error/LYRIC_EVALUATION.md`.
- Lyric status: **DRAFT V1 — READY FOR INITIAL GENERATION**.
- Initial generation package: `songs/02-human-error/INITIAL_GENERATION_PACKAGE.md`.
- Generation package status: **VOCAL-BLOCK V2 — READY FOR FIRST FLOW MUSIC / LYRIA GENERATION**.
- Current Flow Music handoff: one natural-language prompt in `New session`; internal SOUND / DETAILS categories are not treated as separate UI fields.
- User feedback established that line-by-line seven-member handoffs are too fragile for full-song generation.
- Canonical generation strategy now prioritizes **section-level vocal blocks** and direct vocal archetypes over frequent member-name switching.
- UNFRAME remains seven members in canon; generation-facing prompts may simplify explicit lead allocation while preserving the group’s major vocal/rap functions.
- Current HUMAN ERROR first-generation vocal-block map:
  - **VALE / low baritone lead:** Intro + entire Verse 1; short sparse low punctuation after the rap block.
  - **ELIAN / bright tenor:** entire Pre-Chorus 1.
  - **SOREN / power tenor:** entire Chorus 1, Chorus 2, and core Final Chorus melody.
  - **ROOK / technical rapper:** entire first technical rap block in Verse 2.
  - **MIRO / melodic-rap hybrid:** melodic continuation after ROOK, Error Tag, and entire Build / Contamination.
  - **NOEN / intimate tenor:** entire Pre-Chorus 2, entire Bridge, and entire Outro.
  - **EON / high tenor:** restrained support in Chorus 2, strongest upper harmony/counterline/ad-libs in Final Chorus.
- Intentional multi-voice handoffs are concentrated mainly in the rap sequence and final layered chorus, not scattered through normal verses.
- Concrete lyric scenario: narrator faces a contract/promotion representing the safe, socially correct life and knowingly refuses it despite having made a similar choice before, suffered financially, and been told it was a mistake.
- Sonic identity: industrial electro-pop + groove-driven K-pop + restrained hip-hop; begins surgically controlled and progressively becomes warmer, wider, more syncopated, saturated, and human-feeling.
- Tempo preference: **112–114 BPM**; working target **114 BPM**.
- Practical duration target: approximately **3 minutes**.
- Preserved concept alternatives in `docs/IDEA_RESERVE.md`: **DRESS REHEARSAL** and **NO SAINTS AFTER MIDNIGHT**.

## COMPLETED

- F0 repository foundation.
- F1 group identity and official name: **UNFRAME**.
- F2 seven-member architecture and vocal DNA.
- F3 visual preparation then intentionally deferred.
- Rejected-development history recorded for `Main Character` and `Crash Test`.
- F6 concept ideation completed; **HUMAN ERROR** selected.
- Concept reserve pass completed for **DRESS REHEARSAL** and **NO SAINTS AFTER MIDNIGHT**.
- F6 sonic-direction ideation completed; **PRECISION BREAKS INTO BLOOD** selected.
- Tempo preference captured as **112–114 BPM**, working target **114 BPM**.
- F6 song-architecture ideation completed; **CONTROLLED FRACTURE** selected.
- F6 hook ideation completed; **SAME MISTAKE TWICE** selected.
- F6 complete English lyric drafted and audited.
- F6 **INITIAL GENERATION PREP** completed.
- Flow handoff corrected to the single-prompt workflow.
- Flow vocal orchestration revised from micro member handoffs to section-level vocal blocks.

## CURRENT CREATIVE STANDARD

`HUMAN ERROR` must aim for the same overall satisfaction level as `Last Train Home` without copying its genre, emotional premise, melody, arrangement, or imagery.

For generation, prioritize **musical coherence over exact seven-voice bookkeeping**. The first result should sound like a convincing male K-pop group with clear contrasting vocal/rap colors; it is not required to produce seven perfectly stable synthetic timbres from text labels alone.

Protect these decisions:

- same SOREN-style power lead across all primary choruses;
- ROOK-style technical rapper clearly different from MIRO-style melodic-rap hybrid;
- NOEN-style intimate voice remains coherent across its long emotional blocks;
- EON-style high register is saved mainly for final escalation;
- singer changes occur mainly at section boundaries;
- production begins dry/narrow/precise and ends warm/wide/syncopated/human;
- `human error` sounds emotional rather than robotic;
- no excessive glitch/SFX shorthand.

## NEXT_ACTION

The user performs the **INITIAL GENERATION** manually in Google Flow Music using the revised **VOCAL-BLOCK V2** single prompt from `songs/02-human-error/INITIAL_GENERATION_PACKAGE.md`. Preserve the first generated audio if the core song works, then return the audio (preferred) or sufficiently detailed observations so the next project stage can **DIAGNOSE** the actual result. Do not rewrite the lyric again before hearing generation evidence.
