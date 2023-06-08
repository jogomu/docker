# Welcome / Overview

`jogomu` repositories are briefly described here, and generally educational in nature.  Most of them provide Dockerfile image definitions for easily running the examples with docker.  While the provided build scripts (orchestrating `docker build`) are scripted for the `bash` shell, the contents of these scripts can also be explored to accomplish the build in some other way.  Likewise for scripts intended for terminal-based `docker run` exploration of running containers.

See the docker installation pointers below if you are new to docker.  Also some examples or parts of examples may run at web sites like mycompiler.io, and this may be called out in the project when relevant.

* java-bits -- will someday be a broader exploration of Java, not my best language
* ...

# Docker
Docker setup instructions - 2023-06-08

## Mac
### Colima
* install homebrew: https://docs.brew.sh/Installation
* `brew install colima`
* `colima start` or `colima start --edit` to adjust the persistent configuration
* `docker ps` should now work and report no running containers

### Docker Desktop for Mac
https://docs.docker.com/desktop/install/mac-install/

## Windows
https://docs.docker.com/desktop/install/windows-install/

## Linux
...you got this! :)
