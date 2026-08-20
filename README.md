# Study + tutoring book

This folder is a **book**. You name a **subject**. In **Agent** mode, the agent **asks** a few questions, then **writes tutoring lessons** you can study from or teach with — one lesson at a time, with a quiz at the end of each.

Each lesson keeps slots for **video**, **audio**, **image**, and **diagram**, and tracks its own status so you can see progress at a glance.

There is **no subject filled in yet**. Add one when you are ready.

## How to start a subject

1. Switch to **Agent** mode.
2. Say: `Build tutoring lessons for **SUBJECT**, beginner, 5 lessons.`
3. The agent should ask: level, how many lessons, language (if needed).
4. It creates `subjects/<subject-slug>/` with `index.md` and `lesson-01.md`, generating one lesson at a time — it'll check in before moving on to the next.

Copy-paste more prompts in [ASK.md](ASK.md), including ones for extending, reviewing, and maintaining a subject once it exists. Tutoring rules the agent follows: [HOW-TO-TUTOR.md](HOW-TO-TUTOR.md). All subjects: [index.md](index.md).

## What a subject looks like

```
subjects/photosynthesis/
  index.md
  lesson-01.md
  lesson-02.md
  images/
```

The empty pattern to copy is [subjects/_template/](subjects/_template/index.md).

### `index.md`

Each subject's `index.md` tracks:

- **Learning path** — a table of lessons with status (⬜ not started / 🟡 in progress / ✅ done)
- **Media inventory** — a table of which lessons still have `missing` video/audio/image/diagram
- **Glossary** — key terms collected across lessons
- **Progress notes** — freeform space for what's working or confusing

### Each lesson

Every `lesson-0X.md` follows the same shape: learning objectives, key terms, explanation, media slots, a worked example, practice questions with hidden answers, and a summary. See [subjects/_template/lesson-01.md](subjects/_template/lesson-01.md).

## Media

- Put screenshots in that subject's `images/` folder.
- Paste video/audio **URLs** in the lesson. Optional files: `video.mp4` / `audio.mp3` next to the lesson (git ignores them).
- If a media line says `missing`, add it later, or check that subject's media inventory table in `index.md`. Search the book for `missing` to see gaps across everything.

## Studying and quizzing

- `@lesson-01.md` to quiz or edit one lesson — ask the agent to quiz you and it'll go question by question based on that lesson's learning objectives.
- `@index.md` to search the subject list, check your progress, or ask what to study next.
- See [ASK.md](ASK.md) for ready-made prompts to review, translate, adjust difficulty, or fill media gaps.

## Find a topic

Agent searches **this folder** (file names and text).
