# docker-mongodb

Command to pull mongo docker image:

```
docker pull mongo
```

Command to run to start the docker:

```
docker run -p 27017:27017 -v ~/Workspace/mongodb/db/:/data/db --name my-mongo-dev -d mongo mongod --auth
```
