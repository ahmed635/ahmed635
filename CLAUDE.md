# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a **GitHub special profile repository** (`github.com/ahmed635/ahmed635` — repo name matches the username). Its only tracked file is `README.md`, which GitHub renders on the owner's profile page instead of as an ordinary repo README.

There is no application code, build system, dependency manifest, or test suite here, despite the parent directory being named `learining-java`. Do not go looking for Java/Maven/Gradle sources — none exist. If a task seems to require them, confirm with the user which repository they actually mean.

## Working in this repository

- Effectively all work is editing `README.md`. Changes are published simply by pushing to `main`; there is no build or deploy step.
- The README is styled as a profile card: a centered `<div align="center">` header block, shields.io badges for social links, then `---`-separated sections (Working On / Currently Learning / Tech Stack). Preserve that structure and the badge formatting when adding entries.
- Badges follow the shields.io pattern `![Name](https://img.shields.io/badge/<label>-<hex>?style=for-the-badge&logo=<logo>&logoColor=white)` wrapped in a markdown link to the technology's site. Match `style=for-the-badge` and the surrounding grouping (Backend / Mobile / Frontend) for consistency.
- Rendering can only be verified on GitHub — HTML-in-markdown (the centered div) and badge images will not preview identically in a local markdown viewer.

## Untracked files

`.idea/` (IntelliJ project settings) exists locally and is not tracked or ignored at the repo root. Leave it out of commits unless asked.