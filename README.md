# daenuna.co — Miss Knit Landing Page

Marketing landing page for **Miss Knit** (daenuna.co), a handmade knitting and crochet product brand based in Indonesia.

Single-page site with floating WhatsApp CTA, hero, product showcase, brand story, FAQ accordion, and social links. Built and polished by Legacya Sphere.

---

## Tech Stack

Plain HTML · CSS · JavaScript — no build step, no framework.

---

## Features

- Floating WhatsApp CTA button
- Responsive hero section with animated text highlight
- Product showcase grid
- Brand story section
- FAQ accordion
- Social CTA links and footer
- Scroll-reveal animations
- Mobile-responsive layout
- 122 Playwright test cases (desktop + mobile)

---

## Project Structure

```
daenuna.co/
├── index.html           # Full single-page site (~69 KB)
├── assets/              # Images and static assets
├── tests/               # Playwright test suite (122 cases)
├── playwright.config.js
└── package.json
```

---

## Running Locally

No build step needed. Serve with any static server:

```bash
npx serve .
# or
python3 -m http.server 8000
```

---

## Playwright Tests

```bash
npm install
npx playwright install
npx playwright test
```

122 test cases covering brand identity, navigation, hero, products, story, FAQ accordion toggle, social CTA, footer, mobile layout, accessibility basics, and scroll-reveal animations.

---

## Changelog

| Date | What changed |
|------|--------------|
| May 26, 2026 | Full rebrand and polish to daenuna.co identity |
| May 26, 2026 | 122 Playwright test cases added (desktop + mobile) |
| May 26, 2026 | z-index bug fixed: hero highlight `::after` renders behind text correctly |
| May 26, 2026 | `overflow:hidden` + `padding-bottom` fix on `.hero-visual` to prevent `.hero-card-sec` bleed |
| May 26, 2026 | "Powered by Legacya.id" footer pill added (links to Instagram) |
| May 26, 2026 | WhatsApp number updated to real owner contact (+62 821-5056-2263) across all 9 `wa.me` links |

---

## Credits

Built and powered by **[Legacya Sphere](https://instagram.com/legacya.id)** · Bekasi, Indonesia · 2026
