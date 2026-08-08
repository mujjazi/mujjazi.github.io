# Personal Website

Static single-page portfolio hosted on GitHub Pages at [mujtabamehdi.com](https://mujtabamehdi.com).

## Structure

```
index.html          Single-page portfolio (profile, skills, articles, projects)
assets/css/style.css  Styles
assets/images/      Profile and site images
einburgerungtool/   German citizenship eligibility checker (React/Vite build)
404.html            Custom error page
```

## Local development

Open `index.html` directly in a browser, or serve the repo root:

```sh
python3 -m http.server 8000
```

## Deployment

Push to the `gh-pages` branch. GitHub Pages serves the repo root as static files (see `.nojekyll`).

## Note

The Résumé link points to `resume.pdf` at the repo root. Place the PDF there before committing.
