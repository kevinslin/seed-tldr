---
id: osx.ditto
title: Ditto
desc: ''
updated: 1615663978759
created: 1615663978759
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ditto

> Copy files and directories.

- Overwrite contents of destination directory with contents of source directory:

`ditto {{path/to/source}} {{path/to/destination}}`

- Print a line to the Terminal window for every file that's being copied:

`ditto -V {{path/to/source}} {{path/to/destination}}`

- Copy a given file or directory, while retaining the original file permissions:

`ditto -rsrc {{path/to/source}} {{path/to/destination}}`

