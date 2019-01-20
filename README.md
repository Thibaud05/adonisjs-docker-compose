# adonisjs-docker-compose
A template for adonisjs + mysql in docker

The docker-compose file use var in the adonisjs `.env`

__Create `.env.docker` file__

__Change host in the `.env.docker` file__
```
HOST=0.0.0.0
```

## Start the environement :
```
docker-compose up
```

## The step:
- npm install
- Copy .env file
- Run migration
- Run node server

## Enter in the nodejs container :
```
docker exec -it appname-nodejs /bin/bash
```
