# FastAPI Todo Backend

A simple Todo backend API built with FastAPI, PostgreSQL, and Docker.

## Features

- Create, Read, Update, and Delete todos
- PostgreSQL database for persistent storage
- Docker and Docker Compose setup
- RESTful API endpoints

## Requirements

- Docker
- Docker Compose

## Getting Started

1. Clone the repository
2. Run the application:
```bash
docker-compose up --build
```

The API will be available at `http://localhost:8000`

## API Endpoints

- `POST /todos/` - Create a new todo
- `GET /todos/` - List all todos
- `GET /todos/{todo_id}` - Get a specific todo
- `PUT /todos/{todo_id}` - Update a todo
- `DELETE /todos/{todo_id}` - Delete a todo

## API Documentation

Once the application is running, you can access:
- Swagger UI documentation at `http://localhost:8000/docs`
- ReDoc documentation at `http://localhost:8000/redoc` 






To run the application:
Make sure you have Docker and Docker Compose installed
Run docker-compose up --build
The API will be available at http://localhost:8000
You can access the API documentation at:
Swagger UI: http://localhost:8000/docs
ReDoc: http://localhost:8000/redoc
The API supports the following operations:
Create a new todo
List all todos
Get a specific todo
Update a todo
Delete a todo
Each todo item has the following fields:
title (required)
description (optional)
completed (boolean, defaults to false)
created_at (automatically set)
updated_at (automatically updated)
Would you like me to explain any specific part of the implementation or help you test the API?