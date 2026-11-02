# anaveroneze.github.io

Personal website of Ana Veroneze Solórzano. Built with [Jekyll](https://jekyllrb.com) and hosted on GitHub Pages.

## Layout of this repository

| Path | Content |
|------|---------|
| `index.md`, `experience.md`, `personal.md`, `media.md` | Page content in Markdown |
| `_config.yml` | Site settings and the navigation bar |
| `_layouts/default.html` | HTML layout shared by all pages |
| `_sass/` | Styles. The accent color is in `vars.scss` |
| `img/` | Images and logos |
| `.github/workflows/` | GitHub Actions workflow that builds and deploys the site |

## Editing

Edit the Markdown files and push to `main`. GitHub Actions rebuilds and deploys the site automatically.
Images go in `img/` and are referenced as `/img/name.png`.

## Analytics

Create a Google Analytics 4 property for the site and copy its measurement ID (`G-XXXXXXXXXX`).
Set `google_analytics_id` in `_config.yml`. Visitor location is under Reports > User > User attributes > Demographic details.

## Local preview

```
jekyll serve
```

Open http://localhost:4000.
