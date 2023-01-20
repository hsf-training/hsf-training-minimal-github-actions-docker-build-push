# hsf-training-minimal-github-actions-docker-build-push

This repository demonstrates how to build and push a Docker image inside a GitHub Action. The relevant yaml file is at [.github/workflows/build-push.yml](.github/workflows/build-push.yml).

Prerequisites are:
- definition of repository secrets: `DOCKERHUB_USERNAME` and `DOCKERHUB_TOKEN`
