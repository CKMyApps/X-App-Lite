# X-App-Lite (static edition)

A free static, text-first **unofficial companion** for X. No X API, no X Developer Portal configuration, no server and no new hosting account (if you already have GitHub).

## Features
- Write text-only drafts (automatically saved locally), hand off to X official post composer
- Open your X home timeline (on X itself)
- Search posts and open public profiles (on X itself)
- Keep a local list of favorite profiles
- Greek / English and dark / light themes
- PWA shell (install from supported browsers; app assets can be cached)

## Important limitations
- This **cannot** show an authenticated personal X timeline inside the app without an authorized X integration. On X, images, videos, ads etc. may still appear.
- It cannot publish automatically, fetch posts or replies, authenticate users or strip media from x.com. The user completes posts at x.com.
- No OAuth keys or passwords are stored or requested. Posting and search links are created locally.
- A draft uses a conservative 280-codepoint limit; X's own weighted character rules may differ.
- X-App-Lite is not affiliated with X Corp.

## Publish to GitHub Pages
1. Create a new public repository (e.g. `x-app-lite`) on GitHub.
2. Upload **all files in this folder** to the repository root (not the ZIP itself).
3. Open Settings → Pages → Build and deployment → Deploy from a branch → `main`, folder `/(root)` → Save.
4. When deployed, open `https://YOUR-USERNAME.github.io/x-app-lite/`. If the repo is `ckmyapps/x-app-lite`, the expected URL is `https://ckmyapps.github.io/x-app-lite/` (only after you create/publish it).

## Run locally
Open `index.html` for most features or run `python3 -m http.server 8080` and visit `http://localhost:8080`.

## Security
Do not upload X Developer Portal secrets, access tokens or `.env` files to GitHub Pages. If credentials have previously appeared in screenshots, rotate them in Developer Console.
