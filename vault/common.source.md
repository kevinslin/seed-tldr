---
id: common.source
title: Source
desc: ''
updated: 1642441815069
created: 1642441815069
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# source

> Execute commands from a file in the current shell.
> More information: <https://manned.org/source>.

- Evaluate contents of a given file:

`source {{path/to/file}}`

- Evaluate contents of a given file (alternatively replacing `source` with `.`):

`. {{path/to/file}}`

