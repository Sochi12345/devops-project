# DevOps Project: Livee Node.js App with Docker and CI/CD

A fully live Node.js application deployed on AWS, Dockerized and automatically updated via CI/CD.
This project demonstrates real world Devops skills:containerization, Github integration and automated deployments.

## Features

- Dockerized Node.js application
- AWS EC2 deployment
- Continuous Integration & Deployment (CI/CD) with a deploy script
- Automatic updates on GitHub push

## Tech Stack
- Node.js
- Docker
- GitHub

## How to Run

```bash
docker build -t devops-app .
docker run -p 3000:3000 devops-app

## Screenshots

Live app in browser:

(screenshots/app-Live.png)

Docker container running:

(screenshots/docker-container.png)

Deploy log:

(screenshots/deploy-log.png)


