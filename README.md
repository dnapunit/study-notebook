# Study + tutoring book

This folder is a **book**. You name a **subject**. In **Agent** mode, the agent **asks** a few questions, then **writes tutoring lessons** you can study from or teach with.

Each lesson keeps slots for **video**, **audio**, **image**, and **diagram**.

There is **no subject filled in yet**. Add one when you are ready.

## How to start a subject

1. Switch to **Agent** mode.
2. Say: `Build tutoring lessons for **SUBJECT**, beginner, 5 lessons.`
3. The agent should ask: level, how many lessons, language (if needed).
4. It creates `subjects/<subject-slug>/` with `index.md` and `lesson-01.md`, `lesson-02.md`, …

Copy-paste more prompts in [ASK.md](ASK.md). Tutoring rules: [HOW-TO-TUTOR.md](HOW-TO-TUTOR.md). All subjects: [index.md](index.md).

## What a subject looks like

```
subjects/photosynthesis/
  index.md
  lesson-01.md
  lesson-02.md
  images/
```

The empty pattern to copy is [subjects/_template/](subjects/_template/index.md).

## Media

- Put screenshots in that subject’s `images/` folder.
- Paste video/audio **URLs** in the lesson. Optional files: `video.mp4` / `audio.mp3` next to the lesson (git ignores them).
- If a media line says `missing`, add it later. Search the book for `missing` to see gaps.

## Find a topic

Agent searches **this folder** (file names and text). `@index.md` to search the subject list. `@lesson-01.md` to quiz or edit one lesson.
