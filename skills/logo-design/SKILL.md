---
name: logo-design
description: "Design professional logos as SVG code with browser preview. Use this skill when the user asks to design a logo, create a brand mark, make an icon, or build a visual identity. Also triggers on 'logo', 'brand mark', 'wordmark', 'monogram', 'icon design', 'visual identity', or 'design a logo for'. Outputs clean, scalable SVG files with full design rationale."
metadata:
  version: 2.0.0
---

# Logo Design Skill

Transform brand identity into distinctive, memorable visual marks. Every logo tells a story — the skill ensures that story is grounded in research, typographic craft, and strategic thinking, then delivered as production-ready SVG.

**Output format:** SVG vector files, automatically opened in the browser for instant preview.

---

## Phase 1: Discovery & Brief

Before any design work, **you must** gather context from the user. Ask for anything not already provided.

### Required Information
1. **Brand name** — the exact text to appear in the logo
2. **Industry / domain** — what the brand does (drives visual metaphors and tone)
3. **Brand story / core values** — the idea, spirit, or promise the brand wants to communicate
4. **Target audience** — who the primary users/customers are (age, taste, cultural context)

### Recommended Information
5. **Competitors** — key competitor names (for differentiation)
6. **Color preferences** — specific colors, or a mood direction (bold, elegant, playful, tech-forward, etc.)
7. **Style preference** (if not specified, recommend based on analysis):
   - **Wordmark** — pure typography (e.g., Google, FedEx)
   - **Lettermark / Monogram** — initials (e.g., IBM, HBO, LV)
   - **Icon + Text** — symbol paired with brand name (e.g., Apple, Nike)
   - **Abstract Mark** — geometric / abstract symbol (e.g., Pepsi, Airbnb)
   - **Emblem** — text enclosed within a shape (e.g., Starbucks, Harley-Davidson)
   - **Combination Mark** — flexible pairing of icon and text
8. **Exclusions** — styles, colors, or elements the user explicitly does NOT want

---

## Phase 2: Market Research & Inspiration

**You must conduct web research before designing.** This grounds the work in current reality rather than generic assumptions.

### What to Research
1. **Industry logo trends** — current mainstream and emerging styles in the brand's sector
2. **Competitor logo analysis** — visual strategies of named competitors; identify patterns to differentiate from
3. **Typography inspiration** — typefaces and lettering styles that match the brand's tone
4. **Color trends** — how brands in the same space use color; opportunities to stand out

### How to Research
Run these searches using `WebSearch` (adapt keywords to the specific brand):

```
"{industry} logo design trends {current_year}"
"{competitor_name} logo"
"{style_keyword} logo inspiration"
"{industry} brand color palette trends"
```

Compile findings into a brief summary and share key insights with the user before proceeding. Highlight:
- Dominant visual patterns in the industry (what to leverage or avoid)
- Gaps / white-space opportunities (underused styles or colors)
- Notable references worth drawing from

---

## Phase 3: Name & Letterform Analysis

This is the creative engine of the skill. **You must** perform a deep typographic analysis of the brand name before sketching concepts. The analysis directly informs which logo styles will be most effective.

### 3.1 Individual Letter Anatomy

Classify each letter in the brand name:

| Category | Letters | Design Implication |
|---|---|---|
| **Symmetric** | A, H, M, O, T, U, V, W, X, Y | Geometric construction, mirroring, balanced composition |
| **Ascenders** | b, d, f, h, k, l, t | Vertical reach; suits tall, aspirational marks |
| **Descenders** | g, j, p, q, y | Anchoring weight; suits grounded, stable marks |
| **Round forms** | B, C, D, G, O, P, Q, R, S, e, o | Approachable, organic, friendly feel |
| **Angular forms** | A, K, M, N, V, W, Z | Sharp, powerful, dynamic energy |
| **Open counters** | C, G, U, J, c, e, s | Negative-space opportunities |
| **Diagonal stress** | A, K, M, N, V, W, X, Y, Z | Movement, dynamism; natural for italic or oblique treatments |

### 3.2 Letter Combination Analysis

Examine how adjacent letters interact — this is where hidden design opportunities live:

