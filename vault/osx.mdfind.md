---
id: osx.mdfind
title: Osx
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mdfind

> List files matching a given query.
> More information: <https://ss64.com/osx/mdfind.html>.

- Find a file by its name:

`mdfind -name {{file}}`

- Find a file by its content:

`mdfind {{query}}`

- Find a file containing a string, in a given directory:

`mdfind -onlyin {{directory}} {{query}}`

