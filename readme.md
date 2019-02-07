# Concourse Service

This repo contains the resources for running a concourse service, including it's pipelines pipelines

This makes use of the following resources:
- https://github.com/concourse/concourse-docker
- https://github.com/telia-oss/github-pr-resource

## Startup

1) docker-compose up
2) Open browser to http://localhost:8080
3) Log in using username: test, password: test
4) Donwload the cli for the `fly` utility
5) Log in with the commandline utility: fly login -t main -c http://localhost:8080 -b
