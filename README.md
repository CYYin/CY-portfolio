# Chang Yu Yin — Portfolio

Personal portfolio site for an AI & Digital Transformation Project Manager. Pure HTML/CSS/JS, no build step.

## Structure

- `index.html` — Home
- `about.html` — Bio, skills, timeline
- `projects.html` — All 6 projects
- `project-1.html` … `project-6.html` — Project detail pages
- `contact.html` — Contact info
- `styles.css` — Shared stylesheet (light theme, color variables at the top)
- `script.js` — Mobile nav toggle

## Things to still edit

- `about.html` — fill in `[Previous Role 1, Company]` / `[Previous Role 2, Company]` and their `[YEARS]` in the timeline section.

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
