# Arun Khanchandani — Portfolio

Personal portfolio site: [arunkhanchandani.vercel.app](https://arunkhanchandani.vercel.app)

A single-page, dark-themed portfolio showcasing my work as an AI Engineer — RAG pipelines, agentic systems, and backend engineering.

## Overview

Built as a single static `index.html` with no build step or framework — vanilla HTML, CSS, and JavaScript. Chosen deliberately for zero dependencies, instant load times, and trivial deployment.

**Sections:**
- **Hero** — animated role-typing intro
- **About** — background, experience summary, key stats
- **Projects** — featured AI projects with live demos, GitHub links, and demo videos
- **Skills** — grouped by AI & LLM, Backend, Infrastructure, and Engineering Rigor
- **Certifications** — credentials with verification links
- **Contact** — email (click-to-copy), LinkedIn, GitHub

## Tech Stack

- **HTML5 / CSS3** — custom properties (CSS variables) for theming, CSS Grid for layout, no framework
- **Vanilla JavaScript** — typing animation, scroll-based nav highlighting, animated counters, mobile menu, click-to-copy email
- **IntersectionObserver API** — scroll-triggered reveal animations and stat counters, with a scroll/resize fallback for unsupported browsers
- **Google Fonts** — Inter typeface
- **Deployment** — [Vercel](https://vercel.com), static hosting

## Features

- Fully responsive (mobile-first breakpoints at 860px and 560px)
- Respects `prefers-reduced-motion` for accessibility
- No external JS dependencies — everything hand-rolled for a small footprint
- Semantic HTML with ARIA labels on interactive elements (nav, hamburger menu, mobile overlay)

## Local Development

No build step required.

```bash
git clone https://github.com/Arun4535/<repo-name>.git
cd <repo-name>
```

Open `index.html` directly in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Deployed on [Vercel](https://vercel.com) as a static site — pushes to `main` deploy automatically.

## Structure

```
.
├── index.html      # entire site — markup, styles, and scripts
└── README.md
```

## Contact

- **Email:** arunkhanchandani05@gmail.com
- **LinkedIn:** [linkedin.com/in/arun-4535](https://linkedin.com/in/arun-4535)
- **GitHub:** [github.com/Arun4535](https://github.com/Arun4535)
