# F3 — GOOGLE VISUAL GENERATION PROTOCOL

Status: **WORKFLOW APPROVED / CHARACTER DETAILS PENDING APPROVAL**

The user chose Google image generation as the primary tool for creating photorealistic UNFRAME member references during F3. GitHub remains the canonical source for prompts, decisions, approved notes, and reference metadata.

## Operating principle

Generate **one member at a time**. Do not begin with a seven-member group image.

The objective is to establish a stable fictional person first, then create era styling around that person later.

## Per-member sequence

1. Generate a clean master portrait.
2. Reject or refine until the face feels distinctive and correct.
3. Generate a three-quarter portrait using the approved face as reference where the Google workflow supports image referencing.
4. Generate a side-profile reference.
5. Generate a neutral full-body fashion reference.
6. Compare all views for facial consistency.
7. Approve the member only when the same fictional person is recognizable across views.
8. Save the approved prompt, generation notes, and reference filenames/links in the repository.

Do not proceed to group concept photography until all seven individual master identities have been approved.

## Master-reference visual standard

Use a neutral editorial/studio setup:

- photorealistic original fictional young adult male K-pop performer;
- chest-up portrait for the first master image;
- neutral or subtly serious expression;
- direct or near-direct eye contact;
- simple neutral gray background;
- soft directional studio lighting;
- realistic skin texture and pores;
- natural subtle facial asymmetry;
- minimal makeup;
- dark natural-looking hair;
- simple dark clothing;
- no dramatic jewelry;
- no text, logo, watermark, microphone, stage, crowd, train station, or elaborate concept scenery;
- no resemblance to real celebrities or existing idols.

## Shared base prompt

Use this block as the shared foundation for first-pass member portraits:

> Create a photorealistic studio portrait of an original fictional young adult male K-pop performer. He must not resemble any real celebrity, idol, actor, or public figure. Chest-up composition, neutral gray seamless background, realistic editorial photography, soft directional key light with subtle fill, natural skin texture and visible pores, believable minor facial asymmetry, realistic eyes, realistic hair strands, minimal natural makeup, dark simple clothing, no jewelry that dominates the face, no text, no watermark, no logos, no stage, no scenery. Avoid plastic skin, excessive beauty filtering, anime features, doll-like proportions, exaggerated V-line surgery aesthetics, or generic AI symmetry. Preserve the exact facial identity described below.

Append the approved member-specific identity description after this block.

## First-pass file naming

Suggested local naming convention:

- `M01_VALE_master_front_v01.png`
- `M01_VALE_master_3q_v01.png`
- `M01_VALE_master_profile_v01.png`
- `M01_VALE_master_fullbody_v01.png`

Repeat the same pattern for `M02`–`M07`.

Increment the version only when identity materially changes, e.g. `v02`.

## Evaluation checklist

For every candidate ask:

- Does the face feel like a specific person rather than a generic handsome AI idol?
- Is the face clearly different from all already-approved members?
- Does the face match the member's canonical performance identity without becoming a caricature?
- Are eye shape, jaw, nose, and mouth sufficiently distinctive to survive hairstyle changes?
- Does skin look human rather than airbrushed plastic?
- Would the same face still be recognizable with blond hair, wet hair, a hat, or different makeup?
- Is there any accidental resemblance to a real celebrity? If yes, reject or revise.
- Can the character plausibly inhabit the `Last Train Home` debut visual world?

## Preservation rule

Once a front master portrait is approved, future generation attempts should preserve the approved face and change **one major variable at a time** whenever possible.

Examples:

- face approved, change camera angle only;
- face/angle approved, change framing only;
- identity set approved, change wardrobe for debut era;
- debut identity approved, later change hair for a comeback while preserving face.

Do not simultaneously change face, hair, makeup, wardrobe, lens, and environment if the goal is identity consistency.

## Group-generation gate

Only after `M01`–`M07` each have approved individual references should the project generate:

- neutral seven-member lineup;
- `Last Train Home` individual concept portraits;
- `Last Train Home` full group concept image;
- unit images;
- performance/MV-style scenes.

## Repository policy

Large image files do not need to be committed to regular Git unless explicitly desired. The repository should always preserve:

- approved textual face description;
- exact prompt or prompt family used;
- which generated image was approved;
- version label;
- consistency notes;
- immutable vs era-flexible traits;
- any external reference location or Git LFS path if configured later.

## Next operational step after visual-architecture approval

Start with `M01 — VALE` and generate his first clean master portrait using the shared base prompt plus the canonical VALE identity block. Review the result before generating any other member.
