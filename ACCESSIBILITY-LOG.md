# Accessibility test log

Record of accessibility checks on lamitechrepair.pages.dev. Add a new entry after every change to the site.

| Date | Pages | What was checked | Result | Fixes made |
|---|---|---|---|---|
| 2026-11-18 | /, /privacy.html | axe-core 4.10 automated scan (WCAG 2.0/2.1/2.2 A and AA + best practices) | 1 issue | Added role="img" to review star ratings so their label is read |
| 2026-11-18 | / | WCAG 2.2.2 Pause, Stop, Hide (manual) | Fail | Added "Pause animation" button; animation also respects reduced motion |
| 2026-11-18 | / | Bypass blocks (manual) | Improved | Added "Skip to main content" link |
| 2026-11-18 | / | Keyboard tab-through on phone size; focus not obscured (2.4.11); target size (2.5.8) | 2 issues | Contact phone and email links were 23px tall, raised to 28px minimum; added scroll padding so sticky header and phone bar never cover focus |
| 2026-11-18 | / | Reflow at 320px, 200% text, text spacing (1.4.12), forced colors, prefers-contrast | Pass | Thicker focus outline; high-contrast styles added |
| 2026-11-18 | / | New search bar, device picker dialogs and water damage alert: axe scan with dialogs open, keyboard and Esc behavior, error messages | 1 issue | "Coming soon" label in the price table had low contrast after a style name clash, fixed |
| 2026-11-18 | /, /privacy.html, /accessibility.html | Full re-scan after fixes | 0 violations | none needed |
| 2026-11-18 | /, /privacy.html, /accessibility.html | html-validate 8 (recommended rules) | 8 issues | Phone numbers made non-breaking; ARIA labels moved onto elements with a role; HTML now validates clean |
| 2026-11-18 | / | Layout at 1440, 1100, 1000, 880, 768, 600, 375 and 320px | 1 issue | Top menu overflowed between about 860 and 1100px; menu now hides below 1120px (search bar and sections stay available) |
| 2026-11-18 | staging: /, /terms.html, /privacy.html, /accessibility.html | Redesign (Geist font, centered hero, category tiles, twinkling stars, new Terms page): axe scan, dialogs, keyboard focus, reflow, zoom, text spacing, 8 screen widths, html-validate | 1 issue | Top menu wrapped at 1440px with 9 links; trimmed to 6 links. All checks pass |
