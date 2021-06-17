---
id: common.git-update-index
title: Git Update Index
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
# git update-index

> Git command for manipulating the index.
> More information: <https://git-scm.com/docs/git-update-index>.

- Pretend that a modified file is unchanged (`git status` will not show this as changed):

`git update-index --skip-worktree {{path/to/modified_file}}`

