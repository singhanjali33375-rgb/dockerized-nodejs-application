# dockerized-nodejs-application# Dockerized Node.js Application

This project demonstrates how to package a Node.js application into a Docker container for consistent deployment across environments.

## Tech Stack
- Node.js
- Docker

## Steps to Run

docker build -t node-docker-app .
docker run -p 3000:3000 node-docker-app

## Output
Visit http://localhost:3000
Containerized a Node.js application using Docker to ensure consistent runtime, easy deployment, and scalable execution across environments.

Containerized a Node.js application using Docker to enable portable and scalable deployments.
dockerized-nodejs-application/
│
├── app.js
├── package.json
├── Dockerfile
├── .dockerignore
├── README.md
└── .gitignore
