# Academic Website Using Quarto

This repository contains my personal website deployed to GitHub Pages [athulcd.github.io](athulcd.github.io).

## Local development

Install Quarto, then run:

```bash
quarto preview
```

To create a production build locally:

```bash
quarto render
```

## GitHub Pages deployment

1. Push this repository to GitHub.
2. In GitHub, open `Settings > Pages`.
3. Set the source to `GitHub Actions`.
4. Push to the `main` branch.

The workflow at `.github/workflows/publish.yml` will build the site and deploy `_site` to GitHub Pages.
