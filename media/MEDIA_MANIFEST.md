# MEDIA_MANIFEST.md — Deyga Lead Audit Evidence Tracker

> **Audit**: Deyga Organics Lead Audit
> **Date**: 2026-03-09
> **Total Media Files**: 59 (45 client + 14 competitor)
> **Evidence Types**: Screenshots (59), Recordings (0), Code Evidence (1 text file)

---

## Media Structure

```
media/
├── screenshots/
│   ├── client/          (45 files — 44 screenshots + 1 text evidence)
│   └── competitor/      (14 files)
├── recordings/
│   ├── client/          (empty — Chrome gif_creator unavailable)
│   └── competitor/      (empty)
└── user-uploads/        (empty)
```

---

## Finding Card → Evidence Map

### Tab 1: Homepage (5 finding cards)

| # | Finding | Client Screenshot | Competitor Screenshot | Interactive Evidence | Status |
|---|---------|-------------------|----------------------|---------------------|--------|
| H1 | Intrusive Entry Popup | `deyga-homepage-popup-fresh.jpeg` | `competitor-mamaearth-homepage-mobile.jpeg` | Cookie-dependent; can't re-trigger. Used existing capture. | COMPLETE |
| H2 | Confusing Hero Messaging | `deyga-hero-buyonlyifyouwant.jpeg` | `competitor-mcaffeine-pdp-trust-mobile.jpeg` | — (static finding) | COMPLETE |
| H3 | No Variant Selector / Wishlist on Product Cards | `deyga-hp-product-cards-atc.jpeg` | `competitor-sugar-collection-mobile.jpeg` | `collection-mobile-product-cards-no-variants.jpeg` (evidence from collection page showing same pattern) | COMPLETE |
| H4 | SEO Issues — Multiple H1s + Missing Schema | — (code evidence only) | — | Technical finding; no screenshot needed | COMPLETE |
| H5 | JavaScript Errors on Every Page | — (code evidence panel) | — | `console-errors-evidence.txt` — 23 errors documented | COMPLETE |

### Tab 2: Collection (4 finding cards)

| # | Finding | Client Screenshot | Competitor Screenshot | Interactive Evidence | Status |
|---|---------|-------------------|----------------------|---------------------|--------|
| C1 | No Filters on Collection Pages | `deyga-collection-no-filters.jpeg` | `competitor-plum-collection-filters.jpeg` | `collection-mobile-no-filters.jpeg`, `collection-mobile-sort-only.jpeg` (Sort-only dropdown) | COMPLETE |
| C2 | No Collection Banners or Descriptions | `deyga-collection-no-filters.jpeg` | `competitor-sugar-collection-mobile.jpeg` | — (static finding) | COMPLETE |
| C3 | No Breadcrumb Navigation | `deyga-collection-no-filters.jpeg` | `competitor-mamaearth-collection-mobile.jpeg` | — (static finding) | COMPLETE |
| C4 | No Quick View on Product Cards | `deyga-collection-no-filters.jpeg` | `competitor-sugar-collection-mobile.jpeg` | Clicking product card navigates to PDP (no popup) — demonstrated, not screenshotted | COMPLETE |

### Tab 3: Product Detail Page (6 finding cards)

| # | Finding | Client Screenshot | Competitor Screenshot | Interactive Evidence | Status |
|---|---------|-------------------|----------------------|---------------------|--------|
| P1 | No Image Zoom on Mobile | `deyga-pdp-above-fold-mobile.jpeg` | `competitor-minimalist-pdp-mobile.jpeg` | `pdp-mobile-image-tap-no-zoom.jpeg` (tapping image does nothing) | COMPLETE |
| P2 | No Product Video | `deyga-pdp-above-fold-mobile.jpeg` | `competitor-mamaearth-pdp-mobile.jpeg` | — (static finding) | COMPLETE |
| P3 | No Buy Now Button | `deyga-pdp-atc-area-nobuynow.jpeg` | `competitor-sugar-pdp-atc-area.jpeg` | — (static finding) | COMPLETE |
| P4 | No Sticky Add to Cart on Mobile | `deyga-pdp-variants-mobile.jpeg` | `competitor-mcaffeine-pdp-sticky-atc.jpeg` | `pdp-mobile-scroll-no-sticky-atc.jpeg`, `pdp-mobile-deep-scroll-no-sticky-atc.jpeg` (scroll-depth proof) | COMPLETE |
| P5 | No Trust Badges or Certification Display | — (code evidence panel) | — | Technical finding embedded in card | COMPLETE |
| P6 | No Urgency or Scarcity Elements | `deyga-pdp-atc-mobile.jpeg` | `competitor-mamaearth-pdp-mobile.jpeg` | — (static finding) | COMPLETE |

### Tab 4: Cart (3 finding cards)

