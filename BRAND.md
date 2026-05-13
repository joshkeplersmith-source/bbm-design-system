# BODY BALANCE MEDICAL — Brand Operating System
**Captain Kepler Creative · Josh Smith · 2026**
**File:** `BB-BRAND.md` · Version 1.0
**Status:** Active — Single source of truth

---

## HOW TO USE THIS FILE

This file is the complete brand operating system for Body Balance Medical. Drop it into any agent session — at the start, middle, or end of a conversation — and the agent will have everything it needs to produce fully on-brand work.

**When you receive this file, read it fully before doing anything else.** Then confirm:
> "Body Balance Medical brand system active. Ready to build."

This file contains:
- The complete visual design system (colors, typography, spacing, components)
- Brand voice, positioning, and messaging rules
- A full asset library with direct file URLs
- Output type guidance per environment
- Graceful degradation rules for restricted environments
- Image generation style instructions and prompt templates
- Agent behavior rules

**You do not need any other file.** Do not ask for additional brand documents. Everything is here.

---

## SECTION 1 — BRAND IDENTITY

### 1.1 — Color Palette

**Base rule:** Hero stop is 700 across all six families. Never use pure `#000000` or `#ffffff` — always use N-900 and N-100.

---

#### P — Primary · Slate Blue · Dominant brand color

| Stop | Hex | Usage |
|---|---|---|
| P-900 | `#030507` | Deepest dark — nav, footer backgrounds |
| P-800 | `#131c25` | Gradient dark stop — resting state |
| **P-700 ★** | `#2b3a4a` | Hero stop — section backgrounds, gradient selected state |
| P-600 | `#3e536a` | Tile hover / selected on P-700 background |
| P-500 | `#506d8b` | Eyebrow text on light · subheading accent |
| P-400 | `#6a89a9` | Gradient light stop resting · meta labels on dark |
| P-300 | `#91a7bf` | Gradient lighter stop selected |
| P-200 | `#b1c4d7` | Light fills on dark surfaces |
| P-100 | `#d0dbe7` | Lightest tint — background accents |

#### S — Secondary · Rose / Mauve · Female-forward treatments

| Stop | Hex | Usage |
|---|---|---|
| S-900 | `#260d19` | Deepest dark rose |
| S-800 | `#49182f` | Female gradient dark stop — resting |
| **S-700 ★** | `#722c4d` | Hero — female gradient selected stop |
| S-600 | `#973a66` | Mid-rose |
| S-500 | `#b94b7f` | Female accent on light backgrounds (L3) |
| S-400 | `#c9739c` | Supporting rose |
| S-300 | `#da9fbb` | Female card title on dark gradient tiles |
| S-200 | `#ecc5d8` | Light rose fill |
| S-100 | `#f7e8ef` | Lightest rose tint |

#### T — Tertiary · Olive / Sage · Male-forward treatments

| Stop | Hex | Usage |
|---|---|---|
| T-900 | `#232210` | Deepest dark olive |
| T-800 | `#42411f` | Deep olive |
| **T-700 ★** | `#676637` | Hero — male accent on light backgrounds (L4) |
| T-600 | `#888749` | Male gradient dark stop — resting |
| T-500 | `#a8a65c` | Male gradient light stop — selected |
| T-400 | `#bcba81` | Supporting sage |
| T-300 | `#d1d0a8` | Male card title on dark gradient tiles |
| T-200 | `#e7e6cb` | Light olive fill |
| T-100 | `#f5f5ea` | Lightest sage tint |

#### Q — Quaternary · Gold / Amber · Primary accent

**Key rule: Q-300 on dark backgrounds. Q-700 on light backgrounds. Non-interchangeable.**

| Stop | Hex | Usage |
|---|---|---|
| Q-900 | `#2d2006` | Deepest dark gold |
| Q-800 | `#553c0c` | Deep amber |
| **Q-700 ★** | `#866118` | Accent heading on light (L1) · card title on NV tiles |
| Q-600 | `#b18020` | Mid gold |
| Q-500 | `#d99e2b` | Caption on dark (D6) · eyebrow mid-gold |
| Q-400 | `#e2b45b` | Supporting gold |
| **Q-300 ★** | `#ebcc8e` | Primary accent on dark (D1) · card title on gradient/P-700 tiles |
| Q-200 | `#f6e2bc` | Light gold fill |
| Q-100 | `#fbf3e4` | Lightest gold tint |

#### N — Neutral · Warm Greige · Brand Black N-900 · Brand White N-100

| Stop | Hex | Usage |
|---|---|---|
| **N-900** | `#1c1a17` | Brand near-black — body text on light, icon fills |
| N-800 | `#35302c` | Deep warm gray |
| N-700 | `#554f4a` | Dark warm gray |
| N-600 | `#706961` | Secondary body text on light |
| N-500 | `#8b8279` | Muted mid-tone |
| N-400 | `#a59e97` | Supporting neutral |
| N-300 | `#c1bdb8` | Subheading / supporting text on dark (D5) |
| N-200 | `#dcd9d5` | Borders, dividers, horizontal rules on light |
| **N-100 ★** | `#f1f0ee` | Page background · body text on dark · brand near-white |

#### NV — Neutral Variant · Warm Tan · Layout, hierarchy, design support

