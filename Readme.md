# Node-Redis-Mongo app
This is a node js app for demonstrating how to use redis as cache with node js and mongodb

# Requirements
- node
- redis cache
- mongoDB (local or cloud)

# Installation
```
npm install
```

# Running
In first terminal
```
redis-server
```
In another terminal
```
npm start
``` 
PORT= 3000

docker run -d -p 6379:6379 --name my-redis-container redis
docker run -d -p 27017:27017 --name my-mongo-container mongo
