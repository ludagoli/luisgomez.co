# Escape Room Name Testing Sites

## Project Overview
Monorepo of static landing pages deployed on Vercel. Each subdirectory at the root represents a different escape room name idea with its own landing page.

## Structure
```
/              → index page with links to all name ideas
/{name}/       → individual landing page for that name
```

## Current Sites
- `/57rooms` — "57 Rooms" concept (dark/gold theme, door icon)
- `/bajollave` — "Bajo Llave" concept (blue/gold theme, key icon)

## Adding a New Name Idea
1. Create a new directory at root: `{newname}/index.html`
2. Follow the existing landing page style: dark background, centered content, serif font, gold accent color, "Proximamente" CTA
3. Add a link to the new site in `index.html`
4. Commit and push — Vercel auto-deploys

## Tech Stack
- Pure static HTML/CSS (no frameworks, no build step)
- Deployed on Vercel (auto-deploy from GitHub on push)
- Repo: github.com/ludagoli/luisgomez.co

## Conventions
- Each landing page is self-contained (inline CSS, no external dependencies)
- Color palette: dark backgrounds (#0a0a0a range), gold accents (#d4a44a range)
- Typography: Georgia serif, uppercase taglines with letter-spacing
- All text in Spanish
