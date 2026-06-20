# BODY BALANCE MEDICAL — Brand Operating System (Pro)
**Captain Kepler Creative · Josh Smith · 2026**
**File:** `BB-BRAND-PRO.md` · Version 1.3
**Audience:** Josh Smith — designer, creative director, full tool access
**Status:** Active — Single source of truth for pro use

---

## HOW TO USE THIS FILE

This file is the complete brand operating system for Body Balance Medical — pro edition. It includes everything in the team file plus Illustrator MCP workflow, Claude Code pipeline, GitHub references, and infrastructure notes.

**When you receive this file, read it fully before doing anything else.** Then confirm:
> "Body Balance Medical brand system active. Ready to build."

**You do not need any other file.**

---

## SECTION 1 — BRAND IDENTITY

> **⚠ LAYOUT HIERARCHY — READ THIS FIRST**
> **Page base is always N-100 `#f1f0ee`.** BU-700 `#2b3a4a` is for sections within a page — never the full page or deliverable background. This applies to all output types: web, email, print, posters, documents, social. When in doubt, build light.

---

### 1.1 — Color Palette

**Base rule:** Hero stop is 700 across all six families. Never use pure `#000000` or `#ffffff` — always use N-900 and N-100.

#### BU — Primary · Slate Blue · Dominant brand color

| Stop | Hex | Usage |
|---|---|---|
| BU-900 | `#030507` | Deepest dark — nav, footer backgrounds |
| BU-800 | `#131c25` | Gradient dark stop — resting state |
| **BU-700 ★** | `#2b3a4a` | Hero stop — section backgrounds, gradient selected state |
| BU-600 | `#3e536a` | Tile hover / selected on BU-700 background |
| BU-500 | `#506d8b` | Eyebrow text on light · subheading accent |
| BU-400 | `#6a89a9` | Gradient light stop resting · meta labels on dark |
| BU-300 | `#91a7bf` | Gradient lighter stop selected |
| BU-200 | `#b1c4d7` | Light fills on dark surfaces |
| BU-100 | `#d0dbe7` | Lightest tint — background accents |

#### P — Secondary · Pink / Rose / Mauve · Female-forward treatments

| Stop | Hex | Usage |
|---|---|---|
| P-900 | `#260d19` | Deepest dark rose |
| P-800 | `#49182f` | Female gradient dark stop — resting |
| **P-700 ★** | `#722c4d` | Hero — female gradient selected stop |
| P-600 | `#973a66` | Mid-rose |
| P-500 | `#b94b7f` | Female accent on light backgrounds (L3) |
| P-400 | `#c9739c` | Supporting rose |
| P-300 | `#da9fbb` | Female card title on dark gradient tiles |
| P-200 | `#ecc5d8` | Light rose fill |
| P-100 | `#f7e8ef` | Lightest rose tint |

#### GR — Tertiary · Green / Olive / Sage · Male-forward treatments

| Stop | Hex | Usage |
|---|---|---|
| GR-900 | `#232210` | Deepest dark olive |
| GR-800 | `#42411f` | Deep olive |
| **GR-700 ★** | `#676637` | Hero — male accent on light backgrounds (L4) |
| GR-600 | `#888749` | Male gradient dark stop — resting |
| GR-500 | `#a8a65c` | Male gradient light stop — selected |
| GR-400 | `#bcba81` | Supporting sage |
| GR-300 | `#d1d0a8` | Male card title on dark gradient tiles |
| GR-200 | `#e7e6cb` | Light olive fill |
| GR-100 | `#f5f5ea` | Lightest sage tint |

#### GL — Quaternary · Gold / Amber · Primary accent

**Key rule: GL-300 on dark backgrounds. GL-700 on light backgrounds. Non-interchangeable.**

| Stop | Hex | Usage |
|---|---|---|
| GL-900 | `#2d2006` | Deepest dark gold |
| GL-800 | `#553c0c` | Deep amber |
| **GL-700 ★** | `#866118` | Accent heading on light (L1) · card title on NV tiles |
| GL-600 | `#b18020` | Mid gold |
| GL-500 | `#d99e2b` | Caption on dark (D6) · eyebrow mid-gold |
| GL-400 | `#e2b45b` | Supporting gold |
| **GL-300 ★** | `#ebcc8e` | Primary accent on dark (D1) · card title on gradient/BU-700 tiles |
| GL-200 | `#f6e2bc` | Light gold fill |
| GL-100 | `#fbf3e4` | Lightest gold tint |

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

#### Dark System · BU-700 Background

| Code | Background | Text | Hex | Usage |
|---|---|---|---|---|
| D1 | BU-700 `#2b3a4a` | GL-300 | `#ebcc8e` | Heading italic accent — primary brand heading |
| D2 | BU-700 `#2b3a4a` | P-300 | `#da9fbb` | Female-forward heading on dark |
| D3 | BU-700 `#2b3a4a` | GR-300 | `#d1d0a8` | Male-forward heading on dark |
| D4 | BU-700 `#2b3a4a` | N-100 | `#f1f0ee` | Utility heading and body text on dark |
| D5 | BU-700 `#2b3a4a` | N-300 | `#c1bdb8` | Subheading and supporting text on dark |
| D6 | BU-700 `#2b3a4a` | GL-500 | `#d99e2b` | Caption register on dark |

