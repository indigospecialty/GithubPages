# Indigo Specialty Products – HydroForce

Static website for the HydroForce soil surfactant range from Indigo Specialty Products, Rocklea, Queensland. Hosted on GitHub Pages.

- Live site: https://indigospecialty.github.io/GithubPages/
- Main website: https://indigospecialty.com.au/

## Structure

| Path | What it is |
| --- | --- |
| `index.html` | Home page |
| `field-notes/` | Articles (index and posts) |
| `assets/css/style.css` | All styles |
| `assets/images/` | Images (JPG with WebP copies) |
| `404.html` | Not-found page |
| `robots.txt`, `sitemap.xml` | Search engine files |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publishing

1. This folder is the `GithubPages` repository in the `indigospecialty` account, so the site is served at `https://indigospecialty.github.io/GithubPages/`.
2. In the repository, **Settings → Pages** is set to deploy from the `master` branch, root folder.
3. If the repository is ever renamed (for example to `indigospecialty.github.io`), update the canonical links, Open Graph URLs, `sitemap.xml`, `robots.txt` and the root links in `404.html` to the new address.
4. Search engines only read `robots.txt` at the root of a domain, so for this project site submit `sitemap.xml` in Google Search Console instead.

No build step is needed.
