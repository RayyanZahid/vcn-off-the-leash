# Vibe Coding Nights — vibecodingnights.com

The San Francisco builder community for people who code with AI agents.
Bring a laptop, build something real, leave with it working.

Static single-page site (`index.html`) plus a `lab/` of live ASCII simulations
(navier–stokes fluid, ant-colony, wind-tunnel, game-of-life, boids, sentinels)
embedded across the page. Built on the Controlled Chaos PRO engine (Brody persona).

## Structure
- `index.html` — the page
- `lab/*.html` — self-contained interactive experiments (embedded as iframes; each pauses off-screen)
- `posters/`, `hero.mp4`, `og.jpg`, `poster.jpg`, `feed.json` — assets + JSON feed

## Deploy
Static — deploys as-is on Vercel (no build step).

Facilitated by Rayyan Zahid (Immersive Commons), Michalis Vasileiadis (Hacker Bob), Eric Mockler.
