# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

A GitHub **profile README** repository (repo name matches the username `hanzala-bhutto`, so `README.md` renders on the profile page at github.com/hanzala-bhutto). There is no build, test, or lint step — it is `README.md` plus banner GIF assets (`Hero Banner.gif`, `Simple Technology LinkedIn Banner updated.gif`). Changes take effect when pushed to `main`; verify by viewing the rendered README on GitHub.

## Conventions

- Icons come from remote badge services, not local files. Keep to the existing sources rather than mixing new ones:
  - `skillicons.dev/icons?i=<slugs>&theme=dark` — most tech-stack rows.
  - `go-skill-icons.vercel.app/api/icons?i=<slugs>` — used for the Databases row (fallback when a slug is missing from skillicons).
  - `img.shields.io/badge/...` — for concepts that have no icon slug (e.g. Event-Driven Systems).
  - `cdn.simpleicons.org/<slug>/<color>` — the "Connect with me" social icons.
- Stats cards point at a **self-hostable fork**, `github-readme-stats-eight-theta.vercel.app`, not the rate-limited public `github-readme-stats` instance. Keep this host when editing stats/top-langs cards. Theme is `radical`.
- Content is authored as inline HTML (`<img>`, `<p align>`, `<h3>`) rather than Markdown image syntax, to control alignment and sizing. Follow the existing HTML style when adding sections.
- Image `src` values that are local files reference the GIFs by their exact filenames (which contain spaces) — preserve the spaces.
