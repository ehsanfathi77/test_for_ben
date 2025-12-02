# MajorMiters one-pager

A static landing page for MajorMiters, a veteran-owned seamless gutter company. Open `index.html` in your browser to view the one-pager.

## Preview locally

```bash
# from the repo root
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to Vercel

This repo is prepped for a static Vercel deploy.

1. Install the Vercel CLI and log in (`npm i -g vercel && vercel login`).
2. From the repo root, run `vercel` to create the project, then `vercel --prod` to deploy.

The included `vercel.json` uses the static build for `index.html` and routes all paths back to it so the single page works on refresh.
