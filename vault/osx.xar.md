---
id: osx.xar
title: Xar
desc: ''
updated: 1623965306236
created: 1623965306236
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

- Lis[t] the contents of a given xar archive:

`xar -tf {{archive.xar}}`

- Extract the contents of a given xar archive to the current directory:

`xar -xf {{archive.xar}}`

