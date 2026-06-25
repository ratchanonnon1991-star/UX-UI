# Component Spec

## Button
Height 48px. Radius 12px. Padding 16–24px.

Variants:
- Primary: blue → purple gradient
- Secondary: dark surface with border
- Ghost: transparent
- Danger: red
- Success: green

States: default, hover, focus, disabled, loading.

## Card
Use surface or glass background. Radius 20px. Padding 20–24px. Border `--border`. Hover lift allowed.

## Game Card
Contains cover, logo/name, category, badge, rating, starting price.
Badges: Popular, New, Instant, Sale.

## Package Card
Contains currency icon, amount, bonus, price, delivery time.
Selected state uses gradient border + glow.

## Payment Card
Contains payment logo/name, fee, processing time.
Selected state uses primary border and check icon.

## Input
Height 48px. Radius 12px. Dark surface. Focus border primary.
Error border red. Helper text below.

## Search Bar
Large input with icon. Sticky on mobile if needed.

## Badge
Small pill. Use semantic colors.
Examples: Best Value, Popular, Instant, Limited, VIP.

## Navbar
Logo left. Main links center. Login/CTA right. Mobile uses bottom nav or hamburger.

## Hero Banner
Large gradient/glass area with mascot/illustration, title, description, CTA, search.

## Tabs
Used for region, category, order status. Active tab uses primary gradient or border.

## Modal
Glass surface, floating shadow, close button, keyboard dismiss.

## Toast
Top or bottom. Auto dismiss. Include icon and short message.

## Timeline
Used for order tracking.
Steps: Order Created → Payment Verified → Processing → Delivered → Completed.

## Table
Used for order history. Mobile should become stacked cards.

## Empty State
Use mascot illustration and friendly message.
