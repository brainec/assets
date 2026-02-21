# brainec/assets

Static assets (fonts + CSS) served from this GitHub repo.

## CDN (jsDelivr)

This repo can be consumed via jsDelivr’s GitHub endpoint:

- Pinned (recommended for production): `https://cdn.jsdelivr.net/gh/brainec/assets@v0.1.0/css/fonts.css`
- Branch (mutable): `https://cdn.jsdelivr.net/gh/brainec/assets@main/css/fonts.css`

Fonts live in `fonts/` and are referenced by `css/fonts.css`.

## Updating assets

- For asset changes consumed by pinned URLs (`@vX.Y.Z`): create a new tag and update consumers to that tag.
- For docs-only changes (like this README): push to `main` only (no new tag needed).

