# CLAUDE.md — bb-design-system (Body Balance Medical)

The deployable **brand design system** for **Body Balance Medical** — a premium medical wellness and aesthetics practice in Las Vegas, NV. Maintained by **Josh Smith · Captain Kepler Creative**.

This repo is **component #2 of the BB brand's three-component model**:

1. **Brand design markdown** (intelligence layer, agent-facing) — lives in the vault: `clients/body-balance/brand/BB-BRAND-DESIGN-SYSTEM.md`. The canonical visual spec + Josh's deploy methods.
2. **Brand design system HTML** (this repo) — the rendered, distributable system. Canonical file: **`BB-BRAND-TEAM.html`**. Clients drop this file into their own agents to self-brand.
3. **Brand pyramid** (voice/positioning) — lives in the vault: `clients/body-balance/brand/BB-BRAND-PYRAMID.md`.

For voice, vocabulary, and positioning, see component #3. For the full agent-facing spec + deploy methods, see component #1. This repo holds the distributable HTML and the production assets.

---

## What this repo contains

| File / Folder | Purpose |
|---|---|
| `BB-BRAND-TEAM.html` | **Canonical component #2** — the distributable rendered design system. The file clients drop into their agents. |
| `references/` | Supporting docs: `BBM-TEAM-WORKFLOW-GUIDE.html`, `How to Build with AI — Body Balance Medical.pdf`. |
| `_archive/` | Superseded sources — prior brand markdowns (`BB-BRAND-PRO.md`, `BB-BRAND-TEAM.md`), `BB-BRAND-PRO.html`, `BB-DESIGN-SYSTEM-SPEC-RENDER.html`, `BB-BRAND-TEAM-GR-PRIMARY.html`, `index.html`, and earlier versions. Do not reference in active sessions. |
| `.wrangler/` | Cloudflare Wrangler config for R2 asset deployment. |
| `.gitignore` | Repo ignore rules. |

---

## Assets

Production binaries (logos, textures, photography) are served from **Cloudflare R2**, client-scoped:

**R2 base:** `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/clients/body-balance`

Folders: `/logos/` (16 SVG variants), `/textures/` (plant SVGs + logo-mark webp), `/photography/` (~41 references + the two provider photos). The full asset index lives inside `BB-BRAND-TEAM.html`. Deploys are managed via Wrangler (`.wrangler/`).

`*.r2.dev` and `raw.githubusercontent.com` do not resolve in claude.ai chat; they resolve in Claude Code and browser-rendered outputs.

---

## How this system is built and maintained

- The canonical visual spec is the vault intelligence file (component #1). Design changes are approved by Josh, reflected in component #1, and rebuilt into `BB-BRAND-TEAM.html`.
- There is no separate design-system spec document — the old `BB-DESIGN-SYSTEM-SPEC.md` pipeline is retired (archived).
- The repo topology (this nested repo, its remote, and the R2 distribution model) is under review — see the public-distribution idea note in the vault `builds/ideas/`.

---

*Captain Kepler Creative · Josh Smith · 2026 · Confidential*
