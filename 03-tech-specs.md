# 03 — Technical Specs
## Whitley County Chamber of Commerce
> Use this file when scaffolding the project, setting up integrations, or making architecture decisions.
> Paste this alongside 00-master-prompt.md at the start of any technical build session.

---

## Framework & Output

- **Platform:** GoHighLevel AI Studio (website builder)
- **Hosting:** GoHighLevel — pages are hosted natively within the GHL platform
- **CMS:** GoHighLevel CMS — Chamber staff will manage content (events, member deals, news) without touching code
- **Output format:** GoHighLevel pages — build as native GHL site pages, not as exported HTML
- **CSS approach:** GoHighLevel's native styling system; custom CSS classes where needed for typography and animation overrides
- **JavaScript:** GoHighLevel's built-in interaction tools; custom JS only for scroll animations and counter effects if not available natively

---

## Hosting & Deployment

- **Hosting target:** GoHighLevel (native platform hosting)
- **Custom domain:** Yes — whitleychamber.org (confirm DNS transfer/setup with Chamber)
- **Environment:** Static marketing pages with GoHighLevel form and CMS integration — no separate backend needed at launch

---

## Integrations

| Integration | Purpose | Notes |
|-------------|---------|-------|
| Google Analytics | Site analytics and conversion tracking | Add GA4 Measurement ID (G-XXXXXXX) to all pages — [CONFIRM ID with client] |
| GoHighLevel Forms | Membership application — placeholder at launch | Full form with digital signature and payment to be built in GHL and connected post-launch |
| GoHighLevel CMS | Events, Member to Member Deals, member spotlights, news | Chamber staff will update — keep CMS schema simple |
| GoHighLevel Email | Follow-up sequence for membership applications | Basic confirmation email at minimum; nurture sequence TBD |

---

## Forms & Data Collection

| Form | Fields | Where Data Goes | Notes |
|------|--------|----------------|-------|
| Membership Application | Business Name, Owner Name, Email, Phone, Business Address, Number of Employees (for tier selection), Business Type, Digital Signature, Payment | GoHighLevel CRM | **Placeholder at launch** — styled form shell only; GHL payment and signature integration added post-launch |
| Contact Form | Name, Business Name, Email, Phone, Message | GoHighLevel CRM / email notification | Active at launch |
| Email Capture (optional) | Email, First Name | GoHighLevel email list | For visitors not ready to apply — "Stay in the loop" opt-in |

---

## Authentication

- **Auth needed:** No — this is a public marketing and conversion site
- **Member portal:** Not in scope for launch. Future phase may include a GHL-powered member login area for accessing deals and resources.

---

## CMS & Content Management

- **CMS needed:** Yes
- **Platform:** GoHighLevel CMS
- **Who updates content:** Chamber staff (non-technical) — build with this in mind; keep field structures simple
- **Content types managed via CMS:**
  - Events (title, date, time, location, description, registration link, image)
  - Member to Member Deals (business name, deal description, expiration, logo, category)
  - Member Spotlights (business name, owner name, quote, photo, category)
  - News / Blog posts (title, date, body, image)
- **Localization:** No — English only

---

## Performance & SEO

- **SEO priority:** Important — local SEO is a key driver for a county chamber
- **Image optimization:** Yes — compress all images, use modern formats where GHL supports them
- **Sitemap:** Yes — ensure GHL generates and submits sitemap to Google Search Console
- **Robots.txt:** Yes — standard allow-all
- **Structured data:** Yes — add LocalBusiness and Organization schema markup for the Chamber itself
- **Google Search Console:** Connect and verify at launch [CONFIRM with client]

**Local SEO priorities:**
- Page titles and meta descriptions must include "Whitley County," "Columbia City, Indiana," and "Chamber of Commerce"
- About page and footer must include full NAP (Name, Address, Phone) consistently
- Google Business Profile must be claimed, verified, and consistent with site data [CONFIRM status with Chamber]

---

## Browser & Device Support

- **Minimum browser support:** Last 2 versions of Chrome, Firefox, Safari, Edge
- **Mobile-first:** Yes — design and build mobile breakpoints first
- **Accessibility target:** WCAG AA — this is a public civic organization; accessibility is important
  - Sufficient color contrast on all text/background combinations (verify navy on cream, amber on navy)
  - All images have descriptive alt text
  - Form fields have visible labels
  - Keyboard navigation works throughout

---

## Known Constraints

- The membership application join flow is a **placeholder at launch** — the page and form shell should be built and styled, but GoHighLevel payment processing and digital signature integration will be connected in a separate phase
- Do not use any paid third-party npm packages or external services beyond what is listed above
- The site must function as a public, no-login-required experience at launch — no gated content
- GoHighLevel's platform constraints apply — do not design interactions or layouts that require custom server-side logic
- All copy must be reviewed before launch to ensure no guarantees of business outcomes are made — this is a quasi-governmental entity with compliance considerations
