# Workflow (MVP)

Goal: learn C++ from learncpp.com. Don't make this system "better" until it has been used for a full chapter.

## Layout

```
chapter-NN/
  notes.md        one file per chapter, one `##` heading per lesson
  examples/       code typed out from lessons
  quizzes/        my quiz answers
projects/
  <name>/
    PLAN.md       goal, minimal feature list, lessons it depends on
    LOG.md        where I'm stuck, what I tried, what's next
    src/ ...
```

## Per-lesson loop (notes take about 5 minutes; a guideline, not a limit)

1. Read the lesson and type out the examples into `examples/`.j fdsafsdaf
2. Add a section to `chapter-NN/notes.md` using the template below.
3. Move on. Don't copy the lesson or write a book.

## Notes template

```md
## N.N – Lesson title

**In my own words:** 3–6 sentences. No copy-pasting.

**Key concepts/terms:** concepts/term – short definition

**Gotchas / mistakes I made:** things that broke or surprised me

**Open questions:** things I didn't fully get
```

## Rules

1. Write in my own words.
2. Don't polish every lesson. Change the template or fix notes only when there's a real error, a gap, or a reason to improve the system.
3. Fill in "Gotchas" and "Open questions" when something applies; "none" is fine. They drive recall questions and mock exams.
4. Code goes in `examples/` or `quizzes/`. Notes only get a tiny snippet when it clarifies a point.

## End of chapter

- Ask for active recall questions on the chapter, answered in chat.
- Ask for a mock exam when the chapter feels done.
- Fix notes where answers revealed gaps.

## Pet projects

- Start one only after a chapter whose concepts it uses. Keep it small.
- Write `PLAN.md` first (with help). Then code it myself.
- When stuck, update `LOG.md` and ask for a hint, not a solution.
