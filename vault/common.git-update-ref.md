---
id: common.git-update-ref
title: Git Update Ref
desc: ''
updated: 1623965306189
created: 1623965306189
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git update-ref

> Git command for creating, updating, and deleting Git refs.
> More information: <https://git-scm.com/docs/git-update-ref>.

- Delete a ref, useful for soft resetting the first commit:

`git update-ref -d {{HEAD}}`

- Update ref with a message:

`git update-ref -m {{message}} {{HEAD}} {{4e95e05}}`

