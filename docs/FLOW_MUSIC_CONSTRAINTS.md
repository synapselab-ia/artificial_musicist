# FLOW MUSIC — GENERATION CONSTRAINTS

Status: **CANONICAL WORKFLOW CONSTRAINTS**

Last updated: 2026-09-04

## Maximum generated song duration

Google's current Lyria / Flow Music generation model supports songs **up to 3 minutes long**. Treat **3:00 as a hard composition/generation ceiling** for this project unless the platform changes and the limit is re-verified.

The user has also observed in practical Flow Music tests that an output may occasionally finish a few seconds around the nominal boundary because of natural decay, tail, or generator behavior. This must **not** be treated as usable composition budget. Do not intentionally design a song that requires more than 3:00.

## Project design rule

Future UNFRAME songs generated as single Flow Music songs must be composed to fit comfortably inside the 3-minute ceiling.

Default planning target:

- preferred authored/generation target: approximately **2:45–2:55**;
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

## Re-verification rule

If Flow Music / Lyria later changes its maximum generation duration, verify the current official product documentation and update this file, `AGENTS.md`, `docs/CHECKPOINT.md`, and `docs/EXECUTION_PLAN.md` before designing around the new limit.
