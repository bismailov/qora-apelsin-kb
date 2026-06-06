# Qora apelsin — knowledge graph

Interactive knowledge graph of the book **Qora apelsin** (524 concepts, 1005 links,
21 themes; bilingual Uzbek/English), extracted with [Graphify](https://github.com/safishamsi/graphify).

**Live:** https://bismailov.github.io/qora-apelsin-kb/

## Structure
- `site/static/graph.html` — the page (header + the interactive graph below).
- `site/static/graph-raw.html` — the self-contained Graphify graph (search, legend, click-to-highlight).
- `site/index.html` — redirects the site root to the graph.
- `.github/workflows/deploy.yml` — publishes `site/` to GitHub Pages on push to `main` (no build step).

## Update
Regenerate the graph in the source project, copy the new `graph.html` over
`site/static/graph-raw.html` (keep its `<title>`), then `git push`.
