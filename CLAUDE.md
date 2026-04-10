# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

This repository is currently empty. Update this file as the project grows to include:
- Build, lint, and test commands
- High-level architecture overview
- Any non-obvious conventions or constraints

## Workflow

After completing each task, always:
1. `git add` the relevant files
2. `git commit` with a clear, descriptive message
3. `git push origin master` to push to GitHub

## index.html Rule

After **every** change to `index.html`, immediately:
1. `git add index.html`
2. `git commit` with a descriptive message summarizing what changed
3. `git push origin master`

Never leave `index.html` with uncommitted changes. There should be no exceptions to this rule.
