# Data & Content Locations

## Content directories

| Path | Purpose |
|------|---------|
| `_posts/` | Blog posts (Markdown, filename: `YYYY-MM-DD-title.md`) |
| `_publications/` | Publication entries (one `.md` per paper) |
| `_talks/` | Talk entries (one `.md` per talk) |
| `_pages/` | Static pages (about, CV, etc.) |
| `_portfolio/` | Portfolio items |
| `_teaching/` | Teaching entries |
| `_drafts/` | Draft posts (not published) |
| `draft-posts/` | Additional unpublished drafts |

## Static assets

| Path | Purpose |
|------|---------|
| `images/` | Images used in pages (profile photo: `profile.png`) |
| `files/` | PDFs and downloadable files served at `/files/` |
| `assets/` | CSS, JS, and other theme assets |

## Configuration

| File | Purpose |
|------|---------|
| `_config.yml` | Site-wide config: author info, URL, plugins, collections |
| `_data/` | YAML data files used by templates |
| `_includes/` | Reusable HTML snippets |
| `_layouts/` | Page layout templates |
| `_sass/` | SCSS stylesheets |

## Markdown generator

The `markdown_generator/` folder contains Jupyter notebooks and Python scripts to generate `_publications/` and `_talks/` Markdown files from TSV spreadsheets. Useful for bulk importing publication data.

## Talk map

`talkmap.py` and `talkmap.ipynb` generate an interactive map of talk locations. Output goes to `talkmap_out.ipynb` and related files.
