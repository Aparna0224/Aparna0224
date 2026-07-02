# Visual Design Language: Aparna0224
**Profile:** Artificial Intelligence & Data Science Engineer
**Inspiration:** Apple + Linear + GitHub + Vercel
**Core Aesthetic:** Refined Glassmorphism + Minimal Neon + Technical Professionalism

## 1. Theme Configuration
*   **Base:** GitHub Dark mode native blending.
*   **Vibe:** Sophisticated, academic-yet-cutting-edge, highly engineered.
*   **Strict Constraints:** No heavy "cyberpunk" glitches, no aggressive hacker terminal fonts, no cartoon/anime styling. Pure, clean, architectural, and data-driven.

## 2. Color Palette
The color system relies heavily on the stark contrast between deep GitHub darks and high-end, pure neon accents, keeping the overall feeling cool and analytical.

*   **Background (GitHub Native):** `#0D1117` (Maintains seamless integration with GitHub's UI)
*   **Surface / Cards:** `rgba(22, 27, 34, 0.6)` (Slightly lighter than background, translucent)
*   **Surface Border:** `rgba(255, 255, 255, 0.08)` (Ultra-thin, crisp definition)
*   **Primary Accent (Blue Neon):** `#0070F3` (Vercel Blue) fading into `#38BDF8` (Sky)
*   **Secondary Accent (Purple Neon):** `#7928CA` fading into `#A855F7` (Deep Amethyst)
*   **Typography - Primary:** `#E6EDF3` (GitHub standard high-contrast text)
*   **Typography - Secondary:** `#8B949E` (Muted technical text)
*   **Success/Status:** `#10B981` (Emerald - for active status, commits)

## 3. Typography Rules
*   **Primary Font:** `Inter` or `San Francisco` (System-UI fallback) for all headings and body text to maintain Apple/Linear style crispness.
*   **Technical/Data Font:** `JetBrains Mono` or `Fira Code` strictly reserved for numbers, data points, or code snippets. 
*   **Hierarchy:** 
    *   H1/H2 (Section Headers): Semi-bold, tight tracking (-0.02em), often utilizing gradient fills (Blue to Purple).
    *   Body: Regular weight, generous line height (1.6) for legibility.
    *   Micro-copy (Tags, badges): All-caps, wide tracking (0.1em), smallest font size.

## 4. Layout & Spacing
*   **Grid System:** 8pt spatial grid. All margins, paddings, and gaps must be multiples of 8 (8, 16, 24, 32, 48, 64).
*   **Negative Space:** High application of whitespace (dark-space). Elements should breathe, mimicking Apple's landing page layouts. Avoid dense, cluttered clusters of information.

## 5. Border Radius
*   **Cards & Large Containers:** `12px` or `16px` (Modern Apple/Linear rounding).
*   **Buttons & Badges:** `6px` or `8px` (Slightly sharper for interactive/technical elements).
*   **Images/Avatars:** `50%` (Perfect circles) or `12px` (Soft rectangles).

## 6. Card Style
*   **Background:** Glassmorphic translucent dark fill `linear-gradient(145deg, rgba(30, 35, 45, 0.6) 0%, rgba(13, 17, 23, 0.4) 100%)`.
*   **Backdrop Filter:** Blur `12px` to `16px` (simulating frosted dark glass).
*   **Border:** `1px solid rgba(255, 255, 255, 0.08)` with a subtle top highlight `box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1)`.

## 7. Glow Style
*   **Purpose:** Used sparingly to emphasize key metrics, primary actions, or currently active projects. Avoid muddy, large blurs.
*   **Ambient Glow:** Multiple layered, low-opacity shadows. 
    `box-shadow: 0 0 15px rgba(0, 112, 243, 0.15), 0 0 40px rgba(121, 40, 202, 0.1)` (Sharp, localized).
*   **Edge Glow:** Highlighting just the top edge of a card to mimic neon strip lighting hidden beneath the glass.

## 8. Animation Style
*   **Feel:** Snappy, deliberate, fluid (Linear style).
*   **Easing:** Standard `cubic-bezier(0.2, 0.8, 0.2, 1)` (Swift out, slow in).
*   **Durations:** Fast for micro-interactions (150ms), elegant for entrance animations (600ms - 800ms).
*   **SVG Entrances:** Cascading fades + slight vertical translations (e.g., elements sliding up 10px into place while fading in).

## 9. Icon Style
*   **Type:** Outline icons, strictly 1.5px stroke width. NO filled icons unless representing a solid brand logo.
*   **Aesthetic:** Razor-sharp, perfectly aligned to the pixel grid. Think Phosphor Icons or Lucide.
*   **Color:** Muted secondary text color (`#8B949E`), illuminating to neon Blue/Purple on hover/active states.

## 10. SVG & Divider Style
*   **Dividers:** Ultra-minimal. A 1px horizontal line that fades in the center. 
    `linear-gradient(90deg, transparent, rgba(255,255,255,0.1) 50%, transparent)`.
*   **SVG Elements (Nodes/Lines):** AI concepts (neural nets, data pipelines) represented by thin glowing lines (1px) and perfect circular nodes. No chaotic or messy wiring. Everything aligns to strict geometric grids.

## 11. Dashboard Style
*   **Layout:** Masonry or strict grid (like Vercel's project dashboard).
*   **Hierarchy:** The primary metric (e.g., "AI Models Deployed" or "Contributions") acts as the anchor.
*   **Data Vis:** Clean sparklines or minimalist radar charts using the Blue-to-Purple gradient. No axes labels, pure data curvature.

## 12. Grid & Project Card Style
*   **Grid Style:** A muted Cartesian dotted background pattern `radial-gradient(circle, rgba(255,255,255,0.05) 1px, transparent 1px)` with 24px spacing, representing data science environments.
*   **Project Cards:**
    *   **Structure:** Horizontal or vertical layout aligned to a strict baseline.
    *   **Visuals:** Subtle gradient overlay on any project imagery to blend into the Dark background.
    *   **Tags:** Minimal, outlined badges for tech stack items (e.g., [ PyTorch ] [ FastAPI ]).

## Summary
The result is an aesthetic that feels like a high-end SaaS product built for enterprise engineering. It communicates logical precision, modern development workflows, and high attention to detail without falling into typical developer portfolio cliches.
