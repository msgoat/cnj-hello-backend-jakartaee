# cnj-hello-backend-jakartaee

Simplest possible cloud native java application based on Jakarta EE 9.

## Status

![Build status](https://codebuild.eu-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiWWRuMTNQamc0WGV2SWFOeWl3bEx4WWVIK3pYY0U0ZjJzUzY1Smk1VVBwdnFEcXd3Tmd0S080alkrNWlabjNIRWx2RE9FSllEZFFlUFJydFJhNUY0QkdRPSIsIml2UGFyYW1ldGVyU3BlYyI6Ik1hbXdUUGdYaG9XMUJVR1UiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

## Release Information

A changelog can be found in [changelog.md](changelog.md).

## Docker Pull Command

`docker pull docker.cloudtrain.aws.msgoat.eu/cloudtrain/cnj-hello-backend-jakartaee`

## HOW-TO build this application locally

If all prerequisites are met, just run the following Maven command in the project folder:

```shell 
mvn clean verify -P pre-commit-stage
```

Build results: a Docker image containing the showcase application.

## HOW-TO run this showcase locally

In order to run the whole showcase locally, just run the following docker commands in the project folder:

```shell 
docker compose up -d
docker compose logs -f 
```
The showcase application will be accessible via `http://localhost:38080`.

Press `Ctlr+c` to stop tailing the container logs and run the following docker command to stop the show case:

```shell 
docker compose down
```
