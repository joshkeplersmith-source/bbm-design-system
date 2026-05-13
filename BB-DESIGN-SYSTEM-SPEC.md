# BODY BALANCE MEDICAL — Design System Specification
**Captain Kepler Creative · Josh Smith · 2026**
**Version 1.0 — Stage 1 Output**
**Load alongside BB-BRAND.md in any agent session requiring visual or brand specs.**

---

## HOW TO USE THIS DOCUMENT

This is the canonical technical design system for Body Balance Medical. Every value in this document is locked and applies to all brand touchpoints — web, social, ads, print, and any AI-generated creative.

**For Claude Design:** Read this file at session start. Apply all tokens, pairings, and rules to every artifact generated. Do not override values without explicit instruction from Josh.

**For Claude Code:** Use this file to build or verify the `bb-design-system/` folder structure, `tokens.css`, and any component scaffolding.

**For all agents:** When generating copy, layouts, or creative, reference the pairing codes (D1–D6, L1–L6), the typography scale levels, and the Do/Don't rules. These are not suggestions — they are the system.

---

## 01 — COLOR PALETTE

**Base rule:** Hero stop is 700 across all six families. Never use pure `#000000` or `#ffffff` — always use N-900 and N-100.

---

### P — Primary · Slate Blue · Dominant brand color

| Stop | Hex | RGB | Usage |
|---|---|---|---|
| P-900 | `#030507` | rgb(3,5,7) | Deepest dark — nav, footer backgrounds |
| P-800 | `#131c25` | rgb(19,28,37) | Gradient dark stop — resting state |
| **P-700 ★** | `#2b3a4a` | rgb(43,58,74) | **Hero stop — section backgrounds, gradient selected state** |
| P-600 | `#3e536a` | rgb(62,83,106) | Tile hover / selected on P-700 background |
| P-500 | `#506d8b` | rgb(80,109,139) | Eyebrow text on light · subheading accent |
| P-400 | `#6a89a9` | rgb(106,137,169) | Gradient light stop resting · meta labels on dark |
| P-300 | `#91a7bf` | rgb(145,167,191) | Gradient lighter stop selected |
| P-200 | `#b1c4d7` | rgb(177,196,215) | Light fills on dark surfaces |
| P-100 | `#d0dbe7` | rgb(208,219,231) | Lightest tint — background accents |

---

### S — Secondary · Rose / Mauve · Female-forward treatments

| Stop | Hex | Usage |
|---|---|---|
| S-900 | `#260d19` | Deepest dark rose |
| S-800 | `#49182f` | Female gradient dark stop — resting |
| **S-700 ★** | `#722c4d` | **Hero — female gradient selected stop** |
| S-600 | `#973a66` | Mid-rose |
| S-500 | `#b94b7f` | Female accent on light backgrounds (L3) |
| S-400 | `#c9739c` | Supporting rose |
| S-300 | `#da9fbb` | Female card title on dark gradient tiles |
| S-200 | `#ecc5d8` | Light rose fill |
| S-100 | `#f7e8ef` | Lightest rose tint |

---

### T — Tertiary · Olive / Sage · Male-forward treatments

| Stop | Hex | Usage |
|---|---|---|
| T-900 | `#232210` | Deepest dark olive |
| T-800 | `#42411f` | Deep olive |
| **T-700 ★** | `#676637` | **Hero — male accent on light backgrounds (L4)** |
| T-600 | `#888749` | Male gradient dark stop — resting |
| T-500 | `#a8a65c` | Male gradient light stop — selected |
| T-400 | `#bcba81` | Supporting sage |
| T-300 | `#d1d0a8` | Male card title on dark gradient tiles |
| T-200 | `#e7e6cb` | Light olive fill |
| T-100 | `#f5f5ea` | Lightest sage tint |

---

### Q — Quaternary · Gold / Amber · Primary accent

**Key rule: Q-300 on dark backgrounds. Q-700 on light backgrounds. Non-interchangeable.**