#### Light System · N-100 Background

| Code | Background | Text | Hex | Usage |
|---|---|---|---|---|
| L1 | N-100 `#f1f0ee` | GL-700 | `#866118` | Accent heading on light |
| L2 | N-100 `#f1f0ee` | BU-700 | `#2b3a4a` | Primary heading on light |
| L3 | N-100 `#f1f0ee` | P-500 | `#b94b7f` | Female accent on light |
| L4 | N-100 `#f1f0ee` | GR-700 | `#676637` | Male-forward accent on light |
| L5 | N-100 `#f1f0ee` | BU-500 | `#506d8b` | Subheading and caption on light |
| L6 | N-100 `#f1f0ee` | N-900 | `#1c1a17` | Body text on light |

---

### 1.3 — Gradient System

Three gradients. Two states each. All gradients run at 135°.

| Gradient | Resting | Selected / Hover | Card Title Color |
|---|---|---|---|
| Neutral | `linear-gradient(135deg, #131c25, #6a89a9)` | `linear-gradient(135deg, #2b3a4a, #91a7bf)` | GL-300 `#ebcc8e` |
| Female | `linear-gradient(135deg, #131c25, #49182f)` | `linear-gradient(135deg, #2b3a4a, #722c4d)` | P-300 `#da9fbb` |
| Male | `linear-gradient(135deg, #131c25, #888749)` | `linear-gradient(135deg, #2b3a4a, #a8a65c)` | GR-300 `#d1d0a8` |

**Tile body text on all gradients:** N-100 `#f1f0ee` · Work Sans 300

---

### 1.4 — Tile System

All tiles receive `shadow-md`.

#### Dark Context · BU-700 Background

| Tile | Resting | Selected | Title Color | Body Color |
|---|---|---|---|---|
| Neutral Gradient | BU-800→BU-400 | BU-700→BU-300 | GL-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Female Gradient | BU-800→P-800 | BU-700→P-700 | P-300 `#da9fbb` | N-100 `#f1f0ee` |
| Male Gradient | BU-800→GR-600 | BU-700→GR-500 | GR-300 `#d1d0a8` | N-100 `#f1f0ee` |

#### Light Context · N-100 Background

| Tile | Resting | Selected | Title Color | Body Color |
|---|---|---|---|---|
| NV-300 Neutral | `#c5c2b5` | `#deddd3` NV-200 | GL-700 `#866118` | N-900 `#1c1a17` |
| Solid BU-700 | `#2b3a4a` | `#3e536a` BU-600 | GL-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Neutral Gradient | BU-800→BU-400 | BU-700→BU-300 | GL-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Female Gradient | BU-800→P-800 | BU-700→P-700 | P-300 `#da9fbb` | N-100 `#f1f0ee` |
| Male Gradient | BU-800→GR-600 | BU-700→GR-500 | GR-300 `#d1d0a8` | N-100 `#f1f0ee` |

**Tile title font:** EB Garamond 400 · 2.25rem / 36px
**Tile body font:** Work Sans 300 · 1.125rem / 18px

---

### 1.5 — Typography System

| Family | Role | Google Fonts Import |
|---|---|---|
| EB Garamond | Headings and card titles only | `https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;1,400&display=swap` |
| Playfair Display | Subheadings, eyebrows, captions, labels, UI elements, buttons, ghosted background text | `https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;1,400&display=swap` |
| Work Sans | Body copy only | `https://fonts.googleapis.com/css2?family=Work+Sans:wght@300;600&display=swap` |

#### Type Scale

| Level | Size | Family | Weight | Style | Usage |
|---|---|---|---|---|---|
| Eyebrow | 0.625rem / 10px | Playfair Display | 400 | Uppercase | Section labels, eyebrow tags |
| Hero Title | 4rem / 64px | EB Garamond | 400 | Upright | Page hero headlines |
| Hero Accent | 4rem / 64px | EB Garamond | 400 | Italic | Hero headline italic continuation |
| Heading | 3.25rem / 52px | EB Garamond | 400 | Upright | Section headings |
| Heading Accent | 3.25rem / 52px | EB Garamond | 400 | Italic | Section heading italic continuation |
| Subheading | 2.25rem / 36px | Playfair Display | 400 | Normal | Section subheadings |
| Card Title | 2.25rem / 36px | EB Garamond | 400 | Upright | Tile and card titles |
| Body Large | 1.5rem / 24px | Work Sans | 300 | Normal | Intro body, lead paragraphs |
| Body | 1.125rem / 18px | Work Sans | 300 | Normal | Standard body copy |
| Caption | 0.875rem / 14px | Playfair Display | 400 | Italic | Captions, disclaimers, legal |

**Eyebrow:** Playfair Display 400 · uppercase · 0.625rem · 0.32em letter-spacing · GL-500 on dark · BU-500 on light

