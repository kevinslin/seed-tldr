---
id: common.dvc-checkout
title: Dvc Checkout
desc: ''
updated: 1615663978707
created: 1615663978707
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dvc checkout

> Checkout data files and directories from cache.
> More information: <https://dvc.org/doc/command-reference/checkout>.

- Checkout the latest version of all target files and directories:

`dvc checkout`

- Checkout to latest version of a specified target:

`dvc checkout {{target}}`

- Checkout a specific version of a target from a different Git commit/tag/branch:

`git checkout {{commit_hash|tag|branch}} {{target}} && dvc checkout {{target}}`

