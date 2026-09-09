# Hassan Abbas — Professional Portfolio

A deploy-ready static professional website built from selected material in the private `hassan-professional-identity` repository.

## Preview locally

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to Cloudflare Pages

1. Create a new **public or private** Git repository containing this folder.
2. In Cloudflare Pages, connect the repository.
3. Framework preset: **None**.
4. Build command: leave blank.
5. Build output directory: `/` (repository root).
6. Deploy, then attach your custom domain.

The site is plain HTML/CSS/JavaScript, so there is no build tool or package dependency.

## Deploy to GitHub Pages

Push the contents to a repository, then enable **Settings → Pages → Deploy from branch**, using the root of the default branch.

## Before publishing

- Confirm the current-role dates and wording.
- Confirm whether you want the public email address shown.
- Replace or regenerate `cv/Hassan-Abbas-CV.pdf` whenever the CV changes.
- Add public links/publications only after verifying them.
- Keep the source professional-identity/evidence repository private.

## Files

- `index.html` — executive overview
- `work.html` — six case studies
- `experience.html` — career timeline and education
- `research.html` — research interests and methods
- `about.html` — professional narrative and expertise
- `cv.html` — web CV + PDF link
- `assets/styles.css` — complete visual system
- `assets/site.js` — mobile navigation and subtle reveal animation
- `_headers` — basic Cloudflare security headers
