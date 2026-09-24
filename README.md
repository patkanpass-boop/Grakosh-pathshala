# Grahakosha Pathshala

A self-study course in Parashari Jyotisha, built as a single offline HTML file.
Companion to Grahakosha Journal.

## Features
- 18 lessons across Foundation, Intermediate and Advanced levels
- A quiz at the end of every lesson (60% unlocks the next)
- Endless drills generated from reference tables
- Spaced-repetition flashcards
- Doubts notebook with a "copy for AI tutor" option
- Glossary with Devanagari terms
- Progress tracking, streaks, and backup export/import

## Run it
Open `index.html` in any modern browser. No internet or installation needed.

## Host it on GitHub Pages
1. Create a new repository on GitHub (e.g. `grahakosha-pathshala`).
2. Upload `index.html`, `README.md` and `.nojekyll` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, then save.
5. After a minute or two the app is live at `https://<your-username>.github.io/grahakosha-pathshala/`.

## Your data
Progress, flashcards and doubts are stored in your browser's local storage on each device.
Use **Progress → Export backup** regularly, and **Import backup** to move to another device.

## Adding lessons
All course content lives in the `LESSONS` array inside `index.html`. Each lesson has:
- `id`, `m` (module id), `t` (title)
- `body` (HTML content)
- `quiz` (questions with options `o`, correct index `a`, explanation `x`)
- `cards` (flashcard front/back pairs)