| Stop | Hex | Usage |
|---|---|---|
| Q-900 | `#2d2006` | Deepest dark gold |
| Q-800 | `#553c0c` | Deep amber |
| **Q-700 ★** | `#866118` | **Accent heading on light (L1) · card title on NV tiles** |
| Q-600 | `#b18020` | Mid gold |
| Q-500 | `#d99e2b` | Caption on dark (D6) · eyebrow mid-gold |
| Q-400 | `#e2b45b` | Supporting gold |
| **Q-300 ★** | `#ebcc8e` | **Primary accent on dark (D1) · card title on gradient/P-700 tiles** |
| Q-200 | `#f6e2bc` | Light gold fill |
| Q-100 | `#fbf3e4` | Lightest gold tint |

---

### N — Neutral · Warm Greige · Brand Black N-900 · Brand White N-100

| Stop | Hex | Usage |
|---|---|---|
| **N-900** | `#1c1a17` | **Brand near-black — body text on light, icon fills** |
| N-800 | `#35302c` | Deep warm gray |
| N-700 | `#554f4a` | Dark warm gray |
| N-600 | `#706961` | Secondary body text on light |
| N-500 | `#8b8279` | Muted mid-tone |
| N-400 | `#a59e97` | Supporting neutral |
| N-300 | `#c1bdb8` | Subheading / supporting text on dark (D5) |
| N-200 | `#dcd9d5` | Borders, dividers, horizontal rules on light |
| **N-100 ★** | `#f1f0ee` | **Page background · body text on dark · brand near-white** |

---

### NV — Neutral Variant · Warm Tan · Layout, hierarchy, design support

| Stop | Hex | Usage |
|---|---|---|
| NV-900 | `#1d1c16` | Deepest warm tan |
| NV-800 | `#383529` | Deep tan |
| NV-700 | `#595546` | Section dividers · callout lines · underlines |
| NV-600 | `#75715c` | Supporting tan |
| NV-500 | `#918c73` | Secondary rules · callout lines |
| NV-400 | `#aaa692` | Supporting |
| NV-300 | `#c5c2b5` | Neutral tile background resting on N-100 |
| **NV-200 ★** | `#deddd3` | **Texture SVG fill color · NV tile hover state** |
| NV-100 | `#f2f1ed` | Spec boxes · code blocks · secondary surfaces |

---

## 02 — COLOR PAIRINGS

Every text element has a designated pairing code. Reference by code — never describe the color manually.

### Dark System · P-700 Background

| Code | Background | Text | Hex | Usage |
|---|---|---|---|---|
| D1 | P-700 `#2b3a4a` | Q-300 | `#ebcc8e` | Heading italic accent — primary brand heading |
| D2 | P-700 `#2b3a4a` | S-300 | `#da9fbb` | Female-forward heading on dark |
| D3 | P-700 `#2b3a4a` | T-300 | `#d1d0a8` | Male-forward heading on dark |
| D4 | P-700 `#2b3a4a` | N-100 | `#f1f0ee` | Utility heading and body text on dark |
| D5 | P-700 `#2b3a4a` | N-300 | `#c1bdb8` | Subheading and supporting text on dark |
| D6 | P-700 `#2b3a4a` | Q-500 | `#d99e2b` | Caption register on dark |

### Light System · N-100 Background

| Code | Background | Text | Hex | Usage |
|---|---|---|---|---|
| L1 | N-100 `#f1f0ee` | Q-700 | `#866118` | Accent heading on light |
| L2 | N-100 `#f1f0ee` | P-700 | `#2b3a4a` | Primary heading on light |
| L3 | N-100 `#f1f0ee` | S-500 | `#b94b7f` | Female accent on light |
| L4 | N-100 `#f1f0ee` | T-700 | `#676637` | Male-forward accent on light |
| L5 | N-100 `#f1f0ee` | P-500 | `#506d8b` | Subheading and caption on light |
| L6 | N-100 `#f1f0ee` | N-900 | `#1c1a17` | Body text on light |

---

## 03 — GRADIENT SYSTEM

Three gradients. Two states each. Resting = darker stop pair. Selected / hover = lighter stop pair. All gradients run at 135°.

