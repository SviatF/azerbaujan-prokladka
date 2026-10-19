# Azerbaijan Football Pre-Landing Page

English-language mini landing page for the **90+ Azerbaijan** football YouTube channel.

## Files

- `index.html` — English-language page copy, accessibility labels and SEO metadata
- `styles.css`, `compact.css`, `logo-fix.css` — original responsive design
- `script.js` — YouTube and Telegram destinations, click tracking and one-screen scaling
- `photo_2026-04-15_00-22-03.jpg` — existing channel logo
- `logo_turkey.svg` — existing favicon asset, now with English text
- `favicon.svg` — alternate 90+ favicon

## Destinations

- YouTube: https://www.youtube.com/@MelBetAzərbaycan
- Telegram: https://t.me/+O9GSNhMZ8XQ4MTdk

Both links and the `youtube_channel_click` / `telegram_channel_click` analytics events remain unchanged.

## Deployment

Static site for Cloudflare Workers/Pages via `wrangler.jsonc`. No build step is required.
