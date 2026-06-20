# CodeAlpha Docker Web Server

A Dockerized FastAPI-based URL Shortener API.

## Features
- User Authentication
- URL Shortening
- Google OAuth Integration
- REST API Documentation with Swagger UI
- Docker Containerization

## Tech Stack
- Python
- FastAPI
- Docker
- PostgreSQL
- JWT Authentication

## Run with Docker

```bash
docker build -t linkly .
docker run -p 8001:8000 linkly