- **Ligature potential** — which letter pairs can naturally merge?
  - Classic pairs: fi, fl, ft, tt, ff, Th, AV, VA, AT, LT, TA
  - Look for shared strokes, overlapping geometry, or smooth joining points

- **Negative-space discoveries** — does the combination of letters hide a secondary shape?
  - Iconic examples: FedEx (arrow between E and x), Spartan Golf (golfer in negative space), Toblerone (bear in mountain)
  - Systematically check: between each pair of adjacent letters, what shape does the counter-space form?

- **Letter-to-metaphor mapping** — connect letterforms to brand-relevant visual concepts:

  | Letter | Possible Visual Metaphors |
  |---|---|
  | A | Mountain peak, tent, upward arrow, compass point |
  | B | Butterfly wings, infinity (rotated), headphones |
  | C | Moon crescent, embrace, cup/container |
  | D | Sail, half-sun, shield |
  | E | Stacked layers, equalizer bars, comb |
  | G | Spinning disc, spiral, speech bubble |
  | H | Bridge, ladder, building |
  | I | Pillar, candle, exclamation, person |
  | K | Key, branch fork, signal |
  | L | Corner, angle, boot, shelf |
  | M/W | Mountain range, waves, crown, heartbeat |
  | N | Lightning bolt, staircase, zigzag |
  | O | Eye, target, globe, sun, ring, lens |
  | P | Flag, pin, thought bubble |
  | Q | Magnifying glass, balloon, key |
  | R | Running figure, flag waving |
  | S | Path, river, snake, yin-yang flow |
  | T | Hammer, cross, antenna, tree |
  | V | Checkmark, wings, victory, valley |
  | X | Crossroads, multiply, chromosome |
  | Y | Fork in road, tree, chalice |
  | Z | Lightning, zigzag path |

  Always adapt metaphors to the brand's actual domain — a "V" for a travel brand suggests a bird in flight; for a fintech brand it suggests a checkmark of verification.

### 3.3 Visual Wordplay & Hidden Meaning

Push beyond surface-level design:
- **Visual puns** — embed a secondary image or meaning within the letterforms (e.g., the Amazon smile/arrow from A to Z)
- **Negative space** — create a second layer of meaning in the space between or within letters
- **Semantic connections** — explore homophones, word roots, abbreviation meanings, and cultural associations of the brand name
- **Number/letter ambiguity** — if any letter resembles a number or symbol, consider whether that creates a meaningful connection

### 3.4 Analysis Output

Compile and present to the user:
1. The 2-3 most promising letter combinations or individual letters with creative potential
2. 2-3 strongest visual metaphor directions (tied to brand values)
3. Recommended logo style(s) based on letterform characteristics
4. Any hidden meaning or wordplay opportunities discovered

**Wait for user confirmation** on the direction before proceeding to design.

---

## Phase 4: Design Philosophy & Style Direction

### 4.1 Core Design Principles

Every concept must satisfy all four:

- **Simplicity & Recognition** — works at 16x16 favicon AND on a billboard; if you can't describe it in one sentence, simplify
- **Uniqueness & Memorability** — the viewer should remember it after a single 3-second glance
- **Strategic Extensibility** — supports the brand's future growth, not just today's product
- **Storytelling** — every element has a reason; the logo communicates the brand's essence without words

### 4.2 Style Directions

Select the most appropriate direction(s) based on the brief and letter analysis:

#### Modern Minimalist
Strip to essentials. Clean lines, geometric shapes, generous whitespace. Power through restraint. Technique: grid-based construction, mathematical precision, optical alignment.

#### Retro / Classic
Draw from vintage aesthetics — hand-lettering, badges, textures — but filter through a contemporary lens. Suits brands seeking heritage, craft, and authenticity.

#### Abstract / Geometric
Express the brand through pure form — circles, triangles, spirals, tessellations. Ideal when the brand transcends a single product or geography. Technique: golden ratio construction, Fibonacci spirals, modular grids.

#### Hand-drawn / Illustrative
Human warmth through organic linework. Use SVG paths with subtle irregularities to simulate hand-crafted feel. Suits creative, artisanal, or personality-driven brands.

