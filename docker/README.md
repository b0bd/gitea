# Gitea - Docker

Dockerfile is found in the root of the repository. Docker builds expect to be
run from a working tree (the `.git` directory is mounted during `make`), so
local changes such as patches in this checkout are always used when building
either `Dockerfile` or `Dockerfile.rootless`.

Docker image can be found on [docker hub](https://hub.docker.com/r/gitea/gitea).

Documentation on using docker image can be found on [Gitea Docs site](https://docs.gitea.com/installation/install-with-docker-rootless).
