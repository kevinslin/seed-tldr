---
id: common.git-prune
title: Git Prune
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
# git prune

> Git command for pruning all unreachable objects from the object database.
> This command is often not used directly but as an internal command that is used by Git gc.
> More information: <https://git-scm.com/docs/git-prune>.

- Report what would be removed by Git prune without removing it:

`git prune --dry-run`

- Prune unreachable objects and display what has been pruned to stdout:

`git prune --verbose`

- Prune unreachable objects while showing progress:

`git prune --progress`

