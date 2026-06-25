# Design System — Premium Gaming Top-up Platform

## Brand
A premium, fast, fun, and trustworthy game top-up platform supporting many games.

Keywords: modern, gaming, fast, reliable, premium, friendly, accessible.

## Principles
- Mobile-first
- Fast checkout
- Clear hierarchy
- Accessible contrast
- Reusable components
- Consistent spacing
- No copyrighted game character art

## Colors
```css
:root {
  --bg: #0B1220;
  --surface: #121826;
  --surface-2: #1A2335;
  --border: rgba(255,255,255,.12);

  --primary: #4F8CFF;
  --secondary: #8B5CF6;
  --accent: #FBBF24;
  --cyan: #3EE9FF;

  --success: #10B981;
  --warning: #F59E0B;
  --error: #EF4444;
  --info: #38BDF8;

  --text: #F8FAFC;
  --text-muted: #94A3B8;

  --gradient-primary: linear-gradient(135deg, #4F8CFF, #8B5CF6);
  --gradient-promo: linear-gradient(135deg, #8B5CF6, #FF5DAA, #FBBF24);
}
```

## Typography
- Font: Inter, system-ui, sans-serif
- H1: 48px / 1.1 / 800
- H2: 36px / 1.15 / 800
- H3: 28px / 1.2 / 700
- Body: 16px / 1.6 / 400
- Small: 14px / 1.5 / 400
- Caption: 12px / 1.4 / 500
- Button: 14–16px / 600

## Spacing
Use 4px scale: 4, 8, 12, 16, 20, 24, 32, 40, 48, 64, 80, 96.

## Radius
- Small: 8px
- Medium: 12px
- Large: 16px
- XL: 24px
- Pill: 999px

## Shadows
```css
--shadow-card: 0 12px 40px rgba(0,0,0,.35);
--shadow-glow: 0 0 28px rgba(79,140,255,.35);
--shadow-gold: 0 0 24px rgba(251,191,36,.35);
--shadow-floating: 0 24px 80px rgba(0,0,0,.45);
```

## Glassmorphism
Use for important cards only.

```css
background: rgba(18,24,38,.72);
backdrop-filter: blur(16px);
border: 1px solid rgba(255,255,255,.12);
```

## Layout
- Mobile: 4 columns
- Tablet: 8 columns
- Desktop: 12 columns
- Max container: 1280px
- Page padding: 16px mobile, 24px tablet, 32px desktop

## Breakpoints
- Mobile: 360px+
- Tablet: 768px+
- Laptop: 1024px+
- Desktop: 1280px+
- Wide: 1536px+

## Motion
- Hover: 150ms ease-out
- Modal: 200ms ease-out
- Page transition: 250ms ease-out
- Card hover: translateY(-4px)
- CTA hover: glow + slight scale

## Accessibility
- WCAG AA contrast
- Minimum touch target: 44px, prefer 48px
- Visible focus state required
- Keyboard navigation supported
- Do not rely on color alone for status
