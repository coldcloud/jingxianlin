# Jake Lin Resume Site

This folder now contains a lightweight Hugo site for a one-page resume inspired by a direct "hire me" layout.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to GitHub Pages

This repo now includes a GitHub Pages workflow at `.github/workflows/hugo.yaml`.

On GitHub, set Pages to build from `GitHub Actions`. After that, every push to `main` will publish the site to:

```text
https://coldcloud.github.io/jingxianlin/
```

## Update content

Most of the resume copy now lives in `content/_index.md`.
