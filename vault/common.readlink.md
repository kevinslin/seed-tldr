---
id: common.readlink
title: Readlink
desc: ''
updated: 1615663978732
created: 1615663978732
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# readlink

> Follow symlinks and get symlink information.

- Get the actual file to which the symlink points:

`readlink {{filename}}`

- Get the absolute path to a file:

`readlink -f {{filename}}`

