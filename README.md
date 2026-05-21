# Matthew Goldsbrough GitHub Pages Site

This repository contains Matthew Goldsbrough's static one-page profile site.

## Files

- `index.html`: the page content and metadata.
- `styles.css`: the page styling.
- `robots.txt`: allows crawling and points crawlers to the sitemap.
- `sitemap.xml`: lists the canonical profile page for search engines.
- `downloads/`: unlisted download pages and downloadable PDF assets for direct links from LinkedIn or other public channels.
- Profile image is loaded from `assets/matthew-goldsbrough-ned-sketch-transparent-v2.png`.
- `.nojekyll`: tells GitHub Pages to serve the static files directly.

## GitHub Pages

The live custom domain is:

`https://matthewgoldsbrough.com/`

The GitHub Pages fallback URL is:

`https://mgoldsbrough.github.io/matthew-goldsbrough/`

## Search Console Notes

The canonical public URL is the HTTPS apex domain:

`https://matthewgoldsbrough.com/`

GitHub Pages redirects the non-canonical variants to the apex domain:

- `http://www.matthewgoldsbrough.com/`
- `http://matthewgoldsbrough.com/`
- `https://www.matthewgoldsbrough.com/`

Google Search Console may list those variants under "Page with redirect". That is expected and does not need validating as a fix while the sitemap and canonical tags use the HTTPS apex URLs.
