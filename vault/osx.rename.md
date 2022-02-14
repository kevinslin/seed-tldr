---
id: osx.rename
title: Rename
desc: ''
updated: 1644840636311
created: 1644840636311
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rename

> Rename a file or group of files with a regular expression.
> More information: <https://www.manpagez.com/man/2/rename/>.

- Replace `from` with `to` in the filenames of the specified files:

`rename 's/{{from}}/{{to}}/' {{*.txt}}`

