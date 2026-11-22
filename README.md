# nilware.io website

Static site for GitHub Pages. Fonts: Roboto and Roboto Mono (Google Fonts).

Files: index.html, style.css, favicon.svg, railway_drone.mp3, CNAME (nilware.io).

Deploy: GitHub Pages serves branch `master` at `/` (custom domain nilware.io).
Push changes to `master`. The `main` branch only holds a redirect to the
NILWARE publisher page on Steam and is not what nilware.io serves.

Old site: the previous index.html is kept as `index-2025.html`, together with
its files (assets/, cv.html, contact.html, project pages, camp/, the PDF,
manifest.json, the logo). They stay reachable by URL and are not linked from
the new page.

style.css differs from the zip in one place: the Google Translate widget
(`.translate`) is clipped and has a smaller margin on narrow screens, so the
page has no horizontal scroll at 390 px.

Check: the contact address hello@nilware.io is a placeholder; change it if needed.
