# f2mlabs-website

Static website for F2M Labs (Scout Pro) — HTML, CSS (SCSS), and vendor assets.

## Quick start

- Open `index.html` in your browser to preview the site.
- Or serve locally with a simple HTTP server:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Development

- SCSS source files are in `assets/scss/`. To compile to CSS, run:

```bash
sass assets/scss/main.scss assets/css/main.css
```

## Notes

- Add a LICENSE if you want to publish this project publicly.
- Remove large vendor files from the repo if you plan to manage them with a package manager.
