# To-Do API in FastAPI

Simple To-Do REST API built with FastAPI and Tortoise ORM.

Getting started

1. Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Run the app:

```powershell
python main.py
```

API

- GET `/` — health check
- Routes for managing todos live under `/todos` (see `api/routes/todo.py`).

Notes

- This project uses Tortoise ORM; ensure `sqlite://todo.db` is reachable and `tortoise-orm` is installed.
