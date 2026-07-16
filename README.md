# apega-tech.github.io

My personal portfolio site — built to showcase my background as an
aspiring Software Engineer, along with the projects, resume, and
experience that go with it. Live at **https://apega-tech.github.io**

## Stack
- HTML / CSS (single file, no build tools or frameworks)
- Vanilla JavaScript for scroll reveals and the mobile nav toggle
- Google Fonts (Space Grotesk, Inter, JetBrains Mono)

## What's here
- `index.html` — the entire site (structure, styles, and script all in one file)
- `resume.pdf` — downloadable resume, linked from the nav and contact section

## Sections
- **Hero** — name, role tag, and a short intro
- **About** — background and current focus
- **Skills** — grouped by Frontend / Backend & Core / Tools & Practices
- **Experience** — styled as a commit log, most recent first
- **Projects** — each links to its own source repo and a working live demo:
  - [inventory-tracker](https://github.com/apega-tech/inventory-tracker) — Flask + SQLite CRUD app · [live demo](https://apega-tech.github.io/inventory-tracker/)
  - [transaction-analysis](https://github.com/apega-tech/transaction-analysis) — pandas/matplotlib data analysis · [live demo](https://apega-tech.github.io/transaction-analysis/)
  - [compliance-validator](https://github.com/apega-tech/compliance-validator) — rule-based data validation tool · [live demo](https://apega-tech.github.io/compliance-validator/)
  - [algorithms-log](https://github.com/apega-tech/algorithms-log) — Python & Java DS&A solutions · [live demo](https://apega-tech.github.io/algorithms-log/)
- **Education**
- **Contact** — Email, LinkedIn, and Resume buttons (all match in style, lift and turn orange on hover)

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
root of the `main` branch — no extra configuration required. `resume.pdf`
must also sit at the root for the download buttons to work.

## Possible next steps
- Add a blog/notes section for write-ups on what I'm learning
- Add basic analytics to see which sections get the most attention
- Keep Experience/Education in sync as the resume evolves
ns get the most attention
- Keep Experience/Education in sync as the resume evolves
