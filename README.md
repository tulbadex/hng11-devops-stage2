# Full-Stack FastAPI and React Template

Welcome to the Full-Stack FastAPI and React template repository. This repository serves as a demo application for interns, showcasing how to set up and run a full-stack application with a FastAPI backend and a ReactJS frontend using ChakraUI.

## Project Structure

The repository is organized into two main directories:

- **frontend**: Contains the ReactJS application.
- **backend**: Contains the FastAPI application and PostgreSQL database integration.

Each directory has its own README file with detailed instructions specific to that part of the application.

## Getting Started

To get started with this template, please follow the instructions in the respective directories:

- [Frontend README](./frontend/README.md)
- [Backend README](./backend/README.md)

## Docker

To run docker containers, you need to download and install Docker Desktop from the [official Docker website](https://www.docker.com/products/docker-desktop).

### Setup Development with Docker

To run the application in development mode, run the following command in the project root directory:

```bash
docker-compose up --build
```

This command will build and run the frontend, backend, and database containers. 
The frontend will be available at: `http://localhost` 
The backend will be available at: `http://localhost/api`, 
with api docs and redocs available at: `http://localhost/docs`,
and `http://localhost/redoc` respectively.
Also, there is an adminer panel available at: `http://adminer.localhost` to view the database, and nginx proxy is available at: `http://proxy.localhost` to manage proxy configurations.

### Setup Production with Docker

The production deployment will serve:

1. The landing page/frontend from [Front end](https://tulbadex.jumpingcrab.com/)
2. The backend API from [Back end](https://tulbadex.jumpingcrab.com/api)
    i.  API docs: [Docs](https://tulbadex.jumpingcrab.com/docs)
    ii. Redoc: [Redoc](https://tulbadex.jumpingcrab.com/redoc)
3. Adminer from [Adminer](https://database.jumpingcrab.com) to view the database.
4. NGINX Manager from [NGINX Manager](https://nginx-manager.jumpingcrab.com) for proxy management configuration.
