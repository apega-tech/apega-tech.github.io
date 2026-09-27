# apega-tech.github.io

My personal portfolio site — built to showcase my background as an aspiring Software Engineer, along with the projects, resume, and experience that go with it. Live at https://apega-tech.github.io

## Stack

- HTML / CSS (single file, no build tools or frameworks)
- Vanilla JavaScript for the light/dark mode toggle (saves your choice in the browser)
- Google Fonts (Space Grotesk, Inter, JetBrains Mono)
- Custom cursor images embedded directly in the CSS

## What's here

- `index.html` — the entire site (structure, styles, script, and cursor images all in one file)
- `resume.pdf` — downloadable resume, linked from the nav and contact section
- `README.md` — this file

## Sections

- **Hero** — name, "open to work" tag, and a short intro
- **About** — background, current focus, and quick facts (location, email, phone, current training, studies)
- **Skills** — grouped by Languages & Frameworks / Tools & Practices / Core CS
- **Experience** — timeline, most recent first: Year Up United, Food Garden Market, PLS Check Cashers
- **Projects** — each links to a working live demo:
  - [inventory-tracker](https://github.com/apega-tech/inventory-tracker) — Flask + SQLite CRUD app · [live demo](https://apega-tech.github.io/inventory-tracker/)
  - [algorithms-log](https://github.com/apega-tech/algorithms-log) — Python & Java DS&A solutions · [live demo](https://apega-tech.github.io/algorithms-log/)
  - [transaction-analysis](https://github.com/apega-tech/transaction-analysis) — pandas data analysis · [live demo](https://apega-tech.github.io/transaction-analysis/)
  - [compliance-validator](https://github.com/apega-tech/compliance-validator) — rule-based data validation tool · [live demo](https://apega-tech.github.io/compliance-validator/)
- **Education & Certifications** — WGU, Year Up United, plus Linux, ITIL Foundation, Java, Back-End, and AI Optimization certificates
- **Contact** — Email, LinkedIn, and Resume buttons (all match in style, lift and glow violet on hover)

## Features

- Light and dark mode toggle in the nav
- Responsive layout for desktop and mobile
- Custom cursor: blade arrow by default, scout hand over links and buttons

## Running it locally

No build step needed — just open `index.html` in a browser. To preview it the same way GitHub Pages serves it, you can also run a simple local server from this folder:

```
python -m http.server 8000
```

Then visit http://localhost:8000

## Deployment

This repo is named `apega-tech.github.io`, which GitHub automatically publishes as a live site at that URL whenever `index.html` sits at the root of the `main` branch — no extra configuration required. `resume.pdf` must also sit at the root for the download buttons to work.

## Credits

Custom cursor pack from Sweezy Cursors.

## Possible next steps

- Add a blog/notes section for write-ups on what I'm learning
- Add basic analytics to see which sections get the most attention
- Keep Experience/Education in sync as the resume evolves
