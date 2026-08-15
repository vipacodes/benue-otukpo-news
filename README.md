# 💜 Her Anniversary Garden

A living purple garden for our 2 years — butterflies that fly to every touch,
flowers that bloom where she taps, falling petals, fireflies, a live
"together counter", dreamy music, and a letter from the heart.

## Run it locally
Just open `index.html` in any browser (double-click it). No installs needed.

## Host it free on GitHub Pages
1. Create a repository on GitHub (e.g. `for-my-princess`).
2. Push these files:
   ```bash
   git init
   git add .
   git commit -m "Happy 2 years, my princess 💜"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/for-my-princess.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
4. In ~1 minute her page is live at `https://YOUR_USERNAME.github.io/for-my-princess/`

## Add her photo or video to the heart frame 💜
The heart frame looks for these files (root of the repo first, then `assets/`):
- photo: `her.jpg`
- video: `her.mp4`  (autoplays muted on loop; if both exist, the photo wins)

**Easiest way — no git needed (works for videos too):**
1. Go to https://github.com/vipacodes/2-years-anniversary
2. Click **Add file → Upload files**
3. Drag in your file renamed exactly `her.jpg` or `her.mp4`
   (GitHub's limit is 25 MB per file — trim long videos)
4. Commit. The heart shows it automatically within a minute.

Until a file exists, the heart shows a beating 💜.

## Your own real song 🎵
The page plays a real licensed piano love song ("There is Romance" — Kevin
MacLeod, CC BY 3.0) together with the garden nature sounds.
Want **your** song instead? Upload it as `song.mp3` to the repo root (same
Add file → Upload files trick) and it takes over automatically.
- **Start date** (for the live counter): open `index.html`, find
  `const ANNIVERSARY = new Date('2024-08-15T00:00:00');` near the top of the
  `<script>` and change it to your real date.
- Her name, titles, and the letter text are plain HTML at the top of the file.
