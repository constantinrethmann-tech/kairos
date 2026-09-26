# KAIROS

A personal focus app: plan vectors, burn time on them, land them. Runs in the browser and installs as an app
(Edge/Chrome on the laptop, Safari → Add to Home Screen on iPhone and iPad). Works offline.

- `index.html`: the whole app
- `manifest.webmanifest`, `icons/`: name and icon for the installed app
- `sw.js`: keeps a copy for offline use

Your data is not in this repository. It is stored on each device and synced through a secret gist
in your GitHub account (Hangar → Sync & backup inside the app).
