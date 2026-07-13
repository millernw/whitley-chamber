# 02 — Design Direction
## The Chamber of Whitley County
> Use this file when building any UI component, page layout, or visual element.
> Paste this alongside 00-master-prompt.md when starting a design-heavy build.
> Brand system: the **Open Door** identity — Navy, Brick Red, White. Tagline: "Opening Doors to Whitley County."

---

## Aesthetic Direction

- **Vibe keywords:** Bold, civic, classic, trustworthy, welcoming
- **Overall tone:** Confident and community-rooted with the clean authority of a courthouse-town institution. Navy carries the trust and history; brick red is the single, decisive accent that signals action and the "open door." The feel is crisp and civic — proud, established, and genuinely welcoming — not corporate, not fussy.
- **Light or dark theme:** Light — clean white and light cool-gray backgrounds. (Pure white is now approved and preferred for a crisp, civic feel; the old warm off-white is retired.)
- **Density:** Open and airy with generous whitespace. Let the typography and photography breathe. Each section should feel intentional, not crowded.
- **Signature motif — the Open Door / path forward:** The logo is a red doorway with a navy door opening onto a white path. Carry that idea through the site: doorway/threshold framing on featured imagery, a subtle curving "path" line as a section divider or scroll element, and "opening doors / a way forward / step through" language and iconography. Use it as a recurring, understated device — not on every section.

---

## Color Palette

> Official Open Door brand colors: **Navy `#082F5B`**, **Brick Red `#B32120`**, **White `#FFFFFF`**. The remaining roles below are derived supporting tones — marked `[suggested — confirm]` where inferred.

| Role | Hex | Usage |
|------|-----|-------|
| Background | `#FFFFFF` | Clean white — main page background (crisp, civic; pure white is intentional here) |
| Alt surface | `#F4F6F9` | Light cool gray `[suggested]` — alternating banded sections, cards on white, nav background when scrolled |
| Primary | `#082F5B` | Brand navy — civic authority and trust; headings, nav, primary buttons, dark sections |
| Primary deep | `#061F3D` | Darker navy `[suggested]` — hover/pressed state on navy elements, footer |
| Accent | `#B32120` | Brand brick red — the single accent: CTAs, links, underlines, the door motif, key highlights |
| Accent deep | `#8E1A19` | Darker brick red `[suggested]` — hover/pressed state on red CTAs |
| Navy wash | `#E7ECF3` | Very light navy tint `[suggested]` — subtle section backgrounds, tags/eyebrows, icon chips |
| Text primary | `#14181F` | Near-black `[suggested]` — body copy (headings typically use navy `#082F5B`) |
| Text secondary | `#5A6472` | Cool gray `[suggested]` — captions, labels, secondary body text |
| Border | `#DCE1E8` | Light cool gray `[suggested]` — dividers and card outlines |
| Success | `#2E7D46` | Civic green `[suggested]` — confirmations, form success |
| Error | `#B32120` | Brand brick red — form validation errors (context disambiguates from CTAs: errors are text/outline, CTAs are filled buttons) |

**Color philosophy:** Navy is the foundation — the civic trust and history of a courthouse-town institution. Brick red is the accent of action and the open door: used decisively and sparingly, never as a wash. White carries the space and keeps everything crisp. Two colors doing clear, distinct jobs — navy holds, red points. Restraint is the point: this brand looks established and confident, not busy.

**60 / 30 / 10 guide:** ~60% white + light gray, ~30% navy (headers, dark sections, footer), ~10% brick red (CTAs and accents only). If red starts to feel decorative, pull it back.

---

## Typography

> The logo wordmark is custom/outlined artwork with **no named font**, so these are deliberate web fonts chosen to echo the lockup's three roles: a **script** accent ("The Chamber"), a **sturdy serif** ("of Whitley County"), and **wide-tracked sans caps** ("OPENING DOORS TO WHITLEY COUNTY"). They are the project's official web fonts — not placeholders. (Substitute alternatives are noted where relevant if you prefer a different feel.)

- **Script accent font:** Dancing Script
  - Source: Google Fonts
  - Weight: 600–700
  - Use for: Sparingly only — brand accent words, section eyebrows (e.g. a script "The Chamber"), and occasional pull-quote emphasis. Mirrors the "The Chamber" script in the logo.
  - Rules: Never for body copy, never for long headlines, never all-caps. Large sizes only, in navy or brick red. Elegant thinner alternatives if preferred: Great Vibes, Alex Brush.

- **Heading font (serif):** Lora
  - Source: Google Fonts
  - Weight: 700 for H1, 600 for H2–H3
  - Use for: All major headlines, section titles, pull quotes
  - Feel: Sturdy, grounded, classic serif — matches the bold serif of "of Whitley County" and reads as civic authority. (Replaces the former Playfair Display, which was too high-contrast/editorial for this brand.)

