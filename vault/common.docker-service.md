---
id: common.docker-service
title: Docker Service
desc: ''
updated: 1623965016121
created: 1623965016121
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker service

> Manage the services on a docker daemon.
> More information: <https://docs.docker.com/engine/reference/commandline/service/>.

- List the services on a docker daemon:

`docker service ls`

- Create a new service:

`docker service create --name {{service_name}} {{image}}:{{tag}}`

- Display detailed information of a space-separated list of services:

`docker service inspect {{service_name|ID}}`

- List the tasks of a space-separated list of services:

`docker service ps {{service_name|ID}}`

- Scale to a specific number of replicas for a space-separated list of services:

`docker service scale {{service_name}}={{count_of_replicas}}`

- Remove a space-separated list of services:

`docker service rm {{service_name|ID}}`

