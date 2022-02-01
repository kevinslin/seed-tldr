---
id: common.git-sync
title: Git Sync
desc: ''
updated: 1642441815027
created: 1642441815027
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git sync

> Sync local branches with remote branches.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-sync>.

- Sync the current local branch with its remote branch:

`git sync`

- Sync the current local branch with the remote main branch:

`git sync origin main`

- Sync without cleaning untracked files:

`git sync -s {{remote_name}} {{branch_name}}`

