Project Overview

This project involves containerizing and deploying a Node.js application from the GitHub repository node-express-server-rest-api. The goal is to demonstrate proficiency in Docker, CI/CD, Kubernetes, and Helm.

Steps Completed

1. Dockerfile and Docker Compose

Created a Dockerfile to containerize the Node.js application.
Configured a docker-compose.yml file to simplify running the application with Docker.

Instructions to Run:

Clone the repository.

git clone 

Build and run the Docker containers using Docker Compose:

docker-compose up --build

2. Continuous Integration (CI)

Set up a CI/CD pipeline to automatically build a Docker image whenever code is pushed to the "main" branch.

Configured the pipeline to push the built image to Docker Hub.

3. Docker Image on Docker Hub

Successfully pushed the Docker image to Docker Hub.

Challenges Faced

Limited experience with Kubernetes and Helm prevented me from completing the deployment.

Lack of familiarity with real-time Helm chart creation and configuration.

Learning Plan

Currently learning Kubernetes and Helm to address knowledge gaps.

Exploring practical resources and tutorials to implement Kubernetes deployments in future projects.
