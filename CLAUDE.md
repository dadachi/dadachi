# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is the GitHub **profile README** repository for the user `dadachi` (the repo name matches the username, so `README.md` renders on https://github.com/dadachi). It contains no application code, build system, or tests — only:

- `README.md` — the rendered profile page (HTML-in-Markdown, centered headers, shields.io badges, dynamic GitHub-stats cards)
- `assets/` — images referenced by the README (e.g. `printora.png`)

There are no build, lint, or test commands. Changes are validated by how they render on GitHub, not by tooling.

## Working conventions

- **Audience & intent:** The README is a marketing/recruiting page for a solo full-stack mobile engineer (native iOS + Android + Rails). Edits should preserve that positioning — concrete, credibility-signaling detail (test counts, star counts, launch dates, rankings) over generic self-description.
- **Formatting:** The file mixes raw HTML (`<p align="center">`, `<img>`) with Markdown. Match the existing style; keep the section anchors intact (e.g. `#-get-in-touch`) since internal links depend on them.
- **Images:** Reference assets by relative path (`assets/...`), not absolute URLs, so they render in the repo and on the profile.
- **External stats:** GitHub-stats and top-langs cards are fetched live from `github-readme-stats.vercel.app` with `theme=dark`. Keep the theme consistent if adding more cards.
- **Verifying a change:** Preview Markdown+HTML rendering as GitHub would display it (GitHub-flavored Markdown); there is nothing to compile or run.
