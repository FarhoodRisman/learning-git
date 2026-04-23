# My Claude Code Journal

## 2026-04-23 — Getting Started with Git & GitHub

Today I set up my first Git repo and pushed it to GitHub using Claude Code.

### What is a .md file?
- `.md` stands for **Markdown** — a lightweight text formatting language
- Uses plain text with simple syntax: `#` for headings, `**bold**`, `-` for bullet lists
- GitHub automatically renders `.md` files as formatted pages (like this one)
- `README.md` is the standard file GitHub shows on a repo's homepage

### General structure of a repo
- **Root folder** — the top-level directory tracked by Git
- `.git/` — hidden folder Git uses internally to track history (don't touch this)
- `README.md` — describes the project; shown on the GitHub repo page
- Files are tracked via **commits** — snapshots of changes with a message explaining what changed
- **Branches** let you work on changes without affecting the main codebase (`main` is the default)
- **Remote** (e.g. GitHub) is the cloud copy; `git push` sends local commits there
