# Earn AED 2,000 · referral badge

Sidebar referral badge for the Skrooge client cabinet ($-coins). Maroon card, `Earn AED 2,000` headline, cream `Refer a friend` button. No medallion.

Animation, pure CSS (coins are inline SVG with a maroon "$"):
- 10 coins rain from the top, spinning, each with its own speed and offset (4–7 s loops);
- a static pile of 13 coins sits along the bottom edge; falling coins pass behind it and out of the card;
- a highlight sweeps across the button every 5.6 s;
- everything switches off under `prefers-reduced-motion`.

Open `index.html` directly, no build step. Figma: Website Pages → Page 31 → `Referral badge / S coins`.
