# Yufeng Li Personal Homepage

This repository is a static academic homepage designed for GitHub Pages.

## Local Preview

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

The GitHub Pages user-site repository is:

```text
https://github.com/asimfish/asimfish.github.io
```

GitHub Pages is served from the `main` branch root. To update the site after
editing files:

```bash
git add index.html styles.css script.js README.md assets .gitignore
git commit -m "Update academic homepage"
git push origin main
```

The deployed site is:

```text
https://asimfish.github.io
```

## Files

- `index.html` - homepage content and semantic structure
- `styles.css` - responsive academic homepage styling
- `script.js` - mobile navigation and publication filtering
- `assets/profile.jpg` - profile photo
- `assets/Yufeng_Li_CV.pdf` - downloadable CV
- `.nojekyll` - tells GitHub Pages to publish the static files directly

## Notes

The homepage content intentionally omits phone number and other unnecessary
personal details because GitHub Pages is public. The linked CV PDF preserves the
uploaded resume content.
