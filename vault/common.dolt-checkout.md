---
id: common.dolt-checkout
title: Dolt Checkout
desc: ''
updated: 1623965016121
created: 1623965016121
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dolt checkout

> Checkout the work tree or tables to a specific branch or commit.
> More information: <https://github.com/dolthub/dolt>.

- Switch to a branch:

`dolt checkout {{branch_name}}`

- Revert unstaged changes to a table:

`dolt checkout {{table}}`

- Create new branch and switch to it:

`dolt checkout -b {{branch_name}}`

- Create new branch based on a specified commit and switch to it:

`dolt checkout -b {{branch_name}} {{commit}}`

