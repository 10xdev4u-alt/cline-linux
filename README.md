# cline-linux — Cline for Linux download site

Minimal Hugo site (hand-rolled theme, zero JS) deployed to GitHub Pages:
**https://10xdev4u-alt.github.io/cline-linux/**

## Local preview

```bash
hugo server -D
```

## Deploy

Push to `main` — `.github/workflows/pages.yml` builds (`hugo --minify`) and deploys. First-time setup: repo Settings → Pages → Source: **GitHub Actions**.

Downloads point at fork releases: https://github.com/10xdev4u-alt/cline/releases