| Gradient | Resting | Selected / Hover | Card Title Color |
|---|---|---|---|
| Neutral | `linear-gradient(135deg, #131c25, #6a89a9)` P-800→P-400 | `linear-gradient(135deg, #2b3a4a, #91a7bf)` P-700→P-300 | Q-300 `#ebcc8e` |
| Female | `linear-gradient(135deg, #131c25, #49182f)` P-800→S-800 | `linear-gradient(135deg, #2b3a4a, #722c4d)` P-700→S-700 | S-300 `#da9fbb` |
| Male | `linear-gradient(135deg, #131c25, #888749)` P-800→T-600 | `linear-gradient(135deg, #2b3a4a, #a8a65c)` P-700→T-500 | T-300 `#d1d0a8` |

**Tile body text on all gradients:** N-100 `#f1f0ee` · Work Sans 300

---

## 04 — TILE SYSTEM

All tiles receive `shadow-md`. Hover state transitions to selected gradient.

### Dark Context · P-700 Background
Gradient tiles only — 3 types. No solid P-700 tile in dark context.

| Tile | Resting | Selected | Title Color | Body Color |
|---|---|---|---|---|
| Neutral Gradient | P-800→P-400 | P-700→P-300 | Q-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Female Gradient | P-800→S-800 | P-700→S-700 | S-300 `#da9fbb` | N-100 `#f1f0ee` |
| Male Gradient | P-800→T-600 | P-700→T-500 | T-300 `#d1d0a8` | N-100 `#f1f0ee` |

**Important:** The dark tile context section itself sits on a P-700 background. The gradient tiles float above it.

### Light Context · N-100 Background
5 tile types available.

| Tile | Resting | Selected | Title Color | Body Color |
|---|---|---|---|---|
| NV-300 Neutral | `#c5c2b5` | `#deddd3` NV-200 | Q-700 `#866118` | N-900 `#1c1a17` |
| Solid P-700 | `#2b3a4a` | `#3e536a` P-600 | Q-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Neutral Gradient | P-800→P-400 | P-700→P-300 | Q-300 `#ebcc8e` | N-100 `#f1f0ee` |
| Female Gradient | P-800→S-800 | P-700→S-700 | S-300 `#da9fbb` | N-100 `#f1f0ee` |
| Male Gradient | P-800→T-600 | P-700→T-500 | T-300 `#d1d0a8` | N-100 `#f1f0ee` |

**Tile title font:** EB Garamond 400 · 2.25rem / 36px
**Tile body font:** Work Sans 300 · 0.68rem

---

## 05 — TYPOGRAPHY SCALE

**Base:** 16px = 1rem

### Font Families

| Role | Family | Weights Used | Google Fonts String | Fallback |
|---|---|---|---|---|
| Display / Headings | EB Garamond | 400, 400 italic | `EB+Garamond:ital,wght@0,400;1,400` | Georgia, serif |
| Accent / UI / Ghost text | Playfair Display | 400, 400 italic | `Playfair+Display:ital,wght@0,400;1,400` | Georgia, serif |
| Body | Work Sans | 300, 400, 500, 600 | `Work+Sans:wght@300;400;500;600` | system-ui, sans-serif |

**Note:** EB Garamond and Playfair Display are available only at weight 400 from Google Fonts. Elementor may display "300 Light" but the browser serves 400. Document weight as-set in Elementor; verify on live site.

---

### Type Scale — Complete Reference

| Level | Family | Weight | Style | rem | px | Letter Spacing | Line Height | Dark Pairing | Light Pairing |
|---|---|---|---|---|---|---|---|---|---|
| Hero Title | EB Garamond | 400 | Normal | 4rem | 64px | −0.05em | 1.5em | D4 · N-100 | L2 · P-700 |
| Hero Accent | EB Garamond | 400 | Italic | 4rem | 64px | — | 1.5em | D1 · Q-300 | L1 · Q-700 |
| Heading | EB Garamond | 400 | Normal | 3.25rem | 52px | −0.05em | 1.5em | D4 · N-100 | L2 · P-700 |
| Heading Accent | EB Garamond | 400 | Italic | 3.25rem | 52px | — | 1.5em | D1 · Q-300 | L1 · Q-700 |
| Subheading | Playfair Display | 400 | Normal | 2.25rem | 36px | 0 | 1.5em | D5 · N-300 | L5 · P-500 |
| Card Title (dark tile) | EB Garamond | 400 | Normal | 2.25rem | 36px | — | 1.5em | Q/S/T-300 | Q-700 on NV tile |
| Body Large | Work Sans | 300 | Normal | 1.5rem | 24px | 0 | 1.25em | D4 · N-100 | L6 · N-900 |
| Button / Label | Playfair Display | 400 | Normal | 1.5rem | 24px | — | 1.5em | N-100 | N-100 |
| Body | Work Sans | 300 | Normal | 1.125rem | 18px | 0 | 1.25em | D4 · N-100 | L6 · N-900 |
| Caption | Playfair Display | 400 | Normal | 0.875rem | 14px | 0 | 1.25em | D6 · Q-500 | L5 · P-500 |

