---
id: common.docker-rmi
title: Docker Rmi
desc: ''
updated: 1615655543051
created: 1615655543051
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

