---
id: common.cmp
title: Cmp
desc: ''
updated: 1615663978703
created: 1615663978703
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cmp

> Compare two files.

- Find the byte number and line number of the first difference between the files:

`cmp {{file1}} {{file2}}`

- Find the byte number and differing bytes of every difference:

`cmp -l {{file1}} {{file2}}`

