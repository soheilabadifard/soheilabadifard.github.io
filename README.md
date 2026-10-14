# soheilabadifard.github.io

Source for my personal website, https://soheilabadifard.github.io, built with [al-folio](https://github.com/alshedivat/al-folio) (v1).

## Where things are

| Content | File |
| --- | --- |
| Homepage bio and research interests | `_pages/about.md` |
| News (one file per item) | `_news/` |
| Publications | `_bibliography/papers.bib` |
| Talks | `_pages/talks.md` |
| Teaching | `_pages/teaching.md` |
| Service | `_pages/service.md` |
| Name, links, site settings | `_config.yml`, `_data/socials.yml` |

To add a publication, add an entry to `papers.bib`. `abstract`, `code`, `arxiv`, `bibtex_show` and `selected={true}` (shows it on the homepage) are al-folio fields.

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost   # http://localhost:4000
```

## Deployment

Pushing to `master` runs `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch. GitHub Pages serves that branch.
