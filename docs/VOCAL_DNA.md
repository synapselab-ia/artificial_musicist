# VOCAL DNA

Status: **CANONICAL — F2 COMPLETE**

UNFRAME uses seven permanent member IDs with complementary musical identities. Exact synthetic timbre may vary between independent Flow/Lyria generations, so continuity is defined by role, register, delivery, phrasing personality, line assignment, and arrangement behavior as well as any reusable audio reference available in a specific workflow.

## Canonical member map

| Member | Primary musical identity | Secondary identity | Performance function |
|---|---|---|---|
| `M01 — VALE` | Low Vocal / Deep Rap | low harmony / spoken delivery | Anchor |
| `M02 — SOREN` | Main Vocal / Power Vocal | emotional lead | Ignition |
| `M03 — NOEN` | Intimate / Texture Vocal | falsetto / quiet harmony | Lens |
| `M04 — ROOK` | Technical / Fast Rap | rhythmic sub-vocal | Edge |
| `M05 — ELIAN` | Bright Lead Vocal | pre-chorus / melodic connector | Lift |
| `M06 — MIRO` | Melodic Rap / Vocal Hybrid | rhythmic lead vocal | Bridge |
| `M07 — EON` | High Vocal | upper harmony / ad-libs / counter-melody | Flare |

## Member-specific continuity

### M01 — VALE

Dark resonant baritone and deep controlled rap. Weight comes from space, deliberate pauses, low-register authority, and strong consonant placement. Do not write him like ROOK.

### M02 — SOREN

Full-bodied main vocal with chest-dominant power, controlled grit, stable sustained notes, and emotionally convincing belts. Preserve headroom so his large moments remain meaningful.

### M03 — NOEN

Intimate mid-range color with controlled breathiness, conversational musical phrasing, and clean falsetto. Quiet delivery is a strength, not a lesser role.

### M04 — ROOK

Technical rapper built around internal rhyme, articulation, syncopation, acceleration/deceleration, pocket changes, and rhythmic precision. Speed is a tool, not the entire identity.

### M05 — ELIAN

Bright, clean, agile tenor and structural melodic connector. Frequently useful in pre-choruses, hook setups, harmony stacks, and transitions that need lift without using the main climax voice too early.

### M06 — MIRO

True vocal-rap hybrid. Flexible speech-to-song phrasing, melodic rap, rhythmic singing, and vulnerable cadence should connect sections that would otherwise feel abruptly divided into rap and vocal blocks.

### M07 — EON

Clear high tenor and upper-register specialist. Uses controlled mix, upper harmonies, counter-melodies, sustained notes, and selective belts. Brighter and higher than SOREN rather than simply louder.

## Approved-debut compatibility — Last Train Home

The F2 architecture was approved with the explicit requirement that it remain compatible with the already-approved debut. The functional labels in `songs/01-last-train-home/LYRICS.md` map naturally to the canonical lineup:

- `[Low Vocal]` -> primarily **M01 VALE**;
- `[Soft Vocal]` -> primarily **M03 NOEN**;
- `[Emotional Vocal]` -> primarily **M02 SOREN**, with **M05 ELIAN** available for selected melodic setup/connector lines when the F5 attribution pass is performed;
- `[Deep Rap]` -> **M01 VALE**;
- `[Melodic Rap]` -> **M06 MIRO**;
- `[Fast Rap]` -> **M04 ROOK**;
- `[High Vocal]` -> **M07 EON**;
- `[Backing Vocals]` / `[Group Vocals]` -> distributed ensemble roles, with M05 especially useful for mid-high connective harmony and M07 for upper layers.

This mapping is deliberately compatible with the debut's existing structure: intimate opening, low-vocal contrast, three distinct rap personalities, rising melodic pre-choruses, powerful chorus lead, late high-register escalation, layered final chorus, and quiet outro.

F2 does **not** rewrite the approved lyric or audio. Exact member-by-member line attribution for the debut remains an F5 task so that attribution can be done without damaging the approved generation.

## Group-vocal principles

- Choruses should use layered group vocals selectively rather than flattening every member into a single unison sound.
- Final choruses may add upper harmonies, octave doubles, counter-lines, rapper interjections, and ad-libs without obscuring the main hook.
- High notes should be saved when possible so they create genuine escalation.
- SOREN and EON must not be treated as interchangeable climax voices.
- VALE and ROOK must not share the same rap cadence.
- NOEN should receive meaningful quiet moments rather than token lines.
- ELIAN should function as a real melodic connector, not merely background support.
- MIRO should remain a credible hybrid rather than alternating between generic singing and generic rap.
- Rap sections must be written as performance: cadence, pockets, internal rhyme, pauses, syncopation, acceleration, and personality matter.

## Prompting rule

When useful, future Flow/Lyria song materials should reference canonical member IDs directly (`M01`–`M07`) and may add functional annotations secondarily, e.g. `[M07 — High Vocal]`.

Do not claim exact voice cloning or identical synthetic timbre across independent generations unless that continuity has been technically verified.