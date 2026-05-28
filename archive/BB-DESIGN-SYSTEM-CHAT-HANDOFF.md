# HANDOFF — Body Balance Medical Design System Build
**New Chat Session · Captain Kepler Creative · 2026-04-22**

---

## Context

This handoff comes from a long planning session covering:
- Brand board structure and what it needs to contain
- Claude Design workflow integration into Project Kepler Stage 1
- A consolidated 4-phase Stage 1 workflow (now locked in all V4.21 spec files)
- Multiple failed Claude Design sessions due to beta instability (413 errors, base64 corruption, token exhaustion from error recovery)

All Project Kepler V4.21 spec files have been updated to reflect the new Stage 1 workflow. That work is complete and committed to both repos.

---

## What This Session Produces

Two outputs:

**Output 1 — `BB-DESIGN-SYSTEM-SPEC.md`**
The complete technical design system specification for Body Balance Medical. Machine-readable. Agent-facing. Contains every value needed to build or replicate the BB brand in any tool.

**Output 2 — Claude Code prompt**
A handoff prompt Josh takes directly into Claude Code. Code uses the spec to build a `bb-design-system/` folder structure that Claude Design can read as a persistent design system at session start — so every future Claude Design session for BB inherits the system automatically without re-uploading anything.

---

## What Josh Is Bringing Into This Chat

Upload these at session open:

- Brand board screenshot(s) — compressed JPEG, max 1200px wide
- 1 photography reference image — best single example of BB visual style
- 1 website screenshot — showing font hierarchy in use
- Any hex values or font names already locked (paste as text if easier)

**All images must be JPEG — no HEIC, no PNG for photos.** Run through Automator Quick Action before uploading.

---

## What We Know About BB So Far

**Client:** Body Balance Medical — medspa in Las Vegas

**Stage 0 status:** Complete. 18 flagged gaps in Tally Summary, two COMPLIANCE tags, two compressed holiday deadlines. Josh has reviewed.

**Brand Pyramid:** Brainstorm complete. Brand Pyramid locked.

**Visual work done:**
- Brand board partially built in Illustrator
- Website updated with font sizes — screenshots available showing hierarchy in use
- Reference photos selected
- Reference ads selected

**Claude Design status:** Multiple sessions failed due to beta bugs (413 request too large, HEIC base64 corruption, context corruption at message 18+). Tokens near exhaustion from error recovery. Starting fresh after token reset.

---

## The Session Workflow

### Step 1 — Define the Design System (conversational)

Josh uploads images and describes what's locked. Claude extracts and defines:

1. **Color palette** — hex, RGB, color names, usage context per color
2. **Typography scale** — font families, sizes in px AND rem (16px base), weights, line-height (rem), letter-spacing (em), text-transform — for every level: Display, H1, H2, H3, Body Large, Body, Caption, Label
3. **Spacing scale** — REM-based, 0.25rem through 6rem, each mapped to usage
4. **Logo rules** — variants, clearspace (rem + px), minimum sizes, approved/prohibited backgrounds
5. **Photography brief** — generative AI prompt for Firefly/Claude Design, lighting, subjects, editing style, mood, anti-brief
6. **Component patterns** — buttons (primary/secondary/ghost), cards, badges, dividers, form inputs
7. **Do/Don't rules** — logo, color, typography, spacing, photography

Josh corrects anything that's wrong through conversation. Every value locked before moving to Step 2.

### Step 2 — Write BB-DESIGN-SYSTEM-SPEC.md

Once all values are confirmed, Claude writes the complete spec as a structured markdown file using this exact format:

