# Portfolio — Abhayrajsinh Parmar

Personal portfolio for **Abhayrajsinh Parmar**, AI/ML Engineer building production LLM and Generative-AI systems — RAG, agents, and document pipelines on Python and FastAPI.

🔗 **Live site:** [portfolio-two-xi-62.vercel.app](https://portfolio-two-xi-62.vercel.app/)

---

## About

A single-page portfolio showcasing experience, skills, education, and selected projects. Built from scratch as a hand-written, self-contained HTML page — no frameworks, no build step, no dependencies.

The site highlights work on production AI systems including:
- Hybrid RAG pipelines (dense + sparse retrieval on Qdrant)
- Tool-using LLM agents via Model Context Protocol (MCP)
- Self-hosted open-weight LLMs served with vLLM
- Document ingestion pipelines at scale (175K+ documents processed)

---

## Tech Stack

- **HTML5** — semantic markup, structured data (JSON-LD)
- **CSS3** — custom properties, grid, flexbox, responsive design, scroll-reveal, reduced-motion support
- **Vanilla JavaScript** — typewriter effect, IntersectionObserver for scroll reveal and active-section nav, clipboard API
- **Google Fonts** — Space Grotesk + Inter
- **Hosting** — Vercel (auto-deploys from `main`)

No build tools. Zero npm dependencies. Open `index.html` and it works.

---

## Project Structure

```
Portfolio/
├── index.html      # Full site — markup, styles, scripts
├── profile.jpeg    # Profile photo
├── resume.pdf      # Resume (downloadable from the site)
└── README.md       # This file
```

---

## Features

- Fully responsive — mobile, tablet, desktop
- Dark theme with gradient accents
- Animated typewriter effect for job roles
- Scroll-based section reveals (IntersectionObserver)
- Active-section highlighting in the nav
- Sticky "At a glance" sidebar on desktop
- Copy-to-clipboard email with toast notification
- Back-to-top button
- SEO optimized — OpenGraph, Twitter cards, JSON-LD Person schema
- Accessibility — focus-visible outlines, `prefers-reduced-motion` support, semantic HTML
- Lightweight — single HTML file, ~30KB

---

## Running Locally

Clone the repo and open the file:

```bash
git clone https://github.com/abhiparmar1111/Portfolio.git
cd Portfolio
```

Then open `index.html` in your browser, or serve it with any static server:

```bash
# Python 3
python -m http.server 8000

# Node.js (if you have http-server installed)
npx http-server
```

Visit `http://localhost:8000` in your browser.

---

## Deployment

The site is deployed on **Vercel** and auto-rebuilds on every push to `main`. To deploy your own fork:

1. Push the repo to your GitHub account
2. Import it into [Vercel](https://vercel.com/new)
3. Accept defaults (no build command, no output directory — it's static HTML)
4. Done

---

## Contact

- **Email:** [abhayparmar583@gmail.com](mailto:abhayparmar583@gmail.com)
- **LinkedIn:** [linkedin.com/in/abhayraj-parmar-266074253](https://www.linkedin.com/in/abhayraj-parmar-266074253/)
- **GitHub:** [github.com/abhiparmar1111](https://github.com/abhiparmar1111/)

Open to **AI/ML and AI Engineer roles**. 🇺🇸 U.S. Permanent Resident — no sponsorship required.

---

© 2026 Abhayrajsinh Parmar