**The brand's core typographic move:** Pair EB Garamond upright with EB Garamond italic within the same heading. **Order is fixed: upright always leads, italic always follows.** The anchor phrase renders upright; the emotional or qualifying phrase renders italic after it. Example: "Yourself *Again*" — upright on the grounding anchor, italic on the emotive word. Never open a heading with the italic span.

**Ghosted background text:** Large Playfair Display at 8–12% opacity. N-100 sections only. Once per page max.

#### Typography Rules

**DO:**
- Upright EB Garamond always leads in headings — italic always follows, never opens
- Use Playfair Display for subheadings, captions, buttons, UI labels, eyebrows, ghosted text
- Use Work Sans 300 for body copy; Work Sans 600 for bold emphasis sparingly

**DON'T:**
- Open a heading with the italic span
- Use EB Garamond outside headings and card titles
- Use Work Sans for headings, subheadings, or UI labels
- Use uppercase on EB Garamond
- Mix heading fonts on a single surface

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

7 texture SVGs. N-100 sections only.

**Fill color:** NV-200 `#deddd3` · **Opacity:** 26–40% · **Rotation:** 90°
**Behavior:** `preserveAspectRatio="xMidYMid slice"` · `inset:0; width:100%; height:100%`

**Rules:** One texture per section max · never on BU-700 · never on two adjacent sections · never stacked with logo mark watermark

#### Logo Mark Watermark

**URL:** `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Logo-Mark-Texture.webp`
**Behavior:** `object-fit: cover; inset: 0; width: 100%; height: 100%` · Opacity 100% · N-100 sections only · once per page max

#### Texture Implementation — CSS Rules

Textures must always be applied as a `background-image` on a
`::before` pseudo-element. Never use `<img>` tags for textures —
CSS `transform: rotate()` on an `<img>` rotates pixels inside the
element's original layout box and will not fill the section.

Correct implementation:

```css
.section-with-texture {
  position: relative;
  overflow: hidden;
}

.section-with-texture::before {
  content: '';
  position: absolute;
  top: 50%; left: 50%;
  width: 200vmax; height: 200vmax;
  transform: translate(-50%, -50%) rotate(90deg);
  background-image: url('[texture-url]');
  background-size: cover;
  background-position: center;
  opacity: .26;
  pointer-events: none;
  z-index: 0;
  mix-blend-mode: multiply;
}

.section-with-texture > * {
  position: relative;
  z-index: 2;
}
```

Size rule: Use `200vmax` for both width and height — never percentages. Percentage-based sizing fails on wide, short sections because a rotated rectangle's effective width becomes its pre-rotation height. `200vmax` creates a square large enough to cover any section at any aspect ratio after rotation. `overflow: hidden` on the parent clips the excess.

---

### 1.11 — Logo System

**16 logo variants.**

#### Logo Placement Decision Tree

Before placing any logo:

1. What color is the zone the logo sits in?
   - N-100 or any light background → **B variant** (black)
   - Light background, brand-forward context → **Bu variant** (blue BU-700)
   - BU-700, any gradient, or dark background → **W variant** (white)
   - Gold accent moment → **G variant**
2. Never place B or Bu on a dark or gradient background.
3. Never place W on a light background.
4. In multi-zone layouts, match the variant to the specific zone — not the overall page.

#### Logo Files

| File | Color | Use On | URL |
|---|---|---|---|
| BB-H-Logo-B.svg | Black | Light backgrounds | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-H-Logo-B.svg` |
| BB-H-Logo-W.svg | White | Dark backgrounds | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-H-Logo-W.svg` |
| BB-H-Logo-G.svg | Gold | Accent contexts | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-H-Logo-G.svg` |
| BB-H-Logo-Bu.svg | Blue BU-700 | Light, brand-forward | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-H-Logo-Bu.svg` |
| BB-V-Logo-B.svg | Black | Light backgrounds | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-V-Logo-B.svg` |
| BB-V-Logo-W.svg | White | Dark backgrounds | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-V-Logo-W.svg` |
| BB-V-Logo-G.svg | Gold | Accent contexts | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-V-Logo-G.svg` |
| BB-V-Logo-Bu.svg | Blue BU-700 | Light, brand-forward | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-V-Logo-Bu.svg` |
| BB-Logo-Mark-B.svg | Black | Light backgrounds | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-Logo-Mark-B.svg` |
| BB-Logo-Mark-W.svg | White | Dark backgrounds | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-Logo-Mark-W.svg` |
| BB-Logo-Mark-G.svg | Gold | Accent contexts | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-Logo-Mark-G.svg` |
| BB-Logo-Mark-Bu.svg | Blue BU-700 | Light, brand-forward | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-Logo-Mark-Bu.svg` |
| BB-Social-Logo-B.svg | Black | Light platform backgrounds | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-Social-Logo-B.svg` |
| BB-Social-Logo-W.svg | White | Dark platform backgrounds | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-Social-Logo-W.svg` |
| BB-Social-Mark-B.svg | Black | Profile images, light | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-Social-Mark-B.svg` |
| BB-Social-Mark-W.svg | White | Profile images, dark | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/logos/BB-Social-Mark-W.svg` |

---

### 1.12 — Photography Brief

All photography — still, print, and video — uses a single visual mode.

