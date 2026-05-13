# CLAUDE.md — bbm-design-system

This repository is the design system for **Body Balance Medical**, a premium medical wellness and aesthetics practice in Las Vegas, NV.

It is maintained by **Josh Smith · Captain Kepler Creative**.

---

## What This Repo Contains

| File / Folder | Purpose |
|---|---|
| `BRAND.md` | **Start here.** Complete agent-ready brand operating system — colors, typography, voice, assets, behavior rules. |
| `BB-DESIGN-SYSTEM-SPEC.md` | Full technical design system spec. Archival — build input for `BRAND.md`. |
| `tokens.css` | All CSS custom properties. Import into any web or HTML project. |
| `/logos/` | 16 SVG logo variants — horizontal, vertical, mark, social formats in B/W/G/Bu. |
| `/textures/` | 7 texture SVGs + logo mark WebP. |
| `/photography/` | 6 reference photography JPEGs — brand photography style reference only. |
| `/references/` | `BB-DESIGN-SYSTEM-SPEC-RENDER.html` — visual design system reference document. |

---

## How to Use This Repo

**For any agent session involving BBM brand work:**
Read `BRAND.md` first. It contains everything needed to produce fully on-brand work — colors, typography, component rules, voice, logo usage, and direct asset URLs.

**For web or HTML projects:**
Import `tokens.css` for all CSS custom properties. Import Google Fonts per the comment block at the bottom of `tokens.css`.

**For logo usage:**
All 16 logo variants are in `/logos/`. See `BRAND.md` Section 1.11 for the full context guide — which variant to use on which background.

---

## Asset Delivery

Assets are served publicly via Cloudflare R2 for use in any agent environment:

**R2 Base URL:** `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev`

Example URLs:
- `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-H-Logo-W.svg`
- `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-03.svg`

All R2 URLs are listed in `BRAND.md` Section 3.

GitHub raw URLs (`raw.githubusercontent.com`) are blocked in some agent environments — use R2 URLs in `BRAND.md` for maximum compatibility.

---

## Update Protocol

1. Design changes are approved by Josh
2. Updated values go into `BB-DESIGN-SYSTEM-SPEC.md` first
3. `BRAND.md` and `tokens.css` are rebuilt from the updated spec
4. Updated files are pushed to this repo and re-uploaded to R2 if assets changed
5. `BRAND.md` is reloaded into any Claude Projects that use it as permanent knowledge

**One source of truth: `BRAND.md`.** Once built, the team only ever references `BRAND.md` — not the spec directly.

---

*Captain Kepler Creative · Josh Smith · 2026 · Confidential*
