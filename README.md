# Maria Estenzo — Personal Portfolio

A responsive, single-page portfolio for Maria Antonietta C. Estenzo, built with semantic HTML, CSS, and vanilla JavaScript.

## Run locally

Open `index.html` directly, or serve this folder from a local web server. With XAMPP, start Apache and visit `http://localhost/portfolio/MariaPortfolio/`. The page has no build step or framework dependencies. Google Fonts are optional; the site falls back to system sans-serif fonts if they are unavailable.

## Deploy to Vercel

1. Upload or push the **contents of `MariaPortfolio`** to GitHub, including `index.html`, `css/`, `js/`, `images/`, and `vercel.json`.
2. If the GitHub repository contains the outer `portfolio/` folder, set Vercel's **Root Directory** to `MariaPortfolio` in the project settings. If the repository itself is the contents of `MariaPortfolio`, leave Root Directory as `./`.
3. Keep the framework preset set to **Other** and leave the build command empty. `vercel.json` sets the output directory to this folder. This is a static HTML site; no `package.json` or build step is needed.
4. Redeploy. The root rewrite in `vercel.json` directs `/` to `index.html`.

## Project structure

```text
MariaPortfolio/
├── index.html
├── vercel.json
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   ├── profile.jpg
│   ├── activities/
│   └── projects/
└── README.md
```

The profile image is `images/profile.jpg`, project screenshots are stored in `images/projects/`, and activity photos are stored in `images/activities/`.

## Features

- Dark, responsive layout with pink, purple, and blue accents
- Keyboard-accessible mobile navigation and skip link
- Smooth anchor navigation and active-section indicators
- Scroll-triggered reveal effects with reduced-motion support
- Functional email and GitHub links
- No frontend frameworks or build dependencies