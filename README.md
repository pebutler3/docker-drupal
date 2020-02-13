# Drupal + Docker
This is to serve as a starting template for Sparkbox Drupal projects.

## Requirements
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/install/) ( Should be installed with Docker)
- `.env` see `.env.example`

## Installation Instructions
- clone this repo
- cd into your new directory
- `./drupal-install.sh`
- `docker-compose build`
- `docker-compose up`
- Navigate to `localhost:8080` and follow installation prompts.

**The `Host` is the name of your database (Named in .env).**