#### Geometric Construction (Grid-based)
Build the logo on a mathematical grid — golden ratio, circular grids, or modular systems (like the Apple, Twitter/X, or Pepsi logos). Every curve and proportion is derived from the grid, yielding a mark that feels inevitable rather than arbitrary.

#### Emblem / Crest
Text enclosed within a symbol — shield, circle, badge, seal. Conveys tradition, authority, and prestige. Requires careful balance between enclosure and content.

---

## Phase 5: Color Strategy

### 5.1 Color Psychology Reference

| Color Family | Associations | Best For |
|---|---|---|
| **Blue** | Trust, professionalism, technology, stability | Finance, tech, healthcare, corporate |
| **Red** | Passion, energy, boldness, appetite | Food, entertainment, sports, urgency |
| **Green** | Nature, health, growth, sustainability | Wellness, eco, agriculture, finance |
| **Orange / Yellow** | Optimism, creativity, warmth, youth | Education, creative, food, social |
| **Purple** | Luxury, mystery, innovation, spirituality | Beauty, premium, creative, spiritual |
| **Black / Gray** | Premium, minimal, authority, timeless | Luxury, fashion, tech, editorial |
| **Pink** | Gentle, fashionable, caring, modern | Beauty, wellness, social, youth |

### 5.2 Palette Rules
- **1 primary + 1-2 accent colors** maximum; a strong logo works in a single color
- Prioritize differentiation within the industry — if every competitor uses blue, consider the strategic value of not using blue
- Ensure sufficient contrast for readability on both light and dark backgrounds
- Verify the palette reproduces well across media: screen (RGB), print (CMYK intent), single-color (monochrome)
- **Always produce a monochrome (black/white) version** — it is the true test of a logo's structural strength

### 5.3 Color Application in SVG
- Define colors as CSS custom properties in `<style>` for easy theming:
  ```svg
  <style>
    :root {
      --brand-primary: #2563EB;
      --brand-accent: #F59E0B;
      --brand-dark: #1E293B;
    }
  </style>
  ```
- Use `currentColor` for elements that should inherit the parent's text color
- For monochrome versions, use a single fill color or `currentColor` throughout

---

## Phase 6: Typography & Lettering

### 6.1 Typeface Strategy

| Brand Personality | Type Category | Characteristics |
|---|---|---|
| Classic, authoritative | Serif | Tradition, elegance, trustworthiness |
| Modern, clean | Sans-serif | Clarity, simplicity, technology |
| Creative, personal | Script / Handwritten | Warmth, individuality, artistry |
| Technical, precise | Monospace | Code, engineering, systems |
| Futuristic, architectural | Geometric sans | Structure, innovation, boldness |
| Luxurious, editorial | High-contrast serif / didone | Sophistication, fashion, premium |

### 6.2 Typographic Refinement
- **Letter-spacing:** optically adjust per character pair, not a uniform value — critical for wordmarks
- **Stroke weight:** ensure visual consistency at all scales; thin strokes may vanish at small sizes
- **Corner treatment:** rounded corners convey warmth; sharp corners convey precision
- **Baseline alignment:** when combining icon and text, align to optical center, not mathematical center
- **Custom modifications:** consider cutting, extending, connecting, or reshaping individual letterforms to create a unique logotype

### 6.3 Font Implementation in SVG
- **Preferred: convert text to SVG `<path>`** for the final logo — eliminates font-loading dependencies and ensures pixel-perfect rendering everywhere
- When using live text (for editability), import Google Fonts via `@import` in `<style>` and always specify a fallback stack
- For wordmarks and lettermarks, path conversion is **strongly recommended**

---

## Phase 7: SVG Implementation Standards

### 7.1 File Structure

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 {width} {height}"
     role="img" aria-label="{Brand Name} Logo">
  <title>{Brand Name} Logo — {Variant Description}</title>
  <desc>Brief description of the logo design for accessibility.</desc>
  <defs>
    <!-- Gradients, clip paths, masks -->
  </defs>
  <style>
    /* CSS custom properties, font imports */
  </style>
  <!-- Logo geometry -->
