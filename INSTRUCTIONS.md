# Instructions

## Set Secrets in actions

Go to repository settings and enable secrets.

- Add secrets to your repository by creating the Repository Secrets.
  - DOCKER_USER -> DockerHub username
  - DOCKER_PASSWORD -> DockerHub Access Token
    Under DockerHub, go to Account Settings / Security and generate a new Access Token (I did with Read/Write access).

## DockerHub Repository

Create your repository in DockerHub to store your docker image.

## Add Docker to Actions

In the Github Repository, create a new action using Docker Image (By GitHub Actions) to create a build docker image.

Check .github/workflows/docker-image.yml to see how to build your image.

## Semantic Version

https://github.com/marketplace/actions/git-semantic-version
