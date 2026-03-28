# CLAUDE.md

This file provides guidance for AI assistants working with this repository.

## Repository Overview

This is a minimal tutorial repository created via **GitHub Desktop**. Its purpose is to help new users learn basic Git and GitHub Desktop workflows. The repository contains a single `README.md` file that serves as a hands-on introduction to editing files, committing changes, and syncing with GitHub.

## Repository Structure

```
desktop-tutorial/
├── README.md       # Tutorial file — users write their name on line 6
└── CLAUDE.md       # This file
```

## Development Conventions

- **Branch**: All development happens on feature branches. The primary branch is `main`.
- **Commits**: Use clear, descriptive commit messages in the imperative mood (e.g., `Add CLAUDE.md documentation`).
- **Files**: Keep this repository minimal — it is a learning tool, not a production project. Do not add unnecessary files or dependencies.

## Key Workflows

### Making Changes
1. Edit `README.md` (or other files) locally.
2. Stage and commit changes with a descriptive message.
3. Push to the remote branch using `git push -u origin <branch-name>`.

### Git Branching
- Feature branches follow the pattern: `claude/<description>-<id>` for AI-assisted work.
- Always develop on the designated feature branch; never push directly to `main` without a pull request.

## Notes for AI Assistants

- This repository has no build system, test suite, linter, or package manager — no `npm install`, `make`, or similar commands are needed.
- The only meaningful content file is `README.md`. Changes should be focused and minimal.
- When asked to update documentation, prefer editing existing files over creating new ones.
- Do not introduce frameworks, dependencies, or tooling unless explicitly requested by the user.
