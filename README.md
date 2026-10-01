# Node.js CI/CD Demo

## Project Description

This project demonstrates an automated CI/CD pipeline using GitHub Actions.

## Technologies Used

- Node.js
- Express.js
- Docker
- Docker Hub
- GitHub
- GitHub Actions

## CI/CD Workflow

The pipeline performs the following steps:

1. Checkout source code
2. Install Node.js dependencies
3. Run tests
4. Build Docker image
5. Login to Docker Hub
6. Push Docker image to Docker Hub

## Trigger

The pipeline is triggered whenever code is pushed to the main branch.

## Docker Image

The Docker image is published to Docker Hub.

## Result

GitHub Actions automatically tests the application, builds the Docker image, and pushes it to Docker Hub.