```markdown
# BODY BALANCE MEDICAL — Design System Specification
**Captain Kepler Creative · Josh Smith · 2026**
**Version 1.0 — Stage 1 output**
**Load alongside BB-BRAND.md in any agent session requiring visual specs.**

---

## 1. COLOR PALETTE

### Primary Colors
| Name | Hex | RGB | Usage |
|---|---|---|---|
| [Name] | #[hex] | rgb([r],[g],[b]) | [usage] |

### Secondary / Accent Colors
[same table]

### Neutrals
[same table]

### Accessibility Notes
[contrast ratio notes for key text pairings]

---

## 2. TYPOGRAPHY SCALE

Base: 16px = 1rem

| Level | Font Family | Weight | Size (rem) | Size (px) | Line Height | Letter Spacing | Transform |
|---|---|---|---|---|---|---|---|
| Display | | | | | | | |
| H1 | | | | | | | |
| H2 | | | | | | | |
| H3 | | | | | | | |
| Body Large | | | | | | | |
| Body | | | | | | | |
| Caption | | | | | | | |
| Label | | | | | | | |

---

## 3. SPACING SCALE

Base: 16px = 1rem

| Token | rem | px | Usage |
|---|---|---|---|
| space-1 | 0.25rem | 4px | |
| space-2 | 0.5rem | 8px | |
| space-3 | 0.75rem | 12px | |
| space-4 | 1rem | 16px | |
| space-6 | 1.5rem | 24px | |
| space-8 | 2rem | 32px | |
| space-12 | 3rem | 48px | |
| space-16 | 4rem | 64px | |
| space-20 | 5rem | 80px | |
| space-24 | 6rem | 96px | |

---

## 4. LOGO RULES

### Variants
[list each variant]

### Clearspace
- Minimum: [value] rem ([value] px) on all sides
- Minimum width (full logo): [value] px

### Approved Backgrounds
[list]

### Prohibited Backgrounds
[list]

### Color Variants
[list]

---

## 5. PHOTOGRAPHY BRIEF

**Generative AI prompt:**
[full prompt]

**Lighting:** [description]
**Subjects:** [description]
**Editing style:** [description]
**Mood:** [description]
**Composition:** [description]

**Anti-Brief (never generate):**
- [rule 1]
- [rule 2]
- [rule 3]

---

## 6. COMPONENT PATTERNS

### Buttons
- Primary: [bg, text color, font spec, padding, border-radius]
- Secondary: [same]
- Ghost: [same]

### Cards
- Background, border, shadow, corner radius, internal padding

### Badges / Tags
- Background, text, padding, border-radius

### Dividers
- Color, weight, style

### Form Inputs
- Border, focus state, label position, placeholder

---

## 7. DO / DON'T RULES

### Logo
DO: / DON'T:

### Color
DO: / DON'T:

### Typography
DO: / DON'T:

### Spacing
DO: / DON'T:

### Photography
DO: / DON'T:

---

## 8. VERSION LOG

| Version | Date | Changed By | Notes |
|---|---|---|---|
| 1.0 | [date] | Josh Smith | Initial spec — Stage 1 |

---

*Captain Kepler Creative · Body Balance Medical · 2026 · Confidential*
*BB-DESIGN-SYSTEM-SPEC.md — Load alongside BB-BRAND.md*
```

### Step 3 — Write the Claude Code Prompt

After the spec is locked and written, Claude writes a handoff prompt for Claude Code. The prompt instructs Code to:

1. Create `~/Captain-Kepler/client-working-files/body-balance/bb-design-system/` folder
2. Write `DESIGN-SYSTEM-SPEC.md` from the locked spec
3. Write `tokens.css` — all design tokens as CSS custom properties (`--bb-primary`, `--bb-type-display-size`, etc.)
4. Write `CLAUDE.md` — tells Claude Design what this folder is and how to use it
5. Commit to the Captain-Kepler repo with message: `"BB: Design system folder — Claude Design persistent context"`

---

## The Claude Code Prompt Template

Claude writes this at the end of the session, fully populated with BB values:

```
# CLAUDE CODE HANDOFF — BB Design System Folder Build
**Captain Kepler Creative · Body Balance Medical · 2026**

## Task
Create the Body Balance Medical persistent design system folder for Claude Design.

## Working directory
~/Captain-Kepler/client-working-files/body-balance/

## Create this folder structure
bb-design-system/
  CLAUDE.md
  DESIGN-SYSTEM-SPEC.md
  tokens.css

---

## File 1 — CLAUDE.md

Write this file exactly:

# Body Balance Medical — Design System
This folder contains the persistent design system for Body Balance Medical.
Load this folder at the start of every Claude Design session for BB.
The design system defined here governs every artifact produced for this client.

**Primary files:**
- DESIGN-SYSTEM-SPEC.md — full technical specification (human-readable)
- tokens.css — all design tokens as CSS custom properties (machine-readable)

**How to use:**
At Claude Design session start, read both files. Apply all tokens and specs
to every artifact generated in this session. Do not override these values
without explicit instruction from Josh.

---

## File 2 — DESIGN-SYSTEM-SPEC.md

Write this file exactly:

[PASTE FULL BB-DESIGN-SYSTEM-SPEC.md CONTENT HERE]

---

## File 3 — tokens.css

Write this file exactly:

:root {
  /* COLORS */
  --bb-color-primary: [hex];
  --bb-color-primary-rgb: [r, g, b];
  --bb-color-secondary: [hex];
  --bb-color-accent: [hex];
  --bb-color-neutral-dark: [hex];
  --bb-color-neutral-mid: [hex];
  --bb-color-neutral-light: [hex];
  --bb-color-white: [hex];

  /* TYPOGRAPHY — FAMILIES */
  --bb-font-display: '[font name]', [fallback stack];
  --bb-font-body: '[font name]', [fallback stack];

  /* TYPOGRAPHY — SCALE */
  --bb-type-display-size: [rem];
  --bb-type-display-weight: [weight];
  --bb-type-display-line-height: [rem];
  --bb-type-display-letter-spacing: [em];

  --bb-type-h1-size: [rem];
  --bb-type-h1-weight: [weight];
  --bb-type-h1-line-height: [rem];
  --bb-type-h1-letter-spacing: [em];

  --bb-type-h2-size: [rem];
  --bb-type-h2-weight: [weight];
  --bb-type-h2-line-height: [rem];
  --bb-type-h2-letter-spacing: [em];

  --bb-type-h3-size: [rem];
  --bb-type-h3-weight: [weight];
  --bb-type-h3-line-height: [rem];
  --bb-type-h3-letter-spacing: [em];

  --bb-type-body-large-size: [rem];
  --bb-type-body-large-weight: [weight];
  --bb-type-body-large-line-height: [rem];

  --bb-type-body-size: [rem];
  --bb-type-body-weight: [weight];
  --bb-type-body-line-height: [rem];

  --bb-type-caption-size: [rem];
  --bb-type-caption-weight: [weight];
  --bb-type-caption-line-height: [rem];

  --bb-type-label-size: [rem];
  --bb-type-label-weight: [weight];
  --bb-type-label-letter-spacing: [em];
  --bb-type-label-transform: [uppercase/none];

  /* SPACING */
  --bb-space-1: 0.25rem;
  --bb-space-2: 0.5rem;
  --bb-space-3: 0.75rem;
  --bb-space-4: 1rem;
  --bb-space-6: 1.5rem;
  --bb-space-8: 2rem;
  --bb-space-12: 3rem;
  --bb-space-16: 4rem;
  --bb-space-20: 5rem;
  --bb-space-24: 6rem;

  /* COMPONENTS */
  --bb-radius-sm: [rem];
  --bb-radius-md: [rem];
  --bb-radius-lg: [rem];
  --bb-radius-full: 9999px;

  --bb-shadow-sm: [value];
  --bb-shadow-md: [value];
  --bb-shadow-lg: [value];

  --bb-border-color: [hex];
  --bb-border-width: [px];
}

---

## Git

After all three files are written:

git add client-working-files/body-balance/bb-design-system/
git commit -m "BB: Design system folder — Claude Design persistent context v1.0"
git push
```

---

## How to Use the Design System Folder in Claude Design

When Claude Design tokens reset and you open a new session:

1. At session start, tell Claude Design: "Read the files in `~/Captain-Kepler/client-working-files/body-balance/bb-design-system/` — this is the BB design system. Apply it to everything you build in this session."
2. Claude Design reads CLAUDE.md + DESIGN-SYSTEM-SPEC.md + tokens.css
3. Every artifact it generates from that point inherits the system automatically
4. No re-uploading images. No re-defining colors. No re-specifying fonts.

This is the persistent context layer that makes Claude Design reliable for BB going forward.

---

## Vault Commit (after Code session)

Also copy `BB-DESIGN-SYSTEM-SPEC.md` to vault:

```
~/Obsidian/Captain-Kepler/clients/body-balance/brand/BB-DESIGN-SYSTEM-SPEC.md
```

Commit with: `"BB Stage 1: Design system spec — locked v1.0"`

---

## What Comes After This

Once the design system folder is built and committed:

1. Wait for Claude Design token reset
2. Open new Claude Design session → point at `bb-design-system/` folder
3. Generate `BB-BRAND-PITCH.pdf` — the client-facing brand pitch deck
4. Generate `BB-BRAND.md` — in client Claude Project chat, using DESIGN-SYSTEM-SPEC.md + Brand Pyramid as inputs
5. Load `BB-BRAND.md` into Body Balance Medical Claude Project as permanent knowledge
6. Stage 1 complete → proceed to Stage 2 Campaign Brief

---

*Captain Kepler Creative · Josh Smith · 2026 · Confidential*
*Handoff: BB Design System Build Session · 2026-04-22*