---

### Eyebrow / Section Label

Used for section labels, metadata, and all-caps UI labels throughout.

- **Font:** Work Sans 600
- **Size:** 0.56rem / ~9px
- **Letter spacing:** 0.32em
- **Transform:** uppercase
- **Dark background color:** Q-500 `#d99e2b`
- **Light background color:** P-500 `#506d8b`

---

### Ghosted Background Text Technique

Used on N-100 sections only to add depth and visual rhythm.

- **Font:** Playfair Display 400 italic
- **Size:** Large — 8rem and above, or scaled to fill section width
- **Color:** NV-200 `#deddd3`
- **Position:** `position: absolute` behind all content · `z-index: 0` · content at `z-index: 1`
- **Words:** "Natural," "Restored," "Vitality," "Youth," "Balance," "Renewed"
- **Rule:** N-100 sections only. Never on P-700. Never combined with a texture SVG in the same section.

---

### Typography Usage Rules

- EB Garamond: headings and card titles **only**. Never for body copy, ghosted text, or UI labels.
- Playfair Display: subheadings, captions, button labels, UI labels, ghosted background text.
- Work Sans 300: all body copy. Bold (Work Sans 600) permitted within body copy for emphasis only — never as a heading substitute.
- Uppercase: never apply to EB Garamond. Destroys the letterform.
- Eyebrow/section labels: always Work Sans 600 uppercase. Never Playfair Display or EB Garamond for these.
- Do not mix heading fonts on a single surface (no EB Garamond + Playfair Display headings together).

---

## 06 — SPACING SCALE

Base: 16px = 1rem. Use rem for all vertical rhythm and layout. Use px only for component-internal gaps.

| Token | rem | px | Usage |
|---|---|---|---|
| space-1 | 0.25rem | 4px | Fine gaps · icon internal padding |
| space-2 | 0.5rem | 8px | Inline element gaps · tight component spacing |
| space-3 | 0.75rem | 12px | Compact padding · badge padding |
| space-4 | 1rem | 16px | Default unit · mobile gutters · mobile page margin |
| space-6 | 1.5rem | 24px | Column gutters · card inner gaps |
| space-8 | 2rem | 32px | Section sub-spacing · component vertical rhythm |
| space-12 | 3rem | 48px | Section padding tight |
| space-16 | 4rem | 64px | Section padding standard |
| space-18 | 4.5rem | 72px | Section padding large |
| space-20 | 5rem | 80px | Section horizontal padding · desktop page margin |
| space-24 | 6rem | 96px | Hero padding · masthead vertical rhythm |

---

## 07 — GRID SYSTEM

| Property | Value | Token |
|---|---|---|
| Columns | 12 | — |
| Max width | 1280px | — |
| Gutter — desktop | 24px | space-6 |
| Gutter — mobile | 16px | space-4 |
| Page margin — desktop | 80px | space-20 |
| Page margin — mobile | 16px | space-4 |

Applied in Elementor and Webflow. Page horizontal padding is space-20 on desktop, space-4 on mobile.

---

## 08 — LOGO RULES

All logo files are SVG. Four color suffix codes apply across all four families. Never alter, recolor, or apply effects outside the approved variants.

### Color Variant Codes

| Suffix | Color | Hex | Use On |
|---|---|---|---|
| -B | Near-black | `#1c1a17` · N-900 | N-100, NV-100, NV-300 light backgrounds |
| -Bu | Slate blue | `#2b3a4a` · P-700 | N-100, NV-100 — primary light version |
| -G | Gold | `#ebcc8e` · Q-300 | P-700, P-800, P-900, gradient, photo dark backgrounds |
| -W | Near-white | `#f1f0ee` · N-100 | P-700, P-800, P-900, gradient, photo dark backgrounds |

