# DevOps Project

This is a simple Node.js application containerized using Docker and prepared for CI/CD deployment.

## Tech Stack
- Node.js
- Docker
- GitHub

## How to Run

```bash
docker build -t devops-app .
docker run -p 3000:3000 devops-app
