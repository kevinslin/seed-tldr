---
id: linux.mac2unix
title: Mac2unix
desc: ''
updated: 1623965306225
created: 1623965306225
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mac2unix

> Change macOS-style line endings to Unix-style.
> Replaces LF with CR.

- Change the line endings of a file:

`mac2unix {{filename}}`

- Create a copy with Unix-style line endings:

`mac2unix -n {{filename}} {{new_filename}}`

