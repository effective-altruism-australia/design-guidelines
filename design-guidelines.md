# Effective Altruism Australia - Design Guidelines

*Last updated: 27 July 2025*

---

## Colour Palette

### Primary Colours

| Colour | Hex | Usage |
|--------|-----|-------|
| Primary Teal | `#0C869B` | Accents, buttons, links, highlights |
| Dark Teal | `#145565` | Headings, dark text, navigation |
| Warm Off-White | `#F4EFE9` | Page backgrounds, subtle sections |
| Charcoal Black | `#151515` | Body text, primary content |
| Pure White | `#FFFFFF` | Card backgrounds, content areas |

### EAA Warm Colour Palette

| Step | Hex |
|------|-----|
| 50 | `#f9f6f3` |
| 100 | `#f4efe9` |
| 200 | `#e2d4c6` |
| 300 | `#cfb8a2` |
| 400 | `#bb967c` |
| 500 | `#ad7f62` |
| 600 | `#a06d56` |
| 700 | `#855849` |
| 800 | `#6d4a3f` |
| 900 | `#593d35` |
| 950 | `#2f1e1b` |

### EAA Grey Neutral Palette

| Step | Hex |
|------|-----|
| 50 | `#f6f6f6` |
| 100 | `#e7e7e7` |
| 200 | `#d1d1d1` |
| 300 | `#b0b0b0` |
| 400 | `#888888` |
| 500 | `#6d6d6d` |
| 600 | `#5d5d5d` |
| 700 | `#4f4f4f` |
| 800 | `#454545` |
| 900 | `#3d3d3d` |
| 950 | `#151515` |

---

## Typography

### Merriweather (Serif) - Headings

- **Usage:** All headings and titles (H1, H2, H3, etc.)
- **Do:** Use for all headings and titles
- **Don't:** Don't use for body text or long paragraphs
- A classic serif font that provides elegance and readability for headings.

### Mukta (Sans-serif) - Body Text

- **Usage:** Body text, paragraphs, UI elements
- **Do:** Use for all body text and interface elements
- **Don't:** Don't use for headings or titles
- A clean, modern sans-serif font optimized for readability in body text.

### Default Sans-Serif (Fallback)

- **Family:** Arial, sans-serif
- **Usage:** Email and limited contexts
- **Do:** Use when custom fonts aren't available (emails, etc.)
- **Don't:** Don't use when Merriweather and Mukta are available
- Fallback to system default sans-serif fonts when custom fonts cannot be loaded.

---

## Logo Variations

### Square Logos

#### Full Colour

- **Do:** Primary brand representation
- **Don't:** Avoid on coloured backgrounds that conflict
- **Formats:** SVG, PNG, PNG (no padding)
- SVG is best for web use, large displays, and crisp scalable graphics
- PNG is best for presentations, documents, and email
- PNG (no padding) is best for tight layouts with precise spacing control

#### Mono Colour

- **Do:** Use when displayed in small sizes or when full colour isn't an option
- **Don't:** Don't use where full colour is an option
- **Formats:** SVG, PNG, PNG (no padding)

#### Black

- **Do:** Use on light backgrounds where full colour won't work
- **Don't:** Never use on dark backgrounds
- **Formats:** SVG, PNG, PNG (no padding)

#### White

- **Do:** Use on dark backgrounds where full colour won't work
- **Don't:** Never use on light backgrounds
- **Formats:** SVG, PNG, PNG (no padding)

#### Inverted Mono Colour

- **Do:** Use for social media avatars etc.
- **Don't:** Don't use in other cases where full colour logo is an option
- **Formats:** SVG, PNG

### Large Format Logos

#### Full Colour

- **Do:** Primary brand representation
- **Don't:** Avoid on coloured backgrounds that conflict
- **Formats:** SVG, PNG, PNG (no padding)

#### Mono Colour

- **Do:** Use when displayed in small sizes or when full colour isn't an option
- **Don't:** Try to use the full colour version if you can
- **Formats:** SVG, PNG, PNG (no padding)

