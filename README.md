# lta-website

Public website for LTA Engineering: HMI for embedded applications. Plain HTML and CSS, no build step, published with GitHub Pages.

## Structure

- `index.html`: the page
- `css/styles.css`: styles; colors and fonts are CSS variables at the top
- `images/`: images the site shows

## Rules for this repository

- **Everything here is public.** Never add client names, client designs, screenshots or anything from client projects without the client's written OK.
- **Web images, fonts and video are normal git files, not Git LFS.** GitHub Pages does not serve LFS files; they show up broken on the live site. `.gitattributes` is set up for this.
- **Export for the web before committing.** Keep images small (compressed PNG/JPG/WebP, sized for the screen), prefer WOFF2 for fonts, and avoid large video. GitHub rejects files over 100 MB and Pages sites are capped at 1 GB.
- **Design sources (PSD, AI, Figma, TIFF) belong elsewhere.** If one is ever kept here it goes through LFS, but it will be public.
- **Third-party fonts, icons and stock images need a license that allows web use.** Note each one's license in `LICENSES.md`.

## Preview locally

Open `index.html` in a browser.

## Conventions

- Default branch is `master`.
- Pushing to `master` updates the live site within a few minutes.
