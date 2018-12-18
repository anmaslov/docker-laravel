# Example docker-compose environment

## Usage

To build and start it

`docker-compose up --build` 

Optional add key -d for startup as daemon

To stop

`docker-compose stop`

Also you can use Makefile, like this:

`make docker-up` or `make docker-down`

To exec command in container run command like this

`docker exec -ti laravel-docker_php-cli_1 sh`