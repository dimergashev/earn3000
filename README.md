# Earn AED 2,000 · referral badge

Sidebar referral badge for the Skrooge client cabinet ($-coins). Maroon card, `Earn AED 2,000` headline, cream `Refer a friend` button. No medallion.

Animation, pure CSS (coins are inline SVG with a maroon "$"):
- 10 coins rain from the top, spinning, each with its own speed and offset (4–7 s loops);
- a money-bin style vector heap fills the bottom 20% of the card: hundreds of individually placed coins at random tilt, size and shade (some edge-on, some with a $ sign), seeded so the layout is stable; falling coins pass behind it;
- a highlight sweeps across the button every 5.6 s;
- everything switches off under `prefers-reduced-motion`.

Open `index.html` directly, no build step. Figma: Website Pages → Page 31 → `Referral badge / S coins`.
