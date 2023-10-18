# MS-AdiMunawar-BETest Microservices

Welcome to the MS-AdiMunawar-BETest project, which is a microservices-based project for BE TEST. This project consists of multiple services organized and orchestrated using Docker Compose.

## Prerequisites

Before you can use this project, make sure you have installed the following:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Installation Guide

1. Clone this repository to your computer:

    ```bash
    git clone --recursive https://github.com/AdiMunawar31/ms-adimunawar-betest.git
    ```

    Make sure to use the `--recursive` option to initialize and fetch all submodules.

2. Navigate to the project directory:

    ```bash
    cd ms-adimunawar-betest
    ```

3. Start the services using Docker Compose:

    ```bash
    docker-compose up
    ```

    This will start all the services defined in the `docker-compose.yml` file.

## Configuration

Specific service-level configuration or settings may be required for each service in this project. Be sure to consult the documentation for each service and any required configurations.

## Project Structure

- `adimunawar-betest/`: Submodule directory containing the service.
- `nginx/`: Directory containing Nginx configuration and Dockerfile for proxying and routing services.
- `.gitignore`: Git ignore file to specify files or directories that should not be tracked by Git.
- `.gitsubmodule`: Git submodules configuration file.
- `docker-compose.yml`: Docker Compose file for defining and orchestrating the services in this project.

## Contributions

You are welcome to contribute to this project. Please create your own branch, make changes, and submit a pull request for review. Any contributions are greatly appreciated.

