---
id: osx.mdfind
title: Osx
desc: ''
updated: 1615663978760
created: 1615663978760
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