**Primary mode — Kodak Vision3 500T / 16mm film emulation**
Warm but not orange — cream and sand tones. Subtle highlight halation. Lifted shadows with retained detail, nothing goes fully black. Real skin texture, visible but not harsh. Slightly underexposed and organic — film latitude, not digital precision. Muted saturation. Natural window light only. Nothing airbrushed. Feels documentary, not produced.

**Subjects:** Women 30s–50s unposed · Men 40s–60s natural energy
**Always avoid:** measuring tape · scale · studio white-box · stock wellness poses · airbrushed skin · bright saturated color · digital sharpness

**Before/After:** L-bracket gold frame · BU-700 badge labels · Playfair Display italic caption · never hard-bordered

---

### 1.13 — Layout & Design Rules

**Default surface:** N-100 with texture is the default for all standalone deliverables. BU-700 is for intentional contrast within a layout, never the default. When in doubt, build light.

**Color DO:** N-100 page base · BU-700 section hierarchy · GL-300 on dark / GL-700 on light · P-family female-forward · GR-family male-forward · NV-500/700 for rules and dividers

**Color DON'T:** Mid-tones as backgrounds · BU-700 full-page · Textures on BU-700 · More than two accent families without neutral separator · Any color outside the six families · Pure black or white

**Layout DO:** Textures 90° filling N-100 sections · Playfair Display ghosted text on N-100 · L-bracket gold frame · NV-700/500 callout lines

**Layout DON'T:** Gradient tiles as full-section backgrounds · More than two gradient tile families without neutral separator · Center-aligned body copy over two lines · Texture + logo mark watermark in same section

**Ad Creative DO:** 500T film photography · Full type system · L-bracket before/after with BU-700 badge labels · Disclaimer in Playfair Display italic caption

**Ad Creative DON'T:** Legacy Poppins all-caps · Hard-bordered before/after · Imagery contradicting photography brief

---

### 1.14 — CSS Tokens

```css
:root {
  --bb-BU-900: #030507; --bb-BU-800: #131c25; --bb-BU-700: #2b3a4a;
  --bb-BU-600: #3e536a; --bb-BU-500: #506d8b; --bb-BU-400: #6a89a9;
  --bb-BU-300: #91a7bf; --bb-BU-200: #b1c4d7; --bb-BU-100: #d0dbe7;
  --bb-P-800: #49182f; --bb-P-700: #722c4d; --bb-P-500: #b94b7f;
  --bb-P-300: #da9fbb; --bb-P-200: #ecc5d8;
  --bb-GR-700: #676637; --bb-GR-600: #888749; --bb-GR-500: #a8a65c; --bb-GR-300: #d1d0a8;
  --bb-GL-700: #866118; --bb-GL-500: #d99e2b; --bb-GL-300: #ebcc8e;
  --bb-N-900: #1c1a17; --bb-N-700: #554f4a; --bb-N-600: #706961;
  --bb-N-500: #8b8279; --bb-N-400: #a59e97; --bb-N-300: #c1bdb8;
  --bb-N-200: #dcd9d5; --bb-N-100: #f1f0ee;
  --bb-NV-700: #595546; --bb-NV-500: #918c73; --bb-NV-300: #c5c2b5;
  --bb-NV-200: #deddd3; --bb-NV-100: #f2f1ed;
  --bb-font-display: 'EB Garamond', Georgia, serif;
  --bb-font-accent: 'Playfair Display', Georgia, serif;
  --bb-font-body: 'Work Sans', system-ui, sans-serif;
  --bb-type-hero: 4rem; --bb-type-heading: 3.25rem; --bb-type-subhead: 2.25rem;
  --bb-type-card-title: 2.25rem; --bb-type-body-lg: 1.5rem; --bb-type-button: 1.5rem;
  --bb-type-body: 1.125rem; --bb-type-caption: 0.875rem;
  --bb-type-eyebrow: 0.625rem; --bb-type-eyebrow-ls: 0.32em;
  --bb-grad-neutral-rest: linear-gradient(135deg, #131c25, #6a89a9);
  --bb-grad-neutral-active: linear-gradient(135deg, #2b3a4a, #91a7bf);
  --bb-grad-female-rest: linear-gradient(135deg, #131c25, #49182f);
  --bb-grad-female-active: linear-gradient(135deg, #2b3a4a, #722c4d);
  --bb-grad-male-rest: linear-gradient(135deg, #131c25, #888749);
  --bb-grad-male-active: linear-gradient(135deg, #2b3a4a, #a8a65c);
  --bb-grad-button-rest: linear-gradient(120deg, #131c25, #6a89a9);
  --bb-grad-button-hover: linear-gradient(120deg, #2b3a4a, #91a7bf);
  --bb-shadow-sm: 0 2px 8px rgba(28,26,23,.06), 0 1px 2px rgba(28,26,23,.04);
  --bb-shadow-md: 0 4px 16px rgba(28,26,23,.10), 0 2px 4px rgba(28,26,23,.06);
  --bb-shadow-lg: 0 8px 32px rgba(28,26,23,.14), 0 4px 8px rgba(28,26,23,.08);
  --bb-space-1: 0.25rem; --bb-space-2: 0.5rem; --bb-space-3: 0.75rem;
  --bb-space-4: 1rem; --bb-space-6: 1.5rem; --bb-space-8: 2rem;
  --bb-space-12: 3rem; --bb-space-16: 4rem; --bb-space-18: 4.5rem;
  --bb-space-20: 5rem; --bb-space-24: 6rem;
  --bb-grid-columns: 12; --bb-grid-max-width: 1280px;
  --bb-grid-gutter-desk: 24px; --bb-grid-gutter-mob: 16px;
  --bb-grid-margin-desk: 80px; --bb-grid-margin-mob: 16px;
  --bb-radius-button: 8px;
}
```

