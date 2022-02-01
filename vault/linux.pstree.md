---
id: linux.pstree
title: Pstree
desc: ''
updated: 1642441815109
created: 1642441815109
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pstree

> A convenient tool to show running processes as a tree.
> More information: <https://manned.org/pstree>.

- Display a tree of processes:

`pstree`

- Display a tree of processes with PIDs:

`pstree -p`

- Display all process trees rooted at processes owned by specified user:

`pstree {{user}}`

