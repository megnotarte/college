# College Chartered

Single-page marketing site for College Chartered, a college application management service run by Megan Notarte.

Live at [collegechartered.com](https://collegechartered.com) — deployed via GitHub Pages from `main`.

## Stack

Vanilla HTML, CSS, JS. Everything is in `index.html`. No build step, no dependencies.

## Key decisions

- **Typography:** Fraunces (headings) + Source Sans 3 (body) via Google Fonts
- **Nav:** Priority-plus pattern — JS measures available width and overflows items into a "More" dropdown
- **Services grid:** gap-as-border technique (background: var(--border), gap: 1px) — don't switch to nth-child border rules
- **Contact form:** Formspree endpoint `xykvebpw`
- **Booking link:** https://calendar.app.google/4BjvwMLCSoQvj9Aj6

## Design tokens

```css
--white: #FFFFFF;
--warm:  #EDF4F0;
--dark:  #0D1F18;
--clay:  #1A6B47;
--clay-light: #B4DECA;
--muted: #2E4038;
--border: #C4DAD0;
```

## Workflow

Megan reviews changes locally before pushing. Always ask before pushing unless she says "commit and push."
