# diraigent-landing

Static GitHub Pages landing page for Diraigent.

## Layout

```text
docs/
  index.html
  assets/css/style.css
  assets/images/
  favicon-*.png
  favicon.svg
  robots.txt
  sitemap.xml
```

The site source lives in `docs/`, which is the directory GitHub Pages can publish directly from the `main` branch.

## Preview

Serve the `docs/` directory locally:

```bash
python3 -m http.server 8080 --directory docs
```

Then open `http://localhost:8080`.

## Editing

- Page markup: `docs/index.html`
- Styles: `docs/assets/css/style.css`
- Images and social preview assets: `docs/assets/images/`
- Favicons and crawler files: `docs/`

There is no build step for this repository.

## Product messaging

Keep this site aligned with the main [Diraigent repository](https://github.com/diraigent/diraigent), especially its README, `apps/web/src/app/features/landing/` and `apps/web/src/index.html`. This repository publishes the standalone public website; deploying the web app on another host does not update GitHub Pages.

The current description covers shared workspaces, provider choice, direct task execution, human review and optional Orchestra-owned content storage. Avoid advertising retired playbook pipelines or promising that external AI providers keep all data on the host.
