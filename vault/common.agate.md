---
id: common.agate
title: Agate
desc: ''
updated: 1642441814992
created: 1642441814992
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# agate

> A simple server for the Gemini network protocol.
> More information: <https://github.com/mbrubeck/agate>.

- Run and generate a private key and certificate:

`agate --content {{path/to/content/}} --addr {{[::]:1965}} --addr {{0.0.0.0:1965}} --hostname {{example.com}} --lang {{en-US}}`

- Run server:

`agate {{path/to/file}}`

- Display help:

`agate -h`

