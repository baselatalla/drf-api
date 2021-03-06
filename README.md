# lab-31:  Django REST Framework & Docker

## Overview

Use Django REST Framework to create an API, then "containerize" it with Docker.

## Feature Tasks and Requirements

- Rebuild a custom version of `Blog API` demo project from scratch.
  - Replace `Blog` and `Post` with your own application and model.
  - Your model must have at least as many fields as demo's model.
  - Your model must have one field that is a foreign key to user.
  - **NOTE**: You are not required to build any templates for this lab.

## Features - Docker

- **NOTE** Refer to the class demo for built out `Dockerfile` and `docker-compose.yml` examples.
- Update `Dockerfile` and `docker-compose.yml` if needed.

## Stretch Goals

- Research using a production server vs. the built in development server.
- Research using postgres instead of sqlite as database.

## Implementation Notes

- You'll need to run a command to convert pyproject.toml dependencies to requirements.txt
  - > poetry export -f requirements.txt -o requirements.txt
- If you get an `allowed host` error examine the bug details and update code as needed.
- When Docker installed and docker files are ready to go then run...
  - $ docker-compose up
- To shut docker down enter `ctrl+c`
- You'll learn a better way soon


### User Acceptance Tests

- Modify provided unit tests in demo to work for your project.

## Time

start: 3:00
end: 5:00

PR : [lab31](https://github.com/baselatalla/drf-api/pull/1)