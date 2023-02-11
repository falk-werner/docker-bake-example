# Docker buildx bake example

This repository contains an example how to use Docker buildx bake as build system.

## Build

    docker buildx bake

This creates a directoy named `out` will be created, where the build 
results are stored to. This trivial example will only copy a single file
`README.md` to the `out` directory.

## References

- [Docker buildx bake](https://docs.docker.com/engine/reference/commandline/buildx_bake/)
- [Docker bake action](https://github.com/docker/bake-action)