- **Body font (sans):** DM Sans
  - Source: Google Fonts
  - Weight: 400 regular, 500 medium, 600 semi-bold for emphasis
  - Use for: Body copy, nav links, button labels, captions, form labels
  - Feel: Clean, modern, highly readable — balances the serif headings

- **Tagline / eyebrow lockup:** DM Sans, UPPERCASE, wide letter-spacing (0.15em–0.2em), navy or brick red — directly mirrors the logo's "OPENING DOORS TO WHITLEY COUNTY" treatment. Use for the tagline and small section eyebrow labels.

- **Mono font:** Not used

- **Type scale:** Large and confident
  - H1: 64px desktop / 40px mobile — bold, commanding
  - H2: 44px desktop / 30px mobile
  - H3: 30px desktop / 24px mobile
  - Body: 18px desktop / 16px mobile
  - Caption/label: 14px

- **Letter spacing:**
  - Serif headings: Slightly tight (-0.01em to -0.02em)
  - All-caps labels/tags/tagline: Wide (0.15em–0.2em)
  - Script accents: Normal (do not track script)
  - Body: Normal

---

## Reference Sites

**Sites I like (and what specifically to take from them):**

1. URL: https://www.kinfolk.com/
   What to borrow: The editorial grid structure, intentional section layouts, generous whitespace, and the way content sections feel curated rather than templated. Do NOT borrow: The bland neutral-only palette — we lead with confident navy and a decisive brick-red accent.

2. URL: https://www.tampabaychamber.com/
   What to borrow: The professional chamber credibility, the clear membership-focused information architecture, and the section-by-section logic of a membership conversion site. Do NOT borrow: The dated visual treatment, the muddy corporate color palette, the generic photography.

3. URL: https://roundrockchamber.org/
   What to borrow: The civic pride framing and the "why join" section structure. Do NOT borrow: The lack of visual energy — this site should feel more established and decisive, clearly rooted in Whitley County.

**Synthesis:** Take Kinfolk's editorial layout discipline. Take a chamber's structural logic. Ground it all in a crisp navy-and-brick-red civic identity, the recurring open-door / path-forward motif, and genuine photographic storytelling of a real Indiana community.

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
  - Buttons: Brick red deepens to `#8E1A19` (navy buttons deepen to `#061F3D`), subtle scale-up (1.02)
  - Cards: Slight lift (translateY -4px) with shadow increase
  - Nav links: Brick-red underline slides in from left
- **Page load animation:** Subtle fade-in on hero content (300ms delay after load)
- **Transition speed:** Standard — 250ms for most transitions, 400ms for scroll-triggered reveals

---

## Imagery & Media

- **Photography style:** Real, candid, and clean — Whitley County landmarks (Columbia City courthouse, main streets, local storefronts), community gatherings, small business owners at work in their actual environment. Bright, natural light — crisp and true-to-life, not heavily warm/amber color-graded. People should look like Midwest small-town residents, not urban stock photo subjects. Where it fits naturally, favor imagery that echoes the brand motif: doorways, storefront entrances, thresholds, and paths/roads leading forward.
  - Primary sources: Open-source/public domain images of Whitley County, Columbia City, Churubusco, South Whitley, and Larwill, Indiana
  - Fill gaps with: Unsplash — search terms like "small town Indiana," "Midwest main street," "local business owner," "community gathering," "storefront door," "county courthouse"
  - Treatment: Keep a subtle navy duotone or a navy-to-transparent gradient overlay when text sits over photos — reinforces the palette and keeps copy legible. Avoid warm/sepia overlays.
  - Avoid: Generic coastal or urban imagery, people smiling at laptops in coffee shops, skyline photography, anything that doesn't feel like Northeast Indiana

- **Illustration style:** None — photography only. Exception: the open-door/path motif may appear as a simple line/graphic device (dividers, framing), drawn from the logo mark.

- **Icon set:** Phosphor Icons (outline weight) — clean, modern, pairs well with DM Sans. Use navy by default, brick red for emphasis.

- **Video usage:** None at launch — placeholder for future

---

## What to Absolutely Avoid

- NO generic blue-gradient chamber website aesthetic — navy is flat and confident, not a gradient
- NO amber, harvest gold, or forest green — those belonged to the retired palette; the accent is brick red `#B32120` only
- NO stock photography of business handshakes in conference rooms
- NO warm/sepia photo grading — keep imagery clean and true-to-life
- NO Inter, Roboto, Arial, or Playfair Display — use Lora (serif) + DM Sans (sans) + a script accent only
- NO overuse of the script accent — it is for accent words and eyebrows only, never body or long headlines
- NO brick red as a large fill or background wash — it is a ~10% accent; navy carries the dark areas
- NO recoloring, redrawing, or restretching the Open Door logo — keep proportions and colors as delivered
- NO pill-shaped or rounded buttons — keep border radius at 4–6px
- NO Lorem Ipsum or placeholder text anywhere
- NO replication of the existing whitleychamber.org design
- NO imagery that feels urban, coastal, or generic-corporate
- NO promises of business results in copy — frame everything as opportunity and access
