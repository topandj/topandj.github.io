# Anđela Topalović — Portfolio & CV

A single-page interactive portfolio and CV built with HTML, Tailwind CSS, and a small React module. Dark theme, scroll-snap sections, and optional photo panels on the "Beyond Work" section.

## Features

- **Sections:** Contact, Summary, Experience, Education, Technologies, Languages, Beyond Work
- **Navigation:** Fixed side nav with active section highlight and smooth scroll
- **Technologies:** Searchable tech tags (React component) — recently used vs. used in the past
- **Beyond Work:** Hover over items (Nature and wildlife, Travel/sports, Dogs) to show a photo strip panel; custom cursor with “point the item” hint
- **Print-friendly:** Nav and side panels hidden when printing
- **Responsive:** Layout adapts to smaller screens; nav hidden on small viewports

## Tech stack

- **HTML5** — Semantic structure, `lang="en"`
- **Tailwind CSS** (CDN) — Styling
- **React 18** (ESM via esm.sh) — Technologies section only
- **Vanilla JS** — Scroll sync, hash routing, photo panel, custom cursor, date stamp

## Quick start

1. **Clone or download** this repo.
2. **Images (optional):** Place your images in an `img/` folder next to `andjela_portfolio.html`:
   - `Kenya.JPG`, `Kenya2.JPG`, `Kenya3.jpeg` — Nature and wildlife
   - `NinaDjina.jpeg`, `NinaDjina2.jpeg`, `NinaDjina3.jpeg` — Dogs
   - `tso.JPG`, `tso2.jpeg`, `tso3.jpeg` — Travel, sports and outdoor  
   If `img/` or files are missing, those panels simply won’t show images.
3. **Open the page:**
   - **Local:** Double-click `andjela_portfolio.html` or open it in a browser.  
   - **With a local server (recommended for CORS/ESM):**  
     `npx serve .` or `python3 -m http.server 8000` then open `http://localhost:8000/andjela_portfolio.html`.

## Project structure

```
cv/
├── README.md
├── andjela_portfolio.html   # Single-file portfolio (HTML + CSS + JS + React)
└── img/                     # Optional: add images listed above
```

## Browser support

- Modern browsers with ES modules and `scroll-snap` support (Chrome, Firefox, Safari, Edge).  
- The Technologies section requires JavaScript (React loads from esm.sh).

## License

This project is for personal/portfolio use. All rights reserved unless otherwise stated.
# topandj.github.io
