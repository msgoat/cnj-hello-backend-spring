# cnj-hello-backend-spring

Simplest possible cloud native java application based on Spring Boot.

## Status

![Build status](https://codebuild.eu-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiMUdQanVuMHNQLzZqTVBlV3p3dXkvOEJvMUJQM3ZzOGlGRVZ0Mk8vWUdaN1grS1NsL0V1SHUyYVIxZ2J6OE1maGVKcWlCdUV1aWZyZHlSWm41Z2txank0PSIsIml2UGFyYW1ldGVyU3BlYyI6ImdYKzA0bm5tNk1oalBheUsiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

## Release Information

A changelog can be found in [changelog.md](changelog.md).

## Docker Pull Command

`docker pull docker.cloudtrain.aws.msgoat.eu/cloudtrain/cnj-hello-backend-spring`

## Run this application 

```shell 
docker run --name cnj-hello-backend-spring -p 8080:8080 docker.cloudtrain.aws.msgoat.eu/cloudtrain/cnj-hello-backend-spring
```

## Build this application

```shell 
mvn clean verify -P pre-commit-stage
```

Build results: a Docker image containing a Spring Boot application.
