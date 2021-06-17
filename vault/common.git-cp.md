---
id: common.git-cp
title: Git Cp
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
# git cp

> Copy an existing file to a new location, preserving history.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-cp>.

- Copy an existing file in a Git repo, staying in the same directory:

`git cp {{file}} {{new_file}}`

- Copy an existing file in a Git repo and place it elsewhere:

`git cp {{path/to/file}} {{path/to/new_file}}`

