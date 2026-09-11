# Chang Yu Yin — Portfolio

Personal portfolio site for an AI & Digital Transformation Project Manager. Pure HTML/CSS/JS, no build step.

## Structure

Bilingual site: every page has an English version and a `-zh` Traditional Chinese version (e.g. `about.html` / `about-zh.html`), linked via the EN/中文 switcher in the navbar.

- `index.html` / `index-zh.html` — Home
- `about.html` / `about-zh.html` — Bio, skills, timeline
- `projects.html` / `projects-zh.html` — All 5 projects
- `project-1.html` … `project-5.html` (+ `-zh` versions) — Project detail pages
- `contact.html` / `contact-zh.html` — Contact info, resume downloads, QR codes to the site
- `styles.css` — Shared stylesheet (light theme, color variables at the top)
- `script.js` — Mobile nav toggle

## Things to still edit

- `contact.html` / `contact-zh.html` — add your resume PDFs at `resume-en.pdf` and `resume-zh.pdf` in the repo root (same folder as `index.html`) so the download buttons work. Until those files exist, the download links will 404.

## Deploy to GitHub Pages

Repo: https://github.com/CYYin/CY-portfolio

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/CYYin/CY-portfolio.git
git push -u origin main
```

1. On GitHub: go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
4. Your site will be live at `https://cyyin.github.io/CY-portfolio/` within a few minutes.

The `.nojekyll` file is included so GitHub Pages serves the files as-is without Jekyll processing.
