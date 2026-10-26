# Adriatic Intelligence Group website

Source for [adriaticintelligence.com](https://adriaticintelligence.com): a static, single-page site with no build step.

```
index.html            page markup
css/styles.css        all styles (brand colours are CSS variables in :root)
js/main.js            smooth scrolling + navbar shadow on scroll
assets/images/        logo and founder photos
CNAME                 custom domain for GitHub Pages
```

## Preview locally

```bash
python -m http.server 8080
```

Then open http://localhost:8080.

## Deploy

Enable GitHub Pages on this repo (Settings → Pages → deploy from `main`, `/`). The `CNAME` file points it at adriaticintelligence.com.
The live site is currently still served from `nicknastic/nicknastic.github.io`.