### Full Inventory — 16 Files

| File | Family | Dimensions | Primary Use |
|---|---|---|---|
| `BB-H-Logo-B.svg` | Horizontal Lockup | Flexible width | Light background primary |
| `BB-H-Logo-Bu.svg` | Horizontal Lockup | Flexible width | Light background — brand blue version |
| `BB-H-Logo-G.svg` | Horizontal Lockup | Flexible width | Dark background — hero / accent moments |
| `BB-H-Logo-W.svg` | Horizontal Lockup | Flexible width | Dark background primary |
| `BB-V-Logo-B.svg` | Vertical Lockup | Flexible width | Constrained width · light background |
| `BB-V-Logo-Bu.svg` | Vertical Lockup | Flexible width | Constrained width · light background |
| `BB-V-Logo-G.svg` | Vertical Lockup | Flexible width | Constrained width · dark background |
| `BB-V-Logo-W.svg` | Vertical Lockup | Flexible width | Constrained width · dark background |
| `BB-Logo-Mark-B.svg` | Mark Only | 600 × 600 | Social avatar · favicon · tight spaces · light bg |
| `BB-Logo-Mark-Bu.svg` | Mark Only | 600 × 600 | Social avatar · tight spaces · light bg |
| `BB-Logo-Mark-G.svg` | Mark Only | 600 × 600 | Social avatar · dark bg |
| `BB-Logo-Mark-W.svg` | Mark Only | 600 × 600 | Social avatar · dark bg |
| `BB-Social-Logo-B.svg` | Social Lockup | 600 × 600 | Social profile · square format · light bg |
| `BB-Social-Logo-W.svg` | Social Lockup | 600 × 600 | Social profile · square format · dark bg |
| `BB-Social-Mark-B.svg` | Social Mark | 600 × 600 | Social icon · profile picture · light bg |
| `BB-Social-Mark-W.svg` | Social Mark | 600 × 600 | Social icon · profile picture · dark bg |

### Minimum Sizes

| Variant | Minimum Width | Rationale |
|---|---|---|
| H-Logo | 120px | Wordmark must not render below ~11px (≈ 8pt at 96dpi) |
| V-Logo | 80px | Wordmark must not render below ~11px |
| Logo Mark | 32px | Mark remains legible at this size |
| Social Logo / Mark | 32px | Square-format minimum use |

**Clearspace:** Maintain clearspace equal to the cap height of the "b" mark on all four sides. No text, graphics, or other elements within this zone.

### Logo Mark Texture Watermark

File: `BB_Logo_Mark_Texture.png`

The logo mark PNG (black background, cream "b" strokes with paper grain texture) is used as a large-scale section watermark. Deployment:

- Invert the image before use on N-100 backgrounds (cream strokes become dark, black background becomes white)
- Apply `mix-blend-mode: multiply` — white background drops out, dark "b" mark reads through
- `position: absolute` · centered in section · `width: 50–55%` of section width
- **Opacity: 5–10%** — reads as atmosphere, not graphic element
- **One per page maximum**
- N-100 sections only
- Never stack with a texture SVG in the same section

---

## 09 — BUTTON SYSTEM

One button style applied system-wide. Works on both dark and light backgrounds.

| Property | Resting | Hover |
|---|---|---|
| Background | `linear-gradient(120deg, #131c25, #6a89a9)` P-800→P-400 | `linear-gradient(120deg, #2b3a4a, #91a7bf)` P-700→P-300 |
| Text color | `#f1f0ee` N-100 | `#f1f0ee` N-100 |
| Font | Playfair Display 400 · 1.5rem / 24px | — |
| Padding | 16px 40px | — |
| Border-radius | 8px | — |
| Border | None | — |

---

## 10 — SHADOW SYSTEM

All shadows use N-900 at low opacity — warm, never cold or blue-tinted. Shadow-md is the system default for all tiles and cards.