#### Full Colour Dark

- **Do:** Use for large displays on dark backgrounds
- **Don't:** Don't use on light backgrounds or in small sizes - the gradient on the bulb will get lost in the background
- **Formats:** SVG, PNG, PNG (no padding)

#### Mono Colour Dark

- **Do:** Use for smaller displays on dark backgrounds
- **Don't:** Don't use on light backgrounds
- **Formats:** SVG, PNG, PNG (no padding)

---

## Environmental Logo Variations

### Square Logos (ENV)

#### Full Colour

- **Do:** Primary brand representation
- **Don't:** Avoid on coloured backgrounds that conflict
- **Formats:** SVG, PNG, PNG (no padding)

#### Mono Colour

- **Do:** Use when displayed in small sizes or when full colour isn't an option
- **Don't:** Don't use where full colour is an option
- **Formats:** SVG, PNG, PNG (no padding)

#### Black

- **Do:** Use on light backgrounds where full colour won't work
- **Don't:** Never use on dark backgrounds
- **Formats:** SVG, PNG, PNG (no padding)

#### White

- **Do:** Use on dark backgrounds where full colour won't work
- **Don't:** Never use on light backgrounds
- **Formats:** SVG, PNG, PNG (no padding)

#### Inverted Mono Colour

- **Do:** Use for social media avatars etc.
- **Don't:** Don't use in other cases where full colour logo is an option
- **Formats:** SVG, PNG

### Large Format Logos (ENV)

#### Full Colour

- **Do:** Primary brand representation
- **Don't:** Avoid on coloured backgrounds that conflict
- **Formats:** SVG, PNG, PNG (no padding)

#### Mono Colour

- **Do:** Use when displayed in small sizes or when full colour isn't an option
- **Don't:** Don't use where full colour is an option
- **Formats:** SVG, PNG, PNG (no padding)

#### Full Colour Dark

- **Do:** Use for large displays on dark backgrounds
- **Don't:** Don't use on light backgrounds or in small sizes - the gradient on the bulb will get lost in the background
- **Formats:** SVG, PNG, PNG (no padding)

#### Mono Colour Dark

- **Do:** Use for smaller displays on dark backgrounds
- **Don't:** Don't use on light backgrounds
- **Formats:** SVG, PNG, PNG (no padding)

---

## Bad Examples - What Not to Do

### 1. Stacking Text Next to Logo

- **Don't:** Stack the text next to the logo
- **Do:** Use standard logo with two lines of text

### 2. Centre-Justified Text

- **Don't:** Centre-justify the text next to the logo
- **Do:** Use standard logo with right-aligned text

### 3. Wrong Font Usage

- **Don't:** Use other fonts with the logo
- **Do:** Use Merriweather font

### 4. Awkward Spacing

- **Don't:** Awkwardly space the icon and text
- **Do:** Use the logos above as a reference

### 5. Squeezed Text

- **Don't:** Squeeze the text in too close to the logo
- **Do:** Use the logos above as a reference

---

## CSS Design Tokens

```css
/* Primary colours */
--primary:      #0C869B;
--dark:         #145565;
--dark-deeper:  #073845;
--warm-white:   #F4EFE9;
--charcoal:     #151515;
--white:        #FFFFFF;
--bg:           #f9f6f3;

/* Shadows */
--shadow-sm:  0 1px 3px rgba(20,85,101,0.07), 0 2px 8px rgba(20,85,101,0.06);
--shadow-md:  0 4px 16px rgba(20,85,101,0.12), 0 1px 4px rgba(20,85,101,0.07);
--shadow-lg:  0 8px 32px rgba(20,85,101,0.16);

/* Border radius */
--radius:     16px;
--radius-sm:  8px;
--radius-xs:  5px;

/* Easing */
--ease:       cubic-bezier(0.25, 0.46, 0.45, 0.94);
```
