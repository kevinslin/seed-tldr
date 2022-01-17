---
id: common.zmore
title: Zmore
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zmore

> View gzip compressed files with `more`.
> More information: <https://manned.org/zmore>.

- Open a compressed file:

`zmore {{path/to/file.txt.gz}}`

- Display the next page of the file:

`<Space>`

- Search for a pattern in the file (press `n` to go to next match):

`/{{regular_expression}}`

- Exit:

`q`

- Display interactive command help:

`h`

