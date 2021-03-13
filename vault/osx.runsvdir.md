---
id: osx.runsvdir
title: Runsvdir
desc: ''
updated: 1615663978760
created: 1615663978760
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# runsvdir

> Run an entire directory of services.

- Start and manage all services in a directory as the current user:

`runsvdir {{path/to/services}}`

- Start and manage all services in a directory as root:

`sudo runsvdir {{path/to/services}}`

- Start services in separate sessions:

`runsvdir -P {{path/to/services}}`