| Level | CSS Value | Usage |
|---|---|---|
| sm | `0 2px 8px rgba(28,26,23,.06), 0 1px 2px rgba(28,26,23,.04)` | Hover states on interactive elements. Cards in close proximity. |
| **md** | `0 4px 16px rgba(28,26,23,.10), 0 2px 4px rgba(28,26,23,.06)` | **Default for all tiles and content cards. Applied system-wide.** |
| lg | `0 8px 32px rgba(28,26,23,.14), 0 4px 8px rgba(28,26,23,.08)` | Modals, popovers, floating CTAs, hero card overlays. |

---

## 11 — TEXTURE SYSTEM

Two texture tools. Used occasionally to break up long N-100 pages — not applied to every section.

### Section Background SVGs — 7 Files

All files: fill `NV-200 #deddd3` · viewBox `0 0 1920 3240`

| File | Character | Opacity Range |
|---|---|---|
| `BB_Brand_Refresh_Textures-03.svg` | Flowing ribbon wave | 14–18% |
| `BB_Brand_Refresh_Textures-04.svg` | Scattered organic blobs | 16–20% |
| `BB_Brand_Refresh_Textures-05.svg` | Complex botanical | 14–18% |
| `BB_Brand_Refresh_Textures-06.svg` | Organic cluster forms | 16–20% |
| `BB_Brand_Refresh_Textures-07.svg` | Full-page flowing path | 12–16% |
| `BB_Brand_Refresh_Textures-08.svg` | Horizontal wave | 18–24% |
| `BB_Brand_Refresh_Textures-09.svg` | Large spiral + organics | 14–18% |

**Deployment rules:**
- Rotate 90° when placing as a section background — tall portrait format reads as landscape when rotated
- CSS: `position: absolute; inset: 0; width: 100%; height: 100%`
- SVG attribute: `viewBox="0 0 3240 1920" preserveAspectRatio="xMidYMid slice"`
- Transform to rotate paths: `matrix(0,1,-1,0,3240,0)` applied to the path group
- N-100 sections only — **never on P-700**
- One texture per section maximum
- Never apply to two adjacent sections — always skip at least one clean section between
- Never stack a texture SVG and the logo mark watermark in the same section

### Logo Mark Watermark

File: `BB_Logo_Mark_Texture.png` — see Section 08 for deployment rules.

---

## 12 — PHOTOGRAPHY BRIEF

### Primary Mode — Black & White

**Generative AI prompt (Firefly / Claude Design):**
> "Real woman in her late 30s to mid 40s, unposed and natural, visible skin texture, no smoothing. Soft natural window light, slightly warm with film grain simulation. Intimate quiet moment — at ease, not performing. Warm cream or soft gray setting, no studio backdrop. Cinematic, slightly underexposed, slow. Black and white. No makeup artists, no influencer poses, no clinical elements."

| Attribute | Specification |
|---|---|
| Subjects | Real women late 30s–mid 40s. Diverse. No heavy makeup or styled hair. Skin texture and fine lines are intentional. |
| Men | 40s–60s. Natural energy and genuine strength. Real smile, real body. Not performative. |
| Couples / Groups | Sparingly — TRT and wellness angles only. Natural interaction, not posed. |
| Lighting | Soft natural window light or golden hour. Warm and directional with shadow presence. No flat fill. |
| Editing | Film simulation or film-forward digital. Warm grain. Lifted shadows. Soft restrained contrast. |
| Mood | Exhale. Quiet relief. Coming back to yourself. Unhurried. Real. |
| Composition | Close-medium framing. Intimate. Environmental context visible but secondary. |

### Secondary Mode — Kodak Portra 400 Color

| Attribute | Specification |
|---|---|
| Film reference | Kodak Portra 400 — warm tones, fine grain, lifted blacks, natural skin rendering |
| Lighting | Natural or practical light. Warm and directional. No harsh flash. |
| Color in frame | Warm neutrals — cream, linen, warm gray, muted earth. Nothing competing with subject. |
| Grain | Visible but refined — Portra-level grain, not heavy noise |
| Skin tones | Warm and natural. No artificial brightening or smoothing. |

### Approved Reference Images

