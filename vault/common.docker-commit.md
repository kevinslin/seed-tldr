---
id: common.docker-commit
title: Docker Commit
desc: ''
updated: 1642441815008
created: 1642441815008
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker commit

> Create a new image from a container’s changes.
> More information: <https://docs.docker.com/engine/reference/commandline/commit/>.

- Create an image from a specific container:

`docker commit {{container}} {{image}}:{{tag}}`

- Apply a `CMD` Dockerfile instruction to the created image:

`docker commit --change="CMD {{command}}" {{container}} {{image}}:{{tag}}`

- Apply an `ENV` Dockerfile instruction to the created image:

`docker commit --change="ENV {{name}}={{value}}" {{container}} {{image}}:{{tag}}`

- Create an image with a specific author in the metadata:

`docker commit --author="{{author}}" {{container}} {{image}}:{{tag}}`

- Create an image with a specific comment in the metadata:

`docker commit --message="{{comment}}" {{container}} {{image}}:{{tag}}`

- Create an image without pausing the container during commit:

`docker commit --pause={{false}} {{container}} {{image}}:{{tag}}`

- Display help:

`docker commit --help`

