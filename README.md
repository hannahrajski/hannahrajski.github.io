# hannahrajski.github.io

Personal academic website for Hannah Rajski, built on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (v1.x, plugin-based).

Live site: https://hannahrajski.github.io

## Local development

```bash
bundle install
bundle exec jekyll serve
```

The site serves at `http://localhost:4000/`.

## Structure

- `_pages/`, `_posts/`, `_projects/`, `_news/` — site content
- `_bibliography/papers.bib` — publications
- `_data/cv.yml`, `assets/json/resume.json` — CV data (RenderCV / JSONResume)
- `_config.yml`, `Gemfile` — site configuration and plugin wiring
- `docs/` — al-folio setup, customization, and troubleshooting guides
- `test/` — integration and style-contract checks

## Documentation

This site is built on the pluginized al-folio v1.x starter; runtime features (layouts, styling, CV rendering, etc.) live in separate `al_folio_*` gems documented in [docs/BOUNDARIES.md](docs/BOUNDARIES.md). For setup, customization, and troubleshooting, see:

- [docs/QUICKSTART.md](docs/QUICKSTART.md)
- [docs/INSTALL.md](docs/INSTALL.md)
- [docs/CUSTOMIZE.md](docs/CUSTOMIZE.md)
- [docs/TROUBLESHOOTING.md](docs/TROUBLESHOOTING.md)
- [docs/FAQ.md](docs/FAQ.md)

## License

Built on [al-folio](https://github.com/alshedivat/al-folio), available under the [MIT License](https://github.com/alshedivat/al-folio/blob/main/LICENSE).
