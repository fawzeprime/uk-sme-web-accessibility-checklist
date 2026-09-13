# UK SME Web Accessibility Checklist (WCAG 2.2 AA)

A free, practical checklist for UK small business owners who want to make their websites accessible and legally compliant.

## Why This Matters for UK Businesses

- **Equality Act 2010** requires "reasonable adjustments" for disabled users
- **European Accessibility Act** (2026) creates additional digital service requirements
- **95.9%** of the top one million homepages fail basic WCAG 2 checks (WebAIM Million 2026)
- The **Purple Pound** (disabled consumer spending power) is worth **£274 billion/year** in the UK

## The 20 Most Common Failures (From 100+ UK SME Audits)

### Critical (Fix Immediately)

| # | Issue | Found On | Fix |
|---|-------|----------|-----|
| 1 | Missing alt text on images | 81% of sites | Add descriptive `alt` attributes to all informative images |
| 2 | Missing/incorrect heading structure | 78% of sites | Use single H1, nest H2→H3→H4 logically |
| 3 | Colour contrast below 4.5:1 | 65% of sites | Use [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) |
| 4 | Form fields without labels | 72% of sites | Associate `<label>` elements with every input |
| 5 | Missing skip navigation link | 60% of sites | Add "Skip to main content" link at top of page |

### High Priority (Fix This Week)

| # | Issue | Found On | Fix |
|---|-------|----------|-----|
| 6 | No visible focus indicators | 58% of sites | Add `:focus-visible` styles with 2px+ outline |
| 7 | Keyboard navigation traps | 58% of sites | Test all modals, dropdowns, carousels with Tab key |
| 8 | Missing page language attribute | 45% of sites | Add `lang="en"` to `<html>` tag |
| 9 | Auto-playing media | 35% of sites | Remove autoplay or provide pause/stop controls |
| 10 | Missing form error identification | 50% of sites | Associate error messages with specific form fields |

### Medium Priority (Fix This Month)

| # | Issue | Found On | Fix |
|---|-------|----------|-----|
| 11 | Missing ARIA landmarks | 40% of sites | Add `role="navigation"`, `role="main"`, etc. |
| 12 | Inconsistent navigation | 30% of sites | Keep navigation structure identical across pages |
| 13 | Missing breadcrumb navigation | 55% of sites | Add structured breadcrumbs with schema markup |
| 14 | Touch targets too small | 45% of sites | Minimum 44x44px for interactive elements |
| 15 | Missing table headers | 38% of sites | Use `<th>` and `scope` attributes |

### Lower Priority (Schedule)

| # | Issue | Found On | Fix |
|---|-------|----------|-----|
| 16 | Missing link purpose | 25% of sites | Avoid "click here" — use descriptive link text |
| 17 | Missing sitemap | 60% of sites | Create HTML and XML sitemaps |
| 18 | No reduced motion option | 70% of sites | Use `prefers-reduced-motion` media query |
| 19 | Missing live region announcements | 40% of sites | Add `aria-live` for dynamic content updates |
| 20 | Insufficient error prevention | 35% of sites | Add confirmation steps for financial/legal transactions |

## Quick Testing Tools

- **[axe DevTools](https://www.deque.com/axe/devtools/)** — Browser extension for automated testing
- **[WAVE](https://wave.webaim.org/)** — Web-based accessibility evaluator
- **[Lighthouse](https://developer.chrome.com/docs/lighthouse/)** — Built into Chrome DevTools (F12)
- **[Colour Contrast Checker](https://webaim.org/resources/contrastchecker/)** — Test colour combinations
- **[HeadingsMap](https://addons.mozilla.org/en-GB/firefox/addon/headingsmap/)** — Visualise heading structure

## Manual Testing Checklist

- [ ] Navigate entire site using only keyboard (Tab, Shift+Tab, Enter, Escape)
- [ ] Test with screen reader (NVDA on Windows, VoiceOver on Mac)
- [ ] Check all images have meaningful alt text
- [ ] Verify colour contrast on all text elements
- [ ] Test forms without a mouse
- [ ] Check focus is visible on all interactive elements
- [ ] Verify error messages are associated with form fields
- [ ] Test at 200% browser zoom
- [ ] Check with browser animations disabled

## Professional Accessibility Audits

For a comprehensive WCAG 2.2 AA assessment, consider a professional audit. [Daedalus Design](https://daedalusdesign.co.uk) offers:

- **[47-point monthly accessibility audits](https://daedalusdesign.co.uk/services/accessibility-audit)** from £19.99
- **[AI-powered web design](https://daedalusdesign.co.uk/packages)** with accessibility built in from £299
- **[Free website audit](https://daedalusdesign.co.uk/audit)** covering accessibility, SEO, performance, and security

## Contributing

Found an issue or want to add to this checklist? Open an issue or submit a PR.

## License

MIT — free to use, share, and adapt with attribution.

---

*Created by [Daedalus Design](https://daedalusdesign.co.uk), a UK web design agency in Denbighshire, North Wales specialising in AI-powered accessible websites for small businesses.*
