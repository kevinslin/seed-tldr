---
id: linux.xar
title: Xar
desc: ''
updated: 1623965016171
created: 1623965016171
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xar

> Manage .xar archives.

- Create a xar archive of all files in a given directory:

`xar -cf {{archive.xar}} {{path/to/directory}}`

- List the contents of a given xar archive:

`xar -tf {{archive.xar}}`

- Extract the contents of a given xar archive to the current directory:

`xar -xf {{archive.xar}}`