| Stop | Hex | Usage |
|---|---|---|
| NV-900 | `#1d1c16` | Deepest warm tan |
| NV-800 | `#383529` | Deep tan |
| NV-700 | `#595546` | Section dividers · callout lines · underlines |
| NV-600 | `#75715c` | Supporting tan |
| NV-500 | `#918c73` | Secondary rules · callout lines |
| NV-400 | `#aaa692` | Supporting |
| NV-300 | `#c5c2b5` | Neutral tile background resting on N-100 |
| **NV-200 ★** | `#deddd3` | Texture SVG fill color · NV tile hover state |
| NV-100 | `#f2f1ed` | Spec boxes · code blocks · secondary surfaces |

---

### 1.2 — Color Pairings

Every text element has a designated pairing code. Reference by code — never describe the color manually.

#### Dark System · P-700 Background

| Code | Background | Text | Hex | Usage |
|---|---|---|---|---|
| D1 | P-700 `#2b3a4a` | Q-300 | `#ebcc8e` | Heading italic accent — primary brand heading |
| D2 | P-700 `#2b3a4a` | S-300 | `#da9fbb` | Female-forward heading on dark |
| D3 | P-700 `#2b3a4a` | T-300 | `#d1d0a8` | Male-forward heading on dark |
| D4 | P-700 `#2b3a4a` | N-100 | `#f1f0ee` | Utility heading and body text on dark |
| D5 | P-700 `#2b3a4a` | N-300 | `#c1bdb8` | Subheading and supporting text on dark |
| D6 | P-700 `#2b3a4a` | Q-500 | `#d99e2b` | Caption register on dark |

#### Light System · N-100 Background

| Code | Background | Text | Hex | Usage |
|---|---|---|---|---|
| L1 | N-100 `#f1f0ee` | Q-700 | `#866118` | Accent heading on light |
| L2 | N-100 `#f1f0ee` | P-700 | `#2b3a4a` | Primary heading on light |
| L3 | N-100 `#f1f0ee` | S-500 | `#b94b7f` | Female accent on light |
| L4 | N-100 `#f1f0ee` | T-700 | `#676637` | Male-forward accent on light |
| L5 | N-100 `#f1f0ee` | P-500 | `#506d8b` | Subheading and caption on light |
| L6 | N-100 `#f1f0ee` | N-900 | `#1c1a17` | Body text on light |

---

### 1.3 — Gradient System

Three gradients. Two states each. Resting = darker stop pair. Selected/hover = lighter stop pair. All gradients run at 135°.

| Gradient | Resting | Selected / Hover | Card Title Color |
|---|---|---|---|
| Neutral | `linear-gradient(135deg, #131c25, #6a89a9)` | `linear-gradient(135deg, #2b3a4a, #91a7bf)` | Q-300 `#ebcc8e` |
| Female | `linear-gradient(135deg, #131c25, #49182f)` | `linear-gradient(135deg, #2b3a4a, #722c4d)` | S-300 `#da9fbb` |
| Male | `linear-gradient(135deg, #131c25, #888749)` | `linear-gradient(135deg, #2b3a4a, #a8a65c)` | T-300 `#d1d0a8` |

**Tile body text on all gradients:** N-100 `#f1f0ee` · Work Sans 300

---

### 1.4 — Tile System

All tiles receive `shadow-md`. Hover state transitions to selected gradient.

#### Dark Context · P-700 Background
Gradient tiles only. No solid P-700 tile in dark context. The section itself sits on a P-700 background — gradient tiles float above it.

| Tile | Resting | Selected | Title Color | Body Color |
|---|---|---|---|---|
| Neutral Gradient | P-800→P-400 | P-700→P-300 | Q-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Female Gradient | P-800→S-800 | P-700→S-700 | S-300 `#da9fbb` | N-100 `#f1f0ee` |
| Male Gradient | P-800→T-600 | P-700→T-500 | T-300 `#d1d0a8` | N-100 `#f1f0ee` |

#### Light Context · N-100 Background
5 tile types available.

| Tile | Resting | Selected | Title Color | Body Color |
|---|---|---|---|---|
| NV-300 Neutral | `#c5c2b5` | `#deddd3` NV-200 | Q-700 `#866118` | N-900 `#1c1a17` |
| Solid P-700 | `#2b3a4a` | `#3e536a` P-600 | Q-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Neutral Gradient | P-800→P-400 | P-700→P-300 | Q-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Female Gradient | P-800→S-800 | P-700→S-700 | S-300 `#da9fbb` | N-100 `#f1f0ee` |
| Male Gradient | P-800→T-600 | P-700→T-500 | T-300 `#d1d0a8` | N-100 `#f1f0ee` |

**Tile title font:** EB Garamond 400 · 2.25rem / 36px
**Tile body font:** Work Sans 300 · 1.125rem / 18px

---

### 1.5 — Typography System

Three font families. Each has a strictly defined role. Do not swap them.

| Family | Role | Google Fonts Import |
|---|---|---|
| EB Garamond | Headings and card titles only | `https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;1,400&display=swap` |
| Playfair Display | Everything non-heading, non-body — subheadings, eyebrows, captions, labels, UI elements, buttons, ghosted background text | `https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;1,400&display=swap` |
| Work Sans | Body copy only | `https://fonts.googleapis.com/css2?family=Work+Sans:wght@300;600&display=swap` |

#### Type Scale

| Level | Size | Family | Weight | Style | Usage |
|---|---|---|---|---|---|
| Hero | 4rem / 64px | EB Garamond | 400 | Upright + italic mix | Page hero headlines |
| Heading | 3.25rem / 52px | EB Garamond | 400 | Upright + italic mix | Section headings |
| Subhead | 2.25rem / 36px | Playfair Display | 400 | Italic | Section subheadings |
| Card Title | 2.25rem / 36px | EB Garamond | 400 | Upright | Tile and card titles |
| Body LG | 1.5rem / 24px | Work Sans | 300 | Normal | Intro body, lead paragraphs |
| Button | 1.5rem / 24px | Playfair Display | 400 | Normal | Button labels |
| Body | 1.125rem / 18px | Work Sans | 300 | Normal | Standard body copy |
| Caption | 0.875rem / 14px | Playfair Display | 400 | Italic | Captions, disclaimers, legal |
| Eyebrow | 0.56rem / ~9px | Playfair Display | 400 | Uppercase | Section labels, eyebrow tags |

