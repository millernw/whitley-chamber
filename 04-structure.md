# 04 — Site Structure & Layout
## Whitley County Chamber of Commerce
> Use this file when building navigation, page layouts, or any structural scaffolding.
> Paste this alongside 00-master-prompt.md when starting a new page or layout session.

---

## Site Map

| Page | Route | Priority | Notes |
|------|-------|----------|-------|
| Home | `/` | P1 | Primary conversion page — most visitors will enter and convert here |
| Why Join | `/why-join` | P1 | Deeper benefit detail for visitors who want more before applying |
| Member Benefits | `/member-benefits` | P1 | Full breakdown of what membership includes |
| Member to Member Deals | `/member-deals` | P1 | Showcase of active member deals; requires CMS connection |
| Events | `/events` | P1 | Upcoming Chamber events; requires CMS connection |
| Join / Apply | `/join` | P1 | Membership application — placeholder form at launch |
| About | `/about` | P1 | Chamber history, mission, team, and new chapter narrative |
| Contact | `/contact` | P1 | Contact form + Chamber location and info |
| Member Directory | `/directory` | P2 | Browseable list of member businesses — builds FOMO for non-members |
| Member Spotlights | `/spotlights` | P2 | Featured member stories — CMS-driven |
| News / Blog | `/news` | P2 | Chamber news, local business updates, community stories |
| News Post | `/news/[slug]` | P2 | Individual post template |
| Resources | `/resources` | P2 | Links and tools for member businesses |
| Privacy Policy | `/privacy` | P1 | Legal — required for any site collecting form data |
| Terms of Service | `/terms` | P1 | Legal — standard |

---

## Navigation

**Header nav:**
- **Style:** Sticky top bar — transparent over the hero, becomes solid navy (`#1B2D52`) with white text on scroll
- **Logo position:** Left — Chamber logo pulled from existing site, modernized in context
- **Nav links (desktop):** Why Join | Member Benefits | Member to Member Deals | Events | About | Contact
- **CTA in nav:** Yes — "Join the Chamber" button in amber (`#D4882A`) with white text, always visible
- **Mobile nav:** Hamburger menu → full-screen overlay in navy with white links and amber CTA button
- **Transparent on hero?** Yes — transparent over hero, transitions to solid navy on scroll (250ms ease)

---

## Homepage Section Order

1. **Hero**
   - Layout: Full-bleed background photo of Whitley County (Columbia City courthouse or main street), warm overlay tint. Large Playfair Display headline left-aligned, DM Sans subheadline below, two CTA buttons stacked on mobile / side by side on desktop. Subtle parallax on background image.
   - Formula: PAS — headline names the problem (isolation), subheadline agitates and pivots, CTA is the solution
   - Goal: Hook the business owner emotionally in the first 3 seconds and drive to the primary CTA

2. **Trust Bar / Member Logos**
   - Layout: Full-width band in light warm gray (`#E2DDD6`). Marquee/horizontal scroll of current member business logos. Caption above: "Proudly serving Whitley County businesses." No hard sell — just proof of presence.
   - Goal: Establish social proof and FOMO immediately below the fold

3. **The Problem — You Deserve to Be Seen**
   - Layout: Two-column on desktop (bold left-side stat/pull quote, right-side paragraph copy). Single column on mobile. This section names the isolation problem directly before offering the solution.
   - Formula: PAS (continues from hero — deepens the agitate)
   - Goal: Make the visitor feel understood before we make the pitch

4. **Why Join — Member Benefits**
   - Layout: 3-column card grid on desktop, 1-column on mobile. Each card: Phosphor icon (amber), bold short headline, 2-sentence FAB description. Cards use subtle hover lift animation.
   - Formula: FAB
   - Goal: Communicate the five core membership benefits clearly and quickly

5. **Member to Member Deals — Feature Callout**
   - Layout: Full-bleed section with navy background (`#1B2D52`), amber and white typography. Left side: bold headline + copy. Right side: styled membership card mockup graphic. CTA button in amber.
   - Formula: AIDA — build desire for the card before revealing it's a membership perk
   - Goal: Highlight the most tangible, differentiated membership perk and drive interest

6. **How It Works**
   - Layout: 3-step horizontal layout on desktop (numbered icons, step title, 1-sentence description with connecting line between steps). Vertical stacked on mobile. Section header centered.
   - Formula: StoryBrand 3-step plan — Join → Connect → Grow
   - Goal: Remove confusion about what happens after clicking "Join" — reduce friction

7. **Testimonials**
   - Layout: 3-column card carousel on desktop (manual navigation, swipe on mobile). Each card: large opening quote mark in amber, quote text in Playfair Display italic, member name and business in DM Sans below. Cards have warm surface background.
   - Formula: Pure social proof
   - Goal: Build trust with real member voices
   - Note: Use placeholder testimonial cards at launch with [DRAFT] markers — replace with real quotes before go-live

