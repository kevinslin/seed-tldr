---
id: common.docker-start
title: Docker Start
desc: ''
updated: 1615655543051
created: 1615655543051
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# docker start

> Start one or more stopped containers.
> More information: <https://docs.docker.com/engine/reference/commandline/start/>.

- Show help:

`docker start`

- Start a docker container:

`docker start {{container}}`

- Start a container, attaching stdout and stderr and forwarding signals:

`docker start --attach {{container}}`

- Start one or more space-separated containers:

`docker start {{container(s)}}`

