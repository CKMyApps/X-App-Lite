# X-App-Lite v1.2 — GitHub Pages

Free text-first companion to X, hosted entirely on GitHub Pages. No backend, login integration, API keys or credits are required.

## Functions
- Greek and English UI (browser language initially; toggle saves choice)
- Light/dark themes
- Text post composer with automatic local drafts; **Continue on X** opens the official X composer, where the user must confirm posting
- Shortcuts to the official X timeline and search
- Favorite public profile shortcuts stored locally
- AppIcon used as header icon, favicon and web manifest icon

**Limitations:** This is *not* an independent timeline or X login client. It does not read posts using the X API or publish directly. The X website may display media, advertisements and other interface elements.

## Deploy
Upload the **contents** of this folder to the root of your `CKMyApps/X-App-Lite` GitHub repository (keep `index.html` in the root), commit the changes, then ensure `Settings → Pages → Deploy from a branch → main → /(root)` is enabled. The URL is `https://ckmyapps.github.io/X-App-Lite/`. Do not set a custom domain.

Never upload your local `.env`, secrets, or Node.js OAuth code to GitHub Pages.

MIT license applies to original project code, not third-party brands or assets. The project is not affiliated with X Corp.
