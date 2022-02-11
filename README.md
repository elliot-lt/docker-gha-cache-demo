# docker-gha-cache-demo

Demo repository to show use of a local docker registry and GitHub Action caching to speed up container builds between runs and jobs *and* make the resulting image available for use in the normal docker command for executing tests.

All the interesting stuff is in the [docker.yml](./github/workflows/docker.yml) action.
