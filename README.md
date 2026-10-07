# Craeven's Decision Compass — Version 2

This is an iPhone-friendly **separate companion** to Craeven's character sheet. The original character sheet is unchanged.

## What changed
- Combat and roleplay have equal prominence.
- Every scenario presents **three ranked options**, each with a plan, benefits, costs, risks, and character or mechanical reasoning.
- Expand each option to read it; select the preferred action before saving it in the local decision journal.
- Rankings update as you change terrain, threat, goal, readiness, prepared spells, and personality pressures.
- All scenario logic works offline after a first successful install on GitHub Pages. It is a rules-based adviser, not a live AI service, and does not sync with Roll20 or the original character sheet.

## Install to your iPhone via GitHub Pages
1. Create a new public GitHub repository, or choose an existing web repository.
2. Upload the files *inside* this ZIP to the root of the repository: `index.html`, `icon.png`, `manifest.webmanifest`, and `service-worker.js`. Do not upload the ZIP itself as the only file.
3. In the GitHub repo, select Settings → Pages → Build and deployment → Deploy from a branch; choose your main branch and the root folder.
4. Open the published HTTPS Pages URL using Safari on your iPhone.
5. Tap Share → Add to Home Screen → Add. You can then open the Compass like an app.

If replacing V1 on the same Pages address, the V2 service worker updates its cache. Reopen or refresh the app if the old UI remains visible. Browser-stored scenarios/journal entries are kept in that browser/site profile; backing them up/exporting is not currently supported.

## Rules and limitations
The adviser is based on the latest known Craeven/Miasmaeys sheet, including homebrew features. It uses estimated priorities, not certain outcomes, and cannot know exact enemy saves, distances, initiative, resistances, current HP, action availability, or DM rulings. It remembers spell-prepared flags and simple availability switches but does not consume a spell slot automatically. Treat it as a decision aid, not a rules engine.
