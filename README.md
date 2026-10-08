# FastAPI To-Do Application

A full-stack web application designed to manage and track daily tasks. 

## Tech Stack
* **Backend:** Python, FastAPI
* **Database:** PostgreSQL, SQLAlchemy (with Alembic for migrations)
* **Frontend:** HTML, CSS, Jinja2 Templates
* **Server:** Uvicorn

## Local Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/thisisthanu/Fullstack_Todo.git](https://github.com/thisisthanu/Fullstack_Todo.git)
   ```
2. Activate your virtual environment.
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start the local server:
   ```bash
   uvicorn main:app --reload
   ```
5. Open your browser and navigate to `http://127.0.0.1:8000`.