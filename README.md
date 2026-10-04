# ankit-basak.github.io

Personal academic website for Ankit Basak. Plain HTML/CSS (no build step), hosted on GitHub Pages.

## Publish it (about 5 minutes)

1. Create a new **public** repo on GitHub named exactly `<your-username>.github.io`.
2. Upload everything in this folder (`index.html`, `assets/`, `.nojekyll`, this README) to the repo root.
   - On the web: **Add file → Upload files**, drag the folder contents in, commit.
   - Or from a terminal:
     ```bash
     git init && git add . && git commit -m "Initial site"
     git branch -M main
     git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
     git push -u origin main
     ```
3. In the repo, go to **Settings → Pages**, set **Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Your site goes live at `https://<your-username>.github.io` within a minute or two.

## Personalize

| What | Where |
|---|---|
| Headshot | Add a square photo as `assets/profile.jpg` (initials show until you do) |
| Scholar / LinkedIn / GitHub / Bluesky | Uncomment the `TODO` block in the hero section of `index.html` and paste your URLs |
| CV | Replace `assets/Ankit_Basak_CV.pdf` with your latest version (same file name) |
| News | Edit the `<ul class="news">` list in the About section |
| Publications | Copy a `<li class="pub">` block; set `data-k` to `pub`, `pre`, or `prep` so the filter tabs work. Your name is bolded automatically. |

Light/dark mode follows the visitor's system setting, with a toggle in the top-right.