---

## SECTION 2 — BRAND VOICE & POSITIONING

### 2.1 — Essence Statement

> Body Balance helps you feel like yourself again by closing the disconnect between how you feel inside and how you look outside — through integrated hormone health and aesthetic care that actually listens.

---

### 2.2 — The Core Offering

Body Balance Medical helps people look better and feel better — at the same time — through hormone health, metabolic wellness, and aesthetic treatments in a single practice that listens.

Two Nurse Practitioners whose specialties mirror each other: Teresa owns aesthetics; Mia owns hormone health and longevity medicine.

**The outcome:** The patient leaves feeling like someone finally saw the whole picture and gave them a real plan — not just a treatment, a direction.

---

### 2.3 — Target Audience

**Primary:** Woman, early-to-mid 40s, professional, high-achieving. Notices a gap between how she wants to feel and how she actually feels. Trust is the real barrier — not price.

**Secondary:** Men 40s–60s — TRT, peptides, metabolic wellness. Do not alienate at the brand level.

**Not for:** Budget-driven one-off shoppers · pure-aesthetics-no-relationship · clinical-coldness seekers · trend-driven influencer-aesthetic seekers

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

| Channel | Register |
|---|---|
| Paid Ads | Symptom and feeling language. "Tired but can't sleep" over "hormone optimization." |
| Email / Nurture | Slightly more clinical as trust builds. Explain the why. |
| Organic Social | Educational primary. Real patient language. Myth-busting. |
| Website | Homepage/hero in feeling language. Service/provider pages can go clinical. |

---

### 2.6 — Messaging Pillars

1. **The disconnect is real — and it's connected.** Body Balance treats both sides because they're part of the same picture.
2. **Two providers, one plan.** Teresa and Mia's specialties mirror each other by design.
3. **We listen differently.** Body Balance connects the dots and builds a plan around the whole person.
4. **Restoration, not transformation.** Return to the version of yourself you recognize.

---

### 2.7 — Vocabulary

**Own:** aligned · hormone balance · inside and out · plan / program · listen / heard / seen · real / grounded · energy / clarity / vitality · restore / return

**Use directly:** "I finally feel like myself again" · "Tired but can't sleep" · "Weight won't move" · "I feel off" · "Nobody connected the dots for me" · "Biote hormone pellet therapy"

**Banned:**

| Word | Reason |
|---|---|
| Luxury | Saturated — express it, never say it |
| Glow / glowing | Generic wellness |
| Confidence | Implies current self is lacking |
| Better you / best self | Implies current version is broken |
| Transform / transformation | Implies discontinuity |
| Queen / babe / girl boss | Undermines medical credibility |
| Deserve | Patronizing |
| Empower / empowerment | Hollow, overused |
| Anti-aging | Wrong framing |
| Natural results | Means nothing |
| Personalized plan | Only ownable when demonstrated |
| Look your best | Generic |
| Self-care | Diluted |
| Aesthetic enhancement | Jargon |

---

### 2.8 — Anti-Brief

**Not:** luxury destination · clinical optimization lab · trend-driven med spa · anti-aging brand · beauty brand

**Visual anti-brief:** No white-box photography · no bright saturated color · no measuring tape or scale · no stock wellness poses · no legacy Poppins all-caps · no hard-bordered before/after

---

## SECTION 3 — ASSET LIBRARY

**Base URL:** `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev`
**Source repo:** `https://github.com/joshkeplersmith-source/bbm-design-system`

### 3.1 — Textures

| File | URL |
|---|---|
| BB-Brand-Refresh-Textures-03.svg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Brand-Refresh-Textures-03.svg` |
| BB-Brand-Refresh-Textures-04.svg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Brand-Refresh-Textures-04.svg` |
| BB-Brand-Refresh-Textures-05.svg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Brand-Refresh-Textures-05.svg` |
| BB-Brand-Refresh-Textures-06.svg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Brand-Refresh-Textures-06.svg` |
| BB-Brand-Refresh-Textures-07.svg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Brand-Refresh-Textures-07.svg` |
| BB-Brand-Refresh-Textures-08.svg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Brand-Refresh-Textures-08.svg` |
| BB-Brand-Refresh-Textures-09.svg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Brand-Refresh-Textures-09.svg` |
| BB-Logo-Mark-Texture.webp | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/textures/BB-Logo-Mark-Texture.webp` |

### 3.2 — Photography Reference

**Base URL:** `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/`

