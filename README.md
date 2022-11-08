# cnj-hello-backend-jakartaee

Simplest possible cloud native java application based on Jakarta EE 9.

## Status

![Build status](https://codebuild.eu-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiWWRuMTNQamc0WGV2SWFOeWl3bEx4WWVIK3pYY0U0ZjJzUzY1Smk1VVBwdnFEcXd3Tmd0S080alkrNWlabjNIRWx2RE9FSllEZFFlUFJydFJhNUY0QkdRPSIsIml2UGFyYW1ldGVyU3BlYyI6Ik1hbXdUUGdYaG9XMUJVR1UiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

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
