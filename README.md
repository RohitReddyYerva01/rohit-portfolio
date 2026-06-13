# Rohit Reddy Yerva — Portfolio

A single-page, lightweight portfolio site. No build step, no dependencies — just `index.html` + `resume.pdf`.

## Files
- `index.html` — the entire site (HTML, CSS, JS inline)
- `resume.pdf` — your resume, linked from the nav and contact section

## Free Deployment Options

### Option 1: GitHub Pages (recommended)
1. Create a new GitHub repo, e.g. `rohit-portfolio`.
2. Upload `index.html` and `resume.pdf` to the repo root.
3. Go to **Settings → Pages**.
4. Under "Source", select branch `main` and folder `/ (root)`. Save.
5. Your site will be live at: `https://<your-username>.github.io/rohit-portfolio/`
6. (Optional) To use it as your main GitHub profile site, name the repo `<your-username>.github.io` instead — then it's live at `https://<your-username>.github.io/`.

### Option 2: Netlify
1. Go to https://app.netlify.com/drop
2. Drag and drop this folder (containing `index.html` and `resume.pdf`).
3. Netlify gives you a free `*.netlify.app` URL instantly. You can rename it in site settings.

### Option 3: Vercel
1. Go to https://vercel.com, sign up free.
2. "Add New Project" → import this folder or connect your GitHub repo.
3. Deploy — you get a free `*.vercel.app` URL.

All three options are completely free for static sites like this — no charges incurred.

## Customizing
- **Colors**: edit the CSS variables at the top of `index.html` inside `:root { ... }` (`--blue`, `--copper`, `--paper`, etc.)
- **Content**: all text is plain HTML inside the relevant `<section>` tags — search for the section by its `id` (e.g. `id="projects"`).
- **GitHub link**: currently points to `https://github.com/RohitReddyYerva01` — update once your GitHub profile has projects pinned.
- **Resume**: replace `resume.pdf` with an updated version any time (keep the same filename, or update the `href="resume.pdf"` links).

## Notes
- Fully responsive (mobile menu included).
- Respects reduced-motion preference for the animated chart.
- No external JS frameworks — loads fast, works everywhere.
