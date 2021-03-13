---
id: osx.stat
title: Stat
desc: ''
updated: 1615663978761
created: 1615663978761
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stat

> Display file status.

- Show file properties such as size, permissions, creation and access dates among others:

`stat {{file}}`

- Same as above but verbose (more similar to linux's `stat`):

`stat -x {{file}}`

- Show only octal file permissions:

`stat -f %Mp%Lp {{file}}`

- Show owner and group of the file:

`stat -f "%Su %Sg" {{file}}`

- Show the size of the file in bytes:

`stat -f "%z %N" {{file}}`

