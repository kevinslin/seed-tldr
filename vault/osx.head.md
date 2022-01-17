---
id: osx.head
title: Head
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# head

> Output the first part of files.
> More information: <https://ss64.com/osx/head.html>.

- Output the first few lines of a file:

`head -n {{count_of_lines}} {{filename}}`

- Output the first few bytes of a file:

`head -c {{number_in_bytes}} {{filename}}`

