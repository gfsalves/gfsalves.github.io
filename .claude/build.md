# Build & Environment

## Prerequisites

**macOS:**
```bash
brew install ruby node
gem install bundler
```

**Linux/WSL:**
```bash
sudo apt install ruby-dev ruby-bundler nodejs build-essential gcc make
```

## Install dependencies

```bash
bundle install
```

If you get permission errors:
```bash
bundle config set --local path 'vendor/bundle'
bundle install
```

## Serve locally

```bash
jekyll serve -l -H localhost
# or
bundle exec jekyll serve -l -H localhost
```

Site available at `http://localhost:4000`.

## Using Docker (alternative)

```bash
chmod -R 777 .
docker compose up
```

## Verify the build works

After serving, visit `http://localhost:4000` and confirm the homepage loads with author profile and navigation.

## Notes

- `_config.yml` is NOT hot-reloaded — restart the server after editing it.
- Jekyll plugins: `jekyll-feed`, `jekyll-gist`, `jekyll-paginate`, `jekyll-sitemap`, `jekyll-redirect-from`, `jemoji`.
- The site deploys automatically to GitHub Pages on push to `master`.
