# Wiki Maintenance

## Purpose

The wiki is StoryLens's durable knowledge base. It explains how the channel works; it is not a storage location for production assets or a second copy of video-project files.

## Content boundary

### Keep in the wiki

- Channel vision and positioning
- Repeatable workflow and approval gates
- Research, writing, visual, narration, audio, and editing standards
- Reusable checklists and templates
- Decisions that affect future video projects
- Lessons generalized from completed video projects and experiments
- Current project-level status

### Keep in a separate video project

- Topic brief and video-specific decisions
- Sources, research notes, and claim ledger
- Beat sheet and scripts
- Voice files and transcripts
- Storyboards, prompts, images, animation files, and project files
- Subtitles, renders, QA images, and post-release analytics

### Do not maintain

- Duplicate copies of video-project documents
- Temporary commands or terminal output
- Generated caches
- Personal secrets or API keys
- Obsolete advice that has been superseded without historical value

## Page conventions

- Use lowercase kebab-case filenames.
- Give every page one clear purpose.
- Link related pages rather than duplicating their text.
- Record dates on status, experiment, and decision pages.
- Mark rules as **Locked**, **Experimental**, or **Deprecated** when ambiguity matters.
- State the evidence or experiment behind a rule.
- Keep `index.md` as the canonical navigation page.

## Updating knowledge

After an experiment or published video:

1. Record raw video-specific observations in that project's `11-review/` folder.
2. Identify no more than three lessons that should affect future work.
3. Add those lessons to the relevant wiki standard or decision page.
4. Update `project/current-status.md` if a major uncertainty became locked or rejected.
5. Check links from `index.md`.

## Resolving conflicts

The newest explicit decision in `decisions/decision-log.md` wins over older experimental notes. A locked standard wins over a video-specific preference unless the creator deliberately reopens that decision.
