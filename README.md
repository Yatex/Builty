# Builty — Real estate software studio

A responsive static landing page using the selected architectural design: warm neutrals, terracotta, an original isometric illustration, and illustrative product previews.

## Products

- **CleanCal** — property cleaning coordination for Airbnb and short-term rentals, publicly available at https://cleancal.org/.
- **Ayla** — an AI guest assistant available via Telegram, answering questions using owner-approved property knowledge. Publicly available at https://aylamanager.com/.

Both product previews are illustrative, not live app interfaces.

## Preview

Run `python3 -m http.server 5173` from this directory and open `http://localhost:5173`.

## Files

- `index.html` contains the landing page and product metadata.
- `landing.css` contains the landing page styling, mobile layouts, and reduced motion preferences.
- `assets/architecture.svg` is the original architectural illustration.
- `assets/favicon.svg` uses the same building symbol and colors as the page wordmark.
- `assets/builty-real-estate.png` is the social sharing image.
- `privacy.html`, `terms.html`, and `styles.css` contain the legal pages and their styling.

## Deployment

There is no JavaScript, backend, database, dependency installation, or build step. Deploy the folder as a static site. Typography loads from Google Fonts, with local serif and sans-serif fallbacks. When the public domain is chosen, add its canonical URL and sitemap, and make the social sharing image URL absolute.
