# Docker Compose Setup for Django Todo App with MySQL and ENV Configuration

# Project Overview:

This project configures a Django-based Todo application to run in Docker containers alongside a MySQL database. It uses Docker Compose with semantic versioning, environment variables for dynamic database configuration, and persistent storage for MySQL.

# Tech stack:

- Docker & Docker Compose
- MySQL
- Python / Django
- Semantic Versioning
- Shell / Environment variables

# What was done:

- Updated docker-compose.yml to:
  - use semantic versioning for images (e.g., todo-app:2.1.0, mysql-db:1.1.0)
  - pass database connection settings via environment variables: (ENGINE, NAME, USER, PASSWORD, HOST, PORT)
- Modified todolist/settings.py to dynamically read environment variables for the DATABASES configuration

