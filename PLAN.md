# Pittsburgh Maintenance Solutions — Wireframe Prototype Plan

**Domain:** pghms.com · **Stack:** Plain HTML + CSS · **Type:** Wireframe prototype (black text / white background)
**Reference:** https://ppsntx.com · **Fonts:** Archivo (Google Fonts, multiple weights) · **Logo:** `assets/logo.svg` (black)

---

## 1. Positioning (drives all copy)

- **Audience:** Property managers, landlords, investors, small REITs, asset managers. NOT homeowners, NOT tenants, NOT one-off jobs.
- **Voice:** Operational, not contractor. "The maintenance department for professional landlords." Speaks to the customer's time and headaches, not "30 years in business."
- **Working tagline:** "For Landlords, By Landlords" (alternates in client notes if this changes).
- **Personality:** Professional, organized, dependable, responsive, systems-driven. Not handyman, not cheap, not flashy.
- **Key messages:** We solve headaches · Systemized, not customized · We don't do everything — we serve professional landlords best · One point of contact across trades.

## 2. Sitemap & Navigation

Main nav (6 items):

1. **Home** — `index.html`
2. **Services** — `services/index.html` (overview: intro + card grid) with one subpage per service
3. **About (Why Us)** — `about.html`
4. **Become a Customer** — `become-a-customer.html` (prospective customer application)
5. **Work Order** — `work-order.html` (current customers)
6. **Become a Vendor** — `become-a-vendor.html` (subcontractors; Rob providing form fields — placeholder until then)

### Service subpages (ppsntx.com list, adjusted per discovery notes)

| # | Service | Note |
|---|---------|------|
| 1 | Make Ready / Unit Flips | Framed as "Unit Flips" per notes |
| 2 | Handyman & General Repairs | |
| 3 | Plumbing | |
| 4 | Electrical | |
| 5 | HVAC | |
| 6 | Roofing | Copy notes: subbed out — "we manage the subs" |
| 7 | Snow Removal | **Added** per discovery notes |
| 8 | Section 8 Punch List | **Added** per discovery notes |
| 9 | Emergency Response | |
| 10 | Preventative Maintenance | |
| 11 | Property Inspections | |
| 12 | Multifamily Maintenance | |
| 13 | Project / Trade Coordination | |
| 14 | Lawn Maintenance | From reference site — confirm with client |
| 15 | Garage Door Repair | From reference site — confirm with client |

**Removed:** Fencing (explicit "no fencing" in discovery notes).
**Not offered (About page content, not pages):** New construction, high-end rentals.

Total: ~21 pages.

## 3. Page Blueprints (modeled on ppsntx.com)

### Home
1. Hero — H1 + tagline, subhead, dual CTA (Become a Customer / Submit a Work Order), trust badges (Landlord-Focused · Systemized · Licensed & Insured)
2. Quick service link bar
3. Differentiators grid (4) — headache removal, one point of contact, systemized process, landlord-first
4. "Why landlords choose PMS" grid (6)
5. 5-step process (work order → scope → approval → dispatch → close-out docs)
6. Who we serve / who we don't (teaser → About)
7. Services card grid (all services → subpages)
8. Coverage area — Pittsburgh + surrounding (confirm list with client)
9. Final CTA band
10. Footer — 3 columns: contact / services / company, logo, copyright

### Services overview
Intro (operational positioning) + full card grid → subpages.

### Service subpage (template, repeated ×15)
Breadcrumb · H1 + intro · what's included (bullets) · how it works for landlords · photo slot · related services · CTA band.

### About (Why Us)
Why us narrative · **Matrix table**: What we do / Who we do it for vs. What we don't do / Who we don't serve (new construction, high-end rentals — with the "why") · "We don't do everything" positioning · CTA. *(Rob providing matrix content — build with draft content.)*

### Contact pages (×3)
Each: intro explaining who the page is for, placeholder form (non-functional), phone/email fallback, cross-links to the other two pathways.

## 4. Build Standards

- **Structure:** flat HTML files + `/services/` subfolder; shared `css/styles.css`; nav/footer markup duplicated per page (no templating in plain HTML).
- **Typography:** Archivo via Google Fonts — 400 (body), 500/600 (UI, subheads), 700–900 (display). Clear type scale, generous white space.
- **Wireframe palette:** black text, white background, grays for placeholder boxes, borders, and secondary text. No brand color yet (navy/charcoal + accent comes later per client notes).
- **Imagery:** AI-generated via Magnific MCP (Recraft V4.1). Style locked 2026-07-21: **full-color cinematic editorial photography, teal-and-orange LUT, magic-hour light**, keyed to the navy/blue brand palette. ~60 credits per image. Files in `assets/img/` as JPEG; gray labeled boxes remain as placeholders until each image lands.
- **Responsive:** simple mobile breakpoint (stacked nav, single-column grids). Wireframe-grade, not production-grade.
- **Logo:** black SVG in header (linked home) and footer.

## 5. Execution Phases

- [x] **Phase 0 — Foundation:** folder structure, `styles.css` (reset, type scale, layout utilities, header/footer, buttons, cards, form styles, placeholder-box styles), Archivo wired up
- [x] **Phase 1 — Home:** full homepage with drafted copy
- [x] **Phase 2 — Services:** overview page + all 15 subpages with service-specific copy
- [x] **Phase 3 — About:** narrative + matrix table (draft content)
- [x] **Phase 4 — Contact ×3:** Become a Customer, Work Order, Become a Vendor (placeholder forms)
- [x] **Phase 5 — Imagery:** all 18 images generated via Magnific (cinematic teal/orange magic-hour style) and placed
- [x] **Phase 6 — QA:** link check, structural checks, responsive pass, copy audit against client notes — all passing (2026-07-21)

## 6. Open Items / Client Dependencies

| Item | Owner |
|------|-------|
| Confirm final service list (esp. Lawn Maintenance, Garage Door) | Client (Rob) |
| Matrix table content | Rob |
| Become a Vendor form fields | Rob |
| Confirm tagline choice | Client |
| Coverage area / neighborhoods list | Client |
| Phone number + email for CTAs and footer | Client |
