# 02 — Design Direction
## Whitley County Chamber of Commerce
> Use this file when building any UI component, page layout, or visual element.
> Paste this alongside 00-master-prompt.md when starting a design-heavy build.

---

## Aesthetic Direction

- **Vibe keywords:** Bold, civic, warm, editorial, Midwestern
- **Overall tone:** Confident and community-rooted — the visual energy of a modern magazine applied to the warmth of small-town Indiana. Feels like something new is happening here, and it's worth paying attention to.
- **Light or dark theme:** Light — warm off-white backgrounds, not stark white
- **Density:** Open and airy with generous whitespace. Let the typography and photography breathe. Each section should feel intentional, not crowded.

---

## Color Palette

| Role | Hex | Usage |
|------|-----|-------|
| Background | `#FAF7F2` | Warm off-white main page background — never pure white |
| Surface | `#FFFFFF` | Cards, modals, nav background when scrolled |
| Primary | `#1B2D52` | Deep navy — civic authority, trust, primary headings and nav |
| Accent | `#D4882A` | Warm amber/harvest gold — CTAs, highlights, hover states, section accents |
| Secondary accent | `#3A5C3F` | Forest green — used sparingly for tags, icons, or section dividers |
| Text primary | `#1A1A1A` | Near-black — headings, body copy |
| Text secondary | `#6B6B6B` | Captions, labels, secondary body text |
| Border | `#E2DDD6` | Warm gray dividers and card outlines |
| Success | `#3A5C3F` | Forest green — confirmations, form success |
| Error | `#C0392B` | Standard error red — form errors only |

**Color philosophy:** This palette is rooted in Northeast Indiana's identity — navy for the civic trust of a courthouse town, amber for harvest fields and Midwestern warmth, forest green for Indiana's landscape. Together they feel bold but not aggressive, proud but not loud.

---

## Typography

- **Heading font:** Playfair Display
  - Source: Google Fonts
  - Weight: 700 for H1, 600 for H2–H3
  - Use for: All major headlines, section titles, pull quotes
  - Feel: Editorial authority — the kind of type you see in a premium regional magazine

- **Body font:** DM Sans
  - Source: Google Fonts
  - Weight: 400 regular, 500 medium, 600 semi-bold for emphasis
  - Use for: Body copy, nav links, button labels, captions, form labels
  - Feel: Clean, modern, highly readable — balances the weight of Playfair Display

- **Mono font:** Not used

- **Type scale:** Large and dramatic
  - H1: 72px desktop / 42px mobile — bold, commanding
  - H2: 48px desktop / 32px mobile
  - H3: 32px desktop / 24px mobile
  - Body: 18px desktop / 16px mobile
  - Caption/label: 14px

- **Letter spacing:**
  - Headings: Slightly tight (-0.01em to -0.02em) — editorial feel
  - All-caps labels/tags: Wide (0.08em–0.12em)
  - Body: Normal

---

## Reference Sites

**Sites I like (and what specifically to take from them):**

1. URL: https://www.kinfolk.com/
   What to borrow: The editorial grid structure, intentional section layouts, generous whitespace, and the way content sections feel curated rather than templated. Do NOT borrow: The bland neutral-only palette and the lack of energy — we need warmth and color.

2. URL: https://www.tampabaychamber.com/
   What to borrow: The professional chamber credibility, the clear membership-focused information architecture, and the section-by-section logic of a membership conversion site. Do NOT borrow: The dated visual treatment, the corporate color palette, the generic photography.

3. URL: https://roundrockchamber.org/
   What to borrow: The civic pride framing and the "why join" section structure. Do NOT borrow: The lack of visual energy, the coolness — this site needs to feel warmer, more alive, more Whitley County.

**Synthesis:** Take Kinfolk's editorial layout discipline. Take a chamber's structural logic. Inject Midwest warmth, harvest gold, and genuine photographic storytelling of a real Indiana community.

**Sites to avoid:**
- The existing whitleychamber.org — do not replicate any element of its current visual style
- Generic chamber sites with stock photography of people shaking hands in conference rooms
- Any site that feels like it was built from a CMS template without design decisions

---

## Layout & Spacing

- **Border radius:** Small-to-medium — 6px for cards, 4px for buttons, 0px for full-bleed image sections. Never pill-shaped buttons — too soft for this aesthetic.
- **Shadow style:** Subtle — light drop shadows on cards only. No dramatic shadows.
- **Grid system:** 12-column with intentional asymmetry in feature sections. Full-bleed sections alternate with contained content sections.
- **Section padding:** Generous — 120px top/bottom on desktop, 72px on mobile
- **Max content width:** 1280px centered, with full-bleed sections breaking out to viewport width

---

## Animation & Motion

- **Animation level:** Expressive — this site should feel alive and modern
- **Preferred animation style:**
  - Scroll-triggered fade-up on section content (staggered — headline first, then body, then CTA)
  - Parallax on full-bleed hero image (subtle — 15–20% depth)
  - Horizontal scroll or marquee on the member logo bar
  - Smooth counter animation on stats (number counts up when section enters viewport)
- **Hover states:**
  - Buttons: Amber accent color deepens, subtle scale-up (1.02)
  - Cards: Slight lift (translateY -4px) with shadow increase
  - Nav links: Amber underline slides in from left
- **Page load animation:** Subtle fade-in on hero content (300ms delay after load)
- **Transition speed:** Standard — 250ms for most transitions, 400ms for scroll-triggered reveals

---

## Imagery & Media

- **Photography style:** Real, candid, warm — Whitley County landmarks (Columbia City courthouse, main streets, local storefronts), community gatherings, small business owners at work in their actual environment. Golden-hour light preferred. People should look like Midwest small-town residents, not urban stock photo subjects.
  - Primary sources: Open-source/public domain images of Whitley County, Columbia City, Churubusco, and South Whitley, Indiana
  - Fill gaps with: Unsplash — search terms like "small town Indiana," "Midwest main street," "local business owner," "community gathering," "farm town," "county courthouse"
  - Avoid: Generic coastal or urban imagery, people smiling at laptops in coffee shops, skyline photography, anything that doesn't feel like Northeast Indiana

- **Illustration style:** None — photography only

- **Icon set:** Phosphor Icons (outline weight) — clean, modern, pairs well with DM Sans

- **Video usage:** None at launch — placeholder for future

---

## What to Absolutely Avoid

- NO generic blue-gradient chamber website aesthetic
- NO stock photography of business handshakes in conference rooms
- NO pure white (#FFFFFF) as the main background — use the warm off-white `#FAF7F2`
- NO Inter, Roboto, or Arial — use Playfair Display + DM Sans only
- NO pill-shaped or rounded buttons — keep border radius at 4–6px
- NO Lorem Ipsum or placeholder text anywhere
- NO replication of the existing whitleychamber.org design
- NO imagery that feels urban, coastal, or generic-corporate
- NO promises of business results in copy — frame everything as opportunity and access
- NO colors that feel cold, corporate, or generic — this palette is warm and specific
