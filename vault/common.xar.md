---
id: common.xar
title: Xar
desc: ''
updated: 1642441815083
created: 1642441815083
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xar

> Manage .xar archives.
> More information: <https://manned.org/xar>.

- Create a xar archive of all files in a given directory:

`xar -cf {{archive.xar}} {{path/to/directory}}`

- List the contents of a given xar archive:

`xar -tf {{archive.xar}}`

- Extract the contents of a given xar archive to the current directory:

`xar -xf {{archive.xar}}`

