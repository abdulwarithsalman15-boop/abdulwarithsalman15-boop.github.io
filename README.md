# abdulwarithsalman.com

Personal site. Static HTML and CSS, no build step, no dependencies.

```
index.html    the whole page
style.css
img/          proof screenshots, client names redacted
```

## Deploy

Any static host works. The site is plain files.

- **GitHub Pages** — Settings → Pages → Deploy from branch → `main` / root
- **Netlify** — drag the folder onto netlify.com/drop
- **Cloudflare Pages / Vercel** — point at the repo, no build command

## Editing

Open `index.html`. Images live in `img/` and are referenced by relative path.

Screenshots are redacted with `../template/redact.py`, which keeps the box
coordinates per file. Re-run it rather than editing images by hand, so the
redaction stays reproducible.
