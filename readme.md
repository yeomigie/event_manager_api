# Event Manager REST API

A FastAPI REST API for user management using PostgreSQL, Docker, and JWT.

## Resolved Issues
- [Enhance Username Validation](#issue-1)
- [Strengthen Password Validation](#issue-2)
- [Bio-Only Profile Update](#issue-3)
- [Profile Picture URL Update](#issue-4)
- [Combined Bio and Picture Update](#issue-5)
- [OAuth Token Fix](#issue-6)

## Docker Hub
- Image: [yeomigie098/event_manager_api](https://hub.docker.com/r/yeomigie098/event-manager-api)

## Reflection
This project deepened my understanding of backend development with FastAPI, SQLAlchemy, and Pydantic. Implementing validation and testing to 90% coverage taught me rigorous quality assurance. Fixing OAuth issues highlighted the need for secure token handling. Git collaboration improved my workflow with branches and PRs, reflecting industry practices. Challenges like async programming and Docker setup required careful documentation reading. This experience equipped me for professional API development and underscored testing’s importance.

## Setup Instructions
- Fork and clone repository.
- Run `docker-compose up --build`.
- Access API at `http://localhost/docs`, PGAdmin at `http://localhost:5050`.
