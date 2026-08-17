# rawd-legal

Legal and support pages for the **RAWD** iOS app, served by GitHub Pages.

> **Generated file — do not edit by hand.**
> The source is `scripts/build-legal-site.mjs` in the RAWD app repository.
> Edit the CONFIG block there, run `npm run legal`, then copy this folder over.

## URLs

| Page | URL |
|---|---|
| Privacy Policy | https://hqabazard.github.io/rawd-legal/privacy |
| Terms of Use | https://hqabazard.github.io/rawd-legal/terms |
| Support | https://hqabazard.github.io/rawd-legal/support |

Add `?lang=ar` to any URL to open it in Arabic. The app does this automatically
when its own interface is in Arabic. Otherwise the page follows the browser
language, and either can be switched with the toggle in the header.

## First-time setup

```bash
# 1. Create an EMPTY public repo on GitHub named exactly: rawd-legal
#    (no README, no .gitignore, no licence)

# 2. From inside this folder:
git init
git add -A
git commit -m "RAWD legal and support pages"
git branch -M main
git remote add origin https://github.com/hqabazard/rawd-legal.git
git push -u origin main

# 3. On GitHub: Settings -> Pages
#    Source: "Deploy from a branch"
#    Branch: main    Folder: / (root)
#    Save. The site is live in 1-2 minutes.
```

## Updating later

```bash
git add -A && git commit -m "Update legal pages" && git push
```

## Notes

- `.nojekyll` stops GitHub from running Jekyll over the files.
- Each page is a single self-contained HTML file: no build step, no
  dependencies, no external requests, no tracking.
