# Local preview

This homepage now uses the official al-folio Jekyll template (v1). The earlier static pages and files are saved in `archive/`.

From this folder, run:

```sh
BUNDLE_PATH=./vendor/bundle BUNDLE_USER_HOME=./.bundle bundle exec jekyll serve
```

Then open http://127.0.0.1:4000/ . The current built output is in `_site/`. To rebuild without starting a server, replace `serve` with `build`.

The source is deployed to GitHub Pages by `.github/workflows/deploy.yml` after pushes to `main`.
