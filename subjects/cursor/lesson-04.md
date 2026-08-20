---
lesson: 04
subject: cursor
title: Quiz, progress, and ASK.md prompts
level: beginner
duration_minutes: 20
status: draft
---

# Lesson 04: Quiz, progress, and ASK.md prompts

## Learning objectives

By the end of this lesson you should be able to:

- Start a quiz from a lesson using chat (with `@` from [lesson 03](lesson-03.md))
- Read progress from this subject’s `index.md` learning path
- Copy a ready-made prompt from [ASK.md](../../ASK.md) and fill in the blanks

## Prerequisites

[Lessons 01–03](lesson-01.md): files, [Ask vs Agent](lesson-02.md), and [`@` mentions](lesson-03.md).

## Key terms

- **Quiz** — the agent asks questions one at a time from a lesson’s learning objectives; you answer before seeing the key
- **Learning path** — the table in this subject’s `index.md` with status ⬜ / 🟡 / ✅
- **ASK.md** — the book’s list of copy-paste prompts ([ASK.md](../../ASK.md) at the book root)

## Explanation

Studying in this book is not a special app. You open a lesson, `@` it, and use short prompts. [ASK.md](../../ASK.md) is the menu so you do not have to invent wording every time.

### How a quiz should work

1. `@` the lesson file (see [lesson 03](lesson-03.md)).
2. Ask: `Quiz me. Do not show answers until I try.`
3. Answer one question. Get feedback. Then the next.
4. After about five questions, ask which objectives felt shaky.

The hidden `<details>` answers in the lesson are for when you study alone. During a live quiz, do not peek until you have tried.

Use [Ask](lesson-02.md) if you only want questions. Use [Agent](lesson-02.md) only if you also want the index status updated.

### How to read progress

Open [`index.md`](index.md) in this folder. The **Learning path** row tells you written vs studied:

- ⬜ not started — no file yet, or you have not begun
- 🟡 in progress — started, not marked done
- ✅ done — you (or the agent, when you ask) marked it finished

**Progress notes** at the bottom are for what was confusing. **Glossary** is terms to review. **Media inventory** lists `missing` slots — search the book for `missing` to see gaps.

### Using ASK.md

Open [ASK.md](../../ASK.md). Pick a block, paste it into chat, replace `SUBJECT` or `0X`. Examples that fit this subject:

- `Quiz me on lesson-04 of cursor.`
- `@index.md` then `Summarize my progress in cursor and suggest what to study next.`
- `Give me a quick review quiz mixing lessons 01–03 of cursor.`

For a new lesson file you still want [Agent](lesson-02.md). For a quiz only, [Ask](lesson-02.md) is enough.

## Media

- 🎥 Video: missing
- 🔊 Audio: missing
- 🖼️ Image: missing — put file in `images/`, or link a URL
- 📊 Diagram: missing — a flow “open ASK.md → copy prompt → `@` file → send” would help here

## Worked example

You finished reading lesson 03 and want both a quiz and a next-step suggestion.

1. Open [ASK.md](../../ASK.md). Copy the studying line: `Quiz me on lesson-0X of <subject>.`
2. In chat (Ask), type `@` `lesson-03.md`, then: `Quiz me on lesson-03 of cursor. Do not show answers until I try.`
3. After the quiz, `@` this folder’s `index.md` and paste: `Summarize my progress in cursor and suggest what to study next.`
4. Check the learning-path table yourself in the editor. If chat says lesson 05 is done but the table shows ⬜, trust the table until you mark it.

## Practice questions

1. Where do you find ready-made prompts for this book?

<details><summary>Answer</summary>In `ASK.md` at the book root.</details>

2. You want a live quiz on this lesson. What two things should you do in chat?

<details><summary>Answer</summary>`@` `lesson-04.md` (or this file), then ask to quiz you without showing answers first.</details>

3. Which table in `subjects/cursor/index.md` shows ⬜ / 🟡 / ✅?

<details><summary>Answer</summary>The Learning path table.</details>

4. You only want a quiz. Ask or Agent?

<details><summary>Answer</summary>Ask — you are not asking to edit files. Use Agent if you also want status marked in `index.md`.</details>

5. Chat says every lesson is ✅, but the learning path still shows 🟡. What do you believe?

<details><summary>Answer</summary>The `index.md` table in the editor, until you (or Agent, when you ask) update it.</details>

## Quick quiz

Ask the agent: `Quiz me on lesson-04.` (5 short questions, mixed recall + application)

## Summary

Quiz from a lesson’s objectives via `@` and a short prompt. Progress lives in this subject’s `index.md` (learning path, notes, glossary, media). [ASK.md](../../ASK.md) is the prompt menu — copy, fill in, send.

## Next

→ [Lesson 05](lesson-05.md) (A full study loop in this book)
