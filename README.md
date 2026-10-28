# Pizza New Yorker & Fast Food — Website

Static one-page website for Pizza New Yorker & Fast Food (Al Malaz, Riyadh).
Built with React + Vite + Tailwind CSS, exported as a static site.

**Live site:** https://pizza-new-yorker.kimi.page

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Page entry point (title, meta, favicon links, app mount) |
| `assets/index-C_gIadpQ.js` | Compiled app (all sections: navbar, hero, menu, about, location, contact, footer) |
| `assets/index-WPzhF2nh.css` | Compiled Tailwind CSS |
| `assets/logo.png` | Circular badge logo shown in the navbar |
| `assets/favicon-32.png` / `favicon-48.png` | Browser tab icons |
| `assets/apple-touch-icon.png` | iOS home-screen bookmark icon |

## Host it on GitHub Pages

1. Create a new repository on GitHub (e.g. `pizza-new-yorker`).
2. Upload **all files from this folder** to the repository root
   (keep the `assets/` folder structure exactly as-is).
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**,
   select the `main` branch and the `/ (root)` folder, then **Save**.
5. Wait a minute — the site goes live at
   `https://<your-username>.github.io/<repository-name>/`.

> This is a pure static site: no build step, no server code, no environment
> variables. The `.nojekyll` file tells GitHub Pages to serve the files as-is.

## Update the logo or content

The site is a compiled bundle — content edits require rebuilding from the
React source. Contact the site maintainer or rebuild with Vite
(`npm run build`) and replace `index.html` + `assets/`.

---

© Pizza New Yorker & Fast Food · Al Malaz, Riyadh · 054 220 8607
