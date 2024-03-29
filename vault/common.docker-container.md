---
id: common.docker-container
title: Docker Container
desc: ''
updated: 1642441815009
created: 1642441815009
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker container

> Manage Docker containers.
> More information: <https://docs.docker.com/engine/reference/commandline/container/>.

- List currently running Docker containers:

`docker container ls`

- Start one or more stopped containers:

`docker container start {{container1_name}} {{container2_name}}`

- Kill one or more running containers:

`docker container kill {{container_name}}`

- Stop one or more running containers:

`docker container stop {{container_name}}`

- Pause all processes within one or more containers:

`docker container pause {{container_name}}`

- Display detailed information on one or more containers:

`docker container inspect {{container_name}}`

- Export a container's filesystem as a tar archive:

`docker container export {{container_name}}`

- Create a new image from a container's changes:

`docker container commit {{container_name}}`

