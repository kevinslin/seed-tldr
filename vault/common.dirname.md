---
id: common.dirname
title: Dirname
desc: ''
updated: 1623965016119
created: 1623965016119
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dirname

> Calculates the parent directory of a given file or directory path.
> More information: <https://www.gnu.org/software/coreutils/dirname>.

- Calculate the parent directory of a given path:

`dirname {{path/to/file_or_directory}}`

- Calculate the parent directory of multiple paths:

`dirname {{path/to/file_a}} {{path/to/directory_b}}`

- Delimit output with a NUL character instead of a newline (useful when combining with `xargs`):

`dirname --zero {{path/to/directory_a}} {{path/to/file_b}}`

