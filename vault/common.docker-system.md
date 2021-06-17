---
id: common.docker-system
title: Docker System
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
# docker system

> Manage Docker data and display system-wide information.
> More information: <https://docs.docker.com/engine/reference/commandline/system/>.

- Show help:

`docker system`

- Show docker disk usage:

`docker system df`

- Show detailed information on disk usage:

`docker system df --verbose`

- Remove unused data:

`docker system prune`

- Remove unused data created more than a specified amount of time in the past:

`docker system prune --filter="until={{hours}}h{{minutes}}m"`

- Display real-time events from the Docker daemon:

`docker system events`

- Display real-time events from containers streamed as valid JSON Lines:

`docker system events --filter 'type=container' --format '{{json .}}'`

- Display system-wide information:

`docker system info`

