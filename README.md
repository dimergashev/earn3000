# Earn AED 2,000 · referral badge

Sidebar referral badge for the Skrooge client cabinet (S-coins). Maroon card, `Earn AED 2,000` headline, cream `Refer a friend` button. No medallion.

Animation, pure CSS (coins are inline SVG with a maroon "S"):
- 10 coins rain from the top, spinning, each with its own speed and offset (4–7 s loops);
- a pile grows along the bottom edge: 13 coins appear one by one (~1.1 s apart) over a 14 s cycle, then it resets;
- a highlight sweeps across the button every 5.6 s;
- everything switches off under `prefers-reduced-motion`.

Open `index.html` directly, no build step. Figma: Website Pages → Page 31 → `Referral badge / S coins`.
