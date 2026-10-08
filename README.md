# Earn AED 2,000 · referral badge & hero

Sidebar referral badge for the Skrooge client cabinet ($-coins). Maroon card, `Earn AED 2,000` headline, cream `Refer a friend` button. No medallion.

Animation, pure CSS (coins are inline SVG with a maroon "$"):
- 10 coins rain from the top, spinning, each with its own speed and offset (4–7 s loops);
- a money-bin style vector heap fills the bottom 20% of the card: hundreds of individually placed coins at random tilt, size and shade (some edge-on, some with a $ sign), seeded so the layout is stable; the top edge is formed by the stroked coins themselves, no smooth outline; falling coins pass behind it;
- a highlight sweeps across the button every 5.6 s;
- everything switches off under `prefers-reduced-motion`.

Open `index.html` directly, no build step. Figma: Website Pages → Page 31 → `Referral badge / S coins`.

## Referral page hero

Same page shows the top block of the Referral page (1160×280): headline, subline and the "Your referral link" card. 18 larger $-coins fall across the whole width behind the content (5–9 s loops) and a money-bin heap fills the bottom 20% (seeded, 6–15 px coins). Below 1240 px the block scales down to fit.