8. **Stats / Social Proof Band**
   - Layout: Full-width band in amber (`#D4882A`) with white text. 3 large animated counter stats side by side: member count, years serving the community, annual events. Each with a label below.
   - Goal: Quantify the Chamber's presence and momentum
   - Note: Confirm actual numbers with Chamber staff before launch

9. **Pricing — Membership Tiers**
   - Layout: Clean table layout on desktop. Alternating warm white and surface rows. Business size in one column, annual price in the other, short "who it's for" description in a third. Anchor note below table: "Starting at less than $8/month." CTA button below table.
   - Formula: AIDA — subheadline builds desire ("membership that fits your business"), table provides clarity, CTA converts
   - Goal: Show pricing clearly and make the value feel obvious at every tier

10. **FAQ**
    - Layout: Accordion, single column, max-width 800px centered. One open at a time. Warm divider lines. Question in DM Sans semi-bold, answer in regular weight.
    - Formula: PAS reversal — each Q names an objection, the A resolves it warmly
    - Goal: Handle the six most common objections before they become reasons not to join

11. **Final CTA Band**
    - Layout: Full-bleed section with deep navy background and large Playfair Display headline centered. Single amber CTA button. No other distractions.
    - Headline: "Whitley County Is Better When You're Part of It."
    - CTA: Join the Chamber Today
    - Formula: Compressed AIDA
    - Goal: Final conversion push — visitors who made it this far are close

12. **Footer**
    - See Footer section below

---

## Footer

**Structure:** 4-column on desktop, stacked on mobile

- **Column 1 — Brand:** Chamber logo + tagline "You Shouldn't Have to Build It Alone." + short description (1 sentence). Social media icons below (Facebook, Instagram, LinkedIn — confirm active accounts with Chamber).
- **Column 2 — Membership:** Why Join, Member Benefits, Member to Member Deals, Pricing, Join / Apply
- **Column 3 — Chamber:** About, Events, Member Directory, Member Spotlights, News, Resources
- **Column 4 — Contact:** Full NAP (Name, Address, Phone, Email) for Columbia City office. Link to Contact page. Link to Google Maps (confirm address).
- **Bottom bar:** © 2025 Whitley County Chamber of Commerce. All rights reserved. | Privacy Policy | Terms of Service
- **Newsletter:** Optional — "Stay in the loop" email capture field in footer. Single field + button.

---

## Component Needs

**Page-specific:**
- [ ] Membership card mockup graphic (for Member to Member Deals section and page)
- [ ] Member logo marquee / scrolling trust bar
- [ ] Animated stat counter (triggers on scroll into view)
- [ ] Membership tier pricing table
- [ ] Member deal card (CMS-driven — business name, deal, logo, category tag)
- [ ] Event card (CMS-driven — title, date, location, image, registration CTA)
- [ ] Member spotlight card (CMS-driven — photo, name, business, quote)
- [ ] 404 page (warm, on-brand — direct visitor back to Home or Join)

---

## Responsive Behavior

| Section | Mobile (< 768px) | Tablet (768–1024px) | Desktop (> 1024px) |
|---------|------------------|---------------------|---------------------|
| Hero | Stacked, full bleed, text centered | Text left, image behind | Full bleed parallax, text left |
| Trust Bar | Horizontal marquee scroll | Horizontal marquee scroll | Horizontal marquee scroll |
| Why Join cards | 1 column | 2 columns | 3 columns |
| Member to Member Deals | Stacked, card below copy | Side by side | Side by side, wider |
| How It Works | Vertical stacked steps | Horizontal 3-step | Horizontal 3-step with connectors |
| Testimonials | Single card, swipe | 2 cards | 3-card layout |
| Stats Band | Stacked vertically | 3 across | 3 across, larger type |
| Pricing Table | Card stack, one tier per card | Table layout | Full table layout |
| FAQ | Single column accordion | Single column, wider | Single column, max 800px centered |
| Final CTA | Centered, stacked | Centered | Full bleed, centered |
| Footer | Stacked, links expanded | 2 columns | 4 columns |

---

## Interaction Patterns

- **Scroll behavior:** Smooth scroll
- **Sticky elements:** Navigation bar only
- **Modal triggers:** No modals at launch
- **Carousel/slider behavior:** Manual navigation on desktop, swipe on mobile. No auto-play.
- **Accordion behavior:** One open at a time (FAQ)
- **Back to top button:** Yes — appears after scrolling past the hero, bottom-right, amber color
- **Scroll-triggered animations:** Fade-up on section entry, staggered within sections (headline → body → CTA)
- **Member logo marquee:** Continuous horizontal scroll, pauses on hover

---

## Whitespace & Density

- **Section vertical padding:** Generous — 120px desktop, 72px mobile
- **Card internal padding:** Standard — 24–32px
- **Line height (body):** Open — 1.7
- **Overall feel:** Open and airy — editorial, not dense. Each section breathes. Content is intentional, not packed.
