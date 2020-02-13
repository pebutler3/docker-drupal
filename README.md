# Drupal + Docker
This is to serve as a starting template for Sparkbox Drupal projects.

## Requirements
You should have these installed on your machine before starting the installation instructions.

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/install/) (Should be installed with Docker)

## Installation Instructions
1. Clone this repo
1. `cd` into your new directory
1. Create an `.env` file in the root based on the `.env.example` file
1. Run `./drupal-install.sh` to download, extract, and move drupal to a new drupal directory
1. Run `docker-compose build` to build the project in a docker container
1. Run `docker-compose up` to run the container
1. Navigate to `localhost:8080` and follow installation prompts

**The `Host` is the name of your database (named in .env).**
