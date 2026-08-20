# Ask the agent

Use **Agent** mode. Replace `SUBJECT` and numbers as needed.

## Build lessons

```
Build tutoring lessons for SUBJECT, beginner, 5 lessons.
```

```
Build tutoring lessons for SUBJECT. Ask me level, how many lessons, and language first.
```

## Find a topic

```
@index.md Find the subject or lesson about Y.
```

```
Search this book for Y. If there is no lesson, say so. Do not invent a file path.
```

## Tutor / study

```
@lesson-01.md Quiz me. Do not show answers until I try.
```

```
@lesson-02.md Help me tutor this. Ask me a check question first, then explain if I am stuck.
```

## Media

```
Search this book for "missing". List lessons that still need video, audio, image, or diagram.
```

## Building on a subject

- Add a lesson: `Add lesson 0X to <subject>, covering <topic>.`
- Expand a lesson: `Add a worked example and 3 more practice questions to lesson-0X of <subject>.`
- Adjust level: `Rewrite lesson-0X of <subject> for a <level> audience.`
- Translate: `Translate lesson-0X of <subject> into <language>.`

## Studying

- Quiz me: `Quiz me on lesson-0X of <subject>.`
- Review progress: `Summarize my progress in <subject> and suggest what to study next.`
- Spaced review: `Give me a quick review quiz mixing lessons 01–03 of <subject>.`

## Maintenance

- Fill media gaps: `Find or suggest media for lesson-0X of <subject> where media is "missing".`
- Update glossary: `Extract new terms from lesson-0X and add them to <subject>/index.md glossary.`
- Update status: `Mark lesson-0X of <subject> as done in index.md and update the media inventory.`
