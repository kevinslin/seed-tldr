---
id: common.join
title: Join
desc: ''
updated: 1623965016133
created: 1623965016133
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# join

> Join lines of two sorted files on a common field.
> More information: <https://www.gnu.org/software/coreutils/join>.

- Join two files on the first (default) field:

`join {{file1}} {{file2}}`

- Join two files using a comma (instead of a space) as the field separator:

`join -t {{','}} {{file1}} {{file2}}`

- Join field3 of file1 with field1 of file2:

`join -1 {{3}} -2 {{1}} {{file1}} {{file2}}`

- Produce a line for each unpairable line for file1:

`join -a {{1}} {{file1}} {{file2}}`

