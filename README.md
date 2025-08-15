# Creed Thoughts: Trivia Night (MVP)

This is a static web app you can host on **GitHub Pages**. Optional realtime & leaderboards use **Firebase**.

## Files
- `index.html` — main site (solo mode, join live)
- `host.html` — host console for live tournaments
- `admin.html` — owner settings, content tools
- `player.html` — minimal player window for live mode
- `app.js` — solo logic
- `host.js` — live host logic
- `admin.js` — admin logic
- `rt.js` — Firebase wiring
- `config.js` — your passcode, defaults, Firebase config
- `styles.css` — styles
- `questions/` — question JSON sets
- `tools/csv-import.html` — optional CSV→JSON helper

## Quick start (GitHub Pages)
1. Create a public repo and upload all files in this folder.
2. In GitHub: **Settings → Pages → Source: Deploy from branch → main/root**.
3. Edit `config.js`:
   - Change `OWNER_PASSCODE`.
   - Paste your Firebase web config.
4. Visit your Pages URL and test solo mode. Use **Admin** to tweak settings.
5. Use **Host Console** to run a live match.
