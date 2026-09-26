# Contributing to GalaxyERP AI Assistant

Thanks for your interest in contributing. Clear, well-scoped contributions are very welcome.

## Project overview

The web app is intentionally simple: a Flask app (`app.py`) serves a single static page
(`templates/index.html`) that includes an embedded Dialogflow Messenger chat widget. There is no
database or server-side business logic, so most changes are to the HTML/CSS/JavaScript in that page.

## Getting set up

1. **Fork** and **clone** the repository.
2. Create and activate a virtual environment, then install dependencies:
   ```bash
   python -m venv .venv
   # Windows: .venv\Scripts\activate
   # Linux/Mac: source .venv/bin/activate
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   python app.py
   ```
   Then open `http://localhost:5000`.

You can also open `templates/index.html` directly in a browser for quick front-end tweaks (the page
is self-contained apart from the chat widget).

## Making changes

1. Create a branch: `git checkout -b fix/short-description`
2. Keep changes focused. One feature or fix per pull request.
3. Test the page in the browser (navigation, FAQ accordion, responsive layout, and the chat bubble).
4. If you change the container, verify it still builds: `docker build -t galaxyerp .`

## Pull requests

1. Push your branch and open a pull request against `main`.
2. Fill in the pull request template: what changed, why, and how you tested it.
3. Link any related issue (for example, `Closes #12`).

For security issues, follow [SECURITY.md](SECURITY.md) instead of opening a public issue.
