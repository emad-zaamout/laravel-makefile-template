
## Course Pack Source Code

Course: https://youtu.be/D4m0fTPw5Vg

Laravel Makefile template for Docker based projects.

Supported make commands:

````
Usage:
  make <target>

Targets:
  help        Print help.
  ps          Show containers.
  build       Build all containers
  start       Start all containers
  fresh       Destroy & recreate all containers
  stop        Stop all containers
  restart     Restart all containers
  destroy     Destroy all containers
  cache       Cache project
  cache-clear  Clear cache
  migrate     Run migration files
  migrate-fresh  Clear database and run all migrations
  npm-install  Install frontend assets
  npm-dev     Compile front assets for dev
  npm-prod    Compile front assets for dev
  logs        Print all docker logs
  logs-php    Print all php container logs
  logs-node   Print all php container logs
  logs-database  Print all php container logs
  ssh-php     SSH inside php container
  ssh-node    SSH inside node container
  ssh-database  SSH inside database container
````