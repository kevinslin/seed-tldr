---
id: common.interdiff
title: Interdiff
desc: ''
updated: 1623965016132
created: 1623965016132
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# interdiff

> Show differences between two diff files.
> More information: <http://freshmeat.sourceforge.net/projects/patchutils>.

- Compare diff files:

`interdiff {{old_file}} {{new_file}}`

- Compare diff files, ignoring whitespace:

`interdiff -w {{old_file}} {{new_file}}`