**Eyebrow letter-spacing:** 0.32em

**The brand's core typographic move:** Pair EB Garamond upright with EB Garamond italic within the same heading. Example: *"Feel Like* Yourself Again" — italic on the emotional phrase, upright on the grounding phrase.

**Ghosted background text:** Large Playfair Display text rendered at low opacity (8–12%) behind a section's content. N-100 sections only. Use sparingly — once per page maximum.

#### Typography Rules

**DO:**
- Pair EB Garamond upright with EB Garamond italic in headings
- Use Playfair Display for all subheadings, captions, button labels, UI labels, eyebrows, and ghosted background text
- Use Work Sans 300 for all body copy
- Use Work Sans 600 for bold emphasis within body copy — sparingly

**DON'T:**
- Use EB Garamond for body copy, ghosted backgrounds, or anything outside headings and card titles
- Use Work Sans for headings, subheadings, eyebrows, or UI labels
- Use uppercase on EB Garamond
- Mix heading fonts on a single surface
- Use bold as a subheading substitute — use Playfair Display at the correct heading level instead

---

### 1.6 — Spacing Scale

| Token | Value |
|---|---|
| space-1 | 0.25rem / 4px |
| space-2 | 0.5rem / 8px |
| space-3 | 0.75rem / 12px |
| space-4 | 1rem / 16px |
| space-6 | 1.5rem / 24px |
| space-8 | 2rem / 32px |
| space-12 | 3rem / 48px |
| space-16 | 4rem / 64px |
| space-18 | 4.5rem / 72px |
| space-20 | 5rem / 80px |
| space-24 | 6rem / 96px |

---

### 1.7 — Grid System

| Property | Value |
|---|---|
| Columns | 12 |
| Max width | 1280px |
| Gutter (desktop) | 24px |
| Gutter (mobile) | 16px |
| Margin (desktop) | 80px |
| Margin (mobile) | 16px |

---

### 1.8 — Shadow System

All shadows use N-900 `#1c1a17` at warm opacity — never cold gray shadows.

| Token | Value |
|---|---|
| shadow-sm | `0 2px 8px rgba(28,26,23,.06), 0 1px 2px rgba(28,26,23,.04)` |
| shadow-md | `0 4px 16px rgba(28,26,23,.10), 0 2px 4px rgba(28,26,23,.06)` |
| shadow-lg | `0 8px 32px rgba(28,26,23,.14), 0 4px 8px rgba(28,26,23,.08)` |

---

### 1.9 — Button System

Single primary button style. No secondary outlined variant — the gradient button is the system's only button.

| Property | Value |
|---|---|
| Background resting | `linear-gradient(120deg, #131c25, #6a89a9)` |
| Background hover | `linear-gradient(120deg, #2b3a4a, #91a7bf)` |
| Text color | N-100 `#f1f0ee` |
| Font | Playfair Display 400 · 1.5rem |
| Border radius | 8px |
| Shadow | shadow-md |

---

### 1.10 — Texture System

7 texture SVGs available. Textures are layout enhancements — they add depth and tactility to N-100 sections.

**Texture fill color:** NV-200 `#deddd3`
**Opacity range:** 26–40% (adjust per texture based on visual weight at review)
**Rotation:** 90° — textures rotate to fill their container
**Behavior:** Fill container. `preserveAspectRatio="xMidYMid slice"`. `inset:0; width:100%; height:100%`

**Rules:**
- Textures on N-100 sections only — never on P-700 backgrounds
- One texture per section maximum
- Never apply a texture to two adjacent sections
- Never apply color inversion or blend modes — opacity only
- Never stack a texture and the logo mark watermark in the same section

#### Logo Mark Watermark (separate from textures)

**File:** `BB-Logo-Mark-Texture.webp`
**Usage:** Large centered watermark behind section content. Large sections only (full viewport height minimum).
**Behavior:** `object-fit: cover; inset: 0; width: 100%; height: 100%`
**Opacity:** 100% (WebP transparency handles visual weight)
**Blend mode:** None — do not apply any blend mode
**Frequency:** Once per page maximum
**Context:** N-100 sections only

---

### 1.11 — Logo System

**16 logo variants.** Every variant serves a specific background and context.

#### Logo Families

| Family | Description | Variants |
|---|---|---|
| H (Horizontal) | Wordmark + mark side by side | B, Bu, G, W |
| V (Vertical) | Wordmark + mark stacked | B, Bu, G, W |
| Mark (Icon) | Mark only, no wordmark | B, Bu, G, W |
| Social Logo | Horizontal format, optimized for social platforms | B, W |
| Social Mark | Mark only, optimized for social platforms | B, W |

#### Color Variant Key

| Suffix | Color | Use On |
|---|---|---|
| B | Black — N-900 `#1c1a17` | Light backgrounds (N-100, NV tiles) |
| W | White — N-100 `#f1f0ee` | Dark backgrounds (P-700, gradients) |
| G | Gold — Q-700 `#866118` on light / Q-300 `#ebcc8e` on dark | Accent contexts only |
| Bu | Blue — P-700 `#2b3a4a` | Light backgrounds, brand-forward contexts |

