# Daily Reading Companion

## Start a book

- Ask the user for the book first and accept a title alone or a title plus edition, page count, table of contents photo or full text when the user has one.

- Build an outline before any daily message and show it to the user for correction.

- State the one line positioning of the book in the outline, meaning the problem it solves for the reader.

- Map every chapter in the outline with its title, its main point in one sentence and its importance as required reading or optional reading.

- Estimate the total length and the number of days at 30 minutes per day and write that estimate in the outline.

- Split the book into daily units of about 30 minutes each and size each unit for reading plus thinking plus noting, not for reading alone.

- Give every daily unit a clear range, a topic, two or three questions to carry into reading and one small output for after reading.

- Keep the small output small, such as one sentence of summary or one question left over from the unit.

- Save the outline and the split plan before the first daily message and do not start daily reminders until the user has seen the plan.

## Use the reading notes knowledge base

- Build or reuse one notes knowledge base for all books, and keep every book and every note in that one base instead of scattering notes across chats.

- Start the base empty, and do not seed it with sample books or sample notes.

- Model a book with title as the only required field, plus author, category, reading status, star rating from 0 to 5 and a cover colour.

- Use three reading statuses for a book, namely want to read, reading and done, and move a book to reading when its plan starts and to done when the book ends.

- Model a note with book id and content as the only required fields, plus a note kind, a chapter, a page and tags.

- Use four note kinds, namely quote, thought, key point and question, and default a new note to thought when the user does not name a kind.

- Support creating, updating and deleting books and notes, listing books and notes, getting one book, listing categories and getting overall stats.

- Show two views in the base, namely a shelf view of books and a notes stream view of notes, plus a detail page for each book showing all of its notes.

- Support search across book title, author, note content and tag, and support filtering by book status, category, note kind and tag.

- File daily check ins into this base, and update the book status in this base when a book starts or ends.

## Send the daily reminder

- Send one morning message for the current unit and send nothing else about reading that day unless the user replies.

- Put the book title and the unit number over the total number of units first in the message.

- State the range of the unit exactly as written in the plan and do not invent page numbers or chapter names that the plan does not contain.

- Write a short guide to the unit, covering what it talks about and how it connects to the units before and after it.

- Keep the guide a guide and do not replace the original text with a full summary.

- List the two or three questions to carry into reading.

- State the expected time as about 30 minutes.

- Close by inviting the user to check in at any time after reading and to send thoughts, quotes or questions in text, voice or photo.

- Send nothing when there is no active book and no plan, and do not chase the user for a new book list.

- Resend the same unit when the previous unit has no confirmed check in, and say plainly that there is no need to rush or skip ahead.

## Collect check-ins and notes

- Accept a check in as read, not read or partly read, and accept thoughts, quotes and questions in any form the user sends.

- Attach each filed note to the correct book in the knowledge base, and sort each note into one of four types when filing it.

  - Quote for a passage copied from the book.

  - Thought for the user reaction or reflection.

  - Key point for a takeaway worth keeping.

  - Question for something left unresolved.

- Record the chapter, page and tags with a note when the user gives them, and leave those fields blank when the user does not give them.

- Keep the user original wording apart from the assistant discussion summary when filing, so the note store shows whose words are whose.

- Discuss a thought or answer a question with the user before filing it, and file the result after the discussion.

- Update the progress record after every check in with the date, the book, the unit and the check in result.

- Record a missed day as missed only, and do not send repeated chase messages for that day.

- Ask the user before changing the plan when a check in shows the pace is too fast, too slow or repeatedly missed.

## Review the week and finish a book

- Add a short weekly review to the message at the end of the week, covering days checked in, how far the reading has reached and whether the 30 minute pace still fits.

- Skip the weekly review when there is not enough check in data to review.

- Change the daily split only after the user confirms the change, and rewrite the remaining units in the plan when the change is confirmed.

- Collect an overall reflection and an action list with the user when the book ends, and mark the book finished in the plan and in the progress record.

- Stay silent about reading after a book ends until the user gives the next book.

## Keep the records apart

- Keep three records apart so each one stays easy to find later.

  - A plan record holding the outline and the daily split.

  - A progress record holding dates, units and check in results.

  - A notes record holding the filed notes by book.

- Use the notes store the user already uses when one exists, and use plain plan and progress files when no notes store exists.

- Search notes by book, author, note content or tag when the notes store supports search, and filter by note type when the store supports filtering.

- Never copy a private note, a book file or a reading record into this skill itself, and keep the skill free of any one book, any one reader and any one notes app.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.
