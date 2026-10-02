# Priti Yadav — Portfolio

Personal portfolio site: a single static page (HTML, CSS, vanilla JS) with no build step.

- GitHub: https://github.com/Pritscoder
- LinkedIn: https://www.linkedin.com/in/priti-yadav-768854218

## Structure

```
portfolio/
├── index.html          # all page content
├── css/styles.css      # design tokens (colors, fonts) at the top in :root
├── js/main.js          # mobile menu, active nav link, scroll fade-in
└── assets/
    ├── favicon.svg
    └── Priti-Yadav-Resume.pdf   # add your résumé here (linked from the hero)
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or
python -m http.server 8000
```

## Deploy to GitHub Pages

1. Create a repo named `Pritscoder.github.io` on GitHub (public).
2. Push this folder:
   ```bash
   git remote add origin https://github.com/Pritscoder/Pritscoder.github.io.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**, set **Source** to `main` / root.
4. The site goes live at https://pritscoder.github.io.

## Customizing

- Change the accent color with `--accent` in `css/styles.css`.
- Edit text directly in `index.html`; each section is marked with a comment.
