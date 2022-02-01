---
id: common.goreload
title: Goreload
desc: ''
updated: 1642441815030
created: 1642441815030
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# goreload

> Live reload utility for Go programs.
> More information: <https://github.com/acoshift/goreload>.

- Set the name of the binary file to watch (defaults to `.goreload`):

`goreload -b {{path/to/binary}} {{file}}.go`

- Set a custom log prefix (defaults to `goreload`):

`goreload --logPrefix {{prefix}} {{file}}.go`

- Reload whenever any file changes:

`goreload --all`