#### Context Guide

| Background | Recommended Logo |
|---|---|
| N-100 (light page) | H or V · B variant |
| P-700 (dark section) | H or V · W variant |
| Gradient tile | Mark · W variant |
| Social profile image | Social Mark · B or W depending on platform background |
| Social post / story | Social Logo · B or W depending on treatment |
| Gold accent moment | H or V · G variant — use intentionally, not decoratively |
| Brand-blue moment | H or V · Bu variant |

#### Logo Rules

**DO:**
- Always match the logo color variant to its background context (see table above)
- Maintain clearspace equal to the height of the "B" letterform on all sides
- Use H (horizontal) as the default. Use V (vertical) when the layout requires a taller, narrower format. Use Mark when the logo must be very small or icon-sized.

**DON'T:**
- Place any logo on a mid-tone background without verifying contrast
- Apply color, shadow, stroke, outline, or any effect not in the approved variants
- Scale the wordmark below approximately 11px cap height
- Crop, rotate, skew, or distort any logo in any direction
- Place any logo on a busy photographic background without a contrast treatment (dark overlay or light field)
- Recolor any variant — use the approved variant for that context, never alter the file

---

### 1.12 — Photography Brief

#### Primary Mode — Black & White

Black and white is the brand's most distinctive visual move. It signals editorial credibility, reduces distraction, and makes the subjects feel timeless rather than trend-driven.

**Characteristics:**
- Film-forward — not clinical digital black and white
- Rich midtones, soft contrast — not crushed blacks or blown whites
- Authentic grain acceptable — airbrushing and skin-smoothing are not
- Subjects feel present and real — not posed or performative

#### Secondary Mode — Kodak Portra 400

Used for warmth, human moments, and seasonal or campaign-specific content.

**Characteristics:**
- Warm, slightly faded color — not saturated or bright
- Natural grain, soft highlights
- Film emulation — not Instagram filter
- Color palette stays within the brand's warm earth tones — nothing electric or saturated

#### Subject Direction

**Women (primary):**
- 30s–40s, professional, appearance-conscious, grounded
- Unposed or minimally posed — candid energy preferred
- Skin texture visible — no airbrushing
- Environmental context welcome — clinic, outdoor, lifestyle — as long as the subject is primary
- Never: jumping, arms spread, forced smile, looking at the camera with a performance smile

**Men (secondary — TRT, peptides, metabolic wellness):**
- 40s–60s, natural energy, genuine happiness
- Active or at rest — no performance fitness poses
- Never: shirtless fitness shots, measuring tape, before/after body-measurement content

**Props to avoid in all photography:**
- Measuring tape
- Bathroom scale
- Clinical white-box studio background
- Workout equipment used as a wellness metaphor
- Stock wellness poses of any kind

#### Before / After Treatment

- Use the L-bracket gold frame treatment for before/after panels
- P-700 badge labels for treatment name / result identifier
- Never use hard-bordered BEFORE/AFTER blocks with old typography
- Caption in Playfair Display italic, caption size, bottom of frame

---

### 1.13 — Layout & Design Rules

#### Color

**DO:**
- Anchor every page with N-100 as the base page background
- Use P-700 for section-level hierarchy — section and tile level only, not full-page
- Use texture SVGs (NV-200) occasionally to add depth to N-100 sections
- Use Q-300 on dark and Q-700 on light — non-interchangeable
- Use S-family for female-forward content, T-family for male-forward — intentionally, not decoratively
- Use NV-500 and NV-700 for all dividers, rules, underlines, and callout lines

**DON'T:**
- Use mid-tones (any 300–600 stop) as section or page backgrounds
- Use P-700 as a full-page background — sections and tiles only
- Use texture SVGs on P-700 backgrounds
- Use more than two accent families on a single surface without a neutral separator
- Introduce any color outside the six locked families
- Use pure `#000000` or `#ffffff`

#### Layout

**DO:**
- Use texture SVGs rotated 90° filling the full section — N-100 only, one per section, not in adjacent sections
- Use Playfair Display ghosted background text on N-100 sections (8–12% opacity)
- Use the L-bracket gold frame for before/after and featured content panels
- Annotate product and service features with callout lines in NV-700 or NV-500
- Use NV-500 and NV-700 for all section dividers, rules, and underlines

**DON'T:**
- Use gradient tiles as full-section or full-page backgrounds — component level only
- Stack more than two different gradient tile families without a neutral tile between them
- Center-align body copy over two lines — left-aligned only
- Stack a texture SVG and the logo mark watermark in the same section

#### Ad Creative

**DO:**
- Carry B&W photography into performance ads — the brand's most distinctive visual move
- Apply the type system (EB Garamond + Playfair Display + Work Sans) to all ad production
- Use the before/after L-bracket treatment with P-700 badge labels on result-based ads
- Keep legal/disclaimer copy in Playfair Display 400 italic at caption size, bottom of frame
- Use B&W annotated photography with NV-700/NV-500 callout lines as a primary ad layout

**DON'T:**
- Use the legacy Poppins all-caps type system in any new ad production
- Use hard-bordered BEFORE/AFTER stock blocks with old typography
- Use imagery that contradicts the photography brief

---

### 1.14 — CSS Tokens

