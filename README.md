# Yiming Gao — Portfolio

Personal portfolio site — static single-page HTML, GitHub Pages.

```
yimgao@portfolio:~$ █
─────────────────────────────────────────
> about      > experience
> skills     > projects     > contact
```

## One file, no build

- `index.html` — everything (HTML + CSS + JS)
- `.github/workflows/deploy.yml` — auto-deploy to Pages

## Deploy

Push to `main` → Actions deploys automatically to `https://yimgao.github.io/hackerfolio/`

Or manually run the workflow from GitHub Actions tab.

### Repo settings (one-time)

1. Go to repo **Settings → Pages**
2. Source: **GitHub Actions**

That's it.

## Content

Data sourced from `src/lib/portfolioData.ts` (original Next.js project).

© 2026 Yiming Gao
