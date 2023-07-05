# cnj-hello-backend-spring

Simplest possible cloud native java application based on Spring Boot.

## Status

![Build status](https://codebuild.eu-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiMUdQanVuMHNQLzZqTVBlV3p3dXkvOEJvMUJQM3ZzOGlGRVZ0Mk8vWUdaN1grS1NsL0V1SHUyYVIxZ2J6OE1maGVKcWlCdUV1aWZyZHlSWm41Z2txank0PSIsIml2UGFyYW1ldGVyU3BlYyI6ImdYKzA0bm5tNk1oalBheUsiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

## Release Information

A changelog can be found in [changelog.md](changelog.md).

## Docker Pull Command

`docker pull docker.cloudtrain.aws.msgoat.eu/cloudtrain/cnj-hello-backend-spring`

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
