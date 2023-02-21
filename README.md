# Trustpoint

To run this project, follow the following steps:
- Clone this repo and pull the submodules
- Create `.env` file and copy the contents of `.env.template` file to `.env` file
- Fill all the env variables
- Run the docker compose file using `COMPOSE_DOCKER_CLI_BUILD=1 DOCKER_BUILDKIT=1 DOCKER_DEFAULT_PLATFORM=linux/amd64 docker-compose up`