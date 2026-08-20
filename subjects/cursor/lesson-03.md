---
lesson: 03
subject: cursor
title: "@ files and what the agent can see"
level: beginner
duration_minutes: 20
status: draft
---

# Lesson 03: `@` files and what the agent can see

## Learning objectives

By the end of this lesson you should be able to:

- Explain what an `@` mention does in chat
- Point the agent at a lesson or `index.md` on purpose
- Identify what the agent might miss if you do not `@` a file

## Prerequisites

[Lesson 01](lesson-01.md) (files vs chat) and [lesson 02](lesson-02.md) ([Ask](lesson-02.md) / [Agent](lesson-02.md) / [Plan](lesson-02.md)). You already know lessons live as files.

## Key terms

- **`@` mention** — typing `@` in chat and picking a file (or folder) so the agent is told to use it
- **Context** — the files and text the agent is actually looking at for this message

## Explanation

The agent is not magically reading every file in the book all the time. Chat is more like handing someone a specific paper. `@` is how you hand over that paper.

### What `@` does

In the chat box, type `@` then choose a file, for example `lesson-01.md` or `index.md`. Your message now means: “Answer using *this* file.”

You can `@` more than one file if the question needs both (a lesson and the subject index).

### Why this matters for studying

- `@lesson-01.md` then `Quiz me` → questions should come from that lesson’s objectives, not a random guess.
- `@index.md` then `What should I study next?` → the agent can see the learning-path table.
- No `@` and a vague `Quiz me` → the agent may quiz the wrong lesson, or invent a path that is not in the book.

### What the agent still might not see

Even with `@`, the agent only sees what you attached (plus what you typed). It does not automatically know a screenshot you never added, or a lesson file you never mentioned.

If an answer cites a file that does not exist, believe [Explorer](lesson-01.md), not chat. Search the book; do not invent a path — that is also in [ASK.md](../../ASK.md).

## Media

- 🎥 Video: missing
- 🔊 Audio: missing
- 🖼️ Image: missing — put file in `images/`, or link a URL
- 📊 Diagram: missing — a sketch of chat with `@lesson-01.md` attached to a message would help here

## Worked example

You want a quiz on the window layout, not on Ask vs Agent.

1. Open chat. [Ask](lesson-02.md) is enough (no file edits).
2. Type `@` and pick `subjects/cursor/lesson-01.md`.
3. Type: `Quiz me. Do not show answers until I try.`
4. The first question should match lesson 01 (Explorer, editor, chat), not lesson 02 modes.

If the first question is about Plan mode, stop and check: did you `@` the wrong file, or none at all? Fix the `@` and ask again.

## Practice questions

1. What does typing `@` and choosing a file do?

<details><summary>Answer</summary>It adds that file to the message’s context — you are telling the agent to use it.</details>

2. You want a quiz only on lesson 02. What should you `@`?

<details><summary>Answer</summary>`lesson-02.md` (the Cursor lesson 02 file), then ask for the quiz.</details>

3. You want to know which Cursor lessons are still ⬜. Which file is the better `@`?

<details><summary>Answer</summary>This subject’s `index.md`, which has the learning-path table. (The book root `index.md` only lists subjects.)</details>

4. You type `Quiz me` with no `@`. What can go wrong?

<details><summary>Answer</summary>The agent may quiz a different lesson, mix subjects, or invent content that is not in a file.</details>

5. The agent says to open `subjects/cursor/lesson-99.md`, but Explorer has no such file. What do you trust?

<details><summary>Answer</summary>Explorer. Chat can invent paths. Do not assume a file exists until you see it.</details>

## Quick quiz

Ask the agent: `Quiz me on lesson-03.` (5 short questions, mixed recall + application)

## Summary

`@` hands the agent a specific file. Context is what it can see for this message. For quizzes and progress, `@` the lesson or `index.md` you mean; if chat names a missing file, believe Explorer.

## Next

→ [Lesson 04](lesson-04.md) (Quiz, progress, and ASK.md prompts)
