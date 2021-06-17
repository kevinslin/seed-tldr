---
id: osx.mdfind
title: Osx
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mdfind

> List files matching a given query.

- Find a file by its name:

`mdfind -name {{file}}`

- Find a file by its content:

`mdfind {{query}}`

- Find a file containing a string, in a given directory:

`mdfind -onlyin {{directory}} {{query}}`

