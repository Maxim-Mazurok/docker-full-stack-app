# Docker Node MongoDB Example

Simple example of a dockerized Node/Mongo app from the Coursera Guided Project: [https://www.coursera.org/projects/containerize-full-stack-nodejs-application-in-docker](Containerize a full-stack NodeJS application in Docker)

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
