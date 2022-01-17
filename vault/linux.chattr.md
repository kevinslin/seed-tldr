---
id: linux.chattr
title: Chattr
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chattr

> Change attributes of files or directories.
> More information: <https://manned.org/chattr>.

- Make a file or directory immutable to changes and deletion, even by superuser:

`chattr +i {{path/to/file_or_directory}}`

- Make a file or directory mutable:

`chattr -i {{path/to/file_or_directory}}`

- Recursively make an entire directory and contents immutable:

`chattr -R +i {{path/to/directory}}`

