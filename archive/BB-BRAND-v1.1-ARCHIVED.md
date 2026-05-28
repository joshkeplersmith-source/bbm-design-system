# BODY BALANCE MEDICAL — Brand Operating System
**Captain Kepler Creative · Josh Smith · 2026**
**File:** `BRAND.md` · Version 1.1
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

**Ghosted background text:** Large Playfair Display text rendered at low opacity (8–12%) behind section content. N-100 sections only. Once per page maximum.

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
- Use bold as a subheading substitute

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

7 texture SVGs available. Use as fill elements in N-100 sections only.

**Texture fill color:** NV-200 `#deddd3`
**Opacity range:** 26–40%
**Rotation:** 90°
**Behavior:** Fill container · `preserveAspectRatio="xMidYMid slice"` · `inset:0; width:100%; height:100%`

**Rules:**
- N-100 sections only — never on P-700 backgrounds
- One texture per section maximum
- Never apply to two adjacent sections
- Opacity only — no color inversion, no blend modes
- Never stack a texture and the logo mark watermark in the same section

#### Logo Mark Watermark

**File:** `BB-Logo-Mark-Texture.webp`
**URL:** `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Logo-Mark-Texture.webp`
**Usage:** Large centered watermark. Full viewport height sections only. Once per page maximum.
**Behavior:** `object-fit: cover; inset: 0; width: 100%; height: 100%`
**Opacity:** 100% (WebP transparency handles visual weight)
**Blend mode:** None
**Context:** N-100 sections only

---

### 1.11 — Logo System

**16 logo variants.** Every variant serves a specific background and context.

#### Logo Families

| Family | Description | Variants |
|---|---|---|
| H (Horizontal) | Wordmark + mark side by side — default format | B, Bu, G, W |
| V (Vertical) | Wordmark + mark stacked | B, Bu, G, W |
| Mark (Icon) | Mark only, no wordmark | B, Bu, G, W |
| Social Logo | Horizontal, optimized for social platforms | B, W |
| Social Mark | Mark only, optimized for social platforms | B, W |

#### Color Variant Key

| Suffix | Color | Use On |
|---|---|---|
| B | Black N-900 `#1c1a17` | Light backgrounds |
| W | White N-100 `#f1f0ee` | Dark backgrounds |
| G | Gold | Accent contexts only |
| Bu | Blue P-700 `#2b3a4a` | Light, brand-forward contexts |

#### Context Guide

| Background | Recommended Logo |
|---|---|
| N-100 (light page) | H or V · B variant |
| P-700 (dark section) | H or V · W variant |
| Gradient tile | Mark · W variant |
| Social profile image | Social Mark · B or W |
| Social post / story | Social Logo · B or W |
| Gold accent moment | H or V · G variant |
| Brand-blue moment | H or V · Bu variant |

#### Logo Rules

**DO:**
- Match logo color variant to background context
- Maintain clearspace equal to the height of the "B" letterform on all sides
- Use H as default · V when layout requires taller format · Mark at small/icon sizes

**DON'T:**
- Place on mid-tone background without verifying contrast
- Apply any effect not in the approved variants
- Scale wordmark below ~11px cap height
- Crop, rotate, skew, or distort
- Recolor any variant

---

### 1.12 — Photography Brief

#### Primary Mode — Black & White
Film-forward, not clinical digital. Rich midtones, soft contrast, authentic grain. No airbrushing.

#### Secondary Mode — Kodak Portra 400
Warm, slightly faded color. Natural grain, soft highlights. Film emulation — not Instagram filter.

#### Subject Direction
- **Women:** 30s–40s, unposed, skin texture visible, environmental context welcome
- **Men:** 40s–60s, natural energy — for TRT and wellness content
- **Always avoid:** measuring tape, scale, studio white-box, stock wellness poses, airbrushed skin

#### Before / After Treatment
L-bracket gold frame · P-700 badge labels · Playfair Display italic caption · Never hard-bordered legacy blocks

---

### 1.13 — Layout & Design Rules

**Color DO:** N-100 page base · P-700 section hierarchy · Q-300 on dark / Q-700 on light · S-family female-forward · T-family male-forward · NV-500/700 for all rules and dividers

