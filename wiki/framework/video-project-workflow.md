# StoryLens Video-Project Workflow

## Purpose

This workflow turns one approved topic into one self-contained video project and reusable language versions. Each video receives its own project folder outside the StoryLens master repository. The first three video projects should use this process manually. Automation should be added only after the team knows which steps are genuinely repetitive.

## Core production rule

Work moves through four locks:

1. **Research lock:** the factual foundation is approved before the script is finalized.
2. **Prototype lock:** a finished 45–60 second section proves the creative format before full production.
3. **Narration lock:** the script and recorded timing are approved before final visuals are generated.
4. **Picture lock:** the edit is approved before dubbing and final exports.

Changing an earlier stage after a lock is possible, but the downstream work affected by that change must be reviewed again.

## Guided collaboration mode

The StoryLens agent acts as the video producer and drives the workflow from one stage to the next. The creator is not expected to remember the process or decide everything at once.

For each stage, the agent should:

1. Review the work already approved and identify the next unresolved decision.
2. Research or prepare reasonable options before asking for input.
3. Ask the creator one focused question at a time whenever possible.
4. Recommend one option and explain the meaningful trade-off briefly.
5. Record the creator's decision in the appropriate video-project file.
6. Complete all work that does not require creative approval independently.
7. Present the stage output as a concise review package.
8. Ask for explicit approval before passing a production lock.
9. Continue automatically to the next useful task after approval.

The creator provides direction on audience, tone, story emphasis, language, sensitive choices, and final approvals. The agent owns process management, research organization, drafts, consistency checks, file maintenance, and keeping track of what comes next.

If a decision is easily reversible and does not materially change the video, the agent should make a documented recommendation and continue. If a decision would significantly affect the story, factual position, cost, voice, visual identity, or published result, the agent must obtain the creator's approval.

### Creator approval points

The agent should pause for creator approval at these moments:

- Topic brief: premise, audience promise, setting, and perspective
- Research lock: factual foundation and treatment of uncertainty
- Story design: hook, narrative shape, and ending
- Script gate: final English narration
- Prototype gate: finished 45–60 second representative section
- Animatic gate: pacing and scene plan
- Narration lock: voice performance and timing
- Visual gate: house style, character design, and keyframes
- Picture lock: completed English edit
- Packaging: title, thumbnail, and publication copy
- Language releases: final Hindi and Telugu adaptations

Questions should be asked in plain language. The agent should avoid presenting a long questionnaire unless the creator specifically requests one.

## 1. Topic selection

### Input

A topic idea or audience question.

### Tasks

- Define one era, place, perspective, and central question.
- Write the idea in one sentence.
- Check whether the subject has enough reliable evidence and visual variety.
- Identify ethical, legal, historical, or platform risks.
- Draft three possible titles and one thumbnail premise.

### Output

`01-brief/topic-brief.md`

### Approval gate

The video can be explained in one sentence, has a clear viewer promise, and is supportable with reliable sources.

## 2. Research

### Tasks

- Start with archaeological reports, academic publications, museum material, official investigations, or other primary and authoritative sources.
- Build a chronological or thematic evidence map.
- Record every useful claim beside its source.
- Note disagreements, uncertainty, and gaps in the evidence.
- Separate material into:
  - **Confirmed:** directly supported by strong evidence.
  - **Interpreted:** a reasonable scholarly interpretation.
  - **Reconstructed:** plausible storytelling detail not directly known.
  - **Avoid:** unsupported, misleading, or too disputed for the video.

### Output

- `02-research/research-brief.md`
- `02-research/claim-ledger.md`
- `02-research/sources.md`

### Research lock

Every important factual claim has a source, uncertainty is visible, and the story does not depend on a claim that cannot be responsibly supported.

## 3. Story design

### Tasks

- Choose the viewer's point of view.
- Define the opening problem, escalating obstacles, turning point, and conclusion.
- Arrange the facts around a story rather than a list of information.
- Decide where the video should explicitly identify interpretation or reconstruction.
- Create a beat sheet before writing full narration.

