# ☕ Brewfully

A calm, minimal coffee brew guide. Pick your method (Pour Over, French Press, Aeropress), enter your coffee weight or cup count, and Brewfully calculates the water, ratio, and walks you through each phase with a step-by-step countdown timer. Blooming, pouring, steeping, plunging.

**No build step. No dependencies.** One `index.html` file.

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
npx serve .
```

## Deploy

### Vercel
```bash
npm i -g vercel
vercel          # from this folder — it's static, zero config needed
```
Or import the repo at [vercel.com/new](https://vercel.com/new); Vercel auto-detects the static site.

### GitHub Pages
1. Push this repo to GitHub.
2. Repo → Settings → Pages → Source: `main` branch, root.
3. Your site goes live at `https://<username>.github.io/brewfully/`.

## How ratios work

| Method | Ratio | Total time |
|---|---|---|
| Pour Over | 1:16 | ~3 min |
| French Press | 1:15 | ~4.5 min |
| Aeropress | 1:13 | ~2.3 min |

Strength (Gentle / Classic / Bold) adjusts the effective ratio, and the pour amounts per phase are recalculated accordingly.
