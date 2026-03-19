> **Canonical source:** [`harborvane/harborvane` — `BRAND.md`](https://github.com/harborvane/harborvane/blob/main/BRAND.md). This file is a synced copy for the OpenClaw workspace; edit the repo original when brand changes.

---

# Harborvane Brand Guidelines

## Overview

Harborvane is a consulting firm that provides direction when it matters most. Our brand identity reflects maritime heritage, modern precision, and trusted guidance through complexity.

---

## Color Palette

### Primary Colors

#### Primary Navy (Harbor)
- **Hex:** `#0B2A45`
- **RGB:** `11, 42, 69`
- **Usage:** Primary brand color, used for "Harbor" in wordmark, backgrounds, and main UI elements
- **Meaning:** Stability, depth, enterprise trust

#### Teal / Blue-Green (Vane)
- **Hex:** `#1F6F7A`
- **RGB:** `31, 111, 122`
- **Usage:** Accent color, used for "vane" in wordmark, highlights, and interactive elements
- **Meaning:** Direction, clarity, modern innovation

### Secondary Colors

#### Gold (Guidance)
- **Hex:** `#F2C14E`
- **RGB:** `242, 193, 78`
- **Usage:** Sparingly for accents, CTAs, icons, and separators
- **Meaning:** Guidance, insight, illumination

#### Navy Light
- **Hex:** `#1a2332`
- **RGB:** `26, 35, 50`
- **Usage:** Subtle backgrounds, gradient transitions

#### White
- **Hex:** `#FFFFFF`
- **Usage:** Text on dark backgrounds, clean space

#### Gray Shades
- Gray 50: `#f9fafb`
- Gray 200: `#e5e7eb`
- Gray 400: `#9ca3af`
- Gray 600: `#4b5563`
- Gray 900: `#111827`

---

## Typography

### Wordmark Font

**Libre Baskerville**
- **Family:** Serif
- **Weights:** Regular (400), Bold (700)
- **Source:** Google Fonts
- **Character:** Classic maritime serif with modern restraint
- **Letter Spacing:** 3% (`letter-spacing: 0.03em`)

**Alternative Options:**
- Merriweather
- Crimson Pro
- Playfair Display (for more elegance)

**Premium Alternatives:**
- Canela
- Freight Text
- Tiempos Text

### Body Font

**Sans-serif System Stack**
- Primary: `-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif`
- **Usage:** Body text, navigation, UI elements
- **Character:** Clean, modern, highly readable

---

## Logo & Wordmark

### Logo Files

#### Main Logo
- **File:** `harborVane-logo-resized.png`
- **Format:** PNG with transparent background
- **Usage:** Primary brand mark, used in headers, footers, and marketing materials

#### Logo Sizes
- **32px:** `logo.png` (header/footer)
- **96px:** `logo-96.png` (medium displays)
- **288px:** `logo-288.png` (hero sections)

### Wordmark Treatment

#### Standard Wordmark
```
Harbor + vane
```

#### Color Application
- **"Harbor":** White (`#FFFFFF`) or Navy (`#0B2A45`)
- **"vane":** Teal (`#1F6F7A`)

#### Rules
- ✅ Slight letter spacing (+3%)
- ✅ Can use all navy, navy+teal split, or all white on dark backgrounds
- ❌ No heavy drop shadows
- ❌ No outlines
- ❌ No distortion or stretching

#### HTML/CSS Implementation
```html
<span style="font-family: 'Libre Baskerville', serif; letter-spacing: 0.03em;">
    <span style="color: #ffffff;">Harbor</span><span style="color: #1F6F7A;">vane</span>
</span>
```

---

## Favicon & Icons

### Favicon Files
Generated from main logo with trimmed/centered treatment:

- `favicon.ico` (16x16, 32x32 multi-resolution)
- `favicon-16x16.png`
- `favicon-32x32.png`
- `apple-touch-icon.png` (180x180)
- `android-chrome-192x192.png`
- `android-chrome-512x512.png`

### Icon Style
- Transparent background
- Trimmed to minimize empty space
- Centered within canvas
- Maintains visual clarity at small sizes

---

## UI Elements

### Gradients

#### Primary Background Gradient
```css
background: linear-gradient(135deg, #0B2A45 0%, #1a2332 50%, #1F6F7A 100%);
```
From navy → navy-light → teal

#### Button/CTA Gradient
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```
Purple gradient for primary actions

### Shadows
```css
/* Card shadow */
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);

/* Hover shadow */
box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
```

### Border Radius
- Small: `8px`
- Medium: `10px`
- Large: `12px`

---

## Voice & Messaging

### Tagline
**"Direction when it matters most"**

### Brand Voice
- **Professional:** Expert guidance without jargon
- **Confident:** Clear direction, decisive insights
- **Maritime:** Navigation metaphors, stability themes
- **Modern:** Contemporary solutions, not traditional consulting speak

### Key Phrases
- Navigate complexity with confidence
- Clarity, guidance, and trusted insight
- Move forward with certainty
- Even in turbulent conditions

---

## Usage Guidelines

### Do's
✅ Maintain proper color contrast for accessibility  
✅ Use logo with adequate clear space (minimum 20px)  
✅ Keep wordmark legible at all sizes  
✅ Use Libre Baskerville consistently for wordmark  
✅ Apply letter spacing to wordmark  
✅ Use teal as an accent, not dominantly  

### Don'ts
❌ Don't use outdated logo files  
❌ Don't add effects to the wordmark (shadows, outlines, glow)  
❌ Don't stretch or distort the logo  
❌ Don't use off-brand colors  
❌ Don't place logo on busy backgrounds without proper contrast  
❌ Don't use decorative fonts for body text  

---

## File Locations

### Source Files
- Logo: `harborVane-logo-resized.png`
- Wordmark: Rendered via HTML/CSS (no image file)

### Built Assets (dist/)
- All favicon variations
- Logo at multiple sizes
- Compiled CSS with brand colors

### Development (src/)
- `logo.png`, `logo-96.png`, `logo-288.png`
- Favicon source files
- `site.webmanifest` for PWA

---

## Accessibility

### Color Contrast Ratios
- Navy on White: ✅ AAA (10.5:1)
- Teal on White: ✅ AA (4.9:1)
- White on Navy: ✅ AAA (10.5:1)
- Gold on Navy: ✅ AAA (7.8:1)

### Font Sizing
- Minimum body text: 16px
- Minimum touch target: 44x44px
- Line height: 1.5-1.8 for readability

---

## Merchandise & Apparel

### Sweatshirt Design

#### Back Design
```
Harborvane
Consulting & Strategic Guidance
Garner, North Carolina
```

#### Typography
- **"Harborvane":** Libre Baskerville (brand wordmark font)
- **Supporting text:** Merriweather or sans-serif for hierarchy and distinction
- **Alignment:** Center-aligned
- **Size hierarchy:** Brand name largest, supporting text progressively smaller

#### Color Options
- **Primary:** All white text on navy or teal sweatshirt
- **Alternative:** White "Harborvane" + Gold (`#F2C14E`) accent for location line

#### Guidelines
- Maintain adequate spacing between lines for readability
- Ensure text size is large enough to read from a distance
- Use high-quality printing/embroidery to preserve brand quality
- Avoid placing design too high or too low on back (center between shoulder blades and waistline)

---

## Contact

For brand asset requests or questions about brand usage, contact the Harborvane team.

**Last Updated:** February 2, 2026
