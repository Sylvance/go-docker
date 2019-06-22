# Go-Docker
[![Build Status](https://travis-ci.com/Sylvance/go-docker.svg?branch=master)](https://travis-ci.com/Sylvance/go-docker)

Go webserver that is built as a docker image, CI done by Travis and continuosly deployed with Heroku.

## Running locally with Docker
- First build it; `docker build -t go-docker:latest .`
- Run it; `docker run --rm -it -p 8080:8080 go-docker:latest`.
- Go to localhost:8080 to see webpage.

## Running locally with Docker-compose
- Run it; `docker-compose up`.
- Go to localhost:8080 to see webpage.

## One-off run to create app
- Run, `heroku apps:create go-docker`.

## Todo
- Improve by following this tutorial https://medium.com/@adigunhammedolalekan/build-and-deploy-a-secure-rest-api-with-go-postgresql-jwt-and-gorm-6fadf3da505b

## Author
Sylvance Kerandi.
