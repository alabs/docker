# Docker files for Decidim [![CircleCI](https://circleci.com/gh/decidim/docker.svg?style=svg)](https://circleci.com/gh/decidim/docker)

## Docker images for development.

The development image is intended to be in conjunction with docker-compose. This image includes an script that makes feasible to keep ownership of the files created inside the container for for the user used ouside it.

It is convenient, but not absolutelly mandatory that you create a volume for the /gems folder.
