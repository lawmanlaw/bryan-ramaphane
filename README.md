# Bryan Kutlo Ramaphane

Personal website for Bryan Kutlo Ramaphane, legal practitioner and Managing Partner of Ramaphane Law Group, Gaborone.

Static single page, no build step, no dependencies. Served from GitHub Pages.

## Structure

- `index.html` — the whole site, styles and script inline
- `assets/` — photography, organisation marks, favicon, share image
- `.nojekyll` — stops GitHub Pages running the files through Jekyll

## Notes

- Images are served as WebP with JPEG or PNG fallbacks, at several widths via `srcset`
- The firm wordmark is a trace of a low-resolution source. Replace `assets/firm-logo.svg` with the master file from the brand designer when it is available
- The intro, section reveals and logo animations are transform-only and degrade to visible content if scripting or animation fails
- `prefers-reduced-motion` disables all motion, including the intro
- The "Visit the firm" button points at the firm's Facebook page until a site exists on ramaphanelawgroup.co.bw

## Before going live

- Set an absolute `og:image` URL once the domain is known, and add a `canonical` link
- Confirm Bryan's role at the Digital Citizen Foundation and the Emma Boko Trust
- Add links to selected Business Weekly & Review columns
