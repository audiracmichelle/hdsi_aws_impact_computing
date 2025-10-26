# MkDocs Starter (Material theme)

A minimal MkDocs setup (no notebooks).

## Prereqs
- Python 3.9+

## Local usage
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
mkdocs serve
```

## Deploying to GitHub Pages
- Create a repo with this content.
- Enable "Pages" → **Deploy from a branch** → `gh-pages`.
- Push to `main` — the Action will build and publish.

## Customization
- Edit **mkdocs.yml** (nav, theme, features).
- Put pages under **docs/**.
