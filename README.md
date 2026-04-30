# REMAX Advantage Realty — Design System

**Agent:** Jason Froude  
**Brokerage:** REMAX Advantage Realty Ltd., Brokerage  
**Market:** Residential and Commercial Real Estate  
**Brand:** RE/MAX (2025 Brand Evolution)

---

## Sources

| Resource | Path / Location |
|---|---|
| 2025 Brand Standards PDF | `uploads/New Brand_logo_standards_2025.pdf` |
| Logo assets (PNG) | `uploads/` → copied to `assets/` |
| Font files | `uploads/*.otf, *.ttf` → copied to `fonts/` |
| Brand shapes (AI) | `uploads/Remax_25_VIS_ID_Filled_Outlined_Shapes.ai` |

---

## Company & Product Context

RE/MAX Advantage Realty is a franchise brokerage operating under the global RE/MAX brand. Jason Froude is a residential and commercial agent. The design system serves:

1. **Agent marketing** — listing presentations, property flyers, social media cards, email signatures, business cards
2. **Digital presence** — website/landing pages, email campaigns
3. **Signage & print** — exterior and interior office/property signage

The brand underwent a **2025 evolution** — modernizing the logo, introducing the "Dynamic Slash" motif and a refreshed four-quadrant Balloon mark — while preserving the iconic red/white/blue/navy colour heritage.

---

## File Index

```
README.md                             ← This file (start here)
SKILL.md                              ← Agent skill descriptor for Claude Code
colors_and_type.css                   ← CSS tokens: colors, type scale, spacing, radius, shadow

assets/
  Balloon_Mark_RGB.png                ← Four-colour Balloon mark (flat)
  Balloon_Mark_3D.png                 ← Three-dimensional Balloon render
  REMAX_logo_RGB_dark.png             ← Primary logotype — black
  REMAX_logo_RGB_cream.png            ← Primary logotype — cream (reversed)
  REMAX_wordmark_RGB_dark.png         ← Wordmark only — black
  REMAX_wordmark_RGB_light.png        ← Wordmark only — cream
  slash.png                           ← Dynamic Slash graphic — navy

fonts/
  Gotham-Black.otf                    ← 900 weight
  Gotham-Bold.otf                     ← 700 weight
  Gotham-BoldItalic.otf
  Gotham-Medium.otf                   ← 500 weight
  Gotham-Book.otf                     ← 400 weight (body)
  Gotham-BookItalic.otf
  Gotham-Light.otf                    ← 300 weight (legal)
  AkzidenzGrotesk-BoldItalic.otf      ← Secondary face
  AkzidenzGrotesk-MediumItalic.otf
  Arial.ttf / Arial-Bold.ttf / Arial-Italic.ttf  ← System fallback

preview/                              ← Design system cards (visible in DS tab)
  colors-primary.html                 ← 6 brand colors
  colors-neutrals.html                ← Neutral scale 50–900
  colors-semantic.html                ← Semantic CSS token roles
  type-families.html                  ← Gotham weight specimens
  type-display.html                   ← Display → H4 scale
  type-body.html                      ← Body, label, caption, legal
  spacing-scale.html                  ← 4px base spacing ramp
  spacing-shadows-radius.html         ← Shadow system + radius tokens
  brand-logos.html                    ← Logo system light backgrounds
  brand-dark-usage.html               ← Logo system dark backgrounds
  components-buttons.html             ← Button variants
  components-cards.html               ← Listing card + agent card
  components-forms-badges.html        ← Form inputs + badge variants

ui_kits/
  agent_marketing/
    index.html                        ← Interactive agent website prototype
    styles.css                        ← Shared component styles
```

### UI Kits
| Kit | Description | Path |
|---|---|---|
| Agent Marketing | Full website prototype — Home, Listings, About, Contact | `ui_kits/agent_marketing/index.html` |

---

## CONTENT FUNDAMENTALS

### Voice & Tone
- **Professional confidence** — authoritative but approachable; never boastful
- **Achievement-forward** — RE/MAX leads with market leadership claims ("nobody sells more real estate than REMAX")
- **Concise & direct** — short sentences, clear CTAs. No fluff
- **First-person warmth** — agents write as "I" / speak as "we" (office). Client is "you"
- **No emoji** — the brand does not use emoji in formal communications
- **No exclamation spam** — one exclamation point maximum per communication

### Casing
- **Brand name:** "REMAX" (no slash in text references as of 2025 evolution; slash is visual only)
- **Headlines:** ALL CAPS or Title Case depending on context; never sentence case for display
- **Body copy:** sentence case
- **CTAs / labels:** ALL CAPS, tracked wide (e.g. LEARN MORE, CONTACT US)

### Legal Line
All materials must include: *Each Office Independently Owned and Operated.*

