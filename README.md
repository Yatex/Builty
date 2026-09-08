# Builty — Real estate software studio

Three responsive landing page directions, sharing a focused portfolio: CleanCal, Staywise, Ayla, and AylaManager.

- `index.html` — **Architecture:** warm neutrals, terracotta, original isometric buildings, and illustrative product previews.
- `option-2.html` — **Editorial:** forest green, expressive serif typography, architectural artwork, and a considered product collection.
- `option-3.html` — **Blueprint:** cobalt, bold typography, a navigable product map, and a systematic portfolio.

Use the design direction links at the top of each page to compare options. Each page works without JavaScript. Alternative directions are marked `noindex` while under review.

## Preview

Run `python3 -m http.server 5173` from this directory and open `http://localhost:5173`.

## Files

- `landing.css` styles all three directions, including mobile layouts and reduced motion preferences.
- `assets/architecture.svg` and `assets/elevation.svg` are original local architectural illustrations.
- `assets/builty-real-estate.png` is the social sharing image for the focused portfolio.
- `privacy.html`, `terms.html`, and `styles.css` contain the existing legal pages and their styling.
- `assets/builty-ecosystem.*` are legacy assets, no longer used by the landing pages.

The CleanCal and Staywise previews are illustrative, not live app interfaces. Existing product availability is preserved: CleanCal and AylaManager have public links; Staywise and Ayla are private builds. Ayla and AylaManager are presented as supporting content tools without claiming property-specific functionality.

## Deployment

There is no backend, database, dependency installation, or build step. Deploy the folder as a static site. Typography loads from Google Fonts, with local serif and sans-serif fallbacks. When a final direction and public domain are chosen, add its canonical URL and sitemap, and make the social sharing image URL absolute.
