# Contributing Guide

Thanks for helping make Halloween Matrix awesome!

## Branching Model
- `main` – always deployable
- Create feature branches from `main`: `feature/<short-name>`
- Create fix branches: `fix/<short-name>`

## Commit Style
Use clear, present-tense messages. Conventional commits are welcome:
- `feat: add witch palette`
- `fix: mobile canvas sizing`
- `docs: update README`

## Pull Requests
1. Open a PR to `main` with a descriptive title.
2. Fill out the PR template.
3. Required: at least **1 approving review** and all checks green.
4. Link related issues with `Closes #123`.

## Code Style
- Keep JS readable; comment tricky parts.
- Accessibility matters: labels, focus states, aria where useful.

## Issues
- Use *Bug report* / *Feature request* templates.
- Provide repro steps and screenshots for bugs.

## Local Testing
- Open `index.html` directly in a browser, or run a simple server:
  ```bash
  python3 -m http.server 5173
  # open http://localhost:5173
  ```
