# Hugo + Blowfish + GitHub Pages

This repository contains a Hugo site using the Blowfish theme and a GitHub
Actions workflow for GitHub Pages deployment.

## Local preview

```bash
hugo server
```

## Build

```bash
hugo --gc --minify
```

## Deployment

Push to the `main` branch and GitHub Actions will build and deploy the site to
GitHub Pages.
