# armin.business

Personal site, built with [Jekyll](https://jekyllrb.com) and deployed to GitHub Pages at <https://armin.business>.

## Editing

- `_config.yml` – name, tagline, and the list of links shown on the card
- `index.md` – page content
- `assets/css/style.css` – styling
- `_layouts/default.html` – HTML shell

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Deployment

Pushes to `main` trigger `.github/workflows/pages.yml`, which builds the site and deploys it to GitHub Pages.
The `CNAME` file pins the custom domain.
