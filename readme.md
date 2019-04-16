# NodeJS microservice with deployment  to Docker


### Stack
 NodeJS service with a MongoDB for our backend.
- NodeJS 7.5.0
- MongoDB 3.4.2
- Docker for Mac 1.13.0

### Microservices

- [Movies Service example] - ./movies-service 
- [Cinema Catalog Service example]- ./cinema-catalog-service
- [Booking Service example] - ./booking-service
- [Payment Service example] - ./payment-service
- [Notification Service example] - ./notification-service
- [API Gateway Service example] -  ./api-gateway 

### How to run the cinema microservice

We need to have docker installed.

```
$ bash < kraken.sh
```

This will:

1. Install every microservice and setup the docker swarm cluster

2. Deploy every docker service in the swarm.

3. monitor the cluster in a graphic mode. Visit the following url: `http://192.168.99.100:9000`

4. Give us the rancherOS web interface.




### Commands

First instal and get the movie services working.

npm install          # setup node dependencies  
npm test             # unit test with mocha  
npm start            # starts the service  
npm run node-debug   # run the server in debug mode 
npm run chrome-debug # debug the node with chrome
npm run lint         # lint the code with standard
