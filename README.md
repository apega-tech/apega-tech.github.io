# apega-tech.github.io

My personal portfolio site — built to showcase my transition into software
engineering, along with the projects, resume, and background that go with
it. Live at **https://apega-tech.github.io**

## Stack
- HTML / CSS (single file, no build tools or frameworks)
- Vanilla JavaScript for the terminal boot animation, scroll reveals, and mobile nav
- Google Fonts (Space Grotesk, Inter, JetBrains Mono)

## What's here
- `index.html` — the entire site (structure, styles, and script all in one file)
- `resume.pdf` — downloadable resume, linked from the nav and contact section

## Sections
- **Hero** — a terminal-style "boot sequence" intro
- **About** — background and current focus
- **Skills** — grouped by Frontend / Backend & Core / Tools & Practices
- **Experience** — styled as a commit log, most recent first
- **Projects** — links out to each project's own repo:
  - [inventory-tracker](https://github.com/apega-tech/inventory-tracker) — Flask + SQLite CRUD app
  - [transaction-analysis](https://github.com/apega-tech/transaction-analysis) — pandas/matplotlib data analysis
  - [compliance-validator](https://github.com/apega-tech/compliance-validator) — rule-based data validation tool
  - [algorithms-log](https://github.com/apega-tech/algorithms-log) — Python & Java DS&A solutions
- **Education**
- **Contact** — email and LinkedIn

## Running it locally
No build step needed — just open `index.html` in a browser. To preview it
the same way GitHub Pages serves it, you can also run a simple local
server from this folder:
```bash
python -m http.server 8000
```
Then visit http://localhost:8000

## Deployment
This repo is named `apega-tech.github.io`, which GitHub automatically
publishes as a live site at that URL whenever `index.html` sits at the
root of the `main` branch — no extra configuration required.

## Possible next steps
- Swap the "View Repo" project links for live demo links as projects get deployed
- Add a blog/notes section for write-ups on what I'm learning
- Add basic analytics to see which sections get the most attention