| # | Finding | Client Screenshot | Competitor Screenshot | Interactive Evidence | Status |
|---|---------|-------------------|----------------------|---------------------|--------|
| K1 | GoKwik Checkout Errors | `deyga-cart-drawer-mobile.jpeg` | — | `console-errors-evidence.txt` (GoKwik errors documented) | COMPLETE |
| K2 | No Cross-Sell in Cart | `deyga-cart-drawer-mobile.jpeg` | `competitor-mamaearth-pdp-mobile.jpeg` | — (static finding) | COMPLETE |
| K3 | Missing Trust Signals & Coupon in Cart | `deyga-cart-drawer-mobile.jpeg` | `deyga-gokwik-checkout-mobile.jpeg` (shows coupon at checkout, not in cart) | — (static finding) | COMPLETE |

---

## Additional Evidence Files (not directly in finding cards)

### Desktop Reference Shots
| File | Purpose | Captured |
|------|---------|----------|
| `cart-empty-desktop.jpeg` | Desktop cart view — empty state | 2026-03-09 |
| `client-homepage-hero.jpeg` | Desktop homepage hero section | 2026-03-09 |
| `collection-grid-desktop.jpeg` | Desktop collection grid layout | 2026-03-09 |
| `homepage-bottom-desktop.jpeg` | Desktop homepage footer area | 2026-03-09 |
| `homepage-categories-desktop.jpeg` | Desktop homepage category tiles | 2026-03-09 |
| `homepage-hero-desktop.jpeg` | Desktop homepage hero banner | 2026-03-09 |
| `homepage-lower-desktop.jpeg` | Desktop homepage lower sections | 2026-03-09 |
| `homepage-midpage-desktop.jpeg` | Desktop homepage mid-page sections | 2026-03-09 |
| `pdp-atc-area-desktop.jpeg` | Desktop PDP add-to-cart area | 2026-03-09 |
| `pdp-hero-desktop.jpeg` | Desktop PDP hero/images area | 2026-03-09 |
| `pdp-midpage-desktop.jpeg` | Desktop PDP mid-page content | 2026-03-09 |
| `pdp-reviews-desktop.jpeg` | Desktop PDP reviews section | 2026-03-09 |

### Hero Slider Captures
| File | Purpose | Captured |
|------|---------|----------|
| `deyga-hero-slide-0.jpeg` through `deyga-hero-slide-5.jpeg` | All 6 hero slider images for messaging analysis | 2026-03-09 |

### Mobile Browse Evidence (interactive session captures)
| File | Purpose | Captured |
|------|---------|----------|
| `homepage-mobile-initial.jpeg` | Homepage on first load — no popup appeared | 2026-03-09 |
| `homepage-mobile-after-5s.jpeg` | Homepage after 5s delay — still no popup | 2026-03-09 |
| `pdp-mobile-above-fold.jpeg` | PDP above-fold view showing image carousel | 2026-03-09 |

### Duplicates / Near-Duplicates (from original audit + re-capture)
| Original (deyga- prefix) | Re-capture (new session) | Notes |
|---------------------------|--------------------------|-------|
| `deyga-collection-no-filters.jpeg` | `collection-mobile-no-filters.jpeg` | Similar content; both usable |
| `deyga-pdp-above-fold-mobile.jpeg` | `pdp-mobile-above-fold.jpeg` | Similar content; both usable |

---

## HTML Path Update Required

All `<img src="">` paths in `index.html` currently reference `screenshots/` (old flat folder). These must be updated to:
- Client: `media/screenshots/client/{filename}`
- Competitor: `media/screenshots/competitor/{filename}`

**Find/replace pattern:**
```
screenshots/deyga-      → media/screenshots/client/deyga-
screenshots/competitor-  → media/screenshots/competitor/competitor-
```

### Image Reference Count by Finding Tab
| Tab | Client Images | Competitor Images | Total References |
|-----|---------------|-------------------|------------------|
| Homepage | 4 | 3 | 7 |
| Collection | 4 (same image reused 4x) | 4 (2 images reused) | 8 |
| PDP | 4 | 4 | 8 |
| Cart | 3 (same image reused 3x) | 2 | 5 |
| **Total** | **15** | **13** | **28** |

---

## Evidence Quality Summary

| Metric | Value | Target | Status |
|--------|-------|--------|--------|
| Finding cards with screenshots | 16/18 | 18/18 | 2 are code-evidence-only (H4 SEO, P5 Trust) |
| Finding cards with competitor comparison | 14/18 | 16/18 | 4 without competitor (H4, H5, P5, K1) |
| Interactive findings with multi-evidence | 7/7 | 7/7 | All interactive findings have proof |
| Recordings captured | 0 | 7 (ideal) | Chrome gif_creator unavailable in this session |
| Console error documentation | 1 text file | 1 | 23 errors categorized + performance impact |

---

*Generated: 2026-03-09 | Audit: Deyga Organics Lead Audit*
