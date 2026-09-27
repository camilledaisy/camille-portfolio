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

## Design notes

Colours sampled from the desktop screenshots (confirm against Framer):

| Role | Hex |
|---|---|
| Page background | `#F4F1EC` |
| Card footer / process section | `#E6E1D8` |
| Light tile / accessibility card | `#EDE7DD` / `#E9E5DE` |
| Text / primary button / about section | `#23211E` |
| Green (Communimate, accent labels) | `#3C5D58` |
| Sage tile | `#AEC5B7` |
| Mustard (tiles, User Research card) | `#CEB37E` |
| Brown (10,000 Floors) | `#775E49` |
| Slate blue (Behaviour, Inclusive Design) | `#4F5A79` |

- **Fonts:** _[to confirm: a high-contrast condensed display serif for headings; a sans (looks like Inter) for body]_
- **Hover effects:** _[to describe]_
- **Pages:** Home (Work, About, Research interests, Research process, Contact, Footer); _[Resume? case study pages?]_

## Run it locally

Needs [Node.js](https://nodejs.org) 22+.

```
npm install
npm run dev      # live preview at http://localhost:4321
npm run build    # production build into dist/
```

## Deploy (Netlify)

`netlify.toml` tells Netlify how to build the site, so no local setup is needed.
Netlify runs `npm run build` and publishes the `dist/` folder on every push.

## Plan

1. Fill in `screenshots/` and `assets/`, then the design notes above.
2. Build the home page in Astro from the screenshots, then check before building the rest.
3. Go page by page: run a local preview, compare against Framer, fix details.
4. Deploy free on Netlify, Vercel or GitHub Pages.
5. Point the custom domain to the new host, then cancel Framer's paid plan.
