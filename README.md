# Gym Trainer

A mobile-friendly training app (Ukrainian) for a beginner building muscle, 3×/week.
Full-body A/B program with animated exercise demos, set logging, progress tracking,
body-weight tracking, and an infographics dashboard.

- **Single self-contained app** — `index.html` has all the HTML, CSS, and JS. No build step, no dependencies.
- **Offline / installable (PWA)** — `manifest.webmanifest` + `sw.js` make it installable and fully offline once loaded.
- **Your data stays on your device** — workouts and body weight are stored in the browser's `localStorage`.

## Hosting on GitHub Pages

This folder is the site root. Push it to a GitHub repo, then in the repo:
**Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `/ (root)`**.

Your app will be live at `https://<your-username>.github.io/<repo-name>/`.

## Updating

After editing `index.html`, bump the `CACHE` version in `sw.js` (e.g. `gym-trainer-v2`)
so installed phones pick up the new version, then commit and push.
