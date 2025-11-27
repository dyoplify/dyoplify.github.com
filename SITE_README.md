Static site scaffold for `dyoplify.github.com`

Files added:
- `index.html` — main static page built from `DESIGN.md` outline
- `styles.css` — site styles (Tech Blue palette)
- `assets/favicon.svg` — small SVG logo

How to preview locally (PowerShell):

1. Start a simple HTTP server from the repo root:
```
# from PowerShell
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

2. Deploy to GitHub Pages:
- Commit the files and push to the `main` branch (or `gh-pages`) of your repository.
- On GitHub, enable Pages in repository settings (choose branch and folder `/ (root)`).

Notes & next steps:
- I did not overwrite `DESIGN.md` — this scaffold was generated using it.
- I can: create individual project pages, wire a contact form, or convert the site to a generator (Jekyll, Eleventy).