**Color DON'T:** Mid-tones as backgrounds · P-700 full-page · Textures on P-700 · More than two accent families without neutral separator · Any color outside the six families · Pure black or white

**Layout DO:** Textures rotated 90° filling N-100 sections · Playfair Display ghosted text on N-100 · L-bracket gold frame for featured content · NV-700/500 callout lines for annotations

**Layout DON'T:** Gradient tiles as full-section backgrounds · More than two gradient tile families without neutral separator · Center-aligned body copy over two lines · Texture + logo mark watermark in same section

**Ad Creative DO:** B&W photography in performance ads · Full type system on all new ad production · L-bracket before/after with P-700 badge labels · Disclaimer copy in Playfair Display italic caption size

**Ad Creative DON'T:** Legacy Poppins all-caps system · Hard-bordered before/after blocks · Imagery contradicting the photography brief

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
  --bb-grid-columns:     12;
  --bb-grid-max-width:   1280px;
  --bb-grid-gutter-desk: 24px;
  --bb-grid-gutter-mob:  16px;
  --bb-grid-margin-desk: 80px;
  --bb-grid-margin-mob:  16px;

  /* BORDER RADIUS */
  --bb-radius-button: 8px;
}
```

---

## SECTION 2 — BRAND VOICE & POSITIONING

### 2.1 — Essence Statement

> Body Balance helps you feel like yourself again by closing the disconnect between how you feel inside and how you look outside — through integrated hormone health and aesthetic care that actually listens.

Every piece of content this brand produces must be traceable back to this statement.

---

### 2.2 — The Core Offering

Body Balance Medical helps people look better and feel better — at the same time — by combining hormone health, metabolic wellness, and aesthetic treatments in a single practice that actually listens.

Two dedicated Nurse Practitioners whose specialties mirror each other: Teresa owns aesthetics; Mia owns hormone health and longevity medicine. Together, they are the integrated plan made real.

**The outcome:** The patient leaves feeling like someone finally saw the whole picture — their energy, their body, their skin — and gave them a real plan. Not just a treatment. A direction.

---

### 2.3 — Target Audience

#### Primary Avatar
A woman in her early-to-mid 40s — professional, high-achieving, appearance-conscious — who notices a gap between how she wants to feel and how she actually feels. Proactive. Invests in herself. Done with providers who only address half the picture.

**What she wants most:** To look like the version of herself she still feels like inside — and to actually feel that way too.

**What makes her hesitate:** Trust. She has been dismissed, oversold, and handed generic plans before. Price is a surface objection — trust is the real one.

**Two entry points:**
- *Aesthetics:* Surface treatments haven't fully gotten her there.
- *Hormones:* She feels off, can't articulate it, been told her labs look fine. She doesn't feel fine.

Both resolve to the same truth: nobody has given her a plan that treats both as part of the same problem.

#### Secondary Avatar
Men 40s–60s — TRT, peptides, metabolic wellness. Brand is women-forward in voice and visual direction but the core promise applies to anyone experiencing the disconnect. Do not alienate male patients at the brand level.

#### Who the Brand Is NOT For
Budget-driven one-off shoppers · patients wanting pure aesthetics with no relationship · patients who equate clinical coldness with credibility · trend-driven influencer-aesthetic seekers

---

### 2.4 — Brand Personality

| Attribute | What It Means | What It Is Not |
|---|---|---|
| Grounded | Rooted in clinical reality, never hype-forward | Cold, distant, academic |
| Warm without soft | Genuinely caring, confident backbone | Saccharine, soft-selling |
| Clearly intelligent | Educates without condescending | Dense, jargon-heavy |
| Restorative | Return and alignment, not transformation | Fixing what's broken, anti-aging |
| Honest | Says what it means | Salesy, inflated, outcome-guaranteed |

---

### 2.5 — Voice & Tone

**In three words:** Personal. Confident. Restrained.

Speaks like a knowledgeable friend who is also a clinician. Warm enough to feel seen. Authoritative enough to feel safe. Never salesy, never cold, never performatively empathetic.

| Channel | Register |
|---|---|
| Paid Ads | Symptom and feeling language. "Tired but can't sleep" over "hormone optimization." |
| Email / Nurture | Slightly more clinical as trust builds. Explain the why. |
| Organic Social | Educational primary. Real patient language. Myth-busting. |
| Website | Homepage/hero in feeling language. Service/provider pages can go clinical. |

---

### 2.6 — Messaging Pillars

1. **The disconnect is real — and it's connected.** The gap between how you feel inside and how you function outside is not in your head. Body Balance treats both sides because they're part of the same picture.
2. **Two providers, one plan.** Teresa and Mia's specialties mirror each other by design. The aesthetics and hormone conversations happen in the same practice, with providers who talk to each other.
3. **We listen differently.** Most providers address the presenting symptom. Body Balance connects the dots and builds a plan around the whole person.
4. **Restoration, not transformation.** The goal is to return to the version of yourself you recognize — and to feel like that person again, not just look like them.

---

### 2.7 — Vocabulary

#### Own These Words
Aligned / alignment · hormone balance / hormone health · inside and out · plan / program · listen / heard / seen · real / grounded / honest · energy / clarity / vitality · restore / return

#### Customer Language — Use Directly in Copy
"I finally feel like myself again" · "I didn't recognize myself" · "My hormones are all over the place" · "Everything is connected" · "Someone who actually listens" · "Tired but can't sleep" · "Weight won't move" · "I feel off" · "Nobody connected the dots for me" · "I want to feel young, not just look young"

#### Banned Words — Never Use

| Word | Reason |
|---|---|
| Luxury | Saturated — express it, never say it |
| Glow / glowing | Generic wellness language |
| Confidence | Implies the current self is lacking |
| Better you / best self | Implies the current version is broken |
| Transform / transformation | Implies discontinuity, not alignment |
| Queen / babe / girl boss | Undermines medical credibility |
| Deserve | Patronizing |
| Empower / empowerment | Hollow, overused |
| Anti-aging | Frames the problem as age, not disconnect |
| Natural results | Means nothing |
| Personalized plan | Only ownable when demonstrated specifically |
| Look your best | Generic |
| Self-care | Diluted |
| Aesthetic enhancement | Jargon — use feeling language in ads |
| Biote | Website and informed patients only — not a top-of-funnel ad hook |

---

### 2.8 — Anti-Brief

**This brand is NOT:** a luxury destination · a clinical optimization lab · a trend-driven med spa · an anti-aging brand · a beauty brand

**Visual anti-brief:** No flat studio white-box photography · no bright saturated color · no measuring tape or scale · no stock wellness poses · no legacy Poppins all-caps type system · no hard-bordered before/after blocks

---

## SECTION 3 — ASSET LIBRARY

All assets are served from Cloudflare R2:
**Base URL:** `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev`

Source repo (version control): `https://github.com/joshkeplersmith-source/bbm-design-system`

