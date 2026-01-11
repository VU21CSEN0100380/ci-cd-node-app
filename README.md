Trigger CI pipeline run

# CI/CD Pipeline for Containerized Node.js Application

This project demonstrates a complete CI/CD pipeline for a containerized Node.js web application using Docker and GitHub Actions.

## 🚀 Project Overview
- Developed a simple Node.js (Express) web application
- Containerized the application using Docker
- Implemented a CI pipeline using GitHub Actions
- Automated build, test, and Docker image push to Docker Hub

## 🛠️ Tech Stack
- Node.js
- Express.js
- Docker
- GitHub Actions
- Git & GitHub

## 🔄 CI/CD Workflow
1. Developer pushes code to the GitHub repository
2. GitHub Actions triggers the CI pipeline
3. Dependencies are installed and tests are executed
4. Docker image is built using a Dockerfile
5. Docker image is pushed to Docker Hub

## 🐳 Docker
The application is containerized using a Dockerfile and `.dockerignore` to optimize image size.

## 📦 GitHub Actions
GitHub Actions is used to automate:
- Dependency installation
- Testing
- Docker image build
- Secure authentication using GitHub Secrets

## 📌 How to Run Locally
```bash
npm install
npm start
