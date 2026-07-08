# Tanvi Pandey — Portfolio

A single-page portfolio site built with plain HTML/CSS/JS — no build step, no dependencies, no framework.

## Preview

**Hero**
![Hero section](screenshots/hero.png)

**Work**
![Work section](screenshots/work.png)

**About**
![About section](screenshots/about.png)

**Contact**
![Contact section](screenshots/contact.png)

## Features
- Dark hero with an interactive animated pipeline diagram (Data → Model → App → You) — hover any node for details
- Typewriter role text (ML Engineer / Full-Stack Developer / App Builder / Data Scientist)
- Scroll-reveal animations on each section
- Notebook-cell styled project cards with hover effects
- Fully responsive layout

## Structure
- `index.html` — the entire site (hero, work, about, contact)
- `screenshots/` — preview images used in this README

## Run locally
Just open `index.html` in a browser, or serve it with any static server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Deploy (free options)
- **GitHub Pages**: Settings → Pages → Deploy from branch → root
- **Netlify / Vercel**: drag-and-drop this folder or connect the repo

## Edit content
All text, links, and project details live directly in `index.html` — search for the section (`Work`, `About`, `Contact`) and edit inline.
