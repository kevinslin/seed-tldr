---
id: common.cmp
title: Cmp
desc: ''
updated: 1642441815003
created: 1642441815003
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cmp

> Compare two files byte by byte.
> More information: <https://www.gnu.org/software/diffutils/manual/html_node/Invoking-cmp.html>.

- Find the byte and line number of the first difference between two files:

`cmp {{path/to/file1}} {{path/to/file2}}`

- Find the byte number and differing bytes of every difference:

`cmp -l {{path/to/file1}} {{path/to/file2}}`

