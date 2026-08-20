# Subjects

Put each subject in its own folder, copied from [_template](_template/index.md).

When Agent builds a subject, it should:

1. Create `subjects/<slug>/`
2. Copy `_template/index.md` → `index.md`, fill frontmatter and the learning-path table
3. Copy `_template/lesson-01.md` → `lesson-01.md` for the first lesson; generate further lessons one at a time (see [HOW-TO-TUTOR.md](../HOW-TO-TUTOR.md))
4. Add an `images/` folder
5. Add a row to the book [index.md](../index.md)

After any lesson change, keep that subject's `index.md` current: learning-path status, media inventory, glossary, and `updated` date.
