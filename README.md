# Card Catalog Generator

Static website for CardCatalogGenerator.com.

## Branch Workflow

- `main` is the live production thread. Keep it deployable.
- `draft` is the working thread for drafts, experiments, and content changes before they are promoted.

Use `draft` for new site work, then merge into `main` when the update is ready to publish.

## Project Layout

- `index.html` - main generator page
- `styles.css` - shared site styles
- `blog/` - published article pages and blog index
- `assets/` - site imagery and textures
- `assets/blog/` - article hero/social images
