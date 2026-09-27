# Camille Portfolio

Rebuild of my Framer portfolio as a static site (planned stack: **Astro**).

## Folder setup

```
screenshots/
  desktop/   full-page desktop shots of every page (e.g. home.png, about.png, project-x.png)
  mobile/    matching mobile shots, same file names
assets/
  images/    project and page images, exported from Framer at full resolution
  logo/      logo files (SVG preferred, plus PNG)
  icons/     favicon, social icons, UI icons (SVG preferred)
```

Name each page's screenshots the same way in `desktop/` and `mobile/` so they pair up.

## Design notes (fill in before building)

- **Fonts:** _[names + weights, and whether they're Google Fonts or self-hosted files]_
- **Colours:** _[hex codes: background, text, accent, etc.]_
- **Hover effects:** _[e.g. cards lift 4px with shadow, links underline on hover]_
- **Pages:** _[list every page]_

## Plan

1. Fill in `screenshots/` and `assets/`, then the design notes above.
2. Build the home page in Astro from the screenshots, then check before building the rest.
3. Go page by page: run a local preview, compare against Framer, fix details.
4. Deploy free on Netlify, Vercel or GitHub Pages.
5. Point the custom domain to the new host, then cancel Framer's paid plan.
