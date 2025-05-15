# FastAPI 12-Factor App To-Do

This is a simple To-Do application built with FastAPI demonstrating the [12-Factor App](https://12factor.net/) principles.

## Features

- REST API for managing To-Do tasks
- Uses SQLAlchemy ORM with SQLite database
- Configurable via environment variables (`.env`)
- Dockerized for easy deployment
- Ready for cloud deployment (e.g., Railway)

## Project Structure

- `app/main.py`: FastAPI app entry point
- `app/models.py`: Database models
- `app/schemas.py`: Pydantic schemas for request/response
- `app/crud.py`: CRUD operations for database
- `app/database.py`: Database connection setup
- `.env.example`: Example environment variables file
- `Dockerfile`: Docker setup to containerize app
- `requirements.txt`: Python dependencies

## How to Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/Tulip-Gyawali/fastapi_12factorapp_to_do.git
   cd fastapi_12factorapp_to_do
