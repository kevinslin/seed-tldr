---
id: common.git-ls-files
title: Git Ls Files
desc: ''
updated: 1623965016127
created: 1623965016127
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git ls-files

> Show information about files in the index and the working tree.
> More information: <https://git-scm.com/docs/git-ls-files>.

- Show deleted files:

`git ls-files --deleted`

- Show modified and deleted files:

`git ls-files --modified`

- Show ignored and untracked files:

`git ls-files --others`

