# Docker-Images

This repository stores Dockerfiles for generating images hosted on Docker Hub
https://hub.docker.com/r/mathersm

## Images

| linux-common |
|---|
| https://hub.docker.com/r/mathersm/linux-common/ |
| Base = ubuntu:18.04 |
| build-essential |
| cmake |
| git |

| penguin-gcc |
|---|
| https://hub.docker.com/r/mathersm/penguin-gcc |
| Base = mathersm/linux-common |
| g++-8 |
| Penguin |

