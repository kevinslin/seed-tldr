---
id: linux.unix2mac
title: Unix2mac
desc: ''
updated: 1642441815115
created: 1642441815115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unix2mac

> Change Unix-style line endings to macOS-style.
> Replaces CR with LF.
> More information: <https://waterlan.home.xs4all.nl/dos2unix.html>.

- Change the line endings of a file:

`unix2mac {{filename}}`

- Create a copy with macOS-style line endings:

`unix2mac -n {{filename}} {{new_filename}}`

