# KumaBox website

Source of the KumaBox project site. The page is a single static `index.html`
(bilingual: English / 简体中文) with no build step.

- Project: https://github.com/kgpp34/KumaBox
- Deploys to GitHub Pages on every push to `main` via `.github/workflows/pages.yml`.

## One-time setup

In this repository: **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Preview locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Updating benchmark numbers

The performance section lives in `index.html` (section `#performance`): the table
rows and the `rows` array in the script at the bottom of the page. Keep both in sync.
