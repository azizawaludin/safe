# SAFE – School Assessment for Equity

This folder contains a single-page app you can host anywhere that serves static files.

## Quick options

### A) GitHub Pages
1) Create a new public repository on GitHub, for example `safe-app`.
2) Upload **index.html** to the root of the repo and commit.
3) In the repo: Settings → Pages → Build and deployment
   - Source: Deploy from a branch
   - Branch: `main` and `/root`
4) Wait for the build to finish. Your site will be live at:
   `https://<your-username>.github.io/safe-app/`

If you name the repo `<your-username>.github.io`, your site will be:
`https://<your-username>.github.io/`

### B) Netlify
1) Create a Netlify account.
2) Drag-and-drop this folder into the **Add new site** flow (or connect your GitHub repo).
3) Netlify will publish a public URL.

### C) Vercel
1) Create a Vercel account.
2) Create a new project and import your GitHub repo that contains **index.html**.
3) Vercel will deploy a public URL.

## Notes
- The app stores responses locally in the browser using `localStorage`. No server is required.
- To reset saved data, use the Reset button on the results page.
- You can change the page text by editing `index.html` directly.