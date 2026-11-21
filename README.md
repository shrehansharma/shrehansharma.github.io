# Personal Portfolio — Shrehan Sharma

A responsive, single-page portfolio site for a Computer Science student looking for an SDE / Web Developer internship. Built from scratch with HTML, CSS and vanilla JavaScript — no frameworks, no build step.

[Live demo: shrehansharma.github.io](https://shrehansharma.github.io/)

## Problem

A recruiter clicking your GitHub link needs to understand who you are in under a minute. This site puts the essentials — about, skills, projects, education and contact — in one clean, fast, mobile-friendly place.

## Features

- Responsive layout that works on phone, tablet and desktop
- Light / dark theme toggle, remembered across visits
- Animated hero with rotating role text
- Skills grouped into Languages, Web & Backend, Tools & Cloud and Fundamentals
- Projects section designed so new cards can be dropped in easily
- Education timeline and direct contact links (email, GitHub, LinkedIn)
- Scroll-reveal animations that respect `prefers-reduced-motion`
- Semantic HTML, accessible labels and keyboard-friendly controls

## Tech stack

HTML5 · CSS3 (custom properties, grid, flexbox) · Vanilla JavaScript (IntersectionObserver, localStorage)

## How to run

No installation needed — open `index.html` in a browser.

To serve it locally:

```bash
# Python 3
python3 -m http.server 8000
# then visit http://localhost:8000
```

To deploy for free: push this repo to GitHub, then go to **Settings → Pages → Deploy from a branch → main / root** and save. Your site will be live at `https://<username>.github.io/<repo-name>/`.

## Customising it

- **Text and links:** edit `index.html` (search for your name, email and social URLs).
- **Colours:** edit the CSS variables at the top of `styles.css`.
- **Add a project:** copy a `.project-card` block in the Projects section and replace the placeholders.
- **Deploy URL:** replace the `[Live demo](#)` link at the top of this README.

## What this project demonstrates

- Layout and styling with modern CSS without relying on a framework
- DOM interaction and state persistence with `localStorage`
- Accessible, semantic markup and mobile-first responsive design
- Deployment to a static host via GitHub Pages

## Future improvements

- Add real project cards with screenshots and live-demo links as projects ship
- Add a downloadable résumé
- Replace the terminal illustration with a live activity feed from the GitHub API

## License

MIT — see [LICENSE](LICENSE).
