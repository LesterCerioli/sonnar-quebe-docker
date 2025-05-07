

# SonarQube Docker Compose Setup

![SonarQube Logo](https://www.sonarqube.org/assets/logo-31ad3115b1b4b120f3d1efd63e6b13ac9f1f89437f0cf6881cc4d8b5603a52b4.svg)

A ready-to-use Docker Compose configuration to run SonarQube locally for code quality analysis.

## Features

- SonarQube Community Edition (latest)
- PostgreSQL database (recommended for production-grade setup)
- Persistent data storage using Docker volumes
- Easy setup with single command

## Prerequisites

- Docker Engine 20.10+
- Docker Compose 2.0+
- 4GB+ RAM available (SonarQube requires at least 3GB)
- 2 CPU cores minimum

## Quick Start

1. Clone this repository:
   ```bash
   git clone https://github.com/LesterCerioli/sonarqube-docker.git
   cd sonarqube-docker
   ```
2. Start the containers:
   ```bash
   docker-compose up -d
   ```

3. Access SonarQube at:
   ```bashbash
   http://localhost:9000
   ```bash

## Configuration

Environment Variables
Edit the .env file to customize:

```bash
   SONARQUBE_VERSION=9.9.4-community
  POSTGRES_VERSION=13
  SONARQUBE_PORT=9000
  ```
