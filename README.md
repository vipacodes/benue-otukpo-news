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

## Personalize
- **Start date** (for the live counter): open `index.html`, find
  `const ANNIVERSARY = new Date('2024-08-15T00:00:00');` near the top of the
  `<script>` and change it to your real date.
- Her name, titles, and the letter text are plain HTML at the top of the file.
