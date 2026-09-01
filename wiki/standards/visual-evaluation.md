# StoryLens Visual Evaluation Gate

## Purpose

No generated or illustrated asset may enter a StoryLens edit merely because it looks attractive. Every asset must pass a documented evaluation for factual responsibility, narrative correctness, continuity, visual quality, and production suitability.

The evaluator should review the asset separately from the person or system that created it whenever practical. The evaluation uses the approved research brief, claim ledger, scene plan, visual bible, and channel style bible as its ground truth.

## Evaluation sequence

1. Open the asset at full size.
2. Compare it with its scene purpose and generation prompt.
3. Compare it with the research brief and claim ledger.
4. Compare it with the locked channel style.
5. Compare it beside the preceding and following approved shots.
6. Inspect faces, hands, limbs, tools, clothing, objects, text, and background details closely.
7. Preview it at the intended 16:9 crop and at small mobile size.
8. Decide **Pass**, **Revise**, or **Reject** and record the reason.

## Hard-fail checks

Any one of these results in **Revise** or **Reject**, regardless of score:

- Historically impossible or prohibited object
- Unsupported detail presented as confirmed evidence
- Material contradiction with the narration or scene timing
- Character identity, clothing, or tool continuity failure
- Semantic role substitution, such as showing the wrong historical actor performing the narrated action
- Anatomical defect, duplicated object, malformed hand, or visually broken geometry
- Text error, accidental lettering, watermark, signature, or visible generation artifact
- Violation of the locked house style
- Misleading reconstruction that could be mistaken for documented evidence
- Composition that cannot support the required crop, caption, label, or motion
- Demeaning stereotype, unsafe portrayal, or dignity concern

## Scored checks

Score each category from 0 to 2:

- **0:** fails or materially conflicts
- **1:** usable only after correction or carries a notable concern
- **2:** meets the approved requirement

| Category | Question |
|---|---|
| Historical fit | Does the image follow the research brief and avoid prohibited or unsupported specifics? |
| Narrative fit | Does it show the correct moment, action, objects, weather, and emotional beat? |
| Character continuity | Do identity, proportions, hair, clothing, age, and carried objects match adjacent shots? |
| Anatomy and artifact integrity | Are hands, limbs, faces, tools, bindings, and repeated shapes structurally credible? |
| House-style compliance | Does it follow the locked outlines, flat color, shadow, detail, and palette rules? |
| Composition and readability | Is the focal action clear at full and mobile size, with usable label and subtitle space? |
| Motion readiness | Can the frame support the planned pan, zoom, parallax, rain, smoke, or fire treatment? |
| Disclosure and dignity | Is reconstruction handled responsibly and are people portrayed as capable human beings? |

Maximum score: 16.

## Decision rules

- **Pass:** no hard fail and score of 14–16
- **Revise:** any correctable hard fail or score of 10–13
- **Reject:** fundamental factual, continuity, dignity, style, or structural problem; or score below 10

A high numerical score cannot override a hard fail.

## Correction protocol

For a **Revise** decision:

1. Name the smallest concrete defect.
2. State what must remain unchanged.
3. Make one targeted edit rather than regenerating the whole concept when possible.
4. Save the revision as a new version.
5. Re-run the entire evaluation; do not pass it automatically because the named defect changed.

For a **Reject** decision, record why targeted editing is unlikely to produce a trustworthy result and generate a new asset from the approved scene specification.

## Evaluation record

Record each review in the video project's visual folder:

```text
Asset: S03_SH02_rain-shelter_v02.png
Evaluator: StoryLens visual evaluator
Date: YYYY-MM-DD
Decision: PASS | REVISE | REJECT
Hard fail: None | description
Scores: historical 2; narrative 2; continuity 1; anatomy 2; style 2; composition 2; motion 2; dignity 2
Total: 15/16
Required correction: description or None
Notes: concise supporting observations
```

Only assets with a recorded **Pass** may be copied or linked into the editing timeline.

## Sequence-level evaluation

Individual passes are necessary but not sufficient. Before picture assembly, inspect the approved sequence as a contact sheet and check:

- Character drift across shots
- Clothing or tool changes
- Weather and time-of-day continuity
- Shelter and landscape geography
- Repeated compositions or monotonous shot scale
- Unmotivated palette changes
- Visual rhythm and adequate room for subtitles
- Whether reconstructed details accidentally accumulate into a false claim
- Whether an individually acceptable shot remains on screen too long for the narration ideas it contains

The sequence receives its own Pass, Revise, or Reject decision.
