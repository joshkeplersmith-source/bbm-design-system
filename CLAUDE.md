# CLAUDE.md — bbm-design-system

This repository is the design system for **Body Balance Medical**, a premium medical wellness and aesthetics practice in Las Vegas, NV.

It is maintained by **Josh Smith · Captain Kepler Creative**.

---

## What This Repo Contains

| File / Folder | Purpose |
|---|---|
| `references/BB-BRAND-PRO.md` | **Josh's file.** Full brand operating system — includes Illustrator MCP tool access, full asset pipeline, and production workflows. |
| `references/BB-BRAND-TEAM.md` | **Team file (Will, Dez, social media manager).** Self-serve, web-first workflow — no local tool dependencies. |
| `tokens.css` | All CSS custom properties. Import into any web or HTML project. |
| `/logos/` | 16 SVG logo variants — horizontal, vertical, mark, social formats in B/W/G/Bu. |
| `/textures/` | 7 texture SVGs + logo mark WebP. |
| `/photography/` | 6 reference photography JPEGs — brand photography style reference only. |
| `/references/` | `BB-DESIGN-SYSTEM-SPEC-RENDER.html` — visual design system reference document. |
| `/archive/` | Previous brand file versions including `BB-BRAND-v1.1-ARCHIVED.md` and `BB-DESIGN-SYSTEM-SPEC.md`. Do not reference in active sessions. |

---

## How to Use This Repo

**Brand system is now split into two files:**

> `references/BB-BRAND-PRO.md` is for Josh — full tool access including Illustrator MCP and the complete production pipeline. `references/BB-BRAND-TEAM.md` is for Will, Dez, and the social media manager — self-serve, web-first workflow with no local tool dependencies. The original `BRAND.md` v1.1 is archived in `/archive/`.

**For any agent session involving BBM brand work (Josh):**
Read `references/BB-BRAND-PRO.md` first.

**For any agent session involving BBM brand work (team):**
Read `references/BB-BRAND-TEAM.md` first.

**For web or HTML projects:**
Import `tokens.css` for all CSS custom properties. Import Google Fonts per the comment block at the bottom of `tokens.css`.

**For logo usage:**
All 16 logo variants are in `/logos/`. See `references/BB-BRAND-PRO.md` or `references/BB-BRAND-TEAM.md` Section 1.11 for the full context guide — which variant to use on which background.

---

## Asset Delivery

Assets are served publicly via Cloudflare R2 for use in any agent environment:

**R2 Base URL:** `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev`

Example URLs:
- `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-H-Logo-W.svg`
- `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-03.svg`

All R2 URLs are listed in `references/BB-BRAND-PRO.md` and `references/BB-BRAND-TEAM.md` Section 3.

GitHub raw URLs (`raw.githubusercontent.com`) are blocked in some agent environments — use R2 URLs in `references/BB-BRAND-PRO.md` or `references/BB-BRAND-TEAM.md` for maximum compatibility.

---

## Update Protocol

1. Design changes are approved by Josh
2. Updated values go into `BB-DESIGN-SYSTEM-SPEC.md` first
3. `references/BB-BRAND-PRO.md`, `references/BB-BRAND-TEAM.md`, and `tokens.css` are rebuilt from the updated spec
4. Updated files are pushed to this repo and re-uploaded to R2 if assets changed
5. Brand files are reloaded into any Claude Projects that use them as permanent knowledge

**One source of truth per audience.** `references/BB-BRAND-PRO.md` for Josh. `references/BB-BRAND-TEAM.md` for the team. Neither references the spec directly — the spec is the build input, not the working document.

---

*Captain Kepler Creative · Josh Smith · 2026 · Confidential*
