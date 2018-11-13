# adonisjs-docker-compose
A template for adonisjs + mysql in docker

The docker-compose file use var in the adonisjs `.env`

__Change host in the `.env` file__
```
HOST=0.0.0.0
```

## Start the environement :
```
docker-compose up
```

## Enter in the nodejs container :
```
docker exec -it appname-nodejs /bin/bash
```
