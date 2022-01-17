---
id: common.git-repack
title: Git Repack
desc: ''
updated: 1642441815026
created: 1642441815026
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git repack

> Pack unpacked objects in a Git repository.
> More information: <https://git-scm.com/docs/git-repack>.

- Pack unpacked objects in the current directory:

`git repack`

- Also remove redundant objects after packing:

`git repack -d`

