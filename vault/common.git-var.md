---
id: common.git-var
title: Git Var
desc: ''
updated: 1623965016129
created: 1623965016129
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git var

> Prints a Git logical variable's value.
> See `git config`, which is preferred over `git var`.
> More information: <https://git-scm.com/docs/git-var>.

- Print the value of a Git logical variable:

`git var {{GIT_AUTHOR_IDENT|GIT_COMMITTER_IDENT|GIT_EDITOR|GIT_PAGER}}`

- [l]ist all Git logical variables:

`git var -l`

