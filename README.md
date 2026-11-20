# HocusFocus

A static, browser-based personal productivity dashboard. This release intentionally excludes the experimental 3D Study Room so the core site can be deployed independently to GitHub Pages or Vercel.

## Included sections

- Today dashboard
- Focus timer and Pomodoro settings
- Tasks and targets
- Move / workout tracker
- Nourish / meal and water tracker
- Reflections and study analytics
- Themes and settings

## Run locally

You can open `index.html` directly in a modern browser. No Python, Node.js, build step, or external JavaScript CDN is required for this version.

## Deploy to GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root (make sure `index.html` is at the root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Select **Other** / static site if prompted.
4. Leave the build command empty and set the output directory to `.` (project root).
5. Deploy.

## Data and privacy

The app stores its working data in the browser's `localStorage` on the current device. This build deliberately retains the existing `afterlife-v3` storage key so data saved by the previous version in the same browser can still be read. Browser-local data does not automatically sync between devices or browsers. Use the app's Export Backup feature before clearing site data or changing domains.

## Notes

- The Study Room and GLB avatar viewer are not included in this release. They can be reintroduced later as a separately loaded feature.
- No server-side database or account system is included.
