# AHLAM — Housewarming Invitation

A premium, original redesign of the AHLAM housewarming invitation site.

## Structure
```
index.html        Semantic markup for all sections
css/style.css      Design system (tokens, layout, animation, responsive)
js/script.js       Loader, nav, countdown, scroll reveal, parallax, RSVP, audio
assets/house.jpeg  Home photo (hero + "Our Home" section)
assets/music.mp3   Optional background audio
```

## Notes
- RSVP form posts to the same Google Apps Script endpoint as before — no backend changes needed.
- Countdown target: 14 August 2026, 11:30 AM IST (edit in `js/script.js`).
- Design tokens (colors, type, spacing) are centralized as CSS custom properties at the top of `css/style.css` — change the palette or fonts there.
- Respects `prefers-reduced-motion`.

## Deploy
Static site — upload as-is to Vercel, Netlify, Cloudflare Pages, or any static host. No build step required.
