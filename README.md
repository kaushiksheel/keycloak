# Keycloak-React Authentication Example

This project demonstrates how to implement authentication in a React application using Keycloak. It includes a Node.js backend and a React frontend, all containerized with Docker.

## Project Overview

The project consists of three main components:
1. Keycloak server for authentication
2. Node.js backend with protected and public routes
3. React frontend that interacts with Keycloak and the backend

## Prerequisites

Before you begin, ensure you have the following installed:
- Docker and Docker Compose
- Node.js (v14 or later)
- npm (v6 or later)



## Project Overview

This project consists of three main components:
1. Keycloak server for authentication
2. Node.js backend with protected and public routes
3. React frontend that interacts with Keycloak and the backend

The application demonstrates secure authentication flows, token management, and accessing protected resources.



## Commands

### Build and Run Containers

To start the containers, use the following commands:

```bash
# Build the services
docker-compose build

# Start the services
docker-compose up