```css
:root {
  /* COLORS — PRIMARY */
  --bb-P-900: #030507; --bb-P-800: #131c25; --bb-P-700: #2b3a4a;
  --bb-P-600: #3e536a; --bb-P-500: #506d8b; --bb-P-400: #6a89a9;
  --bb-P-300: #91a7bf; --bb-P-200: #b1c4d7; --bb-P-100: #d0dbe7;

  /* COLORS — SECONDARY */
  --bb-S-800: #49182f; --bb-S-700: #722c4d; --bb-S-500: #b94b7f;
  --bb-S-300: #da9fbb; --bb-S-200: #ecc5d8;

  /* COLORS — TERTIARY */
  --bb-T-700: #676637; --bb-T-600: #888749; --bb-T-500: #a8a65c;
  --bb-T-300: #d1d0a8;

  /* COLORS — QUATERNARY (GOLD) */
  --bb-Q-700: #866118; --bb-Q-500: #d99e2b; --bb-Q-300: #ebcc8e;

  /* COLORS — NEUTRAL */
  --bb-N-900: #1c1a17; --bb-N-700: #554f4a; --bb-N-600: #706961;
  --bb-N-500: #8b8279; --bb-N-400: #a59e97; --bb-N-300: #c1bdb8;
  --bb-N-200: #dcd9d5; --bb-N-100: #f1f0ee;

  /* COLORS — NEUTRAL VARIANT */
  --bb-NV-700: #595546; --bb-NV-500: #918c73; --bb-NV-300: #c5c2b5;
  --bb-NV-200: #deddd3; --bb-NV-100: #f2f1ed;

  /* TYPOGRAPHY — FAMILIES */
  --bb-font-display: 'EB Garamond', Georgia, serif;
  --bb-font-accent:  'Playfair Display', Georgia, serif;
  --bb-font-body:    'Work Sans', system-ui, sans-serif;

  /* TYPOGRAPHY — SCALE */
  --bb-type-hero:       4rem;
  --bb-type-heading:    3.25rem;
  --bb-type-subhead:    2.25rem;
  --bb-type-card-title: 2.25rem;
  --bb-type-body-lg:    1.5rem;
  --bb-type-button:     1.5rem;
  --bb-type-body:       1.125rem;
  --bb-type-caption:    0.875rem;
  --bb-type-eyebrow:    0.56rem;
  --bb-type-eyebrow-ls: 0.32em;

  /* GRADIENTS */
  --bb-grad-neutral-rest:   linear-gradient(135deg, #131c25, #6a89a9);
  --bb-grad-neutral-active: linear-gradient(135deg, #2b3a4a, #91a7bf);
  --bb-grad-female-rest:    linear-gradient(135deg, #131c25, #49182f);
  --bb-grad-female-active:  linear-gradient(135deg, #2b3a4a, #722c4d);
  --bb-grad-male-rest:      linear-gradient(135deg, #131c25, #888749);
  --bb-grad-male-active:    linear-gradient(135deg, #2b3a4a, #a8a65c);
  --bb-grad-button-rest:    linear-gradient(120deg, #131c25, #6a89a9);
  --bb-grad-button-hover:   linear-gradient(120deg, #2b3a4a, #91a7bf);

  /* SHADOWS */
  --bb-shadow-sm: 0 2px 8px rgba(28,26,23,.06), 0 1px 2px rgba(28,26,23,.04);
  --bb-shadow-md: 0 4px 16px rgba(28,26,23,.10), 0 2px 4px rgba(28,26,23,.06);
  --bb-shadow-lg: 0 8px 32px rgba(28,26,23,.14), 0 4px 8px rgba(28,26,23,.08);

  /* SPACING */
  --bb-space-1:  0.25rem; --bb-space-2:  0.5rem;  --bb-space-3:  0.75rem;
  --bb-space-4:  1rem;    --bb-space-6:  1.5rem;  --bb-space-8:  2rem;
  --bb-space-12: 3rem;    --bb-space-16: 4rem;    --bb-space-18: 4.5rem;
  --bb-space-20: 5rem;    --bb-space-24: 6rem;

  /* GRID */
  --bb-grid-columns:       12;
  --bb-grid-max-width:     1280px;
  --bb-grid-gutter-desk:   24px;
  --bb-grid-gutter-mob:    16px;
  --bb-grid-margin-desk:   80px;
  --bb-grid-margin-mob:    16px;

  /* BORDER RADIUS */
  --bb-radius-button: 8px;
}
```

---

## SECTION 2 — BRAND VOICE & POSITIONING

### 2.1 — Essence Statement

> Body Balance helps you feel like yourself again by closing the disconnect between how you feel inside and how you look outside — through integrated hormone health and aesthetic care that actually listens.

This statement is the organizing principle for every piece of content this brand produces. If a piece of creative cannot be traced back to this statement, it does not fit the brand.

---

### 2.2 — The Core Offering

Body Balance Medical helps people look better and feel better — at the same time — by combining hormone health, metabolic wellness, and aesthetic treatments in a single practice that actually listens.

**What makes this different:** The integration of both tracks — clinical and aesthetic — in one practice, delivered by two dedicated Nurse Practitioners whose specialties mirror each other. Teresa owns aesthetics; Mia owns hormone health and longevity medicine. Together, they are the integrated plan made real.

**The outcome:** The patient leaves feeling like someone finally saw the whole picture — their energy, their body, their skin — and gave them a real plan. Not just a treatment. A direction.

---

### 2.3 — Target Audience

#### Primary Avatar

A woman in her early-to-mid 40s — professional, high-achieving, appearance-conscious — who is starting to notice a gap between how she wants to feel and how she actually feels. She is proactive, not reactive. She invests in herself, expects quality, and is done with providers who only address half the picture.

**What she wants most:** To look like the version of herself she still feels like inside — and to actually feel that way too, not just look it.

