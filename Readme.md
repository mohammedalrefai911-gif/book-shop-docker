# Book Shop Docker Deployment

This project runs the Book Shop Django application using Docker, Docker Compose, and PostgreSQL.

## Services

- PostgreSQL database
- Django backend application

## Requirements

- Docker
- Docker Compose

## Setup

Create a `.env` file or use the environment variables in `docker-compose.yml`.

Required variables:

```env
SECRET_KEY=your-secret-key-here
POSTGRES_DB=bookshop_db
POSTGRES_USER=bookshop_user
POSTGRES_PASSWORD=your-password-here
ALLOWED_HOSTS=localhost,127.0.0.1