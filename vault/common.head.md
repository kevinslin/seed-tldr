---
id: common.head
title: Head
desc: ''
updated: 1615663978718
created: 1615663978718
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# head

> Output the first part of files.

- Output the first few lines of a file:

`head -n {{count_of_lines}} {{filename}}`

- Output the first few bytes of a file:

`head -c {{size_in_bytes}} {{filename}}`

- Output everything but the last few lines of a file:

`head -n -{{count_of_lines}} {{filename}}`

- Output everything but the last few bytes of a file:

`head -c -{{size_in_bytes}} {{filename}}`

