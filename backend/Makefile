install:
	uv sync

makemigrations:
	uv run manage.py makemigrations

migrate:
	uv run manage.py migrate

lint:
	uv run ruff check

test:
	uv run manage.py test

shell:
	uv run manage.py shell

start:
	uv run python manage.py runserver
