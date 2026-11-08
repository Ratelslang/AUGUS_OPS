# AEGIS Executive Protection — Ops PWA
Gray & white daily security operations app. All data stays in the browser (localStorage). No server needed.

## Run locally
Open `index.html` — or serve it: `python3 -m http.server 8000` then open http://localhost:8000

## Upload to GitHub + GitHub Pages
1. Create a new repo on github.com (e.g. `aegis-ops`), do NOT add README/.gitignore yet.
2. Upload ALL files in this folder (index.html, manifest.json, sw.js, icons/, logo.webp) — drag & drop on GitHub web, or:
```
git init; git add .; git commit -m "AEGIS Ops PWA"; git branch -M main
git remote add origin https://github.com/<you>/aegis-ops.git; git push -u origin main
```
3. Repo → Settings → Pages → Deploy from branch → Branch: main, Folder: / (root) → Save.
4. Open https://<you>.github.io/aegis-ops/ — use HTTPS (required for Install).
5. Install: Chrome/Edge menu → Install app / Add to Home Screen. iPhone Safari → Share → Add to Home Screen.
6. Rename the company: search/replace `AEGIS` in index.html + manifest.json.

## Use
Default PIN: **1234** (change in Settings → Change PIN). Demo data loads once; use Settings → Clear all data to start clean. Export/Import backup in Settings. Print any report with the Print button.
