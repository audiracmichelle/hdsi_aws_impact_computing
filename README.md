# HDSI AWS Impact Computing

## Install MkDocs (locally)

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install mkdocs-material
```

## Run the local dev server

```bash
mkdocs serve
```

Open http://127.0.0.1:8000 and edit files under `docs/` — it live reloads.

## Build the static site

```bash
mkdocs build --strict
```

## Deploying to GitHub Pages
- Create a repo with this content.
- Enable "Pages" → **Deploy from a branch** → `gh-pages`.
- Push to `main` — the Action will build and publish.

## Customization
- Edit **mkdocs.yml** (nav, theme, features).
- Put pages under **docs/**.
