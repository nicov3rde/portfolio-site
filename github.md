repo: nicov3rde/my-portfolio
branch: master

## Last sync
date: 2026-07-28T18:50:00Z

### Updated in this project
- Read existing Next.js portfolio (Hero, About, Projects, Nav, Footer, data/projects.ts, data/writing.ts) to ground a product-marketing-focused rebuild in the real brand: black/green/Bebas Neue+Inter, campaign data, bio facts.
- Copied reference assets (headshot, verde house flyer, logo, gallery photos) into this project for use in the rebuilt design.
- Built as static Design Components (.dc.html) — not wired back into the Next.js repo. Treat as a design pass for the user to hand to Claude Code / rebuild into the app.

## Screen map
| Screen | Source files |
|---|---|
| Portfolio.dc.html (homepage) | src/components/Hero.tsx, About.tsx, Projects.tsx, Nav.tsx, Footer.tsx, src/data/projects.ts, src/data/writing.ts, globals.css, tailwind.config.ts |
| Verde-House.dc.html | src/data/projects.ts (verde-house entry) |
| LinkedOut.dc.html | src/data/projects.ts (linkedout entry) |
| Underground-Journal.dc.html | src/data/projects.ts (underground-journal entry) |
