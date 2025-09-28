# Jaihyun Park — JAY LAB academic portfolio

Minimal academic portfolio built with Jekyll (Academic Pages theme).

Live site: https://park-jay.github.io/

## Quick start (Docker)

Requires Docker and Docker Compose.

1. From the repository root, build and start the site:

```powershell
docker compose up --build -d
```

2. Open http://localhost:4000 in your browser.

3. Stop the site:

```powershell
docker compose down
```

## Where to edit

- Pages and site content: `_pages/`, `_publications/`, `_research/`, `_teaching/`, `_advising/`, `_service/`
- Site-wide config: `_config.yml`
- Author/profile: `_data/authors.yml` and `author` fields in `_config.yml`
- Static files (images, PDFs): `images/`, `files/`

## Local dev notes

- The repository includes a `Dockerfile` and `docker-compose.yaml` that run Jekyll on port 4000.
- NPM scripts for building/minifying JS live in `package.json` (optional).
- To use the Ruby toolchain locally instead of Docker, run `bundle install` then `bundle exec jekyll serve`.

## Contact

Jaihyun Park — jaipark@iu.edu

## License

MIT — see `LICENSE`.
