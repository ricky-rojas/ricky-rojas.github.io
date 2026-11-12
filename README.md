# Ricky Rojas — personal site

Static site deployed via GitHub Pages at [ricky-rojas.github.io](https://ricky-rojas.github.io/).

## Editing content

- **Homepage intro:** `index.html`
- **About:** `about/index.html`
- **Projects:** `projects/index.html` and the featured rows in `index.html`. Each project also has its own landing page at `projects/<slug>/index.html` (short description + link to GitHub; add a demo there once one exists).
- **Teaching:** `teaching/index.html`
- **CV:** edit `cv/index.html`, then re-export `assets/files/cv.pdf` via print-to-PDF
- **SciComm:** `scicomm/index.html` is a short landing page that links out to the portfolio, hosted separately at [rickyrojas311.github.io/nsc-portfolio](https://rickyrojas311.github.io/nsc-portfolio/). The rest of `/scicomm/` (artifacts, images, PDFs) is legacy content from before the portfolio moved to its own repo — safe to delete once you've confirmed everything is live at `nsc-portfolio`.
- **Favicon:** `assets/img/favicon.svg` — same mark as the SciComm portfolio's, in the site accent red (`#8C1515`) instead of purple.

## Design reference

- Visual system: `context/styleguide.html` (open in a browser)
- Code conventions: `context/WEB_SPEC.md`
- Original build prompt: `context/BUILD_PROMPT.md`

## Hosting on GitHub Pages

The site is a GitHub Pages **user site** owned by the `ricky-rojas` organization. The repo is `ricky-rojas/ricky-rojas.github.io`, and that exact name is what makes it serve at the domain root.

- Settings → Pages: Source "Deploy from a branch," branch `main`, folder `/ (root)`.
- The SciComm portfolio is still a project site on the personal account (`rickyrojas311/nsc-portfolio`), so it stays at `rickyrojas311.github.io/nsc-portfolio/`.
- The old address `rickyrojas311.github.io` is a separate redirect-only repo on the personal account (`rickyrojas311/rickyrojas311.github.io`) that sends every old path to the same path on `ricky-rojas.github.io`.

## Deploying

Push to `main`. GitHub Pages builds automatically.
No build step, no dependencies.