**What makes her hesitate:** Trust. She has been dismissed before, oversold before, and handed generic plans before. She needs to believe this place is different before she commits. Price is a surface objection — trust is the real one.

**Two entry points, one promise:**
- *Aesthetics entry:* She wants to look like the version of herself she has in her head. The surface-level treatments she's tried haven't fully gotten her there.
- *Hormone entry:* She feels off in a way she can't fully articulate, and no one has connected the dots for her. She's been told her labs look fine. She doesn't feel fine.

Both resolve to the same underlying truth: nobody has given her a plan that treats both as part of the same problem.

#### Secondary Avatar

Men 40s–60s seeking TRT, peptides, and metabolic wellness (approximately 20% of clientele). The brand is women-forward in voice and visual direction — but the core promise applies to anyone experiencing the disconnect between how they feel inside and how they look and perform outside. Do not alienate male patients at the brand level.

#### Who the Brand Is NOT For

- The budget-driven one-off shopper
- The patient who wants pure aesthetics with no relationship
- The patient who equates clinical coldness with credibility
- Anyone seeking trend-driven, influencer-aesthetic treatments

---

### 2.4 — Brand Personality

| Attribute | What It Means | What It Is Not |
|---|---|---|
| Grounded | Rooted in clinical reality, never hype-forward | Cold, distant, or overly academic |
| Warm without soft | Genuinely caring, but with a confident backbone | Saccharine, sycophantic, or soft-selling |
| Clearly intelligent | Educates without condescending | Dense, jargon-heavy, or showing off |
| Restorative | The frame is always return and alignment, not transformation | Fixing what's broken, anti-aging, better-you |
| Honest | Says what it means, means what it says | Salesy, inflated, or outcome-guaranteed |

---

### 2.5 — Voice & Tone

**In three words:** Personal. Confident. Restrained.

**In conversation:** Body Balance speaks like a knowledgeable friend who also happens to be a clinician. Warm enough to make you feel seen. Authoritative enough to make you feel safe. Never salesy, never clinical to the point of coldness, never performatively empathetic.

**The register shifts by channel:**

| Channel | Register |
|---|---|
| Paid Ads (Meta/Google) | Lead with symptom language and feeling. "Tired but can't sleep" over "hormone optimization." Emotional recognition is the hook. |
| Email / Nurture | Slightly more clinical language as trust builds. Explain the why. Use "hormone balance," "peptide protocols," "lab-guided care." |
| Organic Social | Educational primary. Carousel explainers, myth-busting, honest conversations. Real patient language used directly. |
| Website | Homepage and hero in feeling language. Service and provider pages can go clinical. |

---

### 2.6 — Messaging Pillars

**1. The disconnect is real — and it's connected.**
The gap between how you feel inside and how you look and function outside is not in your head. And it's rarely just one thing. Body Balance treats both sides because they're part of the same picture.

**2. Two providers, one plan.**
Teresa and Mia aren't in separate departments. Their specialties mirror each other by design. The aesthetics conversation and the hormone conversation happen in the same practice, with providers who talk to each other.

**3. We listen differently.**
Most providers address the presenting symptom. Body Balance connects the dots — labs, aesthetics, energy, weight, skin — and builds a plan around the whole person.

**4. Restoration, not transformation.**
The goal is not to become someone new. It is to return to the version of yourself you recognize — and to feel like that person again, not just look like them.

---

### 2.7 — Vocabulary

#### Own These Words

- Aligned / alignment
- Hormone balance / hormone health
- Inside and out / interior and exterior
- Plan / program (structured, not just "treatments")
- Listen / heard / seen
- Real / grounded / honest
- Energy / clarity / vitality
- Restore / return

#### Customer Language — Use Directly in Copy

- "I finally feel like myself again"
- "I didn't recognize myself"
- "My hormones are all over the place"
- "Everything is connected"
- "Someone who actually listens"
- "Tired but can't sleep"
- "Weight won't move"
- "I feel off"
- "Nobody connected the dots for me"
- "I want to feel young, not just look young"

#### Banned Words — Never Use

| Word | Reason |
|---|---|
| Luxury | Saturated, table stakes — express it, never say it |
| Glow / glowing | Every competitor says it — generic wellness language |
| Confidence | The category default — implies the current self is lacking |
| Better you / best self | Implies the current version is broken |
| Transform / transformation | Too dramatic — implies discontinuity, not alignment |
| Queen / babe / girl boss | Trend-driven, undermines medical credibility |
| Deserve | Patronizing — implies she hasn't had something she should have had |
| Empower / empowerment | Hollow, overused in wellness marketing |
| Anti-aging | Frames the problem as age, not as disconnect |
| Natural results | Everyone says it — means nothing |
| Personalized plan | Only ownable when demonstrated specifically, never claimed generically |
| Look your best | Generic — doesn't speak to the real job to be done |
| Self-care | Diluted — doesn't capture the clinical and emotional depth here |
| Aesthetic enhancement | Clinical jargon — use feeling language in ads |
| Biote | Credibility with informed patients and on the website — not an ad hook for top-of-funnel |

---

### 2.8 — Anti-Brief

**This brand is NOT:**
- A luxury destination — luxury is implicit in the experience, never claimed in the language
- A clinical optimization lab — the medicine is real; the experience of it is human
- A trend-driven med spa — no seasonal treatments, no influencer aesthetics, no gimmick hooks
- An anti-aging brand — the frame is restoration and alignment, not reversing time
- A beauty brand — aesthetics is the front door, not the whole house

**Visual anti-brief:**
- No flat studio white-box photography
- No bright saturated color palettes
- No measuring tape, scale, or body-measurement props
- No stock wellness poses — jumping, arms spread, forced smiles
- No old Poppins all-caps type system in any new production
- No hard-bordered before/after blocks with legacy typography

