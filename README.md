# Containers from Scratch

## Setup

- `docker build -t go_ubuntu_container .`
- `sudo docker run --rm -it -v <ABSOLUTE_PATH_TO_REPOSITORY_ROOT>:/go/src/github.com/samyakahuja/containers/ go_ubuntu_container`
- `go run main.go run <CMD> <ARGS>`
