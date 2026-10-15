# deephoony.github.io

Personal academic website of Chang-Hoon Jeong, a Ph.D. candidate in Computer
Science and Engineering at Seoul National University.

Live at <https://deephoony.github.io>.

## Local preview

```bash
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 8081
```

Then open <http://127.0.0.1:8081>.

Two notes on serving locally:

- `_config.yml` changes are not picked up by the file watcher. Restart the
  server after editing it.
- In development Jekyll overwrites `site.url` with the local server address, so
  asset links become absolute to `localhost`. That is fine on your own machine,
  but if you expose the preview through a tunnel, run it with
  `JEKYLL_ENV=production` so the configured `url` is kept.

## Editing

Everything on the page lives in [`_pages/about.md`](_pages/about.md): the
biography, the section table of contents, the publication list, and the
teaching record. The publication list is hand-written HTML with a small style
block at the top of the file; `*` marks co-second authors and `†` the
corresponding author.

Site-wide settings are in [`_config.yml`](_config.yml).

## Deployment

[`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) builds the site
with Bundler and publishes it to GitHub Pages on every push to `main`. The
built-in Pages Jekyll build is not used, because this site depends on the
al-folio v1 gems, which are outside the set of plugins GitHub Pages supports.

## Credits

Built on [al-folio](https://github.com/alshedivat/al-folio), which is
distributed under the MIT License; see [LICENSE](LICENSE).
