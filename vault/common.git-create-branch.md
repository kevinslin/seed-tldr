---
id: common.git-create-branch
title: Git Create Branch
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
# git create-branch

> Create a Git branch in a repository.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-create-branch>.

- Create a local branch:

`git create-branch {{branch_name}}`

- Create a branch locally and on origin:

`git create-branch --remote {{branch_name}}`

- Create a branch locally and on upstream (through forks):

`git create-branch --remote upstream {{branch_name}}`

