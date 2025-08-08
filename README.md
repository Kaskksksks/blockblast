BlockBlast — GitHub Pages ready
==============================

How to publish on GitHub Pages (quick):
1. Create a new GitHub repository (public).
2. Upload the files from this package (index.html, README.md, LICENSE).
   - In the GitHub web UI you can click "Add file" → "Upload files".
3. Commit to the `main` branch.
4. Go to Settings → Pages, set the source to `main` branch and `/ (root)`. Save.
5. After a minute, your site will be live at:
   https://<your-username>.github.io/<repository-name>/

Notes:
- This is a static-only build — no global leaderboard (needs a backend). If you want a global leaderboard, use the Replit project I prepared earlier (Node server + Replit DB) or host a small backend (I can help).
- High score is stored locally in your browser (localStorage).
- Sounds are tiny embedded beeps; if you want richer SFX, I can add better base64 or external files.