</svg>
```

### 7.2 Technical Requirements
- **Always** use `viewBox` for scalability; do NOT hardcode `width`/`height` on the root `<svg>` (or set them to responsive values like `100%`)
- Keep markup clean — minimize `<g>` nesting and avoid unnecessary `transform` attributes
- Use semantic element names and `id` attributes for maintainability
- Optimize `<path>` data — remove redundant control points, simplify curves, use shorthand commands (e.g., `h`, `v`, `z`)
- Prefer basic shapes (`<circle>`, `<rect>`, `<ellipse>`, `<polygon>`, `<line>`) over complex paths when they achieve the same result
- Ensure all colors are defined in one place (CSS variables or a single `<style>` block)

### 7.3 Quality Checklist
Before delivering each SVG, verify:
- [ ] Renders correctly at 16x16 (favicon), 64x64 (app icon), and 512+ (hero size)
- [ ] No visual artifacts at any scale
- [ ] Text is either converted to paths or has proper font fallbacks
- [ ] `viewBox` is set and no fixed dimensions on root
- [ ] Accessibility attributes present (`<title>`, `aria-label`, `role="img"`)
- [ ] File is reasonably compact (no bloated path data)

### 7.4 Prohibitions
- **No** `<image>` tags embedding raster bitmaps
- **No** complex filter effects (`<filter>`, `feGaussianBlur`, `feTurbulence`) — they degrade at small sizes and increase file weight
- **No** overly detailed illustrations — logos must reduce to simple, recognizable forms
- **No** fonts without fallbacks
- **No** generic clip-art aesthetics — every logo must feel intentionally crafted for this specific brand

---

## Phase 8: Delivery

### 8.1 Default Deliverables: 3 Distinct Concepts

Each concept explores a fundamentally different direction:

| Concept | Direction | Purpose |
|---|---|---|
| **A** | Bold / innovative | Pushes creative boundaries; the "unexpected" option |
| **B** | Classic / safe | Proven style, polished execution; the "reliable" option |
| **C** | Unique angle | A synthesis or an unconventional take; the "surprise" option |

Each concept must be a separate SVG file.

### 8.2 File Naming Convention
```
logos/{brand}-concept-a-{style}.svg    # e.g. logos/acme-concept-a-wordmark.svg
logos/{brand}-concept-b-{style}.svg    # e.g. logos/acme-concept-b-abstract.svg
logos/{brand}-concept-c-{style}.svg    # e.g. logos/acme-concept-c-emblem.svg
```

### 8.3 Output Workflow
1. Create a `logos/` directory in the current working directory
2. Write each SVG file to `logos/`
3. **Open each SVG in the browser using `open` (macOS) for immediate visual preview**
4. Present each concept to the user with:
   - **Design rationale** — why this direction, what story it tells
   - **Letter analysis connection** — how the name analysis informed this specific design
   - **Recommended use cases** — where this style works best (digital, print, merch, etc.)
   - **Color palette** — hex values and the reasoning behind the choices

---

## Phase 9: Iteration & Refinement

### 9.1 Feedback Collection

After presenting the 3 concepts, ask:
- Which concept resonates most (or which elements from multiple concepts to combine)?
- What needs adjustment — color, proportion, weight, symbol, typography?
- Does the overall feel match the brand's personality?

### 9.2 Iterative Refinement (2-3 Rounds)
- Iterate rapidly — SVG is code, so changes are precise and fast
- Each round: produce 2-3 variations of the chosen direction
- Progressively narrow toward the final mark
- Open updated SVGs in the browser after each round for side-by-side comparison

### 9.3 Final Delivery (After User Approval)

Once the user confirms the final design, provide:
1. **Full-color version** — the primary brand logo
2. **Monochrome version** — single-color (black) for maximum versatility
3. **Reversed version** — white/light version for dark backgrounds
4. **Usage notes:**
   - Minimum recommended display size
   - Clear-space guidelines (safe area around the logo)
   - Color values (hex, RGB)
   - Brief do's and don'ts

---

## Workflow Summary

```
Discovery → Research → Letter Analysis → [User Checkpoint]
  → Design Direction → Color & Type → 3 SVG Concepts
  → Browser Preview → [User Feedback]
  → Iterate (2-3 rounds) → Final Delivery
```

Communicate with the user at every checkpoint. Never design in isolation — validate direction before investing in execution. The best logos emerge from dialogue, not from a single pass.