---

## SECTION 3 — ASSET LIBRARY

All assets are hosted in the public GitHub repository:
`https://github.com/joshkeplersmith-source/bbm-design-system`

Base URL for raw file access:
`https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/`

---

### 3.1 — Logo Files

#### Horizontal Logos (H)
Wordmark + mark side by side. Default logo format.

| File | Color | Use On | URL |
|---|---|---|---|
| BB-H-Logo-B.svg | Black | Light backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-H-Logo-B.svg` |
| BB-H-Logo-W.svg | White | Dark backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-H-Logo-W.svg` |
| BB-H-Logo-G.svg | Gold | Accent contexts | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-H-Logo-G.svg` |
| BB-H-Logo-Bu.svg | Blue (P-700) | Light, brand-forward contexts | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-H-Logo-Bu.svg` |

#### Vertical Logos (V)
Wordmark + mark stacked. Use when horizontal space is limited.

| File | Color | Use On | URL |
|---|---|---|---|
| BB-V-Logo-B.svg | Black | Light backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-V-Logo-B.svg` |
| BB-V-Logo-W.svg | White | Dark backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-V-Logo-W.svg` |
| BB-V-Logo-G.svg | Gold | Accent contexts | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-V-Logo-G.svg` |
| BB-V-Logo-Bu.svg | Blue (P-700) | Light, brand-forward contexts | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-V-Logo-Bu.svg` |

#### Mark Only (Icon)
No wordmark. Use at small sizes or when the context is already brand-established.

| File | Color | Use On | URL |
|---|---|---|---|
| BB-Logo-Mark-B.svg | Black | Light backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-Logo-Mark-B.svg` |
| BB-Logo-Mark-W.svg | White | Dark backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-Logo-Mark-W.svg` |
| BB-Logo-Mark-G.svg | Gold | Accent contexts | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-Logo-Mark-G.svg` |
| BB-Logo-Mark-Bu.svg | Blue (P-700) | Light, brand-forward contexts | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-Logo-Mark-Bu.svg` |

#### Social Logos
Optimized for social platform contexts.

| File | Color | Use On | URL |
|---|---|---|---|
| BB-Social-Logo-B.svg | Black | Light platform backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-Social-Logo-B.svg` |
| BB-Social-Logo-W.svg | White | Dark platform backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-Social-Logo-W.svg` |
| BB-Social-Mark-B.svg | Black | Profile images, light backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-Social-Mark-B.svg` |
| BB-Social-Mark-W.svg | White | Profile images, dark backgrounds | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/logos/BB-Social-Mark-W.svg` |

---

### 3.2 — Texture Files

7 texture SVGs. Use as fill elements in N-100 sections. Rotate 90°, fill container, opacity 26–40%.

| File | URL |
|---|---|
| BB-Brand-Refresh-Textures-03.svg | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/textures/BB-Brand-Refresh-Textures-03.svg` |
| BB-Brand-Refresh-Textures-04.svg | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/textures/BB-Brand-Refresh-Textures-04.svg` |
| BB-Brand-Refresh-Textures-05.svg | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/textures/BB-Brand-Refresh-Textures-05.svg` |
| BB-Brand-Refresh-Textures-06.svg | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/textures/BB-Brand-Refresh-Textures-06.svg` |
| BB-Brand-Refresh-Textures-07.svg | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/textures/BB-Brand-Refresh-Textures-07.svg` |
| BB-Brand-Refresh-Textures-08.svg | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/textures/BB-Brand-Refresh-Textures-08.svg` |
| BB-Brand-Refresh-Textures-09.svg | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/textures/BB-Brand-Refresh-Textures-09.svg` |

#### Logo Mark Watermark

| File | URL |
|---|---|
| BB-Logo-Mark-Texture.webp | `https://raw.githubusercontent.com/joshkeplersmith-source/bbm-design-system/main/textures/BB-Logo-Mark-Texture.webp` |

---

## SECTION 4 — OUTPUT TYPES

What this system can build, per environment, and what asset access each environment supports.

| Output Type | Environment | Logo Access | Texture Access | Notes |
|---|---|---|---|---|
| HTML email templates | GHL | Full — GitHub URLs resolve | Full | Import Google Fonts via `<link>` |
| Web pages | Webflow | Full — GitHub URLs resolve | Full | Use CSS tokens from Section 1.14 |
| PDFs / presentations | Claude Code | Full — GitHub URLs resolve | Full | Reference URLs directly in HTML-to-PDF |
| Word documents | Google Docs | Manual drop-in required | Not applicable | Apply rules-based: colors, fonts, spacing |
| Canva templates | Canva | Pre-loaded by Josh | Not applicable | Templates pre-built — team uses as-is |
| Social content | Canva | Pre-loaded by Josh | Not applicable | Templates pre-built — team uses as-is |

---

## SECTION 5 — GRACEFUL DEGRADATION

This section defines how to behave when working in a closed environment where the GitHub asset URLs cannot resolve.

### State 1 — GitHub Accessible (Normal Operation)

Pull all logos and textures by URL from Section 3. Full system, all assets available. No user action required. Build and proceed normally.

### State 2 — GitHub Not Accessible (Restricted Environment)

Everything can still be built. Colors, typography, spacing, voice, component patterns, and layout rules are all available from this file — no external access required. The only thing that may require a file from the user is the logo.

**Textures:** Omit silently. Do not mention them. Do not flag them as missing. Do not ask the user to provide them. A page or document without textures is still fully on-brand — textures are enhancements, not requirements.

