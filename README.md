# Daily Reading Companion

A Muse skill that turns a reading notes knowledge base into a daily habit.

It covers three things that work together:

1. A knowledge base for books and notes. Books carry title, author, category, want to read / reading / done status, a 0 to 5 rating and a cover colour. Notes carry a book, content, a kind of quote / thought / key point / question, plus chapter, page and tags. It has a shelf view, a notes stream view, a detail page per book, search and filters.
2. A book plan. Muse outlines a book, then splits it into daily units of about 30 minutes, each with a range, a topic, two or three questions to carry into reading and one small output.
3. A daily loop. One morning message with the day range, a short guide that does not replace the original text, and the questions. The reader checks in afterwards, Muse discusses the thoughts and questions, files the notes into the knowledge base, and records progress. A missed day resends the same unit instead of rushing ahead. A short weekly review closes the week.

## Install

Copy the skill folder into a Muse custom skills directory:

```bash
cp -r skills/daily-reading-companion ~/workspace/custom-skills/
```

Then ask Muse to start a book, for example by giving it a title. The knowledge base starts empty. No book, note or reading record from any previous user is included in this repository.

## Layout

- `skills/daily-reading-companion/SKILL.md` — the full skill.
- `skills/daily-reading-companion/skill.yaml` — name, title and description.

## Note on the original app

The knowledge base this skill describes was originally built as a private, server-backed app. That app itself cannot be exported as code, so this repository publishes the reproducible part: the data model, the views, and the daily workflow. Any Muse following this skill can rebuild the same empty knowledge base and run the same daily loop.
