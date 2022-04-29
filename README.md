# nuxtjs docker starter
My personal docker setup for any nuxtjs project. For local development or production deployment.

## How to use
- Install Docker compose (https://docs.docker.com/compose/install/)
- Put your nuxtjs project files inside `my_app` folder. Or you can just rename you project directory into `my_app`.
- Switch between `Development mode or Production Mode` in `docker-compose.yml` file.
- run `docker-compose build` to build our main app container.
- and finally, run `docker-compose up` or `docker-compose up -d`.

## NOTES
- You can easily change this compose configuration at `docker-compose.yml`