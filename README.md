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

## Analytics

Traffic uses [GoatCounter](https://www.goatcounter.com) (free tier, cookieless, no consent banner needed):

1. Create a site at goatcounter.com (e.g. code `clinelinux`).
2. Sites → your site → enable **public dashboard** so `/stats/` can link it.
3. Set `counterID = "clinelinux"` in `hugo.toml` (uncomment/replace the empty value).
4. Push — the count script loads site-wide; verify hits land in GoatCounter, then add the dashboard URL to `content/stats.md`.