---

### 3.1 — Logo Files

#### Horizontal Logos — Default format

| File | Color | Use On | URL |
|---|---|---|---|
| BB-H-Logo-B.svg | Black | Light backgrounds | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-H-Logo-B.svg` |
| BB-H-Logo-W.svg | White | Dark backgrounds | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-H-Logo-W.svg` |
| BB-H-Logo-G.svg | Gold | Accent contexts | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-H-Logo-G.svg` |
| BB-H-Logo-Bu.svg | Blue P-700 | Light, brand-forward | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-H-Logo-Bu.svg` |

#### Vertical Logos — When horizontal space is limited

| File | Color | Use On | URL |
|---|---|---|---|
| BB-V-Logo-B.svg | Black | Light backgrounds | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-V-Logo-B.svg` |
| BB-V-Logo-W.svg | White | Dark backgrounds | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-V-Logo-W.svg` |
| BB-V-Logo-G.svg | Gold | Accent contexts | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-V-Logo-G.svg` |
| BB-V-Logo-Bu.svg | Blue P-700 | Light, brand-forward | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-V-Logo-Bu.svg` |

#### Mark Only — Icon size or brand-established contexts

| File | Color | Use On | URL |
|---|---|---|---|
| BB-Logo-Mark-B.svg | Black | Light backgrounds | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-Logo-Mark-B.svg` |
| BB-Logo-Mark-W.svg | White | Dark backgrounds | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-Logo-Mark-W.svg` |
| BB-Logo-Mark-G.svg | Gold | Accent contexts | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-Logo-Mark-G.svg` |
| BB-Logo-Mark-Bu.svg | Blue P-700 | Light, brand-forward | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-Logo-Mark-Bu.svg` |

