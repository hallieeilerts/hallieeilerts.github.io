# Personal site + lab manual (Quarto)

## What's where

- `index.qmd` – homepage: short intro, then papers and posts, newest first
- `papers.yml` – your papers and talks (one entry each)
- `posts/` – blog posts, one `.qmd` file each
- `about.qmd`, `cv.qmd` – the About and CV pages
- `manual/` – the lab manual, with its own sidebar
- `_quarto.yml` – site title, top menu, manual sidebar, footer links
- `custom.scss` – font and colors

To add a manual page: create a `.qmd` file in `manual/`, then list it under
`sidebar: contents:` in `_quarto.yml`.

## Preview and publish

1. In RStudio's Build tab click **Render Website** (or run `quarto render`).
2. In the Git tab: tick all files, Commit, Push.
3. One time only, on GitHub: Settings → Pages → branch `main`, folder `/docs`.
