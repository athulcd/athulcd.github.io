# Quarto Academic Website

This repository contains a simple Quarto website configured for deployment to GitHub Pages.

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
