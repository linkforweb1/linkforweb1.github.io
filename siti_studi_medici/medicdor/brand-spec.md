# Brand spec — Medicdor

Extracted from logo (mp79o1h2-logo.png) + header image (mp79o1gz-header-img.png).

## Color tokens

```css
:root {
  --bg:      oklch(98.5% 0.005 260);  /* very light blue-white */
  --surface: oklch(100% 0 0);          /* pure white */
  --fg:      oklch(18% 0.01 260);      /* near-black, blue tint */
  --muted:   oklch(50% 0.02 260);      /* mid grey */
  --border:  oklch(90% 0.008 260);     /* light grey-blue */
  --accent:  oklch(55% 0.22 265);      /* brand blue — rgb(37,103,255) */
  --accent2: oklch(75% 0.08 260);      /* light periwinkle — rgb(160,180,240) */
  --accent3: oklch(70% 0.12 290);      /* purple-blue — rgb(200,160,240) */
}
```

## Font stacks

- **Display**: `'Inter', -apple-system, BlinkMacSystemFont, system-ui, sans-serif`
- **Body**: `'Inter', -apple-system, BlinkMacSystemFont, system-ui, sans-serif`

One-family system — clean, precise, professional. Weight contrast (Bold for headings, Regular for body) provides hierarchy without a second family.

## Layout posture

- Clean, generous whitespace
- Subtle borders, minimal shadows
- Single accent (brand blue) for CTAs, links, key highlights
- 12px border-radius on cards for softness (not cold)
- Responsive grid: 12-column on desktop, 6 on tablet, 1 on mobile
- Tabular numerics for stats/phone
