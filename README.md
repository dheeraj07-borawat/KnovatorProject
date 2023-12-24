# KnovatorProject
# Dockerized Node.js and React with Nginx Reverse Proxy

This project demonstrates how to use Docker Compose to set up a development environment with Node.js and React applications, both served behind an Nginx reverse proxy.

## Prerequisites

- [Docker](https://www.docker.com/) installed on your machine

## Project Structure


- **node-app:** Contains the Node.js application.
- **react-app:** Contains the React application.
- **nginx:** Contains the Nginx configuration file.

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/dheeraj07-borawat/KnovatorProject.git
----docker-compose up --build

Configuration
node-app: The Node.js app runs on port 5000.
react-app: The React app runs on port 3000.
nginx-proxy: Nginx serves as a reverse proxy on port 80, forwarding requests to the Node.js and React apps.
Customizing Applications
Modify the Node.js app in node-app/app.js.
Modify the React app in react-app/src.