#### Social Logos

| File | Color | Use On | URL |
|---|---|---|---|
| BB-Social-Logo-B.svg | Black | Light platform backgrounds | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-Social-Logo-B.svg` |
| BB-Social-Logo-W.svg | White | Dark platform backgrounds | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-Social-Logo-W.svg` |
| BB-Social-Mark-B.svg | Black | Profile images, light | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-Social-Mark-B.svg` |
| BB-Social-Mark-W.svg | White | Profile images, dark | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/logos/BB-Social-Mark-W.svg` |

---

### 3.2 — Texture Files

| File | URL |
|---|---|
| BB-Brand-Refresh-Textures-03.svg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-03.svg` |
| BB-Brand-Refresh-Textures-04.svg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-04.svg` |
| BB-Brand-Refresh-Textures-05.svg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-05.svg` |
| BB-Brand-Refresh-Textures-06.svg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-06.svg` |
| BB-Brand-Refresh-Textures-07.svg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-07.svg` |
| BB-Brand-Refresh-Textures-08.svg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-08.svg` |
| BB-Brand-Refresh-Textures-09.svg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Brand-Refresh-Textures-09.svg` |
| BB-Logo-Mark-Texture.webp | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/textures/BB-Logo-Mark-Texture.webp` |

---

### 3.3 — Photography Reference

