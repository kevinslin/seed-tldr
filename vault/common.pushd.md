---
id: common.pushd
title: Pushd
desc: ''
updated: 1623965306206
created: 1623965306206
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pushd

> Place a directory on a stack so it can be accessed later.
> See also `popd` to switch back to original directory and `dirs` to display directory stack contents.

- Switch to directory and push it on the stack:

`pushd {{directory}}`

- Switch first and second directories on the stack:

`pushd`

- Rotate stack by making the 5th element the top of the stack:

`pushd +4`

