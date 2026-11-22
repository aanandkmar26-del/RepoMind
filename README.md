# RepoMind

Understand any codebase. RepoMind is an AI-style GitHub repository analyzer: paste any public GitHub repo link and get an instant code-intelligence dashboard, right in your browser.

**Live demo:** https://aanand-designs.aanandkmar26.workers.dev/repomind

## What it does

RepoMind is a single-file, fully client-side web app. It calls the public GitHub REST API directly from your browser, no server, no backend, no sign-in needed.

## Features

- **Repository stats** at a glance for any public GitHub repo
- **Programming languages** breakdown
- **Project folders** overview
- **File explorer** to browse the repo tree
- **File extensions** analysis
- **README preview** rendered in the dashboard
- **View on GitHub** quick link to the source repo

## How to run

No build step, no install:

1. Download `repomind.html` from this repo.
2. Open it in any modern browser (phone or desktop).

Or just use the live demo link above.

## Tech notes

- Vanilla HTML/CSS/JS in one self-contained file (`repomind.html`).
- Uses the public GitHub REST API (`api.github.com`) from the browser.
- Unauthenticated GitHub API usage is rate limited to 60 requests per hour per IP address. If you analyze many repos in a short time, wait for the limit to reset.
- Google Fonts (Inter, Space Grotesk, JetBrains Mono) loaded via CDN.

---

RepoMind &copy; 2026, built for developers. Crafted with care by [Aanand Designs](https://aanand-designs.aanandkmar26.workers.dev/).
