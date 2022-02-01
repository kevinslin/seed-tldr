---
id: common.head
title: Head
desc: ''
updated: 1642609744898
created: 1642609744898
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
> More information: <https://www.gnu.org/software/coreutils/head>.

- Output the first few lines of a file:

`head --lines {{count}} {{path/to/file}}`

- Output the first few bytes of a file:

`head --bytes {{count}} {{path/to/file}}`

- Output everything but the last few lines of a file:

`head --lines -{{count}} {{path/to/file}}`

- Output everything but the last few bytes of a file:

`head --bytes -{{count}} {{path/to/file}}`