**Logo:** If a logo is needed for the output being built, say exactly this (adjust wording naturally for context):

> *"I can't access the logo files from the design system in this environment. Josh should have shared the BBM logo files with you — drop the logo you need into this chat and I'll use it. If you're not sure which one to use, ask Josh for the [Black horizontal / White horizontal / Black mark] version depending on your background."*

Then wait for the upload and proceed. Do not build without the logo if the output requires one. Do not substitute a placeholder, a text label, or any other element in place of the logo.

**After the user uploads the logo:** Confirm receipt and proceed. Do not re-explain the restriction. Build normally with the uploaded file.

---

## SECTION 6 — IMAGE GENERATION

### If You Can Generate Images

Apply these style instructions directly to every image generated for this brand.

**Primary style — Black & White:**
- Film photography aesthetic — not clinical digital monochrome
- Rich midtones, soft contrast, authentic grain
- Natural soft lighting — never flat studio or harsh strobe
- Subjects: real women 30s–40s, unposed, skin texture visible; men 40s–60s for wellness/TRT content
- Environmental context welcome — clinic, outdoor, lifestyle — subject always primary
- Mood: grounded, warm, present — never aspirational-stock or performative

**Secondary style — Portra 400 Color:**
- Warm, slightly faded color palette — not saturated
- Natural film grain, soft highlights, warm shadows
- Same subject direction as B&W above
- Color stays within the brand's warm earth tone range — nothing electric or bright

**Always avoid:** measuring tape, bathroom scale, studio white-box background, stock wellness poses (jumping, arms spread, forced smile), airbrushed or smoothed skin, bright saturated color.

### If You Cannot Generate Images

Output this ready-to-use prompt for the user to take to Midjourney, Firefly, DALL-E, or any image generation tool. All BBM brand variables are baked in — the user does not need to know the brand system to get an on-brand result.

**Copy and adapt this prompt — fill in `[SUBJECT]` and `[SETTING]`:**

```
[SUBJECT] in [SETTING], editorial portrait photography, black and white film aesthetic,
Kodak Tri-X grain, soft natural window light, rich midtones, no blown highlights,
unposed candid moment, authentic skin texture, no retouching, no studio lighting,
cinematic composition, warm and grounded mood, medical wellness atmosphere,
real person not model-perfect, 30s-40s professional woman [or: 40s-60s man for wellness content],
environmental context visible but subject primary. Style: film photography, not digital.
No measuring tape. No workout equipment. No forced smiles. No aspirational stock imagery.
```

**For Portra 400 color variant — add to the prompt:**
```
Color photography, Kodak Portra 400 film simulation, warm slightly faded tones,
natural grain, soft warm shadows, no saturation boost, no Instagram filter treatment.
```

---

## SECTION 7 — AGENT BEHAVIOR RULES

When working from this brand system, follow these rules for every session.

**Before building anything:**
1. Confirm the brand system is loaded: *"Body Balance Medical brand system active. Ready to build."*
2. Identify the output type and environment (see Section 4).
3. Check GitHub access state and apply the correct mode (see Section 5).
4. If a logo is needed and GitHub is inaccessible, ask for the file before proceeding.

**While building:**
- Never use a color outside the six families defined in Section 1.1.
- Never introduce a font outside the three families defined in Section 1.5.
- Reference color pairings by code (D1–D6, L1–L6) — never describe colors manually.
- If generating copy, apply the voice rules from Section 2.5 and the vocabulary rules from Section 2.7.
- If the output involves a logo, apply the logo context guide from Section 1.11.
- Textures are enhancements — include them if GitHub is accessible and the layout benefits from them. Never force a texture where it doesn't serve the layout.

**If you're unsure about a design decision:**
Default to: N-100 background, P-700 section accent, EB Garamond heading (upright + italic mix), Work Sans 300 body, Q-300 gold accent on dark / Q-700 gold accent on light. That is the brand's safe baseline.

**Flagging gaps:**
If something required to complete the output is missing or unclear, flag it specifically and wait for input. Never silently produce an off-brand result. Never guess at a logo file, a brand color, or a voice rule.

**Updating this file:**
If a design value changes after review, the change goes into `BB-DESIGN-SYSTEM-SPEC.md` first, then `BB-BRAND.md` is rebuilt. Do not attempt to edit this file mid-session to accommodate a one-off change. Flag the change, complete the session using the current values, and note that the spec update is needed afterward.

---

## QUICK REFERENCE

**Page background:** N-100 `#f1f0ee`
**Section dark background:** P-700 `#2b3a4a`
**Primary heading:** EB Garamond 400 upright + italic · 3.25rem
**Body copy:** Work Sans 300 · 1.125rem · N-900 `#1c1a17` on light / N-100 `#f1f0ee` on dark
**Gold on dark:** Q-300 `#ebcc8e`
**Gold on light:** Q-700 `#866118`
**Button:** Gradient `linear-gradient(120deg, #131c25, #6a89a9)` · Playfair Display · 8px radius
**Default logo (light bg):** BB-H-Logo-B.svg
**Default logo (dark bg):** BB-H-Logo-W.svg
**Essence:** *Feel like yourself again — integrated hormone and aesthetic care that listens.*

---

*Captain Kepler Creative · Josh Smith · 2026 · Confidential*
*BB-BRAND.md — Body Balance Medical Brand Operating System v1.0*
*Built from: BB-DESIGN-SYSTEM-SPEC.md + BB-BRAND-PYRAMID.md*
*Repo: https://github.com/joshkeplersmith-source/bbm-design-system*