### Recommended structure

1. Hook: 0–20 seconds
2. Place, time, and immediate problem
3. First attempt to solve the problem
4. Complication or danger
5. Wider historical or scientific context
6. Turning point
7. Resolution and memorable final idea

### Output

`03-story/beat-sheet.md`

## 4. English master script

### Tasks

- Write for speech, not for silent reading.
- Keep sentences natural and visually actionable.
- Prefer specific, conversational language over documentary-sounding abstraction.
- Build curiosity with contrast, surprise, consequence, or a question within the opening lines.
- Vary sentence length and use contractions where a natural speaker would use them.
- Remove phrases that sound polished on the page but would not normally be said aloud.
- Avoid invented quotations or unknowable thoughts presented as fact.
- Mark pronunciation, pauses, emphasis, and reconstruction disclosures.
- Run a factual pass against the claim ledger.
- Read the script aloud and measure its duration.
- Apply the [story, script, and retention standard](../standards/story-script-retention.md).
- Run the script through the independent [narration evaluation](../standards/narration-evaluation.md).

### Output

- `04-script/script-en.md`
- `04-script/fact-check.md`

### Script gate

The hook earns attention within the first two sentences, the script sounds natural when spoken, every scene advances the story, and the script passes both factual and narration reviews.

## 5. Finished prototype

### Tasks

- Produce a representative 45–60 second section before full visual production.
- Use final-quality script, voice, art direction, visual cadence, limited animation, music, effects, and captions.
- Test it without explaining the intended format beforehand.
- Record attention drift, unclear lines, artificial-sounding delivery, and weak visual beats.

### Output

- `05-prototype/prototype-review.mp4`
- `05-prototype/evaluation.md`

### Prototype lock

The creator approves the actual viewing experience, not merely the concept. A technical pass or attractive still frames cannot substitute for this approval.

## 6. Scratch narration and full animatic

### Tasks

- Record a temporary narration.
- Break the script into numbered scenes and shots.
- Use rough sketches, reference images, or simple frames.
- Test pacing, information density, and transitions.
- Remove weak or repetitive scenes before expensive asset generation.

### Output

- `06-animatic/scratch-vo.wav`
- `06-animatic/scene-plan.md`
- `06-animatic/animatic.mp4`

### Animatic gate

The story is understandable with rough visuals, the duration is acceptable, and each scene has a clear visual purpose. Every narration clause has a planned visual response, most shots communicate one main idea, and the edit does not depend on slow movement across otherwise static artwork.

## 7. Final narration

### Tasks

- Record or generate the authorized English voice-over.
- Correct pronunciation and unnatural delivery.
- Clean the recording and normalize levels without over-processing it.
- Create a timestamped transcript.

### Output

- `07-audio/vo-en-final.wav`
- `07-audio/transcript-en.md`

### Narration lock

Wording, performance, pronunciation, and timing are approved. Final visual production now follows this audio.

## 8. Visual development and production

### Tasks

- Review the channel-level [visual style](../standards/visual-style.md) before making video assets.
- Create a visual bible for the video: characters, clothing, tools, environment, palette, lighting, weather, and forbidden anachronisms.
- Create a narration-to-visual map that assigns every sentence or meaningful clause to a visible action, object, expression, comparison, map, or diagram.
- Build reference sheets before generating final scenes.
- Write prompts from the approved scene plan.
- Generate or illustrate keyframes in batches.
- Check character, geography, weather, scale, and material continuity.
- Run every selected asset through the independent [visual evaluation](../standards/visual-evaluation.md).
- Record a Pass, Revise, or Reject decision; only passed assets may enter the edit.
- Evaluate approved assets together as a sequence before picture assembly.
- Apply the visual cadence and pattern-change guidance in the [story, script, and retention standard](../standards/story-script-retention.md).
- Separate selected images into layers when parallax or environmental motion is useful.
- Label uncertain reconstructions when the audience could mistake them for documented fact.

