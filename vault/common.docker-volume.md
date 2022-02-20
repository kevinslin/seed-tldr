---
id: common.docker-volume
title: Docker Volume
desc: ''
updated: 1645347700206
created: 1645347700206
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker volume

> Manage Docker volumes.
> More information: <https://docs.docker.com/engine/reference/commandline/volume/>.

- Create a volume:

`docker volume create {{volume_name}}`

- Create a volume with a specific label:

`docker volume create --label {{label}} {{volume_name}}`

- Create a `tmpfs` volume a size of 100 MiB and an uid of 1000:

`docker volume create --opt {{type}}={{tmpfs}} --opt {{device}}={{tmpfs}} --opt {{o}}={{size=100m,uid=1000}} {{volume_name}}`

- List all volumes:

`docker volume ls`

- Remove a volume:

`docker volume rm {{volume_name}}`

- Display information about a volume:

`docker volume inspect {{volume_name}}`

- Remove all unused local volumes:

`docker volume prune`

- Display help for a subcommand:

`docker volume {{subcommand}} --help`

