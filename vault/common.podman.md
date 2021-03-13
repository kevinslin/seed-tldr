---
id: common.podman
title: Podman
desc: ''
updated: 1615663978730
created: 1615663978730
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# podman

> Simple management tool for pods, containers and images.
> Podman provides a Docker-CLI comparable command line. Simply put: `alias docker=podman`.
> More information: <https://github.com/containers/libpod/blob/master/commands.md>.

- Print out information about containers:

`podman ps`

- List all containers (both running and stopped):

`podman ps --all`

- Start one or more containers:

`podman start {{container_name}} {{container_id}}`

- Stop one or more running containers:

`podman stop {{container_name}} {{container_id}}`

- Pull an image from a registry (defaults to the Docker Hub):

`podman pull {{image_name}}:{{image_tag}}`

- Open a shell inside of an already running container:

`podman exec --interactive --tty {{container_name}} {{sh}}`

- Remove one or more stopped containers:

`podman rm {{container_name}} {{container_id}}`

- Display the logs of one or more containers and follow log output:

`podman logs --follow {{container_name}} {{container_id}}`