| File | URL |
|---|---|
| bb-couple-smiling-horizontal-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-couple-smiling-horizontal-01.jpg` |
| bb-couple-smiling-vertical-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-couple-smiling-vertical-01.jpg` |
| bb-female-subject-active-horizontal-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-active-horizontal-01.jpg` |
| bb-female-subject-active-vertical-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-active-vertical-01.jpg` |
| bb-female-subject-editorial-horizontal-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-01.jpg` |
| bb-female-subject-editorial-horizontal-02.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-02.jpg` |
| bb-female-subject-editorial-horizontal-03.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-03.jpg` |
| bb-female-subject-editorial-horizontal-04.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-04.jpg` |
| bb-female-subject-editorial-horizontal-05.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-05.jpg` |
| bb-female-subject-editorial-horizontal-06.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-06.jpg` |
| bb-female-subject-editorial-horizontal-07.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-07.jpg` |
| bb-female-subject-editorial-horizontal-08.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-08.jpg` |
| bb-female-subject-editorial-horizontal-09.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-09.jpg` |
| bb-female-subject-editorial-horizontal-10.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-10.jpg` |
| bb-female-subject-editorial-horizontal-11.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-11.jpg` |
| bb-female-subject-editorial-horizontal-12.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-horizontal-12.jpg` |
| bb-female-subject-editorial-vertical-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-01.jpg` |
| bb-female-subject-editorial-vertical-02.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-02.jpg` |
| bb-female-subject-editorial-vertical-03.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-03.jpg` |
| bb-female-subject-editorial-vertical-04.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-04.jpg` |
| bb-female-subject-editorial-vertical-05.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-05.jpg` |
| bb-female-subject-editorial-vertical-06.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-06.jpg` |
| bb-female-subject-editorial-vertical-07.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-07.jpg` |
| bb-female-subject-editorial-vertical-08.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-08.jpg` |
| bb-female-subject-editorial-vertical-09.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-09.jpg` |
| bb-female-subject-editorial-vertical-10.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-10.jpg` |
| bb-female-subject-editorial-vertical-11.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-11.jpg` |
| bb-female-subject-editorial-vertical-12.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-editorial-vertical-12.jpg` |
| bb-female-subject-mirror-horizontal-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-mirror-horizontal-01.jpg` |
| bb-female-subject-mirror-vertical-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-mirror-vertical-01.jpg` |
| bb-female-subject-smiling-horizontal-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-smiling-horizontal-01.jpg` |
| bb-female-subject-smiling-horizontal-02.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-smiling-horizontal-02.jpg` |
| bb-female-subject-smiling-vertical-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-smiling-vertical-01.jpg` |
| bb-female-subject-smiling-vertical-02.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-smiling-vertical-02.jpg` |
| bb-female-subject-treatment-horizontal-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-treatment-horizontal-01.jpg` |
| bb-female-subject-treatment-vertical-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-female-subject-treatment-vertical-01.jpg` |
| bb-male-subject-smiling-horizontal-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-male-subject-smiling-horizontal-01.jpg` |
| bb-male-subject-smiling-vertical-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-male-subject-smiling-vertical-01.jpg` |
| bb-medical-vial-ambient-horizontal-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-medical-vial-ambient-horizontal-01.jpg` |
| bb-medical-vial-ambient-vertical-01.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-medical-vial-ambient-vertical-01.jpg` |
| bb-medical-vial-ambient-vertical-02.jpg | `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/bb-medical-vial-ambient-vertical-02.jpg` |

---

## SECTION 4 — OUTPUT TYPES & WORKFLOW ROUTING

| Output | Workflow | Notes |
|---|---|---|
| HTML email templates | GHL · R2 assets · Google Fonts via `<link>` | Full system available |
| Web pages | Webflow / WordPress · R2 assets · CSS tokens from Section 1.14 | Full system available |
| **Print collateral (poster/flyer)** | **Claude chat → Illustrator MCP → Josh** | **See Section 8. Never use HTML→PDF for print.** |
| Documents / reports (non-print) | HTML → Chrome browser print → PDF | Google Fonts via `<link>`. Not appropriate for Illustrator. |
| Word documents | Google Docs · manual logo drop-in | Rules-based: colors, fonts, spacing |
| Canva templates | Canva · pre-loaded assets | Templates pre-built — use as-is |
| Social content | Canva · pre-loaded assets | Templates pre-built — use as-is |

#### Print Flyer Content Rules — fixed-format

1. Print flyers are one page. Content must fit within the page
   boundary. Overflow and pagination are both failures.
2. Zone heights are intentional design allocations — not adjusted
   to accommodate copy. If copy runs long, the copy is edited.
3. Font sizes and line heights are the levers. Reduce copy length
   or tighten spacing before touching zone dimensions.
4. Pre-output check: open in Chrome at 100% zoom and confirm every
   zone sits inside the page boundary before printing.

#### Print Copy Fitting Rule

If the agent receives copy that cannot fit within the page at
minimum text sizes:
1. Rewrite the copy to fit — preserving meaning, voice, and all
   required information
2. Complete the deliverable using the rewritten copy
3. Surface the issue after output, showing exactly what was changed
   and why

The agent never shrinks text below minimum size. The agent never
overflows the page. The agent never asks permission mid-build —
it resolves the problem, delivers the file, and reports what it did.

