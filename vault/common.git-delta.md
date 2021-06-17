---
id: common.git-delta
title: Git Delta
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
# git delta

> List files that differ from another branch.
> Part of git-extras.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-delta>.

- List files from the current checked out branch that differ from the `main` branch:

`git delta {{main}}`

- List files from specific branch that differ from another specific branch:

`git delta {{branch_1}} {{branch_2}}`

