# AGENTS.md

Important: after any important structural, dependency, or convention change, update this file so future agents know the current project setup and expectations.

## Project overview

This repository is a browser-based task list app called Kainos Task List. It is intentionally simple: static HTML, CSS, and JavaScript only, with no build step or package installation required.

## Project structure

- `index.html` — main application page and task list UI
- `popup.js` — JavaScript logic for the main app; contains the workshop task stubs and behavior for tasks 1–5
- `options.html` — settings page for configuration options
- `options.js` — JavaScript for the options/settings page, including stubs for Task 5
- `README.md` — project documentation, prerequisites, setup instructions, and workshop plan
- `.gitignore` — repository ignore rules
- `.git/` — Git metadata (not part of project source)

## Typical workflow

1. Open the project in VS Code.
2. Start the app by opening `index.html` in a browser or using a local static server.
3. Make changes in the JavaScript and HTML files.
4. Save the files and refresh the browser to test changes.

## Workshop tasks

The project is structured around five learning tasks:

- Task 1: Add tasks and persist them with `localStorage`
- Task 2: Mark tasks as done and delete them using event delegation
- Task 3: Add filter buttons for All / Active / Done and show a task counter
- Task 4: Add due dates, urgency badges, and sorting
- Task 5: Add AI-powered priority suggestions via the OpenRouter API

## Notes for future agents

- This is a frontend-only project; no backend, database, or package manager setup is required.
- Keep changes minimal and aligned with the workshop progression.
- Prefer simple vanilla JavaScript and DOM manipulation over frameworks.
- If updating the UI, match the existing Kainos styling conventions already present in `index.html`.
- Any AI features should be added in a way that is clearly separated from the base task list logic, especially for the Task 5 OpenRouter integration.
- Validate by refreshing the browser and checking the console for runtime issues.

## Expected conventions

- Use semantic HTML where practical.
- Keep functions readable and small.
- Preserve the workshop structure and task progression.
- Favor explicit, beginner-friendly code over abstract abstractions.

## References

- See `README.md` for the full workshop instructions and setup guidance.
