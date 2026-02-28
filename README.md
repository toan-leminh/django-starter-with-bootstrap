# Django Starter Project
A production-ready Django starter template designed for learning, rapid development, and real-world deployment.

This project provides a clean architecture, Dockerized environment, MySQL integration, Redis support, and a modular app structure

# Tech Stacks
- Framework: Python Django
- Frontend: HTMX + Bootstrap 
- Database: MySQL
- Cache / Queue Ready: Redis
- Containerized with: Docker

# Purpose
- Learning Django in structured way
- Building production-ready system

# Project Structure
```
django-starter/
│
├── app/        # Configuration (settings, urls, wsgi, asgi)
├── user/       # User-facing pages (authentication, profile, dashboard)
├── admin/      # Admin interface and management pages
├── api/        # REST APIs (third-party integrations)
│
├── docker/     # Docker (MySQL, Redis)
    ├── docker-compose.yml
├── requirements.txt # Library management
└── manage.py
```
# Features
## Core 
- [ ] User authentication
- [ ] Admin authentication
- [ ] Docker composer setup (Redis, MySQL)

# API Layer
- [ ] REST API authentication
- [ ] Sample endpoints

# Testing
- [ ] Basic unit test structure
- [ ] Example test cases

# Setup 
To manually create a virtualenv on MacOS and Linux:

```
$ python3 -m venv .venv
```

After the init process completes and the virtualenv is created, you can use the following
step to activate your virtualenv.

```
$ source .venv/bin/activate
```

If you are a Windows platform, you would activate the virtualenv like this:

```
% .venv\Scripts\activate.bat
```

Once the virtualenv is activated, you can install the required dependencies.

```
$ pip install -r requirements.txt