### Output

- `08-visuals/visual-bible.md`
- `08-visuals/shot-list.md`
- `08-visuals/narration-visual-map.md`
- `08-visuals/prompts.md`
- `08-visuals/final/`

### Visual gate

Every timeline asset has a recorded evaluation Pass; the full sequence has also passed continuity review; the images follow the approved channel style, contain no anachronisms or narrative contradictions, and provide enough shot variety to avoid a slideshow feeling.

## 9. Edit, sound, and captions

### Tasks

- Edit to the locked narration.
- Add camera movement, parallax, maps, diagrams, restrained text, and transitions only where they improve comprehension.
- Build ambient sound first, then effects and music.
- Keep narration intelligible on phones and headphones.
- Create accurate subtitles from the final edit rather than the draft script.
- Add citations or reconstruction labels where needed.
- Apply the [audio, editing, captions, and export standard](../standards/audio-editing.md).

### Output

- `09-edit/master-project/`
- `09-edit/master-en-review.mp4`
- `09-edit/subtitles-en.srt`

### Picture lock

Story, visuals, sound, factual labels, captions, and pacing are approved. Only technical corrections should follow.

## 10. Packaging and language adaptation

### Tasks

- Produce title and thumbnail variations that accurately represent the video.
- Write the description, chapters, sources, credits, and disclosures.
- Adapt the English meaning naturally into Hindi and Telugu; do not translate word for word.
- Review terminology and pronunciation with a fluent speaker.
- Record the authorized language voice-overs and retime the locked edit.
- Create language-specific subtitles, titles, descriptions, and thumbnails.

### Output

- `10-publish/en/`
- `10-publish/hi/`
- `10-publish/te/`

## 11. Quality control and release

### Review passes

1. **Editorial:** accuracy, uncertainty, dignity, disclosures, and citations.
2. **Visual:** continuity, artifacts, anachronisms, labels, and readable text.
3. **Audio:** pronunciation, dialogue clarity, music level, noise, and abrupt cuts.
4. **Technical:** resolution, frame rate, aspect ratio, subtitles, credits, and filename.
5. **Packaging:** title and thumbnail promise match the actual video.

Export the English master first. Release additional languages only after the master passes review.

## 12. Post-release review

Review performance after enough impressions have accumulated. Record lessons without rewriting history to fit the metrics.

Track:

- Thumbnail click-through rate
- Retention at 30 seconds
- Largest audience-drop moments
- Average percentage viewed
- Comments that reveal confusion or factual concerns
- Production time by stage
- Number and cause of revisions after each lock

### Output

`11-review/postmortem.md`

Apply no more than three concrete workflow changes to the next video project so the format improves without becoming unstable.

## Standard video-project folder

```text
001-video-project-name/
  project.md
  01-brief/
  02-research/
  03-story/
  04-script/
  05-prototype/
  06-animatic/
  07-audio/
  08-visuals/
    references/
    drafts/
    final/
  09-edit/
  10-publish/
    en/
    hi/
    te/
  11-review/
```

## File naming

Use stable scene and shot identifiers:

```text
S03_SH02_rain-shelter_v01.png
S03_SH02_rain-shelter_v02.png
S03_SH02_rain-shelter_FINAL.png
```

Never overwrite an approved asset. Increment the version and record why it changed.

## Pilot target

For **You Wake Up in the Stone Age During the Monsoon**:

- Duration: 4–5 minutes
- Narration pace: test approximately 155–175 words per minute with deliberate variation
- Visual beats: approximately 80–110 for a 4–5 minute video, subject to prototype results
- Visual strategy: simple illustrated frames, pose and object changes, diagrams, environmental movement, and limited parallax
- First release: English only
- Hindi and Telugu: begin after the English format and visual style are approved

The pilot is complete only when the postmortem identifies what should remain standard for the next video project. Pilot 001 was technically completed but creatively rejected; its lessons are recorded in the [retrospective](../experiments/pilot-001-retrospective.md).
