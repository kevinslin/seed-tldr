---
id: common.git-reset-file
title: Git Reset File
desc: ''
updated: 1623965016128
created: 1623965016128
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git reset-file

> Revert a file to HEAD or a specific commit.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-reset-file>.

- Reset a file to HEAD:

`git reset-file {{path/to/file}}`

- Reset a file to a specific commit:

`git reset-file {{path/to/file}} {{commit_hash}}`

