---
id: osx.chflags
title: Chflags
desc: ''
updated: 1623965016172
created: 1623965016172
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chflags

> Change file or directory flags.

- Set the `hidden` flag for a file:

`chflags {{hidden}} {{path/to/file}}`

- Unset the `hidden` flag for a file:

`chflags {{nohidden}} {{path/to/file}}`

- Recursively set the `uchg` flag for a directory:

`chflags -R {{uchg}} {{path/to/directory}}`

- Recursively unset the `uchg` flag for a directory:

`chflags -R {{nouchg}} {{path/to/directory}}`

