---
id: osx.yaa
title: Yaa
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
# yaa

> Create and manipulate YAA archives.

- Create an archive from a directory:

`yaa archive -d {{path/to/directory}} -o {{path/to/output.yaa}}`

- Create an archive from a file:

`yaa archive -i {{path/to/file}} -o {{path/to/output.yaa}}`

- Extract an archive to the current directory:

`yaa extract -i {{path/to/archive.yaa}}`

- List the contents of an archive:

`yaa list -i {{path/to/archive.yaa}}`

- Create an archive with a specific compression algorithm:

`yaa archive -a {{algorithm}} -d {{path/to/directory}} -o {{path/to/output.yaa}}`

- Create an archive with an 8MB block size:

`yaa archive -b {{8m}} -d {{path/to/directory}} -o {{path/to/output.yaa}}`