| File | URL |
|---|---|
| AdobeStock_293083555.jpg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/photography/AdobeStock_293083555.jpg` |
| AdobeStock_436559124.jpg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/photography/AdobeStock_436559124.jpg` |
| AdobeStock_448721416.jpg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/photography/AdobeStock_448721416.jpg` |
| AdobeStock_478793348.jpg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/photography/AdobeStock_478793348.jpg` |
| AdobeStock_605986661.jpg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/photography/AdobeStock_605986661.jpg` |
| AdobeStock_895842891.jpg | `https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev/photography/AdobeStock_895842891.jpg` |

---

## SECTION 4 — OUTPUT TYPES

| Output | Environment | Logo Access | Texture Access | Notes |
|---|---|---|---|---|
| HTML email templates | GHL | Full — R2 URLs resolve | Full | Import Google Fonts via `<link>` |
| Web pages | Webflow | Full — R2 URLs resolve | Full | Use CSS tokens from Section 1.14 |
| PDFs / documents | Claude Code | Full — R2 URLs resolve | Full | Reference URLs in HTML-to-PDF |
| Word documents | Google Docs | Manual drop-in | Not applicable | Rules-based: colors, fonts, spacing |
| Canva templates | Canva | Pre-loaded by Josh | Not applicable | Templates pre-built — use as-is |
| Social content | Canva | Pre-loaded by Josh | Not applicable | Templates pre-built — use as-is |

---

## SECTION 5 — GRACEFUL DEGRADATION

### State 1 — R2 Accessible (Normal Operation)

Pull all logos and textures directly from the URLs in Section 3. Full system, all assets available. Build and proceed normally.

### State 2 — R2 Not Accessible (Restricted Environment)

Everything can still be built. Colors, typography, spacing, voice, component patterns, and layout rules are all available from this file. The only thing that may require action from the user is the logo.

**Textures:** Omit silently. Do not mention them. Do not flag them as missing. Do not ask the user to provide them. A page without textures is still fully on-brand — textures are enhancements, not requirements.

**Logo:** If a logo is needed, say:
> *"I can't access the logo files in this environment. Josh should have shared the BBM logo files with you — drop the logo you need into this chat and I'll use it. If you're not sure which one to use, the most common ones are: BB-H-Logo-B.svg for light backgrounds, BB-H-Logo-W.svg for dark backgrounds."*

Wait for the upload. Do not build without the logo if the output requires one. Do not substitute a placeholder or text label. After upload, confirm and proceed — do not re-explain the restriction.

---

## SECTION 6 — IMAGE GENERATION

### If You Can Generate Images

**Primary style — Black & White:**
Film photography aesthetic. Rich midtones, soft contrast, authentic grain. Natural soft lighting — never flat studio. Real women 30s–40s, unposed, skin texture visible. Environmental context welcome. Mood: grounded, warm, present.

**Secondary style — Portra 400 Color:**
Warm, slightly faded. Natural grain, soft highlights. Color stays within the brand's warm earth tone range — nothing electric or saturated.

**Always avoid:** measuring tape · bathroom scale · studio white-box · stock wellness poses · airbrushed skin · bright saturated color

### If You Cannot Generate Images

Use this prompt — fill in `[SUBJECT]` and `[SETTING]`:

```
[SUBJECT] in [SETTING], editorial portrait photography, black and white film aesthetic,
Kodak Tri-X grain, soft natural window light, rich midtones, no blown highlights,
unposed candid moment, authentic skin texture, no retouching, no studio lighting,
cinematic composition, warm and grounded mood, medical wellness atmosphere,
real person not model-perfect, 30s–40s professional woman [or: 40s–60s man for wellness content],
environmental context visible but subject primary. Style: film photography, not digital.
No measuring tape. No workout equipment. No forced smiles. No aspirational stock imagery.
```

**For Portra 400 color — add:**
```
Color photography, Kodak Portra 400 film simulation, warm slightly faded tones,
natural grain, soft warm shadows, no saturation boost, no Instagram filter treatment.
```

---

## SECTION 7 — AGENT BEHAVIOR RULES

**Before building:**
1. Confirm: *"Body Balance Medical brand system active. Ready to build."*
2. Identify the output type and environment (Section 4)
3. Check R2 access state and apply correct mode (Section 5)
4. If logo needed and R2 inaccessible, ask for the file before proceeding

**While building:**
- Never use a color outside the six families in Section 1.1
- Never use a font outside the three families in Section 1.5
- Reference color pairings by code (D1–D6, L1–L6)
- Apply voice rules from Section 2.5 and vocabulary from Section 2.7 to all copy
- Apply logo context guide from Section 1.11 whenever a logo is used
- Include textures only when R2 is accessible and the layout benefits — never forced

**Safe baseline when unsure:**
N-100 background · P-700 section accent · EB Garamond heading (upright + italic mix) · Work Sans 300 body · Q-300 gold on dark / Q-700 gold on light

**Flagging gaps:**
Flag specifically and wait for input. Never silently produce an off-brand result. Never guess at a brand color, logo file, or voice rule.

**Updating this file:**
Changes go into `BB-DESIGN-SYSTEM-SPEC.md` first, then `BRAND.md` is rebuilt. Do not edit mid-session. Flag the change, complete the session with current values, note the spec update needed.

---

## QUICK REFERENCE

| | |
|---|---|
| Page background | N-100 `#f1f0ee` |
| Section dark | P-700 `#2b3a4a` |
| Primary heading | EB Garamond 400 upright + italic · 3.25rem |
| Body copy | Work Sans 300 · 1.125rem · N-900 on light / N-100 on dark |
| Gold on dark | Q-300 `#ebcc8e` |
| Gold on light | Q-700 `#866118` |
| Button | `linear-gradient(120deg, #131c25, #6a89a9)` · Playfair Display · 8px radius |
| Default logo (light bg) | BB-H-Logo-B.svg |
| Default logo (dark bg) | BB-H-Logo-W.svg |
| Essence | *Feel like yourself again — integrated hormone and aesthetic care that listens.* |

---

*Captain Kepler Creative · Josh Smith · 2026 · Confidential*
*BRAND.md — Body Balance Medical Brand Operating System v1.1*
*Built from: BB-DESIGN-SYSTEM-SPEC.md + BB-BRAND-PYRAMID.md*
*Assets: https://pub-3d3d32a357bf480291c4f1804a9ded88.r2.dev*
*Repo: https://github.com/joshkeplersmith-source/bbm-design-system*
