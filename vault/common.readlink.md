---
id: common.readlink
title: Readlink
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# readlink

> Follow symlinks and get symlink information.
> More information: <https://www.gnu.org/software/coreutils/readlink>.

- Get the actual file to which the symlink points:

`readlink {{filename}}`

- Get the absolute path to a file:

`readlink -f {{filename}}`

