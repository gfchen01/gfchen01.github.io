# gfchen01.github.io

Source for Guofei Chen's personal website: a single static page (template adapted from [Jon Barron's site](https://github.com/jonbarron/jonbarron.github.io)).

## Layout

- `index.html` — the entire site (bio, publications, projects, experience). Each publication/project is one `<tr>` in a table; edit it directly to add/update entries.
- `stylesheet.css` — styling.
- `images/` — thumbnails used in `index.html`.
- `data/` — locally hosted PDFs (resume, papers without a permanent external host).

## Checking the site locally

No build step — just open the file or serve the directory:

```bash
open index.html
# or
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deployment

`.github/workflows/gh-pages.yml` publishes the repo root as-is to the `gh-pages` branch on every push to `main`, which serves the live site at [gfchen01.cc](https://gfchen01.cc) (the workflow writes the `CNAME` for the custom domain). There is no build/compile step — whatever is committed in `index.html` is what goes live.
