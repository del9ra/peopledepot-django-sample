## Getting started

1.	Install `uv` on your machine: `curl -LsSf https://astral.sh/uv/install.sh | sh `
2.	Install all project dependencies from pyproject.toml (or exact versions from uv.lock if it exists): `uv sync`
3.	Run database migrations: `uv run python manage.py migrate`
4.	Start the development server: `uv run python manage.py runserver`
5.	Open the app at: `http://127.0.0.1:8000/`
