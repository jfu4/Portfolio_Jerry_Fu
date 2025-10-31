# Portfolio PDF (GitHub Pages)

A minimal static site that embeds and serves your portfolio PDF using GitHub Pages.

## Quick start

1. **Rename and add your PDF**  
   Put your portfolio at `assets/portfolio.pdf`. (Replace the placeholder.)

2. **Commit & push to GitHub**  
   Create a new repo (e.g., `portfolio-pdf`) and push these files.

3. **Enable GitHub Pages**  
   - Go to **Settings → Pages**  
   - Under **Build and deployment**, set **Source** to **Deploy from a branch**  
   - Select **Branch: `main`** and **Folder: `/ (root)`**, then **Save**  
   - Wait for the site to build. Your site will be at the URL GitHub shows (often `https://<username>.github.io/<repo>`).

> If you prefer GitHub Actions, you can switch the Pages source to **GitHub Actions** later.

## Files

- `index.html` — responsive PDF viewer + download/open links  
- `assets/portfolio.pdf` — **your** PDF (you add this)  
- `.nojekyll` — disables Jekyll processing so assets are served as-is  
- `assets/favicon.svg` — tiny inlined icon

## Local preview (optional)

Open `index.html` in a browser. The embedded viewer should load your PDF once you place it at `assets/portfolio.pdf`.

---

MIT License.
