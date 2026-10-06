# Hablar ya

Spanish learning platform for Russian speakers. Static, dependency-free HTML/CSS/JavaScript, deployed on Vercel.

## Included

- 12 introductory A1–A2 topic lessons with examples, quizzes and explanatory feedback.
- 72 searchable vocabulary items, favorites, browser speech synthesis and spaced repetition (1, 3, 7, 14, 30 days).
- 6 grammar guides; 4 authored choice-based dialogues.
- Listening, phrase selection, word matching and flashcards.
- Local progress, daily goals, streaks, achievements, validated JSON export/import.
- Responsive layouts and keyboard-accessible controls.

## Run and deploy

Serve the repository with any static server, e.g. `python -m http.server 3000`.
Vercel: Other framework, no build or install command, output directory `.`. Entry point: index.html.

## Scope

An introductory learning application, not a complete CEFR course or certification. A1/A2 labels indicate topic difficulty. XP measures practice, not proficiency. Progress stays in localStorage on the current browser. Export a backup to move it elsewhere. No accounts, server database, analytics or paid API dependencies. Audio uses available browser Spanish voices. Dialogues are authored choices, not AI conversations or pronunciation scoring.

## Verification

JavaScript syntax and automated logic checks covered all seven sections, lesson completion at 2/3 correct, duplicate-answer prevention, review scheduling, dialogue retries/completion, practice pools and persistence. Visual browser testing was unavailable in the authoring environment.
