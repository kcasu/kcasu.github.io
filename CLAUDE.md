# CLAUDE.md — How we build this portfolio together

This file is guidance for Claude Code sessions working in this project.
It describes the collaboration workflow, current decisions, and conventions.

## What we're building

A personal portfolio website for Kavya Casula: projects, skills, experience,
and contact info. Priorities are speed, simplicity, and easy content updates.

## How we work together

1. **Discuss before big changes.** For new sections, redesigns, or tech
   decisions (frameworks, hosting), propose an approach and get Kavya's
   sign-off before building. Small tweaks and fixes can just be done.
2. **Show, don't describe.** After visual changes, open the result in Chrome
   so Kavya can see it:
   `open -a "Google Chrome 2" <file>` (Chrome is installed under that name).
3. **Verify with Playwright.** Playwright for Python is installed
   (`python3 -m playwright ...`, Chromium only). Use it to screenshot pages
   and sanity-check layout/behavior before declaring something done.
4. **Content and design are separate concerns.** Keep real content (project
   descriptions, bio, links) easy to edit without touching layout code.
5. **Iterate in small steps.** One coherent change per round — easier to
   review in the browser and easier to roll back.

## Decisions so far

| Decision | Status |
|---|---|
| Tech stack | **Undecided** — start with plain HTML/CSS; revisit if it gets unwieldy |
| Hosting | Undecided (GitHub Pages, Netlify, and Vercel are candidates) |
| Design direction | **Kavya's Figma file is the style reference** — see `design-ref/STYLE-GUIDE.md` (palette, type, patterns) and `design-ref/figma-*.png` exports; `design-ref/style-tile.html` is a browsable summary |
| Version control | Not initialized yet — `git init` when real work starts |

Update this table as decisions get made.

## Environment notes

- macOS (Apple Silicon), Homebrew available
- Python 3.11 at `python3`; **Node.js is NOT installed** — don't assume npm
  exists; if the stack ever needs Node, install it via Homebrew first
- Playwright CLI is not on PATH; always invoke as `python3 -m playwright`
- Chrome application name is `Google Chrome 2.app`

## Conventions

- `index.html` at the project root is the entry point
- Project detail pages live in `projects/` (one page per project card;
  cards on the homepage link to them)
- Shared styles (tokens, navbar, tags) in `styles/main.css`; page-specific
  CSS stays inline in each page
- Assets in `assets/` (images, fonts) — originals are kept alongside the
  web-optimized copies the site actually serves
- Placeholder content is fine while designing, but mark it clearly
  (e.g. `<!-- PLACEHOLDER -->`) so it doesn't ship by accident