| Image | Tier | Notes |
|---|---|---|
| AdobeStock_448721416.jpg (woman, hands on face) | Tier 1 · Primary Reference | Defines the BB photography voice. Intimate, skin texture visible, quiet and unposed. |
| AdobeStock_436559124.jpg (woman at mirror) | Tier 1 · Primary Reference | Right age, mirror moment, unperformed, environmental context. Equally strong. |
| AdobeStock_895842891.jpg (woman, fist raised) | Tier 2 · Selective Use | Confident and contained. Not forced. Female wellness and weight loss content. |
| AdobeStock_605986661.jpg (man, genuine smile/strength) | Tier 2 · Selective Use | Natural energy and genuine happiness. TRT and wellness content. |
| AdobeStock_293083555.jpg (couple running) | Tier 3 · Sparingly | Right energy but activity framing reads more fitness than medspa. TRT/wellness only. |

### Anti-Brief — Never Generate or Select

| # | Rule |
|---|---|
| 1 | **Measuring tape, scale, or body-measurement props** — the canonical anti-brief image (AdobeStock_478793348.jpg) |
| 2 | Flat-lit harsh studio or clinical procedure lighting |
| 3 | Airbrushed or overly perfected skin |
| 4 | Heavy makeup, false lashes, or highly styled hair |
| 5 | White-box clinical environments, stethoscopes, lab coats, medical equipment in frame |
| 6 | Aspirational "it girl" or influencer-coded poses |
| 7 | Bright saturated color palettes |
| 8 | Overly aggressive flexing or forced performative energy |
| 9 | Stock wellness archetypes — jumping, arms spread, forced smile |

### Before / After Guidelines

Before/after framing is permitted where clinically appropriate. Use the L-bracket gold accent frame as the structural device — not hard-bordered stock-style BEFORE/AFTER blocks. Label badges: P-700 background · N-100 text · Playfair Display 400.

---

## 13 — DO / DON'T RULES

### Logo

**DO:**
- Use Logo-W on P-700, gradient, or photo backgrounds
- Use Logo-Bu on N-100 or NV backgrounds — preferred light version
- Use Logo-G sparingly on dark hero moments only
- Maintain clearspace equal to the cap height of the "b" mark on all sides
- Observe minimum sizes: H-Logo 120px · V-Logo 80px · Mark 32px
- Use mark alone only for social avatars and tight spaces where the full lockup doesn't fit

**DON'T:**
- Place logo on any mid-tone background without sufficient contrast
- Apply color, shadow, stroke, or any effect not in the approved four variants
- Scale below minimum sizes — wordmark must never render below ~11px
- Crop, rotate, or distort the logo
- Place on a busy photographic background without sufficient contrast

---

### Color

**DO:**
- Anchor every page with N-100 as the base page background
- Use P-700 for section-level hierarchy — section and tile level only, not full-page
- Use texture SVGs (NV-200) occasionally to add depth to N-100 sections
- Use Q-300 on dark and Q-700 on light — non-interchangeable
- Use S-family for female-forward, T-family for male-forward — intentionally, not decoratively
- Use NV-500 and NV-700 for all dividers, rules, underlines, and callout lines

**DON'T:**
- Use mid-tones (any 300–600 stop from any family) as section or page backgrounds
- Use P-700 as a full-page background — sections and tiles only
- Use texture SVGs on P-700 backgrounds — N-100 sections only
- Use more than two accent families on a single surface without a neutral separator
- Introduce any color outside the six locked families
- Use pure `#000000` or `#ffffff` — always use N-900 and N-100

---

### Typography

**DO:**
- Pair EB Garamond upright with EB Garamond italic in headings — the brand's core typographic move
- Use Playfair Display for subheadings, captions, button labels, UI labels, section labels, and ghosted background text
- Use the Playfair Display ghosted text technique on N-100 sections only
- Use Work Sans 300 for all body copy
- Bold Work Sans within body copy for emphasis only — sparingly

**DON'T:**
- Use EB Garamond for body copy, ghosted backgrounds, or anything outside headings and card titles
- Use Work Sans for headings or subheadings
- Use bold as a subheading substitute — give it a proper heading level
- Use uppercase on EB Garamond
- Mix heading fonts on a single surface
- Use Playfair Display or EB Garamond for eyebrow labels — those use Work Sans 600 uppercase

---

### Photography

