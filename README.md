# Rashid Zahoor — Portfolio

Personal portfolio website for **Rashid Zahoor**, Computer Science Teacher & Visiting Lecturer (Lahore, Pakistan).

Plain HTML, CSS and vanilla JavaScript — no build step, no dependencies.

## Structure

```
index.html            # single-page site
css/style.css         # styles
js/main.js            # nav, scroll-reveal, counters
Rashid_Zahoor_CV.pdf  # CV linked from the "Download CV" button (add this file)
netlify.toml          # Netlify config (publish root)
vercel.json           # Vercel config
```

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

### Netlify
1. Push this repo to GitHub.
2. In Netlify → **Add new site → Import an existing project** → pick the repo.
3. Leave the build command empty and set the publish directory to `.` (already set in `netlify.toml`).
4. Deploy.

### Vercel
1. Push this repo to GitHub.
2. In Vercel → **Add New → Project** → import the repo.
3. Framework preset: **Other**. No build command, output directory blank.
4. Deploy.

## Updating content

All content lives in `index.html`. Colours and fonts are CSS variables at the top of `css/style.css`.
