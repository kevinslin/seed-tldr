---
id: common.docker-rmi
title: Docker Rmi
desc: ''
updated: 1615663978706
created: 1615663978706
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker rmi

> Remove one or more Docker images.
> More information: <https://docs.docker.com/engine/reference/commandline/rmi/>.

- Show help:

`docker rmi`

- Remove one or more images given their names:

`docker rmi {{image1 image2 ...}}`

- Force remove an image:

`docker rmi --force {{image}}`

- Remove an image without deleting untagged parents:

`docker rmi --no-prune {{image}}`

