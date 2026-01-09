# sn91.github.io

Personal academic website for **Sayyed Neha Firdous**.

## About

Master's student in Computer Science at Clausthal University of Technology, Germany. Software Engineer with experience in DevOps, databases, and LLM research.

## Built With

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [al-folio](https://github.com/alshedivat/al-folio) - Academic theme

## Local Development

### Using Docker (Recommended)

```bash
docker compose pull
docker compose up
```

The site will be available at `http://localhost:8080`.

### Manual Setup

```bash
bundle install
pip install jupyter
bundle exec jekyll serve --lsi
```

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions on push to `master` or `main` branch.

## License

This project uses the [al-folio](https://github.com/alshedivat/al-folio) theme, available under the MIT License.
