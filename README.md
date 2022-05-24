# cnj-hello-backend-jakartaee

Simplest possible cloud native java application based on Jakarta EE 9.

## Status

![Build status](https://drone.cloudtrain.aws.msgoat.eu/api/badges/msgoat/cnj-hello-backend-jakartaee/status.svg)

## Release Information

A changelog can be found in [changelog.md](changelog.md).

## Docker Pull Command

`docker pull docker.cloudtrain.aws.msgoat.eu/cloudtrain/cnj-hello-backend-jakartaee`

## Run this application 

```shell 
docker run --name cnj-hello-backend-jakartaee -p 8080:8080 docker.cloudtrain.aws.msgoat.eu/cloudtrain/cnj-hello-backend-jakartaee
```

## Build this application 

```shell 
mvn clean verify -P pre-commit-stage
```

Build results: a Docker image containing a Payara Full Profile application server plus the deployed application.