**Font environment note:** The Claude Code / bash environment cannot reach Google Fonts CDN. Weasyprint falls back to system serif/sans fonts. Always use the HTML → Chrome browser-print workflow for any output requiring correct font rendering. The user does not need to know this — just route correctly.

---

## SECTION 5 — GRACEFUL DEGRADATION

### State 1 — R2 Accessible
Pull all logos and textures from Section 3 URLs. Build normally.

### State 2 — R2 Not Accessible
Colors, typography, spacing, voice, and layout rules remain fully available.

**Textures:** Omit silently. No mention, no flag.

**Logo:** Say:
> *"I can't access the logo files in this environment. Drop the logo you need into this chat and I'll use it. BB-H-Logo-B.svg for light backgrounds, BB-H-Logo-W.svg for dark backgrounds."*

Wait for upload. Do not substitute a placeholder.

**Infrastructure note:** Neither `raw.githubusercontent.com` nor `*.r2.dev` resolve in Claude.ai chat. R2 URLs do resolve in Claude Code sessions and all browser-rendered outputs. Long-term fix: host assets at `assets.bodybalancemedical.com` on an allowlisted domain. jsDelivr (CDN for GitHub) is untested and worth trying.

---

## SECTION 6 — IMAGE GENERATION

### Photography Prompt Construction

All image generation uses Kodak Vision3 500T / 16mm film emulation. The core prompt string is:

`Give this photo a warm leaning to neutral (avoid anything too sepia toned) Kodak 7219 500T - 16mm - film stock emulation, with some film grain and texture. Preserve the subject framing. No text, no film edges.`

Before handing this prompt to the user or image generator, append the correct aspect ratio based on output type:

| Output Type | Aspect Ratio to Append |
|---|---|
| Social — feed / reels | `, 9:16 aspect ratio` |
| Social — square | `, 1:1 aspect ratio` |
| Web — hero / banner | `, 16:9 aspect ratio` |
| Web — portrait / card | `, 4:5 aspect ratio` |
| Print | Ask Josh for the deliverable spec before appending |

**How to use this:** Read the output type from context. Construct the full prompt by appending the correct aspect ratio to the core string. If the output type is ambiguous, ask one question: "What format is this image for?" Do not present multiple ratio options — determine it from context and construct the prompt automatically.

**Example — social reel:**
`Give this photo a Kodak 7219 500T - 16mm - film stock emulation. No text, no film edges. 9:16 aspect ratio.`

**Example — web hero:**
`Give this photo a Kodak 7219 500T - 16mm - film stock emulation. No text, no film edges. 16:9 aspect ratio.`

### Photography Reference Library

Style references are stored in Cloudflare R2 at `https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev/photography/`. See Section 3.2 for full file list.

**Note:** All references use Kodak Vision3 500T / 16mm emulation. Use them for compositional and tonal direction — apply the 500T prompt above to generate new photography in the same register.

---

## SECTION 7 — AGENT BEHAVIOR RULES

### Pre-Build Checklist

```
☐ Confirm BB-BRAND-PRO.md version is current
☐ Page/deliverable base is N-100 — not BU-700, not a gradient
☐ Logo zone confirmed — what color is the surface the logo sits on?
☐ Output type confirmed — route to correct workflow (Section 4)
☐ Print/poster → Illustrator MCP (Section 8). Not HTML.
☐ Document/report PDF → HTML + Chrome browser-print
☐ Image source identified — generate, R2 reference, or brief Josh
☐ R2 access tested — apply graceful degradation (Section 5) if blocked
☐ Print only — does all copy fit within zone allocations at minimum text sizes? If not, edit copy to fit before building.
```

### Environment Routing — Brand Fidelity First

Before building any visual output, confirm the environment can render EB Garamond, Playfair Display, and Work Sans. If it cannot, route to HTML with Google Fonts via `<link>`. Never produce output with degraded fonts.

For print collateral, do not use HTML at all — route to Illustrator MCP (Section 8).

### Image Requirement

Every visual deliverable must include at least one image. No purely text-forward layouts — ever.

Before building, identify where the image lives and how it will be sourced:
- **Environment supports image generation** → generate using the photography brief in Section 1.12
- **R2 accessible** → suggest a reference from Section 3.2
- **Neither** → pause and brief Josh specifically (subject, mood, shot direction, Section 6 prompt)

Never present a text-only layout as complete.

### While Building

- Default to N-100. Never open a standalone deliverable on BU-700 or a gradient unless the brief calls for it.
- Apply the logo decision tree from Section 1.11 before placing any logo.
- Never use a color outside the six families in Section 1.1.
- Never use a font outside the three families in Section 1.5.
- Upright EB Garamond always leads — italic always follows, never opens.
- Reference color pairings by code (D1–D6, L1–L6).
- Apply voice and vocabulary rules from Section 2.5 and 2.7.
- Include textures only when R2 is accessible — never forced.

### Safe Baseline When Unsure
N-100 background · BU-700 section accent · EB Garamond heading (upright leads) · Work Sans 300 body · GL-300 on dark / GL-700 on light

