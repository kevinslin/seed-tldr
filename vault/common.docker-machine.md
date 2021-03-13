---
id: common.docker-machine
title: Docker Machine
desc: ''
updated: 1615655543051
created: 1615655543051
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# docker-machine

> Create and manage machines running Docker.
> More information: <https://docs.docker.com/machine/reference/>.

- List currently running docker machines:

`docker-machine ls`

- Create a new docker machine with specific name:

`docker-machine create {{name}}`

- Get the status of a machine:

`docker-machine status {{name}}`

- Start a machine:

`docker-machine start {{name}}`

- Stop a machine:

`docker-machine stop {{name}}`

- Inspect information about a machine:

`docker-machine inspect {{name}}`

