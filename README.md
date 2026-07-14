# Day Zero Blueprint — Landing Page

Static landing page for Adrienne Lloyd's Day Zero Blueprint (Optimize Healthcare).
No build step — pure HTML/CSS. Deploys as-is on Netlify.

## Structure
- `index.html` — the entire page (copy, styles, layout)
- `assets/` — all images

## Image slots awaiting upload (page falls back gracefully if absent)
| File | Where it appears |
|---|---|
| `assets/adrienne.jpg` | "Hi, I'm Adrienne" photo card |
| `assets/medical-team.jpg` | Hero background (gradient fade) |
| `assets/rrr.png` | RESET / REIMAGINE / RELAUNCH strip |
| `assets/AAO.png, aapc.png, MGMA.png, ASOA.png, IHI.png, ache.png` | "Featured By" trust bar |

Drop the files into `assets/` with these exact names and they render automatically.

## Editing
All copy lives in `index.html`, organized by `<!-- SECTION n -->` comments (0–13).
Every CTA links to the Calendly strategy-call URL with a per-section `utm_content` tag.

© Optimize Healthcare, LLC
