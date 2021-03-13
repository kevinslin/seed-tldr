---
id: linux.dos2unix
title: Dos2unix
desc: ''
updated: 1615663978743
created: 1615663978743
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dos2unix

> Change DOS-style line endings to Unix-style.
> Replaces CRLF with CR.

- Change the line endings of a file:

`dos2unix {{filename}}`

- Create a copy with Unix-style line endings:

`dos2unix -n {{filename}} {{new_filename}}`

