# Node.js TypeScript Docker Starter

## Description

This repository provides a starter template for building Node.js applications with TypeScript in a Docker environment. It allows users to develop and run Node.js applications without the need for local installations by leveraging Docker and Docker Compose. The setup includes hot reload functionality based on Docker volumes, enabling a seamless development experience.

## Prerequisites

- Docker
- docker-compose

## How to Use the Repository

1. Clone the repository:
- `$ git clone https://github.com/qest-cz/nodejs-in-docker-starter.git`
2. Start the Docker environment:
- `$ docker-compose up`

This command will install the necessary `node_modules` and serve the `./src/index.ts` file with hot-reload functionality.

