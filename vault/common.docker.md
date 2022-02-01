---
id: common.docker
title: Docker
desc: ''
updated: 1642441815010
created: 1642441815010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker

> Manage Docker containers and images.
> Some subcommands such as `docker run` have their own usage documentation.
> More information: <https://docs.docker.com/engine/reference/commandline/cli/>.

- List all docker containers (running and stopped):

`docker ps --all`

- Start a container from an image, with a custom name:

`docker run --name {{container_name}} {{image}}`

- Start or stop an existing container:

`docker {{start|stop}} {{container_name}}`

- Pull an image from a docker registry:

`docker pull {{image}}`

- Display the list of already downloaded images:

`docker images`

- Open a shell inside a running container:

`docker exec -it {{container_name}} {{sh}}`

- Remove a stopped container:

`docker rm {{container_name}}`

- Fetch and follow the logs of a container:

`docker logs -f {{container_name}}`