**DO:**
- Use black and white as the primary brand photography mode
- Use Kodak Portra 400 color as the secondary mode
- Prioritize real women in their 30s–40s — unposed, skin texture visible
- Include men 40s–60s for TRT and wellness — natural energy, genuine happiness
- Allow environmental context as long as the subject is primary
- Use before/after framing where clinically appropriate — with L-bracket frame treatment

**DON'T:**
- Use measuring tape, scale, or body-measurement props
- Use flat studio white-box lighting for brand photography
- Airbrush or smooth skin — authenticity is intentional
- Use stock wellness poses — jumping, arms spread, forced smile
- Use hard-bordered BEFORE/AFTER blocks with old typography
- Use bright saturated color palettes

---

### Layout

**DO:**
- Use texture SVGs rotated 90° filling the full section — N-100 only, one per section, not in adjacent sections
- Use the logo mark PNG as a large centered watermark — 5–10% opacity, `mix-blend-mode: multiply`, once per page maximum
- Use Playfair Display ghosted background text on N-100 sections
- Use the L-bracket gold frame for before/after and featured content panels
- Annotate product and service features with callout lines in NV-700 or NV-500
- Use NV-500 and NV-700 for all section dividers, rules, and underlines

**DON'T:**
- Use gradient tiles as full-section or full-page backgrounds — component level only
- Use texture SVGs on P-700 backgrounds
- Stack more than two different gradient tile families without a neutral tile between them
- Center-align body copy over two lines — left-aligned only
- Apply a texture to two adjacent sections
- Stack a texture SVG and the logo mark watermark in the same section

---

### Ad Creative

**DO:**
- Carry B&W photography into performance ads — the brand's most distinctive visual move
- Apply the new type system (EB Garamond + Playfair Display + Work Sans) to all new ad production
- Use the before/after L-bracket treatment with P-700 badge labels on result-based ads
- Keep legal/disclaimer copy in Playfair Display 400 at caption size, bottom of frame
- Use B&W annotated photography with NV-700/NV-500 callout lines as a primary ad layout

**DON'T:**
- Use the legacy Poppins all-caps type system in any new ad production
- Use hard-bordered BEFORE/AFTER stock blocks with old typography
- Use imagery that contradicts the photography brief

---

## APPENDIX — CSS TOKENS REFERENCE

For `tokens.css` in the `bb-design-system/` folder:

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
  --bb-type-hero-size:        4rem;
  --bb-type-heading-size:     3.25rem;
  --bb-type-subhead-size:     2.25rem;
  --bb-type-card-title-size:  2.25rem;
  --bb-type-body-lg-size:     1.5rem;
  --bb-type-button-size:      1.5rem;
  --bb-type-body-size:        1.125rem;
  --bb-type-caption-size:     0.875rem;
  --bb-type-eyebrow-size:     0.56rem;
  --bb-type-eyebrow-spacing:  0.32em;

  /* GRADIENTS */
  --bb-grad-neutral-rest:    linear-gradient(135deg, #131c25, #6a89a9);
  --bb-grad-neutral-active:  linear-gradient(135deg, #2b3a4a, #91a7bf);
  --bb-grad-female-rest:     linear-gradient(135deg, #131c25, #49182f);
  --bb-grad-female-active:   linear-gradient(135deg, #2b3a4a, #722c4d);
  --bb-grad-male-rest:       linear-gradient(135deg, #131c25, #888749);
  --bb-grad-male-active:     linear-gradient(135deg, #2b3a4a, #a8a65c);
  --bb-grad-button-rest:     linear-gradient(120deg, #131c25, #6a89a9);
  --bb-grad-button-hover:    linear-gradient(120deg, #2b3a4a, #91a7bf);

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
  --bb-grid-columns:    12;
  --bb-grid-max-width:  1280px;
  --bb-grid-gutter-desktop: 24px;
  --bb-grid-gutter-mobile:  16px;
  --bb-grid-margin-desktop: 80px;
  --bb-grid-margin-mobile:  16px;

  /* BORDER RADIUS */
  --bb-radius-button: 8px;
}
```

---

*Captain Kepler Creative · Josh Smith · 2026 · Confidential*
*BB-DESIGN-SYSTEM-SPEC.md — Load alongside BB-BRAND.md*
