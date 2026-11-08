# Yanfeng Zhao — Academic Portfolio

Plain HTML + CSS. No build step. Works directly on GitHub Pages.

## Deploy to GitHub Pages
1. Create a repo named **`<your-username>.github.io`** on GitHub (public).
2. Upload everything in this folder (drag-and-drop on github.com, or):
   ```bash
   git init && git add . && git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: *Deploy from a branch*, Branch: `main` / `(root)`.
4. Site goes live at `https://<your-username>.github.io` in ~1 minute.

## What to edit
| File | What |
|---|---|
| `index.html` | Scholar / GitHub links, News |
| `projects/*.html` | Research question, 3 contributions, system overview, BibTeX, links |
| `publications.html` | Full titles, co-authors, PDF/DOI links |

| `files/cv.pdf` | Drop in your CV PDF |
| `assets/img/` | Replace the `.svg` placeholders with real photos (e.g. `mammal.jpg`) and update the `src=` paths |

Search for `TODO` to find every placeholder: `grep -rn TODO .`

Tips: export photos at ~1600px wide, JPG quality ~80 (keep each < 400 KB).
For demo videos use a muted looping `.mp4` (< 8 MB) or embed YouTube in `.p-media`.
