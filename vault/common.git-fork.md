---
id: common.git-fork
title: Git Fork
desc: ''
updated: 1642441815024
created: 1642441815024
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git fork

> Fork the given GitHub repo. Like `git clone` but forks first.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-fork>.

- Fork and clone a GitHub repository by its URL:

`git fork {{https://github.com/tldr-pages/tldr}}`

- Fork and clone a GitHub repository by its slug:

`git fork {{tldr-pages/tldr}}`

