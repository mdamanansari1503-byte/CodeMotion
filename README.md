# CodeMotion — Code in Motion
Created by MD Aman

A read-only Python learning site with prepared solutions and step-by-step visual explanations. It does not execute visitor-entered code.

## Run locally
Because the site loads `questions.json` with `fetch()`, open the folder using a local server such as **Live Server** in VS Code. Do not double-click `index.html`.

## Add or edit questions
All question content lives in `questions.json`. Each question has an `id`, `title`, `intro`, `problem`, `input`, `output`, `code` array and `steps` array. To show a question in a learning level, add its ID to that level's `questions` array. Python and ICPC have separate level lists. Python Level 1 currently contains questions 1–10.

### Important
- Keep each question ID unique.
- `code` is an array of lines, so each item becomes a separate highlighted line.
- Each `steps` entry has `heading`, `text`, and `visual` (an array of values shown in the animation panel).
- ICPC levels are intentionally separate and currently awaiting their own question content.
# CodeMotion
