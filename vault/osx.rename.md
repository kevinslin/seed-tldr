---
id: osx.rename
title: Rename
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rename

> Rename a file or group of files with a regular expression.

- Replace `from` with `to` in the filenames of the specified files:

`rename 's/{{from}}/{{to}}/' {{*.txt}}`

