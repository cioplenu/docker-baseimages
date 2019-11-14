# FOSSA CLI

This folder contains various dockerfiles for building different environments where we use the [fossa-cli](https://github.com/fossas/fossa-cli) in to analyze our dependencies.
The resulting images are then used in our [concourse-ci](concourse-ci.org) pipelines.
All images should be build automatically by dockerhub and published there under names like [cioplenu/fossa-node](https://hub.docker.com/r/cioplenu/fossa-node).
