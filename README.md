# The Candy Family Sweepstake — FIFA World Cup 2026

An installable web app (PWA) tracking a family sweepstake for the 2026 FIFA World Cup.

## Features
- **Leaderboard** and a full **League Table** (members and every team, best to last, with goal difference)
- **The Draw** — FIFA-style knockout bracket with each fixture's owner
- **Members** view, **Teams & Odds**, and the **Schedule** with TVNZ+ broadcast info
- Light/dark theme, mobile-friendly, installable on Android & iOS (offline support)

## Run it
Open `index.html` in a browser, or host the folder (see below) to install it as an app.

## Host on GitHub Pages
1. Create a new repository on GitHub and push these files (see commands below).
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Your app will be live at `https://<your-username>.github.io/<repo-name>/`.
4. Open that link on your phone and use **Install** / **Add to Home Screen**.

## Files
- `index.html` — entry point (redirects to the portal)
- `World_Cup_2026_Sweepstake_Portal.html` — the app
- `manifest.webmanifest`, `sw.js` — PWA manifest + offline service worker
- `icon-192.png`, `icon-512.png`, `maskable-512.png`, `apple-touch-icon.png` — app icons

_Data as of 28 June 2026. Results/odds from public sources, for fun only._
