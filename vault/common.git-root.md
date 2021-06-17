---
id: common.git-root
title: Git Root
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
# git root

> Print the root directory of the current Git repository.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-root>.

- Print the absolute path of the current Git repository:

`git root`

- Print the current working directory relative to the root of the current Git repository:

`git root --relative`

