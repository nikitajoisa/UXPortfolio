# Nikita Joisa — UX/UI Portfolio

A single-page portfolio site built around one deep case study rather than several shallow ones: the redesign of **LeisureWorld Cork**'s website.

The case study walks through Background → Problem → Process → Final Product → Impact → Reflections, all in one scroll.

## What's inside

- **`index.html`** — the portfolio site (About Me + the LeisureWorld Cork case study), built as a single self-contained HTML file with inline CSS and JavaScript. No build step, no dependencies beyond Google Fonts and Chart.js (loaded via CDN for the research charts).
- **`Images/`** — screenshots, product photography, and UI assets used throughout the case study.
- **`Videos/`** — before/after screen recordings for the Homepage, Swim School, and Centre Policies sections, plus process videos (ideation and prototyping).
- **`trial.html/`** — an earlier working draft of the page, kept for reference.

## Highlights of the case study

- Stakeholder mapping, empathy maps, and journey maps synthesised into prioritised design decisions
- A before/after comparison toggle for each redesigned page (Homepage, Swim School, Centre Policies)
- Data visualisations (Chart.js) showing emotional journey trends and pain-point priority
- A living design system panel (typefaces, colours) pulled from the live site's stylesheet

## Running locally

This is a static site — no build tools required. Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Tech

HTML, CSS, JavaScript — no frameworks. Chart.js (via CDN) for the data visualisations.

## Contact

- Email: [nikitajoisaie@gmail.com](mailto:nikitajoisaie@gmail.com)
- LinkedIn: [linkedin.com/in/nikitajoisa](https://www.linkedin.com/in/nikitajoisa/)
