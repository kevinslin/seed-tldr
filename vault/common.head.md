---
id: common.head
title: Head
desc: ''
updated: 1623965016131
created: 1623965016131
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# head

> Output the first part of files.
> More information: <https://www.gnu.org/software/coreutils/head>.

- Output the first few lines of a file:

`head -n {{count_of_lines}} {{filename}}`

- Output the first few bytes of a file:

`head -c {{size_in_bytes}} {{filename}}`

- Output everything but the last few lines of a file:

`head -n -{{count_of_lines}} {{filename}}`

- Output everything but the last few bytes of a file:

`head -c -{{size_in_bytes}} {{filename}}`

