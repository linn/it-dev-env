# Developer environment

This is a repo to hold files required when developing against any of the Linn IT infrastructure. 

##Initialisation

`docker-compose up -d` - Will create everything and run all services

##Stopping

`docker-compose stop` - Will stop all the services, but leave your volumes untouched

##Starting

`docker-compose start` - will start all the services using existing volumes

##Destroying

`docker-compose down` - will stop all the services and destroy all your volumes
