# Host on GitHub Pages (Instant Setup)

This `temp/` folder contains the production-ready static website files for **Aniket Sonwane (Anixss) — Business Card**.

---

## How to Host for Free on GitHub Pages:

### Method 1: New Repository (Recommended)
1. Go to [GitHub](https://github.com) and click **New Repository**.
2. Name it either:
   - `AniketSonwane.github.io` (for your main personal domain `https://AniketSonwane.github.io`), or
   - `identity-card` (or any name you prefer).
3. Choose **Public**, then click **Create repository**.
4. Click **"uploading an existing file"**.
5. Drag and drop all the files from this `temp/` folder into GitHub:
   - `index.html`
   - `assets/` (folder with JS, CSS, and images)
   - `.nojekyll`
   - `favicon.svg`
6. Click **Commit changes**.
7. Go to **Settings** → **Pages** (in the left sidebar).
8. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
9. In about 30–60 seconds, your website will be live!

---

### Files Included:
- `index.html` — Optimized HTML with font links and relative asset paths (`./assets/`)
- `assets/` — Bundled & minified JavaScript, Vanilla CSS, and debossed logo watermark
- `.nojekyll` — Tells GitHub Pages not to process files with Jekyll (prevents missing file errors)
- `favicon.svg` — Custom SVG favicon
