---
id: common.git-missing
title: Git Missing
desc: ''
updated: 1642441815025
created: 1642441815025
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git missing

> Show commits which aren't shared between two branches.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-missing>.

- Show commits which aren't shared between the currently checked-out branch and another branch:

`git missing {{branch}}`

- Show commits which aren't shared between two branches:

`git missing {{branch_1}} {{branch_2}}`

