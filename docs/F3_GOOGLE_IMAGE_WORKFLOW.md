# F3 — GOOGLE IMAGE GENERATION WORKFLOW

Status: **ACTIVE WORKFLOW — F3**

## Purpose

Create stable photorealistic master visual references for all seven UNFRAME members using Google image-generation tools, one member at a time, while keeping GitHub as the canonical record.

## Order

`M01 VALE -> M02 SOREN -> M03 NOEN -> M04 ROOK -> M05 ELIAN -> M06 MIRO -> M07 EON`

Do not generate the seven-member group image before all seven individual identities are approved.

## Per-member workflow

### Step 1 — Neutral master portrait

Generate a clean front-facing chest-up studio portrait with:

- photorealistic Korean male K-pop idol appearance;
- mainstream top-tier idol attractiveness;
- simple dark wardrobe;
- neutral gray studio background;
- soft controlled studio light;
- realistic skin texture;
- minimal natural idol grooming;
- neutral or very restrained expression;
- no concept scene;
- no text or watermark.

Generate several candidates if the tool permits, but evaluate the face rather than styling.

### Step 2 — Select the facial identity

Judge:

- does the member read immediately as a Korean male K-pop idol?
- is he conventionally attractive within the intended mainstream idol aesthetic?
- does the face match the member's performance identity?
- is the face memorable rather than generic?
- is it sufficiently different from already approved members?
- would it still work with black hair and simple clothing?

If not, revise only the necessary facial variables and regenerate.

### Step 3 — Three-quarter reference

Use the approved neutral portrait as the visual reference when the Google interface supports image referencing. Request the same person at approximately a 30–45 degree angle. Do not redesign the face.

### Step 4 — Side-profile reference

Use the approved face/reference again. Request a clean side profile under the same neutral studio conditions.

### Step 5 — Full-body reference

Use the same character identity. Keep wardrobe minimal and fitted enough to reveal natural body proportions. Do not introduce debut-era styling yet.

### Step 6 — Performance-expression reference

Create one controlled performance portrait showing the member's stage aura without changing facial identity.

### Step 7 — Canon review

The user reviews the set. If approved, record:

- immutable facial traits;
- body proportions;
- stable identifying detail(s);
- approved source image filenames/locations;
- reusable master prompt;
- any known failure modes.

Only then mark the member's visual identity canonical.

## Prompting discipline

- Always describe the subject as **fictional**.
- Do not request the likeness of any real artist or celebrity.
- Real K-pop groups may serve only as broad references for polish, visual standard, luxury editorial quality, and mainstream idol presentation.
- Keep the first portrait concept-neutral.
- Do not use train-station, stage, cyberpunk, dramatic rain, or music-video scenery during face creation.
- Do not solve a weak face with more styling.
- Change as few variables as possible between iterations.

## File naming

Suggested local filenames:

`M01_VALE_master-front_v01.png`
`M01_VALE_master-3q_v01.png`
`M01_VALE_master-profile_v01.png`
`M01_VALE_master-fullbody_v01.png`
`M01_VALE_performance_v01.png`

Increment the version number for rejected or revised generations. Only approved references should later be marked `APPROVED` in the repository notes.
