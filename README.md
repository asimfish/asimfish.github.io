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
- `favicon.svg` - small browser tab icon
- `assets/profile.jpg` - profile photo
- `assets/Yufeng_Li_CV.pdf` - downloadable CV
- `.nojekyll` - tells GitHub Pages to publish the static files directly

## Notes

The homepage content intentionally omits phone number and other unnecessary
personal details because GitHub Pages is public. The linked CV PDF preserves the
uploaded resume content.

## Content and media sources

- Bench2Dex uses the title and abbreviated author order from its
  [project homepage](https://bench2dex.github.io/). The linked
  [arXiv version](https://arxiv.org/abs/2609.15726) uses a different title;
  the ICLR 2027 submission status was supplied by Yufeng Li.
- Remembering What Matters is featured in Selected Publications. Its author order
  and equal-contribution marks follow the October 2026 CV and
  [coauthor's homepage](https://changwinde.github.io/); its method summary follows
  the CV. The linked OpenReview PDF required browser verification during this update.
  The update date uses the official
  [NeurIPS 2026 author notification date](https://neurips.cc/Conferences/2026/Dates)
  (September 24, AoE), rather than an independently verified individual decision timestamp.
- `assets/supertranslate/cover-landscape.png` is the unmodified V15 video cover from
  [SuperTranslate](https://github.com/asimfish/super_translate/blob/main/docs/assets/promo/v15/cover-landscape.png).
  Its original video wording, media links, and measurement context are documented in
  [PRESENTATION.md](https://github.com/asimfish/super_translate/blob/main/docs/PRESENTATION.md).