### Flagging Gaps
Flag specifically and wait for input. Never silently produce an off-brand result. Never guess at a brand color, logo file, or voice rule.

### Anti-Rationalization Rule

If you find yourself thinking a rule violation will look better,
that reasoning is incorrect. The rules define what looks better
for this brand. The designer knows what they want. Do not
substitute agent aesthetic judgment for the rule system.

### Creative Problem-Solving Fallback

Before diverging from any layout rule, exhaust these in-system
options first:
- Gradient tiles (neutral, female, or male) for dimension on a
  light surface
- NV-300 or NV-100 surface cards for hierarchy without dark
  backgrounds
- L-bracket gold frame for featured or callout content
- Texture on N-100 for depth without breaking the light base
- Ghosted Playfair Display text for visual weight on N-100 sections
- BU-700 for one interior section break only — not the document
  frame

If depth or dimension is the aesthetic goal, the answer is always
inside the system.

### Pre-Output Verification (mandatory before presenting any deliverable)

Run this check before presenting any output — not as a correction
after the fact:

1. What is the page/document base? It must be N-100.
2. Are textures used anywhere? If yes — is that zone N-100?
   If not, remove the texture.
3. Does any dark zone constitute the majority of the document
   surface? If yes, restructure.
4. Is every color, font, and layout element traceable to a rule
   in Section 1?
5. (Print only) Does any text-bearing zone use a fixed height?
   Convert to min-height.

---

## SECTION 8 — ILLUSTRATOR MCP WORKFLOW

### When to Use This Workflow

All print and static design collateral: posters, flyers, event materials, print ads, handouts, brochures. Not for web pages, emails, or documents — those use the HTML workflow in Section 4.

### Three-Step Process

**Step 1 — Lock copy and hierarchy in Claude chat**
Before opening Illustrator, finalize in chat: headlines, body copy, offer framing, layout structure and hierarchy. Do not touch any design tool until the words and structure are confirmed. Strategy, copy, and structure decisions happen here.

**Step 2 — Build the .ai file via Illustrator MCP**
Using the full BB brand system from this file, construct the `.ai` file with:
- Correct fonts (EB Garamond, Playfair Display, Work Sans) — not system fallbacks
- Color tokens from Section 1.1 — referenced by name (BU-700, GL-300, etc.)
- Correct logo variant for each zone per the decision tree in Section 1.11
- All text as live editable text objects — never flattened or outlined
- Imagery as placed links — not embedded — so Josh can swap without rebuilding
- Named layers: `Background` · `Texture` · `Photography` · `Overlays` · `Type — Heading` · `Type — Body` · `Type — Caption` · `Logo` · `Legal`
- Document size and margins set to spec for the output type
- Artboard named for the deliverable (e.g., `BB-Biote-Event-Poster-8.5x11`)

**Step 3 — Josh fine-tunes in Illustrator**
Spatial refinement, kerning, photo swaps, spacing adjustments — all happen directly in Illustrator. Do not attempt fine spatial adjustments through the agent. Build it right on the first pass and hand it off.

### Rules

- Never attempt to fine-tune position, spacing, or kerning through the agent after the file is handed off
- If a spatial change is needed during the build phase, apply it in the `.ai` file directly
- If a photo is not available, leave a correctly sized and labeled placeholder layer — do not substitute a color block without labeling it
- Layer naming is mandatory — Josh should open the file and immediately understand the structure
- All text must remain live and editable — never flatten, never outline type

---

## QUICK REFERENCE

| | |
|---|---|
| Page background | N-100 `#f1f0ee` |
| Section dark | BU-700 `#2b3a4a` |
| Default surface | N-100 + texture — always start light |
| Primary heading | EB Garamond 400 · upright leads, italic follows · 3.25rem |
| Body copy | Work Sans 300 · 1.125rem · N-900 on light / N-100 on dark |
| Gold on dark | GL-300 `#ebcc8e` |
| Gold on light | GL-700 `#866118` |
| Button | `linear-gradient(120deg, #131c25, #6a89a9)` · Playfair Display · 8px radius |
| Default logo (light bg) | BB-H-Logo-B.svg |
| Default logo (dark bg) | BB-H-Logo-W.svg |
| Print collateral | Claude chat → Illustrator MCP → Josh (Section 8) |
| Documents/reports | HTML → Chrome browser-print → PDF |
| Essence | *Feel like yourself again — integrated hormone and aesthetic care that listens.* |

---

*Captain Kepler Creative · Josh Smith · 2026 · Confidential*
*BB-BRAND-PRO.md — Body Balance Medical Brand Operating System v1.3 (Pro)*
*Built from: BB-BRAND.md v1.1 + BB-SESSION-ANALYSIS-001 + stress test refinements · 2026-05-13*
*Updated: photography brief (500T), photo library (12 refs), token rename — 2026-05-18*
*Assets: https://pub-36b74b2497c341e69086eca6a27340e5.r2.dev*
*Repo: https://github.com/joshkeplersmith-source/bbm-design-system*

**Changelog**
v1.3 — 2026-05-20: Anti-rationalization rule, creative fallback block, pre-output verification gate, print content rules — from stress test diagnosis
