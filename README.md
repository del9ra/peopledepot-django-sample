## Getting started

1.	Clone the repo: `git clone <repo-url>`, `cd <repo-name>`
2.  Install `uv` on your machine: `curl -LsSf https://astral.sh/uv/install.sh | sh `
3.	Install all project dependencies from pyproject.toml (or exact versions from uv.lock if it exists): `uv sync`
4.	Run database migrations: `uv run python manage.py migrate`
5.	Start the development server: `uv run python manage.py runserver`
6.	Open the app at: `http://127.0.0.1:8000/`