### Example Copy (from brand guide)
> "Thank you for reaching out to REMAX Professionals to help you with buying your new home! As you may know, nobody in the world sells more real estate than REMAX, as measured by residential transaction sides."

---

## VISUAL FOUNDATIONS

### Colors
Six official brand colors (2025 palette):

| Name | Hex | Use |
|---|---|---|
| Primary Red | `#FF1200` | CTA, accents, Balloon top-right |
| Primary Blue | `#0043FF` | Supporting accent, Balloon bottom-right |
| Dark Red | `#660000` | Balloon top-left, dark backgrounds |
| Dark Navy | `#000E35` | Primary dark bg, text on light |
| Cream | `#F7F5EE` | Primary light bg, reversed text |
| Black | `#000000` | Primary text, secondary logotype |

Neutrals are derived from the cream base, desaturated toward gray.

### Typography
- **Primary face:** Gotham (Black 900, Bold 700, Medium 500, Book 400, Light 300)
- **Secondary face:** Berthold Akzidenz Grotesk (Bold Italic, Medium Italic — supporting role)
- **Fallback:** Arial (system-safe alternative, permitted by brand guide)
- Display headlines: Gotham Black, ALL CAPS, tight tracking
- Body: Gotham Book, normal tracking, 1.5 leading

### Logo System
1. **Primary Brand Logotype** — Balloon mark + REMAX wordmark (use on most applications)
2. **Secondary Logotype** — REMAX wordmark only (single color / BW contexts)
3. **Dynamic Logo** — Wordmark with open "Dynamic Area" between RE and MAX for agent photo or image
4. **Balloon Mark** — Standalone only in social profile avatars or HQ templates

Logo colours: wordmark letters are **black or cream only**. Balloon must appear in full four-colour.

### Motifs & Shapes
- **Dynamic Slash** — diagonal navy parallelogram; the "/" between RE and MAX, also a standalone graphic element
- **Balloon Mark** — four-quadrant heart-shaped location pin: Dark Red (top-left), Red (top-right), Cream (middle band), Dark Navy (bottom-left), Blue (bottom-right)
- No custom SVG shapes beyond provided assets; avoid geometric decoration not from brand toolkit

### Backgrounds
- Light: Cream (`#F7F5EE`) or White
- Dark: Dark Navy (`#000E35`) or Black
- No gradients — brand avoids gradient fills
- Photography: Full-bleed, warm-toned architectural/lifestyle; clipped backgrounds on people shots
- No patterns or textures beyond the brand's own graphic elements

### Spacing & Layout
- Clean, generous whitespace
- Clear space around logos: min 0.5× height of "X" in REMAX on all sides
- Strong grid alignment; typically 12-column
- Fixed elements: legal line always at bottom of any print piece

### Borders & Radius
- Minimal use of borders; prefer whitespace to separate content
- Radius: near-zero (2–4px) for cards and inputs — clean, rectilinear aesthetic
- No pill buttons (brand is sharp, not bubbly)

### Shadows & Elevation
- Subtle drop shadows (low opacity, tight spread) for cards on light backgrounds
- Dark surfaces: no shadows; use colour contrast instead

### Animation
- Minimal, purposeful; no bounces or elastic easing
- Prefer opacity fades and clean linear/ease-out transitions
- Duration: 150–250ms for micro-interactions; 300–500ms for page-level transitions

### Hover / Press States
- Hover: slight darkening of accent colour (e.g. Red darkens toward Dark Red)
- Press: scale(0.97) + darken
- Links: underline on hover, no underline at rest

### Iconography
- No dedicated icon system from brand guide; Lucide Icons (CDN) used as system default
- Stroke-weight icons preferred (not filled)
- See ICONOGRAPHY section below

---

## ICONOGRAPHY

### Brand Assets
| File | Description |
|---|---|
| `assets/Balloon_Mark_RGB.png` | Four-colour Balloon mark (flat vector render) |
| `assets/Balloon_Mark_3D.png` | Three-dimensional Balloon render |
| `assets/REMAX_logo_RGB_dark.png` | Primary logotype — black on white |
| `assets/REMAX_logo_RGB_cream.png` | Primary logotype — cream (reversed) |
| `assets/REMAX_wordmark_RGB_dark.png` | Wordmark only — black |
| `assets/REMAX_wordmark_RGB_light.png` | Wordmark only — cream |
| `assets/slash.png` | Dynamic Slash graphic — navy |

### UI Icons
No proprietary icon font was provided. Design system uses **Lucide Icons** via CDN:
```html
<script src="https://unpkg.com/lucide@latest/dist/umd/lucide.min.js"></script>
```
Lucide icons are stroke-weight, 24px default grid, consistent with the brand's clean aesthetic.

### Emoji
Not used in brand communications. Prohibited in formal materials.

---
