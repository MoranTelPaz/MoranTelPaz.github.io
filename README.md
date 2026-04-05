# MoranTelPaz.github.io

Personal website for Moran Tel-Paz — data science researcher and .

## Structure

Plain HTML + CSS, no build step required.

- `index.html` — The entire website (bio, publications, talks, media, CV)
- `stylesheet.css` — Styles (Lato font, link colors)
- `images/` — Profile photo and publication thumbnails
- `data/` — PDFs for publications and talks

## Deployment

Push to `main` triggers a GitHub Actions workflow (`.github/workflows/jekyll-gh-pages.yml`) that deploys the root directory as a static site to GitHub Pages.

## Credits

Adapted from the Omer Shubi website template, based on the [Jon Barron template](https://github.com/jonbarron/jonbarron.github.io).
