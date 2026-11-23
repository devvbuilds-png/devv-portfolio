# devv-portfolio

**My personal portfolio as an AI product builder and aspiring APM, laid out as an interactive solar system.**

Live: https://devvbuilds-png.github.io/devv-portfolio/

## What it is / why I built it

I didn't want a resume-as-a-webpage. I wanted the site to show how I think about product experience, so I built it as a small 3D solar system. Each planet is a section of my portfolio, and you navigate by orbiting and selecting. It covers the work I'm proudest of, including Kaizen (the flagship of Seemara, my one-person AI products studio), client work, and side projects like SohailCab.

## Features

- Three.js solar-system navigation: planets for Home, Projects, Skills.md, Blog and Contact, with drag-to-orbit and planet selection
- Guide overlay that explains what each planet holds
- Projects section split into product work in the wild and personal builds, with live links
- Skills section framed around the AI-first PM path: agents, LLMs, product and building
- Contact routes (email, LinkedIn, GitHub, blog) and a link to my Bear Blog
- Background music toggle

## Tech stack

- A single static `index.html` with vanilla JS and CSS
- Three.js (r128, via CDN)
- Google Fonts: Space Grotesk, Inter, Fira Code, Press Start 2P
- Hosted on GitHub Pages

## Run locally

No build step is needed. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Project structure

```
index.html            the current portfolio (all markup, styles and scripts)
home.html             earlier version
First attempt.html    first version
*.png / *.jpg / *.mp3 images and audio used by the pages
```

## Status

Live and maintained. Recently repositioned for APM and AI-builder roles.
