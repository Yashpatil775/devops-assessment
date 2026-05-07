# DevOps Assessment Project

## Project Overview

This project demonstrates the implementation of a CI/CD pipeline for a Node.js application using GitHub Actions and Docker. The application was developed and deployed in a Linux (CentOS) environment running on VMware.

The project includes:

* Node.js Express application setup
* Automated testing using Jest
* Docker containerization
* GitHub Actions CI/CD pipeline
* Git version control and GitHub integration

---

# Technologies Used

* Node.js
* Express.js
* Jest
* Docker
* Git & GitHub
* GitHub Actions
* CentOS Linux
* VMware Workstation

---

# Application Setup

## Clone Repository

```bash
git clone <repository-url>
```

## Navigate to Project Directory

```bash
cd devops-assessment/app
```

## Install Dependencies

```bash
npm install
```

---

# Running the Application

Start the Node.js application:

```bash
npm start
```

Application runs on:

```bash
http://localhost:3000
```

---

# Running Automated Tests

Execute Jest test cases:

```bash
npm test
```

---

# Docker Setup

## Build Docker Image

```bash
docker build -t devops-app .
```

## Run Docker Container

```bash
docker run -d -p 3000:3000 --name myapp devops-app
```

---

# CI/CD Pipeline

The CI/CD pipeline was implemented using GitHub Actions.

## Pipeline Stages

1. Source Code Checkout
2. Dependency Installation
3. Automated Test Execution
4. Docker Image Build
5. Deployment Validation

The pipeline is automatically triggered on every push to the GitHub repository.

---

# Project Features

* Automated build and testing workflow
* Docker-based containerization
* GitHub Actions pipeline automation
* Linux-based deployment environment
* Version-controlled project repository

---

# Author

Yash Patil
