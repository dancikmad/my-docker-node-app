# My Docker Node App

## Description
`my-docker-node-app` is a simple fullstack application built with **Node.js**, **PostgreSQL**, and **pgAdmin**. This project was created to practice **Docker containerization** and to follow best practices for setting up containers with Docker.

The application is designed to run in a multi-container setup using `docker-compose.yml`. The three containers include:


1. **Node.js App** - The backend server running your application.
2. **PostgreSQL** - The relational database for storing application data.
3. **pgAdmin** - A web-based administration tool for managing PostgreSQL databases.

## Features
- Containerized with **Docker** for easy deployment and isolation.
- **PostgreSQL** as the database and **pgAdmin** for database management.
- Simple fullstack application built with **Node.js**.
- Built using a **Docker Compose** configuration to handle multiple containers.

## Prerequisites
Make sure you have the following installed:

- **Docker** - For creating and managing containers.
- **Docker Compose** - For defining and running multi-container Docker applications.

## Getting Started

### Clone the Repository
First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/my-docker-node-app.git
cd my-docker-node-app
```

### Build and Run the Project
Once the repository is cloned, run the following command to build and start all containers:
```bash
docker-compose up --build
```

### Docker Compose File Overview

The docker-compose.yml file defines the following services:

- **Node.js:** The app's backend server.
- **PostgreSQL:** The database service.
- **pgAdmin:** The web-based UI for managing the PostgreSQL database.