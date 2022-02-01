---
id: osx.split
title: Split
desc: ''
updated: 1642441815123
created: 1642441815123
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# split

> Split a file into pieces.

- Split a file, each split having 10 lines (except the last split):

`split -l {{10}} {{filename}}`

- Split a file by a regular expression. The matching line will be the first line of the next output file:

`split -p {{cat|^[dh]og}} {{filename}}`

- Split a file with 512 bytes in each split (except the last split; use 512k for kilobytes and 512m for megabytes):

`split -b {{512}} {{filename}}`

