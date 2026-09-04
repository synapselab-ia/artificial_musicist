# FLOW MUSIC — GENERATION CONSTRAINTS

Status: **CANONICAL WORKFLOW CONSTRAINTS**

Last updated: 2026-09-04

## Maximum generated song duration

Google's current Lyria / Flow Music generation model supports songs **up to 3 minutes long**. Treat **3:00 as a hard composition/generation ceiling** for this project unless the platform changes and the limit is re-verified.

The user has also observed in practical Flow Music tests that an output may occasionally finish a few seconds around the nominal boundary because of natural decay, tail, or generator behavior. This must **not** be treated as usable composition budget. Do not intentionally design a song that requires more than 3:00.

## Project design rule

Future UNFRAME songs generated as single Flow Music songs must be composed to fit comfortably inside the 3-minute ceiling.

Default internal planning target:

- preferred authored target: approximately **2:45–2:50**;
- hard design ceiling: **3:00**;
- a brief natural tail around the boundary may occur, but is not guaranteed and must not be relied upon.

The preferred margin exists to protect:

- complete verses without rushed delivery;
- rap diction and pocket clarity;
- a real bridge rather than a token breakdown;
- chorus escalation;
- final ad-libs / upper harmonies;
- a complete outro or natural decay;
- the intended tempo instead of forcing the generator to accelerate or compress sections to fit.

## Two-budget duration strategy

Use separate duration budgets for authorship and Flow-facing generation.

### 1. Authored budget

Write and architect the song so its essential material should fit in approximately **2:45–2:50** at the intended tempo.

This internal estimate must include every required lyric, the complete rap block, the bridge, the transformed final section, and a real ending. Do not count on the generator inventing extra time to rescue an overloaded draft.

### 2. Flow-facing target

In the generation prompt, normally request a result around **2:55–2:58**, with an explicit requirement to finish cleanly by approximately **2:59** and never cross the 3:00 hard ceiling.

The additional requested time is not permission to add content. Explicitly direct Flow to use the margin for:

- intelligible consonants and complete lyric delivery;
- natural breathing and phrase endings;
- rap articulation without omitted lines;
- short transitions between major sections;
- a complete final decay or outro.

Also explicitly prohibit Flow from using the extra margin for:

- an additional chorus cycle;
- a new post-chorus;
- a dance break;
- a long instrumental intro or outro;
- an instrumental solo;
- repeated filler lines.

Do **not** normally request a range ending exactly at `3:00`, such as `2:55–3:00`. The generator may treat the upper bound as a target and leave insufficient safety for a complete ending. Prefer language such as:

> Aim for approximately 2:56–2:58. Use the available time for complete, intelligible lyric delivery and natural breathing. Finish the full song cleanly by 2:59 and never exceed 3:00. Do not add sections or repetitions to fill time.

This is a generation heuristic, not a guarantee. Diagnose the actual output rather than assuming the requested duration was followed.

## Architecture implications

When drafting SONG ARCHITECTURE and LYRICS:

- estimate total section load before finalizing the lyric;
- prioritize fewer strong sections over too many underdeveloped sections;
- do not solve overlength by defaulting to faster BPM;
- do not overload verses with words merely to preserve every conceptual detail;
- protect the hook, bridge, rap clarity, and final payoff first;
- compress or remove lower-value repetitions before sacrificing high-value structural functions;
- consider the vocal-block strategy and duration constraint together: fewer, longer coherent blocks are preferable to many small handoffs that consume time and confuse the generator.

## HUMAN ERROR lesson

The approved `HUMAN ERROR` generation landed at approximately **2:59.18** and remained musically successful, but it also realized a faster tempo than the original working target. The faster tempo was accepted because it did not sound harmful, but future songs should not intentionally sit this close to the ceiling if a modestly shorter design can preserve more breathing room.

The project should distinguish:

- **audible quality:** whether the result sounds complete and convincing;
- **technical compression risk:** whether the generator may have accelerated, shortened, reduced pauses, or compressed section development to remain within the 3-minute cap.

A song may be approved even if the generator adapts its pacing, but future architecture should reduce the need for that adaptation.

## SECOND SKIN lesson

`SECOND SKIN` was authored below the hard ceiling and the accepted master landed around **2:47**. However, repeated edit/remix attempts to restore individual dense rap lines caused Flow to trade one lyric line for another and shorten the song further.

This suggests two workflow rules:

1. create enough authored headroom before first generation rather than relying on later surgical time expansion;
2. in the initial prompt, ask Flow to spend unused duration on complete delivery and breathing instead of allowing it to interpret a shorter song as preferable.

Repeated remix passes should not be used as the primary method for creating duration headroom when the editor is already substituting or removing lyric material.

## Re-verification rule

If Flow Music / Lyria later changes its maximum generation duration, verify the current official product documentation and update this file, `AGENTS.md`, `docs/CHECKPOINT.md`, and `docs/EXECUTION_PLAN.md` before designing around the new limit.
