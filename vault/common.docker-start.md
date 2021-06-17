---
id: common.docker-start
title: Docker Start
desc: ''
updated: 1623965306180
created: 1623965306180
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

