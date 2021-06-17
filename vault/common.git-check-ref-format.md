---
id: common.git-check-ref-format
title: Git Check Ref Format
desc: ''
updated: 1623965016126
created: 1623965016126
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git check-ref-format

> Checks if a given refname is acceptable, and exits with a non-zero status if it is not.
> More information: <https://git-scm.com/docs/git-check-ref-format>.

- Check the format of the specified refname:

`git check-ref-format {{refs/head/refname}}`

- Print the name of the last branch checked out:

`git check-ref-format --branch @{-1}`

- Normalize a refname:

`git check-ref-format --normalize {{refs/head/refname}}`

