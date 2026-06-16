# 93 Great Suffolk Street — 1st Floor

Single-page marketing website for **Unit 2, 1st Floor, 93 Great Suffolk Street, London SE1 0BX**,
an office to let. Owner: **Waverley Equity**.

A static site built with plain HTML and CSS (no build step, no JavaScript). It is responsive and
designed for both mobile and desktop.

## Structure

| Path | Purpose |
|------|---------|
| `index.html` | The page — Home (hero), Features, Layout, Location, Contact |
| `styles.css` | All styling, brand colours, responsive layout |
| `images/optimized/` | Web-optimised photos actually served by the site |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll processing) |

> Full-resolution original photos are kept locally only (git-ignored) to keep the repo lean;
> the site references the optimised copies in `images/optimized/`.

## Contact form

The enquiry form posts to **Formspree** (`https://formspree.io/f/mkoaevdl`) with an
enquiry-type field (Managed / Conventional lease). The destination email is configured in the
Formspree dashboard.

## Deployment — GitHub Pages

Served from the repository root of the `main` branch. After enabling Pages
(Settings → Pages → Source: `main` / root), the site is available at the Pages URL.

## To do

- Replace the placeholder **stone** logo with the official **brown** Waverley Equity logo
  (high-res transparent PNG/SVG) at `images/optimized/logo.jpg`.

---
© 2026 Waverley Equity.
