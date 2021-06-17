---
id: common.pre-commit
title: Pre Commit
desc: ''
updated: 1623965306205
created: 1623965306205
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pre-commit

> Create Git hooks that get run before a commit.
> More information: <https://pre-commit.com>.

- Install pre-commit into your Git hooks:

`pre-commit install`

- Run pre-commit hooks on all staged files:

`pre-commit run`

- Run pre-commit hooks on all files, staged or unstaged:

`pre-commit run --all-files`

- Clean pre-commit cache:

`pre-commit clean`

