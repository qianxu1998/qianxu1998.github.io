# qianxu1998.github.io

Personal academic homepage of Jiantao Liu, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and deployed to GitHub Pages at <https://qianxu1998.github.io>.

## How it deploys

Every push to `main` triggers the **Deploy site** GitHub Actions workflow (`.github/workflows/deploy.yml`), which builds the site and publishes it to the `gh-pages` branch. GitHub Pages serves that branch. No local Ruby/Jekyll setup is needed.

## Where to edit content

| What | File |
| --- | --- |
| Bio, photo layout, subtitle | `_pages/about.md` |
| Profile photo | `assets/img/prof_pic.jpg` (replace the file) |
| News items | `_news/*.md` (one file per item) |
| Publications | `_bibliography/papers.bib` (`selected={true}` shows on home page) |
| CV content | `_data/cv.yml` |
| CV PDF download | put your PDF in `assets/pdf/` and update `cv_pdf` in `_pages/cv.md` and `_data/socials.yml` |
| Email / GitHub / Scholar links | `_data/socials.yml` |
| Site title, name, SEO | `_config.yml` |

Placeholder spots are marked with `TODO`. Search the repo for `TODO` to find everything that still needs your real content.

## Docs

The full theme documentation is in `docs/` (`CUSTOMIZE.md`, `FAQ.md`, `INSTALL.md`).
