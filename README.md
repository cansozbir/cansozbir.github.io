# cansozbir.dev

Personal website of **Can Sözbir** — a plain, dependency-free static site
served via **GitHub Pages** at [cansozbir.dev](https://cansozbir.dev).

## Structure

```
index.html        # the entire single-page site (inline CSS + SVG icons)
CNAME             # custom domain: cansozbir.dev
.nojekyll         # serve files as-is, skip Jekyll processing
assets/
  img/cansozbir.jpeg
  Can-Sozbir-Resume.pdf
  favicon.png
```

## Local preview

No build step. Just open `index.html`, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Push to `main`. GitHub Pages is configured to deploy from the `main` branch
(root). The custom domain `cansozbir.dev` is set via the `CNAME` file plus DNS.
